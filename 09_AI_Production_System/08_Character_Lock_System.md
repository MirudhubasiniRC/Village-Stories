# Character Lock System

## Purpose

This is the permanent production manual for keeping recurring Village Stories
people and the Family Dog recognisable across stills, Google Flow clips, edits,
episodes, and future seasons.

It converts approved character canon into small, testable production locks.

It does not create a new person, wardrobe, relationship, or behavioural fact.

## Non-Negotiable Context

- The world is early-1990s rural Tamil Nadu.
- The core family is Father, Mother, Elder Brother, Younger Daughter, and Dog.
- Show a family member only when the approved scene needs that person.
- Use only established named characters and approved community groups.
- Do not populate scenes with invented relatives or anonymous lookalikes.
- Preserve ordinary life, dignity, and a calm observational tone.
- The visual treatment is original premium cinematic anime.
- Faces retain natural South Indian features and believable anatomy.
- Never name or imitate an external studio, artist, film, or franchise.

## Authority

Apply the first applicable source in this order.

1. Approved current production decision.
2. `01_Canon/` continuity, timeline, art-style, and camera locks.
3. The character's `03_Characters/` source documents.
4. Approved character reference asset.
5. Approved episode brief, script, board, and scene-state ledger.
6. `08_Production/` execution and quality-control requirements.
7. This manual and the relevant prompt template.
8. A selected previous asset only as evidence of an already approved state.
9. Tool defaults and generated candidates have no authority.

If two approved sources conflict, stop and record `HOLD FOR CANON DECISION`.

Never average contradictory descriptions into a compromise design.

## Lock Vocabulary

- `IDENTITY HARD LOCK`: same recurring individual or animal.
- `ANATOMY HARD LOCK`: age band, build, height relationship, face, coat, or scale.
- `WARDROBE HARD LOCK`: documented garment or permanent accessory.
- `STATE FACT`: current approved condition in this scene.
- `VARIABLE`: a permitted scene-specific change.
- `OPTIONAL`: safe detail that may be omitted.
- `NEGATIVE`: prohibited result.
- `OPEN`: missing fact; never silently invent it.
- `REFERENCE`: an attachment with one declared job.
- `CARRYOVER`: fact inherited from the preceding approved shot.

Hard locks survive every shot unless a higher source explicitly changes them.

Variables may change only when their start and end state are recorded.

## Character Source Packet

Build one compact packet per visible character before prompt construction.

Do not paste entire character manuals into a generation tool.

Load facts, not pages.

### Required Packet Fields

```text
Episode / scene / shot ID:
Character:
Why visible in this shot:
Source documents and revisions:
Approved reference filename and role:
Identity hard locks:
Visible anatomy hard locks:
Wardrobe hard locks:
Permanent accessories or markings:
Expression and body-language limits:
Current activity:
Start position and screen direction:
End position and screen direction:
Current clothing / grooming / cleanliness state:
Held or worn objects:
Relationship partner and approved interaction:
Location and surface:
Time / weather / light:
Carryover facts:
Permitted variables:
Negative constraints:
Open facts and owner:
```

Use `NONE` only when a field genuinely does not apply.

Use `OPEN` only with an owner and resolution path.

An unresolved identity, wardrobe, or position fact blocks a continuity-critical
shot.

## Packet Extraction Rules

- Extract the smallest set of facts that constrains the intended frame.
- Keep identity facts separate from current pose and camera facts.
- Keep clothing identity separate from temporary soil, dampness, or folds.
- Record whether an object is worn, held, carried, set down, or absent.
- Record which side of the body holds a visible object.
- Record whether a face must be readable, partial, distant, or off-screen.
- Record who is permitted to touch whom and why.
- Record the prior shot when a person crosses a cut.
- Record scale relationships when two family members share a frame.
- Record absence when it prevents an unwanted extra character.

## Reference Hierarchy

Use references in the following priority order.

1. The relevant written canon.
2. An approved dedicated canon-design reference.
3. The immediately preceding selected asset for continuity.
4. An approved turnaround, storyboard, or source still.
5. A production photo only when approved as a factual aid.
6. A generated candidate never replaces canon.

One attachment may have one primary job.

Label every attachment before upload.

