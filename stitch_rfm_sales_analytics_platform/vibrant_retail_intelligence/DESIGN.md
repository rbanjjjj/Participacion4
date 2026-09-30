---
name: Vibrant Retail Intelligence
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
  on-surface-variant: '#5a4139'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#8e7067'
  outline-variant: '#e2bfb4'
  surface-tint: '#ab3500'
  primary: '#a73400'
  on-primary: '#ffffff'
  primary-container: '#d04505'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb59c'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#00685f'
  on-tertiary: '#ffffff'
  tertiary-container: '#008378'
  on-tertiary-container: '#f4fffc'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbd0'
  primary-fixed-dim: '#ffb59c'
  on-primary-fixed: '#390c00'
  on-primary-fixed-variant: '#832700'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#89f5e7'
  tertiary-fixed-dim: '#6bd8cb'
  on-tertiary-fixed: '#00201d'
  on-tertiary-fixed-variant: '#005049'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.005em
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
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
  metric-stat:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  table-data:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 0.75rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style
The design system balances high-velocity retail data analytics with accessible, human-centered decision making. Targeted at enterprise retail merchandisers, growth marketers, and data scientists, the interface projects analytical precision, momentum, and operational clarity.

The aesthetic blends **Modern Corporate** structure with **High-Contrast Precision**:
- **Clarity over Clutter:** Dense data representations (RFM matrix grids, cohort heatmaps, decile distributions) rely on white space and subtle structural lines rather than visual noise.
- **Vibrant Purpose:** An energetic orange primary anchor cuts through cool, warm-slate neutrals to immediately signal actionable insights, anomalous churn risks, and top-tier customer loyalty segments ("Champions").
- **Physical Structure:** Elements feature tailored hairline borders, understated micro-depth, and tight, confident typography to foster immediate trust in high-stakes monetary metrics.

## Colors
The color architecture prioritizes rapid cognitive scanning across dense analytical tables, metric banners, and customer segment badges.

### Palette Architecture
- **Primary (`#F05B21` - Kinetic Orange):** Dedicated strictly to key actionable states, active navigation indicators, focal trend lines, RFM primary cohort triggers, and high-value conversion funnels. Avoid overuse in large background blocks.
- **Secondary (`#0F172A` - Deep Obsidian Slate):** Provides high-contrast anchor weights for headlines, dense metric numerals, and structural table headers. Ensures supreme legibility against light surfaces.
- **Tertiary (`#0D9488` - Deep Teal):** Used to represent health, positive cohort shifts, and monetary growth, serving as an analytical counterweight to the warmth of the primary orange.
- **Neutral (`#64748B` - Slate Neutral):** Powers secondary data labels, column subtitles, table metadata, subtle borders (`#E2E8F0`), and page canvas tints (`#F8FAFC`).

### Functional RFM Segment Tokens
- **Champions / High Value:** Tinted deep orange-amber with crisp orange borders.
- **Loyal / Regulars:** Slate-teal balanced tones.
- **At Risk / Churning:** Subdued coral-rose (`#E11D48`) accents.
- **Hibernating / Lost:** Cool muted neutral slate with low saturation.

## Typography
The system employs **Plus Jakarta Sans** for display, headlines, and big numerical callouts, providing modern geometric presence. **Inter** handles high-density body copy, complex tables, metadata labels, and form elements where vertical rhythm and tabular numerical legibility are critical.

### Application Rules
- **Tabular Numerics:** Enable `font-feature-settings: "tnum" 1` across all data tables, metric tiles, and monetary comparisons to prevent column jitter when metrics recalculate.
- **Hierarchy Balance:** Metric cards place `label-sm` (uppercase with letter spacing) on top, followed by `metric-stat` in primary slate, and contextual delta indicators in `body-sm`.
- **Contrast Control:** Major figures use `#0F172A`, standard text uses `#334155`, and supplementary labels rely on `#64748B`. Never drop body contrast below WCAG AAA requirements for data readability.

## Layout & Spacing
A fluid 12-column grid anchors desktop views, folding into a 6-column grid on tablets, and a 4-column single-axis stack on mobile devices.

### Grid Breakpoints
- **Desktop (>= 1280px):** 12-column layout, 24px (`1.5rem`) gutters, 32px (`2rem`) margins. Max container constraint: 1600px.
- **Tablet (768px - 1279px):** 6-column layout, 16px (`1rem`) gutters, 24px (`1.5rem`) margins. Metric cards stack into 2x2 grids.
- **Mobile (< 768px):** 4-column layout, 12px (`0.75rem`) gutters, 16px (`1rem`) margins. Dashboard modules snap to full width with sticky summary bars.

### Spacing Principles
- Spacing follows an 8pt base grid with a 4pt micro-step (`0.25rem`) for fine component alignment.
- Dense data tables enforce a compact 8px vertical cell padding, preserving visual breathing space without sacrificing data per screen inch.

