# KL Night Street

A 3D scroll-driven website for KL Night Street, a night market in Rampai Business Park, Kuala Lumpur.

## Pages

- **[index.html](index.html)** — the main site. A continuous Three.js scene: the hero photo lives in the 3D world and travels back into a hanging sign as you scroll into the street, past 12 real vendor stalls (as tilt cards) and into a "Visit Us" section with directions.
- **[street-only.html](street-only.html)** — an earlier pure-3D version of the street walkthrough, no photos, kept for reference.
- **[market.html](market.html)** — an earlier version with photos as full-bleed section backgrounds, kept for reference.
- **[compare.html](compare.html)** — a hub linking the main site plus four alternate 3D concept prototypes (`concept-1-cloud.html` through `concept-4-shaft.html`).

## Running locally

No build step — plain HTML/CSS/JS, Three.js loaded from a CDN.

```bash
python3 -m http.server 4173
```

Then open `http://localhost:4173/`.

## Deploying

Static site — works as-is on Netlify, Cloudflare Pages, or GitHub Pages. `index.html` is the homepage.
