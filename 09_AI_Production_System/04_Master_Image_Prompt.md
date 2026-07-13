# Master Image Prompt

## Purpose And Scope

This is the direct-use production manual and copy-ready master prompt for
Village Stories still-image generation. It turns an approved shot into a
bounded, canon-safe instruction for one usable still image.

Use it for storyboard stills, image-generation keyframes, Google Flow source
images, selected scene images, inserts, cutaways, repair generations, thumbnail
candidates, and continuity frames.

This manual does not create story facts, redesign a character, establish a
location, select an undocumented object, resolve research, or authorize release.
For the expanded supporting material, use
`09_AI_Production_System/04_Image_Prompt_Reference.md` (the Reference).

---

## Operating Rule

> Generate one truthful, editable view of one approved moment in the established
> Village Stories world. Do not ask the generator to invent the world.

If the frame cannot plausibly occur with the known people, place, period,
objects, weather, light, and emotional scale, reject it or return the earlier
decision to its owner.

---

## Authority Summary

This manual inherits authority; it creates no factual canon. Resolve conflict by
following the highest applicable source without averaging contradictions. Record
the conflict in the shot issue record, then revise the prompt or return the shot
to its owning stage.

```text
Current approved production decision
↓
01_Canon/ — timeline, continuity, global visual and style locks
↓
02_World/ · 03_Characters/ · 04_Objects/ · 05_Research/
↓
06_Story_Engine/ — story truth and emotional boundaries
↓
Approved episode brief, script, storyboard, and scene-state ledger
↓
07_Episode_System/ — format, pacing, opening, ending, visual rhythm
↓
08_Production/ — execution, QA, edit, and release
↓
09_AI_Production_System/01_Master_Workflow.md
↓
This manual and the Reference
↓
References, tool settings, candidate image, selected image
```

A prior generation, an appealing candidate, stock imagery, or a tool default is
never evidence that a conflicting fact is allowed. If a required fact is
`OPEN`, mark the shot `HOLD FOR CANON OR RESEARCH`; do not generate a recurring
or continuity-critical asset from it.

---

## Minimum Mandatory Locks

Apply these to every prompt. They are fixed instructions, not variables.

### World, Period, And Style

* Early-1990s rural Tamil Nadu; exact calendar year may be flexible, period is
  not.
* Specific, lived-in, practical, dignified rural Tamil world; never a generic
  exotic village or impoverishment spectacle.
* Period-correct work, clothing, objects, architecture, infrastructure, and
  problem solving.
* Original premium cinematic anime identity: semi-realistic anime characters,
  natural South Indian features and anatomy, soft painterly hand-painted digital
  rendering, layered natural colour and material texture, restrained organic
  linework, natural global illumination, story-serving composition, weather-
  grounded atmospheric depth, detailed culturally accurate environments, and
  warm restrained slice-of-life feeling.
* No named studio, artist, film, franchise, or other external-property
  imitation.
* No mobile phones, internet, digital screens, LED fixtures, modern appliances,
  contemporary vehicles, modern branding or packaging, current fashion, urban
  infrastructure, or unsupported modern items.

### Camera, Geography, And Light

* Select the approved shot direction, angle, framing, and screen-direction rule
  from `19_Camera_Direction_Bible.md`.
* This still-image prompt locks camera direction only. Any planned camera motion
  must be recorded separately and sourced from `20_Camera_Movement_Bible.md`.
* Camera is a patient human observer: natural, non-distorting, stable, and
  screen-geography aware.
* No fisheye, action-camera distortion, impossible aerial or drone view, Dutch
  angle, surveillance view, spectacle hero angle, or arbitrary lens drama.
* Morning light enters from the east; evening light enters from the west.
* The family house, rear yard, and kitchen lie west; paddy fields and pond east;
  village entrance, banyan tree, and river ghat north; fields, pond, and
  irrigation canal south.
* Light follows documented time, weather, architecture, and orientation. Never
  reverse sun direction across adjacent shots.
* Monsoon remains inviting with cool, diffused daylight; it is not a blue-black
  disaster or thriller treatment.

### Recurring People And Dog

Show a family member only when the approved scene gives them a source-backed
reason to be present.

