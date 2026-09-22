# G.E.M. · 生成提示词与修复模板

使用内置 imagegen，附件是唯一外观依据，布局图仅用于排列。此文档汇总主提示词、已用修复提示词及预备重试模板；预备模板不代表发生过对应重试，实际选定生成结果见 qa/generation-log.json。

## base-pet.md

Create one clean full-body reference sprite for Codex pet G.E.M..

Pet identity: Supplied image is sole appearance authority. Preserve exact face, hairstyle partition and clothing asymmetry. Anatomical RIGHT hand holds black wireless mic (viewerLEFT front), left hand free. Neutralpose only lower microphone belowchest and relaxfreehand, plantbothfeet. No new props, shadows,effects,text. Allrows fixedmic side, attachedhair/accessories; nevermirror..
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Precisely preserve supplied Japanese anime chibi: original head/body ratio, brown large anime eyes, deepbrown long curls, fine linework, soft cel shading, subtle gradients and hair highlights. Black cropped biker stage jacket, dark glitter top, silver hardware/earrings, black long trousers and platform ankleboots. No realistic/plush/3D style..


Place a single centered pose on a perfectly flat pure user-selected #00FF00 chroma-key background. Keep the full pet visible, compact, readable at 192x208, and easy to animate. Preserve approved reference identity cues. No scenery, text, borders, checkerboard transparency, shadows, glows, detached effects, or extra props. Keep #00FF00 and close colors out of the pet, props, highlights, and effects.
Normalize ONLY the supplied confirmed illustration into a neutral full-body standing reference: keep exact original face, eye design, deepbrown hairpart/curls/length, silver earrings, every stage-costume shape, black cropped jacket/dark crop top/silver hardware, long black trousers, boots and original largehead/smallbody ratio. Do not redesign or simplify into a different mascot. Bothfeet planted and parallel, leftfreehand softlyrelaxed, right-hand blackmic lowered to belowchest. A soft smallsmile, no singing orwave. Anatomical right=viewerleft in frontview. Transparentbackgroundpreferred: actualalphatransparency, notpaintedcheckerboard. Generous12%clear margins allaroundfullsilhouette. If opaque backgroundnecessary useonly#00FF00. No groundshadow ornewprops/effects.


## look-anchor-repairs/000.md

Repair one cardinal anchor for Codex pet `gem-stage`: `000` means looking up.

Use the canonical base, completed standard contact sheet, approved cardinal-strip cells, and `qa/look-mechanics.md` for identity, scale, registration, and pet-specific gaze mechanics. Keep the face broadly frontal and point the eyes and natural head mechanism toward the TOP edge. Screen coordinates are viewer-relative.

Output one centered complete full-body pose on a flat pure user-selected #00FF00 background with generous padding. Keep the feet/base and lower body registered to the approved anchors. The requested cardinal must be unmistakable at final 192x208 display size.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement eyes, labels, arrows, guide marks, shadows, scenery, detached effects, or chroma-key colors inside the pet.


## look-anchor-repairs/090.md

Repair one cardinal anchor for Codex pet `gem-stage`: `090` means looking right.

Use the canonical base, completed standard contact sheet, approved cardinal-strip cells, and `qa/look-mechanics.md` for identity, scale, registration, and pet-specific gaze mechanics. Put the nose tip, pupils, face surface, or natural aiming feature on the screen-right side of the head center. Screen coordinates are viewer-relative.

Output one centered complete full-body pose on a flat pure user-selected #00FF00 background with generous padding. Keep the feet/base and lower body registered to the approved anchors. The requested cardinal must be unmistakable at final 192x208 display size.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement eyes, labels, arrows, guide marks, shadows, scenery, detached effects, or chroma-key colors inside the pet.


## look-anchor-repairs/180.md

Repair one cardinal anchor for Codex pet `gem-stage`: `180` means looking down.

Use the canonical base, completed standard contact sheet, approved cardinal-strip cells, and `qa/look-mechanics.md` for identity, scale, registration, and pet-specific gaze mechanics. Keep the face broadly frontal and point the eyes and natural head mechanism toward the BOTTOM edge. Screen coordinates are viewer-relative.

Output one centered complete full-body pose on a flat pure user-selected #00FF00 background with generous padding. Keep the feet/base and lower body registered to the approved anchors. The requested cardinal must be unmistakable at final 192x208 display size.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement eyes, labels, arrows, guide marks, shadows, scenery, detached effects, or chroma-key colors inside the pet.


## look-anchor-repairs/270.md

Repair one cardinal anchor for Codex pet `gem-stage`: `270` means looking left.

Use the canonical base, completed standard contact sheet, approved cardinal-strip cells, and `qa/look-mechanics.md` for identity, scale, registration, and pet-specific gaze mechanics. Put the nose tip, pupils, face surface, or natural aiming feature on the screen-left side of the head center. Screen coordinates are viewer-relative.

Output one centered complete full-body pose on a flat pure user-selected #00FF00 background with generous padding. Keep the feet/base and lower body registered to the approved anchors. The requested cardinal must be unmistakable at final 192x208 display size.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement eyes, labels, arrows, guide marks, shadows, scenery, detached effects, or chroma-key colors inside the pet.


## look-cardinals.md

CreateONE horizontal strip with exactly4completefullbody poses ofthe SAMEapprovedblackstageanimechibi. Attachoriginal/canonical/standardcontactsheetforidentity; guideONLYspacing.
Left-to-right order: unmistakableUP, screenRIGHT, DOWN, screenLEFT.
UP: facecentered, chinlift15degrees, underchinvisible, irisesclearlyHIGHintheoriginalanimeeyeapertures withlightsclerabelow. MustreadlookingOVERHEADnotfront.
RIGHT: nose/chin/pupils atscreenRIGHTofheadcenter, gentle25degreeheadyaw. DOWN: centeredgentleheadbow, loweredpupils/lids, chinclosercollar. LEFT: nose/chin/pupils atscreenLEFTofheadcenter withoppositefacialplane; notfrontalorright.
Keeporiginalskull/eyeproportions, warmtinyclosedmouthsmile, hairpart/curls, blackjacket/darktop/silverhardware/trousers/boots. Anatomical RIGHT-handblackmicbelowchest andLEFTfreearmrelaxed unchanged; nevermirror. Feetplanted/bodyfront, onlyeyes/head/neckandsmallshoulderfollow. Hair/earringsattached. No facialstretch/wholebodytilt orprops crossingface.
Exactly4separatedwholefiguresonecoherentfamily. Source2176x724, figureheight~480px,width<=300, generousgaps/outermargins. Fullhair/bootsvisible. Actualtransparency, no labels/guide/effects/shadows.


## row-retries/failed-layout-repair.md

Edit sprite strip image 1 for layout only using image 2 as invisible spacing template. Preserve these EXACT eight character drawings, their facial variations, microphone in anatomical right hand viewer LEFT, relaxed free left hand, hair and clothes. Main correction: SHRINK every character uniformly to 70% its current rendered size, preserving the original canvas 2172x724. Center them at x=136,408,680,952,1224,1496,1768,2040, y=362. Each full figure should be about 400 pixels tall and 200 pixels wide. There must be CLEAR TRANSPARENT EMPTY GAPS at least 55 pixels wide between all eight silhouettes. Large transparent top and bottom margins at least 150px tall. Never fill the canvas; small character drawings in a big empty canvas. The entire first and eighth silhouettes must be fully inside canvas with generous transparent outer margins. Keep exactly eight figures on one horizontal row, same baseline, all whole boots/hair. True alpha transparency no shadows, no checkerboard, no guides, no text. Do not let hair touch adjacent frame. Final frame mouth a gentle closed smile.


## row-retries/failed.md

Create one coherent horizontal strip of exactly 8 complete full-body animation frames for Codex pet G.E.M., state failed.

Soleappearanceauthority is originalapprovedblackstageillustration. Preserve exact originalface, largebrowneyedesign, originalhead/bodyratio, deepbrownlongcurlyhairpart, silverdanglingearrings, croppedblackbikerjacket withsilverhardware, darkcroptop, blacktrousers withasymmetricbelts/straps, blackplatformankleboots. Anatomical RIGHT hand alwaysholdsblackwirelessmic (viewerLEFT front); freeLEFThand. Nevermirror. Fineanime linework/softcelshading, not3D/photo/plush. Noaddedprops/text/logo/shadow/background/effects.

Action: 8phase mildregret: normal, eyeslower, smilebrieflysoftensaway, littleheadtilt, smallthoughtfulpause, gaze lifts, softsmilerestores, return. No tears/crying, exaggeratedslump, sigh, symbols/effects. Stablefeet, micsteady.

