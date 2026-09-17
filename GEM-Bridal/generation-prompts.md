## prompts\base-pet.md

Create one clean full-body reference sprite for Codex pet G.E.M. 婚纱版.

Pet identity: Use the supplied approved character as the ONLY appearance reference; no redesign. Preserve exact head/body ratio, rounded anime face, brown curled long hair and eyes, gold earrings, asymmetric white neckline on anatomical LEFT shoulder (viewer RIGHT in front view), silver-white structured corset with copper-brown patina at lower edge, long pleated white skirt and long attached veil. Preserve intentional scorched holes and ragged edges at their major positions; no new damage, flames or smoke. Gold microphone with black bands always held in anatomical RIGHT hand (viewer LEFT in front view); free anatomical LEFT hand holds skirt. Full-length gown always. Neutral base: gentle closed-mouth smile, upright relaxed stance, microphone below chest away from face. Entire veil and hem contained. No bouquets crown notes effects or ground shadows..
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Preserve exact refined Japanese anime chibi reference: fine linework, soft cel shading, hair highlights, pale gray and lavender-gray white fabric shadows, hand-painted metallic corset highlights. Do not exaggerate chibi proportions beyond reference..


Place a single centered pose on a perfectly flat pure blue #0000FF chroma-key background. Keep the full pet visible, compact, readable at 192x208, and easy to animate. Preserve approved reference identity cues. No scenery, text, borders, checkerboard transparency, shadows, glows, detached effects, or extra props. Keep #0000FF and close colors out of the pet, props, highlights, and effects.


## prompts\look-anchor-repairs\000.md

Repair one cardinal anchor for Codex pet `gem-bridal`: `000` means looking up.

Use the canonical base, completed standard contact sheet, approved cardinal-strip cells, and `qa/look-mechanics.md` for identity, scale, registration, and pet-specific gaze mechanics. Keep the face broadly frontal and point the eyes and natural head mechanism toward the TOP edge. Screen coordinates are viewer-relative.

Output one centered complete full-body pose on a flat pure blue #0000FF background with generous padding. Keep the feet/base and lower body registered to the approved anchors. The requested cardinal must be unmistakable at final 192x208 display size.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement eyes, labels, arrows, guide marks, shadows, scenery, detached effects, or chroma-key colors inside the pet.


## prompts\look-anchor-repairs\090.md

Repair one cardinal anchor for Codex pet `gem-bridal`: `090` means looking right.

Use the canonical base, completed standard contact sheet, approved cardinal-strip cells, and `qa/look-mechanics.md` for identity, scale, registration, and pet-specific gaze mechanics. Put the nose tip, pupils, face surface, or natural aiming feature on the screen-right side of the head center. Screen coordinates are viewer-relative.

Output one centered complete full-body pose on a flat pure blue #0000FF background with generous padding. Keep the feet/base and lower body registered to the approved anchors. The requested cardinal must be unmistakable at final 192x208 display size.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement eyes, labels, arrows, guide marks, shadows, scenery, detached effects, or chroma-key colors inside the pet.


## prompts\look-anchor-repairs\180.md

Repair one cardinal anchor for Codex pet `gem-bridal`: `180` means looking down.

Use the canonical base, completed standard contact sheet, approved cardinal-strip cells, and `qa/look-mechanics.md` for identity, scale, registration, and pet-specific gaze mechanics. Keep the face broadly frontal and point the eyes and natural head mechanism toward the BOTTOM edge. Screen coordinates are viewer-relative.

Output one centered complete full-body pose on a flat pure blue #0000FF background with generous padding. Keep the feet/base and lower body registered to the approved anchors. The requested cardinal must be unmistakable at final 192x208 display size.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement eyes, labels, arrows, guide marks, shadows, scenery, detached effects, or chroma-key colors inside the pet.


## prompts\look-anchor-repairs\270.md

Repair one cardinal anchor for Codex pet `gem-bridal`: `270` means looking left.

Use the canonical base, completed standard contact sheet, approved cardinal-strip cells, and `qa/look-mechanics.md` for identity, scale, registration, and pet-specific gaze mechanics. Put the nose tip, pupils, face surface, or natural aiming feature on the screen-left side of the head center. Screen coordinates are viewer-relative.

Output one centered complete full-body pose on a flat pure blue #0000FF background with generous padding. Keep the feet/base and lower body registered to the approved anchors. The requested cardinal must be unmistakable at final 192x208 display size.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement eyes, labels, arrows, guide marks, shadows, scenery, detached effects, or chroma-key colors inside the pet.


## prompts\look-cardinals.md

Create one horizontal four-cardinal anchor strip for Codex pet `gem-bridal`.

Use the attached canonical base, completed standard contact sheet, and layout guide for exact identity, style, scale, baseline, face construction, materials, palette, markings, props, and spacing. Read `qa/look-mechanics.md` and use the pet's natural gaze mechanism.

Output exactly four centered complete full-body poses in this exact left-to-right order: `000 up`, `090 screen-right`, `180 down`, `270 screen-left`. Screen-left and screen-right always mean the viewer's image edges, never the character's own left or right.

For `000`, keep the face broadly frontal and point the eyes and natural head mechanism toward the TOP edge. For `090`, put the nose tip, pupils, face surface, or natural aiming feature on the screen-right side of the head center. For `180`, keep the face broadly frontal and point toward the BOTTOM edge. For `270`, apply the inverse screen-left landmark rule. Every cardinal must be unmistakable without labels.

Place one pose in each invisible equal-width slot on a flat pure blue #0000FF background with generous padding. Keep scale, feet/base, lower body, and registration consistent across all four slots.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement eyes, labels, degree text, arrows, boxes, guide marks, shadows, scenery, detached effects, or chroma-key colors inside the pet.


