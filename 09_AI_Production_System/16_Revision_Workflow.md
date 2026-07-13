# Revision Workflow

## Permanent Purpose

This manual governs every correction to a Village Stories AI prompt, reference
set, still, Google Flow task, clip, audio candidate, selected asset, or
episode-generation record.

Its purpose is not to get more attractive outputs by repeated experimentation.
Its purpose is to identify why a bounded production result failed, preserve the
last known-good state, change the smallest responsible input, and make the
result safe to approve, edit, reuse, or archive.

> Diagnose the failure. Preserve what is correct. Change only what caused it.

This is the operating authority for AI-production revision discipline. It works
with, and never replaces, the authority of canon, story, episode, production,
quality-control, file-organization, version-control, and publishing manuals.

---

## Scope And Non-Scope

Use this workflow when:

* a prompt produces an incorrect candidate;
* a selected still or Flow clip must be repaired or replaced;
* a reference, keyframe, prompt module, camera instruction, or tool setting
  needs a material change;
* a late editorial, sound, QA, or publishing finding affects an AI asset;
* a previously approved asset is found to be inconsistent with canon;
* a production tool changes behavior and a controlled retest is necessary.

This workflow does not authorize:

* a new character, place, object, cultural claim, relationship fact, event, or
  permanent visual design;
* a change to story intent, scene purpose, performance, or pacing without the
  owning story or episode approval;
* a new camera direction or movement merely because a candidate is difficult;
* a release change without the required Quality Control and Publishing review;
* overwriting, deleting, or relabeling the only approved asset.

If the requested “revision” changes what the episode means or what is true in
the world, it is not a local prompt revision. Return it to the owning authority.

---

## Authority And Conflict Resolution

Generated output is evidence of tool behavior, not evidence that a fact is
permitted. Apply this precedence:

```text
Current approved production or release decision
↓
01_Canon/ — timeline, continuity, art style, and series locks
↓
02_World/ · 03_Characters/ · 04_Objects/ · 05_Research/
↓
06_Story_Engine/ — story truth and emotional limits
↓
Approved episode brief, script, storyboard, scene-state ledger
↓
07_Episode_System/ — form, pacing, openings, endings, sound, format
↓
08_Production/ — execution, versioning, QA, edit, publishing
↓
09_AI_Production_System/01_Master_Workflow.md
↓
Applicable master prompt, lock system, and camera bibles
↓
This revision workflow
↓
Prompt, reference set, tool settings, candidate, selected asset
```

For camera decisions, the authority is deliberately split:

* `19_Camera_Direction_Bible.md` is the sole operational authority for shot
  size, height, angle, side, composition, screen direction, and framing.
* `20_Camera_Movement_Bible.md` is the sole operational authority for whether
  and how the already-directed camera moves.

Do not cure a failed movement by silently changing the camera direction. Do not
cure an undefined direction by adding motion language.

When sources conflict:

1. State the exact fact in conflict.
2. Locate the highest applicable source.
3. Mark the affected asset `HOLD FOR CANON OR BOARD` if the fact is required.
4. Record the conflict and owner in the issue record.
5. Revise only after the owner resolves it.

Never average conflicting instructions, use a generated image as a tie-breaker,
or crop away a contradiction.

---

## Revision Principles

### 1. Preserve the known-good baseline

The selected asset, approved prompt revision, source manifest, reference
attachments, tool settings available, and approval record are the baseline.
Copy or branch from it; do not edit it in place. A later better-looking result
is a candidate until it has passed the same checks.

### 2. Diagnose before generating

“Try again” is not a diagnosis. Name the observed defect, where it appears,
which required lock it violates, its likely cause, and the smallest testable
correction.

### 3. Make one responsible change

Within a controlled comparison batch, change one causal group only:

* one prompt module;
* one reference attachment or its declared role;
* one approved still input;
* one camera direction field;
* one camera movement field;
* one tool mode, ratio, duration, or supported control; or
* one board/ledger fact after formal approval.

Do not simultaneously change identity, wardrobe, object state, lighting,
composition, action, and camera. The next result would teach nothing and could
hide a new defect.

### 4. Correct at the earliest responsible stage

Repair the earliest input that contains the error:

