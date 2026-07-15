# Episode Generation Pipeline

## Permanent Purpose

This manual is the end-to-end operating pipeline for turning one approved
Village Stories idea into a traceable, quality-approved YouTube episode.

It connects story development, script, boards, canon packets, still-image
generation, Google Flow animation, voice and audio, edit, QA, packaging,
publishing, and archive. It defines required handoffs and quality gates so that
an episode remains the same known village at every stage.

> Each stage may clarify or execute an approved decision. No stage may invent a
> new permanent fact to make itself easier.

This is a production pipeline, not a substitute for the authorities it uses.
Canon decides facts; Story Engine decides truthful story; Episode System decides
viewer experience; Production decides execution and release controls; the AI
Production System makes approved visual work repeatable.

---

## Authority And Pipeline Law

Apply the highest relevant source. A generated output, platform control,
reference image, analytics result, or attractive candidate has the lowest
authority.

```text
Current approved production or release decision
↓
01_Canon/ — global timeline, continuity, art style, camera philosophy
↓
02_World/ · 03_Characters/ · 04_Objects/ · 05_Research/
↓
06_Story_Engine/ — story truth, emotional limits, forbidden patterns
↓
Approved episode brief, script, storyboard, and state ledger
↓
07_Episode_System/ — hook, structure, pace, sound, format, ending
↓
08_Production/ — file, version, generation, edit, QA, release practice
↓
09_AI_Production_System/ — prompt, lock, Flow, revision systems
↓
Prompts, references, tool settings, candidates, selected assets
```

If facts conflict or an essential fact is absent:

1. name the conflict or missing fact;
2. mark the affected work `HOLD FOR CANON OR RESEARCH`;
3. return it to the owner of that decision;
4. record the hold in the episode record;
5. resume only with a documented resolution.

Never average instructions, invent a bridge fact, use a generated asset as
proof, or ask editing to conceal a contradiction.

---

## Non-Negotiable Production Locks

Every pipeline stage must preserve the applicable locks below. A lock is not
optional because it appears only in a background detail.

### World, period, and dignity

* The setting is early–mid-1990s rural Tamil Nadu. The exact calendar year can
  flex; the period cannot.
* No mobile phones, internet, contemporary screens, LED fixtures, modern
  branding or packaging, current fashion, current vehicles, modern appliances,
  urban infrastructure, or unsupported convenience may appear.
* Village life is specific, practical, lived-in, and dignified—not a generic
  exotic setting, a poverty spectacle, or an AI showcase.

### Story and character

* Use people only when the approved story gives them a reason to be present.
* Preserve documented character appearance, personality, skill, conduct,
  relationship, age appropriateness, and emotional scale.
* Mother, Father, Elder Brother, Younger Daughter, and the Family Dog retain
  their individual documents as the detailed authority.
* Father’s approved design reference is required as `CHARACTER_IDENTITY` when
  he is principal, face-visible, establishing a new setup, or being repaired.
  It controls identity only, not incidental background or pose.
* Preserve Mother’s approved practical identity and, where visible, her small
  bindi, left-nostril nose pin, thin glass bangles, jhumkas, and exactly one
  thali chain.
* The Family Dog is a gentle German Shepherd household companion, never an
  attack, police, military, rescue, chase, injury, threat, or stakes device.
* Do not create villains, panic, humiliation, danger, child endangerment,
  animal distress, or melodrama to increase apparent engagement.

### Style, location, light, camera

* Use the official Studio Ghibli-inspired digital anime aesthetic for the entire
  frame (`Art_Style.md`), matching
  `11_Assets/Character_References/Father_Canon_Design_Reference.png` /
  `Mother_Canon_Design_Reference.png`: painterly watercolor/gouache digital
  anime; soft delicate linework; soft cel-style painted shading; warm cinematic
  lighting. Do not name or imitate any other studio, artist, film, franchise, or
  property.
* Preserve documented location layout, materials, work zones, entry points,
  routes, landmarks, and screen geography.
* Preserve season, time, weather, wetness, vegetation, smoke, water, and
  physically motivated light. Morning is east light; evening is west light.
* `19_Camera_Direction_Bible.md` is the sole authority for camera position,
  size, height, angle, side, screen direction, composition, and framing.
* `20_Camera_Movement_Bible.md` is the sole authority for camera motion. Start
  from an approved direction; use at most one calm, bounded movement. Stillness
  is a normal choice.

