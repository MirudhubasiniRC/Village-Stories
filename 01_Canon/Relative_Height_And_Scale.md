# Relative Height & Scale Reference

## Purpose

This document is the **sole authority** for relative height and scale between
recurring characters and family animals.

Any shot containing more than one character must respect this fixed scale
relationship so proportions never drift between independently generated clips.

For solo shots, use each character's absolute height in their `03_Characters/`
appearance document. For **two or more characters in frame**, this table overrides
independent height guessing.

---

# Family Scale Table

Using **Father** as baseline (tallest adult):

| Character | Height relative to Father | Absolute reference | Notes |
| --- | --- | --- | --- |
| **Father** | Baseline — tallest | 5'5"–5'7" (165–170 cm) | Lean, athletic adult male build |
| **Mother** | ~2 inches / ~5 cm shorter than Father | 5'2"–5'3" (157–160 cm) | Slim, graceful adult female build |
| **Elder Brother** | Reaches roughly **Mother's shoulder height** | 130–140 cm | Childlike proportions; clearly taller than Younger Daughter |
| **Younger Daughter** | Reaches roughly **Mother's chest / mid-torso height** | 115–125 cm | Smaller childlike proportions; noticeably shorter than Elder Brother |

**Rule:** Mother must never appear equal to or taller than Father. Elder Brother
must never appear adult-height beside Mother. Younger Daughter must never appear
shoulder-height on Mother — she tops out at chest / mid-torso.

---

# Animal Scale Anchors

| Animal | Scale relative to adults |
| --- | --- |
| **Family Dog (German Shepherd)** | Standing height reaches roughly **mid-thigh on Father** when Father is standing; noticeably taller than Younger Daughter when the dog is standing and the child is seated |
| **Family Cow** | Shoulder height roughly **chest-height on Father** |
| **Goats** | **Knee-to-thigh height** on adults |
| **Chickens** | **Ankle-to-shin height** — always clearly the smallest moving figures in a shot |

---

# Prompt Rule For Multi-Character Shots

When two or more family members appear together, include this block after character
descriptions:

```text
SCALE LOCK (relative to Father as tallest):
Father — tallest adult in frame.
Mother — visibly ~5 cm shorter than Father, slim graceful build.
Elder Brother — top of head reaches Mother's shoulder.
Younger Daughter — top of head reaches Mother's chest / mid-torso; clearly shorter than Elder Brother.
Family Dog (if standing) — mid-thigh height on Father.
```

Do not re-derive relative scale from scratch each generation.

---

# Continuity Rules

Always preserve:

- Father tallest human in every family grouping.
- Mother consistently shorter than Father by a visible margin.
- Elder Brother shoulder-height on Mother.
- Younger Daughter chest-height on Mother.
- Dog mid-thigh on standing Father.

Never:

- Make Mother equal height to Father.
- Age children into teen/adult proportions beside parents.
- Shrink Father or enlarge children to fill frame convenience.
- Let the Dog read as wolf-sized or small-pet sized beside adults.

---

# Canon Authority

This document is the permanent reference for relative height and scale.

When any conflict exists between a generated image and character appearance
documents, **this table governs multi-character proportion**.

Related documents:

- `03_Characters/Family/Father/Appearance.md`
- `03_Characters/Family/Mother/Appearance.md`
- `03_Characters/Family/Elder_Brother/Appearance.md`
- `03_Characters/Family/Younger_Daughter/Appearance.md`
- `03_Characters/Family/Family_Dog/Appearance.md`
- `09_AI_Production_System/08_Character_Lock_System.md`
