# Version Control and History Manual

## Purpose

This manual defines how Village Stories preserves safe, intelligible history for documents, prompts, production assets, approvals, and releases.

It answers:

> How do we know which decision is current, what changed, why it changed, and how to recover safely?

---

# Philosophy

Version history is memory with evidence.

Village Stories is a persistent world. A small alteration to a character detail, location layout, prompt, sound cue, title, or release master can affect every later episode. History must therefore protect understanding, not merely store copies.

Use the lightest control that preserves traceability. Plain-text project documentation belongs in Git when practical. Large media needs managed storage, stable identifiers, manifests, and immutable release records. No one tool is mandatory; the controls are.

Never overwrite the only copy of an approved decision.

---

# Objectives

The version-control system must:

* maintain a recoverable history of production decisions;
* distinguish working drafts from approved and released states;
* protect canon and continuity from casual changes;
* make reviews and approvals attributable;
* prevent accidental loss, silent overwrites, and conflicting edits;
* support Git-aware documentation without requiring Git for every binary asset;
* preserve an exact, auditable release archive for YouTube;
* make Google Flow-generated work reproducible enough to review and reuse safely.

---

# Relationship and Authority Documents

This manual governs history, approvals, backups, release preservation, and change records.

It does not determine whether a creative change is correct. The following sources retain their authority:

* `00_Project_Core/README.md` — repository and single-source-of-truth philosophy.
* `01_Canon/` — permanent rules and style locks.
* `02_World/`, `03_Characters/`, and `04_Objects/` — persistent factual authority.
* `05_Research/` — evidence and historical cautions.
* `06_Story_Engine/` and `07_Episode_System/` — story and episode construction authority.
* `08_Production/16_File_Organization.md` — file locations, naming, status, and source references.
* `10_Episodes/` — completed episode decisions and records.
* `12_Quality_Assurance/` — quality criteria and review evidence when present.

When a version conflicts with canon, the newer timestamp does not make it valid. Escalate the contradiction for a deliberate canon decision.

---

# Terms

## Working copy

The editable current material being developed.

## Revision

A meaningful labeled iteration of one file or asset, such as `r03`.

## Version history

The ordered record of changes, authorship, reason, review, and recovery path.

## Baseline

The approved reference state from which later work proceeds.

## Lock

A declared freeze for a milestone. A lock does not make a file correct; it controls change.

## Release archive

The preserved package that identifies exactly what was delivered or uploaded.

## Rollback

The deliberate restoration of a prior approved state after recording the reason and impact.

---

# Control Levels

Apply control in proportion to risk.

| Material | Required control |
| --- | --- |
| Temporary notes or private experiments | Clear date/owner; delete or archive deliberately |
| Episode drafts | Revision label, source reference, handoff record |
| Prompts and selected generated shots | Prompt record, candidate/selection status, source inputs, decision record |
| Canon, character, world, and research documentation | Reviewed change, meaningful history, continuity review |
| Approved reusable assets | Stable asset ID, approval record, provenance, backup |
| Release master and YouTube metadata | Immutable archive, approval evidence, checksum when feasible, backup |

The table states minimum control. Apply stricter controls when a change affects public release, safety, rights, continuity, or many downstream episodes.

---

# Git-Aware Text Documentation

Use Git, or an equivalent change-tracking system, for structured text where it is available.

For Git-managed material:

* make focused changes with a clear purpose;
* inspect the changed content before review or commit;
* use meaningful commit messages that explain the production reason;
* avoid mixing unrelated changes in one history event;
* preserve line-oriented, readable Markdown rather than opaque generated blobs;
* do not rewrite shared history simply to make it look cleaner;
* never store secrets, private credentials, or access tokens in the repository.

Git history records text evolution. It does not replace an approval decision, a backup, an asset register, or a release archive.

---

# Safe Commit Practice

Before recording a Git change:

1. Confirm the change belongs to the repository.
2. Confirm the working tree does not include unrelated material.
3. Read the intended diff.
4. Verify cited source paths and headings still resolve.
5. Check that a canon-affecting change has the required review.
6. Record the reason in a clear commit message.

