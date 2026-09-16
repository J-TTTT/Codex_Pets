# La Signora generation prompts

Generated with the built-in image generation tool, grounded in the approved La Signora reference.

## base-pet.md

Create one clean full-body reference sprite for Codex pet La Signora.

Pet identity: Use approved reference as ONLY design. La Signora human form: pale blonde side-part curls, ornate black half-mask covering CHARACTER LEFT eye (viewer RIGHT in front view); ONLY character right grey-blue eye visible (viewer LEFT). Never swap mask side or reveal hidden eye. Viewer-left red-black hair bow and gold jewels. Black/red dress, white stylized fur shoulder collar, burgundy cape lining, gold trim, red jewels, black long gloves, dark shoes. Keep original round face, head-body proportions, proud gentle smile, cel-anime style. Empty hands, no weapons, no transformation. Generate left and right movement independently; never mirror. Complete mask tips/curls/cape/skirt/shoes with ample margins. No text, checkerboard, effects, shadow or props..
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Fine Japanese chibi anime linework, soft cel color, restrained gradients, pale skin and blush, grey-blue anime visible eye; white collar drawn as simplified fur tufts, never plush photography or 3D. Preserve reference proportions and design; only neutral stance and framing may change..


Place a single centered pose on a perfectly flat pure user-selected #00FF00 chroma-key background. Keep the full pet visible, compact, readable at 192x208, and easy to animate. Preserve approved reference identity cues. No scenery, text, borders, checkerboard transparency, shadows, glows, detached effects, or extra props. Keep #00FF00 and close colors out of the pet, props, highlights, and effects.


## 000.md

Repair one cardinal anchor for Codex pet `la-signora`: `000` means looking up.

Use the canonical base, completed standard contact sheet, approved cardinal-strip cells, and `qa/look-mechanics.md` for identity, scale, registration, and pet-specific gaze mechanics. Keep the face broadly frontal and point the eyes and natural head mechanism toward the TOP edge. Screen coordinates are viewer-relative.

Output one centered complete full-body pose on a flat pure user-selected #00FF00 background with generous padding. Keep the feet/base and lower body registered to the approved anchors. The requested cardinal must be unmistakable at final 192x208 display size.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement eyes, labels, arrows, guide marks, shadows, scenery, detached effects, or chroma-key colors inside the pet.


## 090.md

Repair one cardinal anchor for Codex pet `la-signora`: `090` means looking right.

Use the canonical base, completed standard contact sheet, approved cardinal-strip cells, and `qa/look-mechanics.md` for identity, scale, registration, and pet-specific gaze mechanics. Put the nose tip, pupils, face surface, or natural aiming feature on the screen-right side of the head center. Screen coordinates are viewer-relative.

Output one centered complete full-body pose on a flat pure user-selected #00FF00 background with generous padding. Keep the feet/base and lower body registered to the approved anchors. The requested cardinal must be unmistakable at final 192x208 display size.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement eyes, labels, arrows, guide marks, shadows, scenery, detached effects, or chroma-key colors inside the pet.


## 180.md

Repair one cardinal anchor for Codex pet `la-signora`: `180` means looking down.

Use the canonical base, completed standard contact sheet, approved cardinal-strip cells, and `qa/look-mechanics.md` for identity, scale, registration, and pet-specific gaze mechanics. Keep the face broadly frontal and point the eyes and natural head mechanism toward the BOTTOM edge. Screen coordinates are viewer-relative.

Output one centered complete full-body pose on a flat pure user-selected #00FF00 background with generous padding. Keep the feet/base and lower body registered to the approved anchors. The requested cardinal must be unmistakable at final 192x208 display size.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement eyes, labels, arrows, guide marks, shadows, scenery, detached effects, or chroma-key colors inside the pet.


## 270.md

Repair one cardinal anchor for Codex pet `la-signora`: `270` means looking left.

Use the canonical base, completed standard contact sheet, approved cardinal-strip cells, and `qa/look-mechanics.md` for identity, scale, registration, and pet-specific gaze mechanics. Put the nose tip, pupils, face surface, or natural aiming feature on the screen-left side of the head center. Screen coordinates are viewer-relative.

Output one centered complete full-body pose on a flat pure user-selected #00FF00 background with generous padding. Keep the feet/base and lower body registered to the approved anchors. The requested cardinal must be unmistakable at final 192x208 display size.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement eyes, labels, arrows, guide marks, shadows, scenery, detached effects, or chroma-key colors inside the pet.


## look-cardinals.md

Create one horizontal four-cardinal anchor strip for Codex pet `la-signora`.

Use the attached canonical base, completed standard contact sheet, and layout guide for exact identity, style, scale, baseline, face construction, materials, palette, markings, props, and spacing. Read `qa/look-mechanics.md` and use the pet's natural gaze mechanism.

Output exactly four centered complete full-body poses in this exact left-to-right order: `000 up`, `090 screen-right`, `180 down`, `270 screen-left`. Screen-left and screen-right always mean the viewer's image edges, never the character's own left or right.

For `000`, keep the face broadly frontal and point the eyes and natural head mechanism toward the TOP edge. For `090`, put the nose tip, pupils, face surface, or natural aiming feature on the screen-right side of the head center. For `180`, keep the face broadly frontal and point toward the BOTTOM edge. For `270`, apply the inverse screen-left landmark rule. Every cardinal must be unmistakable without labels.

Place one pose in each invisible equal-width slot on a flat pure user-selected #00FF00 background with generous padding. Keep scale, feet/base, lower body, and registration consistent across all four slots.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement eyes, labels, degree text, arrows, boxes, guide marks, shadows, scenery, detached effects, or chroma-key colors inside the pet.

La Signora identity/occlusion lock: mask covers anatomical LEFT eye (viewer RIGHT in frontal pose) forever; only anatomical RIGHT grey-blue eye is visible. Never swap mask or show hidden eye. Keep original hairbow side, round face, blonde curls, earrings, white collar, black/red cape/dress. Moderate head yaw about30degrees combines with visible-eye/eyelid direction; do not turn wholebody. Mask follows skull, far-side features foreshorten naturally. For DOWN keep a narrow visible iris instead of fully closing eye. For UP clearly raise chin and iris above neutral. Rightward nose/face aim imageRIGHT, leftward aim imageLEFT, regardless of mask silhouette. Feet/waist/lowercape anchors fixed and alltips insideframe. No weapons/props/effects/shadows or designchanges.


