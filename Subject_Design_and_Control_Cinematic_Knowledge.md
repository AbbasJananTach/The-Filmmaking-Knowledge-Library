# SUBJECT DESIGN & CONTROL — CINEMATIC FILMMAKING KNOWLEDGE FILE
Version: 1.0
Purpose: Teach an AI filmmaking skill to make deliberate, story-driven decisions about the subject in every cinematic shot.

---

## 1. WHY THIS FILE EXISTS

The subject is the person, creature, object, or visual element that the audience is meant to notice, understand, or emotionally respond to in a shot. Subject design is not merely naming what appears in the frame. It includes identity, visible attributes, pose, action, expression, orientation, placement, relationships, condition, continuity, and the degree of emphasis given to the subject.

The AI must not blindly add every possible subject detail to every prompt. It must decide which details matter for the current story beat, shot size, camera position, lighting, environment, and intended audience response.

**Core rule:** Every subject instruction should have a purpose. If a detail does not support story clarity, emotional meaning, visual continuity, realism, or the intended composition, omit it or reduce its priority.

This file concerns the subject itself and how it is specified. Camera angles, camera movement, composition, lighting, color, lens choice, focus, sound, editing, and scene construction should have their own dedicated knowledge files. The subject file may refer to those disciplines when their interaction matters, but must not replace their detailed files.

---

## 2. THE AI'S RESPONSIBILITY

For each shot, the AI must determine:

1. Who or what is the subject?
2. Is there one primary subject, multiple co-primary subjects, or a primary subject plus secondary subjects?
3. What must the audience notice first?
4. What must the audience understand about the subject in this exact moment?
5. Which visible details are essential to recognition or storytelling?
6. What is the subject doing, and what observable action proves that?
7. What emotion or mental state should be communicated, and through which visible cues?
8. What physical condition is the subject in now?
9. What must remain consistent with earlier shots?
10. What is intentionally changing in this shot?
11. Which details should be explicit, and which should be left to natural performance or the generation model?
12. Could any instruction conflict with another instruction or overload the prompt?
13. How will the result be checked, and what should be corrected if it fails?

Do not treat a prompt as a bag of keywords. Treat it as a set of prioritized instructions.

---

## 3. SUBJECT HIERARCHY

### 3.1 Primary subject
The person or element carrying the shot's main story information or emotional focus.

Examples:
- A stranded heroine trying to catch her breath on a riverbank.
- A hand trembling while holding a damaged phone.
- A frightened animal trapped behind a fallen branch.

### 3.2 Secondary subject
An element that supports the primary subject's action or meaning but should not steal the focus unless the shot intentionally changes priority.

Examples:
- A capsized boat behind the heroine.
- A distant animal watching from the trees.
- A rescue light in the far background.

### 3.3 Background subjects
People, animals, or objects that establish place, scale, or activity without becoming the main point of attention.

### 3.4 Multiple co-primary subjects
Use this when the shot's meaning depends on a relationship or interaction between subjects. State the relationship and interaction clearly rather than simply listing both subjects.

**Decision rule:** If the audience needs to understand a relationship, describe what the subjects do in relation to one another. If the shot is about one character's reaction, make that character the primary subject and the other subject secondary.

---

## 4. SUBJECT IDENTITY

Identity is the set of stable traits that lets the audience recognize the same character or object across shots.

For a recurring character, define only traits that are useful and observable:
- Approximate adult age range or intended age presentation.
- Face shape and distinctive facial traits.
- Eye, eyebrow, hair, and skin characteristics where visible.
- Body proportions and overall build.
- Distinctive marks or accessories, if important.
- Stable wardrobe design, when continuity requires it.

Do not overload the prompt with a long inventory of tiny facial details when the shot is wide, the face is hidden, or the details cannot reasonably be visible. A close-up may need face detail; a distant silhouette does not.

### Identity priority
1. Explicit reference image or approved character sheet, if supplied.
2. Established character bible / continuity record.
3. Current shot description.
4. New details introduced only when necessary and not in conflict with the above.

If the current request conflicts with a reference identity, do not silently redesign the character. Preserve identity and flag the conflict or make only the specifically requested change.

### Identity versus condition
Stable identity should not change casually. Temporary condition may change:
- Stable: face shape, natural hair type, eye color, body proportions, distinctive features.
- Temporary: wet hair, mud, sweat, bruises, fatigue, dirt, torn clothing, expression, posture.

A survival film should show accumulated wear in a plausible way. Do not reset the character to perfectly clean and dry after every shot unless a time jump, scene change, or deliberate reset explains it.

