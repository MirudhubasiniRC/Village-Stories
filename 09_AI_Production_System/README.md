# AI Production System

## Purpose

This folder permanently defines how Village Stories converts approved canon and production plans into reusable, reviewable AI prompts.

It captures prompt knowledge that must not remain only in a single operator's memory:

* Character, location, object, style, and camera locks.
* Prompt modules and variables.
* Master prompt templates.
* Google Flow prompt practice.
* Prompt quality assurance.
* Failure diagnosis and revision.
* End-to-end AI episode generation.

The AI Production System does not create new canon. It makes existing canon reproducible through disciplined prompt construction.

---

# Why This Folder Exists

AI generation can create attractive images and animation that are unusable for a persistent series.

An image fails when it:

* Changes a recurring character's age, face, clothing, proportions, or emotional behaviour.
* Rebuilds a familiar location with a different layout.
* Replaces a period-correct object with a modern equivalent.
* Changes weather, time of day, camera direction, or story state between shots.
* Introduces an unapproved visual style.
* Uses a movement description that breaks the intended scene action.

Prompt quality is therefore not only a writing skill. It is a continuity-control system.

---

# System Philosophy

Prompts must be assembled from approved information, not improvised from memory.

Every prompt should be:

* Specific enough to protect continuity.
* Modular enough to reuse.
* Short enough for the target tool to interpret reliably.
* Structured around the purpose of the shot.
* Reviewed as a production asset, not accepted as an experiment.

The goal is not to make the most decorative prompt.

The goal is to make the correct shot reliably.

---

# AI Production Workflow

```text
Approved episode and scene plan
↓
Select canonical locks
↓
Select relevant prompt modules
↓
Set scene-specific variables
↓
Build image or animation prompt
↓
Generate and review output
↓
Diagnose any failure
↓
Revise the smallest necessary prompt component
↓
Approve and archive the usable asset
```

Never begin with a blank creative prompt when an established module, lock, reference, or prior approved shot already exists.

---

# Authority Hierarchy

The AI Production System inherits, but does not override, higher authorities:

```text
01_Canon/
↓
02_World/ · 03_Characters/ · 04_Objects/
↓
05_Research/
↓
06_Story_Engine/
↓
07_Episode_System/
↓
08_Production/
↓
09_AI_Production_System/
↓
Episode prompt and generated asset
```

If a prompt module conflicts with character, world, or production canon, the higher document wins and the module must be corrected.

---

# Prompt Construction Principle

Every prompt has two layers.

## Permanent Layer

The permanent layer contains reusable canon locks:

* Series style and visual identity.
* Character identity and behaviour.
* Location layout and material language.
* Object identity and period limits.
* Camera and composition rules.
* Google Flow continuity instructions.

## Scene Layer

The scene layer contains the change specific to one shot:

* Current action.
* Emotional state expressed through visible behaviour.
* Time of day, weather, and seasonal condition.
* Required objects and their current state.
* Framing and camera movement.
* Sound or transition context where relevant.

Keep permanent and scene information separate. This makes it possible to diagnose which part caused a drift.

---

# Folder Roadmap

The AI Production System will be completed one document at a time.

```text
09_AI_Production_System/

README.md

01_Master_Workflow.md

02_Master_Story_Prompt.md
03_Master_Script_Prompt.md
03_Script_Prompt_Reference.md
04_Master_Image_Prompt.md
04_Image_Prompt_Reference.md
05_Master_Animation_Prompt.md
06_Master_Voice_Prompt.md

07_Prompt_Modules.md

08_Character_Lock_System.md
09_Location_Lock_System.md
10_Object_Lock_System.md
11_Style_Lock_System.md
12_Camera_Lock_System.md

13_Google_Flow_Best_Practices.md
14_Prompt_QA.md
15_Common_Failures.md
16_Revision_Workflow.md
17_Episode_Generation_Pipeline.md
19_Camera_Direction_Bible.md
20_Camera_Movement_Bible.md
```

---

# File Responsibilities

## 01_Master_Workflow.md

Defines the complete AI prompt lifecycle from approved scene plan to archived usable asset.

## 02_Master_Story_Prompt.md

