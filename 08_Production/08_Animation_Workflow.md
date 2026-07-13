# Animation Workflow

## Purpose

This manual defines the permanent workflow for turning an approved Village Stories scene into usable animation with Google Flow.

It protects the series from the most common AI-production failure: a beautiful individual clip that no longer belongs to the same village, family, day, or emotional moment as the clips around it.

Use this manual after story and episode planning are approved and before a scene is released to post-production.

---

## Philosophy

Animation is not decoration placed on top of the story.

It is the visible behaviour of a living village: a hand rinsing rice, a child waiting for an answer, a fan moving slowly in the heat, a dog choosing a patch of shade, and rain changing the pace of work.

Google Flow supplies motion; the production team supplies judgment. A generated shot is only acceptable when its movement, camera, weather, props, performance, and emotional temperature agree with canon and with the adjacent shots.

Prefer one clear action, observed patiently, over restless movement or spectacle.

---

## Objectives

Every completed animated scene must:

* Preserve the identity of locked characters, locations, objects, and animals.
* Preserve the approved camera language, art direction, lighting, and period detail.
* Show a truthful, physically understandable action.
* Carry the scene's intended story beat without exaggerated performance.
* Join its preceding and following shots without continuity jumps.
* Leave space for natural sound, ASMR, narration, and silence.
* Be technically clean enough for the intended YouTube format.

---

## Scope and Boundary

This document governs animation production and animation review.

It does not define a character's canonical appearance, a location's layout, an object's design, a story's meaning, or the final audio mix. Read and obey the documents that hold those authorities. Do not solve a production problem by silently changing canon.

When a new recurring visual fact is required, pause production and document or obtain approval through the appropriate canon process before treating it as permanent.

---

## Required Inputs

Before opening Google Flow, assemble a scene packet containing:

1. Approved episode beat and scene objective.
2. Shot list or storyboard with shot purpose, duration target, framing, and transition.
3. Relevant character profiles, including clothing and emotional state.
4. Relevant location documentation, including time, weather, entrances, and usable zones.
5. Object references for every recurring or story-critical prop.
6. The applicable Series Style Lock documents.
7. A continuity ledger from the prior scene, or a new-scene baseline.
8. Audio intention: narration, featured natural sound, and planned silence.

Do not begin from a vague premise such as “make a pretty village scene.” Ambiguity makes continuity drift inevitable.

---

## Roles

### Director or Episode Lead

Owns story intent, shot purpose, and final creative approval. Decides whether a shot says the right thing, not merely whether it looks impressive.

### Continuity Lead

Maintains the scene packet and continuity ledger. Verifies costume state, prop position, time of day, weather, injuries or dirt, and unfinished actions across shots.

### Google Flow Operator

Builds controlled generation briefs, submits generations, labels versions, and identifies deviations rather than concealing them with selective exports.

### Animation Reviewer

Checks performance, physical logic, camera behaviour, visual identity, and cut compatibility before handoff.

One person may fill more than one role in a small production, but each responsibility must still be performed explicitly.

---

## Canon Authority

Apply authority in this order:

1. Specific character, location, object, animal, and world documents define what exists.
2. Series Style Lock documents define how the world looks, moves, sounds, and feels.
3. Story Engine defines truthful dramatic use.
4. Episode System defines the delivery shape for viewers.
5. This manual defines the animation-production procedure.

If a Google Flow result conflicts with any higher authority, reject or regenerate it. Visual attractiveness does not make an incorrect result usable.

---

## Continuity Ledger

Create one ledger per episode and update it after every approved shot.

For each scene, record:

* Scene, shot, version, and source reference.
* Day, time of day, weather, season, and lighting family.
* Character present, entrance side, exit side, costume, hair, footwear, and carried items.
* Location zone, door or window state, furniture arrangement, and visible background anchors.
* Object start position, handling hand, condition, fill level, and end position.
* Action start pose and action end pose.
* Emotional temperature and narration status.
* Featured sound opportunity and silence requirement.
* Transition rule for the next shot.

The ledger is an operational record, not an optional memory aid.

---

## Google Flow Operating Principles

### Generate From References

Use approved image, character, location, and prop references whenever Google Flow allows them. A text-only description is insufficient for recurring elements.

### Keep the Unit Small

Generate a single shot with one central action. Do not request a complete scene containing arrivals, dialogue, a cooking process, a camera orbit, and a dramatic conclusion.

### State What Must Not Change

Name essential continuity locks: the same costume, same clay stove, same doorway, same late-afternoon light, same object in the right hand, or same wet courtyard.

### Describe Observable Action

Write “Mother lifts the brass tumbler, pauses to listen to rain, then sets it beside the stove” rather than “Mother feels nostalgic.”

### Preserve Camera Restraint

Specify the approved framing and movement. Calm observational shots generally need locked framing, a slow deliberate drift, or a small motivated follow—not a wandering camera.

### Generate Alternatives, Then Select

