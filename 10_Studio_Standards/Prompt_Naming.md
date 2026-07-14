# Prompt Naming

## Purpose

This manual defines the permanent naming and identity controls for governed
prompt work in Village Stories.

It makes a prompt, module, lock packet, reference bundle, generation record,
QA record, and selected output traceable without treating any one tool as the
source of truth.

Prompt naming is an operational control.

It prevents an operator from using the wrong reusable instruction, silently
changing a lock, confusing an image prompt with an animation prompt, or losing
the connection between a selected output and the instructions that produced it.

This manual answers:

- what a prompt artifact is called;
- when it receives a stable prompt identifier;
- how reusable sources differ from task-specific derived prompts;
- how modules, locks, references, and safe variables are named and recorded;
- how Google Flow work and YouTube release evidence retain prompt lineage; and
- how prompt revisions, reviews, migrations, and handoffs remain auditable.

It is a naming and lineage manual.

It does not prescribe prompt prose, creative content, tool operation, visual
style, camera direction, voice performance, or acceptance criteria.

Those controls remain with their owning manuals and approved source records.

## Guiding Principle

Name every retained prompt artifact so a future contributor can identify its
purpose, scope, authority, revision, and relationship to outputs without
guessing.

When brevity conflicts with traceability, preserve traceability.

When a tool label conflicts with studio identity, preserve studio identity.

When a prompt is reused, preserve the source relationship rather than creating
an untracked copy.

When an output is selected, preserve the exact prompt revision and input set
that produced it.

## Scope

This manual applies to retained, shared, reviewed, selected, approved, handed
off, released, or archived prompt-related work.

It applies whether work is stored in the repository, managed production
storage, Google Flow, another generation tool, an editing system, or a release
record.

It applies to humans and automation that create prompt names, prompt IDs,
generation records, manifests, exports, or migration maps.

It applies to:

- reusable master prompts;
- reusable prompt modules;
- lock packets and lock references;
- task assemblies and tool-ready prompt instances;
- image prompts;
- animation and Google Flow prompts;
- voice prompts and voice-direction packets;
- negative modules and repair prompts;
- source and reference bundles;
- input-reference manifests;
- generation and tool-session records;
- candidate and selected-output lineage records;
- prompt QA, review, approval, rejection, and revision records;
- prompt-to-output lineage manifests;
- YouTube release records that depend on generated work; and
- archived prompt evidence.

This manual does not require a governed name for an unshared one-line scratch
instruction that is immediately discarded.

The item becomes governed when it is reused, sent to a tool for retained work,
attached to a review, cited by an output, used in a handoff, or retained beyond
the immediate task.

## Boundaries

`Naming_Standards.md` is authoritative for universal filename grammar,
characters, case, separators, generic states, revision tokens, collision
handling, and universal migration rules.

`Asset_Naming.md` is authoritative for asset IDs, asset classes, media output
names, derivatives, and asset manifests.

`Folder_Standards.md` is authoritative for placement, custody, source/derived
separation, and folder ownership.

`09_AI_Production_System/` is authoritative for prompt content, module
architecture, lock content, tool practices, generation controls, prompt QA,
and revision workflow.

This manual supplies the specialist naming vocabulary and lineage rules that
connect those systems.

It must not duplicate their detailed creative or operational instructions.

Where a conflict appears, apply the highest relevant authority.

Do not resolve a conflict by inventing a new prompt name or silently copying a
source prompt into a local folder.

## Authority

The authority order for a prompt-related naming decision is:

```text
Legal, rights, safety, and platform obligations
↓
Approved canon and governing source records
↓
Approved episode, scene, storyboard, and continuity decisions
↓
10_Studio_Standards/Naming_Standards.md
↓
This Prompt Naming manual
↓
09_AI_Production_System prompt and lock controls
↓
Task prompt, tool settings, generated candidate, and export
```

The order resolves conflicts.

It does not transfer ownership of a source record to the prompt operator.

A prompt can cite a character, location, object, style, camera, or voice
authority.

It cannot become the permanent authority for that fact.

An approved prompt name is not evidence that its content is canon-safe.

An approved output name is not evidence that the prompt was approved.

Approval remains decision-specific and must be recorded by the applicable
workflow.

## Terms

`prompt ID` is the stable identifier for one governed prompt artifact.

`module ID` is the stable identifier for one reusable bounded instruction block.

`lock packet` is a task-relevant set of referenced locks, not a new authority.

`assembly` is the chosen source prompt, modules, locks, references, and approved
variables for one bounded task.

`prompt instance` is the task-specific, tool-ready instruction produced from an
assembly.

`reference bundle` is the controlled manifest of source records and attached
inputs used for a task.

`generation record` is the factual record of a tool submission, inputs,
settings, and outputs.

`lineage record` is the durable map from a source prompt through an instance and
generation record to candidate, selected, derived, or released output.

`source` is an authoritative input or record from which a prompt is assembled.

`derived` is an artifact produced from source prompt work, such as an instance,
rendered prompt export, candidate, or editorial derivative.

`archive` is retained historical evidence that is no longer active operational
input.

`safe variable` is a task-specific value explicitly permitted to vary by the
relevant source and continuity record.

