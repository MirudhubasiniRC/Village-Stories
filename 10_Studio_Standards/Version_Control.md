# Studio Version Control

## Purpose

This manual defines the permanent, studio-wide controls for preserving,
reviewing, changing, recovering, and releasing Village Stories work.

It answers one operational question:

> How can a future contributor identify the controlling state of an artifact,
> understand how it came to be, and safely restore or continue the work?

Version control is the studio memory system.

It applies to both human-created and tool-created work.

It is Git-aware but tool-neutral.

The required outcomes are traceability, integrity, recoverability, and clear
authority.

No particular repository host, cloud drive, asset manager, editor, or AI tool
is required to achieve those outcomes.

## Scope

This manual applies to every retained artifact whose change could affect canon,
continuity, quality, rights, approval, reuse, handoff, publication, or history.

It applies to canon and research records.

It applies to world, character, location, object, and style records.

It applies to studio standards and templates.

It applies to episode documents and production records.

It applies to reusable prompts, prompt modules, lock packets, and prompt
instances.

It applies to source references, generated candidates, selected assets, edits,
renders, audio, thumbnails, captions, metadata, and delivery masters.

It applies to Google Flow sessions and exported outputs.

It applies to release packages, YouTube publication records, corrections, and
archives.

It applies whether those items live in the repository, managed media storage,
a generation platform, an edit system, a cloud workspace, or a release
platform.

It applies to humans, automation, and external services that create or retain
governed work.

It does not require a permanent record for a private thought or disposable
test that is immediately discarded.

An item becomes governed when it is shared, reviewed, selected, approved,
handed off, cited, reused, released, or retained as evidence.

## Boundaries

This manual governs common version-control language and evidence.

It does not decide the factual truth of canon.

It does not write prompt content or define lock construction.

It does not prescribe the detailed operation of Google Flow.

It does not replace production-stage procedures or release checklists.

It does not create legal rights, platform clearance, or public-release
approval.

The owning source remains responsible for those decisions.

Use `08_Production/17_Version_Control.md` for production-specific versioning,
file handling, and operational history procedures.

Use `08_Production/16_File_Organization.md` for production placement and
production filename application.

Use `08_Production/07_Google_Flow_Workflow.md` for the active generation
workflow and its tool-operating steps.

Use `08_Production/14_Quality_Control.md` for production and release QA.

Use `08_Production/15_Publishing_Workflow.md` for publication procedure.

Use `09_AI_Production_System/` for prompt architecture, lock systems,
generation controls, prompt QA, diagnosis, and AI revision practice.

Use `10_Studio_Standards/Prompt_Naming.md` for prompt identifiers, names,
and prompt-to-output lineage vocabulary.

Use `10_Studio_Standards/Asset_Naming.md` for asset identifiers, variants,
derivatives, and asset-record requirements.

Use `10_Studio_Standards/Naming_Standards.md` for universal revision syntax,
state tokens, dates, and filename grammar.

Use `10_Studio_Standards/Folder_Standards.md` for placement, custody,
authoritative homes, copying, retention, and archive boundaries.

Use the later `10_Studio_Standards/Canon_Change_Process.md` for the evidence,
review, approval, communication, and application of canon changes.

This manual must not duplicate those detailed workflows.

When controls overlap, apply the highest relevant authority and link to the
owner instead of creating a shadow procedure.

## Governing Principle

Preserve every approved or released state so that it can be found, understood,
verified, and recovered without relying on private memory.

When speed conflicts with traceability, preserve traceability.

When convenience conflicts with recoverability, preserve recoverability.

When a tool label conflicts with studio identity, preserve studio identity.

When a newer file conflicts with approved authority, the newer file is not
automatically valid.

When uncertainty exists, stop the promotion of the artifact and resolve its
authority before reuse or release.

## Version Philosophy

Version control is not a copying habit.

Version control is the deliberate preservation of meaningful state changes.

A good history tells a reviewer what changed.

A good history tells a reviewer why it changed.

A good history identifies who made and reviewed the decision.

A good history states what authority permitted the change.

A good history connects the changed item to affected downstream work.

A good history allows a prior safe state to be recovered.

The lightest control that preserves these outcomes is preferred.

Text records usually benefit from line-level change history.

Binary media usually benefits from stable IDs, manifests, immutable delivered
copies, checksums where practical, and managed backup storage.

Tool session history is useful but is not a sufficient studio record by itself.

A platform upload is distribution evidence, not the authoritative studio
record.

