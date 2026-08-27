# Overseer Landing Page v2

Static GitHub Pages landing page for Overseer.

## What's included

- Product-focused hero section
- Animated mock run / workflow UI
- Capability overview
- Workflow-engine visualization
- Control-layer / human-in-the-loop section
- Provider, SCM and execution integration overview
- Responsive mobile layout
- Scroll reveal animations
- No build process required

## Files

```text
.
├── index.html
├── styles.css
├── script.js
├── .nojekyll
└── README.md
```

## Local preview

From this directory:

```bash
python -m http.server 8080
```

Then open:

```text
http://localhost:8080
```

## Replace the current GitHub Pages site

If your existing landing-page repository is already configured for GitHub Pages:

1. Back up the current files if you want to keep them.
2. Replace the old `index.html` and `styles.css`.
3. Add `script.js`.
4. Keep `.nojekyll` in the repository root.
5. Commit and push:

```bash
git add .
git commit -m "Redesign Overseer landing page"
git push
```

GitHub Pages will redeploy automatically.

## Privacy

The page intentionally describes product capabilities without exposing source code,
internal implementation details, credentials, private repository information or
detailed infrastructure architecture.
