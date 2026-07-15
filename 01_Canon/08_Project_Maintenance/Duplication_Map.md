# Duplication Map (Source of Truth Register)

## Purpose

Identify duplicated topics across the Production Bible.

**Do not delete duplicate prose automatically.**  
Point producers to one canonical owner; other documents should cross-reference.

Status: Active maintainability register · Updated 2026-07-15

---

## How to use

| Situation | Action |
| --- | --- |
| Writing new content | Check this map first |
| Updating a rule | Edit the **Canonical source** only |
| Secondary docs | One-line pointer + link; no re-authoring of the rule |
| Conflict found | Escalate; do not “fix” by editing the secondary copy alone |

---

## Topic → Canonical source

| Topic | Canonical source | Secondary / satellite (should reference, not redefine) | Notes |
| --- | --- | --- | --- |
| Project mission / emotional promise | `00_Project_Core/Project Vision.md` | Style Lock Storytelling Identity; Story Philosophy intro | Vision owns “why”; Story Engine owns “how to write” |
| End-to-end pipeline stages | `00_Project_Core/Production Pipeline.md` | `08_Production/*` workflows; `09_…/17_Episode_Generation_Pipeline.md` | Core = map; Production = human steps; AI = generation assembly |
| Instruction / conflict priority | `01_Canon/04_Instruction_Priority.md` | Studio Standards README; AI README; Master Cursor Command | Keep one stack wording |
| Art / rendering style | `01_Canon/01_Series_Style_Lock/Art_Style.md` | Style Lock System; Clip Formula STYLE; Master Image Prompt; character Appearance intros | Official phrase: Studio Ghibli-inspired… |
| Color language | `01_Canon/01_Series_Style_Lock/Color_Language.md` + `Color_And_Lighting_Formula.md` | Character_Color_And_Light_Reference; Clip Formula color line | Formula owns promptable color block |
| Lighting families | `01_Canon/01_Series_Style_Lock/Lighting_Style.md` | Location light notes; M-21; Time_Of_Day | |
| Camera framing / direction | `09_AI_Production_System/19_Camera_Direction_Bible.md` | Camera Lock System; Style Lock Camera_Language; Location camera notes | Direction Bible sole for framing |
| Camera motion | `09_AI_Production_System/20_Camera_Movement_Bible.md` | Animation workflows; Flow practices | Movement Bible sole for motion |
| Story philosophy / formula | `06_Story_Engine/01_Story_Philosophy.md` + `04_Episode_Formula.md` | Episode Philosophy; Storytelling Identity | Engine owns construction; Episode owns viewer form |
| Conflict / emotion / pacing (story) | `06_Story_Engine/05–07` | Episode System pacing/openings | Episode System adapts for format, does not redefine conflict types |
| ASMR | `06_Story_Engine/14_ASMR_Storytelling.md` | `07_…/09_ASMR_Placement.md`; Music/SFX workflow | Engine = meaning; Episode = placement; Production = mix |
| Forbidden story patterns | `06_Story_Engine/18_Forbidden_Story_Patterns.md` | Episode checklists; Prompt QA dignity checks | |
| Episode checklist (viewer gates) | `07_Episode_System/14_Episode_Checklist.md` | `11_Templates/Episode_Checklist.md` | Template = working copy |
| Production checklist (build gates) | `08_Production/18_Project_Checklist.md` | `11_Templates/Production_Checklist.md` | Template = working copy |
| Clip prompt shape | `09_AI_Production_System/21_Clip_Prompt_Formula.md` | Image/Animation templates; Master prompts | Formula mandatory |
| Prompt modules catalog | `09_AI_Production_System/07_Prompt_Modules.md` | Master prompts (assemble modules, don’t fork list) | |
| Character locks | `09_AI_Production_System/08_Character_Lock_System.md` | Character Appearance files (identity facts); Relative Height | Lock system = production enforcement; Appearance = identity truth |
| Location locks | `09_AI_Production_System/09_Location_Lock_System.md` | Location bibles; Master Map | Map = geography authority |
| Village geography | `02_World/Geography/Village_Master_Map.md` | Orientation; Walking_Routes; Landmarks | Map highest for placement |
| Naming grammar | `10_Studio_Standards/Naming_Standards.md` | Asset_Naming; Prompt_Naming; Production file org | |
| Version / status language | `10_Studio_Standards/Version_Control.md` | `08_Production/17_Version_Control.md` | Standards = governance; Production = execution habits — prefer Standards wording for status tokens |
| Quality scoring | `10_Studio_Standards/Quality_Score_System.md` | `08_Production/14_Quality_Control.md`; Prompt QA | Score math vs gate operation |
| Canon change | `10_Studio_Standards/Canon_Change_Process.md` | Lessons Future_Recommendations | |
| Common AI failures | `09_AI_Production_System/15_Common_Failures.md` | Lessons Categories/Prompt_Failures | Failures = catalog; Lessons = evidence feed |

---

## Known intentional overlaps (keep, but don’t fork)

1. **Pipeline thrice** — Core overview / Production workflows / AI generation pipeline. Keep all three; each owns a layer. Add “Authority” one-liners at top of secondary docs pointing up.
2. **ASMR thrice** — Story meaning / Episode placement / Mix workflow. Same split.
3. **Camera multi-doc** — Acceptable if Direction vs Movement remain sole operational authorities.
4. **Checklists vs Templates** — Manuals define rules; `11_Templates/` holds fillable copies.

---

## Recommended next maintenance (not done in this pass)

- Add a one-line **Canonical owner** callout at the top of each major satellite doc.
- Stop expanding satellite prose when Core/Canon/Engine already states the rule.
- After two more episodes, revisit Version_Control dual manuals for a clearer “governance vs execution” split sentence in both.

## Related

- `Folder_Migration_Plan.md` (numbering / index drift)
- `Style_Consistency_Decision.md` (Ghibli lock language)
- `Automation_Architecture.md` (reduce copy risk via packets)
