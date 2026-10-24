---
name: Luminous Vanguard
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
  on-surface-variant: '#44474c'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#75777d'
  outline-variant: '#c5c6cd'
  surface-tint: '#525f75'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#0e1c2f'
  on-primary-container: '#77849c'
  inverse-primary: '#bac7e1'
  secondary: '#a73a00'
  on-secondary: '#ffffff'
  secondary-container: '#fd651e'
  on-secondary-container: '#571a00'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#002113'
  on-tertiary-container: '#009668'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3fe'
  primary-fixed-dim: '#bac7e1'
  on-primary-fixed: '#0e1c2f'
  on-primary-fixed-variant: '#3a475c'
  secondary-fixed: '#ffdbce'
  secondary-fixed-dim: '#ffb599'
  on-secondary-fixed: '#370e00'
  on-secondary-fixed-variant: '#7f2b00'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 3.5rem
    fontWeight: '800'
    lineHeight: 4.25rem
    letterSpacing: -0.03em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '800'
    lineHeight: 2.75rem
    letterSpacing: -0.025em
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.5rem
    fontWeight: '700'
    lineHeight: 3rem
    letterSpacing: -0.025em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.75rem
    fontWeight: '700'
    lineHeight: 2.25rem
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.75rem
    fontWeight: '600'
    lineHeight: 2.25rem
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
    letterSpacing: -0.01em
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '600'
    lineHeight: 1.625rem
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.75rem
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.5rem
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.375rem
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: 1.25rem
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: 1rem
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  gutter-lg: 2rem
  margin: 1.5rem
  margin-sm: 1rem
  margin-lg: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies high-achievement academic rigor fused with warm, forward-looking mentorship. It balances the timeless authority of an elite educational institute with the dynamic, optimistic energy required to inspire students preparing for competitive academic journeys.

The visual aesthetic synthesizes **Modern Academic Editorial** with refined **Frosted Glassmorphism** and subtle tactile interactions:
- **Tone & Persona:** Authoritative, motivating, structured, and profoundly clear. It conveys prestige without feeling austere or archaic.
- **Target Audience:** Driven students, competitive exam aspirants, and discerning parents seeking institutional trust, proven results, and structured clarity.
- **Visual Expression:** Generous architectural whitespace, deep midnight navy structural anchors, energetic amber-orange milestones, and crisp emerald proof points. Surfaces utilize crystalline frosted transitions, hairline borders, and fluid soft corners to sustain an unmistakably contemporary feel across bilingual script interfaces.

## Colors

The palette establishes an intellectual hierarchy using midnight navy for institutional grounding, saturated amber for motivational momentum, and vibrant emerald for verifiable achievement.

- **Primary (`#0B192C` to `#1E3A8A`):** The institutional anchor. Used for primary interactive actions, high-emphasis headings, key structural navigation, and foundational UI framework elements.
- **Secondary / Accent (`#EA580C` to `#F97316`):** The catalyst color. Used intentionally for high-conversion CTAs, active progress indicators, live lecture highlights, and critical deadlines. Avoid using this for large background fills.
- **Tertiary / Success (`#10B981`):** Academic verification. Dedicated to rank milestones, pass badges, score improvements, verified test results, and positive state banners.
- **Neutral / Structural (`#64748B`):** Cool slate spectrum. Regulates secondary typography, subtle gridlines, pill borders, and inactive states.
- **Canvas & Surface Palette:**
  - Base Background: `#F8FAFC` (Slate 50) to provide a soft, non-glare foundation.
  - Surface Pure: `#FFFFFF` for primary cards and focus states.
  - Surface Glass: `rgba(255, 255, 255, 0.82)` with `backdrop-filter: blur(16px)` for floating global navigation and contextual modals.
  - Hairline Borders: `rgba(226, 232, 240, 0.8)` for delicate division without structural noise.

## Typography

The typography leverages **Plus Jakarta Sans**, chosen for its geometric precision, open letter apertures, and broad unicode optical performance that natively harmonizes with contemporary Bengali system scripts (such as Noto Sans Bengali or Hind Siliguri) in bilingual educational contexts.

- **Bilingual Typographic Scale:** Maintain a strict 1.4 to 1.6 relative line-height multiplier across Bengali body segments to accommodate matras (vowel signs) without ascender/descender collision.
- **Hierarchy Rules:** 
  - Never set body content beneath 14px equivalent (`body-sm`) to preserve rigorous legibility for syllabus details, academic notices, and mathematical problem statements.
  - Headings feature tighter tracking (`-0.025em`) to evoke an assertive, editorial stance.
  - Labels and tags use moderate positive tracking (`+0.01em` to `+0.02em`) with medium-to-bold weights to guarantee scannability on test dashboards and schedules.

## Layout & Spacing

The layout architecture implements a crisp 12-column responsive fluid grid designed to support information-dense student portals as well as spacious institutional landing pages.

- **Breakpoints & Grids:**
  - **Desktop (≥ 1280px):** 12-column layout, 72rem to 80rem max-width, `gutter-lg` (32px), `margin-lg` (48px).
  - **Tablet (768px – 1279px):** 8-column layout, `gutter` (24px), `margin` (24px).
  - **Mobile (< 768px):** 4-column layout, `gutter-sm` (16px), `margin-sm` (16px).