Good message examples:

```text
Document approved rain-scene reference sources
Lock episode 012 release metadata after QA approval
Correct tea stall reference link following folder migration
```

Weak messages:

```text
updates
final
fix stuff
changes
```

Do not commit generated media binaries, cache files, platform downloads, or disposable previews merely because they are available. Use the project’s managed asset storage and registers unless a deliberate repository policy says otherwise.

---

# Change Classes

Classify each meaningful change before review.

## Editorial

Clarifies wording or formatting without changing an approved fact, production requirement, prompt decision, or release state.

## Production

Changes a scene plan, timing, prompt, selected asset, audio treatment, edit, metadata, or workflow record.

## Continuity

Changes or risks changing an established appearance, location, prop, chronology, relationship, season, or event record.

## Canon

Changes a permanent series rule or fact. This is high impact.

## Emergency release correction

Corrects a public error, rights issue, safety issue, or serious platform mistake after release.

The label determines who must review, not whether the change may be hidden.

---

# Approval Requirements

Use a named approver or accountable role. “Everyone agreed” is not a record.

| Change class | Minimum approval |
| --- | --- |
| Editorial | Responsible document owner |
| Production | Stage lead plus affected downstream owner |
| Continuity | Continuity owner and relevant canon owner |
| Canon | Canon authority plus production lead |
| Emergency release correction | Release owner plus relevant authority; record immediately |

For each approval, record:

* item or stable identifier;
* revision or immutable reference;
* decision: approved, rejected, approved with conditions, or deferred;
* reviewer;
* date;
* conditions and follow-up owner.

An approval of one revision does not automatically approve later revisions.

---

# Revision Labels

Use a revision label when a file is transferred, reviewed, approved, or has a material change.

```text
r01  first reviewable revision
r02  revised after feedback
r03  approved production revision
```

Revision labels are not substitutes for a changelog. A reader should be able to discover what changed and why.

Do not reset a revision number because a production phase restarts. If a concept is abandoned and rebuilt, retain the history and create a new approved baseline when appropriate.

---

# Changelog Standard

Maintain a short changelog for materials whose changes affect production or continuity.

```text
Date:
Item and revision:
Change class:
Summary:
Reason:
Sources affected:
Approved by:
Downstream impact:
```

Write the reason, not just the action. “Updated prompt” is not enough; “Updated prompt to preserve the mother’s approved sari continuity between shots 3 and 4” is useful.

---

# Branching and Parallel Work

Parallel work is allowed only when owners and merge points are clear.

For Git-based workflows:

* use a short-lived working branch for a focused reviewable change when the team workflow supports it;
* name it for scope, not a person or temporary emotion;
* keep one branch responsible for one change set;
* merge only after required review and conflict resolution;
* delete or close stale branches after the outcome is retained.

For non-Git tools:

* create one named change request or working record;
* identify the current editor;
* prevent simultaneous uncoordinated edits;
* reconcile changes against the approved baseline before handoff.

No parallel workstream may create a second hidden canon.

---

# Detailed Workflow

## 1. Start from an approved baseline

Identify the current approved document, asset, prompt, or release record before editing. Confirm its authority, status, revision, and storage reference.

## 2. Classify the intended change

Label it editorial, production, continuity, canon, or emergency release correction. This determines the reviewer, evidence, and downstream checks.

## 3. Create a recoverable revision

Make the change in the appropriate managed system. For text, use focused Git-aware history where available. For media, create a new revision and update its manifest; do not overwrite an approved asset.

## 4. Review the difference

Compare the candidate with the baseline. Record what changed, why, source documents affected, risks, and any work that must be rechecked.

## 5. Obtain the required decision

Submit the exact revision or immutable asset reference to the accountable reviewer. Record approval, conditions, rejection, or deferral.

## 6. Lock, distribute, and back up