An AI generation is an output event, not an approval event.

A file marked `final` is not necessarily approved.

A Git commit is not necessarily a review approval.

A release tag, snapshot, or immutable package is not necessarily proof that
the underlying creative decision was canon-safe.

Each record must state only the decision it actually proves.

## Core Commitments

The studio preserves identity separately from filenames.

The studio preserves status separately from revision numbers.

The studio preserves approval separately from authorship.

The studio preserves source relationships separately from storage location.

The studio preserves release history separately from current working state.

The studio preserves canon as a controlled authority rather than a mutable
draft collection.

The studio preserves discarded candidates only when they are needed to explain
a decision, rights issue, failure, or lineage.

The studio never silently overwrites the only approved copy of a governed item.

The studio never uses deletion to conceal an incorrect, rejected, or replaced
decision.

The studio never treats a timestamp alone as proof of currentness.

The studio never treats a filename alone as a complete version history.

## Authority and Version Truth

Version order does not override authority order.

Approved canon outranks an unapproved later draft.

An approved production decision outranks a convenient local export.

An active studio standard outranks an outdated template.

An approved prompt source outranks an untracked copied prompt.

A release record outranks recollection of what was uploaded.

A rights restriction outranks an asset's technical availability.

When two records at the same authority level conflict, pause the affected work.

Identify the current approved record, its owner, and the decision history.

Do not resolve a conflict by choosing the newest modification date.

Do not resolve a conflict by choosing the most attractive output.

Do not resolve a conflict by editing both records until they appear to agree.

Escalate the conflict to the owner of the relevant authority.

Record the final resolution as a new, attributable decision.

## Artifact Identity Model

Every governed artifact has distinct identity layers.

The stable ID answers which controlled artifact this is.

The filename answers which stored expression, role, state, and revision this
file represents.

The version reference answers which meaningful state is being discussed.

The status answers whether the state may be used for a declared purpose.

The lineage record answers what sources and transformations produced it.

The review record answers whether the declared scope was accepted.

The release record answers what was actually delivered or published.

The location answers where the controlled copy can be retrieved.

Do not force all identity layers into one filename.

Do not replace a stable ID because a title, scope, or storage path changes.

Do not use a stable ID as proof that every derivative is approved.

Do not change a revision number merely because an artifact was moved.

## Immutable Canon and Mutable Work

Canon is immutable in ordinary production work.

Immutable means canon cannot be silently edited, locally overridden, or
rewritten by downstream convenience.

Immutable does not mean canon can never change.

It means every canon change requires a separate, explicit, attributable
governance decision.

Until that decision is approved through the Canon Change Process, the current
approved canon remains controlling.

Treat approved canon as a baseline reference.

Cite the controlling canon record and revision when a dependent production
decision needs traceability.

Do not copy canon into episode files as a competing authority.

Do not alter a canon quote in a prompt to make generation easier.

Do not infer a canon change from a selected visual, an edit, a voice take, or
a generated asset.

When a production need exposes a canon ambiguity, record the question.

Do not solve the ambiguity inside a local draft.

Mutable work includes drafts, candidates, experiments, assemblies, working
edits, and review submissions.

Mutable work may change rapidly while it stays inside its declared work state.

Mutable work becomes controlled when it is handed off, reviewed, approved,
selected, released, or made reusable.

A controlled mutable state must remain recoverable after later work continues.

## Baselines and Locks

A baseline is the accepted starting state for a bounded task.

A baseline may be a canon record, approved episode script, selected board,
approved prompt, source asset, edit decision list, or release candidate.

Record the baseline identity and revision before beginning work that depends on
it.

A lock is a declared temporary freeze at a milestone.

A lock protects change coordination.

A lock does not prove factual correctness, quality, or approval.

State the lock scope, owner, effective point, and release condition.

Examples include script lock, board lock, prompt lock, asset lock, picture
lock, metadata lock, and release-package lock.

Do not call an item locked when active changes are still expected without a
documented exception.

Do not use a lock to avoid correcting a material error.

If a locked baseline must change, classify the change, assess downstream
impact, and record an unlock or controlled exception.

## Working States and Branches

A branch is a bounded line of work that can evolve without changing the
controlling shared baseline.

Git branches are one technical implementation of this concept.

A separate folder, asset workspace, project copy, edit version, or tool session
can also represent a working branch when Git is not applicable.

The studio requires the concept, not one tool's feature.

Every branch of governed work must identify its source baseline.

Every branch of governed work must identify its purpose.

