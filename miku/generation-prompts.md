# Miku generation prompts

Generated with the built-in image generation tool, grounded in the approved Miku reference.

## base-pet.md

Create one clean full-body reference sprite for Codex pet Miku.

Pet identity: The supplied approved second-version Miku reference is the ONLY character design authority. Preserve exactly its face shape, layered curved teal twin-tails and bangs, soft tapered hair tips, half-open teal anime eyes, tiny gentle smile, faint blush, black magenta hair ornaments, light-gray sleeveless top, teal tie, black pleated skirt with teal trim, black detached long sleeves and boots. Approximately 2.5 heads tall with large round head, small body and short natural limbs, SAME proportions as reference. Quiet gentle Fufu-like slightly airheaded personality. Normalization may change only framing, padding, background and relaxed neutral standing pose, never redesign. Reference waving hand belongs only in waving action. All movements small and restrained. No extra props or effects..
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Exactly match the approved reference: refined Japanese hand-drawn anime chibi, delicate linework, soft cel shading with modest gradients and hair highlights. Skin hair clothing are illustrated; no plush fibers, felt, embroidered eyes, stitches, doll photography or realistic3D. Remove reference checkerboard completely; final true alpha..


Place a single centered pose on a perfectly flat pure user-selected #00FF00 chroma-key background. Keep the full pet visible, compact, readable at 192x208, and easy to animate. Preserve approved reference identity cues. No scenery, text, borders, checkerboard transparency, shadows, glows, detached effects, or extra props. Keep #00FF00 and close colors out of the pet, props, highlights, and effects.
This is normalization of an approved design, not a redesign. Keep the exact reference face, half-open eye construction and proportions. Both hands relaxed naturally down; head nearly upright, both boots planted. Frame entire twin-tail silhouette with generous padding. Remove baked gray checkerboard. No waving pose in this neutral base.


## 000.md

Repair one cardinal anchor for Codex pet `miku`: `000` means looking up.

Use the canonical base, completed standard contact sheet, approved cardinal-strip cells, and `qa/look-mechanics.md` for identity, scale, registration, and pet-specific gaze mechanics. Keep the face broadly frontal and point the eyes and natural head mechanism toward the TOP edge. Screen coordinates are viewer-relative.

Output one centered complete full-body pose on a flat pure user-selected #00FF00 background with generous padding. Keep the feet/base and lower body registered to the approved anchors. The requested cardinal must be unmistakable at final 192x208 display size.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement eyes, labels, arrows, guide marks, shadows, scenery, detached effects, or chroma-key colors inside the pet.


## 090.md

Repair one cardinal anchor for Codex pet `miku`: `090` means looking right.

Use the canonical base, completed standard contact sheet, approved cardinal-strip cells, and `qa/look-mechanics.md` for identity, scale, registration, and pet-specific gaze mechanics. Put the nose tip, pupils, face surface, or natural aiming feature on the screen-right side of the head center. Screen coordinates are viewer-relative.

Output one centered complete full-body pose on a flat pure user-selected #00FF00 background with generous padding. Keep the feet/base and lower body registered to the approved anchors. The requested cardinal must be unmistakable at final 192x208 display size.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement eyes, labels, arrows, guide marks, shadows, scenery, detached effects, or chroma-key colors inside the pet.


## 180.md

Repair one cardinal anchor for Codex pet `miku`: `180` means looking down.

Use the canonical base, completed standard contact sheet, approved cardinal-strip cells, and `qa/look-mechanics.md` for identity, scale, registration, and pet-specific gaze mechanics. Keep the face broadly frontal and point the eyes and natural head mechanism toward the BOTTOM edge. Screen coordinates are viewer-relative.

Output one centered complete full-body pose on a flat pure user-selected #00FF00 background with generous padding. Keep the feet/base and lower body registered to the approved anchors. The requested cardinal must be unmistakable at final 192x208 display size.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement eyes, labels, arrows, guide marks, shadows, scenery, detached effects, or chroma-key colors inside the pet.


## 270.md

Repair one cardinal anchor for Codex pet `miku`: `270` means looking left.

Use the canonical base, completed standard contact sheet, approved cardinal-strip cells, and `qa/look-mechanics.md` for identity, scale, registration, and pet-specific gaze mechanics. Put the nose tip, pupils, face surface, or natural aiming feature on the screen-left side of the head center. Screen coordinates are viewer-relative.

Output one centered complete full-body pose on a flat pure user-selected #00FF00 background with generous padding. Keep the feet/base and lower body registered to the approved anchors. The requested cardinal must be unmistakable at final 192x208 display size.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement eyes, labels, arrows, guide marks, shadows, scenery, detached effects, or chroma-key colors inside the pet.


## look-cardinals.md

Create one horizontal four-cardinal anchor strip for Codex pet `miku`.

