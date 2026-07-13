# Master Animation Prompt

## Purpose And Scope

This is the permanent production manual and copy-ready master prompt for
animating approved Village Stories stills in Google Flow.

Use it to turn one approved visual moment into one short, controlled motion
clip that can cut into the episode without changing its people, place, period,
story state, or visual identity. It covers source selection, one-image and
two-image Flow input, movement, camera, duration, continuity, review, revision,
and edit handoff.

This manual does not create story facts, redesign characters, establish a
location, choose an undocumented object, or repair an unclear board with
movement. It also does not replace the still-image prompt: the image prompt
creates the frame; this prompt instructs what may move within it.

## Operating Philosophy

> Animate the smallest truthful change that makes the approved moment feel
> alive. Preserve everything else.

Good Village Stories animation is patient, observable, and edit-ready. A hand
finishing one task, a person taking a few grounded steps, a saree responding to
a mild breeze, or rain continuing beyond a doorway may be enough. More motion
is not more cinematic when it damages identity, clarity, dignity, or continuity.

Google Flow is a bounded motion tool, not a writer, director of story facts, or
canon authority. When the requested movement cannot be stated as one clear
action with a visible start and end state, split it into shots, use an insert,
use a still, or return to the board.

---

## Authority And Canon

This manual inherits authority and creates none. Follow the highest applicable
source; never average conflicting instructions.

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
07_Episode_System/ — format, pacing, openings, endings, rhythm
↓
08_Production/ — execution, edit, QA, release
↓
09_AI_Production_System/01_Master_Workflow.md
↓
04_Master_Image_Prompt.md and this manual
↓
19_Camera_Direction_Bible.md and 20_Camera_Movement_Bible.md
↓
Flow settings, generated candidate, selected clip
```

An attractive generation, a prior candidate, tool default, reference image, or
retention metric never authorizes a conflicting fact. If an essential fact is
`OPEN`, mark the shot `HOLD FOR CANON OR RESEARCH`; do not animate a recurring
or continuity-critical shot from guesswork.

### Permanent Series Locks

- Early-1990s rural Tamil Nadu is fixed; the exact year may flex, the period
  cannot. No modern technology, packaging, infrastructure, fashion, vehicles,
  lighting, screens, branding, or problem-solving.
- Preserve the original premium cinematic anime identity: semi-realistic South
  Indian people, believable anatomy, soft painterly hand-painted digital
  rendering, restrained organic linework, natural material texture, soft global
  illumination, detailed culturally accurate environments, and warm,
  restrained slice-of-life feeling. Do not name or imitate any studio, artist,
  film, franchise, or other external property.
- The camera is a calm human observer: natural, stable, non-distorting, and
  aware of screen geography. No fisheye, action-camera look, drone view, Dutch
  angle, surveillance view, hero angle, or arbitrary spectacle.
- Camera direction must be selected from
  `19_Camera_Direction_Bible.md`; camera movement, speed, boundaries, and
  direction/movement pairing must be selected from
  `20_Camera_Movement_Bible.md`. Never merge those fields into one ambiguous
  instruction.
- Preserve documented orientation and light: morning arrives from the east,
  evening from the west; the house/rear yard/kitchen are west, fields and pond
  east, banyan tree and river ghat north, and canal south. Weather and light
  must follow the approved scene and adjacent shots.
- Keep ordinary life dignified. Do not manufacture danger, panic, urgency,
  violence, humiliation, child endangerment, animal distress, rescue, chase, or
  melodrama through motion, sound, expression, or camera.
- Only animate people, animals, objects, weather, and background activity
  approved for the shot. Absence is a valid instruction.

### Recurring Identity Locks

When Father is visible, preserve the same recurring man defined by
`11_Assets/Character_References/Father_Canon_Design_Reference.png`: thick
naturally tousled black hair, light natural stubble, warm medium-brown South
Indian complexion, lean farmer build with broad shoulders and strong forearms,
and calm, grounded manner. Attach the stored reference as
`CHARACTER_IDENTITY` whenever Flow supports it and Father is a principal
subject, his face is visible, a setup establishes him, or a candidate repairs
his identity. It controls identity, not incidental pose, light, or background.

When Mother is visible, retain her same face, warm medium-brown complexion,
traditional half-up black hairstyle unless the approved task requires a
temporary work-safe arrangement, small red bindi, left-nostril gold nose pin,
thin glass bangles, small traditional gold jhumkas, and exactly one simple gold
chain carrying a traditional thali pendant. Her jhumkas and single thali chain
may respond subtly to natural body motion; do not replace, multiply, remove, or
make them ornate.

The Family Dog remains a gentle German Shepherd household companion. It may
wait, follow, look, rest, respond softly, or play naturally. It is never an
attack, police/military, chase, rescue, missing-pet, injury, threat, or stakes
device.

---

## Inputs And Outputs

### Required Inputs

Do not assemble the final Flow prompt until this brief is complete. Use `NONE`
only when genuinely unnecessary. Use `OPEN` only with a named owner and
resolution path.

```text
Episode / scene / shot ID:
Animation revision and requesting owner:
Approval status of scene, board, and source still(s):

