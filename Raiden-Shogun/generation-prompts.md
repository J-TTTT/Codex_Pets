# Raiden-Shogun generation prompts

Generated with the built-in image generation tool, grounded in the approved Raiden-Shogun reference.

## base-pet.md

Create one clean full-body reference sprite for Codex pet Raiden-Shogun.

Pet identity: Use the supplied approved Raiden-Shogun image as sole identity authority. Purple bangs and side locks, one thick long purple braid connected behind head and curving down viewer-left in front view, purple flower and gold ornament on viewer-left, light/deep-purple Japanese clothing, red knots, gold details, dark-purple stockings and sandals. Preserve asymmetric flower, braid, shoulder/outfit relationships under natural occlusion in turns. Empty hands; NO weapons/props. Full head ornament, braid end, sleeves and feet inside every frame. Quiet restrained motion. Idle hands down with gentle visible breath/blink. No effects, symbols, shadows or baked checkerboard. Generate left run separately, never mirror..
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Exact approved reference anime illustration. Clean fine linework, soft cel shading, subtle gradients and hair highlights. Preserve rounded face, purple anime eyes, blush, gentle small smile, exact head/body proportions. No plush, realistic3D, plastic or redesign..


Place a single centered pose on a perfectly flat pure user-selected #00FF00 chroma-key background. Keep the full pet visible, compact, readable at 192x208, and easy to animate. Preserve approved reference identity cues. No scenery, text, borders, checkerboard transparency, shadows, glows, detached effects, or extra props. Keep #00FF00 and close colors out of the pet, props, highlights, and effects.


## 000.md

Repair one cardinal anchor for Codex pet `Raiden-Shogun`: `000` means looking up.

Use the canonical base, completed standard contact sheet, approved cardinal-strip cells, and `qa/look-mechanics.md` for identity, scale, registration, and pet-specific gaze mechanics. Keep the face broadly frontal and point the eyes and natural head mechanism toward the TOP edge. Screen coordinates are viewer-relative.

Output one centered complete full-body pose on a flat pure user-selected #00FF00 background with generous padding. Keep the feet/base and lower body registered to the approved anchors. The requested cardinal must be unmistakable at final 192x208 display size.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement eyes, labels, arrows, guide marks, shadows, scenery, detached effects, or chroma-key colors inside the pet.


## 090.md

Repair one cardinal anchor for Codex pet `Raiden-Shogun`: `090` means looking right.

Use the canonical base, completed standard contact sheet, approved cardinal-strip cells, and `qa/look-mechanics.md` for identity, scale, registration, and pet-specific gaze mechanics. Put the nose tip, pupils, face surface, or natural aiming feature on the screen-right side of the head center. Screen coordinates are viewer-relative.

Output one centered complete full-body pose on a flat pure user-selected #00FF00 background with generous padding. Keep the feet/base and lower body registered to the approved anchors. The requested cardinal must be unmistakable at final 192x208 display size.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement eyes, labels, arrows, guide marks, shadows, scenery, detached effects, or chroma-key colors inside the pet.


## 180.md

Repair one cardinal anchor for Codex pet `Raiden-Shogun`: `180` means looking down.

Use the canonical base, completed standard contact sheet, approved cardinal-strip cells, and `qa/look-mechanics.md` for identity, scale, registration, and pet-specific gaze mechanics. Keep the face broadly frontal and point the eyes and natural head mechanism toward the BOTTOM edge. Screen coordinates are viewer-relative.

Output one centered complete full-body pose on a flat pure user-selected #00FF00 background with generous padding. Keep the feet/base and lower body registered to the approved anchors. The requested cardinal must be unmistakable at final 192x208 display size.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement eyes, labels, arrows, guide marks, shadows, scenery, detached effects, or chroma-key colors inside the pet.


## 270.md

Repair one cardinal anchor for Codex pet `Raiden-Shogun`: `270` means looking left.

Use the canonical base, completed standard contact sheet, approved cardinal-strip cells, and `qa/look-mechanics.md` for identity, scale, registration, and pet-specific gaze mechanics. Put the nose tip, pupils, face surface, or natural aiming feature on the screen-left side of the head center. Screen coordinates are viewer-relative.

Output one centered complete full-body pose on a flat pure user-selected #00FF00 background with generous padding. Keep the feet/base and lower body registered to the approved anchors. The requested cardinal must be unmistakable at final 192x208 display size.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement eyes, labels, arrows, guide marks, shadows, scenery, detached effects, or chroma-key colors inside the pet.


## look-cardinals.md

Four cardinals MUST be UP, SCREEN-RIGHT, DOWN, SCREEN-LEFT in that order. Preserve exact canonical Raiden-Shogun identity and asymmetric braid/flower/armor. Arms relaxed down, feet/body fixed. UP liftedchin/high eyes; RIGHT nose/face and eyes clearly image-right; DOWN tuckedchin/lowvisibleeyes; LEFT nose/face and eyes clearly image-left. Natural head/neck yaw and pitch, no body rotation or mirroring. Read qa/look-mechanics.md. Four SMALL whole figures, broad puregreen margins above/below and between; keep entiregoldtip/braid/sleeves/feet within each of4 equal-width invisible slots. No guide marks.

Create one horizontal four-cardinal anchor strip for Codex pet `Raiden-Shogun`.

Use the attached canonical base, completed standard contact sheet, and layout guide for exact identity, style, scale, baseline, face construction, materials, palette, markings, props, and spacing. Read `qa/look-mechanics.md` and use the pet's natural gaze mechanism.

Output exactly four centered complete full-body poses in this exact left-to-right order: `000 up`, `090 screen-right`, `180 down`, `270 screen-left`. Screen-left and screen-right always mean the viewer's image edges, never the character's own left or right.

For `000`, keep the face broadly frontal and point the eyes and natural head mechanism toward the TOP edge. For `090`, put the nose tip, pupils, face surface, or natural aiming feature on the screen-right side of the head center. For `180`, keep the face broadly frontal and point toward the BOTTOM edge. For `270`, apply the inverse screen-left landmark rule. Every cardinal must be unmistakable without labels.