* Wrong fact in the premise, script, board, or ledger → return to that owner.
* Wrong keyframe at frame one → repair or replace the still before Flow.
* Correct keyframe but unstable motion → revise the Flow motion contract.
* Correct output but unsuitable cut, crop, caption, or rhythm → revise the edit
  or delivery composition; do not mislabel it as a character failure.

### 5. Approval is revision-specific

Approval of `r03` does not approve `r04`. Approval for a Flow source image does
not make it a thumbnail, reusable character reference, or other-format asset.

### 6. Recheck dependencies

Every replacement can affect adjacent shots, the continuity ledger, captions,
sound timing, thumbnail truth, metadata, and release status. Recheck the
smallest complete dependency set, not merely the changed file.

---

## The Locks That Revisions Must Protect

Before a revision, declare which locks are involved and whether each is
`UNCHANGED`, `CORRECTED`, `RECONFIRMED`, or `ESCALATED`.

| Lock | What must remain controlled |
| --- | --- |
| Canon and timeline | Early–mid-1990s rural Tamil Nadu; no unsupported modern fact, chronology, or cultural claim. |
| Series style | Original premium painterly cinematic anime identity; no named-studio imitation, plastic CGI, chibi or generic-anime substitution. |
| Character | Approved face, age, build, skin tone, hair, wardrobe logic, ornaments, posture, behaviour, relative scale, and relationship conduct. |
| Father identity | Use the approved Father canon design reference when required; it controls identity, not unrelated composition or lighting. |
| Mother identity | Preserve her approved face, practical dress and hairstyle, small bindi, left-nostril nose pin, thin glass bangles, jhumkas, and exactly one thali chain where visible. |
| Family Dog | Gentle German Shepherd household companion; never a threat, rescue, police, military, chase, injury, or stakes device. |
| Location | Documented zone, architecture, material, entry points, routes, landmarks, and usable screen geography. |
| Object | Period, material, count, owner, hand, orientation, amount, condition, placement, and end state. |
| Season and light | Season, time, weather, wetness, vegetation, source direction, and physical consequence; morning east and evening west. |
| Camera direction | The approved Document 19 direction record, line of action, side, height, shot size, composition, and safe crop. |
| Camera movement | The approved Document 20 movement type, path, speed, boundaries, and resting frame; one behavior maximum. |
| Continuity | Incoming and outgoing character, prop, weather, task, emotion, sound, and screen-direction state. |
| Delivery | Format, aspect ratio, mobile readability, caption-safe space, runtime, and edit purpose. |
| Audio | Approved dialogue, voice, ambience, Foley, music, silence, rights, and caption meaning; generated audio has no authority by default. |

Apply only the locks material to the asset, but never omit a visible or
continuity-critical one to make a revision easier.

---

## Revision States

Use the shared status vocabulary from `08_Production/16_File_Organization.md`.

```text
approved baseline
    ↓ defect found
hold / review
    ↓ diagnosis and approved test plan
candidate r+1
    ↓ independent review
approved or selected r+1
    ↓
supersede prior approved asset only for the stated downstream use
```

Use `rejected` for a candidate that must never be reused, `superseded` for
history that has been replaced, and `retired` when an old approved asset is no
longer valid for future use. Preserve all three with their reason; they are not
interchangeable.

---

## Required Revision Record

Create one record for every material revision. A concise record is acceptable;
an unexplained regenerated file is not.

```text
Revision ID:
Episode / scene / shot / asset ID:
Asset type and current status:
Baseline asset and revision:
Requesting owner:
Date:

Observed defect:
Evidence: timestamp, frame, crop, reviewer note, or source comparison:
Severity: blocker / major / minor / observation:
Violated source and lock:
Likely root cause:

Smallest proposed change:
Changed variable group:
Variables explicitly unchanged:
Expected result / pass condition:
Risk and dependencies to recheck:
Required approvals before generation:

New prompt or stable prompt reference:
New reference set and declared role:
Tool / model / mode / ratio / duration / available settings:
Candidate ID(s):

Review decision:
Reviewer(s):
Downstream handoff:
Archive location:
Superseded or rejected asset disposition:
```

