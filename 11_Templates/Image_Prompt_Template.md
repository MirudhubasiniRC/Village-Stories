# Image Prompt Template

**Phased rule:** Deliver **image prompt only**. Do not attach animation until the still is approved.

**Authority:** `09_AI_Production_System/21_Clip_Prompt_Formula.md` ·  
`01_Canon/01_Series_Style_Lock/Art_Style.md` ·  
`01_Canon/01_Series_Style_Lock/Color_And_Lighting_Formula.md` (**GENTLE COLOR POP + WARMTH LOCK**) ·  
`01_Canon/01_Series_Style_Lock/Lighting_Style.md`

| Field | Value |
| --- | --- |
| Episode ID | `ep_` |
| Clip / Shot ID | |
| Aspect | 9:16 / **16:9** (board-approved) |
| Status | draft / in_review / approved |
| Revision | r01 |
| Source still lineage | — |
| Attachments | **Default: NONE — write full word locks** (optional M-61 only if needed) |

---

## Mandatory production rules (do not skip)

1. **Self-contained words** — Describe art style, colour, lighting, characters, and location fully in text. Do not rely on attached refs unless the operator explicitly chooses M-61.
2. **DIGITAL anime** — Studio Ghibli-inspired **digital** anime with readable linework + soft cel shading. Reject washed storybook / chalky pastel stills.
3. **GENTLE COLOR POP** — Always paste the colour lock block below (or season variant from `Color_And_Lighting_Formula.md`).
4. **Banned bleach words** — Never use: `soft warm wash` · `muted palette` · `airy high-key` · `pastel` · `dreamy haze` · `overexposed` as desired look.
5. **One frozen moment** — Image prompt = still only.

---

## IMAGE PROMPT — CLIP [Number]

---

**CONTINUITY**

[Clip number] — [Brief description]. [Follows Clip N-1 … OR Opens episode]. [Location/action]. [Season]. [Lighting Family]. [Time of day]. [Light direction]. [Season state]. [Geography]. [Full character appearance if visible — word lock]. [Location per bible — word lock]. [Episode wardrobe carryover if any].

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
| **Shot Type** | |
| **Camera Height** | |
| **Camera Angle** | |
| **Lens Feeling** | [35mm / 50mm / … — warm cinematic depth, Ghibli digital anime rendering] |
| **Composition** | |
| **Depth of Field** | |

**Delivery:** [9:16 vertical · caption-safe **OR** 16:9 landscape — match board]

---

**STYLE — ART LOCK (required every clip)**

```text
Studio Ghibli-inspired DIGITAL anime for the ENTIRE frame —
people, animals, architecture, props, plants, sky = one painted world.
Delicate FINE clean anime LINEWORK with slight variation — readable outlines
on faces, hair, cloth folds, wood, tools.
Painterly DIGITAL watercolor/gouache textures.
Soft CEL-STYLE shading blended with painted digital brushwork —
clear soft form-shadows on faces and clothes (NOT flat chalk wash).
Soft matte finish.
Naturalistic anime proportions; soft rounded faces where appropriate;
grounded expressive eyes approximately 1/5 of face height.
Richly illustrated digital background with atmospheric depth.
Warm nostalgia, softly lit — with CLEAR lively colour (see colour lock).
NOT photoreal · NOT CGI/3D · NOT HDR · NOT heavy manga · NOT chibi ·
NOT washed children’s-book pastel illustration · NOT storybook chalk poster ·
NOT stock-photo background with anime characters pasted on.
```

**Character Rendering (full word locks — required):**

- **[Name]:** [Age · height/scale · skin hex · face · eyes · hair · jewellery · wardrobe colours · expression · pose notes — or "None in frame"]

**Environmental Rendering (full word locks — required):**

- [Architecture · materials · plants · props · period details]

---

**LIGHTING (required)**

**Lighting Family:** **[Warm & Sunlit / Cool & Monsoon]**  
**Time / weather:** [e.g. ~3pm clear afternoon · early morning · monsoon overcast]  
**Light direction:** [per Orientation / sun logic — e.g. soft golden side-kiss]  
**Quality:** Medium-soft Ghibli shadows · controlled highlights · NOT harsh noon glare · NOT night lamps unless board says night

**Season:** **[Summer / Monsoon / Post-Monsoon/Harvest]** — [vegetation / ground / sky cue]

---

**COLOUR — GENTLE COLOR POP + WARMTH LOCK (required every clear outdoor / bright indoor clip)**

*Copy into the prompt. Swap Summer/Monsoon season locks from `Color_And_Lighting_Formula.md` when those seasons are on the board.*

