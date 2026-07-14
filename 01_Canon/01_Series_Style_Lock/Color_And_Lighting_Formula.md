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
| Clear Soft Blue Sky (Post-Monsoon day) | `#7EB8E8`–`#A8D4F0` | Late morning / afternoon Post-Monsoon — **never pure white** |
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
terracotta pot, soft blue sky, gentle side-light — like approved early Ep1 stills.

### Ep1 late morning courtyard (simple)

```text
Warm & Sunlit · Post-Monsoon · late morning
Soft golden side-light from east / left
Soft blue sky with light white clouds — not blown white
Fresh greens · terracotta pot · warm earth
Clear vibrant blue butterfly · bright orange marigold
Studio Ghibli-inspired digital anime — soft linework, painterly, NOT photoreal
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

- Paddy: **fresh saturated green** + golden edge highlights
- Sky: **clear soft blue** + soft white clouds — **never pure white, never grey**
- Coconut: deep saturated green + golden edges
- House: terracotta roof + cream walls — wall **darker than sky** for depth

### Garden & Courtyard (Ep1)

- Leaves: fresh garden green `#5A9A4A`–`#4F8F3C` + golden highlights
- Flowers: marigold orange `#E8A020` vivid
- Earth: warm brown `#8B7355`–`#A07850` + terracotta `#C97B4A`
- Sky: clear soft blue `#7EB8E8`–`#A8D4F0` + soft white clouds
- Wall: cream `#F0E0C8` — readable against blue sky (not same brightness)

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

### COLOR RICHNESS LOCK (every season — base)

```text
Warm muted Ghibli-inspired anime palette per Art_Style.md
Subject accents (marigold, butterfly) may be clear and vibrant
Post-Monsoon outdoor: soft blue sky — not blown white
NOT photoreal · NOT HDR · NOT Bollywood neon
```

*(Add SUMMER / MONSOON season lock only when that season is on the board.)*

### EP1 COURTYARD (LOCKED — Clip 01 baseline)

Use this language for Ep1 outdoor clips. Do **not** replace with heavy
“medium cinematic / hex-lock / anti-fog” stacks.

```text
Art: Studio Ghibli-inspired anime — soft, warm, delicate fine linework,
painterly digital watercolor/gouache, soft matte finish.
Lighting Family: Warm & Sunlit — early morning
Light: soft golden sun from east; gentle side-light; soft short morning shadows
Season: Post-Monsoon/Harvest
Sky: soft blue sky with light clouds in bokeh — NOT blown white / cream wipe
Colors: marigold orange #E8A020 · terracotta #C97B4A · butterfly iridescent blue ·
cream wall #F5E6C8 · soft green #5A9A4A — never neon
Environment: terracotta pot, packed earth, cream lime wall bokeh, simple backyard edge
NOT photoreal · NOT HDR · NOT harsh noon · NOT sunset amber wash
```

This is the locked Ep1 look. Seasonal Summer/Monsoon tables elsewhere are for
other episodes only.

---

## Prompt checklist

```text
✓ Season locked (Summer / Monsoon / Post-Monsoon)
✓ Time of day locked (and matches season table)
✓ Correct lighting family (Warm & Sunlit vs Cool & Monsoon)
✓ Season-true sky / greens / earth / atmosphere
✓ Contrast matches season (high / very low / medium)
✓ Skin warm consistent
✓ Natural light sources only
✓ Ep1: POST-MONSOON LATE MORNING lock — blue sky, not misty grey wash
```

---

## Episode mapping

| Episode / zone | Lock |
| --- | --- |
| **ep_001 courtyard** Clips 01–10 | **POST-MONSOON LATE MORNING** |
| Mother kitchen dusk | Kitchen dusk + evening west |
| Monsoon episodes | **MONSOON LOCK** |
| Summer episodes | **SUMMER LOCK** + correct ToD |

---

## Guiding Principle

One season, one truth: Summer harsh and dusty, Monsoon dark and wet, Post-Monsoon
**clear, warm, and vibrant** — always Ghibli-inspired digital anime on a lived-in
1990s Tamil village, without washing out or mixing season moods.