## prompts\row-retries\failed.md

Create Codex pet row `failed` for `gem-bridal`: exactly 8 full-body frames in one horizontal strip on flat pure blue #0000FF.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Use the supplied approved character as the ONLY appearance reference; no redesign. Preserve exact head/body ratio, rounded anime face, brown curled long hair and eyes, gold earrings, asymmetric white neckline on anatomical LEFT shoulder (viewer RIGHT in front view), silver-white structured corset with copper-brown patina at lower edge, long pleated white skirt and long attached veil. Preserve intentional scorched holes and ragged edges at their major positions; no new damage, flames or smoke. Gold microphone with black bands always held in anatomical RIGHT hand (viewer LEFT in front view); free anatomical LEFT hand holds skirt. Full-length gown always. Neutral base: gentle closed-mouth smile, upright relaxed stance, microphone below chest away from face. Entire veil and hem contained. No bouquets crown notes effects or ground shadows.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Blocked/failed loop: slumped or deflated reaction with sad or closed eyes.

State requirements:
- Show failure through slumped pose, drooping ears/limbs, closed or sad eyes, and lower body position.
- Tears, small smoke puffs, or tiny stars are allowed only if attached to or overlapping the pet silhouette and kept inside the same frame slot.
- Do not draw red X marks, floating symbols, detached stars, separated smoke clouds, falling tear drops, dust, or other loose effects.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #0000FF colors in the pet.

User-approved choreography (takes precedence over generic action): Restrained disappointment: head lowers a little, smile briefly fades, eyes soften, then gaze lifts and composure returns. No crying, tears, symbols or added effects. Microphone in right hand and gown/veil unchanged.
Do not simplify the approved costume into an ordinary wedding dress. Keep scorch-edge holes, copper-brown corset patina and inner white fabric distinct; no new cracks, transparent bands, props, floor shadow, smoke, fire, petals, notes or halo. Keep the original refined anime face and original head/body ratio.


## prompts\row-retries\idle.md

Create Codex pet row `idle` for `gem-bridal`: exactly 6 full-body frames in one horizontal strip on flat pure blue #0000FF.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Use the supplied approved character as the ONLY appearance reference; no redesign. Preserve exact head/body ratio, rounded anime face, brown curled long hair and eyes, gold earrings, asymmetric white neckline on anatomical LEFT shoulder (viewer RIGHT in front view), silver-white structured corset with copper-brown patina at lower edge, long pleated white skirt and long attached veil. Preserve intentional scorched holes and ragged edges at their major positions; no new damage, flames or smoke. Gold microphone with black bands always held in anatomical RIGHT hand (viewer LEFT in front view); free anatomical LEFT hand holds skirt. Full-length gown always. Neutral base: gentle closed-mouth smile, upright relaxed stance, microphone below chest away from face. Entire veil and hem contained. No bouquets crown notes effects or ground shadows.. Preserve silhouette, face, palette, material, proportions, markings, and props.

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

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #0000FF colors in the pet.

User-approved choreography (takes precedence over generic action): Quiet breathing, one gentle blink, tiny curl and attached veil sway. Right-hand microphone below chest, left hand lightly holds skirt throughout. No singing or waving. First/last pose close.
Do not simplify the approved costume into an ordinary wedding dress. Keep scorch-edge holes, copper-brown corset patina and inner white fabric distinct; no new cracks, transparent bands, props, floor shadow, smoke, fire, petals, notes or halo. Keep the original refined anime face and original head/body ratio.


## prompts\row-retries\jumping.md

Create Codex pet row `jumping` for `gem-bridal`: exactly 5 full-body frames in one horizontal strip on flat pure blue #0000FF.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Use the supplied approved character as the ONLY appearance reference; no redesign. Preserve exact head/body ratio, rounded anime face, brown curled long hair and eyes, gold earrings, asymmetric white neckline on anatomical LEFT shoulder (viewer RIGHT in front view), silver-white structured corset with copper-brown patina at lower edge, long pleated white skirt and long attached veil. Preserve intentional scorched holes and ragged edges at their major positions; no new damage, flames or smoke. Gold microphone with black bands always held in anatomical RIGHT hand (viewer LEFT in front view); free anatomical LEFT hand holds skirt. Full-length gown always. Neutral base: gentle closed-mouth smile, upright relaxed stance, microphone below chest away from face. Entire veil and hem contained. No bouquets crown notes effects or ground shadows.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Hover jump loop: anticipation, lift, airborne peak, descent, and settle through body height.

State requirements:
- Show the jump through pose and vertical body position only: anticipation, lift, airborne peak, descent, settle.
- Do not draw ground shadows, contact shadows, drop shadows, oval shadows, landing marks, dust, smears, bounce pads, or motion marks under the pet.
- Keep the background outside the pet perfectly flat chroma key with no darker key-colored patches.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #0000FF colors in the pet.

User-approved choreography (takes precedence over generic action): Small elegant hop: anticipate by gently lifting skirt with left hand, rise, modest apex with hem slightly spreading, descend, soft settle. Microphone secure in right hand. Veil follows naturally and stays fully within each slot. Same body scale, visible vertical lift, compact range.
Do not simplify the approved costume into an ordinary wedding dress. Keep scorch-edge holes, copper-brown corset patina and inner white fabric distinct; no new cracks, transparent bands, props, floor shadow, smoke, fire, petals, notes or halo. Keep the original refined anime face and original head/body ratio.


## prompts\row-retries\look-row-10.md

