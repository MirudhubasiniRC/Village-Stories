# Image Prompt Reference

## Purpose And Relationship

This is the detailed supporting reference for
`09_AI_Production_System/04_Master_Image_Prompt.md` (the Master Manual).

The Master Manual is the concise operational document used to assemble, validate,
generate, review, revise, and hand off a still-image prompt. This reference
preserves the expanded series locks, source-loading rules, lock-selection system,
reference-image guidance, Flow planning, composition rules, diagnostic guidance,
and examples that support that work.

Use the Master Manual to run production. Use this reference to answer a detailed
decision, resolve a constraint, or diagnose a failure. This reference does not
create canon or override the authority order stated in the Master Manual.

---

## Expanded Permanent Series Locks

### Time And Place

The series is set in early-1990s rural Tamil Nadu. The exact calendar year may
remain flexible; the historical period does not.

Visible work, travel, communication, household routines, and problem solving
must use believable locally available materials and effort. Each scene has a
defined season, time of day, weather condition, and visible consequence where
relevant.

The village is lived in, specific, practical, and dignified. Dirt, wear,
dampness, repaired surfaces, and handmade variation may appear when supported by
the location and moment. The setting must never become an impoverishment
spectacle or a generic “exotic village.”

Reject modern or unsupported mobile phones, internet or social-media signs,
digital payments, LED fixtures, modern appliances, current vehicles,
contemporary branding, current fashion, plastic-dominant decor, urban
infrastructure, glossy packaged goods, modern road markings, and electronic
screens.

### Core Family

The established family is Mother, Father, Elder Brother, Younger Daughter, and
the German Shepherd Family Dog. Only show a family member when the approved scene
gives that person a source-backed reason to be present. Do not add the entire
family merely to make a composition busy.

### Mother

When Mother is visible, preserve her approved appearance, age, scale, posture,
hairstyle, wardrobe, expression, and relationship behaviour from her source
packet.

Her permanent jewellery identity is:

* small traditional gold jhumkas;
* one simple gold chain carrying her traditional thali pendant;
* a small gold nose pin on the left nostril; and
* thin glass bangles.

Mother wears one thali chain, not multiple necklaces. Her jhumkas and thali
chain remain modest, visible when framing and pose reasonably permit, and never
become ornate fashion jewellery. Her everyday clothing follows canonical
traditional cotton saree and practical blouse logic.

Never replace her with a glamorous redesign, contemporary fashion look, ornate
bridal styling, or inconsistent facial identity.

### Father

When Father is visible, preserve the same individual established by:

```text
11_Assets/Character_References/Father_Canon_Design_Reference.png
```

This is a character lock, not a temporary mood reference. Preserve his face,
thick naturally tousled black hair, light naturally kept stubble, warm
medium-brown South Indian complexion, calm observant expression range, lean
farmer build with broad shoulders and strong forearms, natural outdoor-worker
posture, and age-appropriate semi-realistic anime identity.

Father’s typical work clothing follows the canon packet: practical cotton shirt,
often deep muted blue, cotton veshti or work veshti, and a simple thundu where
the scene supports it.

Never render Father as clean-shaven, heavily bearded, salon-styled, gym-built,
fashion-model glamorous, or as a different man.

### Family Dog

The Dog is a gentle, loyal household companion. It may wait, follow, observe,
rest, respond softly to a familiar sound, play naturally, or receive ordinary
care.

It must never become a police dog, military dog, attack dog, rescue device, chase
device, missing-pet plot device, injured-animal hook, threat, or source of fear.

### Style

Village Stories has an original premium cinematic anime identity. Every accepted
image must use:

* semi-realistic anime characters;
* natural South Indian facial features, skin tones, hair, and proportions;
* soft painterly hand-painted digital rendering;
* layered colour and natural material texture;
* refined organic linework only where it helps clarity;
* soft global illumination and natural colour grading;
* film-quality but story-serving composition;
* atmospheric depth grounded in weather and distance;
* detailed, culturally accurate rural environments;
* believable anatomy and subtle expressions; and
* warm, observant slice-of-life feeling.

Never use named-studio, named-film, named-artist, or franchise visual language;
heavy cel shading; chibi proportions; comic-book outlines; plastic CGI;
hyper-real human faces; glossy synthetic surfaces; generic low-detail anime;
vector-flat illustration; neon colour treatment; excessive bloom; unmotivated
coloured rim lights; or action-film spectacle.

### Lighting, Geography, And Camera

