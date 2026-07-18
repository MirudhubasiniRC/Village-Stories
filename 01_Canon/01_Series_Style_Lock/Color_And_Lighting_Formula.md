# Color & Lighting Formula — Master Reference

## Purpose

This document codifies the **complete color palette and lighting philosophy**
for Village Stories. Every image, animation, and audio prompt should reference
these principles for visual consistency.

**Authority chain:**

- Philosophy and season: `Color_Language.md`
- Lighting families and sun logic: `Lighting_Style.md`
- Character skin and wardrobe hex: `Character_Color_And_Light_Reference.md`
- Prompt section structure: `09_AI_Production_System/21_Clip_Prompt_Formula.md`

This file is the **production copy-ready reference** — hex values, time-of-day
tables, and prompt blocks.

**Google Flow delivery rule:** internal references and hex tables are planning
sources, not sufficient prompt language. Every Flow prompt must restate the
selected visible colours, light temperature/direction, shadow quality,
saturation, brightness, contrast, and forbidden colour casts in plain words.
Never send only “match the approved/reference palette.”

---

## Overall Visual Philosophy

**"Warm Nostalgia, Softly Lit"** — per `Art_Style.md` (warm muted Ghibli-inspired
anime). Seasonal lighting tables below choose sky / weather / mood; they do
**not** override art style into photoreal, HDR, or harsh “cinematic grade.”

- Soft warm anime light; soft shadows
- Nature-grounded colours; accent colours (marigold, butterfly) may read clearly
- Match season + time of day
- **Post-Monsoon outdoor:** keep a **soft blue sky** — not blown white / cream wipe
- Do not pile hex locks or high-contrast filters into every Flow prompt

### Approved early-morning visual target (2026-07-17)

```text
11_Assets/Style_References/Early_Morning_Color_Lighting_Canon_Reference.png
```

This reference is the permanent **colour richness, contrast, and lighting-quality
target** for clear early-morning exteriors:

- Full, layered **fresh green foliage** — deep leaf greens in shade and lively
  yellow-green sunlit edges; never pale sage or grey-green wash.
- Soft golden east side-light on skin, cream plaster, terracotta roof, earth,
  animals, and plants — warm but **not** orange sunset grading.
- **Medium-soft contrast** with readable dark green canopy shade, open midtones,
  and controlled highlights.
- Rich warm terracotta, orange marigolds, red/pink hibiscus, purple brinjal,
  indigo clothing, and natural chicken colours remain distinct and harmonious.
- Skin remains warm golden and naturally integrated into the environment.
- Painterly depth: detailed foreground plants, readable midground action, softer
  background greenery — never a flat wall of green.

**Global application:** Use this as the colour/lighting target for all compatible
**Warm & Sunlit early-morning outdoor scenes** (Front Garden, Backyard, well,
livestock shelter, village path, field). Preserve the same richness and gentle
contrast indoors when morning window light permits.

It does **not** override story-true time or weather: Monsoon rain, midday,
evening, and night retain their own lighting rows. Translate the same colour
clarity and controlled-highlight philosophy into those conditions.

### Art style authority (unchanged)

```text
Studio Ghibli-inspired digital anime — soft delicate linework, painterly
watercolor/gouache, soft cel shading, warm muted palette.
Match Mother / Father canon references.
NOT photoreal · NOT CGI · NOT HDR
```

Seasonal tables inform **weather mood**. Art style stays as second Ep1-quality
still: clean anime outlines, vivid butterfly/marigold accents when those are subjects.

---

## Primary Color Palette

| Color Family | Specific Shades | Purpose |
| --- | --- | --- |
| **Earth Tones** | Terracotta, red oxide, clay, mud brown | Floors, walls, pots, architecture |
| **Greens** | Paddy green, coconut green, moss, banana leaf | Nature, fields, plants, gardens |
| **Warm Goldens** | Golden sunlight, honey, warm beige | Sunlight, skin warmth, highlights |
| **Cream & Whites** | Off-white, cream, pale beige, cotton white | Clothing, walls, curtains |
| **Deep Reds** | Maroon, rust, deep crimson | Mother saree, bindis, spices, festival |
| **Mustard & Ochre** | Mustard yellow, turmeric, golden brown | Father accents, spices, sunlight |
| **Indigo & Deep Blues** | Indigo, navy, deep blue-black | Traditional clothing, deep shadow tones |
| **Neutral Browns** | Warm brown, wood brown, café au lait | Wood, furniture, skin undertones |
| **Soft Grays** | Warm gray, slate, mist gray | Rain, morning mist, temple stone |