Create Codex v2 pet look row 10 for `gem-bridal` as exactly 8 full-body frames in this order: 180, 202.5, 225, 247.5, 270, 292.5, 315, 337.5.

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

Use a flat pure blue #0000FF background. One complete unclipped pose per invisible slot. No whole-sprite rotation, replacement eyes, labels, guide marks, shadows, glows, scenery, detached effects, or #0000FF colors in the pet.


## prompts\row-retries\look-row-9.md

Create Codex v2 pet look row 9 for `gem-bridal` as exactly 8 full-body frames in this order: 000, 022.5, 045, 067.5, 090, 112.5, 135, 157.5.

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

Use a flat pure blue #0000FF background. One complete unclipped pose per invisible slot. No whole-sprite rotation, replacement eyes, labels, guide marks, shadows, glows, scenery, detached effects, or #0000FF colors in the pet.


## prompts\row-retries\review.md

Create Codex pet row `review` for `gem-bridal`: exactly 6 full-body frames in one horizontal strip on flat pure blue #0000FF.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Use the supplied approved character as the ONLY appearance reference; no redesign. Preserve exact head/body ratio, rounded anime face, brown curled long hair and eyes, gold earrings, asymmetric white neckline on anatomical LEFT shoulder (viewer RIGHT in front view), silver-white structured corset with copper-brown patina at lower edge, long pleated white skirt and long attached veil. Preserve intentional scorched holes and ragged edges at their major positions; no new damage, flames or smoke. Gold microphone with black bands always held in anatomical RIGHT hand (viewer LEFT in front view); free anatomical LEFT hand holds skirt. Full-length gown always. Neutral base: gentle closed-mouth smile, upright relaxed stance, microphone below chest away from face. Entire veil and hem contained. No bouquets crown notes effects or ground shadows.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Ready-review loop: focused inspection of completed output with lean, blink, narrowed eyes, head tilt, or paw pose.

State requirements:
- Show review through lean, blink, narrowed eyes, head tilt, or paw/hand position.
- Do not add magnifying glasses, papers, code, UI, punctuation, symbols, or other new props unless they already exist in the base pet identity.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #0000FF colors in the pet.

User-approved choreography (takes precedence over generic action): Inspect completed result: slight forward head lean, eyes carefully observe, pause then small confirming nod and pleased gentle smile. Free left hand near skirt; right-hand microphone steady. Distinct from chin-thinking work pose and idle.
Do not simplify the approved costume into an ordinary wedding dress. Keep scorch-edge holes, copper-brown corset patina and inner white fabric distinct; no new cracks, transparent bands, props, floor shadow, smoke, fire, petals, notes or halo. Keep the original refined anime face and original head/body ratio.


## prompts\row-retries\running-left.md

Create Codex pet row `running-left` for `gem-bridal`: exactly 8 full-body frames in one horizontal strip on flat pure blue #0000FF.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Use the supplied approved character as the ONLY appearance reference; no redesign. Preserve exact head/body ratio, rounded anime face, brown curled long hair and eyes, gold earrings, asymmetric white neckline on anatomical LEFT shoulder (viewer RIGHT in front view), silver-white structured corset with copper-brown patina at lower edge, long pleated white skirt and long attached veil. Preserve intentional scorched holes and ragged edges at their major positions; no new damage, flames or smoke. Gold microphone with black bands always held in anatomical RIGHT hand (viewer LEFT in front view); free anatomical LEFT hand holds skirt. Full-length gown always. Neutral base: gentle closed-mouth smile, upright relaxed stance, microphone below chest away from face. Entire veil and hem contained. No bouquets crown notes effects or ground shadows.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Dragging-left loop: show directional movement to the left through body and limb poses only.

State requirements:
- Show directional drag movement to the left through body, limb, and prop movement only.
- The row must unmistakably face and travel left.
- The movement cadence must alternate visibly across the 8 frames instead of repeating one nearly static stride.
- Do not draw speed lines, dust clouds, floor shadows, motion trails, or detached motion effects.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #0000FF colors in the pet.

User-approved choreography (takes precedence over generic action): Face and move screen-LEFT in light tiny steps. Anatomical left hand lifts gown slightly; anatomical right hand securely holds microphone. Preserve shoulder construction and microphone hand; this is NOT a mirrored design. Alternating toe glimpses and hem lift convey actual steps, full-length gown unchanged. Small body bob with curls/veil lag, eight phases with two alternating foot contacts.
Do not simplify the approved costume into an ordinary wedding dress. Keep scorch-edge holes, copper-brown corset patina and inner white fabric distinct; no new cracks, transparent bands, props, floor shadow, smoke, fire, petals, notes or halo. Keep the original refined anime face and original head/body ratio.


## prompts\row-retries\running-right.md

Create Codex pet row `running-right` for `gem-bridal`: exactly 8 full-body frames in one horizontal strip on flat pure blue #0000FF.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Use the supplied approved character as the ONLY appearance reference; no redesign. Preserve exact head/body ratio, rounded anime face, brown curled long hair and eyes, gold earrings, asymmetric white neckline on anatomical LEFT shoulder (viewer RIGHT in front view), silver-white structured corset with copper-brown patina at lower edge, long pleated white skirt and long attached veil. Preserve intentional scorched holes and ragged edges at their major positions; no new damage, flames or smoke. Gold microphone with black bands always held in anatomical RIGHT hand (viewer LEFT in front view); free anatomical LEFT hand holds skirt. Full-length gown always. Neutral base: gentle closed-mouth smile, upright relaxed stance, microphone below chest away from face. Entire veil and hem contained. No bouquets crown notes effects or ground shadows.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Dragging-right loop: show directional movement to the right through body and limb poses only.

