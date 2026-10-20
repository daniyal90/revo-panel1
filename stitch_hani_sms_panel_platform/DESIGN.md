---
name: Deep Slate Telemetry
colors:
  surface: '#0c1324'
  surface-dim: '#0c1324'
  surface-bright: '#33394c'
  surface-container-lowest: '#070d1f'
  surface-container-low: '#151b2d'
  surface-container: '#191f31'
  surface-container-high: '#23293c'
  surface-container-highest: '#2e3447'
  on-surface: '#dce1fb'
  on-surface-variant: '#bbcabf'
  inverse-surface: '#dce1fb'
  inverse-on-surface: '#2a3043'
  outline: '#86948a'
  outline-variant: '#3c4a42'
  surface-tint: '#4edea3'
  primary: '#4edea3'
  on-primary: '#003824'
  primary-container: '#10b981'
  on-primary-container: '#00422b'
  inverse-primary: '#006c49'
  secondary: '#4cd7f6'
  on-secondary: '#003640'
  secondary-container: '#03b5d3'
  on-secondary-container: '#00424e'
  tertiary: '#73d1ff'
  on-tertiary: '#003548'
  tertiary-container: '#38aede'
  on-tertiary-container: '#003e54'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#6ffbbe'
  primary-fixed-dim: '#4edea3'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#acedff'
  secondary-fixed-dim: '#4cd7f6'
  on-secondary-fixed: '#001f26'
  on-secondary-fixed-variant: '#004e5c'
  tertiary-fixed: '#c1e8ff'
  tertiary-fixed-dim: '#73d1ff'
  on-tertiary-fixed: '#001e2b'
  on-tertiary-fixed-variant: '#004d67'
  background: '#0c1324'
  on-background: '#dce1fb'
  surface-variant: '#2e3447'
  surface-panel: rgba(15, 23, 42, 0.60)
  panel-border: rgba(30, 41, 59, 0.80)
  emerald-active: '#059669'
  emerald-glow: rgba(16, 185, 129, 0.25)
  cyan-glow: rgba(6, 182, 212, 0.20)
  text-bright: '#f8fafc'
  text-muted: '#94a3b8'
  text-dim: '#475569'
  danger-red: '#f43f5e'
typography:
  display-hero:
    fontFamily: Space Grotesk
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Space Grotesk
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
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
  metric-lg:
    fontFamily: JetBrains Mono
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.02em
  metric-md:
    fontFamily: JetBrains Mono
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 24px
    letterSpacing: '0'
  code-badge:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.12em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.25rem
  gutter-lg: 1.75rem
  margin: 1rem
  margin-md: 1.5rem
  margin-lg: 2.5rem
  space-2xs: 0.125rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
---

## Brand & Style

This design system embodies a high-density, mission-critical fintech and telecom infrastructure aesthetic. Designed for operators, financial engineers, and network architects who require instantaneous situational awareness, the interface merges the precision of high-throughput data streams with a refined, tactile cyberpunk minimalism.

The visual style is **Glassmorphic Cyber-Minimalism**. It pairs ultra-deep slate foundations with glowing, calibrated neon emerald and cyan telemetry markers. Frosted translucent panels provide spatial isolation without obstructing global system awareness. The visual environment feels rigorous, low-latency, and high-frequency, deliberately avoiding ornamental skeuomorphism while leveraging crisp luminescence, fine-gauge borders, and monospaced diagnostic markers to communicate speed, integrity, and security.

## Colors

The palette revolves around deep optical clarity in persistent dark environments:

- **Neutral Foundation (`#020617`)**: Deepest slate canvas serving as the visual sink, minimizing eye strain across 24/7 network and trading operations.
- **Primary Emerald (`#10b981` / `#059669`)**: Indicates optimal status, active telecom routing, live transactions, positive rates, and high-priority confirmations.
- **Secondary Cyan (`#06b6d4`)**: Represents network handshakes, packets, auxiliary telemetric data, and secondary actions.
- **Tertiary Cyan-Sky (`#4fbff0`)**: Sourced from telecom signature tones, used for hyperlinked elements, external protocol indicators, and highlighted latency markers.
- **Glass Panel Surface (`rgba(15, 23, 42, 0.60)`)** paired with **Panel Border (`rgba(30, 41, 59, 0.80)`)**: Creates layered data strata while retaining background luminescent trace.

Gradients and glows should be reserved strictly for status telemetry, active focus rings, and high-consequence interactive states. Never apply full-bleed glowing fills to static content containers.

## Typography

The typographic hierarchy uses a deliberate three-tier arrangement:

1. **Space Grotesk (Headlines & Structural Anchors)**: Brings a precise, industrial character to top-level numbers and section titles without geometric distortions.
2. **Inter (UI Body & Narrative)**: Selected for its neutral legibility across dense lists, modals, table entries, and long descriptions.
3. **JetBrains Mono (Telemetry, Rates & API Metrics)**: Used for all numeric values, monetary balances, IP endpoints, hash digests, network throughput stats, and state tags. Tabular figures must remain strictly aligned across all dynamic ticker streams.

## Layout & Spacing

The interface is anchored by a structured 12-column fluid grid tailored for dashboard cockpits, low-latency command centers, and split transactional panes.

- **Desktop (1280px+)**: 12 columns, 1.75rem (`gutter-lg`) gutters, 2.5rem (`margin-lg`) margin. High-density grids can pack up to 4 data metrics per row or split 8/4 between real-time charts and live order/call feeds.
- **Tablet (768px - 1279px)**: 8 columns, 1.25rem (`gutter`) gutters, 1.5rem (`margin-md`) margin. Sidebars collapse to icon rails; metric sets wrap into 2x2 grids.
- **Mobile (< 768px)**: 4 columns, 0.75rem gutters, 1rem (`margin`) margin. Panels stack vertically; horizontal scrolls are used only for dense statistical tables with locked primary columns.

