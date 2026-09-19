# 文静婚纱版 · 实际生成提示词

使用内置 imagegen。参考图定义外观，布局图只用于排列，不是成品的一部分。

## base-pet.md

Create one clean full-body reference sprite for Codex pet G.E.M. 文静婚纱版.

Pet identity: Only appearance authority is supplied reference. Anatomical RIGHT hand holds gold microphone with black bands (viewer LEFT front), anatomical LEFT shoulder covered by single shoulder neckline (viewer RIGHT). Preserve copper-brown lower corset weathering, full length pleated gown, attached long veil, existing scorched holes and inner cloth. Quiet restrained personality. All motion gentle and small. No jumping, running, toe-rise or broad gestures: jumping name means grounded joyful response; movement means slow tiny walking steps. No extra props, effects, text, floor shadows. Lower microphone below chest for neutral small closed-mouth smile..
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Exactly preserve attached refined Japanese anime chibi style, original head-body ratio, delicate linework, soft cel shading, brown curled hair and eyes, gold earrings, white/lavender-gray gown folds and hand-painted silver corset..


Place a single centered pose on a perfectly flat pure user-selected #0000FF chroma-key background. Keep the full pet visible, compact, readable at 192x208, and easy to animate. Preserve approved reference identity cues. No scenery, text, borders, checkerboard transparency, shadows, glows, detached effects, or extra props. Keep #0000FF and close colors out of the pet, props, highlights, and effects.

Only normalize the approved reference composition/padding and quiet neutral standing pose: right microphone held lower below chest, left hand at skirt, small gentle closed-mouth smile. Keep the EXACT reference face, large head ratio, long gown/veil design, original shoulder direction and scorch-hole locations. Do not redesign, simplify into another character, elongate body or enlarge head. Full outline with generous empty margins.


## look-anchor-repairs/000.md

Repair one cardinal anchor for Codex pet `GEM-bridal_2`: `000` means looking up.

Use the canonical base, completed standard contact sheet, approved cardinal-strip cells, and `qa/look-mechanics.md` for identity, scale, registration, and pet-specific gaze mechanics. Keep the face broadly frontal and point the eyes and natural head mechanism toward the TOP edge. Screen coordinates are viewer-relative.

Output one centered complete full-body pose on a flat pure user-selected #0000FF background with generous padding. Keep the feet/base and lower body registered to the approved anchors. The requested cardinal must be unmistakable at final 192x208 display size.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement eyes, labels, arrows, guide marks, shadows, scenery, detached effects, or chroma-key colors inside the pet.


## look-anchor-repairs/090.md

Repair one cardinal anchor for Codex pet `GEM-bridal_2`: `090` means looking right.

Use the canonical base, completed standard contact sheet, approved cardinal-strip cells, and `qa/look-mechanics.md` for identity, scale, registration, and pet-specific gaze mechanics. Put the nose tip, pupils, face surface, or natural aiming feature on the screen-right side of the head center. Screen coordinates are viewer-relative.

Output one centered complete full-body pose on a flat pure user-selected #0000FF background with generous padding. Keep the feet/base and lower body registered to the approved anchors. The requested cardinal must be unmistakable at final 192x208 display size.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement eyes, labels, arrows, guide marks, shadows, scenery, detached effects, or chroma-key colors inside the pet.


## look-anchor-repairs/180.md

Repair one cardinal anchor for Codex pet `GEM-bridal_2`: `180` means looking down.

Use the canonical base, completed standard contact sheet, approved cardinal-strip cells, and `qa/look-mechanics.md` for identity, scale, registration, and pet-specific gaze mechanics. Keep the face broadly frontal and point the eyes and natural head mechanism toward the BOTTOM edge. Screen coordinates are viewer-relative.

Output one centered complete full-body pose on a flat pure user-selected #0000FF background with generous padding. Keep the feet/base and lower body registered to the approved anchors. The requested cardinal must be unmistakable at final 192x208 display size.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement eyes, labels, arrows, guide marks, shadows, scenery, detached effects, or chroma-key colors inside the pet.


## look-anchor-repairs/270.md

Repair one cardinal anchor for Codex pet `GEM-bridal_2`: `270` means looking left.

Use the canonical base, completed standard contact sheet, approved cardinal-strip cells, and `qa/look-mechanics.md` for identity, scale, registration, and pet-specific gaze mechanics. Put the nose tip, pupils, face surface, or natural aiming feature on the screen-left side of the head center. Screen coordinates are viewer-relative.

Output one centered complete full-body pose on a flat pure user-selected #0000FF background with generous padding. Keep the feet/base and lower body registered to the approved anchors. The requested cardinal must be unmistakable at final 192x208 display size.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement eyes, labels, arrows, guide marks, shadows, scenery, detached effects, or chroma-key colors inside the pet.


## look-cardinals.md

Create one horizontal four-cardinal anchor strip for Codex pet `GEM-bridal_2`.

Use the attached canonical base, completed standard contact sheet, and layout guide for exact identity, style, scale, baseline, face construction, materials, palette, markings, props, and spacing. Read `qa/look-mechanics.md` and use the pet's natural gaze mechanism.

Output exactly four centered complete full-body poses in this exact left-to-right order: `000 up`, `090 screen-right`, `180 down`, `270 screen-left`. Screen-left and screen-right always mean the viewer's image edges, never the character's own left or right.

For `000`, keep the face broadly frontal and point the eyes and natural head mechanism toward the TOP edge. For `090`, put the nose tip, pupils, face surface, or natural aiming feature on the screen-right side of the head center. For `180`, keep the face broadly frontal and point toward the BOTTOM edge. For `270`, apply the inverse screen-left landmark rule. Every cardinal must be unmistakable without labels.

Place one pose in each invisible equal-width slot on a flat pure user-selected #0000FF background with generous padding. Keep scale, feet/base, lower body, and registration consistent across all four slots.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement eyes, labels, degree text, arrows, boxes, guide marks, shadows, scenery, detached effects, or chroma-key colors inside the pet.

PET-SPECIFIC MECHANICS (authoritative):
# 文静婚纱版 · 注视运动方案

Approved standard57frames inspected independently. Preserve this humanoid character's exact face, skull/eye proportions, calm small smile, LEFT shoulder neckline and anatomical RIGHT-hand gold microphone. Do not mirror face/body/costume to create leftward looks.

Lower gown, hips, feet and hem baseline stay planted and at the same scale in all16 directions. Eyes lead: redraw the brown anime eyes coherently inside original apertures, with iris/pupil, sclera, lid contour and highlights coordinated; never floating/googly pupils. Head turns gently at neck with only necessary shoulder follow-through. Preserve skull and feature spacing; no raster warps or whole-sprite rotation.

Cardinal families in SCREEN coordinates:
- 000 UP: broadly frontal head, small chin lift, irises and lids clearly aim upward. Some under-chin visible, no horizontal turn. Distinct from neutral.
- 090 RIGHT: gentle but unmistakable head yaw to viewer RIGHT (roughly25-30degrees), nose and pupils right of headcenter. Left visible facial plane expands while far right eye foreshortens as appropriate. Do not turn lower body or swap hands.
- 180 DOWN: broadly frontal head gently bows, chin nearer neckline, eyelids lower and pupils look down. Hair crown becomes slightly more visible; face not crushed. Distinct from closed-eye idleblink.
- 270 LEFT: gentle unmistakable yaw to viewer LEFT, nose and pupils left of headcenter. Opposite facial-plane visibility to090, naturally redrawn without mirroring costume or hair. Do not let leftcardinal remain frontal/right.

