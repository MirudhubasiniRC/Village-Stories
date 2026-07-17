# Camera Movement Bible

## Permanent Purpose

This is the permanent studio cinematography manual and the sole operational
authority for **camera movement** in Village Stories storyboards, production
planning, image-to-video briefs, and Google Flow animation prompts.

It defines how the camera may move, how slowly it may move, why a movement is
chosen, where it begins and ends, and when it must not move. It is written for
repeatable production decisions, not for decorative cinematography.

The camera is a calm human observer in early-1990s rural Tamil Nadu. It quietly
witnesses ordinary life. The viewer should remember the family, their work, the
weather, and the village—not a conspicuous camera move.

> Move the camera only when a still frame cannot express the approved story
> beat as clearly, calmly, and continuously.

Stillness is a valid and frequent cinematographic decision. A technically
possible move is not a reason to use it.

---

## Authority, Scope, And Precedence

This document inherits all higher canon and creates no story, visual, location,
character, object, weather, period, or emotional facts.

```text
Current approved production decision
↓
01_Canon/ — timeline, continuity, style, animation, and camera philosophy
↓
02_World/ · 03_Characters/ · 04_Objects/ · 05_Research/
↓
06_Story_Engine/ — story truth and emotional limits
↓
Approved episode brief, script, storyboard, scene-state ledger
↓
07_Episode_System/ — pace, format, rhythm, and episode purpose
↓
08_Production/ — execution, editorial, QA, and delivery
↓
09_AI_Production_System/01_Master_Workflow.md
↓
09_AI_Production_System/19_Camera_Direction_Bible.md
↓
This document: 20_Camera_Movement_Bible.md
↓
Google Flow settings, generated candidates, selected clip
```

If sources conflict, follow the higher applicable source. Never average two
conflicting instructions. Mark an unresolved required fact `HOLD FOR CANON OR
BOARD` and do not invent a movement to conceal it.

This document is the sole operational authority for:

- movement names and their meanings;
- movement speed language and practical limits;
- movement start and end boundaries;
- movement suitability by story purpose;
- Flow camera-movement prompt wording;
- movement-related QA and correction;
- editorial continuity caused by movement.

The higher-level camera philosophy remains in
`01_Canon/01_Series_Style_Lock/Camera_Language.md`. This manual must obey it.

The master Flow assembly and source-control procedure remain in
`09_AI_Production_System/05_Master_Animation_Prompt.md`. This manual supplies
the camera-movement module used there.

---

## Camera Movement Is Not Camera Direction

Camera direction is defined only by the separate
`09_AI_Production_System/19_Camera_Direction_Bible.md`.

**Camera direction** answers where the camera is and what it is looking at:

- shot size and framing;
- camera side of the action;
- height and angle;
- lens feeling;
- screen direction and line of action;
- subject placement, eyeline, crop-safe space, and composition;
- whether a shot is a wide, medium, close-up, reverse, over-the-shoulder, or
  other approved shot selection.

**Camera movement** answers how that already-approved camera travels or holds
during one continuous shot:

- whether the camera holds, pans, tilts, tracks, rises, arcs, or orbits;
- its path, speed, extent, and endpoint;
- what visible story information the movement reveals or follows;
- what it must not cross, obscure, alter, or newly introduce.

Do not use movement wording to repair an undefined direction. “Move around
Father” does not define camera side, frame, line of action, or endpoint. Obtain
those from the direction document and the approved board first.

Likewise, do not use direction wording as a substitute for a movement
instruction. “Medium side view of Mother” defines a frame; it does not say
whether the camera holds, pans, or tracks.

Every movement instruction therefore begins with an approved direction and adds
only one camera behavior.

```text
Camera Direction: Medium side view from the approved kitchen doorway, Mother
screen-left facing the stove screen-right.

Camera Movement: Locked Camera.

Movement Speed: None; stable hold.

Subject: Mother lifts the lid once; steam rises naturally.

Framing Stability: Hold the established medium frame, camera side, eye level,
and caption-safe lower area. No reframing.
```

---

## Non-Negotiable Series Camera Laws

- Treat the camera as a physically possible, calm human observer.
- Default to a static or locked camera.
- Use one camera movement maximum in one Flow clip.
- Use the smallest movement that communicates the approved beat.
- Keep movement slow, smooth, motivated, and almost unnoticed.
- Preserve the established camera side and line of action.
- Preserve screen direction unless the approved board establishes a motivated
  reversal in a separate shot.
- Preserve location geography, landmark relations, time, light direction,
  weather, season, character identity, wardrobe, jewellery, props, and state.
- Maintain readable faces, hands, tools, food, and important object evidence.
- Do not move crucial information into a crop, edge, subtitle, or Shorts UI
  zone.
- Let a moving shot settle before it ends whenever the duration permits.
- Cut rather than force multiple discoveries into one camera move.

Never use camera movement to manufacture danger, urgency, romance spectacle,
melodrama, heroism, surveillance, or action energy that the approved scene does
not contain.

The following are prohibited unless a higher approved document makes a specific,
exceptional, documented authorization:

- whip pans;
- snap tilts;
- fast zooms and crash zooms;
- zoom-burst simulation;
- camera shake;
- action-camera or body-mounted look;
- drone-style flyovers;
- fisheye or extreme wide-lens distortion;
- Dutch-angle movement;
- unmotivated spins;
- long circling moves;
- focus hunting used as spectacle;
- repeated reframing;
- camera-line crossing;
- impossible movement through walls, foliage, cookware, people, or furniture.

---

## Movement Decision Rule

Before selecting a movement, answer all five questions:

1. What single visible fact must the viewer notice?
2. Why is an unchanged frame insufficient?
3. What approved frame does the move start in?
4. What approved frame or resting composition does it end in?
5. Can this happen with one simple path and no camera-line crossing?

If any answer is unknown, use `LOCKED CAMERA` or return to the board.

Use this preference order:

```text
1. Static composition
2. Locked camera
3. Slow push in or slow pull out
4. Slow pan or subtle tilt
5. Short truck or short dolly
6. Gentle arc or crane
7. Orbit only as a rare, explicitly justified exception
8. Handheld only as an almost-never exception
```

“More cinematic” is never a valid justification. A movement must serve one of
the following approved purposes:

- reveal an already-approved detail;
- follow a small, grounded change of position;
- gently connect two already-approved areas of one space;
- make a contained emotional change legible;
- open a spatial relationship required by the story;
- observe atmosphere without adding event or emphasis.

---

## Speed Vocabulary And Duration

Google Flow does not need arbitrary camera-speed numbers. Use plain,
observable speed language paired with a finite endpoint.

| Studio term | Meaning | Default use |
| --- | --- | --- |
| None | No camera travel or reframing. | Static and locked shots. |
| Nearly imperceptible | The frame changes only slightly across the clip. | Intimate emotion and atmospheric holds. |
| Very slow | A patient movement with no visible acceleration. | Most approved moving shots. |
| Slow | Readable, calm travel with stable framing. | Short follows and simple reveals. |
| Measured | The upper limit for an ordinary-life move; never brisk. | A bounded track or necessary crane. |

Do not use `fast`, `dynamic`, `energetic`, `sweeping`, `cinematic`, `dramatic`,
`rapid`, `whip`, `rush`, `glide through`, or `soar` as Flow camera-speed
instructions. They invite spectacle, drift, or an unbounded path.

### Practical Duration Bands

| Delivery duration | Suitable camera behavior |
| --- | --- |
| 1–2 seconds | Static, locked, or a barely perceptible push/pull only. |
| 2–4 seconds | One simple pan, tilt, push, pull, or very short truck/dolly. |
| 4–6 seconds | One clear action plus a calm, finite move and short settle. |
| Over 6 seconds | Prefer an editorial cut into two approved clips; do not stretch a move to fill time. |

The correct duration is the shortest time that makes the start, change, and
settled end readable. A candidate is not usable merely because it fills the
requested seconds.

---

## Universal Movement Boundaries

Every movement must include all of the following boundaries in the board or
Flow prompt:

```text
Start frame: [approved shot size, camera side, height, subject relation].
Movement: [one named movement] [left/right/up/down/in/out if applicable].
Speed: [none / nearly imperceptible / very slow / slow / measured].
Path extent: [small, finite description].
End frame: [approved resting composition or exact reveal].
Subject protection: [face / hands / object / path that stays visible].
Continuity protection: [line of action, screen direction, light, state].
Prohibitions: [no other reframing, zoom, shake, crossing, or new action].
```

