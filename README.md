# Aarzoo Chourasia — Data Engineer Portfolio

A clean, professional developer portfolio for a Senior Data Engineer. Built with pure HTML, CSS, and JavaScript. Designed to be hosted on GitHub Pages.

## Structure

```
portfolio/
├── index.html              # Main portfolio page
├── README.md
├── projects/
│   ├── realtime-pipeline.html
│   ├── ml-feature-store.html
│   ├── data-lakehouse.html
│   ├── analytics-platform.html
│   ├── data-quality.html
│   └── streaming-dashboard.html
├── articles/
│   ├── kafka-at-scale.html
│   ├── dbt-patterns.html
│   ├── iceberg-migration.html
│   ├── data-contracts.html
│   ├── feature-stores.html
│   └── streaming-vs-batch.html
└── assets/
    ├── css/
    │   └── style.css       # Full design system
    ├── js/
    │   └── main.js         # Theme toggle, scroll animations
    └── images/             # Add your images here
```

## Features

- **Light/Dark mode** — persisted to localStorage, respects system preference
- **Scroll reveal animations** — sections fade up as they enter the viewport
- **Fully responsive** — works on mobile, tablet, desktop
- **Zero dependencies** — no npm, no build step, no frameworks
- **Accessible** — semantic HTML, ARIA labels, keyboard navigable

## Customisation

### 1. Change name & info
Edit `index.html` and update:
- Hero section name and title
- Stats grid numbers
- About section bio
- Contact links (GitHub, LinkedIn, Medium, Email)

### 2. Add your projects
Each project card in `index.html` links to a corresponding file in `projects/`.
The project detail pages are templates — replace the placeholder content with your real project details.

To add a project image, drop the file in `assets/images/` and replace the `<div class="project-img-placeholder">` with:
```html
<img src="../assets/images/your-image.jpg" alt="Project name" />
```

### 3. Add your articles
Article pages in `articles/` are ready-to-fill templates.
Update the article cards in `index.html` and the content in each article file.

### 4. Update the colour accent
The amber/gold accent colour is defined in `assets/css/style.css`:
```css
--accent: #c8932a;        /* light mode */
--accent: #d4a43a;        /* dark mode */
```
Change these to your preferred accent colour.

## Deploy to GitHub Pages

1. Push this folder as the root of your GitHub repo (or a `docs/` subfolder)
2. In repo Settings → Pages, set source to the branch and folder
3. Your portfolio will be live at `https://yourusername.github.io/`

No build required — GitHub Pages serves static HTML directly.
