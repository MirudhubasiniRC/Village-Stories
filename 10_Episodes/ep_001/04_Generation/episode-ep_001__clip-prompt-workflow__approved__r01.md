# ep_001 — Clip prompt workflow

## Phased delivery (locked)

| Phase | When | What you receive |
| --- | --- | --- |
| **1** | Per clip, in order (01 → 12) | **Image prompt only** |
| **2** | After you approve that still in Flow | **Animation prompt** + **Audio prompt** (dialogue inside audio) |

Do not request animation/audio until the current clip image is done.

## Dialogue rule

Spoken lines are written inside the **Audio / ASMR prompt** — not a separate
voice file.

**ep_001 dialogue (revised flow):**
- Clip 03 — Younger Daughter: `Butterfly…` (cute, happy tone)
- Clip 10 — Younger Daughter: `No…!` (laughing, dog licks her face)

## Story flow — Clip 01 → 12 (revised)

| Clip | ID | ~Dur | Story beat |
| --- | --- | --- | --- |
| 01 | sh_001 | 4 s | **Hook** — Blue butterfly on marigold in terracotta pot on **Front Garden / entrance-path edge**. No people. Open greens; **no compound wall**. |
| 02 | sh_002 | 6 s | **Orientation** — Siblings + German Shepherd discover butterfly at pot along **open village/entrance path** (same camera side as Clip 01). Soft neighbour life deep BG. Dog head tilt. |
| 03 | sh_003 | 5 s | **Turn + line 1** — Butterfly **starts to rise**. Younger Daughter says **`Butterfly…`** cutely, happy tone. **Elder Brother laughs** at his little sister’s sweet reaction. |
| 04 | sh_004 | 3 s | **Insert — calf** — Baby calf playfully nuzzles / head-butts hay. No horns, small brass bell. Same late-morning compound. |
| 05 | sh_005 | 3 s | **Insert — goats** — White goat + brown goat (droopy ears) drinking at stone trough. |
| 06 | sh_006 | 5 s | **Choppu saman — setup (macro)** — Choppu on mini clay stove; water + sand; **dog with them**. Keep duration short in Flow (≤5s) so props do not vanish. |
| 07 | sh_007 | 5 s | **Choppu saman — fill shell (macro)** — Brother packs **wet sand into a half coconut shell** (idli mould). Dog present. Prefer ≤5s in Flow. |
| 08 | sh_008 | 5 s | **Choppu saman — press (macro)** — Brother **presses the filled coconut shell into the packed earth**, then lifts — round sand idli stamped on the ground. Dog present. Prefer ≤5s in Flow. |
| 09 | sh_009 | 6 s | **Choppu payoff (MS)** — **Continuity from pressed sand idli** — medium shot: brother and sister **smiling** proudly at the ground idli / coconut-shell play. |
| 10 | sh_010 | 7 s | **Comedy + line 2** — **Continuity** — Family Dog **licks** smiling Younger Daughter’s face. She laughs: **`No…!`** |
| 11 | sh_011 | 6–8 s | **Release (wide)** — Pulls back to **open village path + greens** — siblings, dog, choppu play edge, soft neighbour life deep BG; **no compound wall**. Peaceful soft hold. **No fade** in this clip. |
| 12 | sh_012 | 5–6 s | **Day end — Tamil wall calendar** — Close on **1990s Tamil calendar** on **house plaster only** (calendar mount — not compound enclosure): **Tamil numbers**, small **deity pictures**, soft late-day light. Hold → **fade to black** in animation/edit. |

**Emotional arc:** Wonder → discovery → sweet laugh → village life → choppu play (fill shell → press ground → smile) → dog comedy → open path wide → quiet calendar day-end → black.

**Sand idli method (locked):** wet sand packed into **coconut shell** → **pressed into the earth** → stamped sand idli on ground. Not palm-mould.

**Calendar end (locked):** 1990s Tamil wall calendar on cream house wall — **readable Tamil numbers**, small **printed deity/idol images**, soft day-end light; **fade to black** only on Clip 12 (not on wide Clip 11).

