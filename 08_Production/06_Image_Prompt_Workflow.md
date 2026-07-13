# Image Prompt Workflow

## Purpose

This is the permanent manual for creating, generating, reviewing, and versioning still-image prompts for Village Stories.

It converts a locked storyboard shot into a repeatable visual instruction that preserves early-1990s rural Tamil Nadu canon, recurring identity, location truth, prop state, camera logic, and the hand-painted series style.

Use it for keyframes, start frames, end frames, inserts, thumbnails, backgrounds, image-to-video references, and repair generations.

---

# Philosophy

A prompt is not a wish and it is not a substitute for art direction.

It is a precise production brief for one image.

The best prompt makes a narrow, observable request from already decided facts.

It does not ask a model to resolve character design, geography, history, action, lens, emotion, and composition simultaneously.

Specificity should protect meaning, not bury it in decorative adjectives.

---

# Canon Authority

Prompts inherit authority; they never create it.

Apply this order when prompt details conflict:

```text
01_Canon/ Series Style Lock and timeline
↓
02_World/ location, culture, nature, season, and time
↓
03_Characters/ Character_Rules and individual packets
↓
04_Objects/ recurring objects and materials
↓
Approved episode brief and locked storyboard
↓
Shot continuity record
↓
This prompt workflow
↓
Generated image, animation input, crop, and edit
```

If the prompt needs a visual fact that canon does not establish, mark it `OPEN`.

Resolve it with the Canon And Continuity Lead before generating a recurring asset.

---

# Guiding Principle

Write the image so precisely that it remains recognizably Village Stories even when the caption, dialogue, and episode title are removed.

---

# Roles

## Prompt Lead

Writes the shot prompt, applies references, records versions, and maintains prompt-to-shot traceability.

## Canon And Continuity Lead

Supplies approved facts and rejects output that changes identity, history, geography, or material culture.

## Storyboard Artist Or Director

Approves composition, shot purpose, screen direction, and emotional emphasis.

## Image Generator Operator

Runs controlled variants and logs model, mode, references, seeds or equivalent settings when available, and selected output.

## Google Flow Operator

Confirms whether the chosen still has clean motion potential and is an appropriate source reference for the planned animation.

## Editor

Checks crop flexibility, cut compatibility, visual rhythm, caption-safe areas, and thumbnail usefulness.

---

# Required Inputs

Do not write a final prompt until these are available:

* Locked storyboard panel and shot ID.
* Exact output aspect ratio and intended use.
* Canon source references for each recurring subject.
* Location and time-of-day facts.
* Character visual states: clothing, hair, accessories, posture, emotion, and held objects.
* Prop state and material details.
* Camera framing, height, direction, and movement intent.
* Preceding and following shot handoff facts.
* A concise description of the single frame moment.

For an animation keyframe, also obtain the required motion start or end state.

---

# Prompt Architecture

Build prompts in modules.

Keep the modules in this order unless a tool requires another syntax:

```text
1. Output intent
2. Subject and identity
3. Action or held moment
4. Location and spatial relationship
5. Time, weather, and light
6. Camera and composition
7. Series art direction
8. Materials and period anchors
9. Continuity constraints
10. Exclusions
```

Each module has a job.

Do not repeat the same fact in five different forms.

## 1. Output Intent

State what the image will become.

Examples:

* `Vertical 9:16 keyframe for a YouTube Short.`
* `16:9 opening wide shot for a long-form episode.`
* `Close insert designed as the start frame of a gentle animation.`

This establishes framing priorities before decoration.

## 2. Subject And Identity

Name only characters who matter in the frame.

For a recurring character, cite the approved reference and describe the active state, not a replacement design.

Good:

`Mother, matching her approved Village Stories character reference, kneeling comfortably beside the clay stove; her documented hairstyle and simple early-1990s household clothing remain unchanged.`

Weak:

`a beautiful Indian mother in a sari`

The weak form invites a new person, costume, age, and cultural context.

## 3. Action Or Held Moment

Specify one visible moment.

Good:

`She lowers a split firewood piece into the stove; the wood has not yet caught flame.`

Weak:

`She cooks enthusiastically in a lively kitchen.`

The first has a readable beginning and state; the second requires the model to invent several actions.

## 4. Location And Spatial Relationship

Use the documented location and its meaningful sub-area.

State where the subject stands relative to fixed features:

`inside the Family House kitchen, seen from the doorway, clay stove against the documented wall, grinding stone in the near foreground, open garden-side window behind her.`

Do not say `traditional village kitchen` when the location has a defined identity.

## 5. Time, Weather, And Light

Choose facts, not mood words alone.

Good:

`early monsoon morning, overcast daylight entering through the window, soft wet reflections at the threshold, low-contrast shadows.`

Weak:

`beautiful cinematic moody lighting`

The image needs a source, direction, and atmospheric consequence.

## 6. Camera And Composition

Describe the viewer’s position and focal hierarchy.

Include:

* format,
* shot size,
* camera height,
* viewing angle,
* subject placement,
* foreground and depth,
* screen direction when it matters,
* protected negative space.

Example:

`medium side view at Mother’s seated eye level, camera just inside the doorway, Mother in the lower-right third facing screen left, stove and hands are the focal plane, soft doorway foreground creates depth; keep the upper-left area quiet for a possible caption.`

Use lens language only if the production tool reliably interprets it and the storyboard has called for it.

Do not add wide-angle distortion, dramatic low angles, or shallow focus just to make a mundane task look expensive.

## 7. Series Art Direction

Use the series lock rather than an unrelated visual trend.

Core language:

`original hand-painted animated-film aesthetic, soft painterly digital rendering, watercolor and gouache-inspired texture, gentle cel-style shading blended into painted forms, fine organic linework, natural brush variation, soft atmospheric depth, warm and culturally specific.`

Do not make a living studio name the main instruction.

The project’s approved look is original, even though its existing art-style documentation describes its inspiration.

Avoid photorealism, 3D CGI sheen, vector flatness, glossy synthetic surfaces, heavy outlines, and overly sharp digital edges.

## 8. Materials And Period Anchors

Name materials that make the setting tangible:

* lime-washed wall,
* soot-darkened clay stove,
* brass tumbler,
* woven bamboo basket,
* worn wood,
* packed-earth courtyard,
* hand-painted plaster,
* cotton clothing,
* banana leaf,
* stone grinding surface.

Use only objects and materials appropriate to the documented action and location.

One accurate detail is better than ten generic “rustic” details.

## 9. Continuity Constraints

State facts the model must not drift from:

* character reference identity,
* current costume and hair,
* carried prop hand and condition,
* direction of attention,
* weather state,
* light direction,
* preceding-shot end state,
* planned animation start state.

Example:

`Maintain the same brass tumbler from SH012: half-full, in Mother’s left hand, no handle, water surface still.`

## 10. Exclusions

Use targeted exclusions for known risks.

Examples:

`No smartphones, branded packaging, plastic water dispenser, LED lighting, modern appliances, modern vehicles, text, logos, extra fingers, duplicated utensils, camera-facing pose, or photorealistic rendering.`

An exclusion list must address actual failure modes.

Do not turn it into an incoherent wall of forbidden words.

---

# Prompt Workflow

## Step 1: Read The Storyboard, Not Just The Panel Image

Read the shot description, start state, end state, prior shot, and next shot.

A single still is part of a sequence.

If SH018 ends with the basket in Elder Brother’s right hand, the keyframe for SH019 cannot place it on the ground for compositional convenience.

## Step 2: Create The Shot Fact Sheet

Before prose, list facts under these headings:

```text
Shot ID:
Purpose:
Use:
Aspect ratio:
Moment:
Characters:
Character references:
Location:
Time / weather:
Props:
Continuity from prior shot:
Continuity into next shot:
Camera:
Safe areas:
Known risks:
```

Do not begin generation until this sheet has no unmarked unknowns.

## Step 3: Select References Deliberately

Use the minimum set of reference images that establishes identity.

Typical reference hierarchy:

1. Character reference for every prominent recurring character.
2. Location reference when its architecture or layout is visible.
3. Prop reference when it carries story information.
4. Prior approved shot when matching a handoff or light state.

Too many competing references can confuse visual priority.

When a reference is only inspirational, label it as such and do not use it as a canon source.

## Step 4: Write The Base Prompt

Write the most important facts first:

* who,
* doing what,
* where,
* when,
* from which view,
* in what project style.

Then add only the material and continuity facts that protect the shot.

Read it aloud.

If the main image cannot be described in one sentence, the board may contain too much action.

## Step 5: Add Format And YouTube Framing

Frame for the delivery crop, not a hypothetical master image.

For 9:16 Shorts:

* keep the face, hands, and story prop in the central vertical band;
* do not hide the essential beat at the extreme top or bottom;
* reserve clean, low-detail space where captions may appear;
* allow a little crop tolerance but not a second composition.

For 16:9:

* preserve readable action on standard phone playback;
* use width to explain geography, not to scatter attention;
* avoid placing all emotion in a tiny center figure.

For thumbnails:

* prioritize one face, object, or clear action;
* use readable contrast and silhouette;
* do not generate false drama that does not occur in the episode;
* leave room for title treatment only when it does not cover the story clue.

## Step 6: Generate Controlled Variants

Generate a small, purposefully varied batch.

Change one variable group per batch:

* composition,
* gesture,
* light balance,
* prop placement,
* or environment density.

