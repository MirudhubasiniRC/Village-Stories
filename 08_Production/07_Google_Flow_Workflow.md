# Google Flow Workflow

## Purpose

This is the permanent production manual for turning approved Village Stories image assets and storyboards into controlled animation clips in Google Flow.

It defines how to use Google Flow as an animation-production environment without allowing generation convenience to break early-1990s rural Tamil Nadu canon, recurring character identity, location geography, prop state, camera continuity, or YouTube framing.

Use it for every Flow-generated shot, extension, variation, repair, and final clip selection.

---

# Philosophy

Google Flow is a collaborator for bounded motion, not the author of the episode.

The storyboard decides what the shot means.

The image-prompt workflow decides what it looks like at the start.

Google Flow is asked to animate one clearly defined change while protecting the approved world around it.

The most reliable AI animation is modest in scope:

* one person,
* one meaningful action,
* one camera intention,
* one stable place,
* one beginning,
* one ending.

Quiet motion is a feature of Village Stories, not a limitation.

---

# Google Flow-Specific Operating Principle

Use the currently available Google Flow controls, modes, reference-image features, clip-extension tools, and model options as shown in the product interface.

Google Flow changes over time. This document defines the production discipline that remains valid even if a control is renamed, moved, added, or removed.

Before a new production cycle, the Flow Operator should confirm:

* available generation modes;
* current clip-duration choices;
* supported aspect ratios and output resolution;
* reference-image or ingredient behavior;
* first-frame and last-frame controls, if available;
* extension and edit capabilities;
* audio-generation behavior, if available;
* download and project-history limitations.

Do not assume an older interface tutorial remains correct.

---

# Canon Authority

Google Flow output is lower authority than every approved production input.

Use this precedence:

```text
01_Canon/ Series Style Lock and timeline
↓
02_World/ geography, locations, culture, nature, and time
↓
03_Characters/ Character_Rules and individual character packets
↓
04_Objects/ recurring prop definitions
↓
Approved episode brief and locked storyboard
↓
Approved image prompt and selected keyframe
↓
Shot continuity record
↓
Google Flow generation prompt and settings
↓
Generated clip and editorial selection
```

An output never becomes canon because it was expensive, difficult to reproduce, or visually impressive.

---

# Guiding Principle

Animate the smallest truthful change that advances the story, and preserve everything else.

---

# Roles

## Director

Approves performance, shot feeling, camera restraint, and final creative selection.

## Canon And Continuity Lead

Approves input references, verifies generated clips against canon, tracks handoffs, and decides whether a discrepancy requires regeneration or a documented revision.

## Storyboard Artist

Supplies the shot purpose, visual plan, action boundary, framing, start state, end state, and cut logic.

## Image Prompt Lead

Supplies approved start frames, end frames where required, reference sets, and the visual prompt record.

## Google Flow Operator

Creates Flow projects, uploads or assigns approved ingredients/references, writes motion prompts, runs controlled variants, records configuration, and exports candidate clips.

## Editor

Tests clip duration, cut points, aspect ratio, crop safety, rhythm, and compatibility with adjacent footage.

## Sound Lead

Approves whether any generated audio is usable, determines ambience and ASMR needs, and ensures final sound remains intentional and period-appropriate.

---

# Required Inputs

Do not open a Flow generation task without:

* approved shot ID and revision;
* locked storyboard panel;
* shot fact sheet;
* approved start keyframe;
* approved end keyframe when matching an endpoint is required;
* character, location, and prop references;
* current scene continuity ledger;
* intended aspect ratio and target clip duration;
* stated dominant action;
* camera behavior;
* sound decision;
* preceding and following edit notes.

If a character, prop, or location is recurring but no approved reference exists, create and approve it through the image workflow first.

---

# Flow Project Organization

Use a production project for one episode or a clearly bounded sequence.

Name it:

```text
EP###_ShortTitle_Flow
```

Name each generation task:

```text
EP###_S##_SH###_Action_Revision
```

Example:

```text
EP014_S02_SH006_DaughterPicksLeaf_R01
```

In the shot record, link:

* Flow project or generation identifier;
* exact prompt version;
* reference set version;
* model or mode selected;
* duration and aspect ratio;
* selected candidate;
* export filename;
* review result;
* reason for any regeneration.