`unsafe variable` is a value that would alter a continuing fact, lock, rights
condition, platform obligation, or approved production decision.

## Core Naming Model

All governed filesystem names use the universal grammar:

```text
[scope]__[subject]__[artifact]__[qualifier]__[state]__[revision].[extension]
```

Use lower-case ASCII characters.

Use hyphens inside a token.

Use double underscores between major tokens.

Use an accurate state and a controlled revision token.

Do not place blank, guessed, or decorative tokens into a name.

Prompt-specific artifacts use this model by selecting the correct artifact
token and a bounded qualifier.

The base prompt-family model is:

```text
prompt__[prompt-id]__[artifact]__[qualifier]__[state]__r01.md
```

The base task-instance model is:

```text
[task-subject]__prompt-instance__[purpose]__[state]__r01.md
```

The base record model is:

```text
[task-subject]__[record-type]__[purpose]__[state]__r01.md
```

Bracketed values are placeholders.

They must be replaced only with approved controlled values.

They are not literal names and do not create or imply episode identifiers.

## Prompt IDs

Prompt IDs provide stable identity when a human-readable name changes, when a
prompt is reused across tasks, or when a source prompt must be cited outside its
folder.

A prompt ID identifies one governed prompt artifact.

It does not identify every output produced by that prompt.

It does not replace an asset ID, task ID, Google Flow task ID, or YouTube video
ID.

Use the following grammar:

```text
prm-[class]-[stable-key]
```

Examples of class tokens:

- `master` for a reusable master prompt;
- `module` for a reusable instruction module;
- `lock` for a maintained lock packet record;
- `image` for a reusable image-prompt source;
- `animation` for a reusable animation-prompt source;
- `voice` for a reusable voice-prompt source;
- `repair` for a reusable controlled repair prompt; and
- `qa` for a reusable QA prompt or review template.

The `stable-key` is a controlled, durable label or assigned non-semantic key.

It must not encode a guessed episode number, a public title, a contributor name,
or a temporary tool session.

Examples of valid ID patterns:

```text
prm-master-[stable-key]
prm-module-[stable-key]
prm-lock-[stable-key]
prm-image-[stable-key]
prm-animation-[stable-key]
prm-voice-[stable-key]
```

The examples establish grammar only.

They do not reserve any stable key.

Do not treat a filename revision as part of the prompt ID.

Do not change a prompt ID merely because its wording receives a controlled
revision.

Create a new prompt ID when purpose, authority, reusable scope, or semantic
identity materially changes.

Record predecessor and successor IDs in the lineage or migration record.

## Module IDs

Use module IDs for reusable instruction blocks that can be selected in multiple
assemblies.

Use this grammar:

```text
mod-[domain]-[stable-key]
```

Approved domain families include:

- `canon`;
- `character`;
- `location`;
- `object`;
- `style`;
- `camera`;
- `motion`;
- `voice`;
- `audio`;
- `format`;
- `negative`;
- `qa`; and
- `repair`.

Examples of valid patterns:

```text
mod-character-[stable-key]
mod-location-[stable-key]
mod-style-[stable-key]
mod-camera-[stable-key]
mod-negative-[stable-key]
```

A module ID is stable across wording revisions of the same module.

A module revision identifies the exact content selected for an assembly.

Do not create near-duplicate module IDs for a spelling change or a single
task-specific variable.

Do not use a module ID for a pasted excerpt whose authority is not recorded.

## Lock Packet Identity

A lock packet is a controlled task-facing record of which source locks apply.

It is not a new canon record.

It is not permission to edit a lock locally.

Use `lock-packet` as the artifact token.

Use a bounded task or reusable scope as the subject.

Examples:

```text
prompt__prm-lock-[stable-key]__lock-packet__active__r01.md
[task-subject]__lock-packet__generation__review__r01.md
```

The lock packet must identify:

- its packet ID or controlled record identity;
- the exact source paths or source IDs;
- the source revisions or immutable references;
- each lock’s role in the task;
- the task scope;
- the assembly or prompt instance it constrains;
- its current state; and
- its owner or escalation route.

Do not paste lock text into an instance without recording the source lock
reference and revision.

Do not name an assembly `lock-packet` merely because it includes one lock.

## Artifact Vocabulary

Use the following controlled artifact tokens for prompt work.

| Artifact token | Use |
| --- | --- |
| `master-prompt` | Reusable top-level prompt source |
| `prompt-module` | Reusable bounded instruction block |
| `lock-packet` | Task-relevant record of applied lock sources |
| `prompt-assembly` | Selected components before tool-ready rendering |
| `prompt-instance` | One bounded tool-ready task prompt |
| `image-prompt` | Image-specific source or instance where needed |
| `animation-prompt` | Animation-specific source or instance where needed |
| `voice-prompt` | Voice-specific source or instance where needed |
| `negative-module` | Controlled reusable negative instruction block |
| `reference-bundle` | Input-source and attachment manifest |
| `generation-record` | Tool submission and output record |
| `lineage-record` | Prompt-to-output relationship record |
| `prompt-qa-record` | Prompt review and QA evidence |
| `revision-record` | Controlled prompt-change decision record |
| `selection-record` | Candidate-to-selected-output decision record |
| `handoff-record` | Cross-role or cross-system transfer record |
| `migration-map` | Legacy-to-governed prompt identity map |

