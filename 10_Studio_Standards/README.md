# Studio Standards

## Purpose

`10_Studio_Standards/` is the permanent governance manual for shared Village Stories studio conventions.

It defines the rules that keep work findable, attributable, reviewable, compatible, and safe to continue across episodes, operators, tools, and years.

It governs conventions shared by the whole studio.

It does not duplicate the detailed creative, production, prompt, template, or lesson workflows maintained elsewhere.

Use this folder when deciding:

* What a file, asset, prompt, version, or release record must be called.
* Where a shared studio artifact belongs.
* Which document has authority when instructions overlap.
* How a convention becomes approved, changed, communicated, and retired.
* What evidence is required before work passes a shared quality gate.
* How exceptions are requested without silently creating a competing rule.

The objective is continuity of operations, not bureaucracy for its own sake.

---

# Studio Philosophy

Village Stories is a long-lived body of work, not a collection of isolated uploads.

Every convention must help a future contributor understand the work without relying on undocumented memory.

Standards exist to reduce avoidable uncertainty.

They protect:

* Canonical truth.
* Historical and cultural care.
* Character, location, object, and visual continuity.
* Reliable handoffs between creative and technical roles.
* Recoverable version history.
* Honest, repeatable release quality.
* Reuse of approved assets and knowledge.

A convention is valuable when it makes the correct action easier than an improvised action.

A convention is not valuable merely because it is detailed.

Prefer the smallest rule that prevents recurring confusion, loss, drift, or rework.

---

# Scope

This folder governs studio-wide conventions that apply across more than one system, episode, role, or tool.

It covers:

* Naming syntax and reserved terms.
* Folder structure and placement expectations.
* Asset and prompt identification.
* Version status and revision history.
* Canon-change governance.
* Shared quality scoring and review records.
* Release readiness standards.
* Exception handling and enforcement.

This folder does not own:

* The facts of the fictional world.
* Character, location, object, or style canon.
* Story design or episode structure.
* Step-by-step production execution.
* AI prompt composition, lock construction, or tool-specific prompting.
* Reusable document and production templates.
* Retrospective learning records.

Those responsibilities belong to their designated source systems.

---

# Governing Principle

Make every decision traceable, every handoff understandable, and every approved result safe to reuse.

When speed, novelty, or convenience conflicts with that principle, protect traceability, understanding, and reuse.

---

# Index

| File | Single responsibility |
| --- | --- |
| `Naming_Standards.md` | Defines the universal syntax, tokens, separators, capitalization, dates, and prohibited naming patterns used across studio records. |
| `Folder_Standards.md` | Defines the shared rules for folder purpose, placement, ownership, archival boundaries, and prohibited storage practices. |
| `Asset_Naming.md` | Defines unique, human-readable names and identifiers for visual, audio, document, project, and reference assets. |
| `Prompt_Naming.md` | Defines names, identifiers, statuses, and lineage labels for reusable prompts, prompt modules, and episode prompt instances. |
| `Version_Control.md` | Defines version labels, change records, approval states, supersession, and recovery expectations for governed artifacts. |
| `Canon_Change_Process.md` | Defines how proposed canon changes are evidenced, reviewed, approved, recorded, communicated, and applied. |
| `Quality_Score_System.md` | Defines the shared scoring dimensions, thresholds, evidence requirements, and interpretation rules used at quality gates. |
| `Review_Process.md` | Defines the studio-wide review roles, review records, disposition states, escalation route, and closure requirements. |
| `Release_Standards.md` | Defines the minimum shared evidence and approval conditions required before a public release may be published. |

Each planned file has one primary responsibility.

Do not move a responsibility into another standard merely because it is related.

Cross-reference the owning standard instead.

---

# Authority Hierarchy

When two instructions appear to conflict, use the highest applicable authority.

