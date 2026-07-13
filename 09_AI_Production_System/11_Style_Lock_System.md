# Style Lock System

## Permanent Purpose

This is the operating system that keeps every Village Stories image, keyframe,
Google Flow clip, repair, thumbnail candidate, and selected asset inside one
original visual identity.

It converts the series art direction into small, traceable prompt locks. It
does not ask a model to “make it cinematic” or to copy a recognizable outside
work. It specifies the visible properties that make Village Stories itself:
original premium cinematic anime, semi-realistic South Indian people and
anatomy, painterly digital rendering, restrained organic linework, natural
light, lived-in early-1990s rural Tamil environments, and quiet human dignity.

The lock is a production control, not a decorative paragraph. It prevents style
drift between generations while leaving the approved scene its own time,
weather, action, and emotional weight.

## Authority, Scope, And Limits

This system inherits style facts; it creates no canon and does not overrule an
approved episode, character, location, object, camera, or continuity decision.

```text
Current approved production decision
↓
01_Canon/ — series style, timeline, continuity, light, and camera philosophy
↓
02_World/ · 03_Characters/ · 04_Objects/ · 05_Research/
↓
06_Story_Engine/ — story truth and emotional limits
↓
Approved episode brief, script, storyboard, and scene-state ledger
↓
07_Episode_System/ · 08_Production/
↓
09_AI_Production_System/01_Master_Workflow.md
↓
This Style Lock System and applicable master prompt
↓
Reference attachments, tool settings, candidate, selected asset
```

The higher applicable source wins. Do not average contradictory instructions,
silently replace a source fact with a pleasing candidate, or treat an accepted
candidate as new style canon.

This system is the operational authority for:

- selecting the smallest applicable style packet;
- separating permanent style facts from scene facts;
- wording an original, non-imitative visual-style instruction;
- assigning reference images a limited role;
- reviewing style fidelity in stills and Flow clips;
- diagnosing whether a failure is style, canon, source-image, camera, or tool
  drift; and
- recording and approving a style-related revision.

It is not the authority for character appearance, wardrobe, location layout,
object truth, story performance, framing, screen direction, or camera
movement. Use the relevant source for those decisions. In particular,
`19_Camera_Direction_Bible.md` governs camera direction and
`20_Camera_Movement_Bible.md` governs camera movement.

## Non-Negotiable Series Identity

Every asset must retain all applicable parts of this identity:

```text
Original premium cinematic anime for a warm, restrained slice-of-life series.
Semi-realistic South Indian people with believable anatomy, natural scale,
specific facial structure, grounded posture, and subtle expression.
Soft painterly hand-painted digital rendering with layered natural colour,
material texture, gentle global illumination, and restrained organic linework.
Detailed, culturally accurate, lived-in early-1990s rural Tamil Nadu
environments. Natural atmosphere and story-serving composition. Ordinary life
is observed with dignity, never turned into spectacle.
```

This is a description of Village Stories’ original visual properties. Never
name, invoke, compare to, imitate, or request “in the style of” a studio,
artist, animator, franchise, film, game, publisher, or other external
property. A named reference is not acceptable shorthand, even if an operator
believes it describes a desirable rendering trait.

## The Style-Lock Model

Classify every visible style instruction before prompt assembly.

| Class | Meaning | Prompt treatment |
| --- | --- | --- |
| HARD STYLE LOCK | Permanent identity that every asset must preserve. | Include in the compact style core. |
| CONTEXTUAL STYLE LOCK | Permanent identity made specific by approved time, weather, location, or format. | Include only when relevant to the shot. |
| SCENE FACT | An approved, changing fact such as rain, dusk, cooking smoke, or mud. | Put in the scene layer, not the permanent style core. |
| REFERENCE ROLE | A file that controls one assigned visual fact. | Attach and label its limited role. |
| NEGATIVE | A known failure or prohibited visual treatment. | State when it protects a real risk. |
| OPEN | Required information with no source authority. | Name the owner and hold the affected asset. |

Do not turn all style information into an enormous repeated prompt. A compact,
complete lock is more reliable than an overloaded list. Load only information
that constrains the proposed shot.

## Permanent Style Core

Use the following core in every image-generation prompt, then add contextual
locks and scene-specific facts:

```text
ORIGINAL STYLE LOCK — Original premium cinematic anime; semi-realistic South
Indian people with believable anatomy, natural proportions, grounded posture,
and subtle expressions; soft painterly hand-painted digital rendering; layered
natural colour and material texture; restrained organic linework; gentle
natural global illumination; detailed, culturally accurate, lived-in rural
Tamil Nadu environment; warm, restrained slice-of-life observation. Preserve
the approved scene’s physical light, weather, and material state. Do not imitate
or name any studio, artist, franchise, film, or external property.
```