Place one pose in each invisible equal-width slot on a flat pure user-selected #00FF00 background with generous padding. Keep scale, feet/base, lower body, and registration consistent across all four slots.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement eyes, labels, degree text, arrows, boxes, guide marks, shadows, scenery, detached effects, or chroma-key colors inside the pet.


## look-up-repair.md

Create ONE whole-body Raiden-Shogun UP-looking cardinal reference. This is a precise head/eye pose edit of the canonical character, not a redesign. Canonical and original are identity; standard contact fixes body proportions; four-pose strip fixes the stable planted body and other correct directions.

The previous first pose looked neutral. Make upward attention unmistakable: gently tip the head BACK at the neck and lift the chin so the underside/neck connection is subtly more visible. Her purple irises and pupils visibly aim toward the TOP of the original anime eye apertures, with eyelids/brows following coherently. Keep eyes open, rounded face unchanged, tiny closed gentle smile. She is looking at something ABOVE the viewer's head, not at the viewer. Preserve natural anime eye structure and face proportions, do not add or replace eye layers or round googly eyes.

Keep torso, skirt, feet, relaxed lowered hands, head SIZE and braid root anchored; gold/purple flower ornament follows the skull naturally and long braid follows very slightly without moving its lower end. Exact canonical purple hair, thick long braid, flower/goldornament, asymmetric white-purple clothing/redknots/golddetails/shoulderarmor, stockings and shoes. Empty hands, no props. Full goldtip, braidend, sleeves and feet with generous padding on flat puregreen #00FF00. No text, effects, shadows, checkerboard or scenery. One full figure only.

## failed.md

Create Codex pet row `failed` for `Raiden-Shogun`: exactly 8 full-body frames in one horizontal strip on flat pure user-selected #00FF00.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Use the supplied approved Raiden-Shogun image as sole identity authority. Purple bangs and side locks, one thick long purple braid connected behind head and curving down viewer-left in front view, purple flower and gold ornament on viewer-left, light/deep-purple Japanese clothing, red knots, gold details, dark-purple stockings and sandals. Preserve asymmetric flower, braid, shoulder/outfit relationships under natural occlusion in turns. Empty hands; NO weapons/props. Full head ornament, braid end, sleeves and feet inside every frame. Quiet restrained motion. Idle hands down with gentle visible breath/blink. No effects, symbols, shadows or baked checkerboard. Generate left run separately, never mirror.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Blocked/failed loop: slumped or deflated reaction with sad or closed eyes.

State requirements:
- Show failure through slumped pose, drooping ears/limbs, closed or sad eyes, and lower body position.
- Tears, small smoke puffs, or tiny stars are allowed only if attached to or overlapping the pet silhouette and kept inside the same frame slot.
- Do not draw red X marks, floating symbols, detached stars, separated smoke clouds, falling tear drops, dust, or other loose effects.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #00FF00 colors in the pet.


## idle.md

Create Codex pet row `idle` for `Raiden-Shogun`: exactly 6 full-body frames in one horizontal strip on flat pure user-selected #00FF00.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Use the supplied approved Raiden-Shogun image as sole identity authority. Purple bangs and side locks, one thick long purple braid connected behind head and curving down viewer-left in front view, purple flower and gold ornament on viewer-left, light/deep-purple Japanese clothing, red knots, gold details, dark-purple stockings and sandals. Preserve asymmetric flower, braid, shoulder/outfit relationships under natural occlusion in turns. Empty hands; NO weapons/props. Full head ornament, braid end, sleeves and feet inside every frame. Quiet restrained motion. Idle hands down with gentle visible breath/blink. No effects, symbols, shadows or baked checkerboard. Generate left run separately, never mirror.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Calm low-distraction resting loop: subtle breathing, tiny blink, slight head/body bob, and only quiet persona-preserving motion.

State requirements:
- CRITICAL: idle is the low-distraction baseline state and the first frame is also used as the reduced-motion static pet.
- Use only subtle idle motion: gentle breathing, a tiny blink, a slight head or body bob, a very small material sway, or another quiet motion that fits the pet persona.
- Keep the pet essentially in the same pose, facing direction, silhouette, markings, palette, and prop state across all 6 frames.
- Idle variation must stay calm but still read as animation; do not repeat effectively identical copies across the loop.
- Do not show waving, walking, running, jumping, talking, working, reviewing, emotional reactions, large gestures, item interactions, or new props.
- Feet, base, body, or object anchor should remain planted or nearly planted.
- The first and last frames should be very close visually so the loop feels calm and does not pop.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #00FF00 colors in the pet.


## jumping.md

Create Codex pet row `jumping` for `Raiden-Shogun`: exactly 5 full-body frames in one horizontal strip on flat pure user-selected #00FF00.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Use the supplied approved Raiden-Shogun image as sole identity authority. Purple bangs and side locks, one thick long purple braid connected behind head and curving down viewer-left in front view, purple flower and gold ornament on viewer-left, light/deep-purple Japanese clothing, red knots, gold details, dark-purple stockings and sandals. Preserve asymmetric flower, braid, shoulder/outfit relationships under natural occlusion in turns. Empty hands; NO weapons/props. Full head ornament, braid end, sleeves and feet inside every frame. Quiet restrained motion. Idle hands down with gentle visible breath/blink. No effects, symbols, shadows or baked checkerboard. Generate left run separately, never mirror.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Hover jump loop: anticipation, lift, airborne peak, descent, and settle through body height.

State requirements:
- Show the jump through pose and vertical body position only: anticipation, lift, airborne peak, descent, settle.
- Do not draw ground shadows, contact shadows, drop shadows, oval shadows, landing marks, dust, smears, bounce pads, or motion marks under the pet.
- Keep the background outside the pet perfectly flat chroma key with no darker key-colored patches.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #00FF00 colors in the pet.


## look-row-10.md

Create Codex v2 pet look row 10 for `Raiden-Shogun` as exactly 8 full-body frames in this order: 180, 202.5, 225, 247.5, 270, 292.5, 315, 337.5.