Use `OPEN` only with an owner and resolution path. An `OPEN` recurring or
continuity-critical fact blocks generation.

---

## Diagnosis Procedure

### Step 1 — Freeze the exact baseline

Identify the exact prompt, reference assets, tool task or Flow project, input
mode, settings available, candidate identifier, selected output, edit revision,
and reviewers. Save any transient platform information immediately. Google Flow
history is not an archive.

### Step 2 — Observe, do not interpret yet

Describe only what is visible or audible:

* “The brass tumbler changes from Mother’s right hand to her left at 00:02.”
* “The kitchen window is on the wrong wall compared with the approved source.”
* “The clip begins correctly, then Father’s hair and face drift.”
* “The frame is valid in 16:9 but the hand is under the Shorts caption area.”

Avoid observations such as “the tool was confused” or “make it more cinematic.”

### Step 3 — Classify the failure

Choose the narrowest applicable class:

| Class | Typical evidence | First place to inspect |
| --- | --- | --- |
| Source or canon conflict | Prompt asks for a fact absent from or contrary to source | Canon packet, research, board |
| Script or board ambiguity | Several actions, unclear endpoint, no shot purpose | Script, storyboard, scene ledger |
| Identity drift | Face, build, hair, clothing, ornament, or dog changes | Character lock, reference role, source still |
| Location or period drift | Architecture, route, material culture, modern object shifts | Location lock, period anchors, source reference |
| Object-state drift | Count, hand, fill, material, position, or endpoint changes | Object ledger, prop prompt module |
| Light or weather drift | Direction, time, rain, wetness, or shadows contradict | Season/light ledger, camera direction |
| Camera-direction failure | Wrong side, height, size, crop, or screen direction | Document 19 record, board |
| Camera-movement failure | Roaming, shake, line crossing, wrong speed or endpoint | Document 20 contract, Flow prompt |
| Motion/anatomy failure | Floating, extra limbs, impossible contact, multi-stage action | Motion scope, duration, source frame |
| Technical/delivery failure | Wrong ratio, resolution, handles, captions, export, audio | Delivery brief, edit/export settings |
| Editorial failure | Asset is factual but does not support cut or rhythm | Edit notes, scene purpose, adjacent shots |
| Audio/voice failure | Wrong voice, invented dialogue, period-inaccurate sound | Script, sound plan, voice record |

### Step 4 — Find the earliest cause

Ask:

1. Was the incorrect fact already present before generation?
2. If not, did the prompt fail to name a required protected fact?
3. If it was named, was the source reference weak, missing, competing, or used
   outside its declared role?
4. If the first frame is correct, does the failure begin only during motion?
5. Is the tool asked to execute more than one meaningful action, camera move,
   or endpoint?
6. Is the requested outcome impossible at the chosen duration, ratio, or
   available Flow control?

### Step 5 — Write a single revision hypothesis

Use this form:

```text
Because [observed defect] is caused by [specific input or scope failure],
change [one named variable group] while preserving [named unchanged locks].
The revision passes only if [observable condition] is true.
```

Example:

```text
Because the tumbler changes hands during motion, clarify its owner, right-hand
grip, half-full state, shelf destination, and endpoint in the motion contract
while retaining the approved keyframe, fixed camera, kitchen reference, and
lighting. It passes only if the same tumbler remains in Mother’s right hand
until it rests half-full on the documented shelf.
```

### Step 6 — Choose the smallest safe remedy

| Diagnosis | Smallest valid remedy | Do not do |
| --- | --- | --- |
| Prompt lacks one object fact | Add that fact to the object module | Rewrite every module or change composition |
| Start frame is wrong | Repair or regenerate the still | Attempt to animate the wrong fact into correctness |
| Motion drifts after a correct start | Shorten/simplify the action or motion prompt | Change the character lock without evidence |
| Camera side is wrong | Correct the Document 19 direction record and still | Add a pan to hide the wrong side |
| Camera roams | Set `LOCKED CAMERA` or one bounded Document 20 move | Add several counter-instructions |
| Exact outgoing state is required | Use an approved end frame if Flow supports it, or split/cut | Force an unrelated two-image journey |
| Hands fail in a complex action | Split into an action shot and prop insert | Keep rerolling an overloaded action |
| Correct clip fails vertical crop | Generate in 9:16 from a vertical board | Crop the only action from horizontal footage |
| Generated audio invents a fact | Mute/remove it and use post-production sound | Treat it as approved narration or dialogue |
| Tool lacks needed control | Redesign using supported stills, cuts, or shots | Claim a feature exists or fabricate a workaround |

