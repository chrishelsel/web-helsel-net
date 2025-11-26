# web-helsel-net

Minimalist landing page for **helsel.net**, hosted via GitHub Pages.

This repo contains a single static HTML file that renders a clean, centered wordmark:

> `helsel`

No navigation, no email link, no tracking — just a quiet, intentional placeholder for the domain.

---

## Overview

- **Domain:** `helsel.net`
- **Hosting:** GitHub Pages (deployed from this repository)
- **Stack:** Plain HTML & CSS (no build tools, no JavaScript)
- **Design goals:**
  - Minimalist and understated
  - Centered content that scales with screen size
  - Respect system light/dark mode where supported
  - No interactive elements or contact links

---

## Page Design

The page consists of:

- A full-height viewport layout
- Centered text: `helsel` in all lowercase
- White background with black text in light mode
- Near-black background with soft off-white text in dark mode
- Typography that scales with the viewport using `clamp()` so it looks good on:
  - Desktop monitors
  - Tablets (portrait and landscape)
  - Mobile (portrait and landscape)

Key styling decisions are defined directly in `index.html` inside a `<style>` block to keep the project self-contained and simple.

---

## Project Structure

```text
/
└── index.html   # Single-page static site for helsel.net