**Production note — renumber after Clip 06:** inserting the press beat (+1) and calendar (+1) shifts prior Clips 07–10. Old palm-mould Clip 07 / smile / dog / wide map to new **07–11**; calendar is **12**. Re-generate **07, 08, 09** for shell method continuity; **10** (dog) can keep if still contiguous after new smile still; **11** = prior wide still (drop fade).

**Removed from prior draft:** palm-mould idli; fade-to-black on courtyard wide (fade now lives on Clip 12).

## Clip list — image subject summary

| Clip | Image subject |
| --- | --- |
| 01 | Butterfly on marigold |
| 02 | Siblings + German Shepherd see butterfly at pot |
| 03 | Butterfly rises + “Butterfly…” + brother laughs |
| 04 | Baby calf + hay |
| 05 | Goats at stone trough |
| 06 | Macro — choppu on mini clay stove, water + sand |
| 07 | Macro — wet sand packed into coconut shell |
| 08 | Macro — coconut shell pressed into earth; sand idli on ground |
| 09 | MS — siblings smiling at sand idli (continuity from 08) |
| 10 | Dog licks face + “No…!” |
| 11 | Wide — open village path + greens (no compound wall, no black) |
| 12 | Tamil calendar on house plaster → fade black |

**Duration rule:** Every Animation Prompt includes a **Duration** line — reference
target from table above.

**Motion speed:** All motion blocks use **Normal Speed**. See `21_Clip_Prompt_Formula.md`.

**Lighting/colour — LOCKED from Ep1 Clip 01 baseline:**

- Art: Studio Ghibli-inspired anime — soft warm, delicate linework, painterly
  watercolor/gouache, soft matte (`Art_Style.md`)
- Lighting: Warm & Sunlit · **early morning** · soft golden east side-light
- Colors: marigold `#E8A020` · terracotta `#C97B4A` · iridescent blue butterfly ·
  cream `#F5E6C8` · soft green `#5A9A4A`
- **Only post-update keep:** soft **blue sky** in bokeh — not blown white
- **Greens lock (Post-Monsoon):** fresh **saturated** greens — banana leaf / garden
  green `#5A9A4A`–`#4F8F3C`, coconut green `#4A6B3D`. **Never** pale sage, milky
  lime, cream-washed foliage, or heat-haze bleach on leaves. Soft morning light
  without lifting greens into pastel.

Do not apply medium-cinematic / anti-fog / hex-heavy stacks to Ep1 prompts.

**Environment lock — Clip 01 → 12 (from Village Neighbourhood canon):**

Authority: `02_World/Locations/Village_Neighbourhood.md` Continuity Rules —
**Never add large compound walls** · **never isolate families** · keep **open
front yards** · compose along **Main Village Path** with houses on both sides.

Ep1 place: **neighbourhood edge** — Main Village Path / Family Entrance Path /
Front Garden play edge (`Front_Garden.md`, `Walking_Routes.md`). Children play
where village air, greens, and neighbours are still readable.

- **No large compound / closed boundary wall** as backdrop in any Ep1 clip.
- Prefer: packed-earth **village / entrance path**, grass edges, banana /
  coconut / soft roadside greens, distant tiled roofs + open thinnais.
- Soft **neighbour life** deep BG only (tiny figures, roosters, distant
  sweeping) — never steal focus from butterfly / siblings / dog / choppu.
- Whitewashed house plaster allowed only as **soft distant architecture** or
  as **Clip 12 calendar mount** — never as a box enclosing the scene.
- Low wooden entrance gate / low fence OK if open and partial (`Front_Garden.md`)
  — not a tall compound wall.

**Attachments:** Prompts are self-contained. Attach **continuity stills only**
(adjacent clip) when animating — not style/character reference cards.

## Authority

`02_World/Locations/Village_Neighbourhood.md` ·
`02_World/Locations/Front_Garden.md` ·
`02_World/Geography/Walking_Routes.md` ·
`08_Production/06_Image_Prompt_Workflow.md` ·
`09_AI_Production_System/05_Master_Animation_Prompt.md` ·
`09_AI_Production_System/21_Clip_Prompt_Formula.md` ·
`09_AI_Production_System/17_Episode_Generation_Pipeline.md` ·
`01_Canon/01_Series_Style_Lock/Color_And_Lighting_Formula.md` (seasonal + ToD locks)
