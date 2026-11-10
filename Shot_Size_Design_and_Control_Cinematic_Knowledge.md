# Shot Size Design and Control — Cinematic Knowledge Base

**File:** `Shot_Size_Design_and_Control_Cinematic_Knowledge.md`
**Purpose:** Teach a filmmaker or an AI filmmaking assistant how to select, specify, generate, evaluate, and correct **shot size** (cinematic framing scale) in images and video.
**Scope lock:** This file is about shot size only. Camera distance, lens choice, camera angle, composition, aspect ratio, cropping, and camera movement appear here *only* where they directly affect shot-size decisions or help distinguish related concepts. Each of those disciplines has its own dedicated knowledge base, and this file does not replace them.

---

## How to Use This File

**For a human filmmaker:** Read Sections 1–2 for the mental model, use Sections 3–4 as a framing reference, and use Sections 13 and 15 as working tools on set or in review.

**For an AI system:** Treat this file as a decision procedure. The operating loop is:

1. Define what the audience must see, understand, or feel *through information* (Sections 1–2).
2. Choose a shot size by landmarks, not by names alone (Sections 3–4).
3. Specify the shot with boundaries, margins, and scale, not just a label (Section 12).
4. Check composition, continuity, and progression (Sections 7, 9, 10).
5. Verify against observable acceptance criteria (Section 15).
6. If the result fails, diagnose in a fixed order and change one thing at a time (Section 13).

**Epistemic conventions used in this file.** Shot-size terminology is a working vocabulary, not a standard. This file marks the difference:

- **Convention (widely used)** — a definition or practice common across many productions.
- **Variable** — a term or boundary that differs between countries, crews, studios, or traditions. When a request depends on it, specify landmarks instead of the name.
- **Approximate** — a number or boundary that is a practical guide, not a measured fact.
- **Context-dependent effect** — a possible audience effect that depends on story, performance, light, angle, lens, and cutting. Nothing in this file claims that a shot size guarantees a particular emotion.

**Terminology rule.** Technical terms are defined the first time they appear.

---

## Table of Contents

1. Shot-Size Fundamentals
2. Shot-Size Decision Framework
3. Shot-Size Taxonomy
4. Shot-Size Boundaries and Subject Visibility
5. Shot Size and Narrative Purpose
6. Shot Size, Camera Distance, and Lens
7. Shot Size and Composition
8. Shot Size and Audience Experience
9. Shot Size and Continuity
10. Shot-Size Progression Across a Scene
11. Shot Size for Action and Moving Subjects
12. AI Image and Video Generation
13. Shot-Size Failure Diagnosis and Correction
14. Practical Case Studies
15. Quality Control and Final Verification
16. Quick Reference

---

# 1. SHOT-SIZE FUNDAMENTALS

## 1.1 A Precise Definition

**Shot size** is *how much of the principal subject is visible within the frame, and therefore how large the subject appears relative to the frame*, described in terms of the subject's own landmarks (for example, "head to toe," "waist up," "eyes only").

Three parts of this definition do real work:

| Phrase | What it means in practice |
|---|---|
| **"how much of the principal subject"** | Shot size is measured against a *chosen subject*. The same image can be a close-up of a ring and a medium shot of the hand wearing it, depending on which is the principal subject. |
| **"how large the subject appears relative to the frame"** | It is a ratio of subject to frame, not a measurement in meters or pixels. |
| **"in terms of the subject's own landmarks"** | Names such as "medium shot" only mean something when tied to landmarks (waist, shoulders, eyes). For non-human subjects, landmarks must be redefined. |

**Mechanism (established craft principle).** The frame is a window that selects information. Shot size controls the *ratio of subject information to environment information* inside that window. Tighter shot sizes show more detail of less; wider shot sizes show less detail of more.

## 1.2 What Shot Size Controls

| Dimension | Tighter shot size | Wider shot size |
|---|---|---|
| **Subject detail** | More (texture, micro-expression, small gestures) | Less (posture, silhouette, overall movement) |
| **Environment information** | Less (location, other people, geography become limited or hidden) | More (location, scale, other subjects, spatial relationships) |
| **Visual attention** | Concentrated on a narrow area; fewer competing points | Distributed; the viewer scans and chooses |
| **Spatial information** | Weaker (position is inferred) | Stronger (position is shown) |
| **Subject importance** | Often conveys priority, because the frame is devoted to the subject | Importance depends on placement and contrast; a subject may be small yet central |
| **Perceived emotional distance** | Tends to feel closer (context-dependent) | Tends to feel more observational (context-dependent) |
| **Vulnerability and isolation** | Vulnerability can increase when the person has no visible escape; isolation is harder to show | Isolation can be shown through empty space; vulnerability can be shown through scale |
| **Audience understanding** | Risk: confusion about where and with whom | Risk: missing the small but important detail |

## 1.3 Shot Size Is a Framing Decision, Not an Emotion

**Principle:** A shot size selects *information*. It does not, by itself, create an emotion. Emotion arises when the selected information interacts with the story, the performance, the lighting, the sound, and the audience's expectations.

- A close-up of a face shows the face. Whether it feels intimate, threatening, or tedious depends on what the face is doing, what the viewer knows, what angle and lens were used, and what came before.
- A wide shot of a person in a field shows both. Whether it feels lonely, free, or peaceful depends on the story and the person's behavior.

**Design consequence:** Choose shot size to deliver the *information* the scene needs. Then confirm that the surrounding choices produce the intended feeling. If a scene needs an emotion, do not assume the shot size will supply it.

## 1.4 Subject Scale vs. Physical Size