Format: Shorts / long form / both:
Delivery aspect ratio and resolution:
Target clip duration:
Caption-safe / crop-safe area:
Shot purpose and one-sentence visible moment:

Approved source still A filename and revision:
Source still B filename and revision, if used:
Input mode: one-image / two-image:
Reference attachments and role:

Start state:
End state:
One principal character action:
Permitted secondary character response:
Object start state / permitted change / end state:
Environment start state / permitted motion / end state:
Camera start framing / permitted movement / end framing:

Location, zone, and orientation:
Season, time, weather, and visible consequence:
Lighting source, direction, quality, and continuity:
Character identities, clothing condition, positions, and screen direction:
Object positions, handlers, and continuity:
Incoming shot and outgoing shot:
Audio / edit / transition note:

Known risks and scene-specific negatives:
Open facts and owner:
```

### Required Output

The completed animation package contains:

1. a source manifest and source-image approvals;
2. the selected Flow input mode and attachments;
3. one concise Flow movement prompt;
4. an explicit start/end state ledger;
5. camera, lighting, screen-direction, and negative movement constraints;
6. target duration, ratio, crop-safe constraints, and edit intent;
7. candidate IDs, settings available to the operator, QA decision, and revision
   record; and
8. the selected clip plus a handoff record for the edit.

---

## Source-Lock Loading

Load only facts that constrain this clip. Do not paste whole manuals into Flow
or let a mood reference silently redefine a character or location.

Before animation, build a compact source packet containing:

```text
Source path:
Source heading:
Applied fact:
What it locks in this clip:
Risk if ignored:
```

Always load:

- applicable `01_Canon/` timeline, continuity, art-style, lighting, and camera
  constraints;
- the approved scene card, storyboard, start/end ledger, and adjacent-shot
  handoff;
- the selected source still(s) and their image-prompt/QA record;
- applicable character, location, object, and research sources;
- `07_Episode_System/` rules relevant to the delivery format and visual rhythm;
- `08_Production/` Google Flow, edit, file, and quality-control requirements;
- `09_AI_Production_System/README.md`, `01_Master_Workflow.md`, and
  `04_Master_Image_Prompt.md`.

Add Father’s stored reference when the identity rule above requires it. Do not
attach it merely as visual decoration. If Mother is visible, explicitly retain
her jhumkas and one thali chain in the prompt when the framing makes them
reasonably visible.

Classify each loaded fact as `HARD LOCK`, `SCENE FACT`, `MOTION CHANGE`,
`CONTINUITY BRIDGE`, `NEGATIVE`, `REFERENCE`, `OPTIONAL DETAIL`, or `OPEN`.
Resolve an `OPEN` or contradiction before animation.

---

## Image Prompt Versus Animation Instructions

Do not blur these jobs.

| Belongs in the still-image prompt | Belongs in this Flow animation prompt |
| --- | --- |
| Who and what is visible; exact period, location, wardrobe, props, materials, composition, source light, and final keyframe appearance. | What changes from the approved source: one bounded action, speed, movement path, camera behavior, subtle environmental response, and end boundary. |
| Camera position, shot size, screen direction, landmark geography, and crop-safe composition. | Whether that established camera holds, drifts, pans, tracks, or makes one small approved reframing move. |
| The required look of Father, Mother, the Dog, objects, and environment. | Preserve those locks while moving; never use movement as permission to transform, reveal a new feature, or replace a lock. |
| Still weather state: rain visible, damp ground, wind condition, time, and light direction. | Limited continuation: drops fall, leaves stir, fabric shifts, smoke rises, shadows remain consistent. |

The animation prompt must not re-describe every image detail. Refer to the
approved source still and restate only locks at risk during motion. Conversely,
an image prompt must not claim that a camera move or multi-phase action is
already visible in a single frame.

---

## Choosing Flow Input Mode

### One-Image Input

Use one approved still when the shot begins from that exact composed state and
the clip needs a small, self-contained change without a tightly prescribed final
composition.

Appropriate uses:

- a held establishing view with subtle leaves, smoke, water, or rain;
- one person completing one small visible action;
- an insert such as hands setting down a documented vessel;
- a reaction where posture changes modestly;
- an isolated clip that cuts out before a new composition is required.

One-image input is not permission for Flow to invent the end state. State the
end boundary in words and reject a candidate that crosses it.

### Two-Image Input

Use two approved stills only when both the incoming and outgoing visual states
must remain controlled and they represent the same continuous beat. Still A
defines the exact beginning; still B defines the exact permitted ending.

Appropriate uses:

- a documented object moves from a known starting position to a known ending
  position;
- a character must arrive at an approved end pose or screen side;
- a continuity bridge must match adjacent shots;
- the camera must end on a composition already approved for the cut;
- a hand-off, turn, sit, stand, or small travel beat needs both endpoints.

Do not use two images to force a time jump, conceal a story gap, connect
different locations, change weather/time/light, switch wardrobe, add/remove a
person, or ask for multiple actions. If A and B disagree on a hard lock, repair
the stills or return to the board; do not ask Flow to reconcile them.

### Decision Test

Choose:

```text
ONE IMAGE  — source state is exact; end is a modest bounded variation; cut-out
             does not require a fixed pose or composition.