When Mother is visible, preserve her approved identity, age, scale, posture,
hairstyle, practical cotton saree and blouse logic, expression, and relationship
behaviour. Preserve small traditional gold jhumkas, exactly one simple gold
chain with traditional thali pendant, small left-nostril gold nose pin, and thin
glass bangles. Never make her glamorous, bridal, fashion-styled, or a different
person.

When Father is visible, preserve the same individual established by
`11_Assets/Character_References/Father_Canon_Design_Reference.png`: thick
naturally tousled black hair, light natural stubble, warm medium-brown South
Indian complexion, calm observant expression range, lean farmer build with broad
shoulders and strong forearms, natural outdoor-worker posture, and approved
practical clothing. Never make him clean-shaven, heavily bearded, salon-styled,
gym-built, fashion-model glamorous, or a different man. Attach that reference as
`CHARACTER_IDENTITY` whenever the tool supports it and Father is a principal
subject, his face is visible, a new setup is established, a Flow source includes
him, or a repair corrects his identity.

The Family Dog is a gentle, loyal German Shepherd household companion. It may
wait, follow, observe, rest, respond softly, play naturally, or receive ordinary
care. Never depict aggression, threat, injury, chase, rescue, police/military
use, or exaggerated wolf features.

For expanded locks, source loading, and reference rules, see the Reference.

---

## Required Inputs

Do not assemble a final prompt until this brief is complete. Enter `NONE` only
for a genuinely unnecessary field. Enter `OPEN` only with a named owner and
resolution path.

```text
Episode ID:
Episode / scene / shot ID:
Prompt revision:
Image purpose: board / keyframe / insert / repair / thumbnail candidate:
Requesting owner:
Approval status of source scene:

Format: Shorts / long form / both:
Delivery aspect ratio:
Safe-crop requirement:
Target output dimensions or tool setting:

Scene purpose:
One-sentence visible story moment:
Start state:
Required image state:
What must be visibly clear:
What must not be implied:

Season:
Time of day:
Weather:
Visible weather consequence:
Approved location and source path:
Approved location zone / orientation:
Approved characters and source paths:
Approved objects and source paths:
Prior selected shot / continuity source:
Next shot or Flow use:

Composition plan:
Camera side and screen direction:
Shot size:
Subject placement:
Required foreground / middle ground / background:
Action pose and action boundary:
Expression and eyeline:
Lighting direction and motivation:

Required reference images:
Reference role for each image:
Negative constraints:
Known risks:
Open facts and owner:
```

---

## Compact Prompt Architecture

Build in this order. Keep permanent locks separate from scene facts so a
revision changes the responsible layer.

1. **Task declaration** — one still image, purpose, delivery ratio, primary
   visual read.
2. **Immutable canon envelope** — world, style, period, exclusions, camera.
3. **Hard scene conditions** — approved season, time, weather, location,
   motivated light, continuity bridge.
4. **Visible subject locks** — only visible or materially implied characters,
   animals, wardrobe, objects, and spatial relationships.
5. **One scene moment** — one observable action phase, proportionate
   expression, and required visible evidence.
6. **Composition** — shot size, height, side, subject position, direction,
   depth roles, eyeline, and crop-safe action.
7. **Material and finish** — only physically motivated weather, surfaces,
   texture, and atmosphere.
8. **References** — each attachment has one named role and controlled facts.
9. **Negatives and output** — likely failure prevention; one finished frame
   only.

---

## Copy-Ready Master Image Prompt Template

Copy this only after the brief is complete. Every `[VARIABLE: ...]` must be an
approved scene fact and may not override, remove, reinterpret, or weaken a hard
lock. If it conflicts, correct the variable and return the prompt for review.

