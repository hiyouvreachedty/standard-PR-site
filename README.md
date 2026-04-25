# StandardPR Site

A static HTML marketing website for **StandardPR**, a niche public relations concept focused on helping specialized businesses earn editorial coverage in the publications their actual customers read.

## Overview

This project is a single-page HTML website built as a clean, responsive landing page. The current site includes:

- A structured hero section with primary calls to action.
- Light and dark theme support.
- Responsive layout and typography tokens.
- Pricing, testimonials, FAQ, and niche-industry sections.
- Accessible details like a skip link, focus states, and mobile navigation.

The main site file is `index.html` in the repository root.[1]

## Suggested repo structure

```text
standard-PR-site/
├── index.html
├── README.md
├── assets/
│   ├── images/
│   ├── icons/
│   └── screenshots/
├── docs/
│   ├── content-notes.md
│   ├── brand-notes.md
│   └── launch-checklist.md
└── CNAME
```

## What to add next

### 1. Assets

Move external visual dependencies into a cleaner local structure over time.

- `assets/images/` for hero images, logos, and section visuals.
- `assets/icons/` for favicon files or exported SVG assets.
- `assets/screenshots/` for README preview images.

### 2. Documentation

Use the `docs/` folder to separate planning from the site code.

- `content-notes.md` for messaging, headlines, CTA ideas, and section copy.
- `brand-notes.md` for fonts, color tokens, logo direction, and visual references.
- `launch-checklist.md` for deployment, SEO, QA, and performance checks.

### 3. README improvements

A strong README should include:

- Project summary.
- Live demo URL once GitHub Pages is enabled.
- Screenshot preview.
- Tech summary: HTML, CSS, vanilla JavaScript.
- Deployment notes.
- Known next improvements.

## Deployment setup

For a static site like this, GitHub Pages is the easiest next step.

### Recommended deployment flow

1. Keep `index.html` in the repo root.
2. Enable GitHub Pages from the main branch/root folder.
3. Add a custom domain later with `CNAME` if desired.
4. Enforce HTTPS once the custom domain is configured.

## Launch checklist

- Confirm all placeholder content is intentional.
- Replace any stock imagery with chosen brand visuals.
- Add favicon files.
- Add Open Graph tags and social preview image.
- Run Lighthouse checks for performance, accessibility, best practices, and SEO.
- Test mobile layout thoroughly.
- Add a screenshot and live link to the README.

## Notes

This project is already beyond a rough draft because the current `index.html` includes responsive layout tokens, semantic sections, theme switching, FAQ behavior, and polished section structure.[1]

The next phase is less about rebuilding and more about organizing it like a real portfolio/client-ready repo.