TWO IMAGES — both endpoints are approved and the exact end state matters for
             continuity, object state, screen direction, or the next cut.
STILL/CUT  — action is unnecessary, too complex, or safer as an edit transition.
HOLD       — source, endpoint, or continuity fact is open or contradictory.
```

---

## Motion Design Rules

### Start And End State

Every clip needs one observable start and end state. Use action phases, not
vague intention.

```text
START: Father’s right hand rests beside the loose wooden handle; he looks down.
CHANGE: He lifts the handle once and seats it carefully.
END: The handle is seated; his hand relaxes; he remains on the same screen side.
```

State what does not change as clearly as what does:

```text
UNCHANGED: same rear yard, late-afternoon west light, seated posture, clothing,
tool position except handle, Father identity, camera side, and screen direction.
```

Do not request a full task sequence in one clip. “Father repairs the tool,
tests it, smiles at Mother, then walks away” is four beats; split it.

### Character Movement

Use grounded, economical, character-appropriate motion:

- one hand reaches, places, folds, pours, adjusts, passes, or rests;
- a person takes a few measured steps, sits, stands, turns slightly, looks,
  nods, or responds with a restrained expression;
- body weight, feet, hands, cloth, hair, and eyeline move in believable order;
- expressions change subtly and only when supported by the approved beat.

Keep the cast small. A secondary person may make one quiet, clearly subordinate
response only if approved. Do not create crowd choreography, broad gesturing,
theatrical acting, fast walking, running, dramatic turning, dancing, or a new
conversation through mouth movement unless the shot is approved for it.

Mother’s cotton saree, hair, jhumkas, thali chain, and bangles should obey her
body motion and gravity. Their movement is small and natural, never a glamour
effect. Father walks steadily and purposefully without strutting, rushing, or
becoming a heroic figure.

### Object Movement

Move only the object that carries the approved action. State its handler,
material, path, scale, and final state.

- A brass vessel can be lifted, tilted gently, set down, or passed.
- A wooden handle can be aligned and seated.
- A cloth can be folded over school paper.
- A basket can be carried a short distance and placed.

Keep grips, weight, contact, and collisions believable. No object should melt,
multiply, turn into another object, float, teleport, grow, vanish, pass through
hands, or acquire a new use. Do not animate a fragile, detailed, or
continuity-critical object if an insert or still will tell the beat more safely.

### Environment Movement

Environmental motion supports place and weather; it does not create spectacle.

- Mild breeze: limited leaf, hair, saree-edge, and hanging-cloth motion.
- Rain: consistent falling direction, small ripples, damp surfaces, and no
  sudden storm escalation.
- Hearth: restrained motivated smoke and flame movement.
- Water: small ripples or a gentle pour when the scene requires it.
- Animals: a calm ear turn, head movement, tail movement, or small reposition.

Keep permanent landmarks, architecture, vegetation, ground condition, and
weather consequence stable. No sudden wind gusts, lightning, dust storms,
exaggerated smoke, flooding, impossible foliage waves, or moving background
people unless the board specifically requires them.

### Camera Direction And Movement

The default camera instruction is `LOCKED CAMERA`. Stillness is a deliberate
creative choice and often gives the cleanest cut.

When movement serves the shot, choose one modest behavior:

```text
LOCKED       Hold the established frame.
GENTLE PUSH  Move slightly closer to reveal the approved action or response.
GENTLE PULL  Open slightly to reveal an approved spatial relation.
SLOW PAN     Reframe across one continuous, already-visible direction.
SHORT TRACK  Follow a few grounded steps while retaining side and geography.
SUBTLE TILT  Reveal a nearby approved detail without changing spatial logic.
```

State the camera’s start framing, direction, speed, endpoint, and what it must
not cross. Do not combine a pan, push, orbit, tilt, rack focus, and character
travel in one clip. No fast moves, whip pans, zoom bursts, orbiting, handheld
shake, focus hunting, lens distortion, crash zooms, abrupt reframing, or
unmotivated shallow-focus blur.

### Duration

Set duration by the smallest readable action, not by a tool maximum.

```text
1–2 seconds  brief insert, held atmosphere, simple glance, minimal reaction
2–4 seconds  one hand action, modest turn, short environmental continuation
4–6 seconds  one clear action plus settling end state, or slow simple travel
```

Use shorter clips when action, identity, or object fidelity is fragile. Divide
longer process into adjacent clips with intentional cuts. Do not fill time with
looping gestures or invented activity. The requested duration is a delivery
target; the actual candidate must be evaluated for readable start, change, and
resting end.

---

## Continuity Bridge And Hard Constraints

Record the bridge before prompting:

```text
INCOMING: previous shot’s exit pose, location zone, screen side, travel
direction, object state, wardrobe/wetness, emotional state, weather, and light.
THIS CLIP: exact start, one permitted change, exact end.
OUTGOING: next shot’s required entry pose, screen side, object state, eyeline,
light, and edit relation.
```

### Camera, Lighting, And Screen Direction

- Keep people, key objects, and travel on their approved screen side. A
  left-to-right action remains left-to-right unless the board explicitly
  establishes a motivated reversal.
- Retain the camera side of the action. Do not cross the line of action, flip
  faces, reverse a held object, or mirror the location.
- Preserve shot size and source composition unless one modest planned camera
  move changes them.
- Preserve time, weather, sun direction, shadow direction, source warmth, and
  exposure across the clip and adjacent shots. No drifting golden-hour light,
  sudden blue treatment, artificial rim lights, flicker, or day/night change.
- Preserve wardrobe, hair arrangement, jewellery, wetness, dirt, prop damage,
  hand occupancy, and object position except for the named change.
- Retain clear action and caption-safe space. Do not move essential faces,
  hands, or evidence into a crop or subtitle area.

### Negative Movement Constraints

Apply these to every Flow request, plus scene-specific exclusions:

```text
No identity drift, age change, face replacement, hairstyle change, body-scale
change, wardrobe change, jewellery loss/addition, extra people, duplicate limbs,
extra fingers, malformed hands, object transformation, object duplication,
teleportation, floating, modern item, text, subtitle, logo, watermark, border,
collage, visual-style shift, named-property imitation, CGI/hyper-real drift,
chibi anatomy, heavy cel shading, action-camera distortion, screen-direction
flip, camera-line crossing, sudden light/weather/time change, dramatic emotion,
running, chase, rescue, threat, panic, animal distress, or unapproved event.
```

When Mother is visible, also specify: no missing jhumkas, no extra necklace, no
missing or altered thali pendant, and no ornate jewellery. When Father is
visible, specify: same person as the attached canon reference; no clean shave,
heavy beard, salon styling, fashion-model treatment, or gym-built body.

---

## Copy-Ready Master Google Flow Prompt

Complete every variable from approved sources. Variables select facts; they
never override the locks. Keep the completed prompt concise. Delete a variable
only when its field is explicitly `NONE`, rather than inventing a replacement.

```text
CREATE ONE SHORT, CONTINUOUS, EDIT-READY ANIMATION CLIP for Village Stories.