---

## 5. PHYSICAL APPEARANCE AND DETAIL LEVEL

Specify appearance according to what the audience can actually see and what the shot needs.

### Useful appearance categories
- Face and hair.
- Body build and proportions.
- Skin and other visible surface qualities.
- Clothing, footwear, and accessories.
- Distinctive identifying features.
- Current condition: wet, dusty, muddy, injured, exhausted, cold, or clean.
- Interaction with the environment: soaked sleeves, mud on knees, leaves caught in hair.

### Under-specification
If important identity or wardrobe information is omitted, the generator may invent it, vary it between shots, or produce a generic subject.

Possible results:
- Character looks different from the reference.
- Clothing or accessories change unexpectedly.
- Age presentation or body proportions drift.
- A story-relevant condition, such as wet clothes after falling into a river, is missing.

### Over-specification
If too many low-priority details are demanded at once, the model may ignore some instructions, mix incompatible traits, or spend attention on details that are not visible.

Possible results:
- The face or body becomes inconsistent.
- Clothing details compete with the action.
- A wide shot is burdened with close-up-only detail.
- The prompt becomes long without improving the image.

### Correct level
Use enough detail to control the visible result, but no more than the shot can reveal. Prioritize identity, story-relevant condition, and action over decorative detail.

---

## 6. POSE, ORIENTATION, AND BODY LANGUAGE

These are related but not interchangeable.

- **Pose:** The subject's physical arrangement at a moment: crouching, kneeling, lying down, standing, reaching.
- **Orientation:** Which direction the body or face is turned: facing camera, three-quarter profile, side view, back to camera, looking screen-left.
- **Body language:** Observable physical behavior that communicates intention or emotion: shoulders drawn inward, weight shifted back, protective arm position, cautious lean.
- **Gesture:** A specific movement or position of a body part: raising a hand, gripping a branch, pointing, covering the mouth.

Use concrete, observable descriptions rather than vague labels alone.

Weak: “She looks scared.”
Stronger: “She freezes, shoulders tense, breath shallow, eyes fixed on movement between the trees.”

The stronger version describes visible behavior. Do not force exaggerated gestures when subtle performance is more realistic.

### Body-language rules
- Match posture to the character's physical state and immediate goal.
- A character who is exhausted should not hold a perfectly effortless, heroic pose without a story reason.
- Fear does not always mean screaming or wide-open eyes; it may appear as stillness, hesitation, scanning, or controlled breathing.
- Do not specify every finger, elbow, shoulder, and foot unless precise hand action is central to the shot.
- If an object interaction matters, describe contact clearly: which hand holds it, where it touches, and what action occurs.

---

## 7. ACTION: MAKE IT OBSERVABLE

An action instruction should state what the subject does, not merely what the subject is supposed to achieve.

Weak: “She survives the jungle.”
Better: “She tests the muddy bank with one foot, grips a low root, and carefully climbs onto firmer ground.”

For a single generated shot, normally define:
1. Starting state.
2. Main visible action.
3. Ending state or intended final beat.
4. Relevant reaction or consequence.

Avoid stuffing many unrelated actions into one shot. If the action has several distinct beats, divide it into separate shots or clearly state the sequence and timing. A model may collapse a long list of actions into one confusing image.

### Action realism
- Respect gravity, balance, momentum, reach, and body mechanics.
- Make contact with objects physically plausible.
- Ensure the subject can reach the item or surface described.
- Avoid contradictory simultaneous actions.
- Use action verbs that can be seen on screen.
- Do not write internal thoughts as if they were visible. Translate them into behavior where possible.

---

## 8. FACIAL EXPRESSION AND EMOTIONAL READABILITY

The prompt should communicate the intended emotion through visible facial cues and behavior.

Possible cues include:
- Eyes: gaze direction, focus, blinking, squinting, widening.
- Brows: raised, drawn together, relaxed.
- Mouth and jaw: pressed lips, parted lips, clenched jaw, trembling.
- Head: lowered, tilted, turning toward a sound.
- Whole-body behavior: stillness, recoil, cautious approach, protective movement.

### Avoid emotional contradictions
Do not request “calm and terrified” unless the intended meaning is controlled fear. Instead, explain the combination: “She is visibly frightened but deliberately suppresses panic, keeping her movements controlled.”

### Emotion intensity
- Too little: the emotion may be unreadable.
- Too much: the performance may become melodramatic, cartoonish, or unintentionally comic.
- Appropriate: intensity matches the danger, shot size, story beat, and character.