Do not rely on a Flow workspace name alone to reconstruct editorial intent later.

---

# What Google Flow Should And Should Not Do

## Good Uses

Use Flow for:

* gentle head turns;
* a hand setting down one object;
* one or two natural steps;
* steam, smoke, leaves, rain, water, or cloth moving subtly;
* a controlled look, notice, smile, or reaction;
* a small camera pan, track, or push when story justified;
* an action continuation from an approved keyframe;
* a short location atmosphere shot with restrained environmental motion.

## Poor Uses

Do not ask Flow to solve:

* a long conversation with exact dialogue performance;
* many character interactions and handoffs in one take;
* rapid action, fighting, stunts, or danger spectacle;
* a complicated craft process with many sequential tool uses;
* a precise map transition across distant locations;
* major character redesign;
* a full scene that needs multiple camera angles;
* a canon decision missing from the storyboard.

Break these into simpler shots, use approved stills, or plan an editorial bridge.

---

# Preflight Workflow

## Step 1: Read The Shot Contract

Before generation, restate the shot in one sentence:

`From this approved start state, [subject] performs [one action] while the camera [behavior], ending when [observable end state].`

Example:

`From the approved garden keyframe, Younger Daughter gently picks up the fallen mango leaf while the camera remains at her eye level, ending with the leaf in her right hand and the basket still in her left.`

If the sentence has more than one `while`, divide the shot.

## Step 2: Confirm Inputs

Compare the selected keyframe with the storyboard:

* Is the correct character present?
* Is current clothing correct?
* Is the prop in the correct hand and state?
* Does the location match its documented sub-area?
* Does light match the scene?
* Does the format protect YouTube framing?
* Is the keyframe stable enough for the requested movement?

Do not animate a compromised keyframe.

## Step 3: Choose The Generation Strategy

Choose one:

### Start-Frame-Led Animation

Use an approved first frame and ask for one small movement.

Use this for most Village Stories shots.

### Start-And-End-Framed Animation

Use approved beginning and ending frames when an exact handoff is important and the available Flow mode supports it.

Use for a precise object placement, a reaction that must lead into another shot, or a matched transition.

### Reference-Ingredient-Led Animation

Use approved character, location, and prop ingredients when Flow’s current interface supports and reliably respects them.

Use references to preserve identity, not to overload the prompt with every historical detail.

### Text-Led Atmosphere Generation

Use only for non-recurring environmental shots where no existing visual asset must match.

The result still requires canon review before use.

## Step 4: Decide Motion Scope

Classify intended complexity:

* `M1` — environmental motion only.
* `M2` — one body or hand action.
* `M3` — one person plus one simple environmental response.
* `M4` — multi-subject or multi-stage action; redesign into smaller shots.

Village Stories normally uses M1 through M3.

If a shot is M4, storyboard a cut before prompting.

## Step 5: Set Duration For The Edit

Choose the shortest duration that contains:

* a readable beginning;
* the intended action;
* a usable ending or cut point.

Generate extra time only when the editor needs a settle, overlap, or ambience hold.

Never extend a clip simply to make a calm sequence longer.

The final edit can hold a strong frame more cleanly than a generation can sustain complex motion.

## Step 6: Confirm Output Format

Generate in the delivery ratio whenever possible.

For 9:16 Shorts, keep the action in the central vertical zone and leave room for interface overlays or captions.

For 16:9, verify that wide compositions preserve a distinct subject at mobile scale.

Do not animate a horizontal master and assume a vertical crop will retain hands, faces, props, and motion.

---

# Motion Prompt Architecture

Use a brief, declarative motion prompt.

The still image and references already carry most appearance information.

Write in this order:

```text
1. Preserve instruction
2. Subject and action
3. Camera behavior
4. Environmental motion
5. End state
6. Motion exclusions
```

## 1. Preserve Instruction

Begin by protecting the approved frame:

`Preserve the approved character identity, clothing, location architecture, props, painterly Village Stories style, and early-1990s rural Tamil Nadu details.`

This is not a substitute for appropriate input references.

## 2. Subject And Action

State a single dominant action with pace and physical logic.

Good:

`The Younger Daughter slowly reaches down, lifts the fallen mango leaf with her right hand, and brings it gently toward the small basket in her left hand.`

