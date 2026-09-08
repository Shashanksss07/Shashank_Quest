# Shashank_Quest

My personal website — the home base for **Shashank Shekhar** (builder, educator, creator of Smart Notes).

The whole site is a single self-contained `index.html`: an interactive workspace/desktop experience with an About, Projects, Smart Notes, journey timeline, Darshan Labs, values, reading list, and a mini terminal — no build step, no framework, no third-party requests. It was moved out of the [100 small apps portfolio](https://shashanksss07.github.io/My-100-small-app-portfolio/) (where it started life as project #52) to be managed on its own under a proper domain.

## Running locally

Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploying

`index.html` at the repo root is deploy-ready for GitHub Pages, Vercel, Netlify, or any static host — point your domain at it.

## Workspace interaction

The front room uses rounded geometry, procedural oak grain, studio reflections, soft shadows, and a detailed retro CRT. On phones the welcome copy sits above the room, with a camera fitted to the available space. Drag to orbit, click the monitor, or use **Enter my computer**.

- **Sound** is opt-in and uses short, locally synthesized Web Audio cues for entering, opening, closing, and leaving.
- **Haptics** is a separate opt-in control, shown only when the browser exposes the Vibration API. Device/browser support determines whether vibration is delivered.
- Reduced-motion preferences disable automatic movement and haptics. Rotation can still be explicitly enabled. Rendering pauses while the tab is hidden; the reduced-motion scene idles when unchanged.
- Textures, reflections, and sounds are generated locally; the single-file, offline architecture is retained.
