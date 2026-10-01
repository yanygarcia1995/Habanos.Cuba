---
name: Tabac & Cava Inventory
colors:
  surface: '#fbf9f5'
  surface-dim: '#dbdad6'
  surface-bright: '#fbf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ef'
  surface-container: '#efeeea'
  surface-container-high: '#eae8e4'
  surface-container-highest: '#e4e2de'
  on-surface: '#1b1c1a'
  on-surface-variant: '#4e4540'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f0ed'
  outline: '#80756f'
  outline-variant: '#d2c4bd'
  surface-tint: '#6c5b51'
  primary: '#110703'
  on-primary: '#ffffff'
  primary-container: '#2b1e16'
  on-primary-container: '#988479'
  inverse-primary: '#d9c2b5'
  secondary: '#775a19'
  on-secondary: '#ffffff'
  secondary-container: '#fed488'
  on-secondary-container: '#785a1a'
  tertiary: '#160504'
  on-tertiary: '#ffffff'
  tertiary-container: '#311b18'
  on-tertiary-container: '#a1817b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#f6ded1'
  primary-fixed-dim: '#d9c2b5'
  on-primary-fixed: '#251911'
  on-primary-fixed-variant: '#54433a'
  secondary-fixed: '#ffdea5'
  secondary-fixed-dim: '#e9c176'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5d4201'
  tertiary-fixed: '#ffdad4'
  tertiary-fixed-dim: '#e3beb8'
  on-tertiary-fixed: '#2b1613'
  on-tertiary-fixed-variant: '#5b403c'
  background: '#fbf9f5'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2de'
typography:
  display:
    fontFamily: Newsreader
    fontSize: 40px
    fontWeight: '500'
    lineHeight: 48px
    letterSpacing: -0.02em
  display-mobile:
    fontFamily: Newsreader
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Newsreader
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Newsreader
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: 0em
  headline-sm:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: 0em
  body-lg:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-md:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Manrope
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.08em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  margin: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

The design system embodies the quiet luxury and disciplined utility of high-end humidor curation and boutique tobacco commerce. Built for mobile-first environments—such as dimly lit cigar lounges, warehouse humidors, and active retail counters—it balances artisanal sophistication with fast, error-free operational ergonomics. 

The aesthetic is grounded in a refined, warm minimalism: clean surfaces, restrained tactile accents, precise geometric structuring, and decisive color-coded states. Extraneous decoration is stripped away in favor of high-contrast readability, generous touch targets tailored for single-handed thumb operation, and an atmosphere evocative of cedar wood, aged wrapper leaves, and brass inventory tallies.

## Colors

The palette establishes an immediate connection to the craft of fine tobacco, contrasting deep maduro and cedar undertones with warm metallic highlights and pure functional feedback.

- **Primary (`#2B1E16`)**: Deep tobacco maduro. Serves as the primary structural color for headers, dominant call-to-actions, and high-emphasis typographic elements.
- **Secondary (`#C5A059`)**: Muted amber bronze. Applied deliberately to active states, rating badges, selection rings, vitola insignias, and premium status highlights.
- **Tertiary (`#3E2723`)**: Dark aged cedar. Provides mid-tone depth for sub-navigation, card contours, and secondary informational text.
- **Neutral Surface (`#FDFBF7`)**: Warm ivory foundation. Delivers a soft, low-glare canvas that reduces eye strain in indoor cellars while maintaining crisp legibility.
- **Surface Pure (`#FFFFFF`)**: Pure white reserved for elevated cards, transactional sheets, and modal containers to distinguish touchable surfaces.

### Semantic Status Indicators
- **Optimal Stock (`#4A6B48`)**: Olive leaf green. Signifies balanced humidor counts without high saturation.
- **Moderate / Low Stock (`#D49B37`)**: Warm aged amber. Indicates replenishment thresholds.
- **Critical / Exhausted Stock (`#A3382A`)**: Terracotta maduro. High-urgency alert for depleted stock or humidity drift.

## Typography

The typographic pairing reconciles the artisanal heritage of master cigar makers with the instant computational legibility required for high-velocity inventory management.

- **Newsreader** handles editorial and structural headers (`display`, `headline-lg`, `headline-md`). Its classic transitional serif geometry evokes heritage cigar rings, tobacco auctions, and high-end viticulture logs without sacrificing modern screen sharpness.
- **Manrope** serves as the utilitarian core (`headline-sm`, `body-*`, `label-*`). Its geometric construction, open counters, and high x-height guarantee immediate character differentiation when scanning barcodes, verifying factory vitola names, tracking box counts, and auditing wholesale margins.
- **Tabular Figures**: Numeric stock levels, prices, and hygrometer metrics must always render with tabular numbers (`font-variant-numeric: tabular-nums`) to prevent horizontal jitter during rapid stock adjustments.

## Layout & Spacing

The layout is built upon an ergonomic mobile grid system optimized for thumb-reach access. 

