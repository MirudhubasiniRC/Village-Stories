# Master AI Asset Workflow

## Purpose

This manual is the operating authority for converting an approved Village Stories
episode and scene plan into traceable, reusable, canon-safe AI assets.

It governs the lifecycle of a still image, keyframe, Google Flow clip, repair
generation, selected take, and archived production record from the moment a
scene is approved until its final asset package is preserved.

It is deliberately practical. It tells a production team what to prepare, what
to decide, what to generate, what to reject, what to record, and when to stop.

It does not create story canon, alter character designs, decide a location
layout, or authorize a release. Those decisions remain with their owning
documents and production gates.

---

## Guiding Principle

> Use AI to reproduce a carefully known world—not to invent a different world
> every time a scene is generated.

The correct asset is not the most spectacular result. It is the result that
faithfully serves one approved story moment, connects cleanly to its neighbours,
and remains recognizable as Village Stories without an explanation.

---

## Production Philosophy

Village Stories is a persistent, early–mid-1990s rural Tamil Nadu world.
Ordinary life, natural time, family care, weather, craftsmanship, and community
are the subject—not decorative background for an AI showcase.

AI is a bounded production tool. It may generate controlled visual candidates,
but it must not decide:

* what a character looks like, knows, or would do;
* where a familiar place is located or how it is arranged;
* which period object is appropriate;
* whether a story event, emotion, sound, or transition is truthful;
* which candidate is safe to use because it merely looks attractive.

Continuity is more valuable than novelty. A calm, clear, correct shot is more
valuable than a visually impressive shot that changes the village.

---

## Objectives

This workflow must:

1. turn every approved shot into a bounded, reviewable generation task;
2. protect canon, historical accuracy, and continuity before generation;
3. preserve the original premium cinematic anime identity of the series;
4. make Google Flow animation a controlled continuation of approved imagery;
5. ensure each selected output has a known purpose, state, owner, revision,
   source, and approval;
6. detect errors before an asset enters the edit;
7. make revisions diagnostic rather than random;
8. preserve enough history to reproduce, audit, replace, or safely retire an
   asset later; and
9. support truthful YouTube viewing on mobile, in Shorts, and in long-form
   episodes.

---

## Scope and Boundaries

This document applies to:

* still-image generation for boards, keyframes, inserts, thumbnails, and repair;
* prompt module selection and assembly;
* reference-image selection;
* one-image and two-image Google Flow decisions;
* Google Flow animation, extensions, candidate review, and exports;
* shot-level continuity recording;
* naming, versioning, selection, handoff, and archive records.

This document does not replace:

* `06_Story_Engine/` for premise, emotional truth, and story doctrine;
* `07_Episode_System/` for episode form, scene purpose, pacing, hook, opening,
  ending, education, ASMR, music, visual rhythm, Shorts, and long form;
* `08_Production/` for storyboard, editing, sound, release, file, version, and
  quality-control procedures;
* `01_Canon/`, World, Character, Object, and Research documents for facts.

---

## Authority and Conflict Resolution

Prompts inherit authority. Generated output has the lowest authority in the
chain.

```text
Current approved user or production decision
↓
01_Canon/ — global rules, timeline, continuity, style locks
↓
02_World/ · 03_Characters/ · 04_Objects/ · 05_Research/
↓
06_Story_Engine/ — story boundaries and emotional truth
↓
Approved episode brief, storyboard, and scene state ledger
↓
07_Episode_System/ — viewer-facing episode construction
↓
08_Production/ — execution, file, version, QA, and release controls
↓
09_AI_Production_System/ — reusable prompt and AI asset controls
↓
Prompt, reference set, tool settings, candidate, and selected output
```

When two instructions conflict:

1. Identify the fact or decision in dispute.
2. Locate the highest applicable source.
3. Follow that source.
4. Record the conflict in the shot or issue record.
5. Return the asset to the owning stage if a storyboard or prompt must change.

Do not solve a conflict by averaging instructions, silently changing a prompt,
cropping away evidence, or treating a generated image as proof that a new fact
is acceptable.

If a required fact is absent, mark it `OPEN`, assign an owner, and pause the
affected recurring or continuity-critical generation. Do not invent permanent
facts for convenience.

---

## Non-Negotiable Series Locks

Every generation must preserve the following baseline unless a higher approved
source deliberately states otherwise.

### Time and place

* The world is early–mid-1990s rural Tamil Nadu.
* The exact calendar year is intentionally flexible; the period is not.
* Seasons are Summer, Monsoon, or Post-Monsoon / Harvest.
* Every episode belongs to one defined season.
* Geography, routes, house orientation, landmarks, weather consequences, and
  time passage remain continuous.
* Modern technology, contemporary fashion, modern vehicles, branded packaging,
  LED fixtures, current appliances, urban signage, and plastic-dominant dressing
  are rejected unless an authoritative source explicitly permits them.

### Family identity

The principal family is:

* Mother;
* Father;
* Elder Brother;
* Younger Daughter; and
* the German Shepherd Family Dog.