Use the canonical base, standard contact sheet, layout guide, approved four-cardinal strip, and `qa/look-mechanics.md`. Draw the complete eight-pose row as one coherent animation family, interpolating even 22.5-degree steps between the cardinal pose families. Keep the same pet identity, face construction, materials, palette, markings, and props. Each direction must read correctly at pet size and join continuously at the 000 and 180 boundaries.

DIRECTION TARGETS — use these to shape the coherent row, not as pixel-level landmark gates:

1. `180`: vertical DOWN; no horizontal requirement.
2. `202.5`: horizontal SCREEN-LEFT and vertical DOWN.
3. `225`: horizontal SCREEN-LEFT and vertical DOWN.
4. `247.5`: horizontal SCREEN-LEFT and vertical DOWN.
5. `270`: horizontal SCREEN-LEFT; no vertical requirement.
6. `292.5`: horizontal SCREEN-LEFT and vertical UP.
7. `315`: horizontal SCREEN-LEFT and vertical UP.
8. `337.5`: horizontal SCREEN-LEFT and vertical UP.

Cardinals must be unmistakable. Intermediate poses should broadly occupy the intended quadrant and advance naturally through the ordered loop. Minor pupil, nose, eyelid, or aiming-feature deviations are acceptable when the overall direction, continuity, identity, and motion remain coherent. Do not deform the character merely to make every intermediate axis independently obvious.

HARD LAYOUT AND CONTINUITY CONTRACT — DETERMINISTIC REGISTRATION: draw exactly eight separated pose groups in left-to-right direction order. Keep enough chroma-only space between neighboring poses that each complete pose can be detected without cutting through foreground. Approximate the guide's equal spacing, but do not distort a pose merely to hit an exact source-canvas coordinate; deterministic assembly will crop the eight ordered groups, then apply one shared scale and baseline.

Use the same body height, head size, baseline, and planted-body position across the generated family. Never overlap neighboring poses, merge two poses into one connected group, crop foreground at the outer canvas edge, or resize one pose independently.

Keep the feet, base, or lower torso planted at the same coordinates across all eight frames. Express direction through the eyes, face, head, upper body, and physically appropriate prop movement, not by moving, rotating, or rescaling the entire sprite.

ROW-BOUNDARY LOCK: 180 must continue directly from row 9's 157.5, matching its body size, baseline, planted anchor, expression, and construction. 337.5 must be one even 22.5-degree step before 000: nearly up-facing while remaining on the overall left-hand arc. Do not distort pupils, nose, or body geometry merely to exaggerate the subtle horizontal component.

PRE-RETURN CHECK: reject this result if it does not contain eight separated pose groups in the required order; neighboring poses overlap; foreground is cropped at the outer canvas edge; any frame changes sprite scale, body or head size, baseline, or planted-body position; the row visibly reverses into the wrong half of the loop; or 180 does not continue from 157.5 or 337.5 does not flow evenly into 000. Minor intermediate pupil or nose deviations are not rejection reasons. Exact cell cropping, resizing, and recentering happen deterministically after generation.

Use a flat pure user-selected #00FF00 background. One complete unclipped pose per invisible slot. No whole-sprite rotation, replacement eyes, labels, guide marks, shadows, glows, scenery, detached effects, or #00FF00 colors in the pet.


## look-row-9.md

Create Codex v2 pet look row 9 for `Raiden-Shogun` as exactly 8 full-body frames in this order: 000, 022.5, 045, 067.5, 090, 112.5, 135, 157.5.

Use the canonical base, standard contact sheet, layout guide, approved four-cardinal strip, and `qa/look-mechanics.md`. Draw the complete eight-pose row as one coherent animation family, interpolating even 22.5-degree steps between the cardinal pose families. Keep the same pet identity, face construction, materials, palette, markings, and props. Each direction must read correctly at pet size and join continuously at the 000 and 180 boundaries.

DIRECTION TARGETS — use these to shape the coherent row, not as pixel-level landmark gates:

1. `000`: vertical UP; no horizontal requirement.
2. `022.5`: horizontal SCREEN-RIGHT and vertical UP.
3. `045`: horizontal SCREEN-RIGHT and vertical UP.
4. `067.5`: horizontal SCREEN-RIGHT and vertical UP.
5. `090`: horizontal SCREEN-RIGHT; no vertical requirement.
6. `112.5`: horizontal SCREEN-RIGHT and vertical DOWN.
7. `135`: horizontal SCREEN-RIGHT and vertical DOWN.
8. `157.5`: horizontal SCREEN-RIGHT and vertical DOWN.

Cardinals must be unmistakable. Intermediate poses should broadly occupy the intended quadrant and advance naturally through the ordered loop. Minor pupil, nose, eyelid, or aiming-feature deviations are acceptable when the overall direction, continuity, identity, and motion remain coherent. Do not deform the character merely to make every intermediate axis independently obvious.

HARD LAYOUT AND CONTINUITY CONTRACT — DETERMINISTIC REGISTRATION: draw exactly eight separated pose groups in left-to-right direction order. Keep enough chroma-only space between neighboring poses that each complete pose can be detected without cutting through foreground. Approximate the guide's equal spacing, but do not distort a pose merely to hit an exact source-canvas coordinate; deterministic assembly will crop the eight ordered groups, then apply one shared scale and baseline.

Use the same body height, head size, baseline, and planted-body position across the generated family. Never overlap neighboring poses, merge two poses into one connected group, crop foreground at the outer canvas edge, or resize one pose independently.

Keep the feet, base, or lower torso planted at the same coordinates across all eight frames. Express direction through the eyes, face, head, upper body, and physically appropriate prop movement, not by moving, rotating, or rescaling the entire sprite.

ROW-BOUNDARY LOCK: 157.5 must be one even 22.5-degree step before 180. Match the approved 180 pose's body size, baseline, planted anchor, expression, and construction. Preserve the overall right-hand arc, but do not distort pupils, nose, or body geometry merely to exaggerate the subtle horizontal component.

PRE-RETURN CHECK: reject this result if it does not contain eight separated pose groups in the required order; neighboring poses overlap; foreground is cropped at the outer canvas edge; any frame changes sprite scale, body or head size, baseline, or planted-body position; the row visibly reverses into the wrong half of the loop; or 157.5 does not flow evenly into 180. Minor intermediate pupil or nose deviations are not rejection reasons. Exact cell cropping, resizing, and recentering happen deterministically after generation.