---

## Digital Hex Reference

| Color | HEX | Purpose |
| --- | --- | --- |
| Golden Sunlight | `#F5D6A8` | Sunlight, highlights |
| Golden Sunlight (alt) | `#F5C842` | Stronger morning highlight |
| Warm White | `#F5E8D0` | Walls, cotton, curtains |
| Cream Cotton | `#F5E6C8` | Veshti, sarees, walls |
| Cream Wall (courtyard) | `#F0E0C8` | Lime-plaster courtyard walls — warmer than sky |
| Clear Soft Blue Sky (Post-Monsoon day) | `#5BA3D9`–`#7EB8E8` | Bluey clear sky — **never pure white / milky wipe** |
| Soft White Cloud | `#F5F7FA` with soft grey underside | Cumulus accents — never blown-out white field |
| Horizon Warm Glow (optional) | `#F8DCC8` | Thin warm band near horizon only — **not** whole sky |
| Terracotta | `#C67A4E` / `#C97B4A` | Roofs, floors, pots — rich and warm |
| Red Oxide | `#A0522D` | Courtyard floor, worn earth |
| Warm Earth / Soil | `#8B7355`–`#A07850` | Packed earth paths — richer post-monsoon |
| Marigold Orange | `#E8A020` | Bright vivid orange-yellow marigolds |
| Paddy Green | `#7C9A5E` | Rice fields, foliage |
| Coconut Green | `#4A6B3D` | Coconut grove, deep greens — saturated |
| Fresh Garden Green | `#5A9A4A`–`#4F8F3C` | Courtyard plants — fresh after rains |
| Maroon | `#8B1A2B` / `#7A1F2B` | Mother saree, accents |
| Mustard | `#C49A2A` | Spices, fabric accents |
| Yellow Dress (child) | `#E8C872` | Younger Daughter dress |
| Warm Brown Wood | `#6B4C3B` | Pillars, furniture, tools |
| Brass | `#C9A84C` | Utensils, lamps, highlights |
| Deep Brown (darkest) | `#3D2B1F` | Deep shadows — never pure black |
| Skin (warm lit) | `#E8C89A`–`#F0D8B0` | Family skin — consistent across seasons |
| Summer dusty olive | `#8A9A5A`–`#9AAB6A` | Summer foliage — never deep emerald |
| Summer dust yellow earth | `#C4A574`–`#B8956A` | Dry cracked summer soil |
| Monsoon slate sky | `#4A5560`–`#6B7A8A` | Heavy monsoon overcast |
| Monsoon wet emerald | `#1F5C3A`–`#2E7A4A` | Glossy saturated wet greens |
| Moonlight cool | `#A8B8C8` ambient | Night scenes — never pure blue face light |
| Oil lamp amber | `#E8A040`–`#C97B4A` glow | Night warm pools |

---

## Universal rules (all seasons)

| Element | Rule |
| --- | --- |
| **Pure black** | Never — deepest shadows warm brown `#3D2B1F`, maroon, or navy |
| **Pure white** | Never as field — highlights warm cream / pale gold (except Summer midday glare is yellow-white **with** readable form; never blank white sky plate) |
| **Blue tones** | Sky, water, cool shadow edges — never blue cast on earth/architecture |
| **Skin** | Warm medium brown `#E8C89A`–`#F0D8B0` every season |
| **Light sources** | Sun, moon, fire, oil lamps only |
| **Season lock** | Same season = same sky family, colour mood — never change mid-scene |
| **Atmosphere** | Season-true: Summer dust/heat haze · Monsoon rain/mist · Post-Monsoon **day** = clean air (not fog) |
| **Post-Monsoon greens** | Fresh **greeny** banana / garden / coconut greens (`#3F8F3A`–`#5A9A4A`, `#3D6B35`–`#4A6B3D`) — **never** pale sage / milky wash (see GENTLE COLOR POP LOCK) |