### Continuity, delivery, and audio

* Preserve wardrobe, hair, carried objects, object count/owner/hand/fill/state,
  task progress, emotion, screen direction, routes, and next-shot handoff.
* Generate in the delivery aspect ratio where practical. Shorts require central
  9:16 action and caption-safe framing; long form uses 16:9 to preserve useful
  geography without losing a phone-readable subject.
* Generated sound has no authority by default. Dialogue, narration, ambience,
  Foley, music, silence, captions, and rights require their own approved plan.

---

## Roles And Stage Ownership

| Role | Owns |
| --- | --- |
| Episode Director | Episode intent, creative choices, changed scene purpose, final creative approval. |
| Canon and Continuity Lead | Source authority, lock selection, continuity ledger, factual holds and cross-shot decisions. |
| Story / Script Lead | Approved premise, beat sheet, script, dialogue/narration, story-state handoff. |
| Storyboard Artist / Shot Designer | Scene-to-shot design, camera direction, cut logic, state and delivery plan. |
| Prompt Lead | Source packets, prompts, references, prompt versions, and diagnostic revision records. |
| Image Operator | Controlled still-generation candidates and source-image records. |
| Google Flow Operator | Bounded Flow tasks, supported-mode confirmation, candidate clips, exports, and settings record. |
| Voice and Sound Lead | Voice direction, sound plan, Foley, ambience, music, captions, rights, and mix. |
| Editor | Sequence assembly, picture/sound relationship, crop, rhythm, captions, and master exports. |
| Quality Lead | Independent gate evidence, defects, waivers, and release recommendation. |
| Release Manager / Publisher | Approved package, private upload, platform verification, schedule, public record. |

No person approves their own unresolved defect. A role may be held by one
person in a small production, but the records and independent review standard
still apply.

---

## Episode Record And Workspace

Before work begins, create an identified episode record using the logical
workspace model from `08_Production/16_File_Organization.md`:

```text
[Episode_ID]/
  00_Admin/       brief, owners, approvals, handoffs
  01_Story/       premise, beats, script, narration
  02_References/  source manifest, lock packets, approved reusable references
  03_Storyboard/  scene cards, boards, shot list, animatic
  04_Generation/  prompts, stills, Flow tasks, candidates, selected assets
  05_Audio/       voices, ambience, Foley, music, captions, rights
  06_Edit/        projects, sequences, edit exports
  07_QA/          issue log, reviews, approvals, waivers
  08_Release/     master, thumbnail, metadata, upload record
  09_Archive/     frozen milestones and superseded history
```

The episode record must identify:

```text
Episode ID / working title / owner / revision:
Format: Short / long form / both:
Target runtime and delivery ratios:
One-sentence premise and emotional centre:
Selected characters, locations, season, time, weather:
Continuity start and required final state:
Source manifest and OPEN items:
Hook and ending intent:
Audio, caption, thumbnail, and metadata plan:
Current stage and approvals:
```

Use fixed identifiers (`ep_014`, `sc_02`, `sh_006`, `r03`, `tk_01`) and the
production naming pattern. Never label an asset `final`, `latest`, or
`use_this_one`.

---

# The Pipeline

## Gate 0 — Intake, Format, And Canon Readiness

### Objective

Confirm there is a source-supported episode worth planning before a script,
board, prompt, or tool task exists.

### Required inputs

* episode identifier, owner, intended format, and target runtime;
* a one-sentence practical premise;
* applicable canon, world, character, object, research, and Story Engine
  sources;
* initial season, time, weather, location, character, and continuity facts;
* any existing cross-episode relationship or release-order constraint.

### Procedure

1. State the ordinary practical need, gentle pressure, response, emotional
   centre, and resting end image.
2. Confirm that every named person, place, object, skill, route, and cultural
   detail is supported.
3. Select Short, long form, or both from the storytelling need, not by simply
   cropping one plan later.
4. Identify all `OPEN` facts and their owners.
5. Decide whether the episode starts a new state or continues a documented one.

### Gate 0 pass

Pass only when the premise is truthful, proportionate, source-backed, and has
no unresolved recurring or continuity-critical fact.

**Handoff to story:** approved premise, compact source manifest, format
rationale, initial state, known restrictions, and resolved/open-item record.

---

## Stage 1 — Story Development And Episode Plan

### Objective

Turn the premise into an approved episode promise that viewers can understand
without violating the series’ calm, practical scale.