State requirements:
- Show directional drag movement to the right through body, limb, and prop movement only.
- The row must unmistakably face and travel right.
- The movement cadence must alternate visibly across the 8 frames instead of repeating one nearly static stride.
- Do not draw speed lines, dust clouds, floor shadows, motion trails, or detached motion effects.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #0000FF colors in the pet.

User-approved choreography (takes precedence over generic action): Face and move screen-RIGHT in light tiny steps. Anatomical left hand lifts gown slightly; anatomical right hand securely holds microphone. Alternating toe glimpses and hem lift convey actual steps; full-length gown unchanged. Small body bob with curls/veil lag, eight phases with two alternating foot contacts. Do not mirror shoulder or handedness.
Do not simplify the approved costume into an ordinary wedding dress. Keep scorch-edge holes, copper-brown corset patina and inner white fabric distinct; no new cracks, transparent bands, props, floor shadow, smoke, fire, petals, notes or halo. Keep the original refined anime face and original head/body ratio.


## prompts\row-retries\running.md

Create Codex pet row `running` for `gem-bridal`: exactly 6 full-body frames in one horizontal strip on flat pure blue #0000FF.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Use the supplied approved character as the ONLY appearance reference; no redesign. Preserve exact head/body ratio, rounded anime face, brown curled long hair and eyes, gold earrings, asymmetric white neckline on anatomical LEFT shoulder (viewer RIGHT in front view), silver-white structured corset with copper-brown patina at lower edge, long pleated white skirt and long attached veil. Preserve intentional scorched holes and ragged edges at their major positions; no new damage, flames or smoke. Gold microphone with black bands always held in anatomical RIGHT hand (viewer LEFT in front view); free anatomical LEFT hand holds skirt. Full-length gown always. Neutral base: gentle closed-mouth smile, upright relaxed stance, microphone below chest away from face. Entire veil and hem contained. No bouquets crown notes effects or ground shadows.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Working loop: focused active-task processing, thinking, typing, scanning, or effortful concentration; not literal foot-running, jogging, sprinting, treadmill motion, raised knees, long steps, pumping arms, or directional travel.

State requirements:
- Show the pet actively working or processing, as if running a task: focused posture, busy hands or paws, purposeful bobbing, thinking motion, tool or prop motion only if already part of the pet identity, or other non-locomotion activity.
- Do not show literal foot-running, jogging, sprinting, treadmill motion, raised knees, long steps, pumping arms, directional travel, speed lines, dust clouds, floor shadows, motion trails, or detached motion effects.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #0000FF colors in the pet.

User-approved choreography (takes precedence over generic action): WORK/THINKING, planted lower body. Right-hand microphone slightly lowered. Free left hand comes gently to chin, focused eyes and small thoughtful nod. No walking or continuous singing. Preserve gown/veil and gold microphone black bands.
Do not simplify the approved costume into an ordinary wedding dress. Keep scorch-edge holes, copper-brown corset patina and inner white fabric distinct; no new cracks, transparent bands, props, floor shadow, smoke, fire, petals, notes or halo. Keep the original refined anime face and original head/body ratio.


## prompts\row-retries\waiting.md

Create Codex pet row `waiting` for `gem-bridal`: exactly 6 full-body frames in one horizontal strip on flat pure blue #0000FF.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Use the supplied approved character as the ONLY appearance reference; no redesign. Preserve exact head/body ratio, rounded anime face, brown curled long hair and eyes, gold earrings, asymmetric white neckline on anatomical LEFT shoulder (viewer RIGHT in front view), silver-white structured corset with copper-brown patina at lower edge, long pleated white skirt and long attached veil. Preserve intentional scorched holes and ragged edges at their major positions; no new damage, flames or smoke. Gold microphone with black bands always held in anatomical RIGHT hand (viewer LEFT in front view); free anatomical LEFT hand holds skirt. Full-length gown always. Neutral base: gentle closed-mouth smile, upright relaxed stance, microphone below chest away from face. Entire veil and hem contained. No bouquets crown notes effects or ground shadows.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Needs-input loop: expectant asking pose for approval, help, or user input.

State requirements:
- Show that Codex needs approval, help, or user input through an expectant asking pose.
- Keep the motion patient and readable, without turning it into ordinary idle or review.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #0000FF colors in the pet.

User-approved choreography (takes precedence over generic action): Expectant gentle head tilt and slight upper-body lean toward user, warm attentive eyes, left hand rests on skirt, microphone secure in right hand. Quiet motion distinct from ordinary idle, awaiting a response.
Do not simplify the approved costume into an ordinary wedding dress. Keep scorch-edge holes, copper-brown corset patina and inner white fabric distinct; no new cracks, transparent bands, props, floor shadow, smoke, fire, petals, notes or halo. Keep the original refined anime face and original head/body ratio.


## prompts\row-retries\waving.md

Create Codex pet row `waving` for `gem-bridal`: exactly 4 full-body frames in one horizontal strip on flat pure blue #0000FF.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Use the supplied approved character as the ONLY appearance reference; no redesign. Preserve exact head/body ratio, rounded anime face, brown curled long hair and eyes, gold earrings, asymmetric white neckline on anatomical LEFT shoulder (viewer RIGHT in front view), silver-white structured corset with copper-brown patina at lower edge, long pleated white skirt and long attached veil. Preserve intentional scorched holes and ragged edges at their major positions; no new damage, flames or smoke. Gold microphone with black bands always held in anatomical RIGHT hand (viewer LEFT in front view); free anatomical LEFT hand holds skirt. Full-length gown always. Neutral base: gentle closed-mouth smile, upright relaxed stance, microphone below chest away from face. Entire veil and hem contained. No bouquets crown notes effects or ground shadows.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`.