Every branch of governed work must identify its owner.

Every branch of governed work must identify its intended disposition.

Permitted dispositions are merge, promote, replace, archive, abandon, or
retain as evidence.

Do not create an unlabelled parallel copy of an approved item.

Do not use a branch name or workspace label that implies approval before it is
approved.

Do not merge, replace, or promote work merely because it is newer.

Review the branch against its declared baseline and scope.

## Conceptual Working-State Lifecycle

Use the following state progression when applicable.

```text
Source or baseline
↓
Bounded working branch
↓
Reviewable revision
↓
Reviewed disposition
↓
Approved or selected controlled state
↓
Released, superseded, archived, or retired state
```

Not every artifact requires every state.

Every material transition requires a record proportional to its risk.

No artifact becomes approved merely by moving between folders.

No artifact becomes released merely by exporting it.

No artifact becomes archival merely by becoming old.

## State Vocabulary

Use the common status meanings defined in `10_Studio_Standards/README.md`.

Use `Draft` for work in preparation that is not approved for operational use.

Use `In Review` for a submitted revision awaiting a formal decision.

Use `Approved` for a revision accepted for its declared scope.

Use `Active` for approved material intended for current routine use.

Use `Conditional` for material usable only under recorded constraints.

Use `Deprecated` for material retained during a transition but not for new work.

Use `Superseded` for material replaced by a named approved successor.

Use `Archived` for historical material retained outside active operations.

Use `Rejected` for material considered and not approved for the requested use.

Use `Selected` only when a candidate has been chosen for a named bounded use.

Use `Released` or `Published` only when the applicable release action occurred.

Use `Corrected` only when a previously released state has an attributable
correction record.

Do not use `final`, `latest`, `new`, or `use-this` as status substitutes.

## Revision Labels and Version Semantics

Use the revision syntax required by `Naming_Standards.md`.

A revision distinguishes meaningful iterations of the same artifact role.

Revision order does not communicate approval.

Revision order does not communicate ownership.

Revision order does not communicate release status.

Increment a revision when the artifact content, governed settings, source set,
selection, or decision changes materially.

Do not increment a revision for an unrecorded cosmetic file-system event.

Do not reuse a revision identifier after an item has been handed off, reviewed,
approved, or released.

When a revision is withdrawn before review, retain its history if it informed
a later decision or handoff.

Use a separate stable ID when the artifact has become a different controlled
thing rather than a revision of the same thing.

Examples include a new reusable asset, a distinct prompt module, a different
episode scope, or a materially different release package.

## Change Classification

Classify each material change before it is promoted, reviewed, or released.

Classification determines impact analysis, review route, and record depth.

### Editorial Change

An editorial change improves wording, formatting, navigation, or metadata
without changing a governed fact, instruction, selected source, or decision.

Editorial changes still require an attributable history entry when the item is
governed.

Editorial changes must not disguise a change in meaning.

### Administrative Change

An administrative change repairs a path, manifest pointer, owner field,
retrieval record, or status display without changing the underlying artifact.

Administrative corrections must preserve the former value when it is relevant
to retrieval or audit.

### Technical Change

A technical change alters encoding, format, render settings, checksum,
delivery wrapper, storage location, or tool compatibility without intended
creative change.

Technical changes require equivalence verification when the item is approved
or released.

### Production Change

A production change alters a scene plan, script, prompt instance, selected
asset, edit, audio treatment, subtitle, metadata, thumbnail, or delivery
decision.

Production changes require review by the responsible stage owner and affected
downstream owner.

### Continuity Change

A continuity change alters or risks altering established appearance, geography,
prop state, chronology, relationship, recurring sound, visual language, or
episode-state consistency.

Continuity changes require continuity review before promotion.

### Canon Change

A canon change alters a permanent series fact, rule, constraint, or approved
world truth.

Canon changes must follow the Canon Change Process.

This manual records their version-control implications but does not approve
their content.

### Rights, Safety, or Compliance Change

A rights, privacy, safety, accessibility, legal, or platform-obligation change
affects whether material may be retained, reused, published, or displayed.

Such a change requires the applicable accountable authority.

### Release Correction

A release correction changes a public asset, public metadata, captions,
thumbnail, availability, rights state, or audience-facing record after release.

Release corrections require a new correction record and preserved release
history.

### Emergency Change

An emergency change is the minimum action needed to prevent material loss,
public harm, rights harm, safety harm, platform harm, or irreversible
continuity damage.

