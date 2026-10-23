---
name: Academic BL4 Analysis Tool
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#434655'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#006a61'
  on-secondary: '#ffffff'
  secondary-container: '#86f2e4'
  on-secondary-container: '#006f66'
  tertiary: '#6a1edb'
  on-tertiary: '#ffffff'
  tertiary-container: '#8343f4'
  on-tertiary-container: '#f7edff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#89f5e7'
  secondary-fixed-dim: '#6bd8cb'
  on-secondary-fixed: '#00201d'
  on-secondary-fixed-variant: '#005049'
  tertiary-fixed: '#eaddff'
  tertiary-fixed-dim: '#d2bbff'
  on-tertiary-fixed: '#25005a'
  on-tertiary-fixed-variant: '#5a00c6'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  headline-sm:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
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
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  code:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
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

This design system delivers a professional network engineering theme optimized for academic BL4 analysis tools. The visual narrative balances rigorous data-density with approachable legibility, establishing an environment where complex academic network analysis data—spanning Mobile IP, Cellular Networks, and MANET routing protocols—can be inspected without visual fatigue.

- **Target Audience:** Network researchers, academic engineers, and protocol analysts.
- **Emotional Response:** Reliable, precise, highly focused, and intellectually rigorous.
- **Design Style:** Corporate / Modern, prioritizing structured layouts, utilitarian typography, and high-clarity data presentation.

## Colors

The color palette is purposefully engineered to map directly to network topology domains while maintaining strict adherence to accessibility standards on a clean light background (`#F8FAFC`). 

- **Primary (`#2563EB`):** Crisp blue accent dedicated to Mobile IP telemetry and core navigational actions.
- **Secondary (`#0D9488`):** Deep teal accent representing Cellular Networks layers and throughput metrics.
- **Tertiary (`#7C3AED`):** Distinctive purple accent designated for MANET (Mobile Ad-hoc Network) multi-hop links and routing states.
- **Neutral (`#0F172A`):** Deep navy text providing optimal contrast against light surfaces for dense tabular data and code blocks.

## Typography

The typography system utilizes Inter as a reliable, highly legible system font approach that ensures maximum clarity for complex academic network analysis data. Font weights are restricted to regular (400), medium (500), and semi-bold (600) to maintain a utilitarian, corporate tone without extraneous decorative flourishes. Monospace variants leverage system defaults for raw packet inspection and hexadecimal log outputs.

## Layout & Spacing

The layout is built on a responsive 12-column fluid grid system designed to maximize screen real estate for topological graphs, matrix views, and analytical data tables. 

- **Gutters & Margins:** Standardized at 1.5rem gutters and 2rem outer canvas margins on desktop, compressing gracefully to 1rem for mobile viewports.
- **Spacing Rhythm:** Based on a strict 4px/8px scale (`space-xs` through `space-xl`) to maintain vertical rhythm across dense analytical dashboards, sidebars, and property inspectors.

## Elevation & Depth

Visual hierarchy relies on low-contrast outlines and subtle tonal layering rather than heavy drop shadows, ensuring the UI remains crisp and analytical.

- **Surfaces:** Use flat white (`#FFFFFF`) containers resting upon the light grey canvas (`#F8FAFC`).
- **Borders:** Subtle 1px boundaries (`#E2E8F0`) separate data panels, charts, and navigation regions.
- **Focus States:** High-precision rings utilizing the primary blue (`#2563EB` with 40% opacity) denote interactive selection.

## Shapes

In alignment with the selected visual identity, a restrained roundedness level (`1`) is applied across all interactive elements and containers. 

- **Border Radius:** Base components use a subtle 0.25rem radius (`rounded`), scaling to 0.5rem (`rounded-lg`) for major cards and modal dialogs. This prevents an overly playful appearance while softening the rigid geometry of dense network matrices.

## Components

All interface components are built for high-density academic environments, prioritizing predictability, speed, and clear state communication.

- **Buttons:** Primary actions use solid `#2563EB` with white text; secondary actions use bordered outlines against the neutral background. Domain-specific variant classes support Mobile IP (blue), Cellular (teal), and MANET (purple) triggers.
- **Chips & Tags:** Compact badges utilizing domain colors with light tinted backgrounds (`#EFF6FF` for Mobile IP, `#F0FDFA` for Cellular, `#F5F3FF` for MANET) to categorize protocol types instantly.
- **Lists & Tables:** High-density rows with alternating subtle background tints and strict vertical alignment for packet logs, node inventories, and simulation parameters.
- **Checkboxes & Radios:** Crisp square and circular indicators with precise 1px borders, avoiding decorative gradients.
- **Input Fields:** Outlined text fields featuring deep navy text (`#0F172A`), clear placeholder styling, and inline validation messaging.
- **Cards:** Structured container blocks holding telemetry graphs, summary metrics, and topology preview panes, bordered with neutral light gray dividers.
- **Specialized Components:** Includes protocol topology node inspectors, latency sparklines, packet flow control toolbars, and multi-hop route matrix viewers.