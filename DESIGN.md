---
name: Pulse 60 / India Now
colors:
  surface: '#0f131d'
  surface-dim: '#0f131d'
  surface-bright: '#353944'
  surface-container-lowest: '#0a0e18'
  surface-container-low: '#171b26'
  surface-container: '#1c1f2a'
  surface-container-high: '#262a35'
  surface-container-highest: '#313540'
  on-surface: '#dfe2f1'
  on-surface-variant: '#e7bdb2'
  inverse-surface: '#dfe2f1'
  inverse-on-surface: '#2c303b'
  outline: '#ad887e'
  outline-variant: '#5d4038'
  surface-tint: '#ffb5a0'
  primary: '#ffb5a0'
  on-primary: '#601400'
  primary-container: '#ff5625'
  on-primary-container: '#541100'
  inverse-primary: '#b12d00'
  secondary: '#ffb59d'
  on-secondary: '#5d1900'
  secondary-container: '#b83900'
  on-secondary-container: '#ffddd2'
  tertiary: '#4edea3'
  on-tertiary: '#003824'
  tertiary-container: '#00a572'
  on-tertiary-container: '#00311f'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdbd1'
  primary-fixed-dim: '#ffb5a0'
  on-primary-fixed: '#3b0900'
  on-primary-fixed-variant: '#872000'
  secondary-fixed: '#ffdbd0'
  secondary-fixed-dim: '#ffb59d'
  on-secondary-fixed: '#390c00'
  on-secondary-fixed-variant: '#832600'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#0f131d'
  on-background: '#dfe2f1'
  surface-variant: '#313540'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '800'
    lineHeight: 34px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 19px
    fontWeight: '700'
    lineHeight: 25px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 17px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
  label-caps:
    fontFamily: Inter
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 12px
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
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-desktop: 2.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1.25rem
  space-xl: 2rem
---

## Brand & Style
This design system establishes a high-velocity, authoritative, and distraction-free editorial interface tailored for real-time national news and live event tracking across India. Built for speed of comprehension under cognitive load, it conveys immediacy, journalistic credibility, and uncompromised precision.

The design movement merges **High-Contrast Editorial** with modern **Utility-First Real-Time Dashboards**. Rather than relying on heavy skeuomorphic cues, the interface utilizes high-contrast tonal layering, sharp typographic hierarchies, micro-status indicators, and crisp edge delineation. The aesthetic balances the relentless energy of 60-second updates with the gravitas of verified journalism.

## Colors
The palette is rooted in an ultra-deep navy-slate night architecture, engineered to reduce glare during continuous monitoring while giving maximum pop to real-time signals:

- **Canvas & Base Surface (`#0B0F19`)**: Absolute dark navy slate foundation, grounding the UI and minimizing visual fatigue.
- **Surface Elevation Layers**:
  - `surface-container-low`: `#121826` for primary news cards, stream panels, and collapsed feeds.
  - `surface-container-high`: `#1E293B` for elevated modals, active filtering bars, popovers, and sticky headers.
  - `surface-border`: `#334155` for ultra-fine 1px architectural divider lines.
- **Urgent & Breaking Primary (`#FF4500` / `#FF6B35`)**: Electric Vermilion and High-Heat Saffron used selectively for breaking news ribbons, flash alerts, and live counter pulses. Never applied in large solid fields.
- **Live Status & Verification Tertiary (`#10B981`)**: Vibrant Emerald reserved for ongoing live streams, active ticker statuses, verified source checkmarks, and new alert pulses.
- **Text & Contrast Hierarchy**:
  - Primary text: `#F8FAFC` (98% contrast against base).
  - Secondary text: `#94A3B8` (metadata, relative timestamps, author credits).
  - Tertiary / Ghost text: `#64748B` (unfocused icons, inactive track bars).

## Typography
Typography is split purposefully between two specialized typefaces:

1. **Plus Jakarta Sans** governs all headlines and lead titles. Its wide aperture, sharp geometric cuts, and contemporary sans structure deliver immediacy without descending into tabloid sensationalism.
2. **Inter** powers body copy, real-time ticker data, verified tags, and timestamps. It provides mathematical vertical alignment, exceptional rendering at sub-12px sizes, and support for tabular figures (`tnum`) essential for elapsed counters ("12s ago", "03:45 remaining").

All breaking news caps (`label-caps`) enforce tracked uppercase styling to provide immediate anchor points for the eye as the reader scans down a rapid feed.

