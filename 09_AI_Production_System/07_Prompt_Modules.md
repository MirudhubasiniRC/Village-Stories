# Prompt Modules

## Purpose And Scope

This is the permanent modular prompt architecture for Village Stories.

It defines reusable, traceable modules for assembling canon-safe prompts for
story development, scripts, still images, Google Flow animation, voice, sound
handoff, review, repair, and archive.

Use it with:

- `01_Master_Workflow.md`;
- `02_Master_Story_Prompt.md`;
- `03_Master_Script_Prompt.md`;
- `04_Master_Image_Prompt.md`;
- `05_Master_Animation_Prompt.md`;
- `06_Master_Voice_Prompt.md`;
- the Camera Direction and Camera Movement Bibles;
- applicable canon, research, episode, and production documents.

This manual does not create new character, location, object, story, cultural,
style, or camera canon.

It does not replace a source packet with a convenient summary.

It does not grant a module permission to override a higher authority.

It makes approved information repeatable without turning prompts into
untraceable walls of prose.

## Operating Principle

> Assemble prompts from approved modules; vary only the scene facts that have
> been approved to vary.

A module is a bounded instruction block with:

- a defined purpose;
- an authority source;
- an owner;
- an applicability rule;
- immutable and variable fields;
- a validation method;
- a revision path.

An attractive prompt is not necessarily a safe prompt.

A concise prompt is not necessarily an incomplete prompt.

The best prompt is the smallest complete assembly that reliably produces the
approved task without inventing a different world.

## Authority And Conflict Rule

Modules inherit authority; they do not generate it.

```text
Current approved production decision
↓
01_Canon/
↓
02_World/ · 03_Characters/ · 04_Objects/ · 05_Research/
↓
06_Story_Engine/
↓
Approved episode brief, script, storyboard, scene-state ledger
↓
07_Episode_System/
↓
08_Production/
↓
09_AI_Production_System master prompts and lock systems
↓
This module catalog and assembled task prompt
↓
Tool settings, generated candidate, selected asset
```

Follow the highest applicable source.

Never average conflicting instructions.

Never let a lower module “balance” a higher lock.

If a module conflicts with an approved source:

1. Name the exact conflicting instruction.
2. Identify the source path and revision.
3. Apply the higher authority.
4. Mark the assembly `REVISE` or `HOLD`.
5. Correct the module record only after confirming its owner.
6. Preserve the prior approved module version for traceability.

A prior generation, reference image, tool default, prompt-library entry, metric,
or user preference is never evidence that a conflicting fact is permitted.

## Terms

`MODULE` is a reusable instruction block.

`LOCK` is a fact or rule that must remain stable for the task.

`VARIABLE` is an approved scene-specific selection or state.

`SOURCE` is the document, ledger, reference, or decision that owns a fact.

`OWNER` is the role or document responsible for resolving a fact.

`ASSEMBLY` is the selected module set plus completed variables for one task.

`TASK PROMPT` is the tool-ready text created from the assembly.

`CANDIDATE` is an unapproved tool output.

`SELECTED ASSET` is the approved output with a recorded revision.

`OPEN` is unresolved and must include a named owner and path to resolution.

`NONE` means intentionally unnecessary, not unknown.

`IMMUTABLE` means the operator cannot alter the instruction for the task.

`CONDITIONAL` means the module applies only when its trigger is true.

`SCENE VARIABLE` means a value may change only within the approved scene state.

## Why Modularity Matters

Prompt drift often begins when one operator rewrites familiar facts from memory.

It grows when a revision changes several things at once.

It becomes difficult to repair when no one can identify which instruction owns a
result.

Modules prevent this by separating:

- recurring identity from temporary pose;
- fixed location geography from current activity;
- object identity from current state;
- permanent style from shot mood;
- camera direction from camera movement;
- source language from tool formatting;
- factual instruction from aesthetic wording;
- a prompt defect from a generated-asset defect.

Modules are not a license to paste every available paragraph into every task.

Select only the modules required to make the requested output truthful and
reliable.

## Immutable And Variable Layers

Every assembly has two layers.

### Immutable Layer

The immutable layer protects facts that cannot change because the tool is asked
to make a new image, clip, line, or revision.

Typical immutable modules include:

- global period and world boundaries;
- original premium animated style boundaries;
- relevant recurring character identity;
- approved character reference attachment role;
- documented location layout and orientation;
- recurring object identity and material;
- camera safety and geography rules;
- explicit source hierarchy;
- project safety and dignity boundaries;
- Google Flow preservation constraints;
- approved language and voice-rights constraints.

Immutable does not mean every fact is present in every prompt.

It means that if the fact applies, it cannot be silently rewritten as a scene
preference.

### Variable Layer

The variable layer contains the approved change for this task.

Typical variables include:

- episode, scene, and shot identifier;
- output use and delivery ratio;
- visible action or held moment;
- current pose, expression, and screen position;
- present clothing condition;
- time, season, weather, and immediate light condition;
- object handler, count, position, and current state;
- shot size, framing, and focal hierarchy;
- camera start and end state;
- Flow movement and duration;
- narration unit, pace, emphasis, and protected sound window;
- repair target and acceptance criteria.

A variable may select from approved facts.

A variable may not redefine a lock.

### Variable Decision Test