Use the attached canonical base, completed standard contact sheet, and layout guide for exact identity, style, scale, baseline, face construction, materials, palette, markings, props, and spacing. Read `qa/look-mechanics.md` and use the pet's natural gaze mechanism.

Output exactly four centered complete full-body poses in this exact left-to-right order: `000 up`, `090 screen-right`, `180 down`, `270 screen-left`. Screen-left and screen-right always mean the viewer's image edges, never the character's own left or right.

For `000`, keep the face broadly frontal and point the eyes and natural head mechanism toward the TOP edge. For `090`, put the nose tip, pupils, face surface, or natural aiming feature on the screen-right side of the head center. For `180`, keep the face broadly frontal and point toward the BOTTOM edge. For `270`, apply the inverse screen-left landmark rule. Every cardinal must be unmistakable without labels.

Place one pose in each invisible equal-width slot on a flat pure user-selected #00FF00 background with generous padding. Keep scale, feet/base, lower body, and registration consistent across all four slots.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement eyes, labels, degree text, arrows, boxes, guide marks, shadows, scenery, detached effects, or chroma-key colors inside the pet.

Miku lock: retain approved half-open anime eyes and tiny gentle smile, no wide surprised eyes or O mouth. Hands relaxed DOWN, boots and torso anchored. These are eye-attention directions, not body rotation. Both pupils and chin clearly distinguish up/down. FOURTH pose nose and eye must point toward LEFT IMAGE EDGE. Preserve full original layered twin-tail shapes; generous green-only gaps between silhouettes. Keep entire poses small enough for empty gutters, no clipped hair.


## failed.md

Create Codex pet row `failed` for `miku`: exactly 8 full-body frames in one horizontal strip on flat pure user-selected #00FF00.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: The supplied approved second-version Miku reference is the ONLY character design authority. Preserve exactly its face shape, layered curved teal twin-tails and bangs, soft tapered hair tips, half-open teal anime eyes, tiny gentle smile, faint blush, black magenta hair ornaments, light-gray sleeveless top, teal tie, black pleated skirt with teal trim, black detached long sleeves and boots. Approximately 2.5 heads tall with large round head, small body and short natural limbs, SAME proportions as reference. Quiet gentle Fufu-like slightly airheaded personality. Normalization may change only framing, padding, background and relaxed neutral standing pose, never redesign. Reference waving hand belongs only in waving action. All movements small and restrained. No extra props or effects.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Blocked/failed loop: slumped or deflated reaction with sad or closed eyes.

State requirements:
- Show failure through slumped pose, drooping ears/limbs, closed or sad eyes, and lower body position.
- Tears, small smoke puffs, or tiny stars are allowed only if attached to or overlapping the pet silhouette and kept inside the same frame slot.
- Do not draw red X marks, floating symbols, detached stars, separated smoke clouds, falling tear drops, dust, or other loose effects.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #00FF00 colors in the pet.


## idle.md

Create Codex pet row `idle` for `miku`: exactly 6 full-body frames in one horizontal strip on flat pure user-selected #00FF00.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: The supplied approved second-version Miku reference is the ONLY character design authority. Preserve exactly its face shape, layered curved teal twin-tails and bangs, soft tapered hair tips, half-open teal anime eyes, tiny gentle smile, faint blush, black magenta hair ornaments, light-gray sleeveless top, teal tie, black pleated skirt with teal trim, black detached long sleeves and boots. Approximately 2.5 heads tall with large round head, small body and short natural limbs, SAME proportions as reference. Quiet gentle Fufu-like slightly airheaded personality. Normalization may change only framing, padding, background and relaxed neutral standing pose, never redesign. Reference waving hand belongs only in waving action. All movements small and restrained. No extra props or effects.. Preserve silhouette, face, palette, material, proportions, markings, and props.

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

Create Codex pet row `jumping` for `miku`: exactly 5 full-body frames in one horizontal strip on flat pure user-selected #00FF00.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: The supplied approved second-version Miku reference is the ONLY character design authority. Preserve exactly its face shape, layered curved teal twin-tails and bangs, soft tapered hair tips, half-open teal anime eyes, tiny gentle smile, faint blush, black magenta hair ornaments, light-gray sleeveless top, teal tie, black pleated skirt with teal trim, black detached long sleeves and boots. Approximately 2.5 heads tall with large round head, small body and short natural limbs, SAME proportions as reference. Quiet gentle Fufu-like slightly airheaded personality. Normalization may change only framing, padding, background and relaxed neutral standing pose, never redesign. Reference waving hand belongs only in waving action. All movements small and restrained. No extra props or effects.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Hover jump loop: anticipation, lift, airborne peak, descent, and settle through body height.

State requirements:
- Show the jump through pose and vertical body position only: anticipation, lift, airborne peak, descent, settle.
- Do not draw ground shadows, contact shadows, drop shadows, oval shadows, landing marks, dust, smears, bounce pads, or motion marks under the pet.
- Keep the background outside the pet perfectly flat chroma key with no darker key-colored patches.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #00FF00 colors in the pet.