Emergency status changes the timing of review, not the need for evidence.

## Impact Assessment

Before approving a material change, identify what depends on the prior state.

Check canon references.

Check episode, scene, and shot references.

Check prompts, modules, locks, and reference bundles.

Check generated candidates and selected assets.

Check edit timelines, audio, captions, thumbnails, and metadata.

Check QA evidence, approval records, and release packages.

Check public YouTube records when the change affects a release.

State whether each dependency is unaffected, requires verification, requires
revision, or requires retirement.

Do not claim that a change has no impact without checking its declared scope.

## Review and Approval

Review is a named decision against a declared scope.

Approval is not implied by silence, access permission, or a casual message.

An approver must have authority for the decision being made.

An approval applies only to the identified artifact, revision, scope, and
conditions.

Approval of a source does not automatically approve a derivative.

Approval of a prompt does not automatically approve its output.

Approval of a selected output does not automatically grant reusable-asset
status.

Approval of a production master does not automatically approve a YouTube
publication.

Every formal approval record must identify the artifact ID or unambiguous path.

Every formal approval record must identify the revision or immutable reference.

Every formal approval record must identify the review scope.

Every formal approval record must identify the reviewer role or named approver.

Every formal approval record must identify the disposition and date.

Every formal approval record must identify conditions, blockers, or follow-up
work when they exist.

## Minimum Approval Matrix

Editorial changes require the responsible artifact owner.

Administrative changes require the responsible custodian or record owner.

Technical changes to an approved asset require the technical owner and an
equivalence check by the affected use owner.

Production changes require the relevant stage owner and any affected downstream
owner.

Continuity changes require the continuity owner and the relevant canon owner
when canon is implicated.

Canon changes require the Canon Change Process and its named authorities.

Reusable prompt changes require the AI Production System owner and affected
authority review when locks or canon-facing behavior change.

Reusable asset changes require the asset owner and relevant continuity, rights,
or production review.

Release changes require the release owner and all applicable quality, rights,
and platform checks.

Emergency changes require the available accountable authority and a subsequent
formal review.

## Commit and Change Records

A commit, revision entry, asset manifest update, change request, or managed
history event may record a change.

The record format may differ by tool.

The record must remain durable and retrievable from the governed artifact.

For Git-managed text, use focused commits that describe the reason for the
change.

Inspect the intended diff before recording it.

Do not mix unrelated governed changes in a single commit.

Do not rewrite shared history merely to make it look cleaner.

Do not store secrets, credentials, access tokens, private keys, or restricted
personal data in version history.

For non-Git work, use a manifest, revision register, managed-history entry, or
equivalent durable record.

Every material record must identify the item.

Every material record must identify the prior and resulting revision or state.

Every material record must summarize what changed.

Every material record must state why the change was made.

Every material record must identify the actor or accountable role.

Every material record must identify the applicable change class.

Every material record must link required review or approval evidence.

Every material record must identify affected dependencies when material.

## Commit Record Quality

Write change summaries in terms of production purpose.

Good records explain the decision or reason.

Good records mention an approval or source when it matters.

Good records allow a future reviewer to distinguish correction from invention.

Weak records include `updates`, `final`, `fix`, `misc`, and `changes`.

Weak records force a future reviewer to reconstruct intent from guesswork.

Example strong summary:

```text
Record approved revision to the market-day location reference
```

Example strong summary:

```text
Correct episode asset manifest after selected Flow output replacement
```

Example strong summary:

```text
Archive superseded YouTube metadata after published title correction
```

The change record must not claim approval that has not occurred.

## Release Records

A release record is the immutable account of what was approved for delivery or
what was actually made public.

Create a release record before publication readiness is claimed.

Complete the release record when the platform action has occurred.

Retain the release record even when the public item is later changed, removed,
or replaced.

The release record must identify the episode or release scope.

The release record must identify the platform and channel context when relevant.

The release record must identify the approved platform master and its revision.

The release record must identify the thumbnail, title, description, captions,
metadata, and audience-setting versions where applicable.

The release record must identify required quality, rights, and approval
evidence.

The release record must identify the publication date, time, platform URL, and
platform identifier when publication occurs.

The release record must identify the responsible release owner.

The release record must identify the archive location and recovery path.

Never edit a historic release record to impersonate a later corrected state.

Create a linked correction record instead.

## Release Immutability

After release approval, preserve the exact approved release package.

After publication, preserve the exact known published state where feasible.

Store a checksum or equivalent integrity marker for masters when practical.

