# Common Failures

## Permanent Role

This is the permanent diagnosis and repair manual for AI image and Google Flow
animation failures in Village Stories. It converts an observed defect into a
repeatable production decision: classify the failure, identify its likely
cause, select the smallest authorized repair, validate the repair, and retain a
record that prevents recurrence.

It does not authorize a change to canon, story, character, location, object,
camera language, or production process. A failure is evidence to investigate,
not permission to improvise.

> Diagnose the cause, not just the ugly frame. A new adjective cannot repair a
> wrong source, a missing board decision, or a conflict in canon.

---

## Authority And Repair Boundaries

Use the highest applicable authority and do not average contradictions.

```text
Current approved production decision
↓
01_Canon/
↓
02_World/ · 03_Characters/ · 04_Objects/ · 05_Research/
↓
06_Story_Engine/
↓
Approved brief, script, storyboard, scene-state ledger
↓
07_Episode_System/ and 08_Production/
↓
09_AI_Production_System manuals and camera bibles
↓
Prompt revision and candidate repair
```

`19_Camera_Direction_Bible.md` is the sole authority for framing, camera side,
screen direction, composition, and line of action. `20_Camera_Movement_Bible.md`
is the sole authority for camera motion, speed, path, boundaries, and movement
repair. Do not “fix” a camera defect by inventing a new view or move.

When the required answer does not exist, assign `HOLD FOR CANON OR RESEARCH`.
When the action, endpoint, or shot purpose is unclear, assign `HOLD FOR BOARD`.
When a source still is wrong, assign `HOLD FOR SOURCE REPAIR`. These are valid
outcomes, not failed prompt-writing.

---

## Failure Taxonomy And Severity

Assign a primary taxonomy code and any contributing codes:

```text
CAN — canon, period, culture, style, or emotional-boundary failure
ID — character, animal, wardrobe, or jewellery identity drift
LOC — location, geography, architecture, or lighting failure
OBJ — object count, material, placement, state, or handoff failure
CAM — direction, screen geography, crop, or movement failure
ACT — action, anatomy, hand/tool contact, timing, or end-state failure
CON — adjacent-shot continuity or transition failure
FMT — Shorts/long-form aspect, caption-safe, pacing, or edit failure
PRM — prompt construction, overload, contradiction, or reference-role failure
SRC — wrong, weak, or inconsistent source image/reference
TOOL — repeatable model/tool limitation after the brief and prompt are sound
```

Severity decides disposition:

- **Critical** — canon, period, identity, safety/dignity, required continuity,
  or unapproved story fact is broken. Reject or hold.
- **Major** — the shot cannot serve its story, camera, action, endpoint, crop,
  or edit purpose. Regenerate or return to owner.
- **Moderate** — a required visual detail, physical relationship, or stable
  material is visibly wrong. Repair source/prompt and regenerate.
- **Minor** — a non-required imperfection lies outside the retained edit; it
  may permit an explicit approved trim, never a silent waiver.

Never downgrade a failure because a candidate is otherwise beautiful.

---

## Universal Diagnosis Procedure

1. **Freeze the evidence.** Record candidate ID, prompt revision, source
   revisions, settings available, timestamp/frame, and the selected neighboring
   shots. Do not overwrite the prompt that produced the defect.
2. **State the symptom literally.** “Father becomes clean-shaven at 00:02.1”
   is useful. “Identity feels off” is not.
3. **Name the violated lock.** Cite the source path and heading that the result
   fails to meet.
4. **Classify the failure.** Apply taxonomy code(s) and severity.
5. **Find the earliest cause.** Check authority/brief, source image, reference
   role, mode choice, camera decision, prompt wording, then tool behavior—in
   that order.
6. **Make the smallest authorized repair.** Change only the component that
   caused the failure. Do not rewrite every prompt module after one defect.
7. **Regenerate or return.** Use the appropriate status; do not keep an
   unapproved candidate as a hidden production asset.
8. **Re-run QA.** Apply `14_Prompt_QA.md` to the changed asset and the
   relevant continuity bridge.
9. **Record the learning.** Add recurrence prevention if the issue can affect
   later shots.

If two candidates fail differently, do not combine their good parts mentally.
Each selected asset must independently pass.

---

## Failure Library

### CAN-01: Modern Or Unsupported Period Detail