---

# SUMMER

**Overview:** Intense, dry, harsh Tamil Nadu summer. Brutal sun, cracked earth,
dust, sharp shadows. Bleached and dusty — not freshly green.

**Impression:** *"Harsh, dust-bleached, high-contrast, yellow-white glare, deep
blue-brown shadows, heat shimmer over cracked earth."*

### Lighting

| Element | Detail |
| --- | --- |
| **Color temperature** | Very warm–high contrast 5000–5500K — yellow-white, intense |
| **Quality** | Harsh, direct, unfiltered |
| **Direction** | High overhead — steep angle |
| **Shadows** | Sharp, dark, well-defined |
| **Atmosphere** | Heat haze (dust), **no mist** |
| **Heat feel** | Yellow-white glare, heat shimmer over fields |

### Sky

| Time | Sky |
| --- | --- |
| Morning | Pale yellow-washed blue, hazy horizon |
| Midday | Bleached pale blue, almost white near horizon |
| Evening | Deep orange, pink, purple — dramatic |

### Colors

| Element | Color |
| --- | --- |
| Greens | Dusty olive, pale yellow-green, brown-green — **never deep emerald** |
| Earth | Dry terracotta, pale brown, dust yellow, cracked |
| Walls | White-washed — bleached, glaring in sun |
| Shadows | Warm brown-blue, deep brown |
| Water | Pale blue-white, strong reflection |
| Foliage | Yellowing, dusty, wilted at midday |

### Contrast

**High** — bright hot highlights, dark sharp shadows. Deepest shadow still
warm brown, not pure black.

### Must use / Must avoid

**Use:** heat haze · dust · bleached pale colours · deep sharp shadows under trees · cracked dry earth · glaring white-washed walls

**Avoid:** mist · deep saturated greens · wet surfaces (unless irrigated) · soft shadowless look · cool blue casts on earth

### Summer time-of-day

| Time | Lighting | Feel |
| --- | --- | --- |
| **Early morning** | Warm golden low-angle; long soft warm-brown shadows; pale yellow-blue sky; still cool, dew rare, dust rising | Fresh but already warming |
| **Midday 11–3** | Blazing white-yellow overhead; short dark sharp shadows; bleached hazy sky; heat shimmer | Unforgiving — prefer shade / indoor for story |
| **Evening** | Deep golden-orange low west; long deep warm shadows; orange/pink/purple sky; dust settling | Dramatic, nostalgic, intense |

### SUMMER PROMPT LOCK

```text
SUMMER LOCK — Warm & Sunlit · dry · harsh:
Lighting: 5000–5500K yellow-white direct sun, high angle (midday) or low harsh evening gold
Shadows: SHARP, dark, well-defined warm brown-blue
Greens: dusty olive / pale yellow-green — NOT deep emerald
Earth: dry cracked terracotta, dust yellow
Atmosphere: heat haze + dust — NO mist, NO rain-wet gloss
Sky: bleached pale blue (day) or dramatic orange-pink (evening)
Contrast: HIGH — NOT soft Post-Monsoon medium contrast
Impression: harsh dust-bleached yellow-white glare, heat shimmer over cracked earth
```

---

# MONSOON

**Overview:** Heavy rain, dark skies, saturated wet world. Flat ambient light,
deep glossy greens, reflective puddles. Maps to lighting family **Cool & Monsoon**.

**Impression:** *"Dark, saturated, flat, shadowless, deep wet greens, grey skies,
heavy rain, reflective surfaces, cool and damp."*

### Lighting

| Element | Detail |
| --- | --- |
| **Color temperature** | Cool-warm 4500–5000K — overcast, grey, muted |
| **Quality** | Diffused, flat, nearly shadowless |
| **Direction** | Ambient — no direct sun (except rare cloud break) |
| **Shadows** | Nearly absent — very soft, vague |
| **Atmosphere** | Dense cloud, moisture-heavy, mist/fog in patches |