Use a family member only when the story, task, relationship, and individual
character packet support that presence. Never add the full family merely to
make a frame feel busy.

Prominent recurring people require their approved visual references. Preserve
face, age, build, South Indian features, skin tone, hair, clothing logic,
posture, habits, emotion, relationship behavior, and relative scale.

The Family Dog is a gentle, loyal household companion. It may wait, follow,
observe, rest, react softly to an unusual sound, or play naturally with the
children. It must never be framed as a police, military, attack, rescue, or
threatening dog device.

### Style identity

Use the original Village Stories premium cinematic anime style:

* semi-realistic anime characters with natural South Indian features;
* soft painterly, hand-painted digital rendering;
* refined organic linework only where it aids clarity;
* gentle global illumination, natural colour, and atmospheric depth;
* detailed, culturally specific rural environments;
* believable anatomy, subtle expression, and warm slice-of-life feeling.

Reject heavy cel shading, chibi proportions, comic outlines, plastic CGI,
hyper-real faces, glossy synthetic textures, vector-flat imagery, generic
low-detail anime, named-studio imitation language, and artificial perfection.

### Camera and motion identity

The camera is an observer. It witnesses life at plausible human viewpoints.

Prefer static observation, gentle push-ins, slow pull-backs, slow pans, gentle
tracking, and restrained crane movement only when the board requires them.
Avoid whip pans, fast zooms, shake, drone-like travel, orbiting, action-camera
behavior, and movement whose only purpose is spectacle.

Motion is natural, physically grounded, and emotionally proportionate. It has
weight, acceleration, pause, and consequence. Stillness is valid.

---

## Roles and Accountabilities

### Episode Director

Owns the intended scene meaning, performance level, and final creative choice.
Approves a changed shot intention before it is generated.

### Canon and Continuity Lead

Provides source authority, approves lock selection, maintains the state ledger,
blocks factual drift, and determines whether an issue requires regeneration,
storyboard revision, or canon escalation.

### Storyboard Artist or Shot Designer

Supplies the shot purpose, framing, start state, end state, action boundary,
camera side, screen direction, cut logic, and delivery use.

### Prompt Lead

Builds fact sheets, selects approved modules and references, writes prompts,
records prompt revisions, and ensures every instruction is traceable.

### Image Generator Operator

Runs deliberate still-image variants, preserves tool and reference records, and
does not alter an approved visual plan without return approval.

### Google Flow Operator

Creates controlled Flow tasks, uses only approved inputs, records available
tool configuration, produces bounded candidate clips, and exports correctly
identified assets.

### Editor

Tests a candidate in delivery framing and beside adjacent shots. The Editor
checks cut points, handles, crop safety, rhythm, caption space, and whether an
asset genuinely serves the edit.

### Quality Lead or Reviewer

Runs independent evidence-based checks, records severity and required remedy,
and approves or rejects the exact revision under review.

No person may approve their own unresolved defect.

---

## Required Inputs

Do not begin a production generation task until these inputs exist and are
identifiable:

* approved episode ID, format, working title, owner, and current revision;
* approved premise and locked scene plan;
* storyboard panel and stable scene/shot ID;
* scene card and state ledger entry;
* selected season, time of day, weather, and world state;
* relevant character, location, object, research, and style sources;
* approved reusable references and their status;
* prior-shot end state and next-shot required handoff;
* output use, aspect ratio, duration range, and caption/overlay needs;
* one visible primary action or held moment;
* camera size, side, height, screen direction, and movement intent;
* sound decision: natural sound, restrained music support, or intentional quiet;
* known risks and unresolved questions.

For Google Flow, also require:

* an approved start keyframe;
* an approved end keyframe when the endpoint must match exactly and current
  Flow controls support two-image input;
* a declared reference role for every uploaded image; and
* a bounded motion contract.

---

## Required Working Records

### Episode reference manifest

Before generation, the episode must identify every material source:

```text
Episode ID:
Working title / format:
Source path:
Source heading:
Fact used:
Production implication:
Approved reference asset:
Open question / owner:
Last reconciled date:
```

### Scene state ledger

The scene ledger bridges approved story intent and repeatable generation. Record:

```text
Scene and shot ID:
Purpose and intended duration:
Location and spatial orientation:
Season / time / weather / light direction:
Characters present and current state:
Wardrobe, hair, physical condition, and emotion:
Object owner, position, orientation, amount, and condition:
Start state:
One primary action:
Required visible change:
End state:
Camera and screen direction:
Sound plan:
Required opening state for next shot:
```

### Shot fact sheet

Build this before writing any final prompt:

```text
Shot ID / current revision:
Output use and aspect ratio:
Shot purpose:
Single frame moment or motion contract:
Approved character locks:
Approved location locks:
Approved object locks:
Style and camera locks:
Time / weather / lighting locks:
Prior-shot continuity facts:
Next-shot continuity facts:
Reference assets and declared roles:
Known failure risks:
Prompt version:
```