Use an existing universal artifact token where it describes the item more
accurately.

For example, use `review-record` for a broad review decision governed under
asset or production naming rules.

Do not create synonyms such as `prompt-text`, `ai-prompt`, `flow-prompt-file`,
or `magic-prompt` when a controlled artifact token applies.

## Prompt Classes

Prompt class identifies the primary job of a reusable prompt or task instance.

Use a class in the prompt ID and, where needed, as a filename qualifier.

The primary prompt classes are:

- `story`;
- `script`;
- `image`;
- `animation`;
- `voice`;
- `audio`;
- `thumbnail`;
- `metadata`;
- `qa`;
- `repair`; and
- `archive`.

A class describes the prompt’s main output purpose.

It does not assert that an output was accepted.

Use one primary class.

If a task needs multiple output types, create distinct prompt instances and
link them through the same assembly or lineage record.

Do not call a mixed instruction file a single image prompt if it contains
independent image, motion, voice, and release decisions.

## Source and Derived Prompt Work

Every governed prompt artifact must have one custody relationship:

- source;
- derived; or
- archive.

The custody relationship must be clear from its record, placement, status, or
manifest.

### Source prompt work

Source prompt work includes approved reusable master prompts, reusable modules,
maintained lock records, controlled templates, and approved reusable QA
structures.

Source prompt work has one authoritative home.

It may be referenced from an episode or tool record.

It must not be copied into an episode workspace as an independently editable
source.

### Derived prompt work

Derived prompt work includes task assemblies, prompt instances, rendered
tool-ready text, bounded repair prompts, reference bundles, generation records,
and task-specific QA evidence.

Derived prompt work must identify its source prompt, selected module revisions,
lock references, and safe-variable record where applicable.

Derived prompt work must not be promoted into a reusable source merely because
it produced an attractive candidate.

Promotion requires review by the owning prompt system.

### Archive prompt work

Archive prompt work includes superseded source revisions, retired modules,
closed task instances, rejected candidates that remain evidential, historical
Google Flow records, and released prompt-to-output lineage snapshots.

Archive material must identify why it is retained.

Archive material must identify its active successor or final disposition when
one exists.

Do not reopen an archived prompt by removing `archived` from a copied filename.

Create a controlled restoration or new revision record instead.

## Status Rules

Use universal state tokens from `Naming_Standards.md`.

For prompt artifacts, apply them with the following meanings.

`draft` means the artifact is editable and has not passed its applicable review.

`review` means it is submitted for a named review, not that review passed.

`approved` means the named revision is authorized for its declared use.

`active` means the reusable source revision is the current approved operational
source for its declared scope.

`conditional` means it may be used only under a documented limitation.

`planned` means a controlled artifact is proposed but not ready for use.

`paused` means work is intentionally stopped with an owner and reopening route.

`deprecated` means a source remains readable but must not be selected for new
work.

`superseded` means a successor revision or prompt ID has replaced it.

`rejected` means the artifact or candidate failed its stated gate.

`archived` means the artifact is retained history and not current input.

Do not use `final`, `latest`, `new`, `use-this`, or tool-interface labels as
prompt states.

Do not call a prompt `approved` because it was submitted to a tool.

Do not call a candidate `approved` because it resembles the intended result.

## Revision Rules

Use the universal revision token:

```text
r01
```

Increment the revision when the controlled artifact changes while retaining the
same semantic identity.

The revision applies to the named artifact only.

An output revision does not automatically revise its source prompt.

A changed prompt instance does not automatically revise its reusable module.

A changed Google Flow submission record does not automatically revise an image
source prompt.

Create a new revision when any retained prompt wording, approved safe variable,
attachment selection, tool parameter, lock reference, source reference, or QA
decision changes in a way that affects reproducibility or review.

Create a new prompt ID rather than a new revision when the reusable purpose,
authority boundary, intended output class, or ownership materially changes.

Every revision record must state:

- the exact prior artifact identity and revision;
- the exact new artifact identity and revision;
- the reason for change;
- the change category;
- the affected sources, locks, variables, or settings;
- the expected impact;
- the reviewer or approver when required;
- linked outputs that may need recheck; and
- whether a successor, supersession, or migration applies.

Do not use a date, a contributor initial, or a tool run count as a revision
token.

## Safe Variables

Safe variables are controlled task fields, not free-form opportunities to
rewrite a prompt.

Every safe variable must have:

- a variable key;
- a human-readable label;
- a permitted value or value source;
- an owning authority;
- a task scope;
- a validation rule;
- a continuity effect when applicable; and
- an explicit state when unresolved.

Use lower-case kebab-case keys.

Examples of safe-variable keys:

```text
visible-action
current-pose
expression-range
time-of-day
weather-state
light-direction
object-handler
object-state
shot-size
framing-priority
camera-start-state
camera-end-state
motion-change
delivery-ratio
voice-pace
pronunciation-note
repair-target
```

The key is not a filename.

Record it in an assembly, instance, generation record, or variable manifest.

Use the variable value only after confirming its approved source.

Examples of values that may be safe when the applicable source permits them:

- the visible action for the specified shot;
- a scene-approved weather condition;
- the approved time-of-day state;
- a selected framing within the camera plan;
- an approved aspect ratio or crop-safe requirement;
- a bounded Google Flow motion change;
- a narration pace within the voice direction;
- a repair target named by a QA record.

Examples of unsafe values unless separately approved:

- a changed character identity, age, relationship, or signature appearance;
- a new location layout or unseen room;
- a changed recurring object material, count, or ownership;
- a conflicting period detail;
- a new canonical event or outcome;
- a new camera geography that contradicts the board;
- a new voice identity or rights assumption;
- a tool default that overrides an approved lock; or
- a public-title claim inserted into the internal creative prompt.

If a value cannot be classified as safe, treat it as open.

Do not hide an open value behind `tbd`, `maybe`, or a vague qualifier in a
filename.

Use `hold`, name the owner, and resolve it through the applicable source.

## Safe-Variable Record

Use a safe-variable record within the prompt assembly or as a linked controlled
record when the task needs detailed variable governance.

Minimum fields are:

```text
Task subject:
Prompt instance:
Variable key:
Proposed value:
Source path or controlled ID:
Source revision or date:
Authority owner:
Validation method:
Continuity dependency:
Decision state:
Reviewer, if required:
```

Do not record sensitive account credentials, private personal data, or access
tokens as variables.

Reference secure credential management when a tool requires access.

## Reusable Master Prompts

Use `master-prompt` for a retained reusable prompt that coordinates a broad
production function.

Example pattern:

```text
prompt__prm-master-[stable-key]__master-prompt__active__r01.md
```

The record must identify:

- prompt ID;
- purpose and declared reuse scope;
- owner;
- applicable source authorities;
- module-selection rules;
- permitted task classes;
- prohibited uses;
- required QA path;
- revision history; and
- deprecation or successor information when applicable.

Do not name a task-specific prompt instance `master-prompt`.

Do not call a prompt master merely because it is long.

## Prompt Modules

Use `prompt-module` for a reusable bounded instruction block.

Example pattern:

```text
prompt__prm-module-[stable-key]__prompt-module__active__r01.md
```

The module record must cite its module ID.

It must state its domain, purpose, trigger, owner, source authority, immutable
instructions, permitted variables, dependencies, incompatible combinations, and
validation method.

The complete module architecture remains governed by
`09_AI_Production_System/07_Prompt_Modules.md`.

This manual governs the module’s name and its relationship to assemblies.

Do not name a copied module excerpt as a new module without an assigned module
ID and an owner.

## Prompt Assemblies

Use `prompt-assembly` for the controlled selection of source prompt, modules,
locks, references, and variables before text is rendered for a specific task.

Example pattern:

```text
[task-subject]__prompt-assembly__[purpose]__review__r01.md
```

An assembly must identify:

- its bounded task subject;
- source master prompt ID and revision, if used;
- selected module IDs and revisions;
- lock packet or lock-source references;
- safe-variable record;
- reference-bundle identity;
- requested output class;
- tool target when relevant;
- expected output relationship;
- reviewer and readiness state; and
- the prompt instance derived from it.

An assembly is not automatically tool-ready.

It becomes generation-ready only after the applicable prompt QA gate.

## Prompt Instances

Use `prompt-instance` for a task-specific tool-ready instruction.

The instance is a derived record.

It must not replace the reusable master prompt or modules from which it was
assembled.

Examples:

```text
[task-subject]__prompt-instance__image__review__r01.md
[task-subject]__prompt-instance__animation__review__r01.md
[task-subject]__prompt-instance__voice__review__r01.md
```

Each instance must identify:

- task subject and intended output;
- prompt class;
- parent assembly;
- all selected source prompt and module revisions;
- lock packet references;
- reference bundle;
- resolved safe variables;
- declared tool target;
- exact tool-ready text or immutable export;
- readiness or review state; and
- resulting generation record when submitted.

Do not use one prompt instance for unrelated shots or voice units.

Do not silently edit a submitted prompt instance after outputs exist.

Create a new controlled revision and record which submission used it.

## Image Prompt Naming

Use `image` as the qualifier for an image-specific prompt source, assembly, or
instance.

Examples:

```text
prompt__prm-image-[stable-key]__image-prompt__active__r01.md
[task-subject]__prompt-instance__image__review__r01.md
[task-subject]__generation-record__image__review__r01.md
```

The image record must distinguish:

- a reusable image-prompt source;
- the task-specific instance;
- attached reference images;
- generated image candidates; and
- the selected still, if any.

Image-candidate and selected-still names remain governed by `Asset_Naming.md`.

Do not name a selected still after the prompt ID alone.

Record the prompt ID and revision in its asset lineage instead.

## Animation Prompt Naming

Use `animation` as the qualifier for a motion or animation-specific prompt
source, assembly, or instance.

Examples:

```text
prompt__prm-animation-[stable-key]__animation-prompt__active__r01.md
[task-subject]__prompt-instance__animation__review__r01.md
[task-subject]__generation-record__animation__review__r01.md
```

An animation prompt instance must distinguish its source still or start state
from its requested motion change.

When an end state is used, record that input as a distinct reference role.