## failed.md

Create Codex pet row `failed` for `la-signora`: exactly 8 full-body frames in one horizontal strip on flat pure user-selected #00FF00.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Use approved reference as ONLY design. La Signora human form: pale blonde side-part curls, ornate black half-mask covering CHARACTER LEFT eye (viewer RIGHT in front view); ONLY character right grey-blue eye visible (viewer LEFT). Never swap mask side or reveal hidden eye. Viewer-left red-black hair bow and gold jewels. Black/red dress, white stylized fur shoulder collar, burgundy cape lining, gold trim, red jewels, black long gloves, dark shoes. Keep original round face, head-body proportions, proud gentle smile, cel-anime style. Empty hands, no weapons, no transformation. Generate left and right movement independently; never mirror. Complete mask tips/curls/cape/skirt/shoes with ample margins. No text, checkerboard, effects, shadow or props.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Blocked/failed loop: slumped or deflated reaction with sad or closed eyes.

State requirements:
- Show failure through slumped pose, drooping ears/limbs, closed or sad eyes, and lower body position.
- Tears, small smoke puffs, or tiny stars are allowed only if attached to or overlapping the pet silhouette and kept inside the same frame slot.
- Do not draw red X marks, floating symbols, detached stars, separated smoke clouds, falling tear drops, dust, or other loose effects.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #00FF00 colors in the pet.

User-specific action: Eight-frame restrained reaction: visible eye lowers, smile fades, head turns slightly with mild surprise/reluctance, then composed expression returns. No crying, anger, symbols or effects.


## idle.md

Create Codex pet row `idle` for `la-signora`: exactly 6 full-body frames in one horizontal strip on flat pure user-selected #00FF00.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Use approved reference as ONLY design. La Signora human form: pale blonde side-part curls, ornate black half-mask covering CHARACTER LEFT eye (viewer RIGHT in front view); ONLY character right grey-blue eye visible (viewer LEFT). Never swap mask side or reveal hidden eye. Viewer-left red-black hair bow and gold jewels. Black/red dress, white stylized fur shoulder collar, burgundy cape lining, gold trim, red jewels, black long gloves, dark shoes. Keep original round face, head-body proportions, proud gentle smile, cel-anime style. Empty hands, no weapons, no transformation. Generate left and right movement independently; never mirror. Complete mask tips/curls/cape/skirt/shoes with ample margins. No text, checkerboard, effects, shadow or props.. Preserve silhouette, face, palette, material, proportions, markings, and props.

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

User-specific action: Elegant relaxed hands below chest throughout; exposed eye blinks briefly then opens. Gentle breathing, tiny curl/cape sway. Six subtly different poses; loop returns to same rest.


## jumping.md

Create Codex pet row `jumping` for `la-signora`: exactly 5 full-body frames in one horizontal strip on flat pure user-selected #00FF00.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Use approved reference as ONLY design. La Signora human form: pale blonde side-part curls, ornate black half-mask covering CHARACTER LEFT eye (viewer RIGHT in front view); ONLY character right grey-blue eye visible (viewer LEFT). Never swap mask side or reveal hidden eye. Viewer-left red-black hair bow and gold jewels. Black/red dress, white stylized fur shoulder collar, burgundy cape lining, gold trim, red jewels, black long gloves, dark shoes. Keep original round face, head-body proportions, proud gentle smile, cel-anime style. Empty hands, no weapons, no transformation. Generate left and right movement independently; never mirror. Complete mask tips/curls/cape/skirt/shoes with ample margins. No text, checkerboard, effects, shadow or props.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Hover jump loop: anticipation, lift, airborne peak, descent, and settle through body height.

State requirements:
- Show the jump through pose and vertical body position only: anticipation, lift, airborne peak, descent, settle.
- Do not draw ground shadows, contact shadows, drop shadows, oval shadows, landing marks, dust, smears, bounce pads, or motion marks under the pet.
- Keep the background outside the pet perfectly flat chroma key with no darker key-colored patches.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #00FF00 colors in the pet.

User-specific action: Five distinct phases: slight preparation crouch, rise with both feet off baseline, modest apex, descent, soft landing. Upright graceful small jump, cape/skirt lift slightly then settle, no ground effects.


## look-row-10.md

Create Codex v2 pet look row 10 for `la-signora` as exactly 8 full-body frames in this order: 180, 202.5, 225, 247.5, 270, 292.5, 315, 337.5.

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

Create Codex v2 pet look row 9 for `la-signora` as exactly 8 full-body frames in this order: 000, 022.5, 045, 067.5, 090, 112.5, 135, 157.5.

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

Create Codex pet row `review` for `la-signora`: exactly 6 full-body frames in one horizontal strip on flat pure user-selected #00FF00.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Use approved reference as ONLY design. La Signora human form: pale blonde side-part curls, ornate black half-mask covering CHARACTER LEFT eye (viewer RIGHT in front view); ONLY character right grey-blue eye visible (viewer LEFT). Never swap mask side or reveal hidden eye. Viewer-left red-black hair bow and gold jewels. Black/red dress, white stylized fur shoulder collar, burgundy cape lining, gold trim, red jewels, black long gloves, dark shoes. Keep original round face, head-body proportions, proud gentle smile, cel-anime style. Empty hands, no weapons, no transformation. Generate left and right movement independently; never mirror. Complete mask tips/curls/cape/skirt/shoes with ample margins. No text, checkerboard, effects, shadow or props.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Ready-review loop: focused inspection of completed output with lean, blink, narrowed eyes, head tilt, or paw pose.

State requirements:
- Show review through lean, blink, narrowed eyes, head tilt, or paw/hand position.
- Do not add magnifying glasses, papers, code, UI, punctuation, symbols, or other new props unless they already exist in the base pet identity.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #00FF00 colors in the pet.

