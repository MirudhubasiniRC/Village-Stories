# Quality Score System

## 1. Purpose

This manual defines the permanent, studio-wide scoring method for Village Stories quality gates.

It is a permanent operating standard, not a planning template.

Its purpose is to make quality decisions consistent, traceable, and comparable across episodes, roles, tools, and years.

It answers one operational question:

> How does the studio measure whether an artifact is good enough for its declared gate, and what evidence justifies that measurement?

This manual governs shared scoring dimensions, thresholds, evidence requirements, and interpretation rules.

It does not own the step-by-step review workflow for any single discipline.

It does not replace production gate timing, prompt QA procedure, or release publishing steps.

When a workflow defines when a review occurs, this manual defines how the score is calculated, what blocks approval, and what record must exist.

Quality scoring protects audience trust in an early-1990s rural Tamil Nadu animated series produced with Google Flow and related AI tools.

A high score is not permission to violate canon.

A low score on a non-blocking dimension is not permission to ignore a hard gate failure.

## 2. Guiding Principle

Score evidence, not enthusiasm.

Score the artifact against its declared gate scope, not against unrelated aspirations.

Score continuity and truth before polish.

Score usability for the next contributor, not only beauty for the current reviewer.

A generated asset is not approved because it is attractive.

An approved asset is not automatically reusable in a different gate without re-scoring.

A passing weighted score cannot override a failed hard gate.

A failed weighted score cannot be waived by informal agreement without a recorded disposition.

When uncertain, defer and gather authority.

When a hard gate fails, block and cite the governing source.

When two reviewers disagree on interpretation, escalate before averaging.

The studio prefers one honest blocked artifact over one misleading approved artifact.

## 3. Scope

This manual applies to every formal quality gate in Village Stories production.

It applies to story and premise artifacts.

It applies to script, beat sheet, and dialogue records.

It applies to storyboard, shot plan, and continuity handoff records.

It applies to image prompts, generated stills, selected source frames, and repair assets.

It applies to Google Flow animation prompts, candidate clips, trims, and selected motion assets.

It applies to rough cut, picture lock, sound lock, captions, and accessibility deliverables.

It applies to thumbnail, title, description, tags, chapters, cards, end screens, and playlist placement.

It applies to release packages, platform uploads, corrections, and post-release change requests.

It applies whether the artifact is human-authored, AI-assisted, hybrid, or tool-exported.

It applies at episode scope and at reusable-system scope when a shared artifact crosses episodes.

This manual does not define canon facts.

This manual does not define prompt construction.

This manual does not define folder placement or filename grammar.

This manual does not define the review meeting schedule.

Those responsibilities belong to their owning systems.

Cross-reference them instead of copying them here.

## 4. Boundaries

Use this manual when a reviewer must produce or interpret a quality score.

Use this manual when a gate owner must decide pass, revise, block, defer, or escalate.

Use this manual when a template or workflow needs shared threshold language.

Do not use this manual as a substitute for:

* `08_Production/14_Quality_Control.md` for production gate operation, defect logging, and release authorization workflow.
* `09_AI_Production_System/14_Prompt_QA.md` for prompt pre-generation checks, candidate inspection, and prompt-specific status labels.
* `10_Studio_Standards/Review_Process.md` for review record structure, reviewer assignment, and closure mechanics.
* `10_Studio_Standards/Release_Standards.md` for minimum release evidence and publication approval conditions.
* `10_Studio_Standards/Version_Control.md` for revision labels, supersession, and recoverable history.
* `10_Studio_Standards/Canon_Change_Process.md` for proposing, approving, and applying canon changes.

This manual supplies the shared scoring language those systems must use consistently.

If a workflow adds a discipline-specific checklist item, it must map that item to a dimension here or cite a hard gate here.

If a workflow invents a new pass threshold without standards approval, treat the threshold as non-binding until corrected.

## 5. Definitions

A quality gate is a named decision point where an artifact must meet declared requirements before downstream work may rely on it.

A hard gate is a non-negotiable requirement.

Failure of a hard gate blocks approval regardless of weighted score.

A scored dimension is a measurable quality area evaluated on a numeric scale.

A rubric is the set of dimensions, weights, descriptors, and thresholds used at one gate.

A raw score is the unweighted value assigned to one dimension.

A weighted score is the dimension score multiplied by its gate weight.

A composite score is the sum of weighted scores for all applicable dimensions at a gate.

A pass threshold is the minimum composite score required for approval when all hard gates pass.

A revision threshold is the composite score below which the artifact must return for correction rather than proceed.

A block threshold is a score or condition that prevents any forward use, often because a hard gate failed or a safety rule was breached.

Evidence is the linked, inspectable material a reviewer used to justify a score or gate result.

A score record is the permanent note of dimensions scored, values assigned, weights applied, thresholds checked, hard gates checked, disposition, and reviewer identity.

A waiver is a documented, authorized acceptance of a known defect that does not meet the usual threshold.

A waiver is not a silent compromise.

A calibration artifact is a reference example used to align reviewers on score meaning.

An edge case is a situation where the rubric alone does not clearly decide approval.

Edge cases require explicit interpretation rules or escalation.

## 6. Authority Hierarchy

When scoring, apply the highest applicable authority before assigning dimension values.

```text
Studio mission, audience promise, legal and platform obligations
↓
01_Canon/ and approved canonical decisions
↓
02_World/ · 03_Characters/ · 04_Objects/ · 05_Research/
↓
06_Story_Engine/ · 07_Episode_System/
↓
Approved episode brief, script, storyboard, scene-state ledger
↓
08_Production/ gate operation and episode records
↓
09_AI_Production_System/ prompt manuals, locks, and prompt QA
↓
10_Studio_Standards/ shared scoring, review, version, and release conventions
↓
11_Templates/ forms and starting structures
↓
12_Lessons_Learned/ retrospective evidence
↓
Working drafts, experiments, and unselected generations
```

Scoring never creates authority over canon.

Scoring never waives a hard gate unless a higher authority has issued a documented exception through the proper process.

If two sources conflict, stop scoring and escalate.

Do not average conflicting instructions into a mid-score.

Do not raise a dimension score because a lower source is more convenient.

The current approved version of a source is controlling within its level.

Superseded material may inform history but must not control a new score.

## 7. Scoring Philosophy

Village Stories quality is multi-layered.

A production-ready artifact must be:

* Correct within applicable authority.
* Continuous with adjacent approved state.
* Culturally and historically careful.
* Safe for the intended audience, including children shown in the work.
* Free of modern visual, sonic, and narrative contamination unless canon explicitly permits an exception.
* Usable by the next role without hidden assumptions.
* Traceable to source, version, owner, and review state.
* Honest about limits, conditions, and unresolved risks.

