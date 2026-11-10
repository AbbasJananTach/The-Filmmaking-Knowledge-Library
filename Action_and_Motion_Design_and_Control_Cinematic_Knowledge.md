# Action and Motion Design and Control — Cinematic Knowledge Base

**File:** `Action_and_Motion_Design_and_Control_Cinematic_Knowledge.md`
**Purpose:** Teach a filmmaker or an AI filmmaking assistant how to design, describe, generate, evaluate, and correct believable **action and motion** in cinematic images and video.
**Scope lock:** This file is about what subjects do and how they, their parts, and the objects around them move over time. Camera movement, shot size, camera angle, composition, lighting, focus, editing, and mood appear here *only* where they directly affect the design, readability, continuity, or evaluation of action and motion. Each of those disciplines has its own dedicated knowledge base, and this file does not replace them.
**Content note:** Physical confrontation is covered only as non-graphic, readable choreography (positions, timing, contact, and response). No injury detail is included.

---

## How to Use This File

**For a human filmmaker:** Read Sections 1–2 for the mental model, use Sections 3–6 as a movement reference, and use Sections 17, 19, and 20 as working tools in planning and review.

**For an AI system:** Treat this file as a decision procedure. The operating loop is:

1. Define the action's purpose, the subject's intention, and its start and end states (Sections 1–2).
2. Break the action into phases and specify direction, path, timing, contact, and consequence (Sections 3–9).
3. Check plausibility, style, and emotional meaning (Sections 4, 10, 11).
4. Specify the action for generation using observable movement, with camera behavior kept separate (Sections 14–16).
5. Verify the result against observable criteria (Sections 19–20).
6. If it fails, diagnose in a fixed order and change the smallest relevant variable (Section 17).

**Epistemic conventions used in this file.** Movement knowledge combines physics, anatomy, performance craft, animation craft, and style. This file marks the difference:

- **Physical principle** — follows from mechanics (gravity, momentum, balance, contact). Violating it produces implausible motion unless the violation is deliberate stylization.
- **Craft convention** — a widely taught practice in performance, animation, or choreography. Useful, not universal.
- **Approximate value** — a typical figure (a duration, speed, or rate) that varies with the person, animal, object, surface, and situation. Treat as a starting estimate, never as a law.
- **Context-dependent meaning** — what a movement communicates depends on personality, culture, ability, and story. No movement has one universal meaning.

**Terminology rule.** Technical terms are defined the first time they appear. Where terms vary between fields (for example, "secondary action" in animation), this file states the definition it uses.

---

## Table of Contents

1. Action and Motion Fundamentals
2. Action-Design Decision Framework
3. Action and Motion Taxonomy
4. Body Mechanics, Balance, and Weight
5. Movement Timing, Speed, and Rhythm
6. Motion Paths and Spatial Relationships
7. Action Cause and Effect
8. Object Interaction and Contact
9. Multi-Subject Action and Coordination
10. Action, Emotion, and Character
11. Naturalism, Stylization, and Movement Quality
12. Secondary Motion and Follow-Through
13. Action Continuity Across Shots
14. Action and Camera Movement
15. Action Design for AI Image and Video Generation
16. Action Complexity and Generation Reliability
17. Action and Motion Failure Diagnosis
18. Practical Case Studies
19. Action-Design Worksheet
20. Quality Control and Final Verification
21. Quick Reference

---

# 1. ACTION AND MOTION FUNDAMENTALS

## 1.1 Definitions

**Action** is *goal-directed or state-changing behavior by a subject*, described by what the subject does and why ("she opens the door," "he flinches," "the dog stops and listens"). An action has an intention, a reaction, or a change of state behind it.

**Motion** is *the physical change of position, orientation, or shape over time* of any entity or part of an entity (a limb, a door, a leaf, a vehicle). Motion can be described without any reference to intention ("the forearm rotates 90° over 0.4 seconds"; "the door swings through an arc").

**Relationship:** An action is *realized through* motion. Motion is the visible evidence; action is the interpreted meaning. A leaf blowing across a path has motion but no action (no intention). A character deciding not to move performs an action (restraint) with almost no motion.

| | Action | Motion |
|---|---|---|
| **Describes** | What the subject is doing and for what purpose | How the body or object physically changes over time |
| **Requires** | Intention, reaction, or state change | Only physical change |
| **Example** | "She checks whether the door is locked." | "Her right arm extends, the hand turns the knob 30°, the door resists, and her hand releases." |
| **Use in design** | Defines purpose and success | Defines what must be visible and when |

## 1.2 Distinctions That Prevent Design Errors

| Pair | Definition and why the distinction matters |
|---|---|
| **Subject movement vs. camera movement** | Subject movement changes the subject's position or shape in the scene. Camera movement changes the viewpoint. In a frame, both can look like "things moving." They must be specified independently (Section 14). |
| **Action vs. motion** | See 1.1. Specify the action for purpose and the motion for visibility. |
| **Intended action vs. visible movement** | The intended action is "pick up the cup." The visible movement is a sequence of reach, hand opening, contact, grip, lift. A viewer infers the action from the visible movement. If the visible movement is wrong, the action is misread. |
| **Whole-body vs. localized movement** | Whole-body movement changes the body's overall position or posture (walking, sitting). Localized movement involves one region (a head turn, a finger tap). Localized movement is easy to lose in wide frames. |
| **Voluntary vs. involuntary movement** | Voluntary movement is chosen (reaching). Involuntary movement is automatic (a blink, a startle response, breathing). Involuntary reactions occur *after* a stimulus with a short delay; voluntary actions can precede stimuli. |
| **Continuous vs. discrete actions** | Continuous movement flows without clear boundaries (walking). Discrete actions have a start and an end (picking up a cup). Mixing the two changes how they are specified. |
| **Physical vs. perceived or implied movement** | Physical movement happens over time on screen. Implied movement is suggested by a still pose, an off-balance posture, motion blur, an editing cut, or a sound. |
| **Naturalistic vs. stylized movement** | Naturalistic movement follows ordinary physical and anatomical behavior. Stylized movement changes timing, amplitude, or physics deliberately (Section 11). |
| **An action's beginning, execution, contact, and outcome** | The action's four broad stages (1.4). Viewers read cause and effect through them. |

## 1.3 Movement Event vs. Ongoing Movement State

- A **movement event** is a bounded change with a start and an end: standing up, throwing a ball, closing a door.
- An **ongoing movement state** is a continuing condition: walking at a steady pace, breathing, leaves rustling, a fan rotating.

**Why it matters:** Events need *phases* and an *end state*. States need a *rate* and a *duration*. An event embedded in a state (a person drops a glass while walking) requires saying which is primary and how the state continues or stops.

**Design rule:** For every action, label each component as *event* or *state*. If a state is not meant to change (background wind), say so; otherwise it may start or stop by accident.

## 1.4 Action Phases

An action can be divided into phases. Phase names are a craft vocabulary; different fields use different labels.

| Phase | Definition | Example (reaching for and lifting a cup) |
|---|---|---|
| **Preparation (anticipation)** | The body positions itself for the action, often with a small countermovement or weight shift. | Her eyes locate the cup; she leans slightly forward; the hand opens. |
| **Initiation** | The first visible movement of the action itself, usually driven by a trigger. | The arm begins to extend. |
| **Acceleration** | The movement speeds up from rest. | The hand moves faster toward the cup. |
| **Execution** | The main portion of the action at its working speed. | The arm travels to the cup. |
| **Interaction or contact** | The moment the subject meets another object or person. | Fingers touch the cup and close on it. |
| **Follow-through** | Continued movement of parts after the main action. | The arm continues upward as the cup is lifted; the sleeve settles. |
| **Deceleration** | The movement slows toward its end. | The arm slows as the cup reaches her mouth level. |
| **Recovery** | The body returns toward a stable, balanced posture. | Shoulders relax; weight resettles. |
| **Resulting state** | The stable condition after the action. | She holds the cup at chest height, looking at it. |

**Not every action contains every phase.** A blink has little preparation and no contact. A slow push on a door may have contact from the start. A fall has no deliberate preparation. The phases that matter are those the viewer needs to *read* the action. The sequence depends on the action: an object throw has preparation (wind-up), acceleration, release (contact ends), follow-through, and recovery; a tap on the shoulder has preparation, contact, and a brief release.

**Four broad stages (simplified):**

| Stage | Phases included |
|---|---|
| **Beginning** | Preparation, initiation |
| **Execution** | Acceleration, main movement, deceleration |
| **Contact or interaction** | Meeting of the subject with an object or person |
| **Outcome** | Follow-through, recovery, resulting state |

## 1.5 Layers of Movement in a Frame

| Layer | Definition | Example | Design implication |
|---|---|---|---|
| **Primary action** | The action that carries the scene's purpose. | A woman opens a letter. | Gets the most clarity, time, and visibility. |
| **Secondary action** | A deliberate supporting action that adds information without upstaging the primary action. (Animation usage; some fields use other names.) | She glances at the door while opening the letter. | Supports meaning; must not compete. |
| **Secondary motion** | Passive movement that results from the primary movement. (Defined fully in Section 12.) | Her sleeve swings after her arm stops. | Adds realism; follows physics. |
| **Incidental motion** | Small, unplanned, often involuntary movement present in any living subject. | Blinking, small posture shifts, breathing. | Keeps still subjects alive; must not distract. |
| **Background action** | Activity of other people or things behind the primary subject. | A waiter carries plates across the room. | Sets context; must not steal attention. |
| **Environmental motion** | Motion of the setting: wind, water, smoke, light flicker, traffic. | Curtains move in a breeze. | Establishes conditions; must agree with other motion. |

## 1.6 Visible Movement vs. Inferred Intention

Viewers do not see intention. They *infer* it from visible evidence: direction of gaze, direction of travel, preparation before the action, contact, and consequence. Two different intentions can produce similar movement (a character reaching toward a drawer could be searching or hiding something). The gap is closed by context, gaze, timing, and consequence.

**Design consequence:** If the intention must be read, supply at least two corroborating pieces of evidence (for example, gaze directed at the target *and* a clear preparatory movement *and* a visible outcome).

## 1.7 Action Clarity and Cause and Effect

**Action clarity** is the degree to which a viewer can identify what is being done, by whom, to what, and with what result. It depends on **recognizable cause and effect**: a cause (trigger or intention), a force or movement, a contact or interaction, and a consequence (Section 7).

Clarity fails when a link is missing (the cup moves but no hand touches it), when order is wrong (a reaction before the event), or when too many things happen at once.

## 1.8 Common Misconceptions

| Misconception | Correction |
|---|---|
| "More motion makes the action more engaging." | Engagement comes from clear intention, stakes, contrast, and consequence. Constant motion removes contrast and reduces readability. |
| "Fast means energetic." | Energy is conveyed by force, intention, and contrast with stillness. A slow, heavy, deliberate push can read as more forceful than a rapid flurry. |
| "Natural means random." | Natural movement has structure: preparation, weight transfer, follow-through, and individual rhythm. |
| "An action verb is enough to specify it." | Verbs such as "grab" or "run" leave the path, speed, contact, and phases undefined (Section 15). |
| "One movement pattern fits everyone." | Bodies, ages, footwear, surfaces, loads, fatigue, and styles change movement. |
| "Stillness is the absence of action." | Stillness can be an action (waiting, listening) and gives movement contrast. |
| "If the pose at the end is right, the action is right." | The path and phases carry plausibility; a correct end pose can result from teleportation or morphing. |
| "Realism requires every secondary effect." | Too much secondary motion can distract. Choose what supports the action. |

---

# 2. ACTION-DESIGN DECISION FRAMEWORK

Action design is a **repeatable sequence of decisions**. Skipping steps produces vague, implausible, or unreadable movement.

## 2.1 The Twelve Steps

### Step 1 — Identify the narrative purpose of the action
**What:** State what the action does for the story: reveals character, advances plot, builds tension, shows relationship, provides rest.
**Why:** The purpose determines which phases, details, and outcomes must be visible.
**How:** Complete: *"After this action, the story is different because ______."*

### Step 2 — Determine what the subject intends to accomplish
**What:** State the subject's goal in concrete terms ("to find out whether anyone is behind the door").
**Why:** Intention shapes preparation, speed, path, and gaze.
**How:** Write the goal and any competing impulse (curiosity vs. fear).

### Step 3 — Define the starting state and physical constraints
**What:** Specify posture, orientation, position, what is held, what surrounds the subject, and physical limits (confined space, slippery floor, heavy load, fatigue).
**Why:** The same action differs by start state: standing up from a chair is different from standing up from the floor.
**How:** Use the Initial State line of the Action Specification Block (2.2).

### Step 4 — Specify the trigger or motivation
**What:** Identify what starts the action: a sound, a decision, an arriving person, a time cue.
**Why:** An action without a trigger looks arbitrary; a reaction before its trigger looks like an error.
**How:** Name the trigger and its timing relative to the action's start.

### Step 5 — Identify the main body parts or objects involved
**What:** List the parts that carry the action (eyes, right hand, torso, feet) and the objects that take part (door, cup).
**Why:** It limits what must be specified and rendered clearly.
**How:** Name each part and its role (lead, support, balance).

### Step 6 — Break the action into meaningful phases
**What:** Divide the action into the phases that the viewer must read (Section 1.4).
**Why:** Phases prevent teleportation between poses.
**How:** Write 3–6 phases, each with a start and end state.

### Step 7 — Define direction, path, speed, force, duration, and endpoint
**What:** For each phase specify the direction and path (Section 6), approximate speed and duration (Section 5), the force or effort level (Section 4), and the endpoint.
**Why:** These are the parameters that make an action reproducible.
**How:** Use ranges and comparative terms with anchors ("about two seconds," "slower than a normal walk").

### Step 8 — Identify contact points and interactions
**What:** Name where and when the subject touches other subjects or objects, and in what order (Section 8).
**Why:** Contact is where plausibility is judged.
**How:** List contact events in sequence: "fingertips touch the handle; palm closes; wrist rotates."

### Step 9 — Determine the expected physical consequences
**What:** State what changes as a result: the door opens, the cup rises, the floor creaks, the sleeve swings.
**Why:** Consequence confirms the action and anchors cause and effect.
**How:** Write the consequence for each contact and for the final state.

### Step 10 — Check physical plausibility and visual readability
**What:** Test for balance, weight, joint limits, and cause and effect (Sections 4, 7); test whether the action can be read at the intended frame size and screen time.
**Why:** Implausible or unreadable movement fails either way.
**How:** Run the plausibility and readability checks in 2.4.

### Step 11 — Define what must remain consistent
**What:** List identity, clothing, proportions, object size, position relationships, and style that must not change.
**Why:** Many generation failures are changes in things that should have stayed fixed.
**How:** Write the "must remain unchanged" list.

### Step 12 — Establish observable success criteria
**What:** Write statements that can be checked by viewing: "The hand touches the handle before the door moves."
**Why:** "Looks natural" cannot be verified.
**How:** Write 3–6 criteria tied to phases, contact, and final state.

## 2.2 The Action Specification Block (Compact Output)

```
ACTION SPECIFICATION
Purpose:            [what the action does for the story]
Subject / goal:     [who; what they intend]
Initial state:      [posture, orientation, position, held objects, constraints]
Trigger:            [what starts the action and when]
Participating:      [body parts / objects and their roles]
Phases:             [preparation → initiation → ... → resulting state]
Direction / path:   [relative to subject, scene, or screen — stated explicitly]
Speed / timing:     [approximate durations per phase; overall duration]
Force / weight:     [light, heavy, resisted, supported]
Contact sequence:   [what touches what, in order]
Consequence:        [what changes as a result]
Final state:        [posture, position, object states]
Must remain fixed:  [identity, clothing, proportions, object size, camera if still]
Camera:             [specified separately]
Success criteria:   [3–6 observable statements]
```

## 2.3 Practical Decision Tree

```
START
│
├─ Q1. Can I state the action's purpose and the subject's goal in one sentence each?
│    ├─ NO  → STOP. Define purpose and goal first.
│    └─ YES → continue
│
├─ Q2. Are the start state and end state both defined (posture, position, object states)?
│    ├─ NO  → Define them. Without both, the path between them is unconstrained.
│    └─ YES → continue
│
├─ Q3. Is the action UNCLEAR (the viewer could read it as something else)?
│    ├─ YES → Add or strengthen: (a) a trigger, (b) gaze toward the target,
│    │        (c) a visible preparation phase, (d) a visible consequence.
│    └─ NO  → continue
│
├─ Q4. Is the action OVERCOMPLICATED (many simultaneous or sequential parts)?
│    ├─ YES → Identify the story-critical beat. Remove or imply everything else.
│    │        If two or more critical beats remain, split by phase (Section 16).
│    └─ NO  → continue
│
├─ Q5. Is the action PHYSICALLY IMPLAUSIBLE?
│    ├─ Balance: is the center of mass over the base of support at each moment?
│    ├─ Weight: does the body prepare for, and react to, the load?
│    ├─ Joints: are all joints bending within normal limits for the body?
│    ├─ Contact: does the force come from a touch before the object moves?
│    │     → Fix the first failing item. If the implausibility is intended, mark it
│    │       as deliberate stylization (Section 11).
│    └─ NO  → continue
│
├─ Q6. Is the action VISUALLY UNREADABLE (too fast, too small, hidden, or crowded)?
│    ├─ YES → Slow the critical phase; enlarge the subject in frame; remove occluding
│    │        objects; reduce simultaneous activity; separate the contact moment.
│    └─ NO  → continue
│
├─ Q7. Will an AI VIDEO MODEL find it DIFFICULT (many limbs, hidden contact, long
│       duration, crowded scene, repeated movement)?
│    ├─ YES → Simplify (Section 16): one subject, one primary action, visible contact,
│    │        uncluttered space, short duration; or split into phases/shots.
│    └─ NO  → continue
│
└─ Q8. Write acceptance criteria. PROCEED, then verify with Section 20.
```

## 2.4 Plausibility and Readability Checks

| Check | Question | Typical failure |
|---|---|---|
| **Balance** | At each moment, would the subject stay upright or fall as shown? | The subject leans far beyond the base of support without compensating. |
| **Weight** | Do the body and object show appropriate effort and reaction to load? | A heavy box moves as if empty. |
| **Joint limits** | Do limbs bend only where and as far as joints allow? | Elbows or knees bend sideways. |
| **Contact** | Does force come from visible contact? | An object moves before the hand touches it. |
| **Sequence** | Do events occur in causal order? | The door opens before the hand turns the handle. |
| **Continuity** | Do identity, size, and position stay constant? | The hand changes size during a reach. |
| **Screen time** | Does each critical phase last long enough to be read? | The contact phase lasts a few frames. |
| **Visibility** | Is the critical contact visible from the camera's position? | The hand is hidden behind the body at contact. |

## 2.5 Worked Mini-Example

**Action:** A man cautiously checks whether a door is locked.

- **Purpose:** Show that he suspects someone is inside.
- **Goal:** Learn whether the door is locked without making noise.
- **Initial state:** Standing in a corridor, facing the door about 1 m away, right hand at his side.
- **Trigger:** A faint sound from inside the room.
- **Participating:** Eyes, head, right hand and forearm, weight on the rear foot, the door handle.
- **Phases:** Head tilts toward the sound → weight shifts back slightly → hand rises slowly → fingers close on the handle → wrist rotates slowly until resistance → he stops, holds, and listens → releases.
- **Consequence:** The handle turns only a small distance and stops; the door does not open.
- **Final state:** Hand lowered, still facing the door, weight forward again.
- **Must remain fixed:** His clothing, the door's position, the handle's shape.
- **Success criteria:** (1) The head turns before the hand moves. (2) The fingers touch the handle before it turns. (3) The handle stops at a small angle. (4) He holds still for a visible beat after the resistance.

---
# 3. ACTION AND MOTION TAXONOMY

## 3.1 How to Read the Taxonomy

Each entry describes a movement or a closely related group. Entries do not follow one rigid template: related actions are grouped where their mechanics overlap, and their differences are called out. Typical fields:

- **Definition, start, and outcome** — what the movement is, the starting condition, and the intended result.
- **Participating parts** — body parts or objects that carry it.
- **Phases** — the sequence that the viewer must be able to read.
- **Timing, direction, speed, and weight** — how it unfolds. Numbers are *approximate values* for a typical adult and vary widely.
- **Common errors, diagnosis, and correction** — what goes wrong visually and how to fix the smallest relevant variable.
- **Cinematic example.**
- **AI specification** — how to word it for image or video generation.

