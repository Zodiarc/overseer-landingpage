# Overseer Landing Page v3.1

Single-file GitHub Pages landing page with progressive JavaScript animations.

## Improvements over v3

- Scroll reveal effects
- Animated hero run with changing node states and live activity
- Animated workflow visualization with a demonstrated failure/recovery loop
- Control-layer status pings
- Subtle desktop pointer parallax on the run console
- `prefers-reduced-motion` support
- No external JavaScript, CSS, fonts, CDNs or assets

The page remains fully visible and usable if JavaScript is disabled.

## Deploy

Replace the contents of the GitHub Pages repository root with:

- `index.html`
- `.nojekyll`
- optionally `README.md`

Then run:

```bash
git add -A
git commit -m "Add embedded animations to Overseer landing page"
git push
```

If Pages already deploys from `main` and `/(root)`, nothing else needs to be changed.
