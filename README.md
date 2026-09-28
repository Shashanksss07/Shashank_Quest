# Shashank_Quest

My personal website — the home base for **Shashank Shekhar** (builder, educator, creator of Smart Notes).

The whole site is a single self-contained `index.html`: an interactive workspace/desktop experience with an About, Projects, Smart Notes, journey timeline, Darshan Labs, values, reading list, and a mini terminal — no build step, no framework, no third-party requests. It was moved out of the [100 small apps portfolio](https://shashanksss07.github.io/My-100-small-app-portfolio/) (where it started life as project #52) to be managed on its own under a proper domain.

## The room

The landing page is a real-time Three.js scene (r160, inlined): you walk in through a doorway into a sunlit workspace — low golden sun through window blinds, leaf shadows from a tree outside, drifting dust in the sunbeam. Drag to look around; labels in the room (books, poster, mug, plant…) open the matching app; clicking the monitor flies the camera into the screen and boots the desktop. Sound (room tone, birds, footsteps, CRT hum) is synthesised with Web Audio, off by default. Haptics use `navigator.vibrate` where supported. Reduced-motion users skip the walk-in and camera drift.

## Running locally

Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploying

`index.html` at the repo root is deploy-ready for GitHub Pages, Vercel, Netlify, or any static host — point your domain at it.
