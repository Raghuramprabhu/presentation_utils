# presentation_utils
## Tools

- `deepavali/` — **Diya Cloud**: live word cloud. Open `deepavali/` on the projector laptop (presenter view); phones join through the QR code (`#join=<session>`). Messages go through the public [ntfy.sh](https://ntfy.sh) relay, no backend.
- `deepavali/show.html` — Deepavali TMOD projector show.
- `checkin/` — **DTC Hackathon 2026 check-in**: the projector shows a supply vent that blows the QR code into place, a thermostat for headcount, and teams as zones. Settings live in a hidden control panel (Shift+S or triple-click the title): upload a team CSV or paste from Excel, rename teams, open check-in. Phones find their name and their fan spins faster as teammates arrive. The team list stays in the presenter's browser; it is never committed. Same ntfy.sh relay, no backend.
- `studio/`: **Motion Studio** (prototype), the first piece of a free, open-source Mentimeter-style tool. Add text, press Draw path and sketch a route, and the text flies along it and lands where it sits. Drag bars in the timeline to set timing, pick a motion feel (Smooth, Overshoot, Elastic and more) and a landing effect (sparks, confetti, ripple). Present plays it full screen. Decks save to the browser, to a JSON file, or into a share link (compressed into the URL, so there is no backend). Built only with MIT/ISC libraries: Konva, Anime.js 3 and canvas-confetti.

Live at https://raghuramprabhu.github.io/presentation_utils/ once GitHub Pages is enabled (Settings → Pages → Deploy from a branch → `main`, `/ (root)`).