```text
CHARACTER_IDENTITY — same face, hair, build, or coat.
WARDROBE_STATE — same garment, drape, accessory, or cleanliness.
POSE_CONTINUITY — same stance or hand placement.
SCENE_CONTINUITY — incoming frame only.
LIGHTING_CONTEXT — approved exposure and direction only.
DO_NOT_COPY — inspiration excluded from factual authority.
```

Do not use a mood image to override a face reference.

Do not use a close-up reference to infer an unseen full-body wardrobe.

Do not use a selected prior frame to retain an error it contains.

## Father: Permanent Identity Packet

Father is the same recurring South Indian village farmer in every appearance.

His primary design reference is:

```text
11_Assets/Character_References/Father_Canon_Design_Reference.png
```

Attach it as `CHARACTER_IDENTITY` whenever the tool supports references and
Father is principal, face-visible, establishing, or being repaired.

### Father Immutable Facts

- Approximately 31–33 years old.
- Warm medium-brown South Indian complexion.
- Natural outdoor tanning on face, neck, forearms, and lower legs.
- Lean farmer build.
- Broad shoulders.
- Strong forearms.
- Healthy practical muscle, never a gym physique.
- Lean strong jawline.
- Straight well-defined nose.
- Dark brown almond-shaped steady eyes.
- Naturally thick black hair.
- Short-to-medium rural cut.
- Softly tousled side-swept hair.
- Slightly irregular front fringe.
- Light naturally kept stubble.
- No prominent separate moustache.
- Calm, grounded posture.
- Steady, economical walking.
- Capable weathered hands.
- Recognisable outdoor-worker silhouette.

### Father Wardrobe Locks

- Practical cotton shirt.
- Deep muted blue is his primary recurring work-shirt colour.
- Cotton veshti or practical work veshti.
- Simple cotton thundu when the scene supports it.
- Bare feet in appropriate familiar home areas.
- Traditional sandals where the location requires them.
- Natural cotton texture and work wrinkles.
- No fashion tailoring.
- No synthetic shine.

### Father Permitted Variables

- Sleeve roll during practical work.
- Higher veshti fold during labour.
- Light sweat after heat or effort.
- Soil, hay dust, water, sap, or grease when motivated.
- Damp hairline after work or rain.
- White or muted shirt variation when source-backed.
- Cleaner white veshti and neater grooming for approved ceremony.
- Thundu position: shoulder, hand, head cover, or absent when not required.

### Father Negatives

- Never clean-shaven.
- Never heavily bearded.
- Never handlebar moustached.
- Never salon-styled.
- Never spiky or gelled.
- Never fashion-model polished.
- Never bulky bodybuilder-built.
- Never a different man with similar clothes.
- Never contemporary clothing or watch.
- Never spectacle hero posing.
- Never unexplained jewellery.

## Mother: Permanent Identity Packet

Mother is the same recurring South Indian village woman in every appearance.

### Mother Immutable Facts

- Approximately 30–35 years old.
- Warm medium-brown South Indian complexion.
- Soft oval face.
- Gentle jawline and rounded cheeks.
- Dark brown calm almond-shaped eyes.
- Naturally thick long black hair.
- Everyday traditional half-up hairstyle.
- Soft waves through the lower hair.
- Small centered red bindi.
- Small gold nose pin on the left nostril.
- Small traditional gold jhumkas.
- Exactly one simple gold chain.
- The chain carries a traditional thali pendant.
- Thin glass bangles on both wrists.
- Medium healthy build.
- Graceful practical posture.
- Calm, purposeful, efficient walking.
- Skilled, expressive hands.

### Mother Jewellery Lock

Mother's jewellery is identity, not decoration.

- Keep the left-nostril nose pin.
- Keep small modest jhumkas.
- Keep one simple thali chain.
- Keep the thali pendant.
- Keep thin glass bangles.
- Keep jewellery proportionate and non-glamorous.
- Keep jhumkas and chain visible when pose and crop reasonably permit.
- Permit natural small motion only in animation.
- Let bangle colours coordinate with the saree.
- Do not multiply necklaces.
- Do not substitute a heavy jewellery set.
- Do not remove permanent jewellery without approved story justification.

### Mother Wardrobe Locks