Movement boundaries are not optional polish. They prevent Flow from turning a
small instruction into a roaming or multi-axis camera.

Never combine:

- pan plus push;
- pan plus tilt;
- dolly plus orbit;
- truck plus arc;
- crane plus orbit;
- any move plus a simulated zoom;
- a camera move plus complex subject travel;
- multiple camera moves in sequence.

If a planned shot needs two movements, split it into two shots with a cut and
record the bridge.

---

## Google Flow Camera-Movement Standard

Use these five labeled fields, in this order, for every Flow animation prompt.
The surrounding master prompt may add locks, but the movement module must remain
separate and explicit.

```text
Camera Direction: [Approved direction from 19_Camera_Direction_Bible.md:
shot size, camera side, height/angle, subject placement, screen direction.]

Camera Movement: [One approved movement name and only its necessary direction.]

Movement Speed: [None / nearly imperceptible / very slow / slow / measured.]

Subject: [One approved visible action or environmental condition; name what the
camera must keep readable.]

Framing Stability: Start [approved frame]. End [approved frame or reveal].
Preserve camera side, line of action, screen direction, crop-safe area, and
[face/hands/object]. No [all other camera behavior].
```

Use complete, physical language. Prefer:

```text
Camera Movement: Slow Push In.
Movement Speed: Very slow.
Framing Stability: Start medium two-shot; end a slightly tighter medium
two-shot after one small forward move. Hold the same camera side and keep both
faces visible. No pan, tilt, zoom, shake, or line crossing.
```

Avoid vague, compound, or aesthetic-only language:

```text
Camera Movement: Make the camera cinematic and emotionally move around them.
```

The second example gives Flow no bounded route, no end frame, no continuity
protection, and no usable editorial result.

### One-Image Flow Implication

With one approved source still, choose a movement that can grow naturally from
the exact source composition. The source is the non-negotiable start frame.

Use one-image input for:

- a static or locked observation;
- a tiny push or pull;
- a short pan or tilt across already-visible, source-supported space;
- a brief truck/dolly following one small action;
- controlled environmental continuation such as rain, steam, or leaves.

Do not use one image to ask Flow to discover a radically different end angle,
travel behind a subject, reveal undocumented space, complete a large arc, or
change the camera side. Make a new approved source or use two images when an
exact endpoint is required.

### Two-Image Flow Implication

With two approved stills, Source A is the exact start state and Source B is the
exact end state. The movement is only the continuous bridge between them.

Use two-image input when:

- the ending composition must cut directly to the next shot;
- a small dolly, truck, crane, or arc has a specific approved endpoint;
- a reveal exposes a continuity-critical object or person;
- the subject or prop state must be precisely retained at the end;
- the board requires two clearly different but compatible frames.

Do not use two images to license incompatible viewpoints. If A and B cross the
line, reverse screen direction, alter time or weather, move a prop without a
visible path, or imply several moves, repair the board and sources first.

---

## Movement Library

For external filmmaking terms and AI-suggested moves, translate through
**§ Flow Synonym Map And Forbidden Prompt Language** before prompting Flow.

### Static

**Definition**  
A static shot is a deliberate unmoving composition. The camera does not travel,
pan, tilt, zoom, reframe, shake, or seek a new angle. The world may continue
with approved natural motion inside the frame.

**Purpose**  
Static observation lets the viewer inspect a truthful moment without being
directed by camera emphasis. It is ideal when the action, composition, sound,
or natural atmosphere already carries the beat.

**Emotional effect**  
Patient, truthful, settled, domestic, contemplative, and dignified. It can also
make a small action feel important because the camera refuses to exaggerate it.

**Recommended speed**  
None.

**Google Flow compatibility**  
Excellent. It is the safest option for identity, hands, cookware, food,
weather, and continuity-critical frames.

**Use**  
Use for a child watching rain, a pot simmering, hands sorting lentils, a dog
waiting near the doorway, a family member listening, or a wide village frame
with subtle life.

**Do not use**  
Do not use when the approved purpose is a spatial reveal that cannot be seen in
the frame, or when a subject must be followed across enough space to leave the
approved composition.

**Common mistakes**

- Calling a static shot “locked” while asking Flow to slowly zoom.
- Adding several unapproved background motions because the camera is still.
- Letting a subject drift out of frame instead of cutting or using a short,
  planned track.
- Treating a static frame as empty and filling it with invented business.

**Positive example**

```text
Camera Direction: Close view of Mother’s hands at the stone grinder, from the
approved kitchen side.
Camera Movement: Static.
Movement Speed: None.
Subject: Her hands complete one slow grinding pass; the bowl remains steady.
Framing Stability: Hold the exact close composition. Keep hands, stone, and
contents visible. No reframing, zoom, pan, tilt, shake, or camera-line change.
```

**Negative example**

```text
Keep the camera still but gradually zoom, circle the grinder, and reveal the
whole kitchen.
```

**Duration**  
1–6 seconds. Prefer 2–4 seconds for an insert or contained action. Cut before
the action loops or the moment becomes inactive.

**Movement boundaries**  
Keep the physical position and frame essentially fixed. Any visible shake,
reframe, drift, or travel fails the exception unless separately specified and
approved. Preserve all normal camera-side and subject-protection rules.

**Camera-direction pairings**  
Exception only, and only with a documented, stable close or medium direction.
Never pair handheld with wide establishing frames, side-follow shots, or
line-sensitive dialogue coverage.

---

## Preferred Movement By Story Purpose

The following selections are defaults, not permission to override the approved
board. If the board’s visible beat does not need the listed move, remain static
or lock the camera.

### Cooking

Cooking is a sequence of real hand actions, tools, ingredients, heat, steam,
and changing food state. Clarity of hands and object continuity is more
important than camera activity.

Preferred movement:

- Static for ingredients, grinding, stirring, pouring, cutting, serving, and
  heat details.
- Locked Camera for a complete small cooking action or dialogue during work.
- Tilt Down only when the approved purpose is to connect the cook to hands and
  a vessel.
- Very small Pan Left/Right only to reveal a source already adjacent in the
  established kitchen, such as steam to pot.
- Slow Push In only for an earned, quiet completion or careful detail.

Avoid truck, dolly, arc, crane, orbit, and handheld in ordinary cooking. A
kitchen’s dense geometry, hands, smoke, vessels, and fire are fragile. Use
separate inserts and cuts instead of moving around the work.

```text
Camera Direction: Approved close side view of the clay stove and Mother’s hands.
Camera Movement: Locked Camera.
Movement Speed: None; stable hold.
Subject: Mother stirs the pot once; steam rises naturally.
Framing Stability: Keep both hands, spoon, pot rim, and fire area visible. No
reframing, zoom, drift, extra cookware, or altered ingredient state.
```

### ASMR And Sensory Detail

ASMR-style shots are about material behavior: grain falling, ladle touching
metal, water pouring, leaves brushing, rain landing, grinding stone turning,
and fire or steam moving softly. The camera must not compete with the sound and
texture.

Preferred movement:

- Static as first choice.
- Locked Camera as the explicit Flow production default.
- Slow Push In only when a detail becomes the sole approved focus.
- Tilt Down or Tilt Up only for a short, clear material relation.

Do not use pans that hunt for a sound, camera drift that softens the texture,
or any movement that changes the subject size while the key sound occurs.
Avoid handheld completely.

### Family Moments

Family warmth is expressed through posture, glance, timing, touch, and shared
space—not through camera spectacle.

Preferred movement:

- Locked Camera for conversations, shared tasks, listening, food, and quiet
  reactions.
- Static for small gestures or a family tableau.
- Slow Push In for one contained, understated emotional recognition.
- Slow Pull Out when an intimate detail needs to return to the shared home or
  family context.
- A rare short Arc only when it has an approved, non-dramatic spatial reason.

Never orbit a family, whip into a smile, use a rapid push for sentiment, or
shake the camera to manufacture emotion.

### Conversations

Conversation coverage depends on eye lines, camera side, screen direction, and
readable pauses. Direction is set in document 19; movement here must preserve
it.

Preferred movement:

- Locked Camera for almost all conversation coverage.
- Static for an over-the-shoulder, two-shot, or listening close-up.
- Slow Push In only on one restrained interior response, not every line.
- Slow Pull Out only when the approved end requires a shared spatial context.

Do not pan between speakers within a line-sensitive exchange, truck around a
conversation, arc across the line, or reframe to chase every gesture. Use
separate approved shots and editorial cuts.

### Nature

Nature is a living context, not a travel-reel spectacle. Let wind, water,
insects, birds, shadows, leaves, mist, or rain provide the motion.

Preferred movement:

- Static and Locked Camera for leaves, water, insects, birds at rest, field
  texture, light, and weather.
- Slow Pan for one already-visible lateral relation, such as canal to field.
- Slow Tilt for a close vertical relation, such as droplets to banana leaves.
- Slow Pull Out only for a modest context reveal in documented scenery.
- Rare gentle Crane only within a physically plausible local relation.

No drone flyovers, sweeping landscape scans, time-lapse feeling, speed ramps,
or large aerial rises.

### Village Establishing

An establishing shot must clarify geography, time, season, and ordinary life.
It is not an invitation to tour the entire village.

Preferred movement:

- Static wide or Locked Camera wide as primary choice.
- Slow Pan only across one documented, continuous, limited village relation.
- Slow Pull Out only when it reveals a nearby approved context from a closer
  start.
- Rare local Crane when specifically boarded and physically plausible.

Use a cut to establish another sector. Do not fly above roofs, travel through
lanes, orbit landmarks, or use a grand reveal.

### Rain

Rain is read through falling direction, droplets, surface ripples, wetness,
roof edges, leaves, vessels, and character behavior. The camera should make the
weather legible without turning it into crisis.

Preferred movement:

- Static and Locked Camera for threshold rain, roof drip, puddles, hands, dog,
  and family observation.
- Tilt Up/Down for a short approved connection between a roof edge, leaf, and
  droplets or between rain and a puddle.
- Slow Push In for a quiet face or tactile rain detail.
- Slow Pan only from one nearby weather cue to its already-established source.

Do not use handheld, shake, racing tracks, dramatic cranes, storm reveals,
lightning-style flashes, or movements implying danger unless higher canon
explicitly requires a calm, documented exception.

### Emotion

Emotion must remain restrained, behavior-led, and truthful. The lens does not
perform the feeling for the character.

Preferred movement:

- Locked Camera for tears held back, listening, concern, relief, affection,
  disappointment, or contemplation.
- Static for a face, hands, or shared silence.
- Nearly imperceptible Slow Push In for a single already-visible realization.
- Slow Pull Out for a gentle return from a private moment to a truthful context.

Never use a push as a shock cue, an orbit as a romance cue, handheld as
distress, or a crane as emotional elevation.

### Daily Routines

Routines are the series’ core observational material: sweeping, carrying water,
feeding animals, washing, sorting, walking to a nearby place, tending plants,
and preparing food.

Preferred movement:

- Static and Locked Camera for most routines.
- Short Truck for two or three grounded steps in an open documented path.
- Slow Pan for a small lateral action that remains in one space.
- Tilt for a direct relation between a person and task.
- Slow Pull Out only when the routine’s spatial context is necessary.

Do not follow a full routine in one continuous clip. Break it into clear task
beats with purposeful cuts.

---

## Character, Location, Season, And Object Application

Movement never changes a character’s documented behavior, identity, clothing,
appearance, emotional scale, or capability. It merely observes the approved
moment.

### Father

When Father is visible, preserve the same recurring individual and all approved
identity details. His grounded work may support a locked side view, a short
truck alongside two steps, or a modest pan to a tool he already handles.

Do not use aggressive tracking, hero push-ins, low-angle power moves, orbiting,
or athletic camera language. His strength is ordinary and unperformed.

### Mother

When Mother is visible, preserve her approved face, bindi, nose pin, jhumkas,
single thali chain, bangles, practical saree, and task continuity. Cooking and
home routines normally require static or locked coverage so hands, jewellery,
and utensils remain stable.

Any movement must protect jewellery continuity and avoid glamour framing,
fashion movement, or camera behavior that objectifies routine work.

### Children And Family Dog

Observe children at a physically plausible height and with calm, safe distance.
Use static or locked shots for play, learning, waiting, and small discoveries.
A short truck may accompany a few safe, approved steps in clear space.

The Family Dog is a gentle household companion. Keep its behavior ordinary:
waiting, looking, resting, following, soft play, or a small reposition. Never
use a chase camera, shaky urgency, low aggressive pursuit, or rescue framing.

### Recurring Locations

In the house, kitchen, courtyard, thinnai, field, pond, river ghat, tea stall,
grocery store, and utilities, movement must obey documented entrances, exits,
paths, object placements, light directions, and screen geography.

A movement that requires unseen space is not a license to invent that space.
Use an approved image, a two-image endpoint, or a new board frame.

### Season, Time, And Weather

Movement must preserve the scene’s fixed season, time of day, sun direction,
weather, shadow, moisture, smoke, and surface condition from start through
end.

For example:

- A rain pan keeps rainfall direction, wetness, and cloud light constant.
- A morning field truck preserves east-origin light and existing path state.
- A kitchen tilt preserves motivated fire or window light.
- A dry-season pull-out does not introduce lush wet-season growth.

Do not let a moving camera become an excuse for changing weather, exposure,
colour temperature, or the apparent time of day.

---

## Storyboard Notation And Production Planning

Every moving storyboard panel or shot row must record a separate direction and
movement entry. Never write only “camera: cinematic.”

```text
Shot ID:
Narrative purpose:
Approved source still(s):
Input mode: one-image / two-image

Camera Direction:
Camera Movement:
Movement Speed:
Start frame:
End frame:
Movement boundary:
Subject and one permitted action:
Protected visible evidence:
Line / screen-direction rule:
Location and orientation:
Light, season, weather:
Incoming bridge:
Outgoing bridge:
Duration:
Audio / edit intention:
Movement negatives:
Approval owner:
```

### Planning Gate

Approve movement only when all of these are true:

- The direction is already defined by the approved board and document 19.
- The movement has one named path and one reason.
- Start and end frames are both usable editorial compositions.
- The move does not cross the line or reverse screen direction.
- The move does not require an undocumented part of the location.
- The duration permits a readable start, one change, and a settled end.
- A locked shot or cut would not communicate the beat more clearly.

If any condition fails, revise the board, select `LOCKED CAMERA`, or split the
shot.

---

## Copy-Ready Flow Movement Modules

### Static / Locked Module

```text
Camera Direction: [APPROVED SHOT SIZE, CAMERA SIDE, HEIGHT, SUBJECT PLACEMENT,
AND SCREEN DIRECTION].
Camera Movement: [Static / Locked Camera].
Movement Speed: None; stable hold.
Subject: [ONE APPROVED ACTION OR ENVIRONMENTAL CONTINUATION]. Keep [FACE /
HANDS / OBJECT] clearly visible.
Framing Stability: Hold the exact approved [FRAME] from start to end. Preserve
camera side, line of action, screen direction, light, and crop-safe space. No
zoom, drift, pan, tilt, truck, dolly, crane, arc, orbit, shake, or reframing.
```

### Simple Reveal Module

```text
Camera Direction: [APPROVED START DIRECTION].
Camera Movement: [Slow Push In / Slow Pull Out / Pan Left / Pan Right / Tilt Up
/ Tilt Down].
Movement Speed: [Nearly imperceptible / very slow].
Subject: [ONE APPROVED ACTION OR DETAIL]. Keep [PROTECTED EVIDENCE] visible.
Framing Stability: Start [EXACT FRAME]. [MOVE] only a short, finite distance to
end [EXACT APPROVED FRAME OR REVEAL]. Preserve camera side, line of action,
screen direction, light, and crop-safe space. No [ALL OTHER MOVEMENTS], zoom,
shake, focus hunting, or new action.
```

### Short Follow Module

```text
Camera Direction: [APPROVED SIDE ORIENTATION AND SHOT SIZE].
Camera Movement: [Truck Left / Truck Right].
Movement Speed: Slow.
Subject: [CHARACTER] takes [TWO / THREE] grounded steps [SCREEN DIRECTION]
while [ONE APPROVED TASK]. Keep [FACE / CARRIED OBJECT / FEET] readable.
Framing Stability: Travel a short parallel distance only. Start and end
[APPROVED SHOT SIZE] from the same camera side. Do not overtake the subject,
cross the line, pan, push, tilt, shake, or reveal undocumented space.
```

