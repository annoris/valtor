# VALTOR — Luxury Brand Identity & Creative Specification

## 1. Core Brand Identity

| Attribute | Specification |
|---|---|
| **Marque Name** | **VALTOR** |
| **Legal Entity** | VALTOR Automobiles S.A. |
| **Flagship Model** | **VALTOR V9 Aquila** |
| **Year Founded** | **1896** |
| **Latin Motto** | *ULTRA FINES INGENII* |
| **English Translation** | *"Beyond the boundaries of ingenuity, craft endures forever."* |
| **Brand Tagline** | Hand-Built Swiss Coachwork & Aviation-Grade Engineering |
| **Atelier HQ Address** | Route de l'Aéroport 42, 1215 Meyrin, Geneva, Switzerland |
| **Concierge Email** | `concierge@valtorautomobiles.com` |
| **Press Email** | `press@valtorautomobiles.com` |
| **Telephone** | `+41 22 518 09 40` |
| **Copyright** | `© 2026 VALTOR Automobiles S.A. All rights reserved.` |
| **Digital Credits** | `Atelier Digital by Maison Nord` |

### Brand Narrative & Heritage Ethos
Founded in Geneva in **1896**, VALTOR began as an independent atelier crafting bespoke aluminum-bodied carriages before pioneering lightweight rotary aero-engines in the 1920s. Today, every **VALTOR V9 Aquila** is assembled entirely by hand in our Geneva atelier—uniting aviation-grade CNC-milled billet titanium, exposed mechanical linkages, hand-stitched full-grain cognac leather, and sculptural coachwork shaped without compromise.

---

## 2. Visual System & Color Tokens

The website strictly preserves a monochrome architectural editorial palette, allowing warm automotive photography (deep emerald-teal metallic coachwork, cognac saddle leather, brushed titanium, and sepia archival film) to command focus.

### CSS Custom Properties
```css
:root {
  /* Core Surfaces */
  --color-bg-light: #FFFFFF;
  --color-bg-dark: #000000;
  --color-surface-card: #F0F0F0;
  --color-surface-drawer: #FDFEFE;

  /* Typography */
  --color-ink-primary: #101010;
  --color-ink-black: #000000;
  --color-ink-white: #FFFFFF;
  --color-ink-muted: rgba(0, 0, 0, 0.5);
  --color-ink-muted-dark: rgba(255, 255, 255, 0.6);

  /* Borders & Hairlines */
  --color-border-hairline: #B2B2B2;
  --color-border-subtle: rgba(16, 16, 16, 0.14);
  --color-border-dark: rgba(255, 255, 255, 0.2);

  /* Photography Accent Reference (Editorial Use Only) */
  --accent-emerald-coachwork: #0F2B28;
  --accent-cognac-leather: #8C4A27;
  --accent-brushed-titanium: #B8BDC0;
}
```

---

## 3. Typography Mapping (Google Fonts)

| Role | Reference Feel | Google Font Selection | Weights & Style |
|---|---|---|---|
| **Display / Headlines** | Ultra-condensed architectural sans | `Barlow Condensed` (fallback: `Oswald`, `Archivo Narrow`) | `500`, `600`, `700` — Uppercase, tight tracking (`-0.01em` to `0.02em`), line-height `0.92`–`1.0` |
| **UI / Body / Navigation** | Crisp Swiss grotesque sans | `Inter` (fallback: `'Helvetica Neue'`, `Helvetica`, `Arial`, `sans-serif`) | `300`, `400`, `500`, `600` — Clean editorial rhythm, body `15px–16px`, eyebrow `11px–12px` uppercase with `0.18em` tracking |
| **Editorial / Motto Accents** | Classic refined serif | `PT Serif` | `400`, `400i`, `700` — Used for heritage numerals, subtle italic motto accents, and editorial quotes |

### Google Fonts Import URL
```html
<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
<link
  href="https://fonts.googleapis.com/css2?family=Barlow+Condensed:wght@400;500;600;700&family=Inter:wght@300;400;500;600&family=PT+Serif:ital,wght@0,400;0,700;1,400&display=swap"
  rel="stylesheet"
/>
```

---

## 4. Bespoke Photography Briefs (12 Assets for Visual Artist)

All 12 images must be saved in `public/images/` using the exact filenames below. Photography should evoke museum-grade European automotive monographs: razor-sharp focus, natural specular highlights on brushed metal, deep tonal contrast, zero CGI gloss, zero watermarks, and zero text overlays.

### 1. `/images/hero-v9-aquila.jpg`
- **Section:** Hero Full-Bleed Background
- **Aspect Ratio:** `16:9` (high-res landscape)
- **Brief:** Dramatic low-angle front-three-quarter studio portrait of the bespoke **VALTOR V9 Aquila** mid-engine coupe. Coachwork finished in deep emerald-teal metallic paint with satin brushed aluminum aerodynamic intake blades, teardrop glass canopy, and forged turbine-spoke alloy wheels. Shot inside a vast minimalist dark obsidian architectural hall with soft overhead linear light reflections tracing the sculpted fenders. Dark atmospheric negative space along the upper-left and center-bottom for crisp white typography legibility.