Do not hide a changed start frame, end frame, motion instruction, duration,
camera movement, or aspect ratio in an untracked tool session.

Record it in the assembly, instance, or generation record.

Google Flow clip names remain governed by `Asset_Naming.md`.

## Voice Prompt Naming

Use `voice` as the qualifier for voice-specific source prompts, direction
packets, and task instances.

Examples:

```text
prompt__prm-voice-[stable-key]__voice-prompt__active__r01.md
[task-subject]__prompt-instance__voice__review__r01.md
[task-subject]__generation-record__voice__review__r01.md
```

The voice prompt instance must identify the narration or dialogue unit it
serves, the script source and revision, pronunciation evidence where needed,
voice direction source, safe pace or emphasis variables, delivery purpose, and
resulting audio asset relationship.

Do not encode an actor, contributor, account, or voice-provider secret in a
filename.

Do not use an audio asset name as the voice-prompt name.

Audio asset naming remains governed by `Asset_Naming.md`.

## Reference Bundles

Use `reference-bundle` for the controlled manifest of all source references and
attachments supplied to a generation task.

Example pattern:

```text
[task-subject]__reference-bundle__[purpose]__approved__r01.md
```

A reference bundle must identify each item’s:

- controlled asset ID or source path;
- exact revision where applicable;
- role, such as identity, location, style, start frame, end frame, object, or
  voice source;
- custody class;
- rights or reuse caution when relevant;
- attachment form, such as original, upload copy, crop, or proxy;
- authority source; and
- relationship to the prompt instance.

A reference bundle does not make every attachment an approved reusable asset.

Do not use a file browser order, upload order, or tool thumbnail order as the
only reference identity.

Do not attach a reference image without naming its explicit task role.

## Reference Upload Copies

An upload copy is a derived technical convenience, not the authoritative source
asset.

Name it under asset naming rules as a derivative or record it in the reference
bundle as an upload-copy relationship.

The bundle must point to the source asset ID or controlled path and revision.

Do not replace a high-quality source reference with an upload copy.

Do not omit the source relationship because a tool rewrites the uploaded
filename.

## Google Flow Records

Google Flow is a production environment, not the authority for prompt identity,
source identity, or approval.

Use a controlled generation record for each retained Flow task or bounded
submission group.

Example pattern:

```text
[task-subject]__generation-record__google-flow__review__r01.md
```

`google-flow` is a tool qualifier.

It must not replace the shot, asset, prompt, or episode identity in a governed
record.

A Google Flow generation record must identify:

- controlled task subject;
- Flow project reference or URL, when available;
- Flow task, generation, or session reference, when available;
- date and time of submission when material;
- prompt instance ID and exact revision;
- prompt assembly ID and exact revision;
- reference bundle ID and exact revision;
- source image, start frame, and end frame roles and revisions;
- selected locks and safe variables;
- model, mode, duration, ratio, and relevant settings as reported;
- submitted text or immutable prompt-instance export;
- candidate output names or tool references;
- reviewer decision;
- selected output, if any; and
- unresolved drift, error, or continuity risks.

Do not use a Flow project title as a studio prompt ID.

Do not use a Flow task ID as a studio asset ID.

Do not name a candidate `approved` because the Flow interface displays it first.

## Google Flow Project Records

If a Flow project is retained as a meaningful production boundary, record it in
a project record or generation manifest.

Use an accurate bounded name such as:

```text
[scope-subject]__flow-project-record__generation__active__r01.md
```

The record must link the external Flow project identity to studio-controlled
task subjects and generation records.

One Flow project may contain multiple task records.

One studio task may require more than one Flow submission.

Do not infer lineage from the project name alone.

## Google Flow Prompt-to-Output Chain

For each selected Flow output, preserve this chain:

```text
source prompt and module revisions
→ lock packet and safe variables
→ reference bundle and input assets
→ prompt assembly
→ exact prompt instance
→ Google Flow generation record
→ candidate output
→ selection record
→ selected source clip or still
→ editorial derivative, if created
→ release component, if used
```

Each arrow must be represented by a record field, controlled identifier, path,
or manifest entry.

Do not rely on memory, browser history, a chat transcript, or an account login
to reconstruct an arrow.

## YouTube and Prompt Lineage

YouTube is a distribution platform.

It does not become the authority for prompt identity because a generated output
was published there.

When a generated output contributes to a YouTube release, the release manifest
or linked lineage record must identify:

- the selected output asset ID and revision;
- the selection record;
- the prompt instance ID and revision;
- the generation record;
- source references required for continuity or rights review;
- the editorial project or export relationship where applicable;
- the exact platform master revision; and
- the YouTube release record or external video ID after publication.

Do not put a YouTube title, URL, video ID, channel label, or publish date into a
prompt ID.

Do not put an undocumented episode identifier into a prompt filename to make it
look release-ready.

Store public platform identity in the release record.

## QA and Revision Records

Use `prompt-qa-record` for a prompt-specific check that cites an exact prompt
artifact and revision.

Example pattern:

```text
[task-subject]__prompt-qa-record__[prompt-class]__review__r01.md
```

Use `revision-record` for a controlled prompt change record.

Example pattern:

```text
[task-subject]__revision-record__prompt__[state]__r01.md
```