### Procedure

1. Use the story prompt process to develop one central practical thread.
2. Build a visible progression: condition or need, preparation, action, gentle
   turn, response, result, and emotional rest.
3. Make the hook truthful: a task underway, meaningful condition, object,
   weather consequence, or small discovery—not implied danger.
4. Ensure each scene changes task knowledge, place understanding, character
   feeling, or payoff.
5. Identify educational detail through observed skill, care, choice, or
   consequence; never use a lecture or universal cultural claim.
6. Define natural sound, ASMR, music, silence, and dialogue opportunities at
   the scene level.
7. State the first and final continuity condition.

### Short-form plan

A Short normally carries one activity and one recognisable change. The opening
must orient a new viewer quickly; the action must remain central in 9:16; the
final frame must supply a clean rest, loop, or honest cut. Do not add frantic
camera motion or false stakes to force retention.

### Long-form plan

Long form may allow process, environmental arrival, related family work, and
breathing room when each addition reveals something new. It must not extend
runtime with repeated task footage, unmotivated atmospherics, or secondary
conflict.

### Gate 1 pass

The Director, Story Lead, and Continuity Lead confirm the premise, beat plan,
format decision, truthful hook, scene purposes, sound opportunities, ending,
and continuity start/end state.

**Handoff to script:** locked beat sheet, source manifest, scene-purpose list,
format notes, hook/final-image intent, and state ledger seed.

---

## Stage 2 — Script And Narrative Audio Plan

### Objective

Convert the episode plan into observable, production-ready scenes rather than
literary prose or an AI-generated synopsis.

### Procedure

1. Assemble the compact canon packet required by
   `03_Master_Script_Prompt.md`.
2. Write scenes in visual cause and effect: who is where, what changes, what
   viewers must see/hear, and what state passes forward.
3. Use dialogue or narration only when image, action, and sound cannot carry
   the information alone.
4. Record each scene’s location zone, time, weather, character state,
   wardrobe, object state, transition, sound opportunity, and final handoff.
5. State any language and caption requirements.
6. Mark facts as `HARD LOCK`, `SCENE FACT`, `CONTINUITY BRIDGE`, `OPTIONAL`,
   `NEGATIVE`, or `OPEN`.

### Required script output

```text
Scene ID and purpose:
Visible beat / one-sentence action:
Characters and state:
Location / season / time / weather:
Props and state:
Dialogue / narration only if needed:
Natural sound / ASMR / music / silence opportunity:
Incoming continuity:
Outgoing continuity:
Shorts or long-form delivery note:
```

### Gate 2 pass

The script contains no unsupported fact, explanation-only action, unbounded
emotion, ambiguous route, or multi-purpose scene. It gives storyboards a
concrete state transition.

**Handoff to board:** approved script revision, scene cards, narration and
dialogue draft, sound plan, source packet, and state-ledger entries.

---

## Stage 3 — Storyboard, Camera, And Shot Design

### Objective

Translate every scene into the smallest visual units that can be generated,
animated, edited, and reviewed safely.

### Procedure

1. Give every shot a stable scene/shot ID and one primary visual question.
2. Record start state, one visible action or held moment, and required end
   state. Split multi-person, multi-stage, or spectacle-heavy material.
3. Write the full Document 19 camera direction before any motion instruction:
   shot size, height, angle, side, screen direction, subject placement,
   landmark/background relation, crop-safe area, and incoming/outgoing relation.
4. Consult Document 20 only after direction is approved. Choose `LOCKED
   CAMERA` by default; otherwise specify one justified movement with start,
   path, speed, extent, end frame, and subject protection.
5. Design vertical and horizontal compositions separately where both formats
   require genuine readability. Do not treat crop as an afterthought.
6. Build an animatic or timed board sufficient to test pace and visual rhythm.

### Shot design rules

* A board shot is not “Mother cooks while everyone arrives and rain begins.”
  Split it into clear actions and causal reactions.
* A close-up cannot also establish essential geography; a wide cannot also
  carry a subtle facial reaction.
* Keep hands, tools, faces, travel direction, and story evidence visible.
* A planned cut must have a factual handoff; never rely on music, blur, or a
  dissolve to hide a changed prop, weather state, or camera line.

### Gate 3 pass

Every shot has a purpose, source scene, action boundary, direction record,
movement decision, output use, delivery ratio, sound/edit note, and recorded
incoming/outgoing state.