## Elevation & Depth
Depth in the system is structured through **tonal surface layering** and **crisp hairline borders**, rejecting fuzzy, heavy drop shadows in favor of analytical clarity.

### Depth Hierarchy
1. **Canvas (Base Level):** Warm Slate tint (`#F8FAFC`).
2. **Surface Level (Cards, Table Containers, Sidebars):** Crisp pure white (`#FFFFFF`) with a 1px solid border in `#E2E8F0`. 
3. **Card Micro-Shadow (Rest):** `0 1px 3px 0 rgba(15, 23, 42, 0.04), 0 1px 2px -1px rgba(15, 23, 42, 0.03)`.
4. **Interactive / Hover Surface:** Elevated to `0 4px 6px -1px rgba(15, 23, 42, 0.06), 0 2px 4px -2px rgba(15, 23, 42, 0.04)` with a subtle border highlight in `#CBD5E1`.
5. **Floating Panels (Dropzones, Filter Drawers, Modals):** Crisp white with `0 10px 15px -3px rgba(15, 23, 42, 0.08), 0 4px 6px -4px rgba(15, 23, 42, 0.03)` and a 1px slate ring (`#CBD5E1`).

## Shapes
A consistent **Rounded** radius scale (`0.5rem` / `8px` default) delivers a refined contemporary software feel that balances technical rigor with approachability.

### Radius Assignments
- **Inputs, Buttons, Segment Chips:** `0.5rem` (8px).
- **Metric Cards, Chart Containers, Dropzones:** `0.75rem` to `1rem` (12px to 16px).
- **Status Badges & Pill Toggles:** Full pill boundary (`9999px`).
- **Inner Data Bars & Progress Tracks:** `0.25rem` (4px).

## Components

### Metric Cards
- Background: `#FFFFFF`, border: `1px solid #E2E8F0`, corner radius: `0.75rem`.
- Header row contains the RFM dimension or KPI label (`label-sm`, color: `#64748B`, uppercase tracking) paired with an optional micro sparkline or category indicator.
- Metric value displayed in `metric-stat` (`#0F172A`).
- Subtext includes directional badges: Green pill (`#F0FDF4` background, `#15803D` text) for positive cohort movement, Red pill (`#FEF2F2`, `#B91C1C`) for negative retention drift.

### High-Contrast Data Tables
- Header: `#F8FAFC` background, 1px solid horizontal border `#E2E8F0`, column labels in `label-sm` (`#475569`).
- Rows: `#FFFFFF` with hover state shifting to `#F1F5F9`. Cell padding: 12px horizontal, 10px vertical.
- RFM Score indicators: Segmented three-number tags (e.g., `5-5-4`) rendered in monospace-aligned badges with border styling.
- Pinned columns: Left customer identifiers lock with a subtle right drop-border shadow.

### Buttons & Interactive Triggers
- **Primary:** Solid `#F05B21` background, white text (`#FFFFFF`), `label-lg`, height: 40px, roundedness: 8px. Hover: `#D94E1B`. Active: `#C2410C`. Focus: 3px outer ring in `rgba(240, 91, 33, 0.25)`.
- **Secondary:** `#FFFFFF` background, `1px solid #CBD5E1` border, `#0F172A` text. Hover: `#F8FAFC` and border `#94A3B8`.
- **Ghost:** Transparent background, `#475569` text. Hover: `#F1F5F9`.

### File Upload Dropzone (Interactive CSV/Data Feed)
- Border: `2px dashed #CBD5E1`, transition to `2px dashed #F05B21` on drag-over.
- Canvas: `#F8FAFC`, transitioning to `#FFF7ED` when active.
- Icon: Upload cloud glyph centered with a 48px circular `#FFEDD5` badge and `#F05B21` fill.
- Micro-copy: Primary upload prompt in `label-md` (`#0F172A`), supported by schema constraints ("CSV, XLSX up to 50MB") in `body-sm` (`#64748B`).

### Status Badges & Segment Chips
- Height: 24px, pill-shaped (`roundedness: 9999px`), padding: 0 10px.
- **Champions Segment:** Tint `#FFF7ED`, border `#FDBA74`, text `#C2410C`.
- **Loyal Segment:** Tint `#F0FDFA`, border `#99F6E4`, text `#0F766E`.
- **At Risk Segment:** Tint `#FEF2F2`, border `#FECACA`, text `#B91C1C`.
- Includes a leading 6px circular solid status dot.

### Inputs & Selection Controls
- Text Inputs: 40px height, `#FFFFFF` background, `1px solid #CBD5E1` border, `0.5rem` radius. Placeholder text in `#94A3B8`. Focus state elevates border to `#F05B21` with a `0 0 0 3px rgba(240, 91, 33, 0.15)` focus ring.
- Checkboxes: 18x18px, `1px solid #CBD5E1`, rounded `4px`. Checked state: solid `#F05B21` with a white checkmark.