Use `selection-record` for a decision among generated candidates.

Example pattern:

```text
[task-subject]__selection-record__[output-class]__approved__r01.md
```

Use `lineage-record` for a durable source-to-output map when a generation
record alone is not sufficiently readable across systems.

Example pattern:

```text
[task-subject]__lineage-record__[output-class]__active__r01.md
```

The review record must cite the reviewed artifact by stable ID, controlled
filename, revision, and path or URI.

Never cite only “the latest prompt” or a screenshot of tool text.

## Prompt QA Minimums

Before a prompt is marked ready for generation, verify:

- the task subject is real, approved, or explicitly pending in its governed
  record;
- no episode ID has been invented or inferred;
- source prompt and module identities are present;
- every lock has a recorded source;
- every task variable is classified as safe, unsafe, or open;
- open variables have an owner and prevent generation where material;
- reference attachments have explicit roles;
- the prompt instance revision is immutable for the intended submission;
- tool target and delivery requirements are recorded where material;
- the planned output relationship is clear; and
- required prompt QA is linked.

After generation, verify:

- the generation record cites the exact submitted instance;
- candidate outputs are named and registered under asset rules;
- the candidate is not confused with a selected output;
- material tool settings and external IDs are retained;
- drift, failure, or mismatch is recorded when it informs a decision;
- selection cites the exact candidate;
- selected output lineage reaches the prompt source and inputs; and
- later derivatives retain their source-output relationship.

## Continuity Controls

Prompt naming supports continuity by preserving the source of each continuing
fact.

The prompt name alone must not attempt to carry all continuity facts.

Use records and manifests for those facts.

For a task involving recurring identity, the assembly or instance must cite
applicable character, location, object, style, camera, and voice sources by
their controlled identities and revisions.

If a fact changes between shots, record the decision in the appropriate scene,
shot, continuity, or approved source record.

Then record it as a safe variable or an approved new source revision.

Do not encode changing continuity facts as arbitrary filename suffixes.

Do not use `alt-a`, `better`, `warmer`, `fixed`, or `new-look` as a substitute
for a continuity decision.

## Lineage Record Minimum

Use a lineage record whenever a retained output must be explained across a
handoff, review, editing, release, archive, or tool boundary.

Minimum fields are:

```text
Lineage record ID:
Task subject:
Output asset ID and revision:
Output custody and current state:
Selection record:
Generation record:
Tool and external task reference:
Prompt instance ID and revision:
Prompt assembly ID and revision:
Source prompt ID and revision:
Module IDs and revisions:
Lock packet and lock-source revisions:
Reference bundle ID and revision:
Input asset IDs, roles, and revisions:
Safe-variable record:
QA record and disposition:
Editorial derivative IDs, if any:
Release record and platform relationship, if any:
Owner:
Created date:
Last verified date:
```

If a field is inapplicable, state that in the record body according to the
governing template.

Do not place `none` or `na` in a governed filename.

## Example Naming Patterns

The following patterns demonstrate grammar only.

Bracketed values must be replaced with approved controlled values.

They do not create, predict, or reserve episode identifiers.

```text
prompt__prm-master-[stable-key]__master-prompt__active__r01.md
prompt__prm-module-[stable-key]__prompt-module__active__r01.md
prompt__prm-lock-[stable-key]__lock-packet__active__r01.md
prompt__prm-image-[stable-key]__image-prompt__active__r01.md
prompt__prm-animation-[stable-key]__animation-prompt__active__r01.md
prompt__prm-voice-[stable-key]__voice-prompt__active__r01.md

[task-subject]__prompt-assembly__image__review__r01.md
[task-subject]__prompt-instance__image__approved__r01.md
[task-subject]__reference-bundle__image__approved__r01.md
[task-subject]__generation-record__google-flow__review__r01.md
[task-subject]__prompt-qa-record__animation__approved__r01.md
[task-subject]__selection-record__flow-clip__approved__r01.md
[task-subject]__lineage-record__flow-clip__active__r01.md
[task-subject]__revision-record__prompt__approved__r01.md
[scope-subject]__flow-project-record__generation__active__r01.md
```

For a task scoped to an approved shot, the task subject may use the universal
shot grammar defined by `Naming_Standards.md`.

For work without an approved episode identifier, use a bounded controlled task
subject or retain the work inside its controlled container.

Do not manufacture a shot or episode ID merely to satisfy an example.

## Example Record Relationships

### Reusable module to image output

```text
prompt__prm-module-[stable-key]__prompt-module__active__r02.md
→ [task-subject]__prompt-assembly__image__review__r01.md
→ [task-subject]__prompt-instance__image__approved__r01.md
→ [task-subject]__generation-record__image__review__r01.md
→ [asset-name governed by Asset_Naming.md]
→ [task-subject]__selection-record__image-candidate__approved__r01.md
```

The module remains a reusable source.

The instance remains a task-specific derivative.

The asset remains governed by asset naming.

### Image still to Google Flow clip

```text
[selected-still governed by Asset_Naming.md]
→ [task-subject]__reference-bundle__animation__approved__r01.md
→ [task-subject]__prompt-instance__animation__approved__r01.md
→ [task-subject]__generation-record__google-flow__review__r01.md
→ [flow-clip governed by Asset_Naming.md]
→ [task-subject]__lineage-record__flow-clip__active__r01.md
```