Motion budget: small pitch about8-12degrees, yaw25-30max, minute shoulderfollow only; angles denote ATTENTION targets, not rotating wholebody byclockangle. Even22.5degree attention steps with gradual consistent changes. Each nearcardinal secondary axis may be subtle, but no wrongquadrant/reversal. 157.5to180 and337.5to000 are ordinary adjacent steps, no snap or scalechange.

Veil root remains fixed to original crown/rearhead attachment and follows head softly; long lower veil remains behindbody, same length, no drift or hairpenetration. Curls and gold earrings follow natural attachment with restrained movement, no whipping. Mic stays anatomical RIGHT hand belowchest, away fromface/hair/veil; hand/arm makes minute near-rigid follow-through, no teleport or switchedgrip. Free LEFT hand gently holds skirt. Scorchholes andcopperpatina retain main positions/distribution; distinguish whiteinnercloth from transparency. Fullsilhouette remains insideeverycell.

All4cardinals must read unmistakably at192x208 withoutlabels. No singing, walking, jumping or largegestures during gaze. All16 form one quiet continuousfamily. No labels/shadows/props/effects.


## row-retries/failed.md

Create Codex pet row `failed` for `GEM-bridal_2`: exactly 8 full-body frames in one horizontal strip on flat pure user-selected #0000FF.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Only appearance authority is supplied reference. Anatomical RIGHT hand holds gold microphone with black bands (viewer LEFT front), anatomical LEFT shoulder covered by single shoulder neckline (viewer RIGHT). Preserve copper-brown lower corset weathering, full length pleated gown, attached long veil, existing scorched holes and inner cloth. Quiet restrained personality. All motion gentle and small. No jumping, running, toe-rise or broad gestures: jumping name means grounded joyful response; movement means slow tiny walking steps. No extra props, effects, text, floor shadows. Lower microphone below chest for neutral small closed-mouth smile.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row in ALL states, including grounded `jumping`.

User-authoritative action: Restrained regret and renewed thought: eyes gently lower, tiny smile recedes, hold a quiet thoughtful pause, then slowly lift gaze with restored composure. No crying, tears, exaggerated sigh, head shaking, effects or body slump. Keep lower body planted.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #0000FF colors in the pet.

User-authoritative state action: Restrained regret and renewed thought: eyes gently lower, tiny smile recedes, hold a quiet thoughtful pause, then slowly lift gaze with restored composure. No crying, tears, exaggerated sigh, head shaking, effects or body slump. Keep lower body planted.

All nine states: gentle small motion, stable scale and planted hem baseline. Preserve original face/head-to-body ratio and connected veil. Keep designed scorch holes, patina and inner cloth; do not add holes/seams. No detached effects, floor shadows or extra props.


## row-retries/idle.md

Create Codex pet row `idle` for `GEM-bridal_2`: exactly 6 full-body frames in one horizontal strip on flat pure user-selected #0000FF.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Only appearance authority is supplied reference. Anatomical RIGHT hand holds gold microphone with black bands (viewer LEFT front), anatomical LEFT shoulder covered by single shoulder neckline (viewer RIGHT). Preserve copper-brown lower corset weathering, full length pleated gown, attached long veil, existing scorched holes and inner cloth. Quiet restrained personality. All motion gentle and small. No jumping, running, toe-rise or broad gestures: jumping name means grounded joyful response; movement means slow tiny walking steps. No extra props, effects, text, floor shadows. Lower microphone below chest for neutral small closed-mouth smile.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row in ALL states, including grounded `jumping`.

User-authoritative action: Quiet breathing with one slow gentle blink and tiny attached veil/curl sway. Soft closed-mouth smile. Anatomical right hand holds microphone below chest, left hand lightly holds skirt throughout. No singing/waving. Frame sequence: neutral, inhale, half blink, closed blink, reopen, return near neutral. Micro-variation visible but calm.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #0000FF colors in the pet.

User-authoritative state action: Quiet breathing with one slow gentle blink and tiny attached veil/curl sway. Soft closed-mouth smile. Anatomical right hand holds microphone below chest, left hand lightly holds skirt throughout. No singing/waving. Frame sequence: neutral, inhale, half blink, closed blink, reopen, return near neutral. Micro-variation visible but calm.

All nine states: gentle small motion, stable scale and planted hem baseline. Preserve original face/head-to-body ratio and connected veil. Keep designed scorch holes, patina and inner cloth; do not add holes/seams. No detached effects, floor shadows or extra props.


## row-retries/jumping.md

Create Codex pet row `jumping` for `GEM-bridal_2`: exactly 5 full-body frames in one horizontal strip on flat pure user-selected #0000FF.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Only appearance authority is supplied reference. Anatomical RIGHT hand holds gold microphone with black bands (viewer LEFT front), anatomical LEFT shoulder covered by single shoulder neckline (viewer RIGHT). Preserve copper-brown lower corset weathering, full length pleated gown, attached long veil, existing scorched holes and inner cloth. Quiet restrained personality. All motion gentle and small. No jumping, running, toe-rise or broad gestures: jumping name means grounded joyful response; movement means slow tiny walking steps. No extra props, effects, text, floor shadows. Lower microphone below chest for neutral small closed-mouth smile.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row in ALL states, including grounded `jumping`.

User-authoritative action: System name jumping ONLY: grounded gentle joy, absolutely NO physical jump, hop, tiptoe, bounce, airborne pose or vertical translation. Five phases: soft neutral smile, slight chin lift, deeper small smile and gently open shoulders with LEFT hand softly near chest, hand lowers, return to neutral. Feet always grounded and hem baseline perfectly stable. RIGHT-hand microphone never changes hands.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #0000FF colors in the pet.

User-authoritative state action: System name jumping ONLY: grounded gentle joy, absolutely NO physical jump, hop, tiptoe, bounce, airborne pose or vertical translation. Five phases: soft neutral smile, slight chin lift, deeper small smile and gently open shoulders with LEFT hand softly near chest, hand lowers, return to neutral. Feet always grounded and hem baseline perfectly stable. RIGHT-hand microphone never changes hands.

All nine states: gentle small motion, stable scale and planted hem baseline. Preserve original face/head-to-body ratio and connected veil. Keep designed scorch holes, patina and inner cloth; do not add holes/seams. No detached effects, floor shadows or extra props.


## row-retries/look-row-10-boundary-repair.md

