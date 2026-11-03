# Landing Page — Rust Wheel (Web)

A simple, single-page promotional landing page for Rust Wheel, the Pakistan car-and-bike marketplace: a headline, a 0% commission message, three feature cards, and a section pointing visitors to the app and the Rust Wheel Facebook community.

## How to run

Open `index.html` in any browser — no server, build step, or internet connection is needed (the page itself is fully self-contained; only the Facebook group link leaves the page). Or serve it locally:

```bash
python3 -m http.server 8000
```

then open http://localhost:8000 in your browser.

## What was practiced

- A single self-contained HTML/CSS page (no framework, no build step)
- Responsive layout with CSS grid (`auto-fit` / `minmax`) and `clamp()`
- Rust Wheel brand colours: Navy #0B1F3A, Blue #1769AA, Cyan #20A4D8, Sky #EAF6FC
- Writing honest marketing copy: only published claims are used

## Notes

- The figures on the page (0% commission, 500+ listings) are Rust Wheel's published claims, not live counts fetched from the app.
- The page links to the real Google Play listing (https://play.google.com/store/apps/details?id=com.rustinnovations.rustwheel) and to the public Facebook community group.