If a platform transcodes media, preserve the studio-controlled source master.

If public metadata is changed after publication, preserve the prior public
metadata and the correction reason.

If a video is unlisted, privatized, removed, or replaced, retain the action
date, reason, authority, and affected release reference.

Do not replace the original release master in place.

Do not discard the original title, description, thumbnail, or caption evidence
when a public correction is made.

## Rollback and Recovery

Rollback is a deliberate restoration of a prior controlled state.

Rollback is not a silent undo.

Use rollback when a later state is incorrect, unsafe, incompatible, corrupt,
unapproved, or harmful to release integrity.

Before rollback, identify the exact target state.

Before rollback, identify why the current state must be withdrawn.

Before rollback, identify affected dependencies and public consequences.

Before rollback, preserve the state being withdrawn when it is relevant to
audit, diagnosis, or legal retention.

Record the rollback authority.

Record the rollback date.

Record the restored revision or immutable reference.

Record whether dependent work was revalidated, reverted, quarantined, or left
pending.

Do not overwrite the faulty state if a preserved record is needed.

Use `Superseded`, `Rejected`, `Withdrawn`, or an equivalent accurate state for
the displaced item.

## Recovery Targets

A recovery target must be specific.

Acceptable targets include a named approved revision.

Acceptable targets include a signed or tagged release package.

Acceptable targets include a manifest-confirmed asset checksum.

Acceptable targets include a reviewed prompt instance and generation record.

Acceptable targets include a documented pre-migration baseline.

An unlabelled folder called `old`, `backup`, or `final-final` is not an
acceptable recovery target.

When no trustworthy recovery target exists, declare the gap.

Do not manufacture confidence by selecting the oldest or newest copy.

Escalate the missing-history risk before reuse or release.

## Backup and Archive Controls

Version history is not a backup.

A backup is not a version history.

Maintain both when loss would materially harm canon, release, rights,
continuity, or reuse.

Backups protect against loss or corruption.

Version records protect against ambiguity about state and decision.

Archives preserve historical evidence outside active operational work.

Use at least one recovery path that is independent of the primary working
location for critical material.

Critical material includes approved canon, active standards, selected reusable
assets, production masters, release records, and rights evidence.

Test recovery paths periodically.

A backup that cannot be located, read, and restored is not a reliable backup.

Record backup scope, custodian, location class, frequency, and restoration
expectation for critical collections.

Do not make an archive the only backup.

Do not make a backup the active authoritative workspace.

## Archive Rules

Archive when an artifact is no longer active but remains historically,
operationally, legally, or creatively relevant.

Preserve the artifact identity, revision, status, owner, and relationship to
its successor.

Preserve enough context to explain why it was archived.

Preserve a retrieval reference from the active successor when future users may
need the history.

Do not archive a currently controlling canon record merely because it is old.

Do not archive an active baseline while dependent work still cites it.

Do not delete rejected candidates that are required to prove non-use, rights
review, diagnosis, or a material selection decision.

Dispose of non-required sensitive or temporary material only through the
applicable retention and privacy process.

## Conflicts

A conflict exists when two valid-looking changes cannot both control the same
scope without contradiction.

Conflicts may occur in text, media, metadata, prompts, asset registers,
timelines, release records, or platform settings.

Detect conflicts before merge, promotion, approval, or publication whenever
practical.

Do not resolve a conflict by choosing the version with the later date.

Do not resolve a conflict by accepting an automated merge without reading it.

Do not resolve a conflict by retaining two competing `Active` sources.

Identify the common baseline.

Identify each incompatible change.

Identify the authority and owner for each changed claim.

Identify downstream work affected by each resolution.

Escalate canon, rights, safety, and release conflicts immediately.

Record the selected resolution and the reason competing state did not control.

## Merge and Reconciliation Rules

Merge only changes that are compatible with the controlling baseline.

Reconcile text meaning, not just characters.

Reconcile asset metadata, not just filenames.

Reconcile prompt versions, locks, references, and declared variables together.

Reconcile a production package as a set of mutually compatible components.

Reconcile release metadata against the exact master, thumbnail, captions, and
publication evidence it describes.

After reconciliation, create a new reviewable revision.

Do not label a manually reconciled item as unchanged.

## Prompt Lineage

Every retained prompt must have a stable prompt identity or an unambiguous
controlled reference.

Every reusable prompt must identify its owner, purpose, scope, status, and
revision.

Every task-specific prompt instance must identify its source prompt or
assembly.

