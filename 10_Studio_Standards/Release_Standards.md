# Release Standards

## 1. Purpose

This manual defines the minimum shared evidence and approval conditions required
before a Village Stories work may be published publicly.

It is a permanent studio governance standard, not a publishing how-to duplicate.

Its purpose is to ensure every public release is:

* Truthful to the finished episode.
* Canon-safe and continuity-safe.
* Technically deliverable.
* Legally and platform-compliant.
* Accessible to the intended audience.
* Traceable to approved upstream gates.
* Recoverable after publication.

Publishing steps belong in `08_Production/15_Publishing_Workflow.md`.

Release scoring belongs in `Quality_Score_System.md` Gate R.

Review records belong in `Review_Process.md`.

This manual defines what must exist before publish or schedule may be authorized.

## 2. Guiding Principle

A release is a promise.

The public title, thumbnail, description, captions, and video must tell the same
honest story.

A complete file folder is not proof of readiness.

A beautiful export is not proof of approval.

A scheduled time is not proof of truth.

When readiness conflicts with schedule, delay the release.

When evidence conflicts with confidence, gather evidence.

When a required gate is open, publication is blocked.

## 3. Scope

This standard applies to every public or audience-visible release, including:

* Long-form YouTube episodes.
* YouTube Shorts and connected short-form sequences.
* Thumbnails and packaging images shown publicly.
* Titles, descriptions, tags, chapters, and pinned comments.
* Captions, language fields, and essential accessibility surfaces.
* Cards, end screens, playlist placement, and linked destinations.
* Community posts tied to a specific episode release.
* Corrections, replacements, unlistings, and re-uploads that change audience
  meaning.
* Staged or scheduled publication that will become public without further
  review.

This standard applies whether upload is manual, scheduled, or tool-assisted.

This standard applies to first release and to material post-release changes.

## 4. Non-Scope

This manual does not:

* Define publishing UI steps. See `08_Production/15_Publishing_Workflow.md`.
* Define detailed QC checklists by discipline. See
  `08_Production/14_Quality_Control.md`.
* Define weighted release scoring math. See `Quality_Score_System.md` Gate R.
* Define review packet fields in full. See `Review_Process.md`.
* Define version labels and supersession. See `Version_Control.md`.
* Define canon-change procedure. See `Canon_Change_Process.md`.
* Define naming syntax. See `Naming_Standards.md`, `Asset_Naming.md`, and
  related standards.

Workflow manuals may add operational detail.

They may not reduce the minimum evidence defined here without an approved
standards change or documented exception.

## 5. Authority Hierarchy