### Two-Image Endpoint Module

```text
Source A is the approved start frame: [FILE / REVISION].
Source B is the approved end frame: [FILE / REVISION].

Camera Direction: [COMPATIBLE APPROVED DIRECTION FROM A TO B].
Camera Movement: [ONE APPROVED MOVEMENT].
Movement Speed: Very slow.
Subject: [ONE CONTINUOUS APPROVED CHANGE]. Keep [EVIDENCE] stable.
Framing Stability: Animate only the simple continuous path from Source A to
Source B. Preserve identity, camera side, screen direction, geography, light,
weather, object state, and end composition. No additional camera behavior,
crossing, zoom, shake, or invented action.
```

---

## Universal Flow Negative Movement Block

Apply this block to every moving Flow request, then add scene-specific
exclusions:

```text
No camera-line crossing, screen-direction reversal, camera-side change,
unplanned reframing, camera drift, fast movement, whip pan, snap tilt, zoom or
zoom burst, focus hunting, shake, handheld instability, action-camera look,
drone view, fisheye distortion, Dutch angle, spin, full orbit, long tracking,
impossible travel, travel through objects or people, background reconstruction,
new location area, new person, new object, object duplication, identity drift,
light/weather/time change, or new action after the approved end state.
```

Do not replace the block with vague language such as “keep everything stable.”
Name the specific movement prohibition when it protects an important risk.

---

## Continuity Rules For Moving Shots

### Direction And Line

Before animation, record the camera side, character screen positions, travel
direction, eyelines, dominant hand/object side, and line of action. Movement
may occur only within that established geometry.

A pan, truck, dolly, arc, crane, or orbit does not permit the camera to cross
the line. If a new side is necessary, establish it with a separate approved
shot and a clear editorial bridge.

### Start And End State

The source still is the literal starting visual state. For every move, record:

```text
Start: pose, hand occupancy, object state, subject relation, camera frame.
During: one allowed camera path and one allowed action.
End: pose, hand occupancy, object state, camera frame, and settling condition.
```

No candidate is approved when it begins or ends on a state that cannot cut to
the documented adjacent shot.

### Framing And Crop Safety

Maintain safe space for captions and platform UI as specified by the episode
format. A move may not push a face, hand, cooking action, or clue into a
subtitle zone merely to create a more dramatic composition.

For vertical Shorts, favor a stable central vertical action path and small
inward/outward change. Avoid lateral travel that leaves the subject too close
to the side crop or creates a disorienting fast reframing.

### Light, Weather, And Material State

Camera movement must not cause:

- morning light to become evening warmth;
- rain to change direction or intensity without story authorization;
- wet clothing, earth, roof, or leaves to become dry;
- smoke to become an exaggerated cloud;
- pot contents, food, tools, or textiles to transform;
- a background to gain or lose its recurring landmarks.

Review moving footage frame by frame when the shot includes a recurring
character, hand task, prop transfer, food state, rain, fire, or a difficult
location geometry.

---

## Format Rules: Shorts And Long Form

### YouTube Shorts

Shorts need immediate legibility in a vertical crop, but they do not need
frantic movement. The first readable frame should already communicate the
subject and moment.

Prefer:

- static or locked opening frames;
- a tiny slow push for a single emotional or tactile detail;
- one short pan or tilt only when both endpoints read in vertical framing;
- short, stable duration with a clean first and last frame.

Avoid:

- wide lateral trucks across a narrow vertical crop;
- big pull-outs that make people too small;
- long establishing moves before the subject appears;
- orbit, crane spectacle, shake, and fast hook-making moves.

Use a cut, sound cue, or strong approved first image for a hook. Do not use
camera agitation as a retention device.

### Long-Form Episodes

Long form has room for patient observation and rhythm variation, but every move
still needs a reason. Let static and locked shots dominate. Use occasional
slow reveals or short follows to prevent visual monotony only when the story
actually benefits.

Across a scene, avoid a chain of identical slow pushes. Vary shot direction,
size, subject, and editorial relation according to document 19 and the
approved board; do not vary movement merely to display technique.

---

## Movement QA

### Pre-Generation QA

Before sending a Flow request, confirm:

- [ ] Camera Direction is complete and derives from document 19.
- [ ] Camera Movement uses exactly one approved name from this manual.
- [ ] Movement Speed uses the studio vocabulary.
- [ ] The subject contains one visible action or environmental continuation.
- [ ] Start frame and end frame are explicit.
- [ ] The move has a finite path and a story reason.
- [ ] The selected one-image or two-image mode matches endpoint control needs.
- [ ] Camera side, line of action, screen direction, and crop-safe space are
      protected.
- [ ] Duration fits the movement and leaves time to settle.
- [ ] The prompt explicitly bans all unplanned camera behavior.
- [ ] The move respects location, season, weather, light, character, wardrobe,
      object, and emotional canon.
- [ ] Static or locked camera was considered first.

### Candidate QA

Review every candidate from first frame to last frame. Reject it if any of the
following occurs:

- The camera drifts although the instruction was static or locked.
- The movement is faster, longer, larger, or more theatrical than approved.
- The camera combines axes or adds a zoom, shake, spin, orbit, or focus hunt.
- The move crosses the line or reverses screen direction.
- The end frame does not match the approved frame or Source B.
- The subject, hands, face, tool, food, prop, or key evidence becomes hidden.
- The move invents or changes background space, people, objects, architecture,
  weather, time, or lighting.
- Identity, clothing, jewellery, hair, wetness, material condition, or object
  state drifts.
- The clip begins before the planned state or continues into new action after
  the planned end.
- The camera becomes noticeable enough to compete with the observed moment.

### Acceptance Standard

Approve only a candidate that:

1. begins on the approved source state;
2. performs one clear, calm camera behavior;
3. preserves all continuity locks;
4. keeps the intended story evidence visible;
5. settles into an edit-ready end frame; and
6. would not make a viewer consciously notice the camera.

---

## Failure Diagnosis And Minimal Repair

| Failure | Likely cause | Minimal repair |
| --- | --- | --- |
| Camera drifts in a hold | “Static” was not explicit enough or prompt contains conflicting movement language. | Use `Locked Camera`, name exact frame, and prohibit drift/reframing. |
| Move becomes too fast | Vague terms such as cinematic, dynamic, or sweeping. | Replace with `very slow` and state a short endpoint. |
| Flow adds a zoom | Push/pull wording is confused or zoom is not banned. | State physical camera move, modest end frame, and `No zoom`. |
| Camera crosses line | Endpoint or arc is directionally incompatible. | Return to document 19; use a cut or compatible endpoint. |
| Background changes during truck/dolly | Route is too long or space is too complex. | Shorten to a simple path, use two images, or lock the camera. |
| Face or hands deform during a move | Too much parallax, speed, or competing subject action. | Reduce to locked/static or one tiny move; protect exact visible evidence. |
| Pan overshoots or reverses | Endpoint is not named. | State start subject, one rotation direction, end subject, and no reverse. |
| Emotion feels melodramatic | Push/orbit/shake is doing emotional work. | Lock the camera and express the beat through approved behavior. |
| Rain becomes a storm | Movement prompt implies drama or lacks weather boundary. | Lock rain direction/intensity and use static/locked coverage. |
| Two-image bridge morphs | Sources are incompatible in direction, state, or layout. | Repair source pair or use separate shots; do not force interpolation. |

Always revise the smallest causal module. Do not rewrite character, location, or
style locks to solve a camera-movement failure.

---

## Production Workflow

1. Load the approved episode, scene, storyboard, continuity bridge, and higher
   canon.
2. Obtain Camera Direction from `19_Camera_Direction_Bible.md`.
3. State the one visible story reason for camera behavior.
4. Select static or locked camera unless a smaller named movement is necessary.
5. Select one movement from this manual and its approved speed.
6. Write the five Flow fields: direction, movement, speed, subject, and framing
   stability.
7. Choose one-image or two-image input from the needed endpoint control.
8. Add movement boundaries and the universal negative block.
9. Generate candidates without changing the approved facts.
10. QA movement, continuity, and editorial cut compatibility.
11. Archive the chosen clip with source revision, prompt, settings available,
    candidate ID, QA decision, and outgoing state.

