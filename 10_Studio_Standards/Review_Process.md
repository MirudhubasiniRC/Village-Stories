# Review Process

## 1. Purpose

This manual defines the studio-wide review process for Village Stories.

It is a permanent governance standard, not a production how-to duplicate.

Its purpose is to make every formal review:

* Identifiable.
* Scoped.
* Evidence-based.
* Attributable.
* Decisive.
* Recoverable.

Review turns scored evidence into an explicit studio decision.

Scoring methods belong in `Quality_Score_System.md`.

Release packet requirements belong in `Release_Standards.md`.

Discipline execution belongs in `08_Production/`.

Prompt and generation gates belong in `09_AI_Production_System/`.

This manual defines who reviews what, when review is required, what record
must exist, how dispositions are chosen, and how issues are closed or
escalated.

## 2. Guiding Principle

Review is a decision process, not a vague request for feedback.

A comment without a disposition is not a completed review.

An approval without evidence is not a valid approval.

A rejection without owner and required correction is not actionable.

Every formal review must leave the next contributor clearer than before.

When speed conflicts with traceability, preserve traceability.

When confidence conflicts with missing evidence, defer.

## 3. Scope

This process applies to formal review of:

* Story and episode intent.
* Scripts and narration.
* Storyboards and shot plans.
* Image prompts and approved stills.
* Animation prompts and approved clips.
* Audio, music, ambience, and SFX deliverables.
* Edits, captions, and accessibility packages.
* Thumbnails and packaging frames.
* Metadata and publish copy.
* Release bundles and publish approvals.
* Standards changes, canon-change proposals, and exceptions.

This process applies to:

* First-pass submissions.
* Revision resubmissions.
* Conditional approvals awaiting proof.
* Pre-release sign-off.
* Post-release correction review when a new governed version is created.

## 4. Non-Scope

This manual does not:

* Define numeric rubrics or thresholds. See `Quality_Score_System.md`.
* Define release packet contents in full. See `Release_Standards.md`.
* Define version labels or supersession. See `Version_Control.md`.
* Define canon-change proposal mechanics. See `Canon_Change_Process.md`.
* Replace detailed QC checklists. See `08_Production/14_Quality_Control.md`.
* Replace prompt QA hard gates. See `09_AI_Production_System/14_Prompt_QA.md`.

Workflow manuals may add timing and discipline-specific checklists.

They must preserve the disposition model and record fields defined here.

## 5. Authority Hierarchy

Reviewers apply the highest applicable approved source.

```text
Studio mission, audience promise, legal and platform obligations
↓
01_Canon/ and approved canonical decisions
↓
02_World/ · 03_Characters/ · 04_Objects/ · 05_Research/
↓
06_Story_Engine/ · 07_Episode_System/
↓
Approved episode brief, script, storyboard, and scene-state records
↓
08_Production/ and 09_AI_Production_System/
↓
10_Studio_Standards/ scoring, review, version, release, and canon-change standards
↓
Artifact under review
```

If authority conflicts, do not approve around the conflict.

Use `Deferred` or `Escalated` and route to the correct owner.

## 6. Definitions

**Formal review** — A recorded review with scope, evidence, disposition, and
accountable reviewer.

**Informal feedback** — Useful notes that do not by themselves change approval
state.

**Review packet** — The stored record of a formal review.

**Review scope** — What the reviewer is and is not deciding.

**Disposition** — The official outcome of the review.

**Reviewer of record** — The accountable decision owner for the packet.

**Contributing reviewer** — A discipline specialist who supplies findings or
recommended scores.

**Blocking issue** — A defect that prevents approval until resolved or
excepted.

**Condition** — A required proof or correction that must be satisfied while or
after limited downstream progress is allowed.

**Gate** — A production point where formal review is required before continuing.

**Revision cycle** — The numbered resubmission after `Changes Requested`.

**Escalation** — A review routed to higher or different authority.

**Closure** — The point at which all blocking issues and conditions are
resolved or formally excepted.