The Flow clip does not replace the selected still.

The Flow record must preserve the start-frame role and revision.

### Voice task to published release

```text
[task-subject]__prompt-instance__voice__approved__r01.md
→ [task-subject]__generation-record__voice__review__r01.md
→ [voice asset governed by Asset_Naming.md]
→ [editorial derivative governed by Asset_Naming.md]
→ [release record governed by Naming_Standards.md]
```

The published release record links to the audio asset and its lineage.

It does not turn the public title into a prompt identifier.

## Non-Examples

The following names are non-compliant:

```text
final prompt.md
flow prompt latest.txt
AI_Image_Prompt_v2.md
google flow magic prompt.docx
prompt__scene-1__final__v3.md
best-animation-prompt.md
new voice prompt.md
episode-guess__prompt__final.md
use-this-one.txt
prompt-copy-2.md
```

They fail because they use spaces, incorrect casing, vague state labels,
uncontrolled revisions, tool-first identity, unsupported episode IDs, missing
artifact class, or subjective language.

The following practices are also non-compliant:

- naming a reusable source after a temporary task;
- calling a submitted task instance a master prompt;
- using a Google Flow project title as the only task identity;
- using a generated output filename as the prompt identifier;
- changing a prompt file without creating a controlled revision;
- copying lock text without source references;
- using a public YouTube title as an internal prompt subject;
- treating an account session as the only generation record;
- calling a candidate selected without a selection record; or
- declaring a variable safe without identifying its authority.

## Collision Prevention

Before creating a governed prompt name, check for:

- the same prompt ID with a different declared purpose;
- a module ID that differs only by a hyphenation or plural form;
- a task instance that duplicates an existing task and revision;
- a generation record that represents the same external task;
- identical prompt names with different source module sets;
- a record that differs only by case or extension;
- an output linked to multiple competing prompt instances without an explicit
  multi-input record; and
- an external tool export that obscures a governed candidate name.

Resolve a collision by identifying the missing scope, subject, artifact,
qualifier, or stable ID.

Do not append `copy`, random characters, a contributor name, or an extra `final`
token.

Do not use a new revision to distinguish unrelated prompts.

## Handoffs

Every prompt-related handoff must identify the exact artifact being transferred
or referenced.

The handoff must include:

- controlled filename;
- stable prompt, module, or record ID where applicable;
- exact revision;
- authoritative path or URI;
- source, derived, or archive custody;
- current state;
- declared task or reuse scope;
- linked source prompts and module revisions;
- lock packet and reference bundle;
- safe-variable state;
- generation record and output lineage where applicable;
- QA decision, blockers, exceptions, and unresolved risks;
- receiving role; and
- expected next action.

Do not hand off a browser tab, chat message, or a folder with the instruction
“use this prompt.”

### Prompt lead to operator

The Prompt Lead provides the approved prompt instance, assembly, reference
bundle, lock references, safe variables, and required preflight state.

The operator records the exact submitted revision and tool outcome.

### Operator to reviewer

The operator provides the generation record, candidate asset identities,
external task references, selected inputs, and any observed tool drift.

The reviewer does not infer the prompt revision from a screenshot.

### Reviewer to editor

The reviewer provides the selection record, selected output identity, prompt
lineage record, continuity disposition, and permitted editorial use.

The editor records derivatives rather than overwriting the selected source.

### Editor to release owner

The editor provides the exact selected generated components and their
prompt-to-output lineage references when they contribute materially to release.

The Release Owner links them to the platform master and release record.

## Roles

Roles may be held by one person.

Their responsibilities must remain distinguishable.

The Prompt System Owner maintains reusable prompt IDs, module IDs, naming
vocabulary, and promotion or retirement decisions.

The Prompt Lead assembles task prompts, records source relationships, and
identifies safe variables.

The Canon and Continuity Owner confirms source authority for continuing facts
and resolves contradictions.

The Reference or Research Owner confirms source identity, provenance, rights,
and usage cautions.

The Google Flow Operator records external project and task relationships,
submitted prompt instances, inputs, settings, and outputs.

The Voice Owner confirms voice-direction sources, script relationship, and
rights-sensitive constraints.

The Visual or Shot Owner confirms task purpose, reference role, and continuity
connection for visual work.

The QA Owner records prompt readiness, review results, defect classification,
and closure evidence.

The Asset Steward maintains selected output identity and source/derivative
relationships under `Asset_Naming.md`.

The Editor records editorial derivatives and preserves the selected source
relationship.

The Release Owner records which generated outputs contribute to the public
release and retains platform evidence.

The Studio Owner resolves cross-system naming conflicts and approves material
exceptions.

## Placement and One Authoritative Home

Place reusable master prompts, modules, lock systems, and shared templates in
the AI production system or their designated controlled library.

Place episode- or task-specific assemblies, instances, reference bundles,
generation records, and prompt QA evidence in the applicable episode generation
or QA boundary.

Place selected images, clips, and audio outputs under the asset and production
structure defined by `Asset_Naming.md` and `Folder_Standards.md`.