Use a flat pure user-selected #00FF00 background. One complete unclipped pose per invisible slot. No whole-sprite rotation, replacement eyes, labels, guide marks, shadows, glows, scenery, detached effects, or #00FF00 colors in the pet.


## review.md

Create Codex pet row `review` for `Raiden-Shogun`: exactly 6 full-body frames in one horizontal strip on flat pure user-selected #00FF00.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Use the supplied approved Raiden-Shogun image as sole identity authority. Purple bangs and side locks, one thick long purple braid connected behind head and curving down viewer-left in front view, purple flower and gold ornament on viewer-left, light/deep-purple Japanese clothing, red knots, gold details, dark-purple stockings and sandals. Preserve asymmetric flower, braid, shoulder/outfit relationships under natural occlusion in turns. Empty hands; NO weapons/props. Full head ornament, braid end, sleeves and feet inside every frame. Quiet restrained motion. Idle hands down with gentle visible breath/blink. No effects, symbols, shadows or baked checkerboard. Generate left run separately, never mirror.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Ready-review loop: focused inspection of completed output with lean, blink, narrowed eyes, head tilt, or paw pose.

State requirements:
- Show review through lean, blink, narrowed eyes, head tilt, or paw/hand position.
- Do not add magnifying glasses, papers, code, UI, punctuation, symbols, or other new props unless they already exist in the base pet identity.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #00FF00 colors in the pet.


## running-left.md

Create Codex pet row `running-left` for `Raiden-Shogun`: exactly 8 full-body frames in one horizontal strip on flat pure user-selected #00FF00.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Use the supplied approved Raiden-Shogun image as sole identity authority. Purple bangs and side locks, one thick long purple braid connected behind head and curving down viewer-left in front view, purple flower and gold ornament on viewer-left, light/deep-purple Japanese clothing, red knots, gold details, dark-purple stockings and sandals. Preserve asymmetric flower, braid, shoulder/outfit relationships under natural occlusion in turns. Empty hands; NO weapons/props. Full head ornament, braid end, sleeves and feet inside every frame. Quiet restrained motion. Idle hands down with gentle visible breath/blink. No effects, symbols, shadows or baked checkerboard. Generate left run separately, never mirror.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Dragging-left loop: show directional movement to the left through body and limb poses only.

State requirements:
- Show directional drag movement to the left through body, limb, and prop movement only.
- The row must unmistakably face and travel left.
- The movement cadence must alternate visibly across the 8 frames instead of repeating one nearly static stride.
- Do not draw speed lines, dust clouds, floor shadows, motion trails, or detached motion effects.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #00FF00 colors in the pet.


## running-right.md

Create Codex pet row `running-right` for `Raiden-Shogun`: exactly 8 full-body frames in one horizontal strip on flat pure user-selected #00FF00.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Use the supplied approved Raiden-Shogun image as sole identity authority. Purple bangs and side locks, one thick long purple braid connected behind head and curving down viewer-left in front view, purple flower and gold ornament on viewer-left, light/deep-purple Japanese clothing, red knots, gold details, dark-purple stockings and sandals. Preserve asymmetric flower, braid, shoulder/outfit relationships under natural occlusion in turns. Empty hands; NO weapons/props. Full head ornament, braid end, sleeves and feet inside every frame. Quiet restrained motion. Idle hands down with gentle visible breath/blink. No effects, symbols, shadows or baked checkerboard. Generate left run separately, never mirror.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Dragging-right loop: show directional movement to the right through body and limb poses only.

State requirements:
- Show directional drag movement to the right through body, limb, and prop movement only.
- The row must unmistakably face and travel right.
- The movement cadence must alternate visibly across the 8 frames instead of repeating one nearly static stride.
- Do not draw speed lines, dust clouds, floor shadows, motion trails, or detached motion effects.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #00FF00 colors in the pet.


## running.md

Create Codex pet row `running` for `Raiden-Shogun`: exactly 6 full-body frames in one horizontal strip on flat pure user-selected #00FF00.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Use the supplied approved Raiden-Shogun image as sole identity authority. Purple bangs and side locks, one thick long purple braid connected behind head and curving down viewer-left in front view, purple flower and gold ornament on viewer-left, light/deep-purple Japanese clothing, red knots, gold details, dark-purple stockings and sandals. Preserve asymmetric flower, braid, shoulder/outfit relationships under natural occlusion in turns. Empty hands; NO weapons/props. Full head ornament, braid end, sleeves and feet inside every frame. Quiet restrained motion. Idle hands down with gentle visible breath/blink. No effects, symbols, shadows or baked checkerboard. Generate left run separately, never mirror.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Working loop: focused active-task processing, thinking, typing, scanning, or effortful concentration; not literal foot-running, jogging, sprinting, treadmill motion, raised knees, long steps, pumping arms, or directional travel.

State requirements:
- Show the pet actively working or processing, as if running a task: focused posture, busy hands or paws, purposeful bobbing, thinking motion, tool or prop motion only if already part of the pet identity, or other non-locomotion activity.
- Do not show literal foot-running, jogging, sprinting, treadmill motion, raised knees, long steps, pumping arms, directional travel, speed lines, dust clouds, floor shadows, motion trails, or detached motion effects.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #00FF00 colors in the pet.


## waiting.md

Create Codex pet row `waiting` for `Raiden-Shogun`: exactly 6 full-body frames in one horizontal strip on flat pure user-selected #00FF00.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Use the supplied approved Raiden-Shogun image as sole identity authority. Purple bangs and side locks, one thick long purple braid connected behind head and curving down viewer-left in front view, purple flower and gold ornament on viewer-left, light/deep-purple Japanese clothing, red knots, gold details, dark-purple stockings and sandals. Preserve asymmetric flower, braid, shoulder/outfit relationships under natural occlusion in turns. Empty hands; NO weapons/props. Full head ornament, braid end, sleeves and feet inside every frame. Quiet restrained motion. Idle hands down with gentle visible breath/blink. No effects, symbols, shadows or baked checkerboard. Generate left run separately, never mirror.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Needs-input loop: expectant asking pose for approval, help, or user input.