### Step 7 — Approve the test plan

Do not generate a material revision until the appropriate people approve the
change class:

| Change class | Minimum approval before/after revision |
| --- | --- |
| Editorial wording that affects no prompt fact | Responsible owner |
| Production prompt, reference, tool, candidate, or selected-asset change | Stage lead and affected downstream owner |
| Continuity, camera side, prop state, appearance, location, or cross-shot change | Continuity Lead and relevant canon/board owner |
| Story meaning, scene purpose, pace, script, or emotional action change | Episode Director plus Story/episode owner |
| Canon fact or reusable lock change | Canon authority plus Production Lead |
| Release-master, caption, metadata, thumbnail, or public correction | Quality/Release authority under `08_Production/` |

No person may approve their own unresolved defect. A reviewer may approve a
verified correction they did not author.

### Step 8 — Generate a controlled candidate

Use the approved baseline and make the declared one-group change. Keep:

* the same asset ID and a new revision label;
* the same declared output use unless a new use is explicitly approved;
* a small purposeful batch;
* the source record, references, and tool settings linked to every candidate.

For a test batch, vary only the stated test group. If the hypothesis fails,
record the result and make a new diagnosis; do not accumulate untested changes.

### Step 9 — Review from source to sequence

Review the candidate:

1. against required canon and lock sources;
2. at full resolution for identity, objects, period, anatomy, artifacts, and
   generated text;
3. at intended crop and ordinary phone size;
4. against incoming and outgoing shot state;
5. in the actual edit with sound/caption space where relevant;
6. against the declared pass condition.

A candidate that resolves one defect but creates another remains a candidate.

### Step 10 — Decide, hand off, and archive

Record one of these outcomes:

* `approved` — passes for a defined use;
* `selected` — chosen for the named edit from approved options;
* `revise` — hypothesis partially worked; a new record is required;
* `redesign` — the board, scene, or asset strategy is unsuitable;
* `hold` — a required authority or fact is missing;
* `rejected`, `superseded`, or `retired` — preserve history and prohibit use as
  indicated.

Then notify only affected downstream owners with the exact asset revision,
change summary, continuity impact, recheck request, and archive link.

---

## Prompt, Asset, And Edit Revision Boundaries

### Prompt-only revision

Use when the existing approved source frame and factual plan are correct but a
wording, targeted exclusion, module ordering, or bounded motion instruction is
insufficient. The exact required state must remain unchanged.

Example: add “no readable text, logo, or packaging copy” after a tea-stall
candidate introduces a sign. Do not also change the shop architecture, crowd,
weather, or camera.

### Reference-set revision

Use when the prompt names the correct fact but the tool needs a better approved
visual anchor. Declare each reference role:

```text
START_FRAME
END_FRAME
CHARACTER_IDENTITY
LOCATION_GEOGRAPHY
OBJECT_IDENTITY
STYLE_CONFIRMATION
```

Never attach inspiration images that compete with a canon reference. A
reference controls only its declared role; a character portrait does not
authorize a new costume, setting, or camera angle.

### Still/keyframe revision

Use when the defect exists at frame one, when a Flow source does not have a
stable composition, or when an exact continuity start/end state needs a new
approved image. The still must pass image QA before it becomes a Flow input.

### Flow motion revision

Use only when the start frame is correct and the fault appears during motion.
Keep the source still, locks, camera direction, and delivery use fixed unless
the diagnostic record identifies one of them as causal. Reduce scope before
adding detail: one action, one camera behavior, one environmental response.

### Storyboard or scene-ledger revision

Use when the planned shot is overloaded, its endpoint is impossible, its camera
logic is missing, or the requested visual change changes story meaning. A
prompt cannot repair an incoherent shot.

### Editorial/audio revision

Use when approved assets are factual but the cut, rhythm, sound, caption
placement, title, or thumbnail fails. Preserve picture provenance; do not
regenerate picture to compensate for an edit decision without a diagnosis.

