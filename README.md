# Jarvis

A personal daily-planning PWA. One page, no build step, no backend.

- **Today** — an auto-assembled checklist: recurring routines due today, plus the one project the scheduler picked for tonight's focus block.
- **Projects** — anything with a finish line. Give it a size, a deadline, and a priority; it gets paced across your focus nights automatically.
- **Routines** — ongoing habits on any cadence (daily, every N days, certain weekdays, biweekly, monthly).
- **Plan** — a 10-day forward projection and deadline outlook that recalculates whenever anything changes.

All data is stored in the browser's `localStorage` on the device — nothing is sent anywhere, and nothing personal lives in this repo. The starter routines are generic examples; replace them with your own.

## Running it

Serve the folder over HTTP (not `file://`, which blocks storage):

```
python -m http.server 8000
```

then open `http://localhost:8000/`. Deployed as a static site (e.g. GitHub Pages) it installs to a phone home screen and works offline.