Unknown facts must remain explicitly marked `OPEN`; they must not be disguised
as expressive language such as “traditional,” “beautiful,” or “cinematic.”

---

## The Complete Master Workflow

### Phase 0 — Receive an approved production handoff

1. Confirm that the episode and scene plan are approved for production.
2. Verify the episode ID, scene ID, shot ID, format, owner, and working
   revision.
3. Read the scene card rather than relying only on a visual board image.
4. Identify the scene’s primary visible change and emotional movement.
5. Confirm the start state, required end state, and transition to the next shot.
6. Return the handoff if it lacks a reason for the scene, a factual start state,
   a one-action shot plan, or the canon sources it needs.

**Output:** a generation-ready shot brief or a documented return to story,
storyboard, research, or canon clarification.

### Phase 1 — Assemble the canon packet

1. Select only the sources that materially constrain this shot.
2. Extract the applied facts, not whole copied documents.
3. Identify character identity, present clothing, body language, and relationships.
4. Identify location sub-area, fixed features, routes, and usable camera geography.
5. Identify story props, material, count, owner, hand, condition, and endpoint.
6. Confirm seasonal, weather, plant, water, ground, animal, and light behavior.
7. Confirm early-1990s material culture and likely modern contamination risks.
8. Record each source path and heading in the reference manifest.

Do not create a second, competing canon file inside an episode workspace. The
episode record states how an existing authority is applied.

**Output:** source-backed shot fact sheet with no unresolved recurring facts.

### Phase 2 — Select canon locks

Select a lock only when it protects a fact visible in the shot or required by
its continuity handoff. The lock system is selective, not a demand to repeat
the entire series bible in every prompt.

| Lock type | Select when | Minimum protected fact |
| --- | --- | --- |
| Series style | Every visual asset | Original painterly cinematic anime identity |
| Character | A recurring person is prominent | Approved face, build, clothing, behavior |
| Family Dog | The dog is visible | German Shepherd identity and gentle companion behavior |
| Location | Documented architecture or geography is visible | Sub-area, fixed features, orientation |
| Object | An object carries story evidence | Material, count, state, owner, placement |
| Time/weather | Visible or continuity-critical | Season, sky, wetness, light direction |
| Camera | Every shot | Framing, side, height, focal subject, screen direction |
| Transition | Prior/next shot depends on it | Exact start or end fact |
| Delivery | Shorts, long form, thumbnail, or caption use | Ratio, mobile readability, safe space |

If a lock conflicts with the board, the board must be reviewed. Do not weaken
the lock simply to make a prompt shorter.

**Output:** declared lock list and reference set.

### Phase 3 — Choose the asset strategy

Select the smallest asset type that can deliver the shot’s purpose.

| Need | Preferred strategy |
| --- | --- |
| Stable visual idea, board, insert, thumbnail, or repair | Still image |
| One short action continuing a clear visual state | Start-frame-led Flow animation |
| Exact visual handoff at both beginning and end | Two-image Flow animation, if supported |
| Quiet non-recurring atmosphere | Text-led or reference-led atmosphere generation, then review |
| A complicated process, dialogue, or multi-person sequence | Split into multiple shots or return to board |

Do not generate motion merely because a still could communicate the needed
moment more reliably.

**Output:** asset type and rationale recorded on the shot fact sheet.

### Phase 4 — Make the one-image or two-image decision

Use one image when the approved start state carries enough identity and the
shot has one simple, internally controlled change.

Good one-image cases:

* a fixed wide view with leaves, steam, rain, smoke, or cloth moving gently;
* Mother placing one known object while its destination is visible;
* Father taking one or two steps with no required matched endpoint;
* Younger Daughter noticing an object and making a small reaction;
* the Family Dog shifting its paws and looking toward a familiar doorway.

Use two images only when an approved end state is genuinely needed and the
current Flow mode supports first- and last-frame control reliably.

Good two-image cases:

* a brass tumbler must move from Mother’s hand to one exact shelf position;
* a leaf must finish above a basket to match the next shot;
* a gaze or handoff must land on a documented next-frame composition;
* a matched transition requires the outgoing and incoming composition to agree;
* a controlled object state is more important than free-flowing motion.

Do not use two images:

* to force a complex multi-stage action through an unsupported tool behavior;
* when the end frame differs in camera, location, time, or action scale;
* when either image is not already approved;
* to conceal an unclear storyboard endpoint.

Decision test:

```text
Can the editor safely cut from a naturally generated end state?
  Yes → one image is normally sufficient.
  No  → use two images if Flow supports it, or redesign the shot.
```

**Output:** `one_image`, `two_image`, or `redesign` strategy recorded with reason.

### Phase 5 — Assemble the prompt modules

Separate permanent information from scene-specific information.

**Permanent modules**

* series art style;
* character identity and behavior;
* location layout;
* recurring object identity;
* camera language;
* period exclusions;
* Flow preservation language.

**Scene modules**

