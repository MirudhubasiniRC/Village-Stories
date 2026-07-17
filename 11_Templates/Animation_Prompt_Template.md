# Animation Prompt Template

**Gate:** Use only after the clip still is approved. Preserve the source image(s).

| Field | Value |
| --- | --- |
| Episode ID | `ep_` |
| Clip / Shot ID | |
| Approved source still | |
| Previous approved end frame (continuity) | [path / clip ID — REQUIRED] |
| Status | draft / in_review / approved |
| Revision | r03 |
| Flow mode | One-image / **Two-image** (decide — see below) |
| Duration | [seconds] — always state beat breakdown |
| Camera choice | Static / Locked / Slow Push In / Slow Pull Out / … + **why** |

Authority: `09_AI_Production_System/21_Clip_Prompt_Formula.md` ·  
`13_Google_Flow_Best_Practices.md` · `05_Master_Animation_Prompt.md` ·  
`20_Camera_Movement_Bible.md`

**Production rules:**

1. Deliver **Animation + Audio together** with explicit **Duration**. Character motion speed = **Normal Speed**.
2. **Think continuity first** (LL-EP002-02): Do not wait for producer pushback. Before writing the prompt, decide one-image vs two-image and name Begin→End.
3. **Use the Camera Movement Bible** (LL-EP002-03): Do not default to Static out of habit. Run preference order; if moving, use named moves (**Slow Push In**, **Slow Pull Out** = push-back, Pan, Tilt, short Truck/Dolly). Fill all five Flow camera fields every time.

---

## Pre-flight (CD fills — mandatory)

Answer before drafting:

| Question | Answer |
| --- | --- |
| Previous approved end frame? | |
| Does this beat **change state** from that frame (run→stop, empty→hug, ask→point)? | Yes → **prefer Two-image** · No → One-image OK |
| Story relation readable in silhouette? (win / lose / arrive / comfort) | |
| Camera purpose? (hold / emotion push in / return to context pull out / follow small action) | |
| Chosen camera from Bible preference order | |

### When to use Two-image (default yes if…)

- Prior approved clip **end state** is the true begin of this motion
- Beat is **decelerate / stop / result** after travel or race
- Begin and end compositions **materially differ** and both are approved stills
- Spatial story (e.g. **winner ahead · loser behind**) must survive the interpolate

### Camera vocabulary (use these names)

| Say this | Means |
| --- | --- |
| Static / Locked Camera | No travel / no reframing |
| Slow Push In | Camera moves slightly **forward** toward subject (emotion / realization) |
| Slow Pull Out | Camera moves slightly **back** (push-back) — reveal context / shared space / result |
| Pan Left / Right · Tilt Up / Down | One-axis only |
| Short Truck / Short Dolly | Rare · bounded path only |

**External / AI terms:** translate via `20_Camera_Movement_Bible.md` § **Flow Synonym Map**
(e.g. "tracking" → Truck, "reveal" → Slow Pull Out). Never paste vague cinematic
synonyms into Flow.

Never combine two move types in one clip. Speed words: `none` / `nearly imperceptible` / `very slow` / `slow` / `measured` — never `fast` / `cinematic` / `dramatic`.

---

## CLIP [Number] — Animation Prompt