Use attached original and canonicalidentity, and layoutguide ONLY for invisible equalspacing. Keepfullhair/boots/accessoriesinsideeachslot, nooverlap orouteredgeclipping. Landscape2176x724source, generousblankspaceaboveandbelow, onecenteredfigureperequalslot. For8slots keepdrawnfigureheightabout380-410pixels,maxwidth220pixels; forfewerframes keepfigureheightabout450pixels. Consistentbody/headscale acrossallframes; baseline stable except smallrunbob or intendedjump. Animate attachedparts naturally, no detachedhardware orhair. Background trulytransparentpreferred; ifopaqueuseflat#00FF00only. No guidepixels, borders, labels orcheckerboard.


## row-retries/idle-layout-repair.md

Use case: identity-preserve. EDIT image 4, the six-frame idle animation strip, to repair layout only. Images 1 and 3 are original character appearance and canonical identity references. Image 2 is invisible spacing guide only, never draw its lines. Canvas exactly 2172x724, a horizontal strip of exactly SIX full-body figures. The current six figures are MUCH TOO BIG and touch. Uniformly REDUCE ALL SIX WHOLE FIGURES TO 70% of their current size: current height 662 pixels becomes target height 460 pixels, maximum width 250 pixels. Do NOT shorten hair or body, uniformly scale every complete figure including head, hair, boots, microphone and accessories. Center the six figures at x=181,543,905,1267,1629,1991; head tops around y=140, boot soles around y=600. Large empty space above and below is INTENTIONAL and REQUIRED. At least 60 pixels of empty transparent gap between every pair of silhouettes, at least 50 pixels outer left and right margin. Full silhouette and all hair contained, no clipping, no touching. Preserve the exact face, original large brown eye shape, head/body ratio, long curly brown hair, silver dangling earrings, cropped black biker jacket, dark crop top, black trousers with asymmetric straps, platform boots. Preserve coherent six sequential phases: rest, inhale, half blink, closed blink, reopen, rest. Gentle breathing only, feet fixed. Anatomical RIGHT hand holds same black wireless microphone low below chest in ALL six frames (viewer LEFT); free LEFT hand relaxed. Never mirror or swap hands. Fine anime linework with soft cel shading, preserve identity and clothing details. Exactly six complete figures, no extra frames or new props. True transparent alpha background. No shadows, text, guides, grid, border, checkerboard, decorative effect, or detached pieces. This is a spacing repair of the complete coherent row, not a redesign.


## row-retries/idle.md

Create one coherent horizontal strip of exactly 6 complete full-body animation frames for Codex pet G.E.M., state idle.

Soleappearanceauthority is originalapprovedblackstageillustration. Preserve exact originalface, largebrowneyedesign, originalhead/bodyratio, deepbrownlongcurlyhairpart, silverdanglingearrings, croppedblackbikerjacket withsilverhardware, darkcroptop, blacktrousers withasymmetricbelts/straps, blackplatformankleboots. Anatomical RIGHT hand alwaysholdsblackwirelessmic (viewerLEFT front); freeLEFThand. Nevermirror. Fineanime linework/softcelshading, not3D/photo/plush. Noaddedprops/text/logo/shadow/background/effects.

Action: Quiet breathing and one gentle slow blink, tiny attached curl sway. Mic in anatomical RIGHT hand below chest, LEFT freehand relaxed. 6phases: rest, inhale, halfblink, closedblink, reopen, rest. No waving, singing, footsteps or broad gesture. Visible microvariation with stablefeet.

Use attached original and canonicalidentity, and layoutguide ONLY for invisible equalspacing. Keepfullhair/boots/accessoriesinsideeachslot, nooverlap orouteredgeclipping. Landscape2176x724source, generousblankspaceaboveandbelow, onecenteredfigureperequalslot. For8slots keepdrawnfigureheightabout380-410pixels,maxwidth220pixels; forfewerframes keepfigureheightabout450pixels. Consistentbody/headscale acrossallframes; baseline stable except smallrunbob or intendedjump. Animate attachedparts naturally, no detachedhardware orhair. Background trulytransparentpreferred; ifopaqueuseflat#00FF00only. No guidepixels, borders, labels orcheckerboard.


## row-retries/jumping.md

Create one coherent horizontal strip of exactly 5 complete full-body animation frames for Codex pet G.E.M., state jumping.

Soleappearanceauthority is originalapprovedblackstageillustration. Preserve exact originalface, largebrowneyedesign, originalhead/bodyratio, deepbrownlongcurlyhairpart, silverdanglingearrings, croppedblackbikerjacket withsilverhardware, darkcroptop, blacktrousers withasymmetricbelts/straps, blackplatformankleboots. Anatomical RIGHT hand alwaysholdsblackwirelessmic (viewerLEFT front); freeLEFThand. Nevermirror. Fineanime linework/softcelshading, not3D/photo/plush. Noaddedprops/text/logo/shadow/background/effects.

Action: 5phase compactjoyfuljump: slightkneebend preparation, smallupwardtakeoff, lowairborneapex, softbentkneelanding, relaxedstand. Samebody/headscale; preservevisibleverticalmotion. Micneverleaves anatomicalRIGHT hand. Curls softlyliftandsettle. Entirehead/hair/boots stayinsideframe. No groundshadow/dust/landingmarks.

Use attached original and canonicalidentity, and layoutguide ONLY for invisible equalspacing. Keepfullhair/boots/accessoriesinsideeachslot, nooverlap orouteredgeclipping. Landscape2176x724source, generousblankspaceaboveandbelow, onecenteredfigureperequalslot. For8slots keepdrawnfigureheightabout380-410pixels,maxwidth220pixels; forfewerframes keepfigureheightabout450pixels. Consistentbody/headscale acrossallframes; baseline stable except smallrunbob or intendedjump. Animate attachedparts naturally, no detachedhardware orhair. Background trulytransparentpreferred; ifopaqueuseflat#00FF00only. No guidepixels, borders, labels orcheckerboard.


## row-retries/look-row-10-four-percent-07.md

IMAGE1 is the complete coherent APPROVED direction row, only slightly too small. Edit it by drawing all EIGHT whole characters exactly4% LARGER, uniformly, maintaining their exact current body/head ratios, body shapes, silhouettes and poses. Preserve every facial gaze direction from IMAGE1. Do not redesign. Current fullbody height390–396px, desired working height415–420px on2172x724transparentcanvas. Keep enough transparent space to maintain eight separate silhouettes, no touching hair, all curls and boots fullyvisible. All8 same common scale, stable bootbaseline, even horizontal slots. Do not fill canvas.
Image2 approvedrow9 is SCALE REFERENCE ONLY, absolutely never copy its rightward gaze poses. Image3 lossless original/canonical above and standardanimationsbelow locks identity. Image4 spacing only. Image5 cardinal meanings.
Exact approvedimage1poses unchanged: DOWN; down/slightlyLEFT; DOWN-LEFT; LEFT/slightlydown; LEFT; LEFT/slightlyUP; UP-LEFT; UP/slightlyLEFT. Last7 retain left component, last3 gaze upwardleft. Same largebrown animeeyes, browncurls/hairpart, silverearrings, blackstagejacket/top/trousers/boots, asymmetricstraps, right-hand blackwirelessmic belowchest and relaxed lefthand. No mirroring, changedbodypose, text, guides, props, effects, shadows. Actualtransparentbackground. Only4% larger drawing of this same existing complete eight-pose row.


## row-retries/look-row-10-fresh-09.md

Create ONE transparent 2172×724 PNG: a coherent horizontal row of EXACTLY EIGHT complete black-stage anime chibi gaze poses.
Image 1 supplies the correct LEFT-HALF poses; enlarge their drawing scale by about 7.5% to match image 2. Image 2 supplies ONLY the approved 421–423 pixel figure height, head/body scale and baseline; do not copy its rightward gaze. Image 3 supplies original and canonical identity. Image 4 is spacing/framing only: draw inside the blue rectangles but erase all guide graphics. Image 5 gives UP, RIGHT, DOWN, LEFT cardinal meanings.
Each figure approximately 420 pixels tall and 247 pixels wide on this 2172×724 canvas, crown near y153 and boots at y574. Keep 150 pixels blank above and below. Eight equally spaced centers x136,408,680,952,1224,1496,1768,2040; clear 20–25 pixel gaps. Full curls, hands and boots visible. Keep original proportions; never fill canvas height.
Exact left-to-right attention directions: (1) DOWN centered bowed head, (2) down with slight screen-left, (3) down-left, (4) left with slight down, (5) LEFT nose and pupils clearly left of head center, (6) left with slight up, (7) up-left, (8) up with slight left. All of poses 2–8 have screen-left component. Smooth small head yaw/pitch and eye changes; body, hips, feet fixed. Last three lift chin and pupils while still looking LEFT.
Preserve the exact original large brown anime eyes, face/head ratios, long brown curls and hair partition, silver earrings, black cropped jacket/top, silver hardware, asymmetric trouser straps and boots. Anatomical RIGHT hand holds black microphone below chest; anatomical LEFT hand relaxed. Draw all eight together as one consistent family. No mirroring, whole-body turning, shadows, text, guides, scenery, detached effects or extra objects. Genuine transparent background.