**Caution:** The phases and timings below describe *typical* patterns. Anatomy, proportions, footwear, surfaces, load, fatigue, age, ability, and style change them (Section 4.8).

---

## 3.2 WHOLE-BODY MOVEMENT

### 3.2.1 Standing Up and Sitting Down

- **Definition, start, outcome:** A posture transition between sitting and standing. *Standing up:* start seated with the torso upright; outcome stable standing. *Sitting down:* the reverse, ending supported by the seat.
- **Participating parts:** Feet, knees, hips, torso, head, arms (balance or push-off), the seat.
- **Phases (standing up):** Feet draw back under the knees → torso leans forward so the center of mass moves over the feet → hands may push off a support → hips lift → legs extend → torso straightens → balance settles. *Sitting down:* the reverse, with the hips moving backward and down in a controlled lowering; contact with the seat; weight transfers to the seat; torso settles.
- **Timing, direction, weight:** Natural sit-to-stand takes roughly 1.5–2.5 seconds; cautious or tired movement is slower; urgent movement can be about one second. The forward lean *before* the hips rise is essential: the body cannot rise straight up from a seated position without it. Weight shifts from seat to feet.
- **Common errors:** Rising straight up with a vertical torso; feet far in front of the knees; arms hanging passively; hips arriving at the seat before the legs control the descent; the chair moving without cause.
- **Diagnosis and correction:** Compare torso angle and foot position at the start of the rise. *Fix:* specify "feet under the knees, torso leans forward, then rises."
- **Example:** A tired woman at a kitchen table leans forward, presses one palm on the table, and rises slowly, steadying herself with the other hand on the chair back.
- **AI specification:** "From a seated position, she moves her feet under her knees, leans her torso forward, pushes up with her right hand on the table, straightens her legs over about two seconds, and stands fully upright with her weight centered over both feet; the chair stays in place."

### 3.2.2 Walking

- **Definition, start, outcome:** A continuous gait in which at least one foot is always in contact with the ground. Start from rest or an ongoing state; outcome is a displaced position or a continuing state.
- **Participating parts:** Legs, feet, hips, torso, arms (counter-swing), head.
- **Phases (one stride):** Heel contact → weight accepted on the leading leg → body passes over the planted foot → push-off → swing of the trailing leg forward. There are brief periods when both feet are on the ground (double support).
- **Timing, direction, weight:** Typical adult walking speed is about 1.2–1.4 m/s with a cadence of about 100–120 steps per minute and step length of about 0.6–0.8 m. Arms commonly swing opposite to the legs (right arm forward with left leg). The torso rotates slightly with the stride and the head rises and falls slightly. Fatigue, caution, load, or style change rhythm and stride.
- **Common errors:** Feet gliding without lifting; only one foot touching the ground in a "floating" way; arm swing in the same phase as the leg on the same side; stride length changing between steps; body sliding forward faster than the feet.
- **Diagnosis and correction:** Check whether each foot plants and stays fixed while the body passes over it. *Fix:* specify "feet plant and push off with each step; arms swing opposite to the legs; steady pace."
- **Example:** A courier walks along a corridor at a steady pace, shoulders level, one hand holding a parcel against his hip.
- **AI specification:** "She walks at a steady natural pace of about two steps per second, each foot planting flat on the floor and lifting in turn, arms swinging gently opposite to her legs, toward the end of the corridor."

### 3.2.3 Running and Sprinting

- **Definition, start, outcome:** A gait with a flight phase in which neither foot touches the ground. Sprinting is maximal-effort running with greater lean and stride power.
- **Participating parts:** Legs, feet, hips, torso, arms (bent and driving), head.
- **Phases:** Push-off → flight → landing on the forefoot or midfoot (varies) → weight accepted → push-off again. Arms bent at about the elbow swing forward and back opposite to the legs.
- **Timing, direction, weight:** Jogging is about 2.5–3.5 m/s; sprinting can reach 6–10 m/s depending on the person. The torso leans forward, especially during acceleration; stride length and cadence increase with speed. Ground contact times shorten as speed increases.
- **Common errors:** No flight phase (looks like a fast walk); feet sliding; upright torso at a sprint; arms swinging in a walking pattern; the body speed not matching ground movement (skating).
- **Diagnosis and correction:** Check for a visible airborne moment and a forward lean. *Fix:* specify "forward lean, bent driving arms, a visible moment when both feet leave the ground."
- **Example:** A runner sprints down an alley, body leaning forward, arms bent and driving, shoes striking the ground in sharp alternation.
- **AI specification:** "He sprints down the alley with a forward lean, elbows bent at about 90°, arms pumping opposite to his legs, with a brief moment in each stride when both feet leave the ground."

### 3.2.4 Starting from Rest, Slowing Down, and Stopping

- **Definition, start, outcome:** Transitions between standing and locomotion. *Starting:* from rest to movement. *Slowing:* decrease in speed. *Stopping:* from movement to rest.
- **Participating parts:** Whole body; the feet and the forward lean.
- **Phases (starting):** Weight shift to the stance foot → forward lean → first step with a shorter stride → gradual lengthening of strides. *Stopping:* shortened steps → braking by planting the lead foot ahead of the center of mass → leaning back or lowering the center of mass → weight settles over both feet.
- **Timing, direction, weight:** Momentum (mass × velocity) means stopping requires deceleration over a distance. Stopping from a walk takes roughly one or two steps; from a run, several steps. The body leans forward to start and slightly back to stop.
- **Common errors:** Instant velocity changes; the body stopping while the legs continue; no lean; feet sliding.
- **Diagnosis and correction:** Check the lean and the step shortening. *Fix:* specify "two shortened braking steps, torso leans back, weight settles."
- **Example:** A girl runs toward a road, hears a car horn, and stops abruptly: two quick braking steps, arms out for balance, weight on her heels.
- **AI specification:** "She runs, then slows over three shortened steps, plants her lead foot, leans back slightly, and comes to a full stop with her weight evenly over both feet."

### 3.2.5 Turning, Pivoting, and Changing Direction

- **Definition, start, outcome:** A change in the body's facing direction (turning, pivoting) or in the direction of travel.
- **Participating parts:** Eyes and head (lead), shoulders, torso, hips, feet.
- **Phases:** Eyes and head lead toward the new direction → shoulders and torso follow → hips rotate → the feet step or pivot on the ball of the foot → the new heading is established. Sharp direction changes at speed involve braking, planting a foot, leaning into the turn, and pushing off.
- **Timing, direction, weight:** The head typically begins the turn first, followed by the shoulders and then the hips; the lead is often a few tenths of a second. At speed, the body leans into a curve; the greater the speed, the wider the radius unless the body brakes.
- **Common errors:** The whole body rotating as one rigid piece; feet not moving during a turn; direction change with no lean or braking at speed.
- **Diagnosis and correction:** Check whether the head leads and the feet participate. *Fix:* specify "head turns first, then shoulders, then hips; feet step through the turn."
- **Example:** A woman hears her name, turns her head, then her shoulders, then pivots on one foot to face the caller.
- **AI specification:** "She turns her head to the left first, then rotates her shoulders and hips, pivoting on her left foot, until she faces the doorway; her right foot steps to rebalance."

### 3.2.6 Leaning and Shifting Weight

- **Definition, start, outcome:** A change in the body's weight distribution without a change of location, or a lean toward or away from something.
- **Participating parts:** Torso, hips, legs and feet.
- **Phases:** Preparation (subtle shift) → lean → hold → return.
- **Timing, direction, weight:** Leaning moves the center of mass toward the edge of the base of support; the body counterbalances by moving other parts (hips back when the head goes forward). Shifting weight from one leg to the other is a common incidental motion in standing subjects.
- **Common errors:** Leaning without counterbalance; leaning beyond the base of support without a fall or step; weight shifts that do not move the hips.
- **Diagnosis and correction:** Compare the hip position with the head. *Fix:* specify "hips shift as the weight moves to the left foot."
- **Example:** A man leans on a counter and shifts his weight to his right foot as he waits.
- **AI specification:** "He shifts his weight onto his left foot, his hips moving slightly left, his right knee relaxing; his torso stays upright."

### 3.2.7 Crouching, Squatting, and Kneeling

- **Definition, start, outcome:** *Crouching/squatting:* lowering the body by bending the hips and knees while feet stay on the ground. *Kneeling:* one or both knees contact the ground.
- **Participating parts:** Hips, knees, ankles, torso, hands (balance).
- **Phases:** Hips move back and down → knees and ankles flex → torso inclines forward for balance → hands may touch the ground or a support → settle. *Kneeling:* a knee lowers to contact the ground, weight transfers, and the other leg may stay flexed.
- **Timing, direction, weight:** The center of mass must stay over the feet (or the knees and feet when kneeling). The torso tilts forward to balance the hips going back. Rising reverses the sequence.
- **Common errors:** Hips dropping straight down with a vertical torso; heels lifting without cause; knees bending in the wrong direction; the body shrinking instead of folding.
- **Diagnosis and correction:** Check the hip travel and the torso lean. *Fix:* specify "hips move back and down, torso leans forward, heels stay on the ground."
- **Example:** A child crouches to look at an insect, knees bent, one hand on the ground.
- **AI specification:** "She lowers into a crouch by bending her knees and hips, her hips moving back, torso leaning forward, heels flat on the ground, and rests her right hand on the ground."

### 3.2.8 Bending, Reaching, and Stretching

- **Definition, start, outcome:** *Bending:* flexing the torso or knees to lower the upper body. *Reaching:* extending an arm (and often the body) toward a target. *Stretching:* extending the limbs or torso beyond the neutral position, usually for range.
- **Participating parts:** Spine, hips, shoulders, arm, hand; legs for balance.
- **Phases (reaching):** Eyes locate the target → the shoulder and arm begin → the torso leans or rotates as needed → the hand shapes for the target → extension reaches its limit → contact or hold → return.
- **Timing, direction, weight:** The farther the reach, the more the torso and legs participate. A heel may lift and the opposite leg may extend backward to counterbalance. The reaching arm leads; the hand opens before contact.
- **Common errors:** Arm extending beyond its length; the shoulder not moving; no counterbalance; the hand not shaped for the target.
- **Diagnosis and correction:** Compare arm length with the target distance. *Fix:* shorten the reach or add a torso lean and a step.
- **Example:** A man reaches for a top shelf, rising on his toes with his left hand on the shelf edge.
- **AI specification:** "He reaches up with his right arm to the top shelf, rising on his toes, his torso leaning slightly forward, his left hand steadying on the shelf edge."

### 3.2.9 Crawling

- **Definition, start, outcome:** Locomotion on hands and knees or with the torso near the ground.
- **Participating parts:** Hands, knees (or forearms and toes), torso, head.
- **Phases:** Typically a diagonal pattern: one hand and the opposite knee advance, then the other pair. Low crawls drag the body forward with forearms and legs.
- **Timing, direction, weight:** The weight is supported by three limbs while one moves, or by diagonal pairs. Speed is slower than walking; the head and gaze point forward.
- **Common errors:** Limbs moving in the same side pattern without balance; hands or knees sliding; the torso not shifting weight.
- **Diagnosis and correction:** Check the limb pattern. *Fix:* specify "right hand and left knee advance together, then left hand and right knee."
- **Example:** A person crawls beneath a low pipe with their head down.
- **AI specification:** "She crawls forward on her hands and knees in a diagonal pattern, her right hand and left knee advancing together, then her left hand and right knee, her palms and knees planting on the floor."

### 3.2.10 Climbing and Descending

- **Definition, start, outcome:** Moving up or down using the hands and feet on stairs, ladders, rocks, or walls.
- **Participating parts:** Hands, feet, legs, arms, torso.
- **Phases:** Reach and grip or place the foot → load the support → push or pull → release and move to the next hold. Stairs involve lifting the foot to the next step and shifting weight onto it.
- **Timing, direction, weight:** Three points of contact are a common stable pattern on ladders and rock (two feet and one hand, or the reverse). When descending, movements are controlled to resist gravity; the body faces the structure on a ladder.
- **Common errors:** Foot never fully planted; hands not gripping; body moving upward without a load shift; descending as if weightless.
- **Diagnosis and correction:** Check each hold. *Fix:* specify the order of limb movements.
- **Example:** A man climbs a ladder, one hand then the other reaching up, feet stepping onto each rung.
- **AI specification:** "He climbs the ladder facing it, moving one hand up, then the opposite foot to the next rung, alternating, each hand wrapping around a rung and each foot planting on a rung."

### 3.2.11 Jumping and Landing

- **Definition, start, outcome:** Leaving the ground by a push-off and returning to it. Outcome is a controlled landing.
- **Participating parts:** Legs, hips, torso, arms, feet.
- **Phases:** Preparation (crouch and arm swing back) → push-off (rapid extension of hips, knees, ankles; arms swing up) → flight → preparing to land (legs extend toward the ground) → landing (knees and hips flex to absorb impact; arms balance) → recovery.
- **Timing, direction, weight:** Flight time is set by gravity and take-off speed; for a vertical jump of about 0.3 m, flight lasts roughly half a second. The body follows a curved (parabolic) path; once airborne it cannot change its trajectory by much. Landing involves flexing joints to absorb impact.
- **Common errors:** No crouch before the jump; the body rising at a constant speed rather than slowing at the top; stiff-legged landing; feet landing with no flexion; hovering at the peak.
- **Diagnosis and correction:** Check preparation and landing flexion. *Fix:* specify "crouch, arms swing up, push off, land with knees bending."
- **Example:** A girl jumps over a puddle, bending her knees on landing and swinging her arms for balance.
- **AI specification:** "She crouches, swings her arms back, pushes off with both feet and swings her arms forward, travels through the air over the puddle, and lands on both feet with her knees bending to absorb the landing."

### 3.2.12 Falling, Stumbling, and Recovering

- **Definition, start, outcome:** *Stumbling:* a loss of balance caused by an obstacle or a misstep, with a recovery step. *Falling:* continued loss of balance until the body reaches the ground or a support. *Recovering:* regaining stability.
- **Participating parts:** Whole body; arms and feet are prominent.
- **Phases (stumble and recover):** Trigger (foot catches or slips) → the center of mass moves beyond the base of support → arms flail or extend for balance → a quick step to catch the body → weight resettles → posture rebuilds. *Falling:* the body continues to accelerate toward the ground under gravity; the arms extend to meet the ground or a support; contact is absorbed; the body settles.
- **Timing, direction, weight:** Gravity accelerates the body at roughly 9.8 m/s²; an object falling about 1 m takes about 0.45 seconds. Reflexive arm and step responses start within a fraction of a second of the loss of balance. Falling to the side or the front looks different from falling backward.
- **Common errors:** Falling like a rigid plank; no protective arm or step response; falling in slow motion without a reason; a stumble with no trigger; instant recovery.
- **Diagnosis and correction:** Check the trigger and the reflex. *Fix:* specify "foot catches on the step, torso pitches forward, arms extend, a quick step catches the weight."
- **Example:** A woman's foot catches on a loose tile; she lurches forward, takes two quick steps, and grabs a railing.
- **AI specification:** "Her right foot catches on the edge of the tile; her torso pitches forward; her arms extend; she takes two quick steps and grips the railing with her left hand, regaining her balance; she stands upright and looks back at the tile."

### 3.2.13 Rolling and Tumbling

- **Definition, start, outcome:** A rotation of the body over the ground, usually for movement or to absorb momentum.
- **Participating parts:** Whole body, rounded back, arms, legs.
- **Phases:** Preparation (low posture) → tuck → contact on the rounded back/shoulder → rotation → return to feet or the next posture.
- **Timing, direction, weight:** The body rotates around a center; momentum continues the roll until friction and posture change stop it.
- **Common errors:** The body unrolling like a flat sheet; limbs changing length; the head or limb contacting the ground in an anatomically unlikely way.
- **Diagnosis and correction:** Check the body's shape through the rotation. *Fix:* specify "a tucked, rounded shape through the roll; hands on the ground first."
- **Example:** A stuntperson rolls across the floor and rises into a crouch (non-graphic).
- **AI specification:** "She places her hands on the ground, tucks her chin, rolls forward over her rounded shoulder and back, and rises into a crouch."

### 3.2.14 Balancing and Losing Balance

- **Definition, start, outcome:** *Balancing:* holding stability on a small or unstable base of support. *Losing balance:* the center of mass moves outside the base.
- **Participating parts:** Arms, torso, hips, feet.
- **Phases (balancing):** Small corrections (arms, torso, hips) → hold → adjustments in response to disturbances. *Losing balance:* a drift of the center of mass → larger compensations → recovery or a step.
- **Timing, direction, weight:** Small, continuous adjustments; arms extend for stability; knees may bend slightly to lower the center of mass.
- **Common errors:** A perfectly still balance on a narrow base; no compensation; recovery with no movement.
- **Diagnosis and correction:** Check for small corrections. *Fix:* specify "small arm adjustments, slight knee flex."
- **Example:** A girl walks along a narrow wall with arms out.
- **AI specification:** "She walks along the narrow wall with her arms out to the sides, making small adjustments with her hands, placing one foot directly in front of the other, her knees slightly bent."

### 3.2.15 Pushing and Pulling (Whole Body)

- **Definition, start, outcome:** Applying force to move or resist an object or person. *Pushing:* force away from the body. *Pulling:* force toward the body.
- **Participating parts:** Hands, arms, shoulders, torso, hips, legs and feet.
- **Phases:** Positioning → establishing contact → leaning or bracing → force build-up → movement of the object (or resistance) → release.
- **Timing, direction, weight:** To push a heavy object, the body leans into it, the feet push against the ground, and the legs and hips drive. To pull, the body leans back, with the feet braced. The object does not move until the applied force exceeds the resistance (friction or weight); the body leans more as the load increases.
- **Common errors:** An upright body with an object moving easily; no foot bracing; the object moving before the force builds.
- **Diagnosis and correction:** Check the lean and the foot grip. *Fix:* specify "leans forward, feet braced, the object begins to move slowly."
- **Example:** A man pushes a heavy crate along the floor.
- **AI specification:** "He braces both hands on the crate, leans his body forward at about 30°, drives with his legs, and the crate slides slowly forward as his feet push against the floor."

### 3.2.16 Lifting, Carrying, Lowering, and Placing Objects

- **Definition, start, outcome:** Raising, transporting, and setting down an object.
- **Participating parts:** Hands, arms, torso, hips, legs; the object.
- **Phases:** Approach and position → grip → load (the body prepares for the weight) → lift → carry (posture adjusts to the load) → lower → release → recovery.
- **Timing, direction, weight:** Heavier objects produce slower movements, wider stances, and body lean to keep the combined center of mass over the feet. A load carried in front causes the torso to lean back; a load on one side causes a lean to the opposite side.
- **Common errors:** A heavy object lifted with no body adjustment; the object's size changing; the object floating without a grip; no change in gait when carrying.
- **Diagnosis and correction:** Check whether posture and gait respond to the load. *Fix:* specify "wider stance, back leaning, slower steps."
- **Example:** A woman lifts a box of books from the floor, carries it to the shelf, and places it down.
- **AI specification:** "She squats, grips both bottom corners of the box, straightens her legs to lift, holds it against her torso with her torso leaning back slightly, walks with short steps to the shelf, and lowers it to the shelf with both hands."

---
## 3.3 LOCALIZED BODY MOVEMENT

Localized movements involve one region of the body. They carry much of a performance's meaning, and they are the first to be lost in wide frames or crowded prompts.

### 3.3.1 Head Turns, Head Tilts, and Gaze Shifts

- **Definition, start, outcome:** *Head turn:* rotation about the vertical axis. *Head tilt:* sideways or forward/back inclination. *Gaze shift:* a change in where the eyes look.
- **Participating parts:** Eyes, neck, head, sometimes shoulders.
- **Phases:** The eyes move first (a fast jump to the new target) → the head follows → the shoulders may follow for large turns → the eyes settle on the target.
- **Timing, direction, weight:** Eye movements between targets are very fast (a small fraction of a second); a head turn is slower (about 0.3–0.8 seconds for a natural turn). Gaze direction often tells the viewer what matters next.
- **Common errors:** The eyes and head moving together with no lead; the head turning while the eyes remain on the camera; gaze not aligned with the target; the head rotating beyond a plausible range.
- **Diagnosis and correction:** Check the gaze target at the end of the turn. *Fix:* specify the target and order: "eyes shift to the window, then the head turns."
- **Example:** A woman glances at the clock, then turns her head toward the sound.
- **AI specification:** "Her eyes shift to the window first, then her head turns about 45° to the right over half a second, and her gaze holds on the window."