```text
CREATE ONE FINISHED STILL IMAGE for Village Stories.

TASK AND OUTPUT
Production purpose: [VARIABLE: approved purpose].
Delivery: [VARIABLE: approved aspect ratio and dimensions].
Primary visual read: [VARIABLE: one approved visible story moment].
Frame requirement: one coherent frame, not a collage, poster, sequence, split
screen, contact sheet, or design sheet.

IMMUTABLE VILLAGE STORIES CANON — DO NOT OVERRIDE
Set in early-1990s rural Tamil Nadu. Preserve a specific, lived-in, dignified
rural Tamil world with period-correct work, clothing, objects, materials,
architecture, and infrastructure. No mobile phones, internet, digital screens,
modern appliances, LED fixtures, contemporary vehicles, branded modern
packaging, current fashion, urban infrastructure, or unsupported modern items.

Use the original Village Stories premium cinematic anime identity: semi-realistic
anime characters with natural South Indian features and believable anatomy; soft
painterly hand-painted digital rendering; layered natural colour and material
texture; restrained organic linework where it improves clarity; gentle natural
global illumination; story-serving film-quality composition; weather-grounded
atmospheric depth; detailed culturally accurate rural environments; warm,
observant, restrained slice-of-life emotion. This is an original visual identity.
Do not imitate or name any studio, artist, film, franchise, or existing visual
property.

The camera is a calm human observer at a natural, non-distorting viewpoint. No
action-camera look, fisheye, impossible drone angle, Dutch angle, spectacle hero
angle, surveillance framing, or arbitrary dramatic distortion.

CONTINUITY
Continuity from prior clip or shot: [VARIABLE: approved incoming character
positions, clothing condition, object state, completed action, emotional state,
screen direction, and light/weather match; use "Independent opening shot" only
when the board explicitly permits it].

HARD SCENE CONDITIONS
Season: [VARIABLE: approved season only].
Time and weather: [VARIABLE: approved time, weather, and visible consequence].
Location: [VARIABLE: approved location name, source, exact zone, orientation,
permanent landmarks, materials, and ground condition].
Lighting: [VARIABLE: approved motivated light source, direction, quality, and
required readability; must match global village orientation].
Continuity bridge: [VARIABLE: approved prior-state match or NONE].

SUBJECT
[VARIABLE: one sentence stating the complete visible story situation and why this
single frame matters].

CHARACTERS — INCLUDE ONLY APPROVED SUBJECTS
[VARIABLE: one compact block per visible subject: canon-backed identity,
clothing/current condition, pose, expression, position, eyeline, and reference
role.]

MANDATORY CHARACTER SUB-LOCKS WHEN APPLICABLE
If Mother is visible: preserve her approved South Indian identity, practical
cotton saree and blouse logic, small gold jhumkas, exactly one simple gold chain
with traditional thali pendant, left-nostril small gold nose pin, and thin glass
bangles. No additional necklaces or ornate fashion jewellery.

If Father is visible: preserve the same individual in
11_Assets/Character_References/Father_Canon_Design_Reference.png — thick
naturally tousled black hair, light natural stubble, warm medium-brown South
Indian complexion, calm observant expression, lean farmer build, and approved
practical clothing. Use the attached Father reference as CHARACTER_IDENTITY.
Do not copy its incidental pose or background unless separately required.

If the Family Dog is visible: preserve a gentle German Shepherd household
companion with natural anatomy and calm behaviour. No aggression, rescue, police
or military styling, threat posture, injury, or chase staging.

ACTION AND OBJECT STATE
Show exactly this approved action phase: [VARIABLE: one observable action in one
chosen phase, including who acts, what is handled, and what must visibly change
within this frame].
Required visible evidence: [VARIABLE: approved object, practical condition, or
relationship evidence].
Objects: [VARIABLE: approved period-correct object locks with material, scale,
position, handler, and current state; or NONE].
Do not add story events, people, props, animals, or background activity beyond
the approved scene need.

CAMERA
[VARIABLE: approved shot size, viewpoint height, camera side, subject placement,
screen direction, eyeline, foreground/middle/background roles, clear action
area, and delivery crop-safe area.]
Keep the essential face, hands, object state, and action unobstructed.

CAMERA MOVEMENT HANDOFF
Still-image prompt: request a stable single frame only; do not describe a camera
move as if it is already visible in a still.

Planned Google Flow movement: [VARIABLE: NONE for an edit still, or approved
camera movement, character movement, environmental movement, start/end boundary,
and explicit movement limits for the later animation prompt].

ENVIRONMENT
[VARIABLE: approved foreground, midground, and background elements; natural
materials; weather effects; depth detail; and visible location evidence only.
Do not add fantasy, glamour, nostalgia treatment, or unrelated genre styling.]

MOOD
[VARIABLE: one approved emotional atmosphere expressed through visible action,
light, posture, pace, and environment; never abstract melodrama.]

STYLE
Original premium cinematic anime illustration; semi-realistic South Indian
characters; soft painterly hand-painted digital rendering; natural colour
grading; soft global illumination; detailed early-1990s rural Tamil Nadu
environment; gentle slice-of-life feeling. Do not name or imitate any studio,
artist, film, franchise, or existing property.

REFERENCES
[VARIABLE: filename | role | controlled facts | facts it must not control.
Use NONE only when no reference is required by the canon packet.]

NEGATIVE PROMPT
No readable text, subtitles, signs, logos, labels, watermarks, borders, collages,
split screens, duplicate people, extra limbs, malformed hands, deformed anatomy,
modern technology, contemporary packaging, modern clothing, plastic CGI,
hyper-real faces, heavy cel shading, chibi proportions, comic outlines,
vector-flat graphics, neon lighting, named-studio imitation, named-artist
imitation, melodramatic danger, disaster imagery, or any element conflicting
with hard canon.
[VARIABLE: approved scene-specific negatives only; these cannot weaken prior
exclusions.]

RETURN ONE CANON-SAFE, EDIT-READY STILL FRAME ONLY.
```