```text
Studio mission, audience promise, and legal or platform obligations
↓
01_Canon/ and approved canonical decisions
↓
02_World/ · 03_Characters/ · 04_Objects/ · 05_Research/
↓
06_Story_Engine/ · 07_Episode_System/
↓
10_Studio_Standards/ shared conventions and governance
↓
08_Production/ production workflow and approved episode records
↓
09_AI_Production_System/ prompt systems, locks, and generation controls
↓
11_Templates/ approved reusable forms and starting structures
↓
12_Lessons_Learned/ retrospective evidence and improvement proposals
↓
Working files, drafts, experiments, and generated outputs
```

This hierarchy answers authority questions; it does not erase ownership boundaries.

For example, a production workflow may define when a review occurs, while this folder defines the shared status labels and record expectations used by that review.

An approved episode-specific decision may constrain work for that episode.

It cannot silently change a higher-level canon fact or a studio-wide standard.

Only a documented change through the owning authority may do that.

---

# Authority Rules

## Higher authority wins

If a lower-level document conflicts with a higher-level document, stop using the conflicting instruction.

Record the conflict where the work is being reviewed.

Correct the lower-level document through its owning process.

## Specific authority applies within its scope

A specific, approved rule is stronger than a general rule only inside the specific rule's declared scope.

An episode exception does not become a series convention.

A tool-specific rule does not become a studio-wide rule.

## Current approved version wins

Within one authority level, the current approved version is controlling.

Superseded material may be retained for history but must be clearly marked as non-current.

## Absence of a rule is not permission

When a decision could affect canon, continuity, release integrity, safety, traceability, or shared reuse, do not infer permission from silence.

Escalate the question to the owner of the relevant system.

---

# Document Status Language

Every governed artifact should use a clear status when its state matters to another person or system.

Use only these meanings:

| Status | Meaning |
| --- | --- |
| `Draft` | Being prepared; not approved for operational use. |
| `In Review` | Submitted for evaluation; may change. |
| `Approved` | Accepted for its declared scope and ready for use. |
| `Active` | Approved and currently intended for routine use. |
| `Conditional` | Usable only with the stated constraint, owner, or expiry. |
| `Deprecated` | Retained for transition or history; do not start new work from it. |
| `Superseded` | Replaced by a named approved successor. |
| `Archived` | Retained as historical record; not operational guidance. |
| `Rejected` | Considered and not approved; retained only when useful for decision history. |

Do not use ambiguous labels such as “final,” “latest,” “new,” or “use this one” as a status substitute.

---

# Standards Workflow

A studio convention follows this lifecycle:

```text
Observed recurring need
↓
Written proposal with scope and evidence
↓
Compatibility and ownership check
↓
Review by affected owners
↓
Approval or rejection
↓
Publication in the owning standard
↓
Adoption in affected systems and templates
↓
Use, review evidence, and periodic reassessment
↓
Revision, deprecation, or retirement when justified
```

No convention is active merely because someone used it once.

No convention is retired merely because a newer practice is preferred informally.

## 1. Identify the need

Propose a standard only when a shared need exists.

Valid triggers include:

* Repeated naming collisions or misplaced files.
* Inconsistent approvals or missing revision history.
* A quality failure that crossed team or episode boundaries.
* A recurring handoff delay caused by unclear expectations.
* A new tool, distribution requirement, or legal requirement.
* A lesson that has been demonstrated in more than one use case.

## 2. Define the boundary

State what the proposed rule governs and what it deliberately does not govern.

Name the files, roles, systems, and artifacts affected.

Do not write a broad standard to solve a narrow local issue.

## 3. Check ownership

Determine whether the rule belongs in:

* Canon or research.
* The episode system.
* Production.
* The AI Production System.
* Templates.
* Lessons Learned.
* Studio Standards.

If it belongs in another system, refer the proposal there.

Studio Standards may record the shared convention only when the rule crosses those systems or establishes their common language.

## 4. Test compatibility

Check the proposal against active names, folders, templates, assets, prompt modules, review records, and releases.