## look-row-10.md

Create Codex v2 pet look row 10 for `miku` as exactly 8 full-body frames in this order: 180, 202.5, 225, 247.5, 270, 292.5, 315, 337.5.

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

Create Codex v2 pet look row 9 for `miku` as exactly 8 full-body frames in this order: 000, 022.5, 045, 067.5, 090, 112.5, 135, 157.5.

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

Create Codex pet row `review` for `miku`: exactly 6 full-body frames in one horizontal strip on flat pure user-selected #00FF00.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: The supplied approved second-version Miku reference is the ONLY character design authority. Preserve exactly its face shape, layered curved teal twin-tails and bangs, soft tapered hair tips, half-open teal anime eyes, tiny gentle smile, faint blush, black magenta hair ornaments, light-gray sleeveless top, teal tie, black pleated skirt with teal trim, black detached long sleeves and boots. Approximately 2.5 heads tall with large round head, small body and short natural limbs, SAME proportions as reference. Quiet gentle Fufu-like slightly airheaded personality. Normalization may change only framing, padding, background and relaxed neutral standing pose, never redesign. Reference waving hand belongs only in waving action. All movements small and restrained. No extra props or effects.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Ready-review loop: focused inspection of completed output with lean, blink, narrowed eyes, head tilt, or paw pose.

State requirements:
- Show review through lean, blink, narrowed eyes, head tilt, or paw/hand position.
- Do not add magnifying glasses, papers, code, UI, punctuation, symbols, or other new props unless they already exist in the base pet identity.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #00FF00 colors in the pet.


## running-left.md

Create Codex pet row `running-left` for `miku`: exactly 8 full-body frames in one horizontal strip on flat pure user-selected #00FF00.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: The supplied approved second-version Miku reference is the ONLY character design authority. Preserve exactly its face shape, layered curved teal twin-tails and bangs, soft tapered hair tips, half-open teal anime eyes, tiny gentle smile, faint blush, black magenta hair ornaments, light-gray sleeveless top, teal tie, black pleated skirt with teal trim, black detached long sleeves and boots. Approximately 2.5 heads tall with large round head, small body and short natural limbs, SAME proportions as reference. Quiet gentle Fufu-like slightly airheaded personality. Normalization may change only framing, padding, background and relaxed neutral standing pose, never redesign. Reference waving hand belongs only in waving action. All movements small and restrained. No extra props or effects.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Dragging-left loop: show directional movement to the left through body and limb poses only.

State requirements:
- Show directional drag movement to the left through body, limb, and prop movement only.
- The row must unmistakably face and travel left.
- The movement cadence must alternate visibly across the 8 frames instead of repeating one nearly static stride.
- Do not draw speed lines, dust clouds, floor shadows, motion trails, or detached motion effects.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #00FF00 colors in the pet.


## running-right.md

Create Codex pet row `running-right` for `miku`: exactly 8 full-body frames in one horizontal strip on flat pure user-selected #00FF00.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: The supplied approved second-version Miku reference is the ONLY character design authority. Preserve exactly its face shape, layered curved teal twin-tails and bangs, soft tapered hair tips, half-open teal anime eyes, tiny gentle smile, faint blush, black magenta hair ornaments, light-gray sleeveless top, teal tie, black pleated skirt with teal trim, black detached long sleeves and boots. Approximately 2.5 heads tall with large round head, small body and short natural limbs, SAME proportions as reference. Quiet gentle Fufu-like slightly airheaded personality. Normalization may change only framing, padding, background and relaxed neutral standing pose, never redesign. Reference waving hand belongs only in waving action. All movements small and restrained. No extra props or effects.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Dragging-right loop: show directional movement to the right through body and limb poses only.

State requirements:
- Show directional drag movement to the right through body, limb, and prop movement only.
- The row must unmistakably face and travel right.
- The movement cadence must alternate visibly across the 8 frames instead of repeating one nearly static stride.
- Do not draw speed lines, dust clouds, floor shadows, motion trails, or detached motion effects.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #00FF00 colors in the pet.


## running.md

Create Codex pet row `running` for `miku`: exactly 6 full-body frames in one horizontal strip on flat pure user-selected #00FF00.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: The supplied approved second-version Miku reference is the ONLY character design authority. Preserve exactly its face shape, layered curved teal twin-tails and bangs, soft tapered hair tips, half-open teal anime eyes, tiny gentle smile, faint blush, black magenta hair ornaments, light-gray sleeveless top, teal tie, black pleated skirt with teal trim, black detached long sleeves and boots. Approximately 2.5 heads tall with large round head, small body and short natural limbs, SAME proportions as reference. Quiet gentle Fufu-like slightly airheaded personality. Normalization may change only framing, padding, background and relaxed neutral standing pose, never redesign. Reference waving hand belongs only in waving action. All movements small and restrained. No extra props or effects.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Working loop: focused active-task processing, thinking, typing, scanning, or effortful concentration; not literal foot-running, jogging, sprinting, treadmill motion, raised knees, long steps, pumping arms, or directional travel.