- **Rhythm & Spatial Logic:**
  - Content containers rely on an 8pt baseline cadence (`space-sm: 8px`, `space-md: 16px`, `space-lg: 24px`, `space-xl: 40px`).
  - Section-to-section breaks leverage vertical breathing room (minimum 64px on mobile, 96px to 120px on desktop) to keep academic curriculum structures digestible and unhurried.

## Elevation & Depth

Visual depth combines ethereal frosted surfaces with soft ambient shadows tinted by the midnight navy primary hue, rejecting sterile grays in favor of dimensional warmth.

- **Surface Level 0 (Base Canvas):** `#F8FAFC`, non-elevated, grounding the layout.
- **Surface Level 1 (Resting Cards & Panels):** `#FFFFFF` paired with an ultra-soft ambient occlusion shadow:
  - `box-shadow: 0 4px 20px -2px rgba(11, 25, 44, 0.04), 0 2px 6px -1px rgba(11, 25, 44, 0.02);`
  - Border: 1px solid `rgba(226, 232, 240, 0.8)`.
- **Surface Level 2 (Hover States & Interactive Overlays):**
  - `box-shadow: 0 12px 32px -4px rgba(11, 25, 44, 0.08), 0 4px 12px -2px rgba(11, 25, 44, 0.03);`
  - Subtle upward translateY (-2px) transition over 200ms cubic-bezier(0.16, 1, 0.3, 1).
- **Glassmorphism Layer (Sticky Top Navigation & Quick Floating Panels):**
  - Background: `rgba(255, 255, 255, 0.82)`.
  - Backdrop Blur: `16px`.
  - Border bottom: 1px solid `rgba(226, 232, 240, 0.6)`.
  - Provides a sleek, floating veil that allows underlying colors to softly bleed through without compromising text accessibility.

## Shapes

The design system employs a refined `rounded-2xl` architecture (1rem / 16px base corner radius) that imbues modern friendliness while preserving structural discipline.

- **Component Outer Enclosures (Cards, Feature Modules, Modals):** `rounded-2xl` (16px) or `rounded-3xl` (24px) for expansive hero units.
- **Inner Interactive Elements (Buttons, Inputs, Selectors):** `rounded-xl` (12px) to form a harmonious nested relationship inside 16px containers.
- **Pills & Metas (Status Badges, Rank Tags, Filter Chips):** Full pill curvature (`rounded-full`) to differentiate lightweight metadata from content containers.
- **Structural Integrity:** Elements must maintain consistent concentric radiuses—inner radii should match the outer radius minus the uniform padding to eliminate corner tension.

## Components

### Buttons
- **Primary Action (Institutional):** Deep navy (`#0B192C`) solid fill, white text, 12px corner radius. Padding: `12px 24px`. Hover state reveals subtle lightening to `#1E3A8A` with a calibrated navy drop shadow (`rgba(11, 25, 44, 0.2)`).
- **Secondary Action (Energetic/Enrollment):** Vibrant warm amber (`#EA580C`) fill, white text. Dedicated to conversion events ("Enroll Now", "Book Free Demo"). Hover shifts to `#F97316` with a micro-glow shadow (`rgba(234, 88, 12, 0.25)`).
- **Tertiary / Ghost:** Transparent fill, `#0B192C` border (1px hairline) or neutral slate text. Hover yields `rgba(11, 25, 44, 0.04)` fill.

### Badges & Chips
- **Success / Results Badges:** Emerald green tint (`#ECFDF5`) background, `#047857` deep emerald text, `rgba(16, 185, 129, 0.2)` stroke. Accompanied by a solid 6px emerald status dot.
- **Subject & Category Chips:** Light slate tint (`#F1F5F9`) background, `#334155` text, pill-shaped (`rounded-full`), padding `6px 14px`. Hover triggers border transition to `#CBD5E1`.
- **Urgent / Live Indicator:** Light amber tint (`#FFF7ED`) background, `#C2410C` text, paired with a pulsing amber beacon indicator.

### Cards
- **Course & Batch Card:** White surface, 16px radius, subtle slate border (`#E2E8F0`). Divided into three vertical zones: course visual/batch tag, structured metadata (teacher, schedule, seat count), and primary CTA footer.
- **Achievement / Rank Card:** White surface with top-right accent sash in emerald or navy, incorporating a high-contrast serif/bold score display alongside student attribution.

### Input Fields & Selects
- **Form Controls:** 48px height, 12px radius, `#FFFFFF` interior with `#CBD5E1` border.
- **States:** Focus replaces border with `#1E3A8A` accompanied by an ambient focus ring (`0 0 0 3px rgba(30, 58, 138, 0.12)`). Labels rest above inputs in `label-md` slate typography.

### Lists & Curriculum Accordions
- **Batch Schedule & Syllabus Lists:** Clean horizontal item rows separated by `1px solid #F1F5F9`. Expanded module headers sport light gray backgrounds with rotating chevron indicators and clear duration/lecture count metadata tags.

### Academic Highlights & Banners
- **Notice Bar:** Glassmorphism overlay banner pinned at the viewport top with subtle amber alert highlight, delivering immediate schedule shifts or competitive exam notifications.