```text
Does this instruction change a continuing fact?
  Yes → it is a lock or requires source-owner approval.
  No  → continue.

Is the instruction visible, audible, or necessary in this specific task?
  Yes → it may be a scene variable.
  No  → remove it.

Does it conflict with an immutable module?
  Yes → reject it and identify the higher source.
  No  → validate it against the scene ledger.
```

## Module Record Standard

Every permanent module record must use this structure.

```text
Module ID:
Module name:
Status: draft / approved / retired:
Version:
Owner:
Purpose:
Applies to:
Trigger:
Primary source paths:
Higher authority:

Immutable instructions:
Approved variable fields:
Required attachments:
Dependencies:
Incompatible modules or combinations:
Assembly position:
Tool-specific formatting note:

Pre-generation validation:
Output review criteria:
Revision owner and method:
Archive / change-log note:
```

Do not create an informal “temporary module” that becomes a recurring
production rule without being recorded.

If a task needs a one-off instruction, label it a scene variable and retain its
source in the task record.

## Module Catalog At A Glance

```text
CORE
M-00 Task Identity and Output Intent
M-01 Authority and Source Packet
M-02 Global World, Period, and Dignity Lock
M-03 Original Premium Animated Style Lock
M-04 Targeted Negative Constraints

SUBJECTS
M-10 Character Presence and Identity
M-11 Character State, Wardrobe, and Behaviour
M-12 Family Dog Presence and Behaviour

WORLD
M-20 Location Identity and Geography
M-21 Time, Season, Weather, and Light
M-22 Background Life and Environmental Restraint

OBJECTS
M-30 Object Identity and Material
M-31 Object State, Ownership, and Continuity

CAMERA
M-40 Camera Direction and Composition
M-41 Camera Movement and Motion Boundary
M-42 Screen Direction, Edit, and Crop Safety

TOOL AND OUTPUT
M-50 Still Image Task
M-51 Google Flow Input and Preservation
M-52 Google Flow Motion Contract
M-53 Voice and Pronunciation
M-54 Audio / ASMR / Silence Handoff
M-55 YouTube and Accessibility Handoff

CONTROL
M-60 Continuity Bridge
M-61 Reference Attachment Roles
M-62 Validation Gate
M-63 Repair and Revision
M-64 Archive and Provenance
```

The catalog is an architecture, not a default paste list.

## M-00 Task Identity And Output Intent

**Purpose:** establish exactly what is being made and how it will be used.

**Applies to:** every prompt and handoff.

**Immutable instructions:**

- State the task type before descriptive prompt language.
- State a single primary output use.
- Preserve the task ID and revision through the workflow.
- Do not claim approval status that does not exist.

**Approved variables:**

- episode, scene, shot, unit, and revision ID;
- task type;
- format and aspect ratio;
- target duration;
- delivery resolution where known;
- intended downstream use;
- target tool or workflow;
- crop-safe or caption-safe requirement.

**Template:**

```text
Task: [image / Flow clip / voice unit / repair / handoff]
ID / revision: [VARIABLE]
Primary use: [VARIABLE]
Format / ratio / duration: [VARIABLE]
Downstream owner: [VARIABLE]
Approval state of upstream sources: [VARIABLE]
```

**Validation:** task type and output use match the approved production plan.

**Common failure:** requesting a “cinematic scene” without saying whether the
output is a keyframe, Flow source, final still, thumbnail candidate, or edit
insert.

## M-01 Authority And Source Packet

**Purpose:** make the factual basis visible before generation.

**Applies to:** every task involving recurring content or scene facts.

**Immutable instructions:**

- Higher authority wins.
- `OPEN` requires a named owner.
- Tool output cannot resolve a source conflict.
- References control only their declared role.

**Approved variables:**

- source paths and revisions;
- approved scene packet;
- relevant research source;
- character, location, object, and camera sources;
- unresolved item and owner.

**Template:**

```text
Required sources: [VARIABLE: paths and revisions]
Approved scene state: [VARIABLE]
Open facts: [NONE or item / owner / resolution path]
Conflict rule: follow the highest applicable approved source; do not invent or
average conflicting facts.
```

**Validation:** each substantive prompt instruction can be traced to a source,
scene ledger, or approved module.

## M-02 Global World, Period, And Dignity Lock

**Purpose:** protect the permanent setting and ethical tone.

**Applies to:** all story, image, Flow, voice, and public-facing tasks.

**Immutable instructions:**

- Early-1990s rural Tamil Nadu; exact year may flex, period cannot.
- Use period-correct materials, work, clothing, architecture, transport,
  infrastructure, packaging, and problem-solving.
- Keep rural life specific, lived-in, practical, and dignified.
- Do not depict generic exotic village imagery or decorative poverty.
- Do not introduce phones, internet, digital payment, screens, modern
  appliances, LED fixtures, current vehicles, contemporary fashion, branding,
  or unsupported infrastructure.
- Do not manufacture danger, humiliation, severe distress, violence, panic,
  child endangerment, animal threat, or false urgency.

**Approved variables:**

- documented local task;
- approved period object;
- season-linked material condition;
- contextually necessary cultural detail.

**Template:**

```text
Set in early-1990s rural Tamil Nadu. Preserve practical, dignified, culturally
specific village life and period-correct material reality. Do not introduce
modern technology, contemporary branding, generic spectacle, or invented stakes.
```

**Validation:** scan the prompt and candidate for modern leakage and dignity
violations.