State requirements:
- Show the pet actively working or processing, as if running a task: focused posture, busy hands or paws, purposeful bobbing, thinking motion, tool or prop motion only if already part of the pet identity, or other non-locomotion activity.
- Do not show literal foot-running, jogging, sprinting, treadmill motion, raised knees, long steps, pumping arms, directional travel, speed lines, dust clouds, floor shadows, motion trails, or detached motion effects.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #00FF00 colors in the pet.


## waiting.md

Create Codex pet row `waiting` for `miku`: exactly 6 full-body frames in one horizontal strip on flat pure user-selected #00FF00.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: The supplied approved second-version Miku reference is the ONLY character design authority. Preserve exactly its face shape, layered curved teal twin-tails and bangs, soft tapered hair tips, half-open teal anime eyes, tiny gentle smile, faint blush, black magenta hair ornaments, light-gray sleeveless top, teal tie, black pleated skirt with teal trim, black detached long sleeves and boots. Approximately 2.5 heads tall with large round head, small body and short natural limbs, SAME proportions as reference. Quiet gentle Fufu-like slightly airheaded personality. Normalization may change only framing, padding, background and relaxed neutral standing pose, never redesign. Reference waving hand belongs only in waving action. All movements small and restrained. No extra props or effects.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Needs-input loop: expectant asking pose for approval, help, or user input.

State requirements:
- Show that Codex needs approval, help, or user input through an expectant asking pose.
- Keep the motion patient and readable, without turning it into ordinary idle or review.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #00FF00 colors in the pet.


## waving.md

Create Codex pet row `waving` for `miku`: exactly 4 full-body frames in one horizontal strip on flat pure user-selected #00FF00.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: The supplied approved second-version Miku reference is the ONLY character design authority. Preserve exactly its face shape, layered curved teal twin-tails and bangs, soft tapered hair tips, half-open teal anime eyes, tiny gentle smile, faint blush, black magenta hair ornaments, light-gray sleeveless top, teal tie, black pleated skirt with teal trim, black detached long sleeves and boots. Approximately 2.5 heads tall with large round head, small body and short natural limbs, SAME proportions as reference. Quiet gentle Fufu-like slightly airheaded personality. Normalization may change only framing, padding, background and relaxed neutral standing pose, never redesign. Reference waving hand belongs only in waving action. All movements small and restrained. No extra props or effects.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Greeting loop: paw or limb down, raised, tilted, and returning in a friendly attention gesture.

State requirements:
- Show the greeting through paw, hand, wing, or limb pose only.
- Do not draw wave marks, motion arcs, lines, sparkles, symbols, or floating effects around the gesture.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #00FF00 colors in the pet.


## failed.md

Create one horizontal animation strip for Codex pet `miku`, state `failed`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 8 full-body frames in one left-to-right row on flat pure user-selected #00FF00. Treat the row as 8 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: The supplied approved second-version Miku reference is the ONLY character design authority. Preserve exactly its face shape, layered curved teal twin-tails and bangs, soft tapered hair tips, half-open teal anime eyes, tiny gentle smile, faint blush, black magenta hair ornaments, light-gray sleeveless top, teal tie, black pleated skirt with teal trim, black detached long sleeves and boots. Approximately 2.5 heads tall with large round head, small body and short natural limbs, SAME proportions as reference. Quiet gentle Fufu-like slightly airheaded personality. Preserve the approved design exactly while expressing this row action. All movements small and restrained. No extra props or effects.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Exactly match the approved reference: refined Japanese hand-drawn anime chibi, delicate linework, soft cel shading with modest gradients and hair highlights. Skin hair clothing are illustrated; no plush fibers, felt, embroidered eyes, stitches, doll photography or realistic3D. Remove reference checkerboard completely; final true alpha..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Blocked/failed loop: slumped or deflated reaction with sad or closed eyes.

State requirements:
- Show failure through slumped pose, drooping ears/limbs, closed or sad eyes, and lower body position.
- Tears, small smoke puffs, or tiny stars are allowed only if attached to or overlapping the pet silhouette and kept inside the same frame slot.
- Do not draw red X marks, floating symbols, detached stars, separated smoke clouds, falling tear drops, dust, or other loose effects.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.
Miku action: Soft lowered head with slightly sad brows/eyes and tiny disappointed expression, no tears or dramatic crying.
Source layout: every COMPLETE silhouette including twin-tails fits within 72% of its slot width. Wide continuous pure green gutters between all poses. Do not let hair touch a neighbor; no outer-edge clipping.


