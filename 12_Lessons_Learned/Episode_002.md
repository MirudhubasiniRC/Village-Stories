# Episode 002 — Lessons Learned

| Field | Value |
| --- | --- |
| Episode ID | `ep_002` |
| Episode title | Kesari Afternoon |
| Format | Long-form · 16:9 · ~4–5 min |
| Status | in production · Phase 5 stills |
| Lesson owner | Creative Director |
| Last updated | 2026-07-15 (LL-EP002-02 · LL-EP002-03) |
| Release ID | — |

---

## Episode Close Summary

Not yet released.

---

## Lessons

### LL-EP002-01

**Date:** 2026-07-15  
**Stage:** image  
**Type:** defect / continuity  
**Severity:** medium (recurring)

**What happened:**  
Front Thinnai / house stills for sh_002 repeatedly generate **closed compound walls** or isolated house boxes, instead of an **open neighbourhood** with neighbour roofs, thinnais, and greens readable beyond the family house — same drift pattern as Ep1 outdoor work.

**Evidence:**  
Multiple sh_002 candidates; Front Thinnai generating as a sealed private compound rather than village-edge open front.

**Root cause:**  
Prompts emphasize house architecture (pillars/door) without an explicit **open neighbourhood / no compound wall** lock. Flow fills empty background with walls.

**Corrective action taken:**  
Add mandatory environment lock to sh_002+ outdoor prompts: neighbour houses with greens · Main Village Path / Front Garden air · **NO large compound walls**. Authority: `Village_Neighbourhood.md` Continuity Rules.

**Recommendation for future episodes:**  
Every outdoor house-edge / Front Thinnai / Front Garden image prompt must include the neighbourhood openness block + negatives for compound walls — do not assume Flow will leave the village open.

**Standards impact:** none (canon already forbids large compound walls) · reinforce in Image Prompt Template outdoor checklist if it keeps recurring after Ep2.

**Status:** adopted in episode · promoted to category register

---

### LL-EP002-02

**Date:** 2026-07-15  
**Stage:** animation / continuity  
**Type:** defect / process  
**Severity:** high (director should have caught without pushback)

**What happened:**  
Flashback finish (sh_007) was first boarded/prompted as a weak single still (“girl crying · dog present”) that did **not** read as **dog winning**. Early animation drafts also failed to lock **run → stop → win ahead → cry** from the approved sh_006 running end. Continuity had to be forced by the producer instead of being designed up front.

**Evidence:**  
Rejected still: girl foreground, dog *behind* her on the path (reads as follower/comfort, not race result). Approved path: sh_006 end (L→R run, dog ahead) → two-image Flow into sh_007 (both stopped; dog ahead-right win; girl trailing cry).

**Root cause:**  
Prompts described emotion (“she cries”) without a **spatial win contract** and without a mandatory **Begin→End continuity decision** (one-image vs two-image) against the previous approved frame.

**Corrective action taken:**  
- Win lock: dog AHEAD · girl TRAILING · same screen direction as run.  
- Two-image Flow when the beat is a true state change from the prior approved frame (run → stop/cry).  
- CD/agent must propose this **before** the producer asks.

**Recommendation for future episodes:**  
Before every animation prompt, answer: *What is the previous approved end frame? Does this beat need two-image? Is the story relation (win / lose / arrive / ask) readable in silhouette?* If state changes, default to **two-image** + Begin→End contract.

**Standards impact:** reinforce in `11_Templates/Animation_Prompt_Template.md` · Movement/continuity checklist.

**Status:** adopted in episode · promoted to category register

---

### LL-EP002-02b (race-loss motion)

**Date:** 2026-07-15  
**Stage:** animation  
**Type:** story-clarity  
**Severity:** medium

**What happened / corrected:**  
Finish beat read weak if **both** decelerate and stop together. Producer note: **girl stops + cries; dog keeps running ahead** — continued lead = visible loss.

**Lock for race-result clips:** Loser halts and sobs · winner **keeps running and exits ahead / out of frame** (do not mirror-stop). **End still must already show that split** — dog mid-stride exiting right; girl stopped trailing. A both-standing-stopped end still forces Flow to freeze the dog with her.

**Status:** adopted · see Animation Mistakes LL-CAT-ANM-01 note

---

### LL-EP002-03

**Date:** 2026-07-15  
**Stage:** animation / camera  
**Type:** process defect  
**Severity:** medium–high (recurring habit)

**What happened:**  
Animation prompts repeatedly defaulted to **Static Camera only**, without choosing and naming approved moves from `20_Camera_Movement_Bible.md` — including **Slow Push In** and **Slow Pull Out** (push-back). Producer had to demand camera language.

**Evidence:**  
Multiple ep_002 animation deliveries labeled Static/Locked by habit even when emotion, finish, or context would earn a near-imperceptible push in / pull out.

**Root cause:**  
Template allowed “Static / [approved move]” as optional shorthand; agent defaulted to Static without running the Movement Bible preference + purpose test.

**Corrective action taken:**  
Animation template now **requires** the five Flow camera fields every time, with an explicit choose-from list (Static / Locked / Slow Push In / Slow Pull Out / Pan / Tilt / short Truck·Dolly) and a one-line **why this move** (or why locked). Never ship “Static” without that decision note.

**Recommendation for future episodes:**  
For each clip: consider Static first, then whether a **nearly imperceptible Slow Push In** (emotion / realization) or **Slow Pull Out** (return to context / win+loss result in space) serves the beat. Name it. Do not wait for producer pushback.

**Standards impact:** `11_Templates/Animation_Prompt_Template.md` · Camera Movement Bible already authoritative.

**Status:** adopted in episode · promoted to category register

---

### Related category rows

- `Categories/Visual_Consistency.md` → LL-CAT-VIS-01  
- `Categories/Prompt_Failures.md` → LL-CAT-PRM-01  
- `Categories/Animation_Mistakes.md` → LL-CAT-ANM-01 · LL-CAT-ANM-02  
- `Categories/Workflow_Improvements.md` → LL-CAT-WFL-01  
