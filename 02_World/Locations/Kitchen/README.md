# Kitchen Documentation

## Purpose

This folder contains the complete production documentation for the Family Kitchen.

The Kitchen is the primary storytelling location of the Village Stories universe and therefore requires a level of detail beyond that of a standard location.

Rather than placing all information inside a single document, the Kitchen is divided into specialized files.

Each file has a single responsibility, reducing duplication and improving long-term maintainability.

---

# Folder Structure

```
Kitchen/

├── README.md
├── Architecture.md
├── Raised_Clay_Stove.md
├── Storage.md
├── Traditional_Tools.md
├── Workflows.md
├── Lighting_And_Atmosphere.md
├── Camera_Language.md
└── Continuity.md
```

---

# File Responsibilities

## Architecture.md

Defines the physical structure of the Kitchen.

Includes:

* Room dimensions
* Orientation
* Doors
* Windows
* Ventilation
* Permanent layout
* Work zones

This file answers:

**"What does the Kitchen look like?"**

---

## Raised_Clay_Stove.md

Defines the permanent cooking system.

Includes:

* Clay stove
* Burners
* Firebox
* Smoke
* Fire behaviour
* Ash
* Cooking positions

This file answers:

**"How is cooking performed?"**

---

## Storage.md

Defines permanent storage areas.

Includes:

* Firewood
* Brass vessels
* Clay pots
* Water storage
* Ingredient storage
* Preparation surfaces

This file answers:

**"Where is everything stored?"**

---

## Traditional_Tools.md

Defines every traditional cooking tool.

Includes:

* Ammikkal
* Aatukkal
* Aruvamanai
* Ural & Ulakkai
* Coconut scraper
* Sieves
* Bamboo baskets
* Other recurring kitchen tools

This file answers:

**"Which tools are used and where do they belong?"**

---

## Workflows.md

Defines how cooking happens.

Includes:

* Ingredient preparation
* Washing
* Grinding
* Cooking
* Serving
* Cleaning
* Morning routine
* Evening routine
* Festival cooking

This file answers:

**"How does a meal move through the Kitchen?"**

---

## Lighting_And_Atmosphere.md

Defines environmental behaviour.

Includes:

* Natural lighting
* Seasonal lighting
* Steam
* Smoke
* Rain
* Breeze
* Audio
* Smells
* Environmental interactions

This file answers:

**"How does the Kitchen feel?"**

---

## Camera_Language.md

Defines visual storytelling.

Includes:

* Establishing shots
* Signature compositions
* Garden Window framing
* Clay stove framing
* Steam shots
* ASMR close-ups
* Character blocking

This file answers:

**"How should the Kitchen be filmed?"**

---

## Continuity.md

Defines permanent production rules.

Includes:

* Things that never change
* Canon restrictions
* Object permanence
* Relationship with other locations
* Cross references

This file answers:

**"What must always remain consistent?"**

---

# Relationship With Other Documents

This folder expands the master document:

```
Locations/
└── Kitchen.md
```

The master document defines the Kitchen's purpose and identity.

The files in this folder define every permanent production detail.

---

# Relationship With Objects

This folder defines **spaces**.

Individual cooking equipment belongs in:

```
04_Objects/
```

Example:

```
04_Objects/

Clay_Pot.md
Brass_Uruli.md
Ammikkal.md
Aatukkal.md
Wooden_Ladle.md
Clay_Stove_Poker.md
```

Kitchen files describe where these objects belong.

Object files describe the objects themselves.

---

# Design Philosophy

Each document should answer one question only.

Avoid repeating information across files.

When new information is added, place it in the document whose responsibility best matches that information.

This modular structure ensures long-term consistency, easier maintenance, and better retrieval by AI assistants.

---

# Canon Authority

This folder contains the complete canonical documentation for the Family Kitchen.

Every story, storyboard, image prompt, animation, and production document involving the Kitchen should reference these files together with the master `Kitchen.md`.
