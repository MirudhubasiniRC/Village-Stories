# Asset Naming

## Purpose

This manual defines the permanent asset-identity system for Village Stories.

It tells contributors how to name, identify, relate, select, hand off, release,
and retain media and asset-adjacent production records.

An asset name is not a description of what looks attractive in one moment.

It is a durable statement of what the item is, what it is for, and how it can
be traced without relying on the creator, a browser session, or a tool library.

This manual applies to original, generated, imported, selected, derived,
reviewed, released, and archived assets.

It applies whether an asset is stored in the repository, managed cloud storage,
an edit system, Google Flow, a voice platform, or a release platform.

## Governing Principle

Give every retained asset an identity that lets a future contributor locate its
authority, lineage, intended use, and current decision without guessing.

When a shorter name obscures lineage, keep the lineage visible.

When a richer name duplicates information held by the asset ID or manifest, use
the ID and preserve the detail in the record.

When a tool offers a convenient label that cannot survive a handoff, assign the
studio-controlled name before the asset is reviewed or reused.

## Scope and Boundaries

This manual owns asset classes, asset namespaces, asset identifiers, variant
identity, derivative relationships, selection identity, and asset-specific
handoff evidence.

`Naming_Standards.md` remains authoritative for universal filename grammar,
characters, casing, separators, dates, state tokens, revision syntax, and
general collision handling.

`Folder_Standards.md` remains authoritative for placement, custody, folders,
copies, archives, and the one-authoritative-home rule.

This manual does not create a new asset store, episode structure, or release
folder pattern.

This manual does not define canon, prompt wording, camera language, audio
creative direction, legal rights, edit workflow, or release approval policy.

Those decisions remain with their owning authorities.

## Authority

Apply the highest relevant authority whenever an asset decision overlaps.

Legal, rights, safety, privacy, and platform obligations override this manual.

Approved canon overrides a convenient visual, audio, or descriptive label.

The entity owner in `02_World/`, `03_Characters/`, or `04_Objects/` owns the
canonical identity represented by an asset.

`09_AI_Production_System/` owns prompt systems, locks, generation controls,
Google Flow operating practice, and prompt QA.

`08_Production/` owns production execution, edit decisions, and release gates.

This manual controls how the relevant asset and its relationships are named and
recorded across those systems.

An asset name never grants canon approval, rights clearance, reuse permission,
or release authorization.

## Relationship to Canon

Asset names must preserve canon rather than invent it.

Use an approved character, location, object, story, or episode identifier only
when the owning system has assigned it.

Do not create an episode token from a working title, upload order, calendar
date, or an assumed sequence number.

Do not turn a provisional scene description into a canonical entity name by
placing it in an asset filename.

When an episode ID is not assigned, retain the asset in its controlled work
boundary and use an approved pending reference in the accompanying record.

Do not use an invented episode-number token or unapproved placeholder in a
retained asset name.

Examples in this manual use bracketed variables such as `[approved-episode-id]`.

Bracketed variables are grammar illustrations, not names to create.

## Asset Identity Model

Every governed retained asset has four separable identity layers.

The asset ID answers: which durable controlled asset is this?

The filename answers: which file, role, state, and revision is this?

The lineage record answers: what source, prompt, edit, or other asset produced
this item?

The use record answers: where, how, and under what approval is this item used?

Do not attempt to force all four layers into one filename.

Do not use a filename alone as the asset register.

Do not use an asset ID alone as proof that a particular derivative is approved.

## Asset Record Minimum

Create or update an asset record when an item is selected, approved, reused,
shared outside its task, attached to a formal review, or retained as evidence.

The asset record must identify the asset ID.

The asset record must identify the current controlled filename and path or URI.

The asset record must identify the asset class and custody class.

The asset record must identify the owning role or system.

The asset record must identify the current status and revision.

The asset record must identify its source relationship or state that it is
original capture.

The asset record must identify applicable rights or usage constraints.

The asset record must identify the relevant continuity subjects.

The asset record must identify review, selection, or approval evidence when
those decisions are required.

The asset record may be a manifest entry, asset register row, controlled record,
or linked managed-media record.

## Core Filename Grammar

Use the universal grammar from `Naming_Standards.md`.

For most governed assets, the applicable form is:

```text
[scope]__[subject-or-asset-id]__[artifact]__[qualifier]__[state]__[revision].[extension]
```

The subject or asset ID identifies the represented or controlled item.

The artifact token identifies the specific file role.

The qualifier distinguishes a bounded variant, technical delivery, language,
channel, input role, or review round when needed.

The state token records actual operational status.

The revision token identifies a controlled iteration of the same file role.

Do not add placeholders for optional values.

Do not repeat an asset class in both subject and artifact tokens unless each
word contributes different meaning.

## Asset ID Grammar

Use this generic asset ID grammar:

```text
ast-[class]-[stable-key]
```

The `ast` prefix means a studio-controlled asset identifier.

The class identifies the durable asset namespace, not the file extension.

The stable key is assigned by the controlling asset register.

Use lower-case ASCII and hyphens in asset IDs.

Do not encode a mutable approval state, revision, owner, date, or public title
inside an asset ID.

Do not recycle an asset ID after rejection, deletion, archive, or replacement.