### Sky

| Condition | Sky |
| --- | --- |
| Light rain | Dark grey-blue, heavy clouds |
| Medium rain | Charcoal grey, stormy |
| Heavy rain | Dark slate, nearly black at horizon |
| Cloud break (rare) | Pale blue-grey patches + golden cloud edges |

### Colors

| Element | Color |
| --- | --- |
| Greens | Deep emerald, dark wet glossy green |
| Earth | Dark wet brown, deep muddy terracotta |
| Walls | Greyed cream — damp, darkened |
| Water | Dark blue-grey / muddy brown — reflective |
| Sky | Dark slate, charcoal, grey-blue |

### Contrast

**Very low** — flat, muted highlights (grey-white), soft/absent shadows.
Texture reduced by wetness.

### Must use / Must avoid

**Use:** visible rain streaks/splash · wet glossy surfaces · dark saturated greens ·
low cloud / mist patches · dark muddy earth · puddle reflections

**Avoid:** clear blue Post-Monsoon sky · warm golden directional sun (unless brief break) ·
sharp Summer shadows · heat haze · dry dusty surfaces

### Outdoor vs indoor

| | Outdoor | Indoor |
| --- | --- | --- |
| Light | Flat overcast ambient | Grey-blue through window; stove/lamp warmer |
| View | Dark sky, rain visible | Cool grey outdoor vs warm wood/red oxide indoor |
| Feel | Soaked, misty, rainy | Darkened, damp, cozy if fire/stove |

### MONSOON PROMPT LOCK

```text
MONSOON LOCK — Cool & Monsoon · wet · overcast:
Lighting: 4500–5000K flat diffused ambient — NO directional golden sun
Shadows: nearly ABSENT — soft, vague
Sky: dark grey / charcoal / slate — NOT clear blue
Greens: deep wet emerald — glossy saturated
Earth: dark muddy wet brown / deep terracotta
Atmosphere: rain streaks, mist patches, puddle reflections — soaked world
Contrast: VERY LOW — flat, muted
Impression: dark saturated flat shadowless wet greens, grey skies, cool damp
```

---

# POST-MONSOON / HARVEST

**Overview:** Soft warm morning after rains — vibrant village, gentle anime light.

**Keep from correction:** soft **blue sky** (not blown white).

**Do not force:** medium-cinematic grade, hex piles, fog bans, harsh directional
contrast that push Flow toward photoreal or pale butterflies.

**Impression:** Soft Ghibli morning with vivid marigold and butterfly accents,
terracotta pot, soft blue sky, **rich green leaves**, gentle side-light — like
approved early Ep1 stills.

### GENTLE COLOR POP + WARMTH LOCK (series outdoor — never forget)

Locked after Ep1 finish (Clip 10+ stills): words like **“soft warm”**, **“soft
diffused”**, **“muted”**, or **“airy”** often push Flow into **high-key white**
— colours flatten (sage greens, pale sky, pinkish shirt, porcelain skin).

Target look:

- **A little more warmth** than white daylight — golden side-kiss, not sunset
  amber dunk
- **Gentle colour pop** — each hue reads as itself:
  - blue → more **bluey** (sky / butterfly)
  - green → more **greeny / fresh** (banana, palm, grass)
  - red / check / terracotta / saree → more **reddy / warm brick** (not dusty pink, not dull brown-mud)
  - yellow dress / marigold → clear sunny yellow-orange (not creamy pale)
- **Medium-soft contrast** — soft Ghibli shading, readable forms, gentle shadows
  — **NOT** high-contrast punchy darks, crushed blacks, or harsh sun/shadow split
- **Slightly reduced brightness** — gentle midtone richness; highlights controlled
  — **NOT** overbright / high-key glare / blown white highlights · **NOT** dark
  or dim overall
- Still Ghibli soft matte — **not** neon, HDR, Bollywood crush, or heavy sepia

