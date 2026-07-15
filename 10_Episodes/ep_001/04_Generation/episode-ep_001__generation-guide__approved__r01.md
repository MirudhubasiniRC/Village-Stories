# Episode ep_001 — Google Flow generation guide

> **STATUS:** Superseded for production.  
> **Shipped board:** `episode-ep_001__clip-prompt-workflow__approved__r01.md`
> (12 clips · Flow generation complete 2026-07-15).  
> Keep this file only as early 7-shot archive. Do not use for regen.

> **Legacy workflow note:** Image prompts only, one clip at a time. After each
> still is approved in Flow, request animation + audio for that clip.
> Dialogue goes inside the audio prompt.

**Aspect ratio:** 9:16 vertical (portrait) — design every frame vertical, never crop
from 16:9.

**Recommended order (legacy):** sh_002 → sh_001 → sh_004 → sh_003 → sh_005 → sh_006 → sh_007

**Optional attachments in Flow:**
- sh_002+: `Elder_Brother_Younger_Daughter_Scale_Reference.png` as STYLE_TARGET
- Children shots: individual child refs as CHARACTER_IDENTITY if needed

---

## SHARED STYLE BLOCK (prepend to every shot)

```
### STYLE — 9:16 VERTICAL
Studio Ghibli-inspired DIGITAL anime for the ENTIRE frame. Painterly digital watercolor/gouache, soft matte, delicate linework, soft cel shading blended with brushwork. Richly illustrated digital background. Warm & Sunlit · Early morning · Post-Monsoon/Harvest. Soft golden morning light from east. Portrait composition 9:16 aspect ratio — central subject, caption-safe margins top and bottom. NOT photoreal, NOT chibi.
```

---

## sh_001 — Hook (4 s) — butterfly on marigold

```
[SHARED STYLE BLOCK]

### SHOT — ECU vertical 9:16
Extreme close-up bright orange marigold flowers in terracotta clay pot. Courtyard garden edge, soft green leaves blurred behind. One beautiful blue butterfly with painterly iridescent wings settles on marigold petal — wings folded, about to twitch open. Warm golden morning side-light on petals. Shallow depth, marigold and butterfly fill centre 70% of vertical frame.

### MOTION (Flow)
Butterfly wings twitch once gently; marigold stem sways barely in morning breeze.

### NEGATIVE
children in frame, photoreal, cartoon mascot butterfly, neon colors, horizontal composition, text overlay.
```

---

## sh_002 — Hero orientation (6 s) — siblings see marigold

```
[SHARED STYLE BLOCK]

### SHOT — MS vertical 9:16
Medium shot eye-level. Early-morning family garden courtyard. Elder Brother (boy 9-10): messy tousled black hair, reddish-brown white checkered short-sleeve shirt with pocket, tan shorts, barefoot, wicker basket in right hand. Younger Daughter (girl 6-7): two braids with pink ribbon bows, small red bindi, soft yellow dress with pink flower print and pink hem trim, barefoot. SCALE LOCK: brother clearly taller — sister reaches his shoulder/chest, never equal height.

Cream plaster wall with open wooden picket gate behind. Terracotta marigold pots, pink hibiscus, warm earth path. Both children look toward orange marigold pot below frame edge where blue butterfly rests. Soft curious expressions — gentle not posed. Peach-cream morning sky.

### MOTION (Flow)
Both children turn heads slightly toward marigold; basket still in brother's right hand.

### NEGATIVE
equal height children, adult proportions, modern clothes, photoreal, horizontal frame, missing either child.
```

---

## sh_003 — Sister steps closer (8 s)

```
[SHARED STYLE BLOCK]

### SHOT — MS vertical 9:16
Same courtyard, same children, same wardrobe and scale lock as sh_002. Younger Daughter takes one small step closer toward marigold pot, small hands gently together at chest. Elder Brother stands patient beside her, basket lowered slightly, soft protective older-brother posture. Cream wall, wooden gate, marigold pots, morning light.

### MOTION (Flow)
Sister one small step forward; brother still, slight smile.

### NEGATIVE
reaching to grab butterfly, running, shouting, scale drift, wardrobe change.
```

---

## sh_004 — Butterfly wings (5 s)

```
[SHARED STYLE BLOCK]

### SHOT — CU vertical 9:16
Close-up orange marigold and blue butterfly on petal. Painterly anime iridescent blue wings slowly opening and closing. Soft golden morning light. Green garden bokeh background. Vertical frame — flower centre.

### MOTION (Flow)
Slow wing open and close once.

### NEGATIVE
children visible, photoreal insect, horizontal, harsh flash.
```

---

## sh_005 — Butterfly lifts (7 s)

```
[SHARED STYLE BLOCK]

### SHOT — MS vertical 9:16
Same siblings as sh_002 in same courtyard. Blue butterfly lifts upward from marigold below frame. Both children look up following butterfly — sister silent delight, brother gentle proud smile. Scale and wardrobe locked. Morning garden, cream wall, gate.

### MOTION (Flow)
Butterfly rises slowly; children's eyes track upward; soft smile grows.

### NEGATIVE
jumping, chasing, butterfly giant, scale wrong, dusk lighting.
```

---

## sh_006 — Marigold petal gift (6 s)

```
[SHARED STYLE BLOCK]

### SHOT — MS vertical 9:16
Same siblings, same place, morning light. Butterfly gone. Elder Brother extends one fallen orange marigold petal in open palm toward Younger Daughter. She receives with both small hands, soft grateful smile. Brother kind smile. Scale locked. Basket in brother's other hand.

### MOTION (Flow)
Brother hand extends petal slowly; sister hands reach to accept.

### NEGATIVE
butterfly still visible, adult hands, jewellery overload, photoreal.
```

---

## sh_007 — Wide release (5 s)

```
[SHARED STYLE BLOCK]

### SHOT — Wide vertical 9:16
Wide courtyard morning rest. Small figures of brother and sister standing peacefully among marigold pots, cream wall, wooden gate, hibiscus, soft palms in distance. Warm peach morning sky with atmospheric perspective. Children not centred large — environment breathes. Peaceful episode ending hold.

### MOTION (Flow)
Near-still; one leaf drifts slowly; optional soft cloud shift.

### NEGATIVE
new characters, dramatic action, horizontal panorama crop, harsh noon.
```

---

## After generation

1. Save selected stills per `10_Studio_Standards/Asset_Naming.md`
2. Run Flow one motion per clip (M1–M3 calm motion only)
3. Register in `04_Generation/episode-ep_001__selected-asset-register__draft__r01.md`
4. Edit in `06_Edit/` to 50–55 s master
5. QA per `07_Episode_System/14_Episode_Checklist.md`