### 3.3.2 Facial Expressions and Expression Transitions

- **Definition, start, outcome:** Changes in the face (brows, eyelids, cheeks, mouth) that show a state or reaction.
- **Participating parts:** Brows, eyelids, eyes, cheeks, nose, mouth, jaw.
- **Phases:** Neutral → onset (small movement in one region) → peak → hold → release or transition to another expression. Real transitions often begin around the eyes and brows and may be asymmetrical.
- **Timing, direction, weight:** Spontaneous expressions often last a fraction of a second to a few seconds; micro-changes are small; amplitude depends on the character and context.
- **Common errors:** Instant changes from one expression to another; symmetrical, held "masks"; exaggerated expression for subtle moments; mouth and eyes in conflict without intent.
- **Diagnosis and correction:** Check the onset and the region. *Fix:* specify small changes: "brows draw slightly together; lips press."
- **Example:** A man listens to news; his brow tightens, then he looks down and presses his lips together.
- **AI specification:** "Her face starts neutral; her brows draw slightly together over about half a second; her gaze lowers; her lips press together; she holds the expression for a beat."

### 3.3.3 Shoulder, Arm, Hand, Wrist, and Elbow Movement

- **Definition, start, outcome:** Gestures and manipulations performed with the upper limb.
- **Participating parts:** Shoulder (ball-and-socket, large range), elbow (hinge, bends in one plane), wrist (rotation and flexion), hand and fingers.
- **Phases:** Shoulder initiates a large movement → elbow flexes or extends → wrist adjusts orientation → hand shapes for the task → return.
- **Timing, direction, weight:** Joints have limits: the elbow bends mainly one way; the forearm can rotate (palm up or down); the wrist bends in several directions. Gestures start slightly before the words they accompany.
- **Common errors:** Elbow bending backward; arms of different length; the wrist rotating beyond its range; hands appearing with the wrong number of fingers; gestures with no shoulder involvement.
- **Diagnosis and correction:** Check each joint's direction. *Fix:* specify the joint movement: "the elbow flexes, the forearm rotates palm up."
- **Example:** A teacher raises her hand, palm up, and lowers it slowly while speaking.
- **AI specification:** "She lifts her right forearm, bending the elbow about 90°, rotates her palm upward, and lowers the forearm slowly; her left arm stays at her side."

### 3.3.4 Finger Movements

- **Definition, start, outcome:** Small movements of individual fingers: tapping, pinching, typing, fidgeting, pointing.
- **Participating parts:** Fingers (each has multiple joints that flex in the same direction), thumb (opposes the fingers).
- **Phases:** Preparation (fingers shape) → movement → contact or pause → release.
- **Timing, direction, weight:** Fingers flex mostly toward the palm; the thumb moves across the palm to pinch. Repetitive tapping has regular rhythm with small variations.
- **Common errors:** Extra or fused fingers; fingers bending backward; fingers passing through objects; a pinch without contact.
- **Diagnosis and correction:** Count fingers; check contact. *Fix:* specify "five fingers, thumb and index finger pinching the pen."
- **Example:** A man drums his fingers on a table while waiting.
- **AI specification:** "His four fingers tap the table in sequence from index to little finger, then repeat, at about two taps per second; the thumb stays still."

### 3.3.5 Torso Rotation, Torso Bending, Hip Movement, and Weight Transfer

- **Definition, start, outcome:** Movement of the trunk and pelvis, including shifting weight between legs.
- **Participating parts:** Spine, ribcage, pelvis, hips, legs.
- **Phases:** Hips lead or follow depending on the action; torso rotation often follows the hips and precedes the arms (for example, in swinging or throwing); weight moves from one leg to the other.
- **Timing, direction, weight:** Rotation is shared across the spine, so the shoulders turn more than the hips. Weight transfer precedes the step.
- **Common errors:** Rigid torso; the hips not shifting during a step; the shoulders and hips rotating by the same angle in a way that looks stiff.
- **Diagnosis and correction:** Check for differential rotation. *Fix:* specify "hips turn first, then the shoulders."
- **Example:** A woman turns to pick up a bag from the chair behind her.
- **AI specification:** "She rotates her hips and torso to the right, her shoulders following, her weight shifting onto her right foot, and reaches back with her right arm."

### 3.3.6 Leg and Foot Movement

- **Definition, start, outcome:** Movement of the leg joints (hip, knee, ankle) and the foot.
- **Participating parts:** Hip, knee (hinge), ankle, foot.
- **Phases:** Lift (hip flexes, knee bends) → swing → placement (heel or ball first, depending on the action) → weight acceptance.
- **Timing, direction, weight:** The knee bends in one direction; the foot's contact with the ground defines the step; the toes lead on tiptoe movements.
- **Common errors:** Knees bending sideways; feet sliding; feet rotating while planted; leg length changing.
- **Diagnosis and correction:** Check whether the planted foot stays still. *Fix:* specify "foot plants and does not slide."
- **Example:** A man steps over a puddle.
- **AI specification:** "He lifts his right knee, swings the leg forward over the puddle, places his foot flat on the far side, and transfers his weight onto it."

### 3.3.7 Breathing-Related Motion, Small Involuntary Movements, and Stillness

- **Definition, start, outcome:** *Breathing motion:* the chest, shoulders, and abdomen move with breath (adults at rest typically breathe about 12–20 times per minute). *Involuntary movement:* blinks (typically a few per minute to about 20, varying with the person and task), small postural shifts, fidgets. *Stillness:* the intentional absence of visible movement.
- **Participating parts:** Chest, abdomen, shoulders, eyelids, head, hands.
- **Phases:** Breathing alternates between inhalation and exhalation; blinks are quick closures and openings; shifts are small and irregular.
- **Timing, direction, weight:** Breathing is more visible after exertion, in fear, or in cold air. A living subject held perfectly rigid looks artificial; a subject who is deliberately still still breathes and blinks.
- **Common errors:** A "frozen" person with no breathing; blinking at a constant rate; breathing that does not match the exertion.
- **Diagnosis and correction:** Check for chest movement and blinks. *Fix:* specify "slow, shallow breathing, occasional blinks."
- **Example:** A hiding character stays still; only her breath moves her shoulders.
- **AI specification:** "She stays still with her eyes fixed on the door; her chest rises and falls slowly with shallow breaths; she blinks once; no other movement."

---

## 3.4 INTERACTION AND PHYSICAL ACTION

### 3.4.1 Reaching Toward, Grasping, Holding, Releasing, and Catching