When approved for a milestone, lock the defined scope, hand off the exact selected material, update the archive/backup, and mark prior versions accurately.

## 7. Preserve the release record

After upload, reconcile the release archive with the live YouTube delivery. Later corrections are new documented events, never silent substitutions.

---

# Role Handoffs

## Creator to Reviewer

The creator provides the precise revision, change class, baseline, change summary, sources affected, and requested decision. The reviewer must not be asked to approve a moving target.

## Reviewer to Downstream Owner

The reviewer records the decision, conditions, and approved revision. The downstream owner uses only that identified revision and reports any mismatch before proceeding.

## Editor or Generation Lead to Release Owner

The handoff includes selected assets, the edit/master reference, source manifest, QA state, rights notes, and any unresolved condition. A release owner never infers approval from a filename or folder position.

## Release Owner to Archive Custodian

The release owner supplies the published URL, platform settings, exact master, metadata, approvals, and correction history. The archive custodian confirms that a future recovery can locate them.

---

# Decision Framework

Before changing, merging, replacing, or rolling back a production item, answer:

1. What is the approved baseline and who owns it?
2. What fact, asset, prompt, or public deliverable will actually change?
3. Does the change touch canon, continuity, rights, audience information, or an already released video?
4. What evidence supports the change?
5. What new revision, approval, backup, and QA are required?
6. Is preserving the current state necessary for audit or rollback?

If any answer is unknown, hold the change and resolve the missing evidence first.

---

# Conflict Resolution

When two changes touch the same decision:

1. Stop automatic merging or silent overwriting.
2. Identify the approved baseline.
3. Compare each proposed change against the relevant source authority.
4. Ask the accountable owners to choose, combine, or reject the changes.
5. Record the resolution and downstream impact.
6. Re-run the appropriate continuity and QA checks.

A tool’s automatic merge is only a text operation. It is not a creative or continuity resolution.

---

# Locking Milestones

Lock only a defined scope and state the reason.

Recommended locks:

* premise lock;
* storyboard lock;
* generation selection lock;
* picture lock;
* audio lock;
* release lock;
* archive lock.

A lock record includes:

```text
Scope:
Revision or asset manifest:
Lock type:
Date:
Owner:
Reason:
Permitted changes:
Reopen authority:
```

Minor typographic corrections may be permitted after a lock only if they do not alter the locked decision. Define any exception in writing.

---

# Reopening a Locked Item

Reopen work when a real need exists, not because an unreviewed alternative appears attractive.

Use this decision framework:

1. What defect, contradiction, rights issue, or clear improvement requires change?
2. Which locked decisions and downstream files will be affected?
3. Is the cost proportional to viewer, continuity, legal, or quality benefit?
4. Who has authority to reopen it?
5. Which new QA checks are required before re-locking?

Record the reopening. Create a new revision; never edit an archived master in place.

---

# Google Flow and Generated-Asset History

Generated visuals can vary across runs, accounts, models, and platform changes. Preserve enough information to understand a selected output later.

For every selected Google Flow output, retain:

* stable episode/scene/shot identifier;
* exact prompt text or a stored prompt-file reference;
* input references, including approved character/location/object assets;
* generation model or workflow information when exposed;
* generation date;
* candidate output reference;
* selection decision and reviewer;
* edit or transformation applied afterward;
* final asset reference and status.

If the platform cannot reproduce an exact output, state that limitation. Do not claim reproducibility that the tool does not provide.

An improved-looking regeneration is a new candidate, not an automatic replacement.

---

# Media Version History

Video, audio, images, and editing projects need a manifest even when stored outside Git.

The media manifest must identify:

* asset ID and filename;
* asset type and primary status;
* source project or generation record;
* revision;
* creation date and owner;
* technical characteristics that affect use;
* approval/selection decision;
* storage location;
* relationship to episode, scene, and shot;
* superseded or replacement asset, if any.

Use checksums for approved masters and high-value source assets when feasible. A checksum confirms file identity; it does not prove creative approval.

---

# Backup Strategy