Weak:

`The child happily explores the garden with magical cinematic movement.`

## 3. Camera Behavior

Use only one restrained instruction:

* `camera remains still`;
* `very slow lateral track following her hand`;
* `subtle push in as she notices the leaf`;
* `gentle pan to keep the action centered`.

If the action is already complex, keep the camera still.

## 4. Environmental Motion

Specify only supporting motion:

`Nearby banana leaves sway slightly after the rain; no strong wind.`

Environmental motion should not compete with hands, face, or story prop.

## 5. End State

State what must be true at the usable endpoint:

`End with the leaf held above the basket, before it is released.`

This gives the editor and next shot a factual handoff.

## 6. Motion Exclusions

Target likely deformation:

`No new characters, no wardrobe change, no added objects, no extra limbs or fingers, no facial redesign, no fast camera movement, no text, no modern objects, no dramatic weather change.`

---

# Motion Prompt Template

```text
Preserve the approved [character / location / prop] identity, current wardrobe, prop state, lighting, composition, painterly Village Stories art style, and early-1990s rural Tamil Nadu setting.

[Subject] [one physically clear action], [pace and emotional quality].

[One camera instruction.]

[Only supporting environmental motion.]

End with [precise visual end state].

No [targeted drift, anatomy errors, unwanted actors, wardrobe or prop changes, text, modern details, or excessive camera motion].
```

---

# Example Google Flow Prompts

## Example: Child And Leaf

```text
Preserve the approved Younger Daughter identity, morning clothing, small woven basket in her left hand, damp Family House front garden, overcast monsoon light, painterly Village Stories art style, and early-1990s rural Tamil Nadu setting.

She slowly reaches down with her right hand, gently lifts the fallen mango leaf, and brings it toward the basket with quiet curiosity.

The camera remains still at her eye level.

Only the nearest banana leaves sway very slightly in the soft post-rain breeze.

End with the mango leaf held just above the basket; do not drop it.

No new people or animals, no change to her face, hair, costume, basket, garden layout, weather, or lighting; no extra fingers, fast motion, camera shake, text, logos, or modern objects.
```

## Example: Stove Atmosphere

```text
Preserve the approved Family House kitchen, Mother’s identity and seated position, clay stove, split firewood, brass vessels, soft window light, and painterly Village Stories style.

Mother places one split firewood piece into the clay stove and withdraws her hand naturally. The flame catches gently after the wood is placed.

Use a very subtle push in toward her hands; no other camera movement.

Thin smoke rises upward and a small curl of steam moves from the pot.

End with Mother’s hand resting beside her knee and the new firewood stable in the stove.

No extra utensils, no changes to Mother’s clothing or face, no modern kitchen fixture, no exaggerated flame, no rapid camera move, no text, logos, or photorealism.
```

## Example: Tea Stall Establishing Motion

```text
Preserve the approved Tea Stall architecture, Tea Stall Owner identity, early-morning light, period-appropriate bicycle placement, and hand-painted Village Stories look.

The Tea Stall Owner slowly pours tea from a small vessel while two background villagers wait naturally without moving toward the camera.

The camera stays fixed at the documented path-side view.

Steam rises gently; a distant tree leaf shifts slightly.

End as the pour finishes with the vessel still above the tumbler.

No added customers, signage, branded packaging, motorcycles, modern café furniture, wardrobe changes, dramatic smoke, fast movement, text, logos, or modern lighting.
```

---

# Generation Workflow

## Step 1: Create The Shot Task

Create or open the episode Flow project.

Name the generation with the required shot identifier.

Attach the storyboard panel and add only approved reference assets supported by the current Flow interface.

Confirm that the displayed aspect ratio and duration are correct before submitting.

## Step 2: Add Approved References

Prioritize:

1. Selected start frame.
2. Character reference for prominent recurring people.
3. Location reference when fixed architecture must match.
4. Prop reference when a story prop must remain exact.
5. End frame only for a supported, necessary matching action.

Do not attach unrelated “pretty” images.

Every reference should have a declared role.

## Step 3: Use The Motion Prompt

Paste the approved prompt version.

Check that it requests:

* one action;
* one camera behavior;
* limited secondary motion;
* a defined endpoint;
* targeted exclusions.

