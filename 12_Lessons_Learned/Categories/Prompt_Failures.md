# Prompt Failures

Evidence register for repeatable image/script/voice prompt defects.

Authority support: `09_AI_Production_System/14_Prompt_QA.md` · `15_Common_Failures.md`

| ID | Date | Source | Stage | Summary | Recommendation | Policy status |
| --- | --- | --- | --- | --- | --- | --- |
| LL-CAT-PRM-01 | 2026-07-15 | LL-EP002-01 | image | Prompt omitted open-neighbourhood lock → Flow adds compound walls | Paste Village Neighbourhood openness block on every outdoor house-edge prompt | observe |

## Open patterns to watch

- Gaze / eyeline not repeated in ACTION + NEGATIVE
- Style lock omitted → generic anime drift
- Character lock incomplete (wardrobe/state carryover)
- Location geography flipped
- Module checklist skipped under time pressure
- **Outdoor prompts missing “no compound wall / open neighbour houses + greens”**