## 7. Disposition Model

Every formal review must use exactly one primary disposition.

| Disposition | Meaning | Downstream effect |
| --- | --- | --- |
| `Approved` | Meets declared review scope. | Downstream may depend on this version. |
| `Approved with Conditions` | Meets scope only if named conditions are tracked and satisfied. | Limited downstream allowed; conditions must close. |
| `Changes Requested` | Does not meet scope; corrections required. | Downstream must not treat as approved. |
| `Deferred` | Decision postponed pending named evidence or authority. | Work may continue only on non-dependent tasks explicitly noted. |
| `Rejected` | Not approved for the requested purpose. | Rework or abandon path; do not silently bypass. |
| `Escalated` | Reviewer lacks authority to decide. | Higher or different owner must decide. |

### 7.1 Disposition rules

* Do not use informal phrases like "looks good" as a disposition.
* Do not combine two primary dispositions in one packet.
* `Approved with Conditions` is not a weak approval; conditions are binding.
* `Deferred` is not a soft rejection; it must name what is missing.
* `Rejected` must name why the artifact cannot serve the requested purpose.
* `Escalated` must name the target authority.

### 7.2 Relationship to scoring

When `Quality_Score_System.md` applies:

* Hard gate failure cannot produce `Approved` or `Approved with Conditions`.
* Score bands guide but do not replace reviewer judgment within allowed bands.
* A high score with unresolved blocking issue still cannot close as `Approved`.

## 8. Review Roles

### 8.1 Core roles

| Role | Primary responsibility |
| --- | --- |
| Contributor | Submits artifact, evidence, and remediation. |
| Discipline reviewer | Reviews within one craft or technical domain. |
| Quality lead | Owns gate plan, final gate recommendation, and closure tracking. |
| Canon reviewer | Blocks or escalates truth, continuity, and canon conflicts. |
| Research reviewer | Resolves historical, cultural, occupational, or sensory accuracy questions. |
| Release approver | Confirms release packet and publish readiness. |
| Standards owner | Reviews proposed changes to studio standards and exceptions. |

### 8.2 Role boundaries

| Role | Must not |
| --- | --- |
| Contributor | Self-approve final gate without documented exception |
| Discipline reviewer | Approve outside discipline without quality lead agreement |
| Quality lead | Override canon hard stop without canon authority |
| Canon reviewer | Approve craft quality alone |
| Release approver | Approve with missing upstream gate |

### 8.3 Minimum review coverage by stage

| Stage | Required reviewers |
| --- | --- |
| Story | Story reviewer; canon reviewer when facts are non-trivial |
| Script | Story reviewer; canon reviewer when dialogue asserts facts |
| Board | Story or picture reviewer; camera authority check |
| Image | Picture/continuity reviewer; prompt QA per AI workflow |
| Animation | Picture/continuity reviewer; prompt QA per AI workflow |
| Audio | Sound reviewer; canon reviewer when language or register matters |
| Edit | Picture/continuity and sound reviewers; quality lead recommendation |
| Thumbnail | Picture reviewer; audience-promise check |
| Metadata | Story or release reviewer; policy and honesty check |
| Release | Release approver with quality lead support |
| Canon change | Canon reviewer and standards owner as required |
| Standards change | Standards owner and affected discipline owners |

A single person may hold multiple roles.

The review packet must still show which hats were worn.

## 9. Review Triggers

Formal review is required when:

* An artifact is submitted to a named gate.
* A revision is resubmitted after `Changes Requested`.
* A condition must be verified.
* A conditional approval must be converted to full approval.
* A canon-change proposal reaches review state.
* A release bundle is presented for publish approval.
* A defect is serious enough to require re-approval of a previously approved
  artifact.
* An exception to standards or thresholds is requested.

Formal review is not required for:

* Personal drafting before submission.
* Exploratory AI generation clearly labeled non-approved and isolated.
* Minor note-sharing that does not change version or approval state.

If unsure, treat the event as requiring formal review.