| Element | Prefer (clear pigment) | Never |
| --- | --- | --- |
| Banana / garden leaves | `#3F8F3A`–`#5A9A4A` fresh greeny green | Pale sage, grey-mint, milky lime, dull olive-brown |
| Coconut / palm | `#3D6B35`–`#4A6B3D` | Overexposed white-green |
| Sky | Clear bluey blue `#5BA3D9`–`#7EB8E8` + soft white clouds | Milky white sky, cream wipe, grey wash |
| Check shirt / terracotta / maroon | Reddish-brick / clear maroon `#B85C3A`–`#C97B4A` / deep maroon saree | Washed pink-red, dusty rose, dull brown-only indoor |
| Marigold / accents | Vivid `#E8A020` | Pale cream-orange |
| Skin | Medium-fair golden `#E8C89A`–`#F0D8B0` | Porcelain white, pink-pale anime |
| Hair (Mother / children) | **Natural black** per character bible | Brown hair, auburn/red highlights on Mother |
| Neighbour houses | Warm cream plaster + terracotta roofs (readable) | Grey ghost houses |
| Contrast | Medium-soft · soft painted shadows · open midtones | High contrast · crushed black shadows · harsh noon split |
| Brightness | Slightly lowered · gentle midtones · controlled highlights | Overbright high-key · blown white highlights · dark/dim overall |
| Light wording | Gentle golden east side-light; clear colour; slight warmth; soft shade; slightly reduced brightness | “High contrast cinematic” · “dramatic shadows” · “soft warm wash” · “muted dull” · “bright sunny glare” |

**Prompt words to USE:** `gentle colour pop` · `fresh greeny greens` · `clear
bluey blue sky` · `warm brick reddish` · `slight morning warmth` ·
`medium-soft contrast` · `soft Ghibli shading` · `slightly reduced brightness` ·
`gentle midtones` · `colours clear and lively`

**Prompt words to AVOID:** `soft warm wash` · `muted palette` · `airy high-key` ·
`bright sunny glare` · `overexposed highlights` · `dreamy haze` · `pastel` ·
`high contrast` · `dramatic shadows` · `cinematic crush` · `dull earth wash`

```text
GENTLE COLOR POP LOCK — Post-Monsoon outdoor / clear indoor (Ep2+ and regen):
Slight morning warmth — NOT white daylight bleach · NOT heavy sunset amber
BRIGHTNESS: slightly reduced overall — gentle midtones · controlled highlights
  — NOT overbright high-key · NOT blown white highlights · NOT dark/dim
CONTRAST: medium-soft Ghibli shading — NOT high-contrast punchy darks · NOT crushed blacks
GREEN: fresh greeny greens #3F8F3A–#5A9A4A · palm #3D6B35–#4A6B3D
BLUE: clear bluey sky #5BA3D9–#7EB8E8 + soft white clouds
RED: warm brick reddish terracotta / check / maroon #B85C3A–#C97B4A — not pink · not dull brown mud
YELLOW: clear marigold #E8A020 · sunny yellow dress — not creamy pale
SKIN: medium-fair golden #E8C89A–#F0D8B0
HAIR: natural BLACK per character bible — Mother daytime default HALF-UP
  (subtle dark-brown sheen only — never brown/auburn hair); braid only on request
  jhumkas ~1.5–2 in gold bell-shaped; left-chin mole; nose stud
NOT muted · NOT soft-warm whitewash · NOT high contrast · NOT dull indoor · NOT neon/HDR
```
### Ep1 / outdoor path · neighbourhood (simple)

```text
Warm & Sunlit · Post-Monsoon · early morning
Gentle golden east side-light — slight warmth, clear colour (NOT white high-key)
Clear BLUEY blue sky #5BA3D9–#7EB8E8 + soft white clouds
Fresh GREENY greens — banana / garden / palm (GENTLE COLOR POP LOCK)
Warm brick terracotta roofs + cream plaster neighbour houses (readable)
Marigold #E8A020 · reddish check / terracotta #C97B4A · lively accents
Studio Ghibli-inspired digital anime — soft linework, painterly, NOT photoreal
NO washed-out white frame · NO muted pastel · NO compound-wall box
```
---