A close-up can communicate a small eye or mouth change. A wide shot needs larger body-language cues because facial detail may not be visible.

Do not demand that every frame show an extreme expression. Emotional progression across shots is usually more believable than a constant maximum-intensity expression.

---

## 9. SUBJECT POSITION AND SCREEN DIRECTION

Subject placement is primarily a composition concern, but subject instructions may specify the position needed for story clarity.

Examples:
- “The heroine stands on the left side of the frame, looking toward the river on screen-right.”
- “Her hand enters the frame from the lower-right foreground.”
- “The animal remains distant behind her and does not dominate the shot.”

Avoid confusing spatial terms. “Left” can mean the subject's left or the viewer's left. When placement matters, use:
- screen-left / screen-right for frame position;
- subject's left hand / right hand for body-side identity;
- camera-facing / away from camera for orientation.

Do not add rigid placement instructions when the composition file will decide placement. Use them when they protect continuity, eyeline, action readability, or a required story reveal.

---

## 10. SUBJECT RELATIONSHIPS AND INTERACTIONS

When subjects interact, describe the physical relationship and the cause-and-effect.

Weak: “The girl and the dog.”
Better: “The girl kneels several steps away from the frightened dog, lowers one open hand without approaching, and waits for it to respond.”

For contact or object handling, specify the important facts:
- Which subject initiates the action?
- What exactly makes contact?
- Where does contact occur?
- Is the contact gentle, forceful, hesitant, or accidental?
- What visible response follows?
- Does the interaction change the subject's position or condition?

Do not invent contact that is not intended. Ambiguous interaction can produce fused limbs, floating objects, incorrect hand placement, or confusing blocking.

---

## 11. SUBJECT CONDITION AND PHYSICAL CONSEQUENCES

Track temporary conditions through the timeline:
- Wetness and drying.
- Dirt, mud, blood, or other marks when appropriate to the story.
- Fatigue, breathlessness, shivering, pain, and reduced movement.
- Clothing damage.
- Lost, broken, or recovered equipment.
- Hair and accessories affected by weather or action.

Changes should have a cause. If the subject gets wet, muddy, injured, or exhausted, retain that condition in subsequent shots until a plausible event changes it.

Do not escalate injury or damage arbitrarily. Keep the level consistent with what the story depicts.

For realistic survival stories, show physical limits. A character who has run, climbed, and struggled for hours may move more slowly, pause to recover, protect an injured limb, or make less precise movements.

---

## 12. WARDROBE AND ACCESSORIES AS STORY INFORMATION

Wardrobe can establish identity, role, setting, and condition. It is not merely decoration.

Specify:
- Garment type and recognizable design.
- Color only when it matters for continuity or story.
- Fit and practical suitability.
- Footwear and essential accessories.
- Condition and changes caused by events.

Do not change wardrobe between adjacent shots without a reason. Do not keep clothing pristine after events that should visibly affect it. Do not add accessories simply to make the subject more detailed.

If the model is likely to alter small design features, prioritize a few stable, recognizable wardrobe traits instead of an excessive inventory.

---

## 13. SUBJECT EMPHASIS AND VISUAL PRIORITY

The subject can be emphasized through many film-making choices, but this file should describe the intended priority rather than prescribe every technical solution.

Ask:
- Must the audience notice the subject, the subject's action, or a reaction?
- Is the face essential, or is the silhouette/body/action enough?
- Is the subject supposed to dominate the shot or feel small against the environment?
- Should a secondary object attract attention because it carries story information?
- Is the subject visible clearly, partially hidden, obscured, or only implied?

The camera, composition, lighting, color, focus, and editing files should explain how to achieve this emphasis technically.

Do not demand “everything in sharp focus, every detail visible, dramatic lighting, shallow depth of field, and a huge environment” all at once if those requirements conflict. State the story priority first, then let the relevant technical decisions support it.

---

## 14. HOW MUCH SUBJECT DETAIL SHOULD BE USED?

There is no universal ideal amount. Detail should scale with the shot and the task.

### Minimal detail is suitable when:
- The subject is tiny in a wide establishing shot.
- The subject is only a silhouette.
- The action or environment is more important than identity detail.
- The character has already been established and reference material is available.

### Moderate detail is suitable when:
- The subject's identity, clothing, posture, and action must be readable.
- The shot is a medium shot or full-body shot.
- The subject interacts with an object or environment.

### High detail is suitable when:
- The shot is a close-up or insert.
- Identity consistency is critical.
- A hand, face, wound, object, or subtle reaction carries the story.
- A specific continuity detail must not drift.