Attractiveness is a scored dimension, not the definition of quality.

Technical cleanliness is necessary but insufficient.

Story clarity is necessary but insufficient.

Canon compliance is mandatory and is checked as a hard gate before composite scoring matters.

Continuity is mandatory and is checked as a hard gate before composite scoring matters.

The scoring system exists to separate:

* What must never pass.
* What must improve before the next gate.
* What may pass with recorded conditions.
* What is strong enough to approve cleanly.

## 8. Hard Gates and Scored Dimensions

Every gate uses both mechanisms.

### 8.1 Hard gates

Hard gates are binary.

Each hard gate receives one of:

* `PASS`
* `FAIL`
* `DEFERRED` when required evidence or authority is missing

If any applicable hard gate is `FAIL`, the gate disposition cannot be `Approved`.

If any applicable hard gate is `DEFERRED`, the gate disposition should be `Deferred` or `Changes Requested` until resolved.

Hard gates are evaluated before composite score interpretation.

### 8.2 Scored dimensions

Scored dimensions produce numeric values.

They explain why an artifact is weak or strong within safe boundaries.

They guide revision priority.

They support comparison across reviewers and across time.

They do not override hard gates.

### 8.3 Interaction rule

```text
Evaluate hard gates first
↓
If any hard gate FAIL → disposition is Rejected or Changes Requested; composite score is recorded for diagnosis only
↓
If any hard gate DEFERRED → disposition is Deferred; do not treat composite score as final
↓
If all hard gates PASS → compute composite score and apply thresholds
↓
Map result to Approved, Approved with Conditions, Changes Requested, or Escalated
```

Never publish a composite score without listing hard gate results beside it.

## 9. Mandatory Hard Gates

These hard gates apply at every gate unless the gate scope explicitly excludes them.

Exclusion must be declared in the review record, not assumed.

### 9.1 Canon compliance

The artifact must not contradict an applicable approved canon source.

The artifact must not introduce a new fact that requires canon approval when none exists.

The artifact must not rely on memory, informal chat, or an unapproved generation as authority.

Failure examples:

* A character performs a task outside documented capability without cause.
* A location layout contradicts the approved geography.
* An object material or function conflicts with object canon.
* A story outcome contradicts a released or approved episode fact.
* A thumbnail implies an event that does not occur in the episode.

Pass requires cited authority for every material factual claim in scope.

### 9.2 Continuity

The artifact must preserve required state from prior approved records.

The artifact must hand off explicit state for downstream use where the gate requires it.

The artifact must not contradict neighboring shots, scenes, audio, captions, or packaging without a visible or approved cause.

Failure examples:

* Wardrobe changes without elapsed time or action.
* An object moves or changes state off-screen without cause.
* Weather, light, or season jumps without narrative bridge.
* Screen direction or geography breaks between adjacent shots.
* A caption describes a sound or speaker inconsistent with the master.

Pass requires a continuity reference or handoff record appropriate to the gate.

### 9.3 Historical and cultural safety

The artifact must respect the early-1990s rural Tamil Nadu setting and the studio's research standards.

The artifact must not treat culture as costume, punchline, spectacle, or unexplained decoration.

The artifact must not misrepresent ritual, occupation, caste, gender, religion, language use, or community life.

The artifact must not introduce humiliation, mockery, or exploitative framing of rural life.

Failure examples:

* A ritual shown without research support or story function.
* A character reduced to stereotype for visual interest.
* A prop or practice from the wrong region or period used for flavor only.
* Packaging that exoticizes hardship or work.

Pass requires research or canon support for material cultural claims.

### 9.4 Child safety

Any portrayal of children must follow series dignity and safety rules.

Children must not be placed in sexualized, cruel, terrorizing, or negligently dangerous framing.

Children must not be used to manufacture shock, pity spectacle, or moral punishment.

Work, travel, water, fire, animal, height, and tool contexts involving children require proportionate care and canon-safe portrayal.

Failure examples:

* A child in preventable peril used only for tension.
* Humiliation or fear played for thumbnail impact.
* Adult negligence played as comedy without story repair.

Pass requires explicit review of child presence and context whenever children appear or are implied.

### 9.5 No modern contamination

The artifact must not introduce modern visual, sonic, textual, or metadata signals unless canon and release records explicitly permit them.

This gate applies to image, animation, edit, sound, captions, thumbnail, and public copy.

Failure examples:

* Smartphone, LED lighting, contemporary packaging, modern vehicle, or urban signage in frame.
* Electronic music cue, notification sound, or modern traffic bed without support.
* Contemporary slang, brand, URL style, or platform-native joke in period dialogue or captions.
* A thumbnail with modern clothing, typography, or object cues.

Pass requires period-safe inspection of foreground, background, audio bed, text, and packaging.

### 9.6 Traceability and identity

The artifact must be identifiable, versioned, and linked to its declared sources.

The reviewer must be able to inspect the exact item under review.

Failure examples:

* A shot reviewed without shot ID or source revision.
* A selected asset not linked to prompt revision and candidate history.
* A release package missing the exact master identifier reviewed.

Pass requires the minimum evidence listed for the gate in Section 15.

## 10. Scoring Scale

Use a `0–5` integer scale for each dimension unless a gate record explicitly states a calibrated exception.

Do not use fractional dimension scores in routine operation.

Half-point exceptions require Quality Lead approval and a written calibration note.

### 10.1 Dimension scale meanings

| Score | Meaning |
| --- | --- |
| `0` | Missing, unusable, or actively harmful in scope |
| `1` | Severe defect; major revision required |
| `2` | Material weakness; likely fails revision threshold |
| `3` | Acceptable with notable issues; may pass only with conditions or closely monitored revision |
| `4` | Strong; minor issues only |
| `5` | Excellent within scope; no material issue found |

A score of `3` is not automatically a pass.

A score of `4` does not waive a hard gate.

A score of `5` in one dimension does not compensate for a `0` or `1` in a high-weight dimension if the composite falls below threshold.

### 10.2 Composite scale

Composite scores are numeric sums of weighted dimensions.

Composite scores are gate-specific.

Do not compare composite scores across unlike gates as if they were interchangeable.

For reporting, composite scores may be expressed as:

* Raw weighted total
* Percent of gate maximum
* Band label derived from thresholds

Preferred band labels:

| Band | Typical meaning |
| --- | --- |
| `A` | Clean approval range |
| `B` | Approval with conditions range |
| `C` | Revision required range |
| `D` | Block or reject range |

Band mapping is defined per gate in Section 12.

## 11. Thresholds

Thresholds apply only after all applicable hard gates pass.

### 11.1 Universal threshold meanings