User-specific action: Six-frame inspection loop: hands remain low, head slightly forward, exposed eye scans subtly and pauses, then a small confirming nod. Distinct from hand-at-chin thinking; no props.


## running-left.md

Create Codex pet row `running-left` for `la-signora`: exactly 8 full-body frames in one horizontal strip on flat pure user-selected #00FF00.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Use approved reference as ONLY design. La Signora human form: pale blonde side-part curls, ornate black half-mask covering CHARACTER LEFT eye (viewer RIGHT in front view); ONLY character right grey-blue eye visible (viewer LEFT). Never swap mask side or reveal hidden eye. Viewer-left red-black hair bow and gold jewels. Black/red dress, white stylized fur shoulder collar, burgundy cape lining, gold trim, red jewels, black long gloves, dark shoes. Keep original round face, head-body proportions, proud gentle smile, cel-anime style. Empty hands, no weapons, no transformation. Generate left and right movement independently; never mirror. Complete mask tips/curls/cape/skirt/shoes with ample margins. No text, checkerboard, effects, shadow or props.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Dragging-left loop: show directional movement to the left through body and limb poses only.

State requirements:
- Show directional drag movement to the left through body, limb, and prop movement only.
- The row must unmistakably face and travel left.
- The movement cadence must alternate visibly across the 8 frames instead of repeating one nearly static stride.
- Do not draw speed lines, dust clouds, floor shadows, motion trails, or detached motion effects.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #00FF00 colors in the pet.

User-specific action: Eight-frame independently drawn alternating small-step gait toward SCREEN LEFT. Upright elegant body, subdued bounce, cape/skirt lag. Three-quarter leftward view; preserve anatomical LEFT masked eye, never expose it. Do NOT mirror rightward frames.


## running-right.md

Create Codex pet row `running-right` for `la-signora`: exactly 8 full-body frames in one horizontal strip on flat pure user-selected #00FF00.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Use approved reference as ONLY design. La Signora human form: pale blonde side-part curls, ornate black half-mask covering CHARACTER LEFT eye (viewer RIGHT in front view); ONLY character right grey-blue eye visible (viewer LEFT). Never swap mask side or reveal hidden eye. Viewer-left red-black hair bow and gold jewels. Black/red dress, white stylized fur shoulder collar, burgundy cape lining, gold trim, red jewels, black long gloves, dark shoes. Keep original round face, head-body proportions, proud gentle smile, cel-anime style. Empty hands, no weapons, no transformation. Generate left and right movement independently; never mirror. Complete mask tips/curls/cape/skirt/shoes with ample margins. No text, checkerboard, effects, shadow or props.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Dragging-right loop: show directional movement to the right through body and limb poses only.

State requirements:
- Show directional drag movement to the right through body, limb, and prop movement only.
- The row must unmistakably face and travel right.
- The movement cadence must alternate visibly across the 8 frames instead of repeating one nearly static stride.
- Do not draw speed lines, dust clouds, floor shadows, motion trails, or detached motion effects.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #00FF00 colors in the pet.

User-specific action: Eight-frame alternating small-step gait toward SCREEN RIGHT. Upright elegant body, subdued bounce, cape/skirt lag. Three-quarter rightward view; preserve anatomical LEFT masked eye, never expose it. Do not flip identity.


## running.md

Create Codex pet row `running` for `la-signora`: exactly 6 full-body frames in one horizontal strip on flat pure user-selected #00FF00.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Use approved reference as ONLY design. La Signora human form: pale blonde side-part curls, ornate black half-mask covering CHARACTER LEFT eye (viewer RIGHT in front view); ONLY character right grey-blue eye visible (viewer LEFT). Never swap mask side or reveal hidden eye. Viewer-left red-black hair bow and gold jewels. Black/red dress, white stylized fur shoulder collar, burgundy cape lining, gold trim, red jewels, black long gloves, dark shoes. Keep original round face, head-body proportions, proud gentle smile, cel-anime style. Empty hands, no weapons, no transformation. Generate left and right movement independently; never mirror. Complete mask tips/curls/cape/skirt/shoes with ample margins. No text, checkerboard, effects, shadow or props.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Working loop: focused active-task processing, thinking, typing, scanning, or effortful concentration; not literal foot-running, jogging, sprinting, treadmill motion, raised knees, long steps, pumping arms, or directional travel.

State requirements:
- Show the pet actively working or processing, as if running a task: focused posture, busy hands or paws, purposeful bobbing, thinking motion, tool or prop motion only if already part of the pet identity, or other non-locomotion activity.
- Do not show literal foot-running, jogging, sprinting, treadmill motion, raised knees, long steps, pumping arms, directional travel, speed lines, dust clouds, floor shadows, motion trails, or detached motion effects.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #00FF00 colors in the pet.

User-specific action: Six-frame thoughtful work loop: gloved hand lightly at chin, focused visible eye, tiny nods. Feet planted, NOT foot-running. Controlled dignified expression.


## waiting.md

Create Codex pet row `waiting` for `la-signora`: exactly 6 full-body frames in one horizontal strip on flat pure user-selected #00FF00.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Use approved reference as ONLY design. La Signora human form: pale blonde side-part curls, ornate black half-mask covering CHARACTER LEFT eye (viewer RIGHT in front view); ONLY character right grey-blue eye visible (viewer LEFT). Never swap mask side or reveal hidden eye. Viewer-left red-black hair bow and gold jewels. Black/red dress, white stylized fur shoulder collar, burgundy cape lining, gold trim, red jewels, black long gloves, dark shoes. Keep original round face, head-body proportions, proud gentle smile, cel-anime style. Empty hands, no weapons, no transformation. Generate left and right movement independently; never mirror. Complete mask tips/curls/cape/skirt/shoes with ample margins. No text, checkerboard, effects, shadow or props.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Needs-input loop: expectant asking pose for approval, help, or user input.

State requirements:
- Show that Codex needs approval, help, or user input through an expectant asking pose.
- Keep the motion patient and readable, without turning it into ordinary idle or review.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #00FF00 colors in the pet.