**Handoff to asset packet:** locked boards, shot list, camera records,
animatic/timing notes, scene-state ledger, and delivery/caption-safe plan.

---

## Stage 4 — Canon Packet And Asset-Packet Assembly

### Objective

Create a compact, source-backed work packet for each shot. The packet applies
canon; it does not duplicate or replace it.

### Procedure

1. Select only sources that materially constrain the shot.
2. Extract exact applied facts with source path and heading.
3. Declare required locks: series style, character, location, object,
   period/time/weather/light, camera direction, movement, continuity, delivery,
   and audio where relevant.
4. Select only approved reusable references. Assign each its role:

```text
CHARACTER_IDENTITY
LOCATION_GEOGRAPHY
OBJECT_IDENTITY
STYLE_CONFIRMATION
START_FRAME
END_FRAME
```

5. Record known drift risks and targeted negative constraints.
6. Identify whether the shot is still-only, Flow-ready, an insert, a hold,
   thumbnail candidate, or requires a board redesign.

### Required shot fact sheet

```text
Episode / scene / shot / revision:
Output use, ratio, duration:
Shot purpose and one visible moment:
Source paths and applied facts:
Character / location / object / style locks:
Season, time, weather, light, geography:
Incoming and outgoing continuity:
Document 19 camera direction:
Document 20 movement decision:
Reference files and declared roles:
Still / Flow / edit strategy:
Audio and caption-safe requirement:
Known risks, targeted negatives, OPEN owner:
```

### Gate 4 pass

Prompt Lead and Continuity Lead can identify the one action, all material locks,
what may change, what must remain unchanged, adjacent-shot handoffs, and the
approved references. `OPEN` facts block recurring or continuity-critical work.

**Handoff to still generation:** approved fact sheet, reference manifest,
storyboard panel, current ledger, prompt version, and defined pass condition.

---

## Stage 5 — Still Images, Boards, And Keyframes

### Objective

Generate one correct, editable image for each board, insert, thumbnail
candidate, continuity frame, or Flow start/end input.

### Procedure

1. Build the prompt using `04_Master_Image_Prompt.md` and its Reference.
2. Start with output use, subject, one visible moment, location relation,
   time/weather/light, Document 19 direction, style, period anchors,
   continuity, then targeted exclusions.
3. Generate small controlled candidate batches. Within a batch, vary one group
   only (for example, gesture or composition), never all locks at once.
4. Review full resolution, delivery crop, phone size, and adjacent shot
   relation.
5. Approve a still only for its stated use; a keyframe is not automatically a
   thumbnail or reusable reference.

### Still QA

Check:

* recurring identity, expressions, clothing, ornaments, and scale;
* location geometry, period objects, material, and background contamination;
* object count, hand, orientation, fill, condition, and placement;
* anatomy, tool contact, unwanted people/animals, text, watermark, or logo;
* season, rain/wetness, smoke, light source/direction, and shadows;
* camera direction, screen line, composition, safe crop, and action clarity;
* the incoming and outgoing continuity state;
* Flow readiness if the image will animate.

### Gate 5 pass

The selected still is canon-safe, technically clean, supports its exact
purpose, and is linked to its prompt, source packet, review, and asset ID.

**Handoff to Flow or edit:** approved still/keyframe revision, source manifest,
prompt record, start/end state, ratio/duration, and use authorization.

### Phased prompt delivery (Google Flow)

Per `08_Production/06_Image_Prompt_Workflow.md`:

1. **Image prompt only** — one clip at a time, story order; creator approves
   still in Flow.
2. **Then** animation + audio prompts for that clip only (animation includes
   **Duration** from beat sheet / clip workflow table; **Normal Speed** on all
   motion blocks — see `21_Clip_Prompt_Formula.md` § Motion speed standard).
3. **Dialogue** lives inside the audio prompt, not a separate voice file.

Do not open Flow animation until Gate 5 still pass for that clip.

---

## Stage 6 — Google Flow Animation

### Objective

Use Google Flow as controlled continuation of approved imagery, not as a writer
or free-form director.

### Before opening Flow

Confirm the interface actually supports the planned mode, aspect ratio,
resolution, duration, reference behavior, first/last-frame controls, extension,
audio behavior, project history, and export. Tool behavior changes; record the
available capability rather than relying on a prior interface.

Create a bounded project and task:

```text
EP014_RainyCooking_Flow
EP014_S02_SH006_DaughterPicksLeaf_R01
```

### Choose the input strategy

Use one image when an approved start frame, one simple action, and a naturally
usable end are sufficient. Use two approved images only when an exact end state
is needed for the next shot and current Flow controls support it reliably.

Use a still, split shot, or board redesign when a clip needs several actions,
multiple people changing state, a camera line change, a location/time change,
or an unsupported endpoint.

### Write the motion contract

```text
From this approved start state, [subject] performs [one clear action] while
the camera [locked or one approved bounded behavior], ending when [observable
state].
```

Classify the motion:

* `M1` — environment only;
* `M2` — one body or hand action;
* `M3` — one subject plus one supporting environmental response;
* `M4` — multiple subjects/stages: redesign before generation.

Use M1–M3 normally. The Flow prompt preserves the approved identities,
wardrobe, prop state, location, light, composition, style, period, camera line,
and delivery frame. It states one action, one camera behavior, only necessary
environmental movement, a usable endpoint, and the specific diagnosed
exclusions.

### Flow candidate review

Inspect frame one, the action, and final usable frame independently. Review:

* identity and clothing stability;
* hands, feet, face, anatomy, and physical weight;
* object state, material, count, owner, position, and endpoint;
* location, period, weather, light, and background stability;
* Document 19 direction and Document 20 movement boundaries;
* screen direction, cut handles, crop safety, and duration;
* generated text, watermark, logo, unwanted audio, or modern contamination.

### Gate 6 pass

A clip faithfully continues the approved still, completes only the intended
change, supports the next factual state, and exports under its exact shot ID.

**Handoff to edit:** selected clip, candidate/selection record, Flow prompt,
inputs/roles, available settings, first/final-frame notes, continuity update,
audio note, known limitations, and asset status.

---

## Stage 7 — Voice, Foley, Ambience, Music, And Captions

### Objective

Make sound clarify a truthful visible world without inventing plot, emotion, or
period detail.

### Procedure

1. Lock narration and dialogue against the approved script. Voice must match
   speaker, language, character, relationship, and emotional proportion.
2. Build ambience from documented place, time, weather, distance, and period.
3. Place ASMR at meaningful craft or sensory action, not constantly as a rural
   texture.
4. Use Foley for visible actions only: a ladle, wet footstep, firewood, basket,
   rain on roof, or similar grounded source.
5. Use music sparingly for an earned emotional turn; silence/room tone must
   retain purposeful visual presence.
6. Generate and time captions from the locked final words and essential
   non-speech cues. Keep them clear of face, hands, tools, and story objects.
7. Record music, voice, and sound rights/credit status.

### Audio QA

Reject or repair:

* generated dialogue that invents facts;
* voice that changes a character’s age, tone, or relationship;
* modern traffic, electronic cues, brands, or anachronistic sound;
* music that turns ordinary work into danger or melodrama;
* captions that are wrong, mistimed, inaccessible, or visually obstructive.

### Gate 7 pass

The sound package agrees with picture, script, setting, rights, accessibility,
and the intended calm tone.

**Handoff to edit:** locked voice/audio revisions, track map, caption draft,
rights record, mix notes, and shot-specific sound cues.

---

## Stage 8 — Editorial Assembly And Picture/Sound Lock

### Objective

Build the episode viewers will actually experience and verify that individual
approved assets still tell one continuous story.

### Procedure

1. Assemble only selected/approved assets into the working sequence.
2. Check every cut against the state ledger: position, direction, wardrobe,
   object state, weather, light, route, task progression, emotion, and sound
   source.
3. Maintain the intended visual rhythm. Use wide, medium, close, and detail
   shots because each changes viewer knowledge, not as a mechanical pattern.
4. Preserve process where it is meaningful; compress repeated work.
5. Check 9:16 and 16:9 delivery versions as their own experiences.
6. Time dialogue, ambience, ASMR, music, silence, captions, and transitions
   against final picture.
7. Produce a review export identified by episode revision.

### Editing rules

* Do not mask a broken asset with a rapid cut, crop, blur, dissolve, music
  swell, or captions.
* A clip approved in isolation can be rejected if it breaks its neighbors.
* A late visual replacement requires rechecking captions, sound timing,
  thumbnail truth, metadata, and release assets affected by it.
* Do not manufacture runtime by looping a flow clip or holding empty
  atmosphere after its meaning ends.

