# Clip Prompt Formula

## Purpose

This is the **mandatory production formula** for every episode clip prompt
delivered to Google Flow. Image, Animation, and Audio prompts must use the
titles, sections, and structure defined here.

Additional project-specific detail may be added, but **these sections are
required**.

Phased delivery: see `08_Production/06_Image_Prompt_Workflow.md` — **Image
prompt only** per clip until still approved; then **Animation + Audio** for
that clip.

**Dialogue:** when the approved script assigns speech, include a **Dialogue**
subsection inside the **Audio / ASMR Prompt** (not a separate voice file).

## Google Flow Self-Contained Colour Rule (approved 2026-07-17)

Every prompt delivered to Google Flow must describe its complete colour and
lighting treatment **in words inside that prompt**.

Never write only:

- “match the approved palette”;
- “use the reference palette”;
- “same colours as canon”;
- “see `Color_And_Lighting_Formula.md`.”

Flow cannot inspect project documentation or an unattached palette. For every
image prompt, explicitly state:

1. dominant environment colours;
2. character skin and clothing colours;
3. architecture and object colours;
4. light temperature and direction;
5. shadow colour and softness;
6. saturation, brightness, and contrast;
7. forbidden colour casts or grading.

Animation prompts must also repeat the key colours in words, even when a source
image is attached. References support identity and continuity; they never
replace verbal colour instructions.

---

## Prompt titles

| Prompt Type | Title Format |
| --- | --- |
| **Image Prompt** | `IMAGE PROMPT — CLIP [Number]` |
| **Image Prompt (Revised)** | `IMAGE PROMPT — CLIP [Number] (REVISED — [Reason])` |
| **Image Prompt (Regenerated)** | `IMAGE PROMPT — CLIP [Number] (REGENERATED — [Character/Reason])` |
| **Animation Prompt** | `CLIP [Number] — Animation Prompt` |
| **Animation Prompt (Corrected)** | `CLIP [Number] — Animation Prompt (CORRECTED — [Reason])` |
| **Audio / ASMR Prompt** | `CLIP [Number] — Audio / ASMR Prompt` |

---

## 1. Image prompt formula

```markdown
## IMAGE PROMPT — CLIP [Number]

---

**CONTINUITY**

[Clip number] — [Brief description of this clip]. [Follows Clip [N-1] (ending
frame description) OR "Opens episode — no prior clip"]. [Location/action].
[Season]. [Lighting Family]. [Light direction]. [Season state]. [Geography per
Orientation / location bible]. [Character appearance if visible]. [Location
per location bible]. [Neighbour continuity if applicable].

---

**SUBJECT**

[Main visual subject — what the viewer sees]

---

**ACTION**

[Exact frozen cinematic moment — what is happening]

---

**CAMERA**

| Element | Specification |
| --- | --- |
| **Shot Type** | [Establishing / Wide / Medium / MCU / Close-up / Macro] |
| **Camera Height** | [Eye-level / Low / High / Elevated / Ground] |
| **Camera Angle** | [Facing / 3/4 / Profile / OTS / Straight-on] |
| **Lens Feeling** | [35mm / 50mm / Telephoto macro — warm cinematic depth, Ghibli rendering] |
| **Composition** | [Foreground, midground, background spatial relationships] |
| **Depth of Field** | [Deep / Medium / Shallow — atmospheric haze where appropriate] |

**Delivery:** 9:16 vertical portrait — design for Shorts; caption-safe margins.

---

**STYLE**

Studio Ghibli–adjacent 2.5D polished digital anime (CANON-2026-013) — soft, warm,
emotionally resonant. Clean 2D characters; soft volumetric props/food/animals.
Mother: slim oval (NOT chubby), LARGE soft-almond eyes ~1/4 face height, long
anime lashes, soft pink blush, LEFT-chin mole (CANON-2026-012/013); Father/kids:
grounded ~1/5 until approved. Delicate fine linework. Soft matte–gloss hybrid.

**Character Rendering (Per Character Bible):**

- **[Name]:** [Full description — or "None in frame" for empty shots]

**Environmental Rendering (Per World Layout Bible):**

- [Location, architecture, vegetation, props, atmosphere]

**Lighting:** **[Warm & Sunlit / Cool & Monsoon] — [time/weather].** [Direction,
highlights, shadows]

**Light direction:** [Per Global Orientation & Sun Logic]

**Season:** **[Summer / Monsoon / Post-Monsoon/Harvest]** — [vegetation, water,
ground]

**Colours — write every value in words for Flow:** [Dominant foliage / earth /
wall / roof / water colours. Character skin and garment colours. Light
temperature and direction. Shadow colour and softness. Saturation, brightness,
and contrast. Explicitly forbid unwanted blue, orange, grey, neon, HDR, or
washed-out grading.]

**Atmosphere:** [Mood, emotional quality]

**Authentic 1990s South Indian village (per World / Location bible):**

- [Period-correct details; no modern items]

---

**NEGATIVE**

[Standard negatives per series — see template in this doc § Standard image negatives]

**[Clip-specific negatives]**

---

**Handoff:** When still approved, request Animation + Audio for this clip.
```