State requirements:
- Show that Codex needs approval, help, or user input through an expectant asking pose.
- Keep the motion patient and readable, without turning it into ordinary idle or review.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #00FF00 colors in the pet.


## waving.md

Create Codex pet row `waving` for `Raiden-Shogun`: exactly 4 full-body frames in one horizontal strip on flat pure user-selected #00FF00.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Use the supplied approved Raiden-Shogun image as sole identity authority. Purple bangs and side locks, one thick long purple braid connected behind head and curving down viewer-left in front view, purple flower and gold ornament on viewer-left, light/deep-purple Japanese clothing, red knots, gold details, dark-purple stockings and sandals. Preserve asymmetric flower, braid, shoulder/outfit relationships under natural occlusion in turns. Empty hands; NO weapons/props. Full head ornament, braid end, sleeves and feet inside every frame. Quiet restrained motion. Idle hands down with gentle visible breath/blink. No effects, symbols, shadows or baked checkerboard. Generate left run separately, never mirror.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Greeting loop: paw or limb down, raised, tilted, and returning in a friendly attention gesture.

State requirements:
- Show the greeting through paw, hand, wing, or limb pose only.
- Do not draw wave marks, motion arcs, lines, sparkles, symbols, or floating effects around the gesture.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #00FF00 colors in the pet.


## failed.md

USER ACTION: Slight head bow and mildly confused/downcast eyes, then soft upward glance. Quiet restrained disappointment, no tears/symbols/smoke.

LAYOUT: Small complete figures surrounded by broad pure green gutters, fully separated braid/hair/sleeve silhouettes. Use a wide 3:1 canvas with substantial blank green above and below; keep each whole figure under half the canvas height. Do not fill canvas height. Identical body size and aligned soles except intentional running bob/jump. No new accessories, effects, weapons or props.

Create one horizontal animation strip for Codex pet `Raiden-Shogun`, state `failed`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 8 full-body frames in one left-to-right row on flat pure user-selected #00FF00. Treat the row as 8 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Use the supplied approved Raiden-Shogun image as sole identity authority. Purple bangs and side locks, one thick long purple braid connected behind head and curving down viewer-left in front view, purple flower and gold ornament on viewer-left, light/deep-purple Japanese clothing, red knots, gold details, dark-purple stockings and sandals. Preserve asymmetric flower, braid, shoulder/outfit relationships under natural occlusion in turns. Empty hands; NO weapons/props. Full head ornament, braid end, sleeves and feet inside every frame. Quiet restrained motion. Idle hands down with gentle visible breath/blink. No effects, symbols, shadows or baked checkerboard. Generate left run separately, never mirror.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Exact approved reference anime illustration. Clean fine linework, soft cel shading, subtle gradients and hair highlights. Preserve rounded face, purple anime eyes, blush, gentle small smile, exact head/body proportions. No plush, realistic3D, plastic or redesign..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Blocked/failed loop: slumped or deflated reaction with sad or closed eyes.

State requirements:
- Show failure through slumped pose, drooping ears/limbs, closed or sad eyes, and lower body position.
- Tears, small smoke puffs, or tiny stars are allowed only if attached to or overlapping the pet silhouette and kept inside the same frame slot.
- Do not draw red X marks, floating symbols, detached stars, separated smoke clouds, falling tear drops, dust, or other loose effects.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.


## idle.md

USER ACTION: Hands naturally lowered. Gentle breath and sleeve/braid micro-sway across six distinct frames, one soft blink. Quiet restrained small smile, no waving.

LAYOUT: Small complete figures surrounded by broad pure green gutters, fully separated braid/hair/sleeve silhouettes. Use a wide 3:1 canvas with substantial blank green above and below; keep each whole figure under half the canvas height. Do not fill canvas height. Identical body size and aligned soles except intentional running bob/jump. No new accessories, effects, weapons or props.

Create one horizontal animation strip for Codex pet `Raiden-Shogun`, state `idle`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 6 full-body frames in one left-to-right row on flat pure user-selected #00FF00. Treat the row as 6 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Use the supplied approved Raiden-Shogun image as sole identity authority. Purple bangs and side locks, one thick long purple braid connected behind head and curving down viewer-left in front view, purple flower and gold ornament on viewer-left, light/deep-purple Japanese clothing, red knots, gold details, dark-purple stockings and sandals. Preserve asymmetric flower, braid, shoulder/outfit relationships under natural occlusion in turns. Empty hands; NO weapons/props. Full head ornament, braid end, sleeves and feet inside every frame. Quiet restrained motion. Idle hands down with gentle visible breath/blink. No effects, symbols, shadows or baked checkerboard. Generate left run separately, never mirror.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Exact approved reference anime illustration. Clean fine linework, soft cel shading, subtle gradients and hair highlights. Preserve rounded face, purple anime eyes, blush, gentle small smile, exact head/body proportions. No plush, realistic3D, plastic or redesign..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Calm low-distraction resting loop: subtle breathing, tiny blink, slight head/body bob, and only quiet persona-preserving motion.

State requirements:
- CRITICAL: idle is the low-distraction baseline state and the first frame is also used as the reduced-motion static pet.
- Use only subtle idle motion: gentle breathing, a tiny blink, a slight head or body bob, a very small material sway, or another quiet motion that fits the pet persona.
- Keep the pet essentially in the same pose, facing direction, silhouette, markings, palette, and prop state across all 6 frames.
- Idle variation must stay calm but still read as animation; do not repeat effectively identical copies across the loop.
- Do not show waving, walking, running, jumping, talking, working, reviewing, emotional reactions, large gestures, item interactions, or new props.
- Feet, base, body, or object anchor should remain planted or nearly planted.
- The first and last frames should be very close visually so the loop feels calm and does not pop.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.


## jumping.md

USER ACTION: Small anticipation bend, short happy rise, peak, descending then soft bent-knee landing. Full ornament/braid/sleeves/feet inside each slot. No floor or shadow.