## M-03 Original Premium Animated Style Lock

**Purpose:** preserve the series’ visual identity without external imitation.

**Applies to:** visual tasks and related visual review.

**Immutable instructions:**

- Original premium cinematic anime identity.
- Semi-realistic South Indian people with believable anatomy.
- Soft painterly hand-painted digital rendering.
- Restrained organic linework where useful.
- Natural material texture and layered environmental detail.
- Soft global illumination and weather-grounded atmospheric depth.
- Story-serving composition and a warm restrained slice-of-life feeling.
- No named studio, artist, film, franchise, or external-property imitation.
- No plastic CGI, photorealism, chibi comedy, glossy fashion editorial, or
  synthetic “AI art” ornamentation.

**Approved variables:**

- palette emphasis consistent with time and weather;
- texture emphasis relevant to the material;
- depth treatment appropriate to the shot;
- scene-specific visual restraint.

**Template:**

```text
Use the original Village Stories premium cinematic animated identity:
semi-realistic South Indian people, believable anatomy, soft painterly
hand-painted digital rendering, restrained organic linework, natural material
texture, soft global illumination, and warm restrained slice-of-life atmosphere.
Do not imitate named external creators or properties.
```

**Validation:** candidate reads as original series work, not a tool default or
an external style imitation.

## M-04 Targeted Negative Constraints

**Purpose:** exclude known risks without drowning the primary request in negation.

**Applies to:** visual and motion tasks; voice tasks use their own exclusions.

**Immutable instructions:**

- Negatives protect a named risk.
- A negative cannot substitute for a positive factual instruction.
- Do not add broad stylistic exclusions with no task relevance.

**Approved variables:**

- documented scene-specific drift risks;
- prohibited modern item;
- prohibited incorrect character feature;
- prohibited unsafe motion;
- prohibited camera treatment.

**Template:**

```text
Avoid only these task-specific failures: [VARIABLE].
Do not add modern objects, redesign recurring identities, alter documented
geography, introduce unapproved people, or create drama absent from the scene.
```

**Validation:** every negative corresponds to a known risk, source lock, or
prior candidate failure.

## M-10 Character Presence And Identity

**Purpose:** select and preserve recurring people without overloading the prompt.

**Applies to:** whenever a visible person is present or a script/voice line names
one.

**Immutable instructions:**

- Include a character only with a source-backed reason to be present.
- Preserve the character packet’s identity, scale, age, anatomy, relationship,
  and behaviour.
- Attach approved identity references only in the declared role.
- Do not redesign a person for a more “cinematic” result.

**Father lock when applicable:**

- Same recurring man established by
  `11_Assets/Character_References/Father_Canon_Design_Reference.png`.
- Thick naturally tousled black hair.
- Light natural stubble.
- Warm medium-brown South Indian complexion.
- Lean farmer build with broad shoulders and strong forearms.
- Calm, grounded, observant manner.
- Approved practical clothing only.

**Mother lock when applicable:**

- Preserve approved face, warm medium-brown complexion, and practical cotton
  saree and blouse logic.
- Traditional half-up black hairstyle unless an approved work-safe arrangement
  applies.
- Small red bindi, left-nostril gold nose pin, thin glass bangles, small
  traditional gold jhumkas, and exactly one simple gold chain with traditional
  thali pendant.
- Never glamorize, bridal-style, multiply, remove, or replace these details.

**Approved variables:**

- present character;
- body orientation and screen position;
- current expression;
- task-appropriate clothing state;
- current hand action;
- attachment filename and declared role.

**Template:**

```text
[Approved character] as the established recurring person from [source / approved
reference role], preserving [immutable identity details]. Current scene state:
[VARIABLE: position, posture, expression, clothing condition, one action].
```

**Validation:** identity, age, clothing, accessory count, and presence match the
scene packet and source references.

## M-11 Character State, Wardrobe, And Behaviour

**Purpose:** specify temporary action without modifying identity.

**Applies to:** every visible principal character.

**Immutable instructions:**

- One principal visible action per shot or Flow motion contract.
- Behaviour follows the character’s established temperament.
- Wardrobe follows documented practical, period, weather, and task logic.
- Emotion is shown through observable behaviour, not a generic label.

**Approved variables:**

- seated, standing, walking, waiting, carrying, preparing, looking, or resting;
- current garment condition;
- task-safe hair adjustment;
- one subtle expression;
- left/right hand use when continuity requires it;
- permitted secondary reaction.

**Template:**

```text
Current state: [VARIABLE]. Show [one observable action]. Expression and posture
suggest [approved scene state] without exaggerated performance. Preserve approved
wardrobe, practical condition, and continuity from the incoming shot.
```

**Validation:** state is consistent with the prior shot and does not invent a new
emotion, action, or costume.

## M-12 Family Dog Presence And Behaviour

**Purpose:** preserve the dog as a gentle household companion.

**Applies to:** only when the Family Dog is approved for the scene.

**Immutable instructions:**

- The dog is a gentle German Shepherd household companion.
- It may wait, follow, observe, rest, respond softly, play naturally, or receive
  ordinary care.
- It is never attack, police, military, chase, rescue, missing-pet, injury,
  threat, or stakes device.
- Do not exaggerate wolf features or assign human strategic intent.

**Approved variables:**