## idle.md

Create one horizontal animation strip for Codex pet `miku`, state `idle`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 6 full-body frames in one left-to-right row on flat pure user-selected #00FF00. Treat the row as 6 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: The supplied approved second-version Miku reference is the ONLY character design authority. Preserve exactly its face shape, layered curved teal twin-tails and bangs, soft tapered hair tips, half-open teal anime eyes, tiny gentle smile, faint blush, black magenta hair ornaments, light-gray sleeveless top, teal tie, black pleated skirt with teal trim, black detached long sleeves and boots. Approximately 2.5 heads tall with large round head, small body and short natural limbs, SAME proportions as reference. Quiet gentle Fufu-like slightly airheaded personality. Preserve the approved design exactly while expressing this row action. All movements small and restrained. No extra props or effects.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Exactly match the approved reference: refined Japanese hand-drawn anime chibi, delicate linework, soft cel shading with modest gradients and hair highlights. Skin hair clothing are illustrated; no plush fibers, felt, embroidered eyes, stitches, doll photography or realistic3D. Remove reference checkerboard completely; final true alpha..
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
Miku action: Both hands relaxed DOWN, no greeting pose. Gentle breathing, one blink and very slight twin-tail sway, planted boots, first and last frame close.
Source layout: every COMPLETE silhouette including twin-tails fits within 72% of its slot width. Wide continuous pure green gutters between all poses. Do not let hair touch a neighbor; no outer-edge clipping.


## jumping.md

Create one horizontal animation strip for Codex pet `miku`, state `jumping`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 5 full-body frames in one left-to-right row on flat pure user-selected #00FF00. Treat the row as 5 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: The supplied approved second-version Miku reference is the ONLY character design authority. Preserve exactly its face shape, layered curved teal twin-tails and bangs, soft tapered hair tips, half-open teal anime eyes, tiny gentle smile, faint blush, black magenta hair ornaments, light-gray sleeveless top, teal tie, black pleated skirt with teal trim, black detached long sleeves and boots. Approximately 2.5 heads tall with large round head, small body and short natural limbs, SAME proportions as reference. Quiet gentle Fufu-like slightly airheaded personality. Preserve the approved design exactly while expressing this row action. All movements small and restrained. No extra props or effects.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Exactly match the approved reference: refined Japanese hand-drawn anime chibi, delicate linework, soft cel shading with modest gradients and hair highlights. Skin hair clothing are illustrated; no plush fibers, felt, embroidered eyes, stitches, doll photography or realistic3D. Remove reference checkerboard completely; final true alpha..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Hover jump loop: anticipation, lift, airborne peak, descent, and settle through body height.

State requirements:
- Show the jump through pose and vertical body position only: anticipation, lift, airborne peak, descent, settle.
- Do not draw ground shadows, contact shadows, drop shadows, oval shadows, landing marks, dust, smears, bounce pads, or motion marks under the pet.
- Keep the background outside the pet perfectly flat chroma key with no darker key-colored patches.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.
Miku action: Small happy jump, gentle landing cushion, hair and skirt follow naturally, no ground effects.
Source layout: every COMPLETE silhouette including twin-tails fits within 72% of its slot width. Wide continuous pure green gutters between all poses. Do not let hair touch a neighbor; no outer-edge clipping.


## look-row-10.md

EDIT the FIRST attached image (completed look-row-9) IN PLACE. Keep exactly its canvas size 2172x724, all eight characters' full-body size, x positions, y positions, boot baseline at y520, full-figure height about305pixels, and all empty green padding. This is an in-place gaze change to the already correctly sized image, not a new layout. Keep the body and legs of each character at the same coordinates. Do not enlarge the people. Do not zoom or crop. Preserve the first image's exact anime face construction, hair, outfit and proportions. Generate one coherent new eight-pose family with changes only to eyes, lids, head/neck, and subtle hair follow-through.

The next references define unchanged canonical identity, approved cardinal directions, standard style, and invisible spacing. The cardinal strip order is UP, RIGHT, DOWN, LEFT. Change the FIRST attached image's rightward gaze sequence into the sequence below, looking DOWN through LEFT to UP. Do not mirror the entire image or redesign bangs.
Eight left-to-right poses:
1 DOWN: face visible and frontal, chin tucked, pupils low in natural anime eye apertures, both hands down.
2 DOWN with a little SCREEN-LEFT: near-frontal head, nose and eyes begin pointing image-left while still low.
3 DOWN-LEFT: stronger left yaw, low pupils and tucked chin.
4 LEFT with a little DOWN: clear left-facing face plane, nose toward image-left, gaze slightly below horizontal.
5 LEFT: match the cardinal strip's FOURTH pose. Nose tip and visible pupils clearly LEFT of skull center.
6 LEFT with a little UP: face still left, chin raises, pupils higher.
7 UP-LEFT: reduce yaw toward frontal while chin and eyes remain raised with a left cue.
8 UP with a little LEFT: nearly frontal raised chin and high pupils slightly image-left; one smooth step before row9's frontal UP.

