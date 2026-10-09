---
name: Nxo Tech Moderno
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#3b494c'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f1f1f1'
  outline: '#6b7a7d'
  outline-variant: '#bac9cc'
  surface-tint: '#006875'
  primary: '#006875'
  on-primary: '#ffffff'
  primary-container: '#00e5ff'
  on-primary-container: '#00626e'
  inverse-primary: '#00daf3'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e5e2e1'
  on-secondary-container: '#656464'
  tertiary: '#5e5e5e'
  on-tertiary: '#ffffff'
  tertiary-container: '#d1d0d0'
  on-tertiary-container: '#595959'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#9cf0ff'
  primary-fixed-dim: '#00daf3'
  on-primary-fixed: '#001f24'
  on-primary-fixed-variant: '#004f58'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c9c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474646'
  tertiary-fixed: '#e3e2e2'
  tertiary-fixed-dim: '#c7c6c6'
  on-tertiary-fixed: '#1b1c1c'
  on-tertiary-fixed-variant: '#464747'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  headline-xl:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.03em
  headline-xl-mobile:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 26px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-md:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.03em
  label-badge:
    fontFamily: Space Grotesk
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 12px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-mobile: 0.75rem
  margin: 1.5rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes an unapologetically modern, direct-to-consumer technology e-commerce experience tailored for the Argentine tech market. Combining the stark visual clarity of Swiss modernism with the relentless conversion focus of contemporary digital retail, it projects precision, transparency, and high performance.

The target demographic consists of tech-savvy buyers, gamers, developers, and creative professionals demanding authentic hardware, immediate financing options (cuotas sin interés), and transparent logistics (envíos en el día). 

The emotional response is immediate confidence and momentum: zero ambiguity, razor-sharp product specs, and unmistakable transactional paths. The brand voice exclusively utilizes standard Argentine Rioplatense ("vos", "comprá", "llevátelo hoy", "calculá tu envío"), speaking directly and without corporate pretense.

## Colors

Color is deployed with extreme discipline:

- **Canvas & Surfaces (`#F8F8F8`):** Serves as the clean, low-glare canvas base. Elevated card containers rest on pure white (`#FFFFFF`) to establish crisp visual separation without heavy decoration.
- **Ink & Structure (`#0A0A0A`):** Deep solid black serves as primary text, core navigational headers, stark promotional banners, and high-impact micro-containers.
- **Electric Accent (`#00E5FF`):** Reserved exclusively for conversion triggers: "Comprar ahora" CTA buttons, discount badges, and key financing highlights ("Hasta 12 cuotas fijas"). Text layered over `#00E5FF` must strictly be `#0A0A0A` at semi-bold or bold weights to ensure maximum WCAG AAA legibility.
- **Subdued Elements (`#737373` & `#E5E5E5`):** Reserved for technical SKU metadata, unselected states, and hairline divider rules.

## Typography

Typography pairs technical confidence with utilitarian legibility:

- **Space Grotesk** commands attention across titles, item pricing, key metric numbers, button labels, and promotional badges. Its geometric, monospaced-adjacent quirks inject technical pedigree.
- **Inter** handles all narrative descriptions, specs tables, product reviews, and transactional disclaimers, ensuring fatigue-free scanning on high-density mobile screens.
- **Pricing & Numeric Hierarchy:** Product price points always use `Space Grotesk` with tabular figures (`font-variant-numeric: tabular-nums`) to align currency signs (`$`) and centavos cleanly across product grids.

## Layout & Spacing

This design system uses a strict mobile-first fluid layout:

- **Mobile (< 768px):** 4-column layout with `1rem` outer canvas padding and `0.75rem` gutters. Interactive elements adhere to a minimum 48px touch boundary for rapid single-handed thumb operation.
- **Tablet (768px - 1024px):** 8-column layout with `1.5rem` margins and `1rem` gutters.
- **Desktop (> 1024px):** 12-column layout capped at a max-width of `1280px` centered, retaining `1.5rem` margins.
- **Vertical Rhythm:** Spacing between product cards, pricing tiers, and buy boxes uses uniform 4px base increments (8px, 16px, 24px, 40px) to maintain structured density without visual noise.

## Elevation & Depth

Visual depth is achieved through structural planar layering and crisp low-contrast borders rather than deep, fuzzy shadows:

- **Base Layer:** `#F8F8F8` page background.
- **Card Surfaces:** Pure `#FFFFFF` with a 1px hairline border in `#EBEBEB`.
- **Active / Hover State:** Cards elevate with a crisp, directional micro-shadow: `0 4px 12px rgba(10, 10, 10, 0.06)` and a border shift to `#0A0A0A`.
- **Modals & Drawers:** High z-index overlays feature a subtle dark backdrop blur (`backdrop-filter: blur(4px); background: rgba(10, 10, 10, 0.4)`) paired with solid `#FFFFFF` sheets to focus user intent entirely on the checkout or filter flow.

## Shapes

The design system maintains a modern, engineered feel with controlled, soft geometric edges (`0.25rem` base radius). 

Buttons, input fields, and technical spec tags use precise `4px` corner radii, projecting industrial reliability. Full pill-shapes are strictly forbidden except for floating sticky action wrappers or circular icon actions (e.g., "Favoritos" toggle). Badges and cards use `0.25rem` and `0.5rem` respectively to ensure content boundaries remain crisp and architectural.

## Components

- **Primary Transactional Button ("Comprar"):**
  Solid `#00E5FF` fill, `#0A0A0A` text in `Space Grotesk` (weight 700), uppercase or tracking +0.02em. Height 48px on mobile with active press compression (`transform: scale(0.98)`).
- **Secondary Action Button ("Agregar al carrito", "Ver más"):**
  Solid `#0A0A0A` fill with `#FFFFFF` text, or transparent background with a 1.5px `#0A0A0A` stroke and `#0A0A0A` text.
- **Badges & Tags:**
  - *Descuento / Ahorro:* Solid `#00E5FF` background, `#0A0A0A` text, 4px border-radius, `label-badge` typography. Example: `"25% OFF"`, `"ENVÍO GRATIS"`.
  - *Cuotas / Financiación:* Light gray `#EFEFEF` badge with `#0A0A0A` text highlighting payment plans (e.g., `"6 CUOTAS SIN INTERÉS"`).
- **Product Cards:**
  Solid `#FFFFFF` surface, 1px `#EBEBEB` border, 8px radius. Features an edge-to-edge aspect ratio 1:1 image container, high-contrast price lockup, quick-specs list (using `Inter` 12px), and an immediate full-width or icon-based CTA.
- **Form Inputs & Postal Code Checkers ("Calculá el envío"):**
  1px `#D4D4D4` border, `#FFFFFF` interior, 48px height. On focus, transitions instantly to a 1.5px `#0A0A0A` border with zero colored glow. Inline right-aligned button in `#0A0A0A` for instant validation.
- **Selection Controls (Radio & Checkbox):**
  Sharp 2px-corner checkboxes and circular radios. Selected states utilize `#0A0A0A` fill with crisp white glyph marks.
- **Sticky Mobile Buy Bar:**
  Affixed to the bottom viewport on mobile PDPs (Product Detail Pages). Features total price, selected installment info, and a direct `#00E5FF` "Comprar ahora" button.