- location relative to family;
- simple approved activity;
- gaze direction;
- leash, bowl, bedding, or object relation when sourced;
- distance in frame.

**Template:**

```text
The Family Dog is present only as a gentle household companion, [VARIABLE:
approved simple behaviour]. Keep the dog calm, naturally proportioned, and
non-threatening; do not add a chase, rescue, injury, or dramatic reaction.
```

**Validation:** dog action is ordinary, safe, and not used to fabricate stakes.

## M-20 Location Identity And Geography

**Purpose:** preserve recurring location layout and usable spatial truth.

**Applies to:** all visual, Flow, script, and voice tasks that identify place.

**Immutable instructions:**

- Use the documented location and sub-area.
- Preserve fixed geography, architecture, materials, orientation, and paths.
- Do not replace a known location with a generic village background.
- The family house, rear yard, and kitchen are west.
- Paddy fields and pond are east.
- Village entrance, banyan tree, and river ghat are north.
- Fields, pond, and irrigation canal are south.

**Approved variables:**

- location name and sub-area;
- current working surface;
- distance to fixed landmark;
- occupied zone;
- visible route or boundary;
- weather consequence at the location.

**Template:**

```text
At [approved location and sub-area], preserve [fixed geography / material /
orientation]. Subject is [VARIABLE: relation to fixed feature]. Do not alter
layout, add unapproved structures, or reverse the established world map.
```

**Validation:** location, landmarks, and screen geography connect to adjacent
shots.

## M-21 Time, Season, Weather, And Light

**Purpose:** make environment and light physically consistent.

**Applies to:** all visual and motion tasks, plus voice when the line names it.

**Immutable instructions:**

- Time, season, weather, and light follow the approved scene ledger.
- Morning arrives from the east; evening from the west.
- Light follows architecture, orientation, weather, and material response.
- Monsoon is inviting with cool diffused daylight, not a blue-black disaster
  treatment.

**Approved variables:**

- season;
- time of day;
- weather condition;
- visible wetness, dust, shade, steam, wind, or shadow consequence;
- light source, direction, quality, and intensity;
- continuity from previous and next shot.

**Template:**

```text
[Season / time / weather]. [Documented light] comes from [direction] and creates
[visible physical consequence]. Preserve continuity with [incoming / outgoing
scene state]; do not reverse sun direction or alter weather for spectacle.
```

**Validation:** candidate light, shadows, wetness, and atmosphere match the
source state and world orientation.

## M-22 Background Life And Environmental Restraint

**Purpose:** make a location alive without uncontrolled activity.

**Applies to:** visual and Flow tasks where background detail is visible.

**Immutable instructions:**

- Background life must be source-backed or neutral and non-story-changing.
- Do not introduce crowds, festivals, markets, animals, vehicles, or people to
  make a frame more lively.
- Background motion is subordinate to the principal action.
- Absence is a valid instruction.

**Approved variables:**

- distant leaves moving;
- rain beyond a doorway;
- smoke, steam, cloth, or water responding naturally;
- approved far-background person;
- stillness requirement.

**Template:**

```text
Background: [VARIABLE]. Keep it sparse, natural, and subordinate to the main
action. No unapproved crowd, spectacle, vehicle, animal, celebration, or new
story event.
```

**Validation:** no new narrative burden is created by background detail.

## M-30 Object Identity And Material

**Purpose:** protect recurring and period-critical object truth.

**Applies to:** whenever an object is prominent, handled, named, or continuity
critical.

**Immutable instructions:**

- Use only documented, period-correct objects.
- Preserve object type, material, scale, count, and practical purpose.
- Do not replace a specific object with a modern or generic equivalent.
- Do not add branding or decorative luxury unless source-backed.

**Approved variables:**

- object identifier;
- material condition;
- location;
- visible count;
- task-relevant detail;
- interaction point.

**Template:**

```text
Include [approved object] as [documented material / form / count], used for its
approved practical purpose. Current visible state: [VARIABLE]. Do not substitute
a modern, branded, ornate, or different object.
```

**Validation:** object identity remains intact even if its state changes.

## M-31 Object State, Ownership, And Continuity

**Purpose:** describe changing object state without losing ownership or history.

**Applies to:** handling, inserts, Flow clips, and adjacent shots.

**Immutable instructions:**

- Object state follows the scene-state ledger.
- Handler, placement, count, and condition must connect to adjacent shots.
- A change requires a visible or documented cause.
- Do not create a completed result before the approved action completes.

**Approved variables:**

- start state;
- permitted transformation;
- end state;
- handler;
- position;
- whether the object exits frame;
- incoming / outgoing continuity note.

**Template:**

```text
Object continuity: starts [VARIABLE], may change only by [VARIABLE], ends
[VARIABLE]. Handler and placement: [VARIABLE]. Preserve count, material, and
ownership; do not skip the causal action.
```

**Validation:** object ledger can be read across the cut without a missing state
change.

## M-40 Camera Direction And Composition

**Purpose:** select a calm, readable view from approved camera language.

**Applies to:** stills, Flow source images, Flow clips, and boards.

**Immutable instructions:**

- Camera is a calm human observer.
- Keep camera natural, stable, non-distorting, and aware of screen geography.
- No fisheye, action-camera look, impossible drone view, Dutch angle,
  surveillance view, arbitrary hero angle, or spectacle lens drama.
