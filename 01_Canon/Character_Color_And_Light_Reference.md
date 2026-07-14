# Character Color & Light Reference

## Purpose

This document locks **character skin tones**, **wardrobe colour hex values**,
and **prompt lighting/colour blocks** so they stay consistent with:

- `01_Canon/01_Series_Style_Lock/Lighting_Style.md` — **Warm & Sunlit** and
  **Cool & Monsoon** lighting families
- `01_Canon/01_Series_Style_Lock/Color_Language.md` — seasonal and emotional
  colour philosophy
- `02_World/Geography/Orientation.md` — **Global Orientation & Sun Logic**

Use this document alongside `01_Canon/Relative_Height_And_Scale.md` for
multi-character shots.

---

# Lighting Families (series-wide)

Every scene uses **one** lighting family. Never mix families in a single frame
unless a documented weather transition is shown.

## Warm & Sunlit

Use for: clear mornings, sunny afternoons, golden evenings, dry summer, harvest
days, kitchen firelight at dusk blending with western window glow.

Prompt label: `Lighting: Warm & Sunlit`

Characteristics: soft golden sunlight, warm bounce, gentle contrast, rich warmth,
comfortable atmosphere — never harsh noon blast or neon saturation. Post-Monsoon
outdoor: soft blue sky (not blown white); **fresh saturated greens** — banana /
garden / palm (`#5A9A4A`, `#4F8F3C`, `#4A6B3D`), never pale sage or cream-washed
foliage (`Color_And_Lighting_Formula.md` GREENS LOCK). Art look follows
`Art_Style.md`.

## Cool & Monsoon

Use for: rain, overcast sky, misty mornings, cloud-covered afternoons, monsoon
evenings.

Prompt label: `Lighting: Cool & Monsoon`

Characteristics: soft diffused light, grey-blue ambient, low contrast, moist
atmosphere — still emotionally inviting, never cold or lifeless.

---

# Global Orientation & Sun Logic

Permanent compass (never reverse across adjacent shots):

- **East** — sunrise, paddy fields, pond; morning light enters from east.
- **West** — Family House, Kitchen, rear yard; **evening / sunset light from west**.
- Kitchen large window: **west-facing** — last orange-purple dusk through window;
  clay-stove firelight from within.

Prompt snippet when kitchen or west rooms appear:

```text
Light direction: fading warm western light through west-facing window, blending
with warm orange clay-stove glow; consistent with Global Orientation & Sun Logic.
```

---

# Character Skin Tone Palette

Soft Ghibli-style painterly shading on all skin. Subtle warm blush on cheeks
during emotional moments. Never glossy plastic skin.

## Mother, Elder Brother, Younger Daughter (shared family range)

**Medium-fair with warm golden undertones:**

- Warm-lit: `#E8C89A` · `#F0D8B0`
- Cool-lit (monsoon): shift toward `#DDBF8A` · `#D0B880`

## Father

**Medium-to-fair with warm golden undertones** — healthy sun-kissed, slightly
deeper than Mother in warm light:

- Warm-lit: `#E8C89A` · `#E0C890` · `#DDBF8A`
- Cool-lit: `#DDBF8A` · `#D0B880` · `#C8B078`

---

# Wardrobe Colour Hex (Ghibli-inspired, never neon)

## Mother — cotton saree palette

| Colour | Hex | Use |
| --- | --- | --- |
| Maroon | `#7A1F2B` | Everyday / festival |
| Mustard | `#D4A017` | Everyday / kitchen |
| Dark green | `#3A6B3A` | Everyday / garden |
| Cream | `#F5E6C8` | Morning / calm scenes |
| Indigo | `#2A3A5A` | Cooler / evening |

Glass bangles: coordinating green, red, gold — never oversized.

## Father

| Item | Hex / note |
| --- | --- |
| White / cream veshti | `#F5E6C8` |
| Light shirt | pale cream, light blue, soft white |
| Checked lungi | muted village checks — not neon |

## Elder Brother — pavadai & blouse

Soft yellow `#E8C872` · warm green `#5A9A4A` · soft pink `#D48A8A` · cream `#F5E6C8`

## Younger Daughter — shorts & shirt

Brown, navy, cream shorts; checked shirt (red/white, blue/white, green/yellow)

---

# Environment Colour Anchors (Kitchen — approved reference)

| Element | Hex / tone |
| --- | --- |
| Terracotta roof / warm earth | `#C97B4A` |
| Red oxide floor | warm terracotta-red, slightly worn |
| Cream kitchen walls | `#F5E6C8` |
| Brass utensils | warm metallic gold — soft sheen, not artificial shine |
| Coffee / decoction | golden coffee-brown |
| Clay-stove ember glow | soft ember-orange |

---

# Prompt Blocks (copy-ready)

## STYLE — lighting + colour header

```text
### STYLE
Studio Ghibli-inspired anime aesthetic — soft, warm, emotionally resonant.
Gentle expressive character design, naturalistic anime proportions, grounded
eyes ~1/5 face height. Delicate fine linework, painterly watercolor and gouache
textures, soft matte finish.

Lighting Family: [Warm & Sunlit | Cool & Monsoon]
Light direction: [per Global Orientation & Sun Logic — e.g. western dusk through
kitchen window + clay-stove glow]
Season: [Summer | Monsoon | Post-Monsoon/Harvest]
```

## COLORS block

```text
### COLORS
Skin: [character hex from table above, adjusted for lighting family]
Wardrobe: [approved saree/veshti hex]
Environment: [location anchors — e.g. terracotta #C97B4A, cream #F5E6C8, brass gold]
Never oversaturated, neon, HDR, or Bollywood colour grading.
```

## NEGATIVE — colour & light (append to character negatives)

```text
oversaturated/neon colors, photorealistic HDR, harsh noon lighting, crushed
shadows, glossy plastic skin, Bollywood saturation, wrong sun direction
```

---

# Cross-Scene Consistency Rules

Always maintain:

- One lighting family per shot.
- Sun direction consistent with `Lighting_Style.md` orientation.
- Character skin hex range per lighting family — do not jump between warm-lit
  and cool-lit skin in adjacent cuts without weather motivation.
- Wardrobe colours from approved hex palette or documented saree canon.
- Environment colours grounded in `Color_Language.md` — nature, architecture,
  people, atmosphere hierarchy.

Never:

- Apply cool monsoon grey-blue grade to a Warm & Sunlit story beat without rain.
- Use hex values as flat fills — always soft painterly Ghibli shading.
- Let character clothing colours clash with lighting family mood.

---

# Canon Authority

This document is the production reference for **character colour hex** and
**prompt lighting/colour blocks**.

Philosophy and seasonal rules remain in `Color_Language.md` and
`Lighting_Style.md`. This file adds the **specific values** used in prompts
and Flow generation.
