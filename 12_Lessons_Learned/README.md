# Lessons Learned

## Purpose

`12_Lessons_Learned/` is the permanent evidence library for what Village Stories
production actually taught after work was attempted, reviewed, released, or
reused.

It preserves observations so the studio can improve without relying on memory,
chat history, or tool session logs.

It is not a second policy library.

It is not a substitute for canon, production manuals, prompt manuals, or studio
standards.

Its purpose is to answer:

> What did this episode or production cycle reveal that future work should know?

---

# Guiding Principle

Record evidence before opinion.

Record outcomes before recommendations.

A lesson is valuable when it helps the next contributor avoid a repeated mistake
or repeat a proven success.

A lesson is not valuable when it merely restates an existing rule that was
already documented and simply ignored.

When a lesson proves a repeated shared need, route it through the standards or
canon change process.

Do not turn a one-off accident into permanent policy without review.

---

# Scope

This folder holds retrospective records from:

* Episode production.
* Prompt generation and Google Flow work.
* Image, animation, audio, and edit passes.
* Quality review and release.
* Continuity recovery.
* Reuse of assets across episodes.
* Standards friction discovered in real work.

This folder does not hold:

* Approved canon facts.
* Active production procedures.
* Master prompts.
* Templates that define required workflow.
* Formal review packets (those live with the reviewed artifact).
* Unreleased speculative ideas with no production evidence.

---

# Authority

Lessons are informative until formally adopted.

| Source | Authority |
| --- | --- |
| `01_Canon/` and approved canon decisions | Governing truth |
| Production and AI prompt manuals | Governing execution |
| `10_Studio_Standards/` | Governing shared conventions |
| `12_Lessons_Learned/` | Evidence and improvement proposals |

If a lesson conflicts with an active standard, the standard wins until changed
through the proper approval path.

If a lesson reveals a repeated gap in standards, propose a standards change.

If a lesson reveals a canon or continuity error, route through
`10_Studio_Standards/Canon_Change_Process.md`.

---

# When To Create A Lesson Record

Create or update a lesson record when:

* An episode reaches a meaningful milestone: story lock, first pass, QA, release,
  or post-release correction.
* The same defect appears twice in one episode.
* The same defect appears in two different episodes.
* A prompt pattern, tool setting, or workflow step saves measurable time or
  quality.
* A release, metadata, or packaging issue reaches the audience or nearly does.
* A continuity repair required non-obvious investigation.
* A standard was unclear, impractical, or missing in real use.
* An exception was needed and exposed a real rule problem.

Do not create a lesson record for:

* Every minor typo.
* Every rejected AI candidate unless the rejection reveals a repeatable pattern.
* Personal preference with no production evidence.
* Ideas that never reached generation, review, or release.

---

# Folder Structure

```text
12_Lessons_Learned/
├── README.md
├── Continuous_Improvement_Index.md
├── Categories/                    ← cross-episode registers (see index)
├── Episode_001.md
├── Episode_002.md
└── ...
```

### Continuous improvement layer

Use `Continuous_Improvement_Index.md` and `Categories/` for studio-wide
pattern capture (prompt failures, Flow limits, SEO, bottlenecks, etc.).

Prefer episode-owned records first.

Add a category register row only when an episode lesson (or verified release
event) supplies evidence.

Do not invent lessons to fill registers.

Optional series supplements (e.g. `Series_Prompt_Patterns.md`) may still be
created after the same lesson appears in two or more episodes.

---

# Naming Rules

Follow `10_Studio_Standards/Naming_Standards.md` and
`10_Studio_Standards/Folder_Standards.md`.

| Item | Pattern |
| --- | --- |
| Episode lesson file | `Episode_###.md` with three-digit episode number |
| Series supplement | `Series_[Topic].md` |
| Lesson entry ID inside a file | `LL-EP###-##` or `LL-SER-[TOPIC]-##` |

Examples:

```text
Episode_001.md
Episode_012.md
Series_Prompt_Patterns.md
LL-EP001-01
LL-SER-FLOW-03
```

---

# Episode Lesson File Format

Each `Episode_###.md` is one durable episode learning log.

Create it when pre-production begins or when the first material lesson appears.

Update it through production, release, and post-release correction.

Do not split one episode across multiple lesson files.

## Required file header

```text
Episode ID:
Episode title:
Format: Shorts / long form / both
Status: in production / released / corrected / archived
Lesson owner:
Last updated:
Release ID if published:
Linked review IDs:
```

## Lesson entry template

Copy this block for each distinct lesson.

```markdown
### LL-EP###-##

**Date:**
**Stage:** story / script / board / image / animation / audio / edit / thumbnail / metadata / release
**Type:** success / defect / near-miss / friction / tool / canon / continuity / packaging / reuse
**Severity:** low / medium / high / release-impacting

**What happened:**
[Factual description of the work event. No blame language.]

**Evidence:**
[File names, clip IDs, prompt revisions, review IDs, screenshots, candidate IDs,
or measurable outcome.]

**Root cause:**
[Why it happened — missing brief, weak lock, tool drift, unclear standard, etc.]

**Corrective action taken:**
[What was changed in this episode.]

**Recommendation for future episodes:**
[Specific reusable guidance.]

**Standards impact:**
none / propose standard change / propose canon change / propose prompt manual
change / propose template need

**Status:**
open / adopted in episode / promoted to series lesson / sent to standards review
/ closed-no-action
```