- **Definition, start, outcome:** Hand-object interaction: extending toward an object, taking hold, maintaining a grip, letting go, or stopping a moving object.
- **Participating parts:** Eyes, shoulder, arm, hand and fingers, the object.
- **Phases:** Gaze locks on the object → the arm travels → the hand pre-shapes (opens to the object's size) → contact → grip closes → hold → release (fingers open, the object settles). *Catching:* the hand anticipates the object's path, makes contact, and moves with it to absorb its momentum.
- **Timing, direction, weight:** The grip tightens in proportion to the object's weight and fragility. In a catch, the hand moves in the direction of the object's travel and decelerates it gradually.
- **Common errors:** The hand closing before reaching the object; the hand passing through it; the object moving without contact; a catch with no absorption.
- **Diagnosis and correction:** Check the contact frame. *Fix:* specify "fingers touch the handle first; the grip closes; the cup rises."
- **Example:** A man catches a keyring tossed across a room, his hand closing and drawing back slightly.
- **AI specification:** "Her right hand opens as it approaches the cup, her fingers wrap around it, her grip closes, then the cup lifts; the cup stays upright."

### 3.4.2 Opening and Closing Doors and Containers

- **Definition, start, outcome:** Operating a hinged, sliding, or removable closure.
- **Participating parts:** Hand, forearm, body; the door or container.
- **Phases:** Approach → hand aligns with the handle or edge → grip → release of a latch (if any) → the door begins to move → continues along its constrained path → release or stop.
- **Timing, direction, weight:** A hinged door moves along an arc around its hinge; a sliding door along a line; a lid lifts or twists. Resistance (stiffness, weight) shows in the body's effort. The latch must release before the door moves.
- **Common errors:** The door opening toward the wrong side; the door moving before the latch; the handle passing through the hand; the door's size changing.
- **Diagnosis and correction:** Check hinge side and direction. *Fix:* specify "hinges on the left; the door swings inward away from her."
- **Example:** A woman turns a doorknob, pauses, and pushes the door open.
- **AI specification:** "She grips the knob with her right hand, turns it clockwise until the latch clicks, then pushes the door inward; the door swings on hinges at its left edge through about 90°."

### 3.4.3 Picking Up, Putting Down, and Handing Over Objects

- **Definition, start, outcome:** Lifting an object from a surface, placing it down, or passing it to another person.
- **Participating parts:** Eyes, hands, arms, torso; the object and its surface; the other person for handovers.
- **Phases (pick up):** Gaze → reach → contact → grip → lift → hold. *(Put down):* approach the surface → lower → contact the surface → release → withdraw. *(Hand over):* the giver extends the object → the receiver reaches → both grip briefly → the giver releases → the receiver takes the weight.
- **Timing, direction, weight:** The object stays on the surface until the grip is secure. In a handover, the weight transfers gradually from one grip to the other.
- **Common errors:** The object lifting before the grip; the object changing hands without both hands touching it; the receiver's hand arriving early or late; the object disappearing during a pass.
- **Diagnosis and correction:** Check the shared-grip moment. *Fix:* specify "both hands hold the folder for one beat before the giver releases."
- **Example:** A courier hands a package to a customer.
- **AI specification:** "He extends the package with both hands; she reaches out with both hands and grips its sides; for one beat both pairs of hands hold it; he releases and lowers his hands; she draws it toward her chest."

### 3.4.4 Pulling, Pushing, Dragging, and Resisting (Interaction)

- **Definition, start, outcome:** Using force on an object or person, or opposing a force applied to the subject.
- **Participating parts:** Hands, arms, torso, legs, feet; the object or other subject.
- **Phases:** Contact → force builds → the object moves or resists → continued force or release.
- **Timing, direction, weight:** The visible effort increases until the object overcomes resistance. When resisting, the body braces, leans against the force, and the feet hold or slide.
- **Common errors:** The body not responding to the opposing force; the object moving without effort; the grip changing during the pull.
- **Diagnosis and correction:** Check the body's lean. *Fix:* specify "leans back, heels dig in."
- **Example:** A child pulls a stubborn wagon up a slope.
- **AI specification:** "She grips the handle with both hands, leans forward, steps up the slope; the wagon follows behind with its wheels turning."

### 3.4.5 Dodging, Evading, Blocking, Redirecting, and Non-Graphic Confrontation Choreography

- **Definition, start, outcome:** Avoiding or deflecting an approaching movement, and staging a physical confrontation as readable choreography. (This file treats confrontation as movement design only; contact is shown through position, timing, and response.)
- **Participating parts:** Eyes, head, torso, arms, legs.
- **Phases:** Perception → reaction → movement (step, lean, duck, raise forearm) → the approaching object or person passes or is redirected → recovery to a balanced stance.
- **Timing, direction, weight:** A dodge begins after the threat is perceived (reaction delay about 0.15–0.3 seconds for simple stimuli, approximate); the body moves out of the path rather than only the head; a block uses the forearm or an object to redirect the movement's line. In choreography, each exchange has a clear order: attack movement → response → counter-response.
- **Common errors:** Reacting before the approach; both parties moving at once without cause; contact with no response; the evading subject remaining in the line of movement.
- **Diagnosis and correction:** Check the order and the lines of movement. *Fix:* specify who moves first, the direction of each movement, and the response.
- **Example:** A man steps aside as a cart rolls toward him; it passes at the edge of the frame.
- **AI specification:** "A cart rolls from the left; he sees it, steps right and leans his torso away; the cart passes where he was standing; he steadies himself with one hand on the wall."

### 3.4.6 Reacting to an External Impact; Colliding With or Contacting an Object

- **Definition, start, outcome:** The body's response to a force or contact from something else, such as a bump, a thrown object, or a wall.
- **Participating parts:** Whole body; the contacted area.
- **Phases:** Contact → the contacted region moves → the rest of the body follows with a short delay → balance adjustments → recovery.
- **Timing, direction, weight:** Movement direction follows the force direction; heavier subjects move less; a light object (a balloon) moves more.
- **Common errors:** No visible response; the response in the wrong direction; a response before contact.
- **Diagnosis and correction:** Check the order. *Fix:* specify "contact first, then the shoulder rotates back."
- **Example:** A woman bumps a shelf; the jar tilts, and she steadies it.
- **AI specification:** "Her elbow bumps the shelf; the shelf shakes slightly; a jar tilts; she turns and catches it with her left hand."

### 3.4.7 Supporting Another Person's Weight; Helping Someone Stand or Move

- **Definition, start, outcome:** One subject provides physical support to another.
- **Participating parts:** Both subjects' arms, torsos, legs; contact points (shoulders, forearms, hands).
- **Phases:** Approach → positioning → contact → weight transfer → movement together → release.
- **Timing, direction, weight:** The supporter lowers and widens their stance; the supported person leans on the supporter; movement is slower and shorter-stepped; gaze and speech coordinate.
- **Common errors:** No weight on the supporter; arms passing through bodies; the supported person moving without leaning.
- **Diagnosis and correction:** Check the contact points. *Fix:* specify "her arm around his shoulder, his weight on her left side."
- **Example:** A woman helps an elderly man rise from a bench.
- **AI specification:** "She places her right hand under his elbow and her left hand on his forearm; he leans forward; she steadies him as he stands; they pause."

### 3.4.8 Coordinated Movement Between Two or More Subjects

- **Definition, start, outcome:** Subjects whose movements relate to each other in time and space: walking together, dancing, lifting together, moving a table.
- **Participating parts:** Each subject's relevant limbs; shared objects.
- **Phases:** Agreement on the start (gaze, a signal) → synchronized or alternating movement → adjustments → shared stop.
- **Timing, direction, weight:** Subjects may move in unison, in alternation, or in response; each retains individual rhythm; coordination relies on gaze and cues.
- **Common errors:** Mirror-image synchronization where independence is expected; subjects swapping roles; one subject's limbs merging with another's.
- **Diagnosis and correction:** Check each subject's action independently. *Fix:* specify actions for each subject and the cue that links them.
- **Example:** Two movers carry a sofa through a doorway, turning it.
- **AI specification:** "The taller man at the front and the shorter woman at the back lift the sofa together; he walks backward; she calls a count; they turn it sideways to pass through the doorway."

---

## 3.5 ANIMAL AND ENVIRONMENTAL MOTION

**Caution:** Human framing and movement conventions do not transfer directly to animals, vehicles, or objects. Define each subject's own mechanics.

### 3.5.1 Animal Walking, Running, Jumping, Turning, and Resting

- **Definition, start, outcome:** Locomotion and posture changes in animals. Four-legged animals use gaits (walk, trot, canter, gallop for horses; other animals differ); birds walk on two legs and hop; fish swim with body waves.
- **Participating parts:** Legs, spine, head, tail, ears (varies by species).
- **Phases:** Each gait has a repeating limb sequence. A walk typically has four-beat footfalls; a trot is a two-beat diagonal pattern; a gallop includes a moment when all feet are off the ground (patterns vary across species). Resting involves lowering the body, folding the legs, and settling.
- **Timing, direction, weight:** Animals' centers of mass lie close to the ground relative to humans; the head and tail move to balance; turning involves a curved path and the head leading.
- **Common errors:** Human-like movement on four legs; limbs of changing length; feet sliding; tails not moving.
- **Diagnosis and correction:** Check the footfall pattern and the head and tail. *Fix:* specify the gait.
- **Example:** A dog trots across a yard, then stops and sits.
- **AI specification:** "The dog trots left to right at a steady pace, diagonal legs moving together, tail slightly raised; it stops, lowers its hindquarters, and sits with its front paws planted."

### 3.5.2 Wing, Tail, Ear, and Head Movements; Animal-to-Object Interaction

- **Definition, start, outcome:** Movement of an animal's appendages and its interaction with objects.
- **Participating parts:** Wings, tail, ears, head, mouth or beak, paws.
- **Phases:** An ear rotates toward a sound; the head turns; the animal approaches; sniffing or touching; reaction. Birds flap: the downstroke generates lift; the wings fold on landing; the feet extend forward.
- **Timing, direction, weight:** Ears and head respond quickly to stimuli; tails reflect balance or state in a species-specific way.
- **Common errors:** Wings not flapping coherently; extra limbs; the animal touching objects without contact; sudden changes in size.
- **Diagnosis and correction:** Check the appendage's range. *Fix:* specify each part's movement.
- **Example:** A cat's ears turn toward a sound; it lowers its head and steps forward.
- **AI specification:** "The cat's left ear rotates toward the sound; its head turns; it lowers its body and steps forward with one front paw, then the other."

### 3.5.3 Leaves, Grass, Fabric, Hair, Smoke, Dust, Water, and Other Environmental Motion

- **Definition, start, outcome:** Passive movement driven by wind, a moving subject, gravity, or a disturbance.
- **Participating parts:** Leaves, blades of grass, cloth, hair, particles, fluids.
- **Phases:** Disturbance → movement → settling. Light elements move first and most; heavy elements move little.
- **Timing, direction, weight:** Direction follows the force: wind from the left moves things to the right. Fabric trails behind a moving body and billows with wind. Smoke rises and spreads. Dust is disturbed by feet and settles slowly. Water ripples outward from an impact and calms gradually.
- **Common errors:** Elements moving in different directions without cause; motion in still air; hair moving against the wind; water ripples with no source.
- **Diagnosis and correction:** Identify the force source. *Fix:* specify one wind direction.
- **Example:** A breeze from the left bends the grass and lifts her scarf toward the right.
- **AI specification:** "A light wind from the left moves the grass blades and the ends of her scarf to the right; her hair lifts slightly; the movement is steady."

### 3.5.4 Objects Rolling, Sliding, Swinging, Falling, Bouncing, and Rotating

- **Definition, start, outcome:** Passive object motion under gravity, impact, or force.
- **Participating parts:** The object, the surface.
- **Phases:** *Rolling:* the object turns as it moves. *Sliding:* it moves without rotating, slowing from friction. *Swinging:* it oscillates around a pivot (a pendulum with a length of about 0.25 m has a period of about 1 second; about 1 m about 2 seconds). *Falling:* it accelerates under gravity. *Bouncing:* it rebounds with each rebound lower than the last. *Rotating:* it spins around an axis.
- **Timing, direction, weight:** An object keeps moving unless a force acts. Bounces decrease in height; sliding stops through friction.
- **Common errors:** Constant-speed falling; bounces of equal height; rolling without turning; swinging objects that never settle.
- **Diagnosis and correction:** Check the speed changes. *Fix:* specify "accelerates as it falls; each bounce lower."
- **Example:** A ball rolls off a table, drops, and bounces three times with decreasing height.
- **AI specification:** "The ball rolls to the table's edge, falls, hits the floor, and bounces three times, each bounce lower than the previous, before rolling slowly to a stop."

### 3.5.5 Moving Vehicles and Mechanical Parts

- **Definition, start, outcome:** Motion of vehicles and machines, including wheels, doors, arms, and linkages.
- **Participating parts:** Wheels, body, suspension, mechanisms.
- **Phases:** Start (acceleration) → steady motion → braking → stop. Mechanical parts follow constrained paths: wheels rotate about axles; pistons move in lines.
- **Timing, direction, weight:** Vehicles accelerate and brake over time; they lean in turns; wheels rotate at a speed consistent with the vehicle's motion.
- **Common errors:** Wheels not turning, or turning backward or inconsistently; the vehicle sliding sideways; parts changing shape.
- **Diagnosis and correction:** Check wheel rotation relative to travel. *Fix:* specify "wheels rotate forward at a speed matching the car's motion."
- **Example:** A car brakes at a stop sign; its nose dips slightly.
- **AI specification:** "The car slows from left to right and stops at the line; its wheels turn more slowly until still; its front dips slightly on braking."

### 3.5.6 Motion Caused by Wind, Gravity, Impact, or Another Identifiable Force

- **Definition, start, outcome:** Movement whose cause is a named physical force.
- **Participating parts:** The moved object and the source (the wind, the weight, the impact).
- **Phases:** Force applied → object responds → force diminishes or continues → settling.
- **Timing, direction, weight:** Movement direction follows the force; its magnitude follows the force and the object's mass and flexibility.
- **Common errors:** A cause that is not visible; the response not matching the force.
- **Diagnosis and correction:** Check that the source is identifiable and consistent. *Fix:* name the force and its direction.
- **Example:** A hanging lamp swings after a door slams.
- **AI specification:** "The door slams on the left; the hanging lamp swings left to right in decreasing arcs over about three seconds."

---
# 4. BODY MECHANICS, BALANCE, AND WEIGHT

**Purpose of this section:** To explain the *visible* principles that make body movement believable. These are guides for design and review, not a biomechanics textbook. **No movement follows one rigid pattern** (see 4.8).

## 4.1 Center of Mass and Balance

- **Center of mass (COM)** is the point where the body's mass is effectively balanced. For a standing adult it lies roughly in the pelvic region, and it moves when limbs, loads, or posture change.
- **Balance** is the ability to keep the COM supported. A body is stable when the COM's vertical projection falls inside its **base of support**.

**Why it matters:** Viewers judge plausibility from where the body's weight appears to be relative to its supports. A body leaning far forward with no step, no counterbalance, and no support looks like it is hanging in the air.

**How to specify:** Name where the weight is ("weight on the left foot"), and what keeps it there ("right arm extended as a counterbalance").

**Failure and fix:** *Symptom:* the character leans at an angle that would fall. *Check:* the COM and the base. *Fix:* add a step, a support, a counterbalance, or reduce the lean.

## 4.2 Base of Support

The **base of support (BOS)** is the area enclosed by the points where the body contacts the ground or a support (the feet and the area between them; a hand on a wall adds to it).

| Condition | Effect on stability |
|---|---|
| **Wide stance** | Larger BOS; more stable; common when carrying loads or bracing |
| **Narrow stance** | Smaller BOS; less stable; requires more corrections |
| **One foot** | Very small BOS; arms and torso make rapid corrections |
| **Added support (hand on a rail)** | Increases BOS; allows leaning |

## 4.3 Weight Transfer

**Weight transfer** is the movement of the body's load from one support to another (from one foot to the other, from a seat to the feet). It precedes or accompanies most movements: the body shifts weight before lifting a foot, before standing, and before turning.

**Why it matters:** Missing weight transfer is one of the most common signs of artificial movement: the body glides to a new position without loading and unloading its supports.

**How to specify:** "Her weight shifts onto her left foot, then her right foot lifts."

## 4.4 Joint Articulation and Movement Limits

| Joint | Type and typical movement | Visible implication |
|---|---|---|
| **Elbow, knee** | Hinge: bend mainly in one plane | Do not bend sideways or backward |
| **Shoulder, hip** | Ball-and-socket: large rotation range | Large arm and leg movements start here |
| **Wrist** | Flexion/extension and side-to-side | The hand can tilt; extreme angles look wrong |
| **Forearm** | Rotation (palm up and down) | Hand orientation changes without moving the elbow |
| **Neck** | Rotation and tilt | Head rotation has a limit; shoulders join in large turns |
| **Spine** | Distributed bending and rotation | The torso curves; it does not hinge at a single point |
| **Fingers** | Flexion toward the palm; the thumb opposes | Fingers do not bend backward |
| **Ankle** | Hinge with limited side movement | The foot flexes; it does not rotate freely |

**Movement limits vary** with the person (flexibility, age, ability) and with deliberate style (a dancer's range is larger).

## 4.5 Coordination Between Torso, Hips, Shoulders, Arms, and Legs

**Kinetic chain (craft and physical principle):** Large movements often pass force through linked segments in sequence. In many throwing, swinging, or pushing movements, the legs and hips start, the torso follows, then the shoulder, arm, and hand. The details vary with the action.

**Cross-body coordination:** In walking and running, arms swing opposite to the legs on the same side.

**Why it matters:** Movements where only the end limb moves (a throw with only the hand) look weak and mechanical.

**How to specify:** "The hips rotate first, then the shoulders, then the arm."

## 4.6 Foot Placement and Ground Contact

- **Planted feet** stay still on the ground while the body moves over them.
- **Stance and swing:** In walking, each foot alternates between being planted (stance) and moving forward (swing).
- **Sliding** (feet moving across the ground while in contact) is appropriate on ice or in a skid; otherwise it signals an error.

**Why it matters:** Viewers are sensitive to foot contact. A foot that slides while the body moves is read as artificial.

**How to specify:** "Each foot plants flat and stays fixed while the body passes over it."

## 4.7 Inertia, Momentum, Acceleration, Resistance, Gravity, and Impact

| Principle | Meaning | Visible consequence | Design instruction |
|---|---|---|---|
| **Inertia** | A body at rest stays at rest, and a moving body keeps moving, unless a force acts. | Starting takes effort; stopping takes distance; a stopped body's loose parts keep moving briefly. | Show a start phase and a stop phase. |
| **Momentum** | Mass × velocity. | A heavy or fast subject needs more force to change direction. | Use wider turns and longer stops for heavy or fast subjects. |
| **Acceleration/deceleration** | Gradual change in speed. | Movements ease in and out. | Avoid instant changes in speed unless there is a collision. |
| **Resistance and counterforce** | When a body pushes something, the thing pushes back. | A pusher leans in; a puller leans back; a door resists. | Show bracing and body lean. |
| **Gravity** | Constant downward acceleration (about 9.8 m/s²). | Falling objects speed up; a drop of about 1 m takes about 0.45 s, of about 2 m about 0.64 s. | Use accelerating falls and arcs. |
| **Landing and impact absorption** | Joints flex to spread the force of landing over time. | Knees and hips bend on landing; stiff landings look abrupt. | Specify a flexed landing. |
| **Recovery** | The body returns to a stable posture. | Weight resettles; limbs settle. | Include a recovery phase after large movements. |

## 4.8 Movement Quality: Light, Heavy, Fatigued, Cautious, Confident, and Unstable

| Quality | Visible characteristics | Differences from a neutral walk or movement |
|---|---|---|
| **Light** | Springy steps, quick lifts, minimal ground contact, small effort | Shorter ground contact; higher lift; smooth arcs |
| **Heavy** | Slower start, longer ground contact, visible effort, a lowered center of mass, momentum that carries on | Slower acceleration; heavier stops; more body sway |
| **Fatigued** | Slower speed, shorter strides, lowered head, less arm swing, slower recovery | Reduced amplitude and energy; longer pauses |
| **Cautious** | Slow, deliberate, short steps, frequent gaze checks, a lowered center of mass, readiness to retreat | Smaller amplitude; head scanning; hesitations |
| **Confident** | Upright posture, even rhythm, full stride, steady gaze | Even timing; broad movements |
| **Unstable** | Frequent corrections, wide stance, arms extended, irregular rhythm | Variable stride; compensatory movements |

## 4.9 How Anatomy, Surface, and Style Change Movement

**Do not assume one pattern.** The following variables change how any movement looks:

| Variable | Effect |
|---|---|
| **Body proportions** | Limb lengths change stride length, reach, and posture. |
| **Age and ability** | Speed, range, and balance responses differ. |
| **Footwear** | High heels, boots, and bare feet change stride, foot contact, and sound. |
| **Surface conditions** | Ice, sand, mud, stairs, and slopes change steps, balance, and speed. |
| **Load** | A heavy backpack or a child on the hip shifts the COM and posture. |
| **Injury or discomfort (as movement modification)** | Protective postures, shorter steps, and favoring one side. |
| **Fatigue** | Smaller amplitude, slower recovery, irregular rhythm. |
| **Stylistic intention** | Exaggeration, minimalism, or physics-bending movement (Section 11). |

---

# 5. MOVEMENT TIMING, SPEED, AND RHYTHM

## 5.1 Speed Categories

| Category | Description | Typical use | Risk |
|---|---|---|---|
| **Slow** | Deliberate, drawn-out; details can be read | Care, hesitation, weight, emphasis | Too slow reads as stalled |
| **Moderate** | Everyday pace | Natural behavior | May lack contrast |
| **Fast** | Quick, energetic | Urgency, alarm | Details may be lost |
| **Explosive** | Very fast burst from rest or low speed | Startle, sudden evasion, jump, release | Often unreadable without a preceding anticipation or a following hold |

## 5.2 Constant Speed vs. Acceleration and Deceleration

**Physical principle:** Real bodies do not change speed instantly (except in collisions). Movements typically accelerate from rest, reach a working speed, and decelerate to the end.

**Craft convention ("slow in, slow out"):** Movements have more frames or time near the start and end and move fastest in the middle.

**Constant speed** looks mechanical (appropriate for machines and for deliberately robotic movement).

**How to specify:** "Starts slowly, speeds up through the middle, and slows to a stop."

## 5.3 Starts, Stops, Pauses, and Reversals

- **Start:** includes preparation.
- **Stop:** includes deceleration and recovery.
- **Pause:** a held moment that can signal thought, listening, or hesitation. It must still show life (breathing, small shifts).
- **Reversal:** a change of direction (going back). Needs deceleration, a plant, and re-acceleration.

## 5.4 Movement Duration and Timing: Approximate Guide

**Approximate durations for typical adult actions (these vary):**

| Action | Natural | Cautious or slow | Urgent |
|---|---|---|---|
| Stand up from a chair | About 1.5–2.5 s | 3 s or more | About 1 s |
| Take one walking step | About 0.5 s | 0.7 s or more | 0.4 s or less (running) |
| Reach and grasp a nearby cup | About 1–1.5 s | 2–3 s | About 0.7 s |
| Head turn toward a sound | About 0.3–0.8 s | 1 s or more | 0.2–0.3 s |
| Open a door (hand on knob to door ajar) | About 1.5–3 s | 4 s or more | About 1 s |
| Sit down | About 1.5–2.5 s | 3 s or more | About 1 s |

## 5.5 Rhythm, Repetition, Hesitation, and Irregularity

- **Rhythm** is the pattern of movement and pause over time.
- **Repetition** (a repeated gesture) creates rhythm but must include small variations in timing and amplitude.
- **Hesitation** is a micro-pause before or during an action; it communicates doubt or caution.
- **Irregularity** (variation in timing) is a sign of life; perfect regularity looks mechanical.

## 5.6 Anticipation, Follow-Through, and Reaction Delay

- **Anticipation:** A small preparatory movement before a major action (a wind-up, a crouch). It tells the viewer what is about to happen and gives the movement force.
- **Follow-through:** Continuation of movement after the main action ends (Section 12).
- **Reaction delay:** The time between a stimulus and a response. For simple stimuli, human reaction times are commonly about 0.15–0.3 seconds (approximate). A reaction that happens *before* the stimulus reads as an error (Section 7). A long delay can signal inattention or shock.

## 5.7 Synchronization Between Multiple Subjects

- **Unison:** Subjects move at the same time (marching, dancing).
- **Alternation:** Subjects move in turns (conversation gestures).
- **Response:** One subject's movement triggers another's after a reaction delay.
- **Independence:** Subjects who are not coordinated should have different rhythms; identical rhythms look unnatural.

## 5.8 Moving Quickly vs. Appearing Energetic

**Energy** is communicated by force, intent, contrast, and clarity of anticipation and follow-through, not by speed alone. A fast but unclear movement can look weak; a slow, heavy, purposeful movement can look powerful.

## 5.9 Stillness and Excessive Speed

- **Stillness before movement** makes the movement more noticeable. A held pause is a contrast device.
- **Excessive speed** makes an action unreadable. A critical phase (contact, release) needs enough screen time to be perceived (often at least a few tenths of a second; depends on frame size and context).
- **Uniform timing** (every phase at the same duration) looks robotic.

## 5.10 Timing by Purpose, Physical Requirement, Subject, and Style

| Driver | How it changes timing |
|---|---|
| **Purpose** | An urgent purpose shortens preparation and accelerates movement; a deliberate purpose adds pauses. |
| **Physical requirement** | A heavy lift takes longer; a precise grasp requires slowing near the target. |
| **Subject** | A child, an older adult, a trained athlete, or a tired person differ in speed and rhythm. |
| **Style** | Stylized action may compress or stretch timing (Section 11). |

## 5.11 Same Action, Four Ways: Reaching for and Lifting a Mug

| Parameter | Cautious | Natural | Urgent | Deliberate |
|---|---|---|---|---|
| **Preparation** | Looks at the mug, glances at surroundings, small hesitation | Glances at the mug, begins | Almost none; begins as the gaze lands | Settles posture, breathes, then begins |
| **Reach speed** | Slow, with a pause near the mug | Smooth, moderate | Fast, with a late deceleration | Even, controlled |
| **Path** | Slightly curved, avoiding objects | Direct | Straight, may brush items | Direct, precise |
| **Grip** | Light first touch, then securing | Normal wrap | Quick and firm | Careful, complete |
| **Lift** | Slow, check for spills | Smooth | Quick, may slosh | Smooth, with a deliberate pause |
| **Ending** | Lowers slowly | Rests or drinks | Immediately moves on | Holds still before the next action |
| **Gaze** | Alternates between mug and surroundings | Mostly on the mug | May stay on something else | Fixed on the mug |

**What changes:** Preparation, speed, path, grip pressure, pauses, and gaze.
**What must remain consistent:** The hand shape fits the mug; the grip contact is visible; the mug stays upright (unless sloshing is intended); the arm length and joint limits stay constant; gravity and momentum apply.

---

# 6. MOTION PATHS AND SPATIAL RELATIONSHIPS

## 6.1 Path Types

| Path | Description | Typical use | Notes |
|---|---|---|---|
| **Straight** | Moves in a line | Direct approach, urgent travel | Can look mechanical over long distances for living subjects |
| **Curved** | Smooth arc | Natural human and animal movement, turns, arms | Most organic movements follow arcs |
| **Circular** | Around a point or subject | Circling, orbiting, pacing around | Requires consistent radius and orientation |
| **Diagonal** | Across the frame or space at an angle | Entering, leaving, crossing | Strong visual direction |
| **Irregular** | Varies in direction | Searching, wandering, uncertainty | Must have reasons (obstacles, indecision) |

## 6.2 Directions Relative to Another Subject

| Direction | Effect on interaction |
|---|---|
| **Toward** | Approach; closes distance; increases contact risk |
| **Away** | Retreat; increases distance |
| **Across** | Passes in front or behind; may block sight lines |
| **Around** | Circles; changes the viewpoint relationship |

## 6.3 Vertical and Horizontal Movement

Vertical movements (standing, jumping, climbing, falling) involve gravity directly and require strong weight cues. Horizontal movements (walking, sliding) involve friction and momentum.

## 6.4 Movement Through Doorways, Corridors, Obstacles, and Confined Spaces

- **Doorways:** The body narrows (shoulders turn) if the opening is tight; the hand may touch the frame; the head may duck for low frames.
- **Corridors:** Provide a straight path with limited lateral movement; turning at corners requires a curved path.
- **Obstacles:** The path bends around them; the body may step over or lean.
- **Confined spaces:** Movement is smaller; the body folds.

## 6.5 Start, Intermediate, and Endpoint Positions

- **Start position:** Where the movement begins; defines the path origin.
- **Intermediate positions (waypoints):** Positions that the path must pass through (the doorway, the table corner). They prevent a movement from becoming a jump between poses.
- **Endpoint:** Where the movement ends.

## 6.6 Distance, Scale, and Orientation

- **Distance traveled:** Estimate in steps (about 0.6–0.8 m per walking step for a typical adult) or meters.
- **Spatial scale:** The distance relative to the frame (a 5 m walk may cross the frame or only part of it).
- **Orientation changes:** The body's facing direction can change during movement; specify when.

## 6.7 Proximity, Separation, and Collision Risk

- Moving subjects in close proximity risk overlap or collision.
- Maintain consistent separation unless contact is intended.
- Specify "does not touch" or "touches at the shoulder" as needed.

## 6.8 Interaction With Environmental Boundaries

Walls, floors, furniture, and edges stop movement or deflect it. A subject moving toward a wall must stop, turn, or touch it.

## 6.9 Screen-Space Movement vs. Movement Through Three-Dimensional Space

| | Screen-space description | Three-dimensional description |
|---|---|---|
| **Example** | "She moves from left to right in the frame." | "She walks from the kitchen toward the front door, crossing in front of the camera." |
| **Limitation** | Depends on camera position; changes if the camera changes | Requires a defined layout |
| **Use** | When the camera is fixed | When the scene's geography matters |

**Rule:** Specify the **frame of reference**: *subject-relative* ("to her left"), *scene-relative* ("toward the door"), or *screen-relative* ("toward the right edge of the frame"). Do not mix them without saying which is meant.

## 6.10 Describing a Path Unambiguously

Include:

1. **Start landmark** ("beside the sofa").
2. **Waypoints** ("past the table's left corner").
3. **Endpoint landmark** ("at the window").
4. **Direction vocabulary and frame of reference** ("toward the screen's right edge").
5. **Orientation along the path** ("facing the direction of travel").
6. **Distance estimate** ("about five steps").

**Preventing disconnected poses:** Describe continuous travel between waypoints ("walks continuously through the doorway without stopping"), and state that intermediate steps occur.

## 6.11 Small Path Changes, Large Differences

| Path change | Effect on balance | Effect on contact | Effect on visibility | Effect on meaning |
|---|---|---|---|---|
| **Approaching a door straight on vs. at an angle** | A straight approach puts weight forward over both feet; an angled approach turns the torso | The reaching arm uses a different hand | The body may hide the handle | A straight approach can look decisive; an angled one can look cautious |
| **Rounding a table corner tightly vs. widely** | A tight turn needs a lean and braking | May brush the corner | The wide turn exposes the whole path | A tight turn can look hurried |
| **Handing an object from the side vs. from the front** | Side handover twists the torso | The hands meet at different angles | The object may hide the faces | Side handover feels casual; frontal feels formal |
| **Walking behind a pillar vs. in front of it** | None | None | The subject disappears behind the pillar | Changes whether the viewer sees the action |

---
# 7. ACTION CAUSE AND EFFECT

## 7.1 The Causal Chain

Physical causality is the backbone of readable action. Every action can be described as a chain:

| Link | Question | Example (pushing a door) |
|---|---|---|
| **1. Initiator** | What starts it (intention, trigger)? | She hears a knock. |
| **2. Force or intention** | What drives it? | She decides to open the door; the arm pushes. |
| **3. Contact or interaction** | What does the subject touch? | Her palm meets the door surface. |
| **4. Moment of interaction** | What happens at the contact? | Pressure builds; the door's resistance is felt. |
| **5. Response** | How do the subject and environment respond? | The door swings inward; her arm follows; her weight shifts. |
| **6. Resulting state** | What remains afterward? | The door is open about 60°; she stands in the opening. |

**Why it matters:** A viewer reads an action as "real" when each link exists, appears in order, and is visible or clearly implied.

## 7.2 Contact, Resistance, Momentum, Deformation, and Follow-Through

- **Contact:** The first moment two things touch. Force transfers only at contact.
- **Resistance:** What opposes the force (weight, friction, a latch, a spring). The subject's body reveals the resistance (leaning in, tension in the arm).
- **Momentum:** Once moving, an object continues. A pushed door keeps swinging briefly after the hand releases.
- **Deformation (where applicable):** Soft things change shape under contact: a cushion compresses; a sleeve wrinkles; a finger pad flattens on glass; a rope sags and tightens.
- **Follow-through:** Movement continues after the main action: the arm continues after a push; the door continues to swing.

## 7.3 Common Causal Failures

| Failure | What it looks like | Why it reads as wrong |
|---|---|---|
| **Object moves before contact** | The cup slides toward the hand before the fingers touch it | The effect precedes the cause |
| **Hand passes through an object** | The fingers appear inside the handle | No contact surface |
| **Reaction before the event** | A character flinches before the glass breaks | The response precedes the stimulus |
| **Impact without visible consequence** | A ball hits a wall with no recoil | No evidence of force |
| **Movement with no clear cause** | A chair slides away on its own | No initiator |
| **Force without effort** | A heavy object moves as if empty | Weight is not conveyed |
| **Effect without end** | A door swings forever | No friction or stop |

## 7.4 Causal-Chain Worksheet (Complex Actions)

For each link of a complex action (for example, a character knocks over a glass and catches it), fill in a row:

| # | Initiator or cause | Force or intent | Contact point | Immediate response | Consequence/state after | Visible evidence required | Check |
|---|---|---|---|---|---|---|---|
| 1 | Elbow bumps the glass | Small sideways force | Elbow touches glass base | Glass tips | Glass begins to fall | Elbow touches before the glass moves | ☐ |
| 2 | Glass falling | Gravity | None | Glass rotates and drops | Glass accelerates downward | Accelerating fall | ☐ |
| 3 | She notices | Reflex | None | Eyes and head turn toward the glass | Body begins to lunge | Head turn before the lunge, after the tip | ☐ |
| 4 | Hand reaches | Intent to catch | Hand meets glass | Fingers close; glass decelerates | Glass held | Fingers touch before the glass stops | ☐ |
| 5 | Catch complete | Momentum absorbed | Hand holds the glass | Arm lowers; liquid settles | Glass upright in hand | Final state | ☐ |

## 7.5 Diagnosing a Broken Cause-and-Effect Sequence

1. **List the links** in the intended order.
2. **Find the first link that is wrong or missing.** Later links often fail because an earlier link failed.
3. **Classify the break:** missing, out of order, wrong direction, wrong magnitude, or invisible.
4. **Correct the smallest relevant variable** (for example, "the hand touches the cup before the cup moves"), not the whole description.
5. **Re-check** the order and the end state.

---

# 8. OBJECT INTERACTION AND CONTACT

## 8.1 The Interaction Sequence

| Stage | What it is | What must be visible | Common error |
|---|---|---|---|
| **Reaching and aligning the hand** | The hand approaches and shapes to the object (aperture scaled to the object's size) | Hand opening before contact; direction toward the object | The hand does not adapt to the object |
| **Establishing contact** | First touch | Fingertips or palm meeting the surface | The hand intersects the object |
| **Grasping or applying force** | The grip closes or force builds | Fingers wrap or press; muscles tighten | No closure; hand passes through |
| **Maintaining contact during movement** | The hand stays attached as the object moves | Stable relative position of hand and object | The object slips or changes orientation without reason |
| **Transferring weight or force** | The object's load moves to the subject (or to another support) | Arm and posture adjust to the load | Heavy object with no adjustment |
| **Releasing** | The grip opens; the object settles | Fingers opening; object resting or leaving | The object vanishes or stays suspended |
| **Showing the resulting object movement** | The object moves because of the action | The object's motion follows the force | The object moves without a cause |
| **Reacting to resistance, unexpected weight, or failed contact** | The subject adjusts | Surprise, tightening, a second attempt | No reaction |

## 8.2 Grip, Size, Placement, Timing, Orientation, and Constraints

| Factor | Principle | Practical specification |
|---|---|---|
| **Grip consistency** | The same grip (fingers on the same parts of the object) remains until release. | "The index finger and thumb stay pinched on the pen." |
| **Object size** | The hand's aperture corresponds to the object; a large object requires two hands. | "Both hands hold the box." |
| **Hand placement** | Hands grip handles, edges, or surfaces that support the object. | "Right hand on the handle; left hand under the base." |
| **Contact timing** | Contact occurs before movement of the object. | "Fingers touch the cup, then the cup lifts." |
| **Object orientation** | The object keeps a consistent orientation unless rotated deliberately. | "The cup stays upright." |
| **Physical constraints** | Hinges, weights, friction, and springs limit movement. | "The door swings on its left hinge." |

## 8.3 Maintaining Object Identity, Shape, Size, Location, and Continuity

1. **Name the object once with its distinguishing features** ("a white ceramic mug with a chipped handle").
2. **Refer to it consistently** by the same name.
3. **State where it starts and ends** ("on the left side of the table; ends in her right hand").
4. **State that it keeps its size and shape** when this is at risk.
5. **Avoid having the object leave and return** unless needed.
6. **Limit the number of similar objects** in frame.

## 8.4 Practical Interaction Examples

### Doors
- **Cause and effect:** Hand on the handle → handle turns → latch releases → door moves along its arc.
- **Details:** Hinge side, swing direction, door thickness, the hand's contact with the handle, the body stepping aside as the door swings.
- **Common errors:** Door opening toward the wrong side; handle not turning; door moving before contact.

### Chairs
- **Pulling a chair out:** The hand grips the backrest, the chair slides back on the floor with friction, the legs stay on the floor, the person steps in.
- **Sitting:** The hips lower, the hands may steady the chair, the weight transfers to the seat, and the chair settles.
- **Common errors:** The chair moving without a hand; the chair legs sliding in the air; the person sitting through the chair.

### Cups
- **Lifting:** Fingers wrap or grasp the handle, the cup lifts, liquid surface stays level and may sway.
- **Common errors:** The cup changing size; the liquid tilting with the cup; a hand missing the handle.

### Bags
- **Picking up a shoulder bag:** The hand grips the strap, the strap tightens, the bag lifts, the shoulder rises to receive the strap, the bag swings and settles.
- **Common errors:** The bag swinging without contact; the strap not tightening; weight not affecting posture.

### Tools
- **Using a hammer or screwdriver:** Grip is appropriate to the handle; the tool's motion follows the arm; contact with the target is visible; the body braces.
- **Common errors:** The tool changing shape; the grip sliding; contact with no effect.

### Objects Handed Between Two Subjects
- **Sequence:** The giver holds the object out with a stable grip → the receiver's hand aligns → both hands touch the object → the receiver takes the weight → the giver releases → the receiver draws the object in.
- **Details:** The shared-grip moment prevents "teleportation." Hands should not overlap in a way that merges them.
- **Common errors:** The object appearing in the receiver's hand with no pass; the giver releasing before the receiver grips; hands merging.

---

# 9. MULTI-SUBJECT ACTION AND COORDINATION

## 9.1 Relationship Types

| Relationship | Description | Design considerations |
|---|---|---|
| **Shared goals** | Subjects work together | Synchronize timing; communicate with gaze and gesture |
| **Conflicting goals** | Subjects oppose each other | Define who acts first and who responds |
| **Turn-taking** | Subjects act in sequence | State the order and the trigger for each turn |
| **Leading and following** | One subject sets direction or tempo | The follower reacts after a short delay |
| **Mirroring** | A subject copies another's movement. *Mirror mirroring:* the follower moves the opposite hand. *Same-side:* the same hand | State which; the choice changes how it reads |
| **Synchronized motion** | Subjects move together | Allow small natural differences |
| **Approaching and retreating** | One moves toward, the other away | Define distances and speeds |
| **Passing objects** | An object travels between subjects | Define the shared-grip moment |
| **Supporting or resisting** | One supports or opposes the other's movement | Show weight and counterforce |

## 9.2 Avoiding Accidental Overlap and Maintaining Distance and Contact

- Define **who occupies which space** at each time.
- State **distance** ("about an arm's length apart").
- State **contact** ("their shoulders do not touch").
- Keep **limbs separate** unless contact is intended; overlapping bodies in generation can merge.

## 9.3 Coordinating Gaze, Orientation, and Hand Placement

- **Gaze:** Subjects look toward each other before synchronized actions.
- **Body orientation:** Bodies turn toward the person they interact with.
- **Hand placement:** Specify which hand touches which part, in what order.

## 9.4 Specifying Who Does What, in What Order, and in Response to What

**Action Ownership Table (use for any multi-subject action):**

| Order | Subject (distinct label) | Action | Trigger (event or the other subject's action) | Timing | Contact with | Ends in |
|---|---|---|---|---|---|---|
| 1 | **A:** taller woman, red coat, on the left | Holds out the folder | Hears "here you go" | 0–1 s | None | Arm extended |
| 2 | **B:** shorter man, gray jacket, on the right | Reaches for the folder | A's arm extends | 0.5 s after 1 | Folder edge | Both hands on the folder |
| 3 | **A** | Releases the folder | B's grip closes | 0.3 s after 2 | None | Hands lowered |
| 4 | **B** | Draws the folder in | A's release | 0.5 s after 3 | Folder | Folder against chest |

## 9.5 Preventing Action Ownership From Switching and Preserving Identity

| Problem | Cause | Prevention |
|---|---|---|
| **The action switches to the wrong character** | Ambiguous pronouns; similar characters | Use distinct labels and attributes every time ("the woman in the red coat"); avoid "they" and "the other one" |
| **Identity merges** | Similar costumes, positions, or overlap | Give each subject distinct clothing and a distinct position ("A on the left; B on the right") |
| **Clothing changes** | The model re-samples | State clothing once per subject and restate it if the shot changes |
| **Proportions change** | Different scales between subjects | State relative size ("A is a head taller than B") |
| **Position swaps** | Subjects cross paths | State the path and that they keep their sides ("they do not change places") |

---

# 10. ACTION, EMOTION, AND CHARACTER

## 10.1 Principle

Movement communicates internal state, but **no movement has one universal meaning.** Interpretation depends on:

- **Context:** what has happened and what is at stake.
- **Personality:** a habitually fidgety person vs. a habitually still one.
- **Physical ability:** limited mobility changes how any emotion appears.
- **Culture:** gestures, personal space, and eye contact differ across cultures.
- **Narrative situation:** the same gesture can be warm or controlling.

**Design rule:** Choose movement *qualities* (timing, amplitude, tension, gaze, coordination) and verify that they read correctly in context. Avoid assigning one fixed gesture to one emotion.

## 10.2 Movement Parameters That Influence Interpretation

| Parameter | What it shows | Examples of variation |
|---|---|---|
| **Posture** | Openness, tension, readiness | Upright, collapsed, braced |
| **Timing** | Urgency, hesitation | Quick, delayed, irregular |
| **Amplitude** | Intensity or restraint | Large vs. small gestures |
| **Gaze** | Attention, avoidance | Direct, averted, scanning |
| **Tension** | Control or relaxation | Tight shoulders, relaxed hands |
| **Pauses** | Thought, doubt | Held beats |
| **Coordination** | Fluency or disruption | Smooth, interrupted, uncoordinated |

## 10.3 Emotional and Character States: Possible Movement Evidence

| State | Possible movement evidence | Context that can change the meaning | Common mistake |
|---|---|---|---|
| **Confidence** | Upright posture, even stride, steady gaze, economical gestures | Arrogance vs. competence | Exaggerated swagger |
| **Hesitation** | Pauses before action, partial movements, retraction, repeated glances | A careful person vs. a fearful one | Freezing completely |
| **Fear** | Shortened steps, bracing, scanning, protective arm positions, faster breathing | A startle vs. sustained fear | Wide-eyed theatrical gestures |
| **Caution** | Slow, small steps, checking gaze, low center of mass, minimal noise | Professional care vs. anxiety | Stiffness that looks mechanical |
| **Curiosity** | Leaning toward, head tilts, approaching by steps, touching lightly | Child's curiosity vs. investigation | Constant head tilting |
| **Suspicion** | Narrowed gaze, slowed movement, stopping to listen, sideways glances | A skeptic vs. an anxious person | Exaggerated squint |
| **Anger** | Tense jaw and shoulders, abrupt movements, forceful contact, sharp direction changes | Controlled anger may be still | Constant shouting gestures |
| **Frustration** | Repeated attempts, sighs, short abrupt gestures, fidgeting | Impatience vs. exhaustion | Over-acting |
| **Relief** | Release of tension: shoulders drop, exhale, slowed movement | Joy vs. exhaustion | Sudden collapse |
| **Exhaustion** | Slow, heavy movements, lowered head, longer pauses, support-seeking | Fatigue vs. illness vs. grief | Slow motion without effort cues |
| **Determination** | Forward lean, steady pace, fixed gaze, deliberate gestures | Stubbornness vs. resolve | Clenched fists in every shot |
| **Urgency** | Fast steps, direct paths, minimal preparation, quick gaze shifts | Panic vs. professionalism | Running when walking fast would do |
| **Grief and emotional restraint** | Slow, minimal movement, held posture, displaced action (smoothing fabric), delayed reactions | Cultural norms and personality | Large sobbing for a restrained moment |
| **Affection and care** | Gentle touch, soft pacing, closeness, attention to the other's needs | A caregiver vs. a romantic partner | Overly sweet gestures |
| **Confusion and uncertainty** | Turning in place, scanning, starting then stopping, asking with gestures | A lost person vs. a thoughtful one | Random movement |
| **Concealment, deception, or avoidance** | Controlled stillness, avoided eye contact, hands hidden or busy, slightly delayed responses | Shyness vs. deceit | Shifty glances that signal "lying" |

## 10.4 Designing Subtle Action Without Theatrical Movement

1. **Change one parameter slightly:** timing (a half-second longer), gaze (a glance away), or amplitude (a smaller gesture).
2. **Use an interrupted or partial action:** a reach that stops before the object; a step that is retracted.
3. **Displace emotion into an object or task:** smoothing a tablecloth, adjusting a cuff.
4. **Use a hold:** a pause that lets the viewer read the state.
5. **Keep the face neutral and let the body carry a small cue:** tight shoulders, a grip that tightens.
6. **Keep the movement credible:** match the character's physical ability and personality.

**Example (restraint):** A man hears bad news. His face stays still; his hand stops mid-way to the cup, hovers, and returns to his lap. He then picks up the cup with careful slowness.

---

# 11. NATURALISM, STYLIZATION, AND MOVEMENT QUALITY

## 11.1 Movement Styles

| Style | Definition | Typical use | Risks |
|---|---|---|---|
| **Naturalistic** | Follows ordinary physical and anatomical behavior | Drama, realism | May lack emphasis |
| **Restrained cinematic** | Naturalistic, with trimmed extraneous movement and clear beats | Most film drama | Can look stiff if overly trimmed |
| **Highly stylized** | Timing, posing, or physics altered by design (dance-like, graphic) | Musicals, stylized genres | Requires consistent rules |
| **Exaggerated action** | Larger amplitude and force than reality | Comedy, heightened action | Can look absurd if inconsistent |
| **Slow motion** | Movement shown slower than natural speed; details and weight are visible | Emphasis, beauty, impact | Can lose urgency; needs consistency in secondary motion |
| **Fast motion** | Movement shown faster than natural | Comedy, time passing, urgency | Details lost |
| **Mechanical or robotic** | Constant speed, discrete joints, abrupt starts and stops | Robots, stylized human movement | Looks like an error if unintended |
| **Dreamlike or physically unconventional** | Floating, time dilation, impossible paths | Dreams, fantasy | Must have internal logic |

## 11.2 Choosing and Maintaining a Style

1. **Choose by purpose:** realism for credibility; stylization for emphasis or tone.
2. **Define the rules** (amplitude, timing, physics) once.
3. **Apply them to all subjects and objects** in the scene.
4. **Restate the style** in each prompt and check each clip.
5. **Do not mix styles accidentally** (a naturalistic walk with a floating jump).

## 11.3 Signs of Artificial Movement

| Sign | What it looks like | Likely cause | Correction |
|---|---|---|---|
| **Excessive joint stiffness** | Limbs moving as rigid rods | Missing joint articulation | Specify joint bending and soft movement |
| **Unnatural joint bending** | Knees or elbows bending the wrong way | Anatomical errors | Specify the joint's direction |
| **Floating feet** | Feet hovering or not planting | No ground contact | Specify planted feet |
| **Sliding without support** | Body glides over the floor | No stance/swing | Specify steps |
| **Inconsistent limb length** | Arms or legs change length | Model drift | Restate proportions; simplify |
| **Sudden body-shape changes** | Clothing or body volume changes | Frame-to-frame instability | Restate costume; shorten the action |
| **Missing weight transfer** | No loading before movement | Pose interpolation | Specify weight shifts |
| **Perfectly synchronized secondary motion** | Hair, cloth, and limbs move in unison | Uniform treatment | Allow independent timing |
| **No anticipation or follow-through** | Starts and stops abruptly | Missing phases | Add preparation and recovery |
| **Unmotivated speed changes** | Sudden acceleration without cause | Unclear timing | Specify speed profile |

## 11.4 Deliberate Stylization vs. Accidental Error

| Test | Deliberate stylization | Accidental error |
|---|---|---|
| **Motivation** | A stated reason (tone, character) | None |
| **Consistency** | Applied consistently across the subject and scene | Appears randomly |
| **Rules** | The movement follows an internal logic | Contradicts itself |
| **Control** | Amplitude and timing are repeatable | Varies without pattern |
| **Documentation** | Recorded in the design | Not mentioned |

**Rule:** If the unusual movement cannot be explained by a purpose and does not repeat consistently, treat it as an error.

---

# 12. SECONDARY MOTION AND FOLLOW-THROUGH

## 12.1 Definitions

- **Primary action:** The main movement that carries the action's purpose.
- **Secondary action:** A deliberate supporting action (Section 1.5).
- **Secondary motion:** *Passive* movement of parts that results from the primary movement: hair swinging, fabric trailing, accessories bouncing, liquid sloshing.
- **Follow-through:** Continued movement after the main action ends.
- **Overlapping action (animation craft):** Different parts of a body or object start and stop at different times because of their different masses and attachments.

## 12.2 Why Secondary Motion Matters

Secondary motion provides evidence of weight, speed, and conditions. A coat that trails behind a walking person shows the body's speed; the way a loose sleeve settles shows the arm's stop.

## 12.3 Types and Their Behavior

| Element | Behavior | Specification |
|---|---|---|
| **Hair** | Lags behind head movement; swings; settles | "Her hair swings after her head turns and settles over about half a second" |
| **Clothing and loose fabric** | Trails during movement; billows with wind; settles | "Her coat trails behind her; it swings forward when she stops" |
| **Accessories** | Swing, bounce, rattle | "The pendant swings forward as she stops and then back" |
| **Delayed movement and settling** | Parts overshoot and return | "The bag swings once and settles" |
| **Objects swinging or oscillating** | Pendulum-like; the period depends on length (about 1 s for 0.25 m; about 2 s for 1 m) and amplitude decreases | "The lamp swings in decreasing arcs" |
| **Breathing and posture adjustments** | Continuous, small | "Her shoulders rise and fall with slow breaths" |
| **Environmental response** | Dust lifts at a step; water ripples from a footstep; foliage moves when brushed | "Dust lifts around his boots with each step" |

## 12.4 When Secondary Motion Supports Realism and When It Distracts

| Supports | Distracts |
|---|---|
| Matches the primary movement in time, direction, and magnitude | Starts before the primary action |
| Shows weight and speed | Continues long after the primary action should have stopped |
| Is limited to a few key elements | Fills the frame with unrelated movement |
| Is consistent with the conditions (wind, humidity) | Contradicts the conditions (hair blowing in still air) |

## 12.5 Avoiding Contradictions

| Problem | Example | Fix |
|---|---|---|
| **Contradicts the primary action** | A scarf flies forward while the wearer runs forward | Make it trail behind |
| **Starts too early** | Hair swings before the head turns | State "after" |
| **Continues too long** | A sleeve keeps swinging after the arm stops | State "settles in about half a second" |
| **Violates apparent conditions** | Flags flap in a windless scene | State wind or its absence |
| **Is perfectly synchronized** | All fabrics move identically | Allow different lag for different materials |

---
# 13. ACTION CONTINUITY ACROSS SHOTS

**Scope reminder:** Editing has its own knowledge base. This section covers only how to preserve the continuity of an *action* that spans more than one shot or clip.

## 13.1 What Must Match Across a Cut

| Element | What must match | Typical break |
|---|---|---|
| **Action direction** | The direction of the movement (left to right, toward the door) | The subject reverses direction after the cut |
| **Body position at the cut** | Posture, limb positions, weight placement | The arm is raised in one shot and lowered in the next |
| **Object state and hand placement** | Which hand holds what, and how; the object's position and condition | The cup moves from the right hand to the left |
| **Movement phase and timing** | The point in the action's phases (reaching, gripping, lifting) | The next shot starts earlier or later in the action |
| **Speed and trajectory** | The pace and path of the movement | A fast reach becomes slow |
| **Contact points** | The same fingers, the same surface | The grip changes between shots |
| **Screen direction** | The direction of travel on the screen | The subject exits right and enters right |
| **Spatial relationships** | Positions of subjects and objects relative to each other | Characters change sides |
| **Costume, props, and surroundings** | Details that identify the moment | A sleeve is rolled up in one shot and down in the next |

## 13.2 Avoiding Duplicated, Skipped, and Reversed Actions

| Problem | What the viewer sees | Cause | Prevention |
|---|---|---|---|
| **Duplicated action** | The same movement appears twice (the hand reaches, then reaches again) | Overlapping coverage both include the movement | Decide in which shot the movement happens and cut at the matching phase |
| **Skipped action** | The movement jumps ahead | The cut removes part of the movement without a visual bridge | Keep the phases continuous or cut to a shot that justifies the gap |
| **Reversed action** | The movement appears to go backward | Different direction in the next shot | Specify direction in each shot |

## 13.3 Planning Action Before, During, and After a Cut

1. **Before the cut:** Define what the subject is doing and the phase at the cut point.
2. **At the cut:** Define the exact body position, object state, and direction.
3. **After the cut:** Define the continuation from the same phase.
4. **Overlap (shooting practice):** Many productions repeat a short portion of the action across adjacent shots so the editor can choose the cut point. In AI generation, repeat the end state of the previous clip as the start state of the next.

## 13.4 Cutting on Action

**Cutting on action** (craft convention) means cutting *while a movement is in progress* rather than before or after it. Because the viewer's attention follows the movement, the change of viewpoint is less noticeable, and the movement can appear continuous.

**Principles:**

1. **Cut mid-movement,** commonly at a point of clear motion (a hand rising, a turn starting), not in a pause.
2. **Match the direction and speed** across the cut.
3. **Match the phase:** the second shot begins at the same point of the action where the first ended (or, with overlap, slightly earlier).
4. **Change the viewpoint enough** to look like a new angle or size (see the Shot Size knowledge base), while the movement continues.
5. **Support the cut with sound** (a sound that continues across the cut).

**When it can be broken:** In fragmentary or stylized editing, repetition or jumps may be deliberate. In action sequences, repeated moments (showing an impact twice) may be intentional. Mark them as deliberate.

## 13.5 Worked Example: A Multi-Shot Action With Continuity Checkpoints

**Action:** A woman at a table notices a ringing phone, picks it up, and answers.

| Shot | Description | Phase covered | Cut point |
|---|---|---|---|
| **S1** | Wide shot: she sits at the table, phone on the right, a mug in her left hand | Preparation and initiation | Cut as her right hand begins to rise |
| **S2** | Medium shot: her right hand moves toward the phone | Execution | Cut as her fingertips are about to touch the phone |
| **S3** | Close-up: fingers close on the phone, lift it from the table | Contact and lift | Cut as the phone clears the table |
| **S4** | Medium close-up: she brings the phone to her ear | Follow-through and resulting state | End |

**Continuity checkpoints:**

| ID | Cut | What must match | Check |
|---|---|---|---|
| **C1** | S1 → S2 | Right hand rising at the same speed; left hand still holding the mug; her gaze on the phone | ☐ |
| **C2** | S1 → S2 | Phone location on the table (right side, screen-left to right as stated); hand direction toward the phone | ☐ |
| **C3** | S2 → S3 | Fingertips approach from above and the right; the hand is open at the same aperture | ☐ |
| **C4** | S2 → S3 | Phone is in the same position and orientation (screen facing up) | ☐ |
| **C5** | S3 → S4 | The phone is held in the right hand, same grip; the lifting direction continues upward | ☐ |
| **C6** | All | The mug stays in the left hand and the sleeve of her right arm remains rolled to the elbow | ☐ |
| **C7** | All | Table, lighting direction, and costume unchanged | ☐ |

**Why it works:** Each cut happens during movement, the direction (toward the phone, then up toward the ear) is continuous, and the object states are tracked.

---

# 14. ACTION AND CAMERA MOVEMENT

**Scope reminder:** Camera movement has its own knowledge base. This section covers only how camera behavior interacts with the readability, continuity, and specification of *subject* action.

## 14.1 Core Principle: Specify Subject and Camera Independently

What the viewer sees on screen is the **relative motion** between the subject and the camera. A subject walking left at the same speed as a camera tracking left appears to stand still on the screen while the background moves right. Because the two motions combine, each must be described *separately* and *explicitly*.

**Template:**

```
SUBJECT MOTION: [what the subject does; path; speed]
CAMERA:         [still, or the camera's own movement; direction; speed]
```

## 14.2 Configurations

| Configuration | Subject | Camera | What the viewer sees | Risks | Specification |
|---|---|---|---|---|---|
| **Subject moves, camera still** | Walks across the space | Locked-off | The subject crosses the frame; the background is fixed | The subject may exit the frame or become small | "Subject walks left to right across the frame; camera locked-off." |
| **Camera follows a moving subject** | Walks forward | Moves behind at the same speed | The subject stays at a constant size; the background moves past | The subject drifts relative to the frame | "Subject walks forward; camera follows behind at the same speed, keeping her centered." |
| **Camera leads a subject** | Walks toward the camera | Moves backward in front | The subject stays at constant size, facing the camera; the background recedes | The camera speed may not match | "Subject walks toward the camera; camera retreats at the same pace." |
| **Camera tracks alongside** | Walks parallel to the camera's path | Moves sideways at the same speed | The subject appears still on screen; the background slides | The subject's motion may be read as stillness | "Subject walks to the right; camera tracks to the right at the same speed." |
| **Camera approaches or retreats during an action** | Performs an action in place | Moves toward or away | The subject appears to grow or shrink while acting | Confusing the subject's own movement with the camera movement | "Subject stands still and turns her head; camera pushes in slowly." |
| **Camera moves around interacting subjects** | Two people converse or hand over an object | Orbits slowly | The relationship between subjects changes in view; the background shifts | Subjects may merge or swap positions | "Two people stand still; the camera orbits 45° clockwise." |
| **Subject and camera move in opposite directions** | Moves left | Moves right | Fast apparent relative speed | Disorientation | "Subject walks left; camera moves right." |
| **Camera reveals an action in stages** | Performs an action in a fixed location | Pans, tilts, or pushes to show more | New parts of the action appear over time | The action may happen out of view | "Subject threads a needle; camera pushes from the shoulder to the hands." |

## 14.3 Avoiding Unintended Movement of Both

| Problem | Cause | Prevention |
|---|---|---|
| **Subject was meant to be still but appears to move** | The camera drifts or zooms | "Camera locked-off; no zoom; no drift." |
| **Camera was meant to move but the subject appears to move** | Ambiguous wording ("moves closer") | "The camera pushes in toward the subject; the subject stays in place." |
| **Both move and the result is confusing** | Neither is specified | Use the template and state both |
| **Background moves like the subject** | Parallax and tracking confusion | Specify which one moves |

## 14.4 Readability Rules for Action and Camera

1. If readability of the action is the priority, **keep the camera simple** (still, or a steady follow).
2. If the camera must move, **move it at a speed that keeps the action's critical phase in frame**.
3. **Do not change the camera's motion at the moment of contact** unless that is the design.
4. **Keep the subject's scale consistent** if the camera tracks (the Shot Size knowledge base covers framing).

---

# 15. ACTION DESIGN FOR AI IMAGE AND VIDEO GENERATION

**Caution:** Model behavior varies. Statements about model tendencies are common observations to guard against, not guarantees about any particular model.

## 15.1 What to Specify

| # | Item | Why | Example phrase |
|---|---|---|---|
| 1 | **Subject identity and starting state** | Prevents identity change; fixes the starting pose | "A woman in a gray coat, seated at a table, hands on her lap" |
| 2 | **Intended action and purpose** | Gives the movement a goal | "She checks whether the door is locked" |
| 3 | **Trigger or initiating event** | Prevents unmotivated movement | "After a faint sound from the room" |
| 4 | **Starting posture and orientation** | Constrains the path | "Standing, facing the door, about one meter away" |
| 5 | **Participating body parts or objects** | Limits what must move | "Her right hand and the door handle" |
| 6 | **Direction and path** | Prevents wrong direction | "Her hand rises toward the handle from the right side" |
| 7 | **Speed and acceleration** | Controls readability | "Slowly, over about two seconds, decelerating as it nears the handle" |
| 8 | **Action phases and timing** | Prevents teleportation | "First the head turns; then the hand rises; then the fingers close" |
| 9 | **Contact points and interaction order** | Ensures contact before effect | "Fingers touch the handle, then the handle turns" |
| 10 | **Weight transfer and balance** | Adds plausibility | "Her weight shifts onto the rear foot" |
| 11 | **Secondary motion** | Adds realism | "Her coat sleeve settles after her hand stops" |
| 12 | **Environmental response** | Shows effect | "The door moves inward slightly" |
| 13 | **Final posture and resulting state** | Fixes the end | "Her hand lowers; she stands still, facing the door" |
| 14 | **Camera behavior, separately** | Avoids confusion | "Camera locked-off" |
| 15 | **Elements that must remain unchanged** | Prevents drift | "Same coat, door, and hand size throughout" |

## 15.2 Action Prompt Template

```
SUBJECT:    [identity, clothing, starting posture and orientation]
ACTION:     [purpose; trigger]
PHASES:     1) [..] 2) [..] 3) [..] (use "then" for order; add approximate durations)
PATH:       [start landmark → waypoints → end landmark; frame of reference stated]
CONTACT:    [what touches what, in order]
WEIGHT:     [balance, effort, load]
SECONDARY:  [hair, fabric, objects, environment]
END STATE:  [final posture, object states]
CAMERA:     [separate statement]
UNCHANGED:  [identity, costume, object size, position of others]
```

## 15.3 Why Action Verbs Alone Are Insufficient

| Verb | What it leaves undefined |
|---|---|
| **"Grabs"** | Path, hand shape, contact timing, grip, the object's response |
| **"Runs"** | Speed, gait, direction, start and stop, surface |
| **"Turns"** | Which way, how far, in what order (head, shoulders, hips), where the feet go |
| **"Opens the door"** | Hinge side, swing direction, handle contact, body position |
| **"Falls"** | Trigger, direction, recovery, contact |
| **"Throws"** | Wind-up, direction, release point, follow-through |

**Replacing vague instructions:**

| Vague | Replace with observable movement |
|---|---|
| **"Moves naturally"** | "Walks at a steady pace with arms swinging opposite to the legs; each foot plants flat." |
| **"Runs dramatically"** | "Runs with a forward lean, elbows bent and driving, a visible moment in each stride when both feet leave the ground." |
| **"Grabs the object"** | "Her right hand opens, fingers wrap around the handle of the cup, grip closes, then the cup lifts." |
| **"Looks scared"** | "Her steps shorten; her head turns repeatedly toward the corridor; her shoulders rise; her breathing is fast and shallow." |
| **"Fights"** | "He steps back as the other man's arm swings past; he raises his forearm to deflect the next swing; he steps in with his shoulder and pushes the other man's arm aside." |

## 15.4 Preventing Common Generation Failures

| Failure | Typical cause | Prevention instruction |
|---|---|---|
| **Teleportation between poses** | The action's path not described | Describe waypoints and continuous travel |
| **Missing intermediate movement** | Only start and end given | Give phases with "then" |
| **Limbs changing shape or length** | Instability | Simplify the action; restate proportions; keep limbs visible |
| **Incorrect joint articulation** | Unspecified joints | Specify the joint motion ("elbow bends about 90°") |
| **Floating feet and foot sliding** | No ground-contact cues | "Each foot plants flat and stays fixed as the body passes over it" |
| **Hands passing through objects** | No contact described | "Fingers touch the handle before the handle moves" |
| **Objects changing size, identity, or position** | Weak object specification | Name the object with distinguishing features; state where it starts and ends |
| **Actions in the wrong order** | Order not stated | Use "first... then... finally" |
| **Premature or delayed contact** | Timing unspecified | State the contact moment relative to other phases |
| **Inconsistent momentum** | No speed profile | State accelerate, steady, decelerate |
| **Unmotivated reactions** | No trigger | State the trigger and that the reaction follows it |
| **Subjects moving when they should remain still** | Stillness unspecified | "Stands still, only breathing" |
| **Camera movement mistaken for subject movement** | Both unspecified | Use SUBJECT MOTION and CAMERA lines |
| **Identity, clothing, or anatomy changing** | Resampling | Restate identity; shorten the action; use a reference frame |
| **Unrequested cuts or time jumps** | Model editing behavior | "One continuous take; no cuts; no time jump" |

## 15.5 Writing Principles for Action Prompts

1. **Use present-tense, observable verbs** (touch, rotate, lift, plant).
2. **Order the phases in the order they occur,** with "then."
3. **Give approximate durations** for key phases.
4. **State direction in a named frame of reference.**
5. **State what does not move** when it matters.
6. **Describe presence, not absence** ("stands still" rather than "does not run").
7. **Keep to one primary action** where possible (Section 16).
8. **Separate camera and subject.**
9. **Avoid synonyms and stacked adjectives.**
10. **Restate the "must remain unchanged" list in every clip.**

## 15.6 Before-and-After Examples

Each example is focused on action and motion, not a complete scene prompt.

### Example 1 — Walking (whole-body)
- **Before:** "A woman walks naturally."
- **After:** "A woman walks at a steady pace of about two steps per second along the corridor toward the window; each foot plants flat and lifts in turn; her arms swing gently opposite to her legs; her head stays level."
- **Why it works:** The gait, rhythm, foot contact, and arm coordination are defined.

### Example 2 — Running and stopping (whole-body, defined start and end)
- **Before:** "He runs dramatically and stops."
- **After:** "He sprints down the alley with a forward lean and bent, driving arms; after about three seconds he slows over three shortened steps, plants his lead foot, leans back slightly, and stands still facing the end of the alley, breathing heavily."
- **Why it works:** Start state, speed profile, braking, and the final state are stated.

### Example 3 — Standing up (whole-body)
- **Before:** "She gets up from the chair."
- **After:** "Seated at the table, she moves her feet under her knees, leans her torso forward, pushes up with her right hand on the table, straightens her legs over about two seconds, and stands upright with her weight centered; the chair stays in place."
- **Why it works:** The forward lean, the push, the timing, and the chair's stability are specified.

### Example 4 — Turning (whole-body)
- **Before:** "He turns around."
- **After:** "He turns to his left: his head turns first, then his shoulders, then his hips, pivoting on his left foot until he faces the doorway; his right foot steps to rebalance."
- **Why it works:** Direction, order of body parts, and foot behavior are defined.

### Example 5 — A gesture
- **Before:** "She waves."
- **After:** "She raises her right forearm to shoulder height with the elbow bent about 90°, her palm facing outward, and swings the hand left and right about three times over one second; her left arm stays at her side."
- **Why it works:** The joint, amplitude, count, timing, and the other arm's state are defined.

### Example 6 — A head and gaze movement
- **Before:** "She looks at the door nervously."
- **After:** "Her eyes shift to the door first; then her head turns about 45° to the right over half a second; she holds still for a beat; her gaze returns to the table."
- **Why it works:** "Nervously" is replaced by order, timing, and a hold.

### Example 7 — Object interaction (cup)
- **Before:** "She grabs the cup."
- **After:** "Her right hand opens as it approaches the white mug, her fingers wrap around the mug's body, her grip closes, and then the mug lifts straight up about 20 cm and stays upright."
- **Why it works:** The pre-shaping, contact order, and the object's state are defined.

### Example 8 — Object interaction (door)
- **Before:** "He opens the door."
- **After:** "He grips the knob with his right hand, turns it clockwise until the latch releases, then pushes the door inward; the door swings away from him on hinges at its left edge through about 90°, and he steps through."
- **Why it works:** The latch-before-motion order, hinge side, and direction are specified.

### Example 9 — Object interaction (handing an object)
- **Before:** "He gives her the folder."
- **After:** "He holds out the blue folder with both hands; she reaches with both hands and grips the sides; for one beat both pairs of hands hold it; he releases and lowers his hands; she draws it toward her chest."
- **Why it works:** The shared-grip beat prevents teleportation and ownership errors.

### Example 10 — Multiple subjects
- **Before:** "Two people dance together."
- **After:** "The taller man in the black jacket (on the left) and the woman in the green dress (on the right) hold hands and step sideways to the right together, then the man turns the woman under his raised right arm; they keep their sides and do not change places; their feet plant and lift in alternation."
- **Why it works:** Subjects are labeled, sides are fixed, and the order of actions is defined.

### Example 11 — Environmental motion
- **Before:** "Wind blows everything."
- **After:** "A light wind from the left moves the tall grass to the right in a steady ripple; the ends of her scarf lift toward the right; her hair moves slightly to the right; the tree trunk stays still."
- **Why it works:** One wind direction, the affected items, and the still elements are defined.

### Example 12 — Secondary motion
- **Before:** "Her hair flows beautifully as she turns."
- **After:** "She turns her head to the right over half a second; her hair swings to the right a moment after the head, overshoots slightly, then settles over about half a second."
- **Why it works:** The lag, overshoot, and settling replace "flows beautifully."

### Example 13 — Movement with clearly defined start and end states
- **Before:** "She puts the book on the shelf."
- **After:** "Start: she stands facing the shelf holding the book in both hands at chest height. She raises the book to the middle shelf, slides it between two other books until its spine aligns with them, releases it, and lowers both hands to her sides. End: the book stands on the shelf; her hands are at her sides; she is facing the shelf."
- **Why it works:** The start and end states are fixed; the path and release are defined.

### Example 14 — Stillness and a single small movement
- **Before:** "He is still but tense."
- **After:** "He stands still with his eyes on the door; only his chest rises and falls with shallow breaths; after two seconds his right hand tightens on the strap of his bag, then relaxes."
- **Why it works:** The stillness is specified as presence, and the single movement is defined.

### Example 15 — Resolving contradictory instructions
- **Before:** "She stands completely still while running to the door."
- **After (option A, still):** "She stands still facing the door, breathing slowly."
- **After (option B, running):** "She runs to the door and stops with her hand on the handle."
- **Why it works:** Contradictory movement states are replaced by one clear state.

### Example 16 — Camera and subject separated
- **Before:** "The camera moves closer as he runs."
- **After:** "SUBJECT MOTION: He runs straight toward the camera at a steady pace. CAMERA: Locked-off, no zoom."
- **Why it works:** The movement is assigned to the subject; the camera is defined as still.

---
# 16. ACTION COMPLEXITY AND GENERATION RELIABILITY

**Caution:** The risk levels below are practical tendencies, not guarantees. Reliability varies by model, version, and prompt. Use them to prioritize, then verify on the output.

## 16.1 How Complexity Affects Reliability

| Factor | Lower risk | Higher risk | Why |
|---|---|---|---|
| **Number of simultaneous actions** | One simple action | Multiple simultaneous actions | Each additional action adds more things that can drift or conflict |
| **Number of subjects** | One subject | Coordinated multi-subject movement | Interactions, overlap, and identity swaps multiply |
| **Duration** | Short action (a few seconds) | Long sequences | Errors accumulate; identity and scale drift over time |
| **Contact** | Clear, visible contact | Hidden or brief contact | Contact is where plausibility is judged; hidden contact invites errors |
| **Repetition** | One-time movement | Repeated movements (many steps, many taps) | Counting and rhythm drift |
| **Environment** | Uncluttered | Cluttered or complex | Objects and edges interfere with limbs and paths |
| **Path** | Simple path | Direction changes, turns, interactions | Each change adds a possible error |
| **Body parts in view** | Limbs clearly visible | Many overlapping limbs (fighting, tangled bodies) | Limb confusion and merging |
| **Fine detail** | Large gestures | Fine finger work | Small parts are often rendered inconsistently |

## 16.2 Simplifying While Preserving Narrative Meaning

**Method:**

1. **Identify the story-critical beat:** the single moment or change that the story needs (for example, "she realizes the door is unlocked").
2. **List everything else** in the action (walking, looking, reaching, speaking).
3. **Classify each item** as *essential*, *supporting*, or *decorative*.
4. **Remove decorative items.**
5. **Imply supporting items** (a glance instead of a head turn plus a step; a sound instead of a visible cause).
6. **Make the essential beat clear:** visible contact, a clear trigger, an unambiguous end state.
7. **Check the meaning** after simplifying: does the viewer still understand the beat?

**Simplification techniques:**

| Technique | Example |
|---|---|
| **Reduce subjects** | One person handles the object; the other is out of frame or still |
| **Reduce simultaneous actions** | The character stands still while the camera shows the object |
| **Shorten duration** | Show the key three seconds, not the whole minute |
| **Make contact visible** | Place the hand in clear view, not behind the body |
| **Simplify the environment** | Plain floor, uncluttered walls |
| **Simplify the path** | One straight path or one turn |
| **Use implication** | Show the hand reaching and cut to the result |
| **Use a larger gesture** | Replace finger detail with a hand-level movement |

## 16.3 Identifying and Prioritizing the Highest-Risk Requirements

**Risk register method:**

| Step | Action |
|---|---|
| **1** | List every movement requirement in the action (each phase, contact, path, and constraint). |
| **2** | Rate **importance** (1 = decorative, 2 = supporting, 3 = story-critical). |
| **3** | Rate **failure risk** using Section 16.1 (1 = low, 2 = medium, 3 = high). |
| **4** | Compute **priority = importance × risk.** |
| **5** | For the highest-priority items, **simplify, restate in detail, or isolate** them in a separate clip. |
| **6** | For low-importance, high-risk items, **remove them.** |
| **7** | For high-importance, low-risk items, **keep them but do not over-specify.** |

**Example:**

| Requirement | Importance | Risk | Priority | Decision |
|---|---|---|---|---|
| Fingers close on the handle (contact visible) | 3 | 2 | 6 | Specify in detail |
| She rolls up her sleeve as she walks | 1 | 3 | 3 | Remove |
| Door swings inward on the left hinge | 3 | 2 | 6 | Specify hinge side |
| Two people pass each other in the corridor | 2 | 3 | 6 | Simplify: one person only |
| Dust lifts at her steps | 1 | 2 | 2 | Optional |

## 16.4 Dividing an Action: Phases and Shots vs. a Continuous Take

**Do not assume that every complex action must be split.** Both approaches have trade-offs.

| | Continuous take | Divided into phases or separate shots |
|---|---|---|
| **Advantages** | Natural flow; unbroken causality; preserves continuity of space and identity within the clip | Each segment is simpler; failures can be corrected locally; the most difficult moments can be isolated |
| **Disadvantages** | Errors anywhere spoil the whole clip; long durations increase drift | Continuity must be matched across cuts; flow may be interrupted; extra clips |
| **Prefer when** | The continuity of the movement is the point (a single unbroken movement, a physical gag, a one-take feel); the action is simple enough to be reliable | The action has several story-critical beats; any phase has high risk (contact, multi-subject); the duration is long |
| **How to manage risk** | Keep the action short; simplify; state the continuity list | Use start/end state handoff (Section 13); match direction, hand placement, and phase at each cut |

**Decision guideline:**

1. If the continuity of the movement *is* the story, try a continuous take at the shortest workable duration.
2. If the action has more than one high-risk beat, divide so that each clip has one.
3. If a continuous take fails repeatedly on the same phase, isolate that phase in its own clip and cut on action.
4. When dividing, preserve the **start and end states** precisely.

---

# 17. ACTION AND MOTION FAILURE DIAGNOSIS

## 17.1 Troubleshooting Table

| # | Intended action | Observed result | Likely cause | Evidence to inspect | Corrective instruction | Possible side effect |
|---|---|---|---|---|---|---|
| 1 | A complete action | **Action is incomplete:** it stops before the end state. | Duration too short for the phases; end state not stated. | Compare the final frame with the specified end state. | State the end state and allow more time: "The action ends with the cup resting on the table, her hand released." | A longer duration may increase drift. |
| 2 | Correct timing | **Action begins or ends at the wrong time.** | No trigger or timing stated; the model starts at frame one or never finishes. | When movement begins relative to the clip start and the trigger. | "Stands still for the first second; then begins to reach." Specify the end hold. | May add stillness at the beginning. |
| 3 | Correct direction | **Movement direction is wrong.** | Ambiguous frame of reference. | Direction on screen vs. the intended direction. | State the reference: "Walks toward the screen's right edge, her left shoulder toward the camera." | Direction may reverse in the next clip if not restated. |
| 4 | Stable identity | **Subject changes identity during movement.** | Long duration; large pose change; identity not restated. | Face, hair, and clothing across frames. | Restate identity; shorten the action; use a reference image; reduce occlusion. | Simplification may reduce movement range. |
| 5 | Stable proportions | **Body proportions change.** | Instability during large movement; changing perspective. | Limb length and head-to-body ratio across frames. | "Her proportions remain constant." Reduce movement amplitude; avoid extreme foreshortening. | Less dramatic movement. |
| 6 | Plausible joints | **Joint motion is anatomically implausible.** | Joint motion unspecified; complex pose. | Direction of elbow, knee, wrist, and finger bends. | Specify joint action: "The elbow bends inward about 90°; the knee bends forward." Simplify the pose. | May reduce fluidity. |
| 7 | Planted steps | **Feet slide across the floor.** | No ground-contact description; mismatch between travel speed and step rhythm. | Foot position relative to the floor between steps. | "Each foot plants flat and stays fixed while the body passes over it; step rhythm matches the walking speed." | Steps may become mechanical. |
| 8 | Stable balance | **Subject floats or loses balance.** | Missing weight transfer; the center of mass not over support. | Weight placement; support under the body. | "Weight shifts onto the left foot before the right foot lifts." Add a support or counterbalance. | May stiffen the movement. |
| 9 | Contact visible | **Object interaction lacks contact.** | Contact not described; hidden contact. | The frame where hand and object should touch. | "Fingers wrap around the handle before the cup moves." Show the hand in clear view. | The shot may need reframing. |
| 10 | Force before motion | **Object moves before force is applied.** | Phase order not stated. | Frames before contact. | "The cup stays still until her fingers close on it; then it lifts." | May produce a delay at contact. |
| 11 | Reaction after trigger | **Reaction occurs before the triggering event.** | Trigger not stated or the order reversed. | The order of the stimulus and the response. | "After the glass breaks, she flinches." State a short delay. | The reaction may become late. |
| 12 | Right speed | **Movement is too fast or too slow.** | Speed not stated; model default. | The duration of key phases. | State approximate duration: "reaches over about two seconds." | Adjusting speed may change other phases. |
| 13 | Weight and momentum | **Action lacks weight or momentum.** | No load cues; no preparation or follow-through. | Body lean, effort, object response. | Add "leans back, braces, slower steps" and follow-through: "the crate keeps sliding a short distance." | May look heavy if overdone. |
| 14 | Compatible secondary motion | **Secondary motion contradicts the primary action.** | Wind or force direction unspecified; secondary elements over-specified. | The direction and timing of hair, cloth, and objects. | State one force direction and lag: "Her scarf trails behind her." | Fewer secondary effects. |
| 15 | Correct order | **Multiple subjects act in the wrong order.** | Ambiguous labels; no triggers. | Which subject moves first, and why. | Use the Action Ownership Table (Section 9.4); label each subject and trigger. | More text in the prompt. |
| 16 | Continuity across shots | **Action continuity breaks across shots.** | Start state of the next clip not matched. | Hand position, object state, direction, and phase at the cut. | Repeat the end state as the start state; use the last frame as a reference. | The clips may feel static. |
| 17 | Separate camera and subject | **Camera and subject movement are confused.** | Ambiguous wording. | Whether the background or the subject moves. | Use "SUBJECT MOTION" and "CAMERA" lines; "camera locked-off." | A locked camera may lose dynamism. |
| 18 | Clear communication | **The output looks active but fails to communicate the intended action.** | Too much motion; no clear trigger, contact, or consequence. | Whether a viewer can name the action. | Reduce secondary activity; emphasize the trigger, contact, and consequence. | Less visual activity. |
| 19 | Achievable in duration | **The action is too complex for the requested duration.** | Too many phases or subjects for the time. | The number of phases per second. | Simplify (Section 16) or split into phases. | More clips to match. |

## 17.2 Diagnostic Order

**Principle:** Diagnose from what defines the action toward what decorates it. Change **one variable at a time** and re-evaluate.

| Order | Layer | Question | Why first |
|---|---|---|---|
| **1** | **Recognition** | Can a viewer name the intended action? | If not, nothing else matters. |
| **2** | **Start and end states** | Do the start and end match the specification? | Defines the action's boundaries. |
| **3** | **Phases and order** | Are all required phases present and in order? | Missing or reordered phases cause most failures. |
| **4** | **Direction and path** | Are direction, path, and waypoints right? | A wrong direction invalidates the rest. |
| **5** | **Contact and causality** | Does force follow contact, and effect follow cause? | Contact is where plausibility is judged. |
| **6** | **Timing and speed** | Are durations and the speed profile right? | Timing affects readability. |
| **7** | **Body mechanics** | Are balance, foot contact, and joints plausible? | Reveals artificial movement. |
| **8** | **Identity and continuity** | Are identity, proportions, and objects stable? | Distinguishes drift from design errors. |
| **9** | **Secondary motion and environment** | Do secondary effects agree with the primary action? | Adds realism, not definition. |
| **10** | **Camera vs. subject** | Is the camera behaving as specified? | Prevents misattributing camera motion. |
| **11** | **Prompt conflicts and complexity** | Are there contradictions or too many requirements? | Reduces failures at the source. |

## 17.3 Correct the Smallest Relevant Variable First

**Do not rewrite the entire prompt after every failure.** A full rewrite changes many variables at once; the cause of improvement or regression becomes unknown.

| Symptom | Smallest relevant change |
|---|---|
| The hand passes through the cup | Add one sentence: "Fingers wrap around the cup before it lifts." |
| Feet slide | Add: "Each foot plants flat and stays fixed." |
| Camera drifts | Add: "Camera locked-off, no zoom." |
| Wrong direction | Restate direction with a frame of reference. |
| Action too fast | Add a duration: "over about two seconds." |
| Identity drifts | Restate the identity and reduce movement amplitude |

**Procedure:**

1. Identify the layer from the diagnostic order.
2. Change one phrase or one parameter.
3. Re-evaluate against the acceptance criteria.
4. **Regression check:** did something else get worse?
5. If the symptom persists, move to the next layer or simplify (Section 16).

---

# 18. PRACTICAL CASE STUDIES

Each case follows the same structure: **A.** narrative purpose; **B.** starting state; **C.** phases; **D.** direction, timing, and interactions; **E.** balance, weight, momentum, and secondary motion; **F.** ending state; **G.** failure modes; **H.** verification criteria; **I.** targeted corrections for a flawed result.

---

## Case 1 — A Character Cautiously Approaches and Opens a Door

- **A. Narrative purpose:** Show that the character suspects someone is inside and is trying not to be heard.
- **B. Starting state:** A man stands in a corridor about three steps from a closed door, facing it, right hand at his side. The door hinges on the left and opens inward.
- **C. Phases:** (1) A faint sound; his head tilts toward it. (2) He steps forward slowly three times. (3) He stops, shifts weight to his rear foot, and raises his right hand. (4) Fingers touch and close on the knob. (5) He turns the knob slowly until the latch releases. (6) He pushes the door inward a few centimeters. (7) He holds and listens. (8) He pushes it open.
- **D. Direction, timing, interactions:** He moves straight toward the door at about half normal walking speed (roughly one step per second). The hand rises over about one second. The knob turns clockwise over about two seconds. The latch releases *before* the door moves. The door swings on its left hinge.
- **E. Balance, weight, momentum, secondary motion:** Short steps with the center of mass low; his weight stays near the rear foot as he reaches. The door has slight resistance; it swings and stops by his push. His sleeve settles after his hand stops.
- **F. Ending state:** The door is open about 30°; his hand rests on its edge; he is leaning slightly forward, still listening.
- **G. Failure modes:** The door opening before the hand turns the knob; the hand passing through the knob; the door swinging outward; steps that slide; the hand changing size.
- **H. Verification criteria:** (1) The head turns before he steps. (2) The fingers touch the knob before it turns. (3) The latch releases before the door moves. (4) The door swings inward on the left hinge. (5) There is a visible hold before the final push.
- **I. Corrective instructions for a flawed result:** *Flawed result:* the door swings open while his hand is still approaching. *Targeted corrections:* (1) Add "The door stays closed until his fingers close on the knob and turn it." (2) If it persists, add "Latch releases with a small click, then the door moves." (3) If the hand still passes through, add "his fingers wrap around the knob and the knob turns with his wrist."

---

## Case 2 — A Character Picks Up and Examines a Small Object

- **A. Narrative purpose:** Show curiosity about a clue (a small brass key) and a decision to take it.
- **B. Starting state:** A woman stands at a table; the key lies on the table about 30 cm from her right hand; her left hand rests on the table's edge.
- **C. Phases:** (1) Gaze lands on the key. (2) She leans slightly forward. (3) Her right hand approaches, thumb and index finger shaping a pinch. (4) Fingertips contact the key. (5) She lifts it about 15 cm. (6) She turns it over once, looking at both sides. (7) She holds it up to the light. (8) She lowers it into her palm.
- **D. Direction, timing, interactions:** The reach takes about one second; the lift about half a second; the inspection about three seconds. The key stays between thumb and index finger. The wrist rotates about 180° to turn the key.
- **E. Balance, weight, momentum, secondary motion:** The key is light; the pinch is gentle; her torso leans over the table, supported by her left hand. Her sleeve slides slightly down her forearm.
- **F. Ending state:** The key rests in her open right palm at chest height; her gaze on the key.
- **G. Failure modes:** The key changing size or shape; the pinch with no contact; the key floating; fingers merging; the grip changing during the turn.
- **H. Verification criteria:** (1) The pinch contacts the key before it lifts. (2) The key stays the same size and shape. (3) The wrist rotates to show both sides. (4) The key ends in her palm.
- **I. Corrective instructions for a flawed result:** *Flawed result:* the key appears in the hand without a visible grasp. *Targeted corrections:* (1) "Her thumb and index finger touch the key's sides, close, and lift it." (2) "The key stays on the table until the pinch closes." (3) If the key changes shape, add "a small brass key with a round head and two teeth; same size throughout."

---

## Case 3 — A Character Stands Up From a Seated Position and Begins Walking

- **A. Narrative purpose:** Show the character deciding to leave after hearing news.
- **B. Starting state:** A man sits on a chair at a table, torso upright, feet flat, hands on the table, facing forward. A doorway is to his right.
- **C. Phases:** (1) He looks toward the doorway. (2) He draws his feet back under his knees. (3) He leans his torso forward and pushes up with both hands. (4) His hips lift and his legs extend. (5) He stands, weight over both feet. (6) He turns his head, then shoulders, to the right. (7) He takes the first step with a short stride. (8) He settles into a walk.
- **D. Direction, timing, interactions:** The rise takes about two seconds. The turn takes about one second. The first step is shorter than later steps. He walks to the right toward the doorway at a normal pace (about two steps per second).
- **E. Balance, weight, momentum, secondary motion:** The forward lean moves the center of mass over the feet before the rise. His shirt shifts as he stands. The chair slides back slightly under his push, then stops.
- **F. Ending state:** He is walking steadily toward the doorway; his hands are at his sides; the chair is empty and slightly turned.
- **G. Failure modes:** Rising straight up with no lean; feet far in front; the chair moving without a cause; starting at full walking speed; sliding feet.
- **H. Verification criteria:** (1) Torso leans before hips rise. (2) Hands contact the table. (3) The head turns before the feet. (4) The first step is shorter. (5) Feet plant.
- **I. Corrective instructions for a flawed result:** *Flawed result:* he rises vertically and glides to the door. *Targeted corrections:* (1) "He leans his torso forward before his hips rise." (2) "Each foot plants flat and stays fixed as his body passes over it." (3) "The first step is short, then the pace builds."

---

## Case 4 — A Character Runs, Stops, and Looks Toward an Unexpected Sound

- **A. Narrative purpose:** Convey urgency interrupted by a threatening or surprising event.
- **B. Starting state:** A woman in sneakers stands at the end of a paved alley, facing down it, preparing to run.
- **C. Phases:** (1) She crouches slightly and leans forward. (2) She accelerates over three steps. (3) She runs at speed for about three seconds. (4) A sound occurs to her left (a metallic clang). (5) She brakes over three shortened steps, planting her lead foot. (6) She stops with her weight on her heels, arms out for balance. (7) Her head turns toward the sound (eyes first, then the head). (8) She holds still, breathing hard.
- **D. Direction, timing, interactions:** She runs toward the camera-left end of the alley (state frame of reference). The sound occurs on her left; the reaction begins after about 0.2–0.3 seconds. The brake takes about one second. The head turn takes about half a second.
- **E. Balance, weight, momentum, secondary motion:** The forward lean at speed; backward lean during braking; momentum carries her forward a step even after the lead foot plants. Her hair continues forward briefly and settles; her jacket swings; her chest rises and falls rapidly.
- **F. Ending state:** She stands still, facing the sound, knees slightly bent, hands lifted, breathing hard.
- **G. Failure modes:** Reaction before the sound; instant stop with no braking; feet sliding; the head turning before the eyes; secondary motion that doesn't continue after the stop.
- **H. Verification criteria:** (1) The sound occurs before the reaction. (2) A flight phase is visible in the run. (3) Shortened braking steps. (4) Eyes lead the head turn. (5) Hair and jacket settle after the stop.
- **I. Corrective instructions for a flawed result:** *Flawed result:* she stops instantly at the sound, and her head turns first. *Targeted corrections:* (1) "After the clang, she brakes over three shortened steps." (2) "Her eyes shift to the left, then her head turns." (3) "Her hair swings forward after she stops and settles over half a second."

---

## Case 5 — Two Characters Exchange an Object

- **A. Narrative purpose:** Show trust between two characters as one passes the other a sealed envelope.
- **B. Starting state:** Subject A, a taller woman in a red coat, stands on the left holding a white envelope in her right hand at waist height. Subject B, a shorter man in a gray jacket, stands on the right, arms at his sides, an arm's length away. They face each other.
- **C. Phases:** (1) A glances at B. (2) A extends the envelope toward B. (3) B's gaze moves to the envelope. (4) B reaches with his right hand. (5) B's fingers touch the envelope's lower edge while A still holds the upper edge. (6) A releases. (7) B draws the envelope toward his chest. (8) Both lower their gaze, then look at each other.
- **D. Direction, timing, interactions:** A's arm extends over about one second; B's hand starts about half a second later. Both hold the envelope for one beat. A releases after B's grip closes. They keep their sides and do not step toward each other.
- **E. Balance, weight, momentum, secondary motion:** The envelope is light; the transfer is gentle. A's coat sleeve moves slightly; the envelope flexes slightly when held by both.
- **F. Ending state:** B holds the envelope against his chest; A's hands are lowered; they remain on their original sides.
- **G. Failure modes:** The envelope appearing in B's hand with no pass; hands merging; the characters swapping sides; the envelope changing size or color; A's action attributed to B.
- **H. Verification criteria:** (1) Both hands touch the envelope for at least one beat. (2) A releases after B's grip closes. (3) The envelope stays the same size and color. (4) Characters stay on their sides. (5) Each action is performed by the correct character.
- **I. Corrective instructions for a flawed result:** *Flawed result:* the envelope jumps into B's hand and A's hand disappears. *Targeted corrections:* (1) "For one beat, A's right hand and B's right hand both hold the envelope." (2) "A releases only after B's fingers close." (3) "A, the taller woman in the red coat on the left, performs the extending; B, the shorter man in the gray jacket on the right, performs the receiving."

---

## Case 6 — A Character Loses Balance and Recovers

- **A. Narrative purpose:** Show that the floor is slippery and that the character is resilient (a light comic or tense beat).
- **B. Starting state:** A man walks at a normal pace across a wet tiled floor, carrying a tote bag on his left shoulder. A railing is on his right.
- **C. Phases:** (1) Normal steps. (2) His right foot slides outward on a wet patch. (3) His torso pitches slightly backward; his arms lift. (4) His left foot takes a quick wide step to catch his weight. (5) His right hand grabs the railing. (6) He pulls himself upright. (7) He exhales and looks down at the floor.
- **D. Direction, timing, interactions:** The slip lasts about 0.3 seconds; the catching step follows within about 0.3 seconds; the grab occurs about half a second later. The sliding foot moves outward and forward.
- **E. Balance, weight, momentum, secondary motion:** His center of mass leaves the base of support, so he extends his arms and takes a wide step. The tote bag swings out and returns. Water splashes slightly under the sliding foot.
- **F. Ending state:** He stands upright, right hand on the railing, left foot planted, bag settling.
- **G. Failure modes:** No trigger for the slip; falling like a plank; no reflexive arm or step; instant recovery; bag not responding.
- **H. Verification criteria:** (1) The wet patch triggers the slip. (2) The sliding foot is visible. (3) The arms and a catching step appear. (4) The hand grips the railing. (5) The bag swings and settles.
- **I. Corrective instructions for a flawed result:** *Flawed result:* he stumbles with no cause and stands straight up. *Targeted corrections:* (1) "His right foot slides on a wet patch." (2) "He takes one quick wide step with his left foot and grips the railing with his right hand." (3) "The tote bag swings outward and returns."

---

## Case 7 — An Animal Moves Through an Environment and Reacts to a Stimulus

- **A. Narrative purpose:** Show a wary deer in a meadow noticing danger and leaving.
- **B. Starting state:** A deer stands in a meadow, head lowered, grazing; its tail is down; tall grass reaches its knees; a tree line is on the right.
- **C. Phases:** (1) The deer grazes with small head movements. (2) A twig snaps off-screen on the right. (3) Its ears rotate toward the sound. (4) Its head lifts. (5) It freezes with its body tense. (6) Its tail lifts. (7) It turns its body away from the sound. (8) It bounds away to the left in a few jumps.
- **D. Direction, timing, interactions:** The reaction begins within about a fraction of a second of the sound. The freeze lasts about two seconds. The bounds travel to the left (away from the sound). Its legs push against the ground; its hooves contact the grass.
- **E. Balance, weight, momentum, secondary motion:** The deer's weight shifts to the hind legs for the turn; the bounds have flight phases; the grass parts around its legs and springs back; its ears move independently.
- **F. Ending state:** The deer disappears to the left; the grass shakes and settles.
- **G. Failure modes:** Human-like movement; limbs changing length; the grass not responding; hooves sliding; the reaction before the sound.
- **H. Verification criteria:** (1) The sound precedes the ear and head response. (2) The animal freezes before running. (3) Footfalls show a plausible gait. (4) The grass responds. (5) The direction is away from the sound.
- **I. Corrective instructions for a flawed result:** *Flawed result:* the deer slides sideways without bounding, and the ears do not move. *Targeted corrections:* (1) "The left ear rotates toward the sound, then the head lifts." (2) "The deer bounds in three jumps, all four hooves leaving the ground in each." (3) "The grass parts around its legs and springs back."

---
# 19. ACTION-DESIGN WORKSHEET

## 19.1 Blank Worksheet (Copy and Complete)

Fields marked ★ are **essential for AI-generated video** (see 19.3).

```
ACTION-DESIGN WORKSHEET
─────────────────────────────────────────────────────────────────
 1.  Narrative purpose:
 2.★ Subject identity (name/label, distinguishing clothing, proportions):
 3.★ Initial position and posture:
 4.★ Initial orientation (facing direction; frame of reference):
 5.★ Intended goal or action:
 6.★ Trigger or initiating event (and timing):
 7.★ Participating body parts or objects:
 8.★ Action phases (preparation → ... → resulting state):
 9.★ Movement direction and path (start → waypoints → end; frame of reference):
10.★ Speed and timing (approximate durations per phase; overall duration):
11.  Force, resistance, or weight considerations:
12.★ Contact points and interaction sequence:
13.  Balance and support requirements:
14.  Secondary motion:
15.  Environmental response:
16.★ Camera movement constraints (stated separately):
17.  Required continuity (across shots/clips):
18.★ Final position and state:
19.★ Elements that must remain unchanged:
20.  Likely failure modes:
21.★ Acceptance criteria (3–6 observable statements):
─────────────────────────────────────────────────────────────────
```

## 19.2 How to Complete Each Field

| Field | How to complete it | How it influences later decisions |
|---|---|---|
| **1. Narrative purpose** | One sentence on what the action does for the story. | Decides which phases and details must be visible and which can be implied. |
| **2. Subject identity** | Label each subject distinctly; state clothing, relative size, and position. | Prevents identity swaps and ownership confusion (Section 9.5). |
| **3. Initial position and posture** | Where the subject is and how the body is arranged (seated, standing, hands where). | Constrains the first phase; prevents teleporting into the action. |
| **4. Initial orientation** | Facing direction in a stated frame of reference. | Determines turns, path, and visibility. |
| **5. Intended goal or action** | The goal in concrete terms ("to check whether the door is locked"). | Shapes preparation, speed, and gaze. |
| **6. Trigger** | The event that starts the action, and its timing relative to the clip start. | Prevents unmotivated movement and reactions before events. |
| **7. Participating parts or objects** | List the parts that move and the objects involved; mark the role of each. | Limits what must be specified; focuses on what the viewer must see. |
| **8. Action phases** | 3–6 phases with start and end states. | The skeleton of the specification; prevents missing intermediate movement. |
| **9. Direction and path** | Landmarks for start, waypoints, and end; frame of reference. | Prevents wrong direction and disconnected poses. |
| **10. Speed and timing** | Approximate durations; speed profile (accelerate, steady, decelerate). | Controls readability and weight. |
| **11. Force, resistance, weight** | Describe load, resistance, effort. | Informs body lean, bracing, and object response. |
| **12. Contact points and interaction sequence** | Order of touches and the response to each. | Ensures contact before effect; prevents hands passing through objects. |
| **13. Balance and support** | Where the weight is; what supports; what counterbalances. | Prevents floating and implausible lean. |
| **14. Secondary motion** | Which parts respond and how long they take to settle. | Adds realism; check for contradictions. |
| **15. Environmental response** | What the environment does in response (dust, door, water). | Shows consequence. |
| **16. Camera constraints** | State the camera's behavior separately (locked-off, following). | Prevents camera/subject confusion. |
| **17. Required continuity** | What must match across shots or clips (hand, object state, direction). | Defines handoff states (Section 13). |
| **18. Final position and state** | End posture, position, object states. | Defines the end; used for the next clip's start. |
| **19. Must remain unchanged** | Identity, costume, object size, positions of others. | Becomes the "unchanged" line in the prompt. |
| **20. Likely failure modes** | Top 3 risks, from Sections 16–17. | Guides pre-emptive wording and the diagnostic starting point. |
| **21. Acceptance criteria** | Observable statements tied to phases, contact, and end state. | Used for verification in Section 20. |

## 19.3 Fields Essential for AI-Generated Video

| Priority | Fields | Reason |
|---|---|---|
| **Essential (★)** | 2, 3, 4, 5, 6, 7, 8, 9, 10, 12, 16, 18, 19, 21 | These define what moves, how, in what order, in what space, with what constraints, and how it will be checked. Omitting them leaves large parts of the movement to model defaults. |
| **Recommended** | 1, 11, 13, 14, 15, 17, 20 | These add plausibility, meaning, and continuity. Include them when the action is heavy, interactive, multi-shot, or high-risk. |
| **Optional for simple actions** | 13, 14, 15 | A simple gesture may not need balance, secondary, or environmental detail. |

## 19.4 Completed Example

```
ACTION-DESIGN WORKSHEET — "The Courier Rings the Bell and Steps Back"
 1.  Purpose: Show that the courier expects the door to open soon and is wary.
 2.★ Subject: A young man in a yellow rain jacket and dark trousers, carrying a small
     brown parcel under his left arm.
 3.★ Initial position/posture: Standing on the doorstep, one step from the door,
     upright, right hand at his side.
 4.★ Initial orientation: Facing the door (screen-left to right: door is straight ahead).
 5.★ Goal: Press the doorbell and wait.
 6.★ Trigger: He glances at the number on the door, then decides to ring.
 7.★ Participating: Right index finger, right arm, eyes, head, feet; the doorbell button
     on the right side of the door frame; the parcel (held still).
 8.★ Phases: (1) Glance at the number. (2) Right arm rises to the bell. (3) Index finger
     touches and presses. (4) Finger releases. (5) He steps back one step. (6) He waits.
 9.★ Path: Hand rises from his side to the bell at shoulder height; he steps straight back
     (away from the door) one step.
10.★ Timing: Glance 0.5 s; reach 1 s; press 0.5 s; release 0.3 s; step back 0.7 s; hold 2 s.
11.  Weight: Parcel is light; arm stays pressed to his side.
12.★ Contact: Fingertip touches the button → button depresses → finger releases.
13.  Balance: Weight on both feet; shifts back on the step.
14.  Secondary: Jacket sleeve slides slightly; the raincoat hood settles after the step.
15.  Environment: Light rain continues; a small chime is heard (sound only).
16.★ Camera: Locked-off medium shot; no zoom; no drift.
17.  Continuity: Parcel under the left arm throughout; yellow jacket unchanged.
18.★ Final state: Standing one step back from the door, hands at his sides, parcel under
     his left arm, facing the door.
19.★ Unchanged: Jacket color, parcel size and position, door and bell position.
20.  Failure modes: Finger passing through the button; parcel changing position; camera drift.
21.★ Acceptance: (1) Finger touches the bell before it depresses. (2) He steps backward,
     not sideways. (3) The parcel stays under his left arm. (4) The camera does not move.
```

---

# 20. QUALITY CONTROL AND FINAL VERIFICATION

## 20.1 Purpose and Use

Use this checklist **before approving an action design** (pre-production) and **before approving a generated or filmed movement** (post-production). Evaluate the *movement on screen* against observable criteria, not against the description in the brief.

## 20.2 Verification Checklist

Rate each item **Pass**, **Minor issue**, or **Critical failure**.

| # | Question | Pass criterion | Severity if failed |
|---|---|---|---|
| 1 | **Is the intended action recognizable?** | A viewer without the brief can name the action. | **Critical** |
| 2 | **Does the movement have a clear beginning, progression, and outcome?** | The start state, the phases in order, and the end state are visible. | **Critical** if a required phase or the end is missing; **Minor** if a supporting phase is weak |
| 3 | **Are the movement path and direction correct?** | The path and direction match the specification in the stated frame of reference. | **Critical** if wrong; **Minor** if slightly off |
| 4 | **Are timing and speed appropriate?** | Durations match the specification within a reasonable range; the speed profile fits the purpose. | **Critical** if the action is unreadable; **Minor** otherwise |
| 5 | **Are anatomy, balance, and weight transfer plausible for the intended style?** | Joints bend in plausible directions; feet plant; the weight is supported; no floating. | **Critical** if implausible and not stylized; **Minor** if slightly stiff |
| 6 | **Are contacts and interactions visible and consistent?** | Contact is visible; hand and object do not intersect; grips are consistent. | **Critical** if contact is absent or hands pass through objects; **Minor** if contact is brief |
| 7 | **Do cause and effect occur in the correct order?** | The effect follows the cause; no reaction before the stimulus. | **Critical** |
| 8 | **Are secondary movements physically and narratively compatible?** | Secondary motion agrees with the primary action and conditions. | **Minor** (or **Critical** if it contradicts the story) |
| 9 | **Is subject identity and object continuity preserved?** | Face, clothing, proportions, and objects stay consistent. | **Critical** if identity or key objects change; **Minor** for small details |
| 10 | **Are subject movement and camera movement correctly separated?** | The camera behaves as specified; the subject's movement is not an artifact of camera motion. | **Critical** if confused or unintended camera movement alters the action |
| 11 | **Does the final state match the requested outcome?** | The final posture, position, and object states match. | **Critical** |
| 12 | **Does the movement serve the scene rather than merely add activity?** | Each visible movement supports the purpose or is clearly incidental. | **Minor** (or **Critical** if activity obscures the action) |
| 13 | **Are multi-subject actions attributed to the correct subjects in the correct order?** | Ownership and order match the Action Ownership Table. | **Critical** |
| 14 | **Is the movement style consistent?** | Naturalistic or stylized rules hold throughout. | **Minor** (or **Critical** if inconsistency changes meaning) |
| 15 | **Are acceptance criteria met?** | Every written criterion is verified. | **Critical** for each unmet core criterion |

## 20.3 Critical Failures vs. Optional Stylistic Refinements

### Critical failures (must be corrected before approval)

- The intended action is not recognizable, or the wrong action is shown.
- A required phase, the contact, or the end state is missing.
- The direction or path is wrong.
- Cause and effect are out of order (reaction before the stimulus; effect before contact).
- Hands pass through objects, or objects move without contact.
- Anatomy, balance, or weight is implausible and not deliberately stylized.
- Subject identity, proportions, or a key object changes.
- Subjects swap roles or act in the wrong order.
- Camera and subject movement are confused, or unintended camera movement changes the action.
- The action is unreadable (too fast, too small, hidden).

### Optional stylistic refinements (may remain a creative choice)

- Small variations in speed within the intended range.
- Slight differences in amplitude or posture that do not change meaning.
- Secondary motion that is slightly more or less than specified but physically compatible.
- A documented stylized exaggeration applied consistently.
- Minor background activity that does not compete.
- A different but equivalent grip or step pattern.

## 20.4 Approval, Revision, and Rejection Conditions

These thresholds are **practical guidelines**; adapt them to project needs.

| Decision | Conditions |
|---|---|
| **Approve** | No critical failures; all minor issues corrected or recorded as acceptable stylistic choices; acceptance criteria met. |
| **Revise** | One or two critical failures that trace to one or two layers in the diagnostic order and can be addressed by a targeted change (Section 17.3); or several minor issues that together reduce clarity. Make one change at a time and re-verify. |
| **Reject (return to the brief)** | The action is unrecognizable; identity is lost; three or more critical failures across different layers; or the same critical failure persists after several targeted revisions. Return to Sections 2 and 16: re-define the action, simplify it, or split it. |

## 20.5 Reviewer Procedure

1. **Watch once at normal speed** and write down the action you perceive.
2. **Compare with the intent:** does it match?
3. **Step through key moments** (start, each contact, end), checking positions, contact, and object states.
4. **Check the first and last frames** against the start and end states.
5. **Check phase order** against the specification.
6. **Check body mechanics:** feet, joints, balance.
7. **Check identity and object continuity** across the clip.
8. **Check the camera** (compare the first and last frames for drift).
9. **Decide:** approve, revise (one targeted change), or reject.

---

# 21. QUICK REFERENCE

## 21.1 Compact Action-Phase Reference

| Phase | What it shows | Typical visible cue | May be skipped when |
|---|---|---|---|
| **Preparation** | The body gets ready | Weight shift, small countermovement, gaze at the target | The action is a reflex or accident |
| **Initiation** | The action starts | First movement toward the goal | Never skipped (start of the movement) |
| **Acceleration** | Speed builds | Gradual speed-up | The action is very short |
| **Execution** | The main movement | Steady working speed | Never skipped |
| **Interaction or contact** | Meeting an object or person | Visible touch, resistance | There is no object (a turn, a step) |
| **Follow-through** | Movement continues after the action | Limbs or parts continue; objects swing | The action ends with a hold |
| **Deceleration** | Speed reduces | Slowing near the end | An impact stops it |
| **Recovery** | Return to stability | Weight resettles; posture straightens | The next action begins immediately |
| **Resulting state** | The stable end condition | A clear final posture and object state | Never skipped (the end must be defined) |

## 21.2 Action, Motion, Gesture, Reaction, and Secondary Motion

| Term | Definition | Driven by | Example | Design note |
|---|---|---|---|---|
| **Action** | Goal-directed or state-changing behavior | Intention or a state change | She opens the door. | Define purpose, phases, and outcome. |
| **Motion** | Physical change of position, orientation, or shape over time | Any cause | The door rotates 90° about its hinge. | Define direction, path, speed. |
| **Gesture** | A communicative or expressive movement, usually of hands, arms, or head | The subject's intention to express | A raised palm meaning "wait." | Meaning is context-dependent; keep it modest. |
| **Reaction** | A response to a stimulus (can be involuntary or deliberate) | An external event | She flinches at the noise. | Must follow the stimulus after a short delay. |
| **Secondary motion** | Passive movement of parts resulting from the primary movement | Physics (inertia, wind) | Her scarf swings after she stops. | Must agree with the primary action and conditions. |

## 21.3 Decision Tree for Simplifying or Specifying Movement

```
START: I have an action to generate.
│
├─ Can a viewer name the action from its start state, key movement, and end state?
│    ├─ NO  → Redefine the action (Section 2). Do not generate yet.
│    └─ YES → continue
│
├─ How many story-critical beats does it contain?
│    ├─ ONE → Keep a single clip; specify the beat in detail.
│    ├─ TWO OR MORE → Does the continuity of movement matter more than reliability?
│    │        ├─ YES → Try a continuous take at the shortest workable duration;
│    │        │        if it fails repeatedly, divide at the riskiest phase.
│    │        └─ NO  → Divide into clips, one beat each; match start/end states.
│
├─ Is there more than one subject?
│    ├─ YES → Can one subject be still or out of frame? If yes, simplify.
│    │        If not, label each subject and use the Action Ownership Table.
│    └─ NO  → continue
│
├─ Is contact visible (hand and object in clear view)?
│    ├─ NO  → Reposition the subject or camera framing so contact is visible,
│    │        or imply contact and show the consequence.
│    └─ YES → continue
│
├─ Is the path simple (one straight path or one turn)?
│    ├─ NO  → Reduce direction changes; add waypoints; or split the path.
│    └─ YES → continue
│
├─ Is the environment uncluttered?
│    ├─ NO  → Simplify the environment near the action.
│    └─ YES → continue
│
├─ Specify: identity, start state, trigger, phases, direction/path, timing, contact,
│  weight, secondary motion, end state, camera (separately), unchanged elements.
│
└─ Generate → verify with Section 20 → diagnose with Section 17 if needed.
```

## 21.4 Checklist for Reliable AI Action Instructions

- ☐ Subject identity and clothing are stated once and restated if needed.
- ☐ The starting posture, position, and orientation are specified.
- ☐ The action's purpose and trigger are stated.
- ☐ The participating body parts and objects are named.
- ☐ The phases are listed in order with "then."
- ☐ Direction and path use a named frame of reference.
- ☐ Approximate durations or a speed profile are given.
- ☐ Contact points and interaction order are specified; contact precedes effect.
- ☐ Weight transfer and balance cues are included for whole-body movement.
- ☐ Foot planting is specified for walking, running, and standing movements.
- ☐ Secondary motion is limited to what supports the action and agrees with one force direction.
- ☐ The final posture and object states are specified.
- ☐ Camera behavior is stated separately ("locked-off" if the camera should not move).
- ☐ The "must remain unchanged" list is included.
- ☐ "One continuous take; no cuts" is stated when needed.
- ☐ Stillness is specified for subjects who should not move.
- ☐ Vague words ("naturally," "dramatically," "grabs") are replaced by observable movement.
- ☐ Contradictions are removed; one primary action is requested where possible.

## 21.5 Common Motion Failures and Corrections

| Failure | Correction |
|---|---|
| Teleportation between poses | Add waypoints and phases ("then"). |
| Feet sliding or floating | "Each foot plants flat and stays fixed while the body passes over it." |
| Hands through objects | "Fingers touch the object before it moves." |
| Object moves before force | State the order: contact, then movement. |
| Reaction before the event | State the trigger and a short delay. |
| Wrong direction | State direction with a frame of reference. |
| Limbs change length | Simplify the action; restate proportions. |
| Implausible joint bending | Specify the joint's direction and range. |
| No weight | Add lean, bracing, slower acceleration, follow-through. |
| Robotic timing | Add anticipation, easing, and small variations. |
| Secondary motion contradicts | State one force direction and lag. |
| Camera mistaken for subject motion | Use separate SUBJECT MOTION and CAMERA statements. |
| Identity drift | Restate identity; shorten; reduce movement amplitude. |
| Action too complex | Simplify or split into phases. |
| Active but unclear | Reduce secondary activity; emphasize trigger, contact, consequence. |

## 21.6 Final Operational Rule Set

1. **Define purpose and intention before movement.** An action without a purpose is activity.
2. **Separate action from motion.** Specify the action for meaning and the motion for visibility.
3. **Define start and end states first.** Then design the path between them.
4. **Break the action into the phases the viewer must read,** and do not skip preparation or the resulting state when they carry meaning.
5. **Specify cause and effect in order:** trigger → intention or force → contact → response → resulting state.
6. **Make contact visible.** Contact precedes effect; hands never pass through objects.
7. **Respect physical principles:** balance, base of support, weight transfer, inertia, gravity, and joint limits, unless a stylization is declared.
8. **Do not assume one movement pattern fits all bodies or situations.** Account for proportions, load, surface, footwear, fatigue, and style.
9. **Use observable movement descriptions,** not adjectives or bare verbs.
10. **State direction and path in a named frame of reference,** with start, waypoints, and endpoint.
11. **Give timing as approximate durations and speed profiles;** use stillness, anticipation, and follow-through to make movement readable.
12. **Design emotion through movement qualities** (timing, amplitude, tension, gaze, pauses), not through a fixed gesture per emotion; verify in context.
13. **Keep secondary motion consistent with the primary action and one force direction.**
14. **Keep the camera and the subject separate** in every specification.
15. **Limit complexity:** one primary action, visible contact, an uncluttered path; split or simplify when the risk is high, but do not split by default.
16. **Label each subject distinctly** and assign each action to its subject, in order, with its trigger.
17. **Preserve continuity:** match direction, body position, hand placement, object state, and phase across cuts and clips; repeat the end state as the next start state.
18. **Diagnose in order** (recognition, start/end states, phases, direction, contact, timing, mechanics, continuity, secondary motion, camera, conflicts), change **one** variable at a time, and check for side effects.
19. **Verify the movement on screen,** not the description: step through the start, each contact, and the end.
20. **Approve only when no critical failure remains,** and record stylistic exceptions as intentional.

---

*End of file — Action_and_Motion_Design_and_Control_Cinematic_Knowledge.md*