Use at least three independent safeguards for release-critical work:

1. the active managed working location;
2. a separate backup location;
3. an offline, archival, or separately governed copy.

Keep at least two media forms where possible: editable source and approved deliverable.

Back up:

* canonical documentation and repository history;
* episode manifests and approval records;
* selected prompts and input references;
* selected visual and audio source assets;
* editing project files;
* approved release masters;
* YouTube metadata and publication records.

Do not treat synchronization as a backup if deletion or corruption propagates automatically.

---

# Backup Verification

A backup is only real after recovery is tested.

At planned intervals and before a major release:

* verify the backup completed;
* restore a representative text record and media asset to a safe test location;
* open the restored file with the intended tool;
* compare the checksum or file characteristics when available;
* record failures and corrective action.

Test an actual release archive periodically, not only a draft asset.

---

# Rollback Procedure

Use rollback to restore a known approved state safely.

1. Pause distribution or downstream changes if necessary.
2. Identify the current state, last approved baseline, and reason for rollback.
3. Preserve the current state as a superseded record; do not delete evidence.
4. Restore or recreate the prior approved revision.
5. Verify sources, filenames, status, metadata, and technical integrity.
6. Obtain the required approval for the restored state.
7. Notify affected owners and update the changelog.
8. Run QA appropriate to the impact.

For a public YouTube correction, retain both the original release record and the correction record, including the public consequence and verification.

---

# Release Archive

Create a release archive immediately after final release approval and update it after upload verification.

It must contain or reference:

```text
Release identifier:
Episode identifier and title:
Approved master filename and checksum when feasible:
Picture/audio/subtitle versions:
Thumbnail final and source reference:
Approved title, description, credits, chapters, disclosures:
Rights and music records:
Canon and prompt manifests:
QA sign-off:
Approvers and dates:
Upload date/time, URL, and platform video ID:
Post-upload verification:
Known deviations or corrections:
```

Make the archive read-only or otherwise protected after verification. Any later modification is a new controlled record, not a silent replacement.

---

# YouTube Relevance

YouTube is where viewers receive an episode; it is not a reliable version-control system.

Maintain local or managed records for:

* every uploaded master;
* the precise metadata used at publication;
* thumbnail version;
* subtitle/caption files;
* visibility and audience settings;
* rights disclosures and credits;
* published URL and release date;
* any later title, description, thumbnail, or file correction.

Before modifying an already published video, decide whether the change is metadata-only, a correction requiring a new master, or a public communication issue. Record the decision.

---

# Quality Assurance

Before a lock, approval, or release, confirm:

* the current revision is identifiable;
* the change reason and owner are recorded;
* no unreviewed file has replaced an approved source;
* canon-affecting changes received the correct authority review;
* asset manifests identify selected versus candidate files;
* backups include the current critical material;
* release artifacts are complete and accessible;
* platform records agree with the release archive.

---

# Common Mistakes

## Overwriting “the final”

This destroys the recovery path. Create a new revision and preserve the prior approved version.

## Treating Git as a media archive

Git is excellent for text history; it is not automatically appropriate for large, frequently changing binary media. Use manifests and managed storage.

## Treating cloud sync as backup

Sync can replicate deletions, ransomware, or mistakes. Maintain independent recovery copies.

## Confusing a lock with approval

A locked draft may be frozen for review; it is not automatically fit for release.

## Replacing a selected Google Flow output invisibly

Any replacement changes the visual record. Give it a new candidate, review it, and update the selection manifest.

## Squashing away meaningful production history

Clean history is useful only when it retains why material decisions were made. Preserve the decision record.

---

# Continuity and Canon Authority

History cannot legitimize an unapproved contradiction.

When a historical version reveals a conflict with an established fact, use it as evidence for review. Do not backdate, erase, or rename records to imply that a later decision always existed.

The relevant canon document remains authoritative until it is deliberately changed through its own approval path.

---

# Guiding Principle

Every approved production decision must have a recoverable past, a clearly identified present, and a safe path to a corrected future.