Generate one coherent horizontal strip of exactly8 complete full-body poses for this same quiet bridal singer. Match the first attached completed row9's drawn bodyheight450-454pixels (not420) on a2176x724canvas, baseline607; same head/face size, gownwidth, style and identity. Use firstimage for SCALE AND COSTUME only: do NOT copy its rightward direction poses. Otherrefs: original+canonical identitypanel,8slotspacingguide, standardcontactsheet, final4cardinalanchors.
This new strip is the LEFT HALF of clockwise attention: left-to-right DOWN, downslightlyLEFT, DOWNLEFT, mostlyLEFTslightlyDOWN, LEFT, mostlyLEFTslightlyUP, UPLEFT, upslightlyLEFT. These mean VIEWER/SCREEN coordinates. Frames2-8 noseandface/pupils MUST favor imageLEFT. Frame5 must unmistakably face imageLEFT; neverturnright. Forframes6-8 eyes and chin lift upwards WHILE face staysLEFT; do not copy upperRIGHT fromrow9. Frame8 is almostfrontal but retainsleftbias andvisibleUP eyes/chin, joining row9's strongUPpose smoothly.
The suppliedlast cardinalstrip's fourthpose is LEFT directionauthority; interpolate fromDOWN throughLEFT toUP. Gentle naturaleye/head/neck motion, lowerbody planted. Originalanimeeyes, calm smallsmile. Onecoherent8posefamily with gradualattentionsteps. Exactface, hair, proportion, whiteasymmetricLEFTshoulder neckline(viewerrightfrontal), anatomicalRIGHThandgoldblackmicrophone(viewerleftfrontal), freeLEFThandskirt, originalstagegown/corset copperpatina/scorchedholes, attachedveil. Gownandfeetbaseline stable; nevermirrororwholebodytilt.
8separatefullsilhouettes ontrulytransparentbackground. Aim centerpositions136,408,680,952,1224,1496,1768,2040. Eachcompletecharacterabout450pxhigh,max250pxwide, withgaps and10pxminimumoutermargins. Nooverlap,cropping,shadows,text,guidelines,effects,newprops. Keepfullgownandveileveninsourceouterposes.


## row-retries/look-row-10-scale-repair.md

Edit the attached eight-pose LEFT-half direction strip as one coherent complete strip. Preserve ALL eight existing face directions and costume/identity exactly. The only correction is layout/scale: uniformly reduce EVERY figure's WHOLE silhouette by about5% from its current471pxheight to448-450pxheight. Do not shorten skirts or distort heads; scalecompletefigure includingveil/hair/body together. Keepcanvas2172x724 transparent, bodytoparound175px bottom625px, eightequalcenters136,408,680,952,1224,1496,1768,2040. Maxfigurewidth250px, clear22pxgapbetweenneighbors, 10pxminimumoutermargin. Firsttwogownsmustnot touch. Fullsilhouetteinsideeachslot.
The suppliedcompletedrow9 defineshead/bodyPROPORTIONS andexactSOURCE scale; matchits450pxbodyheight. All8figuresmusthaveidenticaldrawingheight. DoNOTenlargearttofillcanvas. Generousblankspaceaboveandbelowisintentional.
Left-to-right directionsremain DOWN, downslightlyLEFT, DOWNLEFT, mostlyLEFTslightlyDOWN, LEFT, mostlyLEFTslightlyUP, UPLEFT, upslightlyLEFT. Lastthree facesremainleftofheadcenter withupwardeyechin, notright. Rightmic/leftshoulder unchanged; preserveoriginalgownholes/copperpatina/veilattachment. Noextratext/shadows/effects. Composeall8togetherasonecoherentrow.


## row-retries/look-row-10.md

Create Codex v2 pet look row 10 for `GEM-bridal_2` as exactly 8 full-body frames in this order: 180, 202.5, 225, 247.5, 270, 292.5, 315, 337.5.

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

Use a flat pure user-selected #0000FF background. One complete unclipped pose per invisible slot. No whole-sprite rotation, replacement eyes, labels, guide marks, shadows, glows, scenery, detached effects, or #0000FF colors in the pet.


## row-retries/look-row-9-blind-repair.md

Regenerate this complete coherent eight-pose row, preserving the supplied row's identity, fixed anatomy, gown and all pose spacing/size. Fix the first pose so it unmistakably LOOKS UP at pet size: gently raised chin with visible underside, both brown irises high within naturally redrawn eyelids, clear light sclera crescent below irises, attention visibly toward overhead. Preserve eyes' original large anime structure and calm expression; do not just smile forward. It must read UP without labels, stronger than neutral, while remaining gentle. The neighboring second pose should continue smoothly up-right. All other direction meaning stays as supplied.
Exactly8 full-body poses left-to-right: UP, mostlyUPslightlyRIGHT, UPRIGHT, mostlyRIGHTslightlyUP, RIGHT, mostlyRIGHTslightlyDOWN, DOWNRIGHT, mostlyDOWNslightlyRIGHT. Viewer's screen directions. Fifth clear nose/face/pupilsRIGHT. Sixth a slight visible downward head pitch. Last bowed head with slightRIGHT yaw.
One coherent eight-frame family, no isolated cell patch. Hold source canvas about2176x724 and bodyheight420-426pixels, same head/body ratio, horizontal baseline about594, keep entire veil and gown insidecanvas with20pxoutermargins and gaps,8separate figures. Do not enlarge any pose, merge skirts, or movefeet. Transparentbackground, no shadows/text/effects/guide lines. Keep exact anatomical RIGHT-hand microphone (viewerleft frontal), LEFT shoulder asymmetrical neckline (viewerright frontal), stagegown holes/copperpatina, attachedveil,curls,earrings. No mirroring/face stretching/wholebodytilt/newprops. All visual traits follow originalandcanonical referencepanel. Suppliedcardinal strip sets direction families; don't copy its frontal-looking eyes forUP: strengthen overhead gaze as described.


## row-retries/look-row-9.md

Create Codex v2 pet look row 9 for `GEM-bridal_2` as exactly 8 full-body frames in this order: 000, 022.5, 045, 067.5, 090, 112.5, 135, 157.5.

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

Use a flat pure user-selected #0000FF background. One complete unclipped pose per invisible slot. No whole-sprite rotation, replacement eyes, labels, guide marks, shadows, glows, scenery, detached effects, or #0000FF colors in the pet.


## row-retries/review.md

Create Codex pet row `review` for `GEM-bridal_2`: exactly 6 full-body frames in one horizontal strip on flat pure user-selected #0000FF.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Only appearance authority is supplied reference. Anatomical RIGHT hand holds gold microphone with black bands (viewer LEFT front), anatomical LEFT shoulder covered by single shoulder neckline (viewer RIGHT). Preserve copper-brown lower corset weathering, full length pleated gown, attached long veil, existing scorched holes and inner cloth. Quiet restrained personality. All motion gentle and small. No jumping, running, toe-rise or broad gestures: jumping name means grounded joyful response; movement means slow tiny walking steps. No extra props, effects, text, floor shadows. Lower microphone below chest for neutral small closed-mouth smile.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row in ALL states, including grounded `jumping`.

User-authoritative action: Review completed results: small head dip, eyes slowly scan a small range, pause, lift eyes, slight confirming nod and very faint reassured smile. Free hand at skirt, right-hand microphone steady. Distinct from downward thinking and idle.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #0000FF colors in the pet.

User-authoritative state action: Review completed results: small head dip, eyes slowly scan a small range, pause, lift eyes, slight confirming nod and very faint reassured smile. Free hand at skirt, right-hand microphone steady. Distinct from downward thinking and idle.

All nine states: gentle small motion, stable scale and planted hem baseline. Preserve original face/head-to-body ratio and connected veil. Keep designed scorch holes, patina and inner cloth; do not add holes/seams. No detached effects, floor shadows or extra props.