---

## Google Flow Revision Rules

Google Flow behavior may change. Before revision, verify the currently
available mode, model, ratio, duration, first/last-frame input, reference
behavior, extension, audio, history, and download controls. Record what is
actually available, not what an old tutorial describes.

### Frame-one rule

If the first generated frame is wrong, stop. Do not extend the clip or revise
only the motion language. Repair the start image, reference set, or source
packet first.

### One-image versus two-image revision

Use one image when a stable start state and one bounded action produce an
editorially usable natural end. Use two approved images only when the next shot
requires an exact end state and the current Flow mode demonstrably supports it.

Two-image is not a cure for:

* a location, time, or wardrobe change;
* a multi-stage process;
* an unapproved or inconsistent end frame;
* an action whose physical journey would be implausible.

### Extension rule

Extend only a clip that ends in a correct stable state and naturally continues
the same action. Never extend a drifting face, altered prop, broken camera
line, wrong location, or unresolved story beat.

### Flow revision prompt pattern

```text
Preserve [approved start-frame locks and reference roles].

[One subject] [one physically clear action] at [natural pace].

Camera: [the approved Document 19 direction] remains [locked / one approved
Document 20 movement with finite endpoint].

Only [necessary environmental response] moves.

End when [observable factual end state].

No [diagnosed drift only: identity replacement, added people, changed object
state, text, modern detail, camera crossing, shake, or weather change].
```

The revision prompt should mention the diagnosed risk, not grow into a
contradictory list of every possible failure.

---

## Naming, Versioning, And Archives

Follow `08_Production/16_File_Organization.md` and
`08_Production/17_Version_Control.md`. The minimum naming pattern is:

```text
[episode_id]_[scene_or_shot]_[asset_type]_[subject]_[status]_[revision].[extension]
```

Examples:

```text
ep_014_sc_02_sh_006_prompt_leaf_pick_review_r02.md
ep_014_sc_02_sh_006_image_daughter_candidate_r02.png
ep_014_sc_02_sh_006_video_daughter_selected_r03.mp4
ep_014_sc_02_sh_006_revision_log_approved_r03.md
```

Use fixed-width IDs: `ep_014`, `sc_02`, `sh_006`, `r03`, `tk_01`. Do not use
`final`, `final_final`, `latest`, `new`, `use_this_one`, or a platform task ID
as the primary name.

### Revision-number rules

* Increment the revision when a reviewable, transferable, approved, selected,
  or materially changed asset is created.
* Keep the same revision across files that are inseparable parts of one tested
  package only when their manifest explicitly binds them.
* Do not renumber an approved shot merely because a scene was rearranged.
* Preserve the baseline file and create the new revision alongside it.
* A rollback creates a documented new decision; it does not erase newer history.

### Archive package

At selection, picture lock, sound lock, and release, archive:

* the final prompt text and revision history;
* source manifest and declared reference roles;
* approved inputs, selected outputs, and candidate IDs;
* tool, mode, model, ratio, duration, and available settings;
* revision hypotheses and results;
* issue, approval, selection, waiver, and dependency-recheck records;
* continuity ledger and edit relationship;
* source-file paths and stable managed-storage links;
* superseded, rejected, and retired materials with disposition reasons.

Keep release-critical media in managed storage with a backup and recovery copy
as prescribed by Production. Do not rely on Flow or an editor cache as the only
archive.

---

## Handoff Standard

A revision handoff is complete only when the recipient can act without guessing.

```text
To:
From / owner:
Episode / scene / shot / asset revision:
Status:
What changed:
Why it changed and evidence:
What remains locked:
Exact files / managed-storage links:
Source manifest / prompt revision:
Continuity impact:
Requested decision or next action:
Dependencies to recheck:
Known limitations or OPEN items:
Receipt confirmation:
```

The sender retains responsibility until the recipient confirms receipt and
fitness for the next stage. Do not hand off “the latest.”

---

## Approval And Recheck Matrix