---

# Lesson Categories

Use the `Type` field consistently.

| Type | Use when |
| --- | --- |
| `success` | A method, prompt structure, or workflow step worked well and should be reused |
| `defect` | A material error was found and fixed or blocked |
| `near-miss` | A defect was caught before release |
| `friction` | Work was slowed by unclear ownership, naming, folder placement, or handoff |
| `tool` | Google Flow or other tool behavior affected outcome |
| `canon` | A canon or research question was exposed |
| `continuity` | Character, location, object, time, or screen geography drift |
| `packaging` | Thumbnail, title, description, or audience promise issue |
| `reuse` | Asset reuse, prompt reuse, or archive recovery lesson |

---

# Stage Guidance

### Story and script

Record:

* Premise weaknesses discovered late.
* Historical or cultural questions that blocked writing.
* Character voice drift.
* Ending or educational promise mismatches.

### Image prompts

Record:

* Gaze-direction failures.
* Style drift between character and background.
* Lock omissions that caused regeneration loops.
* Reference attachment mistakes.
* Framing notes that saved or broke Flow follow-up.

### Animation and Flow

Record:

* Source-image fidelity problems.
* One-change discipline violations.
* Camera movement contradictions.
* Identity morphing.
* Clip length and pacing mismatches.

### Audio and ASMR

Record:

* Primary sound hierarchy mistakes.
* Crossfade failures between clips.
* Narration fighting visible sound.
* Missing ambience continuity.

### Edit, packaging, release

Record:

* Caption or accessibility issues.
* Promise triangle failures.
* Live verification defects.
* Archive or manifest gaps.

---

# Relationship To Other Systems

| System | Relationship |
| --- | --- |
| `08_Production/18_Project_Checklist.md` | Checklist may prompt a lesson entry at episode close |
| `10_Studio_Standards/Quality_Score_System.md` | Repeated low dimensions may justify a lesson |
| `10_Studio_Standards/Review_Process.md` | Review packets supply evidence links |
| `10_Studio_Standards/Canon_Change_Process.md` | Canon-impacting lessons route here |
| `09_AI_Production_System/15_Common_Failures.md` | Permanent failure catalog; lessons feed updates |
| `10_Episodes/` or episode archive | Episode artifacts remain the source evidence |

A lesson points to evidence.

It does not replace the evidence file.

---

# Promotion Rules

### Keep in episode file when:

* The lesson is specific to one story, location, prop, or packaging choice.
* The issue is unlikely to generalize.

### Promote to series supplement when:

* The same lesson appears in two or more episodes.
* The lesson concerns a reusable prompt, Flow, audio, or release pattern.

### Send to standards review when:

* The lesson shows a repeated convention gap.
* Contributors keep solving the same problem privately.
* A manual is unclear enough to cause repeated defects.

### Send to canon change when:

* The lesson reveals a canon contradiction or required correction.

---

# What Good Lessons Look Like

### Good example

```markdown
### LL-EP001-03

**Date:** 2026-07-14
**Stage:** image
**Type:** defect
**Severity:** medium

**What happened:**
Clip 10 Family Dog first pass looked toward camera instead of Mother and Father.

**Evidence:**
IMG_EP001_C10_v1.0 rejected in Prompt QA; corrected in v1.2 with explicit
side-profile and gaze lines in ACTION block.

**Root cause:**
Gaze direction was implied in SUBJECT but not repeated in ACTION and NEGATIVE.

**Corrective action taken:**
Added explicit body orientation, muzzle direction, and gaze negatives.

**Recommendation for future episodes:**
For any animal or character with required off-camera eyeline, repeat gaze in
ACTION and NEGATIVE PROMPT.

**Standards impact:**
none

**Status:**
adopted in episode
```

### Weak example — do not write like this

```markdown
The dog prompt did not work. Try harder next time.
```

This is not evidence-based and cannot help future production.

---

# Episode Close Routine

At episode release or archive, add a final section to the episode lesson file:

```markdown
## Episode Close Summary

**Released version:**
**Main successes to reuse:**
**Main defects avoided late:**
**Open items for next episode:**
**Standards proposals opened:**
**Canon questions opened:**
```

If no lessons were recorded and nothing notable occurred, write:

```text
No material lessons beyond routine production.
```

That is a valid close state.

---

# Governance

The Lessons Learned Owner maintains this folder.

Contributors may add entries to the episode they worked on.

Reviewers may add entries when a gate exposes repeatable evidence.

No lesson becomes mandatory policy without approval.

No lesson should contain secrets, private credentials, or unpublished personal
data.

---

# Start Rule

Do not pre-create dozens of empty episode files.

Create `Episode_001.md` when Episode 001 production actually begins.

Let the folder grow with real work.

The value of this system is honest evidence, not folder fullness.

---

# Final Rule

If future you would need this lesson to avoid repeating the same cost, write it
down now with evidence.

If it is only a passing annoyance with no reusable lesson, skip it.

The studio improves by recording what the work actually taught.
