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

Studio Ghibli-inspired anime aesthetic — soft, warm, emotionally resonant.
Gentle expressive designs, naturalistic proportions, grounded eyes ~1/5 face
height. Delicate fine linework. Painterly digital watercolor/gouache. Soft
matte finish.

**Character Rendering (Per Character Bible):**

- **[Name]:** [Full description — or "None in frame" for empty shots]

**Environmental Rendering (Per World Layout Bible):**

- [Location, architecture, vegetation, props, atmosphere]

**Lighting:** **[Warm & Sunlit / Cool & Monsoon] — [time/weather].** [Direction,
highlights, shadows]

**Light direction:** [Per Global Orientation & Sun Logic]

**Season:** **[Summer / Monsoon / Post-Monsoon/Harvest]** — [vegetation, water,
ground]

**Colors (Ghibli-inspired):** [Hex list — never neon/HDR]

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
Oversized shoujo or chibi eyes (grounded ~1/5 face height when people appear)
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
| **Pacing:** Normal speed — natural physical timing, not rushed. | `not slow`, `slowly`, `languid`, `leisurely` as pacing labels |

Describe *what* moves and *how much* — not “slowly.” Example: “one partial wing
open (~30%) then close over ~2 seconds” instead of “wings slowly open.”

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
- PRESERVE colour palette: [key colours]
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

**Pacing:** Normal speed — natural physical timing, not rushed.
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
- `08_Production/06_Image_Prompt_Workflow.md`
- `07_Episode_System/09_ASMR_Placement.md`
- `01_Canon/01_Series_Style_Lock/Art_Style.md`

Episode clip lists: `10_Episodes/[id]/04_Generation/episode-[id]__clip-prompt-workflow__*.md`