```text
CLIP [Number] — Animation Prompt

SERIES STYLE LOCK — APPLY TO ALL ANIMATIONS

STYLE LOCK INSTRUCTIONS:
- PRESERVE exact [characters / props / location facts from approved still(s)].
- DO NOT reinterpret, redesign, or "improve" characters, clothing, environments, props.
- DO NOT change skin tone, hair, facial features, or clothing colours.
- DO NOT add or remove objects, furniture, or architectural details unless board allows.
- PRESERVE Studio Ghibli-inspired DIGITAL anime — painterly soft matte — not photoreal.
- PRESERVE lighting family and light direction from source image(s).
- PRESERVE geography / screen direction / open-neighbourhood locks when present.
- PRESERVE story silhouette locks (e.g. winner ahead · loser behind) through whole clip.
- ONE principal visible action chain only.

CONTINUITY DECISION:
Previous approved end: [Clip / still ID]
Flow mode: One-image / Two-image
Reason: [state change? spatial win? lip line? hold?]

Input Specification:
Input Type: Single Image / Two Images
Number of Images: 1 / 2
Source Image 1 (BEGIN): [approved still — e.g. prior clip END if two-image]
Source Image 2 (END): [approved still — only if two-image]

Begin → End Continuity Contract:
BEGIN: [pose / positions / emotion]
END: [pose / positions / emotion]
Must not: [teleport · swap who is ahead · reverse screen direction · new location]

Animation Source:
Mode: Single Image / Two Image
Duration: [N] seconds — [beat breakdown]

CAMERA (required — from Camera Movement Bible):
Camera Direction: [start side / height / shot size]
Camera Movement: [Static / Locked Camera / Slow Push In / Slow Pull Out / Pan Left|Right / Tilt Up|Down / Short Truck|Dolly]
Movement Speed: [none / nearly imperceptible / very slow / slow / measured]
Framing Stability: Start [ ] → End [ ] · same camera side · protect [faces / hands / win gap]
Subject protection: [what must stay readable]
Why this camera: [one line — or “Locked because hold/micro only”]
Prohibitions: No second move · no zoom · no orbit · no handheld · no recompose geography

Character Motion (Normal Speed):
[Character]: [exact motion] — [locks]

Environment Motion (Normal Speed):
[Element]: [motion or locked solid]

Micro Motion (Normal Speed):
[Optional tiny living world]

Motion Priority:
1. [Primary — usually Begin→End story]
2. [Camera if moving — never fights character action]
3. Everything else locked

End Frame: [readable end — match Image 2 if two-image]

Quality Lock: Avoid [continuity breaks, wrong who-ahead, unwanted Static-only laziness if push earned, etc.]

Pacing: Normal speed — [beat intent].
```

### Example — race finish (ep_002 sh_007 pattern)

```text
Flow mode: Two-image
Source Image 1: sh_006 END — mid-run · dog ahead · L→R
Source Image 2: sh_007 — both stopped · dog ahead win · girl trailing cry
Begin→End: RUN → STOP → dog HOLDS win ahead → girl CRRIES
Camera Movement: Slow Pull Out (very slow) OR Locked Camera
Why: Pull out reveals win gap in space; Locked if pull risks losing faces — pick one.
```

### Example — near-still + fade (calendar / title card)

```text
Duration: 6 seconds — ~4 s hold + ~2 s fade to black
Camera Movement: Locked Camera · Movement Speed: none
Character Motion: NONE
Fade (end only): 4.0–6.0 s gentle fade to black
End Frame: Full black — episode end
```

---

## CLIP [Number] — Audio / ASMR Prompt (deliver with animation)

```text
CLIP [Number] — Audio / ASMR Prompt

Duration Match: Align to picture [N] seconds.

Primary Sounds (Visible Actions):
[sound timed to Begin→End beats]

Environmental Ambience:
Village: [beds]
Home / place: [beds]

Dialogue:
NONE / [Speaker]: "[line]" at [time window] — English · Indian accent (if locked)

Audio Mix Priority:
1. [primary]
2. [supporting]
3. [silence / fade]

Fade behaviour (if any):
[…]

Continuous Ambience: [bridge from previous clip — REQUIRED]

No: […]
```

---

## Fill checklist before send

- [ ] Previous approved end frame named  
- [ ] One-image vs two-image **decided with reason** (not habit)  
- [ ] Begin→End contract if two-image or state change  
- [ ] Story silhouette lock (win/lose/arrive) if relevant  
- [ ] **All five camera fields** filled · move named or Locked + why  
- [ ] Slow Push In / Slow Pull Out considered when emotion or context earns it  
- [ ] Duration + beat breakdown  
- [ ] Style lock lists shot-specific PRESERVE facts  
- [ ] One principal action chain · Normal Speed  
- [ ] Audio in same message · continuous ambience bridge  

**Handoff:** After Flow approve → next IMAGE PROMPT only (phased).