SOURCE AND OUTPUT
Use [INPUT MODE: ONE APPROVED SOURCE STILL / TWO APPROVED ENDPOINT STILLS].
Source A is the exact start state: [SOURCE A FILENAME AND REVISION].
[If two-image: Source B is the exact approved end state: SOURCE B FILENAME AND
REVISION. Animate only the continuous transition from A to B.]
Delivery: [ASPECT RATIO, RESOLUTION IF SET, TARGET DURATION].
Shot purpose: [ONE SENTENCE VISIBLE STORY MOMENT].

IMMUTABLE SERIES LOCKS
Preserve early-1990s rural Tamil Nadu: specific, lived-in, dignified,
period-correct daily life, clothing, objects, architecture, materials, and
infrastructure. No modern technology, screens, LED lighting, modern vehicles,
branding, contemporary packaging, current fashion, urban infrastructure, or
unsupported items.

Preserve the original Village Stories premium cinematic anime identity:
semi-realistic South Indian characters, believable anatomy, soft painterly
hand-painted digital rendering, restrained organic linework, natural material
texture, soft global illumination, detailed culturally accurate environment,
and warm restrained slice-of-life feeling. Do not name or imitate a studio,
artist, film, franchise, or other property.

CONTINUITY LOCK
Location / zone / orientation: [APPROVED FACTS].
Season, time, weather, and visible consequence: [APPROVED FACTS].
Lighting: [MOTIVATED SOURCE, DIRECTION, QUALITY, AND MATCH TO ADJACENT SHOTS].
Incoming and outgoing bridge: [EXIT FACTS > THIS CLIP CHANGE > ENTRY FACTS].
Keep approved character positions, wardrobe condition, hair, jewellery, object
state, screen direction, camera side, and emotional scale unchanged except for
the single movement stated below.