User-specific action: Six-frame quiet expectant loop: tiny head tilt, one gloved hand near waist, other palm gently open inviting response. Patient confident little smile, no impatience.


## waving.md

Create Codex pet row `waving` for `la-signora`: exactly 4 full-body frames in one horizontal strip on flat pure user-selected #00FF00.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Use approved reference as ONLY design. La Signora human form: pale blonde side-part curls, ornate black half-mask covering CHARACTER LEFT eye (viewer RIGHT in front view); ONLY character right grey-blue eye visible (viewer LEFT). Never swap mask side or reveal hidden eye. Viewer-left red-black hair bow and gold jewels. Black/red dress, white stylized fur shoulder collar, burgundy cape lining, gold trim, red jewels, black long gloves, dark shoes. Keep original round face, head-body proportions, proud gentle smile, cel-anime style. Empty hands, no weapons, no transformation. Generate left and right movement independently; never mirror. Complete mask tips/curls/cape/skirt/shoes with ample margins. No text, checkerboard, effects, shadow or props.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Greeting loop: paw or limb down, raised, tilted, and returning in a friendly attention gesture.

State requirements:
- Show the greeting through paw, hand, wing, or limb pose only.
- Do not draw wave marks, motion arcs, lines, sparkles, symbols, or floating effects around the gesture.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #00FF00 colors in the pet.

User-specific action: Four poses: resting gloved hand, slowly raise hand, small graceful wave with a slight head tilt and smile, return toward rest. No gesture marks.


## failed.md

Create one horizontal animation strip for Codex pet `la-signora`, state `failed`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 8 full-body frames in one left-to-right row on flat pure user-selected #00FF00. Treat the row as 8 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Use approved reference as ONLY design. La Signora human form: pale blonde side-part curls, ornate black half-mask covering CHARACTER LEFT eye (viewer RIGHT in front view); ONLY character right grey-blue eye visible (viewer LEFT). Never swap mask side or reveal hidden eye. Viewer-left red-black hair bow and gold jewels. Black/red dress, white stylized fur shoulder collar, burgundy cape lining, gold trim, red jewels, black long gloves, dark shoes. Keep original round face, head-body proportions, proud gentle smile, cel-anime style. Empty hands, no weapons, no transformation. Generate left and right movement independently; never mirror. Complete mask tips/curls/cape/skirt/shoes with ample margins. No text, checkerboard, effects, shadow or props.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Fine Japanese chibi anime linework, soft cel color, restrained gradients, pale skin and blush, grey-blue anime visible eye; white collar drawn as simplified fur tufts, never plush photography or 3D. Preserve reference proportions and design; only neutral stance and framing may change..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Blocked/failed loop: slumped or deflated reaction with sad or closed eyes.

State requirements:
- Show failure through slumped pose, drooping ears/limbs, closed or sad eyes, and lower body position.
- Tears, small smoke puffs, or tiny stars are allowed only if attached to or overlapping the pet silhouette and kept inside the same frame slot.
- Do not draw red X marks, floating symbols, detached stars, separated smoke clouds, falling tear drops, dust, or other loose effects.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.

User-specific action: Eight-frame restrained reaction: visible eye lowers, smile fades, head turns slightly with mild surprise/reluctance, then composed expression returns. No crying, anger, symbols or effects.


## idle.md

Create one horizontal animation strip for Codex pet `la-signora`, state `idle`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 6 full-body frames in one left-to-right row on flat pure user-selected #00FF00. Treat the row as 6 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Use approved reference as ONLY design. La Signora human form: pale blonde side-part curls, ornate black half-mask covering CHARACTER LEFT eye (viewer RIGHT in front view); ONLY character right grey-blue eye visible (viewer LEFT). Never swap mask side or reveal hidden eye. Viewer-left red-black hair bow and gold jewels. Black/red dress, white stylized fur shoulder collar, burgundy cape lining, gold trim, red jewels, black long gloves, dark shoes. Keep original round face, head-body proportions, proud gentle smile, cel-anime style. Empty hands, no weapons, no transformation. Generate left and right movement independently; never mirror. Complete mask tips/curls/cape/skirt/shoes with ample margins. No text, checkerboard, effects, shadow or props.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Fine Japanese chibi anime linework, soft cel color, restrained gradients, pale skin and blush, grey-blue anime visible eye; white collar drawn as simplified fur tufts, never plush photography or 3D. Preserve reference proportions and design; only neutral stance and framing may change..
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

User-specific action: Elegant relaxed hands below chest throughout; exposed eye blinks briefly then opens. Gentle breathing, tiny curl/cape sway. Six subtly different poses; loop returns to same rest.


## jumping.md

Create one horizontal animation strip for Codex pet `la-signora`, state `jumping`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 5 full-body frames in one left-to-right row on flat pure user-selected #00FF00. Treat the row as 5 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Use approved reference as ONLY design. La Signora human form: pale blonde side-part curls, ornate black half-mask covering CHARACTER LEFT eye (viewer RIGHT in front view); ONLY character right grey-blue eye visible (viewer LEFT). Never swap mask side or reveal hidden eye. Viewer-left red-black hair bow and gold jewels. Black/red dress, white stylized fur shoulder collar, burgundy cape lining, gold trim, red jewels, black long gloves, dark shoes. Keep original round face, head-body proportions, proud gentle smile, cel-anime style. Empty hands, no weapons, no transformation. Generate left and right movement independently; never mirror. Complete mask tips/curls/cape/skirt/shoes with ample margins. No text, checkerboard, effects, shadow or props.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Fine Japanese chibi anime linework, soft cel color, restrained gradients, pale skin and blush, grey-blue anime visible eye; white collar drawn as simplified fur tufts, never plush photography or 3D. Preserve reference proportions and design; only neutral stance and framing may change..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Hover jump loop: anticipation, lift, airborne peak, descent, and settle through body height.

State requirements:
- Show the jump through pose and vertical body position only: anticipation, lift, airborne peak, descent, settle.
- Do not draw ground shadows, contact shadows, drop shadows, oval shadows, landing marks, dust, smears, bounce pads, or motion marks under the pet.
- Keep the background outside the pet perfectly flat chroma key with no darker key-colored patches.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.

