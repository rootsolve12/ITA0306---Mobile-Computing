---
name: Protocol Analysis Platform
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
  on-surface-variant: '#424754'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#727785'
  outline-variant: '#c2c6d6'
  surface-tint: '#005ac2'
  primary: '#0058be'
  on-primary: '#ffffff'
  primary-container: '#2170e4'
  on-primary-container: '#fefcff'
  inverse-primary: '#adc6ff'
  secondary: '#6b38d4'
  on-secondary: '#ffffff'
  secondary-container: '#8455ef'
  on-secondary-container: '#fffbff'
  tertiary: '#00685f'
  on-tertiary: '#ffffff'
  tertiary-container: '#008378'
  on-tertiary-container: '#f4fffc'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a42'
  on-primary-fixed-variant: '#004395'
  secondary-fixed: '#e9ddff'
  secondary-fixed-dim: '#d0bcff'
  on-secondary-fixed: '#23005c'
  on-secondary-fixed-variant: '#5516be'
  tertiary-fixed: '#89f5e7'
  tertiary-fixed-dim: '#6bd8cb'
  on-tertiary-fixed: '#00201d'
  on-tertiary-fixed-variant: '#005049'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  headline-xl:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Space Grotesk
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
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
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

This design system establishes a high-performance, rigorous visual identity tailored for advanced networking telemetry and protocol research. The aesthetic bridges academic precision with cutting-edge technical visualization, leveraging experimental futuristic typography to evoke advanced wireless routing concepts and decentralized network topologies.

- **Brand Personality:** Analytical, cutting-edge, rigorous, authoritative.
- **Target Audience:** Networking engineers, computer science researchers, and university students analyzing routing mechanics.
- **Emotional Response:** Clarity, mathematical certainty, technological immersion, and structural confidence.
- **Design Style:** High-Contrast / Bold meets Technical Minimalism, featuring razor-sharp geometries, stark layout demarcations, and vibrant, protocol-specific color routing.

## Colors

The color palette is engineered for high data density and distinct protocol differentiation. 

- **Primary (`#3B82F6`):** Vibrant electric blue representing deterministic, table-driven DSDV routing mechanics.
- **Secondary (`#8B5CF6`):** Deep ultraviolet accent dedicated to on-demand AODV discovery phases and route request telemetry.
- **Tertiary (`#0D9488`):** Precision teal utilized for validation metrics, successful packet delivery ratios, and comparative analytical overlays.
- **Neutral (`#0F172A`):** Deep slate-black canvas text and primary structural lines, offering stark contrast against pristine light structural backgrounds (`#F8FAFC`).

## Typography

Typography enforces a strict hierarchy between technical metrics and qualitative commentary. `Space Grotesk` provides a technical, futuristic geometry for all headlines, mirroring terminal output and data-sheet aesthetics. `Inter` ensures maximum legibility for dense comparative data tables, metric readouts, and telemetry logs. All metadata labels are rendered in uppercase `label-sm` with slight tracking to simulate hardware interface labeling.

## Layout & Spacing

The layout relies on a rigid 12-column structural grid optimized for side-by-side protocol benchmarking (DSDV vs. AODV). 

- **Grid System:** Fixed-fluid hybrid grid with 24px structural gutters and 32px outer canvas margins.
- **Responsive Behavior:** 
  - **Desktop (1024px+):** Dual-pane comparative view mapping table updates against on-demand discovery streams.
  - **Tablet (768px - 1023px):** Stacked metric blocks with collapsible protocol drawers.
  - **Mobile (<768px):** Single-column linear flow prioritizing active simulation states and core packet loss graphs.

## Elevation & Depth

Depth is conveyed strictly through low-contrast outlines and razor-sharp structural borders rather than soft, atmospheric shadows. This aligns with the experimental technical identity, avoiding skeuomorphic blur in favor of precise, instrument-like paneling.

- **Surfaces:** Flat, opaque containers bounded by 1px solid neutral borders (`#E2E8F0`).
- **Active States:** Elevated parameters utilize crisp 2px primary or secondary border highlights to denote focus, completely discarding drop-shadow elevation.

## Shapes

All UI elements adhere to a strict zero-radius (`0px`) sharp-cornered geometry. This uncompromising rectangular form factor evokes technical schematics, oscilloscope readouts, and terminal windows, reinforcing the advanced engineering context of the routing protocol analysis.

## Components

Components are engineered for high-density information display and rapid analytical interaction.

- **Buttons:** Sharp 0px rectangles featuring high-contrast solid fills for primary actions (Run Simulation, Export Telemetry) and crisp 1px bordered outlines for secondary actions. Hover states invert the border and background colors instantaneously.
- **Chips & Tags:** Protocol indicators use stark rectangular badges with uppercase labels (`DSDV` in primary blue, `AODV` in secondary purple) and zero border-radius.
- **Lists & Tables:** Dense data tables featuring alternating row tints, pinned header rows, and monospaced numeric columns for metric comparisons (hop count, routing overhead, convergence time).
- **Checkboxes & Radio Buttons:** Perfect square and diamond selections replacing traditional rounded inputs, reflecting terminal toggle states.
- **Input Fields:** Uncompromising rectangular containers with 1px solid borders, featuring embedded monospaced units for parameter entry (e.g., node velocity, transmission range).
- **Cards:** Structural telemetry containers outlining live network graphs, node topology maps, and comparative latency metrics with top-aligned protocol status indicators.
- **Protocol Visualizers:** Custom canvas blocks designed for rendering real-time packet broadcasts, route request (RREQ) floods, and table update intervals.