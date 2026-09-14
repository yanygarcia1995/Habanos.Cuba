---
name: Atelier Humidor
colors:
  surface: '#fbf9f6'
  surface-dim: '#dbdad7'
  surface-bright: '#fbf9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f0'
  surface-container: '#efeeeb'
  surface-container-high: '#eae8e5'
  surface-container-highest: '#e4e2df'
  on-surface: '#1b1c1a'
  on-surface-variant: '#52443b'
  inverse-surface: '#30312f'
  inverse-on-surface: '#f2f0ed'
  outline: '#847469'
  outline-variant: '#d7c3b6'
  surface-tint: '#885124'
  primary: '#7d481c'
  on-primary: '#ffffff'
  primary-container: '#9a6032'
  on-primary-container: '#ffeee4'
  inverse-primary: '#ffb782'
  secondary: '#625d5b'
  on-secondary: '#ffffff'
  secondary-container: '#e9e1dd'
  on-secondary-container: '#686361'
  tertiary: '#8e3e00'
  on-tertiary: '#ffffff'
  tertiary-container: '#b25207'
  on-tertiary-container: '#ffeee7'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdcc5'
  primary-fixed-dim: '#ffb782'
  on-primary-fixed: '#301400'
  on-primary-fixed-variant: '#6c3a0f'
  secondary-fixed: '#e9e1dd'
  secondary-fixed-dim: '#ccc5c2'
  on-secondary-fixed: '#1e1b19'
  on-secondary-fixed-variant: '#4a4643'
  tertiary-fixed: '#ffdbca'
  tertiary-fixed-dim: '#ffb68e'
  on-tertiary-fixed: '#331200'
  on-tertiary-fixed-variant: '#763300'
  background: '#fbf9f6'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2df'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 44px
    fontWeight: '600'
    lineHeight: 52px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: '0'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
  title-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.01em
  title-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.06em
  numerical-data:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 24px
    letterSpacing: -0.02em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2.5rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies the ritualistic, tactile world of rare tobacco collections translated into a modern digital archive. Blending refined editorial minimalism with functional utility, it caters to discerning collectors, lounge proprietors, and sommeliers who value provenance, age, and meticulous care.

The visual tone draws inspiration from bespoke horology cataloging, high-end editorial volumes, and Spanish cedar cabinetry. The UI balances quiet luxury with surgical operational clarity:
- **Atmosphere:** Warm, serene, and uncluttered. It eschews gratuitous skeuomorphism (such as simulated wood grain or leather textures) in favor of authentic tactile warmth delivered through color temperature, expansive negative space, and crisp micro-details.
- **Demeanor:** Professional, respectful of craftsmanship, and effortless to navigate during cellar and humidor auditing.
- **Style Direction:** Modern Editorial Minimalism accented with warm tonal layering, crisp borders, and authoritative typographic hierarchy.

## Colors

The palette is anchored in organic humidor tones: aged parchment, cured wrapper leaves, polished brass hygrometer trims, and Spanish cedar drawers.

### Roles & Tonal Tiers
- **Canvas Base:** `#FAF8F5` (Parchment White) creates a soft, museum-grade surface that eliminates the eye fatigue associated with stark digital white.
- **Surface Level 1 (Cards & Modals):** `#FFFFFF` provides high contrast against the parchment backdrop, focusing attention on inventory items.
- **Surface Level 2 (Subtle Insets & Well Backgrounds):** `#F5F2EB` for table headers, metric chips, and counter wells.
- **Primary / Brand Accent:** `#9A6032` (Cedar Amber) serves as the primary interactive hue, reflecting aged wrappers and mahogany craftsmanship.
- **Secondary / High Contrast Text & Accents:** `#1C1917` (Smoked Charcoal) provides definitive readability for headings, primary numbers, and deep contrast buttons.
- **Tertiary / Warm Glow:** `#B45309` (Burnished Tobacco) and `#D97706` (Sun-cured Gold) are reserved for active status states, highlights, and star ratings.
- **Borders & Dividers:** `#E7E2DA` delivers razor-sharp structural delineation while preserving a soft, low-contrast feel.
- **Status & Condition Signals:**
  - *Optimal Humidity / In Stock:* Muted Olive `#4D6B53` (Background: `#F1F5F2`)
  - *Aging Required / Moderate:* Amber Honey `#B45309` (Background: `#FDF6EC`)
  - *Critical / Depleted:* Deep Claret `#88292F` (Background: `#FBF1F1`)

## Typography

The typographic hierarchy pairs the literary dignity of `Playfair Display` with the structural, uncompromised precision of `Inter`.

- **Editorial Serifs (Playfair Display):** Applied deliberately to vitola designations, brand marques (e.g., Cohiba, Arturo Fuente, Partagás), humidor titles, and major summary views. Sets an unhurried, artisanal tone.
- **Technical Sans-Serif (Inter):** Deployed for all metadata: ring gauges, wrapper varieties, humidity/temperature telemetry, quantities, timestamps, and data tables. Monospaced lining figures (`font-variant-numeric: tabular-nums`) must be activated for all inventory counts and dimensions to guarantee vertical alignment in lists and tables.
- **Labels:** Uppercase tracking (`0.04em` to `0.06em`) is strictly reserved for micro-labels (e.g., `FACTORY NAME`, `STATUS`, `RH%`, `BOX CODE`) to establish clear visual anchors without competing with primary data.

## Layout & Spacing

The layout is built on a responsive 12-column grid system designed around intentional breathing room. The interface avoids dense enterprise dashboard layouts, opting instead for a curated gallery approach.

