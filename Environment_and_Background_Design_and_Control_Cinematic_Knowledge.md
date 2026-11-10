# Environment and Background Design and Control — Cinematic Knowledge Base

**File:** `Environment_and_Background_Design_and_Control_Cinematic_Knowledge.md`
**Purpose:** Teach a filmmaker or an AI image and video generation system how to design, select, construct, control, evaluate, and troubleshoot the physical or digitally created **environment and background** surrounding the subject in a cinematic image or video.
**Scope lock:** This file centers on environment and background. Lighting, color, composition, camera, lens, shot size, action, sound, and editing appear here *only* where they interact with environmental decisions. Each of those disciplines has its own dedicated knowledge base, and this file does not replace them.

---

## How to Use This File

**For a human filmmaker:** Read Sections 1–3 for the mental model and the design method, use Sections 4–10 as a design and scouting reference, and use Sections 15, 17, and 18 as working tools in planning and review.

**For an AI system:** Treat this file as a decision procedure. The operating loop is:

1. Define the scene's narrative purpose and what the audience must learn from the place (Sections 2–3).
2. Choose an environment type and a spatial arrangement, then select the few features that carry meaning (Sections 4–8).
3. Check scale, depth, hierarchy, light, and plausibility (Sections 5, 6, 9, 10).
4. Specify the environment for generation layer by layer, with fixed landmarks and a lock list (Section 14).
5. Verify the result against observable criteria (Section 18).
6. If it fails, diagnose in a fixed order and change the smallest relevant variable (Section 15).

**Epistemic conventions used in this file.** Environment design mixes physics, perception, architecture, production practice, and creative convention. This file marks the difference:

- **Established principle** — follows from optics, perception, or widely observed production practice (for example, that distant objects appear lower in contrast because of atmospheric scattering).
- **Production convention** — a common practice that varies between crews, countries, and budgets (for example, how "set dressing" and "props" are divided).
- **Approximate value** — a typical dimension or figure (a door height, a stair riser) that varies with country, building era, and design. Treat it as a starting estimate.
- **Context-dependent effect** — an effect that depends on story, culture, genre, and combination of elements. No environment feature has a universal meaning.

**Terminology rule.** Technical terms are defined the first time they appear.

---

## Table of Contents

1. Core Definition and Scope
2. The Functions of an Environment
3. Environment Design from Story Requirements
4. Environment Types and Their Design Requirements
5. Spatial Layers and Environmental Depth
6. Background Complexity, Clutter, and Visual Hierarchy
7. Location Selection and Location Scouting
8. Set Design, Set Dressing, Props, and Environmental Evidence
9. Scale, Proportion, and Physical Plausibility
10. Environmental Lighting and Atmosphere
11. Environmental Dynamics: Weather, Time, Season, and Background Activity
12. Environment and the Subject: Separation, Placement, and Integration
13. Environmental Continuity
14. Environment Design for AI Image and Video Generation
15. Environment and Background Failure Diagnosis
16. Practical Case Studies
17. Environment Design Worksheet
18. Quality Control and Final Verification
19. Quick Reference

---

# 1. CORE DEFINITION AND SCOPE

## 1.1 Definitions