## row-retries/look-row-10-fresh-09b.md

Generate ONE transparent 2172×724 image, one coherent horizontal row of exactly EIGHT small complete full-body black-stage anime chibi poses, with broad transparent spacing.
Reference 1: correct LEFT-HALF gaze pose family. Reference 2: face construction, proportions and style continuity only. Reference 3: original and canonical character identity. Reference 4: NEW smaller framing boxes; all silhouette fits INSIDE each blue box, remove every guide pixel. Reference 5: cardinal meanings UP, RIGHT, DOWN, LEFT.
CRITICAL FRAMING: figure drawing height ONLY 360–370 pixels. Small full bodies occupy the middle HALF of canvas height. Use generous blank transparent top and bottom margins and clear 40–55px horizontal gaps between all hair silhouettes. Eight equal horizontal slots. Keep original head/body proportions; scale the entire drawing down uniformly, never shorten legs or enlarge heads. Do not fill the canvas. Hair, microphone, hands and boots all complete and separated.
Exact left-to-right directions: 1 DOWN centered bowed head; 2 down with slight screen-left; 3 down-left; 4 left with slight down; 5 LEFT with nose/pupils left of head center; 6 left with slight up; 7 up-left; 8 up with slight left. Every pose 2–8 retains a LEFT component. Match first reference's smooth head movement; final three lift chin and pupils while still pointing LEFT. Feet, hips and body stay planted, subtle head/neck pitch and yaw only.
Preserve exact original brown anime eyes, face construction, brown long curls/hair partition, silver earrings, black cropped jacket/top, hardware, asymmetric trouser straps and black boots. Anatomical RIGHT hand holds black microphone below chest, LEFT hand relaxed. All eight drawn together as one consistent family. True transparency, no background, no text, guides, shadows, effects, mirrors or extra objects.


## row-retries/look-row-10-fresh-09c.md

Generate ONE transparent 2172×724 image, one coherent horizontal row of exactly EIGHT small complete full-body black-stage anime chibi poses, with broad transparent spacing.
Reference 1: correct LEFT-HALF gaze pose family. Reference 2: face construction, proportions and style continuity only. Reference 3: original and canonical character identity. Reference 4: NEW smaller 357px-high framing boxes; all silhouette fits INSIDE each blue box, remove every guide pixel. Reference 5: cardinal meanings UP, RIGHT, DOWN, LEFT.
CRITICAL FRAMING: figure drawing height ONLY 340–350 pixels. Small full bodies occupy the middle HALF of canvas height. Use generous blank transparent top and bottom margins and clear 40–55px horizontal gaps between all hair silhouettes. Eight equal horizontal slots. Keep original head/body proportions; scale the entire drawing down uniformly, never shorten legs or enlarge heads. Do not fill the canvas. Hair, microphone, hands and boots all complete and separated.
Exact left-to-right directions: 1 DOWN centered bowed head; 2 down with slight screen-left; 3 down-left; 4 left with slight down; 5 LEFT with nose/pupils left of head center; 6 left with slight up; 7 up-left; 8 up with slight left. Every pose 2–8 retains a LEFT component. Match first reference's smooth head movement; final three lift chin and pupils while still pointing LEFT. Feet, hips and body stay planted at exactly the same baseline. Subtle head/neck pitch and yaw only. The last three upward-looking poses must not raise the entire head/body silhouette: retain the same crown-height envelope as earlier poses, lifting chin and gaze within the existing head space.
Preserve exact original brown anime eyes, face construction, brown long curls/hair partition, silver earrings, black cropped jacket/top, hardware, asymmetric trouser straps and black boots. Anatomical RIGHT hand holds black microphone below chest, LEFT hand relaxed. All eight drawn together as one consistent family. True transparency, no background, no text, guides, shadows, effects, mirrors or extra objects.


## row-retries/look-row-10-frozen-body-02.md

EDIT IMAGE 1, keeping its canvas, full-body scale, feet, bodies, microphone and layout frozen exactly. Eight poses. Change ONLY head pitch/yaw and eyes to gaze in the LEFT half of attention circle, in this exact order: DOWN; down/slightlyLEFT; DOWN-LEFT; LEFT/slightlydown; LEFT; LEFT/slightlyup; UP-LEFT; UP/slightlyLEFT. DO NOT make any rightward face or pupils. For poses6,7,8 nose and gaze remain on screenLEFT side while chin/eyes rise. Image5 fourth character is authoritative LEFT face structure; third is DOWN; first is UP. Image2 canonical original face/style, image3 layout only, image4 standard identity. Preserve all image1 lower body, hand/blackmic, costume, curls styling, proportions and geometry. No mirrored outfit/hair. Pose1 downcast visible eyes, not closed. FULLBODY height about422 pixels on2172x724 canvas, bootbaseline575 exactly as IMAGE1. At least15px blank margin each edge; separate silhouettes with gaps. Output true transparent, no text, guides, shadows. Critical edit: FIXED bodies from image1, all seven later faces look screenLEFT or upLEFT, never screenRIGHT.


## row-retries/look-row-10-guide-first-08.md

Create one coherent eight-pose chibi sprite strip using IMAGE1 as precise COMPOSITION GEOMETRY. Each of eight BLUE BOXES is247pixels wide by419pixels high on2176x724canvas; topy152 bottomy571. Each complete character should fit and nearly touch the box TOP and BOTTOM, fullbodyheight419±3px, natural original head/body ratio. Keep all8 uniformly same fullbodyheight. Silhouette approximately247pxwide maximum; adjacent figures have24px cleartransparentgaps. Geometry priority: match blueboxHEIGHT closely; do not enlarge beyond boxes. REMOVE all guide lines, boxes, grid and whitebackground from finaloutput. True transparentbackground.
IMAGE2 is the exact correct eight-direction character family to depict, including identity, natural body proportions, outfit, mic and facial directions. IMAGE3 approvedrow9 is SCALE/IDENTITY only, do NOT copy its rightward directions. IMAGE4 contains losslessoriginal/canonical above and approvedstandardanimationsbelow. IMAGE5 cardinalsUP RIGHT DOWN LEFT.
Draw all8 together as a coherent family matching image2; SAME directions: centeredDOWN; down/slightlyscreenLEFT; DOWN-LEFT; LEFT/slightlyDOWN; LEFT; LEFT/slightlyUP; UP-LEFT; UP/slightlyLEFT. Everypose2–8 retains leftwardcomponent; last3eyes/chinrise while face staysLEFT. No opposite quadrants. Original largebrownanimeeyes, browncurledhairpart, silverearrings, blackcroppedjacket, blacktop, asymmetrictrouserstraps, blackboots. AnatomicalRIGHT handblackwirelessmic belowchest, relaxedLEFThand. Plantedfeet and nearfrontalbody. No mirror, redesign, props, effects, shadows, text. Allcurls/hands/boots completelyinside eachbox, clear24pxgaps andoutermargins. Finaltransparent2176x724strip,8fullbodyfigures419±3pxhigh, guideart entirelyremoved.


## row-retries/look-row-10-middle-scale-05.md

Precise framing edit of IMAGE1. All eight poses are approved: preserve every gaze direction, face construction, exact body shape, head/body ratio, curl silhouette, outfit, mic, planted stance. Increase EACH complete character uniformly by ONLY6 percent from current390–396px to target414–420px fullbody height. Keep canvas2172x724, topabout153, bootsbottomabout570. Keep equally spaced horizontal centers and clear gaps. This is the middle size between current390px and rejected454px; DO NOT grow to454px or fill canvas. Entire8 figures exactly same common scale. Shoulders/hand/belt heights should be comparable to IMAGE2 approvedrow9 after baseline alignment.
Image1 EXACT EDIT TARGET, preserve its poses. Image2 row9 SCALE ONLY, never copy rightward faces. Image3 lossless original/canonical identity above, standard animations below. Image4 spacing only. Image5 cardinal direction meanings. Keep current approved firstDOWN then sevenLEFTcomponent directions, finalthreeUP-LEFT. Do not change facial directions or redesign. Same anatomical RIGHT hand blackwirelessmic belowchest, relaxed LEFT hand, same browncurled hairpart, silver earrings, blackjacket/top/trousers/boots and asymmetric straps. NO mirror, wholebodyrotation, addedprops, text, guides, shadows. Complete8 all drawn together as one row, actual transparentbackground. Only6% larger characters than image1, with original proportions.


## row-retries/look-row-10-scale-spacing-01.md