**Symptoms:** phone, electric appliance, current packaging, LED-like light,
modern vehicle, contemporary fashion, branding, urban utility, or modern
problem-solving appears.

**Likely causes:** vague location/object prompt; unsourced stock reference;
tool default; negative constraint omitted; source still already contaminated.

**Repair:** reject the candidate; identify the exact prohibited detail; load
the correct period/object authority; replace contaminated source references;
state the practical period-correct object or absence needed. Do not merely add
“1990s” to an otherwise generic prompt.

**Prevention:** include period and material locks in the permanent layer and
perform asset QA before Flow animation.

### CAN-02: Generic, Exoticized, Or Melodramatic Village

**Symptoms:** decorative poverty, tourism image, fantasy village, disaster
weather, thriller color, grand heroic staging, panic, humiliation, violence, or
unapproved urgency.

**Likely causes:** mood-first words such as “dramatic,” “epic,” or “rustic”;
missing scene purpose; unbounded style reference; camera spectacle; tool
interpreting emotional adjectives as danger.

**Repair:** return to the approved observable beat; replace mood language with
specific practical activity, location materials, calm expression, light, and
camera direction. Reject any candidate that changes the emotional boundary.

**Prevention:** state the dignified slice-of-life intent and the explicit
absence of threat where the scene could be misread.

### ID-01: Character Face Or Body Drift

**Symptoms:** recurring person changes age, complexion, face, hair, stubble,
build, posture, or reads as a different person between images or frames.

**Likely causes:** identity reference absent or assigned no role; overloaded
prompt; wide/distant source with no useful facial anchor; source image already
wrong; long or complex Flow action.

**Repair:** reject for recurring principal shots. Use the approved identity
reference where mandated, repair the source still at a usable identity scale,
reduce action complexity, and restate only defining identity features. If the
identity has no authoritative design, hold for canon.

**Prevention:** attach references as `CHARACTER_IDENTITY`, not general style;
select the correct approved source still and inspect identity at start, middle,
and end of Flow clips.

### ID-02: Wardrobe, Jewellery, Or Character State Drift

**Symptoms:** clothing color/style changes; Mother loses or gains jewellery;
Father becomes clean-shaven or overly groomed; garments become glamorous;
dirty/wet/dry state changes without cause.

**Likely causes:** adjacent-shot state not loaded; only generic clothing
description; framing has not been considered; Flow is asked for too much body
motion; source A/B disagree.

**Repair:** list exact must-match wardrobe/state facts in the continuity bridge;
repair either input image before using two-image Flow; reduce to a smaller
motion or a still if the state cannot remain stable. Reject any visible
unapproved multiplication or removal of Mother's required details.

### ID-03: Family Dog Mischaracterized

**Symptoms:** dog becomes wolf-like, aggressive, injured, police/military,
rescue/chase device, or a different breed.

**Likely causes:** generic “dog” wording, dramatic action, unsafe reference, or
tool completion bias.

**Repair:** reject; restore the gentle German Shepherd household-companion lock,
use an approved reference if available, and reduce the dog’s role to an
ordinary, source-backed behavior.

### LOC-01: Location Layout Or Geography Changes

**Symptoms:** doors, windows, stove, yard route, field/pond relation, building
materials, or world orientation change; a move crosses impossible space.

**Likely causes:** location not named by zone; source reference controls mood
rather than layout; camera direction is improvised; two endpoints depict
different places.

**Repair:** return to the location source and approved zone; state the camera
side and visible anchors from the direction bible; replace incompatible source
images; split the shot if travel crosses an unestablished area.

**Prevention:** load a location packet and record geography in every continuity
bridge.

### LOC-02: Light, Weather, Or Time Reversal

**Symptoms:** sunlight changes side, shadows reverse, rain starts/stops,
monsoon becomes a storm, morning/evening color shifts, or weather consequences
disappear mid-shot.

**Likely causes:** time/weather not in brief; generic golden-hour or dramatic
lighting language; adjacent image source mismatch; too much generated duration.

**Repair:** reject; cite the scene ledger, orientation, and required visible
weather consequence. Remove generic lighting adjectives. Use shorter motion or
a stable still if the condition cannot be held.

### OBJ-01: Object Duplication, Loss, Or Wrong State

**Symptoms:** extra cup/tool/utensil, object disappears, object changes
material/size, food appears, lid opens/closes inconsistently, or object moves
without the approved handler.

