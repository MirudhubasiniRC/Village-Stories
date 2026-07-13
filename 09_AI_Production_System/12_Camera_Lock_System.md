# Camera Lock System

## Permanent Purpose

This manual makes approved camera decisions usable, traceable, and testable in
Village Stories prompt packets. It is the integration layer between the
storyboard, still-image prompt, Google Flow task, candidate review, revision
record, and editorial handoff.

It does not teach, replace, summarize, or create camera direction or movement.
Those authorities already exist and remain separate:

- `09_AI_Production_System/19_Camera_Direction_Bible.md` is the sole authority
  for camera direction: viewpoint, framing, shot size, height, angle, camera
  side, composition, lens-feel, screen direction, line of action, and visible
  geography.
- `09_AI_Production_System/20_Camera_Movement_Bible.md` is the sole authority
  for camera movement: whether the approved direction holds or moves, movement
  name, path, speed, start/end boundaries, Flow movement wording, and
  movement-specific QA.

This document operationalizes those approved decisions. It never creates a new
framing to make Flow easier, never names a new movement, and never permits a
movement to conceal missing camera direction or broken screen geography.

## Core Rule

> A camera lock is valid only when an approved direction is copied from
> Document 19, an approved movement decision is copied from Document 20, and
> their separate fields remain separate from planning through final edit.

The default movement decision is not an implied move. It must be written as
`Static` or `Locked Camera` under the authority of Document 20.

## Authority And Conflict Handling

```text
Current approved production decision
↓
01_Canon/ — timeline, visual locks, continuity, light, camera philosophy
↓
02_World/ · 03_Characters/ · 04_Objects/ · 05_Research/
↓
06_Story_Engine/ — truth and emotional boundary
↓
Approved episode brief, script, storyboard, scene-state ledger
↓
07_Episode_System/ · 08_Production/
↓
09_AI_Production_System/01_Master_Workflow.md
↓
19_Camera_Direction_Bible.md — sole direction authority
↓
20_Camera_Movement_Bible.md — sole movement authority
↓
This Camera Lock System — packet, validation, revision, handoff control
↓
Tool settings, candidate, selected asset
```

Use the highest applicable authority. Never average conflicting instructions.
An attractive candidate, tool default, reference image, previous output, or
editorial preference cannot overrule an approved board or either camera bible.

When a required camera fact is absent or contradictory:

1. mark the fact `OPEN — owner and resolution`;
2. mark the affected task `HOLD FOR CAMERA / BOARD`;
3. return direction decisions to Document 19 and movement decisions to
   Document 20;
4. revise the storyboard or source still if needed; and
5. regenerate only after the packet has an approved, compatible record.

Do not crop, reverse, add an unapproved camera move, or use an ambiguous prompt
to hide a continuity failure.

## Scope And Boundary

This manual governs:

- the camera-lock inputs that every shot packet must carry;
- the exact separation of direction and movement fields;
- how a still-image prompt and a Flow prompt inherit those fields;
- screen-direction and line-of-action transfer across input images, clips, and
  edit handoffs;
- one-image versus two-image Flow source validation;
- pre-generation, candidate, acceptance, and handoff QA;
- a diagnostic revision path and traceable revision record.

It does not govern:

- selection of shot type, height, angle, side, composition, or line of action;
- selection, name, speed, or bounds of a camera move;
- character design, world layout, object facts, lighting canon, story meaning,
  audio, or release approval.

Direct questions to their owners, rather than expanding this file:

| Decision needed | Owning authority |
| --- | --- |
| Is this a Medium Full, eye-level, doorway-side frame? | Document 19 and approved board. |
| Does this frame preserve the action axis? | Document 19 and approved board. |
| Should the clip hold, pan, track, or push? | Document 20. |
| How fast, how far, and where does a move end? | Document 20. |
| Is the family position, light, or prop state factual? | Canon, scene ledger, and relevant source packet. |
| How does a correct camera decision enter a prompt and get audited? | This manual. |

## Direction And Movement Are Separate Records

Direction answers **where the camera is at the start of the shot and what the
frame shows**. Movement answers **how that already-approved camera behaves over
the duration of a continuous clip**.

Never merge these records into one “Camera” sentence. The merger is a common
source of missing height, missing camera side, axis breaks, camera drift, and
unbounded Flow behavior.