Identify migration work before approval.

Do not approve a convention that requires silent mass renaming or breaks traceability without a migration plan.

## 5. Review and decide

The appropriate owners review the proposal.

The decision must be recorded as approved, conditionally approved, deferred, or rejected.

A conditional approval must state the condition, owner, and expiry or review point.

## 6. Publish and communicate

Place the approved rule in its owning document.

Update only the affected templates, workflow references, and active examples.

Publish a short change note that states the effective date, scope, and required action.

## 7. Verify adoption

At the next applicable review gate, check whether new work follows the convention.

Correct misunderstanding before treating it as noncompliance.

## 8. Reassess

Review a convention when evidence shows it is unclear, costly, obsolete, or insufficient.

Prefer revision over adding parallel exceptions.

---

# Roles and Responsibilities

Roles may be held by one person in a small studio.

The responsibilities remain distinct even when the person is the same.

## Studio Owner

The Studio Owner is the final steward of the Village Stories operating system.

The Studio Owner:

* Approves studio-wide standards and material exceptions.
* Resolves authority conflicts that cross system owners.
* Ensures standards support the audience promise and long-term continuity.
* Assigns or confirms system owners.
* Authorizes retirement of an active shared convention.

## Canon Owner

The Canon Owner protects the truth and continuity of the series world.

The Canon Owner:

* Approves or rejects canon changes through the canon-change process.
* Clarifies canonical ambiguity.
* Identifies when a proposed standard would alter world truth.
* Ensures standards never override established canon.

## Production Owner

The Production Owner owns the executable episode workflow in `08_Production/`.

The Production Owner:

* Applies shared standards within production planning, making, review, release, and archive work.
* Defines production-specific procedures without duplicating shared convention rules.
* Escalates recurring production failures that require a studio-wide standard.
* Confirms that an episode meets operational release gates.

## AI Production System Owner

The AI Production System Owner owns reusable prompt architecture and generation controls in `09_AI_Production_System/`.

The AI Production System Owner:

* Applies shared naming, version, review, and quality conventions to prompts and generated assets.
* Preserves the distinction between reusable prompt systems and episode-specific production decisions.
* Escalates tool or prompt practices that require a shared convention.
* Does not use an AI output or prompt change to establish new canon.

## Templates Owner

The Templates Owner maintains approved reusable forms and starting structures in `11_Templates/`.

The Templates Owner:

* Keeps templates aligned with active studio standards.
* Removes superseded conventions from active templates.
* Ensures a template guides use without becoming a competing policy.
* Routes policy changes to the responsible standards owner.

## Lessons Learned Owner

The Lessons Learned Owner maintains evidence from completed work in `12_Lessons_Learned/`.

The Lessons Learned Owner:

* Records observations, decisions, outcomes, and recommendations.
* Distinguishes evidence from approved policy.
* Proposes standards changes when lessons demonstrate a repeated shared need.
* Does not declare a lesson to be mandatory without approval.

## Contributors and Operators

Contributors and operators are responsible for following active standards in work they create, modify, review, or release.

They must:

* Use approved names, folders, statuses, templates, and review records.
* Preserve identifiers and history when revising artifacts.
* Report an unclear, conflicting, or impractical standard promptly.
* Request an exception before intentionally departing from an active standard.
* Avoid solving a shared issue with a private undocumented workaround.

## Reviewers

Reviewers assess work against the applicable authority and record a clear disposition.

Reviewers must:

* Review evidence, not assumptions.
* Separate blocking issues from suggestions.
* Cite the applicable rule or authority for a blocking issue.
* Escalate conflicts they cannot resolve within their authority.
* Confirm closure of blocking issues before approval.

---

# Relationship With 08 Production

`08_Production/` defines how an approved episode is planned, made, checked, released, and archived.

`10_Studio_Standards/` defines shared conventions that production must use consistently with other systems.

Production owns:

* Episode execution stages.
* Operational handoffs.
* Production-specific checklists.
* Production asset handling.
* Final assembly and publishing workflow.

Studio Standards owns:

* The common language for statuses, versioning, review evidence, and release readiness.
* Cross-system naming and folder rules.
* Governance for conventions that affect more than production.

Do not copy a production workflow into this folder.

Instead, state the shared convention here and link production procedures to it when they need to apply it.

Production remains responsible for determining whether an episode is operationally ready.

Studio Standards determines what makes that determination traceable and consistently expressed.

---

# Relationship With 09 AI Production System

`09_AI_Production_System/` defines reusable prompt architecture, lock systems, generation practice, prompt QA, diagnosis, and AI-asset revision.

`10_Studio_Standards/` governs only the shared conventions those systems must observe.

The AI Production System owns:

* Prompt construction and modularity.
* Character, location, object, style, and camera locks.
* Tool-specific generation practice.
* Prompt-level quality assurance.
* AI failure diagnosis and revision workflow.

Studio Standards owns:

* Cross-system prompt names and identifiers.
* Approved status and version meanings.
* Shared review record expectations.
* Escalation when AI work exposes a governance gap.

An AI prompt may improve a result without changing a standard.

A prompt module may become a studio convention only after it is reviewed for cross-system applicability and approved by the proper owner.

AI generation never creates authority over canon, production decisions, or release standards.

---

# Relationship With 11 Templates

`11_Templates/` contains reusable structures that help the studio apply active rules consistently.

Templates are implementation aids.

They are not authority sources.

When a template and an active standard disagree, the active standard wins.

The template must then be corrected and versioned.

A template should:

* Name its purpose and intended user.
* Identify its governing standards where useful.
* Preserve required fields and status labels.
* Avoid embedded rules that contradict or duplicate the source standard.
* Be reviewed when the standards it implements change.

Do not change a template merely to avoid requesting a justified standards change.

Do not change a standard merely because a template was poorly designed.

---

# Relationship With 12 Lessons Learned

`12_Lessons_Learned/` preserves observations from production, review, release, and reuse.

Lessons Learned is the studio's evidence base for improvement.

It is not a second policy library.

A lesson may identify:

* A repeated source of confusion.
* A missing or ambiguous standard.
* A convention that creates unnecessary work.
* A quality signal that was missed.
* A successful practice worth testing more broadly.

Until formally approved, a lesson is informative rather than mandatory.

When a lesson justifies a new or changed convention, create a proposal through the Standards Workflow.

Link the approved standard to the supporting lesson record when that context will aid future review.

---

# Quality Standard

Quality is not limited to visual attractiveness or technical correctness.

A production-ready studio artifact is quality-ready only when it is:

* Correct within its applicable authority.
* Complete for its declared purpose.
* Consistent with adjacent assets, decisions, and records.
* Traceable to its source, owner, version, and review state.
* Reusable without hidden assumptions.
* Accessible to the next responsible contributor.
* Honest about its limits, conditions, and unresolved risks.

The detailed shared scoring method belongs in `Quality_Score_System.md`.

Production, AI prompt, and release workflows may add discipline-specific checks.

They must not redefine the shared meanings of approval, quality evidence, or score thresholds without an approved standard change.

## Minimum quality questions

Before approving any governed artifact, ask:

* Is the owner and scope clear?
* Is the current status visible?
* Does the name preserve identity and retrieval?
* Is the applicable version identifiable?
* Does the content follow higher authority?
* Is required evidence attached or linked?
* Could another contributor use or review it without private context?
* Are limitations, dependencies, and next actions visible?

If a material answer is no, the artifact is not ready for approval.

---

# Continuity Standard

Continuity is the ability to carry correct state forward without loss, contradiction, or accidental reinvention.

Studio-wide continuity includes:

* Canonical facts.
* Character identity and recurring visual state.
* Location geography and object state.
* Story, scene, and episode state.
* Asset identity and approved source relationships.
* Prompt lineage and revision history.
* Review outcomes and release records.
* Naming, folder, and archive structure.

Every handoff must identify what remains fixed, what has changed, and what evidence establishes the new state.

When continuity evidence is missing, do not fill the gap with confidence.

Mark the issue, locate the owner, and resolve it before the uncertainty becomes a reused error.

---

# Review Standard

Review is a decision process, not a vague request for feedback.

Every formal review must identify:

* The artifact or decision being reviewed.
* The review scope.
* The applicable authority.
* The reviewer or reviewers.
* The evidence examined.
* The disposition.
* Blocking issues, if any.
* Required corrections and responsible owner.
* The date and resulting version or status.

Use one of these dispositions:

| Disposition | Meaning |
| --- | --- |
| `Approved` | Meets the declared review scope. |
| `Approved with Conditions` | May proceed only under explicitly recorded conditions. |
| `Changes Requested` | Does not yet meet the scope; corrections are required. |
| `Deferred` | Decision postponed pending named evidence or authority. |
| `Rejected` | Not approved for the requested purpose. |
| `Escalated` | Requires a decision from a higher or different authority. |

The detailed review mechanics belong in `Review_Process.md`.

Workflows may define their review timing and discipline-specific checklist items.

They must preserve this common decision record.

---

# Enforcement

Enforcement protects the work; it is not punitive by default.

The first response to noncompliance is to determine whether the rule was unclear, inaccessible, impractical, or knowingly bypassed.

## Correction levels

### Level 1 — Clarify

Use when the contributor likely lacked awareness or the rule is unclear.

Provide the source standard, explain the required correction, and improve discoverability if needed.

### Level 2 — Correct before handoff

Use when the issue would confuse a reviewer, break retrieval, weaken version history, or create avoidable rework.

The artifact must be corrected before the next formal handoff or approval.

### Level 3 — Block approval

Use when the issue risks canon, continuity, quality, legal or platform obligations, release integrity, or loss of recoverability.

The artifact may not proceed until corrected or covered by an approved exception.

### Level 4 — Escalate systemic failure

Use when the same issue recurs, standards conflict, ownership is unclear, or a shared workflow cannot comply without unreasonable harm.

The relevant owners must review the system, not merely the most recent artifact.

## Non-negotiable conditions

The following always block approval unless a higher authority provides a documented exception:

* Deliberate misrepresentation of approval status or version history.
* Silent overwrite of an approved or releasable artifact without recoverable history.
* Unrecorded canon changes.
* Release of work known to violate required legal, platform, safety, or audience-trust obligations.
* Use of a superseded source when the active source is available and the difference is material.

---

# Exceptions

An exception permits a limited departure from an active standard.

It is not a shortcut for avoiding review.

An exception must be requested before the departure when practical.

If immediate action is required to prevent loss or harm, record the exception request as soon as the immediate risk is controlled.

## Required exception record

Every exception must state:

* The standard and exact rule affected.
* The artifact, episode, system, or release affected.
* The reason compliance is impractical or harmful in this case.
* The risk created by the exception.
* The mitigation or compensating control.
* The owner requesting it.
* The approver.
* The effective period or expiry point.
* The condition for returning to normal compliance.

## Exception limits

An exception is:

* Specific, not open-ended.
* Temporary unless explicitly approved as permanent.
* Traceable to a named decision.
* Reviewable at its expiry or after the affected release.
* Non-precedential unless adopted through the Standards Workflow.

Repeated exceptions are evidence that the standard, workflow, template, tooling, or ownership model needs review.

Do not normalize a repeated exception through habit.

---

# Change Management

Changes to active studio standards must be deliberate because they affect future work and interpretation of past work.

Every proposed change should include:

* The problem being solved.
* The current rule and proposed replacement.
* Affected systems, templates, assets, and records.
* Compatibility risks.
* Migration or coexistence plan.
* Required owner approvals.
* Effective date.
* How adoption will be checked.

## Compatible changes

A compatible change clarifies, repairs, or adds optional guidance without changing the interpretation of approved historic work.

Compatible changes may be adopted after normal review and communication.

## Breaking changes

A breaking change alters names, statuses, folder placement, identifiers, review records, or release evidence in a way that affects retrieval or interpretation.

Breaking changes require:

* A named migration plan.
* A transition period or clear cutover date.
* Direction for existing approved work.
* Updated templates and references.
* Verification that the change does not sever traceability.

## Emergency changes

Emergency changes may be made when delay risks legal compliance, platform safety, material loss, public harm, or irreversible continuity damage.

The Studio Owner or delegated authority may approve the minimum safe emergency change.

Record the reason, scope, decision, and follow-up review within the next practical review cycle.

Emergency action does not remove the need for documentation.

---

# Version and Record Principles

Version control is not reserved for code.

Any artifact whose change can affect quality, continuity, approval, release, reuse, or interpretation needs recoverable history.

At minimum, preserve:

* Artifact identity.
* Current version or revision marker.
* Status.
* Owner.
* Date of material change.
* Summary of material change.
* Review or approval reference when applicable.
* Relationship to replaced or dependent artifacts.

Never use an unqualified filename as the only proof of currentness.

Never delete an approved artifact solely because a newer version exists unless retention policy explicitly allows it and traceability is preserved elsewhere.

Detailed version syntax and handling belong in `Version_Control.md`.

---

# Adoption Checklist

Before treating a standard as active, confirm:

* Its purpose and scope are explicit.
* Its owner is known.
* It has been reviewed by affected owners.
* It does not conflict with higher authority.
* Required names, statuses, and records are defined or referenced.
* Existing workflows are linked rather than duplicated.
* Affected templates have been assessed.
* Affected active work has a migration or coexistence plan.
* Exceptions and escalation paths are clear.
* Its effective date and version are recorded.

Before treating an artifact as compliant, confirm:

* The applicable standard is active.
* The artifact uses the required naming and status conventions.
* Its folder placement is correct.
* Its current version and history are recoverable.
* Required review evidence exists.
* Any exception is approved, visible, and unexpired.
* It remains consistent with canon and production state.

---

# Anti-Patterns

Avoid these practices:

* Creating a private naming convention for one episode without recording it.
* Calling a draft “final” to force a handoff.
* Renaming approved assets without preserving their former identity or lineage.
* Treating an AI tool's output as proof that a canon change is acceptable.
* Copying a full workflow into a standard instead of linking to its owner.
* Making a template the only place where a required rule exists.
* Treating a retrospective lesson as binding policy before review.
* Using exceptions as permanent shadow standards.
* Leaving review feedback without a final disposition.
* Publishing a release because its files look complete while its approval evidence is missing.

---

# Maintenance Cadence

Review this governance manual:

* Before adding a new studio-wide standard.
* When a new production system, AI tool, template family, or release channel affects shared conventions.
* After a material continuity, quality, or release failure.
* When repeated exceptions or corrections show a rule is not working.
* At least once during each planned annual operating review.

Maintenance should answer:

* Does the hierarchy still match how the studio works?
* Are ownership boundaries still clear?
* Are active standards discoverable and usable?
* Are templates applying current rules?
* Are lessons being converted into improvements when warranted?
* Are repeated exceptions revealing systemic problems?
* Are quality and continuity records sufficient for future reuse?

Do not revise this manual simply to make it longer.

Revise it when a change improves clarity, accountability, continuity, or operational reliability.

---

# Final Direction

Village Stories should remain understandable even when the original creator is not present to explain a file, prompt, asset, decision, or release.

The studio standard is therefore simple:

> Build a system in which good work can be found, verified, continued, and trusted.

Every shared convention should serve that outcome.
