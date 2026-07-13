# File Organization Manual

## Purpose

This manual establishes the permanent production filing system for Village Stories.

It makes every approved document, visual, audio file, Google Flow generation, edit, export, review, and release record easy to find, verify, reuse, and audit without changing established story or canon authority.

It answers:

> Where does a production item live, what is it called, and which copy may be used?

---

# Philosophy

File organization is a continuity system, not office administration.

An unlabeled asset can be used in the wrong episode. A duplicate prompt can silently diverge from canon. A final-looking export can be published before approval. Clear structure prevents these failures before they reach viewers.

The repository is documentation-first. It records the decisions and references that make production reproducible. Large binary media may live in the approved production storage system, but its authoritative index, status, and source relationship must be recorded here.

No file becomes trustworthy because its name contains `final`.

It becomes trustworthy when its status, source, approval, and intended use are unambiguous.

---

# Objectives

This system must:

* preserve the existing single-source-of-truth principle;
* separate permanent canon from episode-specific work;
* let a producer identify the approved source in seconds;
* make handoffs safe between writing, design, generation, sound, editing, QA, and upload;
* prevent accidental reuse of drafts, tests, and rejected assets;
* support Git-aware text documentation without requiring a particular application;
* support Google Flow and YouTube deliverables without treating either platform as the canon authority;
* retain enough context to recreate a released episode later.

---

# Authority and Relationship Documents

This manual governs file placement, naming, status labels, registers, and source references.

It does not define creative truth. Consult the appropriate authority before filing or producing:

1. `00_Project_Core/README.md` — repository identity and documentation philosophy.
2. `01_Canon/` — permanent series rules and style locks.
3. `02_World/` — geography, environment, culture, seasons, and locations.
4. `03_Characters/` — character identity, relationships, appearance, and behaviour.
5. `04_Objects/` — recurring objects and period-appropriate handling.
6. `05_Research/` — research evidence and historical cautions.
7. `06_Story_Engine/` — story construction authority.
8. `07_Episode_System/` — episode form, pacing, and viewer-facing structure.
9. `10_Episodes/` — the permanent record of completed episode decisions.
10. `11_Assets/` — approved reusable reference assets and their indexes.
11. `12_Quality_Assurance/` — continuity and quality controls when present.

If a location in this manual conflicts with an existing project-level directory decision, retain the existing directory decision and update this manual through the approved documentation process.

---

# Folder Responsibilities

`08_Production/` holds durable methods, templates, checklists, prompt procedures, and production governance.

It must not become a dumping ground for episode exports or a second canon library.

Use the following broad separation:

```text
01_Canon/              Permanent non-negotiable series rules
02_World/              Persistent setting facts
03_Characters/         Persistent character facts
04_Objects/            Persistent object facts
05_Research/           Sources, findings, cautions
06_Story_Engine/       Story construction rules
07_Episode_System/     Episode structure and audience delivery rules
08_Production/         Production methods and controls
10_Episodes/           Episode-specific plans and released records
11_Assets/              Reusable approved media references
12_Quality_Assurance/  QA standards and evidence
Archive/               Superseded material retained for history
```

An item belongs in the narrowest authoritative home. Link to it from other documents rather than copy its contents.

---

# Episode Workspace Model

Each episode needs one stable identifier before production starts. Use the project’s assigned episode identifier; do not invent a competing numbering scheme.

Within the episode record, keep work grouped by function:

```text
[Episode_ID]/
  00_Admin/
  01_Story/
  02_References/
  03_Storyboard/
  04_Generation/
  05_Audio/
  06_Edit/
  07_QA/
  08_Release/
  09_Archive/
```

This is a logical model. A storage platform may use a different physical layout only if its index preserves these same functional boundaries and references.

Do not place permanent character, world, object, or research files inside an episode folder merely because the episode uses them.

---

# Numbered Folder Meanings

* `00_Admin/` — brief, owner list, dates, status board, approvals, and handoff notes.
* `01_Story/` — premise, outline, script, dialogue, narration, and scene list.
* `02_References/` — reference manifest and links to canon, research, locations, objects, and approved assets.
* `03_Storyboard/` — shot plan, boards, animatic notes, and camera continuity plan.
* `04_Generation/` — prompt records, source references, candidate outputs, and selected-shot register.
* `05_Audio/` — dialogue, ambience, Foley, music, mix notes, and rights records.
* `06_Edit/` — editing project files, sequence notes, subtitles, and review exports.
* `07_QA/` — checklists, issue log, reviewer findings, and release decision.
* `08_Release/` — approved master, thumbnail package, title/description record, upload record, and platform metadata.
* `09_Archive/` — frozen milestones, withdrawn candidates, and superseded non-canon working records.

---

# Naming Philosophy

A filename is a compact production sentence. It should state what the file is without requiring a person to open it.

Use names that are:

* readable by humans;
* sortable in ordinary file browsers;
* stable across tools and operating systems;
* specific enough to avoid collisions;
* free of private, temporary, or ambiguous language.

Use lowercase words separated by underscores, unless an external platform requires another form.

Use ASCII letters, numerals, underscores, and hyphens. Avoid spaces, emoji, slashes, leading punctuation, and characters that have special meaning in URLs or shell tools.

---

# Standard Filename Pattern

Use this pattern where scope supports it:

```text
[episode_id]_[scene_or_shot]_[asset_type]_[subject]_[status]_[revision].[extension]
```

Examples:

```text
ep_012_sc_03_sh_04_video_mother_stove_candidate_r02.mp4
ep_012_sc_03_sh_04_prompt_firewood_lighting_approved_r03.md
ep_012_audio_kitchen_ambience_mix_approved_r01.wav
ep_012_thumbnail_mango_basket_approved_r02.png
```

Use `series_` only for a series-wide production file. Use `ref_` for a non-episode reusable reference.

Never use `new`, `latest`, `use_this_one`, `final_final`, a person’s initials alone, or a date alone as a status.

---

# Identifier Rules

Use fixed-width numeric identifiers where an ordered sequence matters:

* Episode: `ep_001`
* Scene: `sc_01`
* Shot: `sh_001`
* Revision: `r01`
* Take: `tk_01`

Do not renumber an approved scene or shot solely to make a list look tidy. Preserve the identifier and record a skipped or removed item in the relevant register.

Dates use ISO format: `YYYY-MM-DD`.

Use dates for milestones, backups, and releases; do not use them in every media filename unless the workflow creates multiple same-day deliverables that would otherwise collide.

---

# Asset Type Vocabulary

Use a controlled, plain-language asset type:

* `brief`
* `outline`
* `script`
* `scene_list`
* `reference_manifest`
* `storyboard`
* `animatic`
* `prompt`
* `image`
* `video`
* `audio`
* `foley`
* `music`
* `voice`
* `edit`
* `subtitle`
* `thumbnail`
* `metadata`
* `master`
* `qa`
* `approval`

Add a new asset type only when the existing vocabulary cannot describe it honestly. Define it in the episode register before use.

---

# Asset Status Vocabulary

Status communicates whether an asset may move forward. Use one primary status:

* `planned` — authorized need; no usable asset exists.
* `draft` — incomplete working material; not for downstream use.
* `candidate` — complete enough to evaluate; not approved.
* `review` — submitted to a named reviewer; changes are controlled.
* `approved` — accepted for its stated purpose.
* `selected` — chosen from approved candidates for a specific edit or release.
* `locked` — frozen for a milestone; change requires reopening control.
* `released` — published or delivered master.
* `superseded` — retained history; do not use.
* `rejected` — evaluated and unsuitable; do not reuse.
* `retired` — deliberately no longer valid for future use.

`approved` is not equivalent to `released`. An approved image may be a usable asset while a released master is a public deliverable.

---

# Canonical Source References

Every production item that depicts, states, or relies on persistent information needs source references.

Record them in a reference manifest, prompt record, shot record, or metadata entry. A useful reference contains:

```text
Source path:
Section or heading:
Fact used:
Access date:
Production implication:
```

Example:

```text
Source path: 03_Characters/Family/Mother/Appearance.md
Section or heading: Daily clothing
Fact used: Approved clothing details for this scene
Access date: 2026-07-13
Production implication: Keep the selected garment, colour, and accessories consistent across shots.
```

A path alone is insufficient when a source contains several possible facts. A copied excerpt is insufficient because it can become stale. Reference the source and the exact applied decision.

---

# Reference Manifest Requirements

Create or update an episode reference manifest before storyboards or Google Flow generation begin.

It must list:

* episode identifier and working title;
* every canon, world, character, object, and research document consulted;
* approved reusable visual and sound assets;
* facts that materially affect scene continuity;
* unresolved questions and their owner;
* the date the manifest was last reconciled.

The manifest is an index, not a replacement for the cited documentation.

---

# Google Flow Generation Records

Google Flow is a production tool, not the source of truth.

For each selected generated shot, retain a durable record outside the platform:

* episode, scene, and shot identifier;
* prompt text or a stable prompt-file reference;
* model or workflow identifier if known;
* input reference assets and their approved status;
* generation date;
* candidate filename or platform link;
* selected output identifier;
* continuity notes;
* reviewer and decision.

Do not rely on a chat history, browser session, or platform library as the only record of a selected visual.

Capture the source media or approved platform export according to rights, storage, and availability rules.

---

# YouTube Release Files

The release folder must distinguish platform copy from the episode master.

Keep records for:

* approved upload master;
* thumbnail source and final upload image;
* title options and approved title;
* description and credits;
* subtitles, captions, and language versions;
* chapter list when used;
* audience, disclosure, and rights settings;
* upload date/time;
* published URL and video identifier;
* post-upload verification record.