| Revision affects | Mandatory recheck |
| --- | --- |
| Character appearance, wardrobe, or behaviour | Character/canon source, adjacent shots, related references, continuity ledger |
| Location, direction, landmark, or lighting | Location source, Document 19 record, light/weather ledger, adjacent shots |
| Camera movement | Document 20 boundaries, screen direction, cut/handles, edit rhythm |
| Object state or action | Object source, prior/next shot, hand/position/count/fill state, caption crop |
| Still used by Flow | Image QA, reference roles, Flow input record, frame-one review |
| Flow clip | First/final frames, motion, camera, object and identity integrity, edit and sound timing |
| Voice or audio | Script, performance approval, sound plan, captions, rights, mix |
| Edit or duration | Scene purpose, pacing, sound/caption timing, thumbnail and metadata truth |
| Thumbnail, title, metadata, or captions | Final locked cut, Quality Control, Publishing Workflow |
| Canon source or permanent lock | All dependent active episodes, reusable assets, prompt modules, and production documentation |

---

## Worked Examples

### Example 1 — Controlled prop correction

**Observed defect:** In a Flow clip, Mother begins with a half-full brass
tumbler in her right hand. At 00:02 it becomes a handled steel cup in her left
hand.

**Diagnosis:** The keyframe is correct. The motion request says only “Mother
places the cup on the shelf,” leaving material, hand, fill state, and endpoint
unprotected.

**Smallest change:** Keep the same approved keyframe, kitchen reference,
locked camera, duration, and lighting. Revise only the object/motion module:
“Mother keeps the same half-full brass tumbler in her right hand and places it
on the marked shelf; it remains brass, half-full, and unchanged.”

**Approval/review:** Prompt Lead and Continuity Lead review the candidate’s
first frame, hand continuity, exact shelf end, and next insert. The old clip is
`rejected`; the new clip can become `approved` only for that shot.

### Example 2 — Camera failure is not an animation-detail failure

**Observed defect:** A candidate begins as the approved medium side view of
Father repairing a fence, then circles him and crosses the established line.

**Diagnosis:** The direction was correct. The Flow prompt said “cinematic
movement,” which is an unbounded movement instruction and violates Document 20.

**Smallest change:** Retain the Document 19 camera direction and set
`LOCKED CAMERA`. Keep one grounded hand action. Do not rewrite Father’s
appearance or the fence location.

### Example 3 — Format requires a new composition

**Observed defect:** A valid long-form 16:9 clip places the basket and hands at
the lower edge; caption-safe 9:16 crop hides them.

**Diagnosis:** This is a delivery composition failure, not an edit crop problem.

**Required action:** Create a vertical storyboard direction and new still
keyframe that keeps the action centrally readable. The 16:9 clip remains
approved for long-form use, not for the Short.

---

## Edge Cases

### An approved asset is later contradicted by canon

Immediately mark it unavailable for future downstream use, preserve it as
history, identify every dependent shot/edit/reference, and obtain a
Continuity/Canon decision. Do not silently replace files or merely rename the
asset. A canon correction may require a new episode and release review.

### A reviewer requests an aesthetic alternative without a defect

Classify it as an observation. Do not reopen an approved asset just to seek a
different taste unless the Episode Director authorizes a new production
decision. Preserve schedule and continuity discipline.

### A candidate solves the defect but is better for a different use

Record it separately and seek approval for that use. It cannot be substituted
for a board still, Flow source, thumbnail, or release master by convenience.

### No reliable Flow result after controlled revisions

Stop escalating prompt complexity. Use a still hold, a simpler motion, a
separate insert, a two-image task only where warranted, or a storyboard/edit
redesign. Record the tool limitation as production evidence.

### A post-release correction is necessary

Follow `08_Production/15_Publishing_Workflow.md`. Preserve the released
version, record the public impact, identify the corrected version and date,
and recheck captions, metadata, thumbnail, cards, end screens, and continuity
claims affected by the correction.

---

## Final Standard

A revision is complete only when a future team member can answer:

* What exact defect was found?
* Which authority and lock governed it?
* Why was this the root cause?
* What was the smallest change?
* Which approved baseline remains preserved?
* Who approved the new revision?
* What downstream material was rechecked?
* Where are the prompt, inputs, outputs, decision, and archive?

If those answers are unavailable, the work is an experiment, not a safe
production revision.

