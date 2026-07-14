# Naming Standards

## Purpose

This manual defines the permanent, studio-wide grammar for naming governed work.

Its purpose is to make every important artifact easy to identify, locate, relate,
review, preserve, and reuse without depending on a person's memory.

A name is operational metadata.

A good name communicates what an artifact is, where it belongs, which work it
serves, its meaningful state, and how it relates to neighboring records.

This manual establishes the shared grammar.

It does not replace the specialist naming manuals listed in
[Related Standards](#related-standards).

Those manuals own detailed rules for their artifact classes.

## Governing Principle

Name work so that a future contributor can identify, retrieve, and safely use it
without guessing.

When readability conflicts with traceability, preserve traceability.

When a shorter name removes necessary meaning, use the clearer name.

When more detail adds noise without distinguishing the artifact, omit it.

## Philosophy

Village Stories is a long-lived production system, not a collection of isolated
uploads or personal working files.

Names must survive handoffs between writers, directors, editors, reviewers,
generative tools, storage providers, and publishing platforms.

Names must remain understandable when viewed outside their original folder.

Names must not require a proprietary application, a hidden conversation, or a
person's recollection to decode.

Names are descriptive, not persuasive.

Do not use names to market an unfinished decision.

Do not use a filename as the only place that stores critical creative or legal
information.

Use the name for identification and retrieval.

Use the governed record, manifest, metadata, or review for detail and evidence.

Prefer stable identifiers over emotional labels.

Prefer explicit status over words such as `final`, `latest`, or `new`.

Preserve historical truth rather than renaming evidence to hide its origin.

## Scope

This standard applies to all studio-governed names, including:

- folders and controlled subfolders;
- documents, spreadsheets, presentations, and forms;
- episode, scene, sequence, and shot records;
- visual, audio, graphic, text, and project assets;
- reusable prompts, prompt modules, and prompt instances;
- research and reference material;
- generated candidates and approved outputs;
- reviews, approvals, issue records, and QA evidence;
- release packages and release archive records;
- Google Flow projects, exports, and linked generation records;
- YouTube upload records, platform deliverables, and post-release corrections.

This standard applies whether the artifact is stored locally, in managed cloud
storage, in a production application, or recorded in a manifest.

This standard applies to humans and automated systems that create names.

This standard does not require every temporary scratch file to receive a full
governed name.

The moment a temporary item is shared, reviewed, used as a source, attached to a
decision, or retained beyond its immediate task, it must receive a governed name
or be recorded in a governed container.

## Authority

`10_Studio_Standards/Naming_Standards.md` is the authority for universal naming
grammar across the studio.

It is subordinate to legal requirements, platform requirements, and approved
canon where those requirements constrain a name or identifier.

It does not change the authority of:

- `01_Canon/` for canonical facts and approved canonical terminology;
- `02_World/`, `03_Characters/`, and `04_Objects/` for named entities;
- `05_Research/` for evidence and source interpretation;
- `06_Story_Engine/` and `07_Episode_System/` for story and episode design;
- `08_Production/` for execution and release workflows;
- `09_AI_Production_System/` for generation controls, locks, and prompt content.

When a specialized naming standard conflicts with this manual's universal
grammar, this manual controls separators, characters, casing, and shared token
order unless the specialized manual explicitly documents an approved exception.

When a canonical proper name conflicts with a generic naming abbreviation,
preserve the canonical proper name in the human-readable label and retain the
generic identifier separately.

## Naming Model

Every governed name is assembled from tokens.

A token is one discrete, meaningful unit of a name.

Tokens must be readable without a legend when the standard token vocabulary is
known.

The canonical file-name model is:

```text
[scope]__[subject]__[artifact]__[qualifier]__[state]__[revision].[extension]
```

Square brackets mean an optional token.

Double underscores separate major tokens.

A token may itself contain hyphen-separated words.

Not every artifact needs every optional token.

Do not add empty placeholders such as `none`, `na`, or `tbd` to a published
governed name.

Use a record field for information that is unknown, pending, or inapplicable.

The canonical folder-name model is:

```text
[order-]purpose
```

Folder names describe a durable responsibility, not a momentary activity.

The canonical human-readable record title model is:

```text
Subject — Artifact — Qualifier
```

Human-readable titles may use spaces and an em dash.

Filesystem names must use the file-name model unless a platform technically
requires another form.

## Required Meaning

A governed name must answer the questions that matter for its class.

At minimum, a controlled file name must identify:

- the artifact class or purpose;
- the relevant scope when it cannot be inferred from the folder;
- the subject or controlled identifier when there is more than one candidate;
- its state or revision when substitution risk exists.

A governed folder name must identify:

- its durable purpose;
- its sequence only when ordering is meaningful;
- its ownership boundary when the surrounding structure does not provide it.

A governed release name must identify:

- the release subject;
- the delivery type;
- the approved release state;
- the revision or correction identity when applicable.

A governed review name must identify:

- the reviewed subject;
- the review type;
- the disposition or review state;
- the review round when more than one exists.

## Token Order

Use tokens in this order when they are needed:

1. scope;
2. subject;
3. artifact;
4. qualifier;
5. state;
6. revision;

Do not move the revision before the artifact.

Do not place a status before the subject.

Do not repeat information already expressed by an earlier token.

Put the broadest distinguishing context first.

Put the most changeable control information last.

Example:

```text
series__episode-placeholder__shot-list__reviewed__r02.xlsx
```

This is readable from left to right: scope, subject, artifact, state, revision.

## Token Vocabulary

Use lower-case kebab-case words inside tokens.

Use singular nouns for an individual artifact class.

Use plural nouns only for a container of multiple comparable items.

Use action-neutral labels such as `review`, `manifest`, `brief`, `record`, and
`package`.

Use controlled terms when they exist in the owning system.

Use canonical character, location, object, and world terms exactly as approved
by their owning authorities.

Do not invent abbreviations for canonical names.

Do not shorten a canonical term merely to make a name compact.

Use a documented identifier where a canonical label would make a filesystem name
unreasonably long.

## Allowed Characters

Filesystem names may contain:

- lower-case letters `a-z`;
- numerals `0-9`;
- hyphens `-` inside a token;
- double underscores `__` between major tokens;
- one final period `.` before a file extension.

Use ASCII characters for governed filesystem names.

ASCII names are portable across tools, operating systems, cloud storage, Google
Flow exports, scripts, and archive systems.

Human-facing titles may use approved Unicode characters only when the platform
and audience require them.

Do not rely on Unicode punctuation to distinguish governed filesystem names.

## Prohibited Characters

Do not use spaces in governed filesystem names.

Do not use slashes, backslashes, colons, semicolons, quotation marks, apostrophes,
question marks, asterisks, pipes, angle brackets, or control characters.

Do not use leading periods.

Do not use trailing periods or trailing spaces.

Do not use repeated punctuation for decoration.

Do not use emoji in governed filesystem names.

Do not use tabs, line breaks, or non-printing characters.

Do not use operating-system path separators inside a token.

Do not use a platform-generated name as the permanent studio name.

## Case Rules

Use lower-case for all governed filesystem names.

Use lower-case for identifiers unless the owning external platform requires
upper-case display.

Use sentence case for document headings and record titles.

Use title case only when an external platform's established style requires it.

Do not use `camelCase`, `PascalCase`, or `SCREAMING_SNAKE_CASE` for new governed
filesystem names.

Do not use case alone to distinguish two artifacts.

Case-sensitive storage is not a valid collision-control mechanism.

## Separator Rules

Use one hyphen between words inside a token.

Use two underscores between major tokens.

Use no underscore other than the two underscores that separate major tokens.

Use no hyphen immediately before or after a double underscore.

Use no consecutive hyphens.

Use no leading or trailing hyphen in a token.

Use no trailing separator before an extension.

Correct:

```text
episode-placeholder__release-package__approved__r01.zip
```

Incorrect:

```text
Episode Placeholder_Final-v1 .zip
```

## Length Rules

Keep a governed filesystem name at or below 120 characters where practical.

Keep each token concise enough to scan in a file browser.

Do not sacrifice required identity solely to meet a preferred length.

When a name becomes too long, replace a repeated long label with its controlled
identifier, then document the identifier in the manifest or record.

Do not remove scope, state, or revision before removing nonessential qualifiers.

Avoid abbreviations that require a private legend.

## Reserved Words

The following words must not appear as a replacement for an approved state:

- `final`;
- `final-final`;
- `final2`;
- `latest`;
- `new`;
- `old`;
- `updated`;
- `copy`;
- `backup`;
- `fix`;
- `real`;
- `use-this`;
- `misc`;
- `temp`;
- `test`.

These words may appear only in a clearly defined artifact token when their
literal meaning is the subject of the artifact, such as a `test-plan`.

Do not use `master` as a status label.

Use the delivery or approval state defined by the governing workflow instead.

## Scope Tokens

Use a scope token only when the folder path does not already establish scope or
when the file will be shared, exported, attached, or indexed independently.

Approved generic scope labels include:

- `series`;
- `episode`;
- `scene`;
- `shot`;
- `asset`;
- `prompt`;
- `reference`;
- `review`;
- `release`;
- `studio`.

These labels describe scope, not an episode identifier.

Do not infer an undocumented episode ID from folder order, upload order, or a
working title.

Until an identifier is officially assigned, use a neutral placeholder in records
such as `episode-id-pending`, or store the artifact in the controlled episode
container without placing a false identifier in its filename.

Replace an approved placeholder only through the applicable migration process.

## Subject Tokens

The subject token identifies the work, entity, or controlled item the artifact
concerns.

Use the official identifier whenever one exists.

Use the canonical approved label where no identifier exists and the name remains
portable and unambiguous.

The subject token must not be a personal opinion, a speculative description, or
a publishing headline.

Examples of subject forms:

```text
character-[controlled-id]
location-[controlled-id]
object-[controlled-id]
episode-[approved-id]
scene-[episode-id]-[scene-number]
shot-[episode-id]-[scene-number]-[shot-number]
```

Bracketed values in examples are placeholders for approved values.

They are not literal filenames and do not establish any episode identifiers.

## Artifact Tokens

The artifact token identifies what the item is.

Use plain, durable nouns.

Common cross-studio artifact tokens include:

- `brief`;
- `outline`;
- `script`;
- `board`;
- `shot-list`;
- `direction-record`;
- `manifest`;
- `prompt`;
- `prompt-module`;
- `reference`;
- `source-note`;
- `review`;
- `qa-record`;
- `approval`;
- `release-package`;
- `release-record`;
- `changelog`;
- `readme`.

Specialist standards define the complete controlled vocabularies for their
domains.

Do not create near-synonyms for an existing controlled artifact token.

For example, do not alternate among `shotlist`, `shot-list`, and `shots`.

## Qualifier Tokens

A qualifier narrows meaning without changing the artifact class.

Use a qualifier only when it distinguishes otherwise similar artifacts.

Useful qualifiers include:

- a delivery target such as `youtube`;
- an orientation such as `landscape` or `vertical`;
- a language code when a controlled localization exists;
- a review round such as `round-02`;
- a source role such as `primary-source`;
- a bounded variant such as `alt-a`.

Do not use a qualifier as a hidden status.

Do not use a qualifier to encode a personal owner unless ownership is the
artifact's actual subject.

Do not use a qualifier to encode an undocumented platform or tool claim.

## State Tokens

State communicates the artifact's operational usability.

Use only a state that is accurate at the time the name is assigned.

Use these general states when applicable:

- `draft`;
- `review`;
- `approved`;
- `active`;
- `conditional`;
- `deprecated`;
- `superseded`;
- `archived`;
- `rejected`;
- `planned`;
- `release-ready`;
- `published`;
- `corrected`;
- `paused`.

The governing workflow owns the meaning and allowed transitions of a state.

Do not use a state token on immutable source evidence unless the state describes
the record rather than asserting something about the source.

For example, use `reference__source-record__archived` for the studio's record,
not `reference__historical-photograph__approved` to imply the source itself was
approved as fact.

## Revision Tokens

Use the universal revision form:

```text
r01
```

Increment revisions in two digits through `r99`.

Use three digits only after `r99`.

Do not use `v1`, `version-2`, `rev-a`, dates, or decimals as a substitute for
the controlled revision token.

A revision identifies a controlled iteration of the same artifact.

A materially different artifact needs its own artifact or qualifier token, not a
revision number alone.

Detailed revision lifecycle, approval, supersession, retention, and recovery
rules belong to `Version_Control.md`.

## Date Tokens

Use dates only when time is an essential retrieval key or an immutable event
identity.

Use ISO order:

```text
yyyy-mm-dd
```

Example:

```text
2026-07-14
```

Use dates in:

- dated review sessions;
- source capture records;
- release events;
- scheduled publication records;
- incident and correction records;
- time-sensitive external exports.

Do not use a date in place of a revision token.

Do not use ambiguous date formats such as `07-14-26`, `14-07-26`, or
`july14`.

Do not use a date merely because a file was saved on that day.

## Time Tokens

Use a time only when multiple governed events on the same date require ordering.

Use 24-hour UTC format:

```text
yyyy-mm-ddtHHMMz
```

Example:

```text
2026-07-14t1030z
```

Use the studio's release record to preserve a local scheduled time and time zone
when that context matters.

Do not put a local time-zone abbreviation into a filesystem name.

## Format and Extension Rules

Use the real file extension supplied by the producing application or tool.

Use lower-case extensions.

Do not put a format token in the name when the extension already communicates it.

Use a format qualifier only when the delivery meaning is not obvious from the
extension.

Examples:

```text
episode-[approved-id]__platform-master__youtube__approved__r01.mp4
episode-[approved-id]__caption__en__approved__r01.vtt
episode-[approved-id]__thumbnail__youtube__approved__r01.png
```

Do not name an MP4 `video.mp4` when it is a controlled platform master.

Do not rename a file extension to make an item appear to be another type.

## Identifier Systems

An identifier is a stable reference, not a descriptive title.

Identifiers exist to prevent ambiguity when titles, labels, or subjects change.

Use identifiers in manifests, review records, links, and cross-system references.

An identifier must be:

- unique within its declared namespace;
- stable after approval;
- machine-readable;
- free of inferred meaning that could become false;
- documented by its owning system.

Do not use a public YouTube video ID as the studio's episode ID.

Do not use a Google Flow project ID as the studio's asset ID.

Record external IDs as linked metadata in the applicable record or manifest.

## Episode, Scene, and Shot Identity

Episode identifiers are assigned only by the authorized episode system.

This manual does not create, reserve, predict, or infer episode identifiers.

Use the exact approved episode identifier wherever an episode reference is
required.

If no approved episode identifier exists, keep the item in its episode container
and use a pending reference only in temporary controlled records.

Scene identity must be scoped to an approved episode.

Shot identity must be scoped to an approved episode and scene.

Use zero-padded numeric sequence components when the owning production system
defines numeric scene or shot numbering.

The generic grammar is:

```text
episode-[approved-id]
scene-[approved-id]-[scene-number]
shot-[approved-id]-[scene-number]-[shot-number]
```

Do not use a scene number without its episode scope in an exported file.

Do not use a shot number as a global identifier.

Do not use editorial order as a substitute for a production shot identifier.

## Document Names

Name governed documents by subject, artifact, applicable state, and revision.

Use a document's folder to carry broad project context whenever possible.

Include scope in an exported or standalone document name.

Examples:

```text
studio__naming-standards__active__r01.md
episode-[approved-id]__script__review__r03.docx
scene-[approved-id]-[scene-number]__direction-record__approved__r02.md
```

Non-examples:

```text
Final Script.docx
script_new.docx
notes for scene 3.docx
```

Do not encode a document author's name in the filename unless authorship is the
document's subject or required by an external submission system.

## Folder Names

Use folders to express a durable containment relationship.

Use an order prefix only where viewers must consume sibling folders in a defined
sequence.

Preserve the current actual top-level numbering and names:

```text
00_Project_Core/
01_Canon/
02_World/
03_Characters/
04_Objects/
05_Research/
06_Story_Engine/
07_Episode_System/
08_Production/
09_AI_Production_System/
10_Episodes/
10_Studio_Standards/
11_Assets/
12_Quality_Assurance/
Archive/
```

The shared numeric prefix is an established root taxonomy.

The coexistence of `10_Episodes/` and `10_Studio_Standards/` is intentional
current structure and must not be “corrected” by renumbering either folder.

Do not create an alternate numbered top-level folder without approved structural
governance.

Detailed placement, folder ownership, and archival rules belong to
`File_Organization.md` when published; until then, follow the applicable
existing structure and do not duplicate folder rules here.

## Asset Names

An asset name must identify the controlled asset, not merely its visual
appearance.

Asset names must allow a reviewer to distinguish source, candidate, approved,
and delivery forms.

Use the asset's approved identifier when one exists.

Use the canonical entity identifier before a descriptive asset role when the
asset represents a known character, location, object, or style.

Example generic form:

```text
asset-[approved-id]__[asset-role]__[state]__r01.[extension]
```

Do not use generic camera-export names such as `IMG_0001` as permanent asset
names.

Do not use subjective labels such as `best`, `nice`, or `cool`.

Detailed asset namespaces, classes, variants, derivatives, and manifests belong
to `Asset_Naming.md`.

## Prompt Names

Prompt names identify a governed instruction artifact, not its generated result.

Name reusable prompts, prompt modules, and episode prompt instances distinctly.

Keep a prompt's purpose and scope visible in its name.

Do not embed the full prompt text in the filename.

Do not call unrelated prompts successive revisions of the same prompt.

Example generic form:

```text
prompt__[scope]__[purpose]__[state]__r01.md
```

Prompt content, module taxonomy, lineage, lock references, tool parameters, and
specialized prompt status rules belong to `Prompt_Naming.md` and
`09_AI_Production_System/`.

## Reference Names

References must preserve source identity before studio interpretation.

Use a source-based subject token when the source has a stable title, creator,
repository identifier, collection code, or accession number.

Use a capture date when the source was obtained from a mutable web location or
time-sensitive platform.

Record the full URL, publisher, access date, rights, and relevance in a source
record or manifest, not only in the filename.

Example generic form:

```text
reference__[source-identifier]__source-record__archived__r01.pdf
```

Do not rename a downloaded source to imply authorship by Village Stories.

Do not remove attribution from a source name solely for visual neatness.

## Output Names

An output is an artifact produced by a tool, process, or render.

Retain the producing tool's generated name only as supplemental metadata.

Assign the studio name before an output enters review, a manifest, a handoff, or
a release package.

Identify whether an output is a candidate, approved derivative, platform master,
or archival copy through its artifact and state tokens.

Example generic form:

```text
shot-[approved-id]-[scene-number]-[shot-number]__visual-output__review__r01.png
```

Do not call an unreviewed generation `approved`.

Do not overwrite an approved output with a newly generated file.

## Review Names

Review records must be traceable to their reviewed subject.

Use the review type and round where multiple review passes occur.

Use the disposition in the record body and, when material, as the state token.

Example generic form:

```text
episode-[approved-id]__continuity-review__round-02__review__r01.md
```

Approval evidence must identify the subject, reviewer role, decision, date, and
applicable revision.

Do not name a review `approved` before the authorized disposition is recorded.

Do not replace a rejected review record with a later approved review record.

Retain both records with their accurate states.

## Release Names

Release names identify controlled delivery artifacts and their relationship to a
release record.

Use `platform-master` for the approved audiovisual delivery source only when the
governing release workflow recognizes it as such.

Use a platform qualifier such as `youtube` where an artifact is prepared for a
specific platform.

Example generic forms:

```text
episode-[approved-id]__platform-master__youtube__approved__r01.mp4
episode-[approved-id]__release-record__youtube__published__r01.md
episode-[approved-id]__release-record__youtube__corrected__r02.md
```

Do not place a YouTube URL, video ID, channel name, or publish title in the
master filename unless a platform transfer workflow technically requires it.

Store those values in the release record.

## Google Flow Applicability

Google Flow-generated work must be traceable to a studio-controlled prompt,
input set, and resulting output selection.

Do not treat a Google Flow project title or generated export name as sufficient
studio identification.

When naming an exported Flow output, use the governed subject and artifact name.

Record the Google Flow project, generation session, model or workflow settings,
prompt reference, input assets, and selection decision in the applicable
generation record or manifest.

Use a tool qualifier only when it helps retrieve or audit a tool-specific
derivative.

Do not make `google-flow` the primary identity of an approved creative asset.

The studio asset or shot identity remains primary.

## YouTube Applicability

YouTube is a distribution platform, not the authoritative store for studio
names, versions, or approvals.

Use a clear, viewer-focused upload title on YouTube when required by publishing
strategy.

Do not force the internal controlled filename to match the public YouTube title.

Record the relationship between internal episode identity, delivery filename,
public title, URL, platform video ID, visibility, and publish time in the release
record.

Use the approved internal name for masters, thumbnails, captions, descriptions,
metadata exports, and release archive records.

After publication, record metadata changes and corrections as new controlled
records rather than silently editing historical evidence.

## Collision Handling

A name collision occurs when two different artifacts would receive the same
governed name in the same namespace.

Never solve a collision by changing case, adding `copy`, adding random letters,
or overwriting an existing artifact.

Resolve collisions in this order:

1. confirm whether the artifacts are actually the same controlled item;
2. reuse the existing name only if it is the same artifact and revision;
3. add the missing approved scope, subject, artifact, or qualifier token;
4. assign or reference the correct controlled identifier;
5. create a new revision only if it is a controlled iteration of the same item;
6. record the resolution in the relevant manifest or change record.

Do not use a revision to distinguish unrelated assets.

Do not create a separate namespace merely to avoid an understandable name.

## Similarity and Near-Collision Checks

Before approving a name, check for:

- names differing only by case;
- singular and plural variants;
- hyphenation variants;
- transposed numerals;
- missing leading zeroes;
- duplicate revision values;
- titles that differ but point to the same controlled identifier;
- tool exports that hide an existing approved file;
- path truncation that makes two names appear identical.

If a search result is ambiguous, pause the handoff or release until identity is
resolved.

## Examples

The following examples show grammar only.

Bracketed components must be replaced by approved values.

```text
studio__naming-standards__active__r01.md
character-[controlled-id]__reference-sheet__approved__r02.pdf
location-[controlled-id]__reference__primary-source__archived__r01.pdf
episode-[approved-id]__script__draft__r01.docx
scene-[approved-id]-[scene-number]__shot-list__review__r02.xlsx
shot-[approved-id]-[scene-number]-[shot-number]__direction-record__approved__r01.md
asset-[approved-id]__audio-ambience__approved__r03.wav
prompt__scene__[purpose]__active__r02.md
reference__[source-identifier]__source-record__archived__r01.pdf
episode-[approved-id]__qa-record__release-ready__r01.md
episode-[approved-id]__platform-master__youtube__approved__r01.mp4
episode-[approved-id]__release-record__youtube__published__r01.md
```

The names above are patterns, not authorization to create any unassigned IDs.

## Non-Examples

The following names are non-compliant:

```text
Final Final.mp4
EP01_scene_1_shot_2_NEW.png
my-cool-prompt-v2.txt
village story latest.docx
Character Reference (approved).pdf
IMG_3847.png
youtube upload final 2.mp4
episode__script__final__v3.docx
review - use this one.md
scene3shot4.png
```

They fail because they use spaces, inconsistent separators, undocumented IDs,
ambiguous statuses, ungoverned versions, missing scope, or uninformative
generated names.

## Migration and Legacy Handling

Do not rename an artifact merely because an older name is imperfect.

Migrate when a legacy name creates a material retrieval, continuity, review,
release, automation, legal, or collision risk.

Before a migration, inventory:

- the current path and name;
- the proposed controlled name;
- the artifact's identifier and revision;
- inbound references and manifests;
- external platform links and tool records;
- ownership and approval status;
- any risk of broken automation or traceability.

Create a migration map containing old name, new name, date, owner, reason, and
reference updates.

Preserve the legacy name in the migration map.

Do not silently rewrite historical review evidence, release records, or external
source attribution.

Use redirects, aliases, or manifest mappings where renaming would break an
approved external reference.

Mark a migrated legacy container as `deprecated` or `archived` through its record
when applicable.

Do not leave two active names for the same controlled artifact after migration.

## Legacy Imports

For imported external material, retain the source filename in metadata or a
source manifest.

Assign a governed studio name to the managed copy when it becomes operational.

Do not remove license notices, credit information, identifiers, or source
attribution from imported material.

If an external system requires the original name, store it unchanged there and
maintain the studio-controlled name in the surrounding record.

## Rename Procedure

Before renaming a governed artifact:

1. confirm the correct owner and authority;
2. confirm the artifact is not referenced by an active release or review;
3. determine whether the change is a correction, migration, or new revision;
4. update manifests, links, and cross-references;
5. preserve a rename record when traceability is affected;
6. verify that the new name has no collision;
7. verify that the prior path remains discoverable through the migration map.

Renaming must not become a substitute for version control.

## Quality Assurance

Run naming QA before approval, handoff, archival, release readiness, and bulk
import.

Confirm that:

- the artifact belongs in the actual current top-level structure;
- required scope and subject information are present;
- canonical names and identifiers match their owning records;
- filesystem characters, casing, and separators comply;
- state and revision are accurate;
- the extension matches the actual file format;
- no collision or near-collision exists;
- related manifests and review records use the same identifier;
- a release filename matches the approved release record;
- Google Flow and YouTube external IDs are recorded outside the name where needed;
- no undocumented episode ID was invented;
- any exception has a traceable approval.

Automated checks may validate grammar.

Automated checks must not infer creative or canonical correctness from grammar
alone.

## QA Sampling

For a small handoff, inspect every governed name.

For a large batch, inspect every new root item, every master, every release
artifact, every changed identifier, and a representative sample of derivatives.

Increase sampling to full inspection when a naming defect affects a shared
template, automated export, migration, or release package.

Correct systemic defects at the source process, not one filename at a time.

## Exceptions

An exception is allowed only when compliance would create a material technical,
legal, platform, accessibility, or interoperability problem.

Convenience is not an exception reason.

An exception request must state:

- the affected artifact class;
- the rule that cannot be followed;
- the technical or operational reason;
- the proposed alternate syntax;
- the scope and expiry;
- collision and retrieval controls;
- owner and approver;
- migration or cleanup plan if required.

Record approved exceptions with the affected work.

An exception applies only to its declared scope.

It does not amend this standard.

Expire or review recurring exceptions.

A recurring exception is evidence that a specialist standard, workflow, or tool
integration may need a formal update.

## Emergency Naming

During a time-critical incident, use the closest compliant name available and
record the gap in the incident or release record.

Do not abandon traceability because a deadline is urgent.

Normalize the name, manifests, and references as soon as the immediate risk is
contained.

Do not use emergency handling to bypass approval or correction records.

## Relationships and Continuity

The same controlled identifier must refer to the same subject across documents,
assets, prompts, outputs, reviews, and releases.

A rename of a canonical subject requires its owning authority and a documented
continuity plan.

An asset's display label may change without changing its stable identifier.

A YouTube title may change without changing the internal episode identity.

A Google Flow project may be duplicated without creating a new studio asset
identity unless the resulting asset is materially distinct.

When identity changes, create a new controlled artifact and link its lineage.

When only a revision changes, preserve the base identity and increment the
revision through the applicable version-control process.

## Cross-System Handoffs

Every handoff that crosses a system boundary must preserve:

- the controlled identifier;
- the governed name;
- the applicable revision;
- the source location or manifest;
- the current state;
- the receiving system's external ID when created;
- the responsible owner where needed.

Do not rely on an email subject, chat message, browser tab title, or upload order
as a durable handoff identifier.

## Related Standards

This manual provides the universal grammar and must be read with the following
specialist standards as they are published:

- `Asset_Naming.md` for asset classes, asset IDs, variants, derivatives, and
  asset-manifest requirements;
- `Prompt_Naming.md` for prompt classes, module identity, instances, lineage,
  and prompt-specific status rules;
- `Version_Control.md` for revision lifecycle, approvals, supersession,
  changelogs, retention, recovery, and rollback;
- `File_Organization.md` for folder placement, ownership, storage boundaries,
  archives, and permitted containment patterns.

These standards must reference this manual for shared character, case, separator,
date, state, and collision rules.

They must not silently redefine universal grammar.

This manual must not duplicate their detailed artifact-specific rules.

## Relationship to Existing Systems

Use `01_Canon/`, `02_World/`, `03_Characters/`, and `04_Objects/` to obtain
approved names and identifiers for subjects.

Use `05_Research/` to preserve source identity and attribution.

Use `06_Story_Engine/` and `07_Episode_System/` to determine the correct story,
episode, scene, and format context.

Use `08_Production/` to determine production-stage records and release workflow.

Use `09_AI_Production_System/` to determine prompt content, locks, generation
requirements, and tool controls.

Use `10_Episodes/` for episode-specific records according to its established
structure.

Use `11_Assets/` for asset storage according to the applicable organization and
asset-naming standards.

Use `12_Quality_Assurance/` for governed QA evidence where its structure applies.

## Enforcement

Non-compliant names must be corrected before an artifact becomes an approved
shared source, release artifact, or archival record unless an approved exception
exists.

Reviewers may return a handoff for naming correction without evaluating its
creative content when identity is ambiguous.

Release approval must not proceed when the master, captions, thumbnail,
metadata, or release record cannot be unambiguously matched.

Automation that creates governed names must implement this grammar or route its
output through a controlled naming step.

## Maintenance

Changes to this standard require evidence that the change improves traceability,
compatibility, continuity, retrieval, or operational safety.

Before changing universal grammar, assess:

- effects on existing names;
- migration requirements;
- cross-platform filesystem compatibility;
- Google Flow and YouTube workflow effects;
- automated tool and template effects;
- specialist-standard conflicts;
- training and communication needs.

Do not change a universal rule to accommodate one isolated file.

Record approved changes and communicate migration expectations before adoption.

## Final Check

Before creating, approving, or transferring a governed item, ask:

1. Can a future contributor identify it without asking the creator?
2. Does its name use an approved subject or controlled identifier?
3. Does it describe an artifact rather than an opinion?
4. Is its state honest and its revision controlled?
5. Can it coexist with similar work without collision?
6. Does it preserve continuity across documents, prompts, assets, reviews, and releases?
7. Does it avoid inventing an undocumented episode ID?
8. Can a Google Flow or YouTube record link to it without replacing its identity?

If the answer to any applicable question is no, correct the name or request an
approved exception before proceeding.

## Guiding Principle

Make every name clear enough to survive the person, tool, folder, and moment
that created it.