Place release-specific prompt lineage references in the release manifest or
linked release record.

Do not duplicate a reusable source prompt in every task folder.

Do not store a task-specific instance as a new master in the source library.

Use a controlled reference, path, or lineage record instead of a competing copy.

## Migration

Migrate legacy prompt work when its name, identity, or tool-only location creates
a material traceability, continuity, rights, review, release, or recovery risk.

Do not rename a historical prompt only to make it look cleaner.

Before migration, inventory:

- current path, external URL, and tool label;
- proposed controlled filename;
- proposed or existing prompt ID;
- current revision and state;
- source prompt, module, lock, and reference relationships;
- output candidates and selected outputs;
- QA, selection, release, and archive records;
- inbound links and automated references;
- ownership and approval state; and
- risks of breaking retrieval or evidence.

Create a migration map with:

```text
Legacy name or external reference:
Governed name:
Prompt or record ID:
Revision:
Custody class:
Owner:
Migration date:
Reason:
Updated references:
Preserved external identifiers:
Successor or archive location:
Verification result:
```

Preserve the original tool label, legacy filename, and external ID in the
migration map.

Do not overwrite historical generation records to erase a legacy label.

Do not create two active reusable prompt sources after a migration.

Mark the legacy record deprecated, superseded, or archived as accurate.

## Legacy Google Flow Migration

For retained Flow work whose only identity is a project title, browser URL, or
download filename:

1. create a controlled generation record;
2. capture the available project, task, or session reference;
3. identify the exact output candidate or selected asset;
4. reconstruct prompt source and input references only from documented evidence;
5. mark unverified fields as unresolved rather than guessing;
6. assign a governed record name and prompt relationship where supported;
7. preserve the legacy label in the record; and
8. prevent the unverified record from being used as a reusable source.

Do not invent an episode, shot, prompt, or asset ID during reconstruction.

## Exceptions

An exception is a documented, time-bounded departure from this manual.

Convenience, personal preference, or a tool’s default export name is not an
exception reason.

An exception record must state:

- affected artifact or record class;
- rule that cannot be followed;
- technical, legal, platform, or interoperability reason;
- affected scope and duration;
- proposed alternate name or linkage method;
- collision and retrieval controls;
- compensating lineage evidence;
- owner and approver;
- review or expiry date; and
- migration or cleanup plan.

An exception does not amend this manual.

An expired exception is not continuing permission.

## Enforcement

Correct a prompt naming or lineage defect before the artifact becomes:

- an active reusable source;
- a formal review input;
- a selected output’s only traceability record;
- a cross-system handoff source;
- a release dependency; or
- an archive record needed for recovery or evidence.

Reviewers may return a prompt package without reviewing creative wording when
the source, revision, variables, or output relationship is ambiguous.

Operators must not submit a task that lacks required source, lock, and
safe-variable identification.

Release work must stop when a material generated component cannot be traced to
its selected source and approval evidence.

Automation that creates prompt records must implement this manual’s naming
grammar or route output through a controlled naming and lineage step.

## Prompt Naming QA Checklist

Before approving or handing off a prompt-related record, confirm:

- Is the artifact class correct?
- Is the prompt, module, or record ID stable and unique where required?
- Does the filename follow `Naming_Standards.md`?
- Is the subject approved, bounded, and not fabricated?
- Has any episode identifier been invented or inferred?
- Is the state accurate?
- Is the revision accurate for this exact artifact?
- Is source, derived, or archive custody clear?
- Are source prompt and module revisions cited?
- Are lock sources and safe variables recorded?
- Does every reference attachment have a role and source relationship?
- Does the generation record cite the exact submitted instance?
- Does each selected output cite its candidate and selection record?
- Does the lineage extend to editorial and release use where applicable?
- Are Google Flow and YouTube external IDs retained outside studio IDs?
- Are rights, continuity, and QA dependencies visible?
- Is there a collision or near-collision?
- Is the artifact in its authoritative home?
- Are exceptions documented and unexpired?
- Can the next role continue safely without asking the creator?

If any applicable answer is no, correct the record or escalate before use.

## Maintenance

Review this manual when:

- a recurring prompt-name collision occurs;
- a new generation platform changes task or export identity;
- a QA failure exposes missing prompt-to-output evidence;
- a release or correction cannot identify generated source material;
- a reusable module is repeatedly misclassified as a task instance;
- a new prompt class becomes a durable part of the production system; or
- an approved change to universal naming grammar requires alignment.

Do not revise this manual merely to imitate a temporary tool interface.

Do not create a new vocabulary token for one isolated workaround.

Assess migration impact, training impact, automation impact, cross-system
compatibility, and active lineage records before approving a change.

## Final Operating Rules

One reusable prompt has one controlled identity.

One module revision has one recorded source of authority.

One task instance identifies one bounded task and exact submission text.

One selected output retains a path back to its prompt, inputs, and decision.

One external tool record supplements studio identity; it never replaces it.

One release record links public distribution to internal lineage without
rewriting historical evidence.

One migration preserves the route from legacy identity to governed identity.

One exception has a named owner, control, and expiry.

## Guiding Principle

Name the prompt, preserve the source, record the permitted change, and retain
the path from instruction to output to release.