Light must arise from documented time, weather, architecture, and global village
orientation:

* morning light enters from the east;
* evening light enters from the west;
* the family house, rear yard, and kitchen lie west;
* paddy fields and pond lie east;
* village entrance, banyan tree, and river ghat lie north; and
* fields, pond, and irrigation canal lie south.

Do not reverse sun direction between adjacent shots. Use warm and sunlit lighting
for supported clear mornings, sunny afternoons, golden evenings, dry summer, and
warm harvest conditions. Use cool, diffused monsoon lighting for rain, cloud
cover, mist, and wet afternoons. Monsoon images remain inviting, never cold,
disaster-like, or blue-black thriller scenes.

The camera is a patient observer at a plausible human viewpoint. Prefer stable
observation, eye-level or gently elevated viewpoints, modest story-grounded low
angles, a clear subject, intentional foreground/middle/background, readable
eyelines, preserved screen direction, and negative space only where the edit
needs it.

Avoid extreme Dutch angles, impossible aerial or drone viewpoints, action-camera
distortion, fisheye lenses, aggressive forced perspective, surveillance framing,
spectacle-only hero angles, and arbitrary lens language.

---

## Source-Of-Truth Loading Matrix

Build a compact image canon packet for each shot. Load facts, not whole files,
into the working prompt record.

### Always Load

* Applicable `01_Canon/` time, continuity, art-style, lighting, and camera
  locks.
* Relevant early-1990s rural Tamil Nadu research and exclusions.
* Approved episode brief, script beat, storyboard, and scene-state ledger.
* `09_AI_Production_System/01_Master_Workflow.md`.
* The Master Manual’s mandatory locks.
* Prior selected shot when continuity is required.

### When A Character Is Visible

Load appearance, clothing, expressions, voice/body-language guidance where it
affects pose, continuity notes, relationship limits, approved visual reference,
and scene-specific wardrobe state.

For Father, always load and attach the stored canon design reference when the
tool supports reference input.

### When A Location Is Visible

Load location layout, orientation, entry and exit logic, permanent landmarks,
materials and surface condition, local object placement, seasonal response,
lighting behaviour, and approved location references or selected prior frames.

### When An Object Is Story-Relevant

Load object identity, material, scale, period accuracy, current condition, owner
or usual location, handling method, start state, and required final visible
state.

### When Preparing Flow Inputs

Load selected still image, motion purpose, intended start and end state, camera
plan, action boundary, transition target, crop requirement, and whether a second
image is justified.

### Required Packet Labels

```text
HARD LOCK — cannot change in this shot
SCENE FACT — required in this shot
OPTIONAL DETAIL — permitted but not required
OPEN FACT — blocks or limits generation
NEGATIVE — must not appear
REFERENCE — image or selected prior output and its exact role
```

Do not describe optional atmosphere as a hard lock. Do not treat a hard lock as
a style preference.

---

## Detailed Lock-Selection System

Select locks before writing prose. Do not rely on memory for recurring facts.

### Character Locks

Use a character lock when a recurring character’s face is visible; they are
identifiable through body or clothing; a hand, jewellery item, garment, or
posture carries continuity; they are an emotional subject; the shot connects to
another image; or the still will be used as a Flow source.

```text
Identity:
Age and build:
Face and hair:
Skin tone:
Clothing and current condition:
Jewellery or distinctive accessory:
Pose and expression:
Screen position and eyeline:
Required reference:
```

For an extreme close-up, prioritize face, hair, skin tone, expression,
jewellery, and light. For a distant figure, prioritize silhouette, clothing
colour and shape, scale, screen side, and action.

### Location Locks

Use a location lock when it is recurring; a route or entrance matters; the shot
establishes orientation; it owns a story object; weather changes usable surfaces;
a later cut must match; or it is central to the episode.

```text
Location name and source:
Specific zone:
Compass or local orientation:
Permanent landmarks:
Architecture and materials:
Ground condition:
Season/weather condition:
Permitted background activity:
```

Do not substitute generic huts, tropical foliage, or generic Indian village
streets for an approved specific location.

### Object Locks

Use an object lock when it causes the scene action, carries a before/after state,
is handled on screen, is a recurring household object, its position affects the
cut, or the tool might replace it with a modern equivalent.

```text
Object name and source:
Material and period identity:
Scale:
Current condition:
Position:
Who handles it:
Visible action:
Required state at this image moment:
```

Never call for “an old traditional item” when the board requires a documented
object with an exact functional identity.