- Traditional Tamil cotton saree for ordinary life.
- Matching practical short-sleeved blouse.
- Secure, functional drape.
- Natural cotton folds and gentle wrinkles.
- Earthy, muted palette.
- Thin woven, temple, stripe, or small geometric border.
- Bare feet indoors where appropriate.
- Traditional flat sandals when needed outside.
- No glossy synthetic fabric.
- No modern fashion styling.

### Mother Permitted Variables

- Low bun or simple braid during fire-adjacent cooking or heavy work.
- Return to half-up hairstyle after the temporary work need ends.
- Pallu tucked for cooking.
- Saree tucked slightly for gardening.
- Flour, turmeric, water, or soil on working hands.
- Damp hair and wet saree edge during rain.
- Thin cotton shawl in supported cool morning.
- Jasmine only when source-backed.
- Festival clothing only when the approved occasion requires it.

### Mother Negatives

- Never a different face.
- Never hair cut short or recoloured.
- Never missing bindi without approved reason.
- Never nose pin on the wrong nostril.
- Never multiple everyday chains.
- Never oversized earrings.
- Never ornate bridal styling on an ordinary day.
- Never heavy makeup.
- Never western clothing.
- Never high heels.
- Never glossy designer saree.

## Elder Brother Packet Rules

Load his own identity, appearance, clothing, behaviour, and continuity files.

Preserve his documented age, scale, face, hair, clothing, and sibling role.

Do not infer adulthood, a new school uniform, or a new hobby from a pose.

Keep him visibly younger and appropriately scaled beside Father and Mother.

Use child movement that is natural, safe, and not hyperactive spectacle.

Do not make him a miniature adult, comedian, hero, victim, or plot device.

## Younger Daughter Packet Rules

Load her own identity, appearance, clothing, behaviour, and continuity files.

Preserve her documented age, scale, face, hair, clothing, and family role.

Keep her visibly younger than Elder Brother.

Use child-safe ordinary actions and approved family proximity.

Do not age her up, glamourise her, isolate her in danger, or invent school facts.

Do not make her clothing a fashion costume.

## Family Dog Packet

The Family Dog is a healthy adult male German Shepherd household companion.

### Dog Immutable Facts

- Approximately 3–5 years old.
- Male.
- Medium-large real German Shepherd scale.
- Classic black-and-tan saddle pattern.
- Medium outdoor coat.
- Erect mobile ears.
- Dark intelligent eyes.
- Strong chest and athletic practical body.
- Natural shepherd tail carriage.
- Calm compound presence.
- Gentle orientation toward family.

### Dog Permitted Variables

- Waiting.
- Following.
- Resting.
- Observing.
- Soft response to familiar sound.
- Natural play.
- Light dust on paws and lower legs.
- Damp coat after rain.
- Natural drying in shade.

### Dog Negatives

- Never police or military dog coding.
- Never attack posture.
- Never growling threat.
- Never chase sequence.
- Never rescue device.
- Never missing-pet hook.
- Never injury or distress hook.
- Never oversized wolf-like anatomy.
- Never polished show-dog grooming.
- Never an unexplained collar, uniform, or leash.

## Other Established Characters

For Village People, Neighbours, and Community groups, use only source-backed
facts from their existing character documents.

Load each named person's identity before adding them to a frame.

If no approved visual packet exists for a requested person, hold the shot or use
an approved non-identifying distant presence only when the scene permits it.

Do not synthesize a new named character from profession alone.

Do not confuse Tea Stall Owner, School Teacher, Headmaster, Priest, Potter,
Carpenter, Barber, Blacksmith, Grocery Shopkeeper, neighbours, or vendors.

## Immutable Versus Variable Decision Test

Ask these questions for every visible feature.

1. Does a source say it recurs across the series?
2. Does it identify the person at a glance?
3. Does it affect period, culture, relationship, or story truth?
4. Did the previous approved shot establish its current state?
5. Is the requested change explicitly motivated and recorded?

If answers 1–4 are yes and 5 is no, lock the feature.

If a change is temporary, write its restoration condition.

## Prompt Construction

Build character instructions in this order.

1. Character name and reason for presence.
2. Identity hard lock.
3. Visible wardrobe and permanent accessories.
4. Current state and one visible action.
5. Position, eyeline, and screen direction.
6. Relation to another person, object, and location.
7. Light and camera facts affecting readability.
8. Negative constraints.

