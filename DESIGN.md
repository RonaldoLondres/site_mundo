---
name: Nocturne Real Estate
colors:
  surface: '#0d141d'
  surface-dim: '#0d141d'
  surface-bright: '#333a44'
  surface-container-lowest: '#080f18'
  surface-container-low: '#151c26'
  surface-container: '#19202a'
  surface-container-high: '#242a34'
  surface-container-highest: '#2e353f'
  on-surface: '#dce3f0'
  on-surface-variant: '#bacbc0'
  inverse-surface: '#dce3f0'
  inverse-on-surface: '#2a313b'
  outline: '#84958b'
  outline-variant: '#3b4a42'
  surface-tint: '#00e1a4'
  primary: '#77ffc8'
  on-primary: '#003826'
  primary-container: '#00e6a8'
  on-primary-container: '#006245'
  inverse-primary: '#006c4d'
  secondary: '#a0cfce'
  on-secondary: '#003737'
  secondary-container: '#215050'
  on-secondary-container: '#92c1c0'
  tertiary: '#d9e8ff'
  on-tertiary: '#003259'
  tertiary-container: '#a7ceff'
  on-tertiary-container: '#005896'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#42ffbf'
  primary-fixed-dim: '#00e1a4'
  on-primary-fixed: '#002115'
  on-primary-fixed-variant: '#005139'
  secondary-fixed: '#bcebeb'
  secondary-fixed-dim: '#a0cfce'
  on-secondary-fixed: '#002020'
  on-secondary-fixed-variant: '#1f4e4e'
  tertiary-fixed: '#d2e4ff'
  tertiary-fixed-dim: '#9fcaff'
  on-tertiary-fixed: '#001d36'
  on-tertiary-fixed-variant: '#00497e'
  background: '#0d141d'
  on-background: '#dce3f0'
  surface-variant: '#2e353f'
typography:
  display-lg:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.03em
  display-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Outfit
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Outfit
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Outfit
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-md:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 10px
    fontWeight: '700'
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
  gutter: 1rem
  gutter-sm: 0.75rem
  margin: 1.25rem
  margin-sm: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system targets discerning, tech-forward real estate buyers, renters, and agents operating in fast-paced metropolitan markets. The experience combines the technical precision of an institutional financial terminal with the immersive luxury of a high-end architectural portfolio. It delivers immediate clarity, spatial depth, and high-energy focal points across complex real estate transactions.

The visual aesthetic synthesizes **Cyber-Modernism** and **Tactile Glassmorphism**:
- Ultra-deep, cold-cast dark canvases eliminate visual clutter and reduce eye strain in low-light environments.
- Vivid electric teal and hyper-saturated emerald accents direct user flow through listing cards, interactive map points, and multi-step listing questionnaires.
- Glowing architectural details, fine luminescent boundary lines, and high-contrast typography evoke a sense of premium precision and institutional confidence.

## Colors

The palette leverages a deep void architecture energized by precise, high-visibility neon accents.

### Palette Architecture
- **Canvas / Root Background (`#050b14`)**: An obsidian base tone with a subtle navy cast. Provides maximum contrast for high-saturation signals.
- **Surface Elevation Cards (`#0b1522`)**: The foundational container tone for listings, sheets, and stepped forms.
- **Elevated Interactive Surface (`#122033`)**: Used for hover states, selected chip segments, and modal sheets.
- **Primary Accent (`#00e6a8`)**: Electric mint/cyan. Reserved strictly for primary calls-to-action, key price markers, active progress bars, and critical indicators.
- **Secondary Edge Tone (`#053b3b`)**: Deep teal substrate used for resting structural boundaries, inactive outlines, and subtle glow backplates.
- **Tertiary Accent (`#0099ff`)**: Laser azure for secondary analytics, map transit layers, verified badges, and informational states.
- **Neutral Foreground Tiers**:
  - Primary Content: `#f0f6fc` (95% contrast for property titles, metrics, and price headers).
  - Secondary Content: `#8b9cb0` (Subheaders, amenities, and unselected wizard labels).
  - Muted / Disabled: `#38495c` (Inactive icons, placeholder text, and structural dividers).
- **Functional Semantics**:
  - Critical/Error: `#ff3b5c`
  - Warning: `#ffaa00`
  - Success: `#00e6a8`

## Typography

The type system blends the structural, technical geometry of **Space Grotesk** with the fluid, highly legible clarity of **Outfit**.

- **Display & Headlines (`Space Grotesk`)**: Provides numeric presence for valuations, square footage, capitalization rates, and listing titles. Negative tracking ensures numerical density across mobile viewports.
- **Body & Longform Descriptions (`Outfit`)**: Clean, low-distortion humanist geometry ensures effortless readability across property descriptions, legal clauses, and agent communication channels.
- **Labels & Badges (`Space Grotesk`)**: Slight positive tracking paired with medium-to-bold weights ensures tags like `"NEW ON MARKET"`, `"PENDING"`, and `"VIRTUAL TOUR"` remain legible even at miniature scales.