### Gate 8 pass

The rough cut delivers the approved hook, practical progression, emotional
rest, truthful sound, readable picture, and factual continuity as one
experience.

**Handoff to QA:** identified rough-cut/master revision, edit decision list,
continuity ledger, selected-asset register, captions, sound plan, package
draft, and all current issue records.

---

## Stage 9 — Episode QA And Release Approval

### Objective

Independently confirm the actual complete episode, not merely its assets, is
ready to become a public promise.

### Review sequence

1. Watch once without stopping as the intended viewer.
2. Review against script, boards, canon packet, state ledger, and selected
   asset records.
3. Review all transitions and cross-shot dependencies.
4. Review sound, captions, accessibility, rights, and delivery technicals.
5. Review thumbnail, title, description, chapters, playlist, cards, end
   screens, and any continuation statement against the locked episode.

### QA gates

| Gate | Pass condition |
| --- | --- |
| Story and viewer promise | Hook, action, response, and ending are truthful, clear, proportionate, and complete. |
| Canon and continuity | People, place, period, objects, weather, geography, and cross-episode facts remain correct. |
| Picture and Flow | Generated shots preserve frame-one integrity, motion, camera, identity, and end handoff. |
| Sound and accessibility | Audio is grounded; captions are correct; rights and language fields are complete. |
| Delivery | Master, ratio, resolution, captions, thumbnail crop, and technical export are correct. |
| Packaging | Title, thumbnail, metadata, chapters, links, and opening make the same actual promise. |

Classify findings as blocker, major, minor, or observation. A blocker or major
finding returns only the affected material to the earliest responsible stage,
then requires the documented dependency recheck. Quality approval does not
permit a hidden waiver.

### Gate 9 pass

Quality Lead issues an identified release decision for the exact master,
thumbnail, captions, metadata, and waiver state.

**Handoff to release:** release-approved master ID, thumbnail, metadata,
captions, rights/credits, platform fields, QA authorization, and archive
manifest.

---

## Stage 10 — Publishing And Public Verification

### Objective

Upload and verify only the approved release package under
`08_Production/15_Publishing_Workflow.md`.

### Procedure

1. Confirm that master, thumbnail, metadata, captions, credits, audience,
   rights, links, playlist, cards, and end screens refer to the same approved
   revision.
2. Upload privately first. Never use an alternate master or test thumbnail in a
   viewer-accessible state.
3. Verify duration, processing, caption timing, thumbnail, title, description,
   chapters, language, cards, end screen, and beginning/middle/end playback.
4. Schedule or publish only after private verification passes.
5. Preserve the public URL, exact fields, published timestamp, and release
   state in the release record.

### Gate 10 pass

The public episode is the quality-approved episode and the platform presentation
does not make a stronger, different, or misleading promise.

---

## Stage 11 — Archive And Post-Release Learning

### Archive package

At picture lock, sound lock, and release, preserve:

* approved premise, script, boards, animatic, scene ledger, and source manifest;
* prompt revisions, reference roles, stills, Flow inputs, candidates, settings,
  selected assets, and decision records;
* voice, audio, caption, rights, edit, master, thumbnail, and metadata files;
* QA issues, approvals, waivers, release decision, and public verification;
* managed-storage links, archive locations, and superseded/rejected history.

Google Flow project history is not a durable archive. Export selected media and
record available generation information outside the platform.

### Post-release learning

Review public performance only at a planned interval and only with context.
Analytics may reveal clarity, packaging, pace, or audience-fit questions; they
do not revise canon or turn a trending tactic into series doctrine.

Classify outcomes as:

* public correction;
* episode-process improvement;
* research/canon question; or
* future creative observation.

Record evidence, decision, owner, affected future stage, and whether a present
release correction is required. Do not alter the original release archive
silently.

---

## Revision And Return Loops

Use `16_Revision_Workflow.md` whenever a candidate or selected asset fails.

```text
Finding
↓
Freeze exact baseline and evidence
↓
Classify defect and locate earliest responsible stage
↓
Approve smallest-change hypothesis
↓
Generate/revise one controlled variable group
↓
Review against locks, adjacent shots, and delivery
↓
Approve, select, redesign, or return on hold
↓
Archive and hand off exact revision
```

Common returns:

| Finding | Return to |
| --- | --- |
| Unsupported fact or contradictory source | Canon, research, or continuity owner |
| Weak premise, false hook, wrong emotional scale | Story/Episode planning |
| Multiple actions, impossible endpoint, camera line unknown | Storyboard and state ledger |
| Wrong frame-one identity/location/prop | Still-image asset packet |
| Correct start but Flow drift | Flow motion contract or shorter/simpler shot |
| Correct asset but poor crop or cut | Board delivery design or edit |
| Invented/mismatched voice or sound | Script and sound plan |
| Packaging does not match final episode | Metadata/thumbnail ownership |

Never reroll blindly. Never extend a drifting Flow clip. Never ask a prompt to
solve a missing story decision.

---

## Handoff Contract

Every stage handoff must identify:

```text
From / to:
Episode, scene, shot, and revision:
Current status:
Deliverable paths or stable storage links:
Source manifest and applied locks:
Approval and reviewer:
What changed since prior handoff:
Incoming/outgoing continuity state:
Required next action and decision:
Known limits, risks, OPEN facts, and dependencies:
Receipt confirmation:
```

The sender retains responsibility until the receiving owner confirms the
deliverable is readable, complete, and fit for the next stage. “The latest
files” is not a valid handoff.

---

## Worked Pipeline Examples

### Short: Daughter gathers a leaf after rain

**Story:** A fallen mango leaf is wet enough to be useful for a small household
task. The truthful opening shows the leaf and Daughter noticing it; no danger is
implied.

**Board:** A central 9:16 medium view keeps Daughter, basket, and leaf visible.
The state ledger says basket left hand, leaf at her right, damp garden, soft
overcast light. Document 19 locks the camera side; Document 20 selects locked
camera.

**Assets:** Generate an approved start still, then one-image Flow. The one
motion contract is: she picks up the leaf with her right hand while nearby
banana leaves respond lightly to residual breeze. End before she puts it in the
basket if that placement is not needed.

**Sound/edit:** Soft wet-leaf rustle and garden ambience; no generated dialogue
needed. Captions remain clear of her hands. The Short ends on her quiet
observation or the next factual action, not a baited cliffhanger.

### Long form: Rain affects the cooking fire

**Story:** Damp fuel makes Mother’s usual cooking routine slower. The family
uses patient, plausible household care rather than a “storm emergency.”

**Plan:** Long form can show the damp wood, Mother’s careful adjustment, a
Father contribution supported by his character and location, an insert of the
fire, rain ambience, and a calm meal-rest image. Every scene advances process,
relationship, weather consequence, or resolution.

**Generation:** The kitchen is locked to its documented layout and west-side
geography; light/weather ledger controls the overcast day. Close prop inserts
protect firewood state and hand contact. Flow shots use M1–M3 only, with calm
camera movement only if the board needs a reveal or follow.

**QA:** Verify wetness, fire condition, clothing, object state, sound source,
captions, and that the title/thumbnail describe rainy-day cooking rather than
an emergency.

---

## Edge Cases

### One production package serves both formats

Use shared story facts and asset registers, but create format-specific boards,
camera directions, stills, and/or edits when required. A crop-safe claim is
not evidence that an action remains readable in both aspect ratios.

### A recurring reference asset becomes outdated

Do not silently swap it inside active packets. Mark the reference status,
evaluate affected episodes and prompts, obtain the required character/canon
approval, version the reference, and recheck dependent assets.

### A tool control disappears after boards are approved

Confirm the current Flow limitation and select a safe supported strategy: still
hold, shorter motion, one-image clip, cut, or board redesign. Record the
limitation. Do not force an unsupported two-frame or extension workflow.

### A beautiful candidate changes a core fact

Reject it. Visual appeal does not compensate for changed identity, period,
location, object, weather, camera line, or story state.

### A post-lock replacement affects a release-ready episode

Treat it as a new revision. Recheck adjacent cuts, audio timing, captions,
thumbnail, metadata, QA authorization, and release package before publishing.

---

## Final Standard

An episode is production-complete only when its journey can be reconstructed:

* What source-backed premise began it?
* Which locks and references governed every shot?
* Which script, board, prompt, still, Flow clip, voice, audio, and edit revision
  was selected?
* How did each scene hand off its factual state?
* Which quality gates passed, and who approved them?
* What exact master, thumbnail, captions, and metadata became public?
* Where are the archive and any later correction record?

If the team cannot answer those questions, the episode has not completed the
pipeline, regardless of how polished its images appear.