If it asks Flow to decide the story, return it to storyboard review.

## Step 4: Generate A Controlled Batch

Generate only enough candidates to evaluate the same shot plan.

Do not change the plan while evaluating the first batch.

Review candidates for:

* performance;
* identity stability;
* hands and object interaction;
* location and prop preservation;
* camera behavior;
* period accuracy;
* usable start and end frames.

## Step 5: Choose A Revision Path

Use the failure classification:

### A. Input-Frame Failure

The character, prop, composition, or world is already wrong at frame one.

Return to `06_Image_Prompt_Workflow.md`.

### B. Motion Failure

The start frame is right, but the action becomes mechanical, too large, too vague, or physically impossible.

Reduce action scope or clarify the endpoint.

### C. Identity Drift

The face, hairstyle, body, clothing, or role changes during motion.

Strengthen approved references, shorten the clip, simplify motion, and keep camera movement restrained.

### D. Prop Failure

The tool changes object count, material, placement, fill level, or hand ownership.

Specify the object’s owner, hand, state, and action boundary more explicitly. Consider an insert or cutaway.

### E. Location Or Period Drift

The tool adds modern details, changes architecture, relocates features, or introduces generic scenery.

Use a stronger approved location reference and targeted historical exclusions. Reject the output.

### F. Camera Failure

The camera accelerates, orbits, shakes, reframes, or turns a quiet scene into spectacle.

Specify a locked camera or simplify the subject action. A static shot is a valid solution.

### G. Timing Failure

The desired action happens too early, too late, or has no clean end.

Change the action pacing or endpoint; do not rely on random trimming to fix a missing beat.

## Step 6: Reroll With One Deliberate Change

Log the changed variable:

```text
R02: shortened hand action; camera fixed.
R03: added approved prop reference; no other prompt change.
R04: changed endpoint from “place leaf” to “hold leaf above basket.”
```

Do not stack unexplained prompt edits.

Controlled variation teaches the team which instructions are dependable.

## Step 7: Consider Extension Carefully

Use Flow’s available extension capability only when:

* the existing clip ends in a stable, correct state;
* the action naturally continues;
* character and prop identity remain stable;
* the edit truly needs additional duration.

Before extending, inspect the final frames for drift.

Do not extend a flawed clip in the hope that it will correct itself.

Prefer a new shot when the next beat changes camera, action, emotion, location, or continuity state.

## Step 8: Export And Verify

Export the candidate using the required shot name:

```text
EP014_S02_SH006_R03_CandidateB
```

After export, verify:

* actual frame shape and resolution;
* duration;
* beginning and ending frame;
* dropped frames or compression artifacts;
* crop safety;
* audio presence or absence;
* filename and archive linkage.

An exported clip is not approved until it passes sequence review.

---

# Camera Continuity Rules

## Camera Is An Observer

The camera quietly accompanies ordinary life.

Characters do not play to it.

Direct eye contact is rare and must serve a real story moment.

## Match The Board

Do not change:

* shot size;
* camera side;
* camera height;
* screen direction;
* movement style;
* focal subject;
* or lens feeling

without a documented storyboard revision.

## Use Stable Camera For Delicate Actions

Hands preparing food, children learning, animals resting, and quiet emotional reactions benefit from a fixed frame or a nearly imperceptible move.

## Preserve Screen Direction

If a character exits screen right, the next related shot must preserve understandable travel or intentionally re-establish geography.

Do not let a generation flip the character or reverse a tool action between cuts.

## Match Cut Points

Plan endpoint states that cut cleanly:

* hand reaches object;
* vessel rests on surface;
* gaze arrives at subject;
* person completes one step;
* steam continues;
* door has just settled.

Avoid clips ending in unstable limbs, mid-blinks, object warps, or aggressive camera motion.

---

# Character, Location, And Prop Continuity Rules

## Recurring Characters

Use approved character references for prominent recurring people.

Preserve face, build, age, skin tone, hair, clothing logic, body language, relationships, and role.

The main family is Father, Mother, Elder Brother, Younger Daughter, and the German Shepherd family dog.

The dog remains a gentle, loyal village companion; it must never become a police, military, or threatening attack-dog portrayal.

## Locations

Preserve documented architecture, material wear, entry points, fixed furniture, trees, paths, boundaries, and geography.