Do not alter identity, location, period, and camera all at once.

Record every selected candidate against its shot ID.

## Step 7: Evaluate At Full Frame And Delivery Size

Inspect the image at:

* full resolution for anatomy, materials, artifacts, and background errors;
* the intended YouTube crop for focal clarity;
* ordinary mobile size for readability;
* side-by-side with adjacent approved shots for continuity.

An image can be beautiful at full size and fail completely on a Short.

## Step 8: Repair By Cause

Classify failure before revising:

* Identity failure.
* Canon or period failure.
* Composition failure.
* Prop-state failure.
* Anatomy failure.
* Style failure.
* Animation-readiness failure.
* Crop or caption-safety failure.

Change the prompt module responsible for the failure.

Do not add random adjectives after every bad output.

## Step 9: Approve Or Reject

Approve only when the still:

* fulfills the board’s shot purpose;
* follows canon;
* matches required references;
* has clean anatomy and object logic;
* hands off to adjacent shots;
* supports its planned animation;
* works in its delivery frame.

Reject rather than “fix in edit” if the central action, character, prop, or period is wrong.

## Step 10: Archive The Production Record

For the selected output, store:

```text
Shot ID and revision:
Prompt text:
Reference set:
Tool / model / mode:
Generation date:
Relevant settings available in the tool:
Candidate identifier:
Approved output identifier:
Reviewer:
Known limitations:
Downstream animation use:
```

Archive the approved source at a resolution suitable for the planned workflow.

Never treat a downloaded file with an ambiguous name as sufficient production history.

---

# Image Prompt Template

```text
[Output intent and aspect ratio.]

[Recurring character name], matching the approved character reference, [single visible action or held moment]. [Character state, clothing, hair, expression, and hand/prop facts.]

At [documented location and sub-area], [spatial relationship to fixed location features]. [Relevant recurring props and exact state.]

[Time of day, season, weather, light source, light direction, and physical atmosphere.]

[Shot size, camera position, height, subject placement, screen direction, focal hierarchy, foreground / depth, safe negative space.]

Original Village Stories hand-painted animated-film aesthetic: soft painterly digital rendering, watercolor and gouache-inspired textures, gentle cel-style shading, fine organic linework, layered environmental detail, believable anatomy, subtle expression, culturally specific early-1990s rural Tamil Nadu.

[Continuity constraints from adjacent shots.]

Avoid: [targeted exclusions].
```

---

# Positive Examples

## Example: Animation Start Frame

```text
Vertical 9:16 start keyframe for EP014_S02_SH006.

Younger Daughter, matching her approved Village Stories character reference, crouches at the edge of the front garden and gently reaches toward one fallen mango leaf; her simple morning clothing, hairstyle, proportions, and curious calm expression match the continuity packet. Her left hand already holds the small woven basket from SH005.

At the documented Family House front garden, she faces screen right beside the low garden border; the garden path leads behind her toward the thinnai, with coconut and banana foliage arranged as established for the location.

Early monsoon morning after light rain, soft overcast daylight, damp packed earth, tiny water droplets on leaves, no hard sun shadows.

Medium-low side view at the child’s eye level, camera on the path, Daughter in the central lower third, her reaching hand and the leaf are the focal point, gentle foreground leaves create depth; preserve quiet upper space for captions.

Original Village Stories hand-painted animated-film aesthetic: soft painterly digital rendering, watercolor and gouache-inspired textures, gentle cel-style shading, fine organic linework, layered botanical detail, believable anatomy, subtle expression, culturally specific early-1990s rural Tamil Nadu.

The leaf remains on the ground at this start state; no other character enters frame.

Avoid: modern objects, plastic-dominant dressing, logos, text, extra fingers, duplicated basket, glossy CGI, photorealism, camera-facing pose.
```

Why it works: it names a single action, uses a defined location, protects a carried prop, gives a motion start state, and reserves vertical framing.

## Example: Prop Insert

```text
16:9 close insert for EP021_S03_SH014. A worn brass tumbler, half-full of water, sits on the documented wooden kitchen shelf immediately after Mother places it down. Soft window light comes from screen left; a clay pot and folded cotton cloth stay softly behind it. Camera is at shelf height with the tumbler filling the right third, leaving the left side softly simple for the next cut. Original Village Stories hand-painted animated-film aesthetic, true brass warmth, visible everyday wear, early-1990s rural Tamil Nadu material culture. Avoid handles, branding, plastic, duplicate tumblers, text, modern kitchen fixtures, photorealism.
```

Why it works: a small object receives enough state, place, light, and editorial context to match other shots.

## Example: Location Establishing Frame

