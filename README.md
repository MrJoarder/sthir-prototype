# Sthir — ICU, Ambulance & Blood, Located

A single-file prototype for a medical emergency services platform: nearest ICU beds
(with per-day rates and booking), nearest ambulances (with call/dispatch), and nearest
blood banks (with unit availability), all located from the user's live position.

Everything runs client-side with mock data — no backend required.

## Run locally
Just open `index.html` in a browser.

## Deploy on GitHub Pages
Settings → Pages → Deploy from branch → `main` → `/ (root)`. The site will be live at
`https://<your-username>.github.io/<repo-name>/`.

## Stack
- Vanilla HTML/CSS/JS (no build step)
- [three.js](https://threejs.org/) (r128) for the 3D network visualization
- Google Fonts: Fraunces, Inter, IBM Plex Mono

## Notes
Availability, rates, and network stats shown are mock data for demonstration only.