Repair row10 with scale and spacing ONLY. Input1 completed row9 is authoritative exact identity, source character SCALE and baseline; do NOT use its rightward directions. Input2 original/canonical identity. Input3 spacing guide only. Input4 standard identity. Input5 cardinal direction authority. The first row10 attempt had correct leftward gaze but was too large (439–444px high) and the curls nearly touched. Regenerate all EIGHT together at the correct size using image1's scale, original proportions and independent clear space between characters. Canvas 2172x724. Each entire character should be 421–423 pixels tall, baseline y575, top around y152. All eight head/body scales EXACTLY match image1 row9. No character may be taller than423px or wider than245px. Centers x136,408,680,952,1224,1496,1768,2040. Eight COMPLETE separate silhouettes, clear gaps at least20px, outer margins at least15px, entire curls/boots included. Do not enlarge to fill canvas.
Sequence: 1 centered DOWN bowed head with visible downcast brown irises, not closed eyelids. 2 down slight screenLEFT. 3 DOWN-LEFT. 4 LEFT slightlydown. 5 unmistakable LEFT. 6 LEFT slightlyup. 7 UP-LEFT. 8 mostlyUP slightLEFT, near overhead. Poses2–8 never face right. Last3 face LEFT while eyes/chin rise. Preserve exact original anime face, large brown eyes, curl hair part, silver earrings, black cropped jacket, dark top, silver hardware, asymmetric trouser straps, black boots. Anatomical RIGHT hand holds black wireless microphone belowchest in all8, free LEFT hand relaxed. Same planted feet and pelvis. No mirror or wholebody rotation, no newprops, text, guide lines, shadows/effects. Actual transparent background.


## row-retries/look-row-10-small-silhouettes-03.md

Create a complete eight-character row10 on a 2172x724 transparent canvas. CRITICAL SCALE REPAIR: previous complete row10 had character heights452–454 pixels. Draw ALL eight characters about11% smaller than that, target height395–410 pixels each (only55–56% of canvas height), NEVER enlarge to fill the canvas. Stable boot bottom y575, tops y165–180. Match the exact original identity/proportions, but SMALLER figures with ample transparent space above and below. Eight equal slots centered at x136,408,680,952,1224,1496,1768,2040. Each complete silhouette no wider than220px with at least45px transparent gap between neighbors. All curls/boots enclosed, clear outer margins. All eight drawn in one generation.
REFERENCES: image1 completed row9 for identity and proportions, NOT its rightward directions. Its characters are423px high; this new row should be SMALLER at395–410px, not larger. Image2 original/canonical identity. Image3 spacing only; no guides in output. Image4 standard animation identity. Image5 authoritative cardinals UP RIGHT DOWN LEFT, especially third DOWN and fourth LEFT.
Exact gaze sequence left-to-right:
1 DOWN, centered symmetrical bowed head, no lateral left or right yaw; eyes visibly downcast, chin toward collar, visible crown, NOT closed eyelids.
2 DOWN with slight screenLEFT.
3 DOWN-LEFT.
4 screenLEFT with slightDOWN.
5 clear screenLEFT.
6 screenLEFT with slightUP.
7 UP-LEFT.
8 mostlyUP retaining slight screenLEFT.
Nose and pupils in cells2–8 retain a leftward component. Final3 faces remain screenLEFT while eyes and chin rise. No rightward gaze. Natural head/neck turning only, planted feet/hips and nearfrontal torso. Preserve original brown anime eye construction, curled brown hair/part, silver earrings, black cropped jacket, dark top, silver hardware, asymmetric black trouser straps, black boots. Anatomical RIGHT hand holds black wirelessmic belowchest in all8; free LEFT relaxed. No mirror, no wholebody rotation. Same head/body size in all8. No text, panels, guides, background, shadows, effects or props. True transparent alpha background. Remember: small395–410px fullbody silhouettes, bottom575, not454px.


## row-retries/look-row-10-target-scale-panel-04.md

GEOMETRIC FRAMING EDIT OF IMAGE1. Keep all eight existing characters in image1 with exactly the SAME character anatomy, face identity, head/body ratio, curls, clothing, hands, blackmic, and gaze directions. Draw each entire silhouette uniformly8%SMALLER, from454px to about420px fullbody height, increasing only surrounding transparent whitespace. Keep horizontal centers evenly spaced across2172x724canvas and all boots bottomy575. Do not zoom or fill canvas. Preserve image1's coherent eight-pose family; no redesign.
Image1 is the EXACT EDIT TARGET and authoritative poses. Image2 row9 is SCALE REFERENCE ONLY: NEVER COPY its rightward gaze poses. Image3 is a lossless original/canonical identity panel above and standard animation contact sheet below. Image4 is spacing guide only. Image5 cardinals UP RIGHT DOWN LEFT confirm meanings.
Preserve direction sequence of image1: centeredDOWN; down/slightlyLEFT; DOWN-LEFT; LEFT/slightlydown; LEFT; LEFT/slightlyup; UP-LEFT; UP/slightlyLEFT. The first head should be centered DOWN with no lateral yaw (small correction ifneeded). All remaining seven retain SCREEN-LEFT component. Last3 keep LEFTward facial yaw while chin/eyes rise. Absolutely no rightward poses. Keep right-hand blackmic belowchest, left hand relaxed, original hair part and asymmetric clothing; never mirror. Eight complete separated silhouettes, entire hair and boots, uniform scale and clear gaps/outermargins. True transparent background, no text/guides/shadows/effects. Goal: same eight figures as IMAGE1 at92% of their present size; no other changes.


## row-retries/look-row-10-tiny-reduction-06.md

Edit IMAGE1 with an extremely small geometric framing adjustment ONLY. Reduce all eight existing complete characters uniformly by ONLY2.5percent. Preserve EXACTLY the current approved eight gaze poses, faces, head/body proportions, body shapes, curl designs, mic/hands, outfit and planted stance. No redesign. The current figures are438–444px tall; intended final working range410–420px. Keep canvas2172x724 and clear transparent gaps; eight separate full silhouettes, no touching hair, entire curls and boots, visible outer margins. Keep every character at same common scale and aligned baseline.
Image1 exact EDIT TARGET (eight correct left-half attention poses). Image2 row9 is scale reference ONLY, never copy its RIGHTward gaze. Image3 lossless original/canonical identity above and standard animations below. Image4 layout spacing only. Image5 UP RIGHT DOWN LEFT cardinals.
Preserve image1 direction sequence: DOWN; down/slightlyLEFT; DOWN-LEFT; LEFT/slightlydown; LEFT; LEFT/slightlyup; UP-LEFT; UP/slightlyLEFT. All seven later poses keep screenLEFT component, finalthree upward-left. Do not change any facial direction. AnatomicalRIGHT hand retains blackwirelessmic belowchest, LEFT hand relaxed, same browncurls hairpart and asymmetricalblackstagecostume. No mirror, text, guides, props, shadows, effects. True transparentbackground. Complete coherent8-pose row in one generation. Only the tiny2.5percent reduction to create a little more space around all8 figures.


## row-retries/look-row-10.md

Create one coherent horizontal strip of eight full-body gaze poses for the same approved black-stage anime chibi. Image 1 is completed row 9: use its exact character size, face construction, proportions, costume, and baseline, but do not copy its rightward directions. Image 2 contains the original approved art on the left and canonical neutral on the right. Image 3 is a spacing guide only. Image 4 is the standard animation identity reference. Image 5 gives the authoritative cardinal families UP, RIGHT, DOWN, LEFT.

This is the LEFT HALF of the attention circle. Exact left-to-right order:
1 DOWN, centered bowed head.
2 Down with slight screen-LEFT head and eye direction.
3 DOWN-LEFT.
4 Mostly screen-LEFT, slightly DOWN.
5 Unmistakable screen-LEFT: nose and pupils left of the head center.
6 Mostly screen-LEFT, slightly UP.
7 UP-LEFT.
8 Mostly UP with slight screen-LEFT bias, approaching the first row's clear overhead gaze.
Use viewer/image coordinates. Every pose from 2 to 8 must retain a leftward component. In the final three poses, eyes and chin rise while the face still points LEFT, never right. The fourth pose in the cardinal strip is the LEFT authority. Interpolate naturally between DOWN, LEFT and UP.

Match the completed row 9 SOURCE size closely: full character height 421–423 pixels, head/hair top near y152, boot baseline y575, on a 2172×724 canvas. Keep the same head width and body proportions in all eight poses. Do not enlarge characters to fill the canvas. Use eight equal slots with centers near136,408,680,952,1224,1496,1768,2040; each complete silhouette at most245 pixels wide, clear gaps and outer margins. Entire curls and boots visible. Exact atlas normalization is handled later.

Eyes lead, head and neck turn softly, upper body follows only slightly. Feet and lower body stay planted. Preserve original large brown anime eyes and facial proportions, brown curls and hair partition, silver earrings, black cropped jacket, dark top, silver hardware, asymmetric trouser straps, black boots. Anatomical RIGHT hand always holds the black wireless microphone below chest; free LEFT hand relaxed. No mirroring, facial stretching, whole-body rotation, microphone crossing face/hair, new props, text, guide lines, shadows or effects. True transparent background. All eight poses drawn together as one consistent family.


## row-retries/look-row-9-layout-repair.md