If a shot needs a new angle, establish that angle with a reviewed reference before animating it.

## Props

Track every story prop through:

* owner;
* hand or storage position;
* orientation;
* amount or fill level;
* cleanliness or wetness;
* damage;
* start state;
* end state.

Never allow a Flow output to add duplicate tools, substitute materials, or change a clay, brass, bamboo, wood, or stone object into modern plastic or metal.

## Time, Light, And Weather

Maintain seasonal state, clouds, shadow direction, wetness, flame behavior, smoke movement, clothing response, and time progression.

A rain scene cannot become warm sunny afternoon midway through a clip unless the storyboard expressly includes that transition.

---

# YouTube Delivery Rules

## Shorts

For 9:16:

* put the story action in the central vertical field;
* keep faces, hands, and key props clear of overlay-prone edges;
* make the first visual beat understandable without audio;
* avoid tiny background actions as the only narrative clue;
* provide a clean final frame for a loop, cut, or emotional finish.

Do not use a frantic first second to imitate retention tactics.

The hook should be visible purpose: rain threatens drying chillies, a missing tool interrupts work, a child notices something, or a craft action begins.

## Long Form

For 16:9:

* use wider frames for geography and daily rhythm;
* preserve readable subjects at mobile scale;
* vary scale and pace naturally;
* leave room for sound-led observation;
* avoid filler shots that repeat the same information.

## Captions And Titles

Generate the world without text, titles, subtitles, logos, or watermarks.

Add all readable text in the edit.

Protect uncluttered space for captions only when the board calls for it.

---

# Sound And ASMR Rules

Treat generated audio as a candidate, not automatic final sound.

If Flow’s current mode creates audio, review it for:

* period accuracy;
* intelligibility;
* emotional fit;
* continuity between cuts;
* unwanted music, voices, or effects;
* whether it masks planned ASMR.

Prefer controlled post-production sound for critical continuity:

* grinding stone;
* water vessel;
* rain on roof;
* ladle against brass;
* birds and insects;
* footsteps;
* distant village activity.

Never allow generated dialogue to establish essential canon, naming, plot, or cultural fact unless separately scripted, checked, and approved.

Silence remains a valid and often preferable choice.

---

# QA Workflow

## Pass 1: Technical Integrity

Check:

* no broken anatomy;
* no extra limbs, fingers, faces, animals, or tools;
* no warped objects;
* no flicker that distracts;
* no visual tearing or sudden texture changes;
* no unexpected text, logos, or watermarks.

## Pass 2: Canon And History

Check:

* early-1990s rural Tamil Nadu material culture;
* correct recurring character identity;
* documented location features;
* suitable clothing, tools, architecture, and transport;
* no modern technology, branding, LED lighting, contemporary appliance, or plastic-dominant environment;
* no stereotype, poverty caricature, or generic “village” replacement.

## Pass 3: Continuity

Check:

* prior-shot entry state;
* character orientation and screen direction;
* prop handoff and state;
* costume, hair, and body consistency;
* light, weather, and time;
* next-shot endpoint;
* emotional progression.

## Pass 4: Editorial And YouTube

Check:

* clear focal action;
* usable handles before and after action;
* correct format;
* mobile readability;
* caption-safe composition;
* appropriate duration;
* no unnecessary spectacle;
* a natural cut or hold point.

## Pass 5: Emotional Truth

Ask:

* Does this feel like the documented character?
* Does the action have believable weight and pace?
* Does the village feel lived in?
* Is the camera respectfully observing?
* Does the motion strengthen the episode rather than advertise the tool?

---

# Positive Production Examples

## Example: Simple Object Handoff

Storyboard plan: Mother places a half-full brass tumbler on the kitchen shelf.

Flow plan: one close shot, stable camera, right hand moves tumbler to the shelf, hand withdraws, tumbler remains upright.

Why it succeeds:

* one person;
* one object;
* one motion;
* controlled end state;
* a clean cut to a child noticing the tumbler.

## Example: Rain Observation

Storyboard plan: rain begins during a courtyard task.

Flow plan: static medium shot; three first raindrops darken the packed earth, Mother looks toward the roof edge, clothesline cloth moves slightly.

Why it succeeds:

* weather changes are readable;
* the character reaction is small;
* the location remains stable;
* the editor can cut from the first drop, the glance, or the rain texture.

## Example: Family Dog Beat

Storyboard plan: the dog waits outside the kitchen while food is prepared.

Flow plan: stable low-medium frame; the German Shepherd shifts its paws, looks toward the kitchen door, and its ears respond softly to the ladle sound.

Why it succeeds:

* the dog behaves as a calm household companion;
* motion is limited and natural;
* the kitchen and dog relationship carry emotional information;
* no exaggerated animal performance is required.

---

# Common Mistakes And Corrections

## Mistake: One Prompt, Full Scene

Problem: a request includes dialogue, walking, cooking, a child entering, the dog reacting, rain beginning, and a tracking camera.

Correction: make separate shots for the action, reaction, weather insert, and arrival.

## Mistake: Accepting A “Beautiful” Drift

Problem: the clip has dramatic lighting and fluid movement but turns the house into a generic modern interior.

Correction: reject it. Visual beauty cannot compensate for broken canon.

## Mistake: Camera Spectacle

Problem: the camera circles a person making tea or races through a courtyard.

Correction: lock the camera, use a gentle reveal, or let the subject action carry the shot.

## Mistake: Animating A Bad Keyframe

Problem: the start frame has wrong costume, a distorted basket, or an incorrect garden layout.

Correction: return to the image workflow and repair the source. Flow will amplify input problems.

## Mistake: Rerolling Without A Hypothesis

Problem: the operator submits many variants after a weak result but records no changes.

Correction: classify the failure, change one prompt or input variable, and log the revision.

## Mistake: Extension As A Cure

Problem: a clipped or drifting action is extended repeatedly.

Correction: regenerate the bounded action or cut to a new shot. Extension only continues a stable result.

## Mistake: Missing Prop Logic

Problem: a basket changes hands, a pot changes fill level, or a tool becomes a different material.

Correction: state ownership, hand, orientation, state, and end condition; use an approved prop reference.

## Mistake: Generated Text Or Voice Becomes Canon

Problem: Flow invents a sign, label, spoken line, or narration that changes place or story facts.

Correction: remove it. Add approved text and audio downstream.

---

# Release Checklist

## Shot Setup

* Is the storyboard shot locked and correctly identified?
* Are keyframes and references approved?
* Does the motion prompt state one dominant action and endpoint?
* Is the format correct for the release?

## Generation

* Does the clip preserve identity, location, props, light, and period?
* Is camera behavior restrained and correct?
* Is secondary motion supporting rather than competing?
* Is the clip short enough and editable?

## Continuity

* Does the start match the preceding shot?
* Does the end support the next shot?
* Are screen direction, hands, props, weather, and costume coherent?
* Are character relationships and behavior recognizable?

## Technical

* Are anatomy, objects, backgrounds, and motion stable?
* Is the output free of accidental text, logos, modern objects, and visual artifacts?
* Has the export been verified at actual size and duration?

## Viewer Experience

* Is the key action readable on a phone?
* Does the opening shot work without sound?
* Is the frame safe for captions and interface overlays?
* Does the clip feel warm, patient, and authentic rather than tool-driven?

---

# Related Documents

* `01_Canon/01_Series_Style_Lock/Project_Identity.md`
* `01_Canon/01_Series_Style_Lock/Art_Style.md`
* `01_Canon/01_Series_Style_Lock/Production_Quality.md`
* `01_Canon/07_Timeline.md`
* `02_World/README.md`
* `03_Characters/README.md`
* `03_Characters/Character_Rules/Canon.md`
* `03_Characters/Character_Rules/Camera_Rules.md`
* `04_Objects/README.md`
* `05_Research/Common_Historical_Mistakes.md`
* `06_Story_Engine/14_ASMR_Storytelling.md`
* `07_Episode_System/09_ASMR_Placement.md`
* `07_Episode_System/10_Music_And_Silence.md`
* `07_Episode_System/12_YouTube_Shorts.md`
* `08_Production/05_Storyboard_Workflow.md`
* `08_Production/06_Image_Prompt_Workflow.md`

---

# Final Approval

A Google Flow clip is approved only when it is a faithful, editable continuation of the locked storyboard and approved visual references.

If the generation changes the village instead of serving it, regenerate or redesign the shot.