## 10. Review Packet

Every formal review must produce one review packet.

### 10.1 Required fields

| Field | Required |
| --- | --- |
| Review ID | Yes |
| Artifact name and path | Yes |
| Artifact version | Yes |
| Stage / gate | Yes |
| Review scope | Yes |
| Submission date | Yes |
| Reviewer of record | Yes |
| Contributing reviewers | If any |
| Applicable authority links | Yes |
| Evidence examined | Yes |
| Hard gate result | When scoring system applies |
| Dimension scores and total | When scoring system applies |
| Primary disposition | Yes |
| Blocking issues | If any |
| Conditions | If applicable |
| Required corrections | If any |
| Responsible owner for corrections | If any |
| Escalation target | If escalated |
| Resulting version or status | Yes |
| Next action | Yes |

### 10.2 Recommended fields

| Field | Use |
| --- | --- |
| Revision cycle number | Resubmissions |
| Timestamp of closure | Completed reviews |
| Linked upstream approvals | Release and edit gates |
| Exception reference | If approval uses exception |
| Tool/session reference | AI-generated artifacts |
| Small-size proof link | Thumbnails |
| Caption/accessibility note | Edit and release gates |

### 10.3 Packet naming and placement

Name and store review packets using:

* `Naming_Standards.md`
* `Folder_Standards.md`
* `Version_Control.md`

Do not keep the only review record in chat or comment threads.

Chat may point to the packet.

It may not replace the packet.

### 10.4 Review ID pattern

Use a stable, human-readable ID.

Recommended pattern:

```text
RVW_{STAGE}_{EPISODEORASSET}_{VERSION}_{YYYYMMDD}_{SEQ}
```

Examples:

```text
RVW_IMG_EP001_S03_v1.2_20260714_01
RVW_REL_EP001_BUNDLE_v1.0_20260720_01
RVW_STD_PROMPT_NAMING_v2.0_20260714_01
```

## 11. Stage Review Flows

### 11.1 Story review

**Inputs:** premise, outline, beat sheet, episode brief.

**Scope:** Is the episode worth making, canon-safe, emotionally true, and
structurally viable?

**Minimum evidence:** story artifact, authority links, season and continuity
notes.

**Common blocking issues:**

* Forbidden premise pattern.
* Unsupported historical claim.
* Weak episode promise.
* Character knowledge error.

**Typical outputs:**

* `Approved` → script stage may begin.
* `Changes Requested` → revise beats, promise, or facts.
* `Deferred` → research or canon answer missing.

### 11.2 Script review

**Inputs:** script, narration draft.

**Scope:** Are action, dialogue, pacing, and narration usable for boarding and
audio?

**Minimum evidence:** approved story reference, character voice references,
scene-state notes.

**Common blocking issues:**

* Voice break.
* Unboardable action.
* Hidden new fact.
* Unsafe humour or suspense.

### 11.3 Storyboard review

**Inputs:** boards, shot list, sequence notes.

**Scope:** Is the visual sequence clear, continuous, and prompt-ready?

**Minimum evidence:** approved script, shot list, camera bible citations.

**Common blocking issues:**

* Missing axis or geography.
* Unlabeled camera viewpoint or movement.
* Prop or wardrobe state drift.
* Missing bridge shot.

### 11.4 Image review

**Inputs:** prompt, references, candidate still, prompt QA record.

**Scope:** Is the still canon-true, lock-complete, and edit-usable?

**Minimum evidence:** full prompt, lock fields, references, QA checklist,
candidate still.

**Common blocking issues:**

* Identity drift.
* Wrong object or location state.
* Mixed camera direction and movement.
* Unapproved reference.

Follow `09_AI_Production_System/14_Prompt_QA.md` for hard failures.

### 11.5 Animation review

**Inputs:** animation prompt, source still, candidate clip, QA record.

**Scope:** Does motion preserve identity, geography, and edit usability?

**Minimum evidence:** source still bridge, movement bible citation, clip file,
in/out notes.

