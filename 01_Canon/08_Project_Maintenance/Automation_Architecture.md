# Automation Architecture (Design Only)

## Purpose

Design future automation that reduces production effort **without** inventing
canon or skipping human hard gates.

**Do not implement tooling in this pass.**

Status: Architecture proposal · 2026-07-15

---

## Principles

1. Automation assembles and validates — humans approve hard gates.
2. Canonical facts stay in markdown / approved refs; tools read, never silently rewrite canon.
3. Prefer packet builders over “chat the whole bible.”
4. Fail closed: missing lock → `HOLD`, not best-guess generate.
5. Every automated write uses Naming Standards (`r##`, status tokens).

---

## Target workloads

| Workload | Today | Automation | Human still owns |
| --- | --- | --- | --- |
| Prompt assembly | Manual module checklist | Build clip prompt from shot row + module IDs | Still approval |
| Reference assignment | Manual M-61 | Map cast/location IDs → approved PNG roles | Override attachments |
| Scene continuity validation | Manual ledger | Diff adjacent shots (wardrobe, light, geography) | Interpret story exceptions |
| Character lock validation | Manual QA | Checklist against Appearance + refs | Reject attractive drift |
| Location lock validation | Manual QA | Compass / adjacency / materials checks | Story weather exceptions |
| Production checklists | Copy templates | Pre-fill episode Admin pack from Episode ID | Gate decisions |
| Episode generation pipeline | Manual phased paste | Queue: image-only → wait approve → anim+audio | Approvals |
| File naming | Manual | Suggest names; block illegal tokens | Confirm |
| Version management | Manual | Bump `r##` on approve; supersede prior | Status semantics |
| Quality scoring | Manual forms | Stub scorecard from gate type | Score evidence judgment |

---

## Proposed system shape

```text
                    ┌─────────────────────┐
                    │  Canon / World /    │
                    │  Characters / Objs  │  (read-only sources)
                    └─────────┬───────────┘
                              │
                    ┌─────────▼───────────┐
                    │  Source Packet      │
                    │  Builder            │
                    └─────────┬───────────┘
                              │
         ┌────────────────────┼────────────────────┐
         ▼                    ▼                    ▼
   Shot Ledger          Prompt Assembler     Checklist Filler
   Validator            (Clip Formula)       (11_Templates)
         │                    │                    │
         └────────────────────┼────────────────────┘
                              ▼
                    ┌─────────────────────┐
                    │  Gate UI / Log      │
                    │  pass · hold · rework│
                    └─────────┬───────────┘
                              │
                    ┌─────────▼───────────┐
                    │  Export to Flow /   │
                    │  episode folders    │
                    └─────────────────────┘
```

---

## Components (logical)

### 1. Source Packet Builder

**Input:** Episode ID, shot ID, cast list, location ID, object IDs.  
**Output:** Markdown or JSON packet of paths + extracted lock fields (not whole files).  
**Reads:** Character Appearance, Location bible, Object files, Style lock snippets.  
**Never writes** canon.

### 2. Prompt Assembler

**Input:** Packet + Storyboard shot row + Clip Formula template.  
**Output:** Filled Image / Animation / Audio prompts into `04_Generation/`.  
**Uses:** `07_Prompt_Modules.md` IDs as required section checklist.  
**Phased:** emits image prompt only until status=`still_approved`.

### 3. Continuity Diff

**Input:** Scene-state ledger table.  
**Output:** Warnings (light direction flip, wardrobe change unexplained, prop count).  
**Escalation:** `HOLD FOR BOARD` if unexplained.

### 4. Lock Validators

Separate checkers: Character, Location, Object, Style, Camera crop.  
Each returns hard-gate fail vs soft warn.  
Align dimensions with Quality Score System.

### 5. Naming / Version Guard

Pre-commit or save hook: reject `final`, `latest`, spaces, missing `r##`.  
Suggest next revision on approve.

### 6. Checklist Prefill

Copy `11_Templates/*` into `10_Episodes/ep_XXX/` with Episode ID filled.  
Does not mark gates Pass.

### 7. Lessons Intake Helper

From rejected prompts / QA notes → draft `LL-EP###` stub for human polish → optional category register row.

---

## Data contracts (minimal)

```text
ShotRecord {
  episode_id, shot_id, scene_id,
  location_id, cast[], objects[],
  lighting_family, light_direction,
  season, weather, aspect,
  status, revision
}

Packet {
  shot_id,
  sources: [{path, role}],
  locks: { character[], location, objects[], style },
  modules_required: [M-..]
}
```

Store contracts beside automation later — not in Canon.

---

## Safety / non-goals

- No auto-canon edits
- No auto-publish to YouTube
- No silent Flow submission without still approval
- No scraping Inspiration Library into story without human pick
- No scoring “beauty” as Pass

---

## Suggested build order (future)

1. Naming guard + episode folder prefill from templates  
2. Source Packet Builder for ep_001 shot list  
3. Continuity Diff on ledger  
4. Prompt Assembler (image phase)  
5. Lock validators wired to Prompt QA  
6. Flow queue helper  
7. Lessons stubber  

---

## Success measure

Time from approved shot list → first valid image prompt packet drops without
reducing hard-gate catch rate.

Related: `Duplication_Map.md` · `11_Templates/` · `09_AI_Production_System/17_Episode_Generation_Pipeline.md`