Action: Greeting loop: paw or limb down, raised, tilted, and returning in a friendly attention gesture.

State requirements:
- Show the greeting through paw, hand, wing, or limb pose only.
- Do not draw wave marks, motion arcs, lines, sparkles, symbols, or floating effects around the gesture.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #0000FF colors in the pet.

User-approved choreography (takes precedence over generic action): Left free hand releases skirt, raises for a small elegant wave with slight head tilt and sweet smile, then returns to skirt. Right hand holds microphone steady below chest. Four frames: rest, raise, gentle wave, return.
Do not simplify the approved costume into an ordinary wedding dress. Keep scorch-edge holes, copper-brown corset patina and inner white fabric distinct; no new cracks, transparent bands, props, floor shadow, smoke, fire, petals, notes or halo. Keep the original refined anime face and original head/body ratio.


## prompts\rows\failed.md

Create one horizontal animation strip for Codex pet `gem-bridal`, state `failed`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 8 full-body frames in one left-to-right row on flat pure blue #0000FF. Treat the row as 8 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Use the supplied approved character as the ONLY appearance reference; no redesign. Preserve exact head/body ratio, rounded anime face, brown curled long hair and eyes, gold earrings, asymmetric white neckline on anatomical LEFT shoulder (viewer RIGHT in front view), silver-white structured corset with copper-brown patina at lower edge, long pleated white skirt and long attached veil. Preserve intentional scorched holes and ragged edges at their major positions; no new damage, flames or smoke. Gold microphone with black bands always held in anatomical RIGHT hand (viewer LEFT in front view); free anatomical LEFT hand holds skirt. Full-length gown always. Neutral base: gentle closed-mouth smile, upright relaxed stance, microphone below chest away from face. Entire veil and hem contained. No bouquets crown notes effects or ground shadows.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Preserve exact refined Japanese anime chibi reference: fine linework, soft cel shading, hair highlights, pale gray and lavender-gray white fabric shadows, hand-painted metallic corset highlights. Do not exaggerate chibi proportions beyond reference..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Blocked/failed loop: slumped or deflated reaction with sad or closed eyes.

State requirements:
- Show failure through slumped pose, drooping ears/limbs, closed or sad eyes, and lower body position.
- Tears, small smoke puffs, or tiny stars are allowed only if attached to or overlapping the pet silhouette and kept inside the same frame slot.
- Do not draw red X marks, floating symbols, detached stars, separated smoke clouds, falling tear drops, dust, or other loose effects.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.

User-approved choreography (takes precedence over generic action): Restrained disappointment: head lowers a little, smile briefly fades, eyes soften, then gaze lifts and composure returns. No crying, tears, symbols or added effects. Microphone in right hand and gown/veil unchanged.
Do not simplify the approved costume into an ordinary wedding dress. Keep scorch-edge holes, copper-brown corset patina and inner white fabric distinct; no new cracks, transparent bands, props, floor shadow, smoke, fire, petals, notes or halo. Keep the original refined anime face and original head/body ratio.


## prompts\rows\idle.md

Create one horizontal animation strip for Codex pet `gem-bridal`, state `idle`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 6 full-body frames in one left-to-right row on flat pure blue #0000FF. Treat the row as 6 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Use the supplied approved character as the ONLY appearance reference; no redesign. Preserve exact head/body ratio, rounded anime face, brown curled long hair and eyes, gold earrings, asymmetric white neckline on anatomical LEFT shoulder (viewer RIGHT in front view), silver-white structured corset with copper-brown patina at lower edge, long pleated white skirt and long attached veil. Preserve intentional scorched holes and ragged edges at their major positions; no new damage, flames or smoke. Gold microphone with black bands always held in anatomical RIGHT hand (viewer LEFT in front view); free anatomical LEFT hand holds skirt. Full-length gown always. Neutral base: gentle closed-mouth smile, upright relaxed stance, microphone below chest away from face. Entire veil and hem contained. No bouquets crown notes effects or ground shadows.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Preserve exact refined Japanese anime chibi reference: fine linework, soft cel shading, hair highlights, pale gray and lavender-gray white fabric shadows, hand-painted metallic corset highlights. Do not exaggerate chibi proportions beyond reference..
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

User-approved choreography (takes precedence over generic action): Quiet breathing, one gentle blink, tiny curl and attached veil sway. Right-hand microphone below chest, left hand lightly holds skirt throughout. No singing or waving. First/last pose close.
Do not simplify the approved costume into an ordinary wedding dress. Keep scorch-edge holes, copper-brown corset patina and inner white fabric distinct; no new cracks, transparent bands, props, floor shadow, smoke, fire, petals, notes or halo. Keep the original refined anime face and original head/body ratio.


## prompts\rows\jumping.md

Create one horizontal animation strip for Codex pet `gem-bridal`, state `jumping`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 5 full-body frames in one left-to-right row on flat pure blue #0000FF. Treat the row as 5 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Use the supplied approved character as the ONLY appearance reference; no redesign. Preserve exact head/body ratio, rounded anime face, brown curled long hair and eyes, gold earrings, asymmetric white neckline on anatomical LEFT shoulder (viewer RIGHT in front view), silver-white structured corset with copper-brown patina at lower edge, long pleated white skirt and long attached veil. Preserve intentional scorched holes and ragged edges at their major positions; no new damage, flames or smoke. Gold microphone with black bands always held in anatomical RIGHT hand (viewer LEFT in front view); free anatomical LEFT hand holds skirt. Full-length gown always. Neutral base: gentle closed-mouth smile, upright relaxed stance, microphone below chest away from face. Entire veil and hem contained. No bouquets crown notes effects or ground shadows.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Preserve exact refined Japanese anime chibi reference: fine linework, soft cel shading, hair highlights, pale gray and lavender-gray white fabric shadows, hand-painted metallic corset highlights. Do not exaggerate chibi proportions beyond reference..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Hover jump loop: anticipation, lift, airborne peak, descent, and settle through body height.

