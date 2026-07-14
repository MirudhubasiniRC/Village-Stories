# Prompt QA

## Permanent Role

This is the permanent quality gate for Village Stories image and Google Flow
animation prompts. It defines what must be verified before a prompt is
submitted, what must be inspected after a candidate is generated, how a result
is accepted or rejected, and what evidence is retained.

Quality assurance is not a final beauty pass. It is the control that prevents a
prompt from quietly changing canon, continuity, camera geography, period,
identity, or story meaning.

> A candidate is not approved because it is attractive. It is approved only
> when it is truthful, continuous, usable in the edit, and traceable to
> authority.

This manual is a gate, not a replacement for source documents. It cannot create
a new fact or waive an existing lock.

---

## Authority And Scope

Apply the highest applicable approved source. If two instructions conflict, do
not average them in the prompt; log the contradiction and return it to the owner
of the higher-level decision.

```text
Current approved production decision
↓
01_Canon/
↓
02_World/ · 03_Characters/ · 04_Objects/ · 05_Research/
↓
06_Story_Engine/
↓
Approved episode brief, script, storyboard, and scene-state ledger
↓
07_Episode_System/ and 08_Production/
↓
09_AI_Production_System prompt manuals and camera bibles
↓
Prompt QA decision and generated asset
```

The camera bibles are operational authorities, not optional inspiration:

- `19_Camera_Direction_Bible.md` decides camera viewpoint, framing, side, line
  of action, screen direction, and composition.
- `20_Camera_Movement_Bible.md` decides whether and how the camera moves,
  including its path, speed, boundaries, and motion-related QA.

QA checks both image prompts and Flow prompts. For animation, it also checks the
approved source image(s), image-to-motion feasibility, start/end state bridge,
and candidate clip. For final release QC, follow
`08_Production/14_Quality_Control.md` as well.

---

## Status Model

Every prompt and candidate receives one explicit status:

- `DRAFT`: not ready for review.
- `HOLD FOR CANON OR RESEARCH`: a needed fact has no authoritative answer.
- `HOLD FOR BOARD`: the shot purpose, action, camera, or continuity bridge is
  unclear.
- `HOLD FOR SOURCE REPAIR`: a reference or source still is not approved.
- `READY TO GENERATE`: prompt passed all pre-generation hard gates.
- `GENERATED — REVIEW REQUIRED`: candidate has no approval status yet.
- `APPROVED`: passes all hard gates and is editorially usable.
- `APPROVED WITH TRIM`: only a documented in/out trim is necessary; retained
  frames satisfy all requirements.
- `REGENERATE`: an authorized prompt/input revision can address the defect.
- `RETURN TO OWNER`: repair belongs to canon, research, board, image, camera,
  or edit owner rather than prompt wording.
- `REJECT`: hard-lock breach, uncorrectable asset, or unsuitable candidate.

“Good enough,” “looks close,” and “we can hide it in the edit” are not statuses.

---

## QA Inputs And Traceability

Before reviewing a prompt, identify its evidence. Do not QA from memory.

```text
Episode / scene / shot ID:
Prompt type: image / Flow animation / repair / insert / thumbnail:
Prompt revision and author:
Reviewer and review date:
Requested format / ratio / crop-safe area:
Approved scene and board revision:
Source paths and headings loaded:
References attached and their explicit roles:
Prior selected shot and next selected shot:
Image source A / B revision, if animation:
Camera direction source / movement source:
Known risks and approved exceptions:
Open facts, owner, and resolution:
```

Classify every instruction in the prompt as one of:

- `HARD LOCK` — failure is automatic hold or rejection;
- `SCENE FACT` — approved fact necessary to this shot;
- `CONTINUITY BRIDGE` — must match a neighboring shot;
- `MOTION CHANGE` — the one permitted change in a Flow clip;
- `CAMERA` — direction and, if applicable, movement;
- `NEGATIVE` — a specific disallowed failure risk;
- `REFERENCE` — an attachment and its narrowly declared job;
- `OPTIONAL DETAIL` — removable without changing the approved shot;
- `OPEN` — not generation-ready.

If a prompt contains an instruction that cannot be classified or sourced, remove
it or obtain authority for it.

---

## Gate 0: Brief Completeness

The prompt cannot advance until each required answer is known:

1. What is the exact purpose of this shot in the scene and edit?
2. What is the one visible story moment?
3. What starts this moment, and what must be visible at its end?
4. Who and what may be visible—and who and what must be absent?
5. Which location zone, time, weather, light direction, and period details
   apply?
6. What must connect to the incoming and outgoing shots?
7. What source decides camera direction; what source decides camera movement?
8. Is this a still, a one-image Flow clip, or a two-image Flow bridge—and why?
9. What is the delivery ratio and crop-safe requirement?
10. Who owns every unresolved fact?

Reject a vague request such as “show a cozy village moment” or “make the scene
more cinematic.” Convert it into a boardable, observable moment first.

---

## Gate 1: Canon And Asset QA

Run this gate before prompt style or wording review.

### World, Period, And Style

- Early-1990s rural Tamil Nadu is respected; no modern technology, branding,
  packaging, fashion, vehicles, utilities, or visual shorthand appears.
- The frame is culturally specific and lived-in, not a generic village,
  poverty spectacle, tourism image, thriller, or fantasy.
- The visual style follows the approved Village Stories anime style for the
  entire frame, matching `Father_Canon_Design_Reference.png`
  language without naming or imitating external studios, artists, films, or
  franchises.
- Ordinary life remains calm and dignified; no unsupported danger, panic,
  humiliation, animal distress, rescue, chase, or melodrama is introduced.

### Character And Wardrobe

- Every visible person has source-backed reason to be present.
- Identity, age, complexion, build, hair, expression range, clothing condition,
  and relationship behavior match their character source.
- Father uses the approved identity reference when the master prompt requires
  it; a “similar man” is not sufficient.
- Mother retains her documented visible details when framing permits: small red
  bindi, left-nostril gold nose pin, thin glass bangles, small jhumkas, and
  exactly one simple thali chain. Do not create, remove, multiply, or glamorize
  them.
- The Family Dog remains the documented gentle German Shepherd companion.

### Location, Objects, And Light

- Architecture, zones, practical materials, routes, and object placement match
  the location and object records.
- Objects are period-correct, the correct count, with the correct handler and
  state. Tool interaction is physically legible.
- Time, season, weather, and their visible consequence match the scene ledger.
- Light direction obeys geography: morning from east, evening from west; it
  does not reverse between adjacent shots.

An asset fails this gate even if Flow might animate it successfully. Repair the
still or source packet before generating.

---

## Gate 2: Continuity And Camera QA

Build a compact continuity bridge before submission:

```text
Previous selected shot:
This shot start state:
This shot end state:
Next selected shot:
Must-match character / wardrobe / pose facts:
Must-match object / placement / state facts:
Must-match location / light / weather facts:
Screen positions and travel direction:
Permitted change:
Cut, hold, or transition logic:
```

Confirm:

- the prompt names no incompatible time, weather, costume, object state, or
  location layout;
- the line of action and screen direction are maintained, or an approved
  reorientation establishes a new line clearly;
- the camera direction is copied from the approved board and
  `19_Camera_Direction_Bible.md`, not improvised in mood language;
- a camera movement, if any, is exactly one permitted behavior from
  `20_Camera_Movement_Bible.md`; a locked camera is recorded when appropriate;
- no crucial information leaves the delivery crop or will be covered by a
  Short caption/UI area;
- the selected source image is the literal required start state.

For two-image Flow input, perform a delta check: list every visible difference
between A and B. Only the approved action, permitted response, and approved
camera change may differ. All other differences are source defects.

---

## Gate 3: Prompt Construction QA

The prompt must be compact enough to follow yet complete enough to protect
locks. Confirm that it:

- separates permanent locks from shot-specific state;
- states one primary subject, one visible action, and for motion one observable
  end state;
- gives references a declared role rather than saying “use this style”;
- specifies only details that constrain the requested shot;
- uses positive factual wording plus specific negatives for known risks;
- avoids contradictory adjectives, duplicate variants, lists of alternatives,
  hidden assumptions, and unsupported emotional interpretation;
- excludes tool-specific claims or settings that the operator cannot verify;
- does not ask the tool to choose an object, person, camera, weather, or ending;
- makes absence explicit where a common unwanted element would damage the shot;
- does not use “cinematic,” “dramatic,” “dynamic,” “beautiful,” or “realistic”
  as substitutes for camera, action, or style instructions.