| Threshold type | Meaning |
| --- | --- |
| Pass threshold | Minimum composite score for `Approved` when no conditions are required |
| Conditional pass threshold | Range where `Approved with Conditions` is allowed |
| Revision threshold | Composite score below which `Changes Requested` is required |
| Block threshold | Composite score or dimension floor that forces `Rejected` or stop-work even if not a hard gate breach |

### 11.2 Default universal values

Unless a gate section sets a stricter value, use:

| Control | Default value |
| --- | --- |
| Pass threshold | `≥ 85%` of gate maximum composite |
| Conditional pass range | `75%–84%` of gate maximum composite |
| Revision threshold | `< 75%` of gate maximum composite |
| Single-dimension floor | No dimension below `2` for approval; no dimension below `1` for conditional approval |
| Critical dimension floor | Story truth, continuity usability, and period safety dimensions must be `≥ 3` for any approval |

A gate may define a dimension as critical.

Critical dimension floors override a high composite score.

### 11.3 Threshold interpretation rules

If composite is in pass range but any critical dimension is below floor, disposition is `Changes Requested`.

If composite is in conditional range and all critical dimensions meet floor, disposition may be `Approved with Conditions`.

If composite is in revision range, disposition is `Changes Requested`.

If composite is in block range, disposition is `Rejected` unless the defect is purely evidence-related, in which case `Deferred` may be more accurate.

If a hard gate fails, thresholds are diagnostic only.

Record them, but do not use them to justify approval.

## 12. Gate Rubrics

Each gate uses the shared hard gates plus a weighted rubric.

Weights must sum to `100` for the gate.

Omit a dimension only when the gate scope legitimately excludes it.

Record omitted dimensions as `N/A`, not as automatic full credit.

### 12.1 Gate S — Story and premise

Typical use: premise approval before substantial production.

Aligned production reference: `08_Production/14_Quality_Control.md` Gate 0.

| Dimension | Weight | Critical | Notes |
| --- | ---: | :---: | --- |
| Canon fit and premise truth | 20 | Yes | Episode need arises from approved world facts |
| Story engine alignment | 15 | Yes | Conflict, action, emotion, ending discipline |
| Character-task believability | 10 | Yes | Right people, place, season, and capability |
| Cultural and historical plausibility | 15 | Yes | Practices, occupations, objects, and routes |
| Audience promise honesty | 10 | No | Opening hook and episode promise are truthful |
| Series tone and dignity | 10 | No | Calm, observed-life feeling preserved |
| Production feasibility | 10 | No | Scope fits format, locks, and episode system |
| Traceability and brief completeness | 10 | No | IDs, sources, owners, and open facts visible |

| Band | Percent of max | Disposition guidance |
| --- | ---: | --- |
| A | 85–100 | Approved |
| B | 75–84 | Approved with Conditions or Changes Requested depending on critical dimensions |
| C | 60–74 | Changes Requested |
| D | 0–59 | Rejected or Escalated if canon conflict is unresolved |

Minimum evidence:

* Episode ID and premise revision
* Cited canon and research sources
* Story engine and episode system references used
* Open facts list with owners
* Reviewer, date, and disposition

### 12.2 Gate SC — Script and board

Typical use: locked plan before image generation.

Aligned production reference: `08_Production/14_Quality_Control.md` Gate 1.

| Dimension | Weight | Critical | Notes |
| --- | ---: | :---: | --- |
| Story clarity and scene function | 15 | Yes | Every scene earns its place |
| Cause-before-response discipline | 10 | Yes | Action logic readable on board |
| Continuity handoff completeness | 15 | Yes | Character, object, location, time, sound state |
| Dialogue discipline | 10 | No | Speech reveals only what action cannot |
| Emotional proportion | 10 | Yes | Turn is earned, ending gives rest |
| Visual storytelling readiness | 10 | No | Shots support series camera language |
| Sound-source planning | 10 | No | Planned sounds have visible purpose |
| Board usability for generation | 10 | No | Shot purpose, action, camera, and bridge are clear |
| Traceability | 10 | No | IDs, revisions, and source links present |

| Band | Percent of max | Disposition guidance |
| --- | ---: | --- |
| A | 85–100 | Approved for generation handoff |
| B | 75–84 | Approved with Conditions only if no continuity field is missing |
| C | 60–74 | Changes Requested |
| D | 0–59 | Rejected |

Minimum evidence:

* Approved brief revision
* Script or beat sheet revision
* Board revision with shot IDs
* Continuity handoff fields populated
* Neighbor-shot bridge notes where required

### 12.3 Gate I — Image and still asset

Typical use: approved still before edit or animation source selection.

Aligned prompt reference: `09_AI_Production_System/14_Prompt_QA.md`.

| Dimension | Weight | Critical | Notes |
| --- | ---: | :---: | --- |
| Identity lock fidelity | 20 | Yes | Character, location, object, style locks honored |
| Continuity fidelity | 15 | Yes | Matches board and neighbor state |
| Period and cultural safety | 15 | Yes | No modern contamination or shallow culture use |
| Composition and camera obedience | 10 | Yes | Matches approved direction and movement rules |
| Story truth in frame | 10 | Yes | Frame supports shot purpose without inventing facts |
| Technical usability | 10 | No | Resolution, crop safety, clean edges, edit suitability |
| Aesthetic quality | 10 | No | Attractive within series look; not spectacle-only |
| Prompt and asset traceability | 10 | No | Prompt revision, references, candidate lineage |

| Band | Percent of max | Disposition guidance |
| --- | ---: | --- |
| A | 88–100 | Approved |
| B | 78–87 | Approved with Conditions for minor trim, crop, or repair |
| C | 65–77 | Regenerate or Changes Requested |
| D | 0–64 | Rejected |

Image gate stricter pass default: `88%` because stills anchor downstream motion.

Minimum evidence:

* Shot ID and board revision
* Prompt revision and classification of prompt instructions
* Reference attachments and roles
* Candidate history and selected candidate ID
* Prompt QA status cross-reference
* Reviewer notes on checked lock sources

### 12.4 Gate A — Animation and motion asset

Typical use: Google Flow candidate before edit inclusion.

Aligned prompt reference: `09_AI_Production_System/14_Prompt_QA.md`.

Aligned production reference: `08_Production/14_Quality_Control.md` Gate 2 motion checks.