Every prompt assembly must identify the referenced modules and lock packets.

Every prompt assembly must identify source references and approved variables.

Every material prompt revision must state whether it changed intent, lock
content, source inputs, parameters, wording, or tool compatibility.

Do not edit an approved reusable prompt in place without a new controlled
revision.

Do not copy prompt prose into an episode workspace without retaining the source
relationship.

Do not call a prompt `approved` solely because it produced an attractive image.

Use the prompt naming and lineage rules in `Prompt_Naming.md`.

Use the prompt QA and lock requirements in `09_AI_Production_System/`.

## Prompt-to-Output Lineage

Every selected AI output must be traceable to its producing prompt instance.

Every selected AI output must be traceable to the relevant input reference set.

Every selected AI output must be traceable to the tool session or generation
record when technically available.

Record model, workflow, or settings information when it materially affects
repeatability, diagnosis, rights, or quality.

Record generation date and operator when material.

Record the selection decision that changed a candidate into an approved use.

Record subsequent editorial, compositing, retiming, audio, or format
derivatives as lineage, not as unexplained new sources.

If exact reproduction is impossible because the tool is mutable or stochastic,
record the best available factual evidence.

Never imply reproducibility that the tool cannot provide.

## Asset Lineage

Every retained selected or approved asset requires a stable asset ID or
controlled asset record.

The asset record must identify source, derivative, selection, and use
relationships.

An original capture must state that it is original capture where no earlier
source exists.

An imported asset must retain its source and rights context.

A generated asset must retain its prompt and input lineage.

A derivative must retain its parent asset or transformation record.

A compound asset must identify material component sources where required for
rights, continuity, reuse, or recovery.

A replacement asset must not erase the identity or decision record of the
replaced asset.

Use asset IDs to preserve continuity across path, title, and storage changes.

Use `Asset_Naming.md` for the complete asset-identity and naming system.

## Google Flow Outputs

Google Flow is a production tool, not the authoritative studio version system.

Do not treat a Flow project title as a stable studio identity.

Do not treat a generated export filename as a controlled asset name.

Do not treat a browser history entry as the only generation record.

Before a Flow output enters review, assign its studio-controlled asset or shot
identity and record its source relationship.

For retained Flow work, preserve the relevant project or session reference.

For retained Flow work, preserve the prompt instance reference.

For retained Flow work, preserve the input assets and reference bundle.

For retained Flow work, preserve material model, workflow, or setting details.

For retained Flow work, preserve the generation date and operator when known.

For selected Flow work, preserve the selection and QA decision.

For release-bound Flow work, preserve the exact selected export or its verified
derived production master.

Use the Google Flow workflow for tool operation.

Use this manual to ensure that outputs survive a tool, account, or interface
change with usable lineage.

## YouTube and Public Release Implications

YouTube is a distribution destination, not the source of studio truth.

The studio must retain its own release package before or at publication.

A YouTube upload may be replaced, edited, monetized differently, restricted,
or removed by platform or channel action.

The release record must preserve what the studio submitted and what became
publicly visible as far as practical.

Record the video ID, URL, publication state, publication time, and release
owner after publication.

Record the viewer-facing title, description, thumbnail, captions, playlist,
audience configuration, and material settings applicable to the release.

Record any post-publication correction as a new linked event.

Do not revise a historic approval to make it appear to approve a later public
change.

If a public correction affects canon, continuity, rights, safety, or audience
trust, escalate it under the proper authority in addition to release handling.

## Production Package Integrity

A production package is a controlled set, not a loose folder of recent files.

The package must identify its episode or delivery scope.

The package must identify its controlling baseline.

The package must identify its component revisions.

The package must identify its current status and release readiness.

The package must identify missing, conditional, or substituted components.

The package must identify quality and approval evidence.

The package must identify the responsible production owner.

The package must identify the archive and recovery reference once locked.

Do not assemble a release package from whichever files are most convenient.

Do not mix components from incompatible locked states.

Do not use an old thumbnail, caption, or metadata revision with a newer master
without explicit review.

## Naming and Status Relationships

Names make artifacts retrievable.

Statuses make operational permission visible.

Revision tokens distinguish iterations.

Stable IDs preserve identity across iterations.

Paths communicate custody and context.

Manifests connect those layers when a filename cannot carry all details.

Do not encode approval in a filename unless the approval record exists.

Do not encode `released` in a filename before release occurred.

Do not use `latest` as a durable version relationship.

Do not rename a predecessor so completely that links to it fail.

