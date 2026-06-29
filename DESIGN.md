---
name: Executive Logistics System
colors:
  surface: '#f9f9ff'
  surface-dim: '#d3daef'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f3ff'
  surface-container: '#e9edff'
  surface-container-high: '#e1e8fd'
  surface-container-highest: '#dce2f7'
  on-surface: '#141b2b'
  on-surface-variant: '#4d4632'
  inverse-surface: '#293040'
  inverse-on-surface: '#edf0ff'
  outline: '#7f7660'
  outline-variant: '#d1c6ab'
  surface-tint: '#735c00'
  primary: '#735c00'
  on-primary: '#ffffff'
  primary-container: '#facc15'
  on-primary-container: '#6c5700'
  inverse-primary: '#eec200'
  secondary: '#446900'
  on-secondary: '#ffffff'
  secondary-container: '#b2f746'
  on-secondary-container: '#496f00'
  tertiary: '#0053db'
  on-tertiary: '#ffffff'
  tertiary-container: '#c2cfff'
  on-tertiary-container: '#004ecf'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffe083'
  primary-fixed-dim: '#eec200'
  on-primary-fixed: '#231b00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#b2f746'
  secondary-fixed-dim: '#98da27'
  on-secondary-fixed: '#121f00'
  on-secondary-fixed-variant: '#334f00'
  tertiary-fixed: '#dbe1ff'
  tertiary-fixed-dim: '#b4c5ff'
  on-tertiary-fixed: '#00174b'
  on-tertiary-fixed-variant: '#003ea8'
  background: '#f9f9ff'
  on-background: '#141b2b'
  surface-variant: '#dce2f7'
typography:
  display-lg:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Manrope
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
  headline-md:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  code-sm:
    fontFamily: Manrope
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
  max-width: 1440px
---

## Brand & Style

The design system is engineered for high-stakes operational environments where clarity, speed, and precision are paramount. The brand personality is **Intelligent** and **Strategic**, moving away from traditional industrial aesthetics toward a refined, **Modern Enterprise** feel.

The visual style blends **Minimalism** with **Glassmorphism**. It utilizes expansive white space to reduce cognitive load during complex logistics tasks, punctuated by premium frosted surfaces that indicate active or high-priority layers. The interface communicates **Trust** through balanced proportions and **Operational Efficiency** through a rigorous, systematic application of color and depth.

- **Strategic Focus:** High-visibility data points and real-time status updates.
- **Atmosphere:** Clean, professional, and calm, even under high-load scenarios.
- **Visual Motif:** "The Intelligent Route"—represented by elegant borders and subtle, flowing gradients that guide the eye toward actionable insights.

## Colors

The palette is optimized for both brand recognition and functional utility. 

- **Primary (Logistic Yellow):** Used sparingly for primary actions, critical alerts, and brand identity elements. It ensures high visibility against the neutral backdrop.
- **Secondary (Electric Lime):** Symbolizes movement and "Go" states. Used for successful status updates, active routes, and positive progression.
- **Background (Logistics White):** A warm, off-white base that reduces eye strain compared to pure white, providing a premium "paper-like" quality.
- **Text (Dispatch Charcoal):** Provides maximum contrast for legibility in data-heavy tables and dashboards.
- **Accents:** 
    - **Route Lime Glow:** Used for soft background fills and subtle highlights on secondary surfaces.
    - **Tracking Blue:** Dedicated to information-heavy components, links, and system-level notifications to differentiate from operational status colors.

## Typography

The typography system relies exclusively on **Manrope** for its executive and technical character. It offers the geometric cleanliness required for a modern brand while maintaining the high legibility needed for long-form logistics data.

- **Hierarchy:** Strong weight contrasts (800 for Display, 400 for Body) are used to create a clear scan path.
- **Labels:** Semi-bold labels with slight letter spacing are utilized for technical metadata and table headers.
- **Numerical Data:** For tracking numbers and timestamps, use `code-sm` or `label-md` to ensure character distinction.

## Layout & Spacing

This design system employs a **Fluid Grid** model with strict vertical rhythm based on a 4px baseline.

- **Desktop:** 12-column grid with a 24px gutter. Content is housed in "Stage" containers that can expand to 1440px. 
- **Tablet:** 8-column grid with 20px gutters. Sidebars collapse into icons or drawers to prioritize map and table views.
- **Mobile:** 4-column grid with 16px margins.
- **Spacing Logic:** Padding and margins should always be multiples of 8px for primary layout blocks, while 4px increments are reserved for internal component details (e.g., icon-to-text spacing).

## Elevation & Depth

Visual hierarchy is managed through **Tonal Layers** and **Glassmorphism**. The background (`#FAFAF5`) serves as Level 0.

- **Level 1 (Default Cards):** White background with a 1px solid border (`#E5E7EB`) and a very soft, diffused shadow (0px 4px 20px rgba(0,0,0,0.03)).
- **Level 2 (Active/Hover):** Enhanced shadow (0px 10px 30px rgba(0,0,0,0.06)) and a 1px primary-colored border.
- **Level 3 (Overlays/Modals):** Glassmorphic surfaces with a 20px backdrop blur and 80% opacity white fill.
- **Depth Cues:** Soft, layered gradients (from `#FACC15` to `#A3E635` at 5% opacity) are used to indicate "Areas of Interest" on maps or dashboard widgets.

## Shapes

The design system uses a **Rounded** geometry to soften the industrial nature of logistics.

- **Base Radius (0.5rem):** Standard for buttons, input fields, and small UI widgets.
- **Large Radius (1rem):** Used for cards, dashboard containers, and main content areas.
- **Extra Large (1.5rem):** Reserved for modal containers and large promotional or high-level overview sections.
- **Consistent Enclosure:** Inner elements should have a radius 4px smaller than their parent container to maintain visual harmony.

## Components

### Buttons
- **Primary:** Logistic Yellow (`#FACC15`) fill with Dispatch Charcoal text. Heavy weight, 0.5rem radius.
- **Secondary:** Transparent with a 1px Dispatch Charcoal border.
- **Ghost:** No background, Tracking Blue text for utility actions.

### Cards & Containers
- Cards use the Level 1 elevation. 
- For "Live Tracking," cards use a glassmorphic header to indicate real-time data streaming.

### Input Fields
- High-contrast outlines (`#D1D5DB`) that transition to Logistic Yellow on focus. 
- Included "Micro-copy" labels using `label-sm` for technical constraints (e.g., "Enter 12-digit SKU").

### Chips & Status Badges
- **In-Transit:** Route Lime Glow background with Electric Lime text.
- **Delayed:** Soft Red background with Dark Red text.
- **Delivered:** Electric Lime fill with White text.

### Data Tables
- Header row uses a subtle Logistics White to Grey-100 gradient.
- Row hover states utilize the Route Lime Glow (`#D9F99D`) at 30% opacity to highlight current focus without obscuring data.

### Special Logistics Components
- **The Route Timeline:** A vertical stepper using Electric Lime for completed legs and Tracking Blue for the current position.
- **Telemetry Dashboard:** Small, high-density sparklines using Tracking Blue to show vehicle or warehouse performance over 24h.