CHARACTER IDENTITY
[APPROVED VISIBLE SUBJECTS AND ONLY THEIR RELEVANT LOCKS.]
If Father is visible: preserve the same recurring individual as attached
CHARACTER_IDENTITY reference
11_Assets/Character_References/Father_Canon_Design_Reference.png: thick
naturally tousled black hair, light natural stubble, warm medium-brown
complexion, lean farmer build, broad shoulders, strong forearms, calm grounded
presence. Do not alter identity, grooming, build, or clothing.
If Mother is visible: preserve her same identity, practical cotton saree and
blouse, small gold jhumkas, exactly one simple gold chain with traditional thali
pendant, left-nostril gold nose pin, thin glass bangles, and natural restrained
movement. No missing jewellery, extra chain, or glamour styling.

START STATE
[EXACT OBSERVABLE START POSE, OBJECT STATE, CAMERA FRAME, AND ENVIRONMENT.]

ONE PERMITTED CHANGE
Character movement: [ONE GROUNDED ACTION, PATH, SPEED, AND RESTING END POSE].
Object movement: [HANDLER, OBJECT, START, PATH, AND END STATE; or NONE].
Environment movement: [SUBTLE APPROVED CONTINUATION; or NONE].
End state: [EXACT OBSERVABLE RESULT; match SOURCE B if two-image].

