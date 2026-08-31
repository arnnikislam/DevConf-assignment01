# DevConf 2026

A responsive static landing page for a fictional three-day developer conference. The site presents the event message, featured speakers, and ticket tiers in a clear, polished single-page experience.

**Live site:** [arnnikislam.github.io/DevConf-assignment01](https://arnnikislam.github.io/DevConf-assignment01/)

## Highlights

- Hero section with a clear registration call to action
- Featured speaker cards for AI/ML, cloud and DevOps, frontend, and security
- Standard, Pro, and Team pricing options
- Responsive layout for desktop, tablet, and mobile displays
- Semantic HTML, descriptive alternative text, keyboard-visible focus states, and reduced-motion support

## Built with

- HTML5
- CSS3
- [Inter](https://fonts.google.com/specimen/Inter) via Google Fonts

## Run locally

This is a dependency-free static website. Open `index.html` in a browser, or serve the folder with any static-file server. For example:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Project structure

```text
.
├── assets/          # Logo, banner, and speaker imagery
├── styles/style.css # Site styles and responsive rules
└── index.html       # Single-page markup
```

## Deployment

The site is suited to GitHub Pages. In the repository settings, select **Deploy from a branch**, then choose the branch and root folder containing `index.html`.