* output intent;
* current action or held moment;
* present wardrobe and emotion;
* time, season, weather, and lighting;
* prop ownership and state;
* framing and safe space;
* start and end continuity facts;
* limited motion instructions.

Assemble modules in this order:

```text
1. Output and delivery intent
2. Subject and approved identity
3. One visible action or held moment
4. Documented location and spatial relation
5. Time, season, weather, and physically motivated light
6. Camera and composition
7. Original Village Stories art direction
8. Period materials and environment anchors
9. Continuity constraints
10. Targeted exclusions
```

Each instruction must have an owner. If an instruction cannot be traced to the
board, ledger, or canon packet, remove it or escalate it.

**Output:** prompt draft where every module has a job.

### Phase 6 — Write the still-image prompt

Write one image request, not a compressed episode synopsis.

Start with who is doing what, where, when, and from what viewpoint. Add only
the material, style, and continuity facts needed to make that frame reliable.

Use observable directions:

* “Father holds the rope in his left hand, before tying it.”
* “soft overcast monsoon daylight enters through the east-facing window.”
* “medium side view at seated eye level; hands and stove are focal.”

Avoid vague directions:

* “make it nostalgic and beautiful”;
* “a lively traditional village scene”;
* “cinematic masterpiece with magical energy.”

Still-image template:

```text
[Output use, aspect ratio, and shot ID.]

[Approved subject] matching [approved reference], [one visible held moment or action].
[Current clothing, posture, expression, and hand/prop facts.]

At [documented location and sub-area], [relationship to fixed location features].
[Relevant prop material, count, position, and condition.]

[Season, time, weather, light source, direction, shadows, and physical effects.]

[Shot size, camera position and height, screen direction, focal hierarchy,
depth, and protected caption or crop space.]

Original Village Stories hand-painted animated-film identity: soft painterly
digital rendering, natural South Indian features, believable anatomy, fine
organic linework, warm natural cinematic light, atmospheric depth, and detailed
early-1990s rural Tamil Nadu materials.

[Prior-shot and next-shot continuity constraints.]

Avoid: [specific likely drift].
```

**Output:** reviewable still prompt and approved source-reference list.

### Phase 7 — Preflight the prompt and references

Before generating, check:

* The shot ID, revision, ratio, and intended use are correct.
* The prompt has one readable main action.
* Prominent recurring people have approved character references.
* Visible fixed architecture has a location reference.
* A story prop has a reference when identity or state matters.
* References have declared roles and do not compete unnecessarily.
* The prompt preserves the exact prior-shot handoff.
* The planned end state supports the next shot.
* Lighting obeys the permanent sun orientation: east morning light, west evening
  light, and no reversed shadows.
* Exclusions target actual risk rather than becoming a random wall of negatives.
* The delivery composition works at the intended crop.

Use the minimum reference set that establishes the required identity. Too many
unrelated “inspiration” images weaken the instruction hierarchy.

**Quality gate:** no generation until the Prompt Lead and Continuity Lead can
identify the single action, required locks, permitted changes, and protected
facts.

### Phase 8 — Generate controlled still candidates

Generate a small purposeful batch. Keep the facts fixed.

Within one batch, vary only one tested group:

* composition;
* gesture;
* light balance;
* object placement;
* environmental density; or
* crop tolerance.

Never vary identity, location, period, action, and camera simultaneously. That
does not produce useful learning or a reliable choice.

Label every output as `candidate` until it passes review. A downloaded image is
not an approved asset and must not be used as an animation reference by default.

**Output:** identified candidates linked to prompt revision, references, tool,
mode, and available generation settings.

### Phase 9 — Review and select the still

Review at full resolution, at delivery crop, at ordinary mobile size, and beside
the relevant adjacent shots.

Review in this order:

1. Canon and historical facts.
2. Recurring character identity and dignity.
3. Location, geography, object material, and period.
4. Start/end continuity facts.
5. Anatomy, hands, tool contact, object count, and artifacts.
6. Camera, composition, caption safety, and delivery readability.
7. Style and emotional truth.
8. Animation readiness, where the still will become a Flow input.

Select a still only when it fulfills its designated purpose. A beautiful
alternative composition is not a substitute for the planned shot.

**Quality gate:** reject any still with a wrong core character, period detail,
location, story prop, central action, or incompatible handoff. Do not plan to
hide a central contradiction in crop, blur, or fast editing.

### Phase 10 — Prepare the Google Flow task

Before opening the task, confirm the currently available Flow interface:

* generation modes and model options;
* supported aspect ratios and resolution;
* duration choices;
* reference or ingredient behavior;
* first-frame and last-frame controls;
* extension or edit capability;
* audio behavior;
* project-history and download limitations.

The exact interface may change; production discipline does not.

Create one Flow project per episode or deliberately bounded sequence:

```text
EP###_ShortTitle_Flow
```

Name the generation task:

```text
EP###_S##_SH###_Action_R##
```

Example:

```text
EP014_S02_SH006_DaughterPicksLeaf_R01
```

Attach only approved references, in priority order:

1. selected start frame;
2. prominent recurring character reference;
3. location reference when architecture matters;
4. prop reference when story evidence matters;
5. approved end frame only for a necessary supported two-image task.

**Output:** named Flow task with declared references and the selected strategy.

### Phase 11 — Write the Google Flow motion contract

Restate the shot in a single sentence:

> From this approved start state, [subject] performs [one action] while the
> camera [one behavior], ending when [observable end state].

If the sentence contains multiple actions, multiple camera moves, or more than
one “while,” divide the board into smaller shots.

Classify motion before prompting:

* `M1` — environment only;
* `M2` — one body or hand action;
* `M3` — one person plus one supporting environmental response;
* `M4` — multiple subjects or stages; redesign before generation.

Village Stories normally uses M1 through M3.

Use this motion prompt architecture:

```text
1. Preserve the approved frame and locks.
2. State one subject action with pace and physical behavior.
3. State one restrained camera behavior.
4. State only supporting environmental movement.
5. State the usable end state.
6. Exclude likely drift.
```

Motion template:

```text
Preserve the approved [character, location, object] identity, current wardrobe,
prop state, lighting, composition, original painterly Village Stories style,
and early-1990s rural Tamil Nadu setting.

[Subject] [one physically clear action], [pace and emotional quality].

[One camera instruction.]

[Only necessary environmental motion.]

End with [precise observable end state].

No [identity drift, added actors, prop or wardrobe change, anatomy errors, text,
modern detail, dramatic weather shift, or excessive camera movement].
```

**Output:** approved Flow prompt with a bounded beginning and endpoint.

### Phase 12 — Generate controlled Flow candidates

Generate enough candidates to assess the same shot plan; do not rewrite the
story while evaluating the first batch.

Set duration to the shortest interval that includes:

* a readable start;
* the planned action;
* a usable end state or cut point.

Generate extra duration only when the editor needs a deliberate settle, overlap,
or atmosphere hold. Do not lengthen a calm shot to manufacture runtime.

For each candidate, inspect:

* identity stability;
* hands, face, feet, and body mechanics;
* object ownership, material, count, orientation, and state;
* location preservation and period accuracy;
* camera behavior;
* motion speed and weight;
* frame-one integrity;
* usable first and final frames;
* crop and caption safety;
* unexpected text, logos, watermarks, audio, or modern contamination.

**Output:** candidate clips with tool/project reference, prompt revision,
reference set, aspect ratio, duration, candidate ID, and observed defects.

### Phase 13 — Diagnose before revising

Never reroll blindly. Classify the failure first.

| Failure | Likely cause | Required correction |
| --- | --- | --- |
| Wrong identity at frame one | Bad or missing still/reference | Repair through image workflow |
| Face, hair, body, clothing drifts in motion | Too much motion, weak identity input | Strengthen approved reference, shorten, simplify |
| Object changes hands, count, material, or fill | Unclear prop contract | Specify owner, hand, state, and endpoint; use insert if needed |
| Architecture or period drifts | Weak location anchor or broad request | Use location reference and targeted period exclusions |
| Camera moves too much | Too much action or vague camera language | Lock camera or simplify action |
| Motion is robotic, floating, or abrupt | Action scope or pace is too vague | Reduce action and specify natural pace/end condition |
| End state is unusable | Endpoint is unclear or too ambitious | State exact endpoint, use two images, or split shot |
| Vertical crop loses the action | Horizontal-first composition | Regenerate in 9:16 with central action |
| Generated audio invents facts | Tool behavior exceeds approved sound plan | Mute/remove; use approved post-production sound |

Change one responsible variable per revision and log it:

```text
R02: shortened the hand action; camera remains fixed.
R03: added approved brass-tumbler reference; no other prompt change.
R04: revised end state from “places leaf” to “holds leaf above basket.”
```

**Output:** a testable revision hypothesis, never an unexplained reroll.

### Phase 14 — Revise or redesign

Use the smallest change that addresses the diagnosed cause.

Revise the input image when the error is visible before animation starts.
Revise the motion prompt when the start is correct but movement fails.
Revise references when a lock is insufficiently represented.
Revise the storyboard when the tool is being asked for too many actions,
characters, states, or camera changes.

Return to a higher stage when:

* a canon fact is unknown or contradictory;
* the scene has no clear action or handoff;
* a two-image endpoint cannot be logically reached;
* a complicated process needs several shots;
* the desired result depends on a tool capability that is unavailable;
* a requested visual change would establish a new permanent fact.

Use Flow extension only when the existing clip ends in a stable, correct state
and the same action naturally continues. An extension is not a cure for drift,
a broken endpoint, a changed camera, or a new beat.

**Output:** revised candidate, redesigned shot, or documented escalation.

### Phase 15 — Approve the selected asset

An asset is approved only for its stated use. Approval for a keyframe does not
automatically approve it as a thumbnail, a different crop, or a later episode
reference.

Record:

```text
Asset ID and revision:
Episode / scene / shot:
Asset type and intended use:
Prompt text or stable prompt reference:
Input references and their approved status:
Tool, model, mode, and settings available:
Generation date:
Candidate identifier:
Selected output identifier:
Reviewer and decision date:
Known limitations:
Continuity start and end state:
Downstream animation or edit use:
```

Approval decision meanings:

* `approved` — accepted for the recorded purpose;
* `selected` — chosen from approved assets for a named edit;
* `locked` — frozen at a declared milestone;
* `rejected` — unsuitable and not reusable;
* `superseded` — preserved history, not current;
* `retired` — deliberately invalid for future use.

**Quality gate:** an asset must be reviewed as part of its sequence, not only in
isolation. Verify the preceding entry state and next-shot handoff.

### Phase 16 — Name, version, and hand off

Use the naming pattern from `08_Production/16_File_Organization.md`:

```text
[episode_id]_[scene_or_shot]_[asset_type]_[subject]_[status]_[revision].[extension]
```

Examples:

```text
ep_012_sc_03_sh_04_image_mother_stove_candidate_r02.png
ep_012_sc_03_sh_04_prompt_firewood_approved_r03.md
ep_012_sc_03_sh_04_video_mother_stove_selected_r03.mp4
```

Use fixed-width identifiers: `ep_012`, `sc_03`, `sh_004`, `r03`.
Use lowercase ASCII letters, numerals, underscores, and hyphens.

Never use `final`, `final_final`, `latest`, `new`, `use_this_one`, a date alone,
or an unqualified platform ID as the primary production name.

Every handoff must state:

1. exact deliverable path or stable storage link;
2. status and revision;
3. source and prompt references;
4. requested decision or next use;
5. recipient;
6. known risks, limitations, or open questions.

The sender retains responsibility until the recipient confirms receipt and
fitness for the next stage.

### Phase 17 — Archive and preserve history

Archive selected AI assets outside the transient tool interface. Google Flow is
a production environment, not the permanent source of truth.

At generation selection, picture lock, and release archive, preserve:

* prompt text and revision;
* reference manifest;
* approved input images;
* selected image and video exports;
* Flow project or generation identifier when available;
* model, mode, duration, ratio, and visible settings;
* defect and revision log;
* approval and selection record;
* continuity ledger;
* edit/master relationship;
* superseded assets and reason;
* any platform limitation affecting reproducibility.

Never overwrite the only approved asset. A better-looking regeneration is a new
candidate, not an automatic replacement.

For release-critical media, preserve editable source and approved deliverable,
with managed storage, an independent backup, and an archival or separately
governed recovery copy.

---

## Quality Gates Summary

### Gate A — Plan readiness

Pass only when the scene is approved, sourced, one-purpose, and has a recorded
start and end state.

### Gate B — Prompt readiness

Pass only when locks, references, one action, camera, delivery frame, and
targeted exclusions are known.

### Gate C — Still selection

Pass only when the image is canon-safe, readable, anatomically clean,
continuity-safe, and appropriate for its intended animation or edit use.

### Gate D — Flow readiness

Pass only when the one/two-image decision, motion contract, duration, output
ratio, references, and required endpoint are clear.

### Gate E — Generated asset review

Pass only when technical, canon, continuity, editorial, delivery, and emotional
checks all pass.

### Gate F — Sequence selection

Pass only when the asset is confirmed against adjacent clips and the continuity
ledger has been updated.

### Gate G — Archive completeness

Pass only when a future team member can identify what the asset is, which
decision it serves, how it was made, where its sources are, and whether it may
be reused.

Any blocker stops the affected gate. A scheduling need, a difficult rerun, or
an attractive visual does not convert a blocker into a pass.

---

## Positive Examples

### Positive: one-image Flow shot

The approved start frame shows Younger Daughter crouched in the Family House
front garden. Her basket is in her left hand and a fallen mango leaf lies at
her right. The clip needs only her to lift the leaf while nearby banana leaves
move slightly after rain.

This is one person, one clear hand action, one stable place, and a naturally
usable end state. Use one image and a fixed camera.

### Positive: two-image Flow shot

Mother must place a half-full brass tumbler on the documented kitchen shelf so
the next insert begins with the tumbler at that exact place. Both the held
start image and shelf end image are approved.

Use two images when supported, specify Mother’s hand, tumbler state, shelf
position, fixed camera, and the exact endpoint.

### Positive: period-safe atmospheric shot

A static Tea Stall wide shot shows the documented owner behind the counter,
period-appropriate bicycle placement, two background villagers waiting
naturally, and steam rising from the tea vessel.

The prompt protects the Tea Stall architecture and rejects signage, branded
packaging, motorcycles, modern café furniture, LEDs, text, and logos.

### Positive: dignified Family Dog beat

The German Shepherd rests outside the kitchen, shifts its paws, then looks
toward the doorway when a plausible ladle sound is heard. The camera stays low
and quiet; no person needs to enter.

The dog behaves as a familiar household companion rather than a scripted hero.

---

## Negative Examples

