# Fretmap

Memorize the notes on a standard-tuned guitar neck. Visual drills with real plucked-string audio (Karplus-Strong synthesis — no samples), at your own pace or against the clock.

**Live:** https://akash-solanki-196471.github.io/fretmap/

**Drills**
- **Find the note** — a note name appears; tap its position. Optional *specific string* constraint for complete neck coverage.
- **Find all** — tap *every* position of a note across the neck.
- **Name the note** — a position lights up; name it.

**Pace**
- **Relaxed** — no countdown, no pressure. The default way to learn.
- **Timed** — race a 2–15s clock (default 6s); beating half the clock earns bonus XP.

**Progress & gamification** (saved in localStorage, per device)
- XP and levels — every correct answer earns XP; streaks of 5/10/20/40 in a row earn milestone bonuses.
- Lifetime stats — accuracy, best streak ever, daily practice streak.
- Per-note accuracy bars, with weak spots flagged.
- **Adaptive drilling** — the trainer serves your weakest notes more often, so it self-tunes to whatever you haven't learned yet.
- Session recap on Stop — accuracy, speed, and XP vs. your previous session.

**Feedback** — the in-app feedback form files a prefilled [GitHub issue](https://github.com/akash-solanki-196471/fretmap/issues) on this repo.

**Configurable:** fret range (0–5 / 0–7 / 0–12), naturals vs. all 12 notes, sound on/off, adaptive on/off.

## Run / deploy

`index.html` is fully self-contained (React via CDN). Open it locally, or deploy anywhere static:

- **GitHub Pages:** Settings → Pages → Deploy from branch → `main` / root (this is how the live site is deployed)
- **Netlify / Vercel:** point at this repo, no build step needed

`src/fretboard-trainer.jsx` is the React component source if you want to move to a Vite build later.

---
Built with Claude.