CAMERA
[LOCKED CAMERA / ONE MODEST APPROVED MOVE]. Start [FRAME]; move [DIRECTION AND
SPEED] only as needed; end [FRAME]. Preserve camera side, screen direction,
crop-safe action, and clear view of [FACE / HANDS / OBJECT]. No other camera
movement.

MOVEMENT LIMITS
Keep all motion slow, natural, physically believable, and proportionate to the
approved slice-of-life moment. No new action after the stated end. Let the clip
settle briefly in the end state.

NEGATIVE CONSTRAINTS
No identity drift, age/body/face/hair change, wardrobe or jewellery change,
extra people or limbs, malformed hands, object transformation/duplication/
teleportation, modern items, text, logos, watermarks, visual-style shift,
camera-line crossing, screen-direction flip, sudden light/weather/time change,
fast camera, zoom burst, orbit, shake, melodrama, danger, panic, chase, rescue,
or animal distress.
[SCENE-SPECIFIC NEGATIVES.]

RETURN ONE CANON-SAFE, CONTINUOUS CLIP ONLY.
```

---

## Assembly And Google Flow Handoff

1. Confirm the scene, board, source still(s), and adjacent continuity are
   approved.
2. Build the compact source packet and resolve all open facts.
3. Decide whether no animation, one-image input, or two-image input best serves
   the edit.
4. Record the exact start state, one change, exact end state, and what remains
   unchanged.
5. Attach approved source still(s). Attach Father’s canon identity reference
   when required. Give every attachment one role.
6. Choose the shortest readable duration and the least complex camera behavior.
7. Complete the master prompt without weakening permanent locks.
8. In Google Flow, select the approved image input(s), delivery setting, and
   available duration setting. Paste the compact movement prompt; do not append
   improvised creative direction.
9. Generate a small deliberate candidate set. Preserve source filenames,
   prompt revision, available tool settings, and candidate IDs.
10. Review motion at intended delivery crop and beside adjacent shots. Select,
    repair, regenerate, split, use a still, or return the shot upstream.

Google Flow receives an approved visual source and bounded action. It may not
decide story, dialogue, emotion, historical detail, casting, unseen location
layout, or a new camera grammar.

---

## Quality Gates, Rejection, And Revision

Review the candidate clip, not the wording of the prompt.

### Approval Gates

**1. Canon and period** — no modern drift; approved location, weather, light,
time, object, and cultural facts remain true.

**2. Identity and anatomy** — recurring people remain recognizably the same
individuals throughout the clip; Father matches his reference; Mother retains
her jhumkas and exactly one thali chain when visible; hands, faces, scale, and
the Dog are natural.

**3. Motion and object logic** — one action begins clearly, moves physically,
and ends in the approved state. Nothing unapproved moves, changes, appears, or
disappears.

**4. Camera and continuity** — camera behavior, screen direction, geography,
light, object state, wardrobe, and incoming/outgoing states cut correctly.

**5. Style and delivery** — painterly original premium anime look remains
stable; action reads at delivery size; crop-safe and caption-safe areas remain
usable; no text or watermark appears.

**6. Story and YouTube integrity** — the clip shows a real approved moment.
It does not manufacture urgency, a false mystery, danger, or an incomplete
promise simply to increase retention.

```text
APPROVE — all required gates pass.
APPROVE WITH EDIT NOTE — valid only with a documented crop, trim, or cut.
REPAIR — isolated local defect; preserve approved motion and source locks.
REGENERATE — prompt or source defect affects the clip materially.
SPLIT OR USE STILL — requested action is too complex or motion adds no value.
RETURN TO BOARD — action, endpoint, or camera intent is unclear.
HOLD FOR CANON OR RESEARCH — essential fact is open or contradictory.
REJECT — hard lock, safety, identity, period, or continuity failure.
```

Reject immediately for recurring-character redesign, Mother’s incorrect
jewellery, Father identity drift, modern content, named-property imitation,
unusable anatomy, false danger, threatening/injured Dog, screen-direction flip,
unapproved event, camera spectacle, text/watermark, or a clip that cannot cut
to its neighbours.

Revise the smallest responsible layer:

- bad still identity/composition: repair or regenerate the image source first;
- wrong endpoint: correct the state ledger or use two approved endpoints;
- overloaded motion: divide into clips or use an insert/still;
- camera drift: lock the camera or name only one smaller move;
- object instability: simplify handling, use an insert, or retain a still;
- lighting/period drift: restore the source lock and remove unsupported detail;
- repeated failed output: change the faulty layer, not random wording.

Never use a rejected candidate as a reference.

Record:

```text
Shot ID / candidate ID / prompt revision:
Input mode and source asset revisions:
Observed defect and failed gate:
Severity and decision:
Responsible layer:
Single corrective change:
Retained locks and references:
Reviewer and date:
New candidate / final edit note:
```

---

## Shorts, Long Form, And YouTube

### Shorts

For 9:16 Shorts, keep the meaningful action central and crop-safe. Prefer one
immediately understandable movement, a readable face/hand/object relationship,
and a settled final image. Do not turn vertical framing into frantic camera
motion. Leave the planned caption area clear of hands, faces, key props, and
the thali pendant or other necessary visual evidence.

The opening motion must truthfully represent the episode’s actual practical
moment. Do not use alarm, danger, a misleading before/after, or a withheld
resolution as a hook. The Short still needs a complete small emotional rest.

### Long Form

For 16:9 long form, earn duration through distinct, meaningful process,
location, relationship, atmosphere, sound, and time—not through lengthening a
single synthetic motion. Use a measured mix of held frames, inserts, one-action
Flow clips, and edits. Preserve wider geography and screen direction so the
viewer can follow the family’s work without visual fatigue.

### YouTube Considerations

Animation must support truthful packaging, not create a thumbnail or title
promise the episode cannot fulfill. Prioritize a clear first visual, readable
delivery crop, stable output free of accidental text, and a final frame that can
rest before the next cut. Retention comes from genuine process, care, visual
clarity, and satisfying completion—not speed, spectacle, cliffhangers, or
emotionally manipulative motion.

---

## Positive And Negative Examples

### Positive: Mother Waters a Seedling — Short

**Image prompt owns:** Mother crouched beside the approved garden seedling in a
vertical, east-lit summer-morning frame; her practical cotton saree, small
jhumkas, one thali chain, vessel, soil, and protected central action area.

**Animation instruction:** Locked camera. Mother tips the documented vessel
once; a small stream darkens the soil around the seedling. Her wrist and
bangles move naturally, the saree edge shifts slightly in a mild breeze, and
she returns the vessel upright. End before she stands or begins another task.

This is a one-image clip because the cut-out does not require a separately
prescribed end composition.

### Positive: Father Seats a Handle — Long Form

**Image prompt owns:** Medium-wide rear-yard view, approved tool and
pre-repair state, Father’s approved work clothing and pose, late-afternoon west
light, exact camera side, and attached Father identity reference.

**Animation instruction:** Locked camera. Father aligns and presses the loose
wooden handle into place once; his shoulders and forearms make a small grounded
effort, then relax. Keep the tool on its current side and end with the handle
seated. No test swing, triumphant expression, or walk-away.

Use two images if the outgoing cut requires the precisely seated-handle frame;
otherwise one image can be sufficient.

### Positive: Monsoon Kitchen Insert

**Image prompt owns:** Close view of documented damp firewood by the kitchen
hearth, diffused monsoon doorway light, modest smoke, and period-correct
materials.

**Animation instruction:** Locked camera for two seconds. A small plume of
motivated smoke rises and soft rain continues beyond the doorway. The wood,
hearth, light direction, and room remain unchanged.

### Reject: “Make the Scene More Emotional”

Do not ask Flow to add a tearful face, dramatic wind, fast push-in, thunder,
running child, or anxious Dog to an ordinary household task. This changes story
scale and invents meaning. Return to the scene owner if the approved beat is
not emotionally clear through existing action.

### Reject: “Father Walks Across the Village”

A continuous wide travel montage with changing landmarks, weather, crowds,
camera angles, and multiple tasks is not one Flow action. Board distinct route
shots, use short tracks only where needed, and cut between approved locations.

---

## Edge Cases

- **No visible movement needed:** Use the approved still with intentional sound
  or a short atmosphere clip. Do not animate merely because Flow is available.
- **Dialogue shot:** If audio supplies speech, keep lip movement minimal unless
  a dedicated approved dialogue workflow supports it. Use reaction, hands, or a
  held profile when accurate mouth motion is unreliable.
- **Off-screen action:** Do not have Flow reveal an unseen person, object, or
  event. Show a source-backed reaction or cut to an approved insert.
- **Object enters/exits frame:** State its exact entering side, handler, path,
  and end state. Use two images or split the shot if its continuity matters.
- **Rain or wind:** Continue the established condition gently. Never turn a
  seasonal atmosphere into disaster effects.
- **Occluded jewellery or reference features:** Do not force a close-up merely
  to show them. Preserve them when reasonably visible; use the source and
  identity locks to prevent alteration.
- **Two source images differ:** They must agree on identity, clothing, light,
  location, style, and camera grammar. If not, repair the sources rather than
  interpolating drift.
- **Clip loops awkwardly:** Trim before a repeated motion or regenerate a
  shorter single-phase action. Do not accept an obvious loop.
- **Candidate is beautiful but uncuttable:** Reject or approve only with an
  explicit edit note. A clip that breaks the bridge is not production-ready.
- **Child or Dog action:** Keep it calm, supervised when appropriate, and
  ordinary. Do not create stakes, rescue, fear, or burden.

---

## Related Documents And Final Authority

Use this manual with:

- `09_AI_Production_System/README.md`
- `09_AI_Production_System/01_Master_Workflow.md`
- `09_AI_Production_System/03_Master_Script_Prompt.md`
- `09_AI_Production_System/04_Master_Image_Prompt.md`
- applicable `01_Canon/`, `02_World/`, `03_Characters/`, `04_Objects/`,
  `05_Research/`, `06_Story_Engine/`, `07_Episode_System/`, and
  `08_Production/` sources
- `03_Characters/Family/Father/Appearance.md`
- `03_Characters/Family/Mother/Appearance.md`
- `03_Characters/Family/Mother/Clothing.md`
- `11_Assets/Character_References/Father_Canon_Design_Reference.png`

The Story Engine decides whether a moment belongs in the series. The Episode
System decides how it serves the viewer. Production decides execution, edit,
and release. This manual controls reusable animation-prompt assembly within the
AI Production System; it never overrides higher sources.

If higher authority changes, rebuild affected source packets and revalidate the
still(s), Flow prompt, selected clip, continuity bridge, and edit use.

## Guiding Principle

> Use AI to reproduce a carefully known world in motion—not to invent a
> different world between frames.

Before approving a clip, ask:

> Does this movement preserve the known people, place, period, objects, light,
> screen direction, and emotional scale while making one approved action more
> alive and easier to edit?

If not, reject the candidate or revise the earliest responsible decision. Do
not ask animation to make an unsupported world, unclear action, or weak cut
feel true after the fact.