If a motion concept cannot survive this workflow as one bounded move, it is not
a Flow instruction. Board it as multiple shots or simplify it.

---

## Cross-References

Read this manual with the following sources:

- `01_Canon/01_Series_Style_Lock/Camera_Language.md` — higher-level observer
  philosophy and prohibited spectacle.
- `01_Canon/01_Series_Style_Lock/Animation_Principles.md` — physical realism,
  weight, and natural behavior.
- `09_AI_Production_System/19_Camera_Direction_Bible.md` — sole authority for
  camera position, framing, shot selection, camera side, and screen direction.
- `09_AI_Production_System/05_Master_Animation_Prompt.md` — source loading,
  Flow master prompt, continuity bridge, and generation procedure.
- `09_AI_Production_System/04_Master_Image_Prompt.md` and
  `04_Image_Prompt_Reference.md` — still-image composition and source-frame
  preparation.
- `07_Episode_System/05_Pacing_Timeline.md`,
  `10_Music_And_Silence.md`, `11_Visual_Rhythm.md`,
  `12_YouTube_Shorts.md`, and `13_Long_Form_Episodes.md` — episode rhythm and
  format requirements.
- Applicable character, location, object, research, scene-state, and approved
  storyboard records — factual continuity.

When a cross-reference sets direction, story state, or canon fact, it governs.
This manual determines only the permitted **movement of that approved camera**.

---

## Guiding Principle

The camera exists to quietly witness life.

Choose the stillest truthful frame. When movement is necessary, make one small,
slow, bounded movement that reveals an approved fact, preserves every continuity
lock, and disappears into the lived reality of the village.
Start and end in the same approved composition. No camera-axis change. Subject
motion must remain within the protected frame.

**Camera-direction pairings**  
Best with approved close detail, medium domestic observation, doorway framing,
wide establishing frame, and stable over-the-shoulder conversation coverage.

---

### Locked Camera

**Definition**  
A locked camera is an operational instruction that fixes camera position,
orientation, height, lens feeling, and framing for the entire clip. It protects
an approved frame against tool drift. In practice it produces a static camera,
but it is used when the prompt must explicitly forbid any reframe.

**Purpose**  
Use it as the default Flow camera instruction whenever continuity, action
readability, or an exact source composition must remain stable.

**Emotional effect**  
Unforced observation, confidence, intimacy without intrusion, and edit-ready
clarity.

**Recommended speed**  
None; stable hold.

**Google Flow compatibility**  
Excellent and preferred. It is the production default.

**Use**  
Use for cooking steps, ASMR details, dialogue, hand actions, delicate facial
responses, object-state changes, rainy thresholds, and any shot entering or
leaving a continuity-sensitive cut.

**Do not use**  
Do not use if the approved board explicitly requires a small, single movement
to reveal or follow information. Do not label a moving camera as locked.

**Common mistakes**

- Using “locked camera” and later requesting a push, zoom, pan, or drift.
- Forgetting to name what must remain visible within the fixed frame.
- Allowing Flow to introduce a floating, handheld quality despite the lock.
- Confusing a locked frame with frozen people or weather.

**Positive example**

```text
Camera Direction: Medium two-shot from the approved veranda side, Father
screen-left and Mother screen-right.
Camera Movement: Locked Camera.
Movement Speed: None; stable hold.
Subject: Father listens while Mother finishes one quiet sentence.
Framing Stability: Hold the exact medium two-shot, eye level, camera side, and
caption-safe lower frame. No zoom, drift, pan, tilt, shake, or line crossing.
```

**Negative example**

```text
Locked camera that gently creeps closer, adjusts to their faces, and follows
their conversation.
```

**Duration**  
2–6 seconds, limited by one readable exchange or action. A longer conversation
must be covered by separately approved shots rather than a continuously
correcting camera.

**Movement boundaries**  
No camera movement at all. The end frame equals the start frame; only approved
subject and environment motion may change.

**Camera-direction pairings**  
Best with all approved directions, especially close hand inserts, medium
conversation coverage, kitchen side views, doorway frames, and wide rainy
observations.

---

### Slow Push In

**Definition**  
The camera moves a small distance physically forward toward the approved
subject, producing a modestly tighter framing. It is not a zoom.

**Purpose**  
Use it to let a contained realization, care, detail, or emotional response
become slightly more legible without forcing drama.

**Emotional effect**  
Gentle attention, quiet intimacy, growing recognition, tenderness, or focus.
It must never feel like a revelation sting.

**Recommended speed**  
Nearly imperceptible or very slow.

**Google Flow compatibility**  
Good for small changes in framing. More reliable with one image for a tiny
push; use two images if the end composition must match a following close shot.

**Use**  
Use for Mother noticing the finished dough, Father pausing before responding,
a child’s restrained delight, a hand placing a meaningful ordinary object, or
steam revealing a cooked dish.

**Do not use**  
Do not use to make neutral dialogue falsely dramatic, to cover a missing close
shot, to rush toward a face, or while the subject walks a significant distance.

**Common mistakes**

- Saying “slow push in” but asking for an extreme close-up.
- Combining it with a pan, tilt, orbit, or focus pull.
- Allowing the subject’s face or hands to leave the protected area.
- Making the end frame too tight to preserve established screen geography.

**Positive example**

```text
Camera Direction: Medium close view of Father seated on the thinnai from the
approved front-left camera side.
Camera Movement: Slow Push In.
Movement Speed: Nearly imperceptible.
Subject: Father looks toward the courtyard and gives one small, relieved smile.
Framing Stability: Start medium close; end only slightly tighter on the same
side. Keep his face and shoulder line stable. No pan, tilt, zoom, orbit, shake,
or screen-direction change.
```

**Negative example**

```text
Push rapidly from a wide courtyard shot into an extreme close-up as Father
realizes something important.
```

**Duration**  
2–5 seconds. Reserve the final half-second, where possible, for the settled
response rather than continuing to advance until the cut.

**Movement boundaries**  
Travel forward only a small, finite amount. End before the frame becomes a new
shot size unless that exact endpoint is board-approved. Preserve height, side,
and subject relation.

**Camera-direction pairings**  
Best with medium close and medium frames facing an approved emotional subject
or meaningful detail. Avoid starting from an extreme wide or ending in an
unplanned extreme close-up.

---

### Slow Pull Out

**Definition**  
The camera moves a small distance physically backward from the approved
subject, opening the frame to reveal an already-approved spatial relation. It
is not a zoom out.

**Purpose**  
Use it when a private detail needs to be gently placed back inside family,
home, weather, or village context.

**Emotional effect**  
Breathing room, reflection, modest distance, belonging, or a quiet sense of
the larger world. It should not imply abandonment or tragedy without story
authorization.

**Recommended speed**  
Very slow.

**Google Flow compatibility**  
Good when the added space is documented in the source or endpoint. Prefer two
images when the end wide composition matters.

**Use**  
Use after a child finishes a small task to include the courtyard, after a
close cooking detail to return to the kitchen’s working rhythm, or after a
quiet family gesture to include the nearby listener.

**Do not use**  
Do not use to reveal undocumented rooms, new people, new props, or a sudden
large landscape. Do not use as a default “ending move.”

**Common mistakes**

- Pulling so far back that Flow invents architecture.
- Combining a backward move with an upward crane.
- Turning a calm context reveal into a lonely dramatic withdrawal.
- Ending before the wider frame settles.

**Positive example**

```text
Camera Direction: Close view of a child’s hands tying a small bundle on the
approved courtyard side.
Camera Movement: Slow Pull Out.
Movement Speed: Very slow.
Subject: The child completes the knot once.
Framing Stability: Start close; end at a modest medium view that includes the
already-approved courtyard floor and Mother nearby in soft, stable background.
No crane, pan, zoom, or new background activity.
```

**Negative example**

```text
Pull far back through the roof into a sweeping aerial view of the village.
```

**Duration**  
3–5 seconds.

**Movement boundaries**  
Move backward on one axis only. Reveal only documented, source-supported
space. Keep the same camera height, side, and light direction.

**Camera-direction pairings**  
Best from close to medium or medium to modest wide. Pair with approved doorway,
kitchen, courtyard, and family-group directions where the additional space is
already established.

---

### Pan Left / Pan Right

**Definition**  
The camera rotates horizontally from a fixed position to look left or right
across one continuous, already-approved space. The camera itself does not
travel laterally.