## Layout & Spacing
The layout follows a fluid-grid structure optimized for vertical chronological flow and rapid scanning:

- **Mobile Viewports (< 768px)**: Single-column continuous stream. Outer margins are anchored at `1rem` to maximize screen real estate for dense news snippets. Content blocks maintain compact padding (`space-md`) to ensure 3-4 news items remain visible above the fold.
- **Tablet Viewports (768px - 1024px)**: 8-column layout. Main feed spans 5 columns, with persistent trending/live election or event trackers occupying the remaining 3 columns.
- **Desktop Viewports (> 1024px)**: 12-column fixed-max layout (max width 1280px). 
  - Left utility column (2 cols): Pinned category filters, regional switchers (National, Delhi NCR, Mumbai, Tech, Markets).
  - Central stream (7 cols): Real-time chronologically sequenced cards.
  - Right intelligence pane (3 cols): Live video streams, key developments summary, and high-frequency push alerts.

## Elevation & Depth
This design system departs from fuzzy drop shadows, relying primarily on **Tonal Stratification and Crisp Borders**:

- **Level 0 (Canvas)**: `#0B0F19` base canvas.
- **Level 1 (Card Surface)**: `#121826` surface container bounded by a 1px solid stroke in `#1E293B`.
- **Level 2 (Hover / Active Focus)**: Border shifts to `#334155` with a subtle, non-blurry 0 4px 16px -2px rgba(0, 0, 0, 0.45) drop.
- **Level 3 (Breaking Alert Overlays & Live Sheets)**: `#1E293B` elevated container with an active hairline border tinted with the primary accent: `1px solid rgba(255, 69, 0, 0.3)`.
- **Glass Accents**: Sticky navigation headers and floating "New Updates Available" pills use `backdrop-filter: blur(12px)` over a 75% translucent `#0B0F19BF` background, maintaining orientation while preserving reading momentum.

## Shapes
The design system adopts a **Soft (Level 1)** geometric architectural profile. Rounded corners are intentionally restrained to reinforce an authoritative, disciplined newsroom environment rather than a casual social feed:

- Standard feed cards, multimedia containers, and bottom sheets: `0.25rem` (`rounded`).
- Interactive buttons, tags, chips, and audio pills: `0.5rem` (`rounded-lg`).
- Live indicators, pulsing status pips, and source badges: `9999px` (Full Circle / Pill).

## Components

### Editorial News Cards
- Constructed on `#121826` with a 1px `#1E293B` border.
- Features top metadata slot: Source badge (left), verified tick (Emerald), and relative timestamp (right) in tabular Inter.
- Headline styled in `headline-md` (Plus Jakarta Sans).
- Bottom action shelf: Audio play button, quick bookmark, and native share.
- When an article is marked "BREAKING", the left card border transitions to a 3px solid `#FF4500` accent.

### Live Status Indicators & Badges
- **Live Pill**: Capsule badge with `#10B981` at 15% opacity background, `#10B981` text, enclosing a 6px solid emerald dot with a continuous CSS radial ping animation.
- **Breaking Flash**: Capsule badge with `#FF4500` solid fill, white bold tracked text, accompanied by an instantaneous pulse animation.

### Audio & Read-Out Chips
- Integrated listening chip for quick audio summaries: `#1E293B` background, containing an animated mini waveform icon, "Listen (45s)", and quick scrub capability.
- Active playback shifts the chip to `#FF6B35` outline with subtle text accent.

### Source Verification Tags
- Editorial verification chip composed of a muted slate container, monochrome outlet logo, source name, and a verified green shield badge (`#10B981`).
- Tap state expands a mini-popover revealing credibility score, correspondent attribution, and wire reference (e.g., PTI, ANI, Direct Field Correspondent).

### Buttons
- **Primary**: Solid `#FF4500`, `#FFFFFF` typography, 0.5rem radius, height 40px, bold font weight.
- **Secondary / Ghost**: `#1E293B` fill, `#F8FAFC` text, hover border `#334155`.
- **Stream Control Pill**: Circular 32px utility buttons with centered iconography for playback and rapid sorting.

### Pull-to-Refresh & Live Feed Banner
- Dynamic top pull trigger: Minimalist circular slate dial showing a spinning saffron-to-vermilion gradient indicator.
- Floating "↑ 3 New Updates" pill: Floats centered at the top viewport with `#FF4500` subtle border and a semi-translucent `#121826` glass backdrop, auto-dismissing as the user scrolls to top.