| Term | Definition | Notes |
|---|---|---|
| **Environment** | The total physical or digital surroundings in which the subject exists and acts: space, terrain, architecture, objects, weather, atmosphere, and the conditions of light as they exist in the world of the scene. | A property of the *scene world*. It exists whether or not the camera sees all of it. |
| **Background** | The part of the environment visible *behind the subject* from the camera's viewpoint. | A property of the *image*. Moving the camera changes the background without changing the environment. |
| **Foreground** | The part of the environment between the camera and the subject (or the nearest visible layer). | Often partly out of focus; can frame or obstruct the subject. |
| **Midground** | The layer at or near the subject's distance. | Where most action and interaction occur. |
| **Setting** | The broad time and place of the story (for example, "a fishing town in the 1950s"). | Story-level information; one setting can include many locations. |
| **Location** | A specific place where a scene occurs, whether a real place used for filming or a specific place inside the story world. | Production usage: a real place; story usage: a named place. State which you mean. |
| **Set** | An environment that is constructed (in a studio, on a backlot, or digitally) rather than found. | Can be a partial set (one wall) or a full build. |
| **Set dressing** | Items added to a set or location to make it look inhabited and specific: furniture, curtains, rugs, wall art, signage, clutter. | Usually not handled by performers. |
| **Props** | Objects that performers handle or that take part in action (a cup, a key, a bag). | Production convention varies on the line between "set dressing" and "props"; larger set items that performers use are often treated as props. |
| **Environmental storytelling** | Conveying narrative information through the arrangement, condition, and content of the environment rather than through dialogue or exposition. | Works through visible evidence (Section 8). |
| **Environmental atmosphere** | The sensory and physical qualities of the air and place: haze, dust, humidity, mist, steam, light shafts, temperature cues. | A contributor to mood, not the same as mood (the audience's emotional weather). |

## 1.2 Overlaps and Boundaries

| Item | Belongs to the environment? | Belongs to the background? | Belongs to the subject or foreground? |
|---|---|---|---|
| A brick wall behind the subject | Yes | Yes | No |
| The same wall when the camera faces the other way | Yes | No (not visible behind the subject) | No |
| A lamp on a table beside the subject | Yes (set dressing or practical) | Only if it appears behind the subject | If the subject uses it, it is a prop |
| A coffee cup the subject lifts | Yes (as an object in the world) | No | Prop; part of the subject's action |
| A passing pedestrian far behind | Yes | Yes (background action) | No |
| A tree branch between the camera and the subject | Yes | No | Foreground element |
| Fog drifting through the scene | Yes (atmosphere) | Appears in all layers | May also reduce subject contrast |
| The subject's coat | No | No | Subject (costume) |
| A car the subject leans against | Yes | Possibly | Prop or midground element, depending on interaction |

**Working rule:** *If a thing exists in the world of the scene and is not part of the subject's body or costume, it is part of the environment.* Whether it appears as background, midground, or foreground depends on its distance from the camera relative to the subject, and on where the camera is.

## 1.3 Environment vs. Background: Why the Distinction Matters

- **Design the environment; frame the background.** The environment is designed as a coherent world (layout, objects, conditions). The background is what the chosen camera position makes visible.
- **One environment, many backgrounds.** A kitchen has a different background behind a person at the sink than behind a person at the table. Backgrounds across shots must be consistent with the same layout (Section 13).
- **A background can be changed by moving the camera,** which is often easier than changing the environment.

## 1.4 Why a Background Remains Important When Out of Focus, Dark, Hidden, or Brief

Even when a background is blurred, dim, partly hidden, or visible for only a few frames, it continues to work:

| Reason | Mechanism (established perception principle) | Consequence |
|---|---|---|
| **Gist perception** | Viewers extract the general character of a scene (indoor or outdoor, natural or built, bright or dim, calm or busy) from very brief or blurred views. Blur removes fine detail but preserves color, shape masses, and brightness. | A blurred background still tells the audience where they are and what kind of place it is. |
| **Tonal and color relationships** | The brightness and color of the background determine the subject's contrast and separation. | A wrong background tone can make the subject disappear or glow, even if the background is a blur. |
| **Silhouette interaction** | Background shapes and lines can merge with the subject's outline. | A bright window behind the head turns the face dark; a pole behind the head appears to grow from it. |
| **Scale and depth cues** | Even soft shapes show distance and size. | A blurred row of lamps shows depth; a flat blur can flatten the scene. |
| **Motion cues** | Background movement (passing cars, people) is noticed in peripheral attention even when blurred. | Unmotivated motion can distract or contradict the setting. |
| **Continuity expectations** | Viewers remember the general look of a space. | A different background tone in the next shot reads as a different place or time. |
| **Generated-image behavior** | AI image and video models generate the entire frame at once; background errors (morphing, repeating, extra people) can appear even when the background is a minor part of the prompt. | Background must be specified and checked, not ignored. |

**Design consequence:** Treat the background as *always present in the viewer's perception,* even when it is not sharply seen. Decide its tone, color, shapes, motion, and information deliberately.

---

# 2. THE FUNCTIONS OF AN ENVIRONMENT

An environment can be *decoration* or it can be *information*. Environments become cinematic when each element serves at least one function below. For each function, the entries describe **when it is useful**, **how to achieve it**, and **how it can fail**.

## 2.1 Establishing Where and When a Scene Occurs

- **When useful:** At the start of a film or sequence, after a location or time change, and whenever the audience could be confused about place or period.
- **How to achieve it:** Show distinctive, identifiable features: landmarks, architecture style, signage language, vehicles, clothing seen on others, vegetation, weather, and light direction suggesting time of day. Choose features that are *specific* rather than generic (a recognizable street layout, a particular type of tram).
- **How it can fail:** Generic cues ("a street," "a forest") that could be anywhere; contradictory cues (modern vehicles in a historical setting); a time-of-day cue that conflicts with the light; a place that is recognizable only to people who already know it.

## 2.2 Revealing the World's Social, Cultural, Historical, Technological, and Economic Conditions

- **When useful:** When the story depends on how the world works (a poor district, an authoritarian state, a technologically advanced city).
- **How to achieve it:** Use evidence of use and maintenance (repairs, upgrades, neglect), materials (concrete, timber, glass), technology visible in the space (wiring, screens, tools), the presence or absence of services, and objects of daily life. Let the viewer infer conditions from several consistent clues.
- **How it can fail:** A single stereotype used as shorthand; inconsistent evidence (wealthy interior, collapsing exterior with no reason); cultural details applied incorrectly; clichés that carry no information.

## 2.3 Communicating a Character's Circumstances Without Dialogue

- **When useful:** When showing is more efficient or truthful than telling: a character's work, habits, finances, relationships, and recent events.
- **How to achieve it:** Place objects that show use (a worn chair seat, a stack of unopened mail), personal items (photographs, tools), arrangement (tidy, chaotic, minimal), and traces of other people (a second toothbrush, an empty chair).
- **How it can fail:** Over-explaining with too many "meaningful" objects; objects that look staged; evidence that contradicts the character's established traits; details too small to be seen.

## 2.4 Supporting Genre and Story Plausibility

- **When useful:** When the audience must accept the rules of the story world (realistic drama, science fiction, fantasy, historical drama).
- **How to achieve it:** Keep the environment's logic consistent with the genre's conventions and the story's rules: technology level, architecture, materials, and the physics of the world. In fantastical worlds, establish rules and apply them consistently.
- **How it can fail:** Mixed rules (a medieval village with modern plastic); fantasy elements with no internal logic; realism broken by impossible geometry in a realist story.

## 2.5 Establishing Scale, Distance, Depth, and Spatial Orientation

- **When useful:** When the audience must understand how big a place is, how far things are, and where the characters are relative to exits, threats, and goals.
- **How to achieve it:** Use scale references (doors, people, vehicles), layered depth (Section 5), consistent perspective, landmarks that recur, and a legible layout (a corridor with an end, a room with a visible door).
- **How it can fail:** No scale reference; objects that change size; a layout that cannot be reconstructed; inconsistent landmarks.

## 2.6 Creating Safety, Tension, Loneliness, Mystery, Intimacy, Oppression, Freedom, or Danger

- **When useful:** Whenever the environment should support an emotional atmosphere (the mood knowledge base covers mood itself).
- **How to achieve it:** Use *spatial and physical properties* of the environment: openness vs. enclosure, visibility vs. concealment, order vs. disorder, proportion of the subject to the space, availability of exits, quality of materials, cleanliness, presence or absence of others. Each property *may* support more than one mood depending on context.
- **How it can fail:** Treating one feature as a guarantee (fog = mystery); a mismatch between environment and action; a beautiful environment that contradicts the intended emotional atmosphere.

## 2.7 Providing Meaningful Objects, Landmarks, Routes, Barriers, Entrances, Exits, Hiding Places, and Obstacles

- **When useful:** When the story involves movement through space, escape, pursuit, discovery, or protection.
- **How to achieve it:** Identify the *routes* a character could take and the objects that shape them: doors, stairs, gaps, fences, counters, shadows. Make entrances and exits readable. Place obstacles where they change choices.
- **How it can fail:** Doors that cannot plausibly be used; exits that appear and disappear; obstacles that are decorative only; no visible route to the goal.

## 2.8 Supporting Physical Action and Character Movement

- **When useful:** In any scene where the subject moves, interacts with objects, or performs physical action.
- **How to achieve it:** Ensure adequate clear floor space, believable surfaces (grip, slope), objects at usable heights, doors and passages of usable size, and space for camera and equipment if filming practically.
- **How it can fail:** Cramped space that prevents the planned movement; slippery or uneven surfaces not accounted for; objects in the path; scale that makes interaction look wrong (a chair that is too small to sit on).

## 2.9 Creating Continuity Between Shots and Scenes

- **When useful:** Whenever a scene is covered by multiple shots or clips, or a location recurs.
- **How to achieve it:** Define a layout map, a landmark list, and a state list (what is where, what condition it is in). Keep light direction, weather, and time of day consistent (Section 13).
- **How it can fail:** Objects that move between shots without cause; backgrounds that do not match the geography; changing weather; elements that drift in generated clips.

## 2.10 Function Summary

| Function | Key evidence | Typical failure |
|---|---|---|
| Establish where and when | Distinctive landmarks, period cues, light | Generic or contradictory cues |
| Reveal conditions of the world | Use, wear, materials, technology | Stereotype; inconsistent clues |
| Show circumstances without dialogue | Personal objects, arrangement | Over-staged; too small to see |
| Support genre and plausibility | Consistent rules | Mixed rules |
| Establish scale and orientation | References, layers, layout | No scale reference |
| Create emotional atmosphere | Openness, concealment, order, proportion | Single-cue shortcuts |
| Provide routes and obstacles | Doors, stairs, barriers | Unusable passages |
| Support action | Clear space, workable surfaces | Cramped or mis-scaled space |
| Create continuity | Layout map, state list | Drift between shots |

---
# 3. ENVIRONMENT DESIGN FROM STORY REQUIREMENTS

Environment design is a **repeatable sequence of decisions** that converts story information into physical (or digital) choices. Skipping steps produces scenery that looks attractive but carries no meaning.

## 3.1 The Ten Steps

### Step 1 — Identify the scene's narrative purpose
**What:** State what the scene does in the story: reveals information, changes a relationship, raises stakes, provides rest, marks a transition.
**Why:** The environment must serve this purpose; elements that do not serve it are candidates for removal.
**How:** Complete: *"After this scene, the story is different because ______."*

### Step 2 — Identify the subject's immediate objective
**What:** State what the subject is trying to do in this place (find a document, hide, wait, escape, rest).
**Why:** The objective determines which parts of the environment matter: routes, objects, barriers, hiding places.
**How:** Write the objective in one sentence and list the environmental elements it touches.

### Step 3 — Determine what the audience must understand about the location
**What:** List the facts about place the viewer must receive: where, when, what kind of place, who uses it, how safe it is.
**Why:** Environmental information is limited by frame time and shot size; prioritize.
**How:** Write a must-know list (maximum five items) and a must-not-know-yet list (information to withhold).

### Step 4 — Determine the emotional and atmospheric requirements
**What:** Define the emotional weather the environment should support (see the mood knowledge base) and the physical atmosphere (haze, dust, humidity, quiet or noise).
**Why:** Spatial and physical properties are among the strongest carriers of emotional atmosphere.
**How:** For each requirement, name the *environmental property* that will carry it (enclosure, openness, order, cleanliness, visibility, temperature cues).

### Step 5 — Identify practical action and movement requirements
**What:** Determine what the subject must physically do: walk a distance, climb, sit, open a door, run.
**Why:** The environment must permit the movement, and the camera must have a position from which to show it.
**How:** Sketch the path and the clear space needed; note objects the subject touches and their positions.

### Step 6 — Select the appropriate environment type and spatial arrangement
**What:** Choose the type (Section 4) and the layout: how big, how enclosed, where the entrances and exits are, where the key objects sit.
**Why:** Type and arrangement determine staging, camera positions, depth, and light opportunities.
**How:** Compare two or three candidate types against steps 1–5 and choose the one that satisfies the most requirements with the fewest compromises.

### Step 7 — Select essential environmental features
**What:** Choose the 3–7 features that carry the scene's meaning: landmarks, evidence objects, materials, conditions.
**Why:** A small number of strong features read better than many weak ones.
**How:** For each feature, state its function (identify place, show history, supply scale, create route, supply atmosphere).

### Step 8 — Remove unnecessary or contradictory details
**What:** Delete elements that do not serve a function, compete with the subject, or contradict the setting.
**Why:** Unneeded detail reduces readability; contradiction undermines plausibility.
**How:** Apply the clutter audit (Section 6.6) and the contradiction check (period, purpose, weather, culture).

### Step 9 — Check visual readability and plausibility
**What:** Confirm that the viewer can read the subject, the place, and the layout, and that the environment obeys physical logic (scale, support, light).
**Why:** Implausible or unreadable environments fail even when they are well designed on paper.
**How:** Use Sections 5, 6, 9, and 10.

### Step 10 — Verify continuity and AI-generation constraints
**What:** Define what must stay fixed across shots or clips, and simplify elements that are known to be unstable in generation.
**Why:** Many environment failures are drift: layout, objects, light, or weather changing between frames.
**How:** Write a layout map, a landmark list, and a lock list (Sections 13–14).

## 3.2 How the Process Changes by Scene Type

| Scene type | What changes in the environment design | Priority features | Risks |
|---|---|---|---|
| **Establishing shot** | The environment is the subject. Show place, time, scale, and layout in one image. | Distinctive landmarks, scale references, light cue for time, a clear sense of the world | Generic cues; no scale reference; too much unreadable detail |
| **Dialogue scene** | The environment supports the conversation: quiet background, a layout that stays consistent through reverse shots, evidence of who the speakers are. | Clean areas behind faces; consistent geography; a few characterizing objects | Busy backgrounds; mismatched backgrounds between reverse shots; distracting activity |
| **Close-up** | The background becomes tone, color, and a few shapes; detail is mostly blurred. | Background tonal relationship to the face; a single motivated light source or color cue | Merging shapes; bright spots; background that contradicts the wider shots |
| **Action sequence** | The environment is a *field of play*: clear routes, obstacles, and consequences. | Readable geography; surfaces that match the action; obstacles that change choices | Clutter that hides action; spaces too small; unreadable layout |
| **Suspense scene** | The environment holds *information* the audience can anticipate: where the threat could come from, where the exits are. | Entrances, blind spots, sightlines, concealment, partial visibility | Showing the threat too early; nothing to anticipate |
| **Survival scene** | The environment is an antagonist and a resource: terrain, weather, scarcity, shelter. | Distances, terrain difficulty, resources, conditions | Environment too benign; scale unclear; inconsistent conditions |
| **Flashback** | The environment shows *time difference* from the present: age, wear, light, technology. | Evidence of period or condition difference; consistent treatment of past versus present | Looks identical to the present; inconsistent period cues |
| **Dreamlike scene** | The environment follows *associative logic*: impossible connections that remain internally consistent. | A few anchoring real elements plus a controlled distortion; consistent rules | Random weirdness; unclear whether distortion is intended |
| **Transition** | The environment links two scenes through shape, color, light, or sound cue. | A visual rhyme or contrast between the outgoing and incoming spaces | Link too subtle to notice or too forced |

## 3.3 Decision Table: Narrative Goals and Environmental Characteristics

**Reminder:** These are *tendencies*, not formulas. Each characteristic may support more than one goal depending on context.

| Narrative goal | Environmental characteristics that may support it | Spatial arrangement | Evidence and details | Typical risk |
|---|---|---|---|---|
| **Show isolation** | Large space relative to the subject; few other people; separation by distance, glass, or barriers | Subject off-center in open or empty space | A single place setting; unused spaces | Reads as peaceful if the subject looks content |
| **Show safety and comfort** | Moderate enclosure; soft, lived-in materials; clear sightlines to exits | Visible, easy routes; well-defined resting spots | Signs of care; warm domestic objects | Overly perfect, reads as artificial or unsettling |
| **Build suspense** | Concealment points; limited visibility; layered depth with hidden areas | Corridors, doorways, partial sightlines | Something slightly out of place | Too many cues remove subtlety |
| **Show danger** | Unstable or exposed terrain; limited exits; hazards in the frame | Narrow routes, edges, heights | Visible hazards linked to consequence | Hazard looks decorative |
| **Show oppression** | Heavy or repetitive architecture; low ceilings; uniform materials; surveillance elements | Regimented layout; no visible exits | Rules, numbers, uniform arrangement | Environment overpowers the people |
| **Show freedom** | Open horizons; wide routes; variety of paths | Subject has multiple directions | Movement, open skies, receding depth | Empty space with no subject relationship |
| **Show wealth** | Quality materials; spaciousness; maintained surfaces; organized objects | Generous space; controlled sightlines | Craft, curated objects | Cliché luxury shorthand |
| **Show poverty or hardship** | Worn, patched, improvised surfaces; limited space; scarcity | Tight arrangements; shared spaces | Repairs, workarounds, absence of goods | Exaggerated squalor; over-distressing |
| **Show history** | Layers of age; mixed periods; weathering | Older structures with additions | Objects from different decades | Fake patina; uniform "aging" |
| **Show a character's job or hobby** | Tools, materials, records, spaces designed for the activity | Arrangement matches workflow | Used tools, notes, specialized items | Props that look unused |
| **Show recent events (aftermath)** | Disruption: displaced objects, damage, residue | Disorder with a logic pointing to the event | Evidence in a traceable chain | Chaos with no cause |
| **Show time passing** | Changes in light, wear, season, objects | Same layout, changed state | Dust, growth, replaced items | Changes too subtle or contradictory |
| **Create intimacy** | Small, enclosed, soft-lit spaces; shared surfaces | Close seating; defined boundaries | Personal objects | Claustrophobic if exits are blocked |
| **Create wonder** | Large scale, unfamiliar forms, layered depth, light behavior | Reveals and vantage points | Scale references | Spectacle without human reference |
| **Support a comic tone** | Orderly space disrupted by absurd or misplaced elements | Clear sightlines for gags | Props that set up a joke | Clutter hides the gag |
| **Support a stylized or abstract treatment** | Reduced forms; simplified color; unusual proportion | Controlled geometry | A few defining shapes | Looks unfinished |

---

# 4. ENVIRONMENT TYPES AND THEIR DESIGN REQUIREMENTS

**How to read this section.** Each type is described by how it affects: **staging** (where subjects can be placed and move), **camera placement** (what positions are available), **lighting opportunities** (what the environment offers the light), **depth** (how layers arrange), **movement** (what the environment does or allows), **realism** (what makes it credible), and **continuity** (what tends to drift). Each type also lists **strengths**, **limitations**, and **common failures**. These are descriptions of tendencies, not aesthetic adjectives.

## 4.1 Natural Environments

**General characteristics:** Few straight lines; irregular forms; large scale; light that changes with time and weather; sound and motion from wind and water; limited control (in real locations).

**General staging and camera:** Natural spaces often offer long sightlines and varied distances; camera access can be limited by terrain; the horizon and sky are major compositional factors.

**General risks:** Overly symmetrical or repeated vegetation looks artificial; scale loses meaning without references; lighting changes quickly in real locations.

| Type | Defining spatial traits | Staging and camera | Lighting opportunities | Depth and movement | Common failures and corrections |
|---|---|---|---|---|---|
| **Forests** | Vertical trunks; canopy overhead; undergrowth; filtered light | Trunks create natural framing and partial occlusion; subjects can be hidden or revealed; camera may need clearance among trees | Dappled light through gaps, shafts through haze, soft diffused light under overcast | Layered depth from overlapping trunks; branches and leaves move with wind | *Failure:* trunks aligned behind the head ("poles" through the subject). *Fix:* shift camera or subject; vary trunk spacing. *Failure:* uniformly spaced trees. *Fix:* vary species, size, and spacing |
| **Jungles** | Dense, layered vegetation; high humidity; limited sightlines; mixed light levels | Very restricted visibility; paths and clearings define routes; camera movement is difficult | Strong contrast between canopy shade and openings; mist | Heavy occlusion; constant small motion; sound dominated by life | *Failure:* a "jungle" that looks like a temperate forest. *Fix:* layered plant forms, vines, large leaves, humidity cues (damp surfaces, mist). *Failure:* uniform green. *Fix:* vary tones and depths |
| **Mountains** | Large vertical relief; exposure; changing weather; scale | Long distances and heights; camera placement limited; vantage points reveal scale | Directional light along ridges; long shadows at low sun; cloud shadows | Strong atmospheric perspective; slow cloud motion | *Failure:* no scale reference. *Fix:* include a figure, hut, or path. *Failure:* flat "painted" ranges. *Fix:* overlapping ridges with distance haze |
| **Deserts** | Open terrain; sparse features; strong light; heat; sand or rock | Wide, simple compositions; camera access easy; features sparse | Hard light; long shadows at low sun; heat shimmer | Depth from dune overlap and distance fade; wind-blown sand | *Failure:* empty and featureless. *Fix:* use dune ridges, tracks, textures. *Failure:* inconsistent heat cues. *Fix:* match clothing, shadows, and light |
| **Beaches** | Shoreline; tide zone; horizon; wet and dry sand | Horizontal bands (sky, sea, sand); camera low or high changes the horizon | Reflective wet sand and water; broad light; backlit spray | Waves provide repeated movement; foam lines show scale | *Failure:* wave patterns repeating. *Fix:* vary wave sizes and timing. *Failure:* dry footprints on wet sand inconsistent. *Fix:* match surface wetness |
| **Rivers** | Linear flow; banks; reflections; bridges | A river forms a path and a barrier; camera may use bank or water level | Reflections and glints; light direction affects visibility of depth | Flow direction defines motion; ripples | *Failure:* flow direction inconsistent. *Fix:* define flow direction. *Failure:* reflections that do not match objects. *Fix:* check reflection logic |
| **Oceans** | Large open water; waves; no landmarks; weather dominance | Little reference; boats or horizon needed for scale; camera on a vessel moves with it | Large soft reflections; low-sun glitter | Waves provide rhythmic motion | *Failure:* scale unreadable. *Fix:* include a boat or horizon. *Failure:* wave scale inconsistent. *Fix:* match wave size to wind and boat |
| **Caves** | Enclosed rock; low ceiling; wet surfaces; no daylight beyond the entrance | Tight camera positions; subjects often lit by handheld or practical lights | Light falloff; rim light from entrance; reflective wet rock | Depth from passages and stalactite-like forms; dripping | *Failure:* evenly lit cave. *Fix:* motivate light by a lamp or entrance with falloff. *Failure:* smooth, repeating rock texture. *Fix:* vary forms |
| **Open landscapes (plains, fields, steppe)** | Broad horizon; low features; large sky | Wide shots; horizon dominates; vehicles and fences give scale | Large sky as source; low sun shadows; weather fronts | Depth from field lines and distant features | *Failure:* flat. *Fix:* include layered fields, fences, trees, haze. *Failure:* horizon cutting through the subject's head. *Fix:* change camera height |

## 4.2 Urban Environments

**General characteristics:** Straight lines and repeated modules; strong perspective; many light sources at night; people and vehicles supply motion; signage and text.

**General risks:** Signage text in generated images is often malformed; crowds and traffic can morph; repetitive windows and facades look artificial.

| Type | Defining spatial traits | Staging and camera | Lighting opportunities | Depth and movement | Common failures and corrections |
|---|---|---|---|---|---|
| **Streets** | Linear corridor formed by buildings; sidewalk, road, vehicles | Strong one-point perspective down the street; camera can sit in the road or on the sidewalk | Sun shafts between buildings; headlights and signs at night; reflections on wet roads | Depth from converging lines; background traffic and pedestrians | *Failure:* uniform building facades. *Fix:* vary heights, widths, details. *Failure:* traffic moving against a defined direction. *Fix:* set lane directions |
| **Alleys** | Narrow gap; walls; utilities; dead ends | Confined staging; limited camera positions; strong vertical lines | Spill light from windows; single lamps; pooled light | Compressed depth; steam or drips as motion | *Failure:* too clean. *Fix:* grime at logical places (bases of walls, under pipes). *Failure:* inconsistent width. *Fix:* fix a layout map |
| **Rooftops** | Open sky; edges; equipment; skyline | Heights create exposure; camera access limited; parapets define safe zones | Open sky light; city glow at night; strong backlight | Depth from skyline layers; wind | *Failure:* the skyline repeats or morphs. *Fix:* define a few recognizable buildings. *Failure:* no edge protection logic. *Fix:* add parapets or railings |
| **Public spaces (plazas, parks, markets)** | Open area with varied activity; seating, trees, stalls | Subjects can be isolated or immersed; camera positions flexible | Mixed daylight and shade; evening lamp light | Rich layered activity; crowds | *Failure:* crowd that looks cloned. *Fix:* vary clothing, speed, direction. *Failure:* crowd competing with the subject. *Fix:* thin the crowd near the subject |
| **Transport areas (stations, platforms, airports, bus stops)** | Linear platforms; signage; repeated columns; schedules | Strong perspective lines; staging along platforms; camera at track level or platform | Large fixtures; fluorescent lighting; daylight through windows | Vehicles arriving and departing provide motion | *Failure:* signage text unreadable or incorrect. *Fix:* limit legible text or use blurred signs. *Failure:* trains in the wrong direction. *Fix:* define track direction |

## 4.3 Interior Environments

**General characteristics:** Enclosed volumes defined by walls, floors, and ceilings; lighting from windows and fixtures; scale defined by furniture and doors; strong geometry.

**General risks:** Cramped camera positions; mismatched backgrounds in reverse shots; light that does not match windows; furniture scale errors.

| Type | Defining spatial traits | Staging and camera | Lighting opportunities | Depth and movement | Common failures and corrections |
|---|---|---|---|---|---|
| **Homes** | Rooms connected by doors; furniture and personal objects | Rooms are small; camera often at wall or doorway; layout must be consistent | Windows, lamps, kitchen lights | Doorways create depth into other rooms | *Failure:* generic, staged-looking home. *Fix:* personal evidence (clutter in logical places). *Failure:* inconsistent layout between shots. *Fix:* floor plan |
| **Bedrooms** | Bed as dominant object; personal items; privacy | Intimate; camera positions limited; the bed controls staging | Bedside lamps; window light; screens | Shallow depth; closet or door as depth | *Failure:* hotel-like and impersonal. *Fix:* evidence of occupant. *Failure:* bed scale off. *Fix:* use standard dimensions |
| **Offices** | Desks, partitions, meeting rooms, uniform lighting | Grids; glass walls; long sightlines in open plans | Overhead panels; window light; screens | Depth through rows; people moving | *Failure:* sterile and empty. *Fix:* personal items, wear, paper. *Failure:* identical desks without variation. *Fix:* vary items |
| **Corridors** | Linear volume; doors at intervals; strong perspective | Staging along a line; camera at the end or side; chase geometry | Rows of lights; doorways spilling light | Strong depth; repeated elements | *Failure:* repeated doors identical. *Fix:* vary details. *Failure:* the end is unreadable. *Fix:* give a visible endpoint |
| **Hospitals** | Institutional materials; signage; equipment; routes | Corridors, rooms, nurses' stations; strict layout logic | Fluorescent light; indicator lights; window light | Moving staff and equipment | *Failure:* equipment placement implausible. *Fix:* research layouts; limit detail. *Failure:* signage text errors. *Fix:* simplify signage |
| **Shops** | Shelves, counters, products, signage | Aisles, counters; many surfaces; camera positions can be limited | Display lighting; storefront windows | Depth from aisles | *Failure:* products with garbled labels. *Fix:* blur or simplify labels. *Failure:* shelves with uniform stock. *Fix:* vary and show gaps |
| **Warehouses** | Large volume; racks; pallets; high ceilings; sparse light | Wide staging; vehicles; long sightlines | Pools of light, skylights, dust shafts | Strong depth from racks; machinery motion | *Failure:* scale unreadable. *Fix:* include people, forklifts, pallets of known size |
| **Abandoned buildings** | Decay; debris; exposed structure; overgrowth; daylight through openings | Complex routes; hazards; camera access varies | Shafts through holes; uneven light | Layered debris; dust, drips | *Failure:* decoration of decay with no logic. *Fix:* decay follows water, weather, and time. *Failure:* excessive grunge uniform everywhere. *Fix:* concentrate damage where causes exist |

## 4.4 Industrial and Infrastructural Environments

**General characteristics:** Large scale; functional forms; repeated structural modules; machinery; hazards; strong geometry; harsh or utilitarian lighting.

**General risks:** Machinery that has no plausible function; scale uncertainty; clean appearance that contradicts use; safety features missing in a way that breaks plausibility.

| Type | Defining spatial traits | Staging and camera | Lighting opportunities | Depth and movement | Common failures and corrections |
|---|---|---|---|---|---|
| **Factories** | Production lines; machines; conveyors; storage | Staged along flow lines; camera positions at aisles and platforms | High-bay lamps; machine indicators; sparks and steam | Repetitive motion of machines | *Failure:* machines with no function. *Fix:* design a simple process flow. *Failure:* too clean. *Fix:* oil, dust, wear at contact points |
| **Power facilities** | Turbines, pipes, control rooms, high voltage equipment | Large forms; limited access zones; control rooms for dialogue | Indicator lights; harsh work lights; steam | Heavy machinery; humming; vapor | *Failure:* control panels with random lights. *Fix:* group indicators logically |
| **Bridges** | Long spans; cables or arches; railings; traffic | Heights and distances; camera at deck or underside | Open sky; sunrise or sunset; headlights | Receding structure lines; traffic | *Failure:* impossible structure. *Fix:* follow recognizable structural logic (cables, arches, trusses) |
| **Tunnels** | Enclosed linear volume; repeated lights; limited exits | One-point perspective; staging along the axis | Rows of lights; vehicle headlights; end-of-tunnel light | Strong depth; repeated pattern | *Failure:* pattern lights repeating exactly. *Fix:* introduce varied failures or wear |
| **Construction sites** | Incomplete structures; scaffolding; machinery; materials | Multi-level staging; hazards; camera positions limited | Natural light; work lights; dust | Moving machinery; workers | *Failure:* scaffolding impossible. *Fix:* follow simple repeated structure with anchors |
| **Mechanical spaces (boiler rooms, plant rooms, ducts)** | Pipes, valves, tanks, tight passages | Cramped; camera positions limited | Bare bulbs; steam; spill light | Complex overlap; vibration | *Failure:* pipes ending nowhere. *Fix:* connect lines logically |

## 4.5 Historical and Period Environments

- **Design characteristics:** Environments must be consistent with a specific time and place: architecture, materials, tools, vehicles, clothing of others, signage, lighting technology.
- **Staging and camera:** Camera positions must avoid anachronisms (modern buildings, power lines, signage). Real locations often need modification or digital cleanup.
- **Lighting opportunities:** Period lighting sources (candles, oil lamps, early electric bulbs) differ in color and intensity; practical sources must match.
- **Depth and movement:** Period crowds and vehicles must behave in period ways (speed, clothing, work).
- **Realism:** Research is the main requirement; details such as materials, wear, and everyday objects carry authenticity.
- **Continuity:** Period details must be consistent across all shots; a single anachronism can break plausibility.
- **Strengths:** Rich storytelling evidence; distinctive look.
- **Limitations:** Research and construction cost; risk of clichés (a single "olden days" look).
- **Common failures and fixes:** *Mixed periods* (fix: define the exact year and region and check each element); *too clean* (fix: add period-appropriate wear and use patterns); *costume-party look* (fix: show everyday objects in use); *modern construction visible* (fix: reposition camera or mask).

## 4.6 Futuristic and Science-Fiction Environments

- **Design characteristics:** Environments extrapolate technology and society; they require *internal logic*: power sources, materials, purposes.
- **Staging and camera:** Controlled sets or digital builds; scale references are essential because unfamiliar forms hide size.
- **Lighting opportunities:** Practical light from screens, panels, glowing materials; mixed color sources.
- **Depth and movement:** Layered structures, moving machinery, vehicles, signage.
- **Realism:** Believability comes from *use evidence* (wear, repairs, clutter) and consistent rules, not from polished surfaces.
- **Continuity:** Technology rules and visual language (symbols, colors) must remain consistent.
- **Strengths:** Freedom to design a world; strong visual identity.
- **Limitations:** Easy to look generic (glowing lines, shiny corridors); requires many consistent decisions.
- **Common failures and fixes:** *Sterile, unused-looking spaces* (fix: add wear, maintenance traces, human use); *scale ambiguity* (fix: add doors, railings, people); *impossible function* (fix: define what the space is for); *generic neon* (fix: specify a unique material and lighting logic).

## 4.7 Fantasy Environments

- **Design characteristics:** Worlds with magic, creatures, or impossible geography; they still need *rules* and *scale*.
- **Staging and camera:** Often built digitally; need clear landmarks and routes; camera positions chosen to reveal scale.
- **Lighting opportunities:** Magical light sources must be consistent (color, direction, effect on surfaces).
- **Depth and movement:** Large vistas, unusual structures, creatures; motion from magical phenomena.
- **Realism:** Ground the fantastic in real material behavior (stone looks like stone; wood weathers).
- **Continuity:** Rules for magic and geography must hold.
- **Strengths:** Wonder; distinct identity.
- **Limitations:** Without grounding, it looks like generic illustration; scale confusion.
- **Common failures and fixes:** *Unclear scale* (fix: reference objects, people); *surfaces that look like plastic* (fix: texture and wear); *random magical effects* (fix: a stated rule and consistent appearance); *the "everything glows" problem* (fix: limit light sources).

## 4.8 Minimalist or Abstract Environments

- **Design characteristics:** Reduced forms, limited objects, simple color fields, or empty space; the environment is deliberately restrained.
- **Staging and camera:** The subject and a few shapes carry the image; camera positions matter greatly because there is nothing to hide errors.
- **Lighting opportunities:** Light and shadow shape the space; gradients and edges become visible.
- **Depth and movement:** Depth from light falloff, floor lines, and subtle gradients; little background motion.
- **Realism:** Not necessarily realistic; coherence matters.
- **Continuity:** Few objects to track, but tone and edge consistency are critical.
- **Strengths:** High subject clarity; strong stylistic identity.
- **Limitations:** Flaws are visible; can feel empty or unfinished; weak spatial orientation.
- **Common failures and fixes:** *Looks unfinished* (fix: define the rules of the space: floor material, horizon, light source); *flat* (fix: light gradient, floor line, a single scale object); *inconsistent edges* (fix: define the background's tonal range).

## 4.9 Artificial Sets and Controlled Studio Environments

- **Design characteristics:** Built spaces with removable walls, controlled light, and designed dressing.
- **Staging and camera:** Flexible camera positions (walls can be removed or "wild"), but the set's size limits how much can be shown; backgrounds beyond windows or doors need backing (painted, printed, or screen).
- **Lighting opportunities:** Fully controllable; lights can be placed above and around; practical fixtures must motivate the look.
- **Depth and movement:** Depth must be built (layers, windows, doors, backings); background motion must be created.
- **Realism:** Achieved through detail, wear, and believable light; walls and floors must have texture and variation.
- **Continuity:** Controlled; dressing can be photographed and reset.
- **Strengths:** Control; efficiency; safety.
- **Limitations:** Feels "set-like" if too clean, too shallow, or uniformly lit; limited exterior depth.
- **Common failures and fixes:** *Flat, evenly lit set* (fix: motivated pools of light and shade); *backdrops that look like backdrops* (fix: match perspective, light, and atmosphere; add depth layers in front); *walls with no wear* (fix: add handling marks, fade, repairs).

## 4.10 Digitally Generated and Virtual Environments

- **Design characteristics:** Environments built or generated digitally, as 3D scenes, matte paintings, virtual sets, or AI-generated imagery.
- **Staging and camera:** The camera can be placed anywhere, which creates the risk of unrealistic framing; for generated images, the camera position is implied by the prompt.
- **Lighting opportunities:** Lighting is simulated or implied and must be internally consistent.
- **Depth and movement:** Depth depends on the model or build; parallax may be missing in simple composites; generated video may produce morphing.
- **Realism:** Requires consistent scale, physical light behavior, material properties, and imperfection.
- **Continuity:** In 3D builds, high; in generated media, low unless controlled by references and locks.
- **Strengths:** Unlimited locations; no physical constraints.
- **Limitations:** "Too perfect" looks; geometry errors; repeated textures; text errors; instability across frames.
- **Common failures and fixes:** *Over-smooth and sterile* (fix: wear, asymmetry, clutter at logical places); *melting or morphing architecture* (fix: simplify; fix landmarks; shorten); *inconsistent perspective* (fix: state camera height and horizon); *signage garbage* (fix: avoid legible text or accept blur).

## 4.11 Hybrid Environments (Practical Locations, Sets, and Digital Extensions)

- **Design characteristics:** A real location or a partial set extended digitally (a street with a digital skyline; a cockpit set with a digital view).
- **Staging and camera:** Subjects act in the practical area; camera positions must respect the boundary of the real part (where the build ends).
- **Lighting opportunities:** Lighting on the practical part must match the digital extension (direction, color, intensity, atmosphere).
- **Depth and movement:** The transition between real and digital must preserve parallax and perspective.
- **Realism:** The weakest part sets the perceived realism; boundaries are the most common failure points.
- **Continuity:** The extension must stay consistent between shots.
- **Strengths:** Combines real texture with unlimited scale.
- **Limitations:** Requires planning; mismatches show at the seams.
- **Common failures and fixes:** *Lighting mismatch at the seam* (fix: match light direction, color, and atmospheric haze); *scale mismatch* (fix: shared reference objects); *parallax mismatch* (fix: ensure the extension moves correctly with camera motion); *edge halos or hard transitions* (fix: blend with atmosphere and depth layering).

## 4.12 Type-Selection Summary

| If the scene requires... | Consider | Because |
|---|---|---|
| Large scale and wonder | Natural, fantasy, or digital | Few physical constraints on scale |
| Intimacy and control | Interior or studio set | Controlled light and space |
| Clear routes and hazards | Industrial, urban, or natural terrain | Defined obstacles |
| Period authenticity | Historical (real location or built set) | Research-driven evidence |
| Subject clarity above all | Minimalist or abstract | Few competing elements |
| Unlimited flexibility | Digital or hybrid | Camera and layout freedom |

---
# 5. SPATIAL LAYERS AND ENVIRONMENTAL DEPTH

## 5.1 The Layers

| Layer | Definition | Typical role | Typical risk |
|---|---|---|---|
| **Foreground** | Between the camera and the subject | Frames the subject, adds depth, hides or reveals, adds texture | Blocking the subject; stealing attention; looking pasted on |
| **Midground (subject plane)** | The subject's distance and the area around it | Carries action, interaction, and the subject's immediate context | Cluttering the subject's silhouette |
| **Background** | Behind the subject, within the space | Establishes place, supplies tonal contrast and shape context | Merging with the subject; competing for attention |
| **Distant background** | The farthest visible layer (skyline, mountains, sky) | Establishes scale, region, and atmosphere | Looking flat or painted; inconsistent perspective |

**Why layers matter:** They convert a flat image into a perceived space. Each layer gives the viewer distance information relative to the others.

## 5.2 Depth Cues Provided by the Environment

These cues are established perceptual principles. They work *together*; more agreeing cues produce a stronger sense of depth.

| Cue | How it works | How to use it in the environment | How it fails |
|---|---|---|---|
| **Occlusion (overlap)** | Nearer objects hide parts of farther ones | Place objects so that they partially overlap across layers | No overlap makes layers look like separate cutouts |
| **Relative size** | Objects of known size appear smaller when farther | Include repeated objects of known size at different distances (lamps, poles, people) | Objects of inconsistent size confuse distance |
| **Linear perspective** | Parallel lines converge toward vanishing points | Use roads, rails, corridors, and building edges | Inconsistent vanishing points break the space |
| **Atmospheric perspective** | Distant objects appear lighter, lower in contrast, and bluer because of scattering in the air | Allow haze, mist, or distance fade to soften far layers | No fading makes distant layers look close; heavy haze erases detail |
| **Texture gradient** | Texture becomes finer and denser with distance | Use surfaces with visible texture (paving, grass, tiles) | Uniform texture or a repeating tile pattern removes the cue |
| **Contrast and tonal separation** | Layers separated by tone or color | Give each layer a slightly different tonal range | Same tone throughout merges layers |
| **Light and shadow** | Shadows reveal shape and distance | Use directional light and cast shadows | Flat light removes cues |
| **Parallax (during camera or subject movement)** | Near objects shift more than far ones relative to the viewpoint | Plan camera movement and layer separation | Layers that move together look flat |
| **Focus and defocus** | Out-of-focus areas read as farther or nearer than the plane of focus | Use depth of field to separate layers (covered in the focus knowledge base) | Blur applied uniformly to everything behind looks like a cutout |

## 5.3 Arranging Elements at Different Distances

**Method:**

1. **Choose the subject plane** and place the subject there.
2. **Add a foreground element** only if it frames, adds depth, or reveals; otherwise omit.
3. **Place 2–3 background elements** at distinct distances (nearby wall, mid-distance structure, far skyline).
4. **Check overlap:** at least one element should overlap another.
5. **Check relative size:** repeated items should shrink with distance.
6. **Check tone:** the layers should differ in value or color range.

## 5.4 Layers and Camera Position, Lens, and Movement

| Variable | Effect on layers |
|---|---|
| **Camera position** | Determines which background appears behind the subject and how layers overlap. Moving the camera changes overlap more than changing the lens does. |
| **Lens focal length (wide)** | Includes more of the layers; exaggerates the size difference between near and far objects when the camera is close to the foreground; increases the sense of depth. |
| **Lens focal length (long)** | Includes less; compresses distance; background appears magnified and closer to the subject. |
| **Camera height** | Changes how much of the ground plane is visible; a lower camera makes foreground objects larger and the horizon lower. |
| **Camera movement** | Creates parallax between layers; static shots rely on other cues. |

**Note:** Perspective (the relationship between near and far sizes) is determined mainly by viewpoint (camera position), and focal length determines how much of the scene from that position is captured. Compressed or expanded looks arise from the *combination* of camera distance and focal length chosen to frame the subject.

## 5.5 Creating Depth in Confined Spaces

| Technique | How it works | Example |
|---|---|---|
| **Diagonal views** | A corner-to-corner view has a longer visible distance than a straight-on wall view | Shoot a room from a corner toward the opposite corner |
| **Layered openings** | Doorways, arches, and windows reveal successive spaces | A hallway door opens to a room with a window beyond |
| **Foreground objects** | Partial overlap by furniture or edges | A chair back at the frame edge |
| **Light falloff** | Brightness decreases with distance from sources | A lamp near, a dimmer light at the back |
| **Reflections** | Mirrors and glass add apparent space | A mirror showing a second room |
| **Staggered furniture** | Objects at different distances | A table, a sofa, a bookcase arranged in a diagonal |
| **Atmosphere** | Light haze or dust adds a distance cue | Dust in a sunbeam across the room |

## 5.6 Avoiding a Flat, Cutout-Like, or Artificial Environment

| Symptom | Likely cause | Correction |
|---|---|---|
| Subject looks pasted onto the background | Mismatched light, no contact shadows, inconsistent perspective | Match light direction and color; add contact shadows; check the horizon height |
| Background looks like a painted backdrop | No parallax, no atmospheric depth, uniform sharpness | Add foreground or midground layers; add haze; vary focus |
| Layers have the same tone | No tonal separation | Adjust value and color range per layer |
| Everything is equally sharp and detailed | No hierarchy | Reduce background detail; apply depth falloff |
| Repeating textures or shapes | Tiling or cloning | Vary elements by size, spacing, and condition |
| Perspective lines disagree | Combined images or generated errors | Fix a single horizon and vanishing point set |

## 5.7 Preserving the Intended Subject–Background Relationship

Decide before framing:

- **How far is the background from the subject?** (touching, a few meters, or distant)
- **How visible should it be?** (sharp, soft, or dim)
- **What tonal relationship should it have?** (lighter, darker, or similar)
- **What should it reveal?** (place, scale, or nothing)

State these decisions and keep them stable across shots (Sections 12–13).

## 5.8 When a Deep Background Helps and When a Simpler Environment Is Stronger

| Situation | Deep background | Shallow or simple environment |
|---|---|---|
| **Establishing place or scale** | Preferred: shows geography and context | Insufficient |
| **Showing relationships between subject and surroundings** (isolation, belonging) | Useful | Less informative |
| **Action that depends on geography** | Preferred | Possible if geography is already known |
| **Dialogue and emotional close work** | Often distracting | Preferred: attention stays on faces |
| **Mystery or hidden information** | Useful when depth hides and reveals | Useful when withholding by limited view |
| **Abstract or stylized treatment** | Optional | Often preferred |
| **Confined space** | Possible through layered openings | Natural |
| **AI generation reliability** | More risk (more elements to drift) | Fewer errors |

**Principle:** Depth is a tool. Use it when the viewer needs spatial information; reduce it when the viewer needs concentration.

---

# 6. BACKGROUND COMPLEXITY, CLUTTER, AND VISUAL HIERARCHY

## 6.1 Definitions

- **Environmental complexity:** The number and variety of elements in the environment and the intricacy of their forms.
- **Clutter:** Elements that compete for attention without serving a function (narrative, spatial, atmospheric, or practical). Clutter is defined by *function and organization*, not by quantity.
- **Visual noise:** Unorganized detail (random shapes, textures, and contrast) that adds no information.
- **Visual hierarchy:** The order in which the eye is drawn to elements, determined by contrast, size, color, position, motion, and meaning.

## 6.2 Detailed vs. Cluttered; Simple vs. Weak

| | Description | Effect |
|---|---|---|
| **Detailed and organized** | Many elements, but arranged with a clear structure, tonal grouping, and meaning (a well-kept library; a busy market with a clear central aisle) | Rich yet readable |
| **Cluttered** | Many elements with similar importance and no structure (random objects of similar contrast) | Confusing; subject competes |
| **Simple and strong** | Few elements, clear shapes, deliberate tone | Clear subject; strong mood |
| **Simple and weak** | Few elements but confusing shapes, accidental lines, or unclear spatial relationships (a blank wall with an unexplained edge) | Looks unfinished or ambiguous |

**Principle:** Quality depends on **hierarchy, structure, and meaning**, not on the number of elements.

## 6.3 Element Roles

| Role | Definition | Design treatment |
|---|---|---|
| **Dominant** | The element or area that should be noticed first after the subject (or in place of it) | Clear shape, controlled contrast, correct placement |
| **Supporting** | Elements that add information and context | Visible but lower in contrast and size |
| **Incidental** | Elements that fill the space naturally | Low contrast, soft focus, or small; never eye-catching |

**Procedure:** For each shot, list the dominant, supporting, and incidental elements. If more than one element competes for the dominant role, resolve it.

## 6.4 Controlling Competing Points of Interest

| Competitor | Why it draws attention | Remedy |
|---|---|---|
| **Bright objects** | The eye goes to the brightest area | Lower brightness; move; mask; shade |
| **High-contrast patterns** | Stripes, checks, and grids attract the eye and can shimmer in video | Replace, soften, or reduce contrast |
| **Signage and text** | People read automatically | Blur, simplify, shift out of the main sightline, or ensure it supports the story |
| **Saturated color** | A strongly colored object stands out | Lower saturation; match tones; reposition |
| **Motion** | Moving elements draw attention | Reduce background movement; slow it; make it consistent |
| **Faces and eyes** | Viewers look at faces first | Avoid background faces near the subject unless intended |
| **Random objects** | An unusual object invites inspection | Remove or make it meaningful |

## 6.5 Protecting Readability

**Facial features and body silhouettes must remain readable.** A silhouette is the outline of the subject against the background; the eye identifies the subject mostly through its edges.

| Problem | What it looks like | Correction |
|---|---|---|
| **Tangents and mergers** | A vertical pole, tree trunk, or door frame appears to grow from the head; a horizon line cuts through the neck | Shift the camera or subject so lines pass beside the head; change camera height |
| **Same-tone background** | The subject's dark hair merges with a dark background | Raise background value; add rim light (lighting knowledge base); shift position |
| **Pattern behind the face** | A busy pattern interferes with facial detail | Replace or defocus; reduce contrast |
| **Bright window behind the head** | The face goes dark relative to the window | Reposition; reduce window brightness; change exposure balance |
| **Background faces or figures near the head** | They look like extra faces or stack with the subject | Move or remove |
| **Cropped objects at joints** | A chair arm appears to grow from the shoulder | Reposition objects or subjects |

**Negative space and accidental emptiness:**

- *Intentional negative space* has a stated function (isolation, calm, scale) and is consistent with the story.
- *Accidental emptiness* has no function and looks unfinished.
- **Test:** Can you state why the empty area is there? If not, add a meaningful element or reframe.

**Preserving detail without losing readability:** Place detail where it supports the story and keep contrast and sharpness lower than the subject's. Detail can be rich but quiet.

## 6.6 Clutter-Audit Procedure

**Step 1 — Squint test.** Look at the image through half-closed eyes (or blur it). Which shapes and bright areas stand out? Do they match the intended hierarchy?

**Step 2 — List elements by role.** Mark each element as dominant, supporting, or incidental.

**Step 3 — Check each element's function.** State a function (identify place, show history, supply scale, create route, supply atmosphere). Elements without a function are candidates for removal.

**Step 4 — Check contrast and saturation.** Identify elements brighter, more saturated, or higher in contrast than the subject.

**Step 5 — Check edges and tangents.** Trace lines that touch the subject's head, hands, or silhouette.

**Step 6 — Check repeated patterns and text.** Identify tiling, stripes, and signs.

**Step 7 — Check motion.** Identify moving elements and whether they compete.

**Step 8 — Decide corrective actions** (remove, move, soften, mask, reframe, change camera).

**Step 9 — Re-run the squint test.**

**Scoring (optional):** Count the elements that fail steps 3–7. 0–1: pass; 2–3: revise; 4 or more: redesign.

## 6.7 Examples of Corrective Changes

| Problem | Corrective change | Result |
|---|---|---|
| A café scene with many bright signs behind the speaker | Remove two signs; dim one; blur the rest | The face becomes the brightest, clearest element |
| A forest with trunks lined up behind the head | Move the camera 1 m to the left | Trunks fall to either side; the head is clear |
| A living room with many similar objects | Group objects into three clusters; leave open floor | A readable layout appears |
| A street with a bright white van | Replace with a darker van or move it out of the sightline | The subject regains priority |
| An empty wall behind a close-up that feels unfinished | Add soft tonal gradient or a framed object consistent with the character | The background supports the face |
| A busy plaza behind a dialogue | Thin the crowd; slow background motion; lower contrast | Dialogue stays the focus |

---

# 7. LOCATION SELECTION AND LOCATION SCOUTING

**Scope:** This section applies to real locations used for filming and to real places used as the basis of generated scenes. Permission, privacy, and production constraints are covered at a general level; local rules and legal requirements vary and should be checked by the production. Nothing here is legal advice.

## 7.1 What to Evaluate

| Factor | Questions to ask | Why it matters |
|---|---|---|
| **Narrative suitability** | Does the place express the story's setting and the scene's purpose? | A beautiful but wrong place misleads |
| **Spatial dimensions and usable angles** | Is there enough room for the action? What camera positions and backgrounds are available? | Limits shot variety and staging |
| **Camera access and movement clearance** | Can the camera be placed and moved where needed? Are there obstructions? | Prevents compromises in coverage |
| **Subject movement and blocking** | Can subjects walk, sit, and interact as planned? Are surfaces suitable? | The action must fit |
| **Natural and artificial lighting** | Where do windows and fixtures sit? What are the direction and quality of light? | Determines the look and the need for supplementary lighting |
| **Time-of-day changes** | How does the light change across the filming window? | Affects continuity and schedule |
| **Weather and environmental variability** | What are the likely conditions? What cover is available? | Affects continuity and safety |
| **Background activity and unwanted movement** | What traffic, people, signage, or construction will appear? | May contradict the setting or distract |
| **Practical hazards and accessibility** | Are there unsafe surfaces, heights, traffic, or hazards? Can crew and equipment reach the place? | Safety and feasibility |
| **Sound-related considerations** | What ambient noise (traffic, aircraft, machinery) will be present? | Environmental noise affects recording and mood |
| **Continuity risks** | Will conditions change between shooting days (weather, plants, construction)? | Matches across shots |
| **Permission, privacy, and production constraints** | Is permission needed? Are there restrictions on filming, people, or private property? | Practical and legal feasibility |
| **Landmarks, entrances, exits, and distinctive features** | What features help the audience understand and orient? | Supports establishing and geography |

## 7.2 Location-Scouting Checklist

**Before the visit:**
- ☐ Scene requirements listed (purpose, objective, must-know list, action needs).
- ☐ Candidate types and a list of must-have features.
- ☐ Sun-path and weather information for the filming window.

**During the visit:**
- ☐ Photograph and video the location from multiple positions and heights.
- ☐ Record dimensions (room size, ceiling height, door widths) and mark them on a floor plan.
- ☐ Test camera positions for backgrounds behind subject positions.
- ☐ Note windows, practical lights, and the direction of daylight at different times.
- ☐ Note background activity (traffic, pedestrians, machinery) and when it changes.
- ☐ Check surfaces for movement (slip, noise, stairs).
- ☐ Identify hazards and accessibility limits.
- ☐ Listen for ambient noise at the intended filming time.
- ☐ Check power, space for equipment, and staging areas.
- ☐ Identify visible modern or inconsistent elements that must be hidden or removed.
- ☐ Identify landmarks, entrances, exits, and distinctive features.
- ☐ Note permission contacts and rules.

**After the visit:**
- ☐ Draw a layout map with camera positions and backgrounds.
- ☐ Score the location (7.3).
- ☐ Identify required modifications (dressing, removal, digital cleanup).
- ☐ Record risks and mitigations.

## 7.3 Location Suitability Scoring System

**Scoring scale (per criterion):** 0 = unsuitable, 1 = poor, 2 = workable with major changes, 3 = good, 4 = excellent.

**Weights (importance):** 3 = critical to the scene, 2 = important, 1 = minor.

| Criterion | Weight | Score (0–4) | Weighted |
|---|---|---|---|
| Narrative suitability | 3 | | |
| Spatial dimensions and usable angles | 3 | | |
| Camera access and clearance | 2 | | |
| Blocking and subject movement | 2 | | |
| Lighting conditions | 3 | | |
| Time-of-day stability | 2 | | |
| Weather and variability | 2 | | |
| Background activity control | 2 | | |
| Hazards and accessibility | 3 | | |
| Sound environment | 1 | | |
| Continuity risk | 2 | | |
| Permission, privacy, and constraints | 3 | | |
| Landmarks, entrances, exits | 2 | | |

**Formula:** *Suitability % = (sum of weighted scores) ÷ (sum of weights × 4) × 100.*

| Result | Interpretation |
|---|---|
| **80% or higher** | Strong candidate |
| **65–79%** | Workable with listed mitigations |
| **50–64%** | Risky; consider alternatives or major modifications |
| **Below 50%** | Unsuitable |

**Knockout rule:** A score of **0** on any weight-3 criterion makes the location unsuitable regardless of the total, because the scene cannot be done safely, legally, or meaningfully there.

## 7.4 Why a Visually Attractive Location May Still Be Unsuitable

| Attractive feature | Why it may fail the scene | Example |
|---|---|---|
| **Stunning view** | The view dominates the subject; the story is about confinement | A glass penthouse for a scene about claustrophobia |
| **Beautiful, uniform light** | Light changes quickly, or the sun will be in the wrong direction at the scheduled time | A beach at sunset shot over six hours |
| **Photogenic decay** | Hazards or contamination prevent access; the decay contradicts the character's circumstances | A ruin for a scene set in a well-kept home |
| **Large open space** | The scene needs intimacy; the space swallows the dialogue and the sound | A hall for a whispered conversation |
| **Authentic period building** | Visible modern fixtures and traffic make it impossible to match the period | A historic street with modern signage and parked cars |
| **Quiet and remote** | Access for crew and equipment is impossible | A mountain hut with no road |
| **Rich detail** | The detail competes with the subject or cannot be controlled | A cluttered market with unstoppable crowds |
| **Landmark recognizability** | The location is so famous that it distracts or implies a specific place | A famous bridge for a generic city |

---
# 8. SET DESIGN, SET DRESSING, PROPS, AND ENVIRONMENTAL EVIDENCE

## 8.1 Distinguishing the Layers of a Built Environment

| Layer | Definition | Examples | Production note |
|---|---|---|---|
| **Architecture** | The permanent structure and spatial organization of a place | Walls, floors, ceilings, stairs, windows, doors, bridges | In a real location, found; on a set, built or digitally modeled |
| **Set construction** | Built elements that create or modify the space | Flats (wall panels), platforms, built stairs, partial rooms | Used when no suitable location exists or control is needed |
| **Set dressing** | Movable items added to make the space specific and inhabited | Furniture, curtains, rugs, pictures, plants, clutter, signage | Usually not handled by performers |
| **Props** | Objects handled by performers or central to action | A cup, a phone, a key, a suitcase | The line with set dressing varies between productions |
| **Background objects** | Items visible behind or around the subject that are not handled | Shelf contents, distant vehicles, items on a far counter | They may belong to dressing or to the location itself |

## 8.2 How Objects Communicate

Objects communicate through **evidence**. Each can imply:

| Information | How objects imply it | Example |
|---|---|---|
| **Use** | Wear patterns, position, and condition show how often and how an object is used | A worn spot on a chair arm; a path through dust |
| **Ownership** | Personal items and arrangement show who lives or works there | Photographs, labeled mugs, a coat on a particular hook |
| **Age** | Materials, technology, and condition show age | Faded wallpaper; an older appliance |
| **Occupation** | Tools, documents, and furniture show work | Sketches, a pharmacy scale, a toolbox |
| **Social conditions** | Quality, repairs, and quantity show circumstances | Repaired furniture; stacked boxes in a small flat |
| **Previous events** | Displacement, damage, or residue show what happened | A broken window with fresh glass on the floor |
| **Character behavior** | Habits are visible in how things are organized | Meticulously labeled shelves; unwashed dishes |

## 8.3 Implying a Believable History Without Overexplaining

**Evidence chain method:**

1. **Claim:** State the fact the environment should imply ("the occupant lives alone and recently stopped working").
2. **Evidence:** Choose 2–4 pieces of evidence that support it (a single mug in the drying rack; a work lanyard on a hook; unopened mail).
3. **Placement:** Place each item where it would naturally be.
4. **Visibility:** Ensure at least two items are visible at the intended shot size, and keep the rest as quiet support.
5. **Restraint:** Stop when the claim is clear. More evidence than needed produces a staged feel.

**Principles:**

- **Consistent clues are stronger than many weak ones.** Three agreeing details outweigh ten unrelated ones.
- **Ambiguity is allowed.** Evidence can invite inference without confirming it.
- **Match evidence to character.** Objects must agree with the character's established traits and the story's facts.
- **Avoid the "museum" effect.** Items placed to be noticed, with no signs of ordinary use, look staged.

## 8.4 Material Authenticity

- **Materials behave in recognizable ways:** wood grains, metal oxidizes, paint chips, fabric wrinkles, plaster cracks along stress lines.
- **Authenticity comes from specific properties:** surface finish (matte or glossy), edge wear, seam lines, variation, and imperfection.
- **Common failures:** Uniform, plasticky surfaces; materials inappropriate for the setting (laminate in a period room); textures that tile obviously.
- **Fix:** Specify the material and its condition (for example, "painted plaster, slightly flaking near the window frame").

## 8.5 Wear, Damage, Dirt, Weathering, and Maintenance

**Principle:** *Wear follows use and exposure.* Realistic aging has causes.

| Pattern | Where it appears | Why |
|---|---|---|
| **Handling wear** | Door handles, light switches, banister rails, chair arms | Frequent touch |
| **Foot-traffic wear** | Floor paths, stair edges, thresholds | Footfalls |
| **Water damage** | Under windows, near pipes, at roof leaks, along lower walls | Moisture paths and gravity |
| **Sun fade** | Surfaces facing windows | Light exposure |
| **Dirt accumulation** | Corners, under furniture, along wall bases, in recesses | Dust settles; cleaning does not reach |
| **Weathering outdoors** | Windward faces, horizontal surfaces, drip lines | Rain, wind, sun |
| **Maintenance patches** | Repaints, replaced parts, added bolts | Repairs over time |

**Failure modes:**

- **Implausible cleanliness:** Everything pristine in a used place (or in a futuristic setting presented as lived-in).
- **Excessive distressing:** Grime and damage applied uniformly and decoratively with no cause.
- **Inconsistent maintenance:** A pristine door in a collapsing wall without reason.

**Correction:** Ask "What caused this wear?" for each area; apply wear in the logical places and leave other areas clean.

## 8.6 Object Placement and Believable Use

| Principle | Guidance |
|---|---|
| **Objects sit where they are used** | Kettle near a socket; coats near the door; tools near the bench |
| **Objects show recent use** | A half-full cup; an open book; a drawer slightly ajar |
| **Objects obey gravity and support** | Items rest on surfaces; hanging items have hooks |
| **Spacing follows habits** | Neat in some zones, messy in others, according to the occupant |
| **Orientation matters** | Handles face the user; chairs face tables or each other |

## 8.7 Functional vs. Decorative Details

- **Functional details** have a purpose in the story or the space: a fire exit, a light switch, a trash bin.
- **Decorative details** add character without function: a poster, a plant.

**Balance:** A space made entirely of decorative details looks like a display; a space with only functional ones looks sterile. Use functional details to anchor realism and decorative details to express personality.

## 8.8 Repeated Patterns, Inconsistent Scale, and Other Artificial Signs

| Sign | Why it looks artificial | Correction |
|---|---|---|
| **Repeated patterns (identical books, bricks, windows, trees)** | Real objects vary in size, spacing, condition, and orientation | Introduce variation and breaks in the pattern |
| **Inconsistent object scale** | Items of known size appear at the wrong size | Check against standard dimensions (Section 9) |
| **Implausible cleanliness** | No signs of use | Add traces of use at logical places |
| **Excessive distressing** | Wear with no cause | Reduce and cluster by cause |
| **Objects contradicting purpose, period, or weather** | Break plausibility | Review every object against purpose, period, and weather (for example, a wet umbrella in a dry scene, a modern appliance in a period kitchen) |
| **Background objects that resemble unrelated objects** | A lamp behind the head reads as a hat; a plant looks like it grows from the head; a shelf corner looks like a horn | Move the camera or object; change the silhouette |
| **Misleading silhouettes** | Outlines suggest a different object or a person | Check silhouettes at squinting scale and in the thumbnail; alter shape or position |

## 8.9 Environmental Storytelling Through Visible Evidence

**Principle:** Show *traces of events and behaviors* rather than explaining them.

| Instead of | Use |
|---|---|
| A character stating "He's been gone for weeks." | Dust on the coat on the hook; newspapers stacked at the door |
| A caption "This is a poor neighborhood." | Repaired shutters; shared appliances; modest but cared-for details |
| A line "She's obsessed with the case." | Wall of notes, string, coffee cups; the sleeping bag under the desk |
| A voice-over about danger | A boarded window; a broken lock; scuff marks on the doorframe |

**Method:**

1. Identify the information (a fact or a trait).
2. List two or three observable traces that would exist if it were true.
3. Place them naturally.
4. Verify they are visible and legible at the intended framing.
5. Remove explanatory elements (labels, captions) unless the setting would naturally have them.

---

# 9. SCALE, PROPORTION, AND PHYSICAL PLAUSIBILITY

## 9.1 Why It Matters

Viewers use familiar objects (doors, chairs, cars, people) as **scale references**. When the relationships among those objects are wrong, the environment looks fake, miniature, or dreamlike, even if each object looks good alone.

## 9.2 Typical Dimensions (Approximate Values)

**These are typical figures that vary by country, building age, and design. Use them as starting estimates, not standards.**

| Object | Typical dimension (approximate) |
|---|---|
| Standing adult | About 1.5–1.9 m tall |
| Interior door | About 2.0–2.1 m high; 0.8–0.9 m wide |
| Residential ceiling | About 2.4–2.7 m |
| Stair riser (step height) | About 0.15–0.19 m |
| Stair tread (step depth) | About 0.25–0.30 m |
| Handrail height | About 0.9–1.0 m |
| Dining table height | About 0.72–0.76 m |
| Chair seat height | About 0.43–0.46 m |
| Kitchen counter height | About 0.85–0.95 m |
| Window sill height | About 0.8–1.0 m |
| Car (passenger) | About 4–4.8 m long; 1.4–1.6 m high |
| Road lane width | About 3.0–3.7 m |
| Street lamp pole | About 5–10 m |
| Single-story building eaves | About 3 m |

## 9.3 Scale Cues, Perspective Consistency, and Horizon Placement

**Scale cues** are objects with known size and the relationships among them. **Perspective consistency** means that all elements follow the same viewpoint and vanishing points.

**Horizon principle (established perspective geometry):** On level ground, the horizon line appears at the camera's height. Any object whose top is at the camera's height has its top on the horizon line, no matter how far away it is. Consequently:

- If the camera is at about adult eye height (roughly 1.5–1.7 m), the eyes of standing adults of similar height appear at about the horizon line at all distances.
- A subject whose eyes are noticeably *above* the horizon line is taller than the camera height (or the ground rises).
- A subject whose head is *far below* the horizon line is shorter, standing on lower ground, or the perspective is inconsistent.
- A lower camera moves the horizon lower in the frame and makes subjects appear to tower; a higher camera raises the horizon.

**Use:** To check scale and perspective, draw the horizon line and see whether standing figures and similar-height objects align with it appropriately.

## 9.4 Contact With the Ground and Nearby Objects

- **Ground contact:** Subjects and objects must visibly rest on a surface: contact shadows, footprints, bases that meet the ground.
- **Relationship to nearby objects:** The subject's body should relate correctly to chairs, doors, and counters (a standing adult's hand reaches a counter at hip height).
- **Floating and sinking cues:** A missing contact shadow or a base that does not sit on the ground makes objects float; a base below the ground line makes them sink.

## 9.5 Diagnostic Examples

| Symptom | Check | Likely cause | Correction |
|---|---|---|---|
| **Subject looks too large** | Compare subject height to door, chair, and counter | Subject nearer to the camera than the environment's scale implies; background objects too small | Adjust object sizes or distance; verify horizon alignment |
| **Subject looks too small** | Same | Oversized furniture or architecture; camera too low | Reduce object size; adjust camera height; add a scale reference |
| **Furniture looks miniature** | Compare chair seat height to the subject's knee; table height to the subject's hip | Furniture undersized; wide lens close to furniture; shallow depth blur imitating a miniature effect | Scale furniture; reduce blur contrast; increase distance |
| **Trees or buildings with inconsistent scale** | Compare tree height to nearby doors and cars | Elements generated or combined at different scales | Fix a reference object (a door, a person) and scale others to it |
| **Repeating objects change size implausibly** | Measure successive items against perspective | Perspective not applied (lamps or windows not shrinking with distance); random scaling | Apply consistent diminishing size along the vanishing lines |
| **Subject appears to float or sink** | Look for contact shadows and base alignment | Light mismatch; ground plane unclear; composite error | Add contact shadows; define the ground plane; align feet with the surface |
| **Doors, stairs, windows, or passages cannot plausibly be used** | Compare the opening to the subject's dimensions; check stair riser and tread uniformity; check direction of opening | Wrong proportions; stairs with changing step heights; doors with no handle or blocked swing | Resize to usable dimensions; regularize stairs; define swing direction |
| **Background geometry changes between frames** | Compare landmarks across frames | Generation instability; unlocked layout | Simplify background; fix a landmark list; shorten clips; use a reference frame |

## 9.6 How Lens, Distance, Viewpoint, and Framing Affect Perceived Scale

**Established principle:** *Perspective* (the relative size of near and far objects) is determined mainly by **viewpoint** (the camera's position), not by focal length itself. The **focal length** (with the sensor size) determines the **field of view**: how much of the scene is captured from that position.

**Do not attribute every perspective effect to focal length alone.** Several different variables can produce apparent scale distortion:

| Cause | What happens | Example |
|---|---|---|
| **Camera distance to the nearest object** | A very close near object appears much larger than a far one | A hand near the lens appears huge |
| **Camera height** | Low camera makes the foreground and subjects appear taller and exaggerates height; high camera makes subjects appear smaller | A low camera on a child's toy makes it look like a monument |
| **Camera tilt** | Tilting up or down makes vertical lines converge | A building seems to lean when the camera tilts up |
| **Field of view (wide lens at close range)** | Strong difference between near and far sizes; edge stretching in wide-angle frames | Faces at the edge of a wide frame look stretched |
| **Lens projection and aberration** | Some lenses bend straight lines (barrel distortion) | Curved horizon near the frame edge |
| **Framing and cropping** | Excluding scale references removes cues | A cropped shot hides the doorway that shows scale |
| **Depth-of-field blur** | Strong blur can make real scenes look miniature | A high-angle shot with blurred top and bottom |
| **Forced perspective (deliberate)** | Objects at different distances are arranged to appear the same size | A giant-looking figure beside a smaller one placed farther away |
| **Generation error** | Models may draw objects at inconsistent scales | A door too small for the figure |

**Diagnostic order for suspected scale distortion:** (1) check camera height and tilt; (2) check distance to near objects; (3) check field of view and edge position; (4) check the presence of scale references; (5) check blur; (6) only then consider the focal length.

---

# 10. ENVIRONMENTAL LIGHTING AND ATMOSPHERE

**Scope reminder:** This section is focused on how the *environment* interacts with light and atmosphere: what the place offers, shapes, reflects, and diffuses. It does not replace the lighting knowledge base, which covers the design and control of light itself.

## 10.1 The Environment as a Condition of Light

The environment determines *what light is available and how it behaves*: where light enters, what it strikes, what it reflects, what it scatters through, and what it conceals. A good environmental design makes the light *plausible* (explained by sources and surfaces) and *useful* (shapes mood and readability).

## 10.2 Light Sources in the Environment

| Source | What it provides | Environmental considerations | Failure |
|---|---|---|---|
| **Sun and sky** | Dominant exterior light; direction and quality depend on time and weather | Shadows, sky color, and the angle of light must agree | Shadows pointing in different directions |
| **Windows and skylights** | Daylight entering interiors | Window size, orientation, and curtains control quantity and softness | Interior brightness inconsistent with window brightness |
| **Practical lights (lamps, fixtures, candles, screens, signs)** | Visible sources in the scene | Their position, color, and brightness motivate light | A lit lamp with no effect on nearby surfaces |
| **Reflected light (bounce)** | Light from lit surfaces onto others | Surface color tints bounced light | Neutral shadows next to a bright colored wall |
| **City glow and spill light** | Ambient light from surroundings at night | Gives night scenes base illumination and color | Total darkness in an urban night |
| **Fire and flickering sources** | Warm, moving light | Needs flicker, falloff, and reaction on surfaces | Static light from a fire |

**Motivated-light check:** For each visible light effect, find its source in the environment. If no source can be named, either add one or remove the effect.

## 10.3 Surfaces and Materials

| Property | Behavior | Effect on the image | Failure |
|---|---|---|---|
| **Reflectance (light or dark surfaces)** | Light surfaces reflect more light and raise ambient levels; dark surfaces absorb | A white room is brighter and softer; a dark room has deeper shadows | Dark walls with bright fill that contradicts the room |
| **Gloss (specular) vs. matte (diffuse)** | Glossy surfaces create highlights and reflections; matte surfaces scatter | Wet pavement shows reflected lights; matte plaster shows soft gradients | Uniform sheen on everything |
| **Color** | Colored surfaces tint bounced light | A red wall casts a warm tint nearby | No color bleed on adjacent surfaces |
| **Translucency** | Thin fabrics and leaves transmit light | Curtains glow; leaves look lit from behind | Opaque curtains with window glare |
| **Wetness** | Wet surfaces become darker and more reflective | Rain-wet streets mirror lights | Rain without wet surfaces |
| **Metal and glass** | Strong reflections; glass shows both reflections and transmission | Windows show the interior or exterior depending on light levels | Reflections inconsistent with surroundings |

## 10.4 Architecture Shaping Light

| Feature | Effect | Example |
|---|---|---|
| **Window size and depth** | Depth of the wall creates edge shading and modulates direct sun | Sun patches that move across the floor |
| **Overhangs, awnings, and canopies** | Shade and shape light | A shaded porch with a bright yard beyond |
| **Enclosure and ceiling height** | Higher ceilings allow softer, more distant light; low ceilings create compact light | A low-ceilinged cellar with a single bulb |
| **Corridors and doorways** | Channel light into bands and spill | A bright doorway at the end of a dark hall |
| **Courtyards and canyons (streets)** | Direct sun reaches the ground only at certain times | Narrow streets lit by a thin shaft |
| **Surfaces near the subject** | Nearby walls and floors act as fill | A bright floor lifts shadows under the chin |

## 10.5 Weather and Atmosphere as Light Modifiers

| Condition | Effect on light | Visible evidence | Typical failure |
|---|---|---|---|
| **Overcast** | A large, soft source: low contrast, weak shadows | Diffuse shadows; muted colors | Hard shadows under an overcast sky |
| **Clear sun** | Strong direction and contrast | Crisp shadows; high highlights | Missing shadows |
| **Fog and mist** | Scatter light; reduce contrast and distance; create glow around lights | Faded distance; halos around lamps | Fog with perfect clarity in the distance |
| **Haze** | Light scattering; adds depth cues | Soft distance and bluish far layers | Uniform haze on near and far elements |
| **Dust and smoke** | Makes light beams visible; adds texture | Shafts of light in particles | Beams visible with no particles or source |
| **Rain** | Darkens surfaces; adds reflections; diffuses light | Wet streets, streaks, ripples | Rain with dry ground |
| **Snow** | Raises ambient light by reflection; softens shadows | Bright ground; blue shadows | Snow with dark, unlit ground |
| **Heat shimmer** | Distorts distant details | Wavering horizon | Inconsistent distortion |

**Atmospheric perspective (established principle):** Air scatters light, so distant objects look lighter, lower in contrast, and (outdoors) shifted toward the sky color. The effect increases with distance and with haze or moisture. Use it for depth; avoid it when the scene must look clear and close (for example, a studio interior).

**Visible light beams (volumetric light):** A beam is visible only when it passes through particles (dust, smoke, mist) and the viewer looks at it from an angle that scatters light toward the camera, typically against a darker background. Specify the particles as well as the source.

## 10.6 Color of the Environment

- **Palette from materials:** The colors in the environment come from surfaces and light sources. Choose materials and light sources that jointly produce the palette.
- **Mixed color temperatures:** A scene can include different light colors (warm lamp indoors, cooler daylight at a window) if each is motivated. As approximate typical values, tungsten household lamps are warm (about 2700–3200 K), midday daylight is neutral to slightly cool (about 5500–6500 K), and overcast daylight is cooler; fluorescent tubes can show a greenish cast. These numbers vary by source.
- **Failure:** A palette imposed over the environment with no source (blue light with no blue source).

## 10.7 Consistency Tests

| Test | What to check |
|---|---|
| **Shadow direction** | All shadows in a daylight scene should point away from the same sun direction. |
| **Shadow length vs. time** | Shadow length ≈ object height ÷ tan(sun elevation). At about 45° elevation the shadow equals the object's height; at about 30°, about 1.7 times; at about 15°, about 3.7 times. |
| **Interior and exterior exposure** | Windows in a daytime interior appear brighter than the interior unless exposure is adjusted for them. |
| **Reflections** | Reflections show the objects and lights in front of the reflective surface and agree with perspective. |
| **Falloff** | Brightness decreases with distance from a lamp. |
| **Wetness and reflection** | Wet surfaces reflect nearby lights. |
| **Atmospheric depth** | Distant elements are consistently lighter and lower in contrast. |

## 10.8 Interaction With Environment Types

| Environment type | Light logic to preserve | Common error |
|---|---|---|
| **Forest** | Light filtered through canopy; dappled; shaded undergrowth | Even bright light everywhere |
| **Urban night** | Many motivated artificial sources; wet reflections; spill | Dark background with no sources |
| **Home interior** | Window plus lamps; local pools; bounce off walls | A single flat light source |
| **Industrial** | Harsh overhead fixtures; indicator lights | Soft, cinematic light that ignores fixtures |
| **Cave** | Little ambient light; localized sources | Evenly lit rock |
| **Studio set** | Motivated by windows and practicals | Hidden light sources with no motivation |
| **Digital or generated** | Consistent light logic across all elements | Elements lit by different implied suns |

---
# 11. ENVIRONMENTAL DYNAMICS: WEATHER, TIME, SEASON, AND BACKGROUND ACTIVITY

## 11.1 Principle

An environment is not a still image; it is a **state that changes with time and conditions**. Weather, time of day, season, and the activity of people, vehicles, and animals all give the environment a *current condition*. Each condition leaves visible evidence on surfaces, in light, in clothing, and in behavior. When the evidence agrees, the world feels real; when it conflicts, viewers sense an error even if they cannot say why.

## 11.2 Weather

| Condition | Evidence in the environment | Evidence in subjects | Typical failures and fixes |
|---|---|---|---|
| **Rain** | Wet, darker surfaces; puddles with ripples; streaks; reflections; dripping edges; muted color | Wet hair and clothing; umbrellas or hoods; hunched posture | *Rain with dry ground or dry clothing.* Fix: state wet surfaces and wet subjects. *Rain visible against light but invisible against dark.* Fix: backlight or dark backgrounds for streaks |
| **Snow** | Accumulation on horizontal surfaces; bright ground; muffled look; footprints | Heavy clothing; visible breath in cold air | *Snow with bare ground in sheltered and exposed spots alike.* Fix: accumulate on tops and windward sides; thinner under cover |
| **Fog and mist** | Reduced distance visibility; glow around lights; soft contrast | Moisture on clothing | *Uniform fog with sharp distant detail.* Fix: fade with distance |
| **Wind** | Moving foliage, flags, litter, fabric, hair; direction consistent | Leaning posture; clothing movement | *Elements moving in different directions.* Fix: one wind direction and speed |
| **Heat** | Strong shadows; dry ground; shimmer over surfaces; seeking shade | Light clothing; sweat; slower movement | *Heat with lush wet ground and heavy clothing.* Fix: align all evidence |
| **Cold** | Frost, ice, condensation; visible breath | Layers; stiff posture | *Visible breath only in some shots.* Fix: apply consistently |
| **Storm** | Dark sky; strong wind; heavy rain; flashes | Bracing; hurried movement | *Storm with calm trees.* Fix: link wind and rain intensity |
| **Clear weather** | Crisp shadows; distant clarity | Light clothing appropriate to temperature | *Clear weather with soft shadows.* Fix: match shadows to sky |

## 11.3 Time of Day

| Time | Light and environment evidence | Activity evidence | Failure |
|---|---|---|---|
| **Dawn** | Low, cool then warm light; mist common; few lights | Few people; early deliveries; lights switching off | A sunlit midday shadow length |
| **Morning** | Rising sun; long shadows shortening; fresh color | Commuters; shops opening | Closed shops with people shopping |
| **Midday** | High sun; short shadows; strong top light; little color variety | Peak activity; lunch crowds | Long shadows |
| **Afternoon** | Descending sun; shadows lengthening | School exits; traffic building | Shadows pointing the wrong way |
| **Dusk (golden and blue hours)** | Low warm light then cool, soft light; artificial lights switch on; sky gradient | Lamps lit; people heading home | Sky with a sun at noon height |
| **Night** | Artificial light dominates; dark sky; wet reflections; pools of light | Reduced traffic; open late venues | No light sources; bright sky |

**Shadow-length check:** Shadow length ≈ object height ÷ tan(sun elevation). Use it to confirm that stated time-of-day agrees with the shadows (Section 10.7).

## 11.4 Season

| Season cue | What to show | Failure |
|---|---|---|
| **Vegetation** | Leaf color and density; blossoms; bare branches | Green leaves in a winter scene |
| **Ground** | Mud, snow, dry grass, fallen leaves | Clean pavement in a leaf-fall season |
| **Light angle and day length** | Sun elevation lower in winter in mid-latitudes; earlier dusk | Summer sun height in winter |
| **Clothing and behavior** | Layers or light wear; outdoor seating or indoor gatherings | Heavy coats with sun-baked ground |
| **Objects** | Heaters, fans, holiday items, seasonal food | Out-of-season objects |

## 11.5 Background Activity

**Definition:** Background activity is the movement and presence of people, vehicles, animals, machinery, and natural elements behind or around the subject.

| Function | How it helps | Risk |
|---|---|---|
| **Gives life and plausibility** | A place with no activity can look like a model or set | Excess becomes clutter |
| **Establishes time and place** | Commuters, markets, farm work, night patrols | Anachronistic or contradictory activity |
| **Supplies scale and depth** | People and vehicles at distances | Inconsistent size with distance |
| **Creates tension or contrast** | Calm subject in a busy crowd; a lone figure in an empty street | Distracts from the subject |

**Design rules:**

1. **Make background behavior believable:** people walk, talk, wait, work; vehicles follow lanes and directions.
2. **Keep direction and speed consistent** with the setting (traffic flows, pedestrians cross at crossings).
3. **Control density near the subject:** keep the subject's immediate area clean unless the crowd is the point.
4. **Avoid background figures who look at the camera** unless intended.
5. **Avoid synchronized or cloned movement;** vary clothing, speed, and direction.
6. **Keep background motion lower in contrast and slower than the primary action** unless it is the story.
7. **Do not let background movement start or stop at the same time as the subject's** unless coordinated.
8. **State what moves and what does not.** Unspecified elements may move unpredictably in generated video.

**AI generation considerations (tendencies, not guarantees):** Generated crowds can morph, duplicate, or merge; vehicles can change shape or direction; distant text can scramble. Reduce density, limit the number of distinct actors, keep them small or soft, and specify their behavior ("three pedestrians walk left to right in the distance at a steady pace").

## 11.6 Environmental Change Within a Scene

| Change | How to show | Cautions |
|---|---|---|
| **Weather arrives** | Cloud shadow passes; light level drops; wind rises; first drops; surfaces darken | Sudden complete rain without buildup |
| **Time passes** | Shadows move; light color changes; lamps switch on | Rapid, unmotivated light changes |
| **Light flickers or fails** | Practical source flickers; spill changes | Change with no source |
| **Environment is damaged or transformed** | Progressive evidence (cracks, smoke, debris) | Jumps in state without a visible cause |

---

# 12. ENVIRONMENT AND THE SUBJECT: SEPARATION, PLACEMENT, AND INTEGRATION

## 12.1 The Camera Position Selects the Background

**Principle:** The background is a function of **where the camera stands and where it points** (Section 1.3). The simplest way to improve a background is often to move the camera or the subject, not to change the environment.

**Background walk (practical method):**

1. Place the subject.
2. Walk around the subject at the planned camera height, looking at what is behind them from each angle.
3. Mark positions where the background is clean, supports the story, and avoids tangents.
4. Choose the best position and confirm the lens needed to frame the subject there.

## 12.2 Separation Methods

**Separation** is the visual distinction between the subject and the background.

| Method | How it works | Example | Limitation |
|---|---|---|---|
| **Tonal contrast** | Subject lighter or darker than the background | A light-skinned subject against a dark door | Fails if tones match |
| **Color contrast** | Subject differs in hue or saturation | A red coat against green foliage | Can look forced if overdone |
| **Depth separation** | Background is far enough for focus or haze to separate it | A subject in front of a distant skyline | Needs space |
| **Light separation** | The subject is lit differently from the background (a brighter or darker background; rim light) | A backlit subject against a shaded wall | Requires light control |
| **Silhouette against a clean area** | The subject's outline stands against a simple background | A figure against a plain sky | Requires a clean background |
| **Motion contrast** | Subject moves against a still background, or the opposite | A runner passing a static wall | Distracting if motion is excessive |
| **Focus separation** | Subject sharp, background soft | Shallow depth of field (see the focus knowledge base) | Can look artificial if background blur is uniform |
| **Size and placement** | Subject occupies a position with clear space around | Subject framed against an open area | May feel isolated |

## 12.3 Subject Placement Within the Environment

| Placement principle | Effect | Example |
|---|---|---|
| **Place relative to landmarks** | Shows where the subject is and what they relate to | A person near the exit, a person far from it |
| **Use frame-within-frame devices (doorways, windows, arches)** | Isolates and contextualizes | A subject seen through a doorway |
| **Place the subject in the environment's visual structure** | Aligns with lines or negative space | A subject at the end of a corridor |
| **Maintain consistent placement across shots** | Supports continuity | The subject always beside the same window |
| **Give the subject space to act** | Supports movement and gesture | Clear floor around a person who must walk |

## 12.4 Subject–Environment Relationships

These relationships are **context-dependent**: the same arrangement can mean different things in different stories.

| Relationship | Possible environmental design | Possible meaning (not guaranteed) |
|---|---|---|
| **Dwarfed** | Large architecture or landscape relative to the subject | Insignificance, awe, vulnerability |
| **Framed** | Doors, windows, or arches surrounding the subject | Importance, confinement, observation |
| **Trapped** | Narrowing space, barriers, few exits | Danger, pressure |
| **Belonging** | Subject's colors and shapes echo the environment; personal objects around | Home, identity |
| **Contrasting** | Subject differs from the environment in color, tone, or style | Outsider, difference |
| **Merging** | Subject's tones blend with the background | Camouflage, loss of identity, or a failure of separation |
| **Controlling** | The subject occupies the center of a space with others arranged around | Authority, focus |

## 12.5 Integrating the Subject With the Environment

Integration means the subject *looks like it is in* the environment. It matters most in composites, virtual sets, and generated images.

| Element | Requirement | Failure sign |
|---|---|---|
| **Light direction and color** | The subject's light matches the environment's sources | Subject lit from the left, shadows on the ground to the right |
| **Contact** | Feet, hands, and objects touch surfaces with contact shadows | Floating subject |
| **Scale** | Subject's size agrees with the environment (Section 9) | Subject too large or small |
| **Perspective** | Camera height and horizon agree | Subject seen from a different angle than the background |
| **Atmosphere** | Haze, dust, and color of air affect the subject as they do the background | Crisp subject in a hazy scene |
| **Sharpness and grain** | Subject and background share image qualities | Subject sharper or noisier than its surroundings |
| **Reflections and bounce** | The subject reflects and receives nearby colors | No color from a bright wall nearby |
| **Interaction traces** | The subject leaves traces (footprints, ripples, dust) | Walking through dust leaving no trace |

---

# 13. ENVIRONMENTAL CONTINUITY

## 13.1 What to Track

| Category | Items |
|---|---|
| **Layout** | Room dimensions, positions of doors, windows, stairs, furniture |
| **Landmarks** | Distinctive features that recur and orient the viewer |
| **Object states** | Open or closed doors; full or empty cups; lights on or off; items present or absent |
| **Dressing** | Position of set dressing and clutter |
| **Light** | Direction, color, and level of the main sources |
| **Time of day** | Position of the sun, sky color, and practical lights |
| **Weather** | Rain, wind, cloud cover, wet surfaces |
| **Wear and damage** | Condition of surfaces, damage progression |
| **Background activity** | Who and what is visible and what they are doing |

## 13.2 Geography, Reverse Shots, and Screen Direction

- **Layout map:** Draw a plan view of the space with the positions of landmarks, subjects, and camera positions.
- **Reverse shots:** When the camera turns around, the background changes. What appears behind subject A and subject B must be consistent with the layout (the window that is behind A appears *in front of* B).
- **Background matching table:** For each camera position, list what is behind the subject and which landmarks are visible.

| Camera position | Subject | Background visible | Landmarks visible | Must not appear |
|---|---|---|---|---|
| Cam 1 (facing east) | A | Window, bookcase | Window on the left | Door on the right |
| Cam 2 (facing west) | B | Door, coat rack | Door on the right | Window |

- **Screen direction:** A subject moving through the environment should keep a consistent direction on screen across shots unless a neutral shot or a clear change justifies a reversal. The camera knowledge base covers axis rules.

## 13.3 Continuity Log (State Tracking)

| Item | Scene start | After action 1 | After action 2 | Scene end |
|---|---|---|---|---|
| Front door | Closed | Open | Open | Closed |
| Table lamp | On | On | Off | Off |
| Mug on table | Full | Full | Empty | Empty |
| Window | Closed | Closed | Open | Open |
| Weather | Light rain | Light rain | Heavy rain | Heavy rain |
| Background activity | Two pedestrians | Two pedestrians | None | None |

## 13.4 Continuity Across Time and Scenes

- **Returning to a location after time passes:** Show change with cause (dust, rearranged furniture, different season, damage), or show stability if no time has passed.
- **Flashbacks:** Keep the layout recognizable and change the evidence (age, wear, technology).
- **Lighting and time across shooting:** Real daylight changes during filming; plan to match, or choose conditions that change slowly (overcast), or use controlled light.

## 13.5 Continuity Across AI-Generated Clips

AI generation does not preserve the environment automatically. Use these methods:

| Method | Description | Caution |
|---|---|---|
| **Environment Lock block** | A short, identical description of the layout, landmarks, light, weather, and time included in every prompt | Keep it short; long blocks dilute |
| **Landmark list** | 3–5 named, positioned landmarks (for example, "a red door on the left; a window with white curtains on the right") | State left and right in a frame of reference |
| **Reference frame** | Use a frame from the previous clip as a reference | State what to preserve and what may change |
| **Establishing anchor** | Begin each scene with a wide shot that fixes the layout | Later shots must remain consistent with it |
| **Handoff state** | The end state of one clip is the start state of the next (object positions, doors, light) | Small differences compound |
| **Simplification** | Fewer elements mean fewer chances for drift | May reduce richness |
| **Review pairs** | Compare adjacent clips for landmarks, light, weather, and background | Look for small drift |

**Typical drift types and fixes:**

| Drift | Fix |
|---|---|
| Landmarks move or change | Name them and place them each time |
| Light direction changes | State the light direction and the source |
| Weather changes | State weather and its evidence in every prompt |
| Color palette drifts | State palette and materials |
| Background crowd changes | Specify the crowd or simplify |
| Architecture morphs | Shorten clips; reduce geometric complexity; fix a reference |

## 13.6 Intentional Discontinuity

Changes can be deliberate (dream logic, time jumps, uncanny shifts). They must follow the **deliberate vs. accidental test**: a stated reason, a consistent rule, a controlled pattern, and a payoff. If they cannot be explained, treat them as errors.

---
# 14. ENVIRONMENT DESIGN FOR AI IMAGE AND VIDEO GENERATION

**Caution:** Model behavior varies by system and version. Statements about model tendencies are common observations to guard against, not guarantees about any particular model.

## 14.1 Why Environment Names and Adjectives Alone Are Insufficient

A generation model maps words to statistically typical images. A phrase such as "dark forest," "cyberpunk city," "cozy room," or "abandoned building" evokes a stock composite.

| Problem | Consequence |
|---|---|
| **Generic output** | The most common visual shorthand appears (fog and twisted trees; neon and rain; candles and blankets) |
| **Genre drift** | Words imply a genre's conventions even when the story needs something else |
| **No story evidence** | Nothing tells the audience who lives or works there, or what happened |
| **Unspecified layout** | Doors, windows, and landmarks appear anywhere and change between clips |
| **Unspecified scale** | Subject and environment relationships are arbitrary |
| **Inconsistency across shots** | Each generation re-interprets the words |
| **Background errors in unspecified areas** | Unmentioned regions are filled with whatever the model produces, including errors |

**Rule:** Use environment names as *labels for the designer*. In the prompt, specify the environment with **observable features: layout, layers, materials and condition, light sources, atmosphere, activity, scale references, and constraints.**

## 14.2 The Environment Specification Ladder

Work down the ladder; pick a small number of items on each rung.

| Rung | Question | Example for "a small, cluttered repair workshop" |
|---|---|---|
| **1. Identity** | What kind of place, where, when, and in what conditions? | A small bicycle repair workshop in a European city, late afternoon, overcast |
| **2. Layout** | How is the space arranged? Where are the key openings and landmarks? | A long narrow room; a roll-up door at the left end; a workbench along the right wall; a staircase at the back |
| **3. Layers** | What is in the foreground, midground, background, and distance? | Foreground: a bicycle wheel on a stand (soft); midground: the subject at the bench; background: shelves of parts and the stairs; distance: daylight through the roll-up door |
| **4. Materials and condition** | What surfaces are present and what are their conditions? | Painted brick wall with flaking paint; worn wooden bench with dark patches around the vise; oil stains on the concrete floor |
| **5. Light and atmosphere** | Which sources light the space? What is in the air? | Overcast daylight through the door; a single hanging work lamp over the bench; slight dust in the air |
| **6. Activity** | What moves or is occupied? | No other people; a fan turning slowly; a bicycle bell swinging slightly |
| **7. Constraints** | What must be present, consistent, or absent? | Door and stairs stay in place; no windows; no modern signage |

## 14.3 Environment Specification Template

```
ENVIRONMENT SPECIFICATION
Identity:      [type, place, period, time of day, weather]
Layout:        [shape and size; positions of key openings and landmarks in a named
                frame of reference]
Layers:        FOREGROUND: [..]  MIDGROUND: [..]  BACKGROUND: [..]  DISTANCE: [..]
Evidence:      [3–6 features that show use, history, or conditions]
Materials:     [surfaces and their condition]
Light:         [sources and their directions; atmosphere: haze/dust/mist]
Activity:      [what moves or is occupied; what does not]
Scale cues:    [reference objects and approximate sizes]
Subject link:  [subject distance from background; background tone; clean area behind head]
Lock:          [landmarks and states that must stay fixed]
Avoid:         [conflicting or unwanted elements, described by what is present instead]
```

## 14.4 Specifying the Subject–Background Relationship

| Item | Example phrasing |
|---|---|
| **Background distance** | "The wall is about three meters behind her." |
| **Background tone** | "The background is a mid-gray, darker than her face." |
| **Clean area behind the head** | "No vertical lines or poles directly behind her head." |
| **Camera height and horizon** | "The camera is at her eye height; the horizon passes behind her eyes." |
| **Detail level** | "The background shows soft, simple shapes only." |
| **Scale reference** | "A door behind her, its top about a head above hers." |

## 14.5 Specifying Scale

- **Name a reference object and its size** ("a standard interior door, about two meters high").
- **Place the subject relative to it** ("the subject's head reaches about three-quarters of the door's height").
- **Avoid scale-ambiguous words** such as "huge" or "tiny" without references.
- **For very large or very small environments,** include repeated objects at different distances (lamps, windows, vehicles) to supply perspective cues.

## 14.6 Specifying Light, Time, and Weather Consistently

- **State the source before the effect:** "Low sun from the left, long shadows to the right."
- **State the time of day with an evidence cue:** "late afternoon; shadows about twice the height of the objects."
- **State the weather with its surface evidence:** "light rain; wet pavement with small puddles; people holding umbrellas."
- **Avoid abstract atmosphere words alone** ("moody," "dramatic," "foggy") without describing the source and the visible effect.

## 14.7 Preventing Conflicting Instructions

| Conflict | Why it fails | Fix |
|---|---|---|
| "Bright sunny day, dark moody shadows" | Contradictory light | Choose one light logic |
| "Minimalist empty room full of detailed antiques" | Contradictory density | Choose a density; or define "sparse, with three antiques" |
| "Medieval village with futuristic neon" | Mixed rules | Choose a rule set or define the intended mix |
| "Rainy street, dry pavement" | Contradictory evidence | State wet pavement |
| "Wide open landscape, claustrophobic" | Spatial contradiction | Choose openness or enclosure |
| "Cozy and sterile" | Contradictory materials and condition | Choose a primary condition |
| "Night, bright sun" | Contradictory time | Choose one |
| "Background crowd and empty street" | Contradictory activity | Choose one |

## 14.8 Common Generation Errors in Environments and Prevention

| Error | Typical appearance | Prevention instruction |
|---|---|---|
| **Melting or morphing architecture** | Walls, windows, or stairs change shape within a clip | Simplify geometry; name fixed landmarks; shorten the clip; use a reference frame |
| **Repeating or tiled textures** | Identical bricks, tiles, or trees | Request variation: "irregular spacing, mixed sizes, varied wear" |
| **Garbled signage and text** | Letter-like shapes; wrong words | Avoid legible text; use blurred or simple signs; keep text to one short word if needed |
| **Floating objects or subjects** | No contact with the ground | "Objects rest on the floor with contact shadows" |
| **Perspective conflicts** | Lines converge to different points | State camera height, one-point or two-point perspective |
| **Scale drift** | Objects change size between frames | Provide scale references; limit changing elements |
| **Unusable doors, stairs, windows** | Doors with no frames; stairs with uneven steps | "A standard door with a visible frame and handle; stairs with equal steps" |
| **Extra people or objects** | Unrequested figures | "No other people in the frame" |
| **Overexposed windows or lights** | White areas with no detail | State the exposure relationship: "windows slightly brighter than the room, with visible sky" |
| **Uniform lighting** | Flat light with no sources | State sources and pools of light |
| **Too clean or too perfect** | Pristine surfaces | State wear at logical places |
| **Background crowd morphing** | Faces and bodies merging | Reduce the crowd; specify distant, soft, small figures |
| **Subject merging with background** | Hair or clothing blending | State tonal separation and distance |

## 14.9 Fixed vs. Variable Environment Instructions

| **Must remain fixed (environment anchors)** | **Can vary without changing the environment** |
|---|---|
| Place type, period, and time of day | Exact positions of unimportant small objects |
| Layout and positions of landmarks | Small background details that carry no information |
| Light direction, source, and level | Minor cloud shapes |
| Weather and surface condition | Individual background pedestrians (if unimportant) |
| Palette and material set | Camera position within the layout |
| Scale references | Subject pose |
| Key objects and their states | Foreground blur |
| Deliberate contrasts | Detail density in far areas |

**Environment Lock block (short):**

```
ENVIRONMENT LOCK
Place/time/weather: [..]
Landmarks:          [3–5 landmarks with positions]
Light:              [sources and directions]
Palette/materials:  [..]
States:             [doors/lights/objects that must stay as they are]
```

## 14.10 Avoiding Overload: The Environment Budget

- **One environment** per prompt.
- **3–7 evidence features** (ranked by importance).
- **One light logic.**
- **One activity statement.**
- **One lock list.**

If the prompt needs more, the scene is probably two shots. Remove synonyms and style stacks ("epic, cinematic, dramatic, stunning") that add no information.

## 14.11 Before-and-After Examples

Each "After" is an environment-focused direction, not a complete scene-generation prompt.

### Example 1 — Forest (suspense)
- **Before:** "A dark spooky forest."
- **After:** "A pine forest in late afternoon under overcast sky; trunks of varied thickness at uneven spacing; a narrow dirt path winding left to right; mist thickest between the trunks at mid-distance; the nearest trunks are darker and larger; no trunk directly behind the subject's head; the path's far end is not visible."
- **Why it works:** Layout, depth layers, atmosphere, a concealed endpoint, and a clean area behind the head replace "spooky" and "dark."

### Example 2 — Alley (urban night)
- **Before:** "Cyberpunk alley with neon and rain."
- **After:** "A narrow alley between brick buildings at night after rain; wet asphalt with puddles reflecting a magenta sign on the left wall and a green exit sign far down the alley; steam rising from a grate in the midground; a metal fire escape on the right wall; no legible text on the signs."
- **Why it works:** Sources and reflections are named; wetness has evidence; text is avoided.

### Example 3 — Bedroom (character evidence)
- **Before:** "A cozy bedroom."
- **After:** "A small bedroom with a single bed against the left wall, covered with a patched knitted blanket; a desk by the window on the right with a lamp and stacked notebooks; a pair of worn sneakers by the door; morning daylight from the window, soft; a poster slightly faded on the wall above the bed."
- **Why it works:** Evidence of use and personality replaces "cozy."

### Example 4 — Hospital corridor (plausibility)
- **Before:** "Creepy hospital."
- **After:** "A hospital corridor at night: pale green walls, vinyl flooring with a polished path down the center; ceiling lights alternate lit and unlit panels; a nurses' station with a lit monitor at the far end; a wheelchair parked against the left wall; a closed door at the right with a small window; no people visible."
- **Why it works:** The wrongness comes from lighting pattern, emptiness, and an object; layout and endpoint are defined.

### Example 5 — Desert (scale)
- **Before:** "Epic desert landscape."
- **After:** "A desert of rolling dunes at low sun; the nearest dune ridge sharp with long shadows to the right; a line of footprints leading up the middle dune; a small figure, about 4% of the frame height, near the crest; distant ridges lighter and bluer; no vegetation."
- **Why it works:** Scale is supplied by a figure; depth by atmospheric perspective; light by sun direction.

### Example 6 — Spaceship corridor (sci-fi plausibility)
- **Before:** "Futuristic spaceship corridor."
- **After:** "A narrow spacecraft corridor with curved ceiling ribs every two meters; matte gray panels with scuffed edges at hand height; a handrail along the right wall; yellow-labeled hatch on the left; strip lights along the ceiling, one flickering; cables in a tray along the top; a figure, 1.8 m tall, for scale."
- **Why it works:** The structure, wear, function, and scale are defined without relying on "futuristic."

### Example 7 — Fantasy village (rules and grounding)
- **Before:** "Magical fantasy village."
- **After:** "A hillside village of stone cottages with turf roofs; smoke rising from two chimneys; a stream crossed by a wooden bridge; glowing blue moss growing only on the north-facing walls; stone steps worn in the middle; a market stall with baskets on the left."
- **Why it works:** The magical element has a rule (north-facing walls only), and everything else is grounded in material behavior.

### Example 8 — Minimalist background (control)
- **Before:** "Clean minimal background."
- **After:** "A seamless light-gray studio floor curving into a wall with no visible horizon line; a soft gradient from lighter behind the subject to slightly darker at the corners; a single soft shadow on the floor under the subject; no objects."
- **Why it works:** The rules of the empty space (floor, gradient, shadow) are defined to avoid an unfinished look.

### Example 9 — Market (background activity)
- **Before:** "A busy market."
- **After:** "An open-air market with striped awnings; the subject stands in the foreground; behind her, five to seven shoppers in varied clothing walk slowly left to right at the stalls, all smaller and softer than her; stalls stacked with fruit; no one looks toward the camera; a clear aisle behind the subject's head."
- **Why it works:** Density, direction, size, and clean space are specified.

### Example 10 — Abandoned building (logical decay)
- **Before:** "Abandoned building."
- **After:** "An abandoned warehouse with a partly collapsed roof; daylight shafts through the gap; water stains running down the wall below the gap; a puddle on the floor beneath it; weeds growing in cracks near the open door; machinery covered in a thin layer of dust, undisturbed except for one path of footprints."
- **Why it works:** Decay has causes (a roof gap, water, plants), and the footprints add a story.

### Example 11 — Rooftop (night, scale and light)
- **Before:** "City rooftop at night."
- **After:** "A rooftop with a low parapet at night; air-conditioning units and a water tank in the midground; city lights of varied heights in the distance with slight haze; a red aircraft warning light on a tall tower far right; faint warm glow from stairwell door on the left; the subject stands about two meters from the parapet."
- **Why it works:** Layers, light sources, and distance cues define the place.

### Example 12 — Flashback kitchen (time evidence)
- **Before:** "Old memory kitchen, nostalgic."
- **After:** "A small family kitchen about thirty years earlier: yellow laminate counters, a round-faced clock on the wall, a tube television on the counter, a coffee percolator, cotton curtains with faded flowers; afternoon sunlight from the window onto the table; objects slightly lived-in, no modern appliances."
- **Why it works:** Period evidence replaces "nostalgic."

### Example 13 — Dreamlike hallway (rules for distortion)
- **Before:** "Dreamy surreal hallway."
- **After:** "A long hallway of ordinary apartment doors; each door is the same except that each has a different number of handles; the ceiling is slightly too high and curves upward; soft, even daylight from no visible source; the far end is a door standing open onto a bright beach."
- **Why it works:** A controlled distortion (handles, ceiling, light) has a rule and an anchor in real elements.

### Example 14 — Café dialogue (background control)
- **Before:** "Café with blurred background."
- **After:** "A café interior behind two people at a table; the background is a warm, dim wall with two small framed pictures and a closed door; no other customers visible; window light from the left on their faces; the wall is a darker tone than their faces; no bright signs."
- **Why it works:** The background is quiet, consistent, and tonally separated.

### Example 15 — Mountain survival (conditions and scale)
- **Before:** "Stormy mountain survival."
- **After:** "A rocky mountain slope in a storm; low, fast-moving clouds covering the peaks; wind-driven rain slanting from the left; wet dark rock with small streams running down; a stone overhang offering partial shelter at the right; the subject about 6% of the frame height on a narrow ledge; the path ahead disappears into cloud."
- **Why it works:** Conditions, shelter, scale, and the unseen path create the survival situation.

---

# 15. ENVIRONMENT AND BACKGROUND FAILURE DIAGNOSIS

## 15.1 Troubleshooting Table

| # | Intended environment | Observed result | Likely cause | Evidence to inspect | Corrective action | Possible side effect |
|---|---|---|---|---|---|---|
| 1 | A specific place | **Generic environment** (could be anywhere) | Labels used instead of features | Whether any landmark, material, or detail identifies the place | Add 2–3 specific features with positions | More elements to drift |
| 2 | Readable subject | **Background too busy or cluttered** | Many equal-weight elements; bright items; patterns | Squint test; element roles | Remove or soften; group objects; reduce contrast | Environment looks sparse |
| 3 | Subject distinct from the background | **Subject merges with the background** | Tonal or color similarity; tangents; no depth separation | Tones and edges around the head and body | Change background tone or distance; reposition; add separation | Changes the mood or palette |
| 4 | Convincing depth | **Flat or cutout look** | No overlap, haze, parallax, or tonal separation | Layer overlap, edge softness, light consistency | Add foreground and midground elements; atmospheric fade; consistent light | More complexity |
| 5 | Correct scale | **Scale wrong** (subject too large, small, or the room looks miniature) | Missing references; wrong object sizes; camera height | Door, chair, and counter size relative to the subject; horizon | Add references with sizes; adjust camera height and object scale | May change composition |
| 6 | Grounded subject | **Subject floats or sinks** | Missing contact shadows; ground plane unclear; light mismatch | Contact area under feet and objects | State contact and ground plane; match light | May change shadow style |
| 7 | Usable geometry | **Impossible architecture** (stairs, doors, windows) | Geometry unspecified; generation instability | Step heights; door frames; window placement | Specify standard doors and stairs; simplify; use a reference | Plainer architecture |
| 8 | Stable background in a clip | **Background morphs within the clip** | Complex or unspecified background; long duration | Compare first and last frames | Simplify; name landmarks; shorten; reduce movement | Less detailed background |
| 9 | Consistent place across clips | **Environment changes across clips** | No lock; different interpretations | Landmarks, light, palette across clips | Environment Lock; reference frame; state landmarks and positions | Over-locking looks repetitive |
| 10 | Period or rule consistency | **Anachronism or mixed rules** | Unspecified period; style stack | Each object against the period | State period; remove contradicting objects | Fewer decorative items |
| 11 | Motivated light | **Light inconsistent with the environment** | No named sources; mixed implied suns | Shadow directions; light sources; reflections | State sources and directions; remove unmotivated effects | Less dramatic light |
| 12 | Lived-in space | **Sterile, too clean** | Default polish; no use evidence | Surfaces for wear at logical places | Add wear and use evidence; clutter in logical places | Over-distressing |
| 13 | Believable aging | **Over-distressed, uniform grime** | Decay without cause | Whether damage follows causes | Concentrate damage at causes (water, traffic, sun) | Spaces may look too clean |
| 14 | Environmental storytelling | **Props with no meaning, or over-explained scene** | Evidence not chosen; too many items | Claim and evidence list | Use the evidence chain: claim, 2–4 items, placement, restraint | Story may become too subtle |
| 15 | Environment that supports the story | **Environment contradicts the story** | Chosen for looks rather than purpose | Purpose vs. environment functions | Return to Step 1; adjust type and features | Rework of several shots |
| 16 | Consistent weather | **Inconsistent weather evidence** | Evidence stated in one place only | Surfaces, clothing, light, motion | List all evidence (surfaces, light, subjects) | More text in the prompt |
| 17 | Believable atmosphere | **Haze or fog that does not fit** | Uniform fog; no depth fade; no source | Distance fading; halos around lights | State density and depth fade | Less clarity in the distance |
| 18 | Believable background activity | **Cloned or morphing crowd; unnatural vehicles** | Dense unspecified crowd | Faces, clothing variety, motion | Reduce; specify a few distinct figures; keep them small and soft | Less lively |
| 19 | Subject as the focus | **Environment overwhelms the subject** | Scale, brightness, or detail of the environment | Where the eye goes first | Reduce environment contrast and detail; reframe; increase subject scale | Loss of context |
| 20 | Purposeful empty space | **Accidentally empty or unfinished** | No function stated for the space | Whether the empty area has a role | Add a meaningful element, or reframe | Reduces minimalism |
| 21 | Clean silhouettes | **Lines or objects appear to grow from the head** | Tangents; camera position | Lines touching the head and shoulders | Move the camera or subject; change height | Slight composition change |
| 22 | Legible signs | **Garbled text** | Text not controllable | Signs and labels | Avoid legible text; blur; limit to one short word | Fewer story cues from text |
| 23 | Repeating-pattern-free | **Tiled textures, identical objects** | Cloning | Pattern repeats | Request variation in size, spacing, and condition | Visual complexity |
| 24 | A usable real location | **Location unsuitable** | Poor scouting; fascinating look hid constraints | Scoring sheet (Section 7.3) | Re-score; find a new location; modify; or switch to a set | Schedule and cost |

## 15.2 Diagnostic Order

**Principle:** Diagnose from what defines the environment toward what decorates it. Change **one variable at a time** and re-evaluate.

| Order | Layer | Question | Why first |
|---|---|---|---|
| **1** | **Purpose and brief** | Is the environment's job clear (Section 3)? | A flawed brief cannot be fixed by execution |
| **2** | **Identity** | Can a viewer name the place, time, and conditions? | Identity underlies everything |
| **3** | **Layout and geography** | Is the layout legible and consistent? | Spatial confusion affects all shots |
| **4** | **Scale and plausibility** | Do scale, geometry, and ground contact make sense? | Implausibility breaks belief |
| **5** | **Layers and depth** | Do foreground, midground, background, and distance work? | Depth distinguishes world from backdrop |
| **6** | **Hierarchy and clutter** | Does the subject dominate; are competing elements controlled? | Readability |
| **7** | **Light and atmosphere logic** | Do sources, shadows, and atmosphere agree? | Lighting reveals inconsistencies |
| **8** | **Evidence and detail** | Do objects and wear tell the right story? | Adds meaning |
| **9** | **Dynamics** | Do weather, time, and background activity agree? | Consistency of condition |
| **10** | **Continuity** | Does it match neighbors? | Continuity is relative |
| **11** | **Prompt conflicts and overload** | Are there contradictions or too many requirements? | Reduces failures at the source |

**Procedure:**

1. Identify the layer from the table that most plausibly explains the symptom.
2. Make **one** targeted change.
3. Re-evaluate against the acceptance criteria.
4. Run a **regression check:** did the correction create a new problem (see "Possible side effect")?
5. If the symptom persists, move to the next layer.

## 15.3 Correct the Smallest Relevant Variable First

| Symptom | Smallest relevant change |
|---|---|
| Subject merges with background | Change the background tone or add "the wall is darker than her face" |
| Tree trunk appears behind head | Add "no vertical lines directly behind her head" or move the camera |
| Scale off | Add one reference object with size |
| Floating subject | Add "contact shadows under her feet" |
| Garbled sign | Remove legible text |
| Wrong time of day | State sun direction and shadow length |
| Crowd morphing | Reduce to three small figures |
| Landmark moves | Restate the landmark with its position in each prompt |

---
# 16. PRACTICAL CASE STUDIES

Each case follows the same structure: situation → environmental requirements → main design choices → failure points → flawed result and diagnosis → targeted correction → why it should work.

---

## Case 1 — A Person Alone in a Familiar Room

**Narrative situation.** Ines's long-time flatmate has moved out this morning. It is evening. She stands in the shared kitchen, which now has gaps where the flatmate's things were.

**Environmental requirements.** The environment must show *absence* and *habit* without dialogue. It should feel familiar (lived in for years) and slightly incomplete.

**Main design choices.**
- **Layout:** A small kitchen with a table at the left, counter and window on the right, doorway at the back.
- **Foreground:** A chair edge at the frame's lower left (soft).
- **Midground:** Ines at the counter.
- **Background:** A shelf with two mugs where there were four (pale rings on the shelf where the others stood); a bare hook by the door; a wall calendar with a date circled.
- **Light and atmosphere:** One lamp lit over the table; dusk through the window; a quiet, still room.
- **Evidence chain:** Claim: "a second person has left." Evidence: pale rings on the shelf, an empty hook, two chairs with one pushed in.

**Failure points.** The kitchen looks like a stock "cozy kitchen" with full shelves; the absence is not visible; the lamp is warm and the colors rich, so the space reads as comforting rather than lonely.

**Flawed result.** A tidy, beautifully lit kitchen with fully stocked shelves and a bowl of fruit.

**Diagnosis (ordered).**
1. *Purpose:* clear (absence). ✔
2. *Identity:* generic kitchen. ✘
3. *Evidence:* no signs of absence. ✘
4. *Light and atmosphere:* glamorous warm light supports comfort. ✘ (secondary)

**Targeted correction.** First change the evidence only: "A wall shelf with two mugs and pale rings in the dust where two more stood; a bare coat hook by the door; one chair pushed in and the other pulled out." Then, if needed, simplify the light: "A single lamp over the table; the rest of the room dim; no bowl of fruit."

**Why it should work.** Environmental storytelling operates through traces. The pale rings and the empty hook carry the absence; the lighting change removes a cue that contradicted it.

---

## Case 2 — Arriving in an Unfamiliar City at Night (Establishing Shot)

**Narrative situation.** A traveler steps out of a train station into a city she has never visited, late at night.

**Environmental requirements.** The audience must understand *where* (a specific, unfamiliar city), *when* (night), and the *scale* of the place, and feel the traveler's smallness.

**Main design choices.**
- **Identity:** A northern European port city, after rain, 11 p.m.
- **Layout:** A wide plaza in front of the station; a tram line crossing left to right; a church spire at the far right.
- **Layers:** Foreground: wet cobblestones with reflections; midground: the traveler with a suitcase, about 6% of the frame height; background: tram stop, shop fronts with lit windows; distance: a hill with scattered lights and a church spire.
- **Light:** Warm shop windows; cool streetlamps; reflections on the wet stone.
- **Activity:** One tram passing in the distance; two figures at the tram stop.
- **Scale cues:** The tram (about 3 m high) and the traveler.

**Failure points.** Generic "city at night"; no scale reference; reflections that don't match the lights; tram and shop signs unreadable.

**Flawed result.** A neon cityscape with random tall buildings and no recognizable landmarks; the traveler is the same size as the tram.

**Diagnosis.**
1. *Identity:* generic. ✘
2. *Scale:* the subject and tram are not coherent. ✘
3. *Light and atmosphere:* neon with no source relation to the place. ✘

**Targeted correction.** "A cobbled plaza at night after rain; a tram stop with a low-roofed shelter on the left; a stone church spire lit from below at the far right; warm shop windows along the right side; reflections of those lights on the wet stones; the traveler, about 1.7 m tall, is roughly half the height of the tram's doors; no neon signs."

**Why it should work.** Distinct, positioned landmarks establish place; the tram supplies scale; reflections are tied to named sources.

---

## Case 3 — A Dialogue in a Café

**Narrative situation.** Two friends discuss a difficult decision at a café table. The conversation must stay the focus.

**Environmental requirements.** A believable café that supports the conversation without competing: quiet, consistent geography through reverse shots, evidence of the place.

**Main design choices.**
- **Layout:** A corner table; window on the left of person A; a wall with two framed pictures behind person B; a closed door at the back.
- **Background (behind A):** The window with soft daylight and a blurred street.
- **Background (behind B):** The wall and pictures.
- **Light:** Window light from the left; a warm wall lamp.
- **Activity:** One barista visible far behind B, small and soft; no other patrons near the table.
- **Tone:** Backgrounds darker than the faces; no bright signs.

**Failure points.** A busy crowd behind A; bright signs behind B; reverse-shot backgrounds that do not match the layout; moving figures crossing behind faces.

**Flawed result.** In shot A the window is on the left; in the reverse shot the window also appears behind B. A neon "OPEN" sign glows over B's shoulder.

**Diagnosis.**
1. *Layout and geography:* inconsistent (window in both backgrounds). ✘
2. *Hierarchy and clutter:* the sign competes. ✘
3. *Continuity:* reverse shot mismatched. ✘

**Targeted correction.** Use a background matching table: "Camera 1 (over B toward A): window on the left behind A. Camera 2 (over A toward B): wall with two framed pictures and a closed door behind B; no window." Remove the sign: "No bright signs; the wall is a mid-tone darker than B's face."

**Why it should work.** The layout map fixes what appears behind each person; the removed sign restores the hierarchy.

---

## Case 4 — An Apparently Safe Environment That Contains a Wrong Detail (Suspense)

**Narrative situation.** A family tours a sunlit suburban house they are about to buy. A small environmental detail suggests that something is wrong.

**Environmental requirements.** The house must look safe and ordinary at first. The wrongness must be *visible but quiet*, and discoverable by the audience before the characters.

**Main design choices.**
- **Layout:** A bright open living room with a hallway at the back and a closed door at the end of the hall.
- **Evidence:** Every window is covered on the inside with taped paper; one door has several locks on the outside; a child's height marks on the doorframe stop abruptly at one height.
- **Light:** Even daylight; no dramatic shadows.
- **Activity:** None.
- **Camera access:** Wide framing with the closed door visible at the back of several shots.

**Failure points.** The environment becomes sinister too early (dark, cobwebs); the wrong detail is too obvious or too hidden; the house is generic.

**Flawed result.** A dim, dusty house with flickering lights.

**Diagnosis.**
1. *Purpose and brief:* intended safe-looking house; result is horror-coded. ✘
2. *Evidence:* the wrong detail is missing; generic dread cues replace it. ✘
3. *Light:* low-key where daylight was intended. ✘

**Targeted correction.** "A bright, clean living room in daylight; fresh paint; a staged sofa; all windows covered from the inside with taped paper (visible at one window only in the wide shot); at the far end of the hall, a closed door with three bolts on the outside."

**Why it should work.** The viewer reads the normal first, then notices an out-of-place element. Specific evidence creates suspicion without genre shorthand.

---

## Case 5 — A Survival Scene After a Storm

**Narrative situation.** After a storm, a hiker has lost the trail in a forest at dusk. She needs shelter and water.

**Environmental requirements.** The environment is both antagonist and resource: terrain that blocks, evidence of the storm, visible possibilities (an overhang, a stream).

**Main design choices.**
- **Identity:** A mixed forest on a hillside, dusk, after heavy rain.
- **Layout:** A fallen tree blocking the route; a stream at the bottom of the slope; a rock overhang at the right.
- **Evidence of the storm:** Broken branches on the ground; wet bark darker than dry; mud on the slope; low mist.
- **Light and atmosphere:** Fading cool light; mist in the low areas; wet reflections on the stream.
- **Scale cues:** The hiker's height against the fallen trunk (about half her height).
- **Activity:** Drips from branches; the stream's movement.

**Failure points.** An undamaged forest; no sign of storm; no visible resource; scale unclear; a uniform dark.

**Flawed result.** A calm, uniformly green forest with a clean path.

**Diagnosis.**
1. *Identity and conditions:* storm evidence missing. ✘
2. *Evidence:* no obstacle or resource. ✘
3. *Dynamics:* weather evidence inconsistent with "after heavy rain." ✘

**Targeted correction.** "A hillside forest after a storm: a fallen pine across the path, waist-high to the hiker; broken branches scattered; dark wet bark; mud on the slope; low mist along the stream at the bottom; a rock overhang to the right with a dry patch under it; drips from the branches."

**Why it should work.** Each condition produces a visible trace, and the obstacle and resource create choices.

---

## Case 6 — A Flashback to a Childhood Home

**Narrative situation.** A man remembers the living room of the house he grew up in, when he was eight.

**Environmental requirements.** The place must be recognizable as the same room seen in the present timeline (same layout, same window), but the *evidence of time* must differ: furniture, technology, wear, light.

**Main design choices.**
- **Layout:** The same room: window on the left, doorway on the right, fireplace at the back.
- **Present vs. past evidence:** *Past:* a tube television; patterned wallpaper in good condition; a cloth-covered sofa; a bookcase full of paperbacks. *Present (for comparison):* the same wall painted over; the fireplace blocked; a flat screen.
- **Light:** Warm afternoon light through lace curtains.
- **Scale cues:** The room appears larger relative to the child's eye level (low camera).
- **Continuity:** The window and fireplace remain in the same positions.

**Failure points.** The flashback room looks identical to the present; mixed periods (a modern lamp in a retro room); the layout changes.

**Flawed result.** The same modern living room with a sepia tone.

**Diagnosis.**
1. *Identity:* the period evidence is missing. ✘
2. *Evidence:* only a color filter differentiates. ✘
3. *Continuity:* layout not specified. ✘

**Targeted correction.** "The same living room as before (window on the left, doorway on the right, fireplace at the back) thirty years earlier: patterned wallpaper, a tube television on a wooden stand, a cloth-covered sofa, a full bookcase, lace curtains, warm afternoon light; no modern objects."

**Why it should work.** The layout is locked and the period is carried by objects and surfaces rather than a filter.

---

## Case 7 — A Science-Fiction Station Corridor (Scale and Plausibility)

**Narrative situation.** A maintenance engineer walks along a corridor on an orbital station to inspect a faulty hatch.

**Environmental requirements.** The corridor must look functional and used, not decorative, and its scale must be readable.

**Main design choices.**
- **Layout:** A straight corridor with a curved ceiling; hatches at intervals; a handrail on both walls; a maintenance panel open near the end.
- **Function:** Cables in trays; labeled conduits; signs with simple symbols.
- **Wear:** Scuffed panels at hip height; scratched floor along the center; a small repair patch.
- **Light:** Strip lights along the ceiling, one flickering; indicator lights at the faulty hatch.
- **Scale cues:** Hatch height about 2 m; the engineer about 1.8 m.

**Failure points.** Polished, empty corridor with random glowing lines; hatches larger than doors; no clear function.

**Flawed result.** A glossy white tube with glowing lines and an unreadable scale.

**Diagnosis.**
1. *Identity and function:* no purpose. ✘
2. *Scale:* no reference. ✘
3. *Evidence:* no wear, no use. ✘
4. *Light:* glow without sources. ✘

**Targeted correction.** "A narrow gray corridor with curved ceiling ribs every two meters; matte panels scuffed at hip height; a handrail along the right wall; cable trays on the ceiling; yellow-labeled hatches on the left, each about two meters high; strip lights overhead with one flickering; an engineer 1.8 m tall near the open panel."

**Why it should work.** Function, wear, and scale references give the space credibility; light has named sources.

---

# 17. ENVIRONMENT DESIGN WORKSHEET

## 17.1 Blank Worksheet (Copy and Complete)

Fields marked ★ are **essential for AI-generated images and video** (see 17.3).

```
ENVIRONMENT DESIGN WORKSHEET
─────────────────────────────────────────────────────────────────────────
 1.  Narrative purpose of the scene:
 2.  Subject's immediate objective:
 3.★ Audience must understand (max 5) / must not know yet:
 4.  Emotional and atmospheric requirements:
 5.  Action and movement requirements (paths, clear space, objects touched):
 6.★ Environment type and identity (place, period, time of day, season, weather):
 7.★ Layout and landmarks (positions in a named frame of reference):
 8.★ Layers: FOREGROUND / MIDGROUND / BACKGROUND / DISTANCE:
 9.★ Essential features and their functions (3–7):
10.★ Evidence of use, history, or conditions (claim → 2–4 pieces of evidence):
11.  Materials and condition (wear at logical places):
12.★ Light sources and atmosphere (motivated sources; haze, dust, mist):
13.  Background activity (what moves, what does not; density; direction):
14.★ Scale references (objects with sizes; subject relation):
15.★ Subject–background relationship (distance, tone, clean area behind head):
16.  Elements to remove (unnecessary or contradictory):
17.★ Continuity requirements and lock list (landmarks, states, light, weather):
18.  Likely failure modes:
19.★ Acceptance criteria (3–6 observable statements):
20.  Final verification questions:
─────────────────────────────────────────────────────────────────────────
```

## 17.2 How to Complete Each Field

| Field | How to complete it | How it influences later decisions |
|---|---|---|
| **1. Narrative purpose** | One sentence on what the scene does for the story. | Determines which environmental functions matter. |
| **2. Subject's objective** | What the subject is trying to do in this place. | Identifies routes, objects, and obstacles. |
| **3. Must understand / must not know** | Up to five facts about the place the viewer needs, and what to withhold. | Prioritizes features; guides concealment. |
| **4. Emotional and atmospheric requirements** | The emotional weather and physical atmosphere, tied to environmental properties. | Selects enclosure, openness, order, condition, light behavior. |
| **5. Action and movement requirements** | Paths, clear space, objects the subject touches. | Ensures the space permits the action. |
| **6. Environment type and identity** | Type, place, period, time of day, season, and weather. | Frames all other decisions; becomes the opening line of any prompt. |
| **7. Layout and landmarks** | Shape and size; the positions of doors, windows, landmarks, with a named frame of reference. | Supports continuity and reverse shots. |
| **8. Layers** | One line for each layer. | Builds depth and controls overlap. |
| **9. Essential features and functions** | The 3–7 features that carry meaning; each with a function. | Prevents clutter; becomes the core of a prompt. |
| **10. Evidence** | Claim and 2–4 evidence items with placement. | Delivers storytelling without exposition. |
| **11. Materials and condition** | Surface materials and wear tied to causes. | Authenticity. |
| **12. Light and atmosphere** | Sources, directions, and particles in the air. | Light logic and depth cues. |
| **13. Background activity** | What moves; density; direction; what is still. | Life without competition. |
| **14. Scale references** | Objects with approximate sizes and their relationship to the subject. | Prevents scale errors. |
| **15. Subject–background relationship** | Distance, tone, clean area, camera height and horizon. | Controls readability and separation. |
| **16. Elements to remove** | Contradictions, clutter, and distractions. | Becomes an "avoid" list. |
| **17. Continuity and lock list** | Landmarks, states, light, weather that must not change. | Defines the Environment Lock block. |
| **18. Likely failure modes** | Top three risks from Sections 14–15. | Guides pre-emptive wording. |
| **19. Acceptance criteria** | Observable statements. | Used in Section 18. |
| **20. Final verification questions** | Questions to ask of the result. | Ensures evaluation of the output. |

## 17.3 Fields Essential for AI-Generated Images and Video

| Priority | Fields | Reason |
|---|---|---|
| **Essential (★)** | 3, 6, 7, 8, 9, 10, 12, 14, 15, 17, 19 | These define what the place is, how it is arranged and lit, how large it is, how it relates to the subject, what must stay fixed, and how it will be judged. |
| **Recommended** | 1, 2, 4, 5, 11, 13, 16, 18 | These add purpose, plausibility, and risk control. |
| **Optional for simple backgrounds** | 11, 13 | A simple, quiet background may not need wear or activity details. |

## 17.4 Completed Example

```
ENVIRONMENT DESIGN WORKSHEET — "The Repair Workshop"
 1.  Purpose: Show that the mechanic is skilled and has been working here for decades.
 2.  Objective: Fix a bicycle wheel before a customer returns.
 3.★ Must understand: a bicycle repair shop; long use; cluttered but organized; late
     afternoon. Must not know yet: that the owner is planning to close the shop.
 4.  Atmosphere: Warm, focused, quietly worn.
 5.  Movement: The mechanic moves between the bench and a shelf at the back (3 m).
 6.★ Identity: Small bicycle repair workshop, European city, late afternoon, overcast.
 7.★ Layout: Long narrow room; roll-up door at the left end (open); workbench along the
     right wall; staircase at the back; frame of reference: screen-left/right.
 8.★ Layers: Foreground: a wheel on a stand (soft). Midground: the mechanic at the bench.
     Background: shelves of parts and the stairs. Distance: daylight through the door.
 9.★ Features: workbench with vise (function: work); shelves of sorted parts (function:
     expertise); hanging tools in outlines on pegboard (function: order); a calendar with
     the last page torn off (function: hint of ending).
10.★ Claim: long use. Evidence: dark patches on the bench near the vise; worn handles on
     tools; floor path worn along the bench.
11.  Materials: painted brick with flaking paint; wooden bench; oil-stained concrete floor.
12.★ Light: overcast daylight through the roll-up door; a hanging work lamp over the bench;
     slight dust in the air.
13.  Activity: none besides the mechanic; a slow fan.
14.★ Scale: bench height about 0.9 m; stairs with standard steps; the mechanic is about
     1.75 m.
15.★ Subject link: back wall about 3 m behind him; wall tone mid-brown, darker than his
     face; no vertical lines behind his head.
16.  Remove: modern signage; bright objects near the subject.
17.★ Lock: roll-up door on the left; bench on the right; stairs at the back; overcast
     light from the left; pegboard above the bench.
18.  Failure modes: shelf contents morphing; tools changing; repetitive parts.
19.★ Acceptance: (1) The place reads as a bicycle repair shop. (2) The door, bench, and stairs are in
     their positions. (3) The wall behind the head is clean. (4) Wear appears at the bench and floor path.
20.  Verification: Does the room feel used, not decorated? Does the subject read clearly?
```

---

# 18. QUALITY CONTROL AND FINAL VERIFICATION

## 18.1 Purpose and Use

Use this checklist **before approving an environment design** (pre-production) and **before approving a generated or filmed result** (post-production). Evaluate the *image or video* against observable criteria, not against the description in the brief.

## 18.2 Verification Checklist

Rate each item **Pass**, **Minor issue**, or **Critical failure**.

| # | Question | Pass criterion | Severity if failed |
|---|---|---|---|
| 1 | **Is the environment's purpose defined?** | A purpose, a must-know list, and acceptance criteria exist. | **Critical** |
| 2 | **Can a viewer identify the place, time, and conditions?** | A viewer without the brief names the type of place and time of day. | **Critical** |
| 3 | **Does the environment serve the story?** | Each major feature has a function; no feature contradicts the story. | **Critical** if contradicting; **Minor** if decorative |
| 4 | **Is the layout legible and consistent?** | Landmarks and openings are readable and match the layout map. | **Critical** if confusing; **Minor** if slightly ambiguous |
| 5 | **Are scale and proportion plausible?** | Subject, doors, furniture, and vehicles agree; horizon and perspective consistent. | **Critical** if scale breaks belief; **Minor** if small deviations |
| 6 | **Is the subject grounded and integrated?** | Contact shadows, light, perspective, and atmosphere match. | **Critical** if floating or pasted |
| 7 | **Does depth work?** | Layers overlap and separate; no cutout look. | **Minor** (or **Critical** if flat in a scene that needs depth) |
| 8 | **Is the hierarchy clear?** | The subject is the dominant element; competing elements controlled; no tangents or mergers. | **Critical** if the subject is lost; **Minor** if slight competition |
| 9 | **Are objects and evidence meaningful and believable?** | Evidence is consistent, placed logically, and visible. | **Minor** (or **Critical** if it contradicts the story) |
| 10 | **Is wear logical?** | Wear follows use and exposure; neither sterile nor uniformly distressed. | **Minor** |
| 11 | **Is the light motivated and consistent with the environment?** | Sources, shadows, reflections, and atmosphere agree. | **Critical** if contradictory; **Minor** if slightly off |
| 12 | **Are weather, time, and season consistent?** | All evidence agrees. | **Critical** if contradictory |
| 13 | **Is background activity believable and controlled?** | Behavior is plausible; density suits the scene; no cloning or morphing. | **Minor** (or **Critical** if distracting) |
| 14 | **Is the environment stable within a clip?** | No morphing of architecture or objects. | **Critical** |
| 15 | **Is the environment consistent across shots and clips?** | Landmarks, light, palette, and states match; reverse shots agree. | **Critical** if the place appears to change |
| 16 | **Is the output free of avoidable errors (garbled text, impossible geometry, repeated patterns)?** | None visible, or accepted and recorded. | **Critical** if impossible geometry; **Minor** for small text issues |
| 17 | **Are acceptance criteria met?** | Every written criterion is verified. | **Critical** for each unmet core criterion |

## 18.3 Critical Failures vs. Optional Refinements

### Critical failures (must be corrected before approval)

- The place or time cannot be identified, or the wrong place is shown.
- The environment contradicts the story's purpose or rules without a labeled reason.
- Scale, geometry, or ground contact breaks belief.
- The subject is lost, merged with the background, or overwhelmed.
- Light, weather, or time evidence is contradictory.
- The environment morphs within a clip or changes across clips without reason.
- A required landmark, object, or state is missing or moved.
- Impossible or unusable architecture (stairs, doors, passages) appears in a realist scene.

### Optional refinements (may remain a creative choice)

- Variations in minor background objects that carry no meaning.
- Small differences in texture or wear that do not change reading.
- Slight differences in background activity within the intended range.
- A documented stylization applied consistently.
- Minor text artifacts on distant signs.
- Variations in foreground blur.

## 18.4 Approval, Revision, and Rejection

These thresholds are **practical guidelines**; adapt them to project needs.

| Decision | Conditions |
|---|---|
| **Approve** | No critical failures; minor issues corrected or recorded as acceptable; criteria met. |
| **Revise** | One or two critical failures traceable to one or two layers in the diagnostic order; fixable by a targeted change (Section 15.3). Make one change at a time and re-verify. |
| **Reject (return to the brief)** | The place is unidentifiable; three or more critical failures across layers; the same critical failure persists after several targeted revisions. Return to Sections 3 and 14: re-define purpose and simplify. |

## 18.5 Reviewer Procedure

1. **Look at the image once** and write down the place, time, and conditions you perceive.
2. **Compare with the intent.**
3. **Squint test** for hierarchy and tangents.
4. **Check scale** with references and the horizon.
5. **Check ground contact and integration.**
6. **Check light logic** (sources, shadows, reflections).
7. **Check weather and time evidence.**
8. **Check landmarks and states** against the layout map and lock list.
9. **Compare first and last frames** (video) for morphing.
10. **Compare neighbors** for continuity.
11. **Decide:** approve, revise (one change), or reject.

---

# 19. QUICK REFERENCE

## 19.1 Environment Design Decision Sequence

1. **Purpose:** What must the environment do for the scene?
2. **Objective:** What must the subject do here?
3. **Must-know list:** What must the audience understand about the place?
4. **Atmosphere:** Which environmental properties will carry it?
5. **Action needs:** What space, surfaces, and routes are required?
6. **Type and layout:** Choose the type; place landmarks.
7. **Features:** Choose 3–7 that carry meaning; give each a function.
8. **Remove:** Delete contradictory or unnecessary elements.
9. **Check:** Readability, scale, depth, light, plausibility.
10. **Lock:** Define continuity and an Environment Lock; then generate or shoot; then verify.

## 19.2 Terms Compared

| Term | Meaning | Belongs to | Changes when the camera moves? |
|---|---|---|---|
| **Environment** | All surroundings of the scene world | The scene world | No |
| **Background** | The part of the environment visible behind the subject | The image | Yes |
| **Foreground** | Between the camera and the subject | The image | Yes |
| **Setting** | Broad story time and place | The story | No |
| **Location** | A specific place (real or story) | Production or story | No |
| **Set** | Constructed environment | Production | No |
| **Set dressing** | Movable items that make a space specific | Production | No |
| **Props** | Objects handled by performers | Action | No |
| **Atmosphere** | Physical sensory quality of the place | The environment | Partly (depends on view) |

## 19.3 Layers and Depth Cheat Sheet

| Layer | Purpose | Keep |
|---|---|---|
| **Foreground** | Frame, depth, texture | Sparse; soft; non-blocking |
| **Midground** | Subject and action | Clean silhouette; clear space |
| **Background** | Place and tonal contrast | Quiet; lower contrast; no tangents |
| **Distance** | Scale and region | Lighter, lower contrast, atmospheric fade |

**Depth cues to check:** overlap, relative size, perspective lines, atmospheric fade, texture gradient, tonal separation, light and shadow, parallax, focus.

## 19.4 Quick Clutter Audit

1. Squint test.
2. Label dominant, supporting, incidental.
3. Remove elements without a function.
4. Reduce bright, saturated, high-contrast, and moving elements near the subject.
5. Check tangents at the head and shoulders.
6. Check patterns and text.
7. Re-run the squint test.

## 19.5 Common Environment-Design Errors and Solutions

| Error | Solution |
|---|---|
| Environment treated as decoration | Assign each feature a function; remove those without. |
| Generic place | Add specific, positioned landmarks and evidence. |
| Too many details | Choose 3–7 features; apply the clutter audit. |
| Subject merges with the background | Adjust tone, distance, or camera position; check tangents. |
| Flat environment | Add overlap, atmospheric fade, tonal separation, and layers. |
| Wrong scale | Add reference objects with sizes; check the horizon. |
| Floating subject | Add contact shadows and a clear ground plane. |
| Impossible geometry | Specify standard doors and stairs; simplify; use a reference. |
| Mixed periods or rules | Define the period or rule set; audit every object. |
| Unmotivated light | Name sources and directions; remove unmotivated effects. |
| Sterile or over-distressed | Apply wear where causes exist. |
| Inconsistent weather or time | List all evidence (surfaces, light, subjects, motion). |
| Cloned crowds | Reduce, specify few distinct figures, keep them small and soft. |
| Reverse-shot mismatch | Use a layout map and background matching table. |
| Drift across AI clips | Environment Lock, landmark list, reference frames, shorter clips. |
| Unsuitable real location | Score with Section 7.3; apply the knockout rule. |

## 19.6 Final Operational Rule Set

1. **Treat the environment as information, not decoration.** Every feature should serve a visual, narrative, spatial, atmospheric, or practical purpose.
2. **Define the purpose and the must-know list before choosing the place.**
3. **Distinguish environment from background.** Design the environment; select the background by choosing the camera position.
4. **Choose a type and layout that satisfy the story, the action, and the camera,** and state landmarks with positions in a named frame of reference.
5. **Select 3–7 meaningful features;** remove contradictions and clutter.
6. **Build depth in layers** (foreground, midground, background, distance) with overlap, relative size, atmospheric fade, tonal separation, and consistent perspective.
7. **Control hierarchy:** keep the subject dominant, avoid tangents, and limit bright, high-contrast, moving, and textual distractions.
8. **Use evidence rather than exposition:** show use, wear, ownership, and events through placed, causal details.
9. **Apply wear and weathering where causes exist.**
10. **Keep scale and proportion plausible,** using reference objects and a consistent horizon; do not attribute every distortion to focal length.
11. **Ground the subject:** contact shadows, matching light, perspective, and atmosphere.
12. **Make light, weather, time, and season agree,** and give each visible light effect a source.
13. **Control background activity:** believable, directional, low in contrast, and sparse near the subject.
14. **Maintain continuity:** use a layout map, a landmark list, a state log, and background matching for reverse shots.
15. **For AI generation, specify observable features** (identity, layout, layers, materials, light, activity, scale, constraints), not adjectives; use an Environment Lock.
16. **Budget the prompt:** one environment, 3–7 features, one light logic, one activity statement, one lock list.
17. **Evaluate real locations with the scoring system** and apply the knockout rule; do not select by appearance alone.
18. **Diagnose in order** (purpose, identity, layout, scale, layers, hierarchy, light, evidence, dynamics, continuity, prompt conflicts), change **one** variable at a time, and check for side effects.
19. **Verify the output, not the description:** identify the place, squint for hierarchy, check scale and light, compare frames and neighbors.
20. **Approve only when no critical failure remains,** and record stylistic exceptions as intentional.

---

*End of file — Environment_and_Background_Design_and_Control_Cinematic_Knowledge.md*