---

## Variable Validation

Before generating, confirm every variable:

* comes from an approved brief, board, or canon source;
* does not use “inspired by,” “like,” or a named external property;
* adds no unapproved person, object, animal, location, or background action;
* preserves Mother’s one thali chain and jhumkas when visibility permits;
* preserves Father’s canon-reference requirement;
* retains the early-1990s rural Tamil Nadu lock;
* requests no modern or unresearched item;
* contains one principal action phase;
* matches screen direction, geography, and light continuity;
* requests no drama beyond the approved scene; and
* does not convert optional decoration into required story evidence.

---

## Prompt Assembly Procedure

1. Confirm that the source scene is approved for image work.
2. Complete the image brief and create a compact canon packet.
3. Classify each packet item as `HARD LOCK`, `SCENE FACT`, `OPTIONAL DETAIL`,
   `OPEN FACT`, `NEGATIVE`, or `REFERENCE`.
4. Stop and resolve any open or contradictory hard lock.
5. Select only the visible character, location, object, style, and camera locks.
6. Select the one action phase represented by this still.
7. Set the delivery ratio and crop-safe action zone.
8. Attach only necessary approved references, with one primary role each.
9. Mark the still as independent, continuity-match, one-image Flow, or
   two-image Flow input.
10. Complete the template without changing the immutable envelope.
11. Run variable validation and read the prompt against the approved board.
12. Generate a small, deliberate candidate set.
13. Review every candidate against the QA gates before selecting, repairing, or
    revising.

Do not repeatedly regenerate an unchanged prompt after a predictable failure.
Diagnose the defective layer first. Detailed lock selection, reference planning,
Flow decisions, framing rules, and priority order are in the Reference.

---

## Output QA Gates

Review the candidate image, not the prompt’s intention.

### 1. Fact And Period

Reject for a modern item, unsupported infrastructure, incorrect season or
weather consequence, reversed sun, wrong location geometry, incorrect object
material, unapproved readable text, or invented plot fact.

### 2. Character And Animal

Reject if any recurring person is not recognizably the same individual; face,
age, build, hair, skin tone, wardrobe, jewellery, relationship behaviour, or
screen side drifts; Father conflicts with his reference; Mother’s reasonably
visible required jewellery is wrong; the Dog is threatening or injured; an
unapproved person appears; or anatomy, hands, eyes, or scale are unusable.

### 3. Scene And Object

Reject if the one action phase, required object, object state, proportionate
expression, approved background activity, or cut continuity is wrong.

### 4. Style

Reject named-property imitation, generic AI anime, glossy CGI, hyper-real
portraiture, chibi comedy, heavy cel shading, vector art, neon fantasy, or
action/thriller treatment.

### 5. Composition And Delivery

Reject if action is unreadable at delivery size; the crop removes evidence;
screen direction is broken; the face, hand, or prop is blocked; visual priority
is unclear; Flow action is unsupported; a watermark or text appears; or the
image has no shot purpose.

