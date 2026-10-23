---
name: Academic Institutional
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#444651'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#757682'
  outline-variant: '#c5c5d3'
  surface-tint: '#4059aa'
  primary: '#00236f'
  on-primary: '#ffffff'
  primary-container: '#1e3a8a'
  on-primary-container: '#90a8ff'
  inverse-primary: '#b6c4ff'
  secondary: '#4e45d5'
  on-secondary: '#ffffff'
  secondary-container: '#6860ef'
  on-secondary-container: '#fffbff'
  tertiary: '#002e44'
  on-tertiary: '#ffffff'
  tertiary-container: '#004565'
  on-tertiary-container: '#36b6fb'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b6c4ff'
  on-primary-fixed: '#00164e'
  on-primary-fixed-variant: '#264191'
  secondary-fixed: '#e3dfff'
  secondary-fixed-dim: '#c3c0ff'
  on-secondary-fixed: '#100069'
  on-secondary-fixed-variant: '#372abf'
  tertiary-fixed: '#c9e6ff'
  tertiary-fixed-dim: '#89ceff'
  on-tertiary-fixed: '#001e2f'
  on-tertiary-fixed-variant: '#004c6e'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Inter
    fontSize: 18px
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
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
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

This design system establishes a conventional, highly readable academic layout tailored for computer networking presentations and scholarly documentation. The design narrative prioritizes absolute clarity, cognitive ease, and professional trust, utilizing clean sans-serif typography and reliable institutional blue tones. The interface evokes a sense of authority, precision, and academic rigor, ensuring complex networking concepts are communicated without visual distraction.

## Colors

The color palette centers around a deep institutional blue (`#1E3A8A`) as the primary anchor, paired with a sophisticated purple accent (`#4338CA`) for secondary actions and highlights. A clear sky blue (`#0EA5E9`) serves as a tertiary tone for data visualization and network topology indicators. Neutrals are calibrated for high-contrast readability against crisp white and light gray backgrounds, ensuring optimal legibility during prolonged study or presentations.

## Typography

The typography system relies exclusively on Inter, providing a neutral, systematic, and highly utilitarian visual structure. Letterforms are optimized for exceptional legibility across dense technical documentation, code snippets, and diagrammatic labels. Hierarchy is achieved strictly through shifts in weight and proportional scale rather than decorative type variation.

## Layout & Spacing

A reliable 12-column fluid grid forms the structural foundation, accommodating complex data tables, network architecture diagrams, and academic text blocks with consistent rhythm. Generous outer margins and structured gutters prevent visual crowding, while modular spacing tokens enforce predictable vertical and horizontal relationships across all viewports.

## Elevation & Depth

Elevation is handled through subtle tonal layering and low-contrast outlines rather than heavy drop shadows. Surfaces utilize crisp, clean borders with minimal tonal shifts to indicate interactive states or card containers, maintaining the flat, authoritative aesthetic expected of formal academic publications.

## Shapes

The shape language employs a conservative, soft-rounded approach with a base roundedness of 0.25rem. This subtle softening removes harsh 90-degree industrial edges while preserving the formal, structured character required for scholarly presentations and technical interfaces.

## Components

### Buttons
Primary buttons utilize the institutional blue fill with white text, featuring a subtle 0.25rem corner radius for approachable clarity. Secondary and outline variants rely on clean borders and text colors to maintain secondary hierarchy without visual clutter.

### Chips & Tags
Compact metadata indicators used for protocol types, status flags, or category labels. Styled with muted background tints and solid text matching the accent colors.

### Input Fields
Form inputs feature high-contrast borders, clear label placement above the input area, and distinct focus states highlighted by the primary blue ring to ensure accessibility during rapid data entry.

### Cards
Structured containers with light background fills, thin neutral borders, and generous internal padding. Ideal for grouping technical notes, protocol definitions, or diagram modules.

### Lists & Tables
Data-dense layouts optimized for networking metrics, IP routing tables, and bibliographic references, utilizing alternating row tints and crisp grid lines for scannability.