Keep the wording concrete and observable.

Prefer “Father, same canon-design reference, light stubble, muted blue cotton
shirt, lifts the brass pot with both hands” to adjective piles.

Do not ask the model to remember an entire biography.

## Character Prompt Template

```text
[CHARACTER] is present because [SCENE REASON].
Identity: [IMMUTABLE VISIBLE FEATURES].
Wardrobe and permanent identifiers: [GARMENT / JEWELLERY / MARKINGS].
Current state: [CLEANLINESS / DAMPNESS / TEMPORARY ADJUSTMENT].
Action: [ONE VISIBLE ACTION].
Position and direction: [PLACE / BODY ORIENTATION / EYELINE].
Interaction: [APPROVED PERSON / OBJECT / DISTANCE].
Preserve: [CARRYOVER FACTS].
Do not show: [CHARACTER-SPECIFIC NEGATIVES].
```

## Father Prompt Example

```text
Father, the same man from Father_Canon_Design_Reference.png, stands at the
west-side kitchen threshold. Preserve his warm medium-brown complexion, thick
softly tousled black hair, light natural stubble, lean farmer build, broad
shoulders, and strong forearms. He wears his muted deep-blue cotton work shirt,
off-white work veshti, and a soft cotton thundu on one shoulder. He sets down
one approved water vessel with both hands, then looks toward Mother. Keep his
calm grounded posture and screen-right-facing carryover direction. Do not make
him clean-shaven, heavily bearded, gym-built, salon-styled, or fashion dressed.
```

## Mother Prompt Example

```text
Mother, the same recurring woman, works at the kitchen counter. Preserve her
warm medium-brown complexion, long black half-up hair, centered small red bindi,
left-nostril gold nose pin, small gold jhumkas, exactly one simple thali chain,
and thin glass bangles. She wears the approved practical cotton saree and
short-sleeved blouse with the pallu tucked for cooking. She calmly stirs the
approved pot, facing screen left toward Father. Keep the chain single and
modest. Do not remove her jewellery, add necklaces, use bridal styling, or
modernise her clothing.
```

## Dog Prompt Example

```text
The established adult male Family Dog, a calm black-and-tan German Shepherd,
rests beside the Front Thinnai step with ears softly alert toward the family.
Preserve his real medium-large shepherd scale, erect ears, dark eyes, outdoor
coat texture, and gentle household-companion behaviour. He remains still except
for a small ear turn. Do not make him threatening, uniformed, injured, chasing,
or wolf-like.
```

## Scene Continuity Ledger

Create a row for every visible person or Dog.

```text
Shot ID | Subject | Entry | Position | Facing | Hands/paws | Wardrobe state |
Accessories | Held object | Expression | Exit | Carryover owner
```

Record left/right only from the camera view.

Record body orientation separately from gaze when they differ.

Record hand ownership for every continuity-critical object.

Record if a permanent identifier is intentionally out of crop.

Never use “same as before” without linking the exact source asset.

## Across-Cut Checks

Before approving a shot, compare it with the incoming selected asset.

- Same individual, not merely similar demographics.
- Same age band.
- Same height and scale relationship.
- Same face shape and hair silhouette.
- Same Father stubble treatment.
- Same Mother jewellery set and side-specific nose pin.
- Same current garment unless a change is shown or logged.
- Same garment wetness, soil, sleeve, pallu, and fold state where visible.
- Same held object and hand.
- Same body direction unless movement across the cut explains reversal.
- Same emotional intensity unless the story beat changes it.
- Same Dog coat pattern, scale, and position logic.

## Google Flow Character Rules

Flow animates approved identity; it does not establish identity.

Use an approved source still whenever identity or wardrobe continuity matters.

Use Father’s canon design reference in addition to the still when Flow permits
separate reference roles and Father is recognisably visible.

Choose one-image Flow input when the start state alone sufficiently constrains
the short motion.

Choose two-image Flow input only when the approved end state is materially
different and both states need protection.

In Flow, state:

- Who moves.
- The one principal movement.
- The permitted secondary movement.
- What remains still.
- What accessories may move naturally.
- What must not change.

Example:

```text
Animate only Mother’s right hand completing one slow stir. Her cotton saree,
left-nostril nose pin, small jhumkas, single thali chain, thin bangles, face,
hair, and body position remain unchanged. The jhumkas and bangles move only
subtly with her arm. Keep Father in the background still and recognisable.
```

Reject Flow drift even when the movement looks attractive.

## Still-Image QA

Approve only when every applicable item passes.

- Required subject is present.
- Unrequired family members are absent.
- Identity matches the source packet.
- Age and scale are correct.
- Skin tone is natural and consistent.
- Face and hair are recognisable.
- Father matches the canon reference.
- Father has light stubble.
- Mother has left-nostril nose pin.
- Mother has small jhumkas.
- Mother has one thali chain.
- Mother has thin glass bangles when wrists are visible.
- Clothing is period-correct and scene-correct.
- Temporary state is motivated.
- Action is readable.
- Hand count and anatomy are believable.
- Relationship distance is appropriate.
- Screen direction is continuous.
- No unsupported accessory appears.
- No modern detail appears.

## Motion QA

Approve only when:

- Identity survives every frame.
- Face does not morph.
- Hair length and silhouette do not drift.
- Jewellery does not vanish, multiply, or enlarge.
- Father’s stubble does not change.
- Clothing does not change colour or cut.
- Saree and veshti remain physically plausible.
- Hands remain anatomically credible.
- Movement has one readable purpose.
- Secondary movement remains restrained.
- Dog behaviour remains gentle and natural.
- No new person enters.
- No person disappears without a cut.
- Start and end states match the ledger.

## Rejection Rules

Reject immediately for:

- Wrong recurring face.
- Wrong Father reference identity.
- Wrong Mother nose-pin side.
- Missing, multiplied, or ornate Mother jewellery.
- Modern hairstyle or clothing.
- Different age or body scale.
- Clean-shaven or heavily bearded Father.
- Unapproved character presence.
- Threatening Dog behaviour.
- Broken hands, limbs, anatomy, or facial features.
- Unmotivated wardrobe change.
- Screen-direction reversal.
- Period-inaccurate accessory.

Tag every rejection with one primary cause.

```text
ID_DRIFT
ANATOMY_DRIFT
WARDROBE_DRIFT
JEWELLERY_DRIFT
STATE_DRIFT
RELATIONSHIP_DRIFT
DIRECTION_DRIFT
PERIOD_ERROR
FLOW_MORPH
UNSUPPORTED_ADDITION
```

## Revision Protocol

Preserve the rejected candidate and its prompt.

Identify the earliest failing requirement.

Revise the smallest responsible layer.

Do not add unrelated adjectives after a failure.

Use this order:

1. Correct the packet.
2. Correct the reference role or attachment.
3. Correct one prompt clause.
4. Regenerate a small candidate set.
5. Recheck the same failure category.
6. Escalate to canon only when source material is actually insufficient.

If the model cannot maintain a readable full-body character, split the scene,
change framing, or use an insert.

Do not loosen a permanent lock to accept a pretty result.

## Handoff Package

An approved character-dependent asset hands off:

```text
Asset ID and revision:
Shot ID:
Selected file:
Visible subjects:
Source packet revision:
Reference attachments and roles:
Identity checks passed:
Wardrobe / jewellery checks passed:
Scene-state ledger row:
Incoming and outgoing asset IDs:
Crop-safe notes:
Flow input mode, if animated:
Known limitations:
Approver and date:
```

The editor may crop a frame only if the crop does not hide a required action,
break a permanent identifier, or create a false continuity implication.

## Change Control

This manual may clarify prompt practice.

It may not change a character’s face, age, clothing, jewellery, species, role,
relationship, or timeline.

Propose a canon change in the owning source document first.

Then revise the reference asset, packets, prompt modules, and continuity ledger.

Never repair a canon gap by treating a one-off generation as the new standard.

## Final Operator Check

Before pressing generate, answer:

- Who exactly is this?
- Which source proves that?
- What must make them recognisable?
- What may temporarily change?
- What must carry across the cut?
- What must be absent?
- Can the result be rejected objectively?

If any answer is unclear, do not generate.

## Guiding Principle

The audience should recognise the same familiar people and Dog before the story
asks them to notice the shot.