### Standard image negatives (include in every image prompt)

```text
Generic anime style — ONLY Studio Ghibli-inspired style described above
Oversized shoujo or chibi black-dot eyes with no iris (Mother may use LARGE soft-almond ~1/4 face height WITH iris + catchlights per CANON-2026-012; Father/kids ~1/5)
Heavy manga linework (soft delicate lines)
Exaggerated anime expressions
Western cartoon styling
Hyper-realistic rendering
Flat digital vector style
CGI / 3D rendering
Plastic textures / glossy skin
Modern objects (plastic tools, machinery, PVC, synthetic rope, modern fencing)
Oversaturated / neon colors
Photorealistic / HDR / strong contrast
Text / watermark / signs / labels / typography
Extra limbs / fingers
Inconsistent character scale
Harsh noon / overexposed / crushed shadows
White blown-out sky (Post-Monsoon outdoor should keep soft blue sky)
Horizontal composition when 9:16 vertical required
```

---

## 2. Animation prompt formula

### Motion speed standard (default)

**Use Normal Speed on every clip** unless the episode board explicitly documents
a rare exception (e.g. approved time-lapse insert).

| Write | Do not write in animation prompts |
| --- | --- |
| **Normal Speed** on Character / Environment / Micro motion blocks | `slow`, `too slow`, `very slow`, `slower`, `Fastly Normal Speed` |
| **Pacing:** Normal speed — natural physical timing. Editorial pace is fast
  (Growth Sprint); do not write “slowly / leisurely.” | `not slow`, `slowly`,
  `languid`, `leisurely` as pacing labels |

Describe *what* moves and *how much* — not “slowly.” Example: “one partial wing
open (~30%) then close over ~2 seconds” instead of “wings slowly open.”

**Sudden rain face (CANON-2026-006):** on a dedicated reaction clip, write the
loud face explicitly — e.g. “eyes snap wide, brows up, mouth opens in gasp” —
never “looks calmly at the rain.”

Camera movement speed follows `20_Camera_Movement_Bible.md` when the camera is
not locked — that is separate from character/environment motion speed.

