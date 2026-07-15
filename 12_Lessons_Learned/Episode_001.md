# Episode 001 — Lessons Learned

## File header

| Field | Value |
| --- | --- |
| Episode ID | `ep_001` |
| Episode title | Butterfly Morning |
| Format | YouTube Short · 9:16 · ~60–70 s · 12 clips |
| Status | Flow generation complete — edit next |
| Lesson owner | Production |
| Last updated | 2026-07-15 |
| Release ID | — |
| Linked review IDs | — |

---

## Episode Close Summary

Flow stills + animation + audio for Clips 01–12 approved. Assemble edit next.
Authority board: `10_Episodes/ep_001/04_Generation/episode-ep_001__clip-prompt-workflow__approved__r01.md`.

---

## Lessons

### LL-EP001-01 — Neighbourhood over compound wall

**Date:** 2026-07-15  
**Stage:** Image generation  
**Type:** Continuity / world  
**Severity:** High  

**What happened:** Early stills boxed the play in a cream compound wall.  
**Fix:** Follow `Village_Neighbourhood.md` — no large compound walls; open path +
greens + soft distant neighbour roofs.  
**Carry forward:** Read neighbourhood canon before outdoor episode prompts.

### LL-EP001-02 — “Soft warm / muted” bleaches colour white

**Date:** 2026-07-15  
**Stage:** Image generation  
**Type:** Colour / style  
**Severity:** High  

**What happened:** Soft-warm / muted / airy wording made greens sage and skies milky.  
**Fix:** Series lock **GENTLE COLOR POP** + slight warmth + medium-soft contrast +
slightly reduced brightness (`Color_And_Lighting_Formula.md`).  
**Carry forward:** Avoid `soft warm wash`, `muted`, `airy high-key`, `pastel`.

### LL-EP001-03 — Choppu sand idli = coconut shell demould

**Date:** 2026-07-15  
**Stage:** Story / image  
**Type:** Beat clarity  
**Severity:** Medium  

**What happened:** Palm-mould wording missed the real play.  
**Fix:** Pack wet sand into coconut shell → flip/lift away → sand idli on earth.  
**Carry forward:** Lock prop method in clip board before macros.

### LL-EP001-04 — Pose lock across MS pull-back

**Date:** 2026-07-15  
**Stage:** Image continuity  
**Type:** Continuity  
**Severity:** Medium  

**What happened:** Clip 09 made Brother stand / raise shell overhead.  
**Fix:** Explicit pose lock from prior clip (kneeling/crouching; shell on ground).  
**Carry forward:** State body height and prop hand position in continuity locks.

### LL-EP001-05 — Relative position lock (who stands where)

**Date:** 2026-07-15  
**Stage:** Image + animation continuity  
**Type:** Spatial continuity  
**Severity:** High  

**What happened:** When a later clip needs close contact (e.g. Clip 10 — dog licks
sister’s face), Flow stills from earlier clips sometimes placed the dog far from
the girl or swapped left/right order, so the cut felt like a jump.

**Rule — relative position must carry clip to clip:**

When the **same group** appears in adjacent clips (e.g. Brother + Sister + Dog),
lock **screen order, side, and proximity** from the approved prior still:

| Element | Lock in continuity block |
| --- | --- |
| **Screen order** | e.g. Sister left · Dog centre/between · Brother right (or whatever Clip 02 approved) |
| **Proximity** | If a **future clip** needs dog → girl contact, dog must stay **beside / near sister** in every intervening group shot — not across the frame, not behind brother only |
| **Facing** | All three still oriented toward the shared action (pot, sand idli, etc.) |
| **Camera side** | Same camera side as prior clip — no flip |

**Example (ep_001):**

- Clip 02: siblings + dog discover butterfly at pot — dog **between or beside sister**, close cluster.  
- Clips 06–09: choppu play — dog **still near sister/brother cluster**, not wandering far BG.  
- Clip 10: dog lick — only works if prior still already had dog **next to sister**.

**Fix in prompts:** Add to every **CONTINUITY LOCK** after Clip 02:

```text
RELATIVE POSITION LOCK:
- Screen order: [Sister | Dog | Brother] — same as approved Clip 02
- Dog stays beside/near Younger Daughter (within lick distance) when all three present
- No wide empty gap between dog and sister if Clip 10 dog-lick follows
```

**Carry forward:** Before generating Clip N, read approved Clip N-1 still and
**write relative positions explicitly** — not only wardrobe and lighting. If the
storyboard needs a new layout, treat it as a new approved still, not silent drift.

### LL-EP001-06 — Short Flow duration on busy macros

**Date:** 2026-07-15  
**Stage:** Animation  
**Type:** Tool / Flow  
**Severity:** Medium  

**What happened:** Long Omni/Flash duration vanished props on choppu macros.  
**Fix:** Prefer ≤5 s + object-permanence locks; optional same-still two-image.  
**Carry forward:** Keep choppu macros short in Flow.

### LL-EP001-07 — Scale and identity drift (children / dog / Mother)

**Date:** 2026-07-15  
**Stage:** Image generation  
**Type:** Character  
**Severity:** Medium  

**What happened:** Brother aged up; dog became puppy; skin too fair; Mother hair
went brown with round face drift.  
**Fix:** Hard locks — Brother age 9, sister 6, adult GSD; skin `#E8C89A`–`#F0D8B0`;
Mother oval + almond eyes + black half-up + jhumkas.  
**Carry forward:** Put scale/skin/hair locks in every multi-character image prompt.

---

## Follow-ups for Ep2+

- Start outdoor episodes on open neighbourhood language from Clip 01.
- Use GENTLE COLOR POP wording from first prompt.
- Keep storyboard/docs in sync when clip count changes mid-shoot.
- **Relative position lock:** when boy + girl + dog share a clip, state screen
  order and proximity in continuity — especially if a later clip needs physical
  contact (dog lick, hand give, hug). Dog near girl in Clip 2 → dog still near
  girl before Clip 10.
