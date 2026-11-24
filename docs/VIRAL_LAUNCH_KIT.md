# VALTOR — Viral GitHub Launch, SEO & Distribution Kit

> **Target Repository:** `valtor` — *VALTOR V9 Aquila Digital Flagship*  
> **Category:** Creative Coding · Luxury Web Design · GSAP + Lenis Motion Architecture · Awwwards-Grade Showcase  
> **License:** Proprietary / All Rights Reserved

---

## 1. GitHub Repository Settings (Copy & Paste)

### Repository Description (Max 160 chars)
```text
Awwwards-grade luxury automotive flagship built with Vanilla JS, GSAP ScrollTrigger, Lenis smooth scroll, custom SplitText engine, and dual-axis parallax.
```

### Alternative Short Description
```text
Editorial luxury digital flagship for VALTOR Automobiles S.A. — GSAP ScrollTrigger choreography, Lenis smooth scroll, custom SplitText, and 60fps parallax.
```

### Website URL
```text
https://annoris.github.io/valtor/
```

### GitHub Repository Topics (Add all 20 max tags)
```text
gsap, scrolltrigger, lenis, smooth-scroll, creative-coding, awwwards, webgl-inspired, luxury-design, split-text, parallax, vite, vanilla-js, design-engineering, frontend-architecture, motion-design, swiss-design, automotive-ui, css-grid, interactive-storytelling, micro-interactions
```

---

## 2. Social Preview & SEO Metadata Pack

### Open Graph / Social Card Specs
- **Recommended Social Preview Image:** `public/images/hero-v9-aquila.jpg` (or a `1280×640` composite showing the hero + 3-layer parallax gallery)
- **SEO Title:** `VALTOR — Hand-Built Swiss Coachwork & 60fps Motion Architecture`
- **SEO Meta Description:** `An Awwwards-grade digital flagship showcase for VALTOR Automobiles S.A., featuring custom SplitText typography, Lenis + GSAP ScrollTrigger choreography, clip-path cinema reveals, and dual-axis heritage parallax.`

### Primary High-Intent Keywords
`gsap scrolltrigger template`, `lenis smooth scroll example`, `free splittext alternative vanilla js`, `awwwards website source code`, `luxury brand landing page github`, `clip-path scroll animation gsap`, `mouse parallax gallery javascript`, `swiss editorial web design`

---

## 3. Viral X (Twitter) Launch Thread

### Tweet 1 (Hook + 60fps Video Recording)
```text
We just launched VALTOR — an Awwwards-grade luxury automotive digital flagship built with zero UI frameworks.

Pure Vanilla ES Modules + @greensock ScrollTrigger + @darkroomdevs Lenis + a dependency-free SplitText engine running at a locked 60fps.

Live showcase & architecture breakdown below 🧵👇
```
*(Attach a 25-second 60fps screen capture showing the monogram preloader → hero cascade → 3-layer parallax gallery → clip-path dark reveal → heritage pointer collage)*

### Tweet 2 (The Custom SplitText Engine)
```text
1/ Dependency-Free SplitText Engine

Most developers hit a paywall or bundle heavy wrappers just to animate masked lines & characters.

We built a lightweight custom SplitText utility in `src/animations/splitText.js` that splits DOM nodes into masked lines, words, and chars—and cleanly reverts them.
```

### Tweet 3 (Lenis + GSAP Ticker Sync)
```text
2/ Sub-Pixel Smooth Scroll Synchronization

To eliminate jitter between inertial scrolling and scroll-linked timelines, Lenis is bound directly into GSAP's internal requestAnimationFrame ticker with `lagSmoothing(0)`:

```js
lenis.on('scroll', ScrollTrigger.update);
gsap.ticker.add((time) => lenis.raf(time * 1000));
gsap.ticker.lagSmoothing(0);
```
```

### Tweet 4 (Clip-Path Dark Cinema Reveal & Dual Parallax)
```text
3/ Hardware-Accelerated Clip-Path & Dual Parallax

• The "ULTRA FINES INGENII" dark feature section expands from an inset card to full-bleed #000000 via GPU-accelerated `clip-path: inset(...)`
• The 1896 Heritage Collage combines vertical scroll scrubbing with `gsap.quickTo` pointer parallax across 7 depth planes.
```

### Tweet 5 (Live Showcase CTA)
```text
4/ Explore the Live Interactive Flagship & Architecture Blueprint

Includes:
✦ Complete Swiss editorial design system & CSS tokens
✦ 13 bespoke automotive & haute-horlogerie visual assets
✦ Full brand specification in `docs/BRAND_SPEC.md`
✦ Live 60fps interactive experience on GitHub Pages

Explore & star the showcase here:
https://github.com/annoris/valtor
```