Do not infer an asset ID from a filename hash, camera roll number, Google Flow
project ID, YouTube video ID, or cloud-provider object ID.

## Asset ID Classes

Use one of the following controlled class tokens when the item becomes a durable
asset.

`vis` identifies a reusable visual asset.

`aud` identifies a reusable audio asset.

`gfx` identifies a reusable graphic or design asset.

`ref` identifies a managed reference asset.

`src` identifies an imported or original source asset requiring custody.

`prj` identifies a durable editable project asset.

`pkg` identifies a controlled package asset when package-level identity is
needed.

`doc` identifies an asset-adjacent durable document only when its register
needs an asset relationship.

`tmp` is never a durable asset class.

`gen` is not an asset class because generation method is lineage, not identity.

`flow` is not an asset class because Google Flow is a tool, not the studio's
creative namespace.

## Stable-Key Rules

Assign a stable key only through the owning register or controlled workflow.

Use a sequence or opaque key that is unique within the class namespace.

Use zero padding when the register uses numeric keys.

Use the same asset ID across alternate storage locations only when they are the
same controlled asset.

Assign a new asset ID when a new reusable identity, new rights basis, new
canonical subject, or materially distinct creative source is established.

Do not assign a new asset ID merely because a file is exported in another
format.

Do not assign a new asset ID merely because an image is resized for Google Flow.

Do not assign a new asset ID merely because one episode uses an existing asset.

## Asset Classes

Classify every retained asset by its operational role before naming it.

An asset may have multiple descriptive qualities but only one primary class for
its controlling record.

Use `reference-image` for material consulted to guide a decision.

Use `image-candidate` for an unselected generated or edited still under review.

Use `selected-still` for the exact still chosen for a declared shot, board, or
approved production purpose.

Use `flow-input` for a controlled upload copy or source input used by a Flow
task.

Use `flow-clip` for a downloaded Google Flow output before or after selection.

Use `voice-source` for an original or licensed voice recording source.

Use `voice-take` for a bounded recorded or generated narration performance.

Use `music-source` for licensed, commissioned, or original music source media.

Use `music-stem` for a separated music component.

Use `sfx-source` for an original, licensed, or approved sound-effect source.

Use `audio-mix` for a mixed deliverable serving a defined editorial purpose.

Use `thumbnail` for a platform-facing thumbnail deliverable.

Use `prompt-package` for a bundled controlled prompt instance and its required
machine-readable or human-readable components.

Use `board` for a storyboard, shot board, or visual planning board.

Use `caption` for a caption or subtitle deliverable.

Use `review-proxy` for a review-only encoded picture or audio copy.

Use `review-record` for the evidence or decision record of a review.

Use `platform-master` for an approved audiovisual delivery source recognized by
the release workflow.

Use `release-master` only where the release workflow distinguishes a
platform-neutral immutable master from platform masters.

Use `archive-package` for an intentionally retained immutable archive bundle.

## Reference Images

A reference image informs a decision; it is not automatically approved for
generation, editing, reuse, or public distribution.

Name source-derived reference images by their source identity first.

Use the source creator, collection, accession, repository, or controlled source
record identifier when one exists.

Use a bounded relevance qualifier only when it helps distinguish why the image
is being consulted.

Example grammar:

```text
reference__[source-identifier]__reference-image__[purpose]__archived__r01.jpg
```

For a studio-made reference sheet tied to an approved asset, use the asset ID
or canonical subject rather than an external source label.

Record the origin, rights, access date when material, applied purpose, and
whether the image is evidence, inspiration, match target, or licensed input.

Do not name a borrowed image as though Village Stories created it.

Do not label a reference image `approved` merely because it is visually useful.

Do not use an unverified screenshot as a production input without a source and
rights decision.

## Image Candidates

An image candidate is a generated, edited, or captured still that has not been
selected for its proposed use.

Candidate names must preserve the intended subject and bounded generation or
editorial role without implying acceptance.

Example grammar:

```text
shot-[approved-episode-id]-[scene-number]-[shot-number]__image-candidate__[candidate-key]__review__r01.png
```

The candidate key distinguishes genuinely different candidates for the same
shot and role.

Use a controlled candidate key such as `cand-01`, `cand-02`, or a registered
generation key.

Do not use subjective keys such as `best`, `good-one`, `nice`, or `maybe`.

Do not use revision to distinguish unrelated candidate concepts.

Record prompt revision, input assets, seed or generation settings when
available, tool task reference, and continuity observations in the candidate
register.

Retain rejected candidates only when they explain a material decision, prevent
repeat failure, support rights evidence, or are required by a workflow.

## Selected Stills

A selected still is the exact candidate or source still chosen for a declared
production purpose.

Selection does not automatically make a still reusable across the series.

Selection does not automatically make a still a release deliverable.

The selection record must cite the selected file's revision, its candidate or
source lineage, the intended shot or purpose, reviewer, decision, and date.

Example grammar:

```text
shot-[approved-episode-id]-[scene-number]-[shot-number]__selected-still__[role]__approved__r01.png
```

Valid role qualifiers include `start-frame`, `end-frame`, `keyframe`, `board`,
`edit-hold`, and `thumbnail-source`.

Use `approved` only after the applicable selection decision is recorded.

Use `conditional` when the selected still may proceed only with a named
constraint, such as a pending rights or continuity correction.