LAYOUT: Small complete figures surrounded by broad pure green gutters, fully separated braid/hair/sleeve silhouettes. Use a wide 3:1 canvas with substantial blank green above and below; keep each whole figure under half the canvas height. Do not fill canvas height. Identical body size and aligned soles except intentional running bob/jump. No new accessories, effects, weapons or props.

Create one horizontal animation strip for Codex pet `Raiden-Shogun`, state `jumping`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 5 full-body frames in one left-to-right row on flat pure user-selected #00FF00. Treat the row as 5 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Use the supplied approved Raiden-Shogun image as sole identity authority. Purple bangs and side locks, one thick long purple braid connected behind head and curving down viewer-left in front view, purple flower and gold ornament on viewer-left, light/deep-purple Japanese clothing, red knots, gold details, dark-purple stockings and sandals. Preserve asymmetric flower, braid, shoulder/outfit relationships under natural occlusion in turns. Empty hands; NO weapons/props. Full head ornament, braid end, sleeves and feet inside every frame. Quiet restrained motion. Idle hands down with gentle visible breath/blink. No effects, symbols, shadows or baked checkerboard. Generate left run separately, never mirror.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Exact approved reference anime illustration. Clean fine linework, soft cel shading, subtle gradients and hair highlights. Preserve rounded face, purple anime eyes, blush, gentle small smile, exact head/body proportions. No plush, realistic3D, plastic or redesign..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Hover jump loop: anticipation, lift, airborne peak, descent, and settle through body height.

State requirements:
- Show the jump through pose and vertical body position only: anticipation, lift, airborne peak, descent, settle.
- Do not draw ground shadows, contact shadows, drop shadows, oval shadows, landing marks, dust, smears, bounce pads, or motion marks under the pet.
- Keep the background outside the pet perfectly flat chroma key with no darker key-colored patches.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.


## look-row-10.md

EDIT FIRST IMAGE: FIX BRAID PLACEMENT ONLY, KEEP ITS CORRECT LEFT-FACING HEADS AND EYES.

First image contains correct8attentionposes DOWN→LEFT→UP-LEFT. Their face directions, eye positions, eyelids, head tilt and expressions MUST remain exactly as firstimage. The problem is the long braid suddenly switches to the viewer-RIGHT in poses3–8. Correct the entire coherent8pose row so the long braid hangs on viewer-LEFT in EVERY pose, as in the SECOND image and canonical body. The torso is planted, so a small headturn does not move a hangingbraid fromone side ofthebody toanother. Keep its lower redbow/tassel and purplebraidtip at essentially the SAME viewer-left position inall8poses. Root stays connected behindhead/rightshoulder (viewer-left onfrontbody), upperbraid maybend subtly behindhead toaccommodate LEFTheadyaw. Do not reverse/mirrorbody orclothestoachievethis. No braid onviewer-right, no duplicatebraid, no disappearingbraid, no hardside-switch, no braidrootjump. At finalUP-left pose337.5, braidshouldjoinsecondimage'sfirstUPpose inexactbodyplacement.

Allfive references:
1 edit target with CORRECT LEFT faces and wrongbraids: preserveallfaces/gazes.
2 completedrow9: exactcanvas, body/headscale, plantedfeet, goldflower/outfit and correctviewer-leftbraidbodyrelationship.
3 canonical: unchangedidentity/faceoutfitproportions.
4 standardcontact: stablebody/asymmetry.
5 cardinals: head/eye directions only, DON'TcopycardinalLEFT'sright-sidebraid.

Keep exact2170x725canvas, fullfigureheight about470pixels includinggoldtip/feet; topsaroundy133orbelow, alignedsolesy603. Same8figurepositions andgreenpadding. Redraw as ONE coherentwhole8posefamily, not individualcellpatches. Preserve purpleanimeeyes, originalface/headsize, left-facingnoses fromFIRSTimage, alloutfitgold/red/purpledetails, floweroncorrectanatomicalside and oppositearmor, longwhitesleeves/stockings/sandals. HandsrelaxedDOWN/feet/waistanchored.

Attentionorder is180DOWN,202.5DOWNslightlyLEFT,225DOWN-LEFT,247.5LEFTslightlyDOWN,270LEFT,292.5LEFTslightlyUP,315UP-LEFT,337.5UPslightlyLEFT. The fifthface remains clearlyLEFT ofskullcenter, neverRIGHT; lastfaceup/leftnotneutral. No newprops/weapons/effects/text/shadows/scenery/checkerboard. Puregreen#00FF00gutters, allgoldtips/braidends/sleeves/feetcomplete.

## look-row-9.md

Create one coherent horizontal strip of EIGHT whole Raiden-Shogun attention poses. Use all attached images: user-approved reference and canonical for exact character identity, standard contact for unchanged proportions/style/body, layout only invisible spacing, approved four-cardinal strip for direction meaning (UP, RIGHT, DOWN, LEFT). Read qa/look-mechanics.md.

Canvas approximately2172x724. Eight small similarly sized complete figures, around280-300pixels tall INCLUDING the gold head ornament and feet. Keep broad flat puregreen #00FF00 blankspace above/below, and clear gutters between all braid/hand/sleeve silhouettes and beyond outer poses. Do not fill canvas height. Complete attachedgoldtip, braid end, sleeves and feet. Same body size, same boot baseline.

Left-to-right attention directions (NOT body/camera angles):
1 UP000: frontal, chin clearly raised and purple eyes high; not neutral.
2 UP with slight SCREEN-RIGHT022.5: high eyes, small right head/nose bias.
3 UP-RIGHT045: right yaw and lifted chin/gaze.
4 RIGHT with slightUP067.5: clearer right face plane, gaze a little abovelevel.
5 RIGHT090: canonical RIGHT anchor; nose/face and pupils clearly toward image-right, level gaze.
6 RIGHT with slightDOWN112.5: right face/nose and slightly lowered eyes/chin.
7 DOWN-RIGHT135: smaller right yaw, chin tucked and lowgaze.
8 DOWN with slightRIGHT157.5: nearfrontal, loweyes/tuckedchin but still small visible rightcue.