```text
VALID SEPARATION

Camera Direction: [verbatim approved Document 19 direction module]

Camera Movement: [verbatim approved Document 20 decision]
Movement Speed: [Document 20 vocabulary]
Framing Stability: [Document 20 start/end boundary and protections]
```

```text
INVALID MERGER

Camera: slowly circles Mother as she cooks.
```

The invalid instruction provides neither an approved viewpoint nor a valid,
bounded movement decision. It must return to the board and the bibles.

### Non-Negotiable Separation Tests

Before any packet is approved, confirm:

- the Direction field contains no movement verbs or speed words;
- the Movement field does not substitute an undefined shot type, camera side,
  composition, or screen direction;
- exactly one movement behavior is present for a Flow clip, including a named
  static or locked hold where applicable;
- a movement does not change camera side, cross the action line, or discover
  undocumented geography; and
- the still source, start frame, and end frame retain the approved camera
  relationship.

Do not use `cinematic`, `dynamic`, `emotional`, `beautiful`, `around them`,
`find the best angle`, or `show the scene` as a camera instruction. They are
not records from either authority.

## Camera-Lock Packet

Every shot receives one camera-lock packet before still generation and before
Google Flow submission. It may sit inside a larger shot packet, but all fields
below remain visible and separately labeled.

Enter `NONE` only when a field is truly irrelevant. Enter `OPEN` only with a
named owner and resolution path; an OPEN continuity-critical field is a hold,
not a prompt variable.

```text
CAMERA LOCK PACKET

Identity and authority
Episode / scene / shot ID:
Shot revision:
Requesting owner:
Direction source: Document 19 heading / approved board revision:
Direction approval owner and status:
Movement source: Document 20 heading / approved board revision:
Movement approval owner and status:
Scene-state ledger revision:

Editorial purpose and format
Shot purpose:
One-sentence visible moment:
Format: Shorts / long form / both:
Aspect ratio / resolution:
Caption-safe and crop-safe requirement:
Target duration:
Incoming shot / approved end state:
Outgoing shot / required entry state:

DIRECTION LOCK — Document 19 only
Approved direction module:
Shot size:
Camera height:
Camera angle:
Camera side / viewpoint:
Subject placement and readable action:
Composition / foreground / required background:
Location / zone / orientation:
Light relationship:
Action axis:
Character screen positions, eyelines, travel direction:
Dominant hand and object side, if relevant:
Direction-specific protected evidence:

MOVEMENT LOCK — Document 20 only
Camera Movement:
Movement Speed:
Start frame:
Finite path / extent:
End frame / settled composition:
Movement story reason:
Movement-specific protected evidence:
Movement prohibitions:

Source and input control
Still source A filename / revision / approval:
Still source B filename / revision / approval, if used:
Input mode: still / one-image Flow / two-image Flow:
Reference attachments and assigned role:
Source-A screen-direction verification:
Source-B screen-direction verification, if used:

Validation and release
Known risks:
OPEN facts, owner, and resolution:
Pre-generation camera QA reviewer / result:
Candidate IDs reviewed:
Candidate QA reviewer / result:
Selected asset ID / revision:
Edit handoff status:
```

The `Approved direction module` is copied from the applicable Document 19
record. It is not paraphrased from memory. The movement fields are copied from
the applicable Document 20 record. A prompt lead may shorten only redundant
words after confirming that every approved camera fact remains explicit.

## Required Inputs By Production Stage

### Storyboard And Shot Planning

The Storyboard Artist or Shot Designer supplies the approved visual purpose,
scene state, cut relationship, provisional direction source, action axis, and
screen-direction information. Direction is approved through Document 19 before
the packet can enter image generation.

If the shot will move, the movement decision is independently approved through
Document 20. No shot becomes a moving shot merely because the board has arrows
or because an operator thinks it would look better.

### Still-Image Generation

A still-image packet requires:

- an approved direction record from Document 19;
- source-backed location, light, character, object, and scene-state facts;
- crop-safe requirement and intended Flow/edit use;
- action-axis and screen-direction information where a person, handoff,
  conversation, travel route, tool, or adjacent reverse shot makes it relevant;
- a statement of movement intent for the next stage: `NONE — still only`,
  `Static / Locked Camera intended`, or `movement pending Document 20
  approval`.

An image prompt uses the direction module. It must not contain an animation
move. A keyframe cannot be approved as a Flow source if its camera side, screen
direction, or required background geography is unknown.

### Google Flow Animation

A Flow packet requires every completed camera-lock field plus:

- approved Source A and, if used, Source B;
- one-image or two-image selection justified by endpoint-control need;
- the separate five-field Flow camera block from Document 20;
- exact source-frame relationship to the direction record;
- start/end state and edit-handoff compatibility; and
- named motion and camera-risk checks.

Flow is a continuation tool. It cannot decide coverage, repair a poorly
specified still, travel behind a subject to find new geography, or reverse a
screen relationship.

## Screen Direction Operational Lock

Screen direction is carried through the packet as a continuity fact, not a
general camera preference. It is established by the approved board under
Document 19 and then protected in the source image, Flow request, candidate
review, and editorial handoff.

### Record Before Generation

For any shot involving conversation, handoff, travel, working relation, or
adjacent coverage, write:

```text
Action axis:
Approved camera side:
Subject A screen position and facing:
Subject B screen position and facing:
Travel direction:
Eyeline relation:
Dominant hand / object side:
Fixed landmark or working-surface side:
Reset / bridge shot, if an approved reset exists:
```

These fields must describe the shot that will be generated. “Maintain
continuity” without the established state is not a usable lock.

### Still and Source-Image Validation

Before accepting Source A or Source B:

1. compare the image against the approved direction module;
2. verify left/right placement, facing, gaze, hand occupancy, tool side, and
   landmark relation;
3. confirm that any mirror artifact has not reversed textural clues, handedness,
   cookware, doors, or route direction;
4. verify the camera remains on the approved side of the line; and
5. confirm the crop retains the evidence needed by the next shot.

If a source image has an incorrect screen direction, do not “fix” it by
reversing the image unless every affected direction, hand, object, text,
location, lighting, and incoming/outgoing shot has explicit approval. In the
ordinary case, regenerate the source image from the approved direction packet.

### Flow Protection

Every Flow prompt must explicitly protect the established camera side, action
axis, screen direction, and relevant hand/object side. Document 20’s
`Framing Stability` field is the movement authority for that protection; this
system verifies that it is present and agrees with the packet.

No camera movement permits a cross-axis move. A new side requires a separately
approved reset or bridge shot from the board, then a new direction record under
Document 19. It is not an endpoint option in an otherwise continuous Flow clip.

### Editorial Handoff

At selection, provide the editor the source and destination facts, not merely a
thumbnail:

```text
Selected clip starts: [camera side, screen positions, hand/object state].
Selected clip ends: [camera side, screen positions, hand/object state].
Safe cut-in: [incoming asset ID / frame condition].
Safe cut-out: [outgoing asset ID / frame condition].
No-cut warning: [line, hand, object, or geography risk].
Approved reset / bridge: [asset ID], if applicable.
```

The editor does not repair a screen-direction error by flipping a clip unless
the entire approved packet is revalidated.

## Prompt-Packet Assembly

### Still-Image Camera Module

Use the direction-only module approved under Document 19, followed by factual
camera protections. Do not add a movement instruction.

```text
CAMERA DIRECTION — [VERBATIM OR APPROVED COMPACT DIRECTION MODULE FROM
19_CAMERA_DIRECTION_BIBLE].

CAMERA CONTINUITY LOCK — Preserve the approved camera side, action axis,
screen direction, subject placement, visible landmark relation, light
relationship, and caption-safe composition. This is a still frame; no camera
movement instruction.
```

### Google Flow Camera Module

Document 20’s five labeled fields are mandatory and remain in this order:

```text
Camera Direction: [approved Document 19 direction: shot size, camera side,
height/angle, subject placement, screen direction].

Camera Movement: [one approved Document 20 movement name].

Movement Speed: [approved Document 20 speed vocabulary].

Subject: [one approved action or environmental continuation; name the evidence
that remains readable].

Framing Stability: Start [approved frame]. End [approved frame or reveal].
Preserve camera side, action axis, screen direction, crop-safe area, and
[face/hands/object]. No [all unapproved camera behavior].
```

Do not alter these labels to blend them into literary prose. The larger Flow
prompt may carry source, style, character, object, state, light, and negative
locks around this module, but it may not conceal its direction/movement
separation.

### Source Mode Decision

| Requested result | Input control | Required camera check |
| --- | --- | --- |
| A truthful composed still | Still-image generation | Approved direction module and crop-safe frame. |
| Small continuation from one exact composition | One-image Flow | Source A is an approved literal start; end is achievable without a side change or undocumented reveal. |
| Exact cut-ready beginning and end composition | Two-image Flow | A and B are compatible direction records on the same side of the line, with continuous screen direction and one valid movement bridge. |
| New angle, reverse coverage, or reset of geography | Separate still / separate shot | New Document 19 direction approval and editorial bridge; never use Flow to discover it. |