When a controlled name changes, preserve the former name in the manifest,
redirect record, or lineage history where retrieval requires it.

## Supersession

Supersession replaces an artifact for a declared scope.

It does not delete the predecessor.

A supersession record must identify the predecessor.

A supersession record must identify the successor.

A supersession record must identify the effective scope and date.

A supersession record must identify the reason for replacement.

A supersession record must identify whether downstream work must migrate.

Do not mark an item superseded when no approved successor exists.

Use `Deprecated` when a transition is underway but an approved replacement is
not yet fully adopted.

Use `Archived` only after the item has left active operational use.

## Migration

Migration changes a naming, folder, storage, record, tool, schema, or workflow
structure while preserving usable history.

Every material migration requires a written scope.

Every material migration requires a source inventory.

Every material migration requires an owner.

Every material migration requires a mapping from prior identifiers or paths to
new identifiers or paths.

Every material migration requires a cutover rule.

Every material migration requires a rollback or recovery plan.

Every material migration requires verification of completeness and lineage.

Do not use migration as permission to rewrite history.

Do not change stable IDs merely to make a new tool more convenient.

Do not silently mass-rename approved assets or prompts.

Do not retire the old retrieval path until the mapping is verified.

Preserve the pre-migration baseline until verification and recovery conditions
are met.

## Tool Migration

When moving from one repository host, asset manager, editor, cloud drive, or AI
tool to another, preserve studio-controlled identity above tool-specific IDs.

Capture old tool IDs, project links, and export references when they are needed
to interpret history.

Record what cannot be migrated exactly.

Record whether prompt execution, model settings, assets, timestamps, comments,
or approvals have fidelity limits after migration.

Do not claim that a migrated record is identical when evidence was lost.

Create a post-migration verification record for critical canon, active prompts,
selected assets, production masters, and active release records.

## Emergency Fixes

Use an emergency fix only when delay creates material loss or harm.

Examples include accidental publication of restricted material.

Examples include a severe public metadata error.

Examples include an urgent rights, privacy, safety, or platform issue.

Examples include corruption of a release master or critical active record.

Take the minimum reversible action needed to contain the risk.

Preserve evidence before changing it when doing so does not increase harm.

Record the incident, action, owner, time, authority, and affected scope.

State whether the action is a rollback, correction, takedown, quarantine,
restore, or temporary exception.

Conduct the formal review at the next practical opportunity.

Do not convert emergency privilege into permanent unreviewed process.

## Quarantine

Quarantine isolates a governed item that must not be reused, promoted, or
released while a risk is assessed.

Use quarantine for suspected rights issues, privacy issues, corruption, severe
continuity conflicts, unsafe prompts, compromised access, or uncertain release
integrity.

Quarantine does not mean deletion.

Quarantine records must identify the item, risk, owner, date, and release
restriction.

Quarantine records must identify the decision path for restore, correct,
replace, archive, or dispose.

Do not silently return a quarantined item to active use.

## Quality Assurance of History

Version control requires its own QA.

History QA verifies that a record can be trusted and recovered.

At each material approval or release gate, verify artifact identity.

Verify current revision and visible status.

Verify source, dependency, and lineage references.

Verify review and approval evidence.

Verify the controlling baseline.

Verify that any exception is visible, approved, and unexpired.

Verify that the intended recovery target exists and is retrievable.

Verify that names, manifests, paths, and release records agree.

Verify that superseded or deprecated material is not presented as active.

Use production and prompt QA systems for their detailed discipline checks.

## Periodic Integrity Checks

Perform proportionate integrity checks for active governed collections.

Check that active canon records have recoverable approved history.

Check that active standards cite current owning manuals.

Check that reusable prompts point to current locks and sources.

Check that selected assets have lineage and rights context.

Check that active production packages have compatible component revisions.

Check that release records have preserved masters and public identifiers.

Check that archives remain retrievable.

Check that backups can be restored.

Check that no parallel `Active` source silently competes for the same scope.

Record material gaps and assign an owner for correction.

## Roles

Roles may be performed by one person in a small studio.

The responsibilities remain distinct even when one person holds them.

### Studio Owner

The Studio Owner protects the integrity of studio-wide controls.

The Studio Owner resolves cross-system authority conflicts.

The Studio Owner approves material governance exceptions.

The Studio Owner ensures critical history and recovery obligations have owners.

### Canon Owner

The Canon Owner protects approved canon baselines.

The Canon Owner identifies when a change requires the Canon Change Process.

