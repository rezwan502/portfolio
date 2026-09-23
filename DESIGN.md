---
name: Glacier Obsidian Architectural
colors:
  surface: '#f7f9ff'
  surface-dim: '#cadcf1'
  surface-bright: '#f7f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#edf4ff'
  surface-container: '#e3efff'
  surface-container-high: '#d8eaff'
  surface-container-highest: '#d2e4fa'
  on-surface: '#0b1d2c'
  on-surface-variant: '#3f4850'
  inverse-surface: '#213242'
  inverse-on-surface: '#e8f2ff'
  outline: '#707881'
  outline-variant: '#bfc7d2'
  surface-tint: '#006398'
  primary: '#006194'
  on-primary: '#ffffff'
  primary-container: '#007bb9'
  on-primary-container: '#fdfcff'
  inverse-primary: '#93ccff'
  secondary: '#575f6c'
  on-secondary: '#ffffff'
  secondary-container: '#dbe3f3'
  on-secondary-container: '#5d6572'
  tertiary: '#006387'
  on-tertiary: '#ffffff'
  tertiary-container: '#007da9'
  on-tertiary-container: '#fcfcff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cce5ff'
  primary-fixed-dim: '#93ccff'
  on-primary-fixed: '#001d31'
  on-primary-fixed-variant: '#004b73'
  secondary-fixed: '#dbe3f3'
  secondary-fixed-dim: '#bfc7d6'
  on-secondary-fixed: '#141c27'
  on-secondary-fixed-variant: '#3f4754'
  tertiary-fixed: '#c4e7ff'
  tertiary-fixed-dim: '#7bd0ff'
  on-tertiary-fixed: '#001e2c'
  on-tertiary-fixed-variant: '#004c69'
  background: '#f7f9ff'
  on-background: '#0b1d2c'
  surface-variant: '#d2e4fa'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.03em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.005em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.06em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system channels the pristine, tactile precision of sandblasted architectural glass, cold-rolled titanium, and glacial ice shelves. Built with an editorial, high-end engineering ethos, the visual language avoids decorative gimmickry in favor of optical clarity, structural poise, and calibrated luminescence. 

The aesthetic is a hybrid of **Precision Minimalism** and **Refined Architectural Glassmorphism**. UI surfaces behave like layered panes of optical-grade glass and brushed metal: cool, rigid, and pristine. The emotional response evokes absolute structural integrity, arctic stillness, deliberate restraint, and bespoke technological craft. 

The system serves technical products, advanced engineering suites, and premium enterprise ecosystems where noise is eliminated and every hairline boundary serves a functional purpose.

## Colors

The palette derives its balance from high-contrast obsidian ink set against cool atmospheric ice tones, punctuated by glacial cyan accents.

- **Primary Accent (`#0284C7`)**: Arctic core blue. Reserved for primary interactive anchors, focused states, and significant telemetry highlights.
- **Secondary / Ink (`#0C141F`)**: Deep obsidian navy. Provides commanding contrast for foundational typography, structural icons, and authoritative UI moments.
- **Tertiary Accent (`#38BDF8`)**: Radiant ice-cyan. Employed for active status pings, fine glow highlights, and delicate visual indicators.
- **Neutral Core (`#526375`)**: Cool maritime slate. Calibrated for secondary content tiers, metadata, labels, and muted controls.

### Surface Tiers & Hairline Rules
- **Canvas Base**: `#EDF2F7` to `#F4F7FA`. A cold, mineral wash that grounds the viewport.
- **Raised Containers**: `#FFFFFF`. Ultra-clean, opaque slabs mimicking polished titanium backing behind architectural glass.
- **Glass Overlays**: `rgba(255, 255, 255, 0.72)` paired with `backdrop-filter: blur(16px)` for floating navigational headers and inspection docks.
- **Structural Boundaries**: `#D7E2EA`. Delicate, 1px crisp hairline borders that maintain mathematical structure without visual weight.

## Typography

The type system relies uniformly on **Plus Jakarta Sans**, chosen for its modern geometric rigor balanced by subtle humanist curves. Set in tight tracking at display levels, it mirrors the laser-etched precision of industrial design.

- **Headlines**: Rendered in Obsidian (`#0C141F`) with tight negative tracking (`-0.03em` to `-0.015em`) and condensed leading, commanding technical authority without heavy bulk.
- **Body**: Maintained between 13px and 18px in Cool Slate (`#526375`) to allow long-form scanning without eye strain against pale ice backgrounds.
- **Labels & Monograms**: Transformed to uppercase with deliberate positive tracking (`+0.04em` to `+0.06em`) for categorical tags, unit dimensions, and system indicators.

## Layout & Spacing

The structural layout operates on a 12-column fluid grid on desktop (max width: 1440px) and collapses into a 4-column system on mobile viewports. 

- **Grid Alignment**: Crisp 24px (`1.5rem`) gutters on desktop ensure breathing room akin to wide-aperture architectural floorplates. Margins scale down dynamically on viewports under 768px to 20px (`1.25rem`) to maximize tactile area.
- **Cadence & Rhythms**: Spacing tokens (`space-xs` through `space-xl`) build strictly off a 4px/8px micro-grid. Component interiors employ compact paddings (`space-sm` to `space-md`), preserving dense technical utility while outer layout modules leverage expansive gaps (`space-xl`) to establish high-end editorial calm.