## row-retries/running-left.md

Create Codex pet row `running-left` for `GEM-bridal_2`: exactly 8 full-body frames in one horizontal strip on flat pure user-selected #0000FF.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Only appearance authority is supplied reference. Anatomical RIGHT hand holds gold microphone with black bands (viewer LEFT front), anatomical LEFT shoulder covered by single shoulder neckline (viewer RIGHT). Preserve copper-brown lower corset weathering, full length pleated gown, attached long veil, existing scorched holes and inner cloth. Quiet restrained personality. All motion gentle and small. No jumping, running, toe-rise or broad gestures: jumping name means grounded joyful response; movement means slow tiny walking steps. No extra props, effects, text, floor shadows. Lower microphone below chest for neutral small closed-mouth smile.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row in ALL states, including grounded `jumping`.

User-authoritative action: Slow tiny walking steps facing and moving screen LEFT. Not running. Free anatomical LEFT hand slightly lifts the long skirt; anatomical RIGHT hand holds microphone steadily. Eight phases with alternating tiny toe/hem changes and gentle lag of attached veil and curls. Torso almost level, no bouncing, no high knees. Preserve full-length skirt and asymmetry, independently redraw LEFT facing, never mirror identity.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #0000FF colors in the pet.

User-authoritative state action: Slow tiny walking steps facing and moving screen LEFT. Not running. Free anatomical LEFT hand slightly lifts the long skirt; anatomical RIGHT hand holds microphone steadily. Eight phases with alternating tiny toe/hem changes and gentle lag of attached veil and curls. Torso almost level, no bouncing, no high knees. Preserve full-length skirt and asymmetry, independently redraw LEFT facing, never mirror identity.

All nine states: gentle small motion, stable scale and planted hem baseline. Preserve original face/head-to-body ratio and connected veil. Keep designed scorch holes, patina and inner cloth; do not add holes/seams. No detached effects, floor shadows or extra props.

REPAIR COMPOSITION: updated attached guide is 2176x724, eight 272px slots with safe inner rectangles. Fit each entire character including trailing veil inside its BLUE INNER rectangle, with width<=195px and height<=360px. Do not enlarge figures to fill canvas. Keep huge empty margins above/below and clear gaps. Rightmost veil must end at least38px before canvas edge. Guide only invisible construction, no visible boxes. Same character ratio and face; solve with smaller full figures, never shorten veil or skirt.


## row-retries/running-right.md

Create Codex pet row `running-right` for `GEM-bridal_2`: exactly 8 full-body frames in one horizontal strip on flat pure user-selected #0000FF.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Only appearance authority is supplied reference. Anatomical RIGHT hand holds gold microphone with black bands (viewer LEFT front), anatomical LEFT shoulder covered by single shoulder neckline (viewer RIGHT). Preserve copper-brown lower corset weathering, full length pleated gown, attached long veil, existing scorched holes and inner cloth. Quiet restrained personality. All motion gentle and small. No jumping, running, toe-rise or broad gestures: jumping name means grounded joyful response; movement means slow tiny walking steps. No extra props, effects, text, floor shadows. Lower microphone below chest for neutral small closed-mouth smile.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row in ALL states, including grounded `jumping`.

User-authoritative action: Slow tiny walking steps facing and moving screen RIGHT. Not running. Free anatomical LEFT hand slightly lifts the long skirt; anatomical RIGHT hand holds microphone steadily. Eight phases with alternating tiny toe/hem changes and gentle lag of attached veil and curls. Torso almost level, no bouncing, no high knees. Preserve full-length skirt and asymmetry, never mirror identity.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #0000FF colors in the pet.

User-authoritative state action: Slow tiny walking steps facing and moving screen RIGHT. Not running. Free anatomical LEFT hand slightly lifts the long skirt; anatomical RIGHT hand holds microphone steadily. Eight phases with alternating tiny toe/hem changes and gentle lag of attached veil and curls. Torso almost level, no bouncing, no high knees. Preserve full-length skirt and asymmetry, never mirror identity.

All nine states: gentle small motion, stable scale and planted hem baseline. Preserve original face/head-to-body ratio and connected veil. Keep designed scorch holes, patina and inner cloth; do not add holes/seams. No detached effects, floor shadows or extra props.


## row-retries/running.md

Create Codex pet row `running` for `GEM-bridal_2`: exactly 6 full-body frames in one horizontal strip on flat pure user-selected #0000FF.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Only appearance authority is supplied reference. Anatomical RIGHT hand holds gold microphone with black bands (viewer LEFT front), anatomical LEFT shoulder covered by single shoulder neckline (viewer RIGHT). Preserve copper-brown lower corset weathering, full length pleated gown, attached long veil, existing scorched holes and inner cloth. Quiet restrained personality. All motion gentle and small. No jumping, running, toe-rise or broad gestures: jumping name means grounded joyful response; movement means slow tiny walking steps. No extra props, effects, text, floor shadows. Lower microphone below chest for neutral small closed-mouth smile.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row in ALL states, including grounded `jumping`.

User-authoritative action: Quiet task processing, never locomotion or singing. Right-hand microphone slightly lowered. Eyes gently lower, pause in concentration, small slow nod, return to thoughtful focus. Free left hand naturally rests in front near waist; no repeated gestures and no hand at chin. Planted lower body.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #0000FF colors in the pet.

User-authoritative state action: Quiet task processing, never locomotion or singing. Right-hand microphone slightly lowered. Eyes gently lower, pause in concentration, small slow nod, return to thoughtful focus. Free left hand naturally rests in front near waist; no repeated gestures and no hand at chin. Planted lower body.

All nine states: gentle small motion, stable scale and planted hem baseline. Preserve original face/head-to-body ratio and connected veil. Keep designed scorch holes, patina and inner cloth; do not add holes/seams. No detached effects, floor shadows or extra props.


## row-retries/waiting.md

Create Codex pet row `waiting` for `GEM-bridal_2`: exactly 6 full-body frames in one horizontal strip on flat pure user-selected #0000FF.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Only appearance authority is supplied reference. Anatomical RIGHT hand holds gold microphone with black bands (viewer LEFT front), anatomical LEFT shoulder covered by single shoulder neckline (viewer RIGHT). Preserve copper-brown lower corset weathering, full length pleated gown, attached long veil, existing scorched holes and inner cloth. Quiet restrained personality. All motion gentle and small. No jumping, running, toe-rise or broad gestures: jumping name means grounded joyful response; movement means slow tiny walking steps. No extra props, effects, text, floor shadows. Lower microphone below chest for neutral small closed-mouth smile.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row in ALL states, including grounded `jumping`.

User-authoritative action: Patient quiet attentive waiting: slight soft head tilt, calm direct gaze, natural right-hand microphone and left hand at skirt. Small slow blink then attentive reopen. Do not look impatient or demanding. No broad gesture. Gentle held posture distinct from idle.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #0000FF colors in the pet.

User-authoritative state action: Patient quiet attentive waiting: slight soft head tilt, calm direct gaze, natural right-hand microphone and left hand at skirt. Small slow blink then attentive reopen. Do not look impatient or demanding. No broad gesture. Gentle held posture distinct from idle.