**Purpose**  
Use a slow pan to connect a sound or action cue to its visible source, reveal a
nearby detail, or move attention across a stable shared space.

**Emotional effect**  
Natural noticing, quiet discovery, or gentle connection. It should feel like a
person calmly turning their head, not searching.

**Recommended speed**  
Very slow for a reveal; slow only when following a small, visible action.

**Google Flow compatibility**  
Good for short, bounded horizontal reframes across source-supported scenery.
Avoid long pans across detailed spaces where Flow may invent or rearrange
objects.

**Use**  
Use to pan from rising steam to the clay pot, from the dog’s lifted ears to an
approved approaching family member, or across a tea stall counter from glass
to server.

**Do not use**  
Do not use for a rapid reaction, an entire room tour, a travel substitute, or
to jump across an unestablished line of action.

**Common mistakes**

- Using “pan” to mean lateral camera travel.
- Panning past the subject and then correcting back.
- Crossing a conversation line while panning.
- Making a long pan that causes duplicated people or transformed layout.

**Positive example**

```text
Camera Direction: Medium kitchen view from the approved doorway side.
Camera Movement: Pan Right.
Movement Speed: Very slow.
Subject: Steam enters from frame-left before the camera reveals the documented
clay pot on the stove at frame-right.
Framing Stability: Rotate right from the doorway without moving position. End
with the pot centered in a stable medium detail frame. Keep the same camera
side; no push, tilt, zoom, or second pan.
```

**Negative example**

```text
Whip pan right through the kitchen, zoom into the pot, then pan back to Mother.
```

**Duration**  
2–4 seconds. The actual rotation must be short enough to settle on the source
of attention.

**Movement boundaries**  
Rotate in one horizontal direction from one fixed position. Name the start and
end subject. Do not sweep beyond the endpoint or reverse direction.

**Camera-direction pairings**  
Best with a doorway, veranda, counter, river-step, or courtyard-side direction
where both endpoints belong to the same approved camera side and depth plane.

---

### Tilt Up / Tilt Down

**Definition**  
The camera rotates vertically from a fixed position to look up or down across
one continuous, already-approved vertical relation. The camera does not rise,
fall, or travel.

**Purpose**  
Use a subtle tilt to connect an object with the person handling it, show a
nearby weather effect, or reveal a vertical relation already present in the
location.

**Emotional effect**  
Quiet observation and orderly discovery. A tilt should not feel like a
grandiose reveal.

**Recommended speed**  
Nearly imperceptible or very slow.

**Google Flow compatibility**  
Good for very short, clear relations. More fragile than a pan when moving
between face, hands, and floor; protect identity and frame endpoint explicitly.

**Use**  
Use to tilt down from Mother’s face to her hands measuring rice, tilt up from
rainwater ripples to the banana leaves that shed drops, or tilt from bare feet
to a child standing at the threshold.

**Do not use**  
Do not use for a towering “hero” reveal, a full building scan, a sudden look
down for danger, or an up-and-down correction in one clip.

**Common mistakes**

- Confusing a tilt with a crane.
- Tilting through a face so quickly it distorts.
- Combining vertical rotation with forward travel.
- Ending on an unapproved roof, sky, or floor detail.

**Positive example**

```text
Camera Direction: Medium close view of Mother at the kitchen work surface from
the approved side.
Camera Movement: Tilt Down.
Movement Speed: Very slow.
Subject: Mother measures one handful of rice into the bowl.
Framing Stability: Begin on her calm face and upper body; tilt down a short
distance to end on both hands, bowl, and rice. Camera position remains fixed.
No push, crane, pan, zoom, or line crossing.
```

**Negative example**

```text
Tilt quickly from the floor to the sky while flying upward past Mother.
```

**Duration**  
2–4 seconds.

**Movement boundaries**  
Rotate vertically once, through a short documented range. Start and end on
approved details in the same physical position. Do not reverse or add travel.

**Camera-direction pairings**  
Best with close or medium vertical task relationships, threshold views, shelf
details, rain-to-leaf relations, and grounded child-height observations.

---

### Truck Left / Truck Right

**Definition**  
The camera travels laterally left or right while keeping its general facing
direction and subject relationship stable. It is sideways translation, not a
pan.

**Purpose**  
Use a short truck to accompany a few grounded steps, clear a foreground
obstruction, or maintain an approved side relation during a contained routine.

**Emotional effect**  
Gentle companionship and lived-in spatial presence. It should feel like an
observer taking a few careful steps alongside, never chasing.

**Recommended speed**  
Slow; measured only for a very short approved walk.

**Google Flow compatibility**  
Moderate. Use only when the route, subject path, and background are simple and
documented. Two-image input is preferred if the endpoint matters.

**Use**  
Use beside Father taking two steps along the field edge, alongside a child
carrying a small vessel across a short courtyard path, or to clear one veranda
pillar while retaining the same side.

**Do not use**  
Do not use through dense interiors, crowded market activity, long travel,
complex foreground, or whenever a static side shot and cut would tell the story
more cleanly.

**Common mistakes**

- Calling a pan a truck, or asking for both.
- Tracking too far and generating parallax errors or altered backgrounds.
- Letting the camera overtake the subject.
- Following a person across the line of action.

**Positive example**

```text
Camera Direction: Medium side view of Father on the approved field path, moving
screen-left to screen-right.
Camera Movement: Truck Right.
Movement Speed: Slow.
Subject: Father takes two grounded steps while carrying the documented empty
basket at his side.
Framing Stability: Travel a short distance parallel to him, retaining the
approved side profile and screen direction. Start and end medium side view.
No pan, push, acceleration, overtaking, shake, or line crossing.
```

**Negative example**

```text
Race alongside Father, pass him, spin around, and reveal the full fields.
```

**Duration**  
3–5 seconds for two or three small steps. Cut rather than follow a longer
journey.

**Movement boundaries**  
One short lateral route, parallel to the approved action. Keep a stable
subject-to-camera distance and height. Do not pass the subject or reveal
undocumented lateral space.

**Camera-direction pairings**  
Best with approved side medium and modest wide travel directions, especially
clear field paths, courtyard edges, river-step approaches, and veranda walks.

---

### Dolly In / Dolly Out

**Definition**  
A dolly moves the camera physically forward or backward along a deliberate
grounded route, typically preserving the subject’s central relation more
exactly than a simple push or pull. In this series, it remains small and calm.

**Purpose**  
Use it only when a physical change in viewpoint or foreground/background
relation is materially required by the approved shot—not merely a tighter or
wider frame.

**Emotional effect**  
Attentive presence or gentle spatial opening. It must remain less noticeable
than its theatrical film usage.

**Recommended speed**  
Very slow. Slow only with a short, simple subject action.

**Google Flow compatibility**  
Moderate to fragile. It can generate parallax and spatial drift. Prefer two
images for exact endpoints and choose a push/pull instead when true parallax is
not required.

**Use**  
Use for a short forward move past an approved doorway edge to place the viewer
inside a kitchen task, or a short backward move that reveals Father and the
field tool in their documented relation.

**Do not use**  
Do not use in cluttered rooms, across large depth changes, through people or
objects, to simulate a zoom, or where a push/pull provides the same story
effect.

**Common mistakes**

- Treating “dolly” as a stylish synonym for “push.”
- Requesting a long move through a full house or village.
- Combining dolly travel with pan, tilt, arc, or rack focus.
- Failing to protect foreground objects from warping or disappearing.

**Positive example**

```text
Camera Direction: Medium view from the approved kitchen doorway, clay stove and
Mother’s hands already visible beyond the threshold.
Camera Movement: Dolly In.
Movement Speed: Very slow.
Subject: Mother turns the cooking spoon once.
Framing Stability: Move forward only from the doorway edge to a stable medium
view of the stove and hands. Preserve the same camera side and doorframe
relation. No pan, tilt, zoom, passing through objects, or new kitchen detail.
```

**Negative example**

```text
Dolly rapidly through the entire house, around Mother, and into the pot.
```

**Duration**  
3–5 seconds. Use a shorter clip if foreground geometry or hands are fragile.

**Movement boundaries**  
Travel on one short forward or backward ground-level path. Start and end with
approved depth landmarks. Do not change side, height, or axis.

**Camera-direction pairings**  
Best with doorway, lane, veranda, and field-path directions that offer a clear
documented forward/backward corridor. Avoid tight close-ups and dense rooms.