Do not add every clause when it is visibly irrelevant, but never remove the
originality, South Indian anatomy, painterly-rendering, and no-imitation
requirements. A close hand insert still needs the rendering and material
language; an extreme wide still needs the environment, atmosphere, and
non-spectacle requirements.

## Contextual Style Locks

### People And Anatomy

People must look like the documented individuals and community, not generic
anime types or polished fashion models.

- Preserve age, body build, skin tone, hair, posture, clothing logic, work
  marks, and relative scale from the character sources.
- Use natural South Indian facial features and varied, believable human
  proportions. Do not enlarge eyes, shrink noses, lighten skin, narrow bodies,
  alter age, or use chibi, doll-like, mannequin, or hyper-glamorous anatomy.
- Let farm work, cooking, walking, sitting, and handling tools carry ordinary
  weight and balance. Hands, feet, and joints must remain physically possible.
- Expressions are restrained and legible. Do not substitute exaggerated anime
  reactions, melodramatic tears, romantic glamour, panic, menace, or comic
  distortion for an approved beat.
- Skin, hair, fabric, wood, metal, food, and earth retain tactile, non-plastic
  material variation. Do not apply a beauty filter or synthetic gloss.

### Rendering And Linework

Painterly does not mean blurry, unfinished, or inconsistent.

- Use soft hand-painted digital brush transitions and layered natural colour.
- Keep edges selectively clear where a face, hand, tool, food state, or
  architectural boundary must read; let distant atmosphere soften naturally.
- Use refined organic linework only where it supports form and readability.
  Avoid thick uniform comic outlines, contour halos, sketch residue, and
  vector-flat treatment.
- Keep dimensional light and material texture. Reject plastic CGI surfaces,
  photographic skin pasted into illustration, heavy cel shading, glossy
  gradients, airbrushed faces, and low-detail generic anime.
- Detail follows story importance. A wide view can carry rich place detail
  without becoming clutter; a close view can retain tactile detail without
  fetishizing a face or object.

### Colour, Light, And Atmosphere

Colour must arise from documented light, weather, season, materials, and
emotion—not from a global “cinematic” filter.

- Use natural, restrained colour relationships, gentle contrast, and soft
  global illumination.
- Preserve the approved east-morning and west-evening light relationships,
  season, weather, wetness, smoke, shadow, and time continuity.
- Monsoon is cool, diffused, wet, and inviting—not blue-black disaster light,
  neon rain, or storm spectacle.
- Warmth may come from sun, lamplight where period-supported, earth, fabric,
  food, or family intimacy. It must not become orange-teal grading, golden
  luxury advertising, or overexposed haze.
- Atmospheric depth must preserve usable geography. Do not hide a required
  landmark, person, action, or object in bloom, fog, darkness, flare, or
  shallow focus.

### World Specificity And Dignity

The setting is early-1990s rural Tamil Nadu, practical and culturally specific.

- Preserve approved architecture, paths, fields, utilities, vegetation,
  cookware, textiles, tools, infrastructure, and domestic wear.
- The village is lived in, useful, and beautiful through truth—not an exotic
  postcard, poverty spectacle, tourist tableau, fantasy village, or empty
  rustic backdrop.
- Exclude modern screens, mobile phones, internet equipment, contemporary
  branding, current packaging, LED fixtures, modern appliances, current
  vehicles, urban infrastructure, and unsupported fashion.
- Do not add symbolic animals, decorative crowds, festival decoration, luxury
  polish, ruin, grime, or hardship merely to create a mood.
- Preserve ordinary life’s dignity. Do not manufacture danger, surveillance,
  humiliation, eroticization, heroism, violence, child endangerment, animal
  distress, disaster, or melodrama through colour, rendering, expression,
  composition, or effects.

## Prompt Assembly Procedure

### 1. Confirm the production brief

Before choosing a style packet, verify the shot’s approved purpose, current
scene state, location, time, weather, delivery format, and adjacent-shot
handoff. If a visible fact is `OPEN`, record its owner and do not generate a
recurring or continuity-critical asset from invention.

### 2. Build the source manifest

For every lock or reference loaded, record:

```text
Source path:
Source heading or asset revision:
Applied fact:
Class: HARD STYLE LOCK / CONTEXTUAL STYLE LOCK / SCENE FACT / REFERENCE /
NEGATIVE / OPEN:
Why this shot needs it:
Risk if omitted:
```

### 3. Assemble in stable order