## Layout & Spacing

A disciplined 4-column layout anchors the primary mobile experience, expanding dynamically to 8 columns on tablets and 12 columns on desktop viewports.

### Grid & Canvas Specifications
- **Mobile Handset (< 640px)**: 4 columns, `margin-sm: 1rem`, `gutter-sm: 0.75rem`. Content stacks vertically, with listing media employing edge-to-edge bleed or inset card bounds.
- **Tablet (640px – 1024px)**: 8 columns, `margin: 1.25rem`, `gutter: 1rem`. Master-detail split allows simultaneous map exploration and listing evaluation.
- **Desktop (1024px+)**: 12 columns, max-width container locked to `1280px` centered, `gutter: 1.5rem`.

### Spatial Rhythm
- Interior component padding uses fixed tokens (`space-sm` for chips, `space-md` for inputs, `space-lg` for card bodies).
- Wizard step transitions preserve persistent top/bottom safe-area anchors to guard bottom touch bars and step progress headers.

## Elevation & Depth

Visual hierarchy does not rely on conventional fuzzy drop shadows, which muddy dark canvas designs. Instead, depth is achieved through **luminescent boundary tiers, surface luminosity, and subtle ambient glows**.

### Depth Layers
1. **Base Surface (Level 0 - `#050b14`)**: Root canvas view.
2. **Structural Layer (Level 1 - `#0b1522`)**: Listing cards, filter drawers, questionnaire question blocks. Framed with a 1px border colored `#053b3b`.
3. **Elevated Dynamic Layer (Level 2 - `#122033`)**: Active input fields, hovered cards, and floating action buttons. Uses a 1px border of `#00e6a8` at 60% alpha combined with an outer ambient halo: `box-shadow: 0 0 16px -4px rgba(0, 230, 168, 0.25)`.
4. **Overlay Sheets & Modals (Level 3 - `#0b1522` at 90% opacity with `backdrop-filter: blur(16px)`)**: Floats above all interactive viewports with a 1px continuous hairline highlight (`rgba(0, 230, 168, 0.3)`).

### Neon Glow Signatures
- **Active Icons**: Receive a soft directional bloom (`filter: drop-shadow(0 0 8px rgba(0, 230, 168, 0.6))`).
- **Inactive Icons**: Clean `#8b9cb0` fill with zero optical glow.

## Shapes

The interface balances sharp technical precision with ergonomic touch responsiveness.

- **Base Radius (`0.5rem / 8px`)**: Applied to standard form inputs, segmented controls, small thumbnails, and sub-cards.
- **Large Radius (`1rem / 16px`)**: Applied to master real estate listing cards, bottom sheets, filter cards, and image carousels.
- **Maximum Pill Radius (`9999px`)**: Exclusively reserved for status badges, property filter chips, floating action indicators, and primary call-to-action buttons.

## Components

### Buttons
- **Primary CTA**: Background `#00e6a8`, label `#050b14` (`Space Grotesk`, `label-lg`, weight 700). Pill radius (`9999px`). Glowing hover/active aura: `box-shadow: 0 0 20px rgba(0, 230, 168, 0.4)`.
- **Secondary Ghost**: Background transparent, 1px border `#00e6a8`, text `#00e6a8`.
- **Tertiary Utility**: Surface `#122033`, border 1px solid `#053b3b`, text `#f0f6fc`.

### Form Inputs & Selectors
- **Dark Mobile Field**: Surface `#0b1522`, 1px resting border `#053b3b`, placeholder `#38495c`, active value `#f0f6fc`.
- **Active/Focus State**: Border transitions to `#00e6a8` with a 2px inner-glow spread `rgba(0, 230, 168, 0.15)`. Floating labels render in `Space Grotesk` uppercase (`label-sm`) colored `#00e6a8`.

### Stepped Questionnaire & Listing Wizard
- **Progress Track**: 2px background line `#053b3b`; filled segment `#00e6a8` with leading beacon head emitting a 6px neon blur.
- **Step Cards**: Modular selection cards for property type (e.g., Condo, Penthouse, Townhome) featuring a glowing teal outline and checkmark when selected.

### Badges & Filter Chips
- **Status Pills**: Pill-shaped containers (`roundedness: 3`) with semi-transparent surfaces (`rgba(5, 59, 59, 0.6)`), 1px solid borders (`#00e6a8`), and uppercase labels (`label-sm`).
- **Price Metric Tag**: Solid `#00e6a8` pill with black bold text affixed over listing imagery.

### Real Estate Listing Cards
- **Structure**: Surface `#0b1522`, 1px border `#053b3b`, `rounded-lg` (16px).
- **Image Header**: 16:9 aspect ratio media module with continuous dark vignette at base; contains floating status chips at top-left and heart/save button with neon cyan toggle at top-right.
- **Data Cluster**: Key specs (Bed, Bath, Sq Ft) separated by subtle vertical dividers (`#053b3b`), rendered in `Space Grotesk` bold metrics alongside muted `Outfit` descriptor tags.