Generate all8 as a single coherent family. Keep hands relaxed DOWN, torso/skirt/feet planted. Only eyes, eyelids, brows and head/neck lead; minimal upperbody and hairfollowthrough. Preserve exact same anime eye construction, face, purple layered bangs/side hair, asymmetrical flower/goldornament, thick connected braid, purple/white/red/goldoutfit and tiny calm smile. No identity redesign, no surprised O mouth. Do not mirror or transplant outfit. Braid remains rooted behindhead with quiet naturalfollow; no side flipping. No wholebodyrotation, no backviews, no facewarping, no effects, props, weapons, text, guides, shadows, halos, lightning, scenery or checkerboard.

## review.md

USER ACTION: Lean head slightly forward and inspect with tiny gaze shifts and focused blink; hands relaxed near waist. Distinct from thinking. No props.

LAYOUT: Small complete figures surrounded by broad pure green gutters, fully separated braid/hair/sleeve silhouettes. Use a wide 3:1 canvas with substantial blank green above and below; keep each whole figure under half the canvas height. Do not fill canvas height. Identical body size and aligned soles except intentional running bob/jump. No new accessories, effects, weapons or props.

Create one horizontal animation strip for Codex pet `Raiden-Shogun`, state `review`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 6 full-body frames in one left-to-right row on flat pure user-selected #00FF00. Treat the row as 6 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Use the supplied approved Raiden-Shogun image as sole identity authority. Purple bangs and side locks, one thick long purple braid connected behind head and curving down viewer-left in front view, purple flower and gold ornament on viewer-left, light/deep-purple Japanese clothing, red knots, gold details, dark-purple stockings and sandals. Preserve asymmetric flower, braid, shoulder/outfit relationships under natural occlusion in turns. Empty hands; NO weapons/props. Full head ornament, braid end, sleeves and feet inside every frame. Quiet restrained motion. Idle hands down with gentle visible breath/blink. No effects, symbols, shadows or baked checkerboard. Generate left run separately, never mirror.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Exact approved reference anime illustration. Clean fine linework, soft cel shading, subtle gradients and hair highlights. Preserve rounded face, purple anime eyes, blush, gentle small smile, exact head/body proportions. No plush, realistic3D, plastic or redesign..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Ready-review loop: focused inspection of completed output with lean, blink, narrowed eyes, head tilt, or paw pose.

State requirements:
- Show review through lean, blink, narrowed eyes, head tilt, or paw/hand position.
- Do not add magnifying glasses, papers, code, UI, punctuation, symbols, or other new props unless they already exist in the base pet identity.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.


## running-left.md

USER ACTION: Clear screen-left facing short-step run, alternating legs and light body bob, braid and sleeves lag. Independently draw natural opposite view with correct anatomical ornament/armor and braid attachments, never mirror.

LAYOUT: Small complete figures surrounded by broad pure green gutters, fully separated braid/hair/sleeve silhouettes. Use a wide 3:1 canvas with substantial blank green above and below; keep each whole figure under half the canvas height. Do not fill canvas height. Identical body size and aligned soles except intentional running bob/jump. No new accessories, effects, weapons or props.

Create one horizontal animation strip for Codex pet `Raiden-Shogun`, state `running-left`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 8 full-body frames in one left-to-right row on flat pure user-selected #00FF00. Treat the row as 8 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Use the supplied approved Raiden-Shogun image as sole identity authority. Purple bangs and side locks, one thick long purple braid connected behind head and curving down viewer-left in front view, purple flower and gold ornament on viewer-left, light/deep-purple Japanese clothing, red knots, gold details, dark-purple stockings and sandals. Preserve asymmetric flower, braid, shoulder/outfit relationships under natural occlusion in turns. Empty hands; NO weapons/props. Full head ornament, braid end, sleeves and feet inside every frame. Quiet restrained motion. Idle hands down with gentle visible breath/blink. No effects, symbols, shadows or baked checkerboard. Generate left run separately, never mirror.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Exact approved reference anime illustration. Clean fine linework, soft cel shading, subtle gradients and hair highlights. Preserve rounded face, purple anime eyes, blush, gentle small smile, exact head/body proportions. No plush, realistic3D, plastic or redesign..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Dragging-left loop: show directional movement to the left through body and limb poses only.

State requirements:
- Show directional drag movement to the left through body, limb, and prop movement only.
- The row must unmistakably face and travel left.
- The movement cadence must alternate visibly across the 8 frames instead of repeating one nearly static stride.
- Do not draw speed lines, dust clouds, floor shadows, motion trails, or detached motion effects.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.


## running-right.md

USER ACTION: Clear screen-right facing short-step run, alternating legs and light body bob, braid and sleeves lag. Keep anatomical ornament/armor placements, never mirror; no new props.

LAYOUT: Small complete figures surrounded by broad pure green gutters, fully separated braid/hair/sleeve silhouettes. Use a wide 3:1 canvas with substantial blank green above and below; keep each whole figure under half the canvas height. Do not fill canvas height. Identical body size and aligned soles except intentional running bob/jump. No new accessories, effects, weapons or props.

Create one horizontal animation strip for Codex pet `Raiden-Shogun`, state `running-right`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 8 full-body frames in one left-to-right row on flat pure user-selected #00FF00. Treat the row as 8 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Use the supplied approved Raiden-Shogun image as sole identity authority. Purple bangs and side locks, one thick long purple braid connected behind head and curving down viewer-left in front view, purple flower and gold ornament on viewer-left, light/deep-purple Japanese clothing, red knots, gold details, dark-purple stockings and sandals. Preserve asymmetric flower, braid, shoulder/outfit relationships under natural occlusion in turns. Empty hands; NO weapons/props. Full head ornament, braid end, sleeves and feet inside every frame. Quiet restrained motion. Idle hands down with gentle visible breath/blink. No effects, symbols, shadows or baked checkerboard. Generate left run separately, never mirror.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Exact approved reference anime illustration. Clean fine linework, soft cel shading, subtle gradients and hair highlights. Preserve rounded face, purple anime eyes, blush, gentle small smile, exact head/body proportions. No plush, realistic3D, plastic or redesign..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Dragging-right loop: show directional movement to the right through body and limb poses only.

