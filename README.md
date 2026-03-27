# FORGE CLI — Landing Page

A Neo-Brutalist landing page for **FORGE**, a fictional CLI task runner tool built as a frontend design project.

## What This Is

This is a **static HTML landing page** — a single self-contained file (`forge-landing.html`) that demonstrates what a production-grade marketing page for a CLI tool might look like. No frameworks, no build step, no dependencies. Just HTML, CSS, and vanilla JS.

The tool it advertises ("Forge") is fictional — a concept for a zero-config Node.js task runner.

## What We Built

- `forge-landing.html` — the full landing page

### Design System
- **Aesthetic**: Neo-Brutalist — raw, mechanical, unpolished-on-purpose
- **Colors**: `#FFD700` yellow dominant, pure black/white only
- **Borders**: 4px solid black on every element
- **Shadows**: Hard offset box-shadows (`4px 4px 0 #000`), zero blur
- **Fonts**: `Syne Mono` for display headings, `IBM Plex Mono` for body — 100% monospace

### Sections
1. **Sticky Nav** — black bar with yellow logo and press-state CTA
2. **Split Hero** — grid-textured yellow left panel, animated dark terminal on right
3. **Scrolling Ticker** — infinite marquee of feature labels
4. **Features Grid** — 6 cards, borders-as-layout, full inversion on hover
5. **Stats Bar** — bold display numbers (10x faster, 0ms startup, 48kb, 100% TypeScript)
6. **How It Works** — step list + syntax-highlighted code block showing a sample `forge.js`
7. **CTA Section** — giant watermark text, install command with copy-to-clipboard
8. **Footer** — minimal black footer with links

### Interactions
- **Press effects**: buttons translate `(2px, 2px)` on hover, `(4px, 4px)` on active — shadow shrinks in sync to simulate a physical keypress
- **Terminal animation**: staggered typewriter reveal on page load
- **Copy button**: copies `npm install -g forge-cli` to clipboard with feedback state
- **Scroll reveal**: feature cards and stats animate in on scroll

## How to View

Open `forge-landing.html` directly in any browser. No server needed.

## Stack

- Pure HTML5 / CSS3 / Vanilla JavaScript
- Google Fonts (Syne Mono, IBM Plex Mono)
- No build tools, no npm, no dependencies

---

*This is a design/frontend exercise. The FORGE CLI package does not exist on npm.*