- **Desktop (>= 1200px):** 12-column grid, `margin: 2.5rem`, `gutter: 1.5rem`. Maximum container width is pinned to `1440px` centered to maintain optimal scanning paths.
- **Tablet (768px - 1199px):** 8-column grid, `margin: 1.5rem`, `gutter: 1.25rem`. Complex horizontal tables shift to compact card views or horizontally pinned key columns.
- **Mobile (< 768px):** 4-column grid, `margin-mobile: 1rem`, `gutter-mobile: 1rem`. Inventory rows convert to card patterns with prominent increment/decrement counters within the primary thumb zone.
- **Vertical Rhythm:** Strict multiples of `4px` and `8px`. Component internal padding uses `space-md` (`16px`) and `space-lg` (`24px`) to preserve an open, unhurried air.

## Elevation & Depth

This design system avoids loud dropshadows and glossy treatments in favor of low-contrast outlines, natural light refraction, and warm tonal layering.

- **Surface Separation:** Achieved primarily through border delineations using `#E7E2DA` combined with subtle background switches from `#FAF8F5` (page base) to `#FFFFFF` (card tier).
- **Resting Elevation:** Cards, humidor trays, and modules sit flat with a hairline border (`1px solid #E7E2DA`) and an ultra-diffused, warm ambient shadow:
  `box-shadow: 0 2px 8px -2px rgba(28, 25, 23, 0.04), 0 1px 3px 0 rgba(28, 25, 23, 0.02);`
- **Hover & Active Elevation:** Interactive cards raise slightly with a subtle warm shadow bloom:
  `box-shadow: 0 12px 24px -6px rgba(154, 96, 50, 0.08), 0 4px 8px -2px rgba(28, 25, 23, 0.03);`
  `border-color: #D9D2C7;`
- **Overlays, Drawers & Popovers:** Surface is pure `#FFFFFF` with a crisp border and structured ambient occlusion:
  `box-shadow: 0 20px 32px -8px rgba(28, 25, 23, 0.08), 0 6px 12px -4px rgba(28, 25, 23, 0.04);`

## Shapes

The design system employs a restrained **Soft** shape language (`roundedness: 1`). Soft corners mirror bespoke packaging, cigar boxes, and architectural humidor trays without feeling overly playful or juvenile.

- **Base Radius (`0.25rem` / `4px`):** Used for micro components: inline badges, tag pills, count stepper segment buttons, and tabular status markers.
- **Container Radius (`rounded-lg: 0.5rem` / `8px`):** Standard across inventory cards, metric summary blocks, text inputs, and table container wraps.
- **Large Overlays (`rounded-xl: 0.75rem` / `12px`):** Reserved for floating dialogs, full humidor drawer drawers, and detail inspection modals.

## Components

### 1. Buttons & Stepper Controls
- **Primary Action:** Solid charcoal `#1C1917` with `#FFFFFF` text. On hover, shifts softly to `#292524`. Padding: `10px 20px`. Border-radius: `4px`.
- **Secondary Action:** Outlined with `1px solid #E7E2DA`, text in `#1C1917`, background `#FFFFFF`. On hover, background shifts to `#F5F2EB` and border transitions to `#9A6032`.
- **Cedar Accent Button:** Background `#9A6032`, text `#FFFFFF`. Used for principal collection actions (e.g., "Add Box", "Smoke One").
- **Intuitive Counter Buttons (+ and -):** Integrated stepper control housed in an enclosed `1px solid #E7E2DA` pill. Features dual square micro-buttons (`32px × 32px`) flanking tabular numerical counts. Subtle click depression with tactile state changes (`active:bg-[#E7E2DA]`).

### 2. Status Badges & Chips
- **Geometry:** Height of `24px`, horizontal padding `8px`, corner radius `4px`. All text uses `label-sm` in uppercase.
- **Condition Tiers:**
  - *Resting/In Cellar:* Soft cream background `#F5F2EB`, text `#9A6032`, border `#E7E2DA`.
  - *Ready to Smoke:* Gentle sage tint `#F1F5F2`, text `#3D5943`, border `#D3E0D6`.
  - *Aging Phase:* Pale amber `#FDF6EC`, text `#B45309`, border `#F4DEC3`.
  - *Restock Trigger:* Soft rose `#FBF1F1`, text `#88292F`, border `#EED1D3`.

### 3. Inventory Cards & Vitola Rows
- **Card Format:** Background `#FFFFFF`, hairline border `#E7E2DA`, internal padding `20px`. Displays brand, line, vitola specification (e.g., `Robusto 50 x 124mm`), wrapper provenance, aging duration, current count, and integrated stepper.
- **List / Table Row:** Striped hover with `#FAF8F5`. Monospaced tabular figures for counts, purchase prices, and RH% ratings. Subdued bottom border `1px solid #F5F2EB`.

### 4. Input Fields & Selectors
- **Input Fields:** Background `#FFFFFF`, border `1px solid #E7E2DA`, color `#1C1917`. Placeholder `#A8A29E`. Focus state introduces a crisp `1px solid #9A6032` with an ambient glow (`0 0 0 3px rgba(154, 96, 50, 0.12)`).
- **Segmented Filter Tabs:** Contained within a `#F5F2EB` track. Active tab is `#FFFFFF` with `box-shadow: 0 1px 3px rgba(28, 25, 23, 0.06)`, text `#1C1917`, inactive text `#78716C`.

### 5. Domain-Specific Components
- **Hygro-Thermal Telemetry Gauge:** Compact card showing Relative Humidity (RH%) and Temperature (°F/°C). Value rendered in `Inter` semi-bold with status indicator dot. Optimal range (65–69% RH) indicated via hairline status bar.
- **Vitola Dimension Gauge:** Visual ring gauge and length ruler indicator depicted in fine `#9A6032` linework.
- **Tasting Profile Matrix:** Minimal horizontal bar scores (Body, Strength, Complexity) rendered in soft neutral bars with fill in Cedar Amber `#9A6032`.