All nine states: gentle small motion, stable scale and planted hem baseline. Preserve original face/head-to-body ratio and connected veil. Keep designed scorch holes, patina and inner cloth; do not add holes/seams. No detached effects, floor shadows or extra props.


## row-retries/waving.md

Create Codex pet row `waving` for `GEM-bridal_2`: exactly 4 full-body frames in one horizontal strip on flat pure user-selected #0000FF.

Use the attached canonical base for identity and the layout guide only for spacing. Same pet in every frame: Only appearance authority is supplied reference. Anatomical RIGHT hand holds gold microphone with black bands (viewer LEFT front), anatomical LEFT shoulder covered by single shoulder neckline (viewer RIGHT). Preserve copper-brown lower corset weathering, full length pleated gown, attached long veil, existing scorched holes and inner cloth. Quiet restrained personality. All motion gentle and small. No jumping, running, toe-rise or broad gestures: jumping name means grounded joyful response; movement means slow tiny walking steps. No extra props, effects, text, floor shadows. Lower microphone below chest for neutral small closed-mouth smile.. Preserve silhouette, face, palette, material, proportions, markings, and props.

Keep apparent pet scale and baseline stable within the row in ALL states, including grounded `jumping`.

User-authoritative action: Quiet familiar greeting: small eye lift and little nod, free LEFT hand rises only near front of torso, makes one tiny gentle sway, and returns beside skirt. Four phases: rest, small lift/nod, small hand sway, soft return. Never raise hand above shoulders. RIGHT hand holds microphone steady.

One centered complete pose per invisible slot. No text, boxes, guide marks, scenery, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or #0000FF colors in the pet.

User-authoritative state action: Quiet familiar greeting: small eye lift and little nod, free LEFT hand rises only near front of torso, makes one tiny gentle sway, and returns beside skirt. Four phases: rest, small lift/nod, small hand sway, soft return. Never raise hand above shoulders. RIGHT hand holds microphone steady.

All nine states: gentle small motion, stable scale and planted hem baseline. Preserve original face/head-to-body ratio and connected veil. Keep designed scorch holes, patina and inner cloth; do not add holes/seams. No detached effects, floor shadows or extra props.


## rows/failed.md

Create one horizontal animation strip for Codex pet `GEM-bridal_2`, state `failed`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 8 full-body frames in one left-to-right row on flat pure user-selected #0000FF. Treat the row as 8 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Only appearance authority is supplied reference. Anatomical RIGHT hand holds gold microphone with black bands (viewer LEFT front), anatomical LEFT shoulder covered by single shoulder neckline (viewer RIGHT). Preserve copper-brown lower corset weathering, full length pleated gown, attached long veil, existing scorched holes and inner cloth. Quiet restrained personality. All motion gentle and small. No jumping, running, toe-rise or broad gestures: jumping name means grounded joyful response; movement means slow tiny walking steps. No extra props, effects, text, floor shadows. Lower microphone below chest for neutral small closed-mouth smile.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Exactly preserve attached refined Japanese anime chibi style, original head-body ratio, delicate linework, soft cel shading, brown curled hair and eyes, gold earrings, white/lavender-gray gown folds and hand-painted silver corset..
Animation continuity: keep apparent pet scale and baseline stable within the row in ALL states, including grounded `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

User-authoritative state action: Restrained regret and renewed thought: eyes gently lower, tiny smile recedes, hold a quiet thoughtful pause, then slowly lift gaze with restored composure. No crying, tears, exaggerated sigh, head shaking, effects or body slump. Keep lower body planted.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.

All nine states: gentle small motion, stable scale and planted hem baseline. Preserve original face/head-to-body ratio and connected veil. Keep designed scorch holes, patina and inner cloth; do not add holes/seams. No detached effects, floor shadows or extra props.
REPAIR COMPOSITION: last source had all8 gowns connected and rightmost veil cropped. New attached8slot layoutguide has large safe margins. Render each COMPLETE figure smaller within each blue inner rectangle, at most195pxwide and360pxhigh on2176x724canvas. At least35pxoutermargin and at least25pxclear gap between foreground silhouettes. Preserve exact proportions and quiet failed choreography; do not shorten veil or gown. No guidepixels.


## rows/idle.md

Create one horizontal animation strip for Codex pet `GEM-bridal_2`, state `idle`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 6 full-body frames in one left-to-right row on flat pure user-selected #0000FF. Treat the row as 6 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Only appearance authority is supplied reference. Anatomical RIGHT hand holds gold microphone with black bands (viewer LEFT front), anatomical LEFT shoulder covered by single shoulder neckline (viewer RIGHT). Preserve copper-brown lower corset weathering, full length pleated gown, attached long veil, existing scorched holes and inner cloth. Quiet restrained personality. All motion gentle and small. No jumping, running, toe-rise or broad gestures: jumping name means grounded joyful response; movement means slow tiny walking steps. No extra props, effects, text, floor shadows. Lower microphone below chest for neutral small closed-mouth smile.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Exactly preserve attached refined Japanese anime chibi style, original head-body ratio, delicate linework, soft cel shading, brown curled hair and eyes, gold earrings, white/lavender-gray gown folds and hand-painted silver corset..
Animation continuity: keep apparent pet scale and baseline stable within the row in ALL states, including grounded `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

User-authoritative state action: Quiet breathing with one slow gentle blink and tiny attached veil/curl sway. Soft closed-mouth smile. Anatomical right hand holds microphone below chest, left hand lightly holds skirt throughout. No singing/waving. Frame sequence: neutral, inhale, half blink, closed blink, reopen, return near neutral. Micro-variation visible but calm.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.

All nine states: gentle small motion, stable scale and planted hem baseline. Preserve original face/head-to-body ratio and connected veil. Keep designed scorch holes, patina and inner cloth; do not add holes/seams. No detached effects, floor shadows or extra props.


## rows/jumping.md

