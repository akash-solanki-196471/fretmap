# Fretmap

Memorize the notes on a standard-tuned guitar neck. Timed visual drills with real plucked-string audio (Karplus-Strong synthesis — no samples).

**Drills**
- **Find the note** — a note name appears; tap its position before the timer runs out. Optional *specific string* constraint for complete neck coverage.
- **Find all** — tap *every* position of a note across the neck. Timer scales per position.
- **Name the note** — a position lights up; name it.

**Configurable:** timer (1–10s), fret range (0–5 / 0–7 / 0–12), naturals vs. all 12 notes, sound on/off.

## Run / deploy

`index.html` is fully self-contained (React via CDN). Open it locally, or deploy anywhere static:

- **GitHub Pages:** Settings → Pages → Deploy from branch → `main` / root
- **Netlify / Vercel:** point at this repo, no build step needed

`src/fretboard-trainer.jsx` is the React component source if you want to move to a Vite build later.

---
Built with Claude.