User-specific action: Five distinct phases: slight preparation crouch, rise with both feet off baseline, modest apex, descent, soft landing. Upright graceful small jump, cape/skirt lift slightly then settle, no ground effects.


## look-row-10-repair.md

Create a fresh coherent row of eight complete La Signora gaze poses. Preserve original design and body anchor; repair ONLY the direction family and source size from the rejected attempt.

PRIMARY direction reference is attached single LEFT cardinal (mask-bearing cheek near viewer, nose and face plane pointing toward IMAGE LEFT). The approved cardinal strip defines down/left/up. Row9 is ONLY scale, body, cape and baseline reference; do NOT reuse its rightward heads.

Exactly eight separated full-body figures on flat #00FF00, canvas2172x724. All figures approximately443–450px tall including every mask tip and shoe, never470–485px. Match row9 actual figure size and silhouette, ample green margins. Keep feet/waist/capehem registration fixed. All eight drawn together, no pasting or independent cell styles.

1 DOWN: face horizontally centered, chin tucked, visible eye aimed low.
2 DOWN-LEFT nearDOWN: nose/face slightly LEFT, iris low-left.
3 DOWN-LEFT: definite LEFT head yaw, low-left visible gaze.
4 DOWN-LEFT nearLEFT: use LEFT anchor head, gaze slightly belowlevel.
5 LEFT: preserve approved LEFT anchor face and mask occlusion; eye/nose clearly aim IMAGE LEFT.
6 UP-LEFT nearLEFT: same LEFT head family, eye and chin a little raised.
7 UP-LEFT: definite LEFT nose/face aim with upward visible eye.
8 UP-LEFT nearUP: head returns gently toward front while retaining slight LEFT bias and clear upward gaze; one step before row9 first UP.

Keep mask on ANATOMICAL LEFT eye, always fully covering it. Exposed anatomicalRIGHT grey-blue eye remains on its natural far-side aperture when turning LEFT; do not reveal a second eye. Mask/curls/earrings rotate with skull naturally. Maintain same round face, blonde curls, original asymmetric bow, white collar, black/red dress, cape, gold/red ornaments, gloves and shoes. Feetbody remainfront, headyaws onlyabout30degrees maximum, no wholebodyrotation or warp. Emptyhands, no weapons/effects/shadow/text.

Before returning, verify all six diagonals in this LEFT row have LEFT nose/faceplane, not rightward faces from row9. Every pose complete and same scale. Do not insert a special larger LEFT cardinal in the middle.


## look-row-10-size-edit.md

EDIT the FIRST attached image (complete eight-pose La Signora LEFT-gaze row). It is the approved direction/character family. Preserve ALL eight poses, faces, eye directions, mask occlusion, hairstyles, clothes, ornaments, body proportions, colors, shading and linework exactly. Do not redraw or redesign heads. Other attached references are identity/layout safeguards only.

The ONLY change: uniformly reduce every complete figure to 95% of its current size, about5% smaller, keeping the canvas2171x724 and the same eight horizontal centers and foot baseline. This adds green clearance above the mask horns. Do NOT resize the canvas. Do NOT crop the figures. Use a common scale change for all eight, anchored at each figure's feet, and fill newly exposed pixels with the same flat pure #00FF00 background. The tallest complete figure should be approximately445pixels tall (including all horn tips and soles), rather than the current471pixels.

Maintain one coherent row of8fullbody figures in the exact same DOWN→DOWNLEFT→LEFT→UPLEFT order. Existing anatomy and directions already passed: all six diagonals point IMAGELEFT; mask permanently covers anatomicalLEFTeye; only anatomicalRIGHTgreyblueeye visible. Keep that exactly. No mirror, no swapping sides, no deformation, no per-frame styling changes, no effects, props, text or shadows. Return the complete edited row, never an isolated cell.


## look-row-10.md

Create one horizontal look-direction strip for Codex pet `la-signora`, atlas row 10.

Use the attached canonical base, completed standard contact sheet, layout guide, and approved four-cardinal strip for identity, scale, registration, spacing, direction semantics, and cross-row continuity. Read `qa/look-mechanics.md` and follow its pet-specific movement and eye/prop mechanics. The approved cardinal strip and completed coherent row 9 are authoritative. Use the cardinals for direction meaning and row 9 for cross-row identity, scale, registration, and continuity.

COHERENT SYNTHESIS LOCK: produce one unified eight-pose row. Do not paste, tile, or independently restyle individual cells. Every final cell must be drawn together with the same face construction, body proportions, line/render quality, lighting, materials, scale, baseline, and registration.

Output exactly 8 complete full-body frames in this exact left-to-right order: 180, 202.5, 225, 247.5, 270, 292.5, 315, 337.5. Degrees are clockwise: 000 is up, 090 right, 180 down, and 270 left. Neutral/front is not part of this row.

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

SCREEN-COORDINATE LOCK: screen-left means the viewer's left image edge, never the character's own left. The row should travel naturally through the left half of the loop. Near-vertical 202.5 and 337.5 may have subtle horizontal cues; prioritize a coherent arc over exact pupil or nose placement.

HARD LAYOUT AND CONTINUITY CONTRACT — DETERMINISTIC REGISTRATION: draw exactly eight separated pose groups in left-to-right direction order. Keep enough chroma-only space between neighboring poses that each complete pose can be detected without cutting through foreground. Approximate the guide's equal spacing, but do not distort a pose merely to hit an exact source-canvas coordinate; deterministic assembly will crop the eight ordered groups, then apply one shared scale and baseline.

Use the same body height, head size, baseline, and planted-body position across the generated family. Never overlap neighboring poses, merge two poses into one connected group, crop foreground at the outer canvas edge, or resize one pose independently.

Keep the feet, base, or lower torso planted at the same coordinates across all eight frames. Express direction through the eyes, face, head, upper body, and physically appropriate prop movement, not by moving, rotating, or rescaling the entire sprite.