## Lighting scenes — quick pick (storyboard)

**Rule:** Pick **one season row** + **one time row**. Never default to evening golden hour.

| ID | When | Use |
| --- | --- | --- |
| S-AM | Summer early morning | Soft-warming golden, long soft shadows, pale yellow-blue |
| S-MID | Summer midday | Harsh high, short sharp shadows — prefer shade stories |
| S-PM | Summer evening | Dramatic orange-pink-purple west gold |
| M-RAIN | Monsoon outdoor | Flat cool-warm, wet, grey sky |
| M-IN | Monsoon indoor | Grey window + warmer stove |
| P-EARLY | Post-Monsoon early (mist OK) | Soft gold, optional light dew mist |
| P-LATE | Post-Monsoon late morning | **Ep1** — blue sky, directional gold, medium contrast |
| EVE | Any clear evening (west) | Golden hour — Mother dusk, chores |
| NIGHT | Night | Moon cool + oil lamp amber pools |

---

## Time-of-day overrides (any season)

### Early morning (5:30–7:30)

| Element | Detail |
| --- | --- |
| Lighting | Soft diffused low-angle golden · 3000–3500K |
| Mist | Allowed — light low mist over fields (**Post-Monsoon / winter only** — never Summer) |
| Shadows | Long, soft, muted warm brown |
| Mood | Fresh, hopeful, quiet |
| Sky | Pale with warm gold at horizon; Post-Monsoon may still hold soft blue |

### Midday (11:00–15:00)

| Season | Midday behaviour |
| --- | --- |
| Summer | Harsh bleached — heat shimmer |
| Monsoon | Flat grey if raining |
| Post-Monsoon | Warm clear blue sky, shorter defined shadows — still medium contrast, not Summer bleach |

### Evening / golden hour (16:30–18:30)

| Element | Detail |
| --- | --- |
| Lighting | Deep golden-orange, horizontal from **west** · 2500–3000K |
| Shadows | Long, deep, warm brown |
| Sky | Orange, pink, purple, gold |
| Mood | Dramatic, nostalgic, peaceful |
| Avoid | Over-saturating; do not use for Ep1 morning courtyard |

### Night (19:00–05:00)

| Mode | Detail |
| --- | --- |
| Clear moon | Deep blue sky, stars; pale silver-blue moonlight; soft dark blue-black shadows; oil lamps = warm amber islands |
| Overcast (no moon) | Dark grey sky; lamp pools only |
| Rainy night | Diffused dark + wet reflections of lamp amber |

**NIGHT PROMPT LOCK:**

```text
NIGHT LOCK:
Moonlight cool ambient (~6000K feel) + oil lamp / fire warm amber (~2800K) pools
Deep dark blue or dark grey sky — stars if clear
Shadows soft deep brown-blue — never crushed pure black faces
Warm lamp glow on faces / clay — cool remainder
NOT neon · NOT streetlights · NOT phone glow
```

---

## Indoor variants

### Kitchen — day (any season)

| Element | Detail |
| --- | --- |
| Sources | Large window + ambient + stove glow |
| Temp | Warm 3500–4000K day through window |
| Colors | Red oxide floor · cream walls · brass · terracotta |
| Season | Monsoon cooler grey window · Summer brighter · Post-Monsoon soft golden |

### Kitchen — dusk (evening)

| Element | Detail |
| --- | --- |
| Sources | Dim cooler window + warm stove + lamp |
| Temp | Mixed ~4000K window + ~2800K fire |
| Impression | Warm amber firelight against fading cool grey outside |
| Use | Mother filter-coffee / dusk kitchen beats |

### Bedroom — morning

| Element | Detail |
| --- | --- |
| Source | Window soft golden 3000–3500K |
| Colors | Cream walls · red oxide · cream cotton · warm wood |
| Impression | Soft golden morning light wrapping everything gently |

### Front Thinnai — shade

| Element | Detail |
| --- | --- |
| Light | Diffused ambient + bounce from courtyard |
| Feel | Cool shaded restful retreat; soft cool shade + warm reflections |
| Colors | Red oxide darker in shade · cream walls · wooden pillars cool brown |