### What happens if every detail is set to maximum?
The prompt can become internally crowded. The generator may prioritize the wrong feature, miss the action, or fail to preserve all constraints. Maximum detail is not maximum control.

### What happens if one detail is emphasized while others are vague?
The model may satisfy the emphasized trait while inventing the rest. This is acceptable when creative variation is wanted, but risky for a recurring character or continuity-critical shot.

### Balancing detail
Give the most precise instructions to the details that are:
1. Story-critical.
2. Visible at the chosen shot size.
3. Necessary for identity or continuity.
4. Most likely to be misunderstood by the generator.

---

## 15. INTERACTIONS WITH OTHER CINEMATIC ELEMENTS

Subject choices do not exist in isolation.

- **Scene:** Establishes what is happening and why the subject is there.
- **Composition:** Determines the subject's spatial relationship to the frame and other elements.
- **Camera angle:** Changes the viewer's perceived relationship to the subject.
- **Shot size:** Determines how much of the subject can be read.
- **Camera movement:** Changes how the subject is revealed or followed over time.
- **Lighting:** Changes visibility, texture, depth, and emotional impression.
- **Color:** Influences separation, continuity, and emotional tone.
- **Focus and lens:** Influence attention, perspective, and how much detail is readable.
- **Environment:** Affects the subject's physical interaction and condition.
- **Continuity:** Preserves identity, wardrobe, condition, position, and action across shots.
- **Editing:** Determines how a subject's action and reaction are understood across shots.
- **Sound:** May reveal a subject's presence or reaction even when it is not visible.

Do not try to solve every problem by adding more subject description. If the problem is framing, use composition instructions. If the problem is camera height, use camera-angle instructions. If the problem is darkness or shadow, use lighting instructions. Keep each file's responsibility clear.

---

## 16. COMMON FAILURE MODES AND CORRECTIONS

### Failure: The character looks different in every shot
Likely causes: identity described inconsistently, no reliable reference, too many conflicting details, or continuity not tracked.
Correction: Use one approved identity description/reference and repeat only the essential visible identity traits in each relevant shot.

### Failure: The character's clothing changes
Likely causes: wardrobe not specified, too many variants allowed, or continuity state omitted.
Correction: Maintain a wardrobe/condition record and state essential clothing traits.

### Failure: The subject's emotion looks exaggerated
Likely causes: emotional label too broad, intensity too high, or no specific behavioral cues.
Correction: Describe restrained, observable cues and match intensity to the story beat.

### Failure: The subject does not perform the requested action
Likely causes: too many actions, unclear verbs, impossible physical geometry, or competing priorities.
Correction: Reduce the shot to one main action, clarify the starting state and contact points, and split multi-beat actions.

### Failure: Hands or object contact look wrong
Likely causes: interaction is ambiguous or too many small gestures are specified.
Correction: Specify the relevant hand, object, point of contact, and intended result; avoid unnecessary finger-by-finger instructions.

### Failure: The subject is too small or too dominant
Likely causes: subject emphasis and framing requirements are not aligned.
Correction: State the story priority and intended visibility; refer to the composition and shot-size files for technical implementation.

### Failure: The subject looks clean after a survival event
Likely cause: temporary condition was not carried forward.
Correction: Track wetness, dirt, damage, fatigue, and equipment state across the sequence.

### Failure: The subject looks like a posed model instead of a real person
Likely causes: generic “beautiful/cinematic” wording, excessive perfection, static pose, or no task-related behavior.
Correction: Give the subject a physical objective, natural weight distribution, small reactive movements, and context-appropriate imperfections.

### Failure: Too many characters compete for attention
Likely cause: no primary/secondary hierarchy.
Correction: Identify the primary subject and specify what the secondary subjects contribute.

---

## 17. SUBJECT PROMPT-BUILDING TEMPLATE

Use only the fields that matter. Do not blindly fill every field for every shot.

Primary subject:
[Who or what the audience should notice first.]

Identity/reference:
[Approved identity or reference-image instruction, if applicable.]

Visible appearance:
[Only details visible and relevant at this shot size.]

Wardrobe and accessories:
[Stable traits and current condition.]

Pose and orientation:
[Body position, direction faced, gaze direction, if relevant.]

Main action:
[One clear, observable action.]

Expression/body language:
[Visible cues that communicate the intended state.]

Physical condition:
[Wetness, dirt, fatigue, injury, damage, or other continuity state.]

Relationship to other subjects/objects:
[Contact, distance, interaction, cause and effect.]