| Dimension | Weight | Critical | Notes |
| --- | ---: | :---: | --- |
| Source-image fidelity | 15 | Yes | Motion does not drift identity from approved source |
| Permitted motion discipline | 15 | Yes | Only approved motion change occurs |
| Continuity bridge integrity | 15 | Yes | Start and end states bridge neighbors |
| Period and contamination safety | 10 | Yes | No modern artifact introduced during motion |
| Camera movement obedience | 10 | Yes | Movement bible and lock rules honored |
| Physical plausibility | 10 | No | Weight, contact, weather, and object behavior |
| Edit usability | 10 | No | Trim viability, stability, artifact tolerance |
| Aesthetic motion quality | 5 | No | Calm, observed motion rather than spectacle |
| Traceability | 10 | No | Source frame IDs, prompt revision, clip ID, trim notes |

| Band | Percent of max | Disposition guidance |
| --- | ---: | --- |
| A | 86–100 | Approved |
| B | 76–85 | Approved with Trim or Approved with Conditions |
| C | 64–75 | Regenerate or Changes Requested |
| D | 0–63 | Rejected |

Minimum evidence:

* Approved source image ID and revision
* Flow prompt revision
* Candidate clip ID and review copy
* Documented trim in/out if trim disposition is used
* Neighbor shot references

### 12.5 Gate E — Edit, picture, and assembly

Typical use: rough cut and picture lock.

Aligned production reference: `08_Production/14_Quality_Control.md` Gates 3 and 4.

| Dimension | Weight | Critical | Notes |
| --- | ---: | :---: | --- |
| Story comprehension | 15 | Yes | Viewer understands need, action, and result |
| Pacing and emotional rhythm | 10 | No | Room for work, weather, sound, recognition |
| Continuity across cuts | 20 | Yes | Matrix fields remain coherent |
| Character behavior truth | 10 | Yes | Personality and relationship consistency |
| Period and visual safety | 10 | Yes | No modern grading or contamination through edit choices |
| Technical picture quality | 10 | No | Flicker, anatomy, artifact, text, reflection control |
| Opening and ending integrity | 10 | Yes | True hook and restful ending preserved |
| Traceability | 15 | No | Version ID, defect log, changed-shot record |

| Band | Percent of max | Disposition guidance |
| --- | ---: | --- |
| A | 85–100 | Approved |
| B | 75–84 | Approved with Conditions for logged minor defects |
| C | 60–74 | Changes Requested |
| D | 0–59 | Rejected |

Minimum evidence:

* Cut version identifier
* Continuity matrix or equivalent scene-state record
* Timestamped defect log
* List of approved asset revisions used in cut

### 12.6 Gate AU — Audio, music, and accessibility

Typical use: sound lock and caption approval.

Aligned production reference: `08_Production/14_Quality_Control.md` Gate 5.

| Dimension | Weight | Critical | Notes |
| --- | ---: | :---: | --- |
| Dialogue intelligibility and truth | 15 | Yes | Right speaker, moment, and language choice |
| Foreground sound source truth | 15 | Yes | Sounds match visible action and distance |
| Ambience and room truth | 10 | Yes | Location, weather, and time remain coherent |
| Period-safe sonic palette | 15 | Yes | No modern electronic or urban contamination |
| Music discipline | 10 | No | Supports without forcing emotion or spectacle |
| Silence and ASMR discipline | 5 | No | Calm support, not performance of rural life |
| Caption accuracy and accessibility | 20 | Yes | Timing, readability, essential sound context |
| Traceability | 10 | No | Mix version, rights notes, caption file revision |

| Band | Percent of max | Disposition guidance |
| --- | ---: | --- |
| A | 88–100 | Approved |
| B | 78–87 | Approved with Conditions for minor mix note |
| C | 65–77 | Changes Requested |
| D | 0–64 | Rejected |

Caption failures in story-meaning or safety usually trigger hard gate review, not only low dimension score.

### 12.7 Gate P — Thumbnail and packaging

Typical use: public promise alignment before release scheduling.

Aligned production reference: `08_Production/14_Quality_Control.md` Gate 6.

| Dimension | Weight | Critical | Notes |
| --- | ---: | :---: | --- |
| Factual promise alignment | 20 | Yes | Thumbnail, title, opening agree |
| Period and cultural safety | 15 | Yes | No modern or exploitative packaging |
| Series dignity and child safety | 15 | Yes | No fear, pity, or danger spectacle packaging |
| Readability and platform legibility | 10 | No | Works at small size and in feed context |
| Emotional honesty | 10 | Yes | Uses actual attention, care, uncertainty, or relief |
| Brand and channel consistency | 10 | No | Recognizably Village Stories without over-branding |
| Metadata truth | 10 | Yes | Description, tags, chapters do not overclaim |
| Traceability | 10 | No | Linked episode version and approval references |

| Band | Percent of max | Disposition guidance |
| --- | ---: | --- |
| A | 90–100 | Approved |
| B | 80–89 | Approved with Conditions only for minor copy tweak |
| C | 68–79 | Changes Requested |
| D | 0–67 | Rejected |

Packaging has the strictest default pass threshold because it shapes audience trust before viewing.

### 12.8 Gate R — Release readiness

Typical use: final authorization before publish or schedule.

Aligned production reference: `08_Production/14_Quality_Control.md` Gate 7.

Aligned studio reference: `10_Studio_Standards/Release_Standards.md`.

| Dimension | Weight | Critical | Notes |
| --- | ---: | :---: | --- |
| Gate closure integrity | 20 | Yes | Required upstream gates closed with records |
| Master and asset identity correctness | 15 | Yes | Exact reviewed master and thumbnail selected |
| Legal, rights, and platform compliance | 15 | Yes | Required disclosures and restrictions complete |
| Accessibility completeness | 10 | Yes | Captions and essential accessibility checks done |
| Metadata and destination correctness | 10 | Yes | Title, visibility, playlist, cards, end screens |
| Transcode and playback verification | 10 | No | Start, middle, end verified on platform |
| Version and archive completeness | 10 | No | Release package recoverable and linked |
| Post-release correction readiness | 10 | No | Known limitations and correction path documented |

| Band | Percent of max | Disposition guidance |
| --- | ---: | --- |
| A | 92–100 | Approved for publish or schedule |
| B | 85–91 | Approved with Conditions only for non-public timing or monitoring note |
| C | 70–84 | Changes Requested |
| D | 0–69 | Rejected |

Release readiness is not a creative rewrite gate.

If creative defects remain, send the work back to the owning creative gate rather than compensating here.

## 13. Decision Labels

Use only these dispositions in score-linked review records.

These meanings align with `10_Studio_Standards/README.md`.