The video on YouTube is a delivery instance. The approved local or managed master and release record remain the production authority.

---

# Detailed Workflow

## 1. Establish the episode workspace

Assign the approved episode identifier, create the logical functional areas, and name a production owner. Do not create work under an informal title that may later collide with another episode.

## 2. Build the reference manifest

Before a production asset is made, record the canon, research, reusable-asset, and continuity sources the episode needs. List unresolved facts rather than hiding them in a draft.

## 3. Create and label working material

Use the standard filename pattern and assign `planned`, `draft`, or `candidate` status as appropriate. Keep tests separated from selected material.

## 4. Record selection and approvals

When a candidate becomes usable, retain its stable identifier, source inputs, reviewer, intended use, and current status. Update the register before handing it to the next role.

## 5. Lock approved handoff packages

At storyboard, generation-selection, edit, and release milestones, identify the exact files that are handed forward. Mark replaced material `superseded`; never leave two ambiguous copies in the working area.

## 6. Archive the release package

After YouTube verification, protect the master, metadata, thumbnail, source manifest, QA evidence, and platform record as a release archive. Refer to `17_Version_Control.md` for backup and historical controls.

---

# Handoff Protocol

Every handoff must name:

1. the deliverable;
2. its file path or stable storage link;
3. its primary status;
4. its source references;
5. what decision is requested;
6. the recipient and due context;
7. known risks or open questions.

Use a handoff note or issue record rather than relying on a verbal message.

The sender keeps ownership until the recipient confirms receipt and fitness for the next stage.

---

# Role Handoffs

## Story to Production

The writer or story lead hands off an approved premise, scene list, reference manifest, open-question list, and applicable Story Engine/Episode System decisions.

Production must not infer missing canon facts from a vague script.

## Production Design to Generation

The visual lead hands off approved character, location, prop, lighting, framing, and continuity requirements with their source references.

The generation operator records candidates; they do not silently redefine the visual plan.

## Generation to Edit

The generation operator hands off only selected or explicitly approved assets, with shot identifiers, duration, continuity notes, and known limitations.

The editor does not retrieve a random “better” candidate from a platform library without re-entering review.

## Edit to QA

The editor provides a review export, edit/project reference, subtitle state, audio state, source register, and a list of intentional deviations.

## QA to Release

QA provides a resolved issue log, approval decision, release checklist, and the exact master filename or immutable reference.

---

# Decision Framework for Ambiguous Files

Ask these questions in order:

1. Is this permanent knowledge, episode work, reusable media, QA evidence, or archive history?
2. Does an authoritative home already exist?
3. Is there one source of truth already?
4. Can a person determine status and intended use from its record?
5. Would moving it duplicate canon or make a release harder to reproduce?

If uncertain, place no new permanent file until the production lead assigns a home. Use a temporary, clearly labeled working area only when it is indexed and has an expiry decision.

---

# Quality Assurance

Before approving a production folder or handoff, verify:

* filenames use the agreed identifiers and status vocabulary;
* no asset is labeled ambiguously as final;
* every selected shot has a prompt/source record;
* every continuity-critical claim cites canonical documentation;
* links and paths resolve for another team member;
* rejected and superseded candidates cannot be mistaken for approved material;
* the release master can be identified without opening multiple files;
* platform metadata matches the approved release record.

Run this check at storyboard lock, edit lock, and release approval.

---

# Common Mistakes

## Copying canon into an episode folder

This creates two authorities that eventually disagree. Link to the canon source and record only the episode-specific application.

## Using `final` as a workflow state

`final` has no decision history. Use an explicit status plus revision and approval record.

## Naming files after a platform-only identifier

Platform IDs can be useful references but do not explain the asset. Keep the stable episode and shot identifiers first.

## Keeping prompt history only in Google Flow

Platform access, interface history, and outputs can change. Preserve the selected prompt and input record in managed production documentation.

## Mixing tests with selected assets

Candidate generations belong in an identifiable candidate area or register. An editor should never have to guess which version is usable.

## Treating an export as the source

An export may be compressed, cropped, or out of date. Record the editable source and the approved master separately.

---

# Continuity and Canon Authority

Filing does not approve a new fact.

If a scene, prompt, or asset reveals a contradiction, stop the handoff and escalate it to the relevant canon owner. Do not resolve it by renaming a file, hiding the source reference, or treating a generated output as proof.

Episode-specific records document how canon was applied. They cannot revise canon by implication.

---

# Maintenance

Review this manual whenever:

* a new storage system changes how source links work;
* a repeated naming collision reveals a missing convention;
* a release cannot be reconstructed from its records;
* a platform workflow changes the data that must be retained.

Changes must preserve existing file paths where practical, document any migration, and never retroactively obscure what was released.

---

# Guiding Principle

Every production file should let a future creator answer, without guesswork:

> What is this, where did it come from, what may it be used for, and which approved decision does it serve?
