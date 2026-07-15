# Style Consistency Decision

## Decision (2026-07-15)

**Permanent series style name:**

> Studio Ghibli-inspired digital anime aesthetic

As defined in `01_Canon/01_Series_Style_Lock/Art_Style.md`.

India supplies setting and culture. The rendering language is soft, warm,
painterly Ghibli-inspired digital anime — not Indian folk-art saturation, not
photoreal, not generic modern TV anime.

**Creative Director lock:** This is the one approved external reference name.
Do not replace it with a fully anonymised paraphrase that fights Art_Style.md,
Clip Prompt Formula, or Mother/Father reference enforcement.

---

## Permanent rule (apply everywhere)

1. Prompts and manuals **must** use the official Studio Ghibli-inspired lock wording when stating series style.
2. Do **not** name, imitate, or invoke any **other** studio, artist, film, franchise, or property (Disney, Makoto Shinkai, Kyoto Animation, Pixar, etc.).
3. Character reference PNGs remain identity/rendering anchors alongside the style name.
4. Failure examples that say “Make it look like [named studio]” still apply to **unauthorized** names — they do not ban the official Ghibli-inspired lock.

---

## Inconsistency found

| Document | Conflict |
| --- | --- |
| `Art_Style.md`, Clip Formula, templates, most locks | Use Studio Ghibli-inspired… |
| `08_Character_Lock_System.md` | “Never name or imitate an external studio…” |
| `14_Prompt_QA.md` | “without naming or imitating external studios…” |
| `17_Episode_Generation_Pipeline.md` | “Never name or imitate another studio…” |
| `04_Master_Image_Prompt.md` | “No named studio…” |
| `19_Camera_Direction_Bible.md` | “Do not name… a studio…” |

These absolute bans fought the approved Art Style.

---

## Recommended permanent replacement sentence

Use this wherever an absolute “never name a studio” line appears:

```text
Use the official Studio Ghibli-inspired digital anime aesthetic
(see Art_Style.md). Do not name or imitate any other external studio,
artist, film, franchise, or property.
```

---

## Implementation status

| Action | Status |
| --- | --- |
| Decision recorded | Done (this file) |
| Conflict lines updated to allow Ghibli-inspired exception | Done (same maintenance pass) |
| Full prose audit of every Appearance file | Not required — already Ghibli-aligned |

---

## What we are not doing

- Not inventing a new trademarked style brand name.
- Not removing Ghibli references from Clip Formula or Art_Style.
- Not allowing “make it look like [any anime]” improvisation.
