# Ahren / Visuals

<p align="center">
  <strong>Make it look right.</strong><br>
  A polished portfolio for graphic design, visual design, creative layouts, and Canva work.
</p>

<p align="center">
  <a href="https://kumagod.netlify.app"><img src="https://img.shields.io/badge/Live_Demo-kumagod.netlify.app-00C7B7?logo=netlify&logoColor=white" alt="Live Demo"></a>
  <a href="https://app.netlify.com/sites/kumagod/deploys"><img src="https://api.netlify.com/api/v1/badges/REPLACE_WITH_NETLIFY_SITE_ID/deploy-status" alt="Netlify Deploy Status"></a>
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="MIT License">
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/Responsive-Design-8B5CF6" alt="Responsive Design">
  <img src="https://img.shields.io/badge/Portfolio-Canva-00C4CC?logo=canva&logoColor=white" alt="Canva">
</p>

<p align="center">
  <a href="https://kumagod.netlify.app">View Live Portfolio →</a>
</p>

## About

Ahren / Visuals is a modern, single-page portfolio for Ahren Shalih Mustafa Aryadi (@kumagod), a graphic and visual designer. The experience is intentionally clean, expressive, and easy to navigate—balancing strong typography, a dark visual system, lime and pink accents, and focused calls to action.

The site is designed to be:

- Visually clear, with a memorable creative direction and purposeful composition.
- Fast and lightweight, with a minimal dependency footprint and no build step required for local preview.
- Accessible-minded, using semantic HTML, descriptive metadata, readable contrast, keyboard-friendly links, and responsive layouts.
- Responsive across mobile, tablet, and desktop screens.
- Easy to deploy and maintain through GitHub and Netlify continuous deployment.

## Key Features

- Visual previews: Custom CSS/SVG artwork and service cards communicate the design direction before visitors open a project.
- Canva portfolio showcase: A dedicated CTA links visitors to the complete Canva portfolio.
- Dynamic theme and animations: Dark glassmorphism-inspired surfaces, grid texture, reveal-on-scroll transitions, and subtle hero motion create depth without overwhelming the content.
- Netlify CI/CD auto-deploy: Pushes to the connected GitHub branch trigger a fresh Netlify deployment automatically.
- Clear service positioning: Graphic design, creative layout, presentation and pitch decks, brand identity, and vector assets.
- Mobile-first navigation and layout: Content remains legible and usable at narrow viewport widths.

## Tech Stack

<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Google_Fonts-4285F4?logo=google&logoColor=white" alt="Google Fonts">
  <img src="https://img.shields.io/badge/Canva-00C4CC?logo=canva&logoColor=white" alt="Canva">
  <img src="https://img.shields.io/badge/Netlify-00C7B7?logo=netlify&logoColor=white" alt="Netlify">
</p>

- HTML5 semantic markup
- Tailwind CSS via the official CDN for utility-first styling
- Vanilla JavaScript for Intersection Observer reveal effects
- Inline SVG for lightweight visual previews
- Space Grotesk and JetBrains Mono via Google Fonts
- Canva for the extended portfolio showcase
- Netlify for hosting and continuous deployment

## Project Structure

```text
portfolio-kumagod/
├── index.html                         # Main portfolio page
├── assets/
│   ├── images/                        # Optional exported artwork and previews
│   ├── icons/                         # Optional favicon and social assets
│   └── fonts/                         # Optional self-hosted fonts
├── netlify.toml                       # Optional Netlify build and redirect config
├── README.md
└── LICENSE
```

The current portfolio is intentionally compact: the primary page contains the layout, styles, animations, and inline visual previews in one HTML document. If the source file is currently named `portfolio_kumagod_graphic_designer_v2.html`, rename or copy it to `index.html` before deploying from the repository root.

## Quick Start

### Option 1: Open directly

```bash
git clone https://github.com/ahren17/portfolio-kumagod.git
cd portfolio-kumagod
open index.html             # macOS
# xdg-open index.html       # Linux
# start index.html          # Windows
```

### Option 2: Run a local server

A local server gives the closest browser behavior to production:

```bash
python3 -m http.server 8080
```

Open `http://localhost:8080` and edit `index.html`. Refresh the browser to preview changes.

## Deployment Guide: Netlify + GitHub

1. Push the repository to GitHub.
2. In Netlify, choose Add new site → Import an existing project.
3. Select GitHub and authorize the repository.
4. Use the repository root as the base directory.
5. For this static site, leave the build command empty and set the publish directory to `.`.
6. Select the production branch, usually `main`, and deploy the site.
7. In Site configuration → Domain management, add a custom domain if desired.
8. Every subsequent push to the connected production branch will trigger Netlify CI/CD and publish the latest version.

Live deployment: https://kumagod.netlify.app

> Replace `REPLACE_WITH_NETLIFY_SITE_ID` in the deploy badge URL with the actual Netlify site ID once it is available. This makes the badge report real deployment status instead of displaying a placeholder endpoint.

## Recommended Repository Settings

Repository name: `portfolio-kumagod`

Alternative name: `kumagod-portfolio`

Description: `Ahren's modern graphic and visual design portfolio, built with Tailwind CSS and deployed on Netlify.`

Topics:

```text
portfolio
graphic-design
visual-design
canva
tailwindcss
responsive-web
netlify-deployment
web-design
creative-portfolio
html5
```

## Author

Ahren Shalih Mustafa Aryadi is a graphic and visual designer focused on creating clear, polished, and memorable visual communication for people, products, and businesses.

- GitHub: [@ahren17](https://github.com/ahren17)
- LinkedIn: [Ahren Mustafa](https://www.linkedin.com/in/ahrenmustafa/)
- Canva Portfolio: [View the showcase](https://www.canva.com/design/DAF32pHcEbc/8kHHdWr9cBho_S4uoF2g5w/view)
- Live site: [kumagod.netlify.app](https://kumagod.netlify.app)

## License

Distributed under the MIT License. See `LICENSE` for the full license text.

© 2026 Ahren Shalih Mustafa Aryadi.
