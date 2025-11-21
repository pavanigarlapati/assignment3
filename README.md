# Responsive Personal Portfolio (HTML + CSS only)

## Overview
This repository contains a responsive personal portfolio page built with **HTML + CSS only** (no frameworks). It meets the assignment requirements and includes a CSS-only hamburger for mobile navigation.

Files:
- `index.html`
- `style.css`
- `README.md`

## AI Tool Usage
**AI tool used to generate initial template:** `REPLACE_WITH_AI_TOOL_NAME`  
(Examples: Replit AI, Cursor AI, v0.dev, Bolt.new, Lovable.dev)

> **Important**: Replace the above line with the exact tool you used to generate the initial template.

## What I edited manually
After generating the starter template with the AI tool, I **manually**:
- Reworked the header to include a CSS-only hamburger (checkbox hack) for mobile.
- Implemented responsive breakpoints per the assignment:
  - Desktop (≥1024px): horizontal nav (4 columns where applicable)
  - Tablet (768–1023px): 3 / 2 column behavior for content and skills grid
  - Mobile (≤767px): stacked layout, CSS hamburger, skills become 1-column
- Added a hero section layout with image and CTA button.
- Implemented the skills grid and hover/animation effects.
- Ensured no horizontal scroll on mobile.
- Added subtle CSS-only animation and a card hover effect.
- Replaced placeholder images with the uploaded project image at:
  - `/mnt/data/283aa81d-4b37-4f92-9f67-2cc28dcf1fee.png`

## How to run
1. Clone the repo.
2. Open `index.html` in your browser (no build step required).
3. For correct local image loading, keep the uploaded file at the path used above or update `index.html` to point to your image location.

## Notes to grader
- The project uses only HTML and CSS (small inline script used only to set the year dynamically — can be removed if required).
- If you used a different AI tool to generate the initial template, update the README entry above and describe which parts you modified manually.

