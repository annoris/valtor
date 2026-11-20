---
name: "Bug Report"
about: "Report a visual, animation, scroll choreography, or interactive regression in VALTOR"
title: "[BUG] "
labels: ["bug", "triage"]
assignees: []
---

## Overview

Provide a concise editorial summary of the issue encountered on the **VALTOR — V9 Aquila Digital Flagship**.

---

## Affected Area

Please check all modules or sections impacted by this issue:

- [ ] **Cinematic Preloader** (Monogram SVG stroke / curtain reveal / hero cascade)
- [ ] **Smooth Scroll Engine** (`Lenis` + `GSAP` ticker synchronization)
- [ ] **Custom `SplitText` Engine** (Line masks, word reveals, or scroll-scrubbed opacity)
- [ ] **3-Layer Parallax Craft Gallery** (Asymmetric grid or vertical depth scrub)
- [ ] **Dark Feature Reveal** (`clip-path: inset(...)` scroll expansion or inline film modal)
- [ ] **Heritage Archival Collage** (7-tile dual scroll + mouse pointer parallax)
- [ ] **Boutique Showcase & Drawers** (Carousel, Shopping Bag, Navigation overlay, Newsletter, Cookie drawer)
- [ ] **Responsive Layout / Typography** (`Barlow Condensed`, `Inter`, `PT Serif` rendering)
- [ ] **Build / Deployment** (`Vite`, `Bun`, or GitHub Pages asset paths)

---

## Steps to Reproduce

1. Start the application or open `...`
2. Scroll to section `...` / trigger interaction `...`
3. Observe behavior `...`

---

## Expected vs. Actual Behavior

- **Expected Behavior:**  
  Describe the expected 60fps animation, layout alignment, or drawer state transition.

- **Actual Behavior:**  
  Describe what happened instead (include any console errors or layout shifts).

---

## Visual Evidence (Screenshots / Screen Recording)

> Attach a 60fps screen recording, GIF, or high-resolution screenshot demonstrating the visual or motion defect.

---

## Environment Specification

| Attribute | Details |
| :--- | :--- |
| **OS & Version** | e.g., macOS Sequoia 15.x / Windows 11 / iOS 18 |
| **Browser & Version** | e.g., Chrome 131 / Safari 18 / Arc / Firefox 133 |
| **Viewport / Device** | e.g., Desktop `1920×1080` / Retina `2560×1600` / Mobile `390×844` |
| **Runtime** | e.g., `Bun v1.x` / `Node.js v22.x` |
| **Reduced Motion (`prefers-reduced-motion`)** | `no-preference` / `reduce` |

---

## Additional Context

Add any stack traces, DevTools Performance flamegraph notes, or relevant commit hashes here.