- **Physical size** is how big the subject actually is (a 1.8 m person, a 2 cm coin).
- **Subject scale** is how large the subject *appears in the frame* (for example, the person's height occupies 30% of the frame height).

Physical size does not determine shot size. A coin can fill the frame (extreme close-up) and a mountain can be a tiny shape (extreme wide shot). What matters is the ratio of subject to frame.

**Practical consequence for AI work:** "A tiny object" is not a shot size. "The coin fills most of the frame" is a shot size.

## 1.5 Same Subject, Different Shot Sizes

The same subject, in the same location, can be shown at multiple shot sizes without changing identity:

| Shot | What is visible | What the viewer gets |
|---|---|---|
| Extreme wide | A woman is a small figure on a long pier | Location, mood of space |
| Full shot | Her whole body at the pier's end | Posture, costume, her relation to the water |
| Medium shot | Waist up, the pier behind her blurred | Gesture, attitude |
| Close-up | Face, with water-light on her cheek | Expression |
| Detail | Her hand on the rail | A tiny nervous action |

**Principle:** Identity and location are constants; *selection of information* is the variable. This is why coverage (the set of shots filmed for a scene) usually contains several shot sizes of the same action.

## 1.6 Shot Size Works With Other Information

Shot size is only one of several things that determine what a viewer learns from a shot:

- **Narrative purpose** — why the shot exists.
- **Subject behavior** — what the subject does inside the frame.
- **Surrounding visual information** — what else the frame includes or leaves out.
- **Earlier and later shots** — the viewer compares the shot with neighbors.

A shot size is *appropriate* when it delivers the information the scene needs at that moment, in a way that connects to neighboring shots.

## 1.7 Distinguishing Shot Size From Related Concepts

| Concept | Question it answers | How it differs from shot size |
|---|---|---|
| **Shot size** | How much of the subject is in the frame? | — |
| **Camera angle** | From which direction (above, below, side) is the subject seen? | A close-up can be high-angle, low-angle, or eye-level. Size and angle are independent. |
| **Camera-to-subject distance** | How far is the camera from the subject? | Distance is a physical quantity; shot size is the visible result of distance *and* lens *and* sensor. The same distance gives different shot sizes with different lenses. |
| **Focal length and field of view** | How wide is the visible area from a position? | Focal length is a property of the lens. It affects the framing available from a given position, but it is not the shot size. |
| **Aspect ratio and frame dimensions** | What is the shape of the frame? | A "medium shot" in a vertical 9:16 frame and a horizontal 16:9 frame have the same body landmarks but different amounts of environment on the sides. |
| **Composition and subject placement** | Where in the frame is the subject and how is the frame balanced? | A medium shot can place the subject at left, center, or right. Placement does not change shot size. |
| **Digital cropping or reframing** | Was the framing changed after capture? | Cropping can produce a tighter shot size from a wider capture, but without changing perspective and at a cost in resolution (Section 6). |
| **Camera movement** | Does the camera move during the shot? | A moving camera can change shot size *during* the shot (a push-in goes from medium to close-up). Shot size describes a moment or a range, not the movement. |
| **Apparent size of an object** | How big does a particular object look? | An object near the lens can look huge while the principal subject's shot size is unchanged. Shot size is measured against the principal subject. |

## 1.8 Common Misconceptions

| Misconception | Correction |
|---|---|
| "Close-ups are always emotional." | A close-up shows detail. It can show a letter, a gun, a clock, or a face with no expression. Emotional effect depends on content and context. |
| "Wide shots are always impersonal." | A wide shot can be intimate if two people sit close together in a quiet room, or devastating if a person's smallness is the point. Impersonality is not built in. |
| "A medium shot is neutral." | Neutrality depends on what the shot includes and withholds. A medium shot that crops out a character's hands hides information. |
| "Shot size equals lens." | The same shot size can be achieved by different lenses and distances. |
| "Closer camera equals closer shot." | A long lens from far away can give a close-up. A wide lens from close by can give a wide shot. |
| "There is one standard definition for each name." | Terminology varies (Section 3). Use landmarks to be precise. |
| "Tighter is always more dramatic." | Over-tight framing may hide the information that makes the moment dramatic. |
| "More shot sizes means better coverage." | Coverage is useful only if each shot has a purpose and the cut between them is motivated. |

---

# 2. SHOT-SIZE DECISION FRAMEWORK

Choosing shot size is a **repeatable sequence of decisions**. Skipping steps leads to arbitrary framing.

## 2.1 The Ten Steps

### Step 1 — Identify the scene's narrative purpose
**What:** State what this shot must accomplish in the story.
**Why:** A shot with no purpose is decoration and often hides or shows the wrong thing.
**How:** Complete: *"After this shot, the viewer knows/feels/expects ______."*

### Step 2 — Determine what the audience must understand or notice
**What:** List the information the viewer must receive: who, where, what, how they feel, what changes.
**Why:** The shot size must deliver this information. Anything essential that is outside the frame is lost.
**How:** Make a short list of *must-see* items and *must-not-see* items (information to withhold).

### Step 3 — Decide how much environmental context is necessary
**What:** Determine whether the location, other people, or geography must be visible.
**Why:** Environmental information is the first thing lost as the frame tightens.
**How:** If the viewer would be confused about *where* or *with whom* without it, the frame must be wider or the information delivered in another shot or by sound.

### Step 4 — Identify the primary information carrier
**What:** Decide whether the most important information is **facial expression, body language, physical action, object detail, or spatial relationship**.
**Why:** Each carrier has a typical minimum shot size at which it becomes readable (Section 2.3).
**How:** Pick one primary carrier per shot.

### Step 5 — Select the amount of subject visibility
**What:** Choose the shot size by **landmarks** (for example, "waist up").
**Why:** Landmarks make the choice testable.
**How:** Use the ladder in Section 3.1 and the landmarks in Section 4.

### Step 6 — Consider position, movement, and relationships
**What:** Check where the subject is, how it moves, and how it relates to other subjects.
**Why:** A subject that walks toward the camera will pass through multiple sizes; a pair of subjects requires a frame that holds both.
**How:** Plan the start and end sizes for moving subjects; check whether other subjects must be included.

### Step 7 — Check information and distraction
**What:** Confirm that the frame includes needed information without distracting detail.
**Why:** The frame should contain what matters and exclude what competes.
**How:** Scan the frame edges for intruding objects, bright spots, and partial people.

### Step 8 — Consider continuity with neighboring shots
**What:** Compare with the preceding and following shot sizes and angles.
**Why:** A cut between nearly identical framings can look like a mistake; a cut between mismatched scales can disorient.
**How:** Apply the guidance in Section 9.

### Step 9 — Test for revealing too much or hiding essential information
**What:** Check the shot against the *must-see* and *must-not-see* list.
**Why:** The most common framing failures are an essential detail left out or a withheld detail shown.
**How:** Ask: "What does the viewer know after this shot that I did not intend? What do they miss?"

### Step 10 — Define observable acceptance criteria
**What:** Write statements about the frame that can be checked by looking.
**Why:** "Looks right" cannot be verified.
**How:** Example: "Entire body visible with about one hand-width of space above the head and below the shoes; subject occupies about 60% of the frame height; no other person visible."

## 2.2 The Shot Specification Block (Compact Output)

```
SHOT SPECIFICATION
Purpose:               [what the shot does]
Must see / must not:   [information to show / withhold]
Primary carrier:       [expression / body language / action / object / spatial relationship]
Shot size:             [name] — landmarks: [top boundary] to [bottom boundary]
Subject scale:         [approx. % of frame height or width]
Margins:               [headroom / footroom / looking room / lead room]
Environment included:  [what must remain visible]
Neighbors:             [previous shot size → this → next shot size]
Acceptance criteria:   [3–6 observable statements]
```

## 2.3 Minimum Readability by Information Carrier

**Approximate guide** (depends on resolution, screen size, lighting, and performance):

| Information carrier | Typically readable from about | Becomes clearer at | Risk of going wider | Risk of going tighter |
|---|---|---|---|---|
| **Location / geography** | Very wide to wide | Establishing wide | Subject becomes tiny | Location disappears |
| **Body language / posture** | Full shot to medium long | Medium long | Face unreadable | Posture and limbs lost |
| **Gesture with arms** | Medium long to medium | Medium | Gesture too small | Hands cut off |
| **Facial expression** | Medium close-up and tighter | Close-up | Expression is lost | Face fills frame; body context lost |
| **Eyes and micro-expression** | Close-up to extreme close-up | Extreme close-up | Unreadable | Loses overall face and context |
| **Small objects, text, clues** | Close-up to detail shot | Insert/detail | Unreadable | Loses relation to the person |
| **Spatial relationship between two people** | Two-shot at medium to wide | Wide two-shot | Faces hard to read | Relationship lost |
| **Full physical action** | Full shot to medium long | Full | Action too small | Action cropped |

## 2.4 Practical Decision Tree

```
START
│
├─ Q1. Can I state what this shot must accomplish in one sentence?
│    ├─ NO  → STOP. Define purpose first.
│    └─ YES → continue
│
├─ Q2. What must the viewer SEE and what must they NOT yet see?
│    └─ Write both lists.
│
├─ Q3. Is location or geography essential for understanding?
│    ├─ YES → Is it already established by an earlier shot?
│    │        ├─ YES → a tighter shot may be used now.
│    │        └─ NO  → choose a wide / very wide / establishing frame, or a
│    │                  medium frame with clear environmental landmarks.
│    └─ NO  → continue
│
├─ Q4. What is the primary information carrier?
│    ├─ Spatial relationship    → two-shot / group / wide
│    ├─ Whole-body action       → full shot or medium long shot
│    ├─ Gesture / posture       → medium long to medium
│    ├─ Facial expression       → medium close-up to close-up
│    ├─ Eyes / micro-expression → close-up to extreme close-up
│    └─ Object / clue / text    → insert / detail / object close-up
│
├─ Q5. Does the subject move enough to leave the frame?
│    ├─ YES → widen one step or plan a tracking/reframing move; check lead room.
│    └─ NO  → continue
│
├─ Q6. Are other subjects needed in frame (relationship, reaction, threat)?
│    ├─ YES → choose a multi-subject frame (two-shot, group, OTS) at the minimum size
│    │        that keeps each necessary subject readable.
│    └─ NO  → single-subject framing.
│
├─ Q7. Does this shot connect to its neighbors?
│    ├─ Nearly identical size/angle to the previous shot → change size by at least
│    │   one clear step, or change angle, or merge shots (Section 9).
│    └─ Mismatched scale without reason → adjust, or mark as deliberate contrast.
│
├─ Q8. Does the frame reveal too much or hide essential information?
│    ├─ YES → widen (to show) or tighten/partially frame (to withhold).
│    └─ NO  → continue
│
└─ Q9. Write acceptance criteria. PROCEED, then verify with Section 15.
```

## 2.5 Choosing Among Several Plausible Shot Sizes

When more than one size could work:

1. **Compare what each reveals and conceals** (Section 5 provides comparisons).
2. **Choose the tightest size that still delivers all must-see information.** This keeps the frame efficient and focused.
3. **Choose the widest size that still delivers the primary carrier clearly** when context matters more than detail.
4. **Prefer the size that fits the neighbors.** If the previous shot is a medium and the next is a close-up, a medium close-up between them may be redundant.
5. **Break ties by information to withhold.** The frame that withholds the required information wins.
6. **If still tied, shoot or generate both** and decide in the edit or review; record the tie as a coverage choice rather than a design decision.

## 2.6 Diagnosing an Unsuitable Choice

| Symptom | Probable problem | First check |
|---|---|---|
| Viewer cannot tell where the action happens | Frame too tight; missing environment | Is location established elsewhere? |
| Viewer cannot read the character's reaction | Frame too wide; face too small | Does the face occupy enough of the frame to read? |
| Important object is unreadable | Frame too wide or object obscured | Is the object large enough, in focus, and unblocked? |
| Frame feels crowded or cramped | Tight frame with extra subjects or insufficient margins | Are margins and cropping appropriate? |
| Frame feels empty with no purpose | Wide frame without a reason | Does the empty space carry meaning? |
| Cut feels like a mistake | Neighboring shot sizes too similar | Compare sizes, angles, and positions |
| Action is cropped | Frame too tight for the movement | Plan the full path of the action |

---
# 3. SHOT-SIZE TAXONOMY

## 3.1 The Shot-Size Ladder (Working Reference)

For a **standing human subject** in a **horizontal frame**, shot sizes form an ordered ladder from the widest to the tightest. The percentages describe the approximate share of the *frame height* that the subject's full height would occupy (for tighter shots, the share the visible part occupies is the entire frame, so landmarks are used instead).

| Rung | Common name | Landmark boundary (approximate) | Approx. subject height as share of frame |
|---|---|---|---|
| 1 | Extreme wide / extreme long shot | Subject tiny, barely identifiable; environment dominates | Under about 5% |
| 2 | Very wide shot | Subject small but recognizable as a person | About 5–15% |
| 3 | Wide / long shot | Whole body clearly visible within a large environment | About 15–40% |
| 4 | Full shot | Head to toe fills most of the frame | About 50–90% |
| 5 | Medium long shot | Top of head to about the knees | Subject cropped near the knees |
| 5b | Cowboy / American shot | Top of head to about mid-thigh | Cropped above the knees |
| 6 | Medium shot | Top of head to about the waist | Cropped at or near the waist |
| 7 | Medium close-up | Top of head to about mid-chest | Cropped at mid-chest |
| 8 | Close-up | Face and a little neck/shoulder | Face fills most of the frame |
| 9 | Extreme close-up | Part of the face or a small detail | Detail fills the frame |

**Ladder rules:**

1. The ladder describes *landmarks*, not names. Names are shorthand.
2. **Rungs are approximate** and vary with aspect ratio, subject posture, and the production's convention.
3. A "step" on the ladder means moving one rung up or down. Section 9 uses "steps" for continuity guidance.

## 3.2 Terminology Variation — Read This First

**Terminology and exact framing boundaries vary between productions, countries, and filmmaking traditions.** The table marks what is commonly accepted and what is variable.

| Term | Commonly accepted idea | Variability |
|---|---|---|
| **Extreme wide shot (EWS)** | Subject tiny relative to a vast environment. | Often used interchangeably with *extreme long shot (ELS)* and sometimes with *very wide shot (VWS)*. |
| **Extreme long shot (ELS)** | Same family as EWS. | "Long shot" in some traditions means a wide shot; in others it means a full-body shot. |
| **Very wide shot (VWS)** | A step tighter than EWS: the subject is visible but small. | Not used by all crews; some treat it as the same as EWS or as "wide." |
| **Wide shot (WS)** | Subject fully visible with substantial environment. | Sometimes the same as full shot. Sometimes means whatever is wider than the last shot. |
| **Long shot (LS)** | Subject's whole body visible with environment. | In some traditions equals a full shot; in others, wider than a full shot. |
| **Full shot (FS)** | Head to toe. | Margins vary; some use it for any frame with the whole body visible. |
| **Establishing shot** | A shot that establishes location or context. | It is a *function*, not a size; usually wide but may be any size that establishes. |
| **Master shot** | A single, often wide, shot covering the entire scene's action. | A *coverage role*, not a size. |
| **Medium long shot (MLS)** | About knees up. | Sometimes called a "three-quarter shot"; often merged with *cowboy shot*. |
| **Cowboy shot / American shot** | About mid-thigh up (holster level in westerns). | The French term *plan américain* roughly means a frame cut around the thigh or knee; boundaries differ. |
| **Medium shot (MS)** | About waist up. | Some crews use "medium" for anything between wide and close. |
| **Medium close-up (MCU)** | About chest up. | Sometimes shoulders up. |
| **Close-up (CU)** | Face. | Often includes neck/shoulders; some traditions mean head and shoulders. |
| **Tight close-up** | Face tighter than a standard close-up. | Not standardized; often overlaps with big close-up. |
| **Big close-up (BCU)** | Tighter than CU: forehead to chin or less. | Used mostly in British and some other traditions; in some it equals ECU. |
| **Extreme close-up (ECU)** | A feature (eyes, mouth) or small detail. | Boundaries vary. |
| **Detail / insert / cut-in** | Close view of a small thing. | *Insert* and *cut-in* are used interchangeably by some crews and distinguished by others (see 3.8–3.10). |

**Rule:** If a request depends on an exact crop, **specify landmarks** ("top of head to just below the belt"), not only a name.

---

## 3.3 WIDE AND ENVIRONMENTAL SHOTS

### 3.3.1 Extreme Wide Shot (EWS)

- **A. Framing boundaries (convention, approximate):** The subject occupies under about 5% of frame height; the environment dominates. The subject may be a speck.
- **B. Subject visible:** Whole subject, but without readable detail: no face, little posture.
- **C. Environmental information:** Maximum: landscape, skyline, weather, vastness.
- **D. Uses:** Opening a film or sequence; showing scale of the world or of the problem; transitions; showing a journey's span.
- **E. Possible audience effects (context-dependent):** Insignificance, freedom, isolation, grandeur, or orientation. A viewer may feel observational distance.
- **F. Unsuitable when:** The viewer must read faces or actions; the shot must be short (the viewer needs time to scan); the screen is small and detail is lost.
- **G. Common mistakes:** Subject so small it vanishes; no point of interest, so the frame feels empty; held too briefly to read; horizon crooked or arbitrary.
- **H. Diagnosis and correction:** *Symptom:* viewer cannot find the subject. *Check:* contrast, color separation, and position. *Fix:* move the subject to a visually strong location, increase contrast with the background, add a moving element, or tighten one step to a very wide shot.
- **I. Example:** A single hiker is a dark dot on a vast white salt flat; the horizon sits low; a thread of dust trails behind.
- **J. AI prompt:** "Extreme wide shot: the person is a tiny figure, under 5% of the frame height, in a vast desert; the environment fills most of the frame; the figure is dark against pale ground and clearly visible."

### 3.3.2 Extreme Long Shot (ELS)

- **A. Boundaries (variable):** Often identical to EWS. In some traditions ELS is slightly tighter (subject recognizable as human) than EWS.
- **B–E.** As for the EWS, with the subject marginally more identifiable.
- **F. Unsuitable when:** As for EWS; also when the production's vocabulary uses "long shot" for full-body framing and "extreme long" would be misread.
- **G. Common mistakes:** Confusing it with a *long shot*; assuming the crew shares the definition.
- **H. Diagnosis and correction:** If the result is different from expectation, *check the vocabulary*: restate with landmarks ("subject about 5–10% of frame height, full body visible, small").
- **I. Example:** A convoy of trucks crosses a plain; each truck is a small block.
- **J. AI prompt:** Treat as EWS with the percent: "Extreme long shot, the subject is small but identifiable as a person, about 5–8% of the frame height."

### 3.3.3 Very Wide Shot (VWS)

- **A. Boundaries (variable, approximate):** Subject about 5–15% of frame height; clearly human with identifiable posture and general costume.
- **B. Subject visible:** Whole body, small; large gestures readable; face not.
- **C. Environment:** Large: location, geography, other people at a distance.
- **D. Uses:** Showing a person within a place; large-scale action; isolating a character in space; travel across terrain.
- **E. Effects (context-dependent):** Isolation, smallness, observation; or belonging if the scene is full of life.
- **F. Unsuitable when:** Dialogue or expression must be readable.
- **G. Mistakes:** Placing the subject at the exact center with no reason; leaving too little contrast; mixing with a wide shot in a sequence so the change in size is too small to notice.
- **H. Diagnosis:** *Symptom:* the shot feels like a slightly zoomed-out wide shot. *Fix:* increase the difference in scale or restructure the sequence.
- **I. Example:** A woman crosses a plaza; the clock tower and a few pigeons are visible; she is a small, upright figure.
- **J. AI prompt:** "Very wide shot: full body visible but small, about 10% of frame height; the plaza and buildings fill the frame."

### 3.3.4 Wide Shot (WS)

- **A. Boundaries (convention, variable):** The whole subject is clearly visible, with considerable environment around and above; about 15–40% of frame height for a standing person.
- **B. Subject visible:** Entire body; posture, movement, costume readable; faces small.
- **C. Environment:** Substantial.
- **D. Uses:** Showing action in context; geography; spatial relationships; entrances and exits.
- **E. Effects (context-dependent):** Observational distance; sense of place; or vulnerability if the surroundings are large.
- **F. Unsuitable when:** Expression drives the moment.
- **G. Mistakes:** Frame feels empty with no purpose; subject touches an edge; confusion with a full shot.
- **H. Diagnosis:** *Symptom:* shot feels empty. *Check:* is the empty space motivated (carrying meaning)? *Fix:* tighten to a full shot or add environmental interest.
- **I. Example:** Two friends walk through a market; stalls and crowds fill the frame.
- **J. AI prompt:** "Wide shot: both people fully visible head to toe, about 25% of the frame height, in a busy market."

### 3.3.5 Long Shot (LS)

- **A. Boundaries (variable):** In many traditions equals a *full shot* (whole body in frame with limited margins); in others it equals a *wide shot*.
- **B–E.** Depend on the chosen convention. State it.
- **F. Unsuitable when:** The crew has not agreed on the meaning.
- **G. Mistakes:** Treating "long shot" as a precise size; ambiguity leading to wasted takes or generations.
- **H. Diagnosis and correction:** Replace the term with landmarks.
- **I. Example:** A cyclist rides along a road; the whole body and bicycle are visible with road ahead.
- **J. AI prompt:** "Long shot: cyclist and bicycle fully visible, about 30% of frame height, road and trees visible."

### 3.3.6 Full Shot (FS)

- **A. Boundaries (convention):** Head to toe fills most of the frame height (about 50–90%), with modest headroom and footroom.
- **B. Subject visible:** The entire body, including feet; face partially readable.
- **C. Environment:** Limited but present: floor, nearby objects, background.
- **D. Uses:** Introducing a character with costume and posture; physical action; dance; walking; stance; relationship to a nearby object.
- **E. Effects (context-dependent):** Presence, physicality, a clear read of the person as a whole.
- **F. Unsuitable when:** Facial expression is the main information; the frame is vertical and the subject is wide (for example, with outstretched arms).
- **G. Mistakes:** Cropping feet or the top of the head; too little or too much headroom; frame so tight to the figure that movement cannot be tracked.
- **H. Diagnosis:** *Symptom:* shoes cut off. *Check:* footroom and camera tilt. *Fix:* widen slightly, lower the camera tilt, or add footroom of about one hand-width.
- **I. Example:** A dancer holds a pose at center; the floor reflections show.
- **J. AI prompt:** "Full shot: entire body visible from the top of the head to the shoes, with a small margin above and below; the subject fills about 70% of the frame height."

### 3.3.7 Establishing Shot (a function, not a size)

- **A. Boundaries (variable):** Any frame that establishes place, time, or situation; usually wide, but it can be tight (a street sign close-up establishes location).
- **B. Subject visible:** The location or situation is the subject.
- **C. Environment:** Whatever is needed to establish.
- **D. Uses:** Beginning of a scene; transitions; orienting the viewer.
- **E. Effects (context-dependent):** Orientation, mood of place.
- **F. Unsuitable when:** The location is already clear and the establishing shot would delay the scene.
- **G. Mistakes:** Establishing something irrelevant; establishing with a frame that is too generic (any city); forgetting to establish the time of day.
- **H. Diagnosis:** *Symptom:* viewer is still lost. *Check:* whether the frame includes distinctive landmarks. *Fix:* choose a more specific frame or add a second establishing detail.
- **I. Example:** A shot of a hospital's night entrance with an ambulance bay and a sign.
- **J. AI prompt:** "Establishing wide shot of a hospital entrance at night, the building sign legible, an ambulance bay in the foreground, no close people."

### 3.3.8 Master Shot (a coverage role)

- **A. Boundaries (variable):** A shot, often wide or full, that covers the entire scene's action in one take. It may be a medium if the scene is small.
- **B. Subject visible:** All principal subjects and their relationships.
- **C. Environment:** Enough to show geography.
- **D. Uses:** Safety coverage; reference for spatial relationships; cutaways to closer shots.
- **E. Effects:** A stable, observational view.
- **F. Unsuitable when:** A scene is designed as fragments with no continuous geography.
- **G. Mistakes:** Treating the master as the only coverage; failing to match action in closer shots.
- **H. Diagnosis:** *Symptom:* closer shots do not match the master. *Check:* position and action continuity. *Fix:* re-stage to match, or hide the mismatch with cutaways.
- **I. Example:** A dinner scene shot in one wide take showing all five people at the table.
- **J. AI prompt:** "Master shot: all five people at the table visible, the room's doors and windows visible, camera static; the shot holds the entire scene."

---

## 3.4 MEDIUM SHOTS

### 3.4.1 Medium Long Shot (MLS)

- **A. Boundaries (variable, approximate):** Top of head to about the knees.
- **B. Subject visible:** Most of the body; gesture, posture, and face partly readable.
- **C. Environment:** Moderate: background and nearby furniture.
- **D. Uses:** Walking-and-talking; interactions; transitions between wide and medium.
- **E. Effects:** A balanced view of person and place.
- **F. Unsuitable when:** Facial details or foot action are essential.
- **G. Mistakes:** Cutting at the knee joint (awkward); confusion with the cowboy shot.
- **H. Diagnosis:** *Symptom:* the crop looks awkward. *Fix:* adjust to just above or below the knee.
- **I. Example:** A detective walks toward the camera along a corridor, framed from head to just below the knee.
- **J. AI prompt:** "Medium long shot: top of the head to just below the knees; legs below that not visible; hands and torso visible."

### 3.4.2 Medium Full Shot

- **A. Boundaries (variable):** Often between MLS and FS: head to about the shins or just above the ankles.
- **B–E.** Nearly full body with feet cropped; shows most gesture and stance.
- **F. Unsuitable when:** Feet or ground contact matter.
- **G. Mistakes:** Cropping near the ankle joint.
- **H. Diagnosis:** Re-check footroom; either include the feet or crop mid-shin.
- **I. Example:** A boxer shadowboxes; frame ends at mid-shin.
- **J. AI prompt:** "Medium full shot: top of head to mid-shin; feet not visible."

### 3.4.3 Cowboy Shot / American Shot

- **A. Boundaries (variable):** About mid-thigh up (originally to show a holstered gun).
- **B. Subject visible:** Head, torso, hands, upper legs.
- **C. Environment:** Moderate.
- **D. Uses:** Standoffs; characters with a visible object at the hip or hands; group scenes.
- **E. Effects:** Poise, readiness, presence.
- **F. Unsuitable when:** Feet or ground are important.
- **G. Mistakes:** Cropping at the knee; hiding the hands; mixing with MLS in the same sequence without clear differentiation.
- **H. Diagnosis:** Check where the crop falls; adjust to mid-thigh.
- **I. Example:** Two gunfighters in a street, framed from mid-thigh up.
- **J. AI prompt:** "Cowboy shot: from the top of the head to mid-thigh; hands and belt line visible; cut above the knees."

### 3.4.4 Medium Shot (MS)

- **A. Boundaries (convention):** Top of head to about the waist.
- **B. Subject visible:** Torso, arms, hands partially; face moderately readable.
- **C. Environment:** Some background; limited foreground.
- **D. Uses:** Conversation, interviews, standard coverage; gestures with arms.
- **E. Effects:** Natural, conversational distance (context-dependent).
- **F. Unsuitable when:** Lower-body action or detailed expression is required.
- **G. Mistakes:** Cropping at the elbows or just at the belt in a way that creates awkward cuts; losing hands when the performance depends on them.
- **H. Diagnosis:** *Symptom:* hands cut in half. *Fix:* widen slightly or have the actor hold gestures higher.
- **I. Example:** Two friends talk across a table; each in a waist-up frame.
- **J. AI prompt:** "Medium shot: top of the head to the waist; both hands visible; background softly visible."

### 3.4.5 Medium Close-Up (MCU)

- **A. Boundaries (variable):** Top of head to mid-chest or just below the shoulders.
- **B. Subject visible:** Head, shoulders, upper chest; face readable.
- **C. Environment:** Limited; background is blurred or simplified.
- **D. Uses:** Dialogue coverage; reaction shots; interviews.
- **E. Effects (context-dependent):** Engaged attention; mild intimacy.
- **F. Unsuitable when:** Posture or environment is needed.
- **G. Mistakes:** The vague label "MCU" without landmarks produces inconsistent crops.
- **H. Diagnosis:** Replace the label with "chest-up, cut at mid-chest."
- **I. Example:** A teacher listens to a student; framed from head to mid-chest.
- **J. AI prompt:** "Medium close-up: head to mid-chest; shoulders visible; a small amount of background."

---

## 3.5 CLOSE SHOTS

### 3.5.1 Close-Up (CU)

- **A. Boundaries (convention):** Face and a little neck or shoulder; the face fills most of the frame height.
- **B. Subject visible:** Face including hair or hairline; eyes, mouth, expression.
- **C. Environment:** Minimal; mostly background tones.
- **D. Uses:** Showing expression, decision, realization, speech; emphasizing a character's presence.
- **E. Effects (context-dependent):** Engagement; scrutiny; closeness. It may also feel intrusive.
- **F. Unsuitable when:** The viewer needs to know where the character is or who else is present.
- **G. Mistakes:** Cropping the chin or top of the head accidentally; too little looking room; over-reliance on close-ups, which flattens the sequence.
- **H. Diagnosis:** *Symptom:* the face looks cramped. *Check:* headroom and looking room. *Fix:* adjust position, or widen to an MCU.
- **I. Example:** A student hears her exam result; the frame holds her face as her eyes drop.
- **J. AI prompt:** "Close-up: the face fills about 70% of the frame height, from the top of the hair to the base of the neck; eyes in the upper third; no other people visible."

### 3.5.2 Tight Close-Up

- **A. Boundaries (variable):** Tighter than a standard CU: the face fills the frame with little or no neck; hair may be cropped.
- **B–E.** Intense focus on the face.
- **F. Unsuitable when:** Overuse causes fatigue; resolution is low.
- **G. Mistakes:** Cropping the top of the head so much that the frame feels cut; uneven side margins.
- **H. Diagnosis:** Check which features are cropped; keep the eyes and mouth comfortably inside the frame.
- **I. Example:** A witness's face in an interrogation, cropped at the forehead and chin.
- **J. AI prompt:** "Tight close-up: forehead to chin fills the frame; ears partially cropped; eyes at about one-third from the top."

### 3.5.3 Extreme Close-Up (ECU)

- **A. Boundaries (variable):** A feature (eyes, mouth) or a small detail fills the frame.
- **B. Subject visible:** A part, not the whole.
- **C. Environment:** None visible.
- **D. Uses:** Emphasizing a specific detail (eyes widening, lips trembling, a trigger).
- **E. Effects (context-dependent):** Intensity, tension, abstraction.
- **F. Unsuitable when:** The detail is not meaningful; too many in a row.
- **G. Mistakes:** Focus misses the key feature; detail is not identifiable.
- **H. Diagnosis:** Check focus and identifiability; widen if unclear.
- **I. Example:** An eye reflecting a screen.
- **J. AI prompt:** "Extreme close-up: only the eyes and brow fill the frame; the iris is sharp; skin texture visible."

### 3.5.4 Big Close-Up (BCU), where applicable

- **A. Boundaries (variable):** In some traditions, forehead to chin; in others, an extreme close-up of a facial feature.
- **B–E.** Intense detail of the face.
- **F. Unsuitable when:** The vocabulary is not shared.
- **G. Mistakes:** Mixing definitions.
- **H. Diagnosis:** Define with landmarks.
- **I. Example:** A close view from the eyebrows to the lips.
- **J. AI prompt:** "Big close-up: from the eyebrows to the chin fills the frame."

### 3.5.5 Detail Shot

- **A. Boundaries (convention):** A small part of the subject or the environment fills the frame.
- **B. Subject visible:** A specific detail (a hand, a stitch, a button).
- **C. Environment:** Minimal.
- **D. Uses:** Showing texture or specific information; punctuating a scene.
- **E. Effects:** Highlights importance.
- **F. Unsuitable when:** The detail lacks narrative relevance.
- **G. Mistakes:** Detail shots with no payoff; poor focus.
- **H. Diagnosis:** Does the viewer understand why this detail matters? Add context through the preceding shot.
- **I. Example:** A watch hand ticks.
- **J. AI prompt:** "Detail shot: a wristwatch face fills the frame; the second hand is sharp."

### 3.5.6 Insert Shot

- **A. Boundaries (variable):** A close shot of an object or text, often independent of the main performers (a letter, a phone screen).
- **B. Subject visible:** The object.
- **C. Environment:** Minimal.
- **D. Uses:** Delivering information to the audience.
- **E. Effects:** Clarity.
- **F. Unsuitable when:** The audience can already infer the information.
- **G. Mistakes:** Illegible text; mismatched lighting or props.
- **H. Diagnosis:** Check legibility and continuity with surrounding shots.
- **I. Example:** A close-up of a text message appearing on a phone.
- **J. AI prompt:** "Insert shot: a phone screen fills the frame; a message with large legible text; no fingers visible."

### 3.5.7 Cut-In Shot

- **A. Boundaries (variable):** A close view of a part of the main action (a hand turning a key) that is "cut into" a larger shot of the same action.
- **B. Subject visible:** A part of the actor's action.
- **C. Environment:** Minimal but matching.
- **D. Uses:** Showing a specific action; bridging gaps.
- **E. Effects:** Emphasis.
- **F. Unsuitable when:** Continuity of action cannot be maintained.
- **G. Mistakes:** Mismatch in hand position, props, or lighting.
- **H. Diagnosis:** Compare to the wider shot for continuity.
- **I. Example:** A hand turns a door key while the character stands outside.
- **J. AI prompt:** "Cut-in shot: a hand turning a key in a lock, close and sharp; the sleeve visible; matches the previous wider shot."

---

## 3.6 MULTI-SUBJECT AND SPECIAL FRAMING

### 3.6.1 Two-Shot

- **A. Boundaries (convention):** Two subjects together in one frame; the size describes each subject's visibility (a medium two-shot shows both waist-up).
- **B. Visible:** Both subjects.
- **C. Environment:** Depends on size.
- **D. Uses:** Relationship, conversation, shared reaction.
- **E. Effects:** Connection or separation depending on spacing.
- **F. Unsuitable when:** The scene requires isolating one person.
- **G. Mistakes:** Overlapping bodies; one subject cropped; unequal visual weight.
- **H. Diagnosis:** Check overlap and margins; adjust positions.
- **I. Example:** Two siblings sit on a bench, medium two-shot.
- **J. AI prompt:** "Medium two-shot: both people waist-up, side by side, a hand's width of space between them, both faces fully visible."

### 3.6.2 Three-Shot

- **A. Boundaries:** Three subjects in frame.
- **B–E.** Shows grouping and hierarchy.
- **F. Unsuitable when:** Faces must be clear at a small size.
- **G. Mistakes:** The middle subject hidden; uneven spacing.
- **H. Diagnosis:** Re-stage in depth.
- **I. Example:** Three colleagues at a meeting table.
- **J. AI prompt:** "Medium three-shot: three people visible from waist up, all faces unobstructed, the center person slightly forward."

### 3.6.3 Group Shot

- **A. Boundaries (variable):** Four or more subjects.
- **B–E.** Shows social structure.
- **F. Unsuitable when:** Individual detail is required.
- **G. Mistakes:** Faces hidden; subjects at edges cut.
- **H. Diagnosis:** Re-stage or widen.
- **I. Example:** A team in a locker room.
- **J. AI prompt:** "Group shot: six people arranged in two rows, all faces visible, full bodies in the front row."

### 3.6.4 Over-the-Shoulder Shot (OTS)

- **A. Boundaries (convention):** The frame includes the back of one person's shoulder and head in the foreground and another person facing the camera. **Shot-size component:** usually a medium or medium close-up of the *facing* subject. **Viewpoint component:** the camera is behind and slightly to the side of the foreground person.
- **B. Visible:** The facing subject's face and upper body; the foreground subject's shoulder and part of the head.
- **C. Environment:** Limited; background behind the facing person.
- **D. Uses:** Dialogue; showing relationships and eyelines.
- **E. Effects (context-dependent):** Closeness to the conversation; the viewer shares the foreground person's side.
- **F. Unsuitable when:** The foreground person must not be perceived as present, or the face must be unobstructed.
- **G. Mistakes:** The foreground shoulder blocks the facing subject's face; too much foreground; inconsistent size across reverses.
- **H. Diagnosis:** Check overlaps and the size of the facing subject; match the reverse OTS.
- **I. Example:** A manager speaks; we see the employee's shoulder and the manager's face.
- **J. AI prompt:** "Over-the-shoulder shot: foreground person's shoulder and back of head at the left edge, out of focus; the facing person from head to chest, sharp and centered right."

### 3.6.5 Point-of-View Shot (POV)

- **A. Boundaries (convention):** The frame shows what a character sees. **Shot-size component:** the apparent size of the *thing seen* (a door at wide, a letter at close). **Viewpoint component:** the camera sits where the character's eyes would be.
- **B. Visible:** The object of the character's gaze.
- **C. Environment:** Variable.
- **D. Uses:** Sharing perception; discovery; suspense.
- **E. Effects (context-dependent):** Subjective alignment.
- **F. Unsuitable when:** The viewer needs to see the character.
- **G. Mistakes:** Unrealistic height; unmotivated movement; a size that doesn't match how the character sees (such as an impossibly close view).
- **H. Diagnosis:** Check eye height and plausible distance.
- **I. Example:** A woman looks at the door; the POV shows the door at medium-wide size.
- **J. AI prompt:** "POV shot from a standing adult's eye height: a door at the end of a corridor, about 15 meters away, centered; no part of the viewer visible."

### 3.6.6 Reaction Shot

- **A. Boundaries (function):** Any frame showing a subject reacting; usually medium close-up or close-up.
- **B. Visible:** Face and upper body.
- **C. Environment:** Minimal.
- **D. Uses:** Showing consequences, emotion, decisions.
- **E. Effects:** Directs the viewer's feeling toward the reaction.
- **F. Unsuitable when:** The reaction is unclear or unmotivated.
- **G. Mistakes:** A generic expression; mismatched size with the action shot.
- **H. Diagnosis:** Check expression and size.
- **I. Example:** A mother's face after she hears the diagnosis result.
- **J. AI prompt:** "Reaction close-up: her face fills the frame; her eyes lower slowly; no one else visible."

### 3.6.7 Object Close-Up

- **A. Boundaries (convention):** An object fills most of the frame.
- **B. Visible:** The object and its markings.
- **C. Environment:** Minimal.
- **D. Uses:** Clues, props, weapons, objects of desire.
- **E. Effects:** Emphasis.
- **F. Unsuitable when:** The object lacks story importance.
- **G. Mistakes:** Poor focus; context lost.
- **H. Diagnosis:** Check focus and relation to the previous shot.
- **I. Example:** A key on a table.
- **J. AI prompt:** "Object close-up: a brass key fills about 60% of the frame, sharp, on a wooden table."

### 3.6.8 Hand Close-Up

- **A. Boundaries (convention):** Hand(s) fill the frame; maybe the wrist.
- **B–E.** Shows action and small gestures.
- **F. Unsuitable when:** Hands do not carry meaning.
- **G. Mistakes:** Cutting fingers; anatomical errors in AI generation.
- **H. Diagnosis:** Check fingers and positions.
- **I. Example:** Hands tearing an envelope.
- **J. AI prompt:** "Hand close-up: both hands and wrists fill the frame; five fingers each visible and distinct."

### 3.6.9 Face Close-Up

- **A. Boundaries:** As in 3.5.1, a CU of a face.
- **B–E.** As above.
- **F. Unsuitable when:** Identity or expression is not important.
- **G. Mistakes:** Uneven margins; hair or chin cropped by accident.
- **H. Diagnosis:** Check margin symmetry.
- **I. Example:** A reunion; her face fills the frame.
- **J. AI prompt:** "Face close-up: from the hairline to the chin, both eyes visible and sharp."

### 3.6.10 Environmental Detail Shot

- **A. Boundaries (variable):** A close or medium view of a part of the environment (a cracked wall, a dripping tap) with no subject.
- **B. Visible:** The environment detail.
- **C. Environment:** The detail itself.
- **D. Uses:** Building atmosphere; punctuating; creating transitions.
- **E. Effects:** Texture and mood (context-dependent).
- **F. Unsuitable when:** It delays the story.
- **G. Mistakes:** Decorative shots that carry no meaning.
- **H. Diagnosis:** Does the detail have narrative relevance?
- **I. Example:** A dripping tap in an empty kitchen.
- **J. AI prompt:** "Environmental detail shot: a tap dripping into a stained sink fills the frame; no people."

---
# 4. SHOT-SIZE BOUNDARIES AND SUBJECT VISIBILITY

## 4.1 Framing Landmarks for a Standing Human Subject

Landmarks make shot size testable. The table gives the **crop line** (where the frame's bottom edge falls) for a standing person in a horizontal frame. The top edge is normally just above the head (see 4.4).

| Landmark framing | Crop line (bottom edge) | Closest common name (variable) | What it keeps | What it loses |
|---|---|---|---|---|
| **Entire body / head-to-toe** | Below the shoes, with footroom | Full shot | Posture, costume, stance, ground contact | Facial detail |
| **Knees-up** | Just below the knees | Medium long shot | Torso, hands, upper legs | Feet, ground contact |
| **Mid-thigh** | Mid-thigh | Cowboy / American shot | Hands at the sides, belt area | Knees, feet |
| **Waist-up** | At or just below the waist | Medium shot | Torso, arms, hands in gesture | Lower body |
| **Chest-up** | Mid-chest | Medium close-up | Face, shoulders, upper chest | Hands, torso |
| **Shoulders-up** | At the shoulder line or just below | Close-up (variable) | Face, neck, shoulder line | Chest, arms |
| **Head-and-shoulders** | Just below the shoulders | Close-up or MCU (variable) | Face and shoulder slope | Torso |
| **Face-only** | Neck or chin | Tight close-up / BCU | Eyes, mouth, expression | Neck, shoulders |
| **Feature or detail** | A small part fills the frame | ECU / detail | Fine detail | The rest of the person |

**Note on "variable":** some productions call head-and-shoulders a medium close-up and others a close-up. That is why Section 4.2 recommends specifying the crop.

## 4.2 Avoiding Ambiguous Terms

**Problem:** A term such as "medium close-up" means different crops to different people. Two crews may agree on the term and produce different framings.

**Rule:** When an exact crop is essential, state:

1. **Top boundary** (for example, "top of the head with a small margin").
2. **Bottom boundary** (for example, "mid-chest, above the elbows").
3. **Side behavior** (for example, "shoulders fully inside the frame").
4. **Approximate subject scale** (for example, "the head occupies about 40% of the frame height").

**Template:** *"[Subject], [top boundary] to [bottom boundary], [margin note], [scale note]."*

**Example:** "Her head and upper chest from the top of the hair to mid-chest; both shoulders fully inside the frame; the head occupies about 40% of the frame height."

## 4.3 Cropping at Joints and Where Crops Fall

**Convention (widely taught):** Avoid framing edges that fall exactly at **joints** (ankles, knees, elbows, wrists, neck). A crop at a joint makes the body look amputated or awkwardly truncated. Prefer crops at **mid-segment** (mid-shin, mid-thigh, mid-forearm, mid-chest).

| Joint to avoid | Preferred nearby crop |
|---|---|
| Ankles | Include the feet, or crop at mid-shin |
| Knees | Mid-thigh, or just below the knee at mid-shin |
| Waist/belt line (borderline) | Slightly above or below the belt line |
| Elbows | Mid-forearm or upper arm |
| Wrists | Include the hands or crop mid-forearm |
| Neck | Include the shoulders or crop above the chin deliberately in a tight close-up |

**Intentional vs. accidental partial framing:**

| | Intentional partial framing | Framing mistake |
|---|---|---|
| **Cause** | Chosen to withhold or emphasize | Unplanned |
| **Edge position** | Falls at a mid-segment or in a clearly chosen place | Falls at a joint or slices an object |
| **Pattern** | Consistent across related shots | Differs unexpectedly |
| **Result** | Directs attention | Distracts attention |
| **Test** | Can you say why this edge is here? | Cannot |

## 4.4 Headroom, Footroom, Looking Room, and Lead Room

- **Headroom** is the space between the top of the head and the top of the frame.
- **Footroom** is the space between the feet (or lowest important element) and the bottom of the frame.
- **Looking room (nose room)** is the space in front of a subject's gaze direction.
- **Lead room** is the space in front of a moving subject.

**Convention (widely taught, with accepted exceptions):**

| Shot | Typical headroom (approximate) | Notes |
|---|---|---|
| Wide and full shots | Visible margin above head; the frame includes sky or ceiling | Enough that the head does not touch the edge |
| Medium shots | Small margin: roughly the height of a hand or slightly less | Eyes often fall around the upper third of the frame |
| Close-ups | Little to none; cropping the top of the hair is common | The forehead may be partly cropped; do not crop the eyes |
| Extreme close-ups | None; headroom is not meaningful | Frame by feature |

**Looking room:** A subject facing right is usually given more space on the right than on the left. Too little looking room makes the subject feel pressed against the edge (which may be intended).

**Lead room:** A subject walking left-to-right needs space on the right. Without it, the frame can feel as though the subject is about to collide with the edge.

**Exceptions (context-dependent):** Cramped headroom or looking room can be used deliberately for tension or confinement. Mark it as a decision.

## 4.5 Subject Posture and Body Proportions

Framing landmarks are tied to *body parts*, not to fixed measurements. When posture changes, the same landmark falls at a different place in the frame.

| Condition | Effect on framing | Practical adjustment |
|---|---|---|
| **Sitting** | The waist is lower relative to the frame; the legs are shortened and often hidden by furniture. | "Waist-up" still works, but "full shot" may include a chair and the floor. State whether the chair is included. |
| **Crouching** | The head is lower; the body is compact. | A full shot needs less height but more width for the legs and arms. |
| **Lying down** | The body is horizontal. | A "full shot" is wide, not tall. In a vertical frame, the subject may be tiny; in a horizontal frame, it fills the width. |
| **Reaching / arms extended** | Width increases. | Leave extra side margins or widen. |
| **Leaning toward the camera** | The head is closer; foreshortening exaggerates it. | The frame's crop line may shift upward. |
| **Different body proportions (children, tall subjects)** | Landmarks fall at different heights. | Define crops by landmarks relative to the subject, not by a fixed frame position. |

## 4.6 Non-Human Subjects: Do Not Assume Human Conventions

Human landmarks do not transfer directly to other subjects. Define **subject-specific landmarks** and state them.

| Subject type | Why human conventions fail | How to define shot size |
|---|---|---|
| **Animals** | Body shapes differ (a horse is long, a bird is compact); eyes and heads are positioned differently. | Use the animal's own landmarks: "entire body with tail," "head and neck," "eye and muzzle." For quadrupeds, a "full shot" is wide, not tall. |
| **Vehicles** | There is no waist or shoulder; the key information is front, side, wheels, interior. | "Entire vehicle with all four wheels," "front half," "driver's window," "badge detail." |
| **Architecture** | Scale is vast; "full shot" may mean the facade. | "Entire facade to the roofline," "entrance and two floors," "door detail." |
| **Objects** | They vary in shape. | Use proportions: "the object fills about 60% of the frame width," or landmarks like "the whole handle to the tip." |
| **Groups and crowds** | The subject is plural. | Define by the number of people and the shot size of each. |

---

# 5. SHOT SIZE AND NARRATIVE PURPOSE

For each purpose below, the section lists plausible shot sizes, what each reveals or conceals, and the conditions that make one preferable.

## 5.1 Establishing Location and Geography

| Option | Reveals | Conceals | Prefer when |
|---|---|---|---|
| **Extreme wide** | Scale, region, weather | People, details | The setting is the story's first fact (a remote town). |
| **Wide** | Layout, landmarks, approximate distances | Facial detail | The audience needs to understand where things are relative to each other. |
| **Medium with landmarks (a sign, a doorway)** | Specific place identity | Wider surroundings | The location is a specific known place and the layout is irrelevant. |

## 5.2 Introducing a Character

| Option | Reveals | Conceals | Prefer when |
|---|---|---|---|
| **Full shot** | Posture, costume, bearing, relation to space | Face detail | The character's physicality and style carry identity. |
| **Medium shot** | Attitude and gesture | Lower body | The character's presence is conveyed through speech and gesture. |
| **Detail first (a hand, boots), then reveal** | Partial identity | The whole person | The character should be withheld as a mystery. |

## 5.3 Showing Body Language

| Option | Reveals | Conceals | Prefer when |
|---|---|---|---|
| **Full shot** | Whole-body posture and balance | Fine gestures | Posture or movement is the point (a limp, a stiff walk). |
| **Medium long shot** | Posture and arm positions | Foot detail | The arms and torso carry the gesture. |
| **Medium shot** | Hands and torso gestures | Legs, ground | Conversation with gesturing. |

## 5.4 Reading Facial Expressions

| Option | Reveals | Conceals | Prefer when |
|---|---|---|---|
| **Medium close-up** | Expression with shoulders; some posture | Hands, environment | Expression plus a hint of body. |
| **Close-up** | Fine expression changes | Almost everything else | The moment depends on a small change. |
| **Extreme close-up** | A feature's detail (eyes) | The rest of the face | A single feature carries the information. |

## 5.5 Showing Small Gestures

| Option | Reveals | Conceals | Prefer when |
|---|---|---|---|
| **Medium** | Arm movement | Finger detail | The gesture is large (a wave). |
| **Cut-in or hand close-up** | Finger movement, small objects | Face, surroundings | The gesture is small (a trembling hand). |
| **Medium with hand in foreground** | Gesture and face together | Neither in great detail | The relationship between the gesture and expression matters. |

## 5.6 Emphasizing an Object or Clue

| Option | Reveals | Conceals | Prefer when |
|---|---|---|---|
| **Insert / object close-up** | Object details | Who holds it, context | The object's details are the information. |
| **Medium with the object in focus** | Object plus person | Fine detail | The relation between a person and the object matters. |
| **Wide with the object placed prominently** | Object in the environment | Details | The object should be discoverable rather than presented. |

## 5.7 Communicating Physical Distance Between Characters

| Option | Reveals | Conceals | Prefer when |
|---|---|---|---|
| **Wide two-shot** | Actual distance | Facial detail | The distance itself is information. |
| **Medium two-shot** | Relationship and body language | True distance | The emotional relation matters more than the measurement. |
| **Separate close-ups** | Emotional states | Distance | The distance is unimportant; the effect of the separation is. |

## 5.8 Showing Isolation Within an Environment

| Option | Reveals | Conceals | Prefer when |
|---|---|---|---|
| **Very wide / wide with the subject small** | Empty space around the subject | Facial expression | The viewer must see the emptiness. |
| **Medium with negative space** | Expression and emptiness | Wider context | Isolation and expression both matter. |
| **Close-up with a tight crop** | Inner state | Environment | Isolation is psychological rather than spatial. |

## 5.9 Communicating Intimacy or Emotional Distance

| Option | Reveals | Conceals | Prefer when |
|---|---|---|---|
| **Close two-shot** | Closeness between people | Environment | Physical proximity is the point. |
| **Wide two-shot with space between** | Distance | Facial details | The emotional distance should be visible. |
| **Alternating close-ups** | Individual feelings | The relation in space | Each person's inner state matters; use carefully to avoid fragmenting the scene. |

## 5.10 Revealing a Threat or Hidden Detail

| Option | Reveals | Conceals | Prefer when |
|---|---|---|---|
| **Wide with the threat small in the background** | Threat visible but not noticed by the character | Detail | The audience should see it before the character does. |
| **Close-up of the character, threat out of frame** | Reaction | The threat | The viewer should feel the threat before seeing it. |
| **Detail of the threat** | Specifics | Context | The detail (a weapon, a mark) is the information. |

## 5.11 Following Physical Action

| Option | Reveals | Conceals | Prefer when |
|---|---|---|---|
| **Full / medium long** | Whole-body action | Facial detail | The mechanics of movement matter. |
| **Medium** | Torso and arms | Legs | Upper-body action (a punch, a throw). |
| **Detail cut-ins** | Impact points | Overall geography | Emphasizing impact within a clear geography already established. |

## 5.12 Showing Reactions

| Option | Reveals | Conceals | Prefer when |
|---|---|---|---|
| **MCU** | Expression plus shoulders | Hands | Normal conversational reaction. |
| **CU** | Fine reaction | Context | The reaction is the key moment. |
| **Wide reaction in context** | Group response | Individual detail | The crowd's response is the point. |

## 5.13 Ending a Scene or Emphasizing a Transition

| Option | Reveals | Conceals | Prefer when |
|---|---|---|---|
| **Pull out to wide** | Subject within the larger world | Emotional detail | The scene should close with perspective. |
| **Push to close-up** | Final emotion | Context | The scene ends on an emotional decision. |
| **Cut to an object or environmental detail** | A symbol or hint | The subject | A transition motif or a parting thought is needed. |

**Principle:** The choice between options depends on *what the viewer must receive* and *what must wait*. Use the tightest frame that delivers the needed information, unless context or withholding calls for a wider frame.

---

# 6. SHOT SIZE, CAMERA DISTANCE, AND LENS

## 6.1 The Relationships

Shot size is the *visible result* of several physical variables:

| Variable | What it is | How it affects shot size |
|---|---|---|
| **Camera-to-subject distance** | How far the camera is from the subject. | Closer camera = larger subject in frame (all else equal). |
| **Lens focal length** | A property of the lens (in millimeters) that, with the sensor size, determines field of view. | Longer focal length = narrower view = larger subject at a given distance. |
| **Sensor or image-plane dimensions** | The size of the capture area. | A larger sensor with the same lens sees a wider view; a smaller sensor sees a narrower view. |
| **Field of view (FOV)** | The angle of the scene the camera sees. | Narrower FOV = tighter shot at a given distance. |
| **Camera position and angle** | Where the camera is and where it points. | Changes which parts of the subject are visible and at what apparent size. |
| **Subject dimensions and orientation** | Size and facing direction of the subject. | A wide subject needs more width; a subject turned sideways shows a different silhouette. |
| **Frame boundaries and aspect ratio** | Shape of the visible rectangle. | Determines what fits horizontally versus vertically. |

**Approximate field-of-view formula:** *horizontal FOV = 2 × arctan(sensor width ÷ (2 × focal length)).* With a full-frame sensor (36 mm wide) the approximate horizontal FOV is:

| Focal length | Approx. horizontal FOV (full-frame) |
|---|---|
| 24 mm | About 74° |
| 35 mm | About 54° |
| 50 mm | About 40° |
| 85 mm | About 24° |
| 135 mm | About 15° |

Other sensor sizes give different values; a smaller sensor at the same focal length gives a narrower FOV.

**Approximate visible-height rule:** for a subject far compared with the lens's focal length, *visible height at the subject ≈ distance × (sensor height ÷ focal length).* With a 36 × 24 mm sensor in landscape orientation (sensor height 24 mm), at 50 mm and 4.4 m, the visible height is about 2.1 m — enough for a standing person with small margins. These are approximations; actual values depend on the sensor crop, focus distance, and lens design.

## 6.2 Same Shot Size, Different Combinations

The same shot size can be achieved with different distance and focal-length combinations. The approximate camera distances (full-frame, landscape, subject plane) are:

| Framing | Visible height needed (approx.) | 24 mm | 35 mm | 50 mm | 85 mm | 135 mm |
|---|---|---|---|---|---|---|
| **Full shot** (standing adult with small margins) | 2.1 m | 2.1 m | 3.1 m | 4.4 m | 7.4 m | 11.8 m |
| **Chest-up** (head to mid-chest with small margin) | 0.7 m | 0.7 m | 1.0 m | 1.5 m | 2.5 m | 3.9 m |

**Key insight:** All cells in a row produce a similar **shot size**, but not the same **image**.

## 6.3 Perspective Is Determined by Viewpoint

**Established principle:** *Perspective* (the relative size of near and far things, and the apparent depth) is determined by **where the camera is** (the viewpoint), not by the focal length itself. Focal length determines how much of the scene that viewpoint captures.

Consequences for the chest-up framing above:

| Version | What changes | Effect |
|---|---|---|
| **24 mm at 0.7 m** | Camera very close; the nose and near features are relatively larger than the ears; background shows a wide field behind the subject; the background appears small relative to the subject. | Intimate or distorted; the viewer feels near. |
| **50 mm at 1.5 m** | Moderate distance; natural facial proportions for most uses. | Neutral-feeling. |
| **135 mm at 3.9 m** | Camera farther; facial features appear flatter; the background is a narrow slice that appears much larger relative to the subject. | Compressed; the subject can feel isolated from, or stacked against, the background. |

**Background relationship example (approximate):** A subject stands 3 m in front of a wall. At 0.7 m (24 mm), the camera-to-wall distance is 3.7 m, so the subject-to-camera/wall-to-camera distance ratio is about 0.19. At 3.9 m (135 mm), the wall is at 6.9 m, and the ratio is about 0.57. The wall's features therefore appear roughly **three times larger relative to the subject** with the 135 mm lens, though the subject's shot size is the same. This is why a long lens from afar makes backgrounds look "closer" and magnified.

**Caution:** Depth of field (how much is in focus) also changes with focal length, aperture, and distance; it is outside this file's scope but it interacts with the look of the same shot size.

## 6.4 Moving the Camera vs. Changing the Lens vs. Digital Cropping

| Method | What changes | What stays the same | Advantages | Disadvantages |
|---|---|---|---|---|
| **Move the camera (dolly, walk closer)** | Viewpoint, perspective, background relationships | The lens | Natural perspective change; real parallax (relative motion between near and far things) | Requires physical access; may change lighting or geometry; may intrude on actors |
| **Change the lens (focal length)** | Field of view; with the camera fixed, shot size | Viewpoint and perspective | Fast; preserves the camera position and the perspective of the first setup | The look of depth of field and image rendering may change; framing at a fixed position is the only variable |
| **Digital cropping in post** | The visible part of the image | Perspective, depth of field, motion blur of the original capture | No new setup; flexible | Resolution loss; fixed perspective; subject position and headroom are limited to what was captured |

**Resolution arithmetic:** Cropping a 3840-pixel-wide frame to half its width leaves 1920 pixels (one quarter of the pixel count); cropping to one-third leaves 1280 pixels (one ninth). The crop is acceptable only if the delivery resolution can tolerate it.

## 6.5 Examples Preserving Nominal Shot Size While Changing Visual Character

**Example A — Chest-up dialogue.**
- *Camera moved close with a 35 mm lens:* intimate, background wide and spacious, slight distortion.
- *Camera farther with an 85 mm lens:* flatter face, background compressed, subject separated by blur.
- *Cropped from a wide 4K shot:* same perspective as the wide shot; background shows its original spatial relationships; lower resolution.

**Example B — Full-body walk.**
- *24 mm at 2 m:* the subject looks large in a spacious environment; the corridor walls rush past; limbs closer to the camera look bigger.
- *85 mm at 7 m:* subject and environment look stacked; walking toward the camera seems slower in apparent progress.

**Example C — Object close-up.**
- *Macro lens at close distance:* the object fills the frame with tiny depth of field.
- *Long lens from farther:* the object is the same size but with more working distance and less intrusion on the object.

**Diagnosis tip:** If two shots have the same nominal size but look as though they belong to different films, compare **camera positions** and **focal lengths**.

## 6.6 Zoom Versus Dolly (Camera Movement and Shot Size)

- **Zoom** changes the focal length during the shot: the field of view narrows or widens without changing viewpoint. Perspective stays the same; the subject gets larger or smaller within the same spatial relationships.
- **Dolly or push-in** moves the camera toward or away from the subject: the viewpoint changes, so perspective and background relationships change.

Both change the shot size over time. They do not look the same.

---
# 7. SHOT SIZE AND COMPOSITION

**Scope reminder:** Composition has its own knowledge base. This section covers only how it interacts with shot-size decisions.

**Principle (established craft):** Shot size decides *how much* goes into the frame; composition decides *where and how* it is arranged. Changing the shot size changes the compositional problem. A good composition at one size may fail at another.

## 7.1 Interaction Summary

| Compositional factor | How shot size affects it | What to check |
|---|---|---|
| **Subject placement and visual hierarchy** | In wider shots, placement and contrast decide where the eye goes; in tighter shots, the subject dominates by default. | Does the eye land on the intended subject first? |
| **Negative space** (empty area around the subject) | Wider shots have more of it; it can carry meaning (isolation, calm) or look like waste. | Is the empty space motivated? |
| **Headroom and footroom** | Margins shrink as shots tighten; they are most noticeable in medium shots. | Are margins consistent with neighbors and not accidental? |
| **Looking room and lead room** | Tighter shots make insufficient room more noticeable. | Is there space in the direction of gaze or travel? |
| **Foreground and background** | Tighter shots reduce background and make foreground objects overlap the subject more. | Do foreground elements block or frame the subject? |
| **Environmental context** | Lost progressively as shots tighten. | Is the necessary context still visible? |
| **Subject separation** (distinction from background) | In close shots, background is usually distant or blurred; in wide shots, the subject must separate by contrast, color, or movement. | Can the subject be distinguished at a glance? |
| **Multiple subjects** | A given frame size limits how many can be included at readable scale. | Are all necessary subjects visible and readable? |
| **Overlapping bodies or objects** | Tight multi-subject frames increase overlap. | Is any face or key object blocked? |
| **Background clutter** | Wide shots include more clutter; tight shots can hide it. | Is anything distracting near the subject or the edges? |
| **Aspect ratio and safe framing** | The same shot size has different margins in different frame shapes. | Are critical elements away from the edges and platform overlays? |

## 7.2 Aspect Ratio and Shot Size

The shot-size landmark (for example, "waist-up") stays the same across aspect ratios, but the frame changes what else is included.

| Aspect ratio (examples) | Typical character | Effect on a *waist-up* frame |
|---|---|---|
| **16:9 (wide)** | Standard horizontal | Subject plus background to each side; room for a second subject in a medium two-shot |
| **9:16 (vertical)** | Phone/short-form | Subject fills the width; very little side context; more vertical space above and below; two-shots at the same size become tight |
| **1:1 (square)** | Social formats | Balanced; tight for two people |
| **2.39:1 (anamorphic widescreen)** | Cinematic wide | Very little vertical space; full shots need distance; side context is large |
| **4:3** | Classic | Taller than 16:9; vertical subjects fit more comfortably |

**Rules of thumb (approximate):**

- A **full-length standing person** fits easily in 9:16 but occupies only part of the width in 16:9.
- A **two-person medium shot** fits comfortably in 16:9 and is a squeeze in 9:16.
- When changing aspect ratio, **re-evaluate the shot size**; do not assume the same framing works.

**Safe framing:** Keep critical information (faces, key objects, text) away from the extreme edges. Traditional broadcast guides used "action-safe" and "title-safe" areas (roughly the inner 93% and 90% of the frame; approximate). In vertical platforms, user-interface elements (captions, buttons) may cover parts of the bottom and sides, so keep key information inside a central area. Safe areas depend on the delivery platform; check it.

## 7.3 How Changing Shot Size Improves or Damages Composition

| Change | Possible improvement | Possible damage |
|---|---|---|
| **Tighten** | Removes clutter; emphasizes the subject; increases detail | Cramped margins; lost context; cut-off joints; overlapping foreground |
| **Widen** | Adds context; gives subjects room; clarifies spatial relationships | Subject too small; more clutter; weaker emphasis; empty areas |
| **Reframe by shifting the subject** | Better margins and balance | May change shot size slightly; may break continuity |

## 7.4 Diagnosing Composition Problems Related to Shot Size

| Problem | Likely cause | Evidence to inspect | Correction | Possible side effect |
|---|---|---|---|---|
| **Excessive empty space** | Shot too wide for the subject's importance; subject small; no motivation for space | Share of the frame occupied by the subject; whether the space carries meaning | Tighten one step; reposition the subject; add a meaningful element | Loses context |
| **Cramped framing** | Shot too tight for the subject or action; insufficient margins | Distance from the subject to each edge; looking room | Widen one step; shift the subject; add looking room | Loses detail |
| **Distracting background details** | Wide frame includes clutter; background too sharp or bright | Bright or high-contrast items near the subject | Reframe, change the camera position, simplify, or tighten | Changes perspective if the camera moves |
| **Awkward cropping** | Frame edge falls at a joint or slices a prop | Where the edges cut the subject | Move the crop to mid-segment or include the whole part | Slight change in shot size |
| **Unclear visual emphasis** | Multiple equally strong elements; subject not separated | Where the eye lands first | Change size so the primary subject dominates; reduce competing elements | May hide secondary information |

---

# 8. SHOT SIZE AND AUDIENCE EXPERIENCE

## 8.1 Principle: Framing Choice vs. Encouraged Interpretation

A shot size is a **framing choice**. The **interpretation** it encourages depends on context. This file therefore describes *tendencies* ("may encourage"), never guarantees.

## 8.2 Possible Effects (Context-Dependent)

| Experience | Tighter shot sizes may encourage | Wider shot sizes may encourage | Conditions that change the effect |
|---|---|---|---|
| **Perceived intimacy** | Closeness to the person | Observation from a distance, or the intimacy of a shared space if people are close together | Whether the person is welcoming or hostile; performance; sound |
| **Emotional proximity** | Sharing the character's feelings | Observing the character's situation | Whether the audience already cares about the character |
| **Vulnerability or dominance** | Vulnerability if the person cannot escape the frame; dominance if the subject looms | Vulnerability if the person is small; dominance if the person fills and controls space | Camera angle, lens, behavior, relative size of others |
| **Environmental scale** | Scale is implied by detail | Scale is shown | Reference objects present in frame |
| **Isolation or connection** | Psychological isolation if the background is empty or blurred | Spatial isolation if the person is distant from others | Who else is in the frame or nearby |
| **Mystery and information control** | Withholding the context | Withholding the detail | What the audience already knows |
| **Attention and visual priority** | The subject is prioritized | The viewer chooses where to look | Contrast, movement, and color |
| **Action readability** | Impact detail is shown; geography may be lost | Geography is clear; detail is small | Speed and complexity of action |
| **Subject–object relationship** | The object may dominate | The relationship between the subject and the object is visible | Distance between the two |

## 8.3 Why Context Changes Meaning

The same shot size can read differently because other variables change the information in the frame:

| Variable | How it can change the meaning of a shot size |
|---|---|
| **Performance** | A still face in a close-up can be calm or menacing depending on the eyes and timing. |
| **Camera angle** | A low-angle close-up may make a subject imposing; a high-angle close-up may make the subject seem small. |
| **Lens perspective** | A close-up with a wide lens looks distorted and intrusive; the same close-up with a long lens looks flatter and more observational. |
| **Lighting** | Soft light on a face can be tender; hard light from below can look threatening. |
| **Narrative information** | A close-up of a child's face means one thing before and another after the audience learns what the child has seen. |
| **Sound and editing** | A held wide shot with silence feels different from the same shot cut quickly with music. |

## 8.4 Same Shot Size, Different Effects

| # | Shot size | Context A | Effect A | Context B | Effect B | Why |
|---|---|---|---|---|---|---|
| 1 | **Wide shot** of one person in an empty field | The person has just escaped captivity and runs. | Freedom, relief | The person has been abandoned. | Isolation, helplessness | The story information changes how the same emptiness is read. |
| 2 | **Close-up** of a face | A lover listens to a confession. | Intimacy, anticipation | An interrogator stares at a suspect. | Pressure, scrutiny | Performance and situation define the relationship between the face and the viewer. |
| 3 | **Medium two-shot** | Two friends sit close, laughing. | Warmth | Two people sit close but turn away from each other. | Awkward tension | Behavior within the frame changes the meaning. |
| 4 | **Extreme close-up** of an eye | A baby's eye in morning light | Wonder | An eye behind a rifle scope | Menace | The surrounding context and sound change the same size. |
| 5 | **Full shot** of a standing person | A soldier stands at attention in a parade. | Discipline | A person stands motionless in a corridor at night. | Unease | Environment and lighting alter the reading. |

## 8.5 Practical Consequence

Do not choose shot size to "make the audience feel X." Choose shot size to deliver the *information* needed and then verify that performance, light, sound, and context carry the intended feeling.

---

# 9. SHOT SIZE AND CONTINUITY

**Conventional guidance** in this section reflects widely taught editing practice. It is not mandatory for all editing styles, and the cases where it can be broken deliberately are listed in 9.8.

## 9.1 Matching Shot Sizes Across Adjacent Shots

- **Matching** shot sizes can create rhythm and consistency (for example, alternating medium close-ups in a dialogue).
- **Different** shot sizes can show change of emphasis.
- **Nearly identical but not matching** sizes (for example, a medium close-up followed by a very slightly tighter medium close-up) can look like a mistake.

**Rule (convention):** Decide whether two adjacent shots should *match* or *differ clearly*. Avoid an ambiguous in-between.

## 9.2 The Jump-Cut Effect

A **jump cut** is a cut between two shots of the same subject with so little change in size or angle that the image appears to jump.

**Cause:** The viewer compares the two frames and perceives them as the same shot with something missing, rather than as two different views.

**Conventional guidance (editing tradition):**

| Guidance | Detail |
|---|---|
| **Change shot size by a clear amount** | Move at least about two steps on the ladder (for example, wide to medium, or medium to close-up), or change by one step if the angle also changes noticeably. |
| **Change angle** | A change of about 30 degrees in camera position is a widely cited minimum when the size stays the same ("30-degree rule"). |
| **Change both** | The safest way to avoid a jump cut is to change size and angle together. |

These are **approximate guides** that depend on lens, subject, and style. Some films use jump cuts deliberately (Section 9.8).

## 9.3 How Much Change Makes a Cut Feel Purposeful

A cut feels purposeful when the viewer sees **new information** or a **new emphasis**.

| Difference between shots | Likely perception |
|---|---|
| **None** | The cut feels like a glitch |
| **Very small** (less than one step) | The cut can feel like a jump cut or a mismatch |
| **Moderate** (one to two steps) | The cut can feel like a natural change of emphasis if the angle also changes |
| **Large** (three or more steps) | The cut feels deliberate, with a clear change of information or perspective |

Differences in subject position and action also contribute.

## 9.4 Matching Subject Position and Scale Across Reverse Shots

In dialogue, the shot of one person and the **reverse shot** (the shot of the other person) are usually matched for:

- **Shot size** (for example, both medium close-ups),
- **Camera height and angle relationship** (mirrored),
- **Eye-line position in the frame** (similar height and side),
- **Lens and background depth** (similar).

**Why:** Mismatches make one person look larger, closer, or more powerful than the other, whether or not that is intended.

**Intentional mismatch:** If one person should feel dominant or isolated, use unequal sizes deliberately and keep the pattern consistent.

## 9.5 Maintaining Consistent Perceived Distance During Dialogue

- Keep the **same nominal shot size** for each speaker unless there is a reason to change.
- When changing size (for example, tightening as emotion rises), change **both** speakers in a compatible way or give a clear reason for the asymmetry.
- Avoid shifts in size that the story does not motivate.

## 9.6 Preserving Spatial Relationships in Multi-Subject Scenes

- Establish who is where in a **wider shot** before cutting to tighter ones.
- In tighter shots, preserve **left/right relationships** and eye-lines.
- Keep consistent distances: if two people are close in the wide, they should not seem far apart in the tight shots.

## 9.7 Maintaining Framing as a Subject Moves

| Movement | Framing risk | Guidance |
|---|---|---|
| **Standing up from sitting** | Head rises out of a tight frame | Start with extra headroom or tilt/reframe with the motion |
| **Sitting down** | Head drops, leaving empty headroom | Reframe or start slightly higher |
| **Turning** | Looking room changes sides | Shift the subject to preserve looking room |
| **Approaching the camera** | Shot size tightens | Plan the end size; widen at the start; consider a push-out |
| **Moving away** | Shot size widens; subject shrinks | Consider following or accepting the change |

## 9.8 When Continuity Breaks

| Cause | Result |
|---|---|
| **Unexpected change in camera distance** | The subject appears to jump in scale; the background changes magnification |
| **Mixing focal lengths without adjusting distance** | The same nominal size has different perspective, so shots do not match |
| **Different cropping or digital reframing** | The sizes do not match and the image resolution changes |
| **Unplanned zoom or drift** | Shot size changes during the shot |

**Deliberate breaks (context-dependent):**
- **Jump cuts** for a fragmentary or restless style.
- **Abrupt size changes** for shock.
- **Intentionally mismatched sizes** to emphasize power or isolation.
- **Style-led editing** that does not follow conventional continuity.

## 9.9 Maintaining Intended Subject Scale Across AI-Generated Clips

AI generation does not automatically preserve framing. Use these methods:

1. **Write scale numerically.** "The subject occupies about 60% of the frame height" is more stable than "medium shot."
2. **Restate landmarks in every prompt.** "Top of head to waist, hands visible."
3. **Use the last frame of the previous clip as a reference** when generating the next, and state "same framing and subject scale as the reference."
4. **Lock aspect ratio and orientation** across clips.
5. **Lock camera behavior:** "static camera; no zoom; no push-in" if no change is intended.
6. **Describe planned size changes explicitly:** "begin at medium close-up; end at close-up."
7. **Review adjacent clips side by side:** compare head size, margin sizes, and horizon height.
8. **Correct drift immediately** by restating the boundaries rather than adding more adjectives.

---

# 10. SHOT-SIZE PROGRESSION ACROSS A SCENE

## 10.1 Progression Patterns

| Pattern | Shape | Typical use | Risk |
|---|---|---|---|
| **Wide-to-close** | Establish, narrow to detail | Entering a scene, building focus, revealing information gradually | Predictable if overused |
| **Close-to-wide** | Start with detail, widen to reveal | Withholding context, then revealing (a surprising setting or situation) | The reveal must be worth waiting for |
| **Gradual scale change** | Small steps across shots | Building tension or intimacy slowly | Steps too small may be unnoticed or look like jump cuts |
| **Sudden change** | Large jump | Shock, revelation, emphasis | Must be motivated |
| **Alternation** | Environment ↔ intimate | Showing the relation between a person and a place | Can feel mechanical if rhythmic without purpose |
| **Progressive tightening** | Each shot closer | Revealing information or increasing pressure | May exhaust the ladder too early |
| **Withholding via wider or partial framing** | Keep information out of frame | Mystery, surprise | Frustration if overused |
| **Contrast** | Opposite sizes adjacent | Change in emphasis | Disorientation without a cue |

## 10.2 Rhythm and Variety

- **Rhythm** is the pattern of sizes over time. A coherent rhythm has a reason: for example, scenes tighten as stakes rise.
- **Variety** helps avoid monotony, but changing size every shot without purpose is arbitrary.
- **Repetition** (the same sizes in dialogue) can be effective, but it should vary when the scene's emotional state changes.

**Guidelines:**
1. Give each shot a job (see Step 1 in Section 2).
2. Reserve the tightest sizes for the moments that need them.
3. Revisit a wider size after sustained tight coverage to give the viewer spatial orientation.
4. Avoid changing size without changing information.

## 10.3 Worked Sequence A — Wide-to-Close Reveal (Arrival at a House)

**Narrative situation:** A woman returns to her childhood home and discovers that the door is open.

| # | Shot size | Narrative purpose | Information revealed | Connection to previous / next |
|---|---|---|---|---|
| 1 | **Extreme wide** (house tiny on a hillside, a small car on the road) | Establish isolation and place | The house is remote | **Next:** cut to a closer view of the house to show approach. |
| 2 | **Wide** (house and driveway, her car arriving) | Orientation and geography | Where the car is relative to the house | **Prev:** same location, new size; **Next:** cut closer to the woman. |
| 3 | **Full shot** (woman steps out, looks toward the house) | Introduce the character and her posture | Hesitation, costume, stance | **Prev:** brings the viewer to her scale; **Next:** her gaze motivates a view of the door. |
| 4 | **POV, medium-wide** (the front door slightly open) | Show what she sees | The door is open | **Prev:** gaze motivates the shot; **Next:** cut back to her reaction. |
| 5 | **Medium close-up** (her face, eyes narrowing) | Show her reaction | She senses something is wrong | **Prev:** answers the POV; **Next:** cut to a detail to give her motive. |
| 6 | **Insert** (her hand on the door handle, a small scratch on the lock) | Provide a clue | The lock was forced | **Prev:** from her face to her hand; **Next:** cut to a wider shot as she pushes the door. |
| 7 | **Wide interior** (the door opening onto a dark hall, she is a silhouette) | Return to context as she enters | The hall's layout and darkness | **Prev:** widening after the detail; **Next:** movement into the house. |

**Why this works:** Sizes tighten to deliver specific information, then widen again at the moment of crossing into a new space.

## 10.4 Worked Sequence B — Close-to-Wide Reveal (A Phone Call)

**Narrative situation:** A man stands at a window, speaks on the phone, and is revealed to be in a hospital room.

| # | Shot size | Narrative purpose | Information revealed | Connection to previous / next |
|---|---|---|---|---|
| 1 | **Close-up** (his face, tired eyes, window light) | Start on emotion; withhold place | He is distressed | **Next:** cut to a detail to hint at place. |
| 2 | **Detail** (his hand gripping a phone; a plastic bracelet on his wrist) | Plant a clue | The bracelet suggests a hospital | **Prev:** moves from face to hand; **Next:** cut to a medium shot to start widening. |
| 3 | **Medium shot** (him at the window, a curtain rail visible behind) | Begin to reveal context | A curtain rail, institutional | **Prev:** more context than the detail; **Next:** cut to a wider view. |
| 4 | **Medium long shot** (he turns; a bed edge enters the frame) | Confirm the setting | Hospital bed | **Prev:** continuing widening; **Next:** cut to a wide shot. |
| 5 | **Wide shot** (the full room: bed, monitor, an older woman asleep) | Complete the reveal | He is with a sick relative | **Prev:** completes the progression; **Next:** the final shot may be an extreme wide to leave the room. |

**Why this works:** The audience's questions ("where is he?" "why is he distressed?") are answered by progressively wider frames, with each new size adding one piece of information.

## 10.5 Worked Sequence C — Alternation Between Environment and Intimacy (A Quiet Dinner)

| # | Shot size | Narrative purpose | Information revealed | Connection |
|---|---|---|---|---|
| 1 | **Wide two-shot** (a couple at a long table) | Show distance between them | The table's length separates them | **Next:** tighten to the first person. |
| 2 | **Medium close-up** (the woman) | Show her expression | She is holding something back | **Prev:** from space to person; **Next:** reverse to the other person. |
| 3 | **Medium close-up** (the man, matching size) | Show his reaction | He avoids her gaze | **Prev:** matched size; **Next:** return to the wide shot for contrast. |
| 4 | **Wide two-shot** (the same as shot 1, but the candle has burned lower) | Mark time and distance | Time has passed; nothing has been said | **Prev:** returns to the opening size; **Next:** a detail. |
| 5 | **Detail** (her hand moving away from his) | Punctuate | Withdrawal | **Prev:** from wide to detail with a clear size change; **Next:** end. |

**Why this works:** Returning to the same wide frame lets the viewer compare time and distance, while the matched medium close-ups give each person equal visual weight.

## 10.6 Avoiding Repetitive or Arbitrary Changes

| Problem | Symptom | Correction |
|---|---|---|
| **Same size in every shot** | Monotony | Introduce a purposeful change in size when the information changes. |
| **Size changes without new information** | The cut feels arbitrary | Merge the shots or give each a distinct job. |
| **Over-tight too early** | Nowhere to go for the climax | Hold back the tightest sizes for key moments. |
| **Fragmented scene** | The viewer loses geography | Insert a wider shot to reorient. |

---
# 11. SHOT SIZE FOR ACTION AND MOVING SUBJECTS

## 11.1 Core Trade-Off: Whole Action vs. Specific Detail

| Choice | Strength | Weakness | Prefer when |
|---|---|---|---|
| **Show the whole action** (full or medium long) | The viewer understands geography, sequence, and cause and effect | Small details are lost | The mechanics or the space of the action matter |
| **Emphasize a detail** (medium or tighter) | Impact, effort, or a key gesture is readable | Geography and surrounding actions are lost | The detail is the information, and geography is already established |
| **Combine** (wide for geography, tight cut-ins for impact) | Both clarity and emphasis | Requires matching action across shots | Fights, chases, physical sequences |

**Principle:** Establish geography with a wider frame *before* using tight frames for impact, so the viewer can interpret the tight frames.

## 11.2 Framing Specific Actions

| Action | Recommended shot sizes | Planning notes | Common risk and correction |
|---|---|---|---|
| **Walking and running** | Full shot to medium long; wide for distance | Allow lead room in the direction of travel. A tracking frame keeps the subject at a consistent size. | *Risk:* the subject drifts toward the edge or changes size. *Fix:* match the camera speed or widen. |
| **Turning** | Medium to medium long | Allow space on both sides; looking room changes sides during the turn. | *Risk:* the face is cropped as the head turns. *Fix:* widen slightly. |
| **Reaching** | Medium or wider, depending on arm span | Include the hand's destination. | *Risk:* the hand leaves the frame. *Fix:* widen or reframe to include the target. |
| **Bending, sitting, standing** | Medium long or full | The head's vertical path changes. Start with room above and below. | *Risk:* the head exits at the top when standing. *Fix:* start with extra headroom or tilt with the motion. |
| **Fighting or physical confrontation** | Full or medium long for geography; medium for punches; cut-ins for impact | Keep both fighters visible in most shots; use tight shots for contact; keep sizes consistent within a beat. | *Risk:* too-tight shots hide who is hitting whom. *Fix:* widen; reduce the number of tight cut-ins; add a clear master. |
| **Handling small objects** | Medium for the person and object; close-up or insert for the object | Establish the object before the insert. | *Risk:* the object is unreadable. *Fix:* tighten and ensure focus. |
| **Entering or leaving a location** | Wide for the location; medium for the person at the threshold | Show the transition across the threshold; keep lead room. | *Risk:* the subject is lost at the doorway. *Fix:* widen so the doorway and the subject are both visible. |
| **Moving toward the camera** | Begin wider and tighten, or retreat with the subject | The shot size changes as the subject approaches. Plan the end size. | *Risk:* the subject ends up too large for the intended frame. *Fix:* start wider or move the camera back. |
| **Moving away from the camera** | Begin tight and widen, or follow with the subject | The subject shrinks; the environment grows. | *Risk:* the subject becomes a speck. *Fix:* follow or accept the shrinking deliberately. |
| **Moving across the frame** | Full or medium long, with lead room | Use lead room in the direction of travel. | *Risk:* the subject exits the frame early. *Fix:* pan or track. |
| **Interacting with another subject** | Two-shot or OTS; wider if the physical space matters | Keep both visible when their relationship matters. | *Risk:* one subject cropped. *Fix:* widen or re-stage. |
| **Actions needing environmental context** | Wide or medium long | Keep the environmental elements the action depends on in frame (a ladder, a door, a stove). | *Risk:* the action is incomprehensible. *Fix:* widen to include the necessary context. |

## 11.3 Avoiding Unintentional Cropping and Loss of the Subject

1. **Map the full path of the action** (start, peak, end) and test whether the frame holds all three.
2. **Add a margin of safety** for unpredictable movements.
3. **Plan reframing** (a pan, tilt, or a step back) if the action exceeds the frame.
4. **Check the end of the action** as well as the start.
5. **For AI video**, specify the subject's boundaries during the clip (see Section 12.9).

## 11.4 Making Movement Easy to Understand

- **Keep a consistent scale** across a movement unless a change is intended.
- **Keep the direction of travel consistent** (left to right, or the other way) across shots.
- **Show the beginning and the end** of a movement in the same or a compatible size.
- **Avoid cutting at the peak of an action with a large size change** unless the cut is deliberate.

---

# 12. AI IMAGE AND VIDEO GENERATION

This section translates shot-size decisions into precise generation instructions. It applies to image and video generation, whether prompted by text, by reference images, or both. **Model behavior varies.** Statements about model tendencies below are common observations to guard against, not guarantees about any particular model.

## 12.1 Why Shot-Size Names Alone Are Insufficient

**Reasons:**

1. **Names are variable.** "Medium close-up" and "close-up" have different crops in different traditions (Section 3.2).
2. **Models map words to typical images.** A phrase such as "wide shot" often produces *some* image associated with that phrase, not a measured framing.
3. **Names say nothing about margins.** The head may be cropped, the feet cut, or the subject placed off-center.
4. **Names say nothing about subject scale.** "Wide shot" can result in a subject at 10% or 60% of the frame.
5. **Names are inconsistent across clips.** Each generation interprets them freshly.

**Rule:** Use the shot-size name as a *label for the designer*. In the prompt, combine the name with **landmarks, margins, scale, and what must be visible.**

## 12.2 Specifying Subject Scale Within the Frame

State scale as an approximate fraction of the frame:

| Phrase | Meaning |
|---|---|
| "The subject occupies about 70% of the frame height." | The subject's visible portion spans about 70% of the vertical frame. |
| "The head occupies about 40% of the frame height." | Useful for close-ups and medium close-ups. |
| "The subject is a small figure, about 10% of the frame height." | Useful for very wide shots. |
| "The object fills about 60% of the frame width." | Useful for objects and detail shots. |

**Caution:** Numbers are guidance for the model and for the reviewer; they are not guarantees. Verify the result against the target by measuring or estimating.

## 12.3 Specifying Exact Visible Body Parts or Object Boundaries

Use **top and bottom boundaries** and, where needed, **side boundaries**:

- "From the top of the head to the waist; legs not visible."
- "Head, shoulders, and upper chest; both shoulders fully inside the frame."
- "Both hands and wrists fill the frame; fingers fully visible; face not visible."
- "The entire car including all four wheels, with a small margin around it."

**Tip:** State what is *not* visible by describing what the frame ends at, rather than listing exclusions ("ends at the waist" rather than "no legs").

## 12.4 Specifying Headroom, Footroom, and Other Framing Margins

| Margin | Example phrasing |
|---|---|
| **Headroom** | "A small margin above the head, about the height of a hand." / "The top of the hair is slightly cropped." |
| **Footroom** | "A margin below the shoes of about 5% of the frame height." |
| **Looking room** | "More space on the right, in front of her gaze." |
| **Lead room** | "Open space ahead of him in the direction he is walking." |
| **Side margins** | "Both arms fully inside the frame with space on each side." |

## 12.5 Whether the Entire Subject Must Remain Visible

State explicitly:

- **When the entire subject must remain visible:** "The entire body, including both feet and the top of the head, remains inside the frame for the whole clip."
- **When partial framing is intentional:** "The frame ends at mid-thigh; the feet are not visible."
- **When the subject moves:** "The subject stays fully visible throughout the movement."

**Why:** Models commonly crop heads and feet in wide and full shots when the subject is not explicitly constrained. Ask for visibility directly.

## 12.6 The Amount of Environment That Should Remain Visible

Specify the environment as a **ratio** or as **required landmarks**:

| Intent | Example phrasing |
|---|---|
| **Large environment** | "The environment fills about 80% of the frame; the subject is a small figure at the lower left." |
| **Moderate environment** | "Her full body is visible; the street and two shopfronts remain readable behind her." |
| **Minimal environment** | "The background is a blurred wall; no other objects are readable." |
| **Required landmarks** | "The doorway and the table remain visible behind the subject." |
| **No environment** | "The face and hair fill the frame; no background is visible." |

**Rule:** If a specific object or location element must be recognizable, name it and place it ("the clock tower visible at the right edge").

## 12.7 Camera Distance, Lens, and Perspective Words

- **Camera distance** ("about two meters from the subject") can guide the model but does not guarantee framing; combine it with landmarks.
- **Focal-length words** ("35 mm," "85 mm") may influence perspective and background compression; **do not rely on them to determine shot size**. State the framing separately.
- **Avoid contradictions**: "extreme close-up with a very wide-angle lens, full body visible" is internally conflicting.
- **Perspective choice** should be stated when it matters: "long-lens look, compressed background" or "wide-angle look, expanded space."
- **Camera angle** is a separate variable; state it separately ("eye-level").

## 12.8 Aspect Ratio and Orientation

- State the **aspect ratio** and **orientation** (for example, "vertical 9:16").
- **Re-specify the shot size** for the frame shape: a full-body standing subject in 9:16 can fill the frame height, while the same subject in 16:9 has large side margins.
- **Check safe areas** for the delivery platform and keep key content inside them.

## 12.9 Controlling Shot Size in Video: Movement, Drift, and Change

| Goal | Prompt strategy |
|---|---|
| **Stable shot size** | "Locked-off camera; no zoom; no push-in; the framing stays the same for the entire clip; the subject stays at about 60% of the frame height." |
| **Planned size change** | "The shot begins as a medium shot, waist-up, and slowly pushes in to a close-up of the face over the clip." |
| **Subject moving in a fixed frame** | "The camera stays still; the subject walks toward the camera; the shot begins wide and the subject grows larger." |
| **Tracking at a constant scale** | "The camera moves with the subject at the same speed; the subject remains at about 50% of the frame height." |
| **Reframing** | "The camera tilts up to keep the head inside the frame as she stands." |

**Drift to prevent:** Video models may slowly zoom, push in, or reframe even when not asked. Counter by stating "no camera movement" or by specifying the exact movement desired, and review the last frame against the first.

## 12.10 Multiple Subjects

- **State each subject's visibility:** "Both people visible from the waist up, with faces unobstructed."
- **State spacing and overlap:** "A hand's width between them; neither body overlaps the other."
- **State relative scale:** "Both people at the same scale; the person on the right is not closer to the camera."
- **State viewpoint for OTS:** "Over the left person's shoulder; the right person's face is the focus."

## 12.11 Preserving Shot Size Across Shots, Clips, and Reference Images

| Method | Description | Caution |
|---|---|---|
| **Shot Lock block** | A short block repeated across prompts that fixes the aspect ratio, scale, margins, and camera behavior. | Keep it short; long blocks dilute the rest of the prompt. |
| **Landmark restatement** | Restate the landmarks in each prompt. | Avoid synonyms that change the crop. |
| **Last-frame reference** | Use the final frame of the previous clip as the reference for the next. | State what to preserve (framing and scale) and what to change. |
| **Same camera behavior** | Specify the same movement or stillness. | Even then, check for drift. |
| **Side-by-side review** | Compare head size, margins, and horizon height across clips. | Look for small drift that accumulates. |
| **Reference images** | A reference image defines identity and, often, framing. | A reference with a different crop can override the prompt's shot size; state the intended crop. |

## 12.12 Fixed vs. Variable Shot-Size Instructions

| **Must remain fixed (shot-size anchors)** | **Can vary without changing the shot size** |
|---|---|
| The named shot size and its landmarks | Background details that do not affect framing |
| Subject scale (percentage of frame) | Subject's expression |
| Top and bottom boundaries | Minor props not at the boundary |
| Headroom, footroom, and looking room | Light color and mood |
| Aspect ratio and orientation | Subtle gestures that do not change the crop |
| Camera movement behavior (still or moving) | Wording of the rest of the prompt |
| Which subjects must be visible | Costume details that do not alter the crop |

**Suggested format for a Shot Lock block:**

```
SHOT LOCK
Format:        [aspect ratio, orientation]
Shot size:     [name] — from [top boundary] to [bottom boundary]
Scale:         [subject share of frame height/width]
Margins:       [headroom / footroom / looking or lead room]
Visibility:    [what must remain fully visible; what is intentionally cropped]
Environment:   [required landmarks / amount of environment]
Camera:        [still / planned movement; no zoom unless stated]
```

## 12.13 Preventing Conflicting Instructions

| Conflict | Why it fails | Fix |
|---|---|---|
| "Extreme close-up, full body visible" | Incompatible scales | Choose one size, or split into two shots. |
| "Wide shot, detailed facial expression" | The face is too small to show detail | Choose a tighter size or accept less facial detail. |
| "Close-up, show the whole room" | The environment cannot fit | Use a wide shot or two shots. |
| "Medium shot, camera 10 meters away, 24 mm lens" | Distance and lens are inconsistent with the framing | Remove the numbers or choose consistent values. |
| "Static camera, slow push-in" | Contradictory movement | Choose one. |
| "Subject centered, with lots of looking room on the right" | Conflicting placement | Place the subject left of center. |

## 12.14 Common Model Tendencies and Countermeasures (Observations, Not Guarantees)

| Tendency | Countermeasure |
|---|---|
| Heads or feet are cropped in full or wide shots | State: "entire body visible with margin above the head and below the feet." |
| Subject is larger than intended | State a numeric scale and add "environment fills most of the frame." |
| A "close-up" appears as a medium shot | State landmarks: "face fills the frame from forehead to chin." |
| The subject drifts toward the center | State placement: "left third of the frame." |
| Camera slowly pushes in or out | State "locked-off, no zoom." |
| Background details intrude | State the required background in a short phrase and reduce other detail. |
| Extra hands or fingers appear in hand shots | State "five fingers on each hand, clearly separated" and keep the shot simple. |
| Backgrounds change between clips | Specify the landmarks to preserve and use a reference frame. |

## 12.15 Avoiding Overload

**Rule of the shot-spec budget:**

- One shot size.
- Top and bottom boundaries.
- One scale statement.
- One margin statement.
- One environment statement.
- One camera-behavior statement.

If a prompt needs more than this, the content is probably two shots.

## 12.16 Before-and-After Examples

Each "After" is a shot-size direction, not a whole-scene prompt.

### Example 1 — Full shot

- **Before:** "Full shot of a woman walking, cinematic."
- **After:** "Full shot: the entire body is visible from the top of the head to the shoes, with a small margin above and below; she fills about 65% of the frame height; open space ahead of her in the direction she walks; camera at her walking pace, no zoom."
- **Why it works:** Landmarks, scale, margins, and camera behavior are given. "Cinematic" is removed.

### Example 2 — Close-up

- **Before:** "Close-up of an old man, emotional."
- **After:** "Close-up: from the top of the hair to the base of the neck; the face fills about 75% of the frame height; both eyes in the upper third; no background detail readable; locked-off camera."
- **Why it works:** The crop is defined; "emotional" is replaced with framing that supports the viewing of expression.

### Example 3 — Wide shot

- **Before:** "Wide shot of a man in the desert."
- **After:** "Wide shot: a man fully visible, about 12% of the frame height, at the lower-left third; the desert and sky fill the rest; the horizon sits at the upper third; no other people."
- **Why it works:** It specifies the scale and the placement so the model does not produce a mid-sized figure.

### Example 4 — Medium shot

- **Before:** "Medium shot of two friends talking."
- **After:** "Medium two-shot, horizontal 16:9: both people from the head to the waist, side by side, a hand's width between them; both faces fully visible; a blurred café behind them."
- **Why it works:** Both subjects' boundaries, spacing, and visibility are stated.

### Example 5 — Over-the-shoulder

- **Before:** "Over-the-shoulder shot of a doctor and patient."
- **After:** "Over-the-shoulder shot: the patient's shoulder and back of the head at the left foreground edge, out of focus; the doctor from the head to the chest, sharp, in the right two-thirds of the frame."
- **Why it works:** The foreground and subject sizes are separated, along with their placement.

### Example 6 — Hand close-up

- **Before:** "Close-up of hands writing."
- **After:** "Hand close-up: one hand holding a pen on paper fills about 70% of the frame; the wrist and part of the sleeve visible; five fingers clearly separated; the written line sharp; no face visible."
- **Why it works:** It names the boundaries and constrains anatomy.

### Example 7 — Extreme close-up

- **Before:** "Extreme close-up of an eye, intense."
- **After:** "Extreme close-up: one eye and the brow fill the frame; the iris is sharp and large; eyelashes visible; no other face part visible."
- **Why it works:** It names what fills the frame and what is excluded.

### Example 8 — Planned size change in video

- **Before:** "Camera slowly moves closer to the girl."
- **After:** "The clip begins as a medium shot, waist-up, with the girl at about 55% of the frame height; over the clip the camera pushes in slowly to a close-up, face filling about 70% of the frame; no other movement; her position in the frame stays centered."
- **Why it works:** Start and end sizes are fixed, and the change is stated as one movement.

### Example 9 — Vertical frame

- **Before:** "Wide shot of a runner, vertical video."
- **After:** "Vertical 9:16 full shot: the runner fully visible, filling about 55% of the frame height, centered, with sky above and road below; the road leads into the distance."
- **Why it works:** The vertical frame is addressed; the subject is scaled for it.

### Example 10 — Cut-in to maintain continuity

- **Before:** "Close-up of the hand opening the door."
- **After:** "Cut-in: the same hand and sleeve as in the previous wide shot, turning a brass doorknob; the hand and knob fill about 60% of the frame; the door's edge visible at the right."
- **Why it works:** It matches the earlier clip's prop and costume, and it states the size.

---
# 13. SHOT-SIZE FAILURE DIAGNOSIS AND CORRECTION

## 13.1 Troubleshooting Table

| # | Intended framing | Observed result | Likely cause | Evidence to inspect | Corrective action | Possible side effect |
|---|---|---|---|---|---|---|
| 1 | Close-up of a face | The result is a medium shot; the face is small. | Shot named but not defined by landmarks; model default. | Share of frame height occupied by the head; where the bottom edge falls. | Add landmarks and scale: "forehead to chin fills the frame; head about 75% of frame height." | The model may over-tighten and crop the forehead. |
| 2 | Full shot of a standing person | Feet or the top of the head are cropped. | Subject not constrained to remain fully visible; tight margins. | Top and bottom margins; footroom. | State: "entire body, top of head to shoes, with a margin above and below." Widen slightly. | Subject becomes smaller than intended. |
| 3 | Context needed (location, other people) | The frame is too tight; the viewer cannot tell where the action happens. | Shot size chosen for detail without checking context. | Whether any landmark identifies the place. | Widen one step; add landmarks; or add an establishing shot. | Subject detail decreases. |
| 4 | Expression readable | The frame is too wide; the face is a few pixels. | Shot chosen for geography rather than expression. | Face size relative to the frame; viewing size. | Tighten to MCU or CU; or add a cut-in for the face. | Loses environmental context. |
| 5 | Natural-looking crop | The frame cuts at the knees, ankles, or wrists. | Crop line falls at a joint. | Where the edges cross the body. | Move the crop to mid-segment or include the whole part. | Shot size shifts slightly. |
| 6 | Balanced framing | Excessive headroom or empty space. | Subject too small or placed too low; the shot is too wide for its purpose. | Margins above and around the subject. | Tighten one step; reposition the subject; state "small margin above the head." | May cramp the frame. |
| 7 | Comfortable composition | Cramped frame; the subject presses against an edge. | Insufficient looking or lead room; too tight. | Space in front of gaze or movement. | Widen; shift the subject; add looking room. | Subject appears smaller. |
| 8 | Smooth cut between two shots | The cut feels like a jump or glitch. | Neighbor shot sizes and angles too similar. | Difference in size (steps) and angle between the shots. | Change size by at least about two steps, change angle, or merge the shots. | May introduce a mismatch in perspective. |
| 9 | Matched reverse shots | One person looks larger or closer than the other. | Different camera distances or focal lengths; AI generated each shot independently. | Head size, eye-line height, and background magnification in each shot. | Match size by landmarks and scale; match lens look; regenerate with a shared Shot Lock. | Over-matching may feel static. |
| 10 | Consistent subject scale across clips | Scale drifts between clips. | Each clip generated freshly; no shared scale statement; reference overriding framing. | Head height and margins across clips. | Add numeric scale; use the last frame as a reference; restate landmarks. | Over-constrained clips may look repetitive. |
| 11 | Stable shot size during a clip | The camera slowly zooms or pushes. | Model's default motion; ambiguous movement wording. | Compare first and last frames. | State "locked-off, no zoom, no push-in"; remove movement words from the prompt. | Frames may feel static. |
| 12 | A natural close-up | The face looks distorted, nose enlarged, background expanded. | The close-up was achieved with a wide-angle look at very close distance. | Facial proportions; background field of view. | Specify a longer lens look at greater distance, or change the camera position; keep the size unchanged. | The background becomes more compressed. |
| 13 | Same framing in a new aspect ratio | The framing breaks (subject cropped or tiny). | The shot size was not re-specified for the new frame. | Margins and visible landmarks in the new frame. | Re-specify landmarks and scale for the new aspect ratio. | May require reshooting or regeneration. |
| 14 | Following a moving action | The action leaves the frame or becomes unreadable. | Frame too tight for the movement; no lead room; no reframing. | Path of the action vs. the frame boundaries. | Widen; add lead room; plan a track or pan; state that the subject stays visible. | Detail is lost. |
| 15 | Subject as the focus | An object near the lens dominates the frame. | Confusion between the subject's shot size and an object's apparent size. | What occupies the largest area of the frame. | Move or remove the near object; or state the primary subject's scale. | Foreground depth cue lost. |
| 16 | Controlled information reveal | The reveal comes too early or never arrives. | Frame shows or hides the wrong information. | The must-see and must-not-see lists vs. the frame content. | Widen to reveal; tighten or partially frame to withhold. | May change continuity with neighbors. |

## 13.2 Diagnostic Order

**Principle:** Diagnose from the layers that *define the frame* toward the layers that *decorate it*. Change **one** thing at a time, then re-evaluate.

| Order | Layer | Question | Why first |
|---|---|---|---|
| **1** | **Purpose and acceptance criteria** | Is the shot's purpose and its must-see list defined? | A flawed brief cannot be fixed by execution. |
| **2** | **Format** | Are aspect ratio and orientation as intended? | A wrong frame shape invalidates other measurements. |
| **3** | **Landmarks** | Do the top and bottom boundaries match the specified crop? | The core definition of shot size. |
| **4** | **Scale** | Does the subject occupy the intended share of the frame? | The most direct measurable property. |
| **5** | **Margins and placement** | Are headroom, footroom, looking room, and lead room right? | These determine the comfort of the framing. |
| **6** | **Visibility and cropping** | Is everything that must be visible actually visible, and do crops avoid joints? | Prevents hidden information. |
| **7** | **Environment** | Is the necessary context visible and the clutter limited? | Environmental information is lost first as the frame tightens. |
| **8** | **Lens and perspective** | Does the perspective match the intended look and neighbors? | Same size can look different. |
| **9** | **Camera behavior** | Is there unintended zoom or drift? | Movement changes shot size in time. |
| **10** | **Neighbor continuity** | Does the shot connect to its neighbors? | Continuity is relative. |
| **11** | **Prompt conflicts** | Are there contradictory instructions? | Conflicts cause inconsistent results. |

**Procedure:**

1. Identify the layer that most plausibly explains the symptom.
2. Make **one** targeted change.
3. Re-evaluate against the acceptance criteria.
4. Run a **regression check**: did the correction create a new problem (see "Possible side effect")?
5. If the symptom persists, move to the next layer.

---

# 14. PRACTICAL CASE STUDIES

Each case follows the same structure: situation → intended shot size and purpose → what the audience must see → main choices → failure points → flawed result and diagnosis → targeted correction.

---

## Case 1 — Introducing a Character at a Train Station

**Narrative situation.** Lena arrives at a platform with a single suitcase. This is her first appearance.

**Intended shot size and purpose.** **Full shot**; to introduce her posture, costume, and relation to the platform.

**What the audience must see.** Her whole body, her suitcase, her hesitant stance, a hint of the platform.

**Main choices.**
- **Boundaries:** Top of the head to the shoes, with a small margin above and below.
- **Scale:** About 65% of the frame height.
- **Margins:** Open space ahead of her gaze.
- **Environment:** Platform edge and a pillar visible.
- **Camera:** Locked-off.

**Failure points.** Cropped feet; the suitcase cut off; the subject too small, losing posture.

**Flawed result.** The generated image shows her from the head to the knees; the suitcase is not visible.

**Diagnosis (following the diagnostic order).**
1. *Purpose:* clear (character introduction). ✔
2. *Format:* correct. ✔
3. *Landmarks:* the bottom boundary is at the knees, not the shoes. ✘
4. *Scale:* too large (about 90%). ✘

**Targeted correction.** First change only the landmarks and the visibility constraint: "The entire body and the suitcase visible, from the top of the head to the shoes, with a margin of about 5% of the frame height below the shoes." Then check the scale; if still large, add "she occupies about 65% of the frame height."

**Why it should work.** The model treated "full shot" loosely. Naming the bottom boundary and requiring the suitcase fix the crop; the scale statement keeps margins.

---

## Case 2 — A Dialogue With Mismatched Reverse Shots

**Narrative situation.** A manager and an employee argue at a desk. The shots alternate between them.

**Intended shot size and purpose.** **Matched medium close-ups** on both; equal visual weight.

**What the audience must see.** Each person's face and shoulders; reactions.

**Main choices.**
- **Boundaries:** Top of the head to mid-chest for both.
- **Scale:** Head about 40% of the frame height for both.
- **Eye line:** Eyes in the upper third; each person looks toward the other's side.
- **Lens look:** The same moderate lens look and background distance.

**Failure points.** The manager appears closer and larger; the employee appears distant; the backgrounds differ in magnification.

**Flawed result.** The manager's clip is a close-up (head about 65% of the frame); the employee's clip is a medium shot (head about 25%).

**Diagnosis.**
1. *Landmarks:* different bottom boundaries. ✘
2. *Scale:* inconsistent. ✘
3. *Lens and perspective:* the backgrounds have different magnification. ✘ (secondary)

**Targeted correction.** Use a **Shot Lock** block in both prompts (head about 40% of frame height, top of head to mid-chest, eye line at the upper third). If the employee's clip still differs, use the manager's last frame as a framing reference and state "same scale and eye-line height."

**Why it should work.** Dialogue conveys equality when both sides share scale. The Shot Lock removes variation in interpretation.

---

## Case 3 — Revealing a Threat in the Background

**Narrative situation.** A girl plays in a yard while a stranger stands at the far fence.

**Intended shot size and purpose.** **Wide shot** that lets the audience see the stranger before the girl does.

**What the audience must see.** The girl and the stranger, with the distance between them.

**Main choices.**
- **Boundaries:** Both fully visible; the girl at the left-lower third, the stranger small at the right edge.
- **Scale:** The girl about 20% of the frame height; the stranger about 8%.
- **Focus and light:** Neutral; nothing draws attention to the stranger beyond placement.

**Failure points.** The stranger is cropped by the edge; the stranger is too small to notice; or the stranger is so prominent that the scene becomes a reveal rather than a discovery.

**Flawed result.** The model generates a close-up of the girl; the stranger is not visible.

**Diagnosis.**
1. *Purpose:* the shot must show both. ✔
2. *Landmarks:* the frame is too tight. ✘
3. *Visibility:* the stranger is absent. ✘

**Targeted correction.** "Wide shot: the girl fully visible at the lower left, about 20% of the frame height; at the far fence on the right edge, a man standing motionless, about 8% of the frame height, fully inside the frame; the yard fills the rest."

**Why it should work.** The shot size is defined by both subjects' scales; the stranger's size and position make him discoverable rather than emphasized.

---

## Case 4 — A Small Clue: The Ring on the Counter

**Narrative situation.** A detective notices a ring on the kitchen counter. The ring is engraved with a date.

**Intended shot size and purpose.** **Insert shot** (object close-up) to deliver the date.

**What the audience must see.** A readable engraving, the ring's position on the counter.

**Main choices.**
- **Boundaries:** The ring fills about 60% of the frame width; the counter's edge visible.
- **Focus:** Sharp on the engraving.
- **Camera:** Still.

**Failure points.** The ring too small to read; text distorted by the AI; the shot too tight to show it is on the counter.

**Flawed result.** The generated frame is a wide shot of the kitchen with a tiny ring; the engraving is unreadable.

**Diagnosis.**
1. *Landmarks/scale:* the ring occupies about 3% of the frame. ✘
2. *Information:* the key information (date) is lost. ✘

**Targeted correction.** "Insert shot: a gold ring on a granite counter, filling about 60% of the frame width; the inner engraving is sharp and large; the counter's edge visible at the bottom; no hands." If the engraving is garbled, simplify the text and state only what the viewer needs.

**Why it should work.** The shot size is matched to the information carrier (small text). The counter's edge links the insert to the scene.

---

## Case 5 — A Chase in Vertical Video

**Narrative situation.** A courier runs down an alley, pursued by someone out of frame. The video is vertical 9:16.

**Intended shot size and purpose.** **Medium long shot** following the courier; the viewer must follow the movement and sense urgency.

**What the audience must see.** The courier's body and arms, the alley ahead, the sense of pursuit.

**Main choices.**
- **Boundaries:** Top of the head to just below the knees.
- **Scale:** About 60% of the frame height.
- **Camera:** Tracking backward at the courier's speed; the courier stays at the same size.
- **Lead room:** The alley ahead visible above and around the figure.

**Failure points.** The courier drifts to the edge; the camera falls behind and the courier shrinks; legs and feet are cropped, hiding the running mechanics.

**Flawed result.** The courier moves from the center to the lower part of the frame and becomes smaller; the camera shakes unpredictably.

**Diagnosis.**
1. *Format:* vertical; the shot size should have been specified for it. ✔
2. *Scale:* shrinks during the clip. ✘
3. *Camera behavior:* tracking speed does not match. ✘

**Targeted correction.** "Vertical 9:16: the camera tracks backward at the courier's speed; the courier stays at about 60% of the frame height, centered; knees up visible; the alley ahead visible above his head; no zoom."

**Why it should work.** Specifying both scale and tracking behavior prevents drift; the vertical frame is used for the alley's depth above the figure.

---

## Case 6 — Isolation in a Vast Environment

**Narrative situation.** After a storm, a man stands in a flooded field and watches the horizon.

**Intended shot size and purpose.** **Very wide shot**; show that he is small within the devastation.

**What the audience must see.** The man as a small, identifiable figure; the extent of the flooding.

**Main choices.**
- **Boundaries:** The man fully visible, about 8% of the frame height, lower-left third.
- **Environment:** Water, sky, distant trees; the horizon at the upper third.
- **Camera:** Locked-off.

**Failure points.** The man too large, losing the effect; the man too small, vanishing; a distracting object dominates the foreground.

**Flawed result.** The man occupies 45% of the frame, with the flood visible only at the edges.

**Diagnosis.**
1. *Scale:* far too large. ✘
2. *Environment:* too little. ✘

**Targeted correction.** "Very wide shot: a man standing in knee-deep floodwater, about 8% of the frame height, in the lower-left third; floodwater fills the lower half of the frame and sky the upper half; the horizon at the upper third; no foreground objects."

**Why it should work.** The model is told how small to render the subject and how much of the frame the environment should occupy.

---

# 15. QUALITY CONTROL AND FINAL VERIFICATION

## 15.1 Purpose and Use

Use this checklist **before approving a shot design** (pre-production) and **before approving a generated or filmed result** (post-production). Evaluate the *frame* against observable criteria, not against the label in the brief.

## 15.2 Verification Checklist

Rate each item **Pass**, **Minor issue**, or **Critical failure**.

| # | Question | Pass criterion | Severity if failed |
|---|---|---|---|
| 1 | **Is the shot's purpose defined?** | A one-sentence purpose and a must-see list exist. | **Critical** |
| 2 | **Is the shot size defined by landmarks, not just a name?** | Top and bottom boundaries and an approximate scale are written. | **Critical** |
| 3 | **Does the frame match the defined landmarks?** | The visible crop matches the specified boundaries. | **Critical** |
| 4 | **Does the frame deliver the must-see information?** | All essential information is visible and readable. | **Critical** |
| 5 | **Does it withhold what must be withheld?** | Information to be withheld is not visible. | **Critical** if the reveal changes the story; **Minor** otherwise |
| 6 | **Is the aspect ratio correct and the framing appropriate for it?** | Format matches the brief; critical elements are inside safe areas. | **Critical** if wrong; **Minor** if edges are slightly close |
| 7 | **Are margins appropriate?** | Headroom, footroom, looking room, and lead room fit the design. | **Minor** (or **Critical** if the subject is cropped unintentionally) |
| 8 | **Are crops at mid-segment, not joints?** | No accidental amputating crop. | **Minor** (or **Critical** if it hides essential action) |
| 9 | **Is the environment sufficient and uncluttered?** | Needed context visible; no distracting objects at the edges. | **Minor** |
| 10 | **Does the lens/perspective suit the intent and neighbors?** | Perspective and background magnification are consistent. | **Minor** (or **Critical** if distortion is unintended) |
| 11 | **Is camera behavior as specified?** | No unintended zoom, push, or drift. | **Critical** if the shot size changes unintentionally |
| 12 | **Does it connect to neighboring shots?** | The size difference is clear or matched as intended; no unintended jump-cut effect. | **Critical** if the cut is confusing; **Minor** if slightly abrupt |
| 13 | **Are reverse shots and multi-subject frames consistent?** | Scale and eye-line match; all necessary subjects visible. | **Critical** if one subject is hidden or inconsistent |
| 14 | **Is the subject scale consistent across clips?** | Scale differences are within the stated tolerance (for example, ±10%). | **Minor** (or **Critical** if it changes meaning) |
| 15 | **Are acceptance criteria met?** | Every written criterion is verified. | **Critical** for each unmet core criterion |

## 15.3 Critical Failures vs. Minor Refinements

### Critical failures (must be corrected before approval)

- The shot size is undefined, or the defined crop is not what appears.
- Essential information is missing from the frame, or information to be withheld is visible.
- The subject is unintentionally cropped, or action leaves the frame.
- The aspect ratio is wrong, or critical content lies outside safe areas.
- The shot size changes unintentionally during a clip.
- Adjacent shots mismatch in a way that confuses the viewer or implies an unintended power relationship.
- A required subject is missing or hidden in a multi-subject frame.
- Perspective distortion changes the subject's appearance in an unintended way.

### Minor refinements (may remain a stylistic choice)

- Slight differences in headroom or scale within tolerance.
- A small difference between nominal sizes that does not change the information.
- A background detail that does not compete for attention.
- A stylistic margin choice that is documented as intentional.
- A mild perspective difference between shots that is not noticeable in context.

**Approval rule.** Approve only when there are **no critical failures** and all minor issues are corrected or recorded as acceptable stylistic choices.

## 15.4 Reviewer Procedure

1. **Overlay a grid** (thirds or a 10-division grid) on the frame to estimate the subject's share of the frame and the margins.
2. **Read the crop:** note where the frame edges cross the subject.
3. **List visible information** and compare it with the must-see and must-not-see lists.
4. **Compare neighbors:** place adjacent shots side by side; compare scale, margins, and perspective.
5. **Check camera behavior** by comparing the first and last frames.
6. **Decide:** approve, revise (with a single targeted change), or reject (return to the brief).

---

# 16. QUICK REFERENCE

## 16.1 Shot-Size Decision Sequence

1. **Purpose:** What must this shot do?
2. **Information:** What must be seen? What must be withheld?
3. **Context:** How much environment is needed?
4. **Carrier:** Expression, body language, action, object, or spatial relationship?
5. **Size:** Choose by landmarks (top and bottom boundaries) and scale.
6. **Margins and placement:** Headroom, footroom, looking and lead room.
7. **Camera behavior:** Still, tracking, or planned size change.
8. **Neighbors:** Check continuity and difference between shots.
9. **Criteria:** Write acceptance criteria.
10. **Generate or shoot, then verify.**

## 16.2 Ladder Summary (Approximate)

| Rung | Name | Bottom crop (standing person) | Primary use |
|---|---|---|---|
| 1 | Extreme wide | Whole body tiny (under about 5%) | Scale, world |
| 2 | Very wide | Whole body small (about 5–15%) | Person in place |
| 3 | Wide / long | Whole body in large environment (about 15–40%) | Geography, action in context |
| 4 | Full | Head to toe (about 50–90%) | Introduction, physical action |
| 5 | Medium long | Knees | Posture, walking |
| 5b | Cowboy / American | Mid-thigh | Standoffs, hands at hips |
| 6 | Medium | Waist | Conversation |
| 7 | Medium close-up | Mid-chest | Dialogue, reaction |
| 8 | Close-up | Shoulders/neck | Expression |
| 9 | Extreme close-up | Feature or detail | Emphasis |

## 16.3 Shot Size vs. Related Concepts (Compact)

| Concept | Answers | Independent of shot size? |
|---|---|---|
| Shot size | How much of the subject is in the frame? | — |
| Camera angle | From which direction is the subject seen? | Yes |
| Camera distance | How far is the camera? | Partly (size also depends on lens and sensor) |
| Focal length / FOV | How wide is the view from a position? | Partly |
| Aspect ratio | What is the shape of the frame? | Yes, but it changes what a given size includes |
| Composition | Where and how is the subject arranged? | Yes |
| Digital crop | Was the framing changed after capture? | A crop changes shot size but not perspective |
| Camera movement | Does the framing change over time? | A move can change size during the shot |
| Apparent object size | How big does one object look? | Yes |

## 16.4 Common Shot-Size Errors and Solutions

| Error | Solution |
|---|---|
| Using a shot-size name without landmarks | Add top and bottom boundaries and an approximate scale. |
| Assuming a name has one universal meaning | Specify the crop. |
| Treating shot size as an emotion | Choose size for information; verify the emotion with other variables. |
| Cropping at joints | Move the crop to mid-segment or include the whole part. |
| Cramped margins | Add headroom and looking or lead room; widen. |
| Excess empty space | Tighten or reposition the subject; motivate the space. |
| Too tight to understand context | Widen or add an establishing shot. |
| Too wide to read expression | Tighten or cut in. |
| Nearly identical neighboring sizes | Change size clearly, change angle, or merge. |
| Mismatched reverse shots | Match scale and eye-line with a shared Shot Lock. |
| Camera drift in video | State "locked-off, no zoom," or the exact movement. |
| Confusing size with lens | Specify framing and perspective separately. |
| Scale drift across AI clips | Use numeric scale, last-frame references, and landmark restatement. |
| Aspect ratio change without re-framing | Re-specify landmarks for the new frame. |
| Action leaving the frame | Map the path; widen; plan a track. |

## 16.5 Final Operational Rule Set

1. **Define purpose and the must-see list before choosing a size.**
2. **Choose shot size to deliver information, not to produce an emotion.** Verify emotion with performance, light, sound, and context.
3. **Specify landmarks.** Always give top and bottom boundaries; a name alone is insufficient.
4. **Treat terms as variable.** Where exact framing matters, replace the name with a crop description.
5. **State subject scale** as an approximate share of the frame.
6. **State margins** (headroom, footroom, looking room, lead room) and keep crops off joints.
7. **State the environment requirement** (amount or required landmarks).
8. **Separate shot size from angle, distance, lens, aspect ratio, composition, cropping, and movement,** and specify each when it matters.
9. **Remember perspective comes from camera position.** Choose between moving the camera, changing the lens, and cropping, knowing their different effects.
10. **Re-specify framing when the aspect ratio changes.**
11. **Plan continuity:** match or clearly differentiate adjacent shots; keep reverse shots consistent; apply conventional guidance but break it only deliberately.
12. **Give each shot a job in the progression;** avoid arbitrary size changes.
13. **Lock the camera** (or specify its movement exactly) to prevent unintended shot-size changes.
14. **Budget the prompt:** one size, one scale, one margin note, one environment note, one camera note; split into two shots if more is needed.
15. **Verify the frame, not the label:** estimate scale, check crops, compare neighbors, and compare first and last frames.
16. **Diagnose in order** (purpose, format, landmarks, scale, margins, visibility, environment, lens, camera, neighbors, prompt conflicts), change one thing at a time, and check for side effects.
17. **Approve only when no critical failure remains,** and record stylistic exceptions as intentional.

---

*End of file — Shot_Size_Design_and_Control_Cinematic_Knowledge.md*