For Flow, add:

- literal start state;
- one principal grounded movement;
- only natural secondary motion;
- approved direction plus at most one approved camera behavior;
- literal end state;
- preservation locks and motion-specific negatives.

If a motion prompt needs “then,” “while,” and “after that” to describe several
story actions, split the shot.

---

## Gate 4: Format And Editorial QA

### Shorts

For 9:16, verify the hook reads immediately, meaningful action stays in the
central crop-safe corridor, and hands/objects/faces needed for the beat are not
lost to captions or interface space. Avoid broad lateral travel and fast
movement that makes a small vertical frame unreadable. The end must be a clean
loop, hold, or cut point.

### Long Form

For 16:9, verify that wider context has a story purpose and that the duration
earns attention through process, relationship, place, or a calm change. Do not
use random drift as filler. Preserve usable handle frames for editing and
coverage that maintains geography.

The format rules in `07_Episode_System/12_YouTube_Shorts.md` and
`13_Long_Form_Episodes.md` override a lower prompt preference.

---

## Candidate QA: Image

Compare each generated still to the completed brief and source packet. Inspect
the whole frame and critical regions at useful scale. Ask:

1. Is the shot factual, period-correct, and in approved visual style?
2. Is each recurring person unmistakably the documented person?
3. Are anatomy, hands, tool contact, jewellery, clothing, and object count
   credible?
4. Does the location preserve approved layout, orientation, materials, and
   practical use?
5. Does light, weather, time, and color logic match adjacent shots?
6. Does framing follow the direction bible and preserve crop-safe information?
7. Does it communicate the exact planned moment without adding a new story?
8. Is it a dependable start image if it will be animated?

Reject a still for identity drift, unsupported modernity, incorrect geography or
light, broken anatomy, extra/missing objects, an unapproved character,
unusable crop, or a contradiction to the scene state. A beautiful rendering
does not reduce the severity of a hard-lock failure.

## Candidate QA: Flow Animation

First confirm that source A—and source B when used—passed image QA. Then view
the clip at normal speed and inspect its start, midpoint, and end frames.

### Required Checks

- The first retained frame matches the approved source start state.
- The clip shows one principal action; secondary movement is natural, restrained,
  and does not add a second story beat.
- The final retained frame matches the required end state and can cut to the
  outgoing shot. For two-image input, it matches source B in every required
  respect.
- Faces, bodies, hair, clothing, jewellery, and character identity remain
  stable throughout—not only in the first frame.
- Hands, fingers, limbs, tools, vessels, food, doors, and other contacts remain
  physically credible through the movement.
- No person, animal, object, background item, or weather event appears,
  disappears, duplicates, melts, transforms, or changes state without approval.
- Light direction, shadows, weather, architecture, textures, and location
  geography remain stable.
- Camera side, shot size, screen direction, and crop-safe composition remain
  correct; camera movement follows the recorded movement authority.
- Timing supports the episode format and leaves a usable editorial in/out
  point; no mandatory action is clipped by a trim.
- The clip remains calm, dignified, and legible at intended delivery size.

### Typical Automatic Rejections

- Identity becomes a different person, even briefly.
- Mother’s required visible jewellery is removed, multiplied, or redesigned.
- Father’s face, hair, stubble, or build drifts from the approved identity.
- A modern item, branding, modern infrastructure, or unsupported person enters.
- Sun direction, weather, or time shifts mid-clip.
- A tool passes through a hand, an object duplicates, or a state reverses.
- The camera crosses the line, swings dramatically, zooms, or drifts without
  the camera-bible authorization.
- The end state cannot connect to the next approved shot.
- A candidate invents danger, urgency, comedy, spectacle, or distress.

---

## Severity, Rejection, And Repair

Classify every defect so the response matches the cause:

| Severity | Meaning | Decision |
| --- | --- | --- |
| Critical | Canon, safety, period, identity, or continuity breach | Reject; repair source/brief or return to owner |
| Major | Story action, camera, endpoint, crop, or edit usability failure | Regenerate or return to board |
| Moderate | Visible craft defect affecting a required feature | Regenerate or repair source/prompt |
| Minor | Non-required imperfection outside retained frame | Approve with documented trim only if no lock is affected |