Do not overwrite a selected still with a regenerated candidate.

Create a new candidate and a new selection decision when a replacement is
needed.

## Google Flow Project Identity

Google Flow project names are working labels, not permanent studio identity.

Use an approved episode identifier only when one exists.

When no approved episode identifier exists, use the controlled task or work
boundary label authorized by the production workflow; do not invent an episode
number.

A Flow project label should make its bounded purpose recognizable without
pretending it is an asset ID.

Example project-label grammar:

```text
[approved-episode-id]__flow__[bounded-sequence-or-task]
```

For a non-episode bounded task, use the approved governing subject:

```text
[approved-subject]__flow__[bounded-task]
```

The project record, not the Flow label, must contain the external project ID,
project URL where permitted, owner, access context, and task status.

Do not use a Flow project label as a substitute for a shot record.

Do not create one unbounded Flow project for unrelated episodes, characters, or
release tasks.

## Google Flow Input Names

Every Flow upload must be classified before it enters the tool.

Use `flow-input` for an upload file when the upload copy is retained or must be
distinguished from its source-quality asset.

Example grammar:

```text
shot-[approved-episode-id]-[scene-number]-[shot-number]__flow-input__start-frame__approved__r01.png
```

Use `end-frame` for a controlled second input.

Use `character-reference`, `location-reference`, `object-reference`, or
`style-reference` only when the input's role is precise and its source record
is linked.

Use `upload-copy` only for a transient technical adaptation whose source asset
is recorded.

Do not use `flow-input` as a way to rename or replace the authoritative still.

Do not upload a resized, cropped, or recompressed copy without recording the
source asset ID and derivative relationship.

Do not place unverified reference media into Flow merely because it appears to
solve a visual problem.

## Google Flow Clip Names

Treat every downloaded Flow clip as a candidate until a selection decision says
otherwise.

Example candidate grammar:

```text
shot-[approved-episode-id]-[scene-number]-[shot-number]__flow-clip__[candidate-key]__review__r01.mp4
```

Use the candidate key from the generation record, not the order in which a
browser happened to display clips.

When selected for editorial use, create a selected derivative or change state
only through the selection workflow.

Example selected grammar:

```text
shot-[approved-episode-id]-[scene-number]-[shot-number]__flow-clip__selected__approved__r01.mp4
```

The generation record must link the clip to its Flow project or task ID, exact
prompt instance revision, input asset IDs, input mode, aspect ratio, duration,
known settings, generation date, and reviewer decision.

Do not erase the Flow task relationship when normalizing an export name.

Do not call a Flow clip a `master` solely because it is the best generation.

Do not extend, concatenate, color-correct, or otherwise alter a selected Flow
candidate in place.

Name the editorial derivative for its new role and preserve the source clip.

## Google Flow Continuity Controls

For every Flow task, the generation record must identify what Flow must
preserve.

Record the character identity source or canonical record used.

Record the location or set source used.

Record the object state and contact constraints that matter.

Record the style lock and camera lock references where applicable.

Record the approved start state and intended end state.

Record screen direction, geography, time-of-day, weather, costume, and prop
state when those constrain continuity.

Record the exact selected still revision used as each start or end input.

Do not name a clip as continuity-safe merely because it contains familiar
subjects.

Continuity approval belongs in the review evidence, not an optimistic filename.

## Voice and Narration Assets

Separate the written narration source, voice performance source, generated
voice take, edit proxy, and final mix.

Use `voice-source` for raw source recordings or a licensed source.

Use `voice-take` for a selected or reviewable performance unit.

Use `narration` as a role qualifier when the voice asset is narration.

Use `dialogue` as a role qualifier when the voice asset is character dialogue.

Example grammar:

```text
scene-[approved-episode-id]-[scene-number]__voice-take__narration__review__r01.wav
```

For a bounded line or paragraph, use a controlled line or cue reference from
the script record as a qualifier only when it is stable and documented.

Do not place spoken text, a performer name, or a private account identifier in
the filename unless required by a rights or delivery process.

Record voice source, performer or service, consent and rights basis where
applicable, script revision, pronunciation decisions, processing chain, and
approval evidence outside the filename.

Do not call a generated voice `approved` until content, pronunciation, rights,
and technical review are complete for its declared use.

## Music Assets

Music identity must preserve provenance, rights, and editorial role.

Use `music-source` for an original composition source, licensed track source,
or commissioned delivery source.

Use `music-stem` for isolated components such as `full-mix`, `instrumental`,
`percussion`, or another documented stem role.

Use `music-edit` for an episode-specific edited music derivative.

Example grammar:

```text
asset-[approved-id]__music-stem__instrumental__approved__r01.wav
```

For an episode-specific use, the episode record must cite the reusable asset ID
and exact revision rather than creating a second source identity.

Do not name a licensed track after its mood alone when a source title or asset
ID exists.

Do not remove composer, licensor, cue, or contract identity from the rights
record merely because the studio filename is compact.

Do not treat an editor's volume-adjusted copy as a new music asset unless it is
retained and used as a distinct controlled derivative.

## Sound Effects and Ambience Assets

Use `sfx-source` for an individual source sound effect.

Use `ambience-source` for a location, environment, or room-tone source.

Use `foley-source` for original or licensed performed foley source.