Release readiness must satisfy the highest applicable authority.

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
08_Production/ execution and QC manuals
↓
09_AI_Production_System/ prompt, lock, and camera bibles
↓
10_Studio_Standards/ scoring, review, version, and release standards
↓
Release bundle under authorization
```

If any authority conflict remains unresolved, publication is blocked.

## 6. Definitions

**Release** — The act of making an approved work visible to the public audience
through a platform or equivalent distribution surface.

**Release bundle** — The complete set of approved assets, metadata, records, and
evidence required for one publication event.

**Release authorization** — A formal `Approved` or `Approved with Conditions`
decision for Gate R with linked evidence.

**Release record** — The permanent studio record of what was published, when, by
whom, with which versions, and under which review IDs.

**Platform master** — The final encoded video file approved for upload.

**Packaging** — Thumbnail, title, description, and other pre-view surfaces that
shape audience expectation.

**Promise triangle** — The requirement that thumbnail, title/description, and
episode content agree in tone, subject, and emotional claim.

**Gate closure** — Confirmation that all required upstream formal reviews are
closed for the versions included in the bundle.

**Live verification** — Post-upload confirmation that YouTube processing and
configured fields match the approved release bundle.

**Material correction** — Any change that alters audience meaning, canon
implication, accessibility, or technical delivery enough to require a new
release record.

**Schedule hold** — Publication timing deferred while readiness evidence is
completed.

## 7. Release Philosophy

Village Stories releases should feel as careful as the episodes themselves.

The audience should not need insider knowledge to understand what they are
about to watch.

The studio should not need private memory to understand what was published.

A release is successful when:

* The viewer receives what was promised.
* The studio can prove what was released.
* Future episodes can build on the published state without contradiction.
* Corrections, if needed, are proportionate and recorded.

## 8. Mandatory Preconditions

All preconditions must be true before release authorization.

If any precondition fails, the release is not ready.

| ID | Precondition |
| --- | --- |
| PRE-01 | Episode or release scope is identified with stable episode ID or equivalent release ID. |
| PRE-02 | All required upstream gates are closed for the exact versions in the bundle. |
| PRE-03 | No unresolved hard gate failure affects any bundle item. |
| PRE-04 | No unresolved canon conflict affects public-facing meaning. |
| PRE-05 | Release bundle manifest is complete. |
| PRE-06 | Gate R review packet exists with reviewer of record. |
| PRE-07 | Version labels for all bundle items are visible and current. |
| PRE-08 | Rights, credits, and required disclosures are complete or explicitly not applicable with record. |
| PRE-09 | Accessibility minimums are met or covered by approved exception. |
| PRE-10 | Publisher identity and rollback path are documented. |

## 9. Required Upstream Gate Closure

A release may not proceed while required upstream gates remain open for the
versions being shipped.

### 9.1 Standard long-form episode

| Upstream gate | Minimum closure evidence |
| --- | --- |
| Story | Approved story review ID for current premise version |
| Script | Approved script review ID for current script version |
| Board | Approved board review ID for current board version |
| Image / animation assets | Approved asset review IDs or manifest list for all used shots |
| Audio | Approved audio review ID for narration and essential sound |
| Edit | Approved edit review ID for current master version |
| Thumbnail | Approved thumbnail review ID |
| Metadata | Approved metadata review ID |

### 9.2 Short-form episode or Short

Short-form releases use the same truth and continuity requirements.

They may use a reduced creative packet only when the episode format declaration
explicitly permits it and the release manifest says which gates were in scope.

Never reduce:

* Canon and continuity checks.
* Thumbnail and metadata honesty checks.
* Accessibility minimums.
* Rights and platform checks.

### 9.3 Connected multi-part Shorts

When shorts connect as a sequence:

* Declare sequence ID and part number in the release record.
* Confirm continuity state across parts in the manifest.
* Confirm each part's packaging does not misstate its place in the sequence.
* Link upstream approvals for each part included in the release event.

### 9.4 Re-release, replacement, or correction

If the public artifact changes materially:

* Open a new Gate R packet.
* Link the prior release record.
* Identify which upstream gates require re-closure.
* Do not assume the old release authorization covers the new file.

## 10. Release Bundle Manifest

Every release must have one manifest.

The manifest is the checklist of what is being published.

### 10.1 Manifest required fields

| Field | Required |
| --- | --- |
| Release ID | Yes |
| Episode ID or release scope ID | Yes |
| Format | Yes |
| Target platform | Yes |
| Release type | Yes |
| Scheduled or immediate | Yes |
| Release owner | Yes |
| Publisher | Yes |
| Gate R review ID | Yes |
| Platform master filename and version | Yes |
| Thumbnail filename and version | Yes |
| Title text and version | Yes |
| Description text and version | Yes |
| Caption file and version | Yes |
| Language fields | Yes |
| Visibility setting | Yes |
| Playlist placements | If used |
| Chapters | If used |
| Cards and end screens | If used |
| Pinned comment | If used |
| Community post copy | If used |
| Rights and credits note | Yes |
| Upstream approval list | Yes |
| Known limitations | If any |
| Correction path | Yes |

### 10.2 Manifest storage

Store the manifest with the episode release record per `Folder_Standards.md`.

Name it per `Naming_Standards.md` and `Asset_Naming.md`.

Version it per `Version_Control.md`.

The manifest must be findable without searching chat or upload UI history.

### 10.3 Manifest integrity rules

* Every file named in the manifest must match the approved version exactly.
* No substitute file may be uploaded because it "looks similar."
* If a file changes after manifest finalization, regenerate manifest and
  re-run Gate R.
* The manifest must list review IDs, not only filenames.

## 11. Minimum Evidence by Bundle Item

### 11.1 Platform master

Required evidence:

* Approved edit review ID.
* Exact master filename and version label.
* Duration and format specification.
* Audio loudness or technical note if applicable.
* Start, middle, and end spot-check notes from final review or live
  verification plan.

Blocking conditions:

* Wrong master version.
* Known continuity defect not covered by approved condition.
* Missing caption sync where narration exists.
* Unauthorized story change relative to approved script.

### 11.2 Thumbnail

Required evidence:

* Approved thumbnail review ID.
* Exact image filename and version label.
* Small-size readability proof or reviewer attestation.
* Promise triangle check note against title and episode.

Blocking conditions:

* Misleading emotion or subject.
* Wrong character emphasis.
* Canon or period break.
* Text illegible at mobile size when text is used.

### 11.3 Title and description

Required evidence:

* Approved metadata review ID.
* Exact title and description text versions.
* Policy and honesty check note.
* Educational or cultural claim citations when claims are made.

Blocking conditions:

* Promise triangle failure.
* False educational claim.
* Spoiler misuse.
* Clickbait framing that the episode does not honor.

### 11.4 Captions and accessibility

Required evidence:

* Caption file and version.
* Accessibility review note or checklist result.
* Language field confirmation.

Minimum accessibility standard for release:

* Captions present for narrated or dialogue-driven episodes unless a documented
  platform limitation and compensating control are approved.
* Caption text matches approved script intent without material unauthorized
  change.
* Essential on-screen text is readable and not contradicted by captions.

Blocking conditions:

* Missing required captions.
* Material caption mismatch.
* Accessibility failure covered by neither fix nor approved exception.

### 11.5 Tags, chapters, playlists, cards, and end screens

Required evidence when used:

* Exact configured values recorded in manifest.
* Destination link list.
* Confirmation that destinations are truthful and relevant.

Blocking conditions:

* Card or end screen promises a different kind of video.
* Playlist placement contradicts episode type or sequence truth.
* Chapter labels misstate content.

### 11.6 Rights, credits, and disclosures

Required evidence:

* Rights source note for non-original material if any is used.
* Music, stock, voice, or licensed asset credits as required.
* AI disclosure or platform-required statements when applicable.
* Age suitability or content advisory state.

Blocking conditions:

* Unknown rights status for material used in the release.
* Missing required disclosure.
* Legal or platform restriction unresolved.

## 12. Promise Triangle Standard

The promise triangle must pass before release authorization.

| Surface | Must honestly reflect |
| --- | --- |
| Thumbnail | Main emotional and subject focus of the episode |
| Title | Episode type, central subject, and tone |
| Description | What happens, what the viewer gains, and what not to expect |
| Episode | Approved story, visuals, sound, and ending |

### 12.1 Promise triangle pass rules

Pass when:

* A viewer who reads only packaging would not be surprised by the episode's
  actual subject and emotional arc.
* No packaging surface invents conflict, danger, or spectacle absent from the
  episode.
* Educational claims in metadata are supported by the episode and research
  references where needed.
* Connected shorts clearly signal part/sequence context when relevant.

Fail when:

* Packaging is more dramatic than the episode.
* Packaging highlights a minor background detail as the main premise.
* Metadata claims a lesson the episode does not deliver.
* Thumbnail character or prop state contradicts the episode opening.

Promise triangle failure blocks release regardless of Gate R composite score.

## 13. Approval Conditions

Release authorization requires Gate R disposition of `Approved` or `Approved with
Conditions` per `Review_Process.md`.

### 13.1 Approved

`Approved` means:

* All preconditions pass.
* All required evidence is present.
* Promise triangle passes.
* No open blocking conditions.
* Gate R score meets pass rules in `Quality_Score_System.md`.

### 13.2 Approved with Conditions

`Approved with Conditions` is allowed only for bounded, verifiable items such
as:

* Schedule publication after a named future time while bundle remains unchanged.
* Monitor one non-blocking live verification step after processing.
* Replace a non-public metadata typo before visibility changes from scheduled
  private to public, with named verifier.

`Approved with Conditions` is not allowed for:

* Canon uncertainty.
* Missing captions when required.
* Wrong master or thumbnail version.
* Unresolved rights issue.
* Known promise triangle failure.

### 13.3 Blocked dispositions

These dispositions block publication:

* `Changes Requested`
* `Deferred`
* `Rejected`
* `Escalated` without later closure

## 14. Roles and Release Authority

| Role | Release authority |
| --- | --- |
| Contributor | May assemble bundle; may not authorize release |
| Quality lead | May recommend Gate R outcome; may block release |
| Release reviewer | May record Gate R for release readiness |
| Release manager | Owns readiness decision and release record |
| Publisher | May upload only after release authorization |
| Canon reviewer | May block release for truth or continuity conflict |
| Release approver | Final publish authorization within delegated authority |

No single role may both create and unilaterally approve a release bundle except
under a documented emergency exception with compensating control.

## 15. Release Authorization Record

Every authorized release must leave one authorization record.

### 15.1 Required fields

| Field | Required |
| --- | --- |
| Authorization ID | Yes |
| Release ID | Yes |
| Gate R review ID | Yes |
| Disposition | Yes |
| Authorizing reviewer | Yes |
| Authorization date and time | Yes |
| Exact publish mode | Yes |
| Manifest link | Yes |
| Publisher | Yes |
| Open conditions | If any |
| Expiry or re-review trigger | If conditional |

### 15.2 Authorization validity

Authorization is valid only for:

* The exact manifest versions it names.
* The declared platform and visibility mode.
* The declared release type.

Authorization expires when:

* Any named bundle item changes materially.
* A blocking condition is discovered.
* A canon or research correction affects public meaning.
* Required upstream approval is superseded.

## 16. Scheduling Rules

Scheduled publication is treated as a release commitment.

### 16.1 Schedule prerequisites

Before scheduling:

* Gate R authorization must already exist.
* Manifest must be complete.
* Publisher must confirm upload source matches manifest.
* Rollback plan must be documented.

### 16.2 Schedule change rules

If any bundle item changes after scheduling:

* Pause or cancel schedule.
* Re-run Gate R.
* Issue new authorization record.

Do not let a scheduled clock substitute for re-approval.

### 16.3 Delay policy

Delay rather than publish when:

* Evidence packet is incomplete.
* Live verification fails.
* Promise triangle cannot be confirmed.
* Rights or accessibility status is uncertain.

Record the delay reason in the release record.

## 17. Live Verification

Live verification confirms that the platform received what the studio approved.

It is required after upload and after YouTube processing completes.

### 17.1 Minimum live checks

| Check | Required |
| --- | --- |
| Correct video attached | Yes |
| Duration matches approved master tolerance | Yes |
| Thumbnail displayed is approved version | Yes |
| Title and description match manifest | Yes |
| Caption track present and enabled when required | Yes |
| Start playback clean | Yes |
| Mid playback spot check | Yes |
| Ending matches approved emotional rest | Yes |
| Cards and end screens | If used |
| Visibility matches authorization | Yes |

### 17.2 Live verification failure

If live verification fails:

* Do not leave a public misleading state uncorrected.
* Unlist, private, or correct per platform options.
* Open a correction release record.
* Re-run Gate R if the public artifact changed.

## 18. Short-Form and Long-Form Release Differences

### 18.1 Long-form

Long-form releases require the full standard upstream gate list unless a
documented format exception exists.

Long-form endings must preserve emotional rest per Episode System guidance.

End screens and continuation links must be optional and truthful.

### 18.2 Short-form

Short-form releases still require:

* Promise triangle pass.
* Approved master and packaging.
* Caption minimums when narration or dialogue exists.
* Continuity truth for connected sequences.

Short-form may omit some board granularity only when the format declaration and
manifest explicitly record the reduced scope.

### 18.3 Hybrid campaigns

When one story uses both shorts and long-form:

* Declare relationship in release records.
* Avoid packaging that makes shorts look like unrelated click bait.
* Ensure sequence state is consistent across published parts.

## 19. Archive and Recovery Requirements

A release is not complete until the studio can recover it.

### 19.1 Minimum archive set

| Item | Required |
| --- | --- |
| Approved platform master | Yes |
| Approved thumbnail | Yes |
| Manifest | Yes |
| Authorization record | Yes |
| Gate R review packet | Yes |
| Metadata text versions | Yes |
| Caption file | Yes |
| Upstream approval list | Yes |
| Live verification note | Yes |
| Platform URL or ID after publish | Yes |

### 19.2 Recovery test

Another contributor should be able to answer from archive alone:

* What was published?
* Which versions were used?
* Who approved it?
* What upstream gates closed it?
* What changed in later corrections?

If not, release archive is incomplete.

## 20. Post-Release Corrections

Corrections must be proportionate, truthful, and recorded.

### 20.1 Correction classes

| Class | Examples | Typical response |
| --- | --- | --- |
| Metadata-only | Typo, tag cleanup | New metadata review; note in release record |
| Packaging replacement | Thumbnail swap | New thumbnail and Gate R packet |
| Technical replacement | Wrong export, audio glitch | New edit approval and Gate R packet |
| Meaning correction | Misleading description, wrong claim | Metadata correction and audience notice if needed |
| Canon-audience conflict | Public state contradicts canon | Canon change or correction workflow |

### 20.2 Correction rules

* Link correction record to original release ID.
* Identify public impact before acting.
* Do not silently change meaning.
* Re-run affected gates.
* Update version and review history.
* Re-score Gate P or Gate R when packaging or release package changes.

### 20.3 Unlisting and takedown

Unlisting or takedown requires:

* Named reason.
* Release record update.
* Owner and authorization.
* Note whether audience notice is required.

## 21. Exceptions

A release exception permits a limited departure from this standard.

Exceptions require:

* Named rule and bundle item.
* Reason and risk.
* Compensating control.
* Owner and approver.
* Expiry or re-review trigger.
* Quality lead and release approver sign-off.

Exceptions never waive:

* Child-safety obligations.
* Legal or platform prohibitions.
* Deliberate audience deception.
* Unresolved canon conflict without canon process.

Record exceptions in the Gate R packet and release record.

## 22. Relationship to Other Standards

| Document | Relationship |
| --- | --- |
| `README.md` | Defines shared release philosophy and enforcement |
| `Quality_Score_System.md` | Gate R scores how fully the bundle satisfies this standard |
| `Review_Process.md` | Records Gate R disposition and closure |
| `Version_Control.md` | Tracks bundle item versions and superseded releases |
| `Canon_Change_Process.md` | Governs public meaning changes requiring canon action |
| `08_Production/14_Quality_Control.md` | Operational QC checks feeding release readiness |
| `08_Production/15_Publishing_Workflow.md` | Step-by-step publish, schedule, and verify workflow |

If this manual and Gate R scoring diverge on publication minimums, this manual
controls publication.

## 23. Release Readiness Checklist

### 23.1 Before Gate R submission

- [ ] Episode or release ID confirmed
- [ ] Manifest draft complete
- [ ] All upstream approvals current for exact versions
- [ ] Platform master version confirmed
- [ ] Thumbnail version confirmed
- [ ] Metadata text versions confirmed
- [ ] Caption file attached
- [ ] Rights and disclosures complete
- [ ] Promise triangle checked
- [ ] Known limitations documented

### 23.2 Before publish or schedule

- [ ] Gate R authorization on record
- [ ] Open conditions tracked with owners
- [ ] Publisher matches manifest
- [ ] Rollback path documented
- [ ] Live verification plan assigned

### 23.3 After publish

- [ ] Live verification completed
- [ ] Platform URL or ID recorded
- [ ] Archive set stored
- [ ] Release record closed or conditions closed
- [ ] Lessons learned note opened if failure occurred

## 24. Worked Examples

### 24.1 Example A — Standard long-form release approved

**Release ID:** `REL_EP001_v1.0`

**Evidence:** Full upstream approval list, manifest, promise triangle pass,
captions attached, rights note complete.

**Gate R:** `Approved`

**Outcome:** Publisher schedules upload; live verification completes; archive
stored with platform URL.

### 24.2 Example B — Blocked by stale thumbnail approval

**Release ID:** `REL_EP002_v1.0`

**Issue:** Manifest uses `THB_EP002_v1.2.png` but latest approved thumbnail
review covers `v1.1` only.

**Gate R:** `Changes Requested`

**Outcome:** Thumbnail re-approved or manifest corrected before publish.

### 24.3 Example C — Conditional schedule approval

**Release ID:** `REL_EP003_v1.0`

**Issue:** Bundle complete; team wants overnight schedule after final live
verification assignment.

**Gate R:** `Approved with Conditions`

**Condition:** Live verification note must be added within 24 hours of
processing; release manager closes condition.

### 24.4 Example D — Post-release metadata correction

**Release ID:** `REL_EP004_v1.0`

**Issue:** Description overstates educational claim.

**Action:** Metadata-only correction, new metadata review ID, linked correction
record, no master replacement.

## 25. Common Failure Modes

| Failure mode | Correct response |
| --- | --- |
| Upload because files exist | Block; complete manifest and Gate R |
| Use latest file instead of approved version | Reject; restore approved version |
| Promise triangle ignored | Block release |
| Schedule without authorization | Cancel schedule |
| Missing caption file | Block or approved exception only |
| Live verification skipped | Do not close release record |
| Silent thumbnail swap after approval | Re-run Gate R |
| Chat approval treated as authorization | Invalid; create authorization record |
| Archive only on platform | Store studio archive set |

## 26. Anti-Patterns

Do not:

* Publish to hit a date when Gate R is open.
* Let Shorts packaging exaggerate conflict for clicks.
* Hide canon defects behind vague description wording.
* Assume AI generation history proves approval.
* Treat private upload as a substitute for review when the work is intended to
  become public.
* Delete release history when correcting a mistake.
* Publish first and gather rights later.

## 27. Metrics and Learning

Release records may inform:

* Recurring packaging failures.
* Live verification defects.
* Correction frequency by class.
* Delay reasons.

Do not use release metrics to justify lower truth standards.

Repeated failures should trigger workflow or standards review.

## 28. Quick Reference Card

```text
1. Close upstream gates for exact versions
2. Complete manifest
3. Pass promise triangle
4. Obtain Gate R authorization
5. Publish only approved bundle
6. Run live verification
7. Archive and close record
```

| Missing item | Result |
| --- | --- |
| Upstream approval | Blocked |
| Manifest | Blocked |
| Authorization record | Blocked |
| Promise triangle fail | Blocked |
| Rights uncertainty | Blocked |
| Live verification fail | Correct before close |

## 29. Governance

Changes to required evidence, preconditions, or authority rules require an
approved standards change.

Episode folders may add stricter local release checks.

They may not reduce the minimum shared evidence without exception.

## 30. Final Rule

If the studio cannot prove what it is about to publish, it is not ready.

If the audience would feel misled after clicking, it is not ready.

If future episodes would inherit a contradiction from this release, it is not
ready.

Release only when the promise is true, the evidence is complete, and the record
will survive without you in the room.
