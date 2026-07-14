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
* Original Village Stories anime identity matching
  `11_Assets/Character_References/Mother_Canon_Design_Reference.png`: smooth
  digital anime illustration; polished digital painting with soft gradient
  shading; atmospheric depth; muted cinematic color grading; Japanese anime color
  palette on Indian village settings; clean defined line art; clean-up drawing;
  natural South Indian features; emotionally warm and timeless.
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
`11_Assets/Character_References/Father_Canon_Design_Reference.png`: **strong
structured masculine face** with **prominent angular jawline** (never soft-round);
medium-to-fair warm golden complexion; **warm brown eyes** ~1/5 face height; thick
wavy black medium-length hair with soft side part; **neatly trimmed solid black
moustache** with clean-shaven jaw; **lean athletic build** 5'5"–5'7"; calm
confident presence; white/cream veshti #F5E6C8, light shirt rolled sleeves,
barefoot. Never soft round face, weak jaw, clean-shaven, stubble, gym-built, or a
different man. Attach as `CHARACTER_IDENTITY` whenever the tool supports it and
Father is principal, face-visible, establishing, or being repaired.

The Family Dog is a gentle, loyal German Shepherd household companion with
**classic black-and-tan, fully fluffy** coat — black saddle/back, rich tan/cream
on legs, chest, belly, muzzle, and eyebrows. It may wait, follow, observe, rest,
respond softly, play naturally, or receive ordinary care. Never depict solid
all-black coat, aggression, threat, injury, chase, rescue, police/military use,
or exaggerated wolf features.

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

Use this exact section order and headings in every episode image prompt.

```text
IMAGE PROMPT — [VARIABLE: Clip or Shot ID]

CONTINUITY
[VARIABLE: sequence position; prior clip/shot bridge; who and what remain fixed
from the previous approved frame; same location, lighting, weather, props, and
environment; season and time unchanged.]

Framing Note: [VARIABLE: composition intent for this still and any space or pose
requirement needed for the planned Google Flow animation. Use NONE only when no
Flow follow-up is planned.]

SUBJECT
[VARIABLE: one sentence stating the complete visible story situation and why this
single frame matters.]

ACTION
[VARIABLE: full observable action in one chosen phase. State who does what,
where they face, eyeline, gaze direction, body orientation, hand/object
contact, and what must be unmistakably clear. Repeat gaze-critical details when
a character or animal must look at a specific subject, not the camera.]

CAMERA
| Element | Specification |
| --- | --- |
| Shot Type | [VARIABLE: approved shot size] |
| Camera Height | [VARIABLE: approved height relative to subject] |
| Camera Angle | [VARIABLE: approved viewpoint, side, and screen geography] |
| Lens Feeling | [VARIABLE: natural cinematic perspective; no distortion drama] |
| Composition | [VARIABLE: foreground / midground / background roles; subject
placement; what must remain visible and unobstructed] |
| Depth of Field | [VARIABLE: focus priority and background softness] |
| Animation Preparation | [VARIABLE: space, pose, or framing note for the next
Flow clip; or NONE] |

STYLE
Studio Ghibli-inspired digital anime aesthetic — soft, warm, and emotionally resonant. Painterly digital rendering with simulated watercolor and gouache textures. Soft matte finish. Soft delicate linework with slight variation. Naturalistic anime proportions; soft rounded faces; expressive but grounded eyes approximately 1/5 of face height. Soft cel-style shading blended with painted digital brushwork. Richly illustrated digital backgrounds with atmospheric depth. Authentic 1990s South Indian village atmosphere, emotionally warm and timeless.

Family Dog (STRICT Character Lock)
Large healthy German Shepherd with a **classic black-and-tan, fully fluffy** long
double coat — **black saddle and back**, **rich tan/cream on legs, chest, belly,
muzzle, and eyebrows**. Thick fluffy neck ruff, feathered legs, full bushy tail
curled naturally. Warm intelligent brown eyes, gentle happy expression. Soft
Ghibli-inspired digital anime animal rendering. NOT solid all-black.

Mother (Character Bible Lock)
Young South Indian woman (28–30), warm medium-brown skin, expressive warm brown
eyes gently closed in laughter, long naturally wavy black hair braided over one
shoulder, small maroon bindi, mustard or dark green traditional cotton saree,
small traditional gold jhumkas, exactly one simple gold chain with traditional
thali pendant, small left-nostril gold nose pin, thin glass bangles, gentle
affectionate smile.

Father (Character Bible Lock)
South Indian farmer (31–33), medium-brown complexion, lean athletic build with
broad shoulders, thick black medium-length hair slightly textured and sometimes
tousled, neatly trimmed black mustache with clean-shaven jaw, warm brown eyes,
handsome traditional features, light-coloured cotton shirt with rolled sleeves,
white cream veshti with thin gold kasavu border, barefoot, calm confident gentle
smile. Match 11_Assets/Character_References/Father_Canon_Design_Reference.png
for identity.

ENVIRONMENT
Traditional backyard beside the permanent stone well from the World Layout
Bible. Include: circular weathered stone well, wooden pulley, thick rope, brass
bucket, moss-covered stone washing platform, curry leaf tree, banana plants,
coconut palms, soft drifting evening breeze, warm golden sunlight, authentic
early-1990s South Indian village backyard.

LIGHTING
Warm golden-hour sunlight from the west softly illuminates the side of the
German Shepherd's face and fluffy coat while creating delicate rim lighting
around Mother and Father. Long soft shadows stretch naturally across the yard.

ATMOSPHERE
A peaceful, intimate family reunion witnessed by their loyal companion. Warmth,
safety, nostalgia and unconditional affection.

NEGATIVE PROMPT
Dog facing the camera, dog looking at the viewer, front-facing dog, symmetrical
dog pose, dog blocking the couple, dog looking away from the couple, incorrect
gaze direction, generic shepherd, chibi proportions, Western cartoon style,
photorealistic rendering, CGI, 3D rendering, plastic textures, modern objects,
text, watermark, logo, extra limbs, duplicate animals, distorted anatomy,
named-studio imitation.
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