Use `sfx-edit` or `ambience-edit` for a bounded episode-specific derivative.

Use `audio-mix` for a combined deliverable rather than relabeling every
component as a mix.

Example grammar:

```text
asset-[approved-id]__ambience-source__location-bed__approved__r01.wav
```

Avoid vague audio roles such as `sound`, `audio`, `noise`, or `effect` when a
specific controlled class is available.

Record source, rights, intended reuse scope, loop boundaries, loudness handling,
and processing lineage in the asset record.

Do not promote a temporary generated ambience to reusable status without a
quality, continuity, and rights decision.

## Audio Stems, Mixes, and Exports

Name each audio derivative by its delivery role, not by the software session
that exported it.

Use `audio-stem` for a separately delivered mix component.

Use `audio-mix` with qualifiers such as `review`, `editorial`, `broadcast`, or
another approved purpose where that distinction is necessary.

Example grammar:

```text
episode-[approved-episode-id]__audio-mix__editorial__review__r02.wav
```

Use a language qualifier only when the mix differs by language.

Use a channel-layout qualifier only when it is required to distinguish
deliverables and is defined by the audio workflow.

Do not call a compressed review MP3 the audio master.

Do not use `final-mix`, `mix-new`, or `audio-last` as filenames.

## Thumbnails

Thumbnail naming distinguishes source components, design candidates, selected
upload images, and platform proof.

Use `thumbnail-source` for a still or graphic used as a design input.

Use `thumbnail-candidate` for an unapproved platform design.

Use `thumbnail` for the exact selected upload image.

Example candidate grammar:

```text
episode-[approved-episode-id]__thumbnail-candidate__[variant-key]__review__r01.png
```

Example selected grammar:

```text
episode-[approved-episode-id]__thumbnail__youtube__approved__r01.png
```

The release manifest must identify the exact thumbnail filename and revision
uploaded to YouTube.

Record the editable design project separately from the flattened upload image.

Do not call a thumbnail `youtube` merely because it is a generic series image
that could be used on YouTube.

Do not overwrite an approved upload thumbnail with a revised design.

Create a new revision and record whether the platform image was changed.

## Prompt Packages

A prompt package is a controlled instruction package, not a generated asset.

It is named here because it must maintain a precise relationship to generated
assets and their handoffs.

The detailed prompt taxonomy, modules, locks, content, and tool practice remain
owned by `09_AI_Production_System/`.

Use `prompt-package` for a bounded package delivered to a generation task.

Use `prompt-instance` where the artifact is a single task-specific prompt.

Example grammar:

```text
shot-[approved-episode-id]-[scene-number]-[shot-number]__prompt-package__flow__approved__r01.md
```

The package record must cite every reusable prompt or module revision it uses.

The package record must cite character, location, object, style, and camera
lock references that constrain the task.

The package record must cite the output candidates or selected asset that it
produced when known.

Do not rename a prompt package after the output to imply the output was
guaranteed by the prompt.

Do not use an output asset revision as the prompt package revision.

## Boards and Visual Planning Assets

Use `board` for a storyboard, shot board, or visual planning deliverable.

Use a qualifier such as `sequence`, `scene`, `shot`, `camera`, or `continuity`
only when it distinguishes the board's declared purpose.

Example grammar:

```text
scene-[approved-episode-id]-[scene-number]__board__shot__review__r02.pdf
```

If a board includes selected stills, the board record must cite their asset IDs
or controlled paths and revisions.

Do not treat embedded board images as replacement source copies.

Do not name a board after an unapproved public title.

Do not use an image candidate filename as the board filename.

## Captions and Subtitles

Use `caption` for a timed caption or subtitle file.

Use an approved language code as the qualifier.

Use a second qualifier only when needed to distinguish a platform-specific,
accessibility-specific, or forced-narrative track that the release workflow
defines.

Example grammar:

```text
episode-[approved-episode-id]__caption__en__approved__r01.vtt
```

Use the same episode scope as the platform master it accompanies.

Record the script or edit revision from which the caption was produced.

Record accessibility review and any platform-specific conversion separately.

Do not call platform-generated automatic captions `approved` until they have
been reviewed and corrected for the intended release.

Do not use `english`, `eng`, and `en` interchangeably; use the language code
defined by the release workflow.

## Edit Projects and Exports

Use `edit-project` for a durable editable timeline or project file.

Use `edit-sequence` for an identified editable sequence when the application
stores or exports it separately.

Use `editorial-export` for a non-release export made for editing or review.

Use `review-proxy` only for a copy made to support review rather than editing.

Example grammar:

```text
episode-[approved-episode-id]__editorial-export__picture-review__review__r03.mp4
```

The edit record must map each editorial export to its source project revision
and selected asset set.

Do not use `platform-master` for a review export.

Do not use an edit-project filename to identify a release-ready video.

## Review Assets

Review assets must distinguish the reviewable media from the review decision.

Use `review-proxy` for the submitted media copy.

Use `review-record` for a review form, annotation export, issue list, or
decision record.

Use `continuity-review`, `technical-review`, `audio-review`, `caption-review`,
or `release-review` as review-type qualifiers where applicable.

Example media grammar:

```text
episode-[approved-episode-id]__review-proxy__continuity__review__r01.mp4
```