Create a production sprite strip on a WIDE2176x724 TRANSPARENT canvas. Main layout constraint: EXACTLY EIGHT SMALL fullbody figures with generous whitespace all around each character, eight equidistant centers at x136,408,680,952,1224,1496,1768,2040. Each complete figure INCLUDING curly hair is ONLY200pixels wide and400pixels high, occupying y162through562. Thus minimum72pixels of EMPTY transparent horizontal space between silhouettes. Large empty transparent top/bottom margins. DO NOT enlarge figures to fill canvas. Every silhouette strictly fits its individual layout-guide blue rectangle with spare whitespace. Layout reference2 is spacing only: REMOVE ALL guide marks. No text or grids. Reference1 original appearance; reference3 canonical identity; reference4 approved standard family and proportions; reference5 cardinal directions, ordered UP RIGHT DOWN LEFT. Draw the SAME character eight times with EXACT same planted lowerbody and quiet pose, tiny closed smile, no singing. Black cropped stage jacket with silver details, dark sparkly top, trousers, boots, long brown curls, original anime eyes and original face. Anatomical RIGHT hand (viewerLEFT) holds black mic fixed belowchest; LEFThand stays relaxed. All8maintain same identity and scale. Only eyes/head/neck gently change, NEVER rotate the body, nevermirror. Left-to-right attention directions exactly: UP overhead, UP slightlyRIGHT, UPRIGHT diagonal, RIGHT slightlyUP, RIGHT, RIGHT slightlyDOWN, DOWNRIGHT diagonal, DOWN slightlyRIGHT. Pose1 uses the first cardinal anchor: eyes visibly raisedhighwithwhitebelow, softlyraisedchin, visibleunderchin, definitelyOVERHEAD notfrontidle. Pose5usessecondanchor: face/nose/pupils towardsviewerRIGHT withgentleyaw25degrees. Poses6/7/8 progressivelylower gaze, retainrightbias. Eyeslead headsoftlyfollows, smoothlyinterpolate22.5degree attentionangle steps. Fullboots andallcurls included, no extra props, effects or shadows. True alpha background. Absolute priority: SMALL figures that do nottouch orcrossslots, generousEMPTYspace.


## row-retries/look-row-9.md

DrawONE coherent8pose fullbody gaze strip forG.E.M. blackstagechibi, sameoriginal/canonicalface, eyedesign, browncurls, blackcroppedjacket/darktop/silverhardware, trousers/boots. AnatomicalRIGHTblackmic belowchest, LEFTfreehandrelaxed, asymmetryunchanged. No mirroring.
Useapprovedcardinalstripasdirectionauthority, original/canonicalforidentity, standardcontactforproportions, layoutguideonlyspacing. Seeqa/look-mechanics.md.
8posesleft-to-right: UP, upslightlyRIGHT, UPRIGHT, mostlyRIGHTslightlyUP, RIGHT, mostlyRIGHTslightlyDOWN, DOWNRIGHT, downslightlyRIGHT.
FirstUP mustbeunmistakablyOVERHEAD: softlyraisedchinwithunderchinvisible, originalbrowniriseshighwithincoherentlydrawnlids andsmalllightsclerabelow, notfrontidle. FifthRIGHT nose/face/pupilsclearlytowardsviewerRIGHT. Lastthree eyes/chingentlylower retainingrightbias; eighthalmostcentereddown butslightlyright. Intermediateposesformgradual22.5degree attentionarc, notbodyrotation.
Feet, hips, body/headsize andlowerbodyanchor stable. Eyeslead, head/neckfollowsoftly, curls/earringsattached; micnear-rigidinhand belowface, nopenetration. Tinycalmsmile,no sing/run/gestures. Preserveeyeproportions, no facialwarp.
Source2176x724,eightinvisibleequal272pxslots, exact8separatedwholefigures, maxwidth220px, bodyheight~400px,≥25pxoutermargins andcleargaps. Consistentheight/baseline; entirecurlsilhouette andbootsinsideeachslot. Do notenlargefillcanvas. Realtransparentbackgroundpreferred; ifopaqueonly#00FF00. No guide/text/labels/shadows/newprops/effects.


## row-retries/review.md

Create one coherent horizontal strip of exactly 6 complete full-body animation frames for Codex pet G.E.M., state review.

Soleappearanceauthority is originalapprovedblackstageillustration. Preserve exact originalface, largebrowneyedesign, originalhead/bodyratio, deepbrownlongcurlyhairpart, silverdanglingearrings, croppedblackbikerjacket withsilverhardware, darkcroptop, blacktrousers withasymmetricbelts/straps, blackplatformankleboots. Anatomical RIGHT hand alwaysholdsblackwirelessmic (viewerLEFT front); freeLEFThand. Nevermirror. Fineanime linework/softcelshading, not3D/photo/plush. Noaddedprops/text/logo/shadow/background/effects.

Action: 6phase checkingresults: smallheadforwardlean, eyeslookslightlyleft, slightlyright, pauseobserving, smallconfirmingnod, satisfiedsmallsmile. FreeLEFThandrelaxed, RIGHTmicstablelow. Distinctfromhand-at-chinwork andidle. No newpapers/magnifier/effects.

Use attached original and canonicalidentity, and layoutguide ONLY for invisible equalspacing. Keepfullhair/boots/accessoriesinsideeachslot, nooverlap orouteredgeclipping. Landscape2176x724source, generousblankspaceaboveandbelow, onecenteredfigureperequalslot. For8slots keepdrawnfigureheightabout380-410pixels,maxwidth220pixels; forfewerframes keepfigureheightabout450pixels. Consistentbody/headscale acrossallframes; baseline stable except smallrunbob or intendedjump. Animate attachedparts naturally, no detachedhardware orhair. Background trulytransparentpreferred; ifopaqueuseflat#00FF00only. No guidepixels, borders, labels orcheckerboard.


## row-retries/running-left.md

Create one coherent horizontal strip of exactly 8 complete full-body animation frames for Codex pet G.E.M., state running-left.

Soleappearanceauthority is originalapprovedblackstageillustration. Preserve exact originalface, largebrowneyedesign, originalhead/bodyratio, deepbrownlongcurlyhairpart, silverdanglingearrings, croppedblackbikerjacket withsilverhardware, darkcroptop, blacktrousers withasymmetricbelts/straps, blackplatformankleboots. Anatomical RIGHT hand alwaysholdsblackwirelessmic (viewerLEFT front); freeLEFThand. Nevermirror. Fineanime linework/softcelshading, not3D/photo/plush. Noaddedprops/text/logo/shadow/background/effects.

Action: Light compact running toward SCREEN LEFT with clearly alternating legs and tinybodyrise/fall. 8alternatinggaitphases. Face and torso screenLEFT. Independently redraw, NEVERmirror rightrow: same anatomical RIGHT-hand blackmic, samehairpart, jacketzipper, belthangingstraps andearrings. FreeLEFTarm naturalcounterbalance. Smallcurl/accessorylag. No dust/speedlines.

Use attached original and canonicalidentity, and layoutguide ONLY for invisible equalspacing. Keepfullhair/boots/accessoriesinsideeachslot, nooverlap orouteredgeclipping. Landscape2176x724source, generousblankspaceaboveandbelow, onecenteredfigureperequalslot. For8slots keepdrawnfigureheightabout380-410pixels,maxwidth220pixels; forfewerframes keepfigureheightabout450pixels. Consistentbody/headscale acrossallframes; baseline stable except smallrunbob or intendedjump. Animate attachedparts naturally, no detachedhardware orhair. Background trulytransparentpreferred; ifopaqueuseflat#00FF00only. No guidepixels, borders, labels orcheckerboard.


## row-retries/running-right-layout-repair.md

Edit input image 1: running-right eight-frame animation strip. Make ONLY a layout/scale repair, preserve its eight right-facing alternating running gait phases, original illustration identity, anatomy and exact head/body proportions. Input 2 is the original sole appearance authority. Input 3 layout guide is for invisible spacing only. Input 4 canonical character identity. Canvas remains 2172x724. Uniformly reduce each WHOLE complete figure to 80% of its current size, from current approximately 510 px height to 408 px height, maximum full hair/limb width 216 px. Do NOT make larger heads or shorter bodies: uniformly scale whole figures, preserving original proportions. Eight invisible equal cell centers approximately x=136,408,680,952,1224,1496,1768,2040. Center each full figure including hair in its cell. Each figure must have at least 25 px clear margin from outer image edges and at least 40 px truly empty horizontal gap from the next complete figure. Restore any missing first-frame left hair to a complete natural curl silhouette. Boots baseline about y=600 except natural tiny running bob. Large empty space above and below is INTENDED; do not enlarge to fill canvas. Maintain exactly eight figures, screen-right faces AND torsos, alternating bent legs, slight bob and hair lag, black microphone in anatomical RIGHT hand throughout, natural free LEFT arm. Fine anime linework, original brown curls, silver earrings, black biker outfit, attached silver straps, full platform ankle boots. Preserve true transparency alpha. NO overlap, NO cropping, NO shadows, NO floor, NO effects, NO text/labels, NO guide marks, NO checkerboard. Composition only repair.