---

### Arc Left / Arc Right

**Definition**  
The camera makes a small curved move left or right around a subject while
retaining a consistent, approved subject relation. An arc changes perspective
slightly; it is not a full circle and not an orbit.

**Purpose**  
Use only when a small change in relation reveals a second approved person,
object, or layer of environment that a static frame cannot show without
breaking the scene’s calm.

**Emotional effect**  
Subtle relational connection and quiet dimensionality. It must not create
romantic, heroic, suspenseful, or showy emphasis.

**Recommended speed**  
Nearly imperceptible or very slow.

**Google Flow compatibility**  
Fragile. Use rarely, over a very small arc, in simple documented space. Prefer
two approved endpoint images. If the story works with a pan, locked reverse, or
cut, choose that instead.

**Use**  
Use for a small arc that reveals Mother listening just beyond Father’s shoulder,
or that clears one fixed foreground pillar to reveal a documented cooking tool.

**Do not use**  
Do not use around a single emotional face, around a couple for romance, around
an active person, around a conversation line, or for a 180-degree/360-degree
move.

**Common mistakes**

- Calling a wide orbit an arc.
- Crossing the line of action during the curve.
- Making the camera circle a subject who is already visible.
- Introducing excessive parallax, face morphing, or background rebuild.

**Positive example**

```text
Camera Direction: Medium view of Father seated at the thinnai from the approved
front-left side; Mother is documented just beyond the near pillar.
Camera Movement: Arc Right.
Movement Speed: Nearly imperceptible.
Subject: Father turns his head once toward Mother.
Framing Stability: Make one very small rightward curve only enough to clear the
pillar and include Mother at frame-right. End in the approved medium two-shot.
Preserve the original camera side and line of action. No orbit, pan, push,
crossing, or dramatic circular travel.
```

**Negative example**

```text
Circle around Father and Mother for a romantic 360-degree reveal.
```

**Duration**  
3–5 seconds, with a short stable end. If the endpoint cannot settle, use a cut.

**Movement boundaries**  
Use a small fraction of a circle only. State the obstruction or relation being
revealed and the exact ending frame. Never pass behind the subject or cross the
established line.

**Camera-direction pairings**  
Only pair with approved medium or modest wide relational directions in simple
spaces. Never pair with extreme close-ups, busy routines, or line-sensitive
shot/reverse-shot dialogue.

---

### Crane Up / Crane Down

**Definition**  
The camera rises or descends physically while maintaining an approved looking
direction and a believable local viewpoint. It is physical vertical travel, not
a tilt.

**Purpose**  
Use sparingly to reveal a documented vertical relation, such as courtyard
activity from the thinnai, rain gathering on a roof edge and reaching the
threshold, or a small change from ground-level work to the surrounding field.

**Emotional effect**  
Gentle contextual expansion or settling. It must never become an aerial
spectacle or a god’s-eye view.

**Recommended speed**  
Very slow; measured only when a short physical rise or descent is necessary.

**Google Flow compatibility**  
Moderate to fragile. Vertical travel can invent rooftops, distort people, or
become drone-like. Prefer two images for a defined endpoint.

**Use**  
Use for a small rise from a low garden detail to a child watering plants, or a
short descent from a veranda-edge view to Mother arriving in the courtyard.

**Do not use**  
Do not use over rooftops, above tree height, for a village aerial, for a
dramatic entrance, or in a way that cannot be physically imagined from a
nearby building, step, or simple camera support.

**Common mistakes**

- Confusing crane travel with tilt.
- Rising high enough to resemble a drone.
- Combining the crane with a pull-out or orbit.
- Making the rise reveal an undocumented village layout.

**Positive example**

```text
Camera Direction: Low close view of wet basil leaves in the documented
courtyard garden, facing toward Mother’s approved position.
Camera Movement: Crane Up.
Movement Speed: Very slow.
Subject: Rain beads remain on the leaves while Mother steps once into the
garden behind them.
Framing Stability: Rise only from leaf level to a stable low-medium view that
includes Mother and the garden. Maintain the same facing direction and local
courtyard geography. No aerial height, tilt, pull-out, drone view, or orbit.
```

**Negative example**

```text
Crane rapidly above the house for an epic aerial survey of the rainy village.
```

**Duration**  
3–5 seconds. Use only enough travel to establish the approved local relation.

**Movement boundaries**  
Travel vertically along one short plausible path. Define ground reference,
starting height, ending height, and visible local area. Do not clear roofs,
trees, or the ordinary human scale of the world.

**Camera-direction pairings**  
Rarely pair with approved low-to-medium courtyard, garden, thinnai, or river
step directions. Do not use with a high-angle aerial or hero-angle direction.

---

### Orbit (Rare)

**Definition**  
An orbit is a camera path curving around a subject while continuously keeping
the subject as the center of view. It changes camera side and background
relation over time.

**Purpose**  
Orbit has no routine Village Stories use. It is listed so that production can
recognize and reject it by default. A rare exception requires an explicit
boarded reason, compatible endpoints, and approval from the responsible
production authority.

**Emotional effect**  
Orbits naturally create conspicuous attention, spectacle, romance, suspense, or
heroic emphasis. Those effects conflict with the observer principle in nearly
all series moments.

**Recommended speed**  
Nearly imperceptible only, if exceptionally authorized.

**Google Flow compatibility**  
Low. It is prone to identity drift, background reconstruction, camera-line
crossing, and theatrical motion.

**Use**  
Only use a very small partial orbit when a documented, non-dramatic spatial
relation cannot be communicated by a locked shot, pan, short arc, or edit, and
when both start and end frames are explicitly approved.

**Do not use**  
Do not use for romance, emotional climaxes, character introductions, family
hugs, cooking, conversation, routine, rain, establishing shots, Shorts hooks,
or “cinematic energy.”

**Common mistakes**

- Calling any arc an orbit.
- Treating a full circle as harmless atmosphere.
- Crossing the line and reversing screen direction.
- Using it because an image looks more expensive.

**Positive example**

```text
Camera Direction: Approved modest-wide courtyard two-person relation with both
start and end camera sides documented.
Camera Movement: Orbit (rare, authorized partial orbit only).
Movement Speed: Nearly imperceptible.
Subject: Two family members remain seated and continue their approved quiet
task; no new emotional event occurs.
Framing Stability: Travel through one very small, explicitly approved partial
curve between Source A and Source B. Maintain face identity, object positions,
and local geography. Stop at the approved end frame. No full circle, speed
ramp, camera-line crossing outside the authorized endpoint, zoom, shake, or
additional move.
```

**Negative example**

```text
Orbit 360 degrees around the family as they smile in slow motion.
```

**Duration**  
4–6 seconds only when a short, calm, two-image bridge is demonstrably usable.
Otherwise use a cut.

**Movement boundaries**  
Explicitly document start and end camera side, angle, subject relation, and
fraction of the curve. No full orbit. No unapproved line crossing. No secondary
camera behavior.

**Camera-direction pairings**  
Exception only. Require the separate direction document and storyboard to
define compatible start and end directions. It is not a default pairing for
any shot type.

---

### Handheld (Almost Never)

**Definition**  
Handheld describes small, imperfect camera instability caused by a person
physically carrying the camera. It is not naturalism by default; it is visible
camera behavior.

**Purpose**  
Handheld has almost no normal place in Village Stories. It is included to make
the prohibition operational. An exception needs an explicit higher-approved
story reason that cannot be expressed by stable observation.

**Emotional effect**  
Handheld reads as instability, urgency, documentary self-awareness, danger, or
chaos. These meanings usually contradict the series’ dignified, calm observer.

**Recommended speed**  
None. If an exceptional authorized handheld hold exists, instability must be
minimal and not paired with travel.

**Google Flow compatibility**  
Low. It frequently becomes shake, jitter, morphing, or action-camera
distortion.

**Use**  
Almost never. Use only with documented authorization for an unusually specific,
quiet, physically motivated point-of-view condition where a stable frame would
misstate the scene. The authorization must state why locked camera is
insufficient.

**Do not use**  
Do not use for ordinary realism, rain, walking, comedy, emotion, cooking,
family warmth, conversation, nature, establishing shots, action, chase, panic,
or a “documentary feel.”

**Common mistakes**

