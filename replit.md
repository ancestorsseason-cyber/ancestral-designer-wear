# A.D.W — Ancestral Designer Wear

## Project overview
Static pre-built React site for the A.D.W fashion brand. Contains only compiled output (HTML, JS, CSS, images) — no editable source code.

## How to run
Served via Python's built-in HTTP server:
```
python3 -m http.server 5000
```
Workflow: **Start application** — configured and running on port 5000.

## Key files
- `index.html` — main entry point; includes a spinning logo loading screen
- `assets/logo-ancestral-nobg.png` — background-removed logo (transparent PNG)
- `assets/logo-ancestral-Bfj8ePHN.png` — original logo
- `assets/index-LdP0aVkv.js` — compiled React bundle
- `assets/index-6xHyJjNy.css` — compiled styles

## Loading screen
A CSS/JS loading screen is injected directly in `index.html`. The logo spins until the page `load` event fires (+ 800 ms grace period), with a 5 s safety fallback. Respects `prefers-reduced-motion`. Uses `role="status"` for accessibility.

## User preferences