- **Grid Architecture**: Mobile devices utilize a 4-column fluid layout with a base margin of `1rem` (16px) and gutters of `1rem` (16px). For tablet and desktop master dashboards, the system expands to an 8-column and 12-column layout with `1.5rem` gutters and a maximum content constrain of 1280px.
- **The Thumb Zone**: Critical operational triggers—such as quick-scan barcode inputs, stock +/- steppers, and cart completion buttons—are strictly anchored to the lower 35% of the mobile viewport. Secondary meta-data and deep filtering reside in the neutral upper canvas.
- **Rhythm**: All structural gaps, paddings, and module offsets adhere to a strict 4px/8px base rhythm. Cards use internal paddings of `space-md` (16px) to maximize screen real estate while preventing accidental tap collision in warehouse settings.

## Elevation & Depth

Visual hierarchy is maintained through a combination of crisp tonal surface stepping and understated, warm-tinted ambient diffusion. Heavy artificial drop shadows are strictly avoided to keep the interface flat, architectural, and uncluttered.

- **Base Layer (Level 0)**: `#FDFBF7` canvas background for global page views.
- **Raised Surfaces (Level 1)**: Pure white (`#FFFFFF`) card containers, lists, and inventory tables. Depth is communicated via a subtle 1px border (`#EADBCE` or `rgba(43, 30, 22, 0.08)`) and an ultra-soft ambient shadow: `0 2px 8px rgba(43, 30, 22, 0.04)`.
- **Interactive Floating Layer (Level 2)**: Sticky transaction bars, bottom sheets, and floating filter chips utilize `0 6px 20px rgba(43, 30, 22, 0.08)` coupled with an upper structural border of 1px in `#EADBCE`.
- **Modals & Flyouts (Level 3)**: Box inspection sheets and inventory adjustment overlays use a backdrop scrim tinted with `#2B1E16` at 40% opacity, paired with an elevated sheet shadow of `0 12px 36px rgba(43, 30, 22, 0.16)`.

## Shapes

The design system adopts a soft, architectural shape profile (Level 1: 0.25rem / 4px base radius) reminiscent of hand-crafted Spanish cedar boxes and pressed tobacco packaging. 

- **Interactive Elements**: Buttons, inputs, and stepper triggers feature a subtle 4px corner radius, balancing precision with tactile comfort.
- **Containers**: Cards and bottom sheets scale gently to `rounded-lg` (8px), avoiding overly playful or bubbly shapes in favor of an organized, masculine, and timeless silhouette.
- **Pills & Badges**: Stock status badges and factory denomination chips use a compact 4px or strictly clipped 6px radius to preserve the look of traditional serial seals and vitola labels.

## Components

### Buttons
- **Primary**: Background `#2B1E16`, text `#FFFFFF`, border-radius 4px, height 48px to satisfy one-handed reach standards. Active tap feedback incorporates an opacity shift to 0.9 and a slight scale transform (0.99).
- **Secondary**: Transparent background, 1.5px border `#C5A059`, text `#2B1E16`, height 48px. Used for auxiliary workflows like "Print Box Label" or "Inspect Origin Certificate".
- **Tertiary / Ghost**: Text `#3E2723` with no background or border, used for dismissal and utility triggers.

### Inventory Cards
- Rendered on a pure white surface (`#FFFFFF`) with a 1px contour border (`rgba(43, 30, 22, 0.08)`).
- Divided into three visual anchors:
  1. Header: Brand, Vitola de Galera, and Factory Origin rendered in `Manrope` 14px bold.
  2. Metric Center: Cigar format (Ring Gauge x Length) alongside physical humidor storage location (e.g., "Cabinet C, Shelf 2").
  3. Action Footer: Tabular stock counter with prominent `+` and `-` touch buttons separated by an explicit numeric readout.

### Stock Chips & Status Badges
- **Optimal**: Background `rgba(74, 107, 72, 0.12)`, text `#4A6B48`, uppercase `label-sm`.
- **Moderate**: Background `rgba(212, 155, 55, 0.14)`, text `#996918`, uppercase `label-sm`.
- **Critical / Out**: Background `rgba(163, 56, 42, 0.12)`, text `#A3382A`, uppercase `label-sm`.
- All chips include a 6px solid circular dot indicator before the text label for immediate peripheral recognition.

### Inputs & Quantity Steppers
- **Text Inputs & Barcode Fields**: Height 48px, background `#FFFFFF`, border 1px solid `#DCD0C4`, font `Manrope` 14px. Focus state triggers a 1.5px border in `#C5A059` without jarring glow rings.
- **Quick Steppers**: Dedicated thumb-accessible modules with two 44x44px target buttons flanking a central numeric display, optimized for rapid batch decrementing during register sales.

### Checkboxes & Selection Controls
- Checkbox squares (20x20px, 3px border-radius) in `#2B1E16` when checked, with a crisp ivory checkmark. Radio buttons use a `#C5A059` concentric dot.

### Specialized Component: Humidor Gauge & Vitola Spec Banner
- A compact metadata ribbon placed at the top of detail views, displaying relative humidity (RH%), temperature (°C), and aging date, framed with a delicate hairline border in bronze tone.