```markdown
## CLIP [Number] — Animation Prompt

**SERIES STYLE LOCK — APPLY TO ALL ANIMATIONS**

STYLE LOCK INSTRUCTIONS:
- PRESERVE exact visual style, characters, and environment from source image.
- DO NOT reinterpret, redesign, or "improve" characters, clothing, environments, props.
- DO NOT change skin tone, hair, facial features, or clothing colours.
- DO NOT add or remove objects, furniture, or architectural details.
- PRESERVE Studio Ghibli-inspired anime aesthetic — painterly watercolor/gouache.
- PRESERVE lighting family and light direction from source image.
- PRESERVE [character] exact appearance: [description]
- PRESERVE [location] environment: [description]
- PRESERVE these colours exactly: [repeat key environment, skin, clothing,
  architecture, object, light, and shadow colours in words]
- DO NOT drift toward generic anime, Western cartoon, or photorealism.
- DO NOT change proportions, relative scale, or anatomy.
- FOLLOW source image exactly — animate only required natural motion.

---

**Input Specification:**
- **Input Type:** Single Image (or Two Images when approved)
- **Number of Images:** [1 or 2]
- **Source Image:** Clip [Number] ([brief description])

**Animation Source:**
- **Mode:** Single Image
- **Camera Behavior:** [Static Camera / approved bounded move per Camera Movement Bible]
- **Camera Intent:** [Why — what viewer should notice]

**Duration:** [X seconds] — reference target from episode beat sheet / shot list; set by smallest readable action (see `05_Master_Animation_Prompt.md` § Duration)

**Character Motion (Normal Speed):**
- [Character] — [motion — describe amount and timing, not “slowly”]
- [Or NONE]

**Environment Motion (Normal Speed):**
- [Element] — [motion]

**Micro Motion (Normal Speed):**
- [Element] — [motion]

**Motion Priority:** [Ordered list]

**End Frame:** Static — [final frame description]

**Quality Lock:** Avoid morphing, melting, stretching, flicker, double limbs, face
distortion, identity drift. Maintain [character/location] consistency.

**Pacing:** Normal speed — natural physical timing. Keep editorial selects short
(Growth Sprint); do not describe leisurely motion.
```

---

## 3. Audio / ASMR prompt formula

```markdown
## CLIP [Number] — Audio / ASMR Prompt

**Primary Sounds (Visible Actions):**
- [Sound] — [description] (XX–XX% volume)

**Environmental Ambience (Per [Season] — [Weather]):**
- **[Birds / Breeze / Rain / Village / etc.]:** [description] (XX–XX% volume)

**Dialogue (only when approved script assigns speech to this clip):**
- **Speaker:** [Character]
- **Line:** "[Exact approved words]"
- **Delivery:** [wondering / laughing / soft / etc.]
- **Timing:** [start–end seconds within clip]
- **Mix:** Dialogue foreground; duck ambience 30–50% under speech

**Audio Mix Priority:** [Foreground hierarchy]

**Continuous Ambience:** [Maintain / crossfade from Clip N-1 / fresh start]

**No:** Music, Artificial effects, [unapproved dialogue if none assigned]

---

**Handoff:** Proceed to next clip image prompt when audio approved or at edit.
```

---

## 4. Continuity lock formula (when needed)

```markdown
**CONTINUITY LOCK — CLIP [Previous] → CLIP [Current]**

- Clip [Previous] ends with [description].
- Clip [Current] begins with [description].
- SAME location: [Name].
- SAME lighting: [Lighting Family].
- SAME season: [Season].
- [RAIN / weather note].
- SAME [Character] appearance: [brief].
- CONTINUOUS ACTION: [if applicable].
- NO JUMP CUTS — seamless transition.
```

---

## Quick reference

| Prompt Type | Required sections |
| --- | --- |
| **Image** | CONTINUITY → SUBJECT → ACTION → CAMERA → STYLE → NEGATIVE |
| **Animation** | STYLE LOCK → INPUT SPEC → ANIMATION SOURCE → **DURATION** → MOTION (**Normal Speed**) → END FRAME → QUALITY LOCK → **PACING: Normal speed** |
| **Audio** | PRIMARY SOUNDS → ENVIRONMENTAL AMBIENCE → DIALOGUE (if any) → MIX → CONTINUOUS → NO |
| **Continuity Lock** | Previous → Current → SAME × N → CONTINUOUS ACTION → NO JUMP CUTS |

---

## Authority chain

This formula implements:

- `04_Master_Image_Prompt.md`
- `05_Master_Animation_Prompt.md`
- `01_Canon/01_Series_Style_Lock/Art_Style.md`
- `01_Canon/01_Series_Style_Lock/Color_And_Lighting_Formula.md`
- `08_Production/06_Image_Prompt_Workflow.md`
- `07_Episode_System/09_ASMR_Placement.md`

Episode clip lists: `10_Episodes/[id]/04_Generation/episode-[id]__clip-prompt-workflow__*.md`