State requirements:
- Show the jump through pose and vertical body position only: anticipation, lift, airborne peak, descent, settle.
- Do not draw ground shadows, contact shadows, drop shadows, oval shadows, landing marks, dust, smears, bounce pads, or motion marks under the pet.
- Keep the background outside the pet perfectly flat chroma key with no darker key-colored patches.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.

User-approved choreography (takes precedence over generic action): Small elegant hop: anticipate by gently lifting skirt with left hand, rise, modest apex with hem slightly spreading, descend, soft settle. Microphone secure in right hand. Veil follows naturally and stays fully within each slot. Same body scale, visible vertical lift, compact range.
Do not simplify the approved costume into an ordinary wedding dress. Keep scorch-edge holes, copper-brown corset patina and inner white fabric distinct; no new cracks, transparent bands, props, floor shadow, smoke, fire, petals, notes or halo. Keep the original refined anime face and original head/body ratio.


## prompts\rows\look-row-10.md

Create one horizontal look-direction strip for Codex pet `gem-bridal`, atlas row 10.

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

Place one centered pose in each invisible equal-width slot on flat pure blue #0000FF. Change only the natural parts needed to express gaze: eyes, eyelids, head, face, neck, upper body, appendages, and constrained prop follow-through. Keep identity, silhouette, materials, palette, markings, and props consistent.

ROW-BOUNDARY LOCK: 180 must continue directly from row 9's 157.5, matching its body size, baseline, planted anchor, expression, and construction. 337.5 must be one even 22.5-degree step before 000: nearly up-facing while remaining on the overall left-hand arc. Do not distort pupils, nose, or body geometry merely to exaggerate the subtle horizontal component.

PRE-RETURN CHECK: reject this result if it does not contain eight separated pose groups in the required order; neighboring poses overlap; foreground is cropped at the outer canvas edge; any frame changes sprite scale, body or head size, baseline, or planted-body position; the row visibly reverses into the wrong half of the loop; or 180 does not continue from 157.5 or 337.5 does not flow evenly into 000. Minor intermediate pupil or nose deviations are not rejection reasons. Exact cell cropping, resizing, and recentering happen deterministically after generation.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement/googly eyes, labels, degree text, arrows, clocks, grids, shadows, glows, scenery, detached effects, or chroma-key colors inside the pet.


## prompts\rows\look-row-9.md

Create one horizontal look-direction strip for Codex pet `gem-bridal`, atlas row 9.

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

Place one centered pose in each invisible equal-width slot on flat pure blue #0000FF. Change only the natural parts needed to express gaze: eyes, eyelids, head, face, neck, upper body, appendages, and constrained prop follow-through. Keep identity, silhouette, materials, palette, markings, and props consistent.

ROW-BOUNDARY LOCK: 157.5 must be one even 22.5-degree step before 180. Match the approved 180 pose's body size, baseline, planted anchor, expression, and construction. Preserve the overall right-hand arc, but do not distort pupils, nose, or body geometry merely to exaggerate the subtle horizontal component.

PRE-RETURN CHECK: reject this result if it does not contain eight separated pose groups in the required order; neighboring poses overlap; foreground is cropped at the outer canvas edge; any frame changes sprite scale, body or head size, baseline, or planted-body position; the row visibly reverses into the wrong half of the loop; or 157.5 does not flow evenly into 180. Minor intermediate pupil or nose deviations are not rejection reasons. Exact cell cropping, resizing, and recentering happen deterministically after generation.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement/googly eyes, labels, degree text, arrows, clocks, grids, shadows, glows, scenery, detached effects, or chroma-key colors inside the pet.


## prompts\rows\review.md

Create one horizontal animation strip for Codex pet `gem-bridal`, state `review`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 6 full-body frames in one left-to-right row on flat pure blue #0000FF. Treat the row as 6 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Use the supplied approved character as the ONLY appearance reference; no redesign. Preserve exact head/body ratio, rounded anime face, brown curled long hair and eyes, gold earrings, asymmetric white neckline on anatomical LEFT shoulder (viewer RIGHT in front view), silver-white structured corset with copper-brown patina at lower edge, long pleated white skirt and long attached veil. Preserve intentional scorched holes and ragged edges at their major positions; no new damage, flames or smoke. Gold microphone with black bands always held in anatomical RIGHT hand (viewer LEFT in front view); free anatomical LEFT hand holds skirt. Full-length gown always. Neutral base: gentle closed-mouth smile, upright relaxed stance, microphone below chest away from face. Entire veil and hem contained. No bouquets crown notes effects or ground shadows.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Preserve exact refined Japanese anime chibi reference: fine linework, soft cel shading, hair highlights, pale gray and lavender-gray white fabric shadows, hand-painted metallic corset highlights. Do not exaggerate chibi proportions beyond reference..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Ready-review loop: focused inspection of completed output with lean, blink, narrowed eyes, head tilt, or paw pose.

State requirements:
- Show review through lean, blink, narrowed eyes, head tilt, or paw/hand position.
- Do not add magnifying glasses, papers, code, UI, punctuation, symbols, or other new props unless they already exist in the base pet identity.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.