Example record grammar:

```text
episode-[approved-episode-id]__review-record__continuity-round-01__approved__r01.md
```

The review record must cite the exact filename, asset ID where applicable,
revision, reviewer role, review scope, disposition, issues, and closure result.

Do not rename a review proxy `approved` because feedback was favorable.

The reviewed asset and the review record have separate identities and may have
different states.

## Release Masters

A release master is an exact approved deliverable, not a general description for
the strongest available file.

Use `release-master` only when the release workflow recognizes a platform-neutral
immutable master.

Use `platform-master` for the approved file prepared for a named platform.

Use `youtube` as the platform qualifier for the exact YouTube upload file.

Example grammar:

```text
episode-[approved-episode-id]__platform-master__youtube__approved__r01.mp4
```

The release manifest must identify the exact master revision, checksum when
feasible, source edit revision, approval record, and intended platform.

Do not put the YouTube public title, video ID, upload timestamp, account name,
or URL in the master filename.

Record those platform values in the release record.

Do not replace an approved master after upload without a correction record and
the required release decision.

## YouTube Support

YouTube is a distribution system, not the authority for studio identity.

The internal episode identity remains the approved studio identifier even when
the public title changes.

The upload file, thumbnail, captions, metadata record, and platform proof must
be traceable to one bounded release package.

Use the internal controlled filename for upload preparation and archive
evidence.

Use the audience-facing public title only in the metadata record and YouTube
interface unless a platform export technically requires it.

Record the YouTube video ID, URL, visibility, entered title, entered
description, publish date and time, thumbnail revision, caption revision, and
post-publication changes in the release record.

Do not use a YouTube video ID as an asset ID or episode ID.

Do not rename an internal master because YouTube changed its processing label.

## Release Metadata Assets

Use `release-metadata` for a controlled record or export of entered platform
metadata.

Use `platform-proof` for an evidence artifact showing what the platform
presented or processed.

Use `release-record` for the controlling publication and correction record.

Example grammar:

```text
episode-[approved-episode-id]__release-metadata__youtube__approved__r01.md
```

Metadata and proof files must identify which master, thumbnail, and caption
revisions they represent.

Do not treat a screenshot as the authoritative editable metadata source.

Do not overwrite published metadata evidence when a later correction is made.

Create a new corrected record and preserve the prior released state.

## Archive Assets

An archive asset is retained history that is not active operational input.

Use `archive-package` for an intentional bundle preserved for recovery,
evidence, transfer, or historical completeness.

Use `archived`, `superseded`, or `rejected` only when the governing workflow
supports that true disposition.

Example grammar:

```text
episode-[approved-episode-id]__archive-package__youtube-release__archived__r01.zip
```

The archive record must identify the archived item's prior active identity,
archive reason, retention basis, date, owner, and successor where applicable.

Do not relabel a current source as archived simply because a copy was made.

Do not use an archive filename to hide unresolved status.

Do not place an unclassified collection of downloads into an archive package.

## Asset Status Rules

Use universal status meanings from `Naming_Standards.md`.

Apply `draft` to an editable or assembled asset not ready for formal review.

Apply `review` to a candidate or record submitted for evaluation.

Apply `approved` only when authorized for its declared asset purpose.

Apply `active` only when an approved reusable asset is the current intended
source for routine new work.

Apply `conditional` only with a named constraint, owner, and expiry or review
point in the asset record.

Apply `rejected` to a retained candidate or record not approved for its
requested purpose.

Apply `superseded` only when the asset record names the approved successor.

Apply `archived` only when current operational use has stopped and retention is
intentional.

Apply `published` to the release record or platform proof when publication is
verified; do not apply it to a source master merely because a derivative was
published.

## Revision Rules for Assets

Use `r01`, `r02`, and subsequent universal revision tokens from
`Naming_Standards.md`.

Increment a revision when the same controlled asset file role has materially
changed.

Create a new derivative role when format, crop, mix, encode, platform target,
or purpose changes materially.

Create a new candidate key when the creative output is independently generated
or conceptually distinct.

Create a new asset ID when the durable asset identity changes.

Do not use revision to express review round, candidate number, or public
publication count.

Do not use a date as a revision substitute.

Do not silently rewrite the content of a file while retaining its revision
token.

## Variant Tokens

A variant token differentiates parallel assets of the same class, subject, role,
state, and revision.

Use variants only when they are stable and bounded.

Permitted patterns include `alt-a`, `alt-b`, `crop-16x9`, `crop-9x16`,
`light-pass`, `dark-pass`, `start-frame`, `end-frame`, `cand-01`, and
`language-[code]` when defined by the relevant workflow.

Do not use a variant to hide an approval state.

Do not use personal initials as a variant unless authorship itself is the asset
subject and the applicable rights record requires it.

Do not use `version-a`, `new-one`, `try-again`, `best`, `better`, or `final`.

If variants become long-lived alternatives, assign them separate controlled
asset records or a documented variant set.

## Derivative Relationships

A derivative is a file created from a source asset, project, generation output,
or other controlled input.

Every retained derivative must identify its immediate source in the asset record
or manifest.

Every selected derivative must identify the selected source revision.

Every release derivative must identify the source edit or master revision.

Every Flow input derivative must identify its original still or reference asset.