## row-retries/running-right.md

Create one coherent horizontal strip of exactly 8 complete full-body animation frames for Codex pet G.E.M., state running-right.

Soleappearanceauthority is originalapprovedblackstageillustration. Preserve exact originalface, largebrowneyedesign, originalhead/bodyratio, deepbrownlongcurlyhairpart, silverdanglingearrings, croppedblackbikerjacket withsilverhardware, darkcroptop, blacktrousers withasymmetricbelts/straps, blackplatformankleboots. Anatomical RIGHT hand alwaysholdsblackwirelessmic (viewerLEFT front); freeLEFThand. Nevermirror. Fineanime linework/softcelshading, not3D/photo/plush. Noaddedprops/text/logo/shadow/background/effects.

Action: Light compact running toward SCREEN RIGHT with clearly alternating legs and tiny body rise/fall. 8gait phases: rightfootcontact, down, pass, up, leftfootcontact, down, pass, up. Face and torso screenRIGHT, blackmic steady in anatomical RIGHT hand, freeLEFTarm naturalcounterbalance. Curls and attachedsilverstraps lag softly. No longstride, highkicks, dust orspeedlines.

Use attached original and canonicalidentity, and layoutguide ONLY for invisible equalspacing. Keepfullhair/boots/accessoriesinsideeachslot, nooverlap orouteredgeclipping. Landscape2176x724source, generousblankspaceaboveandbelow, onecenteredfigureperequalslot. For8slots keepdrawnfigureheightabout380-410pixels,maxwidth220pixels; forfewerframes keepfigureheightabout450pixels. Consistentbody/headscale acrossallframes; baseline stable except smallrunbob or intendedjump. Animate attachedparts naturally, no detachedhardware orhair. Background trulytransparentpreferred; ifopaqueuseflat#00FF00only. No guidepixels, borders, labels orcheckerboard.


## row-retries/running.md

Create one coherent horizontal strip of exactly 6 complete full-body animation frames for Codex pet G.E.M., state running.

Soleappearanceauthority is originalapprovedblackstageillustration. Preserve exact originalface, largebrowneyedesign, originalhead/bodyratio, deepbrownlongcurlyhairpart, silverdanglingearrings, croppedblackbikerjacket withsilverhardware, darkcroptop, blacktrousers withasymmetricbelts/straps, blackplatformankleboots. Anatomical RIGHT hand alwaysholdsblackwirelessmic (viewerLEFT front); freeLEFThand. Nevermirror. Fineanime linework/softcelshading, not3D/photo/plush. Noaddedprops/text/logo/shadow/background/effects.

Action: Taskprocessing ONLY, notlocomotion orsinging. 6phases: micRIGHThandlowbelowchest, freeLEFThandgentlytoucheschin, eyesfocusdown, thoughtfulpause, smallnod, refocus. Feetplanted andstill. Do not obstructfacewithmic orletmiccrosshair/body.

Use attached original and canonicalidentity, and layoutguide ONLY for invisible equalspacing. Keepfullhair/boots/accessoriesinsideeachslot, nooverlap orouteredgeclipping. Landscape2176x724source, generousblankspaceaboveandbelow, onecenteredfigureperequalslot. For8slots keepdrawnfigureheightabout380-410pixels,maxwidth220pixels; forfewerframes keepfigureheightabout450pixels. Consistentbody/headscale acrossallframes; baseline stable except smallrunbob or intendedjump. Animate attachedparts naturally, no detachedhardware orhair. Background trulytransparentpreferred; ifopaqueuseflat#00FF00only. No guidepixels, borders, labels orcheckerboard.


## row-retries/waiting.md

Create one coherent horizontal strip of exactly 6 complete full-body animation frames for Codex pet G.E.M., state waiting.

Soleappearanceauthority is originalapprovedblackstageillustration. Preserve exact originalface, largebrowneyedesign, originalhead/bodyratio, deepbrownlongcurlyhairpart, silverdanglingearrings, croppedblackbikerjacket withsilverhardware, darkcroptop, blacktrousers withasymmetricbelts/straps, blackplatformankleboots. Anatomical RIGHT hand alwaysholdsblackwirelessmic (viewerLEFT front); freeLEFThand. Nevermirror. Fineanime linework/softcelshading, not3D/photo/plush. Noaddedprops/text/logo/shadow/background/effects.

Action: 6phase patientlyawaitinguser: slightheadtilt, freeLEFT palm gentlyopens atwaist, warmexpectantface, calmblink, attentiveopeneyes, softheldaskingpose. RIGHThandmicbelowchest. Distinctfromidleandchin-thinking; noimpatientgesture.

Use attached original and canonicalidentity, and layoutguide ONLY for invisible equalspacing. Keepfullhair/boots/accessoriesinsideeachslot, nooverlap orouteredgeclipping. Landscape2176x724source, generousblankspaceaboveandbelow, onecenteredfigureperequalslot. For8slots keepdrawnfigureheightabout380-410pixels,maxwidth220pixels; forfewerframes keepfigureheightabout450pixels. Consistentbody/headscale acrossallframes; baseline stable except smallrunbob or intendedjump. Animate attachedparts naturally, no detachedhardware orhair. Background trulytransparentpreferred; ifopaqueuseflat#00FF00only. No guidepixels, borders, labels orcheckerboard.


## row-retries/waving.md

Create one coherent horizontal strip of exactly 4 complete full-body animation frames for Codex pet G.E.M., state waving.

Soleappearanceauthority is originalapprovedblackstageillustration. Preserve exact originalface, largebrowneyedesign, originalhead/bodyratio, deepbrownlongcurlyhairpart, silverdanglingearrings, croppedblackbikerjacket withsilverhardware, darkcroptop, blacktrousers withasymmetricbelts/straps, blackplatformankleboots. Anatomical RIGHT hand alwaysholdsblackwirelessmic (viewerLEFT front); freeLEFThand. Nevermirror. Fineanime linework/softcelshading, not3D/photo/plush. Noaddedprops/text/logo/shadow/background/effects.

Action: 4phase friendly gentlewave using anatomical LEFT freehand: rest, smallhandlift, smallsidewavewithslightheadtilt andbrightsmile, softreturn. RIGHT hand keepsmicbelowchest. No wavingmarks/effects. No broadoverheadwave.

Use attached original and canonicalidentity, and layoutguide ONLY for invisible equalspacing. Keepfullhair/boots/accessoriesinsideeachslot, nooverlap orouteredgeclipping. Landscape2176x724source, generousblankspaceaboveandbelow, onecenteredfigureperequalslot. For8slots keepdrawnfigureheightabout380-410pixels,maxwidth220pixels; forfewerframes keepfigureheightabout450pixels. Consistentbody/headscale acrossallframes; baseline stable except smallrunbob or intendedjump. Animate attachedparts naturally, no detachedhardware orhair. Background trulytransparentpreferred; ifopaqueuseflat#00FF00only. No guidepixels, borders, labels orcheckerboard.


## rows/failed.md

Create one coherent horizontal strip of exactly 8 complete full-body animation frames for Codex pet G.E.M., state failed.

Soleappearanceauthority is originalapprovedblackstageillustration. Preserve exact originalface, largebrowneyedesign, originalhead/bodyratio, deepbrownlongcurlyhairpart, silverdanglingearrings, croppedblackbikerjacket withsilverhardware, darkcroptop, blacktrousers withasymmetricbelts/straps, blackplatformankleboots. Anatomical RIGHT hand alwaysholdsblackwirelessmic (viewerLEFT front); freeLEFThand. Nevermirror. Fineanime linework/softcelshading, not3D/photo/plush. Noaddedprops/text/logo/shadow/background/effects.

Action: 8phase mildregret: normal, eyeslower, smilebrieflysoftensaway, littleheadtilt, smallthoughtfulpause, gaze lifts, softsmilerestores, return. No tears/crying, exaggeratedslump, sigh, symbols/effects. Stablefeet, micsteady.

Use attached original and canonicalidentity, and layoutguide ONLY for invisible equalspacing. Keepfullhair/boots/accessoriesinsideeachslot, nooverlap orouteredgeclipping. Landscape2176x724source, generousblankspaceaboveandbelow, onecenteredfigureperequalslot. For8slots keepdrawnfigureheightabout380-410pixels,maxwidth220pixels; forfewerframes keepfigureheightabout450pixels. Consistentbody/headscale acrossallframes; baseline stable except smallrunbob or intendedjump. Animate attachedparts naturally, no detachedhardware orhair. Background trulytransparentpreferred; ifopaqueuseflat#00FF00only. No guidepixels, borders, labels orcheckerboard.


## rows/idle.md

Create one coherent horizontal strip of exactly 6 complete full-body animation frames for Codex pet G.E.M., state idle.