### Style And Camera Locks

Every image receives the complete permanent style lock. Add scene-specific style
detail only when physically motivated: rain-softened surfaces, dust in low
evening light, cloth texture, cooking steam, worn wood, wet earth, or leaf
movement implied by a breeze.

Do not introduce fantasy glow, nostalgic sepia, stylized grain, or unrelated
genre treatment as a scene variable.

Use a camera lock for every shot:

```text
Shot size:
Viewpoint height:
Camera side:
Lens character: natural, non-distorting:
Subject position:
Screen direction:
Foreground function:
Background function:
Crop-safe area:
```

If the board does not define camera side, do not invent a camera move. Use the
most neutral continuity-safe observation and mark the missing board choice.

---

## Visual Priority Order

When the prompt is long or a tool is unreliable, preserve information in this
order:

1. Factual and safety-critical canon.
2. Recurring character identity.
3. Scene action and object state.
4. Location identity and period accuracy.
5. Screen direction and composition.
6. Time, weather, and lighting continuity.
7. Original premium cinematic anime rendering.
8. Edit-safe framing.
9. Secondary texture and atmosphere.
10. Decorative detail.

Do not sacrifice a character face or essential object state for extra plants,
birds, clouds, or background figures. If the tool ignores a lower-priority
instruction, remove lower-priority detail before changing a higher-priority
lock.

---

## Negative Constraint Library

Use only relevant constraints, but never omit likely period or identity risks.
Negatives stop known failures; they do not replace a clear positive instruction.

### Universal

```text
no readable text, subtitles, signs, logos, labels, watermarks, borders,
collages, split screens, duplicate people, extra limbs, malformed hands,
deformed anatomy, modern technology, contemporary packaging, modern clothing,
named-studio imitation, named artist imitation, plastic CGI, hyper-real faces,
heavy cel shading, chibi proportions, comic outlines, vector-flat graphics,
neon lighting, melodramatic danger, disaster imagery
```

### Character

```text
do not change identity, age, body type, skin tone, hairstyle, facial hair,
clothing logic, jewellery, relationship behaviour, screen side, or expression
scale; no glamour makeover, no fashion styling, no exaggerated anime eyes
```

Mother:

```text
no additional necklaces, no ornate jewellery, no missing jhumkas, no missing
thali pendant, no right-nostril nose pin, no modern blouse or saree styling
```

Father:

```text
no clean-shaven redesign, no heavy beard, no styled pompadour, no gym physique,
no fashion-model clothing, no different face; preserve the supplied canon
design reference identity
```

Family Dog:

```text
no aggression, snarling, attack stance, police or military styling, rescue
staging, injury, threat behaviour, exaggerated wolf features
```

### Location, Period, And Composition

```text
no city skyline, no paved modern suburb, no contemporary signage, no electrical
LED strip lights, no modern plastic furniture dominance, no current motorcycle
design, no contemporary cars, no mobile phone, no television screen, no modern
appliance, no branded consumer packaging, no fantasy temple or palace
```

```text
no Dutch angle, fisheye distortion, impossible aerial view, action-camera
perspective, extreme close crop that hides the required action, blocked face,
blocked prop, confusing crowd, arbitrary dramatic lens flare
```

---

## Reference-Image Usage

References constrain specific visual facts. They do not transfer every
incidental colour, crop, mood, prop, or background from the source image.

Assign exactly one primary role to each reference:

```text
CHARACTER_IDENTITY — face, hair, build, age, recurring visual identity
CHARACTER_WARDROBE — approved garment, jewellery, current garment condition
LOCATION_LAYOUT — architecture, orientation, landmarks, spatial relationships
OBJECT_IDENTITY — material, form, scale, period-correct construction
STYLE_TARGET — approved Village Stories rendering only
CONTINUITY_MATCH — prior selected shot's state, screen direction, light
FLOW_START — approved first frame for image-to-video
FLOW_END — justified final frame for a bounded transition
```

Do not call a reference “inspiration.” State what it controls and what it does
not control.

### Hierarchy And Count Discipline

For recurring character identity, use:

1. Current approved character canon reference.
2. Approved selected image from the same continuity sequence.
3. Character appearance, clothing, and continuity documents.
4. Scene brief.

For a recurring location, use:

1. Approved location layout and canon.
2. Approved location reference.
3. Selected prior shot from the same scene or sequence.
4. Scene-specific condition.

If a prior selected image conflicts with higher character canon, correct the
prior image rather than propagate its error. Use the fewest references that
protect the shot; too many competing references cause hybrid identities and
incoherent locations.