### 2. `/images/craft-intake-mesh.jpg`
- **Section:** Parallax Gallery — Item 1 (Bespoke Mesh)
- **Aspect Ratio:** `4:5` (vertical editorial)
- **Brief:** Extreme macro architectural detail photograph of a hand-woven brushed titanium and stainless-steel honeycomb air intake grille set into deep emerald-teal metallic coachwork. Subtle warm light grazing across machined aluminum rivets and bevelled edges, shallow depth of field, tactile haute-horlogerie level of metallic precision.

### 3. `/images/craft-turbine-lamp.jpg`
- **Section:** Parallax Gallery — Item 2 (Turbine Tail-Lights)
- **Aspect Ratio:** `4:5` (vertical editorial)
- **Brief:** Close-up studio photograph of a bespoke aviation-inspired circular LED tail-light recessed into a CNC-milled billet aluminum turbine housing on the rear haunch of a deep emerald metallic supercar. Concentric glowing crimson-amber light rings evoking a jet afterburner, crisp reflections on dark gloss coachwork.

### 4. `/images/craft-billet-exhaust.jpg`
- **Section:** Parallax Gallery — Item 3 (Milled Exhausts & Aerodynamics)
- **Aspect Ratio:** `4:5` (vertical editorial)
- **Brief:** Low-angle macro rear detail of twin central CNC-milled brushed titanium exhaust outlets integrated into a sculpted carbon-and-aluminum aerodynamic rear diffuser. Subtle heat-blued patina inside the milled exhaust rims, dramatic chiaroscuro studio lighting emphasizing raw mechanical geometry.

### 5. `/images/feature-obsidian-profile.jpg`
- **Section:** Dark Feature Film Poster & News Article 1
- **Aspect Ratio:** `16:9` (widescreen cinematic)
- **Brief:** Dramatic low-key side-profile silhouette of the VALTOR V9 Aquila parked on wet matte black concrete in a pitch-black Geneva atelier. A single narrow overhead light strip illuminates only the flowing roofline, glass canopy, brushed aluminum side vent, and rear fender haunch—high-contrast cinema still aesthetic.

### 6. `/images/heritage-1896-atelier.jpg`
- **Section:** Heritage Archival Collage (Tiles 1 & 5)
- **Aspect Ratio:** `4:3` (archival landscape)
- **Brief:** Authentic vintage 1896 sepia-toned silver-gelatin archival photograph inside an old-world Swiss coachbuilding workshop. Master craftsmen in leather aprons hand-beating curved aluminum coachwork panels over wooden bucks beneath tall arched factory windows, soft film grain, subtle vignette.

### 7. `/images/heritage-1924-aviation.jpg`
- **Section:** Heritage Archival Collage (Tiles 2 & 6)
- **Aspect Ratio:** `3:4` (archival portrait)
- **Brief:** Authentic 1924 high-contrast black-and-white archival photograph of a gleaming polished-aluminum rotary aero engine mounted to a sleek early monoplane on a misty Alpine airfield tarmac. Crisp mechanical detail, classic medium-format film grain, timeless aviation heritage atmosphere.

### 8. `/images/heritage-1962-alpine.jpg`
- **Section:** Heritage Archival Collage (Tiles 3 & 7) & News Article 3
- **Aspect Ratio:** `16:10` (archival landscape)
- **Brief:** Authentic 1962 black-and-white editorial photograph of a hand-built aluminum grand tourer carving through a misty Swiss Alpine mountain pass framed by stone retaining walls and pine trees. Slight motion blur in the spoked wheels, classic European concours magazine film aesthetic.

### 9. `/images/boutique-monograph.jpg`
- **Section:** Boutique Slide 1 (*The Art of VALTOR* Monograph)
- **Aspect Ratio:** `4:5` (editorial product)
- **Brief:** Luxury minimalist studio product photograph of a thick linen-bound dark charcoal hardcover automotive monograph book resting on a pale honed travertine plinth. Subtle blind-debossed geometric turbine emblem on the cover, crisp gallery daylight casting a soft architectural shadow on a light `#F0F0F0` backdrop.

### 10. `/images/boutique-weekender.jpg`
- **Section:** Boutique Slide 2 (Cognac Weekender) & Boutique Section Background
- **Aspect Ratio:** `16:10` (editorial luxury product)
- **Brief:** Bespoke hand-stitched full-grain cognac saddle-leather weekender travel bag with solid brushed-titanium buckles and quilted diamond-stitched side panels. Photographed on dark charcoal slate in warm directional atelier light, rich leather grain texture, timeless European grand-touring luxury.

### 11. `/images/boutique-chronograph.jpg`
- **Section:** Boutique Slide 3 (Machined Chronograph) & News Article 2
- **Aspect Ratio:** `4:5` (editorial luxury product)
- **Brief:** Haute-horlogerie macro product photograph of a skeletonized mechanical chronograph wristwatch crafted from brushed grade-5 titanium with a dark obsidian dial, exposed gear train, turbine-inspired sub-dials, and a hand-stitched cognac leather strap. Dramatic studio lighting on a neutral architectural stone surface.

### 12. `/images/boutique-gloves.jpg`
- **Section:** Boutique Slide 4 (Cashmere Driving Gloves) & Heritage Collage (Tile 4)
- **Aspect Ratio:** `4:5` (editorial luxury product)
- **Brief:** Editorial overhead studio photograph of a pair of tailored cognac lambskin leather driving gloves with knuckle perforations, brushed aluminum snap fasteners, and fine charcoal cashmere lining peeking from the cuffs. Styled neatly on a light architectural concrete surface with crisp gallery shadows.