Create one horizontal animation strip for Codex pet `GEM-bridal_2`, state `jumping`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 5 full-body frames in one left-to-right row on flat pure user-selected #0000FF. Treat the row as 5 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Only appearance authority is supplied reference. Anatomical RIGHT hand holds gold microphone with black bands (viewer LEFT front), anatomical LEFT shoulder covered by single shoulder neckline (viewer RIGHT). Preserve copper-brown lower corset weathering, full length pleated gown, attached long veil, existing scorched holes and inner cloth. Quiet restrained personality. All motion gentle and small. No jumping, running, toe-rise or broad gestures: jumping name means grounded joyful response; movement means slow tiny walking steps. No extra props, effects, text, floor shadows. Lower microphone below chest for neutral small closed-mouth smile.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Exactly preserve attached refined Japanese anime chibi style, original head-body ratio, delicate linework, soft cel shading, brown curled hair and eyes, gold earrings, white/lavender-gray gown folds and hand-painted silver corset..
Animation continuity: keep apparent pet scale and baseline stable within the row in ALL states, including grounded `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

User-authoritative state action: System name jumping ONLY: grounded gentle joy, absolutely NO physical jump, hop, tiptoe, bounce, airborne pose or vertical translation. Five phases: soft neutral smile, slight chin lift, deeper small smile and gently open shoulders with LEFT hand softly near chest, hand lowers, return to neutral. Feet always grounded and hem baseline perfectly stable. RIGHT-hand microphone never changes hands.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.

All nine states: gentle small motion, stable scale and planted hem baseline. Preserve original face/head-to-body ratio and connected veil. Keep designed scorch holes, patina and inner cloth; do not add holes/seams. No detached effects, floor shadows or extra props.


## rows/look-row-10.md

Create one horizontal look-direction strip for Codex pet `GEM-bridal_2`, atlas row 10.

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

Place one centered pose in each invisible equal-width slot on flat pure user-selected #0000FF. Change only the natural parts needed to express gaze: eyes, eyelids, head, face, neck, upper body, appendages, and constrained prop follow-through. Keep identity, silhouette, materials, palette, markings, and props consistent.

ROW-BOUNDARY LOCK: 180 must continue directly from row 9's 157.5, matching its body size, baseline, planted anchor, expression, and construction. 337.5 must be one even 22.5-degree step before 000: nearly up-facing while remaining on the overall left-hand arc. Do not distort pupils, nose, or body geometry merely to exaggerate the subtle horizontal component.

PRE-RETURN CHECK: reject this result if it does not contain eight separated pose groups in the required order; neighboring poses overlap; foreground is cropped at the outer canvas edge; any frame changes sprite scale, body or head size, baseline, or planted-body position; the row visibly reverses into the wrong half of the loop; or 180 does not continue from 157.5 or 337.5 does not flow evenly into 000. Minor intermediate pupil or nose deviations are not rejection reasons. Exact cell cropping, resizing, and recentering happen deterministically after generation.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement/googly eyes, labels, degree text, arrows, clocks, grids, shadows, glows, scenery, detached effects, or chroma-key colors inside the pet.

PET-SPECIFIC MECHANICS (authoritative):
# 文静婚纱版 · 注视运动方案

Approved standard57frames inspected independently. Preserve this humanoid character's exact face, skull/eye proportions, calm small smile, LEFT shoulder neckline and anatomical RIGHT-hand gold microphone. Do not mirror face/body/costume to create leftward looks.

Lower gown, hips, feet and hem baseline stay planted and at the same scale in all16 directions. Eyes lead: redraw the brown anime eyes coherently inside original apertures, with iris/pupil, sclera, lid contour and highlights coordinated; never floating/googly pupils. Head turns gently at neck with only necessary shoulder follow-through. Preserve skull and feature spacing; no raster warps or whole-sprite rotation.

Cardinal families in SCREEN coordinates:
- 000 UP: broadly frontal head, small chin lift, irises and lids clearly aim upward. Some under-chin visible, no horizontal turn. Distinct from neutral.
- 090 RIGHT: gentle but unmistakable head yaw to viewer RIGHT (roughly25-30degrees), nose and pupils right of headcenter. Left visible facial plane expands while far right eye foreshortens as appropriate. Do not turn lower body or swap hands.
- 180 DOWN: broadly frontal head gently bows, chin nearer neckline, eyelids lower and pupils look down. Hair crown becomes slightly more visible; face not crushed. Distinct from closed-eye idleblink.
- 270 LEFT: gentle unmistakable yaw to viewer LEFT, nose and pupils left of headcenter. Opposite facial-plane visibility to090, naturally redrawn without mirroring costume or hair. Do not let leftcardinal remain frontal/right.

Motion budget: small pitch about8-12degrees, yaw25-30max, minute shoulderfollow only; angles denote ATTENTION targets, not rotating wholebody byclockangle. Even22.5degree attention steps with gradual consistent changes. Each nearcardinal secondary axis may be subtle, but no wrongquadrant/reversal. 157.5to180 and337.5to000 are ordinary adjacent steps, no snap or scalechange.

Veil root remains fixed to original crown/rearhead attachment and follows head softly; long lower veil remains behindbody, same length, no drift or hairpenetration. Curls and gold earrings follow natural attachment with restrained movement, no whipping. Mic stays anatomical RIGHT hand belowchest, away fromface/hair/veil; hand/arm makes minute near-rigid follow-through, no teleport or switchedgrip. Free LEFT hand gently holds skirt. Scorchholes andcopperpatina retain main positions/distribution; distinguish whiteinnercloth from transparency. Fullsilhouette remains insideeverycell.

All4cardinals must read unmistakably at192x208 withoutlabels. No singing, walking, jumping or largegestures during gaze. All16 form one quiet continuousfamily. No labels/shadows/props/effects.

SOURCE LAYOUT: use the attached spacious2176x724eight-slot guide, one entire figure insideeach safeinner rectangle. Aim figurewidth<=210, bodyheight<=370 with consistenthead/bodyratio. Generous35pxoutermargins and25pxgaps. Do not growfigures to fillcanvas orshortengown/veil. Rawpixel scale ofrow10 must match completedrow9exactly; row9 source size willbe supplied before row10. Guide onlyconstruction, no visible marks.
ROW10 RAW SOURCE SCALE LOCK: completed row9 source is2172x724 with entire figureheights424-426px, topapproximately167-170 and hembaseline593. Match this native rawpixelscale exactly: row10 figures420-425px tall, samehead/body proportions, tops~168 andhem~593. Use canvas2172x724 eightpositions. Do not enlarge toward referenceoriginal size or fillheight. Row9 is for IDENTITY/SCALE/REGISTRATION ONLY, not its rightward gaze. Row10 must follow approved LEFT cardinalfamily through DOWN->DOWNLEFT->LEFT->UPLEFT. The270 pose must unequivocally aim nose/eyes toward screenLEFT, notfront/right. Keep anatomicalright microphone/leftshoulder fixed. Last337.5 should approach row9UP onegentle stepbefore. No closedeyes hidingcardinaldirection; brown eyes readable. Preserve allmaincostume details andnatural smallheadturns.

REPAIR ATTEMPT2 — change root causes, preserve identity:
The rejected attempt drew7/8 as UP-RIGHT and grew bodyheight472, connecting allskirts. This must not recur.
Completedrow9 is now FIRST reference and conveys RAW PIXEL SCALE ONLY. The approvedcardinalstrip is LAST and is the sole directionauthority. Its fourthpose270 shows correct screenLEFT. For ALL poses2through8, maintain nose/chin and both pupils on the SCREEN LEFT side of headcenter, with the LEFT-facing faceplane. Poses6,7,8 lift gaze while staying LEFT; do NOT copy up-right faces from row9. Pose8 may approach frontalup but retains distinct slightLEFT bias. Do not mirror entirebody/shoulder/microphone. Pose5 is clearly LEFT. Pose1 is centeredDOWN.
Size: render entirefigures420pxhigh MAXIMUM, not470 orlarger. Canvas2172x724. Top170, hem590. 8 equallyspacedpositions135,407,678,950,1221,1493,1764,2036. Full figurewidth<=250 includingveil, clearforegroundgaps>=18px, outeredgesatleast20px. Maintain originalhead/bodyratio by drawing entirefiguressmaller, never shorteninggown/veil orcompressingface. Row9 figures426pxhigh willbecomenearly198pxfinal;420pxheight here gives195pxfinal and willfit approvedtransform. Do not use large originalportraitref as canvasfill target.


## rows/look-row-9.md

Create one horizontal look-direction strip for Codex pet `GEM-bridal_2`, atlas row 9.

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

Place one centered pose in each invisible equal-width slot on flat pure user-selected #0000FF. Change only the natural parts needed to express gaze: eyes, eyelids, head, face, neck, upper body, appendages, and constrained prop follow-through. Keep identity, silhouette, materials, palette, markings, and props consistent.

ROW-BOUNDARY LOCK: 157.5 must be one even 22.5-degree step before 180. Match the approved 180 pose's body size, baseline, planted anchor, expression, and construction. Preserve the overall right-hand arc, but do not distort pupils, nose, or body geometry merely to exaggerate the subtle horizontal component.

PRE-RETURN CHECK: reject this result if it does not contain eight separated pose groups in the required order; neighboring poses overlap; foreground is cropped at the outer canvas edge; any frame changes sprite scale, body or head size, baseline, or planted-body position; the row visibly reverses into the wrong half of the loop; or 157.5 does not flow evenly into 180. Minor intermediate pupil or nose deviations are not rejection reasons. Exact cell cropping, resizing, and recentering happen deterministically after generation.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement/googly eyes, labels, degree text, arrows, clocks, grids, shadows, glows, scenery, detached effects, or chroma-key colors inside the pet.

PET-SPECIFIC MECHANICS (authoritative):
# 文静婚纱版 · 注视运动方案

Approved standard57frames inspected independently. Preserve this humanoid character's exact face, skull/eye proportions, calm small smile, LEFT shoulder neckline and anatomical RIGHT-hand gold microphone. Do not mirror face/body/costume to create leftward looks.

Lower gown, hips, feet and hem baseline stay planted and at the same scale in all16 directions. Eyes lead: redraw the brown anime eyes coherently inside original apertures, with iris/pupil, sclera, lid contour and highlights coordinated; never floating/googly pupils. Head turns gently at neck with only necessary shoulder follow-through. Preserve skull and feature spacing; no raster warps or whole-sprite rotation.

Cardinal families in SCREEN coordinates:
- 000 UP: broadly frontal head, small chin lift, irises and lids clearly aim upward. Some under-chin visible, no horizontal turn. Distinct from neutral.
- 090 RIGHT: gentle but unmistakable head yaw to viewer RIGHT (roughly25-30degrees), nose and pupils right of headcenter. Left visible facial plane expands while far right eye foreshortens as appropriate. Do not turn lower body or swap hands.
- 180 DOWN: broadly frontal head gently bows, chin nearer neckline, eyelids lower and pupils look down. Hair crown becomes slightly more visible; face not crushed. Distinct from closed-eye idleblink.
- 270 LEFT: gentle unmistakable yaw to viewer LEFT, nose and pupils left of headcenter. Opposite facial-plane visibility to090, naturally redrawn without mirroring costume or hair. Do not let leftcardinal remain frontal/right.

Motion budget: small pitch about8-12degrees, yaw25-30max, minute shoulderfollow only; angles denote ATTENTION targets, not rotating wholebody byclockangle. Even22.5degree attention steps with gradual consistent changes. Each nearcardinal secondary axis may be subtle, but no wrongquadrant/reversal. 157.5to180 and337.5to000 are ordinary adjacent steps, no snap or scalechange.

Veil root remains fixed to original crown/rearhead attachment and follows head softly; long lower veil remains behindbody, same length, no drift or hairpenetration. Curls and gold earrings follow natural attachment with restrained movement, no whipping. Mic stays anatomical RIGHT hand belowchest, away fromface/hair/veil; hand/arm makes minute near-rigid follow-through, no teleport or switchedgrip. Free LEFT hand gently holds skirt. Scorchholes andcopperpatina retain main positions/distribution; distinguish whiteinnercloth from transparency. Fullsilhouette remains insideeverycell.

All4cardinals must read unmistakably at192x208 withoutlabels. No singing, walking, jumping or largegestures during gaze. All16 form one quiet continuousfamily. No labels/shadows/props/effects.

SOURCE LAYOUT: use the attached spacious2176x724eight-slot guide, one entire figure insideeach safeinner rectangle. Aim figurewidth<=210, bodyheight<=370 with consistenthead/bodyratio. Generous35pxoutermargins and25pxgaps. Do not growfigures to fillcanvas orshortengown/veil. Rawpixel scale ofrow10 must match completedrow9exactly; row9 source size willbe supplied before row10. Guide onlyconstruction, no visible marks.


## rows/review.md

Create one horizontal animation strip for Codex pet `GEM-bridal_2`, state `review`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 6 full-body frames in one left-to-right row on flat pure user-selected #0000FF. Treat the row as 6 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Only appearance authority is supplied reference. Anatomical RIGHT hand holds gold microphone with black bands (viewer LEFT front), anatomical LEFT shoulder covered by single shoulder neckline (viewer RIGHT). Preserve copper-brown lower corset weathering, full length pleated gown, attached long veil, existing scorched holes and inner cloth. Quiet restrained personality. All motion gentle and small. No jumping, running, toe-rise or broad gestures: jumping name means grounded joyful response; movement means slow tiny walking steps. No extra props, effects, text, floor shadows. Lower microphone below chest for neutral small closed-mouth smile.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Exactly preserve attached refined Japanese anime chibi style, original head-body ratio, delicate linework, soft cel shading, brown curled hair and eyes, gold earrings, white/lavender-gray gown folds and hand-painted silver corset..
Animation continuity: keep apparent pet scale and baseline stable within the row in ALL states, including grounded `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