These correspond to 180,202.5,225,247.5,270,292.5,315,337.5 CLOCKWISE ATTENTION TARGETS, not turntable angles. Read qa/look-mechanics.md. Draw all8 together as a unified family, never paste independent cells. Keep torso, skirt, boots and relaxed lowered hands planted, uniform source character height290-300pixels, with unchanged head-to-body ratio. Only eyes/lids/head/neck lead attention, upper body and layered twin-tails follow slightly. Preserve exactly original face shape, half-open teal anime eye construction, tiny gentle smile, bangs/twin-tail layer shapes, ornaments, outfit, proportions and handdrawn cel style. No surprised O mouth, replacement eyes or stretched face.

Use small figures with generous flat pure green #00FF00 gutters around every complete silhouette including twin-tails. Keep consistent body size and baseline, no touching hair or cut hair at outer image edge. No whole-sprite rotations, labels, text, grids, shadows, props, symbols or effects. All head/eye cues after first must occupy the LEFT half of attention circle; do not reverse into screen-right.

## look-row-9.md

Create a horizontal strip of EIGHT SMALL THUMBNAIL-SIZED full-body Miku figures, surrounded by extensive completely flat pure-green #00FF00 empty space. Every complete figure INCLUDING all twin-tail tips must use at most45% of its invisible slot width and at most30% of the whole canvas height. Place them in one centered horizontal band. Keep huge green gutters between ALL figures and green margins outside first/last. Do not enlarge figures to fill the canvas. Previous oversized figures touched hair and failed extraction: this output must show eight separate islands of character pixels.

Use all five attached references with their roles. Canonical and original approved image define the SAME Miku design, contact sheet defines style/scale consistency, layout defines eight positions, approved cardinal strip defines directions in order UP/RIGHT/DOWN/LEFT. Preserve face shape, half-open teal anime eyes, tiny gentle smile, layered curved twin-tails and soft tips, hair ornaments, clothing and2.5-head proportions. Scale each COMPLETE character uniformly smaller to create whitespace; do not redesign or squeeze hair. Original handdrawn cel shading, no plush/3D.

Eight poses, left-to-right:
1 UP: frontal face, chin clearly raised, high pupils, small smile.
2 UP and a little screen-RIGHT: chin high, slight right attention.
3 UP-RIGHT: more right head yaw, raised eyes/chin.
4 RIGHT and a little UP: clear right face plane, gaze slightly above horizontal.
5 SCREEN-RIGHT: nose tip and visible pupil right of skull center, match second cardinal.
6 RIGHT and a little DOWN: lowered gaze, head begins returning frontal.
7 DOWN-RIGHT: chin low and small remaining right yaw.
8 DOWN with a little RIGHT: nearly frontal face and low pupils, slight right cue, smoothly precedes frontal DOWN.
These are attention targets 000,022.5,045,067.5,090,112.5,135,157.5, never body rotation angles. Read qa/look-mechanics.md. All bodies and feet remain planted, hands DOWN, identical apparent character/head size and baseline. Eyes and head lead attention, twin-tails follow very slightly. Interpolate one unified family with even transitions; no whole-sprite rotation/warping/back view. No text, grid, symbols, effects, shadows or props. All8 full silhouettes must be intact and isolated with uninterrupted green-only gutters.

## review.md

Create one horizontal animation strip for Codex pet `miku`, state `review`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 6 full-body frames in one left-to-right row on flat pure user-selected #00FF00. Treat the row as 6 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: The supplied approved second-version Miku reference is the ONLY character design authority. Preserve exactly its face shape, layered curved teal twin-tails and bangs, soft tapered hair tips, half-open teal anime eyes, tiny gentle smile, faint blush, black magenta hair ornaments, light-gray sleeveless top, teal tie, black pleated skirt with teal trim, black detached long sleeves and boots. Approximately 2.5 heads tall with large round head, small body and short natural limbs, SAME proportions as reference. Quiet gentle Fufu-like slightly airheaded personality. Preserve the approved design exactly while expressing this row action. All movements small and restrained. No extra props or effects.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Exactly match the approved reference: refined Japanese hand-drawn anime chibi, delicate linework, soft cel shading with modest gradients and hair highlights. Skin hair clothing are illustrated; no plush fibers, felt, embroidered eyes, stitches, doll photography or realistic3D. Remove reference checkerboard completely; final true alpha..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Ready-review loop: focused inspection of completed output with lean, blink, narrowed eyes, head tilt, or paw pose.