| Disposition | Meaning | Typical score context |
| --- | --- | --- |
| `Approved` | Meets declared gate scope; all hard gates pass; composite at or above pass threshold; critical dimension floors met | Band A, or strong B with no required conditions |
| `Approved with Conditions` | May proceed only under recorded conditions, owner, and expiry or review point | Band B within conditional range, or Band A with a non-blocking condition |
| `Changes Requested` | Does not yet meet scope; corrections required before approval | Revision threshold, failed critical floor, or fixable hard-gate evidence gap |
| `Deferred` | Decision postponed pending named evidence, authority, or dependency | Missing source, unresolved canon question, or incomplete review package |
| `Rejected` | Not approved for the requested purpose | Hard gate fail, block threshold, or unfixable unsuitable artifact |
| `Escalated` | Requires decision from higher or different authority | Canon conflict, safety uncertainty, ownership dispute, or repeated scorer disagreement |

Do not use informal substitutes such as:

* “Good enough”
* “Looks close”
* “We can hide it”
* “Final for now”
* “Approved-ish”

Prompt QA may use prompt-native statuses such as `REGENERATE` or `RETURN TO OWNER` during generation workflow.

When a prompt QA result feeds a scored gate, map it into this disposition set in the gate score record.

Suggested mapping:

| Prompt QA status | Gate disposition mapping |
| --- | --- |
| `APPROVED` | Eligible for `Approved` after gate rubric scoring |
| `APPROVED WITH TRIM` | Usually `Approved with Conditions` at Gate A |
| `REGENERATE` | `Changes Requested` |
| `RETURN TO OWNER` | `Changes Requested` or `Escalated` depending on owner |
| `REJECT` | `Rejected` |
| `HOLD FOR CANON OR RESEARCH` | `Deferred` or `Escalated` |
| `HOLD FOR BOARD` | `Changes Requested` at Gate SC or `Deferred` at Gate I/A |

## 14. Reviewer Roles and Scoring Authority

Roles may be held by one person in a small studio.

Scoring authority remains distinct even when the person is the same.

### 14.1 Role matrix

| Role | May score | May finalize disposition | Hard gate authority |
| --- | --- | --- | --- |
| Studio Owner | All gates | Yes, especially Escalated outcomes | Can approve documented exceptions only |
| Quality Lead | All gates | Yes | Yes, with cited authority |
| Canon Reviewer | S, SC, I, A, E, P | No final alone on canon conflict | Canon compliance |
| Story Reviewer | S, SC, E, P | No final alone | Story truth and promise honesty |
| Continuity Reviewer | SC, I, A, E | No final alone | Continuity |
| Cultural Research Reviewer | S, SC, I, A, P | No final alone | Historical and cultural safety |
| Child Safety Reviewer | S, SC, I, A, E, P | No final alone | Child safety |
| AI Prompt Reviewer | I, A | No final alone | Prompt traceability and lock fidelity input |
| Picture Reviewer | I, A, E | No final alone | Visual usability and contamination |
| Sound Reviewer | AU | No final alone | Audio truth and accessibility |
| Packaging Reviewer | P | No final alone | Public promise alignment |
| Release Reviewer | R | No final alone | Release readiness |
| Publisher | R | Co-sign only with Release Reviewer or Quality Lead | Platform identity correctness |

### 14.2 Separation rules

A contributor may score dimensions for transparency.

A contributor must not be the sole final approver of their own unresolved defect.

A reviewer may score only dimensions within their competence.

A reviewer who lacks competence for a dimension must mark it `Deferred` and assign a qualified reviewer.

Final disposition requires a named approver with finalize authority for that gate.

Hard gate failures in canon, child safety, or cultural safety require the relevant specialist reviewer to be cited in the record.

### 14.3 Multi-reviewer aggregation

When two qualified reviewers score the same dimension independently:

* If scores differ by `0` or `1`, use the lower score unless a written reconciliation explains the higher score with evidence.
* If scores differ by `2` or more, mark the dimension `DISPUTED`, pause approval, and convene reconciliation or escalate.
* Do not average disputed scores into approval.

For hard gates, any qualified reviewer `FAIL` must be treated as `FAIL` until overturned by higher authority with evidence.

## 15. Evidence Requirements by Gate

Evidence is part of the score.

Missing evidence is not a low score; it is a reason to `Defer`.

### 15.1 Universal evidence block

Every score record should include:

```text
Artifact ID:
Artifact type:
Gate ID:
Declared scope:
Version or revision reviewed:
Reviewer(s):
Review date:
Applicable authority list:
Hard gate results:
Dimension scores and weights:
Composite score and band:
Disposition:
Blocking issues:
Conditions, owners, and review points:
Linked review record ID:
```

### 15.2 Gate-specific required evidence

| Gate | Required evidence minimum |
| --- | --- |
| S | Premise doc, canon citations, research citations, open-facts list |
| SC | Brief, script or beats, board, continuity handoff |
| I | Shot ID, board revision, prompt revision, references, candidate lineage, QA status |
| A | Source image ID, Flow prompt revision, clip ID, trim record, neighbor references |
| E | Cut version, continuity matrix, defect log, asset manifest |
| AU | Mix version, caption file, rights notes, sound plan cross-check |
| P | Thumbnail file ID, title, description, chapter plan, opening reference |
| R | Upstream gate closures, exact master IDs, platform upload ID, publish checklist |

### 15.3 Evidence quality rules

Evidence must be inspectable by another contributor.

Evidence must point to a specific revision, not a folder habit.

Evidence must distinguish source, candidate, and selected states.

Evidence must not rely on memory or chat screenshots alone.

Evidence must remain linked after rename or migration through version-control rules in `10_Studio_Standards/Version_Control.md`.

If evidence is missing, set disposition to `Deferred` and name the owner and required item.

Do not assign Band A without evidence sufficient for another reviewer to reproduce the conclusion.

## 16. Score Record Format

Use one score record per gate review event.

Do not silently overwrite a prior score record.

Create a new record when the artifact revision changes materially.

### 16.1 Recommended record skeleton

```text
Gate Review Record

Artifact:
Gate:
Revision reviewed:
Reviewer:
Date:

Hard Gates
- Canon compliance: PASS / FAIL / DEFERRED — notes:
- Continuity: PASS / FAIL / DEFERRED — notes:
- Historical and cultural safety: PASS / FAIL / DEFERRED — notes:
- Child safety: PASS / FAIL / DEFERRED — notes:
- No modern contamination: PASS / FAIL / DEFERRED — notes:
- Traceability and identity: PASS / FAIL / DEFERRED — notes:

Dimension Scores
- [Dimension name] — score — weight — weighted — notes

Composite
- Total:
- Percent of max:
- Band:

Disposition:
Conditions:
Required corrections:
Owners:
Escalation target if any:

Evidence links:
Related review record:
Prior score record superseded:
```

### 16.2 Version relationship

Score records are governed artifacts.

They must follow `10_Studio_Standards/Version_Control.md`.

A score record does not change the artifact revision.

It documents the review of a specific artifact revision.

When an artifact is revised, prior score records remain historically valid for the revision they reviewed.