User-authoritative state action: Review completed results: small head dip, eyes slowly scan a small range, pause, lift eyes, slight confirming nod and very faint reassured smile. Free hand at skirt, right-hand microphone steady. Distinct from downward thinking and idle.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.

All nine states: gentle small motion, stable scale and planted hem baseline. Preserve original face/head-to-body ratio and connected veil. Keep designed scorch holes, patina and inner cloth; do not add holes/seams. No detached effects, floor shadows or extra props.


## rows/running-left.md

Create one horizontal animation strip for Codex pet `GEM-bridal_2`, state `running-left`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 8 full-body frames in one left-to-right row on flat pure user-selected #0000FF. Treat the row as 8 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Only appearance authority is supplied reference. Anatomical RIGHT hand holds gold microphone with black bands (viewer LEFT front), anatomical LEFT shoulder covered by single shoulder neckline (viewer RIGHT). Preserve copper-brown lower corset weathering, full length pleated gown, attached long veil, existing scorched holes and inner cloth. Quiet restrained personality. All motion gentle and small. No jumping, running, toe-rise or broad gestures: jumping name means grounded joyful response; movement means slow tiny walking steps. No extra props, effects, text, floor shadows. Lower microphone below chest for neutral small closed-mouth smile.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Exactly preserve attached refined Japanese anime chibi style, original head-body ratio, delicate linework, soft cel shading, brown curled hair and eyes, gold earrings, white/lavender-gray gown folds and hand-painted silver corset..
Animation continuity: keep apparent pet scale and baseline stable within the row in ALL states, including grounded `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

User-authoritative state action: Slow tiny walking steps facing and moving screen LEFT. Not running. Free anatomical LEFT hand slightly lifts the long skirt; anatomical RIGHT hand holds microphone steadily. Eight phases with alternating tiny toe/hem changes and gentle lag of attached veil and curls. Torso almost level, no bouncing, no high knees. Preserve full-length skirt and asymmetry, independently redraw LEFT facing, never mirror identity.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.

All nine states: gentle small motion, stable scale and planted hem baseline. Preserve original face/head-to-body ratio and connected veil. Keep designed scorch holes, patina and inner cloth; do not add holes/seams. No detached effects, floor shadows or extra props.

REPAIR COMPOSITION: updated attached guide is 2176x724, eight 272px slots with safe inner rectangles. Fit each entire character including trailing veil inside its BLUE INNER rectangle, with width<=195px and height<=360px. Do not enlarge figures to fill canvas. Keep huge empty margins above/below and clear gaps. Rightmost veil must end at least38px before canvas edge. Guide only invisible construction, no visible boxes. Same character ratio and face; solve with smaller full figures, never shorten veil or skirt.


## rows/running-right.md

Create one horizontal animation strip for Codex pet `GEM-bridal_2`, state `running-right`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 8 full-body frames in one left-to-right row on flat pure user-selected #0000FF. Treat the row as 8 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Only appearance authority is supplied reference. Anatomical RIGHT hand holds gold microphone with black bands (viewer LEFT front), anatomical LEFT shoulder covered by single shoulder neckline (viewer RIGHT). Preserve copper-brown lower corset weathering, full length pleated gown, attached long veil, existing scorched holes and inner cloth. Quiet restrained personality. All motion gentle and small. No jumping, running, toe-rise or broad gestures: jumping name means grounded joyful response; movement means slow tiny walking steps. No extra props, effects, text, floor shadows. Lower microphone below chest for neutral small closed-mouth smile.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Exactly preserve attached refined Japanese anime chibi style, original head-body ratio, delicate linework, soft cel shading, brown curled hair and eyes, gold earrings, white/lavender-gray gown folds and hand-painted silver corset..
Animation continuity: keep apparent pet scale and baseline stable within the row in ALL states, including grounded `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