**Likely causes:** object lacks a start/change/end ledger; prompt requests
several interactions; source A/B delta is too large; hands obscure the state.

**Repair:** make an object-state table for the shot; repair the source still;
isolate one interaction; use an insert or two-image bridge only when both
endpoints are approved and differ solely by the documented change.

### OBJ-02: Hand, Tool, Or Physics Failure

**Symptoms:** fingers merge, tool passes through hand, vessel floats, weight is
wrong, liquid/steam behaves implausibly, or a hand changes grip mid-action.

**Likely causes:** complex choreography, multiple objects, vague verb, poor
source pose, too-long Flow action, or tool limitation.

**Repair:** simplify to one contact and one grounded verb; create a stronger
start still with the contact already legible; cut to an insert or static shot.
Do not attempt a full multi-step task in one generated clip.

### CAM-01: Incorrect Direction, Framing, Or Screen Direction

**Symptoms:** camera is on the wrong side; person reverses screen direction;
shot size changes; required object leaves frame; horizon/angle becomes
distorting.

**Likely causes:** board lacks camera source; “cinematic” substituted for
direction; reference image silently overrides composition; Flow prompt embeds
an unauthorized view.

**Repair:** return to `19_Camera_Direction_Bible.md` and the approved board;
state camera side, shot size, subject position, and line of action plainly.
Regenerate from a corrected source, not by asking Flow to “fix camera.”

### CAM-02: Unauthorized Or Excessive Camera Movement

**Symptoms:** orbit, zoom, whip, handheld wobble, dolly, reframe, or line-cross
appears without approval; movement calls attention to itself.

**Likely causes:** prompt says “dynamic,” “follow,” “reveal,” or “cinematic”;
no movement boundary; tool adds drift; a complex action provokes reframing.

**Repair:** select `Locked Camera` unless the movement bible authorizes one
specific alternative; state exact start/end framing and speed language from
`20_Camera_Movement_Bible.md`; simplify subject motion.

### ACT-01: Too Many Actions Or Unclear End State

**Symptoms:** subject begins several tasks, action stalls, ends in wrong pose,
adds a reaction, changes location, or produces an uncuttable end.

**Likely causes:** prose sequence used as prompt; no literal end state; a
multi-beat board panel; one-image mode chosen for a cut-critical endpoint.

**Repair:** split into shots; state one action and one observable end state;
use two approved images only when their delta is limited and the endpoint must
match. Otherwise create a new board or still.

### ACT-02: Expression Or Emotional Tone Drift

**Symptoms:** smile becomes grief, neutral face becomes alarm, calm work becomes
performance, or characters stare at camera.

**Likely causes:** emotion words without behavior, action too complex, generic
portrait phrasing, camera too intrusive, or model embellishment.

**Repair:** describe visible behavior and gaze direction, not abstract emotion;
retain calm observer framing; remove drama language; use a shorter clip.

### CON-01: Adjacent-Shot Mismatch

**Symptoms:** person/prop changes side, clothing state changes, tool is already
in the wrong hand, weather/light differs, or cut has a jump with no intended
transition.

**Likely causes:** no bridge ledger; source selected by attractiveness; earlier
asset changed without downstream review; unrecorded trim.

**Repair:** build the explicit incoming/current/outgoing ledger; identify the
first shot where state diverged; repair the earliest causal asset, then re-QA
all dependent shots. Do not patch each later asset independently.

### CON-02: Two-Image Interpolation Failure

**Symptoms:** morphing face/body/object, warped architecture, unexplained
camera travel, new objects, or unstable midpoint despite correct endpoints.

**Likely causes:** A/B images differ in more than the intended action; camera
side or light differs; endpoints are separate scenes; too large a pose or
location change.

**Repair:** perform an A/B delta check. Repair the inputs so only the permitted
change differs, reduce the bridge, or use a cut with two correct stills. Do not
keep the clip because its endpoints look correct.

### FMT-01: Shorts Crop Or Caption Failure

**Symptoms:** face, hand, or tool is clipped; action travels laterally out of
9:16; platform captions cover information; a vertical opening is unreadable.

**Likely causes:** 16:9 candidate repurposed without QA; crop-safe plan absent;
wide composition; movement too large.