Every thumbnail must identify its design source or source component set.

Every caption must identify the script or edit basis.

Do not infer derivation from visual resemblance.

Do not rely on matching filenames to prove derivation.

Use a source asset ID, controlled source filename, immutable storage reference,
or manifest link.

## Continuity Tracking

Asset continuity is the ability to know whether an asset still represents the
same approved character, location, object, visual state, audio state, or story
moment that downstream work expects.

Every selected visual asset must record applicable continuity subjects.

Use the approved IDs or controlled labels for character, location, object,
costume, prop, and setting references.

Record the source revision of each applicable lock or canonical decision.

Record the represented episode, scene, and shot only when those identifiers
exist and apply.

Record the story-state point, screen direction, camera orientation, time of
day, weather, action phase, and object state when the asset's downstream use
depends on them.

Record whether the asset is a continuity source, a single-use depiction, or a
reference only.

Do not create canon by naming a visual state that has not been approved.

Escalate a conflict between a generated asset and canonical continuity rather
than renaming the asset to conceal the conflict.

## Continuity Manifest Fields

For a selected still or Flow clip, the continuity record should identify the
asset ID or controlled filename.

It should identify the exact revision.

It should identify the represented shot or bounded purpose.

It should identify character references and visible appearance state.

It should identify location and geography references.

It should identify object references and relevant object state.

It should identify style and camera lock references where applicable.

It should identify the start state and end state for motion work.

It should identify preceding and following handoff assets when applicable.

It should identify unresolved continuity risks and their owner.

## Collision Prevention

Before assigning an asset name, search the applicable namespace and asset
register.

Check whether the same asset ID already has that file role and revision.

Check whether a similarly named candidate represents the same generation task.

Check whether a case-only or punctuation-only variant already exists.

Check whether a thumbnail, caption, master, or review proxy already serves the
same release purpose.

Check whether a Flow download has already been normalized under its task record.

Check whether a legacy name is mapped to the proposed new name.

Resolve ambiguity before handoff, approval, upload, or archive.

Never solve a collision with `copy`, random characters, a personal initial, or
an undocumented increment.

## Asset Collision Resolution

First determine whether the files are duplicates of the same controlled item.

If they are identical copies, retain one authoritative file and record any
permitted copies.

If they are the same asset role at different controlled iterations, use the
correct revision sequence.

If they are different candidates, assign distinct controlled candidate keys.

If they are different derivatives, add the missing artifact or delivery-role
qualifier.

If they represent different durable reusable identities, assign distinct asset
IDs through the asset register.

If the conflict concerns an approved asset, do not rename or overwrite it
improvisationally.

Record the resolution in the asset manifest, migration record, or change record.

## Legacy Assets

Legacy assets include camera exports, downloads, tool-generated files, personal
working names, pre-standard items, and externally required original names.

Do not assume a legacy filename is wrong merely because it is old.

Migrate a legacy asset when its name or missing identity creates material risk
to retrieval, continuity, rights, automation, review, release, or recovery.

Preserve the original external filename in source metadata when it is relevant
to provenance, legal obligations, or tool recovery.

Assign a governed studio name to a managed operational copy.

Do not alter an original source solely to make its filename look compliant.

Do not silently rename evidence cited by a completed review or published release.

## Legacy Migration Procedure

Inventory each affected file and its existing path.

Identify the proposed governed filename and any new asset ID.

Identify the original filename, source system, source URL or task ID, and
rights information where applicable.

Identify all manifests, edit projects, prompt records, reviews, release records,
and external links that cite the old name.

Classify the item as source, derivative, candidate, selected, release, or
archive material.

Determine whether a rename, an alias, a managed copy, or a new derivative is
the least risky action.

Create an old-to-new mapping with date, owner, reason, and updated references.

Verify the destination name has no collision.

Verify checksum or file identity for high-value or release assets when feasible.

Do not delete the legacy item until recovery, approval, and reference-update
conditions are satisfied.

## Migration of Google Flow Assets

Capture the original Flow export name in the generation record.

Capture the Flow project or task identifier and available generation settings.

Normalize the managed studio copy using the applicable `flow-input` or
`flow-clip` grammar.

Link the controlled filename to the original export name and source task.

Preserve selected original candidates when they are needed to reproduce,
defend, or re-edit the decision.

Do not make browser download order the only candidate identity.

Do not migrate a Flow clip into a reusable visual asset library without an
explicit reuse and provenance decision.

## Migration of YouTube Assets

Preserve the upload filename, published URL, video ID, platform title, and
publication record.

Do not attempt to rename the already-uploaded platform object.

Map the platform object to the controlled studio platform master, thumbnail,
caption, and metadata revisions.

Record any mismatch between a legacy upload filename and the governed internal
name.

For a later correction, create a new controlled revision or correction record;
do not overwrite the historical release evidence.

## Handoffs

Every asset handoff must identify the exact item being handed over.

Provide the asset ID when one exists.

Provide the controlled filename, revision, and authoritative path or URI.

Provide the current status and declared permitted use.

Provide source or prompt lineage sufficient for the receiver to assess
continuity and reproducibility.

Provide relevant rights, restrictions, and expiry conditions.

Provide the applicable review, selection, or approval record.

Provide unresolved risks and the owner of each risk.

Provide the expected next action and receiving role.