- Use `19_Camera_Direction_Bible.md` as the operational authority for shot type,
  framing, angle, position, and screen direction.
- Do not place movement verbs in this direction module.

**Approved variables:**

- shot size;
- camera side, height, and angle;
- focal hierarchy;
- framing and headroom;
- subject screen position;
- foreground / middle / background relationship;
- caption-safe or crop-safe area.

**Template:**

```text
Camera direction: [VARIABLE from approved camera bible]. Frame [principal
subject / action] as focal, with [documented spatial relation]. Preserve natural
observer perspective, screen geography, and [crop / caption-safe] area. No camera
movement instruction in this module.
```

**Validation:** direction supports the story purpose and remains compatible with
adjacent shots.

## M-41 Camera Movement And Motion Boundary

**Purpose:** define only permitted camera motion and action scale.

**Applies to:** Google Flow motion tasks.

**Immutable instructions:**

- Use `20_Camera_Movement_Bible.md` as operational authority.
- Flow receives one bounded motion contract, not an entire scene.
- Preserve identity, place, object state, light, and screen direction during
  motion.
- The smallest truthful change is preferred.
- Do not use camera movement to conceal an unclear action or generate spectacle.

**Approved variables:**

- approved movement type;
- start framing;
- end framing;
- speed;
- duration;
- subject movement;
- permitted secondary motion;
- locked elements.

**Template:**

```text
Camera movement: [VARIABLE from approved movement bible], from [start framing]
to [end framing], at [speed] for [duration]. Principal action: [VARIABLE].
Permit only [secondary motion]. Keep identity, object state, environment,
lighting, and screen direction stable. No extra action or camera flourish.
```

**Validation:** start and end can be cut safely and the movement remains within
the approved visual contract.

## M-42 Screen Direction, Edit, And Crop Safety

**Purpose:** protect continuity beyond one attractive frame.

**Applies to:** sequential shots, Shorts, long form, and repair tasks.

**Immutable instructions:**

- Preserve established left/right travel and eyeline where recorded.
- Preserve incoming object and character positions unless an action changes them.
- Leave required caption-safe, interface-safe, or crop-safe space.
- Do not frame a principal fact where the delivery crop will hide it.

**Approved variables:**

- incoming and outgoing shot IDs;
- subject travel direction;
- eyeline;
- safe-space side;
- match-cut element;
- edit transition;
- crop priority.

**Template:**

```text
Continuity bridge: from [incoming] to [outgoing]. Preserve [screen direction /
eyeline / object position]. Keep [safe area] clear for [captions / crop / edit].
Match [VARIABLE] across the cut.
```

**Validation:** the selected output can enter and leave the edit without a
reversal or hidden essential information.

## M-50 Still Image Task

**Purpose:** assemble a bounded prompt for one truthful image.

**Applies to:** stills, keyframes, inserts, cutaways, thumbnails, and repairs.

**Immutable instructions:**

- One approved visual moment per task.
- The still image establishes a frame; it does not summarize an episode.
- Use `04_Master_Image_Prompt.md` for master structure.
- Include only modules relevant to the frame.

**Approved variables:**

- output use;
- approved held moment;
- selected subject;
- location;
- environmental state;
- camera direction;
- reference roles;
- targeted negatives.

**Assembly order:**

```text
M-00 output intent
M-10 / M-11 subject identity and state
M-20 location
M-30 / M-31 object
M-21 environment and light
M-40 camera direction
M-03 style
M-42 continuity / crop safety
M-04 targeted negatives
M-61 references
```

**Validation:** one frame can communicate the requested approved moment.

## M-51 Google Flow Input And Preservation

**Purpose:** choose safe image inputs and declare what Flow must preserve.

**Applies to:** every Google Flow task.

**Immutable instructions:**

- Flow is a bounded motion tool, not a writer or canon authority.
- Use only approved source stills and references.
- One-image or two-image choice follows continuity need, not convenience.
- Source references control identity or start/end state only as declared.
- Flow must not redesign people, location, objects, period, style, or light.

**Approved variables:**

- source image A;
- source image B when approved;
- input mode;
- identity reference attachment;
- start state;
- end state;
- preservation list;
- reason for two-image use.

**Template:**

```text
Flow input mode: [one image / two images].
Source A: [VARIABLE]. Source B: [VARIABLE or NONE].
Reference roles: [VARIABLE].
Preserve throughout: [identity, clothing, location layout, object state, light,
weather, style, screen direction].
Use the second image only to control the approved end state: [VARIABLE].
```

**Validation:** selected inputs are approved, compatible, and sufficient for the
intended edit boundary.

## M-52 Google Flow Motion Contract

**Purpose:** tell Flow what changes, and equally what does not.

**Applies to:** every animation request.

**Immutable instructions:**

- One principal action with a visible start and end state.
- Motion must be physically plausible and culturally / character appropriate.
- Camera direction and movement remain separately stated.
- Do not ask Flow to invent dialogue, story turns, facial emotion, or object
  changes not supplied by the scene.

**Approved variables:**

- start state;
- principal action;
- end state;
- permitted secondary response;
- environment motion;
- camera movement;
- duration;
- locked elements;
- exit condition.

**Template:**

```text
Start: [VARIABLE].
Principal action: [VARIABLE].
End: [VARIABLE].
Permit only [VARIABLE] as secondary motion.
Environment may [VARIABLE].
Camera: [M-40 direction] plus [M-41 movement].
Keep [VARIABLE] unchanged. No extra gestures, people, objects, weather shifts,
camera drama, or story events.
```