Create enough controlled variations to compare performance and continuity. Never stitch unrelated “best-looking” fragments into an incoherent action.

---

## Prompt Construction

Build each Google Flow prompt in this order:

1. **Identity:** series, location, time, weather, and visual treatment.
2. **Locked assets:** named character, costume state, required objects, and background anchors.
3. **Shot grammar:** framing, camera height, lens feeling if established, and movement.
4. **Action:** one readable sequence with start, change, and finish.
5. **Performance:** restrained physical behaviour and gaze direction.
6. **Light and atmosphere:** only the approved lighting and environmental condition.
7. **Continuity locks:** items that must remain stable until the cut.
8. **Exclusions:** no modern items, logos, extra characters, impossible actions, or unwanted camera moves.

Prompt for what the viewer can verify in the frame. Avoid style adjectives that conflict with the Series Style Lock or invite generic cinematic excess.

---

## Example Google Flow Brief

**Scene objective:** show Father noticing that the first rain has reached the courtyard before he continues a repair.

**Continuity state:** early monsoon afternoon; Father wears the same faded shirt and folded veshti as the prior shot; wooden stool remains beside the half-repaired doorway; hammer stays on the stool.

**Generation brief:**  
“Village Stories, early-1990s rural Tamil Nadu home courtyard in gentle monsoon rain. Medium side view at seated eye level, stable camera with only a very slow inward drift. Father, matching the approved reference and wearing the same faded shirt and folded veshti, sits beside the half-repaired wooden doorway. He hears rain, lifts his gaze toward the courtyard, waits for two calm beats, then covers the hammer on the stool with a folded cloth. Keep the wet red-earth courtyard, brass water pot near the wall, and doorway position unchanged. Restrained hand-painted animation, natural physical timing, no dramatic acting, no modern objects, no camera orbit, no extra people.”

The prompt makes the story, visual lock, action, sound opportunity, and cut state inspectable.

---

## Detailed Workflow

### 1. Confirm the Scene Need

Read the scene objective aloud in one sentence. If it cannot be stated simply, return to the storyboard. Animation cannot repair an unclear story beat.

### 2. Load Only Relevant Authority

Collect the documents for the people, place, objects, season, and style rules in the shot. Do not rely on an old prompt as an authority source.

### 3. Establish the Baseline Frame

Define the exact state at shot start: who is present, where everyone stands, what they wear, where key objects sit, and what the audience last saw.

### 4. Decide the Shot Job

Choose one job: establish place, reveal action, register emotion, show process, create rest, or carry a transition. A shot with multiple jobs tends to become rushed.

### 5. Plan the Cut

Specify what image, action, sound, or stillness connects to the preceding and following shots. Plan the cut before generating, not after finding a pleasing clip.

### 6. Write the Generation Brief

Use the prompt construction order above. Include positive constraints and necessary exclusions; do not overload the prompt with unrelated lore.

### 7. Generate and Log Versions

Label every attempt with episode, scene, shot, take, and date or revision identifier. Record the prompt and references used so an approved result is reproducible.

### 8. Perform First-Pass Rejection

Reject any take with identity drift, anachronism, incorrect object handling, unwanted people, broken anatomy, unexplained camera motion, or a different weather/light condition.

### 9. Review Motion in Context

Place the candidate between temporary adjacent shots. Watch without music first. A clip that works alone may fail through a jump in direction, brightness, pace, or object position.

### 10. Refine One Variable at a Time

When regenerating, change the clearest cause: camera movement, hand action, prop lock, timing, or lighting. Do not rewrite every element after each failure; that removes diagnostic control.

### 11. Approve the Master Take

The Director confirms story truth; the Continuity Lead confirms state; the Animation Reviewer confirms craft. Update the ledger immediately.

### 12. Prepare Handoff

Export the approved version, reference still, version notes, scene ledger entry, and the intended audio space for post-production.

---

## Movement Rules

Characters should move with task, age, mood, and environment in mind.

* Hands contact objects before objects move.
* Weight shifts before standing, lifting, turning, or walking.
* A character looks toward something before reacting to it, unless surprise is the intended beat.
* Children may be lively, but never mechanically hyperactive.
* Elders are not automatically slow or frail; follow their individual character documentation.
* Animals behave with care, distance, curiosity, rest, and routine—not as comic props.
* Weather affects fabric, footing, work speed, and posture when visible.

Do not use constant blinking, head bobbing, hovering fabric, random smiles, or unrelated gesturing to make a quiet shot seem active.

---

## Camera and Composition

Follow `Camera_Language.md` as the authority.

For production review, confirm:

* Screen direction carries through an action unless the cut deliberately resets orientation.
* Camera height respects the viewer's relationship to the subject.
* A move has a reason: reveal, follow, notice, or transition.
* The subject is not framed as a spectacle when the beat is domestic or private.
* Background movement supports the location without competing with the story action.
* The camera leaves room for the visual rhythm needed by narration and sound.