Do not delete rejected score history merely because it is inconvenient.

## 17. Relationship to Version Control

Version control preserves identity, status, and recoverable history.

Quality scoring preserves the evaluative meaning of a specific revision.

Use them together as follows:

* No artifact may receive operational approval without a visible revision marker.
* Every score record must name the exact revision reviewed.
* A newer revision does not inherit approval from an older score.
* A superseded revision retains its score history for audit.
* A release tag or immutable package must point to score records that closed required gates.
* If version history cannot prove which item was reviewed, the traceability hard gate fails.

Do not use filename tokens like `final` or `latest` as a substitute for version identity.

Do not treat a Git commit as proof of quality approval unless the commit explicitly links a completed score record.

For generated assets, preserve candidate lineage so a score can be traced to the exact prompt and source frame set.

Detailed version syntax belongs in `10_Studio_Standards/Version_Control.md`.

## 18. Relationship to Canon Change Process

Canon changes are exceptions to preservation.

Quality scoring assumes current approved canon unless a change record says otherwise.

Rules:

* A score must not approve a canon contradiction because a change “is planned.”
* A planned canon change requires `Deferred` or `Escalated` until approved.
* An approved canon change requires re-scoring of affected artifacts before reuse or release.
* A score record must cite the canon revision used.
* If scoring reveals a canon error, open a canon proposal rather than normalizing the error through a low bar.

When a canon change is in migration, mark affected artifacts `Conditional` and list the migration dependency.

Do not release public-facing artifacts that still display superseded canon unless `Release_Standards.md` and the change record explicitly permit staged correction.

Detailed canon workflow belongs in `10_Studio_Standards/Canon_Change_Process.md`.

## 19. Relationship to Review Process

The review process defines how reviews are requested, assigned, conducted, and closed.

This manual defines what is measured and how measurements decide disposition.

Division of labor:

* `Review_Process.md` owns review timing, assignment, escalation route, and closure checklist.
* `Quality_Score_System.md` owns rubrics, thresholds, hard gates, and score interpretation.
* `README.md` owns shared disposition vocabulary.

Every formal review that affects approval must produce:

* A review record per `Review_Process.md`
* A score record per this manual when the artifact passes through a scored gate

A review comment without dimension or gate structure is supplementary, not sufficient alone.

Blocking issues in the review record must map to a failed hard gate, a failed critical dimension floor, or a below-revision composite score.

Closure requires unresolved blocking issues to be absent or covered by an approved condition with owner and review point.

## 20. Relationship to Release Standards

Release standards define the minimum shared evidence and approval conditions for public publication.

Release readiness scoring does not replace those conditions.

It expresses how completely the release package satisfies them.

Rules:

* Gate R may not be `Approved` if a required release evidence item listed in `Release_Standards.md` is missing.
* A high Gate R composite does not waive missing legal, rights, or accessibility evidence.
* A release exception requires documented approval, not a verbal pass.
* Post-release corrections require a new score record if the published artifact changes materially.

If Release Standards and this manual diverge, treat Release Standards as controlling for publication and revise this manual through the standards workflow.

## 21. Google Flow Scoring Notes

Google Flow introduces motion risk on top of still-image risk.

Apply these studio-specific rules in Gates I and A.

### 21.1 Source-first rule

The approved still is the primary authority for identity in motion.

Motion that improves aesthetics while breaking identity is not a trade worth scoring highly.

Score source-image fidelity before aesthetic motion quality.

### 21.2 One-change discipline

A Flow clip should execute the one permitted motion change declared in the prompt and board.

Extraneous motion is a defect in permitted motion discipline even if attractive.

Extraneous background drift may also fail continuity or contamination hard gates.

### 21.3 Start and end state rule

Score continuity bridge integrity by comparing:

* Approved source frame
* First usable frame of candidate motion
* Last usable frame before trim
* Required neighbor shot state

A bridge failure is a critical weakness even when mid-clip motion looks good.

### 21.4 Trim disposition interaction

`Approved with Trim` is a conditions-style outcome.

The score record must include:

* Exact in and out frames or timecodes
* What defect the trim removes
* Confirmation that retained frames still pass hard gates
* Whether the trim affects sound, caption, or continuity records

Do not use trim to hide a hard gate failure.

### 21.5 Tool session evidence

A Flow session history is helpful but insufficient alone.

The score record must still identify:

* Prompt revision
* Source image revision
* Candidate clip ID
* Selected status
* Export copy used in review

### 21.6 Regeneration scoring

When a candidate is regenerated, create a new score event.

Do not average old and new candidate scores.

Prior rejected candidates may be retained as evidence but must not be treated as selected.

### 21.7 Common Flow scoring errors

| Error | Correct handling |
| --- | --- |
| Rewarding cinematic motion with no story role | Lower story truth and camera obedience dimensions |
| Ignoring hair or clothing drift across seconds | Fail identity or continuity hard gate if material |
| Accepting a clip because only one frame is usable | Low edit usability; likely `Changes Requested` |
| Treating prompt QA approval as final gate approval | Prompt QA is necessary input, not final Gate A disposition |
| Hiding contamination with blur or speed | Fail contamination hard gate if visible or likely visible |

Detailed prompt inspection belongs in `09_AI_Production_System/14_Prompt_QA.md`.

## 22. YouTube and Packaging Scoring Notes

Public packaging is part of quality, not marketing separate from quality.

### 22.1 Promise triangle

Score packaging against the promise triangle:

* Thumbnail
* Title and short public copy
* Opening of the episode

A high score in one corner cannot rescue a lie in another corner.

Misalignment is usually a failed factual promise hard gate.

### 22.2 Small-size readability

A thumbnail may be period-safe and still fail packaging if unreadable in mobile feed context.

Readability is scored, but emotional dishonesty is a hard gate issue.

### 22.3 Metadata overclaim

Tags and description must not claim scenes, themes, or facts absent from the episode.

Overclaim lowers metadata truth and may fail promise honesty.

### 22.4 Chapters and captions

Chapter titles are public copy and must be scored for truth and period-safe language.

Captions are scored in Gate AU but release readiness must confirm the exact caption file tied to the master.

### 22.5 Cards and end screens

Irrelevant destinations lower destination correctness.

A truthful episode may still fail Gate R if cards promise a different kind of video.

### 22.6 Post-publish changes

If thumbnail, title, description, or captions change after release, run an updated Gate P or Gate R score as appropriate.

Do not assume the original release score covers a new public promise.

## 23. Worked Example A — Story premise

Artifact:

* Episode `VS-S02E04` premise revision `r03`

Reviewers:

* Story Reviewer
* Canon Reviewer
* Cultural Research Reviewer

Hard gates:

* Canon compliance: PASS
* Continuity: PASS at premise scope
* Historical and cultural safety: PASS
* Child safety: PASS — child present near well route; task proportionate and supervised in premise
* No modern contamination: PASS
* Traceability: PASS

Dimension sample:

| Dimension | Score | Weight | Weighted |
| --- | ---: | ---: | ---: |
| Canon fit and premise truth | 5 | 20 | 100 |
| Story engine alignment | 4 | 15 | 60 |
| Character-task believability | 4 | 10 | 40 |
| Cultural and historical plausibility | 4 | 15 | 60 |
| Audience promise honesty | 4 | 10 | 40 |
| Series tone and dignity | 5 | 10 | 50 |
| Production feasibility | 3 | 10 | 30 |
| Traceability and brief completeness | 4 | 10 | 40 |

Composite:

* Total weighted: `420`
* Max: `500`
* Percent: `84%`
* Band: `B`

Interpretation:

* Composite is in conditional range.
* No critical dimension below `3`.
* Production feasibility is weak because rain route complexity may exceed episode format.

Disposition:

* `Approved with Conditions`

Conditions:

* Production Owner confirms rain route shot count within format limit before Gate SC lock.
* Open fact on elder’s tool ownership confirmed with object canon by Canon Reviewer.

This example shows Band B becoming conditional approval, not automatic rejection.

## 24. Worked Example B — Google Flow clip

Artifact:

* Shot `VS-S02E04-SH014` Flow candidate `c07` from source image `IMG-014 r02`

Hard gates:

* Canon compliance: PASS
* Continuity: PASS
* Historical and cultural safety: PASS
* Child safety: N/A
* No modern contamination: FAIL — distant background shape reads as modern utility pole on review copy
* Traceability: PASS

Interpretation:

* Hard gate failure blocks approval regardless of motion quality.
* Record composite only for diagnosis.

Disposition:

* `Rejected`

Required action:

* Regenerate with stricter background negative and location lock reference.

* Re-run Gate A only after new candidate and contamination re-check.

Do not approve with crop if the pole remains plausible in adjacent frames or neighbor shots.

## 25. Worked Example C — Release readiness

Artifact:

* Episode master `VS-S02E04-MST r05`
* Thumbnail `VS-S02E04-THB r02`
* YouTube upload draft `YT-DRAFT-8821`

Upstream closures:

* Gates S, SC, I, A, E, AU, P all approved with records linked
* One Gate E condition closed: mud splash continuity note verified

Hard gates:

* All pass

Dimension sample:

| Dimension | Score | Weight | Weighted |
| --- | ---: | ---: | ---: |
| Gate closure integrity | 5 | 20 | 100 |
| Master and asset identity correctness | 5 | 15 | 75 |
| Legal, rights, and platform compliance | 4 | 15 | 60 |
| Accessibility completeness | 5 | 10 | 50 |
| Metadata and destination correctness | 4 | 10 | 40 |
| Transcode and playback verification | 3 | 10 | 30 |
| Version and archive completeness | 4 | 10 | 40 |
| Post-release correction readiness | 4 | 10 | 40 |

Composite:

* Percent: `87%`
* Band: `B`

Disposition:

* `Approved with Conditions`

Condition:

* Publisher re-checks middle chapter marker on platform transcode after upload processing completes.

Rationale:

* Gate R allows conditional pass when creative gates are closed and only platform verification remains.

## 26. Edge Cases and Interpretation Rules

### 26.1 Attractive but wrong

If an asset is aesthetically strong but factually wrong, disposition is `Rejected` or `Changes Requested`, not conditional approval.

Do not use Band B to tolerate a canon or contamination failure.

### 26.2 Minor defect pile-up

Several score-4 dimensions and one score-2 dimension may still fail if:

* The composite drops below revision threshold, or
* The low dimension is critical, or
* The low dimension represents a repeated defect class across shots

Quality Lead may require systemic correction rather than shot-by-shot waivers.

### 26.3 Background-only contamination

If contamination is tiny but identifiable and period-breaking, hard gate fails.

If contamination is ambiguous, mark contamination `DEFERRED`, gather frame enlargement or specialist review, and do not approve.

### 26.4 Child not on screen but implied

Child safety hard gate still applies when packaging, dialogue, or sound implies child peril or humiliation.

### 26.5 Research gap

If cultural or historical truth cannot be supported, historical and cultural safety is `DEFERRED` or `FAIL`.

Do not score plausibility generously to move production.

### 26.6 Missing board field

Missing continuity handoff is a continuity failure at Gates SC, I, A, and E.

At Gate S, continuity may be `PASS` with limited scope if no downstream handoff is yet required.

### 26.7 Prompt QA approved, gate failed

Prompt QA approval means the prompt and candidate passed prompt-native checks.

Gate I or A may still fail on edit usability, neighbor bridge, or packaging relevance.

Treat Prompt QA as upstream evidence, not final disposition.

### 26.8 Emergency release correction

If a released item needs urgent correction for safety or legal reasons, use emergency change rules.

A post-release correction still needs a score record for the corrected public artifact.

Do not silently replace a public asset without release evidence.

### 26.9 Repeated waivers

If the same dimension is waived repeatedly across episodes, escalate as systemic process failure.

A waiver is episode-specific unless adopted through standards change.

### 26.10 Solo reviewer studio

When one person holds all roles, still produce separate hard gate and dimension notes.

The record must show which hats were worn.

Future contributors deserve the same interpretability as a multi-person studio.

## 27. Waivers and Conditional Approval

A waiver accepts a known defect.

A condition requires a named action, owner, or review point before or after proceed.

### 27.1 Waiver requirements

Every waiver must state:

* Gate and dimension affected
* Exact defect
* Why fix is impractical before next step
* Viewer or continuity impact
* Approver
* Whether future reuse is prohibited
* Expiry or review point

### 27.2 What waivers may not do

Waivers may not:

* Approve a hard gate failure except through higher authority exception
* Approve child safety failure
* Approve intentional canon contradiction
* Approve deceptive packaging
* Approve missing release evidence

### 27.3 Conditional approval requirements

Every condition must state:

* The condition text
* Responsible owner
* Evidence required to clear it
* Whether downstream work may begin before clearance
* Review point or expiry

If downstream work may not begin, disposition is more accurately `Changes Requested` than `Approved with Conditions`.

## 28. Calibration and Reviewer Alignment

Scores drift when reviewers improvise personal standards.

Use calibration to keep scores meaningful.

### 28.1 Calibration set

Maintain a small internal set of reference artifacts:

* One clean Band A example per major gate
* One borderline Band B example
* One clear Rejected hard gate example
* One Flow contamination example
* One packaging misalignment example