Place one centered pose in each invisible equal-width slot on flat pure user-selected #00FF00. Change only the natural parts needed to express gaze: eyes, eyelids, head, face, neck, upper body, appendages, and constrained prop follow-through. Keep identity, silhouette, materials, palette, markings, and props consistent.

ROW-BOUNDARY LOCK: 180 must continue directly from row 9's 157.5, matching its body size, baseline, planted anchor, expression, and construction. 337.5 must be one even 22.5-degree step before 000: nearly up-facing while remaining on the overall left-hand arc. Do not distort pupils, nose, or body geometry merely to exaggerate the subtle horizontal component.

PRE-RETURN CHECK: reject this result if it does not contain eight separated pose groups in the required order; neighboring poses overlap; foreground is cropped at the outer canvas edge; any frame changes sprite scale, body or head size, baseline, or planted-body position; the row visibly reverses into the wrong half of the loop; or 180 does not continue from 157.5 or 337.5 does not flow evenly into 000. Minor intermediate pupil or nose deviations are not rejection reasons. Exact cell cropping, resizing, and recentering happen deterministically after generation.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement/googly eyes, labels, degree text, arrows, clocks, grids, shadows, glows, scenery, detached effects, or chroma-key colors inside the pet.

La Signora identity/occlusion lock: mask covers anatomical LEFT eye (viewer RIGHT in frontal pose) forever; only anatomical RIGHT grey-blue eye is visible. Never swap mask or show hidden eye. Keep original hairbow side, round face, blonde curls, earrings, white collar, black/red cape/dress. Moderate head yaw about30degrees combines with visible-eye/eyelid direction; do not turn wholebody. Mask follows skull, far-side features foreshorten naturally. For DOWN keep a narrow visible iris instead of fully closing eye. For UP clearly raise chin and iris above neutral. Rightward nose/face aim imageRIGHT, leftward aim imageLEFT, regardless of mask silhouette. Feet/waist/lowercape anchors fixed and alltips insideframe. No weapons/props/effects/shadows or designchanges.


## look-row-9-right-repair.md

Edit the attached complete eight-pose La Signora right-half gaze strip as one coherent family. Keep EXACT original canvas size, all eight full-body scales, feet baselines, costume, head proportions, hair, masked eye, cape and spacing. Redraw only natural head/neck/face/eye orientation to make the rightward gaze clearly readable. Do not mirror anything.
Eight poses left to right: UP; UP slightly RIGHT; UP-RIGHT; RIGHT slightly UP; RIGHT; RIGHT slightly DOWN; DOWN-RIGHT; DOWN slightly RIGHT. The fifth figure must unmistakably look toward the RIGHT EDGE OF THE IMAGE: head yaw about 35 degrees toward image right, nose tip pointing right, chin and mouth perspective following that turn, exposed grey-blue iris looking toward its eye aperture's RIGHT corner with more white visible on its LEFT. Retain the original anime eye construction and soft expression. Frame 5 must not look left or straight at viewer. Adjacent frames interpolate this rightward yaw smoothly with appropriate upward/downward pitch.
The mask covers her anatomical LEFT eye, on the far side when she turns her face toward image right. The exposed anatomical RIGHT cheek/eye becomes the near-side face surface. Black mask stays attached to its original left face side, foreshortened naturally, never moved to the exposed eye. The head outline and nose direction must carry RIGHT orientation even when the visible eye is partly small. Do not use a whole-body lean to fake this turn.
Body, planted feet and lower cape remain fixed. Keep source figure total heights no greater than the edit target (approximately 435-450 px); eight separated full-body groups with all mask spikes, blonde curls, cape, ornaments and shoes intact. Preserve the approved reference design, round face, pale blonde hair, white drawn fur, burgundy and black dress, fine linework. All eight poses must be redrawn together as one coherent row. No new props, no hidden eye revealed, no text, grid, effects or shadows. Flat pure #00FF00 background for deterministic extraction. Other references: approved original and canonical identity, spacing guide, standard-row contact, cardinal pose families, and completed left-half strip for continuity.


## look-row-9.md

Create one horizontal look-direction strip for Codex pet `la-signora`, atlas row 9.

Use the attached canonical base, completed standard contact sheet, layout guide, and approved four-cardinal strip for identity, scale, registration, spacing, direction semantics, and cross-row continuity. Read `qa/look-mechanics.md` and follow its pet-specific movement and eye/prop mechanics. The approved cardinal strip is authoritative for the up, screen-right, down, and screen-left pose families. Interpolate the intermediate directions as even 22.5-degree steps between those anchors.

COHERENT SYNTHESIS LOCK: produce one unified eight-pose row. Do not paste, tile, or independently restyle individual cells. Every final cell must be drawn together with the same face construction, body proportions, line/render quality, lighting, materials, scale, baseline, and registration.

Output exactly 8 complete full-body frames in this exact left-to-right order: 000, 022.5, 045, 067.5, 090, 112.5, 135, 157.5. Degrees are clockwise: 000 is up, 090 right, 180 down, and 270 left. Neutral/front is not part of this row.

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

SCREEN-COORDINATE LOCK: screen-right means the viewer's right image edge, never the character's own right. The row should travel naturally through the right half of the loop. Near-vertical 022.5 and 157.5 may have subtle horizontal cues; prioritize a coherent arc over exact pupil or nose placement.

HARD LAYOUT AND CONTINUITY CONTRACT — DETERMINISTIC REGISTRATION: draw exactly eight separated pose groups in left-to-right direction order. Keep enough chroma-only space between neighboring poses that each complete pose can be detected without cutting through foreground. Approximate the guide's equal spacing, but do not distort a pose merely to hit an exact source-canvas coordinate; deterministic assembly will crop the eight ordered groups, then apply one shared scale and baseline.

Use the same body height, head size, baseline, and planted-body position across the generated family. Never overlap neighboring poses, merge two poses into one connected group, crop foreground at the outer canvas edge, or resize one pose independently.

Keep the feet, base, or lower torso planted at the same coordinates across all eight frames. Express direction through the eyes, face, head, upper body, and physically appropriate prop movement, not by moving, rotating, or rescaling the entire sprite.