- Adding “subtle handheld” as a generic realism modifier.
- Using shake to create emotion rather than showing behavior.
- Combining handheld with tracking, fast pans, or long lenses.
- Mistaking generated jitter for an approved handheld look.

**Positive example**

```text
Camera Direction: Approved close observational view from a documented physical
position.
Camera Movement: Handheld (almost-never exception; explicitly authorized).
Movement Speed: None; minimal natural micro-instability only.
Subject: [State the authorized visible condition.]
Framing Stability: Preserve the approved frame, subject visibility, camera
side, and all continuity. No travel, pan, tilt, zoom, shake emphasis, action-
camera distortion, or escalation. Reject any candidate with noticeable jitter.
```

**Negative example**

```text
Use energetic handheld shake while the family runs through heavy rain.
```

**Duration**  
1–3 seconds maximum for an approved exception. A longer unstable shot is not
series-compatible.

**Movement boundaries**  
Hold one approved frame with at most minimal micro-instability. No travel, pan,
tilt, zoom, or escalation. Reject any candidate with visible shake or jitter.

**Camera-direction pairings**  
Exception only. Requires explicit authorization stating why Locked Camera is
insufficient.

---

## Flow Synonym Map And Forbidden Prompt Language

### Purpose

Filmmaking, AI tools, and general cinematography lists use many movement names
that are **not** separate Village Stories canon entries. Some map to approved
moves under a different name. Others conflict with the observer principle or
break Google Flow continuity.

**Rule for every Flow animation prompt:** write **one approved bible name**
from the Movement Library above — never a vague or theatrical synonym.

This appendix is operational guidance for prompt writers. It does not add new
movement types. When a synonym maps to an approved move, use the **bible name**
in the `Camera Movement:` field.

---

### Approved alias map

When you think in common filmmaking terms, translate to the bible name before
prompting.

| Common / AI-suggested term | Use this bible name | Notes |
| --- | --- | --- |
| Tracking Shot (generic) | **Truck Left / Truck Right** | Never write "tracking" alone — Flow may chase or orbit |
| Side Tracking Shot | **Truck Left / Truck Right** | Same as above; name screen direction |
| Parallel Tracking Shot | **Truck Left / Truck Right** | Keep parallel side profile; 2–3 steps max |
| Follow Shot | **Truck Left / Truck Right** | Subject walks; camera travels short parallel path |
| Leading Shot | **Truck** or **Locked Camera** | Subject walks toward camera; prefer lock if subject approaches frame |
| Push Follow | **Slow Push In** | Only if subject stays fixed and camera advances slightly |
| Pull Follow | **Slow Pull Out** | Only if opening modest context from closer start |
| Lateral Slide / Side Glide | **Truck Left / Truck Right** | Synonyms only — do not use "slide" or "glide" in prompts |
| Dolly Track | **Dolly In / Dolly Out** | Prefer **Slow Push In / Slow Pull Out** unless parallax is required |
| Arc Tracking Shot / Semi-Orbit | **Arc Left / Arc Right** | Small curve only — not a circle |
| Boom Up / Boom Down / Jib Shot | **Crane Up / Crane Down** | Short local vertical travel only |
| Reveal Shot | **Slow Pull Out** or **Pan Left / Pan Right** | Name what is revealed and endpoint frame |
| Parallax Reveal | **Dolly Out** or **Slow Pull Out** | Prefer pull out unless doorway parallax is boarded |
| Peek Reveal / Rack Reveal | **Pan** or **Slow Pull Out** | One-axis only; no rack focus language in Flow |
| Establishing Glide | **Slow Push In** or **Slow Pull Out** | Wide establishing only; never "glide" |
| POV Walk | **Truck** + approved **POV** direction (Doc 19) | Fragile — prefer cut to MS |
| Shoulder Follow / OTS Tracking | **Truck** + **Over-the-Shoulder** direction (Doc 19) | Rare; two-image if endpoint matters |
| First-Person Tracking | **Truck** + **POV** direction | Almost never — observer principle |
| Observer Camera / Scenic Drift | **Static** or **Locked Camera** | Stillness is the series observer |
| Floating Camera | **Static** or **Locked Camera** | Do not prompt "float" — causes drift |
| Lock-On Tracking / Center Lock Follow | **Truck** (bounded) | Never "lock-on" — Flow chases and morphs |
| Composition Shift / Dynamic Reframe | **Locked Camera** or **cut** | Reframing mid-clip is not authorized |
| Reframing Shot | **Separate approved shot** | Use editorial cut, not in-clip reframe |

---

### Forbidden prompt language

**Never use these words or phrases in Flow `Camera Movement:` or movement
instructions.** They are not canon, and they reliably degrade identity,
geography, and calm observation.

| Forbidden term | Why |
| --- | --- |
| Dolly Zoom / Vertigo Effect | Stylized thriller grammar — not Village Stories |
| Whip Pan / Snap Pan | Conflicts with slow observer; Flow invents motion blur chaos |
| Snap Zoom / Crash Zoom / Zoom In / Zoom Out | Zoom ≠ push/pull; causes face morph |
| Orbit Shot / 360° / Full Orbit | Listed as **Orbit (Rare)** — reject in ordinary production |
| Steadicam Shot / Gimbal Follow | Reads as action/docu; becomes float and shake |
| Snorricam | Specialty stunt grammar — never |
| Handheld (unless doc exception) | Default prohibition |
| Floating Camera / Drone / Aerial sweep | Conflicts with grounded village scale |
| Cinematic camera / Dynamic move / Camera dance | Unbounded — Flow improvises |
| Move around [subject] | Not a movement name — define truck, arc, or cut |
| Tracking (alone, unqualified) | Too vague — always specify **Truck** + direction |
| Glide / Drift / Float / Sweep | Causes unmotivated camera drift |
| Energetic / Fast / Dramatic / Epic | Speed and tone violate movement speed rules |

If a tool suggests one of these, replace it using the alias map or choose
**Locked Camera**.

---

### Six-beat movement cheat sheet

Default move when the board does not specify otherwise:

| Story beat | Preferred movement | Speed | Typical duration |
| --- | --- | --- | --- |
| **Establish** — village, house, field, morning hook | **Slow Push In** or **Locked Camera** wide | Very slow / none | 8–12 s |
| **Intimate** — wake, realization, quiet care | **Slow Push In** | Nearly imperceptible | 6–8 s |
| **Walk** — path, field edge, beside subject | **Truck Left / Truck Right** | Slow | 6–10 s |
| **Cook / hands / dialogue** — kitchen, thinnai talk | **Locked Camera** or **Static** | None | 4–8 s |
| **Wide life** — environment, rest, animals, hold | **Locked Camera** | None | 8–12 s |
| **End / breathe** — return to shared space before cut | **Slow Pull Out** | Very slow | 8–12 s |

Secondary options (only when cheat-sheet default cannot show the beat):

- **Pan / Tilt** — connect two approved details in the same room (2–4 s).
- **Arc** — reveal second person behind pillar (rare, 3–5 s).
- **Crane** — short ground-to-waist garden relation (rare, 3–5 s).
- **Dolly** — doorway threshold parallax when push/pull is insufficient.

When in doubt: **Locked Camera** beats a stylish move.

---

### Copy-ready Flow rule block

Append to animation prompts when using any move:

```text
Camera Movement: [ONE APPROVED BIBLE NAME ONLY — see Movement Library § Flow Synonym Map]
Movement Speed: [None / nearly imperceptible / very slow / slow — never fast]
Framing Stability: Start [exact frame]. End [exact frame or finite reveal].
  Preserve camera side, screen direction, geography, and identity.
  No second move, zoom, orbit, drift, shake, or reframe.
```

---

### Cross-reference

| Document | Role |
| --- | --- |
| `19_Camera_Direction_Bible.md` | Shot size, angle, side — **where** camera starts |
| This document § Movement Library | **How** camera moves — approved names |
| This document § Flow Synonym Map | Translate external terms → bible names |
| `11_Templates/Animation_Prompt_Template.md` | Prompt assembly and pre-flight |

---

## Guiding Principle (Recap)

The camera exists to quietly witness life.

Choose the stillest truthful frame. When movement is necessary, make **one**
small, slow, **named** movement from the Movement Library. Translate every
external or AI-suggested term through the Flow Synonym Map before prompting.
Never add new movement vocabulary to Flow without updating this document.