### Negative: a complete scene in one Flow request

“Mother cooks, Father returns home, the children run in, the dog barks, rain
begins, and the camera circles the house.”

This has several characters, actions, states, effects, and camera decisions.
Split it into the cooking action, arrival evidence, rain insert, reaction, and
any required transition.

### Negative: style replaces fact

“Beautiful cinematic anime Tamil village, masterpiece, cozy and nostalgic.”

It does not identify the documented location, people, task, object state,
period, camera, or continuity. Add factual modules before art direction.

### Negative: accepting spectacular drift

A clip has dramatic golden light and fluid movement but changes the Family House
kitchen into a tiled modern interior.

Reject it. The visual appeal does not compensate for a broken persistent world.

### Negative: using a two-image task to hide a bad board

The start image has Father in the fields at sunrise; the end image has him at
the house at dusk. The team attempts to force a “natural walk home.”

This is a location and time transition, not a single bounded action. Board the
route or use a meaningful editorial transition.

---

## Common Failures and Required Response

### Canon or historical contamination

Examples: phone, scooter, modern branding, LED strip, fashionable current
clothing, plastic-heavy kitchen, generic urban architecture.

Response: reject the asset; strengthen the period and location anchors; add
targeted exclusions; re-review background details at full resolution.

### Character replacement

Examples: different age, facial structure, body scale, hair, sari, emotion, or
uncharacteristic behavior.

Response: return to approved character reference and current continuity state.
Do not describe an archetype such as “rural mother” in place of Mother.

### Object-state mismatch

Examples: duplicated basket, tumbler gains a handle, tool changes material,
pot is unexpectedly empty, object moves hands.

Response: name count, owner, hand, orientation, condition, and endpoint.
Generate an insert or split the action if the contact is not reliable.

### Lighting and weather drift

Examples: rain appears with hard afternoon shadows, sun reverses direction,
wetness disappears between adjacent shots, firelight becomes electric light.

Response: return to the season and light ledger. State light source, direction,
weather result, shadows, and environmental consequence.

### Camera spectacle

Examples: orbiting Mother at the stove, rapid push-ins, shake, impossible aerial
views, a sweeping move that hides an object mismatch.

Response: lock the camera or choose one calm, story-motivated movement.

### Overloaded motion

Examples: several people act, animals cross, rain starts, cloth flies, and the
camera tracks in the same short clip.

Response: classify as M4 and redesign into smaller shots. Do not use retries to
make an overloaded instruction less visibly broken.

### Generated text or audio changes meaning

Examples: invented shop sign, label, narration, dialogue, or music cue creates
a fact or emotional claim not in the approved episode.

Response: remove or mute it. Add approved titles, captions, dialogue, and
sound in controlled post-production.

### Platform history is the only record

Response: export the selected asset and preserve the prompt, references,
settings, candidate identifier, approval, and continuity notes in the episode
record.

---

## Edge Cases

### A beautiful still has no motion potential

Use it as a still, insert, hold, thumbnail candidate, or replace it with a
motion-ready keyframe. Do not force animation on a crowded or unstable frame.

### The action is important but hands repeatedly fail

Simplify the action boundary, generate a stable wide or medium action shot,
then create a separate prop insert. Never accept impossible hand-tool contact
because the overall frame looks good.

### A keyframe is perfect but Flow changes it immediately

Shorten the clip, reduce movement, use a locked camera, reinforce references,
or choose an editorial hold. The keyframe remains valid; the animation strategy
does not.

### A two-image result reaches the end state unnaturally

The endpoint may be correct but the journey may not be usable. Split the action,
change the endpoint to an earlier stable state, or use a cut. Endpoint fidelity
does not excuse physically implausible motion.

### The scene requires many repeated process actions

Show the first action that teaches the process and a later action that proves
change. Bridge the repeated middle with a factual insert, sound, held image, or
transition rather than asking Flow for a long exact procedure.

### An approved asset is later found to conflict with canon

Mark it unavailable for downstream reuse, preserve it as a historical record,
open a new revision, assess every dependent shot and edit, and obtain the
required canon and continuity decision. Do not silently replace it.

### A tool control changes or disappears

Reconfirm the current Flow interface and apply this workflow’s intent:
approved inputs, one bounded action, restrained camera, precise review, and
durable record. Do not rely on an outdated interface tutorial.

---

## Google Flow Considerations

Google Flow should receive a clear action contract, not an entire screenplay.
Its best use in Village Stories is controlled motion that preserves an approved
visual state.

Before each production cycle, test the currently available controls with a
non-production sample if needed, then document observed behavior. Tool behavior
can vary by mode, model, reference support, duration, and platform revision.

Treat these capabilities as conditional:

* reference or ingredient influence;
* first- and last-frame matching;
* extension behavior;
* generated audio;
* exact duration;
* resolution;
* project retention;
* repeatability of a prior output.

Do not claim that an output is exactly reproducible unless the available tool
and recorded settings demonstrably support that claim.

Flow-specific safeguards:

* Use the selected start frame as the main visual authority.
* Attach the smallest relevant reference set.
* Use end frames only for real continuity needs.
* Keep camera fixed when hands, children, animals, or story props are active.
* Generate in the final delivery aspect ratio whenever practical.
* Inspect the first and final frames independently.
* Do not extend a clip that already drifts.
* Export candidates under their shot IDs immediately; do not rely on browser or
  project history alone.

---

## YouTube Considerations

### Shorts

For 9:16:

* keep faces, hands, and story props in the central vertical field;
* avoid placing the only narrative evidence at interface-prone top or bottom
  edges;
* reserve uncluttered space for captions only when the board calls for it;
* make the first visible beat understandable without sound;
* ensure the final frame supports a clean cut, hold, loop, or honest rest;
* do not use frantic motion to imitate retention tactics.

A Short hook must be a truthful visible condition: a task underway, a weather
change, a needed object, a child noticing something, or a practical action
starting. It must not imply danger, shock, or a larger event than the episode
contains.

### Long form

For 16:9:

* use width to establish geography and the relationship between people, place,
  and task;
* preserve a readable subject at phone size;
* vary shot scale only when visual meaning changes;
* leave time for natural sound, process, and emotional recognition;
* avoid repeated atmosphere shots that do not change knowledge or feeling.

### Thumbnails, captions, and generated text

Thumbnails must use a truthful episode moment and remain period-safe. They do
not authorize an alternate dramatic expression, object, weather state, or
event.

Generate the world without readable text, subtitles, logos, watermarks, or
packaging copy. Add all approved text in the edit. Caption safety must never
cover the hands, face, tool, or action that makes the shot understandable.

---

## Relationships With 06, 07, 08, and 09

### 06_Story_Engine

Story Engine decides what the episode means: its premise, character truth,
emotional boundary, proportionate obstacle, and reason for the action.

This workflow translates that approved meaning into one bounded visible asset.
It must return an unclear, melodramatic, unsupported, or multi-purpose scene to
the story and storyboard stages rather than invent visual solutions.

### 07_Episode_System

Episode System decides how viewers experience the episode: scene purpose,
hook, opening, ending, pacing, ASMR placement, music and silence, visual rhythm,
Shorts, long-form structure, and episode review.

This workflow uses the scene card and state ledger as its input. It does not
replace a scene’s visual cause and effect with prompt language. AI assets must
support the episode’s declared viewer promise and visual rhythm.

### 08_Production

Production controls the implementation context: storyboard workflow, image
prompt method, Google Flow procedure, animation, sound, post-production,
quality, file organization, version control, publishing, and release.

This workflow is the cross-stage master lifecycle for AI assets. Use it with:

* `08_Production/06_Image_Prompt_Workflow.md`;
* `08_Production/07_Google_Flow_Workflow.md`;
* `08_Production/14_Quality_Control.md`;
* `08_Production/16_File_Organization.md`; and
* `08_Production/17_Version_Control.md`.

When those documents prescribe a more specific implementation rule, follow that
rule and update this workflow only through the appropriate documentation review.

### 09_AI_Production_System

This document is the lifecycle umbrella for the AI production system.
Subsequent 09 documents should define reusable master prompts, prompt modules,
lock systems, Google Flow best practices, prompt QA, common failures, revision,
and episode pipeline detail without contradicting this authority chain.

---

## Continuity Rules at Every Asset Boundary

Before approving any asset, ask:

* Does the first frame match the prior shot’s final factual state?
* Does the last usable frame provide the next shot’s required state?
* Are character position, posture, gaze, walking direction, and screen direction
  preserved?
* Are wardrobe, hair, footwear, carried items, mud, wetness, and physical
  condition continuous?
* Are object owner, material, count, orientation, fill level, condition, and
  placement correct?
* Does the location retain its documented geometry, entry points, paths,
  furniture, trees, and landmarks?
* Do season, sky, rainfall, water level, ground condition, vegetation, smoke,
  steam, wind, and shadows belong to the same moment?
* Does emotion progress naturally from what the character has just experienced?
* Does sound, if present, have a plausible source and period fit?

No cut may contradict the recorded state without a visible or audible cause.
Do not use a dissolve, music swell, blur, or crop to conceal an impossible
change.

---

## Final Approval Standard

A prompt is ready when its factual inputs, locks, action, camera, delivery use,
and failure risks are explicit.

A still is approved when it is a correct, readable image for its exact purpose.

A Flow clip is approved when it is a faithful, editable continuation of the
approved input that performs one truthful motion without changing the village.

A selected asset is production-ready when its source, prompt, references,
revision, reviewer, start state, end state, technical file, intended use, and
archive location can be identified without guesswork.

If any of those statements is not true, the asset remains a candidate.

---

## Final Rule

Every image and movement should make the audience feel that they have returned
to the same village: the same family, paths, rooms, objects, seasons, light,
and quiet human rhythms.

The workflow succeeds when AI becomes invisible and Village Stories remains
believable.