Use this order so permanent identity is not confused with shot direction:

```text
1. Approved scene moment and required readable evidence
2. Location, period, season, time, weather, and material state
3. Character / object / location locks and approved references
4. Camera direction from 19_Camera_Direction_Bible.md
5. Original Style Lock core and relevant contextual locks
6. Scene-specific action, expression, and atmosphere boundary
7. Negative constraints and output requirements
```

For Flow, preserve the source still’s style. The animation prompt names only
style facts at risk during motion—such as painterly material continuity, wet
surface state, skin tone, jewellery, fabric texture, smoke, rain, or light—and
does not redescribe the entire image.

### 4. Keep factual layers separate

Do not write “golden painterly monsoon magic” when the scene is an overcast,
wet morning. Write the factual light and weather in the scene layer, then use
the style layer to control how those facts render.

Correct:

```text
Scene: overcast monsoon daylight, rain beyond the doorway, wet red-earth yard.
Style: soft painterly rendering, cool diffused natural illumination, tactile wet
materials, restrained colour, no disaster treatment.
```

Incorrect:

```text
Make it a dramatic magical monsoon anime scene.
```

## Reference-Image Authority

A reference controls only the role explicitly assigned to it. It never grants
permission to import its overall style, camera, wardrobe, background, lighting,
or any unassigned feature.

| Reference role | May control | Must not silently control |
| --- | --- | --- |
| CHARACTER_IDENTITY | Documented individual face, build, hair, and stable identity. | Pose, new costume, background, mood, or rendering style. |
| LOCATION_LAYOUT | Approved landmarks, materials, route, and spatial relations. | New people, event, camera side, or time of day. |
| OBJECT_IDENTITY | Approved object form and material logic. | New story use, ownership, or placement. |
| SOURCE_FRAME | Exact approved visual state for a repair or Flow start/end. | A new camera decision or unapproved continuation. |
| STYLE_CALIBRATION | Only an internally approved Village Stories asset’s texture, value range, and finish consistency. | New canon, external imitation, or scene facts. |

Never use an outside studio, artist, film, franchise, or generated image of
unknown provenance as a style reference. An internally approved selected asset
may be used as `STYLE_CALIBRATION` only when its shot record confirms it is
canon-safe and the new shot shares compatible conditions.

## Copy-Ready Prompt Modules

### Still Image Style Module

```text
ORIGINAL STYLE LOCK — Original premium cinematic anime, not an imitation of any
named studio, artist, film, franchise, or external property. Semi-realistic
South Indian people with believable anatomy, natural proportions, grounded
posture, and subtle expression. Soft painterly hand-painted digital rendering,
layered natural colour and material texture, restrained organic linework,
gentle natural global illumination, and detailed culturally accurate,
lived-in early-1990s rural Tamil Nadu. Keep the mood warm and restrained;
preserve documentary truth over spectacle.
```

### Flow Style Preservation Module

```text
STYLE PRESERVATION — Continue the approved source image’s original premium
cinematic anime rendering. Preserve the same semi-realistic South Indian
anatomy, face and skin tone, painterly material texture, restrained organic
linework, natural illumination, colour relationship, weather state, and
period-correct environment. Do not change rendering style, introduce plastic
CGI or heavy cel shading, beautify faces, alter age or anatomy, or imitate any
named external property.
```

### Scene-Specific Negative Module

Add only relevant risks:

```text
No chibi or exaggerated anime proportions; no hyper-real photographic face; no
glossy plastic skin or CGI; no heavy cel shading, thick comic outline,
vector-flat treatment, neon grading, orange-teal filter, fantasy glow,
poverty spectacle, generic village, modern item, external-property imitation,
or drama not in the approved scene.
```

## Examples

### Correct: image packet excerpt

```text
Moment: Mother rolls dough at the documented kitchen board on a wet monsoon
morning; hands, board, and earthen vessel must remain readable.

Camera Direction: [approved direction-only module from Document 19].

ORIGINAL STYLE LOCK — Original premium cinematic anime, not an imitation of a
named external property. Semi-realistic South Indian anatomy and natural,
grounded posture; soft painterly hand-painted digital rendering; tactile dough,
wood, brass, cotton, and damp-earth texture; restrained linework; cool
diffused monsoon daylight with warm interior bounce; lived-in, period-correct
rural Tamil kitchen. Calm, dignified domestic observation.

Negative: no glamour pose, plastic CGI, thick outlines, blue-black storm
treatment, modern packaging, exaggerated steam, or unapproved camera effect.
```

### Correct: Flow packet excerpt