Two images do not authorize incompatible viewpoints. If Source A and Source B
reverse screen direction, change time, alter object placement, cross the line,
or imply multiple moves, return to the board and sources.

## Operational Examples

### Example A: Static cooking insert

```text
Camera Direction: Close-Up, eye level, three-quarter view of Father’s hands
sorting seeds in a shallow brass bowl; bowl rim and textured seeds occupy the
lower frame, dhoti edge and sunlit yard remain softly visible behind; right
hand enters from screen right, preserve established hand continuity.

Camera Movement: Locked Camera.
Movement Speed: None; stable hold.
Subject: Father separates one small cluster of seeds. Keep both hands and the
brass bowl readable.
Framing Stability: Hold the approved close-up from start to end. Preserve the
camera side, action axis, screen direction, right-hand continuity, light, and
crop-safe space. No drift, pan, tilt, push, pull, zoom, shake, reframing, or
line crossing.
```

This is valid because direction, movement, speed, subject, and stability remain
separate. The movement is a deliberate hold under Document 20, not an omitted
field.

### Example B: One-image Flow continuation

```text
Source A: E04_S01_SH03_keyframe_v02 — approved Medium Full kitchen-door-side
frame.
Input mode: one-image Flow.

Camera Direction: Medium Full, eye level, three-quarter front from the
approved kitchen-door side; Mother faces screen right toward the stove; hands,
board, vessel, rear wall, and east-window relationship remain readable.

Camera Movement: Slow Push In.
Movement Speed: Very slow.
Subject: Mother completes one roll of dough. Keep her hands, board, vessel, and
face readable.
Framing Stability: Start the approved Medium Full. Make one small forward move
to a slightly tighter approved Medium Full; preserve camera side, action axis,
screen-right working direction, east-window light relationship, and lower
caption-safe space. No pan, tilt, zoom, camera-side change, line crossing,
shake, new action, or new kitchen area.
```

The source still supplies the exact beginning. The movement may make only the
small approved change; it cannot turn to reveal another side of the kitchen.

### Example C: Invalid request and correction

```text
Invalid: “Start behind Mother, orbit to her face as she cooks, then pull out to
show the family.”
```

Reject it. It has multiple movements, no approved start/end direction record,
likely changes camera side, asks Flow to discover coverage, and creates
unapproved family presence.

```text
Correction: Create a separately approved kitchen direction record for Mother’s
work under Document 19. Use a Locked Camera or one permitted movement under
Document 20. If the family’s relation is needed, plan a separate approved wide
shot and a clear editorial bridge.
```

## Camera-Lock QA

### Gate 1: Packet Completeness

Do not generate until all applicable answers are yes:

```text
[ ] The packet identifies direction and movement sources separately.
[ ] Direction derives from Document 19 and is approved.
[ ] Movement derives from Document 20 and is approved, including Static or
    Locked Camera where no travel occurs.
[ ] The direction field contains no movement verbs.
[ ] The movement field does not invent framing, camera side, or composition.
[ ] Shot purpose, format, duration, crop-safe area, and adjacent-shot relation
    are recorded.
[ ] Source image revision(s) and input mode are identified.
[ ] Every OPEN fact has an owner and the task is held where needed.
```

### Gate 2: Direction and Screen Direction

```text
[ ] Shot size, height, angle, camera side, subject placement, background, and
    light relationship are explicit in the approved direction record.
[ ] The action axis is documented where continuity needs it.
[ ] Screen positions, facing, eyelines, travel direction, and relevant
    hand/object side match the incoming shot and board.
[ ] The proposed source still is not mirrored or cross-axis.
[ ] The crop preserves required faces, hands, feet, object evidence, and
    location geography.
[ ] A reset or reverse has a separately approved bridge shot.
```

### Gate 3: Flow Readiness

```text
[ ] One-image or two-image mode matches the required endpoint control.
[ ] Source A is an approved literal start composition.
[ ] Source B, if used, is compatible in line, screen direction, light, state,
    and camera side.
[ ] The Document 20 five-field movement module is complete and ordered.
[ ] There is one approved movement behavior, finite path, story reason, and
    settled end frame.
[ ] Framing Stability explicitly protects camera side, action axis, screen
    direction, crop-safe area, and the relevant face/hand/object.
[ ] The request does not ask Flow to discover a new angle, location area, or
    coverage.
```

