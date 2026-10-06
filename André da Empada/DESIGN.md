# Design System: André da Empada — Haute Confeitaria Salgada
**Skill:** stitch-design-taste

---

## Configuration — Set Your Style
Dials calibrated for high-end artisanal culinary craft and editorial storytelling:

| Dial | Level | Description |
|------|-------|-------------|
| **Creativity** | `8` | Expressive editorial food studio, inline macro-texture typography in headlines, high typographic contrast, hand-crafted seal stamps. |
| **Density** | `4` | Gallery-airy breathing room, spacious white/dark negative spaces, high sensory focus per dish. |
| **Variance** | `8` | Offset asymmetric Bento grids, dramatic scale tension, non-repeating section geometry. |
| **Motion Intent** | `6` | Fluid spring physics on interactive elements, smooth drawer transitions, zero jitter. |

---

## 1. Visual Theme & Atmosphere
An opulent yet authentic culinary editorial experience celebrating the artisanal mastery of André da Empada in Indaiatuba. The atmosphere bridges an elite Parisian pâtisserie salon with a slow-food wood-fired bakery. Deep velvet obsidian surfaces alternate with organic unbleached flour paper, illuminated by warm Maillard gold reflections and deep bordeaux lacquers. Every section feels deliberate, tactile, and appetizing.

---

## 2. Color Palette & Roles
- **Obsidian Velvet** (`#0b0709`) — Primary dark background canvas, cast-iron depth, velvety and warm.
- **Flour Alabaster** (`#f9f7f4`) — Pure contrast surface, artisanal dough canvas, crisp and organic.
- **Crust Gold** (`#d4af37`) — Signature accent for hot-stamp typography, hairline borders, and pricing illumination.
- **Noble Bordeaux** (`#780a18`) — Primary brand heritage color, wine-wax seal accents, primary order CTAs.
- **Ochre Roast** (`#b87333`) — Secondary golden-baked tone, baking temperature cues, batch identifiers.
- **Smoked Linen** (`#171114`) — Card and bento elevated containers with 1px border `rgba(212, 175, 55, 0.18)`.
- **Muted Yeast** (`#9c948e`) — Secondary descriptive copy, botanical notes, and technical culinary provenance.

### Banned Colors
- Purple/violet neon gradients ("AI Purple").
- Pure black (`#000000`) without warm undertones.
- Oversaturated fast-food reds and chemical yellows.
- Hospital cold whites (`#f0f4f8`).

---

## 3. Typography Rules
- **Display & Noble Signature:** `Fraunces` (weights 400, 600, 700 with soft italic accents) paired with `Cormorant Garamond` — High-contrast editorial grandeur, optical sizing enabled, tight track (`-0.03em`).
- **Body & Menu Copy:** `Plus Jakarta Sans` (weights 400, 500, 600) — Neutral Swiss clarity, generous line-height (`1.65`), 60ch max-width.
- **Culinary Telemetry & Pricing:** `JetBrains Mono` (weights 500, 700) with `tabular-nums` — Batch time, weights in grams (180g / 220g), furnace temperatures, exact currency formatting.
- **Banned:** `Inter`, `Roboto`, default browser serifs (`Times New Roman`, `Georgia`).

---

## 4. Component Stylings
- **Buttons:** Tactile feedback on `:active` (`scale(0.97)`). Primary: Deep Bordeaux with subtle gold rim (`1px solid rgba(212, 175, 55, 0.4)`). Secondary: Ghost border in Crust Gold with parchment hover.
- **Cards & Bento Units:** Generously rounded corners (`1.5rem` to `2rem`). Micro-borders with gold-fused alpha channel (`1px solid rgba(212, 175, 55, 0.15)`). Soft ambient shadows (`0 20px 40px -15px rgba(0,0,0,0.4)`).
- **Stamps & Badges:** No rounded-full pill capsules. Badges use architectural micro-stamps (`rounded-none` or `rounded-md`), uppercase `0.7rem`, `tracking-[0.25em]`, with hairline framing.
- **Order Cart Drawer:** Bottom-sheet / side-tray with real-time recalculation of units and instant WhatsApp deep-link generation.
- **Loaders & Shimmers:** Warm parchment shimmer reflecting gold light, never tech spinners.

---

## 5. Hero Section
- **Inline Image Typography:** Signature technique where macro food photography of golden crust and velvety filling is nestled inline within the display headline (`O Segredo da [img] Massa Quebradiça`).
- **Asymmetric Composition:** Left-aligned commanding narrative with right-offset monumental hero plate showcase.
- **Frictionless Action:** Single primary CTA to explore the daily oven batch or build an artisanal box, backed by direct WhatsApp transmission.

---

## 6. Layout Principles
- **Grid-First:** CSS Grid with 12-column architecture and asymmetric spans (7/5, 8/4, Bento 2fr 1fr 1fr).
- **Zero Tech Contamination:** No loading battery meters, no gamer rank gauges, no tech switch toggles.
- **Containment:** Max-width 1360px with generous margins (`clamp(1.5rem, 5vw, 4rem)`).
- **Responsive Collapse:** Strict single-column graceful degradation below 768px with full-width touch targets.

---

## 7. Motion & Interaction
- **Spring Dynamics:** `cubic-bezier(0.16, 1, 0.3, 1)` for all transforms.
- **Micro-Interactions:** Subtle steam pulse, delicate zoom on hero photography hover, tactile button depression.
- **Accessibility:** Compulsory `prefers-reduced-motion` fallbacks.

---

## 8. Anti-Patterns (Banned)
- Zero emojis anywhere in code, copy, or interface.
- No `Inter` font.
- No AI pill capsules (`rounded-full` text badges).
- No sparkles or magical AI symbols.
- No generic 3-card horizontal rows.
- No fake numbers or marketing slop ("Revolucione", "Next-Gen", "Seamless").