Do not hand off a folder or a chat message saying only “use this one.”

## Handoff: Reference to Generation

The reference owner provides the controlled reference filename or asset ID.

The reference owner provides source and rights context.

The prompt or Flow operator records the reference role and exact revision used.

The operator identifies whether the upload is the source file or an upload-copy
derivative.

The generation record links outputs back to the input reference set.

The receiver must not treat a reference image as an approved public-use asset
unless that permission is separately recorded.

## Handoff: Still to Google Flow

The visual operator provides the exact selected-still filename and revision.

The visual operator provides its selection record and continuity constraints.

The Flow operator creates or records the controlled `flow-input` relationship.

The Flow operator records input mode, start and end frame roles, prompt package
revision, task reference, and expected end state.

The Flow operator returns candidate clips with their controlled names and
generation records.

The Flow operator must not modify the selected-still record to imply that
motion output has been approved.

## Handoff: Flow to Edit

The Flow operator provides the selected `flow-clip` filename and revision.

The Flow operator provides the exact source inputs and prompt instance revision.

The Flow operator provides the selection and continuity review evidence.

The editor records whether an editorial derivative is created.

The editor preserves the source Flow clip and does not overwrite it with the
edited derivative.

The editor reports any discovered continuity issue back to the appropriate
owner rather than correcting canon locally.

## Handoff: Audio to Edit

The audio owner provides the asset ID or controlled audio filename and revision.

The audio owner provides declared role, duration, technical format, rights
status, and permitted use.

The editor records the exact audio revision used in the edit or mix record.

The editor creates a new derivative when processing materially changes the
retained audio.

The editor does not rename a source recording as an episode mix.

## Handoff: Edit to Release

The editor provides the exact platform master candidate, thumbnail, captions,
and metadata record revisions.

The release owner verifies that each component can be matched to its review and
approval evidence.

The release owner records the final package manifest before upload.

The release owner records the platform outcome after upload.

The release owner preserves the immutable approved delivery items and platform
proof according to the applicable retention rule.

## Roles and Responsibilities

Roles may be held by one person, but their decisions remain distinguishable.

The Asset Steward maintains the asset register, namespaces, identity mappings,
and asset migration records.

The Asset Steward does not override canon, rights, or release approval.

The Canon Owner confirms whether a represented identity or continuity label is
canonical and resolves canon conflicts.

The Reference or Research Owner confirms source identity, provenance, and
applicable use cautions.

The AI Production System Owner maintains prompt and generation lineage
requirements for AI-produced work.

The Google Flow Operator records task, input, output, and settings relationships
and does not treat a tool label as the controlling studio record.

The Visual Lead or Shot Owner selects visual assets for their declared
production purpose and records continuity evidence.

The Audio Owner controls source, voice, music, SFX, mix, and rights relationships
within the audio workflow.

The Editor records editorial derivation and protects source-versus-export
distinctions.

The Review Owner records review scope, disposition, blocking findings, and
closure evidence.

The Release Owner identifies exact public deliverables and platform outcomes.

The Studio Owner resolves cross-system naming disputes and approves material
exceptions to this manual.

## Naming QA

Perform asset naming QA before a retained asset enters shared use, formal review,
selection, reusable approval, release preparation, archive, or migration.

Verify that the grammar follows `Naming_Standards.md`.

Verify that the asset class accurately describes the file's role.

Verify that the subject or asset ID is approved, assigned, or legitimately
pending in the controlled record.

Verify that no episode ID has been invented or inferred.

Verify that state reflects the actual decision.

Verify that revision reflects the actual controlled iteration.

Verify that a candidate key or variant is documented and non-subjective.

Verify that extension matches the actual file format.

Verify that source, prompt, and derivative relationships are recorded.

Verify that rights and reuse scope are available where needed.

Verify that continuity subjects and locks are recorded for selected visual work.

Verify that a collision and near-collision search was performed.

Verify that the file's placement follows `Folder_Standards.md`.

## Google Flow QA

Before a Flow task, verify that each input has a controlled source relationship.

Verify the exact start frame and end frame revisions where applicable.

Verify the prompt package or prompt instance revision.

Verify relevant character, location, object, style, and camera lock references.

Verify the task's bounded motion purpose and expected end state.

After generation, verify that each retained output has a candidate identity.

Verify that Flow project or task metadata is in the generation record.

Verify that the selected clip cites its candidate or source relationship.

Verify that no tool export has silently replaced an approved still or clip.

Verify that drift, mismatch, or failure is recorded when it materially informs
the selection decision.

## YouTube Release QA

Verify the exact approved platform master filename and revision.

Verify the exact approved thumbnail filename and revision.

Verify the exact approved caption filenames, language codes, and revisions.

Verify that release metadata cites the intended master and asset revisions.

Verify that the release manifest ties all deliverables to one approved episode
identity when one exists.

Verify that the public title is stored as metadata, not substituted for the
internal identifier.

Verify that the YouTube video ID and URL are recorded outside asset IDs and
filenames.

Verify that platform proof identifies observation date and reviewer.

Verify that correction records preserve earlier release evidence.

## Asset QA Non-Examples

The following names are non-compliant:

```text
best_image.png
final_flow_clip.mp4
ep01_thumbnail_final2.jpg
googleflow_export_3847.mp4
youtube-upload-new.mp4
voice_take_good.wav
IMG_2048_approved.png
caption_english_final.vtt
music_latest.mp3
scene3shot4.png
```

These names fail because they omit durable identity, use invented or undocumented
episode IDs, use ambiguous states, rely on tool exports, or conceal role and
lineage.

## Asset Grammar Examples

The following examples demonstrate grammar only.

Their bracketed components must be replaced only by approved or assigned values.

```text
reference__[source-identifier]__reference-image__location-study__archived__r01.jpg
asset-[approved-id]__reference-image__character-sheet__approved__r02.png
shot-[approved-episode-id]-[scene-number]-[shot-number]__image-candidate__cand-01__review__r01.png
shot-[approved-episode-id]-[scene-number]-[shot-number]__selected-still__start-frame__approved__r01.png
shot-[approved-episode-id]-[scene-number]-[shot-number]__flow-input__start-frame__approved__r01.png
shot-[approved-episode-id]-[scene-number]-[shot-number]__flow-clip__cand-02__review__r01.mp4
shot-[approved-episode-id]-[scene-number]-[shot-number]__flow-clip__selected__approved__r01.mp4
scene-[approved-episode-id]-[scene-number]__voice-take__narration__review__r01.wav
asset-[approved-id]__music-stem__instrumental__approved__r01.wav
asset-[approved-id]__ambience-source__location-bed__approved__r01.wav
episode-[approved-episode-id]__thumbnail-candidate__alt-a__review__r01.png
episode-[approved-episode-id]__thumbnail__youtube__approved__r01.png
shot-[approved-episode-id]-[scene-number]-[shot-number]__prompt-package__flow__approved__r01.md
scene-[approved-episode-id]-[scene-number]__board__shot__review__r02.pdf
episode-[approved-episode-id]__caption__en__approved__r01.vtt
episode-[approved-episode-id]__review-proxy__continuity__review__r01.mp4
episode-[approved-episode-id]__platform-master__youtube__approved__r01.mp4
episode-[approved-episode-id]__archive-package__youtube-release__archived__r01.zip
```

## Exceptions

An asset-naming exception is permitted only when normal compliance creates a
material legal, rights, technical, platform, accessibility, or interoperability
problem.

Convenience, habit, visual preference, and a tool's default export name are not
exception reasons.

The exception record must identify the affected asset or asset class.

The exception record must identify the exact rule that cannot be followed.

The exception record must identify the constraint and its evidence.

The exception record must identify the alternate name or external-name mapping.

The exception record must identify collision, lineage, and retrieval controls.

The exception record must identify the owner, approver, scope, and expiry.

The exception record must identify the cleanup or migration plan.

An exception does not create a new asset namespace or studio convention.

## Emergency Handling

During a release, recovery, or access incident, use the closest compliant name
that preserves the known identity.

Record missing lineage, naming gaps, and temporary external labels in the
incident, asset, or release record.

Do not abandon candidate identity because an export deadline is urgent.

Do not overwrite an approved master, selected still, or source recording to
save time.

Normalize temporary work and update its records as soon as immediate risk is
contained.

## Enforcement

An ambiguous asset name may be returned before review or handoff.

An asset with missing source, prompt, or selection lineage may not be approved
for reuse or release until the gap is resolved or an exception is approved.

A Flow output with no recorded task, inputs, or prompt relationship may not be
treated as a selected production source.

A release package may not proceed when its master, thumbnail, captions, or
metadata cannot be matched to exact controlled revisions.

A contributor must correct a discovered naming defect when doing so is safe.

When correction would disrupt released evidence or active work, use the
controlled migration process rather than an improvised rename.

## Maintenance

Review this manual when new asset classes, generation tools, distribution
platforms, or recurring collision patterns create a durable cross-system need.

Do not add a new class merely because one application has a new export type.

Do not replace an existing clear class with a fashionable synonym.

Assess effects on existing asset registers, prompts, Flow records, edit
templates, release manifests, and archives before changing a class or ID rule.

Plan migration before adopting a breaking asset-identity change.

Keep shared syntax aligned with `Naming_Standards.md`.

Keep custody rules aligned with `Folder_Standards.md`.

## Final Check

Before retaining, selecting, approving, handing off, releasing, or archiving an
asset, ask:

1. Can a future contributor identify this file's role without opening it?
2. Does the name use the correct approved subject or assigned asset ID?
3. Does the name avoid inventing an episode, scene, shot, or canonical identity?
4. Is the state honest for the actual decision?
5. Is the revision a controlled iteration rather than an improvised version?
6. Is the candidate, variant, derivative, or delivery role explicit where needed?
7. Can the asset record identify its source, prompt, inputs, and outputs?
8. Can a reviewer trace selected visual work to continuity evidence?
9. Can a Flow operator identify exact approved inputs and prompt lineage?
10. Can an editor distinguish the source asset from an editorial derivative?
11. Can a release owner identify the exact master, thumbnail, caption, and metadata?
12. Can an archivist explain why this item is retained and what replaced it?

If an applicable answer is no, correct the asset name or its record before the
next governed handoff.

## Guiding Principle

Name each asset so its identity, lineage, decision, and safe next use remain
clear after the person, tool, folder, and moment that created it are gone.
