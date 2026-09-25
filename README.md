# The Solo Store File

A looping operations file for an X video. It's a single `index.html` with no frameworks, images or CDN.

- Canvas: 1080 × 1350. It scales down to fit smaller windows.
- Open `index.html` in a browser and it loops by itself.
- Each state holds 7 seconds: T+00 → T+08 → T+18 → T+30. One full cycle is 28 s, then it repeats.
- To record, set the browser window to 1080 × 1350 and screen-capture 28 s for one full loop.