**Common blocking issues:**

* Morphing identity.
* Camera movement contradiction.
* Unusable first or last frame.
* Speed or path breaks screen logic.

### 11.6 Audio review

**Inputs:** narration, dialogue, ambience, music plan, SFX packet.

**Scope:** Is sound period-true, emotionally aligned, technically usable, and
rights-safe?

**Minimum evidence:** script alignment, audio files, levels note, source/rights
note.

**Common blocking issues:**

* Wrong register or dialect.
* Modern sonic contamination.
* Clipped or noisy narration.
* Missing required ambience.

### 11.7 Edit review

**Inputs:** rough or fine cut, caption file, accessibility package.

**Scope:** Does the sequence cohere, remain continuous, and meet technical
delivery needs?

**Minimum evidence:** timeline reference, shot approval list, captions,
continuity notes.

**Common blocking issues:**

* Geography break across cuts.
* Hidden defect masked by crop or blur.
* Caption mismatch.
* Wrong shot version inserted.

### 11.8 Thumbnail review

**Inputs:** thumbnail image, packaging proof.

**Scope:** Is the packaging honest, readable, on-brand, and non-misleading?

**Minimum evidence:** image file, episode promise reference, small-size proof.

**Common blocking issues:**

* Clickbait betrayal.
* Wrong character emphasis.
* Illegible text or emotion at mobile size.

### 11.9 Metadata review

**Inputs:** title, description, tags, chapters, community copy.

**Scope:** Is public copy accurate, calm, searchable, and policy-safe?

**Minimum evidence:** episode reference, metadata draft, policy check note.

**Common blocking issues:**

* False educational claim.
* Spoiler misuse.
* Tone break.
* Missing language clarity.

### 11.10 Pre-release review

**Inputs:** release bundle, export package, approval chain.

**Scope:** May this version be published without inheriting known unresolved
risk?

**Minimum evidence:** all upstream gate approvals, release checklist,
`Release_Standards.md` packet.

**Common blocking issues:**

* Stale asset in bundle.
* Missing approval.
* Mismatch between thumbnail/metadata and episode.
* Export technical failure.

## 12. Evidence Packets by Review Type

| Review type | Minimum packet contents |
| --- | --- |
| Story | Story file, canon links, research links, score sheet |
| Script | Script file, approved story review ID, voice references |
| Board | Board file, approved script review ID, camera citations |
| Image | Prompt, still, references, prompt QA record, score sheet |
| Animation | Prompt, clip, source still, QA record, score sheet |
| Audio | Audio files, script alignment, sound notes, score sheet |
| Edit | Cut reference, caption file, upstream visual/audio approvals |
| Thumbnail | Image, promise reference, score sheet |
| Metadata | Copy draft, episode reference, score sheet |
| Release | Bundle manifest, approval chain, release checklist, score sheet |
| Canon change | Proposal, impact map, affected assets, decision record |
| Standards change | Diff, rationale, affected workflows, approval record |

Incomplete evidence yields `Deferred`, not silent progress.

## 13. Revision Loop

### 13.1 Standard loop

```text
Submit artifact
↓
Formal review
↓
Disposition
↓
If Approved → close gate
If Approved with Conditions → track conditions
If Changes Requested → contributor revises
If Deferred → supply missing evidence
If Rejected → rework or stop
If Escalated → higher authority decides
↓
Resubmit with new version
↓
Formal re-review
```

### 13.2 Revision rules

* Every resubmission gets a new version label.
* Every resubmission gets a new review packet or a clearly linked continuation
  packet with revision cycle increment.
* Reviewers must inspect what changed.
* Unchanged dimensions may carry forward only per
  `Quality_Score_System.md` rescoring rules.
* Do not erase prior review history.

### 13.3 Revision SLA guidance

SLAs are local operational choices.

The review record must still name:

* Responsible owner.
* Required corrections.
* Whether downstream work is blocked or only partially allowed.

Avoid vague "fix later" conditions on release-bound artifacts.

