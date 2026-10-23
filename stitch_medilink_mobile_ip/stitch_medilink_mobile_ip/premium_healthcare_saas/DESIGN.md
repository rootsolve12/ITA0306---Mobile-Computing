---
name: Premium Healthcare SaaS
colors:
  surface: '#f7fafe'
  surface-dim: '#d7dade'
  surface-bright: '#f7fafe'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f4f8'
  surface-container: '#ebeef2'
  surface-container-high: '#e5e8ec'
  surface-container-highest: '#e0e3e7'
  on-surface: '#181c1f'
  on-surface-variant: '#44474e'
  inverse-surface: '#2d3134'
  inverse-on-surface: '#eef1f5'
  outline: '#74777e'
  outline-variant: '#c4c6ce'
  surface-tint: '#4a5f81'
  primary: '#001632'
  on-primary: '#ffffff'
  primary-container: '#142b4a'
  on-primary-container: '#7d93b7'
  inverse-primary: '#b2c7ee'
  secondary: '#006b5f'
  on-secondary: '#ffffff'
  secondary-container: '#71f8e4'
  on-secondary-container: '#007165'
  tertiary: '#001537'
  on-tertiary: '#ffffff'
  tertiary-container: '#00285e'
  on-tertiary-container: '#508fff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d5e3ff'
  primary-fixed-dim: '#b2c7ee'
  on-primary-fixed: '#021c3a'
  on-primary-fixed-variant: '#324768'
  secondary-fixed: '#71f8e4'
  secondary-fixed-dim: '#50dbc8'
  on-secondary-fixed: '#00201c'
  on-secondary-fixed-variant: '#005048'
  tertiary-fixed: '#d8e2ff'
  tertiary-fixed-dim: '#aec6ff'
  on-tertiary-fixed: '#001a42'
  on-tertiary-fixed-variant: '#004395'
  background: '#f7fafe'
  on-background: '#181c1f'
  surface-variant: '#e0e3e7'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
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

This design system blends high-authority medical reliability with approachable, consumer-grade SaaS polish. The design style relies on elevated soft-geometry, featuring generous whitespace, soft ambient lighting, and high clarity to inspire absolute trust in clinical and administrative workflows.

## Colors

The color palette anchors the user experience with a commanding deep navy primary, balanced by a clean cool grey canvas. Medical teal and sky blue serve as functional, energetic accents to highlight key clinical actions, status indicators, and interactive states without overwhelming the interface.

## Typography

Typography utilizes Plus Jakarta Sans exclusively, optimizing for clean geometric legibility across dense medical records and expansive dashboard views. Hierarchy is established through precise variations in weight and strict proportional scaling, ensuring comfortable reading cadences on both desktop monitors and mobile clinical tablets.

## Layout & Spacing

A 12-column fluid grid system governs the layout, structured with 24px gutters and responsive outer margins that expand gracefully on wider displays. Spacing follows an 8px base rhythm to maintain vertical alignment and generous whitespace, reducing cognitive fatigue in high-stakes environments.

## Elevation & Depth

Visual hierarchy is achieved through ambient, low-opacity shadows tinted with the primary navy hue, paired with clean tonal layering against the cool grey background. Elements feel grounded yet touchable, utilizing multi-layered diffuse drop shadows rather than harsh borders to differentiate interactive surfaces from the canvas.

## Shapes

The shape language uses pill-shaped and highly rounded geometries to project an approachable, human-centric tone. Containers feature generous corner radii (`rounded-lg` and `rounded-xl`), softening the clinical precision of the UI and creating an inviting, low-stress user experience.

## Components

- **Buttons:** Fully rounded (pill) geometry with high-contrast primary fills or soft accent backgrounds. States must feature smooth opacity transitions and subtle scale feedback on press.
- **Chips & Badges:** Compact, pill-shaped elements used for patient status, tags, and filters. Pair muted backgrounds with crisp, solid-weight labels.
- **Input Fields:** Generous touch targets with light cool-grey fills, soft borders, and floating or clear top-aligned labels in Plus Jakarta Sans. Focus states utilize the medical teal or sky blue accent with a soft glow ring.
- **Cards:** Surface containers rendered in clean white against the cool grey background, featuring rounded corners and ambient shadow depth to group complex patient metrics or networking telemetry.
- **Checkboxes & Radios:** Soft-geometry selection controls with crisp inner indicators and smooth transition animations.
- **Lists:** Clean data rows separated by subtle dividers or soft tonal shifts on hover, optimized for rapid scanning of clinical histories or network nodes.