---

## 4. Hacker News (`Show HN`) Launch Post

### Title
```text
Show HN: Valtor – Awwwards-style luxury flagship showcase in Vanilla JS, GSAP, and Lenis
```

### First Comment / Body
```text
Hey HN,

We built VALTOR (https://github.com/annoris/valtor), a complete editorial digital flagship for a fictional Geneva-based bespoke coachbuilder (VALTOR Automobiles S.A., Est. 1896).

Many high-end agency and Awwwards showcase sites bury simple scroll mechanics inside massive React/Next.js bundles. We wanted to showcase a clean, 60fps editorial flagship architecture built with pure Vanilla ES Modules, CSS custom properties, GSAP ScrollTrigger, and Lenis.

Technical highlights showcased in the architecture:
1. Custom SplitText Engine (`src/animations/splitText.js`): Dependency-free line, word, and character splitter with overflow mask wrappers for editorial reveals and word-by-word opacity scrubbing.
2. Deterministic Preloader Handshake (`src/animations/preloader.js`): Waits for `document.fonts.ready` and image decode completion before running the SVG monogram draw, lifting the curtain, and triggering the hero SplitText cascade.
3. Multi-Plane Parallax (`src/animations/sections.js`): Combines 3-layer asymmetric scroll parallax with a 7-tile archival canvas driven simultaneously by ScrollTrigger scrub and `gsap.quickTo()` pointer interpolation.
4. Accessibility & Reduced Motion: Full `prefers-reduced-motion: reduce` support and keyboard-accessible drawer state machines (Navigation, Boutique Bag, Newsletter, Film Modal, and Cookie Preferences).

Experience the live flagship at https://annoris.github.io/valtor/ — would love your feedback on the motion architecture and visual choreography!
```

---

## 5. Product Hunt Launch Copy

- **Name:** VALTOR Digital Flagship
- **Tagline:** Awwwards-grade luxury showcase with GSAP & Lenis
- **Topics:** Design Tools, Web Development, Creative Coding, User Experience
- **Maker's Comment:**
```text
Hi Product Hunt! 👋

We're thrilled to share VALTOR — a digital flagship showcase for creative developers and design engineers who love Swiss editorial typography and choreographed scroll storytelling.

Highlights of the architecture:
• A custom zero-dependency SplitText engine for line-masked reveals and scroll-scrubbed manifesto copy
• Seamless Lenis + GSAP ScrollTrigger synchronization
• A 3-layer parallax craft gallery & dual scroll/mouse heritage collage
• Interactive boutique carousel, shopping bag drawer, and inline cinema player
• Complete brand & design specification (`docs/BRAND_SPEC.md`)

Explore the live 60fps showcase and architectural blueprints on GitHub!
```

---

## 6. Reddit Launch Posts

### `r/webdev` & `r/javascript` (Showoff Saturday / Technical Showcase)
**Title:**
```text
I built an Awwwards-style luxury automotive flagship showcase with Vanilla JS, GSAP ScrollTrigger, Lenis, and a custom SplitText engine
```
**Body:**
```text
I frequently see questions on how creative agencies build smooth-scrolling editorial sites with masked text reveals, clip-path section transitions, and multi-depth mouse/scroll parallax without tanking performance or shipping 500KB of framework overhead.

I put together **VALTOR** as an interactive architectural showcase:
- **Stack:** Vanilla ES Modules + Vite + GSAP (`ScrollTrigger`) + Lenis
- **Custom SplitText (`src/animations/splitText.js`):** Handles character, word, and masked-line splitting natively with automatic `revert()` cleanup.
- **Clip-Path Scroll Reveal:** Smoothly transitions the viewport from an inset card to a full-bleed `#000000` cinema section on scroll.
- **Dual-Axis Heritage Collage:** 7 archival tiles that respond simultaneously to vertical scroll velocity and `gsap.quickTo` cursor tracking.
- **Interactive UI Controller:** Full state management for top navigation drawer, boutique slider, live shopping bag drawer, newsletter modal, and cookie consent.

Repo link: https://github.com/annoris/valtor

Happy to answer any questions about GSAP ticker sync, avoiding layout shifts during SplitText initialization, or structuring vanilla JS motion architectures!
```

---

## 7. Quick-Push Commands to Go Live on GitHub

Once your GitHub repository is created (e.g., `https://github.com/annoris/valtor.git`), run:

```bash
git remote add origin https://github.com/annoris/valtor.git
git branch -M main
git push -u origin main
```
