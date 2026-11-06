# Tamanna — A Birthday Universe ✦

A responsive, pink-dreamy 3D birthday journey built with React, Vite, Three.js, React Three Fiber, Drei and GSAP.

## Run locally

1. Install Node.js 20.19+ (or 22.12+).
2. Open this folder in a terminal.
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the dev server:
   ```bash
   npm run dev
   ```
5. Open the local URL printed by Vite.

## Build for hosting

```bash
npm run build
npm run preview
```

Upload the generated `dist/` folder to Netlify, Vercel, GitHub Pages (with the correct Vite base path), or any static host.

## Journey

- Mystery gift: interactive 3D gift box; tap/click to open.
- Birthday cake: tap the candles or the button to make a wish.
- Secret letter: envelope opens with a personal birthday note.
- Memory garden: three flip cards with editable text.
- Star catcher: collect five stars to unlock the finale.
- Finale: celebratory canvas fireworks and replay.

## Personalize it

- Edit the birthday message in `src/App.jsx`.
- Replace the three `memories` entries with real shared memories.
- To add actual photos, replace each memory card's symbol with an `<img>` and add your images under `public/`.
- Change the colors and typography in `src/styles.css`.

## Notes

- The optional sound button generates a tiny synthesized melody in the browser; it does not load copyrighted music.
- The 3D scene needs WebGL. If a device does not support WebGL, the rest of the page still works, but the 3D scene may not render.
- The project uses Google Fonts when online and falls back to system fonts offline.