---

## Season comparison

| Element | Summer | Monsoon | Post-Monsoon (day) |
| --- | --- | --- | --- |
| **Sky** | Bleached pale blue, hazy | Dark grey / slate / charcoal | Clear soft blue + white clouds |
| **Light** | Harsh, direct | Flat, diffuse | Soft + directional gold |
| **Shadows** | Sharp, dark | Nearly absent | Soft but defined |
| **Contrast** | High | Very low | Medium cinematic |
| **Greens** | Dusty olive, pale | Deep wet emerald | Fresh saturated emerald |
| **Earth** | Dry cracked, dust yellow | Dark wet muddy | Warm rich terracotta brown |
| **Atmosphere** | Heat haze, dust | Rain, mist, wet | Clean post-rain air |
| **Mist** | Never | Sometimes | Early morning only if approved |
| **Wetness** | Dry | Soaked | Dew possible early; drying day |

### Season colour quick reference

```text
SUMMER: bleached pale blue sky · dusty olive · dry dust yellow earth · yellow-white glare · sharp warm-brown shadows · heat haze

MONSOON: charcoal/slate sky · deep wet emerald · dark muddy earth · muted grey highlights · nearly no shadows · rain + reflections

POST-MONSOON DAY: clear soft blue + white clouds · fresh saturated greens · rich terracotta · golden directional light · medium contrast · clean air
```

---

## Scene-Specific Colour Breakdown

### Village Exterior (wide · Post-Monsoon day)

- Paddy: **fresh greeny green** + golden edge highlights
- Sky: **clear bluey blue** `#5BA3D9`–`#7EB8E8` + soft white clouds — never white wipe
- Coconut: deep greeny green + golden edges
- House: terracotta roof + cream walls — wall **darker than sky** for depth

### Garden & path exterior (neighbourhood)

- Leaves: fresh greeny `#3F8F3A`–`#5A9A4A` + soft golden edge only —
  see **GENTLE COLOR POP LOCK** (never pale sage / whitewash)
- Palm / coconut: `#3D6B35`–`#4A6B3D`
- Flowers: marigold `#E8A020` vivid
- Red accents: brick reddy terracotta / check `#B85C3A`–`#C97B4A`
- Earth: warm brown `#8B7355`–`#A07850`
- Sky: bluey `#5BA3D9`–`#7EB8E8` + soft white clouds
- Architecture: warm distant tiled roofs / open thinnais OK — **no large compound
  wall** filling the frame (`Village_Neighbourhood.md`)
- Light: slight morning warmth — **not** muted pastel · **not** white high-key
### Interior — Kitchen (Mother dusk)

- Floor: red oxide + warm shadows
- Walls: cream `#F5E6C8` + terracotta accents
- Stove: blackened clay + warm ember glow
- Utensils: brass `#C9A84C`
- Window: **west** fading cool-grey vs warm fire — not east morning

---

## Contrast & Negative Space (season aware)

| Season | Contrast rule |
| --- | --- |
| Summer | High — retain warm-brown (not pure black) deep shadows |
| Monsoon | Very low — never invent hard sun shafts unless cloud break |
| Post-Monsoon day | Medium cinematic — FG/MG/BG; BG slightly darker than sky |

| Element | Always |
| --- | --- |
| Darkest | Deep brown `#3D2B1F` — never pure black |
| Skin | `#E8C89A`–`#F0D8B0` |
| Clothing whites | Cream / off-white |

---

## Atmospheric elements (season gated)

| Element | When |
| --- | --- |
| Heat shimmer / dust haze | Summer only |
| Rain streaks / puddles | Monsoon (or rain beat) |
| Light dew mist | Early morning Post-Monsoon / winter only — light |
| Steam / smoke / lamp glow | Kitchen / night — any season |
| Clean clear air | Post-Monsoon daytime default |

---

## Key lighting rules

