# JEV Neural Loop · The Split-Brain File

A 30-second looping HUD instrument around a particle brain, for video. It's a single `index.html`: HTML/CSS/SVG plus plain JS drawing on a `<canvas>`, with no libraries, images or CDN.

- Canvas: 1080 × 1350. It scales to fit any window, including Chrome fullscreen.
- Open `index.html` and it runs by itself.
- 4 states × 7.5 s = 30 s cycle: AUDIT → JEV → GATE → CLAUDE. The state sets the focused pods and the tape line.
- Every motion repeats on the same 30 s cycle: rings, pods, brain pulse, tape (every 2 s), verdicts (one per ~4.3 s), bars and counters.
- To record, open it in Chrome, go fullscreen and capture 30 s.