Defines the reusable prompt for developing a canon-safe story premise.

## 03_Master_Script_Prompt.md

Defines the concise, executable prompt for converting an approved premise into a script.

## 03_Script_Prompt_Reference.md

Defines the detailed script rules, source-loading, format distinctions, downstream handoffs, and validation reference used while assembling a script prompt.

## 04_Master_Image_Prompt.md

Defines the concise, executable master structure for still-image generation.

## 04_Image_Prompt_Reference.md

Defines the detailed lock, composition, reference-image, negative-constraint, and Google Flow reference material used while assembling image prompts.

## 05_Master_Animation_Prompt.md

Defines the master structure for animation instructions.

## 06_Master_Voice_Prompt.md

Defines the master structure for narration and voice generation.

## 07_Prompt_Modules.md

Defines reusable prompt components and safe assembly rules.

## 08_Character_Lock_System.md

Defines how recurring people and the Family Dog remain visually and behaviourally stable.

## 09_Location_Lock_System.md

Defines how recurring locations preserve layout, atmosphere, and usable camera geography.

## 10_Object_Lock_System.md

Defines how recurring objects retain identity, materials, placement, and state.

## 11_Style_Lock_System.md

Defines the series-wide visual style layer.

## 12_Camera_Lock_System.md

Defines reusable camera language, framing, movement, and screen-direction controls.

## 13_Google_Flow_Best_Practices.md

Defines Google Flow-specific prompting, reference use, continuity, and review practice.

## 14_Prompt_QA.md

Defines prompt-level checks before generation and output-level checks after generation.

## 15_Common_Failures.md

Defines recurring AI failures, likely causes, and appropriate corrections.

## 16_Revision_Workflow.md

Defines how to revise prompts and assets without losing a usable version or changing canon.

## 17_Episode_Generation_Pipeline.md

Defines the complete prompt and asset sequence for one episode.

## 19_Camera_Direction_Bible.md

Defines the sole operational authority for camera position, shot type, framing, angle, screen direction, and shot selection.

## 20_Camera_Movement_Bible.md

Defines the sole operational authority for camera motion, speed, movement boundaries, and Google Flow movement instructions.

---

# Google Flow Considerations

Google Flow prompts must preserve:

* Character identity across scenes and episodes.
* Location layout and screen geography.
* Object condition and placement from shot to shot.
* Lighting, weather, time, and seasonal continuity.
* Camera direction and transition logic.
* Motion that matches the planned story action.

Choose one-image or two-image input based on continuity need, not convenience:

* One image may be appropriate for an isolated establishing shot or a self-contained action.
* Two images may be necessary when the incoming and outgoing visual state must remain controlled.

The exact selection rules belong in `13_Google_Flow_Best_Practices.md`.

---

# Quality Standard

Before generating, an operator must be able to answer:

* Which canon locks does this shot require?
* What is the one visible action?
* What must remain unchanged from the previous shot?
* What may change in this shot?
* Which module owns each prompt instruction?
* How will an incorrect result be diagnosed?

After generating, an operator must be able to answer:

* Does the result preserve every required lock?
* Does it advance the scene rather than merely look attractive?
* Does it match the planned camera, lighting, and emotional state?
* Can it connect to its neighbouring shots without visual drift?

If any answer is no, the asset is not approved.

---

# Relationship With Other Documents

This system uses:

```text
03_Characters/
02_World/Locations/
04_Objects/
06_Story_Engine/
07_Episode_System/
08_Production/
```

It must be used alongside:

```text
08_Production/06_Image_Prompt_Workflow.md
08_Production/07_Google_Flow_Workflow.md
08_Production/14_Quality_Control.md
08_Production/16_File_Organization.md
08_Production/17_Version_Control.md
```

This folder defines reusable AI prompt systems. It does not replace production approval, episode review, or canon authority.

---

# Canon Authority

This folder is the permanent authority for Village Stories AI prompt architecture, lock systems, generation review, and prompt revision.

It cannot authorise a new character, location, object, style, or story fact. Such changes require the proper higher-level canon document and an explicit canonical decision.

---

# Guiding Principle

Use AI to reproduce a carefully known world—not to invent a different world every time a scene is generated.