1. Lock **season** first, then **time of day**, then location.
2. Post-Monsoon outdoor day = clear blue sky + medium contrast (Ep1 lock).
3. Summer ≠ soft Post-Monsoon; Monsoon ≠ blue-sky Post-Monsoon.
4. Evening golden hour = west light only, when board says evening.
5. Natural sources only.
6. Same season continuity across adjacent clips.
7. Atmosphere is season-true — not “always mist.”

---

## Prompt copy blocks

### GENTLE COLOR POP LOCK (every clear outdoor season — base)

```text
Ghibli-inspired anime — gentle colour pop + slight morning warmth
Blue more bluey · green more greeny/fresh · red more reddy/brick · yellow clear
NOT muted pastel · NOT soft-warm whitewash · NOT photoreal · NOT HDR · NOT neon
```

*(Add SUMMER / MONSOON season lock only when that season is on the board.)*

### EP1 / SERIES PATH · NEIGHBOURHOOD (LOCKED — GENTLE COLOR POP)

Use for outdoor Ep2+ prompts and any Ep1 regen. Do **not** use “soft warm /
muted / airy high-key” stacks that bleach colour.

```text
Art: Studio Ghibli-inspired anime — delicate fine linework,
painterly digital watercolor/gouache, soft matte finish.
Lighting Family: Warm & Sunlit — early morning
Light: gentle golden east side-light — slight warmth, clear pigment
Contrast: medium-soft Ghibli shading — NOT high-contrast punchy darks
Brightness: slightly reduced overall — gentle midtones · NOT overbright glare
Season: Post-Monsoon/Harvest
GENTLE COLOR POP:
  Green: fresh greeny #3F8F3A–#5A9A4A · palm #3D6B35–#4A6B3D
  Blue: bluey sky #5BA3D9–#7EB8E8 + soft white clouds
  Red: brick reddish check / terracotta / maroon #B85C3A–#C97B4A
  Yellow: marigold #E8A020 · clear sunny yellow dress
  Skin: medium-fair golden #E8C89A–#F0D8B0
  Hair: natural BLACK per bible (Mother: long thick wavy black — no brown/red highlights)
Environment: packed-earth path, lively greens, colourful distant neighbour roofs
NO large compound wall · NO washed-out white · NO muted dull · NO harsh contrast crush
NOT photoreal · NOT HDR · NOT neon · NOT harsh noon · NOT heavy sunset amber
```

Full detail: **GENTLE COLOR POP + WARMTH LOCK** above.
---

## Prompt checklist

```text
✓ Season locked (Summer / Monsoon / Post-Monsoon)
✓ Time of day locked (and matches season table)
✓ Correct lighting family (Warm & Sunlit vs Cool & Monsoon)
✓ Season-true sky / greens / earth / atmosphere
✓ GENTLE COLOR POP — bluey blue · greeny green · reddy brick · clear yellow
✓ Medium-soft contrast — soft Ghibli shading · NOT punchy high contrast
✓ Slightly reduced brightness — gentle midtones · NOT overbright glare · NOT dark/dim
✓ Slight morning warmth — NOT white high-key · NOT heavy amber dunk
✓ Mother / child hair natural BLACK per bible — no brown/red highlight drift
✓ Skin medium-fair golden consistent
✓ Natural light sources only
✓ NOT washed-out white · NOT muted dull indoor · NOT milky sky · NOT grey ghost houses
```

---

## Episode mapping

| Episode / zone | Lock |
| --- | --- |
| **ep_001 path/garden** Clips 01–12 | Shipped as-is; any regen / Ep2+ use **GENTLE COLOR POP + WARMTH LOCK** + open neighbourhood (no compound wall) |
| Mother kitchen dusk | Kitchen dusk + evening west |
| Monsoon episodes | **MONSOON LOCK** |
| Summer episodes | **SUMMER LOCK** + correct ToD |

---

## Guiding Principle

One season, one truth: Summer harsh and dusty, Monsoon dark and wet, Post-Monsoon
**clear, slightly warm, and gently lively in colour** — bluey blues, greeny
greens, reddy brick accents — Ghibli soft matte on a lived-in 1990s Tamil
village, never whitewashed and never neon.