Place one centered pose in each invisible equal-width slot on flat pure user-selected #00FF00. Change only the natural parts needed to express gaze: eyes, eyelids, head, face, neck, upper body, appendages, and constrained prop follow-through. Keep identity, silhouette, materials, palette, markings, and props consistent.

ROW-BOUNDARY LOCK: 157.5 must be one even 22.5-degree step before 180. Match the approved 180 pose's body size, baseline, planted anchor, expression, and construction. Preserve the overall right-hand arc, but do not distort pupils, nose, or body geometry merely to exaggerate the subtle horizontal component.

PRE-RETURN CHECK: reject this result if it does not contain eight separated pose groups in the required order; neighboring poses overlap; foreground is cropped at the outer canvas edge; any frame changes sprite scale, body or head size, baseline, or planted-body position; the row visibly reverses into the wrong half of the loop; or 157.5 does not flow evenly into 180. Minor intermediate pupil or nose deviations are not rejection reasons. Exact cell cropping, resizing, and recentering happen deterministically after generation.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement/googly eyes, labels, degree text, arrows, clocks, grids, shadows, glows, scenery, detached effects, or chroma-key colors inside the pet.

La Signora identity/occlusion lock: mask covers anatomical LEFT eye (viewer RIGHT in frontal pose) forever; only anatomical RIGHT grey-blue eye is visible. Never swap mask or show hidden eye. Keep original hairbow side, round face, blonde curls, earrings, white collar, black/red cape/dress. Moderate head yaw about30degrees combines with visible-eye/eyelid direction; do not turn wholebody. Mask follows skull, far-side features foreshorten naturally. For DOWN keep a narrow visible iris instead of fully closing eye. For UP clearly raise chin and iris above neutral. Rightward nose/face aim imageRIGHT, leftward aim imageLEFT, regardless of mask silhouette. Feet/waist/lowercape anchors fixed and alltips insideframe. No weapons/props/effects/shadows or designchanges.


## review.md

Create one horizontal animation strip for Codex pet `la-signora`, state `review`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 6 full-body frames in one left-to-right row on flat pure user-selected #00FF00. Treat the row as 6 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Use approved reference as ONLY design. La Signora human form: pale blonde side-part curls, ornate black half-mask covering CHARACTER LEFT eye (viewer RIGHT in front view); ONLY character right grey-blue eye visible (viewer LEFT). Never swap mask side or reveal hidden eye. Viewer-left red-black hair bow and gold jewels. Black/red dress, white stylized fur shoulder collar, burgundy cape lining, gold trim, red jewels, black long gloves, dark shoes. Keep original round face, head-body proportions, proud gentle smile, cel-anime style. Empty hands, no weapons, no transformation. Generate left and right movement independently; never mirror. Complete mask tips/curls/cape/skirt/shoes with ample margins. No text, checkerboard, effects, shadow or props.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Fine Japanese chibi anime linework, soft cel color, restrained gradients, pale skin and blush, grey-blue anime visible eye; white collar drawn as simplified fur tufts, never plush photography or 3D. Preserve reference proportions and design; only neutral stance and framing may change..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Ready-review loop: focused inspection of completed output with lean, blink, narrowed eyes, head tilt, or paw pose.

State requirements:
- Show review through lean, blink, narrowed eyes, head tilt, or paw/hand position.
- Do not add magnifying glasses, papers, code, UI, punctuation, symbols, or other new props unless they already exist in the base pet identity.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.

User-specific action: Six-frame inspection loop: hands remain low, head slightly forward, exposed eye scans subtly and pauses, then a small confirming nod. Distinct from hand-at-chin thinking; no props.


## running-left.md

Create one horizontal animation strip for Codex pet `la-signora`, state `running-left`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 8 full-body frames in one left-to-right row on flat pure user-selected #00FF00. Treat the row as 8 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Use approved reference as ONLY design. La Signora human form: pale blonde side-part curls, ornate black half-mask covering CHARACTER LEFT eye (viewer RIGHT in front view); ONLY character right grey-blue eye visible (viewer LEFT). Never swap mask side or reveal hidden eye. Viewer-left red-black hair bow and gold jewels. Black/red dress, white stylized fur shoulder collar, burgundy cape lining, gold trim, red jewels, black long gloves, dark shoes. Keep original round face, head-body proportions, proud gentle smile, cel-anime style. Empty hands, no weapons, no transformation. Generate left and right movement independently; never mirror. Complete mask tips/curls/cape/skirt/shoes with ample margins. No text, checkerboard, effects, shadow or props.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Fine Japanese chibi anime linework, soft cel color, restrained gradients, pale skin and blush, grey-blue anime visible eye; white collar drawn as simplified fur tufts, never plush photography or 3D. Preserve reference proportions and design; only neutral stance and framing may change..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Dragging-left loop: show directional movement to the left through body and limb poses only.

State requirements:
- Show directional drag movement to the left through body, limb, and prop movement only.
- The row must unmistakably face and travel left.
- The movement cadence must alternate visibly across the 8 frames instead of repeating one nearly static stride.
- Do not draw speed lines, dust clouds, floor shadows, motion trails, or detached motion effects.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.

User-specific action: Eight-frame independently drawn alternating small-step gait toward SCREEN LEFT. Upright elegant body, subdued bounce, cape/skirt lag. Three-quarter leftward view; preserve anatomical LEFT masked eye, never expose it. Do NOT mirror rightward frames.



## running-right.md

Create one horizontal animation strip for Codex pet `la-signora`, state `running-right`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 8 full-body frames in one left-to-right row on flat pure user-selected #00FF00. Treat the row as 8 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Use approved reference as ONLY design. La Signora human form: pale blonde side-part curls, ornate black half-mask covering CHARACTER LEFT eye (viewer RIGHT in front view); ONLY character right grey-blue eye visible (viewer LEFT). Never swap mask side or reveal hidden eye. Viewer-left red-black hair bow and gold jewels. Black/red dress, white stylized fur shoulder collar, burgundy cape lining, gold trim, red jewels, black long gloves, dark shoes. Keep original round face, head-body proportions, proud gentle smile, cel-anime style. Empty hands, no weapons, no transformation. Generate left and right movement independently; never mirror. Complete mask tips/curls/cape/skirt/shoes with ample margins. No text, checkerboard, effects, shadow or props.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Fine Japanese chibi anime linework, soft cel color, restrained gradients, pale skin and blush, grey-blue anime visible eye; white collar drawn as simplified fur tufts, never plush photography or 3D. Preserve reference proportions and design; only neutral stance and framing may change..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Dragging-right loop: show directional movement to the right through body and limb poses only.