## 14. Conditional Approval

`Approved with Conditions` is for cases where:

* The artifact is substantially usable.
* Remaining issues are bounded, verifiable, and low-risk if tracked.

### 14.1 Valid condition examples

* Replace one shot before final export.
* Verify caption timing on one section.
* Attach missing research citation to metadata.
* Regenerate one clip with documented prompt revision.

### 14.2 Invalid condition examples

* "Hope the edit hides it."
* "Maybe fix canon later."
* "Use if no better option appears."
* "Ignore continuity in background."

### 14.3 Condition tracking

Each condition must include:

* Condition ID.
* Description.
* Owner.
* Verification method.
* Blocking or non-blocking flag.
* Closure review ID when complete.

Release cannot close while blocking conditions remain open.

## 15. Escalation

Escalate when:

* Canon conflict cannot be resolved in the gate.
* Research answer is absent and story/visual truth depends on it.
* A standards exception is needed.
* Role authority is insufficient.
* Legal, platform, or child-safety concern appears.
* Repeated revisions fail the same hard gate.

### 15.1 Escalation route

```text
Discipline reviewer
↓
Quality lead
↓
Canon reviewer / research reviewer / standards owner as needed
↓
Release approver for publish conflicts
```

### 15.2 Escalation packet minimum

* Original review ID.
* Reason escalation is required.
* Options considered.
* Recommended path.
* Target authority.
* Deadline or dependency impact if known.

Escalation does not imply approval.

## 16. Closure

A gate is closed only when:

* Disposition is `Approved`, or
* `Approved with Conditions` and all blocking conditions are verified closed,
  or
* A higher authority documents an approved exception.

Closure requires:

* Final review packet.
* Resulting approved version label.
* Linked score record when applicable.
* Updated status visible to downstream contributors.

Do not infer closure from silence.

## 17. Relationship to Canon Change Process

When review finds a canon conflict that cannot be fixed by local correction:

1. Stop treating the conflict as a craft issue.
2. Mark review `Deferred` or `Escalated`.
3. Open or reference a canon-change proposal per `Canon_Change_Process.md`.
4. Do not approve downstream assets that depend on the unresolved canon state.

Approved canon changes trigger re-review of affected artifacts.

## 18. Relationship to Version Control

Review decisions must align with version state.

| Disposition | Typical version action |
| --- | --- |
| `Approved` | Mark version as approved for its scope |
| `Approved with Conditions` | Mark version as conditionally approved |
| `Changes Requested` | Keep version draft; do not promote |
| `Deferred` | Hold version pending |
| `Rejected` | Mark version rejected or supersede with rework |
| `Escalated` | Hold version pending authority |

Never delete a rejected version that explains a later correction.

## 19. Relationship to Production and AI Systems

| System | Review relationship |
| --- | --- |
| `08_Production/` | Defines when discipline work happens and local QC steps. |
| `08_Production/14_Quality_Control.md` | Supplies detailed operational checks consumed by reviewers. |
| `09_AI_Production_System/` | Defines prompt structure, locks, and camera rules reviewers enforce. |
| `09_AI_Production_System/14_Prompt_QA.md` | Supplies hard prompt/candidate checks before image/animation approval. |
| `07_Episode_System/` | Supplies format and pacing expectations for story/edit review. |
| `06_Story_Engine/` | Supplies story truth and safeguard expectations for story/script review. |

Workflow manuals say what to do.

This manual says how the decision is recorded and closed.

## 20. Informal Feedback Policy

Informal feedback is welcome.

It does not change approval state.

If informal feedback identifies a material defect:

* Convert to formal review, or
* Attach to an open formal review packet.

Contributors should not treat chat approval as gate approval.

## 21. Review Quality Checklist

Before closing any formal review packet, verify:

- [ ] Scope is explicit.
* [ ] Evidence links resolve.
* [ ] Authority links resolve.
* [ ] Disposition is one allowed value.
* [ ] Blocking issues are owned.
* [ ] Conditions are verifiable.
* [ ] Resulting version or status is named.
* [ ] Next action is named.
* [ ] Score record exists when required.
* [ ] Prior revision history is linked for resubmissions.

## 22. Worked Examples

### 22.1 Example A — Script changes requested

**Artifact:** `EP001_Script_v0.4.md`

**Scope:** Dialogue and narration readiness for boarding.

**Findings:** Elder Brother voice too modern in scene 3; one beat lacks clear
action verb.

**Disposition:** `Changes Requested`

**Owner:** Writer

**Required corrections:** Revise scene 3 lines; clarify beat 8 action.

**Resulting status:** Draft remains draft.

### 22.2 Example B — Image approved with condition

**Artifact:** `EP001_S03_IMG_v1.0.png`

**Scope:** Approved still for edit subject to one continuity fix.

**Findings:** Identity and style pass; basket handle angle differs from board.

**Disposition:** `Approved with Conditions`

**Condition:** Regenerate or patch handle angle; attach `v1.1` before final
assembly lock.

### 22.3 Example C — Release deferred

**Artifact:** `EP001_Release_Bundle_v1.0`

**Scope:** Publish approval.

**Findings:** Metadata draft promises a lesson the episode no longer contains.

**Disposition:** `Deferred`

**Missing evidence:** Revised metadata draft and story reviewer confirmation.

### 22.4 Example D — Canon escalation

**Artifact:** `EP002_Board_v0.2.pdf`

**Scope:** Board approval.

**Findings:** Scene introduces post office timing conflict with research record.

**Disposition:** `Escalated`

**Target authority:** Canon reviewer with research reviewer input.

## 23. Common Failure Modes

| Failure mode | Correct response |
| --- | --- |
| Approval without packet | Invalid; create packet before downstream use |
| Mixed dispositions | Split into separate packets or choose one primary |
| Conditions without owners | Not allowed; add owner and verification |
| Ignoring stale upstream approval after canon change | Force re-review |
| Reviewer outside scope approves anyway | Escalate or invalidate approval |
| Using informal chat as release sign-off | Block release |
| Deleting rejected history | Preserve and link to rework |
| "Approved" with open blocking conditions | Change to conditional or requested |

## 24. Exception Handling

A gate may be bypassed only by documented exception.

Exceptions require:

* Named gate and artifact.
* Reason.
* Compensating control.
* Expiry or re-review trigger.
* Approval by quality lead and affected discipline owner.

Exceptions never apply to child-safety, legal, or canon hard stops.

Record exceptions inside the review packet and version history.

## 25. Post-Release Review

If a published work requires correction:

1. Open a new review packet for the correction scope.
2. Identify affected assets and public records.
3. Decide whether correction is metadata-only, asset replacement, or audience
   notice required.
4. Link the correction review to the original release packet.
5. Update version and release records per `Version_Control.md` and
   `Release_Standards.md`.

Do not silently overwrite public meaning without a recorded decision.

## 26. Governance

Changes to required packet fields, dispositions, or role coverage require an
approved standards change.

Episode folders may not invent local disposition vocabularies.

Local checklists may be stricter.

They may not be looser without exception.

## 27. Quick Reference Card

```text
1. Name the artifact and scope
2. Link authority and evidence
3. Run scoring if applicable
4. Choose one disposition
5. Name blockers, conditions, and owner
6. Record version/status result
7. Close only with proof
```

| Disposition | Use when |
| --- | --- |
| Approved | Ready |
| Approved with Conditions | Ready with tracked proofs |
| Changes Requested | Fix and resubmit |
| Deferred | Missing evidence or authority |
| Rejected | Not fit for purpose |
| Escalated | Needs higher authority |

## 28. Final Rule

If the next contributor cannot tell what was decided, the review is not done.

If downstream work must guess, the review is not done.

If the audience would be misled and the packet still says approved, the review
failed.

Review to decide clearly.

Record to preserve the decision.

Close only when the decision is true.