```text
16:9 wide establishing image for EP021_S01_SH002: the documented Tea Stall in early morning, viewed from the village path at standing height. The Tea Stall Owner matches his approved reference and is already working behind the counter, not posing; two background villagers wait naturally under shade without competing for attention. Steam rises from a period-appropriate tea vessel, bicycles rest logically nearby, and the familiar path leads from screen left toward the stall. Soft warm morning light, long but gentle shadows, original Village Stories hand-painted animated-film aesthetic with layered foliage and weathered materials. Avoid modern signage, branded packaging, café furniture, motorcycles, LED lighting, text, logos, glossy CGI.
```

Why it works: it establishes a recurring place, supporting character, activity, and period without turning the village into an empty postcard.

---

# Common Mistakes And Corrections

## Mistake: Prompting A Character Archetype

Problem:

`cute rural girl in a sari`

Correction:

Name Younger Daughter, attach her approved reference, current clothing state, age-appropriate body proportions, known personality, activity, and location.

## Mistake: Style-Only Prompts

Problem:

`beautiful cinematic anime village, masterpiece`

Correction:

Start with the shot’s character, action, location, period, camera, and continuity. Style supports those facts.

## Mistake: Contradictory Camera Language

Problem:

`intimate close-up, wide aerial view, extreme depth of field, macro lens`

Correction:

Choose one intended view from the board. If the shot needs two views, it needs two shots.

## Mistake: Unbounded Motion Image

Problem:

The start frame contains a character mid-stride, a tossed tool, flying cloth, two animals crossing, and rain beginning.

Correction:

Pick the moment immediately before the key movement. Give Google Flow a stable, readable start condition.

## Mistake: Decorative Anachronism

Problem:

The model adds shiny plastic containers, modern tiles, branded packets, LED strips, a scooter, or fashionable contemporary clothing.

Correction:

Add specific period and material anchors plus targeted exclusions. Reject the image; do not crop out a recurring contradiction if its influence remains visible.

## Mistake: “Same Character” Without Reference

Problem:

The prompt assumes prior generations will preserve face, build, hair, and costume.

Correction:

Attach the approved character reference and state the current scene condition. Generate from the selected reference, not from memory.

## Mistake: Ignoring Hands And Tools

Problem:

The story is about grinding, cooking, farming, or repairing, but the prompt gives no tool orientation or hand relationship.

Correction:

Specify which hand holds what, where the tool contacts the material, and whether the action is at its start, middle, or completion.

## Mistake: Duplicate Or Missing Objects

Problem:

The output creates three ladles, two baskets, or removes the story prop.

Correction:

Name the required object count, material, owner, position, and state. Use a prop reference for important repeated objects.

## Mistake: Text Generated Into The World

Problem:

The model invents signage, labels, packaging, or decorative text.

Correction:

Exclude text and logos. Add final text later in the edit, never as a generated world element.

---

# Prompt QA Checklist

## Fact Integrity

* Does the prompt cite the correct shot ID and output use?
* Are character, location, prop, season, time, and weather facts sourced?
* Are unresolved facts marked rather than invented?

## Character Integrity

* Are approved references used for every prominent recurring character?
* Are face, body, hair, clothing, posture, and behaviour consistent?
* Are people naturally engaged with their task instead of posing?

## World And Period

* Is the location recognizably its documented place?
* Are materials, architecture, animals, and vegetation plausible?
* Is it free of modern technology, branding, plastic dominance, and historical caricature?

## Camera And Composition

* Does the framing match the board?
* Is the focal action readable?
* Is screen direction correct?
* Are foreground, depth, and safe text space intentional?

## Continuity

* Does the image match the prior-shot handoff?
* Does it create the required next-shot or animation state?
* Are props, hand positions, wetness, light, and costume correct?

## Technical Review

* Are anatomy, hands, tools, object counts, and reflections believable?
* Is the style painterly and original rather than glossy, photoreal, or generic?
* Does the image succeed at the final YouTube crop and mobile size?

---

# Related Documents

* `01_Canon/01_Series_Style_Lock/Project_Identity.md`
* `01_Canon/01_Series_Style_Lock/Art_Style.md`
* `01_Canon/01_Series_Style_Lock/Production_Quality.md`
* `01_Canon/07_Timeline.md`
* `02_World/README.md`
* `03_Characters/README.md`
* `03_Characters/Character_Rules/Appearance_Rules.md`
* `03_Characters/Character_Rules/Camera_Rules.md`
* `04_Objects/README.md`
* `05_Research/Common_Historical_Mistakes.md`
* `07_Episode_System/12_YouTube_Shorts.md`
* `08_Production/05_Storyboard_Workflow.md`
* `08_Production/07_Google_Flow_Workflow.md`

---

# Final Approval

An approved image prompt and selected output must be reproducible, reviewable, and traceable to the locked shot.

If an image is attractive but cannot be tied to a correct storyboard moment and canon state, it is not a production asset.