Typical guide:

* one reference for a single recurring close-up;
* character and location references for a wide recurring scene;
* one continuity frame plus one character identity reference for a matching
  medium shot;
* one selected still for a simple Flow continuation; and
* two images only when an approved end state truly requires it.

### Reference Preflight

Before attaching a reference, verify it is approved for its role, has no known
canon defect, does not imply an unwanted crop, matches the season or is limited
to identity, contains no text/logos/modern intrusions to copy, has no unresolved
generated drift, and has its filename and revision recorded.

If a canon reference has an incidental wrong background, use it only for its
assigned identity role. Do not copy its background, lighting, wardrobe, or
composition unless separately approved.

---

## Google Flow Input Planning

Google Flow begins with a still that can safely move. The selected still must
already be canon-safe, compositionally readable, and appropriate to the start
state. Do not use Flow to repair a weak image prompt or discover a scene action.

### Start-Image Requirements

The start image must show the required subject clearly; leave space for approved
action; avoid an unmovable pose; preserve hands, feet, and handled objects where
motion needs them; establish screen direction; include motivated light and
weather; avoid cropped action endpoints; support delivery ratio; and contain no
unresolved identity, anatomy, prop, or period issue.

### One-Image Decision

Use one image for a continuation of a stable start frame: a hand setting down a
vessel, Mother looking from task to child, Father adjusting a thundu, a child
gently watering a seedling, the Dog settling by a doorway, steam lifting from a
pot, a small turn toward sound, a slow posture shift, or restrained push-in while
scene state remains stable.

Prefer it when the material state does not change, the action is small and
physically continuous, continuity to the prior cut matters more than visible
transformation, the camera remains observational, or no final frame is needed.

### Two-Image Decision

Use two images only when a controlled approved transition requires a known end
state: an object moves from hand to table, a door closes, a person arrives at a
nearby marked position, an item changes from visibly dry to covered, a verified
lighting change occurs inside one continuous scene, or the next cut needs a
precise final arrangement.

It requires approved start and end images, unchanged character identity,
unchanged location geometry, one continuous action, achievable temporal gap,
recorded action direction, and an interpolation-error review plan.

Never use it for a new beat, location jump, costume change, weather
transformation, sudden time jump, character redesign, unsupported emotional
reversal, crowd appearance, complex multi-person exchange, or substitute for
proper coverage.

```text
Flow task ID:
Source image revision:
One-image / two-image:
Why this option is necessary:
Approved start state:
Approved end state, if any:
Single action:
Camera behavior:
Maximum motion complexity:
Known interpolation risks:
Required rejection criteria:
```

---

## Shot Composition, Lighting, Action, And Expression

Composition serves a visible story question.

An establishing shot orients place, season, weather, time, task context, or
route relation; it is not generic scenery. Preserve readable landmarks and
meaningful scale.

Use a wide shot when body, work area, object relationship, or location geometry
matters. Keep story action readable at delivery crop; never turn it into tiny
decorative figures.

Use a medium shot for practical action, relationship, body language, and
conversation-adjacent observation. Keep hands and essential objects visible.

Use a close-up only for a meaningful decision, expression, hand action, object
condition, sensory detail, or continuity cue; never to manufacture intensity.

An insert must establish object condition, practical action, continuity, sound
anchor, or truthful transition. Do not insert a random picturesque object.

Use foreground only for depth, location identity, gentle framing, a transition
surface, or action relationship. Never let foliage, door frames, or vessels
block the face, hands, or critical object state.

Record which direction each person moves or looks. Preserve direction across a
sequence unless the board gives a clear reset. Do not reverse a person, handoff,
door orientation, or sun direction because a mirror composition looks attractive.

Write the source of light before its aesthetic effect:

```text
soft overcast monsoon daylight from the open east-facing yard, gentle cool
ambient light on wet earth, warm interior bounce from the kitchen doorway
```

Do not use empty instructions such as “beautiful moody cinematic lighting.”
Use contrast to retain action readability; do not bury a face or vital object in
silhouette unless the board explicitly needs a readable silhouette.

One still contains one selected phase: before contact, during contact, after a
small result, or at a quiet resting point. Do not ask it to show a complete
sequence.

Describe expression by observable proportional cues: slight attentive turn, soft
closed-mouth smile, calm focused eyes, curious raised gaze, relaxed shoulders,
brief concern without fear, or quiet satisfaction after a task. Avoid sobbing,
screaming, terror, exaggerated shock, anime rage, melodramatic grief, and
triumphant hero poses.