An unmotivated crane, orbit, rack focus, or fast push-in is a defect even if Google Flow renders it smoothly.

---

## Location and Object Integrity

Do not treat a setting as replaceable scenery.

Maintain:

* Correct architecture, surfaces, vegetation, pathways, and working zones.
* Logical object storage, scale, orientation, wear, and material.
* Doors, windows, vessels, tools, furniture, and garments in their recorded states.
* The practical consequences of the activity: steam near cooking, dampness after rain, dust after sweeping, or reduced light after sunset.

If a prop cannot remain visually reliable across a complex action, redesign the shot around a simpler, more stable interaction. Do not conceal an implausible result with rapid cutting.

---

## Historical Authenticity Check

Before approval, ask:

* Could this tool, garment, vehicle, packaging, light source, or behaviour reasonably exist in the early-1990s village?
* Does the scene avoid treating the village as either a museum display or a stereotype of deprivation?
* Are trade, domestic work, worship, school, animals, and family relationships treated with dignity?
* Has convenience been added only because an AI model defaults to modern life?

Use `05_Research/Common_Historical_Mistakes.md` as the final rejection screen for visible anachronisms.

---

## Animation Quality Checks

### Identity

* Does every recurring character match the approved profile and current costume state?
* Do location anchors and recurring objects match their source documents?

### Action

* Is there one readable action with a logical beginning and end?
* Does contact, weight, timing, and gaze make physical sense?

### Continuity

* Do hands, props, entrances, exits, lighting, weather, and time of day agree with adjacent shots?
* Is the action end state recorded for the next shot?

### Camera

* Is the framing intentional and the move restrained?
* Does screen direction remain clear?

### Series Tone

* Is the performance warm, observant, and emotionally honest?
* Is the pace calm without becoming empty?

### Technical Readiness

* Is the selected take stable, artifact-free, and clean at the destination crop?
* Is there sufficient handle before and after the central action for editing?

---

## Common Mistakes and Corrections

### Mistake: Accepting a Near Match

A generated child is “close enough” to the locked character but has different hair, clothing, or age cues.

**Correction:** reject it. Reuse the approved reference and simplify the shot until identity holds.

### Mistake: Solving Boredom With Camera Motion

A quiet cooking beat is given a fast orbit or dramatic push.

**Correction:** let the action, texture, steam, hand movement, and sound carry attention. Use a stable close or medium shot.

### Mistake: Treating a Prop as Disposable

A brass vessel becomes steel, changes size, or moves from left to right between shots.

**Correction:** lock the object reference, state its position and handling hand, and update the continuity ledger.

### Mistake: Generating Emotion Instead of Behaviour

A prompt asks for “deep sadness,” producing exaggerated faces and theatrical gestures.

**Correction:** specify observable behaviour: a pause, lowered gaze, unfinished task, or softened voice posture.

### Mistake: Cutting Away From Natural Sound

The edit changes shots just as a ladle touches a pot or rain begins on a roof.

**Correction:** preserve the action and leave room for the corresponding sound in post-production.

---

## Decision Framework

When choosing between two acceptable takes, decide in this order:

1. Canon accuracy.
2. Continuity with adjacent shots.
3. Clear story action.
4. Honest performance and physical logic.
5. Camera and style consistency.
6. Audio opportunity and editorial flexibility.
7. Surface beauty.

Never reverse this order. The most attractive clip is not automatically the most useful shot.

If no candidate meets the first four criteria, regenerate or revise the shot plan.

---

## YouTube Delivery Considerations

Choose animation framing for the approved episode format before generation.

* For Shorts, protect the central action and faces within the vertical safe area while retaining a natural composition.
* For long-form video, allow the setting to breathe, but do not leave vital action unreadable on smaller screens.
* Do not crop a character's hands when their work is the story.
* Do not add visual shocks, frantic cutting, or false danger to chase retention.
* Keep readable visual change in the opening, while preserving the series' calm promise.

The platform affects delivery choices; it never authorizes a break from canon or tone.

---

## Related Documents

Read as needed:

* `00_Project_Core/README.md`
* `01_Canon/01_Series_Style_Lock/Animation_Principles.md`
* `01_Canon/01_Series_Style_Lock/Camera_Language.md`
* `01_Canon/01_Series_Style_Lock/Visual_Identity.md`
* `01_Canon/01_Series_Style_Lock/Lighting_Style.md`
* `01_Canon/01_Series_Style_Lock/Production_Quality.md`
* Relevant files in `02_World/`, `03_Characters/`, and `04_Objects/`
* `05_Research/Common_Historical_Mistakes.md`
* `06_Story_Engine/13_Visual_Storytelling.md`
* `07_Episode_System/03_Scene_Structure.md`
* `07_Episode_System/11_Visual_Rhythm.md`

---

## Guiding Principle

Animate the truth of the moment, then protect it from shot to shot.
