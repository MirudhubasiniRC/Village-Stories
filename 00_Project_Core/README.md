# Village Stories

## Overview

Village Stories is a long-running animated universe set in an authentic 1990s South Indian village. The project combines emotional storytelling, slow living, ASMR, and Studio Ghibli-inspired digital anime aesthetic with painterly digital rendering, simulated watercolor and gouache textures, and soft cel-style shading blended with brushwork — India as setting — while remaining grounded in the traditions, architecture, culture, and daily life of rural South India.

This repository serves as the **single source of truth** for the entire production pipeline. Every story, character, location, prompt, and production asset must follow the documentation contained within this project.

The objective is not simply to create individual videos, but to build a living, persistent world where viewers gradually become familiar with the people, places, traditions, and rhythms of village life.

---

# Core Principles

* Authentic 1990s South Indian village life.
* Emotional, family-centered storytelling.
* Relaxing ASMR pacing.
* Persistent world with long-term continuity.
* Historically accurate objects, customs, occupations, and daily routines.
* High production quality suitable for a long-running animated series.

---

# Repository Structure

```text
00_Project_Core      → Project identity, workflow, AI operating instructions
01_Canon             → Rules that never change
02_World             → Geography, locations, environment, seasons, culture
03_Characters        → Character profiles and relationships
04_Objects           → Recurring tools, furniture, vehicles and household items
05_Research          → Historical research and forgotten details of the era
06_Story_Engine      → Story structure, hooks, themes and episode planning
07_Episode_System    → Episode form, pacing, Shorts / long-form design
08_Production        → Episode production workflow and studio handbook
09_AI_Production_System → Prompt modules, locks, Flow, generation pipeline
10_Episodes          → Episode packages and archive
10_Studio_Standards  → Naming, folders, quality, review, and release governance
11_Assets            → Reference images and production assets
11_Templates         → Fillable production forms (copy into episodes)
12_Lessons_Learned   → Episode evidence + continuous improvement registers
12_Quality_Assurance → Pointer only (QA lives in Standards / Production)
Archive              → Deprecated or historical documents
```

Numbering collisions (`10_*`, `11_*`, `12_*`) are documented in
`01_Canon/08_Project_Maintenance/Folder_Migration_Plan.md`.

---

# Documentation Philosophy

Each document has **one responsibility only**.

Information should never be duplicated across multiple files. Every topic has a single authoritative location, and all other documents should reference it instead of repeating it.

This keeps the project organized, scalable, and reliable for both humans and AI.

---

# Canon First

Before creating or modifying any story, storyboard, prompt, or production asset:

1. Follow the Canon.
2. Preserve continuity.
3. Respect the persistent world.
4. Never contradict established facts without intentionally updating the Canon.

---

# Long-Term Vision

Village Stories is designed as a living animated universe capable of supporting hundreds of interconnected episodes while maintaining consistent characters, locations, history, visual identity, and emotional tone.

Every new episode should strengthen the world rather than reinvent it.