---

## Shorts, Long Form, And YouTube Use

### Shorts — 9:16

Make central action readable at phone size. Put the main face, hand, or object
in the protected central zone; preserve natural headroom and hand room; avoid
critical detail at top or bottom edges; use vertical architecture/foreground only
when it clarifies depth; leave caption-safe space only when editing requires it;
and do not create a poster layout.

Useful vertical relationships include person and task, hand and vessel, doorway
and waiting Dog, child and seedling, roof edge and rain, and tree canopy framing
a practical action.

### Long Form — 16:9

Use lateral geography intentionally, preserve screen direction, keep necessary
action in title-safe and crop-safe areas, allow environment only when it orients,
avoid empty panoramas with tiny unreadable subjects, and protect both ends of a
potential gentle pan or edit crop.

### Dual Format

Do not assume one composition crops safely to both formats.

```text
Primary delivery ratio:
Secondary crop:
Shared protected action area:
Elements allowed to crop:
Elements that must not crop:
Whether separate images are required:
```

Generate separate compositions when cropping would remove story action, split a
family relationship, hide the essential object, change emotional distance, or
make the setting unreadable.

YouTube planning clarifies delivery, not story truth. Identify whether the
action reads at phone size, the frame may be a truthful thumbnail candidate, the
first Short image promptly shows a real point of interest, crop protects action,
captions have room without emptying scene, and no false urgency is created.

An honest thumbnail may show a real object condition, task, warm relationship,
seasonal condition, or clear location moment. It must not show a frightened face
from an ordinary situation, false disaster, aggressive animal, broken object as
catastrophe, modern dramatic effect, or generated in-image text.

---

## Continuity Rules

Every image agrees with the declared season: Summer, Monsoon, or Post-Monsoon /
Harvest. Show only sourced consequences:

* Summer: dry dust, hard light, thirsty plants.
* Monsoon: wet earth, roof runoff, damp cloth, diffused light, rain response.
* Post-Monsoon / Harvest: harvest material, clearer air, documented seasonal
  work.

Do not mix seasonal evidence for variety.

Across shots, preserve character face, age, height relation, build, hair, skin
tone, clothing set and condition, jewellery, documented handedness, emotional
progression, screen direction, and relationship distance. Record meaningful
changes such as rolled sleeves, wet garment edge, carried cloth, object changing
hands, fieldwork dust, weather-loosened hair, or a packet-permitted removed
layer.

Preserve location layout, compass orientation, entries/exits, permanent
structures, landmark placement, object storage, ground condition, weather
evidence, light direction, and route logic.

For every story-relevant object, record prior/current location, orientation,
handler, condition, visible amount, whether it is full, empty, wet, clean,
covered, open, repaired, or stored, next required state, and whether it exits
the scene. Never allow an object to reset itself between images.

---

## Detailed Diagnostics And Revision

Revise the smallest responsible layer:

```text
Identity drift → character lock or identity reference problem
Wrong jewellery → character sub-lock or visibility/composition problem
Wrong garment → wardrobe lock or scene wardrobe-state problem
Wrong room / yard → location lock or reference-role problem
Wrong object → object lock or object-state problem
Modern intrusion → period negative or insufficient positive context
Wrong sun / weather → lighting and geography lock problem
Bad crop → composition layer or delivery-planning problem
Extra drama → scene moment or negative constraint problem
Generic rendering → style envelope or conflicting reference problem
Flow-unfriendly pose → shot-design and action-boundary problem
```

Use repair only when the scene moment is correct, identity is substantially
correct, composition remains usable, the defect is localized, the repair tool
can target it without disturbing hard locks, and the repaired output will receive
full QA again.

Use a new generation when main identity, location geometry, action phase, or
delivery composition is wrong; defects are coupled; an unapproved event
dominates; or the image cannot be trusted as a Flow source.

Reject immediately for named-property imitation; modern technology or brand
intrusion; redesigned recurring character; false danger, animal threat, or child
endangerment; wrong historical world; unusable anatomy; readable accidental
text; image sequence/collage; or drama beyond approved story. Do not retain a
rejected candidate as a reference image.

---

## Extended Examples And Non-Examples

### Positive: Mother And Seedling

**Approved need:** Younger Daughter sees a drooping seedling during summer.

