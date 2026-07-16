# Location References — Registry

## Purpose

Track permanent visual identity references for recurring locations.

**Approved PNGs** lock architecture, materials, planting, and rendering language.  
**Specs** define what a future PNG must contain before it is generated and approved.

This folder does **not** invent geography. Source truth remains `02_World/Locations/` and `02_World/Geography/`.

---

## Status legend

| Status | Meaning |
| --- | --- |
| `approved` | PNG present and cited from location bible |
| `spec_ready` | Spec written; PNG not yet generated |
| `blocked` | Location canon incomplete — do not generate yet |
| `deferred` | Reserved / low priority for first production seasons |

---

## Priority production set

Locations that should have permanent visual references for series continuity:

| Location | Expected asset | Canon source | Status |
| --- | --- | --- | --- |
| Front Thinnai | `Front_Thinnai_Canon_Design_Reference.png` | `02_World/Locations/Front_Thinnai.md` | **approved PNG — ground pending regen** (canon = packed earth, not tiles) |
| Kitchen | `Kitchen_Layout_Canon_Design_Reference.png` · `Kitchen_Cook_Window_Canon_Design_Reference.png` | `02_World/Locations/Kitchen.md` + `Kitchen/` | **layout + cook/window PNGs** — big open wood windows + dense greens locked |
| Courtyard | `Courtyard_Canon_Design_Reference.png` | `02_World/Locations/Courtyard.md` | spec_ready |
| Front Garden | `Front_Garden_Canon_Design_Reference.png` | `02_World/Locations/Front_Garden.md` | spec_ready |
| Backyard | `Backyard_Canon_Design_Reference.png` | `02_World/Locations/Backyard.md` | spec_ready |
| Water Well / Well Utility Area | `Water_Well_Canon_Design_Reference.png` | `02_World/Locations/Water_Well.md` | spec_ready |
| Vegetable Garden | `Vegetable_Garden_Canon_Design_Reference.png` | `02_World/Locations/Vegetable_Garden.md` | spec_ready |
| Livestock Shelter | `Livestock_Shelter_Canon_Design_Reference.png` | `02_World/Locations/Livestock_Shelter.md` | spec_ready |
| River Ghat | `River_Ghat_Canon_Design_Reference.png` | `02_World/Locations/River_Ghat.md` | spec_ready |
| Village Square | `Village_Square_Canon_Design_Reference.png` | `02_World/Locations/Village_Square.md` | spec_ready |
| Banyan + Vinayagar Shrine (Temple) | `Banyan_Vinayagar_Shrine_Canon_Design_Reference.png` | `02_World/Locations/Banyan_Tree_And_Vinayagar_Shrine.md` | spec_ready |
| Primary School | `Primary_School_Canon_Design_Reference.png` | `02_World/Locations/Primary_School.md` | spec_ready |
| Tea Stall | `Tea_Stall_Canon_Design_Reference.png` | `02_World/Locations/Tea_Stall.md` | spec_ready |
| Field Rest Area (neem · kattil · field well) | `Field_Rest_Area_Canon_Design_Reference.png` | `02_World/Locations/Field_Rest_Area.md` | **approved** (ep_002 sh_F05 · 2026-07-16) |

## Explicitly deferred

| Location | Reason |
| --- | --- |
| Rice Mill | Listed as reserved SE landmark on Master Map / Future Landmarks — **no location bible**. Do not invent. Create location canon first via Canon Change Process, then add a row here. |
| Grain Drying Yard | Reserved with Rice Mill — same rule. |
| Weekly Market / Bus Stop / Temple Fair / Cattle Fair | Reserved — same rule. |

## Secondary candidates (after priority set)

| Location | Canon source | Status |
| --- | --- | --- |
| Bedroom | `Bedroom.md` | deferred |
| Puja Corner | `Puja_Corner.md` | deferred |
| Stone Bridge | `Stone_Bridge.md` | deferred |
| Small Grocery Store | `Small_Grocery_Store.md` | deferred |
| Festival Ground | `Festival_Ground.md` | deferred |
| Barber / Forge / Carpenter / Potter | each craft file | deferred |
| Family House exterior establishing | `Family_House.md` | deferred (partial coverage via Thinnai + Garden) |

---

## How to add a new approved reference

1. Confirm location bible is `approved` / active.
2. Fill or update the location row in `Location_Reference_Specs.md`.
3. Generate still using Location Lock + Style Lock + Spec.
4. Review against hard gates (geography, period, Ghibli-inspired rendering, no modern drift).
5. Save PNG here with the expected filename.
6. Add **Canon Visual Reference** block to the location bible (mirror Front Thinnai pattern).
7. Flip this registry row to `approved`.

## Spec document

`Location_Reference_Specs.md` — generation briefs for all `spec_ready` locations.

## Naming

```text
[Location_Subject]_Canon_Design_Reference.png
```

Double-check `10_Studio_Standards/Asset_Naming.md` when naming multi-word places.