**Validation:** the contract has one readable movement and an edit-safe endpoint.

## M-53 Voice And Pronunciation

**Purpose:** prepare canon-safe spoken performance.

**Applies to:** narration, dialogue, synthetic voice, recording direction, and
caption handoff.

**Immutable instructions:**

- Exact approved script wording controls.
- Voice is warm, clear, calm, observant, and restrained.
- Do not invent language, transliteration, dialect, honorifics, or pronunciation.
- Do not imitate a real or named voice without explicit lawful authorization.
- Protect approved ASMR, music, and silence.
- Use `06_Master_Voice_Prompt.md` for the operational voice system.

**Approved variables:**

- unit ID;
- language;
- delivery temperature;
- pace;
- pause;
- emphasis;
- pronunciation ledger entry;
- timing;
- voice source;
- clean-stem specification.

**Template:**

```text
Read only the locked approved text: "[VARIABLE]".
Delivery: [temperature], [pace], [approved pause / emphasis].
Use only approved pronunciation ledger entries: [VARIABLE].
Protect [ASMR / silence]. Do not paraphrase, add words, perform an unverified
accent, or compete with the image.
```

**Validation:** final speech, captions, picture, and approved language evidence
agree.

## M-54 Audio, ASMR, And Silence Handoff

**Purpose:** keep prompt outputs compatible with the sound design plan.

**Applies to:** scripts, Flow, voice, edit, and final review.

**Immutable instructions:**

- Sound is not filler.
- Featured natural sound and silence receive protected space.
- Narration and music cannot explain away an unclear picture or noisy mix.
- Do not create sound effects in a voice-generation request unless the task
  explicitly owns them.

**Approved variables:**

- featured sound;
- sound entry and exit;
- protected silence;
- voice ducking note;
- music-entry note;
- source sound owner.

**Template:**

```text
Audio handoff: protect [VARIABLE] from [time / action] to [time / action].
Narration may enter [VARIABLE]. Music may [VARIABLE]. Do not cover the featured
natural sound or replace it with generic effects.
```

**Validation:** the prompt and selected output leave the planned sound event
audible.

## M-55 YouTube And Accessibility Handoff

**Purpose:** protect the final viewer experience without forcing platform
language into the story.

**Applies to:** voice, edit, captions, packaging, and release handoff.

**Immutable instructions:**

- Public-facing claims must be traceable to the episode.
- Captions reflect approved final words and verified local terms.
- A call to action cannot damage story integrity or the resting ending.
- Shorts and long-form delivery requirements do not alter canon.

**Approved variables:**

- caption language;
- subtitle requirement;
- caption-safe composition;
- title / description handoff status;
- end-screen and card timing;
- format-specific crop.

**Template:**

```text
Accessibility and YouTube handoff: [VARIABLE]. Preserve [caption-safe / crop-safe]
space. Captions must match the locked spoken track. Do not add promotional copy
inside the story moment or make claims unsupported by the finished episode.
```

**Validation:** master, captions, thumbnails, and public metadata tell the same
truth.

## M-60 Continuity Bridge

**Purpose:** carry state across source, image, Flow, voice, sound, and edit.

**Applies to:** every shot that has a neighbour or a recurring state.

**Immutable instructions:**

- Describe only continuity facts material to the connection.
- Incoming and outgoing state must be explicit.
- Do not use a prompt to conceal a missing causal step.

**Approved variables:**

- prior shot;
- next shot;
- character position;
- hand / prop state;
- clothing condition;
- light and weather;
- screen direction;
- sound bridge;
- narration entry / exit.

**Template:**

```text
Incoming state from [ID]: [VARIABLE].
Required state in this task: [VARIABLE].
Outgoing state to [ID]: [VARIABLE].
Preserve [specific bridge facts]. If the change needs an unseen action, return to
the board or add an approved connecting shot.
```

**Validation:** a reviewer can state how each continuity-critical fact travels
through the task.

## M-61 Reference Attachment Roles

**Purpose:** prevent a reference from accidentally controlling the wrong thing.

**Applies to:** any task with images, audio, or document attachments.

**Approved reference roles:**

`CHARACTER_IDENTITY` controls the recurring person’s identity only.

`LOCATION_LAYOUT` controls fixed spatial and architectural truth only.

`OBJECT_IDENTITY` controls the named recurring object only.

`STYLE_LOCK` controls approved original series visual language only.

`START_STATE` controls the approved beginning of a motion task.

`END_STATE` controls the approved ending of a two-image Flow task.

`PRONUNCIATION_REFERENCE` controls an approved spoken term only.

`TIMING_REFERENCE` controls edit timing only.

**Immutable instructions:**

- State the role for every attachment.
- A reference does not transfer unrelated pose, lighting, mood, outfit, or
  background facts unless that role is explicitly approved.
- Do not use unapproved external images, voices, franchises, or style examples.

**Template:**

```text
Attachment: [filename / path].
Role: [approved role].
Controls: [specific facts].
Does not control: [specific non-facts].
Source approval: [VARIABLE].
```

**Validation:** attachment role is narrow, traceable, and compatible with the
scene.

## M-62 Validation Gate

**Purpose:** stop an incomplete assembly before tool use.

