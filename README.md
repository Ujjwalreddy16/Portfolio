# Portfolio — Ujjwal Reddy

Single-file, dark/modern portfolio site. All CSS/JS is inline; the only external
dependencies are three CDN scripts for motion (GSAP, ScrollTrigger, Lenis).

## Files
- `index.html` — the portfolio (inline CSS + JS; CDN scripts for animation)
- `resume.pdf` — the résumé the site links to (replace with a new file of the same name to update)
- `resume.html` — print-friendly HTML résumé (open → Print → Save as PDF)

## Motion layer
- **Lenis** — smooth scrolling
- **GSAP + ScrollTrigger** — hero entrance, scroll-reveal staggers, glow parallax,
  animated stat counters, scroll progress bar, active-nav highlighting, magnetic buttons

If the CDN scripts fail to load, or the visitor has "reduce motion" enabled, the
page falls back to fully visible static content — nothing breaks.

## Preview locally
Open `index.html` in a browser (needs internet for the animation CDNs). No build step.

## Deploy

**GitHub Pages**
1. Push this folder to a repo (e.g. `Ujjwalreddy16.github.io` or any repo)
2. Settings → Pages → Source: `main` branch, `/root`
3. Site is live at `https://ujjwalreddy16.github.io/<repo>/`

**Netlify / Vercel** — drag the folder onto the dashboard, or connect the repo. No config needed.

## Editing
All content lives directly in `index.html`. Search for a section id (`#about`, `#projects`, etc.) and edit the markup.