**Repair:** generate/reframe for the Short rather than treating crop as an
afterthought. Keep required action in the central safe corridor and simplify
movement. A long-form approval does not transfer automatically.

### FMT-02: Long-Form Filler Or Pacing Failure

**Symptoms:** random camera drift, extended idle movement, repeated action, or
clip length that contributes no process, relationship, or place.

**Likely causes:** duration treated as value; Flow asked to make stillness
interesting; no edit purpose.

**Repair:** shorten, hold a still, use a purposeful insert, or return to the
scene rhythm. Long form earns duration through meaningful observation, not
motion for its own sake.

### PRM-01: Prompt Overload Or Contradiction

**Symptoms:** candidate follows some instructions while losing others; objects
or style conflict; subject/action/camera are ambiguous.

**Likely causes:** whole manuals pasted into prompt; duplicate descriptions;
multiple alternatives; permanent and scene layers mixed; reference roles not
declared.

**Repair:** rebuild from source packet: hard locks, scene facts, one action,
camera instruction, continuity bridge, and targeted negatives. Delete
non-constraining decoration. Test the repaired prompt against the QA gate.

### SRC-01: Wrong Or Weak Source Asset

**Symptoms:** every candidate inherits wrong clothing, layout, composition,
identity, crop, or object state from the still/reference.

**Likely causes:** source was never asset-QA approved; “best-looking” image was
chosen; reference role not separated; source is too distant or obscured.

**Repair:** stop regenerating motion. Repair/regenerate the source still and
approve it through `14_Prompt_QA.md` before returning to Flow.

### TOOL-01: Repeated Model Limitation

**Symptoms:** the same bounded, well-specified defect persists across careful
revisions: unstable fingers, complex tool contact, precise endpoint, or long
identity hold.

**Likely causes:** request exceeds reliable tool behavior, not a missing
adjective.

**Repair:** change production design within authority: use a still, insert,
shorter motion, simpler action, a different approved coverage angle, or an
editorial cut. Record the limitation so future boards avoid it.

---

## Edge Cases

### A Correct Candidate With One Bad Frame

If a defect is before/after the retained action, a documented trim may be
allowed only after confirming that both new endpoints still match adjacent shots
and no mandatory action is lost. A mid-clip hard-lock defect is not a minor
issue merely because it is brief.

### An Attractive Candidate Establishes A New Detail

Treat it as rejected or return it to canon review. A generator cannot create a
new object, architectural feature, costume, family behavior, or camera
precedent by accident.

### The Prompt And Source Conflict

The source is not automatically right. Identify the higher authority; repair
the lower artifact and record why. Do not ask Flow to reconcile two
contradictions.

### A Previous Approved Shot Is Wrong

Quarantine it from reuse, identify its downstream dependencies, and assign an
owner. Approval history does not protect a detected canon or continuity error.

---

## Failure Record And Recurrence Control

Use one record per failure cluster:

```text
Issue ID / episode / scene / shot / candidate:
Date / operator / reviewer:
Primary and contributing taxonomy codes:
Severity and violated source path / heading:
Literal symptom and timestamp/frame:
Prompt revision, sources, references, input mode, available settings:
Likely earliest cause:
Decision: reject / regenerate / repair source / return to board / hold:
Authorized repair and owner:
New revision / replacement candidate:
QA result after repair:
Recurrence-prevention rule or module change:
Related issue IDs:
```

If an issue recurs, promote the prevention into the appropriate permanent
prompt module, QA checklist, source-selection rule, or board template—without
changing canon through this document.

---

## Cross-References

- `13_Google_Flow_Best_Practices.md` — one/two-image mode and motion control.
- `14_Prompt_QA.md` — pre-generation gates, candidate decisions, and QA record.
- `04_Master_Image_Prompt.md` and `04_Image_Prompt_Reference.md` — still
  construction and reference practice.
- `05_Master_Animation_Prompt.md` — Flow source, prompt, review, and handoff.
- `19_Camera_Direction_Bible.md` and `20_Camera_Movement_Bible.md` — binding
  camera rules.
- `08_Production/14_Quality_Control.md`, `16_File_Organization.md`, and
  `17_Version_Control.md` — production quality and record retention.

## Final Rule

The correct repair is the smallest change that restores an approved fact,
preserves the known world, and makes the next generation easier to verify. If
the repair requires a new fact, stop and obtain the fact from its proper owner.