```text
Source Frame: E03_S02_SH04_keyframe_v03, approved.
STYLE PRESERVATION — Continue the approved source image’s painterly materials,
Mother’s natural South Indian anatomy and identity, cool diffused monsoon
light, wet yard beyond the doorway, and restrained colour. No visual-style
change, face beautification, object transformation, or named-style imitation.
```

### Incorrect

```text
Make it look like [named studio], cinematic, beautiful and emotional.
```

This is prohibited because it delegates the identity to an external property,
does not name the visible production qualities, and offers no protection
against generic or melodramatic output.

## QA Gates

### Pre-Generation Style QA

Approve prompt submission only when every applicable answer is yes:

```text
[ ] The source manifest identifies the applicable style authority.
[ ] The original premium cinematic anime core is present.
[ ] The prompt explicitly protects semi-realistic South Indian anatomy.
[ ] Painterly rendering, organic linework, natural light, and material texture
    are described as visible properties, not a named imitation.
[ ] The current time, weather, location, and scene state are separate facts,
    not a vague mood filter.
[ ] Period and cultural specificity are loaded from approved sources.
[ ] Character, location, object, and camera decisions remain with their own
    authorities.
[ ] References have a declared role and do not silently redefine style.
[ ] The relevant negatives address known failure risk without replacing facts.
[ ] Every OPEN fact has a named owner and resolution path.
```

### Candidate Style QA

Review at full frame and at intended delivery crop. Reject a candidate if it:

- imitates or visibly resembles a named external property requested in error;
- changes the original painterly, semi-realistic series identity;
- makes South Indian people generic, lightened, glamourized, childlike,
  photographic, plastic, or anatomically implausible;
- uses thick comic outlines, heavy cel shading, flat vector treatment, glossy
  CGI, artificial beauty filtering, or vague low-detail anime;
- changes period, material condition, cultural specificity, season, weather, or
  light to create a prettier image;
- turns ordinary life into poverty spectacle, fantasy, disaster, threat, or
  melodrama;
- hides required story evidence behind atmospheric effects; or
- creates style mismatch with the approved incoming or outgoing asset.

### Acceptance Standard

Approve only when the asset is recognizably Village Stories without named
comparison, serves the approved moment, retains the pertinent locks, and cuts
cleanly with its neighbours. “Attractive” is not an acceptance reason.

## Revision And Escalation

Revise diagnostically. Change the smallest responsible component and preserve
all approved components.

| Observed failure | Likely owner | First corrective action |
| --- | --- | --- |
| Generic anime or flat rendering | Style packet | Strengthen rendering, material, and environment lock; retain scene facts. |
| Altered face, age, body, or jewellery | Character source / reference packet | Reattach correct identity reference and character lock; do not solve with style words. |
| Modern or generic environment | World/location packet | Correct source facts and reference role; do not add indiscriminate “village” adjectives. |
| Weather or light changes | Scene ledger / lighting source | Restore factual time, orientation, and material state. |
| Overdramatic image | Scene intention, camera, or style boundary | Remove spectacle language; return camera choices to Document 19. |
| Drift appears only in Flow | Source still / Flow preservation | Use a direction- and style-approved source still; reduce the motion scope. |
| Prompt requires named imitation to work | Prompt design | Stop; rewrite in original visible properties. Do not submit. |

Use this record for every style revision:

```text
Episode / scene / shot ID:
Asset and prompt revision:
Candidate ID:
Observed defect:
Evidence frame / timestamp:
Defect class: style / identity / world / light / camera / motion / source:
Highest applicable authority:
Hypothesis:
One component changed:
Components retained:
Reference attachments and roles:
Reviewer and decision:
Downstream assets needing review:
```

If a correction changes a selected source still, recurring visual precedent, or
an asset used by Flow, assess every dependent prompt and edit. Escalate a
contradiction to the Canon and Continuity Lead; do not normalize it through
repeated generations.

## Handoff And Archive

The selected asset’s handoff must state:

```text
Asset ID / revision / status:
Applied Style Lock version or source headings:
Scene-specific contextual style facts:
References and assigned roles:
Prompt text and relevant negative block:
Approved source still(s), if any:
QA reviewer, date, and decision:
Known limitations or excluded uses:
Incoming and outgoing visual continuity notes:
```

Archive the selected asset, prompt, source manifest, attachment list, candidate
decision, and revision record together. A later operator must be able to learn
why this asset matches the series without guessing from the pixels.

## Final Operating Rule

Describe and preserve the original visible properties of Village Stories. Do
not borrow a visual identity from elsewhere, and do not let a model’s default
replace cultural truth, believable South Indian anatomy, painterly material
presence, or calm human dignity.