State requirements:
- Show directional drag movement to the right through body, limb, and prop movement only.
- The row must unmistakably face and travel right.
- The movement cadence must alternate visibly across the 8 frames instead of repeating one nearly static stride.
- Do not draw speed lines, dust clouds, floor shadows, motion trails, or detached motion effects.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.


## running.md

USER ACTION: Task processing: thoughtful serious focus, tiny nod, one hand near chin. Feet remain planted, absolutely no foot-running.

LAYOUT: Small complete figures surrounded by broad pure green gutters, fully separated braid/hair/sleeve silhouettes. Use a wide 3:1 canvas with substantial blank green above and below; keep each whole figure under half the canvas height. Do not fill canvas height. Identical body size and aligned soles except intentional running bob/jump. No new accessories, effects, weapons or props.

Create one horizontal animation strip for Codex pet `Raiden-Shogun`, state `running`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 6 full-body frames in one left-to-right row on flat pure user-selected #00FF00. Treat the row as 6 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Use the supplied approved Raiden-Shogun image as sole identity authority. Purple bangs and side locks, one thick long purple braid connected behind head and curving down viewer-left in front view, purple flower and gold ornament on viewer-left, light/deep-purple Japanese clothing, red knots, gold details, dark-purple stockings and sandals. Preserve asymmetric flower, braid, shoulder/outfit relationships under natural occlusion in turns. Empty hands; NO weapons/props. Full head ornament, braid end, sleeves and feet inside every frame. Quiet restrained motion. Idle hands down with gentle visible breath/blink. No effects, symbols, shadows or baked checkerboard. Generate left run separately, never mirror.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Exact approved reference anime illustration. Clean fine linework, soft cel shading, subtle gradients and hair highlights. Preserve rounded face, purple anime eyes, blush, gentle small smile, exact head/body proportions. No plush, realistic3D, plastic or redesign..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Working loop: focused active-task processing, thinking, typing, scanning, or effortful concentration; not literal foot-running, jogging, sprinting, treadmill motion, raised knees, long steps, pumping arms, or directional travel.

State requirements:
- Show the pet actively working or processing, as if running a task: focused posture, busy hands or paws, purposeful bobbing, thinking motion, tool or prop motion only if already part of the pet identity, or other non-locomotion activity.
- Do not show literal foot-running, jogging, sprinting, treadmill motion, raised knees, long steps, pumping arms, directional travel, speed lines, dust clouds, floor shadows, motion trails, or detached motion effects.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.


## waiting.md

USER ACTION: Small head tilt, hands together near front, quiet expectant gaze, gentle blink; visibly differs from idle.

LAYOUT: Small complete figures surrounded by broad pure green gutters, fully separated braid/hair/sleeve silhouettes. Use a wide 3:1 canvas with substantial blank green above and below; keep each whole figure under half the canvas height. Do not fill canvas height. Identical body size and aligned soles except intentional running bob/jump. No new accessories, effects, weapons or props.

Create one horizontal animation strip for Codex pet `Raiden-Shogun`, state `waiting`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 6 full-body frames in one left-to-right row on flat pure user-selected #00FF00. Treat the row as 6 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Use the supplied approved Raiden-Shogun image as sole identity authority. Purple bangs and side locks, one thick long purple braid connected behind head and curving down viewer-left in front view, purple flower and gold ornament on viewer-left, light/deep-purple Japanese clothing, red knots, gold details, dark-purple stockings and sandals. Preserve asymmetric flower, braid, shoulder/outfit relationships under natural occlusion in turns. Empty hands; NO weapons/props. Full head ornament, braid end, sleeves and feet inside every frame. Quiet restrained motion. Idle hands down with gentle visible breath/blink. No effects, symbols, shadows or baked checkerboard. Generate left run separately, never mirror.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Exact approved reference anime illustration. Clean fine linework, soft cel shading, subtle gradients and hair highlights. Preserve rounded face, purple anime eyes, blush, gentle small smile, exact head/body proportions. No plush, realistic3D, plastic or redesign..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Needs-input loop: expectant asking pose for approval, help, or user input.

State requirements:
- Show that Codex needs approval, help, or user input through an expectant asking pose.
- Keep the motion patient and readable, without turning it into ordinary idle or review.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.


## waving.md

USER ACTION: One hand rises a little, gives a small shy gentle wave, then settles. Slight softened smile; no waving marks.

LAYOUT: Small complete figures surrounded by broad pure green gutters, fully separated braid/hair/sleeve silhouettes. Use a wide 3:1 canvas with substantial blank green above and below; keep each whole figure under half the canvas height. Do not fill canvas height. Identical body size and aligned soles except intentional running bob/jump. No new accessories, effects, weapons or props.

Create one horizontal animation strip for Codex pet `Raiden-Shogun`, state `waving`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 4 full-body frames in one left-to-right row on flat pure user-selected #00FF00. Treat the row as 4 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Use the supplied approved Raiden-Shogun image as sole identity authority. Purple bangs and side locks, one thick long purple braid connected behind head and curving down viewer-left in front view, purple flower and gold ornament on viewer-left, light/deep-purple Japanese clothing, red knots, gold details, dark-purple stockings and sandals. Preserve asymmetric flower, braid, shoulder/outfit relationships under natural occlusion in turns. Empty hands; NO weapons/props. Full head ornament, braid end, sleeves and feet inside every frame. Quiet restrained motion. Idle hands down with gentle visible breath/blink. No effects, symbols, shadows or baked checkerboard. Generate left run separately, never mirror.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Exact approved reference anime illustration. Clean fine linework, soft cel shading, subtle gradients and hair highlights. Preserve rounded face, purple anime eyes, blush, gentle small smile, exact head/body proportions. No plush, realistic3D, plastic or redesign..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Greeting loop: paw or limb down, raised, tilted, and returning in a friendly attention gesture.

State requirements:
- Show the greeting through paw, hand, wing, or limb pose only.
- Do not draw wave marks, motion arcs, lines, sparkles, symbols, or floating effects around the gesture.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.

