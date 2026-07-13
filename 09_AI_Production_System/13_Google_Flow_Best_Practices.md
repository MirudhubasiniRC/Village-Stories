# Google Flow Best Practices

## Permanent Role

This is the permanent operating manual for using Google Flow to turn approved
Village Stories source images into controlled, editorially usable motion. It
defines the Flow-specific decisions that sit between an approved storyboard and
a selected clip: source choice, one-image or two-image input, motion limits,
continuity control, candidate review, and records.

It is not a story-development document, a character-design document, or a
licence to repair missing decisions through generation. Flow creates candidates;
the approved production record decides what they are allowed to depict.

> Ask Flow to preserve a known world while showing one small, observable change.
> Never ask it to invent the next fact of that world.

For prompt assembly use `05_Master_Animation_Prompt.md`. For the still that
starts a clip, use `04_Master_Image_Prompt.md` and
`04_Image_Prompt_Reference.md`. For framing, screen direction, and camera side,
`19_Camera_Direction_Bible.md` is the sole operational authority. For camera
motion, speed, path, and movement limits, `20_Camera_Movement_Bible.md` is the
sole operational authority.

---

## Authority And Non-Negotiable Limits

Flow inherits authority; it creates none. Resolve a conflict by using the
highest applicable approved source. Do not blend contradictory descriptions or
use a successful candidate as evidence that an unapproved detail is acceptable.

```text
Current approved production decision
↓
01_Canon/ — timeline, continuity, art style, and camera philosophy
↓
02_World/ · 03_Characters/ · 04_Objects/ · 05_Research/
↓
06_Story_Engine/ — story truth and emotional limits
↓
Approved brief, script, storyboard, scene-state ledger, adjacent-shot handoff
↓
07_Episode_System/ — format, pacing, opening, ending, visual rhythm
↓
08_Production/ — execution, QC, edit, files, versions, release
↓
09_AI_Production_System/ — prompt and Flow operating manuals
↓
Flow settings, references, candidates, selected clip
```

The permanent locks include early-1990s rural Tamil Nadu, original premium
cinematic anime rendering, dignified everyday life, correct location geography,
period-correct objects, natural light, and a calm human-observer camera. Refer
to the applicable source rather than paraphrasing an incomplete version of a
lock.

An unresolved required fact is `HOLD FOR CANON OR RESEARCH`. A weak board is
`HOLD FOR BOARD`. A wrong source still is `HOLD FOR SOURCE REPAIR`. None is an
invitation to generate speculatively.

---

## What Flow Is Good At—and What It Is Not

Flow is useful for bounded, image-to-motion work:

- a hand completing one documented task;
- a person taking a few grounded steps along an established path;
- steam, rain, leaves, cloth, water, or smoke moving naturally;
- a small, approved response from another person or the Family Dog;
- a single camera behavior approved by the movement bible.

It is unreliable when asked to resolve several changes at once. Split the shot,
make a new still, use an insert, or hold a still if the beat requires any of
the following:

- a new location, time, weather state, costume, tool, or character entrance;
- a large pose reversal, complex hand-tool contact, or object transfer;
- multiple independent character actions;
- a major emotional turn, a conversation with precise lip-sync, or a plot
  revelation needing exact clarity;
- a long move through changing geography;
- an action whose end state must be exact but cannot be supplied reliably.

Do not use motion as camouflage for a continuity error. A stable, correct still
is preferable to a lively but uncuttable clip.

---

## Required Flow Brief

Do not open a final Flow generation until the following record is complete.
Use `NONE` only when a field is truly irrelevant. `OPEN` requires an owner and
resolution path.

```text
Episode / scene / shot ID:
Prompt revision and operator:
Format / aspect ratio / crop-safe area:
Purpose in the edit:
Approved source still A and image-QA status:
Approved source still B, if used, and image-QA status:
Reference attachments and explicit role:

Input mode: one-image / two-image / no animation:
Visible start state:
One principal visible action:
Permitted secondary response:
Visible end state:
What must remain unchanged:

Location / zone / orientation:
Time / weather / lighting source and direction:
Characters, clothing, pose, screen position, and travel direction:
Objects, handler, start state, permitted change, and end state:
Camera direction source and movement source:
Incoming shot / outgoing shot / match point:
Known generation risks and negatives:
Open facts, owner, and disposition:
```

The operator loads a compact source packet: source path, relevant heading,
applied fact, what it locks, and risk if ignored. A reference controls only its
declared role—identity, wardrobe, source state, end state, or composition—and
does not silently authorize everything visible in it.

---

## Choosing No Animation, One Image, Or Two Images

Select mode for the continuity requirement, not because more inputs feel safer.

### No Animation