```text
APPROVE — all required checks pass
APPROVE WITH CROPPING NOTE — safe only for documented delivery use
REPAIR — isolated correctable defect; preserve approved parts
REGENERATE — prompt-layer defect affects the shot
RETURN TO BOARD — intent, action, or composition is unclear
HOLD FOR CANON — required fact is open or contradictory
REJECT — materially unusable or violates a hard lock
```

---

## Revision And Rejection Summary

Revise the smallest responsible layer. Use repair only when the scene moment,
identity, and composition are sound and the defect is local. Regenerate when
identity, location geometry, action phase, composition, or multiple coupled
defects are wrong.

Reject immediately for named-property imitation, modern technology or branding,
recurring-character redesign, false danger or child endangerment, threatening
Dog, wrong historical world, unusable anatomy, readable accidental text, a
collage/sequence, or drama beyond the approved story. Never reuse a rejected
candidate as a reference.

Record `Shot ID`, `Candidate ID`, decision, defect severity, observed evidence,
failed layer, change made, retained locks, new prompt/reference revision,
reviewer, and date. Use the detailed diagnostic map and repair guidance in the
Reference.

---

## Scene Handoff

An approved image hands off a record, not merely a file.

```text
Episode / scene / shot ID:
Selected asset filename and revision:
Prompt revision:
Tool and available settings:
Source brief and canon-packet revisions:
Attached references and roles:
Approved composition and delivery ratio:
Start-state / end-state ledger entry:
Character positions and screen direction:
Object positions and state:
Season, time, weather, and light:
Flow suitability: none / one-image / two-image:
Required Flow action boundary:
Adjacent shots:
QA result and reviewer:
Known crop, repair, or edit notes:
```

For Google Flow, send the selected still, approved motion purpose, exact action
start/end limits, camera restriction, continuing reference roles, crop and
duration requirements, rejection criteria, and continuity record. The operator
may not add a character, location, time jump, weather escalation, object,
emotional reversal, or dramatic camera move.

For the edit, send the intended cut-in/cut-out relation, screen direction,
crop-safe bounds, action-readability notes, planned caption-safe area, whether
stillness is intentional, sound-transition intent, and thumbnail-candidate
status.

---

## Concise Examples

### Mother And Seedling — Vertical Short

Use a medium 9:16 view of Mother crouching beside a seedling, calmly guiding
Younger Daughter’s small hand holding the documented water vessel. Show darkening
soil, not the whole watering sequence. Lock Mother’s identity and jewellery,
Younger Daughter, garden, vessel, summer morning east light, and a central
protected action zone. This is a gentle Flow-capable teaching moment, not an
emotional spectacle.

### Father Repairs A Handle — Long Form

Use a medium-wide 16:9 rear-yard view. Father, in approved work clothing, sits
beside the documented object with his hands and the loosened handle visible,
calmly focused downward. Attach the Father identity reference; lock rear-yard
orientation, pre-repair object state, next-cut screen side, and late-afternoon
west light. No heroic repair pose.

### Monsoon Kitchen Insert

Use a close insert of documented damp wood near the kitchen hearth, with soft
diffused monsoon daylight at the doorway and a small believable amount of smoke.
Exclude modern fixtures and oversized dramatic flame. The insert establishes a
practical condition; it does not turn rain into danger.

For detailed positive and negative examples, edge cases, and non-examples, see
the Reference.

---

## Related Documents And Final Authority

Use this manual with `09_AI_Production_System/01_Master_Workflow.md`,
`02_Master_Story_Prompt.md`, `03_Master_Script_Prompt.md`, the companion
`04_Image_Prompt_Reference.md`, and applicable Canon, World, Character, Object,
Research, Episode System, and Production sources.

The Story Engine decides whether a moment belongs in the series. The Episode
System decides how the episode serves the viewer. Production decides execution,
files, edit, and release. This manual controls reusable still-image prompt
assembly within the AI Production System; it does not override higher sources.

If a higher authority changes, rebuild affected canon packets and revalidate the
prompt, references, selected still, Flow input, and edit use.

Before selecting any generated still, ask:

> Does this image preserve the known people, place, period, objects, light, and
> emotional scale while making one approved action immediately usable?

If the answer is no, reject the image or revise the earliest responsible
decision. Do not ask an image generator to make an unsupported world feel true
after the fact.
