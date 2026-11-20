## Summary of Changes

Provide a clear, high-level overview of the architectural, visual, or motion choreography changes introduced in this Pull Request.

---

## Related Issues

Closes #<!-- issue number -->

---

## Type of Change

- [ ] **Motion & Scroll Choreography** (`GSAP`, `ScrollTrigger`, `Lenis`, `SplitText`, or pointer parallax)
- [ ] **UI Component / Drawer Architecture** (DOM rendering, interactive modals, navigation, boutique carousel)
- [ ] **Design System & Typography** (CSS tokens, responsive grid, fluid typography, or layout polish)
- [ ] **Bespoke Photography & Editorial Content** (`public/images/`, `brandData.js`, or `docs/BRAND_SPEC.md`)
- [ ] **Bug Fix / Performance Optimization** (60fps frame pacing, layout shift prevention, memory cleanup)
- [ ] **Build / DevOps / Documentation** (`Vite`, `Bun`, `.github/`, or `README.md`)

---

## Visual Verification (Before / After)

> For any visual, layout, or motion change, attach screenshots or a short screen recording below.

| Before | After |
| :--- | :--- |
| <!-- Paste screenshot or video --> | <!-- Paste screenshot or video --> |

---

## Engineering & Quality Checklist

- [ ] **Production Build Verified:** `bun run build` completes with zero errors or broken asset paths.
- [ ] **Relative Asset Paths Preserved:** All static media references use `./images/...` for seamless GitHub Pages compatibility.
- [ ] **60fps Motion Integrity:** ScrollTriggers and pointer parallax listeners clean up properly and avoid layout thrashing.
- [ ] **Responsive Verification:** Tested across Desktop (`1440px+`), Tablet (`1024px`), and Mobile (`390px`) breakpoints.
- [ ] **Accessibility & Semantics:** Verified semantic HTML5 structure, `aria-expanded` / `aria-hidden` toggles, and `Escape` key drawer dismissal.
- [ ] **Documentation Updated:** Updated `README.md` or `docs/BRAND_SPEC.md` if public APIs, tokens, or assets changed.