```text
GENTLE COLOR POP + WARMTH LOCK:
Slight warmth — golden side-kiss — NOT white daylight bleach · NOT heavy sunset amber.
BRIGHTNESS: slightly reduced overall — gentle midtones · controlled highlights —
  NOT overbright high-key · NOT blown white · NOT dark/dim.
CONTRAST: medium-soft Ghibli shading — readable forms —
  NOT punchy high contrast · NOT crushed blacks · NOT flat pastel wash.
GREEN: fresh GREENY greens #3F8F3A–#5A9A4A · palm #3D6B35–#4A6B3D —
  NOT pale sage · NOT milky lime · NOT cream-washed foliage.
BLUE: clear BLUEY blue sky #5BA3D9–#7EB8E8 + soft white clouds when sky shows —
  NOT milky white sky wipe · clothing blues stay rich (indigo/navy) not dusty grey-blue.
RED: warm brick REDDY terracotta / maroon / clear red accents #B85C3A–#C97B4A —
  NOT dusty rose · NOT dull brown mud.
YELLOW: clear marigold #E8A020 · clear sunny yellow dress #E8C872 when used —
  NOT creamy pale washed butter.
SKIN: medium-fair golden #E8C89A–#F0D8B0 — NOT porcelain white · NOT pink-pale.
HAIR: natural BLACK per character bible — no brown/auburn highlight drift.
USE: gentle colour pop · fresh greeny greens · clear bluey blue · warm brick reddish ·
  slight warmth · medium-soft contrast · soft Ghibli shading · slightly reduced brightness ·
  colours clear and lively.
AVOID: soft warm wash · muted palette · airy high-key · pastel · dreamy haze ·
  overexposed · bright sunny glare · washed out · dull earth wash.
```

**Atmosphere:**

[Mood — e.g. tender, safe, calm — still with clear pigment]

**Authentic 1990s South Indian village:**

- [Period-correct details; no modern items]

---

**NEGATIVE (required baseline + clip-specific)**

```text
Generic anime / wrong studio look — ONLY Studio Ghibli-inspired DIGITAL anime above
Washed out · muted pastel · soft warm wash · airy high-key · bleached white
Chalky faded storybook watercolor · pale sage leaves/walls
Creamy pale yellow clothing when clear yellow required
Dusty grey-blue clothing when rich indigo/navy required
Porcelain skin · pink-pale anime skin
Oversized shoujo or chibi eyes (grounded ~1/5 face height when people appear)
Heavy manga linework
Exaggerated anime expressions / horror scream faces unless board requires
Western cartoon styling
Hyper-realistic / photoreal / HDR / strong contrast crush
Flat digital vector style
CGI / 3D rendering
Plastic textures / glossy skin
Modern objects (phones, plastic tools, machinery, PVC, synthetic rope, modern fencing)
Oversaturated / neon colors
Text / watermark / signs / labels / typography / thought bubbles
Extra limbs / fingers
Inconsistent character scale
Harsh noon / overexposed / crushed shadows
White blown-out sky
Wrong aspect (must match board 9:16 or 16:9)
Tiling / seam artifacts — horizontal or vertical bands splitting the image
Repeated collage panels · grid lines across faces · duplicated architecture strips
Upscale stitch seams · multipanel storyboard layout in one still
```

**Clip-specific negatives:**

-

---

### Anti-tiling note (16:9 / wide frames)

If Flow produces faint **horizontal or vertical seams** (as if the picture were
glued from strips), reject the still. See `15_Common_Failures.md` → **TOOL-02**.

Do **not** create a separate “position fix” manual. Repair with regenerate /
smaller clear composition / native aspect / seam negatives.

Add to negatives when regenerating:

```text
image tiling · horizontal seam · vertical seam · split composition bands ·
collage panels · grid lines across face · duplicated roof strips · stitch artifact
```

---

**MODULES USED (check)**

- [ ] M-00 Task · [ ] M-01 Source packet · [ ] M-02 Period/dignity · [ ] M-03 Style · [ ] M-04 Negatives
- [ ] M-10 Character · [ ] M-11 State · [ ] M-12 Dog (if any)
- [ ] M-20 Location · [ ] M-21 Time/season/light · [ ] M-22 Background life
- [ ] M-30 Object · [ ] M-31 Object state
- [ ] M-40 Camera · [ ] M-42 Crop safety
- [ ] M-50 Still · [ ] M-62 Validation
- [ ] **Art lock pasted** · [ ] **GENTLE COLOR POP pasted** · [ ] **Full word character locks**
- [ ] **Anti-tiling / seam negatives included** (especially for 16:9 wide frames)
- [ ] **Outdoor house-edge: open neighbourhood + NO compound walls** (see `Village_Neighbourhood.md`)

**Reference attachments (M-61) — optional**

Default: **leave empty** (words-only). Fill only if operator chooses attachments.

| File | Role |
| --- | --- |
| — | — |

---

**Handoff:** When still approved → Animation Prompt Template + Voice/Audio for this clip.

**QA before send:** If the still looks washed, pastel, or soft-storybook, reject and regen with stronger DIGITAL anime line/cel language + GENTLE COLOR POP — do not “fix” by attaching refs unless necessary. Outdoor house-edge stills: reject large compound walls; require neighbour houses + greens.