User-authoritative state action: Slow tiny walking steps facing and moving screen RIGHT. Not running. Free anatomical LEFT hand slightly lifts the long skirt; anatomical RIGHT hand holds microphone steadily. Eight phases with alternating tiny toe/hem changes and gentle lag of attached veil and curls. Torso almost level, no bouncing, no high knees. Preserve full-length skirt and asymmetry, never mirror identity.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.

All nine states: gentle small motion, stable scale and planted hem baseline. Preserve original face/head-to-body ratio and connected veil. Keep designed scorch holes, patina and inner cloth; do not add holes/seams. No detached effects, floor shadows or extra props.


## rows/running.md

Create one horizontal animation strip for Codex pet `GEM-bridal_2`, state `running`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 6 full-body frames in one left-to-right row on flat pure user-selected #0000FF. Treat the row as 6 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Only appearance authority is supplied reference. Anatomical RIGHT hand holds gold microphone with black bands (viewer LEFT front), anatomical LEFT shoulder covered by single shoulder neckline (viewer RIGHT). Preserve copper-brown lower corset weathering, full length pleated gown, attached long veil, existing scorched holes and inner cloth. Quiet restrained personality. All motion gentle and small. No jumping, running, toe-rise or broad gestures: jumping name means grounded joyful response; movement means slow tiny walking steps. No extra props, effects, text, floor shadows. Lower microphone below chest for neutral small closed-mouth smile.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Exactly preserve attached refined Japanese anime chibi style, original head-body ratio, delicate linework, soft cel shading, brown curled hair and eyes, gold earrings, white/lavender-gray gown folds and hand-painted silver corset..
Animation continuity: keep apparent pet scale and baseline stable within the row in ALL states, including grounded `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

User-authoritative state action: Quiet task processing, never locomotion or singing. Right-hand microphone slightly lowered. Eyes gently lower, pause in concentration, small slow nod, return to thoughtful focus. Free left hand naturally rests in front near waist; no repeated gestures and no hand at chin. Planted lower body.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.

All nine states: gentle small motion, stable scale and planted hem baseline. Preserve original face/head-to-body ratio and connected veil. Keep designed scorch holes, patina and inner cloth; do not add holes/seams. No detached effects, floor shadows or extra props.


## rows/waiting.md

Create one horizontal animation strip for Codex pet `GEM-bridal_2`, state `waiting`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 6 full-body frames in one left-to-right row on flat pure user-selected #0000FF. Treat the row as 6 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Only appearance authority is supplied reference. Anatomical RIGHT hand holds gold microphone with black bands (viewer LEFT front), anatomical LEFT shoulder covered by single shoulder neckline (viewer RIGHT). Preserve copper-brown lower corset weathering, full length pleated gown, attached long veil, existing scorched holes and inner cloth. Quiet restrained personality. All motion gentle and small. No jumping, running, toe-rise or broad gestures: jumping name means grounded joyful response; movement means slow tiny walking steps. No extra props, effects, text, floor shadows. Lower microphone below chest for neutral small closed-mouth smile.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Exactly preserve attached refined Japanese anime chibi style, original head-body ratio, delicate linework, soft cel shading, brown curled hair and eyes, gold earrings, white/lavender-gray gown folds and hand-painted silver corset..
Animation continuity: keep apparent pet scale and baseline stable within the row in ALL states, including grounded `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

User-authoritative state action: Patient quiet attentive waiting: slight soft head tilt, calm direct gaze, natural right-hand microphone and left hand at skirt. Small slow blink then attentive reopen. Do not look impatient or demanding. No broad gesture. Gentle held posture distinct from idle.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.

All nine states: gentle small motion, stable scale and planted hem baseline. Preserve original face/head-to-body ratio and connected veil. Keep designed scorch holes, patina and inner cloth; do not add holes/seams. No detached effects, floor shadows or extra props.


## rows/waving.md

Create one horizontal animation strip for Codex pet `GEM-bridal_2`, state `waving`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 4 full-body frames in one left-to-right row on flat pure user-selected #0000FF. Treat the row as 4 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Only appearance authority is supplied reference. Anatomical RIGHT hand holds gold microphone with black bands (viewer LEFT front), anatomical LEFT shoulder covered by single shoulder neckline (viewer RIGHT). Preserve copper-brown lower corset weathering, full length pleated gown, attached long veil, existing scorched holes and inner cloth. Quiet restrained personality. All motion gentle and small. No jumping, running, toe-rise or broad gestures: jumping name means grounded joyful response; movement means slow tiny walking steps. No extra props, effects, text, floor shadows. Lower microphone below chest for neutral small closed-mouth smile.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Exactly preserve attached refined Japanese anime chibi style, original head-body ratio, delicate linework, soft cel shading, brown curled hair and eyes, gold earrings, white/lavender-gray gown folds and hand-painted silver corset..
Animation continuity: keep apparent pet scale and baseline stable within the row in ALL states, including grounded `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

User-authoritative state action: Quiet familiar greeting: small eye lift and little nod, free LEFT hand rises only near front of torso, makes one tiny gentle sway, and returns beside skirt. Four phases: rest, small lift/nod, small hand sway, soft return. Never raise hand above shoulders. RIGHT hand holds microphone steady.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.

All nine states: gentle small motion, stable scale and planted hem baseline. Preserve original face/head-to-body ratio and connected veil. Keep designed scorch holes, patina and inner cloth; do not add holes/seams. No detached effects, floor shadows or extra props.
