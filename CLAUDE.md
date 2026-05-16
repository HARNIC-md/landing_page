# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

Landing page for **Harnic Telerobotix** — a startup that designs, builds, and operates harvesting telerobots. Dual-purpose: attract investors AND early customers (growers/greenhouse operators). Pre-traction stage.

## Tech Stack

Plain HTML/CSS/JS. No build step. Open `index.html` directly in a browser.

## Structure

```
index.html          — single-page site (all sections)
css/style.css       — all styles, CSS custom properties for theming
js/main.js          — mobile nav toggle only
assets/images/      — robot renders, team photos (to be added)
assets/icons/       — SVG icons (to be added)
```

## Design Principles

Based on transcript.txt analysis — apply these when making changes:
- Write for scanners: bold key points, short paragraphs, minimal copy
- Clarity over prettiness — visitor knows what Harnic does in <3 seconds
- Sell the result (reliable harvests), not the robot specs
- Minimal animation (hover states, smooth scroll only)
- No stock photos — real renders and team photos only
- Repel wrong audience: be bold about what Harnic is and who it serves

## Brand Variables (css/style.css :root)

Colors, fonts, and spacing are all in CSS custom properties. Swap `--color-primary`, `--color-accent`, etc. to rebrand.

## Deployment

Static files — deploy anywhere (GitHub Pages, Netlify, Vercel, S3). No server required.