Calibration artifacts are not public release assets unless approved for that use.

### 28.2 Calibration cadence

Calibrate:

* Before a new season production block
* After a tool change in Google Flow or prompt architecture
* After any standards change to thresholds or weights
* After a significant scoring disagreement
* At least once per operating year

### 28.3 Drift signals

Investigate drift when:

* The same artifact type always scores A without defects found later in edit
* Gate I scores are high but Gate E continuity defects are frequent
* Packaging scores are high but audience comments show promise mismatch
* Prompt QA rejections rise while gate scores remain high

Drift response belongs in lessons learned and may justify a standards revision.

## 29. Checklists

### 29.1 Reviewer pre-score checklist

* I know the artifact ID and revision.
* I know the gate scope.
* I loaded the applicable authority list.
* I confirmed hard gates before scoring dimensions.
* I marked dimensions outside my competence as `Deferred`.
* I can cite evidence for every score of `3` or below.
* I can cite evidence for every score of `5` on a critical dimension.
* I will not approve my own unresolved defect without another qualified review when available.

### 29.2 Quality Lead gate closure checklist

* All required reviewers cited.
* All hard gates explicitly recorded.
* Composite and band calculated correctly.
* Critical dimension floors checked.
* Disposition matches thresholds and hard gate outcomes.
* Conditions have owner and review point.
* Evidence links resolve.
* Score record versioned and linked to review record.
* Superseded score record identified if applicable.

### 29.3 Producer handoff checklist

* I know which gate the next role requires.
* I am handing off the approved revision, not a nearby draft.
* I included continuity handoff fields if required.
* I included known open risks and conditions.
* I did not relabel a draft as approved to speed handoff.

## 30. Anti-Patterns

Avoid these scoring failures:

* Scoring before loading sources.
* Giving high aesthetic scores to wrong facts.
* Treating prompt beauty as canon evidence.
* Using composite score to override a failed hard gate.
* Omitting hard gate section because composite is high.
* Averaging disputed scores without reconciliation.
* Deleting rejected score records.
* Calling a draft “approved” without a score record.
* Approving packaging without watching the opening.
* Approving release without exact master identity check.
* Using waivers to avoid systemic correction.
* Creating private rubric variants per episode without standards approval.

## 31. Enforcement

Scoring enforcement protects the audience and the archive.

### 31.1 Level 1 — Clarify

Use when a contributor did not know a score record was required.

Provide the gate rubric and template.

### 31.2 Level 2 — Correct before handoff

Use when a score is missing, incomplete, or attached to the wrong revision.

No downstream gate may rely on the artifact until corrected.

### 31.3 Level 3 — Block approval

Use when a hard gate failed, a deceptive packaging score was attempted, or release evidence is missing.

### 31.4 Level 4 — Escalate systemic failure

Use when scores consistently diverge from later defects, thresholds are routinely waived, or workflows cannot comply without shadow rubrics.

## 32. Change Management for This Manual

Changes to weights, thresholds, or hard gate definitions are breaking changes for comparability.

Every proposed change should include:

* Problem being solved
* Affected gates and workflows
* Whether historic score records remain valid for audit only
* Calibration updates required
* Template and workflow references to update
* Effective date

Compatible changes clarify wording without altering numeric meaning.

Breaking changes require:

* Named effective date
* Calibration session
* Update to affected templates
* Communication to all reviewers

Emergency changes may occur when a safety or release failure reveals a scoring blind spot.

Record the emergency change and schedule normal review promptly.

## 33. Adoption Checklist

Before using this manual as active:

* Gate list and rubric weights are understood by reviewers.
* Disposition labels match `README.md`.
* Review records in `Review_Process.md` can link to score records.
* Version control can identify reviewed revisions.
* Prompt QA and production QC documents cross-reference this manual.
* Templates include hard gate block and dimension table space.
* Calibration examples exist or are scheduled.
* Release Standards evidence list is compatible with Gate R.

Before treating a score as valid:

* Artifact revision matches record.
* Reviewer authority matches gate.
* Hard gates explicitly listed.
* Composite math verified.
* Disposition consistent with thresholds.
* Evidence links live.
* Conditions owned and dated.

## 34. Maintenance Cadence

Review this manual:

* Before each new production season or major batch of episodes
* After a tool change affecting Google Flow or prompt locks
* After a material quality or release failure
* After repeated scorer disagreement or waiver use
* During annual studio standards review

Maintenance questions:

* Do weights still predict downstream defects?
* Are hard gates catching the failures that matter most?
* Are thresholds too lenient or too punitive?
* Do reviewers need new calibration examples?
* Are workflows citing this manual instead of duplicating it?

Do not change weights casually because one episode scored low.

Change the rubric when evidence shows repeated misalignment with real outcomes.

## 35. Quick Reference Tables

### 35.1 Hard gates at a glance

| Hard gate | Question |
| --- | --- |
| Canon compliance | Does every material fact match authority? |
| Continuity | Does state carry correctly and hand off cleanly? |
| Historical and cultural safety | Is portrayal researched, dignified, and period-fit? |
| Child safety | Are children free from exploitative or negligent framing? |
| No modern contamination | Are visual, sonic, and textual cues period-safe? |
| Traceability and identity | Can another reviewer find and verify the exact item? |

### 35.2 Gate IDs at a glance

| Gate ID | Artifact family |
| --- | --- |
| S | Story and premise |
| SC | Script and board |
| I | Image and still |
| A | Animation and motion |
| E | Edit and picture |
| AU | Audio and accessibility |
| P | Thumbnail and packaging |
| R | Release readiness |

### 35.3 Default thresholds at a glance

| Control | Default |
| --- | --- |
| Dimension scale | 0–5 integers |
| Pass | ≥ 85% of gate max |
| Conditional | 75%–84% |
| Revision | < 75% |
| Critical dimension minimum for approval | ≥ 3 |
| Hard gate failure | Blocks approval |

### 35.4 Disposition triggers at a glance

| Situation | Disposition |
| --- | --- |
| All hard gates pass and composite in pass range | Approved |
| All hard gates pass, composite in conditional range, floors met | Approved with Conditions |
| Fixable defects or low composite | Changes Requested |
| Missing evidence or authority | Deferred |
| Hard gate fail or block threshold | Rejected |
| Canon conflict or scorer dispute | Escalated |

## 36. Final Standard

A quality score is not decoration on a file.

It is the studio's measurable promise that an artifact is fit for its next responsibility.

No approval is honest without hard gate results.

No hard gate pass is honest without evidence.

No composite score is honest without named dimensions and weights.

No release is honest without Gate R tied to the exact public artifact.

Score truthfully.

Record completely.

Approve only what the village, the story, and the audience can trust.