State requirements:
- Show review through lean, blink, narrowed eyes, head tilt, or paw/hand position.
- Do not add magnifying glasses, papers, code, UI, punctuation, symbols, or other new props unless they already exist in the base pet identity.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.
Miku action: Head slightly forward with observing gaze changes, distinct from thinking and idle. No tools or props.
Source layout: every COMPLETE silhouette including twin-tails fits within 72% of its slot width. Wide continuous pure green gutters between all poses. Do not let hair touch a neighbor; no outer-edge clipping.


## running-left.md

Create one horizontal animation strip for Codex pet `miku`, state `running-left`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 8 full-body frames in one left-to-right row on flat pure user-selected #00FF00. Treat the row as 8 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: The supplied approved second-version Miku reference is the ONLY character design authority. Preserve exactly its face shape, layered curved teal twin-tails and bangs, soft tapered hair tips, half-open teal anime eyes, tiny gentle smile, faint blush, black magenta hair ornaments, light-gray sleeveless top, teal tie, black pleated skirt with teal trim, black detached long sleeves and boots. Approximately 2.5 heads tall with large round head, small body and short natural limbs, SAME proportions as reference. Quiet gentle Fufu-like slightly airheaded personality. Preserve the approved design exactly while expressing this row action. All movements small and restrained. No extra props or effects.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Exactly match the approved reference: refined Japanese hand-drawn anime chibi, delicate linework, soft cel shading with modest gradients and hair highlights. Skin hair clothing are illustrated; no plush fibers, felt, embroidered eyes, stitches, doll photography or realistic3D. Remove reference checkerboard completely; final true alpha..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Dragging-left loop: show directional movement to the left through body and limb poses only.

State requirements:
- Show directional drag movement to the left through body, limb, and prop movement only.
- The row must unmistakably face and travel left.
- The movement cadence must alternate visibly across the 8 frames instead of repeating one nearly static stride.
- Do not draw speed lines, dust clouds, floor shadows, motion trails, or detached motion effects.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.
Miku action: Short alternating leg steps facing SCREEN-LEFT, restrained bounce and twin-tails lag gently.
Source layout: every COMPLETE silhouette including twin-tails fits within 72% of its slot width. Wide continuous pure green gutters between all poses. Do not let hair touch a neighbor; no outer-edge clipping.


## running-right.md

Create one horizontal animation strip for Codex pet `miku`, state `running-right`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 8 full-body frames in one left-to-right row on flat pure user-selected #00FF00. Treat the row as 8 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: The supplied approved second-version Miku reference is the ONLY character design authority. Preserve exactly its face shape, layered curved teal twin-tails and bangs, soft tapered hair tips, half-open teal anime eyes, tiny gentle smile, faint blush, black magenta hair ornaments, light-gray sleeveless top, teal tie, black pleated skirt with teal trim, black detached long sleeves and boots. Approximately 2.5 heads tall with large round head, small body and short natural limbs, SAME proportions as reference. Quiet gentle Fufu-like slightly airheaded personality. Preserve the approved design exactly while expressing this row action. All movements small and restrained. No extra props or effects.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Exactly match the approved reference: refined Japanese hand-drawn anime chibi, delicate linework, soft cel shading with modest gradients and hair highlights. Skin hair clothing are illustrated; no plush fibers, felt, embroidered eyes, stitches, doll photography or realistic3D. Remove reference checkerboard completely; final true alpha..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Dragging-right loop: show directional movement to the right through body and limb poses only.

State requirements:
- Show directional drag movement to the right through body, limb, and prop movement only.
- The row must unmistakably face and travel right.
- The movement cadence must alternate visibly across the 8 frames instead of repeating one nearly static stride.
- Do not draw speed lines, dust clouds, floor shadows, motion trails, or detached motion effects.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.
Miku action: Short alternating leg steps facing SCREEN-RIGHT, restrained bounce and twin-tails lag gently.
Source layout: every COMPLETE silhouette including twin-tails fits within 72% of its slot width. Wide continuous pure green gutters between all poses. Do not let hair touch a neighbor; no outer-edge clipping.


## running.md

Create one horizontal animation strip for Codex pet `miku`, state `running`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 6 full-body frames in one left-to-right row on flat pure user-selected #00FF00. Treat the row as 6 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: The supplied approved second-version Miku reference is the ONLY character design authority. Preserve exactly its face shape, layered curved teal twin-tails and bangs, soft tapered hair tips, half-open teal anime eyes, tiny gentle smile, faint blush, black magenta hair ornaments, light-gray sleeveless top, teal tie, black pleated skirt with teal trim, black detached long sleeves and boots. Approximately 2.5 heads tall with large round head, small body and short natural limbs, SAME proportions as reference. Quiet gentle Fufu-like slightly airheaded personality. Preserve the approved design exactly while expressing this row action. All movements small and restrained. No extra props or effects.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Exactly match the approved reference: refined Japanese hand-drawn anime chibi, delicate linework, soft cel shading with modest gradients and hair highlights. Skin hair clothing are illustrated; no plush fibers, felt, embroidered eyes, stitches, doll photography or realistic3D. Remove reference checkerboard completely; final true alpha..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Working loop: focused active-task processing, thinking, typing, scanning, or effortful concentration; not literal foot-running, jogging, sprinting, treadmill motion, raised knees, long steps, pumping arms, or directional travel.