Layout rhythm strictly adheres to an 8px base grid, dropping down to a 4px sub-grid (`space-xs`) strictly for fine-grained metadata alignment and status tags.

## Elevation & Depth

Spatial separation relies on optical translucency, micro-borders, and calibrated back-glows rather than traditional drop shadows:

- **Base Layer (Canvas)**: Solid `#020617` deep slate with subtle radial noise or mesh gradients that emit muted cyan/emerald halos in peripheral zones.
- **Surface Level 1 (Panels & Shells)**: Translucent `rgba(15, 23, 42, 0.60)` with `backdrop-filter: blur(12px)` and a continuous hairline stroke of `rgba(30, 41, 59, 0.80)`.
- **Surface Level 2 (Floating Modals, Flyouts, Drawers)**: `rgba(15, 23, 42, 0.85)` with `backdrop-filter: blur(16px)` and edge highlights (`border: 1px solid rgba(51, 65, 85, 0.90)`).
- **Glow & Telemetry Highlights**: Critical metrics, active status lights, and focused inputs receive dynamic directional glows using dual box shadows:
  - Focused Primary: `0 0 0 1px #10b981, 0 0 16px rgba(16, 185, 129, 0.35)`.
  - Focused Secondary: `0 0 0 1px #06b6d4, 0 0 16px rgba(6, 182, 212, 0.30)`.
- **Elevation Shadows**: Where stacking over dense charts is necessary, use an ambient, non-tinted drop shadow: `0 20px 25px -5px rgba(0, 0, 0, 0.60), 0 8px 10px -6px rgba(0, 0, 0, 0.60)`.

## Shapes

The design system employs a disciplined, soft-cornered geometry (Level 1) to convey industrial rigor and technological precision. 

- **Containers, cards, and glass panels**: Use `0.5rem` (8px / `rounded-lg`).
- **Inputs, buttons, and system controls**: Use `0.25rem` (4px / `rounded-md`).
- **Pills and live indicators**: Reserve fully rounded pills (`9999px`) exclusively for telemetry status badges (e.g., `ONLINE`, `STANDBY`, `THROTTLED`) and compact filter switches.

## Components

### Buttons
- **Primary Action**: Emerald background (`#10b981`) with rich dark slate text (`#020617`), weight 600. On hover, background shifts to `#059669` with a diffuse glow (`box-shadow: 0 0 14px rgba(16, 185, 129, 0.40)`).
- **Secondary / Telemetry Action**: Translucent slate backdrop (`rgba(30, 41, 59, 0.50)`), border `1px solid rgba(6, 182, 212, 0.50)`, cyan text (`#06b6d4`). On hover, border turns solid cyan with a subtle inner glow.
- **Ghost Action**: Transparent background, text `#94a3b8`, hover text `#f8fafc` with subtle `rgba(255, 255, 255, 0.05)` fill.

### Cards & Translucent Panels
Constructed with `bg-slate-900/60`, `backdrop-blur-md`, and `border border-slate-800/80`. Top borders may feature an optional 1px gradient accent line running from transparent to `#10b981` or `#06b6d4` to mark high-priority data blocks.

### Input Fields & Search Bars
- Base: `rgba(2, 6, 23, 0.70)` fill, `1px solid rgba(51, 65, 85, 0.60)`, text `#f8fafc`, placeholder `#475569`.
- Monospace mode used for wallet addresses, API keys, and port numbers.
- Active / Focus: Border changes to `#10b981` with an outer ring of `0 0 0 2px rgba(16, 185, 129, 0.20)`.

### Chips & Telemetry Status Badges
Rendered using `label-caps` in `JetBrains Mono`. Includes a pulsing micro-orb (6px) on the left.
- **Live / Healthy**: `rgba(16, 185, 129, 0.12)` background, `#10b981` text, `1px solid rgba(16, 185, 129, 0.30)`.
- **Routing / Processing**: `rgba(6, 182, 212, 0.12)` background, `#06b6d4` text, `1px solid rgba(6, 182, 212, 0.30)`.
- **Degraded / High Latency**: `rgba(244, 63, 94, 0.12)` background, `#f43f5e` text, `1px solid rgba(244, 63, 94, 0.30)`.

### Checkboxes & Switches
- Checkbox: 16x16px square with 2px radius. Inactive border `rgba(51, 65, 85, 0.80)`. Checked state `#10b981` fill with `#020617` checkmark.
- Switch: Sleek 36x20px capsule track in dark slate (`#0f172a`), thumb 16x16px circle. When active, track turns `rgba(16, 185, 129, 0.30)` with an emerald thumb emitting a slight glow.

### Lists & Data Tables
Tables employ minimal horizontal borders (`1px solid rgba(30, 41, 59, 0.60)`) and transparent cell backgrounds. Row hover invokes a glass highlight (`rgba(255, 255, 255, 0.02)`). Column headers use `label-caps` typography in uppercase slate (`#64748b`). Numeric and timestamp cells must use `metric-md` or `JetBrains Mono` for tabular tracking.

### Additional Domain Components
- **API Metric Streamer**: Monospaced ticker component displaying endpoint, roundtrip latency (ms), HTTP response codes, and fluctuating sparklines.
- **Rate Matrix Card**: Split pane displaying currency pairs or bandwidth throughput with glowing micro-indicators reflecting positive (`#10b981`) or negative (`#f43f5e`) variances.