Do not repair a critical defect through selective wording alone when the real
cause is a wrong source image, unclear board, contradictory authority, or
inappropriate mode choice. Make the smallest authorized change that addresses
the identified cause:

1. name the symptom and affected time/frame;
2. identify whether the cause is source, brief, prompt module, reference role,
   input mode, camera decision, tool behavior, or edit expectation;
3. revise only that component;
4. increment the revision and preserve the prior record;
5. rerun the relevant gate, not merely a visual glance.

Use `15_Common_Failures.md` for the diagnosis taxonomy and repair patterns.

---

## QA Record

Attach this record to every selected image and clip:

```text
Shot ID / candidate ID / prompt revision:
Asset type / ratio / duration:
Prompt author / reviewer / review date:
Sources and approved revisions:
Input mode and reference roles:
Camera direction source / movement source:
Pre-generation gate: pass / hold / reason:

Canon and asset QA: pass / fail / evidence:
Continuity bridge QA: pass / fail / evidence:
Prompt construction QA: pass / fail / evidence:
Format and editorial QA: pass / fail / evidence:
Candidate QA: pass / fail / timestamp or frame:

Defect code / severity / likely cause:
Decision: approved / approved with trim / regenerate / return / reject:
Approved in/out trim and edit handoff:
Repair action, owner, and next revision:
```

When a candidate is rejected, retain a concise screenshot/frame note or
timestamp that makes the reason reproducible. Rejected assets may be archived
as learning evidence, but must be unmistakably marked unusable. Follow
`08_Production/16_File_Organization.md` and `17_Version_Control.md` for file
and version management.

---

## Examples

### Pass: One-Image Cooking Insert

**Brief:** A medium side view from the approved kitchen doorway. Mother is
screen-left facing the stove screen-right. She lifts a pot lid once; steam rises
naturally. Locked camera.

**Why it passes:** It has an approved source still, one action, a bounded end
state, known light and geography, and a clear use as a quiet long-form insert.
The prompt preserves her identity and visible jewellery, room layout, pot,
stove, and weather/light conditions.

**QA caution:** If the action needs food to appear inside the pot, specify the
approved food and source it. Otherwise it is an unsupported object/state change.

### Fail: “Father Walks Cinematically Through the Village”

**Why it fails:** No route, start/end mark, camera side, time, crop, action
boundary, or continuity bridge is supplied. “Cinematically” is not a camera
instruction. The request may cause a new location, camera drift, wardrobe
change, or generic village imagery.

**Repair:** Return to the board for a specific location zone, start state,
screen direction, camera direction and approved movement; then decide whether a
two-image bridge is necessary.

### Edge Case: Correct Clip, Unsafe Vertical Crop

A selected 16:9 clip shows Father’s hand tool at the edge. The intended Short
crop removes the tool, making the action unclear. The clip is not approved for
the Short merely because it passes long-form QA. Reframe/recreate for 9:16 or
use a different shot; do not crop away the purpose.

### Edge Case: Trim Versus Hidden Drift

If the first 0.4 seconds contain a duplicate cup and all retained frames after
the trim are independently correct and the trim does not lose a required match,
`APPROVED WITH TRIM` may be valid. If a brief identity drift occurs mid-shot,
trimming around it cannot be approved unless the retained clip still contains
the complete required action and both continuous sides are correct. Otherwise
regenerate.

---

## Cross-References

- `README.md` — system authority and document responsibilities.
- `01_Master_Workflow.md` — generation lifecycle.
- `04_Master_Image_Prompt.md` and `04_Image_Prompt_Reference.md` — still
  source construction and image QA context.
- `05_Master_Animation_Prompt.md` — Flow prompt assembly and selected clip
  handoff.
- `13_Google_Flow_Best_Practices.md` — Flow mode selection and constraints.
- `15_Common_Failures.md` — defect taxonomy, causes, and repairs.
- `19_Camera_Direction_Bible.md` and `20_Camera_Movement_Bible.md` — binding
  camera authorities.
- `08_Production/14_Quality_Control.md` — production and release QC.

## Final Gate

Approve only an asset that another operator can trace from the selected
candidate back through its prompt, references, source images, scene state, and
canon—and can place beside neighboring shots without discovering a new fact.

