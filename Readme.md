# Nori & Lime — Restaurant Demo Site

A single-page, client-style restaurant website built as a portfolio piece. Concept: a modern fusion restaurant blending Japanese technique with Latin American ingredients and heat.

**[View Live Demo](https://restaurant1sample.netlify.app/)**
## Overview

Built entirely in vanilla HTML, CSS, and JavaScript — no frameworks, no build step, no dependencies beyond Google Fonts. Everything (styles, markup, and scripts) lives in a single `index.html` file.

## Features

- **Hero section** with an animated SVG "collision" mark representing the two cuisines
- **Menu**, styled as a kitchen order ticket (dashed perforated edges, dotted price leaders, mono typeface) with origin tags on each dish
- **Ingredient strip** using hand-drawn SVG icons instead of stock photography
- **Hours & location** section
- **Reservation form** with client-side validation and a confirmation message (front-end only — no backend/email wired up yet)
- Fully responsive down to mobile
- Visible keyboard focus states and `prefers-reduced-motion` support
- Scroll-triggered reveal animations via `IntersectionObserver`

## Tech

- HTML5 / CSS3 (custom properties, CSS Grid & Flexbox)
- Vanilla JavaScript (form handling, scroll reveal)
- Fonts: Fraunces (display), Work Sans (body), JetBrains Mono (utility/menu)

## Design tokens

| Role | Value |
|---|---|
| Background (ink) | `#12201E` |
| Background alt | `#1B2C29` |
| Accent — lime | `#D6E24B` |
| Accent — coral | `#E8543E` |
| Text / paper | `#F2F0E6` |

## Running locally

No build step required — just open `index.html` in a browser.

## Possible next steps

- Wire the reservation form to a real backend (Node/PHP + email, or SQLite)
- Swap SVG ingredient icons for real photography
- Move menu data into a JSON file for easier editing without touching markup

---
Demo project built for portfolio purposes.