User-approved choreography (takes precedence over generic action): Inspect completed result: slight forward head lean, eyes carefully observe, pause then small confirming nod and pleased gentle smile. Free left hand near skirt; right-hand microphone steady. Distinct from chin-thinking work pose and idle.
Do not simplify the approved costume into an ordinary wedding dress. Keep scorch-edge holes, copper-brown corset patina and inner white fabric distinct; no new cracks, transparent bands, props, floor shadow, smoke, fire, petals, notes or halo. Keep the original refined anime face and original head/body ratio.


## prompts\rows\running-left.md

Create one horizontal animation strip for Codex pet `gem-bridal`, state `running-left`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 8 full-body frames in one left-to-right row on flat pure blue #0000FF. Treat the row as 8 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Use the supplied approved character as the ONLY appearance reference; no redesign. Preserve exact head/body ratio, rounded anime face, brown curled long hair and eyes, gold earrings, asymmetric white neckline on anatomical LEFT shoulder (viewer RIGHT in front view), silver-white structured corset with copper-brown patina at lower edge, long pleated white skirt and long attached veil. Preserve intentional scorched holes and ragged edges at their major positions; no new damage, flames or smoke. Gold microphone with black bands always held in anatomical RIGHT hand (viewer LEFT in front view); free anatomical LEFT hand holds skirt. Full-length gown always. Neutral base: gentle closed-mouth smile, upright relaxed stance, microphone below chest away from face. Entire veil and hem contained. No bouquets crown notes effects or ground shadows.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Preserve exact refined Japanese anime chibi reference: fine linework, soft cel shading, hair highlights, pale gray and lavender-gray white fabric shadows, hand-painted metallic corset highlights. Do not exaggerate chibi proportions beyond reference..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Dragging-left loop: show directional movement to the left through body and limb poses only.

State requirements:
- Show directional drag movement to the left through body, limb, and prop movement only.
- The row must unmistakably face and travel left.
- The movement cadence must alternate visibly across the 8 frames instead of repeating one nearly static stride.
- Do not draw speed lines, dust clouds, floor shadows, motion trails, or detached motion effects.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.

User-approved choreography (takes precedence over generic action): Face and move screen-LEFT in light tiny steps. Anatomical left hand lifts gown slightly; anatomical right hand securely holds microphone. Preserve shoulder construction and microphone hand; this is NOT a mirrored design. Alternating toe glimpses and hem lift convey actual steps, full-length gown unchanged. Small body bob with curls/veil lag, eight phases with two alternating foot contacts.
Do not simplify the approved costume into an ordinary wedding dress. Keep scorch-edge holes, copper-brown corset patina and inner white fabric distinct; no new cracks, transparent bands, props, floor shadow, smoke, fire, petals, notes or halo. Keep the original refined anime face and original head/body ratio.


## prompts\rows\running-right.md

Create one horizontal animation strip for Codex pet `gem-bridal`, state `running-right`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 8 full-body frames in one left-to-right row on flat pure blue #0000FF. Treat the row as 8 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Use the supplied approved character as the ONLY appearance reference; no redesign. Preserve exact head/body ratio, rounded anime face, brown curled long hair and eyes, gold earrings, asymmetric white neckline on anatomical LEFT shoulder (viewer RIGHT in front view), silver-white structured corset with copper-brown patina at lower edge, long pleated white skirt and long attached veil. Preserve intentional scorched holes and ragged edges at their major positions; no new damage, flames or smoke. Gold microphone with black bands always held in anatomical RIGHT hand (viewer LEFT in front view); free anatomical LEFT hand holds skirt. Full-length gown always. Neutral base: gentle closed-mouth smile, upright relaxed stance, microphone below chest away from face. Entire veil and hem contained. No bouquets crown notes effects or ground shadows.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Preserve exact refined Japanese anime chibi reference: fine linework, soft cel shading, hair highlights, pale gray and lavender-gray white fabric shadows, hand-painted metallic corset highlights. Do not exaggerate chibi proportions beyond reference..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Dragging-right loop: show directional movement to the right through body and limb poses only.

State requirements:
- Show directional drag movement to the right through body, limb, and prop movement only.
- The row must unmistakably face and travel right.
- The movement cadence must alternate visibly across the 8 frames instead of repeating one nearly static stride.
- Do not draw speed lines, dust clouds, floor shadows, motion trails, or detached motion effects.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.

User-approved choreography (takes precedence over generic action): Face and move screen-RIGHT in light tiny steps. Anatomical left hand lifts gown slightly; anatomical right hand securely holds microphone. Alternating toe glimpses and hem lift convey actual steps; full-length gown unchanged. Small body bob with curls/veil lag, eight phases with two alternating foot contacts. Do not mirror shoulder or handedness.
Do not simplify the approved costume into an ordinary wedding dress. Keep scorch-edge holes, copper-brown corset patina and inner white fabric distinct; no new cracks, transparent bands, props, floor shadow, smoke, fire, petals, notes or halo. Keep the original refined anime face and original head/body ratio.


## prompts\rows\running.md