The Canon Owner does not permit version mechanics to bypass canon governance.

### Production Owner

The Production Owner owns production package state, operational handoffs, and
production-stage version procedures in `08_Production/`.

The Production Owner verifies that release components are compatible.

### AI Production System Owner

The AI Production System Owner owns reusable prompt architecture, locks,
generation controls, prompt QA, and AI revision procedures in
`09_AI_Production_System/`.

The AI Production System Owner ensures that prompt and output lineage remain
usable across tool sessions.

### Asset Custodian

The Asset Custodian maintains asset records, storage integrity, and recovery
references for managed assets.

The Asset Custodian does not grant canon or release approval merely by holding
the files.

### Release Owner

The Release Owner maintains the release record and confirms that public action
matches the approved release package.

The Release Owner records corrections, takedowns, and publication changes.

### Contributors

Contributors preserve source relationships, accurate status, and meaningful
history in work they create or modify.

Contributors must not conceal uncertainty by inventing a version relationship.

### Reviewers

Reviewers verify the declared revision, scope, authority, evidence, and
disposition.

Reviewers must distinguish blocking history defects from non-blocking advice.

## Handoffs

A handoff transfers responsibility for continuing or reviewing a bounded state.

A handoff must identify the artifact or package.

A handoff must identify the current revision and status.

A handoff must identify the controlling baseline and source references.

A handoff must identify required decisions, open risks, and blocked work.

A handoff must identify known exceptions and their expiry.

A handoff must identify the next owner and requested action.

A handoff must identify the recovery or archive reference when the work is
locked or released.

Do not hand off a folder with the instruction to use “the latest files.”

Do not hand off an AI output without its prompt and input lineage when it may
be selected, reviewed, reused, or released.

Do not hand off a release package without its approval and publication record.

## Minimum Handoff Questions

What is the controlling artifact or package?

Which revision is being handed off?

What is its status?

What baseline and authority govern it?

What changed since the last handoff?

What must remain fixed?

What is still open or conditional?

What review has occurred?

What decision is requested next?

Where can the prior safe state be recovered?

## Exceptions

An exception permits a limited departure from this manual.

An exception is not a substitute for history.

An exception must identify the affected rule.

An exception must identify the artifact, scope, and duration.

An exception must identify the risk and compensating control.

An exception must identify the requester and approver.

An exception must identify the expiry or review point.

Repeated exceptions require review of the standard, workflow, template, or
tooling that made normal compliance impractical.

No exception authorizes silent canon change, false approval, secret storage in
history, or unrecoverable overwrite of critical approved work.

## Anti-Patterns

Avoid calling a local export the master without a release record.

Avoid keeping only a tool-generated project name as output lineage.

Avoid overwriting an approved prompt to “save time.”

Avoid treating a more recent timestamp as a higher authority.

Avoid calling an unreleased file `final`.

Avoid placing two conflicting copies in separate folders and calling both
current.

Avoid deleting a rejected candidate when it explains a selected asset's risk.

Avoid converting a public correction into an edited historic release record.

Avoid performing a mass migration without a mapping and recovery plan.

Avoid using a backup folder as an unmanaged working directory.

Avoid assuming Git history protects untracked media or external tool sessions.

Avoid assuming a cloud platform retains data forever.

Avoid treating a published YouTube video as the only release archive.

## Operational Checklist

Before a material handoff, confirm identity.

Before a material handoff, confirm revision and status.

Before a material handoff, confirm baseline and source references.

Before a material handoff, confirm review state and open conditions.

Before a material handoff, confirm the recovery reference.

Before approval, confirm change classification and impact.

Before approval, confirm the approver has authority for the scope.

Before approval, confirm the revision reviewed is the revision recorded.

Before promotion, confirm incompatible parallel work has been reconciled.

Before release, confirm the package components are compatible and immutable.

Before release, confirm platform evidence and archive location are prepared.

After release, confirm the public identifier and publication state are recorded.

After correction, confirm original and corrected states are both traceable.

## Final Direction

Village Stories must remain understandable when the original operator, tool,
workspace, or platform is no longer available.

Every material artifact must therefore have an identity, a state, a history,
and a recovery path appropriate to its risk.

Every approved change must be attributable.

Every release must be reconstructable.

Every exception must be visible.

Every handoff must be understandable.

Every future contributor must be able to distinguish source truth, working
possibility, approved decision, and released record.

The studio rule is simple:

> Preserve the path from authority to outcome, and never make recovery depend
> on memory.