Use a still when the value is composition, observation, a clean edit hold, a
complex continuity state, or a moment that needs no visible change. Use a still
also when Flow would likely distort a face, hands, tool, textural detail, or
required object relationship.

### One-Image Input

One-image input supplies a literal approved start state and lets Flow perform
one bounded change. Use it when all of these are true:

1. the source still is approved and already communicates the required setup;
2. the end state can be described plainly without changing identity, layout, or
   important object state;
3. the action is short, continuous, and visually local;
4. the outgoing cut does not require an exact independently authored endpoint;
   and
5. any drift can be rejected without losing a required match.

Typical one-image clips: Mother lifts a pot lid once and steam rises; Father
walks two calm steps along an already-established ridge; rain continues beyond
a doorway; the dog looks up, then settles; a locked camera holds while leaves
move in a light breeze.

One-image is not suitable merely because the source image looks good. Do not
use it for a tool changing hands, a garment becoming materially different, a
person crossing to a precisely required mark, or a camera arrival that must
match the next shot.

### Two-Image Input

Two-image input constrains both endpoints. Use it when the edit needs a known
start and known finish, especially where a cut, state change, or screen
geography would otherwise be fragile. Both images must be independently
approved, depict the same documented scene, and differ only in the planned
change.

Appropriate uses include:

- a person beginning and ending at two approved marks while retaining the same
  clothing, tool, direction, light, and location;
- a documented object moving from one exact stable position to another;
- a camera bridge that must leave an approved frame and arrive at an approved
  frame under the movement bible;
- a transition whose final pose or composition must cut directly to the next
  shot.

Do not use two images to force an impossible transformation, hide a location
change, jump time or weather, swap a person, or convert different camera sides
into one continuous move. If A and B disagree beyond the planned change, repair
the images or split the edit. Two inconsistent images create interpolation
pressure, not continuity.

### Decision Gate

```text
Is motion necessary to express the approved beat?
  No → use the approved still.
  Yes ↓
Is one source image an exact approved start state, and is the end state small,
continuous, and not cut-critical?
  Yes → one-image.
  No ↓
Do approved start and end images depict the same scene with only the planned
change, and must the end match an edit point?
  Yes → two-image.
  No → split the shot, create a repaired still, or return to the board.
```

---

## Image-to-Motion Constraints

Every clip has a change budget: one principal action, at most one restrained
secondary response, and one camera behavior. The source image is an anchor, not
a vague mood board.

### Preserve Unless Explicitly Approved To Change

- recurring faces, age, build, hairstyle, skin tone, clothing, jewellery, and
  relationship behavior;
- location architecture, object count, material, placement, and condition;
- period, season, weather, time, light direction, and light quality;
- camera side, shot size, screen direction, line of action, and crop-safe
  composition;
- background population and activity;
- expression, body orientation, and hand-object relationship except where the
  planned action changes it.

For Father, apply the stored `CHARACTER_IDENTITY` reference whenever the
requirements in the master image/animation manuals apply. For Mother, retain
the documented bindi, left-nostril nose pin, thin glass bangles, small jhumkas,
and exactly one thali chain when visible. The Family Dog remains a gentle
household companion, never a threat, rescue device, or spectacle.

### Motion Language

Describe what a viewer can verify, in order:

```text
Start: [literal source state].
Action: [one subject] [one grounded verb] [one object/path if needed].
Secondary motion: [only natural supporting motion].
Camera: [approved direction] + [one approved movement or locked hold].
End: [literal observable end state].
Preserve: [critical locks].
Avoid: [specific likely drift].
```

Example:

```text
Start from the approved medium side view in the west kitchen doorway: Mother is
screen-left facing the stove screen-right, holding the pot lid; cool monsoon
daylight remains diffused from the open east-facing window. She lifts the lid
once, looks briefly into the pot, and holds it steady; steam rises naturally.
Locked camera. Preserve her identity, practical saree, bindi, nose pin, thin
glass bangles, small jhumkas, one thali chain, stove, pot, and room layout. No
new food, utensil, person, camera move, lighting shift, expression change, or
extra hand movement.
```

Avoid metaphor-only instructions such as “make it cinematic,” “dynamic,”
“emotional,” “beautiful motion,” or “bring the village alive.” They make a
candidate hard to review and invite unauthorized changes.

### Camera Control

Flow prompt wording does not decide camera direction or movement. Record the
approved direction from `19_Camera_Direction_Bible.md`; then add exactly the
approved movement from `20_Camera_Movement_Bible.md`, including speed, boundary,
and endpoint. “Cinematic camera,” “orbit,” “sweeping,” “dramatic reveal,” and
unbounded “follow” are invalid unless an explicit approved movement module says
otherwise. A locked camera is a deliberate production choice.

