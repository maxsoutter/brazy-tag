# BRAZY TAG: Shine Master Trials

A fast, chaotic 2–4 player local-multiplayer tag game that runs entirely in the browser.
Cube-ninja fighters, elemental decoy powers (🔥 💨 ❄️ 🪨), wall-running, portals,
flood / anti-gravity / mud events, live-synthesized sound, and a GSAP-animated menu.

Everything is client-side — a single `index.html` file with no build step and no backend.

## Play

Just open `index.html` in a browser, or visit the deployed Netlify site.

### Controls
| Player | Move | Power |
|--------|------|-------|
| P1 (Red)    | W A S D          | E |
| P2 (Yellow) | Arrow keys       | Right Shift |
| P3 (Blue)   | I J K L          | O |
| P4 (Green)  | T F G H          | Y |

`M` mutes/unmutes sound.

## Deploy workflow

This repo is connected to Netlify for **automatic deploys**: every push to `main`
triggers a fresh deploy. To ship a change, just edit `index.html`, commit, and push.

## Cover art

The title-screen artwork can be loaded from the menu with **📁 Use my art** (stored in
your browser). To bake it into the site for everyone, save the image as `hero-art.png`
in this folder and commit it.