## Elevation & Depth

Visual depth is achieved through cool, diffused ambient occlusion and refractive glass layering rather than heavy, muddy dropshadows.

1. **Flat Base**: Canvas is grounded in `#F4F7FA`. 
2. **Structural Card Surface (Level 1)**: Pure white `#FFFFFF` bounded by a 1px solid hairline `#D7E2EA`. Elevation is rendered through a dual cool-shadow composite:
   - Ambient: `0 1px 3px rgba(12, 20, 31, 0.03)`
   - Diffuse: `0 12px 28px -4px rgba(82, 99, 117, 0.08)`
3. **Glacial Floating Dock / Panel (Level 2)**: Translucent surface `rgba(255, 255, 255, 0.8)` layered with a 20px blur and a subtle icy rim light:
   - Border: `1px solid rgba(215, 226, 234, 0.8)`
   - Top-edge specular stroke: `inset 0 1px 0 0 rgba(255, 255, 255, 0.9)`
   - Metallic drop shadow: `0 20px 40px -8px rgba(12, 20, 31, 0.08), 0 0 1px 1px rgba(2, 132, 199, 0.04)`
4. **Modal Dialogues (Level 3)**: Pure white `#FFFFFF` overlay with a frosted backdrop overlay (`backdrop-filter: blur(8px); background-color: rgba(12, 20, 31, 0.2)`), elevated by a cool directional shadow:
   - Shadow: `0 24px 64px -12px rgba(12, 20, 31, 0.16)`

## Shapes

The design system employs a **Rounded** corner vocabulary (Base factor: 2). 

- Standard interactive controls, form fields, and chip elements utilize an 8px (`0.5rem`) radius.
- Cards, panels, and modular dashboard containers use 16px (`1rem`).
- Large structural viewports, hero banners, and floating modal sheets utilize 24px (`1.5rem`).

The geometric curvature balances clinical precision with the soft optical lensing of smoothed industrial glass edges. Extreme pill shapes are strictly forbidden except for standalone badge capsules to preserve architectural tension.

## Components

### Buttons
- **Primary**: Solid Glacier Blue (`#0284C7`) background with pure white typography (`label-md`). Hover elevates surface brightness to `#0EA5E9` with an ultra-subtle cyan rim glow (`box-shadow: 0 0 12px rgba(14, 165, 233, 0.35)`). Active state depresses to `#0369A1`.
- **Secondary (Titanium Frost)**: Background `#FFFFFF` with 1px border in `#D7E2EA`, typography in `#0C141F`. Hover triggers background tint `#F4F7FA` and border recoloring to `#0284C7`.
- **Ghost**: Transparent fill, Obsidian ink text, transitioning to `rgba(2, 132, 199, 0.06)` on hover.

### Inputs & Form Controls
- Height standardized to 40px with an 8px radius.
- Inactive state: `#FFFFFF` fill with 1px hairline border in `#D7E2EA`. Placeholder rendered in `#526375` (opacity 60%).
- Focused state: Hairline border transitions sharply to `#0284C7` paired with an icy diffuse focus ring: `box-shadow: 0 0 0 3px rgba(2, 132, 199, 0.15)`.

### Cards & Modular Containers
- Structured with `#FFFFFF` backgrounds and 16px radii.
- Boundary: Continuous 1px perimeter in `#D7E2EA`.
- Internal sections separated by 1px cool division rules (`#EDF2F7`).
- Hoverable cards exhibit an upward micro-translation (-2px) with enhanced diffuse shadow (`rgba(82, 99, 117, 0.12)`) and edge border lighting to `#38BDF8`.

### Chips & Telemetry Badges
- 24px height, 6px or 12px pill geometry.
- Glacial status variant uses `rgba(2, 132, 199, 0.08)` fill, hairline border in `rgba(2, 132, 199, 0.24)`, and text in `#0284C7` (`label-sm`).
- Muted variant uses `#F4F7FA` surface with `#526375` text and `#D7E2EA` border.

### Checkboxes & Radios
- 18px footprint with a 4px radius for checkboxes, full circle for radios.
- Unchecked: `#FFFFFF` fill with 1.5px `#D7E2EA` border.
- Checked: `#0284C7` solid fill displaying a crisp white micro-glyph (0.5px offset). Focused states duplicate the icy halo focus ring.

### Lists & Tables
- Table headers set in `label-sm` with uppercase slate styling on an `#EDF2F7` frosted canvas.
- Rows separated by 1px hairline `#D7E2EA` borders. 
- Row hover produces an atmospheric surface wash of `#F4F7FA` with transition speed locked to 150ms ease-out.

### Data Monoliths (Specialized Component)
- Distinct display blocks for metrics and instrumentation. Features an opaque `#FFFFFF` substrate, an inner 1px inset highlight (`rgba(255, 255, 255, 0.8)`), a prominent numerical value in `#0C141F`, and a secondary trend delta chip illuminated in Ice Cyan (`#38BDF8`).