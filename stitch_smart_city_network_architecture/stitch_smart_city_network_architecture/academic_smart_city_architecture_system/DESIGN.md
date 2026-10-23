---
name: Academic Smart City Architecture System
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#45464d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#0051d5'
  on-secondary: '#ffffff'
  secondary-container: '#316bf3'
  on-secondary-container: '#fefcff'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#00201d'
  on-tertiary-container: '#0c9488'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#dbe1ff'
  secondary-fixed-dim: '#b4c5ff'
  on-secondary-fixed: '#00174b'
  on-secondary-fixed-variant: '#003ea8'
  tertiary-fixed: '#89f5e7'
  tertiary-fixed-dim: '#6bd8cb'
  on-tertiary-fixed: '#00201d'
  on-tertiary-fixed-variant: '#005049'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 24px
  body-lg:
    fontFamily: Source Sans 3
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Source Sans 3
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Source Sans 3
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  margin: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes an institutional, authoritative, and deeply systematic visual identity tailored for complex smart city network architecture. The core personality is academic, highly structured, and precise, engineered to communicate rigorous technical data, MANET topographies, and cellular integration pathways without visual noise.

The visual style bridges the gap between classic academic publishing and modern technical documentation. It utilizes a clean light background, stark neutral grotesks, and functional color coding to distinguish complex network layers. The emotional response is one of absolute clarity, trust, and academic rigor, ensuring that dense architectural schemas remain legible and intellectually accessible.

## Colors

The palette is anchored by a deep academic navy (`#0f172a`) for structural elements and primary typography. Cellular network infrastructures are mapped using a clear, authoritative royal blue (`#2563eb`), while MANET (Mobile Ad-hoc Network) layers utilize a deliberate dual-tone approach combining teal (`#0d9488`) and structured purple (`#7c3aed`) to indicate dynamic node relationships. Background surfaces remain pristine and neutral (`#f8fafc`), supported by subtle gray borders for precise containment.

## Typography

Typography functions as the primary vehicle for information hierarchy in this institutional framework. Inter is utilized for all structural headers, providing clean geometric forms and immediate legibility at scale. Source Sans 3 serves as the body text font, optimized for extended reading sessions across technical whitepapers, architectural specifications, and network logs. Letter spacing is restrained, maintaining a formal academic cadence.

## Layout & Spacing

The layout model relies on a strict 12-column fluid grid system paired with fixed maximum widths for optimal readability on high-resolution scholarly displays. Spacing is governed by a consistent rhythm based on 4px and 8px increments, ensuring that complex diagrams, node lists, and architectural schematics maintain precise alignment. Margins scale down gracefully on mobile viewports while preserving minimum safe areas for touch and visual framing.

## Elevation & Depth

Elevation is expressed through low-contrast outlines and razor-thin neutral borders rather than heavy drop shadows. This flat, architectural approach reinforces the academic context, preventing visual clutter while cleanly separating modular UI panels, network topology graphs, and parameter control cards. Subtle tonal surface shifts are employed exclusively to denote interactive states or active node selections.

## Shapes

The design system implements a strict, restrained roundedness level of `1` (Soft), yielding a base corner radius of 0.25rem, with larger containers scaling up to 0.5rem (`rounded-lg`) and 0.75rem (`rounded-xl`). This minimizes excessive ornamentation, favoring crisp, professional rectangular containers that align naturally with technical diagrams, data tables, and structural code blocks.

## Components

### Buttons
Buttons feature crisp borders, flat primary fills in deep navy (`#0f172a`), and secondary variants utilizing cellular blue (`#2563eb`). Padding is compact and systematic to support dense dashboard layouts.

### Chips & Badges
Used extensively for network protocol identification (e.g., MANET, 5G, LoRaWAN). They combine low-opacity semantic backgrounds with high-contrast text to ensure categorical clarity at a glance.

### Input Fields & Controls
Form controls utilize clean 1px borders, subtle focus rings in primary blue, and clear, persistent label placement above inputs to maintain strict accessibility standards.

### Cards
Cards act as container modules for architectural blueprints and telemetry feeds. They feature neutral white backgrounds (`#ffffff`), 1px subtle borders (`#e2e8f0`), and internal padding scaled to `space-lg`.

### Lists & Tables
Optimized for dense data presentation with alternating row tints, clear column headers, and explicit grid alignments suitable for academic network logs and topology matrices.