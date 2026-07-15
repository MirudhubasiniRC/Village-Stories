# Folder Migration Plan

## Purpose

Record current top-level numbering issues and the approved path to fix them
without breaking production mid-episode.

**Do not rename folders casually.** Folder Standards preserve established
top-level names until an approved migration runs.

Status: Plan only · 2026-07-15 · No renames executed in this pass except creation of missing `11_Templates/`.

---

## Current top-level reality

| Path | Role | Numbering note |
| --- | --- | --- |
| `00_Project_Core/` | Charter | OK |
| `01_Canon/` | Laws | OK |
| `02_World/` | World + **Locations** | OK (Locations live here) |
| `03_Characters/` | Characters | OK |
| `04_Objects/` | Objects | OK |
| `05_Research/` | Research | OK |
| `06_Story_Engine/` | Story | OK |
| `07_Episode_System/` | Episode form | OK |
| `08_Production/` | Workflows | OK |
| `09_AI_Production_System/` | AI / Flow | OK |
| `10_Episodes/` | Episode packages | **Collides with 10_Studio_Standards** |
| `10_Studio_Standards/` | Governance | **Collides with 10_Episodes** |
| `11_Assets/` | Visual refs | **Collides with 11_Templates** |
| `11_Templates/` | Working forms | **Created 2026-07-15; collides with 11_Assets** |
| `12_Lessons_Learned/` | Lessons | **Collides with 12_Quality_Assurance** |
| `12_Quality_Assurance/` | Empty | **Collides; QA lives in Standards + Production** |
| `Archive/` | Parking | OK |

---

## Stale navigation (fix in place)

| Document | Problem | Fix |
| --- | --- | --- |
| `00_Project_Core/Master Index.md` | Still lists `04_Locations`, `05_Objects`, `06_Culture` as top-level; missing many current folders | Rewrite to current layout (this pass) |
| `00_Project_Core/README.md` | Missing `11_Templates`; dual 10/12 noted weakly | Add Templates; note dual numbers |
| `MASTER_CURSOR_COMMAND.md` | Roadmap lists 09–12 as “remaining”; several already exist | Update roadmap to maintenance mode |
| `10_Studio_Standards/Folder_Standards.md` | Ownership list skips `10_Episodes`, `11_Templates`, `12_*` | Patch ownership list (this pass) |
| `02_World/Geography/Landmarks.md` | Points to missing `Water_Well.md` | Resolved — file created |

---

## Recommended future numbering (optional migration)

Only run if Creative Director schedules a quiet maintenance window (no open Flow batches).

### Option A — Minimal (preferred)

Keep dual numbers permanently but **document them as intentional aliases**:

```text
10_Episodes/           episode packages
10_Studio_Standards/   governance
11_Assets/             reusable media
11_Templates/          fillable forms
12_Lessons_Learned/    evidence
12_Quality_Assurance/  RETIRE → redirect into Standards QC + empty folder removed or ARCHIVE
```

Pros: no mass link rewrite.  
Cons: slightly ugly paths forever.

### Option B — Clean renumber (higher cost)

```text
10_Studio_Standards/
11_Episodes/                 (rename from 10_Episodes)
12_Assets/                   (rename from 11_Assets)
13_Templates/                (rename from 11_Templates)
14_Lessons_Learned/          (rename from 12_Lessons_Learned)
```

Retire empty `12_Quality_Assurance/` into Archive with a pointer README.

Requires repo-wide path update in all markdown links + ep_001 paths.

---

## Decision for now

1. **No renames this pass.**
2. Fix **indexes and ownership lists** so humans/AI stop looking for dead folders.
3. Retire empty QA folder behaviorally: QA authority remains Quality Score + Production QC + Prompt QA; empty `12_Quality_Assurance/` gets a pointer README (this pass).
4. Revisit Option B after `ep_001` first release if path confusion still costs time.

---

## Migration checklist (if Option B ever runs)

- [ ] Freeze open generations
- [ ] `git mv` folders
- [ ] Bulk update path strings
- [ ] Update Master Index, Folder Standards, Master Cursor Command
- [ ] Smoke-test ep_001 links
- [ ] Record lesson in Categories/Workflow_Improvements.md
