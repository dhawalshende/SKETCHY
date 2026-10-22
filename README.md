# SKETCHY

**Trust nothing. Graduate (maybe).**

A troll-physics platformer that runs in your browser. It looks like a hand-drawn notebook page, and the game keeps betraying you on purpose. It's a joke about surviving engineering college.

**[Play it here](https://sketchy2.netlify.app/)**


## What makes it annoying

- **The START button runs away.** It dodges your cursor. If you stop chasing it for 4 seconds, it gives up and says "Fine. Click me."
- **Random betrayals mid-game:**
  - Left and right controls swap
  - Moon gravity
  - Jumping is disabled for a moment
  - The whole screen is mirrored
  - Zoom and speed changes mess with your depth perception
- **Hazards and pickups:** crumbling platforms, ink drops, and coffee cups that give you a speed boost
- **Snarky exam-themed death messages**

## How it's built

- **Single HTML file** (about 51 KB). No images, no audio files, no libraries.
- **HTML5 Canvas (2D):** everything is drawn in code. The pencil look comes from drawing each line more than once with small random offsets.
- **Web Audio API:** every sound effect is generated live with oscillators, so there are no audio files to load.
- **Responsive:** the game uses a fixed virtual size and scales to any screen.

## Run it locally

1. Download or clone this repo.
2. Open the HTML file in any modern browser.

No install or build step is needed.

## Controls

- Move: Arrow keys
- Jump: space and W

## About

Built for the JDCOEM college tech fest by [Dhawal Shende](https://www.linkedin.com/in/dhawalshende).
