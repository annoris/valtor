# Contributing to VALTOR — V9 Aquila Digital Flagship

Thank you for your interest in contributing to the **VALTOR — V9 Aquila Digital Flagship**. This project exemplifies Swiss editorial typography, minimalist architectural grid systems, and 60fps hardware-accelerated motion choreography powered by **GSAP**, **Lenis**, and a dependency-free custom `SplitText` engine.

To preserve the engineering rigor and visual discipline of the repository, please review the guidelines below before submitting issues or pull requests.

---

## 1. Code of Conduct

All contributors, maintainers, and community participants are required to uphold our [Code of Conduct](./CODE_OF_CONDUCT.md). Please treat fellow engineers and designers with professional respect.

---

## 2. Architectural & Design Principles

Before proposing changes, ensure your contribution aligns with our core architecture specifications (documented in [`docs/BRAND_SPEC.md`](../docs/BRAND_SPEC.md)):

1. **Zero Framework Bloat:** The application is written in clean, modular ES2022+ Vanilla JavaScript (`src/components/`, `src/animations/`, `src/data/`) bundled via **Vite**. Do not introduce heavy UI runtime dependencies (React, Vue, Tailwind, etc.).
2. **Monochrome Architectural Palette:** All UI surfaces strictly adhere to the `#FFFFFF`, `#000000`, `#F0F0F0`, and `#101010` token system defined in `src/styles/tokens.css`. Color accents belong exclusively to photographic media.
3. **60fps Motion Budget:**
   - All scroll animations must synchronize with the single **Lenis** instance via `gsap.ticker`.
   - Animate only compositor-friendly properties (`transform`, `opacity`, `clip-path`).
   - Respect `prefers-reduced-motion: reduce` across all animations and interactive drawers.
4. **Relative Asset Resolution:** All static assets in `public/images/` must be referenced via relative `./images/...` paths so builds deploy cleanly to both root domains and GitHub Pages subpaths (`base: './'`).

---

## 3. Development Workflow

### Prerequisites
- **Bun** (`>= 1.1.0`, recommended) or **Node.js** (`>= 20.0.0`)

### Local Setup
```bash
# 1. Clone the repository
git clone https://github.com/annoris/valtor.git
cd valtor

# 2. Install dependencies
bun install

# 3. Start the Vite development server (http://localhost:5173)
bun run dev
```

### Pre-Submission Verification
Before opening a Pull Request, verify that the production bundle compiles with zero warnings or broken asset links:

```bash
bun run build
bun run preview
```

Verify the following in a headless or desktop browser:
- Zero console errors or uncaught promise rejections.
- Preloader sequence completes cleanly and reveals the hero headline cascade.
- Navigation drawer, Boutique shopping bag drawer, Newsletter drawer, Cookie modal, and inline film modal open and close smoothly via both pointer and `Escape` key.

---

## 4. Pull Request Process

1. **Fork & Branch:** Create a descriptive feature or bugfix branch from `main` (e.g., `feat/parallax-touch-tuning` or `fix/split-text-resize`).
2. **Atomic Commits:** Use clear, conventional commit messages (`feat:`, `fix:`, `perf:`, `docs:`, `style:`).
3. **Document Visual Changes:** If your PR modifies UI layout, typography, or scroll choreography, include before/after screenshots or a screen recording in the PR description.
4. **Licensing Alignment:** Contributions submitted to this repository are governed by the repository's [Proprietary License](../LICENSE) (**All Rights Reserved**).

---

## 5. Supporting the Project

If you would like to voluntarily sponsor ongoing motion engineering research and showcase maintenance, you may contribute via **Solana (`3HvUMCUSSHEdtA35UuD4J7mbgpTxJ7LgT2X7GfdzvBdm`)**. Full details are available in [`SPONSORS.md`](../SPONSORS.md). For commercial licensing inquiries, please contact the author directly (see [`LICENSE`](../LICENSE)).