**Applies to:** every final task prompt.

**Pre-assembly checks:**

```text
[ ] Task type and primary use are named.
[ ] Required source packet is present and revisioned.
[ ] No essential fact remains OPEN without an owner.
[ ] Applicable immutable modules are selected.
[ ] Variables are scene-approved and source-backed.
[ ] Character / location / object presence is justified.
[ ] Time, weather, light, and geography agree.
[ ] Camera direction and movement are separate.
[ ] Reference attachment roles are declared.
[ ] Targeted negatives correspond to actual risks.
[ ] Flow has one action and defined endpoints, if used.
[ ] Voice has exact text and approved pronunciation treatment, if used.
[ ] Sound, crop, caption, and edit needs are represented where relevant.
```

**Prompt read-through test:**

```text
Can every sentence be assigned to a module or source?
  No  → remove it or identify its owner.

Does one instruction contradict another?
  Yes → apply hierarchy and revise.

Does the assembly ask the tool to decide story, canon, or cultural facts?
  Yes → return the decision upstream.

Could an operator tell what may change and what must not?
  No  → separate locks from variables.
```

**Output:** `READY`, `REVISE`, or `HOLD`.

## M-63 Repair And Revision

**Purpose:** correct the smallest responsible prompt component while preserving
usable work.

**Applies to:** rejected or imperfect candidates.

**Immutable instructions:**

- Preserve the previous approved assembly and candidate record.
- Diagnose before rewriting.
- Change one responsible variable or module at a time where feasible.
- Do not repair an upstream factual defect with a lower-level artistic change.
- Do not use a candidate as new canon.

**Defect classes:**

`SOURCE_DEFECT` — source packet is missing, contradictory, or incorrect.

`ASSEMBLY_DEFECT` — a required module is absent, duplicated, or conflicting.

`VARIABLE_DEFECT` — a scene value is wrong or underspecified.

`REFERENCE_DEFECT` — attachment role, quality, or selection is wrong.

`TOOL_INTERPRETATION_DEFECT` — valid task prompt was interpreted poorly.

`OUTPUT_DEFECT` — generated asset fails identity, continuity, composition,
motion, voice, or technical review.

**Revision template:**

```text
Task / revision:
Candidate ID:
Defect class:
Observed evidence:
Responsible module / variable:
Upstream source check:
Smallest correction:
Immutable modules preserved:
New candidate ID:
Review result:
```

**Validation:** the revision fixes the named defect without introducing a new
unreviewed change.

## M-64 Archive And Provenance

**Purpose:** make a selected output reproducible after the tool session ends.

**Applies to:** every approved asset and useful repair path.

**Immutable instructions:**

- Archive selected assets outside transient tool interfaces.
- Keep source, prompt, settings, references, output, and approval linked.
- Do not overwrite a selected asset with a repair candidate.
- Keep current status clear.

**Required archive fields:**

```text
Task ID and revision:
Asset filename and revision:
Prompt assembly text:
Selected module IDs and versions:
Completed variables:
Source paths and revisions:
Reference attachments and roles:
Tool and relevant settings:
Candidate IDs:
Selected output:
Review checklist and approvals:
Known limitation or waiver:
Incoming / outgoing continuity links:
Revision history:
```

**Validation:** a different approved operator can identify why the selected
asset was allowed and reproduce or safely revise it.

## Assembly Procedure

### Step 1 — Begin With The Approved Task

State the requested output in one sentence.

If the task sentence contains multiple actions, multiple locations, multiple
time changes, or multiple emotional turns, split it before module selection.

### Step 2 — Load Sources, Not Memories

Collect the approved episode, script, scene-state, character, location, object,
style, camera, and production sources that apply.

Record revisions.

Do not silently use a familiar older version.

### Step 3 — Select The Immutable Envelope

Select only applicable permanent modules:

```text
M-00, M-01, M-02, M-03, M-04 as relevant,
plus subject, location, object, camera, tool, and control modules required by
the task.
```

### Step 4 — Fill Scene Variables

Use the approved board and ledger to enter current action, state, environment,
camera, continuity, and delivery values.

Use `NONE` for genuinely irrelevant fields.

Use `OPEN / owner / resolution path` for unresolved ones.

### Step 5 — Declare Attachments

Attach only necessary approved references.

Give each one a role through M-61.

Remove attachments that invite uncontrolled copying.

### Step 6 — Assemble In Task Order

For visual tasks, use:

```text
intent → subject → action → location → object → environment → camera → style
→ continuity → targeted negatives → references → output constraint
```

For Flow tasks, use:

```text
intent → input images → preservation → start → one action → end → camera
direction → camera movement → limited secondary motion → exclusions → output
```

For voice tasks, use:

```text
intent → locked text → narration purpose → scene truth → delivery → approved
pronunciation → sound window → technical stem output
```

### Step 7 — Validate Before Generation

Run M-62.

Read the prompt aloud for contradiction, accidental invention, and excessive
instruction density.

### Step 8 — Generate Or Record

Use the approved task prompt without improvised additions in the tool interface.

If an interface requires a field not covered by the assembly, document it and
confirm it does not alter a lock.

### Step 9 — Review The Output In Context

Review identity, world, action, object state, camera, sound opportunity,
technical quality, and edit connection.

Do not approve based on a small preview alone.

### Step 10 — Archive Or Revise