State requirements:
- Show the pet actively working or processing, as if running a task: focused posture, busy hands or paws, purposeful bobbing, thinking motion, tool or prop motion only if already part of the pet identity, or other non-locomotion activity.
- Do not show literal foot-running, jogging, sprinting, treadmill motion, raised knees, long steps, pumping arms, directional travel, speed lines, dust clouds, floor shadows, motion trails, or detached motion effects.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.
Miku action: Task-processing and thinking, focused eyes and small nod, hand near chin. Feet planted; no foot running.
Source layout: every COMPLETE silhouette including twin-tails fits within 72% of its slot width. Wide continuous pure green gutters between all poses. Do not let hair touch a neighbor; no outer-edge clipping.


## waiting.md

Create one horizontal animation strip for Codex pet `miku`, state `waiting`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 6 full-body frames in one left-to-right row on flat pure user-selected #00FF00. Treat the row as 6 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: The supplied approved second-version Miku reference is the ONLY character design authority. Preserve exactly its face shape, layered curved teal twin-tails and bangs, soft tapered hair tips, half-open teal anime eyes, tiny gentle smile, faint blush, black magenta hair ornaments, light-gray sleeveless top, teal tie, black pleated skirt with teal trim, black detached long sleeves and boots. Approximately 2.5 heads tall with large round head, small body and short natural limbs, SAME proportions as reference. Quiet gentle Fufu-like slightly airheaded personality. Preserve the approved design exactly while expressing this row action. All movements small and restrained. No extra props or effects.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Exactly match the approved reference: refined Japanese hand-drawn anime chibi, delicate linework, soft cel shading with modest gradients and hair highlights. Skin hair clothing are illustrated; no plush fibers, felt, embroidered eyes, stitches, doll photography or realistic3D. Remove reference checkerboard completely; final true alpha..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Needs-input loop: expectant asking pose for approval, help, or user input.

State requirements:
- Show that Codex needs approval, help, or user input through an expectant asking pose.
- Keep the motion patient and readable, without turning it into ordinary idle or review.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.
Miku action: Slight head tilt, both hands close in front of body, quietly expectant.
Source layout: every COMPLETE silhouette including twin-tails fits within 72% of its slot width. Wide continuous pure green gutters between all poses. Do not let hair touch a neighbor; no outer-edge clipping.

REPAIR PRIORITY: Previous strip filled every slot with oversized hair, which touched neighboring poses and was cropped at outer edge. Draw SIX SMALL characters surrounded by extensive empty green space. Confine full characters to the middle horizontal band of the canvas, at most 40% of canvas height. Each complete silhouette including full twin-tails uses at most55% of its invisible slot width. At least22%slotwidth pure green at EACH side. Keep all approved twin-tail shapes unchanged, scale the whole character uniformly smaller. Six clearly isolated islands of character pixels, never touching; no cut hair at canvas sides. Original full-body design otherwise identical.


## waving.md

Create one horizontal animation strip for Codex pet `miku`, state `waving`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 4 full-body frames in one left-to-right row on flat pure user-selected #00FF00. Treat the row as 4 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: The supplied approved second-version Miku reference is the ONLY character design authority. Preserve exactly its face shape, layered curved teal twin-tails and bangs, soft tapered hair tips, half-open teal anime eyes, tiny gentle smile, faint blush, black magenta hair ornaments, light-gray sleeveless top, teal tie, black pleated skirt with teal trim, black detached long sleeves and boots. Approximately 2.5 heads tall with large round head, small body and short natural limbs, SAME proportions as reference. Quiet gentle Fufu-like slightly airheaded personality. Preserve the approved design exactly while expressing this row action. All movements small and restrained. No extra props or effects.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Exactly match the approved reference: refined Japanese hand-drawn anime chibi, delicate linework, soft cel shading with modest gradients and hair highlights. Skin hair clothing are illustrated; no plush fibers, felt, embroidered eyes, stitches, doll photography or realistic3D. Remove reference checkerboard completely; final true alpha..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Greeting loop: paw or limb down, raised, tilted, and returning in a friendly attention gesture.

State requirements:
- Show the greeting through paw, hand, wing, or limb pose only.
- Do not draw wave marks, motion arcs, lines, sparkles, symbols, or floating effects around the gesture.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.
Miku action: Raise one small hand and wave softly with slight head tilt and tiny smile, then lower hand.
Source layout: every COMPLETE silhouette including twin-tails fits within 72% of its slot width. Wide continuous pure green gutters between all poses. Do not let hair touch a neighbor; no outer-edge clipping.