Soleappearanceauthority is originalapprovedblackstageillustration. Preserve exact originalface, largebrowneyedesign, originalhead/bodyratio, deepbrownlongcurlyhairpart, silverdanglingearrings, croppedblackbikerjacket withsilverhardware, darkcroptop, blacktrousers withasymmetricbelts/straps, blackplatformankleboots. Anatomical RIGHT hand alwaysholdsblackwirelessmic (viewerLEFT front); freeLEFThand. Nevermirror. Fineanime linework/softcelshading, not3D/photo/plush. Noaddedprops/text/logo/shadow/background/effects.

Action: Quiet breathing and one gentle slow blink, tiny attached curl sway. Mic in anatomical RIGHT hand below chest, LEFT freehand relaxed. 6phases: rest, inhale, halfblink, closedblink, reopen, rest. No waving, singing, footsteps or broad gesture. Visible microvariation with stablefeet.

Use attached original and canonicalidentity, and layoutguide ONLY for invisible equalspacing. Keepfullhair/boots/accessoriesinsideeachslot, nooverlap orouteredgeclipping. Landscape2176x724source, generousblankspaceaboveandbelow, onecenteredfigureperequalslot. For8slots keepdrawnfigureheightabout380-410pixels,maxwidth220pixels; forfewerframes keepfigureheightabout450pixels. Consistentbody/headscale acrossallframes; baseline stable except smallrunbob or intendedjump. Animate attachedparts naturally, no detachedhardware orhair. Background trulytransparentpreferred; ifopaqueuseflat#00FF00only. No guidepixels, borders, labels orcheckerboard.


## rows/jumping.md

Create one coherent horizontal strip of exactly 5 complete full-body animation frames for Codex pet G.E.M., state jumping.

Soleappearanceauthority is originalapprovedblackstageillustration. Preserve exact originalface, largebrowneyedesign, originalhead/bodyratio, deepbrownlongcurlyhairpart, silverdanglingearrings, croppedblackbikerjacket withsilverhardware, darkcroptop, blacktrousers withasymmetricbelts/straps, blackplatformankleboots. Anatomical RIGHT hand alwaysholdsblackwirelessmic (viewerLEFT front); freeLEFThand. Nevermirror. Fineanime linework/softcelshading, not3D/photo/plush. Noaddedprops/text/logo/shadow/background/effects.

Action: 5phase compactjoyfuljump: slightkneebend preparation, smallupwardtakeoff, lowairborneapex, softbentkneelanding, relaxedstand. Samebody/headscale; preservevisibleverticalmotion. Micneverleaves anatomicalRIGHT hand. Curls softlyliftandsettle. Entirehead/hair/boots stayinsideframe. No groundshadow/dust/landingmarks.

Use attached original and canonicalidentity, and layoutguide ONLY for invisible equalspacing. Keepfullhair/boots/accessoriesinsideeachslot, nooverlap orouteredgeclipping. Landscape2176x724source, generousblankspaceaboveandbelow, onecenteredfigureperequalslot. For8slots keepdrawnfigureheightabout380-410pixels,maxwidth220pixels; forfewerframes keepfigureheightabout450pixels. Consistentbody/headscale acrossallframes; baseline stable except smallrunbob or intendedjump. Animate attachedparts naturally, no detachedhardware orhair. Background trulytransparentpreferred; ifopaqueuseflat#00FF00only. No guidepixels, borders, labels orcheckerboard.


## rows/look-row-10.md

Create one coherent horizontal strip of eight full-body gaze poses for the same approved black-stage anime chibi. Image 1 is completed row 9: use its exact character size, face construction, proportions, costume, and baseline, but do not copy its rightward directions. Image 2 contains the original approved art on the left and canonical neutral on the right. Image 3 is a spacing guide only. Image 4 is the standard animation identity reference. Image 5 gives the authoritative cardinal families UP, RIGHT, DOWN, LEFT.

This is the LEFT HALF of the attention circle. Exact left-to-right order:
1 DOWN, centered bowed head.
2 Down with slight screen-LEFT head and eye direction.
3 DOWN-LEFT.
4 Mostly screen-LEFT, slightly DOWN.
5 Unmistakable screen-LEFT: nose and pupils left of the head center.
6 Mostly screen-LEFT, slightly UP.
7 UP-LEFT.
8 Mostly UP with slight screen-LEFT bias, approaching the first row's clear overhead gaze.
Use viewer/image coordinates. Every pose from 2 to 8 must retain a leftward component. In the final three poses, eyes and chin rise while the face still points LEFT, never right. The fourth pose in the cardinal strip is the LEFT authority. Interpolate naturally between DOWN, LEFT and UP.

Match the completed row 9 SOURCE size closely: full character height 421–423 pixels, head/hair top near y152, boot baseline y575, on a 2172×724 canvas. Keep the same head width and body proportions in all eight poses. Do not enlarge characters to fill the canvas. Use eight equal slots with centers near136,408,680,952,1224,1496,1768,2040; each complete silhouette at most245 pixels wide, clear gaps and outer margins. Entire curls and boots visible. Exact atlas normalization is handled later.

Eyes lead, head and neck turn softly, upper body follows only slightly. Feet and lower body stay planted. Preserve original large brown anime eyes and facial proportions, brown curls and hair partition, silver earrings, black cropped jacket, dark top, silver hardware, asymmetric trouser straps, black boots. Anatomical RIGHT hand always holds the black wireless microphone below chest; free LEFT hand relaxed. No mirroring, facial stretching, whole-body rotation, microphone crossing face/hair, new props, text, guide lines, shadows or effects. True transparent background. All eight poses drawn together as one consistent family.


## rows/look-row-9.md

DrawONE coherent8pose fullbody gaze strip forG.E.M. blackstagechibi, sameoriginal/canonicalface, eyedesign, browncurls, blackcroppedjacket/darktop/silverhardware, trousers/boots. AnatomicalRIGHTblackmic belowchest, LEFTfreehandrelaxed, asymmetryunchanged. No mirroring.
Useapprovedcardinalstripasdirectionauthority, original/canonicalforidentity, standardcontactforproportions, layoutguideonlyspacing. Seeqa/look-mechanics.md.
8posesleft-to-right: UP, upslightlyRIGHT, UPRIGHT, mostlyRIGHTslightlyUP, RIGHT, mostlyRIGHTslightlyDOWN, DOWNRIGHT, downslightlyRIGHT.
FirstUP mustbeunmistakablyOVERHEAD: softlyraisedchinwithunderchinvisible, originalbrowniriseshighwithincoherentlydrawnlids andsmalllightsclerabelow, notfrontidle. FifthRIGHT nose/face/pupilsclearlytowardsviewerRIGHT. Lastthree eyes/chingentlylower retainingrightbias; eighthalmostcentereddown butslightlyright. Intermediateposesformgradual22.5degree attentionarc, notbodyrotation.
Feet, hips, body/headsize andlowerbodyanchor stable. Eyeslead, head/neckfollowsoftly, curls/earringsattached; micnear-rigidinhand belowface, nopenetration. Tinycalmsmile,no sing/run/gestures. Preserveeyeproportions, no facialwarp.
Source2176x724,eightinvisibleequal272pxslots, exact8separatedwholefigures, maxwidth220px, bodyheight~400px,≥25pxoutermargins andcleargaps. Consistentheight/baseline; entirecurlsilhouette andbootsinsideeachslot. Do notenlargefillcanvas. Realtransparentbackgroundpreferred; ifopaqueonly#00FF00. No guide/text/labels/shadows/newprops/effects.


## rows/review.md

Create one coherent horizontal strip of exactly 6 complete full-body animation frames for Codex pet G.E.M., state review.

Soleappearanceauthority is originalapprovedblackstageillustration. Preserve exact originalface, largebrowneyedesign, originalhead/bodyratio, deepbrownlongcurlyhairpart, silverdanglingearrings, croppedblackbikerjacket withsilverhardware, darkcroptop, blacktrousers withasymmetricbelts/straps, blackplatformankleboots. Anatomical RIGHT hand alwaysholdsblackwirelessmic (viewerLEFT front); freeLEFThand. Nevermirror. Fineanime linework/softcelshading, not3D/photo/plush. Noaddedprops/text/logo/shadow/background/effects.

Action: 6phase checkingresults: smallheadforwardlean, eyeslookslightlyleft, slightlyright, pauseobserving, smallconfirmingnod, satisfiedsmallsmile. FreeLEFThandrelaxed, RIGHTmicstablelow. Distinctfromhand-at-chinwork andidle. No newpapers/magnifier/effects.

Use attached original and canonicalidentity, and layoutguide ONLY for invisible equalspacing. Keepfullhair/boots/accessoriesinsideeachslot, nooverlap orouteredgeclipping. Landscape2176x724source, generousblankspaceaboveandbelow, onecenteredfigureperequalslot. For8slots keepdrawnfigureheightabout380-410pixels,maxwidth220pixels; forfewerframes keepfigureheightabout450pixels. Consistentbody/headscale acrossallframes; baseline stable except smallrunbob or intendedjump. Animate attachedparts naturally, no detachedhardware orhair. Background trulytransparentpreferred; ifopaqueuseflat#00FF00only. No guidepixels, borders, labels orcheckerboard.