Create one horizontal animation strip for Codex pet `gem-bridal`, state `running`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 6 full-body frames in one left-to-right row on flat pure blue #0000FF. Treat the row as 6 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Use the supplied approved character as the ONLY appearance reference; no redesign. Preserve exact head/body ratio, rounded anime face, brown curled long hair and eyes, gold earrings, asymmetric white neckline on anatomical LEFT shoulder (viewer RIGHT in front view), silver-white structured corset with copper-brown patina at lower edge, long pleated white skirt and long attached veil. Preserve intentional scorched holes and ragged edges at their major positions; no new damage, flames or smoke. Gold microphone with black bands always held in anatomical RIGHT hand (viewer LEFT in front view); free anatomical LEFT hand holds skirt. Full-length gown always. Neutral base: gentle closed-mouth smile, upright relaxed stance, microphone below chest away from face. Entire veil and hem contained. No bouquets crown notes effects or ground shadows.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Preserve exact refined Japanese anime chibi reference: fine linework, soft cel shading, hair highlights, pale gray and lavender-gray white fabric shadows, hand-painted metallic corset highlights. Do not exaggerate chibi proportions beyond reference..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Working loop: focused active-task processing, thinking, typing, scanning, or effortful concentration; not literal foot-running, jogging, sprinting, treadmill motion, raised knees, long steps, pumping arms, or directional travel.

State requirements:
- Show the pet actively working or processing, as if running a task: focused posture, busy hands or paws, purposeful bobbing, thinking motion, tool or prop motion only if already part of the pet identity, or other non-locomotion activity.
- Do not show literal foot-running, jogging, sprinting, treadmill motion, raised knees, long steps, pumping arms, directional travel, speed lines, dust clouds, floor shadows, motion trails, or detached motion effects.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.

User-approved choreography (takes precedence over generic action): WORK/THINKING, planted lower body. Right-hand microphone slightly lowered. Free left hand comes gently to chin, focused eyes and small thoughtful nod. No walking or continuous singing. Preserve gown/veil and gold microphone black bands.
Do not simplify the approved costume into an ordinary wedding dress. Keep scorch-edge holes, copper-brown corset patina and inner white fabric distinct; no new cracks, transparent bands, props, floor shadow, smoke, fire, petals, notes or halo. Keep the original refined anime face and original head/body ratio.


## prompts\rows\waiting.md

Create one horizontal animation strip for Codex pet `gem-bridal`, state `waiting`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 6 full-body frames in one left-to-right row on flat pure blue #0000FF. Treat the row as 6 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Use the supplied approved character as the ONLY appearance reference; no redesign. Preserve exact head/body ratio, rounded anime face, brown curled long hair and eyes, gold earrings, asymmetric white neckline on anatomical LEFT shoulder (viewer RIGHT in front view), silver-white structured corset with copper-brown patina at lower edge, long pleated white skirt and long attached veil. Preserve intentional scorched holes and ragged edges at their major positions; no new damage, flames or smoke. Gold microphone with black bands always held in anatomical RIGHT hand (viewer LEFT in front view); free anatomical LEFT hand holds skirt. Full-length gown always. Neutral base: gentle closed-mouth smile, upright relaxed stance, microphone below chest away from face. Entire veil and hem contained. No bouquets crown notes effects or ground shadows.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Preserve exact refined Japanese anime chibi reference: fine linework, soft cel shading, hair highlights, pale gray and lavender-gray white fabric shadows, hand-painted metallic corset highlights. Do not exaggerate chibi proportions beyond reference..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Needs-input loop: expectant asking pose for approval, help, or user input.

State requirements:
- Show that Codex needs approval, help, or user input through an expectant asking pose.
- Keep the motion patient and readable, without turning it into ordinary idle or review.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.

User-approved choreography (takes precedence over generic action): Expectant gentle head tilt and slight upper-body lean toward user, warm attentive eyes, left hand rests on skirt, microphone secure in right hand. Quiet motion distinct from ordinary idle, awaiting a response.
Do not simplify the approved costume into an ordinary wedding dress. Keep scorch-edge holes, copper-brown corset patina and inner white fabric distinct; no new cracks, transparent bands, props, floor shadow, smoke, fire, petals, notes or halo. Keep the original refined anime face and original head/body ratio.


## prompts\rows\waving.md

Create one horizontal animation strip for Codex pet `gem-bridal`, state `waving`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 4 full-body frames in one left-to-right row on flat pure blue #0000FF. Treat the row as 4 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Use the supplied approved character as the ONLY appearance reference; no redesign. Preserve exact head/body ratio, rounded anime face, brown curled long hair and eyes, gold earrings, asymmetric white neckline on anatomical LEFT shoulder (viewer RIGHT in front view), silver-white structured corset with copper-brown patina at lower edge, long pleated white skirt and long attached veil. Preserve intentional scorched holes and ragged edges at their major positions; no new damage, flames or smoke. Gold microphone with black bands always held in anatomical RIGHT hand (viewer LEFT in front view); free anatomical LEFT hand holds skirt. Full-length gown always. Neutral base: gentle closed-mouth smile, upright relaxed stance, microphone below chest away from face. Entire veil and hem contained. No bouquets crown notes effects or ground shadows.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Preserve exact refined Japanese anime chibi reference: fine linework, soft cel shading, hair highlights, pale gray and lavender-gray white fabric shadows, hand-painted metallic corset highlights. Do not exaggerate chibi proportions beyond reference..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Greeting loop: paw or limb down, raised, tilted, and returning in a friendly attention gesture.

State requirements:
- Show the greeting through paw, hand, wing, or limb pose only.
- Do not draw wave marks, motion arcs, lines, sparkles, symbols, or floating effects around the gesture.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.

User-approved choreography (takes precedence over generic action): Left free hand releases skirt, raises for a small elegant wave with slight head tilt and sweet smile, then returns to skirt. Right hand holds microphone steady below chest. Four frames: rest, raise, gentle wave, return.
Do not simplify the approved costume into an ordinary wedding dress. Keep scorch-edge holes, copper-brown corset patina and inner white fabric distinct; no new cracks, transparent bands, props, floor shadow, smoke, fire, petals, notes or halo. Keep the original refined anime face and original head/body ratio.