### Gate 4: Candidate Review

Review stills at full frame; review Flow candidates frame by frame where the
shot contains people, hands, transfers, food, recurring objects, rain, fire, or
complex geography. Reject if any occurs:

- the framing, height, side, or composition differs from the approved direction;
- a static or locked request drifts or reframes;
- a move exceeds its boundary, combines axes, becomes theatrical, or adds an
  unapproved zoom, shake, orbit, focus hunt, or camera-side change;
- the line is crossed or screen direction, gaze, travel, handedness, tool side,
  pot side, door side, or landmark relation reverses;
- a source/end frame no longer cuts to its approved neighbor;
- a required face, hand, foot, object, location clue, or crop-safe area is
  lost; or
- camera behavior creates false drama, surveillance, heroism, danger, or
  spectacle not present in the approved story.

### Acceptance Standard

Approve only a camera result that exactly preserves the approved direction,
uses only the approved movement behavior, retains screen geography throughout,
provides usable edit frames, and remains a calm observer of the approved
moment. A visually impressive camera error is rejected.

## Revision Workflow

Never reroll a camera failure without a diagnosis. Identify the first broken
authority, then change one responsible variable.

| Failure | Owning return point | Permitted correction |
| --- | --- | --- |
| Shot size, angle, side, or visible geography is wrong | Document 19 / board | Correct the direction record or regenerate the still. |
| Camera drift or excessive move | Document 20 / Flow packet | Restore one valid movement and its finite stability block. |
| Screen direction or line breaks | Document 19 / board / source still | Regenerate correct source or add approved reset bridge. |
| End frame cannot cut | Board, source A/B, or Document 20 | Correct endpoint source or split the shot; do not stretch the move. |
| Flow cannot reveal needed space | Board / Document 19 | Create a new approved shot and source still. |
| Character or object changes during motion | Character/object packet or source still | Repair the affected lock and source; do not solve with camera wording. |
| Crop loses important evidence | Document 19 direction / format plan | Revise composition or make a new shot; do not add a compensating move. |

Use one revision record per camera issue:

```text
Episode / scene / shot ID:
Prompt and camera-lock revision:
Candidate ID / source asset revision:
Observed failure and evidence frame / timestamp:
Failure class: direction / movement / screen direction / source / crop / edit:
Highest applicable authority:
Direction fields retained or changed:
Movement fields retained or changed:
Screen-direction state before / after:
One revision hypothesis:
Approved source A / B after revision:
Reviewer, decision, and dependent assets to recheck:
```

If the revision changes the selected source still, camera side, action axis,
screen direction, start/end frame, or movement endpoint, review every dependent
Flow clip, adjacent cut, and edit handoff. Escalate a conflict instead of
allowing different departments to keep incompatible versions.

## Roles And Handoffs

| Role | Camera-lock responsibility |
| --- | --- |
| Storyboard Artist / Shot Designer | Supplies shot purpose, cut logic, source direction context, axis, and screen-direction state. |
| Direction approver | Approves direction through Document 19. |
| Movement approver | Approves movement through Document 20. |
| Prompt Lead | Builds the packet, preserves separate fields, verifies sources, and logs revisions. |
| Image Generator Operator | Generates only from an approved direction lock and records source revision. |
| Google Flow Operator | Uses approved source images and the separate Document 20 Flow module; records candidates and settings. |
| Canon and Continuity Lead | Resolves conflicting facts and blocks drift. |
| Editor | Verifies actual cut compatibility; returns, rather than flips or hides, camera-continuity failures. |

### Required Handoff Record

No selected still or clip moves to the next owner without:

```text
Shot ID / asset ID / revision / status:
Approved direction source and approval:
Approved movement source and approval:
Input mode and source still revision(s):
Start and end camera-lock state:
Action axis / camera side / screen positions / hand-object state:
Crop-safe and delivery format:
Candidate QA result and reviewer:
Known limitations, prohibited reuse, and dependent asset IDs:
Incoming and outgoing edit bridge:
```

## Final Operating Rule

Protect the approved camera decision all the way through the asset lifecycle:
direction first under Document 19, movement separately under Document 20,
screen geography continuously, and a traceable packet, QA record, revision, and
handoff for every selected asset.