Archive selected assets through M-64.

Use M-63 for any defect.

## Prompt Safety Rules

Prompt safety means protecting canon, people, cultural specificity, rights,
continuity, and production traceability.

Never:

- invent a name, relationship, belief, ritual, language phrase, dialect, or
  pronunciation to make an output feel local;
- imitate named artists, studios, actors, narrators, creators, or living people;
- clone or simulate a recognisable voice without explicit authorization;
- use an external reference with unclear rights or ownership;
- use a generated candidate as proof of a cultural or historical fact;
- add violence, danger, panic, humiliation, injury, threat, or distress to make
  a gentle scene engaging;
- represent children or animals as stakes devices;
- turn poverty, labor, faith, or domestic life into aesthetic spectacle;
- introduce current technology or branding into the early-1990s world;
- ask a tool to solve unresolved story or cultural questions;
- ask Flow to create a full dramatic scene from one vague instruction;
- ask voice tools to perform an unverified accent;
- hide an unresolved source conflict inside broad “cinematic” direction.

When safety and story requirements appear to conflict, stop and return the
decision to the relevant canon, story, or production owner.

## Source Ownership Matrix

```text
Fact or decision                         Primary owner
--------------------------------------   -----------------------------------
Series continuity / timeline             01_Canon/
Character identity / wardrobe             03_Characters/
Location layout / environment             02_World/
Object identity / material                04_Objects/
Historical or cultural evidence           05_Research/
Story meaning / emotional boundary        06_Story_Engine/
Format / hook / pacing / ending           07_Episode_System/
Operational capture / edit / release      08_Production/
Prompt architecture / assembly            09_AI_Production_System/
Scene state and current action            Approved board / scene ledger
Prompt revision record                    Task owner plus relevant module owner
```

If ownership is unclear, the task is not ready for generation.

## Integration Rules

### Character Integration

Use M-10 and M-11 only when a character has a justified on-screen or spoken
role.

Identity modules do not establish a new costume, relationship, or emotional
fact.

State modules do not authorize identity drift.

### Location Integration

Use M-20 before aesthetic environmental description.

Location layouts determine where a subject can plausibly stand, walk, look, and
receive light.

Do not use a decorative background module instead of a known location.

### Object Integration

Use M-30 for object identity and M-31 for state.

If the object becomes narratively important, confirm its ownership and causal
change in the scene ledger.

### Style Integration

M-03 establishes original visual language.

Scene weather, palette, and camera modules may adapt appearance only inside that
language.

They may not invoke external imitation or a conflicting genre treatment.

### Camera Integration

M-40 controls where the viewer is.

M-41 controls whether and how that viewpoint moves.

M-42 protects what carries across the edit.

Never merge all three into vague “cinematic camera movement” wording.

### Google Flow Integration

M-51 controls approved inputs and what must persist.

M-52 controls the small permitted change.

Use M-60 to confirm that the output joins surrounding shots.

### Voice Integration

M-53 protects wording and performance.

M-54 protects the sound plan.

M-55 protects captions and final delivery.

The voice must never be used to make a faulty visual appear intentional.

## Compact Assembly Templates

### Still Image Assembly

```text
[M-00 task and output]
[M-10 / M-11 approved subject identity and current state]
[M-20 documented location and relation to fixed features]
[M-30 / M-31 relevant object identity and current state]
[M-21 time, weather, light, and visible consequence]
[M-40 camera direction and composition]
[M-03 original Village Stories visual style]
[M-42 continuity and crop safety]
[M-04 targeted exclusions]
[M-61 approved references and roles]
```

### Google Flow Assembly

```text
[M-00 task and duration]
[M-51 approved source image(s), roles, preservation list]
[M-60 incoming start state]
[M-52 one principal action and end state]
[M-40 camera direction]
[M-41 approved camera movement]
[M-22 permitted environmental motion]
[M-42 screen direction and edit exit]
[M-04 targeted motion exclusions]
```

### Voice Assembly

```text
[M-00 unit identity and output]
[M-53 exact locked text, purpose, delivery, pronunciation]
[M-60 picture and edit connection]
[M-54 protected sound and silence]
[M-55 captions and accessibility handoff]
[M-64 stem and approval archive fields]
```

## Final Assembly Gate

Approve a task prompt only when all statements are true.

```text
[ ] The task is singular, bounded, and correctly identified.
[ ] Every selected module is applicable.
[ ] The immutable layer comes from approved authority.
[ ] Every variable is source-backed and scene-specific.
[ ] Characters, locations, objects, and style are integrated without drift.
[ ] Camera direction, movement, and screen continuity are distinct and correct.
[ ] Google Flow receives approved inputs and one bounded motion contract.
[ ] Voice uses locked text and approved language / pronunciation evidence.
[ ] Targeted negatives address real risks without replacing positive facts.
[ ] Reference attachments have narrow declared roles.
[ ] Sound, edit, crop, captions, and YouTube needs are represented where needed.
[ ] No instruction asks AI to invent canon, culture, language, or story.
[ ] Validation result is READY and the assembly is archived.
```

If any box is false, do not generate or record.

Resolve the relevant source, module, variable, or ownership problem first.

## Guiding Reminder

Modules do not make Village Stories generic.

They preserve the known world so each new shot, movement, voice line, and edit
can feel specific, original, premium, and true to the people who inhabit it.