**Correct still:** A medium vertical image of Mother crouching beside the
seedling, calmly guiding Younger Daughter’s small hand holding a documented water
vessel. Darkening soil is visible, not the entire watering sequence.

**Required locks:** Mother character and jewellery; Younger Daughter packet;
garden; vessel; summer morning east light; 9:16 protected action zone; one gentle
practical action.

This works because it shows teaching relationship, object, action phase, season
pressure, and usable Flow start without exaggerated emotion.

### Positive: Father Repairs A Handle

**Approved need:** Father secures a loosened handle before household use.

**Correct still:** A medium-wide horizontal rear-yard view. Father in approved
work clothing sits beside the documented object and looks down with calm focus;
hands and loosened handle remain visible. Soft late-afternoon west light arrives
from the correct direction.

Attach Father as `CHARACTER_IDENTITY`; lock rear-yard orientation, object
material and pre-repair state, next-cut screen side, observer camera, and no
heroic repair pose.

### Positive: Monsoon Kitchen Insert

**Approved need:** Damp firewood causes smoke while dinner is prepared.

**Correct still:** Close insert of documented damp wood near kitchen hearth,
soft diffused monsoon daylight at doorway, a small believable amount of smoke,
no modern fixture, and no oversized dramatic flame.

It establishes a practical condition without a fearful storm image or character
redesign.

### Reject: External Style Imitation

```text
Make this look like [named studio] with its famous warm style.
```

Reject: the series requires an original visual identity, not imitation.

### Reject: Variable Overrides Canon

```text
[VARIABLE: make Father a clean-shaven fashionable young man in a modern shirt]
```

Reject: a variable cannot replace Father’s stored identity, practical wardrobe,
or the historical period lock.

### Reject: Mother Jewellery Drift

```text
Mother wears layered gold necklaces and large statement earrings.
```

Reject: Mother has modest small jhumkas and one simple thali chain, not layered
fashion jewellery.

### Reject: Generic Village Spectacle

```text
Epic aerial view of an exotic Indian village at sunset, dramatic haze.
```

Reject: geographically non-specific, impossible spectacle viewpoint, and no
approved scene function.

### Reject: Multi-Beat Still

```text
Mother cooks, Father returns home, the children run to him, the dog barks, and
heavy rain starts.
```

Reject: multiple actions, subjects, state changes, and uncontrolled emotion.
Select one frame-worthy phase or create separate shots.

### Reject: Hero Dog Framing

```text
The German Shepherd leaps through the storm to rescue the child.
```

Reject: it violates the Dog’s gentle household role and non-danger story
boundary.

---

## Edge Cases

**Father is distant.** Use the stored reference if practical, but prioritize
recognizable silhouette, approved clothing logic, screen side, height, and
action. Do not force face-detail language that conflicts with scale.

**Mother’s jewellery is hidden by pose.** Do not force unnatural posing to show
every item. Preserve identity in the prompt and assess reasonable visibility in
QA. If a close-up should show ear or neckline but omits jhumka or thali, reject.

**Object mostly offscreen.** State visible portion, position, handler, and
continuity role. If its condition must be understood, use an insert or revise
composition.

**Rain under shelter.** Show rain through a permitted background edge, wet
ground, roof runoff, damp surfaces, or diffused light as required. Do not place
rain uniformly inside a protected interior.

**Location lacks approved visual reference.** Use documented location facts and
a conservative composition. Do not establish permanent layout through an
attractive first generation. Mark it provisional and return location-reference
creation to its owner.

**Character carries a new object.** Pause if it is recurring, story-critical,
culturally specific, or historically uncertain. Load or create approved object
documentation before use.

**Tool cannot follow all constraints.** Reduce optional detail, split the shot,
attach better approved references, or choose simpler composition. Never remove a
hard lock for a polished image.

**Scene needs text.** Generate no readable text. Add subtitles, labels, episode
titles, and packaging text later in controlled post-production.

**Best candidate has a small modern intrusion.** Treat it as a defect. Repair
only if the rest is proven safe; otherwise regenerate.

**Vertical crop damages long-form shot.** Create a separate vertical composition
if central action cannot survive. Do not call a compromised crop multi-platform.

---

## Final Reference Rule

The Master Manual remains the operational prompt authority. This reference
supports it with detailed constraints; neither document overrides factual canon,
character/location/object/research sources, Story Engine doctrine, Episode System
format requirements, or Production execution and release procedures.

When a higher authority changes, rebuild affected canon packets and revalidate
every affected prompt, reference set, selected still, Flow input, and edit use.