---

## Continuity Bridges And Asset QA

Before generation, compare the source image to the incoming and outgoing shot.
Record the bridge rather than trusting visual memory.

```text
Incoming outgoing state:
Clip source start state:
Required clip end state:
Next-shot incoming state:
Must-match facts:
Permitted differences:
Screen-direction rule:
Light / weather rule:
Object / wardrobe / character-position rule:
Cut or transition type:
```

Asset QA precedes animation QA. A source still fails if its identity, costume,
object, geography, light, style, period, or camera direction is wrong, even if
its proposed movement is simple. Repair or replace the source; do not animate
it in the hope that motion will make it acceptable.

Two-image inputs require an A/B delta check. List every visible difference. If
the list contains more than the documented action, permitted natural response,
or approved camera change, reject one or both inputs for repair.

---

## Candidate Review And Decision

Review at normal viewing speed, then inspect start, midpoint, and end frames.
Compare against the brief, source still(s), and adjacent selected shots. Judge
the asset in this order:

1. canon, safety, period, and style;
2. character, wardrobe, location, and object identity;
3. start/end state and story action;
4. camera direction, movement, screen geography, crop safety;
5. light, weather, and editing continuity;
6. anatomy, hand/object contact, texture stability, and artifact control;
7. pacing and emotional appropriateness.

Decision codes:

- `APPROVED`: fulfills every hard lock and editorial requirement.
- `APPROVED WITH TRIM`: only a documented in/out trim is needed; no factual
  defect exists within the retained portion.
- `REPAIR SOURCE`: candidate exposes a wrong or inadequate source still.
- `REGENERATE`: prompt, input selection, or settings can be corrected without
  changing the approved shot.
- `RETURN TO BOARD`: requested action/camera/end state is under-defined or too
  complex for one clip.
- `HOLD FOR CANON OR RESEARCH`: a required fact lacks authority.
- `REJECT`: violates a hard lock, introduces a prohibited fact, or cannot be
  made cuttable through an authorized revision.

Never approve “almost correct” identity or continuity for a recurring asset.
Do not average defects across candidates; select one candidate that is correct.

---

## Format And Editorial Rules

### Shorts

For 9:16, keep the action, face, hands, and required object in the central
crop-safe corridor. The opening must read immediately without rapid camera
movement or a full-frame geography explanation. Prefer one readable action,
stable vertical screen position, and a clean end frame that can loop, cut, or
hold. Do not let captions, platform UI, or crop remove the story information.

A two-image bridge is justified when a Short depends on a precise end pose or
loop match; it is not a substitute for a strong first frame.

### Long Form

For 16:9, use wider context only when it clarifies work, relationship, or
place. Earn duration through an observable process, not slow random drift.
Maintain screen geography across coverage and preserve room for editorial
breathing. Split a multi-stage task into distinct shots rather than asking Flow
to sustain a long, evolving event.

The episode format rules in `07_Episode_System/12_YouTube_Shorts.md` and
`13_Long_Form_Episodes.md` remain authoritative.

---

## Production Record And Handoff

Archive enough information to reproduce, audit, or reject the asset later:

```text
Shot ID / candidate ID / revision / date / operator:
Tool and available settings:
Input mode and source filenames with revisions:
Attached references and declared roles:
Exact submitted prompt:
Camera direction and movement source headings:
Start/end state ledger and continuity bridge:
Candidate decision and reviewer:
Defects observed, severity, and disposition:
Approved trim, export filename, and edit destination:
Replacement relationship to prior candidate, if any:
```

Preserve rejected candidates when they document a recurring failure or a repair
decision; label them clearly so they cannot be used by accident. File naming,
version retention, and release rules remain under
`08_Production/16_File_Organization.md` and `17_Version_Control.md`.

---

## Cross-References

- `README.md` — system scope, authority, and folder responsibilities.
- `01_Master_Workflow.md` — lifecycle and source-control procedure.
- `04_Master_Image_Prompt.md` and `04_Image_Prompt_Reference.md` — source
  still construction and image reference practice.
- `05_Master_Animation_Prompt.md` — copy-ready Flow prompt assembly.
- `19_Camera_Direction_Bible.md` — sole authority for viewpoint and framing.
- `20_Camera_Movement_Bible.md` — sole authority for movement.
- `14_Prompt_QA.md` — prompt and asset gate.
- `15_Common_Failures.md` — symptom, cause, repair, and recurrence handling.
- `08_Production/07_Google_Flow_Workflow.md` and `14_Quality_Control.md` —
  production execution and final QC.

## Final Rule

A Flow clip is usable only when it preserves the exact known world, performs
one approved change, and joins its neighbors without asking the audience—or the
editor—to excuse a discontinuity.