## rows/running-left.md

Create one coherent horizontal strip of exactly 8 complete full-body animation frames for Codex pet G.E.M., state running-left.

Soleappearanceauthority is originalapprovedblackstageillustration. Preserve exact originalface, largebrowneyedesign, originalhead/bodyratio, deepbrownlongcurlyhairpart, silverdanglingearrings, croppedblackbikerjacket withsilverhardware, darkcroptop, blacktrousers withasymmetricbelts/straps, blackplatformankleboots. Anatomical RIGHT hand alwaysholdsblackwirelessmic (viewerLEFT front); freeLEFThand. Nevermirror. Fineanime linework/softcelshading, not3D/photo/plush. Noaddedprops/text/logo/shadow/background/effects.

Action: Light compact running toward SCREEN LEFT with clearly alternating legs and tinybodyrise/fall. 8alternatinggaitphases. Face and torso screenLEFT. Independently redraw, NEVERmirror rightrow: same anatomical RIGHT-hand blackmic, samehairpart, jacketzipper, belthangingstraps andearrings. FreeLEFTarm naturalcounterbalance. Smallcurl/accessorylag. No dust/speedlines.

Use attached original and canonicalidentity, and layoutguide ONLY for invisible equalspacing. Keepfullhair/boots/accessoriesinsideeachslot, nooverlap orouteredgeclipping. Landscape2176x724source, generousblankspaceaboveandbelow, onecenteredfigureperequalslot. For8slots keepdrawnfigureheightabout380-410pixels,maxwidth220pixels; forfewerframes keepfigureheightabout450pixels. Consistentbody/headscale acrossallframes; baseline stable except smallrunbob or intendedjump. Animate attachedparts naturally, no detachedhardware orhair. Background trulytransparentpreferred; ifopaqueuseflat#00FF00only. No guidepixels, borders, labels orcheckerboard.


## rows/running-right.md

Create one coherent horizontal strip of exactly 8 complete full-body animation frames for Codex pet G.E.M., state running-right.

Soleappearanceauthority is originalapprovedblackstageillustration. Preserve exact originalface, largebrowneyedesign, originalhead/bodyratio, deepbrownlongcurlyhairpart, silverdanglingearrings, croppedblackbikerjacket withsilverhardware, darkcroptop, blacktrousers withasymmetricbelts/straps, blackplatformankleboots. Anatomical RIGHT hand alwaysholdsblackwirelessmic (viewerLEFT front); freeLEFThand. Nevermirror. Fineanime linework/softcelshading, not3D/photo/plush. Noaddedprops/text/logo/shadow/background/effects.

Action: Light compact running toward SCREEN RIGHT with clearly alternating legs and tiny body rise/fall. 8gait phases: rightfootcontact, down, pass, up, leftfootcontact, down, pass, up. Face and torso screenRIGHT, blackmic steady in anatomical RIGHT hand, freeLEFTarm naturalcounterbalance. Curls and attachedsilverstraps lag softly. No longstride, highkicks, dust orspeedlines.

Use attached original and canonicalidentity, and layoutguide ONLY for invisible equalspacing. Keepfullhair/boots/accessoriesinsideeachslot, nooverlap orouteredgeclipping. Landscape2176x724source, generousblankspaceaboveandbelow, onecenteredfigureperequalslot. For8slots keepdrawnfigureheightabout380-410pixels,maxwidth220pixels; forfewerframes keepfigureheightabout450pixels. Consistentbody/headscale acrossallframes; baseline stable except smallrunbob or intendedjump. Animate attachedparts naturally, no detachedhardware orhair. Background trulytransparentpreferred; ifopaqueuseflat#00FF00only. No guidepixels, borders, labels orcheckerboard.


## rows/running.md

Create one coherent horizontal strip of exactly 6 complete full-body animation frames for Codex pet G.E.M., state running.

Soleappearanceauthority is originalapprovedblackstageillustration. Preserve exact originalface, largebrowneyedesign, originalhead/bodyratio, deepbrownlongcurlyhairpart, silverdanglingearrings, croppedblackbikerjacket withsilverhardware, darkcroptop, blacktrousers withasymmetricbelts/straps, blackplatformankleboots. Anatomical RIGHT hand alwaysholdsblackwirelessmic (viewerLEFT front); freeLEFThand. Nevermirror. Fineanime linework/softcelshading, not3D/photo/plush. Noaddedprops/text/logo/shadow/background/effects.

Action: Taskprocessing ONLY, notlocomotion orsinging. 6phases: micRIGHThandlowbelowchest, freeLEFThandgentlytoucheschin, eyesfocusdown, thoughtfulpause, smallnod, refocus. Feetplanted andstill. Do not obstructfacewithmic orletmiccrosshair/body.

Use attached original and canonicalidentity, and layoutguide ONLY for invisible equalspacing. Keepfullhair/boots/accessoriesinsideeachslot, nooverlap orouteredgeclipping. Landscape2176x724source, generousblankspaceaboveandbelow, onecenteredfigureperequalslot. For8slots keepdrawnfigureheightabout380-410pixels,maxwidth220pixels; forfewerframes keepfigureheightabout450pixels. Consistentbody/headscale acrossallframes; baseline stable except smallrunbob or intendedjump. Animate attachedparts naturally, no detachedhardware orhair. Background trulytransparentpreferred; ifopaqueuseflat#00FF00only. No guidepixels, borders, labels orcheckerboard.


## rows/waiting.md

Create one coherent horizontal strip of exactly 6 complete full-body animation frames for Codex pet G.E.M., state waiting.

Soleappearanceauthority is originalapprovedblackstageillustration. Preserve exact originalface, largebrowneyedesign, originalhead/bodyratio, deepbrownlongcurlyhairpart, silverdanglingearrings, croppedblackbikerjacket withsilverhardware, darkcroptop, blacktrousers withasymmetricbelts/straps, blackplatformankleboots. Anatomical RIGHT hand alwaysholdsblackwirelessmic (viewerLEFT front); freeLEFThand. Nevermirror. Fineanime linework/softcelshading, not3D/photo/plush. Noaddedprops/text/logo/shadow/background/effects.

Action: 6phase patientlyawaitinguser: slightheadtilt, freeLEFT palm gentlyopens atwaist, warmexpectantface, calmblink, attentiveopeneyes, softheldaskingpose. RIGHThandmicbelowchest. Distinctfromidleandchin-thinking; noimpatientgesture.

Use attached original and canonicalidentity, and layoutguide ONLY for invisible equalspacing. Keepfullhair/boots/accessoriesinsideeachslot, nooverlap orouteredgeclipping. Landscape2176x724source, generousblankspaceaboveandbelow, onecenteredfigureperequalslot. For8slots keepdrawnfigureheightabout380-410pixels,maxwidth220pixels; forfewerframes keepfigureheightabout450pixels. Consistentbody/headscale acrossallframes; baseline stable except smallrunbob or intendedjump. Animate attachedparts naturally, no detachedhardware orhair. Background trulytransparentpreferred; ifopaqueuseflat#00FF00only. No guidepixels, borders, labels orcheckerboard.


## rows/waving.md

Create one coherent horizontal strip of exactly 4 complete full-body animation frames for Codex pet G.E.M., state waving.

Soleappearanceauthority is originalapprovedblackstageillustration. Preserve exact originalface, largebrowneyedesign, originalhead/bodyratio, deepbrownlongcurlyhairpart, silverdanglingearrings, croppedblackbikerjacket withsilverhardware, darkcroptop, blacktrousers withasymmetricbelts/straps, blackplatformankleboots. Anatomical RIGHT hand alwaysholdsblackwirelessmic (viewerLEFT front); freeLEFThand. Nevermirror. Fineanime linework/softcelshading, not3D/photo/plush. Noaddedprops/text/logo/shadow/background/effects.

Action: 4phase friendly gentlewave using anatomical LEFT freehand: rest, smallhandlift, smallsidewavewithslightheadtilt andbrightsmile, softreturn. RIGHT hand keepsmicbelowchest. No wavingmarks/effects. No broadoverheadwave.

Use attached original and canonicalidentity, and layoutguide ONLY for invisible equalspacing. Keepfullhair/boots/accessoriesinsideeachslot, nooverlap orouteredgeclipping. Landscape2176x724source, generousblankspaceaboveandbelow, onecenteredfigureperequalslot. For8slots keepdrawnfigureheightabout380-410pixels,maxwidth220pixels; forfewerframes keepfigureheightabout450pixels. Consistentbody/headscale acrossallframes; baseline stable except smallrunbob or intendedjump. Animate attachedparts naturally, no detachedhardware orhair. Background trulytransparentpreferred; ifopaqueuseflat#00FF00only. No guidepixels, borders, labels orcheckerboard.