Story priority:
[What the audience must understand or feel about this subject in this shot.]

Continuity constraints:
[What must remain unchanged from previous shots and what is allowed to change.]

Do-not-introduce constraints:
[Only likely, important unwanted changes; avoid long generic negative lists.]

---

## 18. DECISION LOGIC FOR THE AI

Before writing the final shot prompt, apply this sequence:

1. Read the scene's story purpose.
2. Identify the primary subject and any secondary subjects.
3. Determine what information about the subject is necessary for this shot.
4. Check whether a character reference or continuity record exists.
5. Select the appropriate detail level based on the intended shot size and visibility.
6. Define one main observable action or reaction.
7. Specify expression and body language only to the degree needed.
8. Track wardrobe, condition, equipment, and injuries from earlier shots.
9. Check physical plausibility and remove contradictory instructions.
10. Delegate camera angle, composition, lighting, color, focus, movement, and sound decisions to their own dedicated rules while preserving any necessary cross-references.
11. Rank instructions: story-critical first, identity/continuity second, action and visible condition next, decorative details last.
12. Run a consistency check against the preceding and following shots.
13. Produce the prompt in the requested format and keep internal reasoning out of the user-facing output unless requested.

If a critical detail is unknown, do not invent a complicated backstory. Choose a safe, minimal default only when it will not affect the intended result; otherwise ask one concise clarification.

---

## 19. QUALITY-CONTROL CHECKLIST

Before accepting a generated shot, check:

- Is the intended primary subject present?
- Does the subject match the approved identity?
- Are age presentation, body proportions, hair, face, and distinctive features consistent where visible?
- Is wardrobe consistent with the story timeline?
- Is the subject's pose and orientation correct?
- Is the main action visible and physically plausible?
- Does the expression match the intended emotional beat without becoming exaggerated?
- Are hands and object interactions plausible?
- Is the subject's physical condition consistent with previous events?
- Are secondary subjects supporting rather than accidentally replacing the intended focus?
- Are details appropriate for the shot's visibility?
- Did the prompt accidentally prescribe camera, lighting, or composition choices that conflict with another file?
- What is the single most important failure to correct in the next iteration?

Do not attempt to fix every minor defect at once. Correct the highest-priority failure first, regenerate, then reassess.

---

## 20. WORKED EXAMPLE — THE STRANDED HEROINE

### Story beat
After being swept from a small boat, the heroine reaches a muddy riverbank. She is exhausted and frightened but trying to assess her situation.

### Subject specification
Primary subject: the established young adult heroine from the approved character reference.
Visible condition: wet clothing and hair, mud on knees and hands, tired posture, no new severe injury unless the story established it.
Pose: crouched low on the muddy bank, one hand braced against the ground.
Action: she catches her breath, looks at her wet hands, then turns her attention toward the river after hearing a sound.
Expression/body language: restrained fear and exhaustion; tense shoulders, shallow breathing, alert gaze. Avoid theatrical screaming.
Continuity: preserve face identity, hair characteristics, body proportions, and wardrobe design; carry forward the wetness and mud from the accident.
Story priority: communicate that she has survived the immediate danger but is vulnerable and beginning to assess what to do next.

### Why this works
- It defines an observable story moment rather than the broad idea “survive in the jungle.”
- It separates stable identity from temporary physical condition.
- It specifies a clear action sequence without forcing numerous unrelated actions.
- It uses physical cues to communicate emotion.
- It keeps technical decisions such as angle, framing, lighting, and focus available to their dedicated knowledge files.

### Common weaker version
“A beautiful girl in a jungle, cinematic, dramatic, realistic, scared, 4K.”

Why it is weak:
- No identity control.
- No concrete action.
- No continuity state.
- “Scared” is not translated into observable performance.
- “Cinematic” and “4K” do not explain what the subject must do.

---

## 21. FINAL OPERATING PRINCIPLES

1. Subject details must serve the story, not merely decorate the prompt.
2. Define stable identity separately from temporary condition.
3. Describe visible behavior rather than relying only on abstract emotion labels.
4. Prefer one clear main action per shot.
5. Match detail to what the shot can reveal.
6. Use more precision for identity-critical and continuity-critical details.
7. Do not maximize every variable simultaneously.
8. Track physical consequences across time.
9. Keep subject instructions consistent with the scene and other technical knowledge files.
10. Treat generated output as something to inspect and correct, not as guaranteed compliance.
11. When revising, change the smallest number of instructions needed to fix the main failure.
12. Never confuse “more words” with “more control.”

END OF FILE