State requirements:
- Show directional drag movement to the right through body, limb, and prop movement only.
- The row must unmistakably face and travel right.
- The movement cadence must alternate visibly across the 8 frames instead of repeating one nearly static stride.
- Do not draw speed lines, dust clouds, floor shadows, motion trails, or detached motion effects.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.

User-specific action: Eight-frame alternating small-step gait toward SCREEN RIGHT. Upright elegant body, subdued bounce, cape/skirt lag. Three-quarter rightward view; preserve anatomical LEFT masked eye, never expose it. Do not flip identity.


## running.md

Create one horizontal animation strip for Codex pet `la-signora`, state `running`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 6 full-body frames in one left-to-right row on flat pure user-selected #00FF00. Treat the row as 6 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Use approved reference as ONLY design. La Signora human form: pale blonde side-part curls, ornate black half-mask covering CHARACTER LEFT eye (viewer RIGHT in front view); ONLY character right grey-blue eye visible (viewer LEFT). Never swap mask side or reveal hidden eye. Viewer-left red-black hair bow and gold jewels. Black/red dress, white stylized fur shoulder collar, burgundy cape lining, gold trim, red jewels, black long gloves, dark shoes. Keep original round face, head-body proportions, proud gentle smile, cel-anime style. Empty hands, no weapons, no transformation. Generate left and right movement independently; never mirror. Complete mask tips/curls/cape/skirt/shoes with ample margins. No text, checkerboard, effects, shadow or props.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Fine Japanese chibi anime linework, soft cel color, restrained gradients, pale skin and blush, grey-blue anime visible eye; white collar drawn as simplified fur tufts, never plush photography or 3D. Preserve reference proportions and design; only neutral stance and framing may change..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Working loop: focused active-task processing, thinking, typing, scanning, or effortful concentration; not literal foot-running, jogging, sprinting, treadmill motion, raised knees, long steps, pumping arms, or directional travel.

State requirements:
- Show the pet actively working or processing, as if running a task: focused posture, busy hands or paws, purposeful bobbing, thinking motion, tool or prop motion only if already part of the pet identity, or other non-locomotion activity.
- Do not show literal foot-running, jogging, sprinting, treadmill motion, raised knees, long steps, pumping arms, directional travel, speed lines, dust clouds, floor shadows, motion trails, or detached motion effects.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.

User-specific action: Six-frame thoughtful work loop: gloved hand lightly at chin, focused visible eye, tiny nods. Feet planted, NOT foot-running. Controlled dignified expression.


## waiting.md

Create one horizontal animation strip for Codex pet `la-signora`, state `waiting`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 6 full-body frames in one left-to-right row on flat pure user-selected #00FF00. Treat the row as 6 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Use approved reference as ONLY design. La Signora human form: pale blonde side-part curls, ornate black half-mask covering CHARACTER LEFT eye (viewer RIGHT in front view); ONLY character right grey-blue eye visible (viewer LEFT). Never swap mask side or reveal hidden eye. Viewer-left red-black hair bow and gold jewels. Black/red dress, white stylized fur shoulder collar, burgundy cape lining, gold trim, red jewels, black long gloves, dark shoes. Keep original round face, head-body proportions, proud gentle smile, cel-anime style. Empty hands, no weapons, no transformation. Generate left and right movement independently; never mirror. Complete mask tips/curls/cape/skirt/shoes with ample margins. No text, checkerboard, effects, shadow or props.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Fine Japanese chibi anime linework, soft cel color, restrained gradients, pale skin and blush, grey-blue anime visible eye; white collar drawn as simplified fur tufts, never plush photography or 3D. Preserve reference proportions and design; only neutral stance and framing may change..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Needs-input loop: expectant asking pose for approval, help, or user input.

State requirements:
- Show that Codex needs approval, help, or user input through an expectant asking pose.
- Keep the motion patient and readable, without turning it into ordinary idle or review.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.

User-specific action: Six-frame quiet expectant loop: tiny head tilt, one gloved hand near waist, other palm gently open inviting response. Patient confident little smile, no impatience.


## waving.md

Create one horizontal animation strip for Codex pet `la-signora`, state `waving`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 4 full-body frames in one left-to-right row on flat pure user-selected #00FF00. Treat the row as 4 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Use approved reference as ONLY design. La Signora human form: pale blonde side-part curls, ornate black half-mask covering CHARACTER LEFT eye (viewer RIGHT in front view); ONLY character right grey-blue eye visible (viewer LEFT). Never swap mask side or reveal hidden eye. Viewer-left red-black hair bow and gold jewels. Black/red dress, white stylized fur shoulder collar, burgundy cape lining, gold trim, red jewels, black long gloves, dark shoes. Keep original round face, head-body proportions, proud gentle smile, cel-anime style. Empty hands, no weapons, no transformation. Generate left and right movement independently; never mirror. Complete mask tips/curls/cape/skirt/shoes with ample margins. No text, checkerboard, effects, shadow or props.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Fine Japanese chibi anime linework, soft cel color, restrained gradients, pale skin and blush, grey-blue anime visible eye; white collar drawn as simplified fur tufts, never plush photography or 3D. Preserve reference proportions and design; only neutral stance and framing may change..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Greeting loop: paw or limb down, raised, tilted, and returning in a friendly attention gesture.

State requirements:
- Show the greeting through paw, hand, wing, or limb pose only.
- Do not draw wave marks, motion arcs, lines, sparkles, symbols, or floating effects around the gesture.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.

User-specific action: Four poses: resting gloved hand, slowly raise hand, small graceful wave with a slight head tilt and smile, return toward rest. No gesture marks.

