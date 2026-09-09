# Locked front-page art direction

`workspace-target.png` is the original user-supplied 864 × 1536 reference, preserved without edits.

SHA-256: `0c6d4222b5629d48aff4fd3b36d7af43ea519f7f25e18822b4a4d072138e6944`

The target controls the room's opening pose, material family, light direction, object inventory, and typography. Keep this image unchanged when iterating. Compare at 864 × 1536 with auto-rotation paused. The image is a design reference only; the runtime renders Three.js geometry and live HTML controls.

## Target composition

| Element | Target region, as fraction of image |
| --- | --- |
| Wordmark | x .07–.39; y .05–.09 |
| Identity / location | x .07; y .11–.15 |
| Eyebrow | x .07; y .19–.21 |
| Two-line headline | x .07–.72; y .24–.34 |
| Supporting copy | x .07–.65; y .37–.42 |
| Enter button | x .07–.56; y .44–.51 |
| Ambient wall frame | x .74–.92; y .23–.41 |
| CRT and keyboard | x .52–.86; y .54–.69 |
| Books | x .25–.46; y .55–.65 |
| Desk / olive cabinet | x .10–1; y .64–.91 |
| Olive chair | x .31–.71; y .67–.93 |
| Control bar | x .11–.89; y .93–.97 |

## Materials and lights

- Warm ivory plaster wall with low-amplitude mottling and off-white skirting.
- Brown wood tabletop with longitudinal grain; narrow charcoal steel legs.
- Matte olive filing cabinet and softly rounded, woven olive chair cushions. No chair armrests.
- Aged cream plastic CRT, recessed dark bezel, green phosphor display, matching keyboard and mouse.
- Ivory ceramic mug, ribbed olive pencil cup, eight named books, olive task lamp, cream wall frame, woven rug, trailing pothos and potted foliage.
- Warm key light from upper left/front, soft contact shadows, a small warm task-light source, feathered diagonal window-light shafts.
- Seeded procedural maps keep texture placement repeatable and preserve the self-contained/offline page.

## Behaviour

Keep all eight desktop apps and their content intact. Enter button and monitor both open the existing desktop. Drag changes the room view within bounded angles. Auto-rotation is a very small movement around the reference pose; reduced-motion preference disables it. Sound is off by default; haptics are optional and report unsupported browsers. Rendering pauses when the room or tab is hidden.

## Fidelity boundary

This is a real-time reconstruction from one image, not the source 3D scene. The image does not reveal original meshes, PBR maps, camera calibration or off-camera lighting. Treat exact pixel identity as an outstanding visual target, not a verified claim. Widescreen uses a separate composition to preserve readable HTML and scene access.

## Validation for this change

- JavaScript syntax checked for both embedded scripts.
- All eight desktop application definitions compared byte-for-byte with the base revision.
- Unique HTML IDs, embedded dependency references, and control/event bindings checked.
- Locked reference compared byte-for-byte with the supplied upload.
- Browser preview was denied by the browser access policy. No screenshot comparison or browser interaction pass is claimed.
