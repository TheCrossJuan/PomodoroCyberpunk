---
name: Cyberware Terminal
colors:
  surface: '#121317'
  surface-dim: '#121317'
  surface-bright: '#38393e'
  surface-container-lowest: '#0d0e12'
  surface-container-low: '#1a1b20'
  surface-container: '#1f1f24'
  surface-container-high: '#292a2e'
  surface-container-highest: '#343439'
  on-surface: '#e3e2e8'
  on-surface-variant: '#e9bcb6'
  inverse-surface: '#e3e2e8'
  inverse-on-surface: '#2f3035'
  outline: '#af8782'
  outline-variant: '#5e3f3b'
  surface-tint: '#ffb4aa'
  primary: '#ffb4aa'
  on-primary: '#690003'
  primary-container: '#e50914'
  on-primary-container: '#fff7f6'
  inverse-primary: '#c0000c'
  secondary: '#a8c8ff'
  on-secondary: '#003061'
  secondary-container: '#3491ff'
  on-secondary-container: '#002955'
  tertiary: '#ffba26'
  on-tertiary: '#422d00'
  tertiary-container: '#966a00'
  on-tertiary-container: '#fff7f0'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad5'
  primary-fixed-dim: '#ffb4aa'
  on-primary-fixed: '#410001'
  on-primary-fixed-variant: '#930007'
  secondary-fixed: '#d5e3ff'
  secondary-fixed-dim: '#a8c8ff'
  on-secondary-fixed: '#001b3c'
  on-secondary-fixed-variant: '#004689'
  tertiary-fixed: '#ffdea9'
  tertiary-fixed-dim: '#ffba26'
  on-tertiary-fixed: '#271900'
  on-tertiary-fixed-variant: '#5e4100'
  background: '#121317'
  on-background: '#e3e2e8'
  surface-variant: '#343439'
  focus-alert: '#e50914'
  focus-hover: '#ff0f1a'
  focus-highlight: '#ff4d4d'
  focus-glow: rgba(229, 9, 20, 0.25)
  break-cyan: '#0088ff'
  break-hover: '#00a2ff'
  break-highlight: '#4da6ff'
  break-glow: rgba(0, 136, 255, 0.25)
  terminal-void: '#0b0c10'
  terminal-obsidian: '#131318'
  terminal-surface: '#18181b'
  trace-gold: '#ffb700'
  trace-gold-muted: '#2a2b36'
  bus-border: rgba(255, 255, 255, 0.12)
typography:
  display-timer:
    fontFamily: Space Mono
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -1.5px
  display-timer-mobile:
    fontFamily: Space Mono
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -1px
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.5px
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: 0px
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: 0px
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: 0.5px
  body-lg:
    fontFamily: Space Mono
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: 0px
  body-md:
    fontFamily: Space Mono
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0px
  body-sm:
    fontFamily: Space Mono
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.2px
  label-lg:
    fontFamily: Space Mono
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 18px
    letterSpacing: 1.5px
  label-md:
    fontFamily: Space Mono
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 1.5px
  label-sm:
    fontFamily: Space Mono
    fontSize: 9px
    fontWeight: '700'
    lineHeight: 12px
    letterSpacing: 2px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-tablet: 1.5rem
  margin-desktop: 2.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

The design system establishes a high-performance, combat-ready digital HUD architecture designed for deep cognitive endurance, technical execution, and tactical temporal pacing. Built directly upon the functional dichotomy of Pomodoro time-boxing, the system treats time tracking not as an ambient passive clock, but as an active cyberdeck telemetry console.

The audience consists of cyber-architects, software developers, technical operators, and night-shift power users operating within terminal environments who require intense visual clarity, low optical fatigue, and instantaneous cognitive mode shifts.

The aesthetic fuses **Military Cyberpunk HUD** with **Brutalist Terminal Geometries**:
- **Dual Operational Modalities:** Instant structural shift between high-arousal, alert-tier Focus state (combat performance, overclocked red neon telemetry) and low-arousal, thermal-venting Break state (bioluminescent electric blue, cryo-circuit recovery).
- **Absolute Edges:** Radical zero-radius framework across all frames, inputs, progress bars, and modal chassis.
- **Hardware Telemetry:** Direct data exposure, alphanumeric index stencils, terminal block prompt cursors, and PCB bus trace demarcations.

## Colors

The color system operates on an absolute dark substrate, simulating cold obsidian chassis and conductive motherboard masks punctuated by radiant phosphor bus lines.

### Functional Modality Logic
- **Primary / Focus Mode (`#e50914` - Neon Alert Crimson):** Active during focus work cycles. Dictates the dynamic accent tokens: primary button fills, countdown rings, active tracking indicators, and critical telemetry highlights. Supported by `#ff0f1a` on hover and deep resonant glow emissions (`rgba(229, 9, 20, 0.25)`).
- **Secondary / Break Mode (`#0088ff` - Cryo-Electric Blue):** Engaged automatically during rest and cool-down cycles. Replaces the primary accent dynamically across the entire UI canvas—calming optical arousal while maintaining high-contrast HUD legibility. Supported by hover state `#00a2ff` and coolant bio-luminescent emissions (`rgba(0, 136, 255, 0.25)`).
- **Tertiary (`#ffb700` - Industrial Gold):** Signifies persistent system locks, circuit test pads, audio waveform status, and hardware status pins.
- **Neutral Foundation (`#0b0c10` / `#131318` - Terminal Obsidian):** Ultra-dark, non-reflective ground plane that eliminates peripheral eye strain and allows colored spectral signals to pop with clinical authority.

## Typography

The typography couples the aggressive, technical proportion of **Space Grotesk** with the surgical tabular precision of **Space Mono**.

- **Display & Numerical Chronometers (`Space Mono`):** The primary timer readout uses `Space Mono` set to `display-timer` with strict `font-variant-numeric: tabular-nums`. Monospacing prevents mechanical jitter or layout displacement as digits shift during active execution.
- **Section Headers & Deck Titles (`Space Grotesk`):** Provides punchy, high-impact titles with structural legibility. Used on main chassis labels, dialog modals, and high-level section identifiers.
- **Data Channels, Telemetry, and Interactive Controls (`Space Mono`):** Every button action, task item, audio attribution, and parameter field relies on `Space Mono` to preserve the diagnostic cyberdeck identity.
- **Micro-Annotations:** Labels, mode indicator kickers, and hardware indices utilize full uppercase transforms with wide tracking (`1.5px` to `2.0px`), simulating silkscreen markings stenciled directly onto circuit motherboards.

## Layout & Spacing

Layouts follow a modular hardware matrix inspired by rack-mounted servers and cyberdeck tactical monitors. Every view conforms to strict horizontal and vertical alignments with zero arbitrary floating distances.

### Grid Architecture
- **Mobile (< 768px):** 4-column layout with 16px (`1rem`) outer margins and 16px gutters. Single-stack centered chronometer card (max-width 480px) with sliding bottom drawer overlays for tasks and audio sub-routines.
- **Tablet (768px – 1199px):** 8-column layout with 24px (`1.5rem`) outer margins and 24px gutters. Secondary monitors (task queue, YouTube ambient audio stream) dock into flanking peripheral brackets.
- **Desktop (≥ 1200px):** 12-column layout with 40px (`2.5rem`) outer margins. Supports side-by-side terminal operations: persistent HUD tasks panel docked at 320px fixed width, primary chronometer pod centered at 480px, and auxiliary audio telemetry docked into lower status margins.

### Spacing Cadence
Spacing follows an exact 4px/8px mathematical rhythm (`0.25rem` intervals). Negative space serves as electrical separation—delineating data buses and container perimeters rather than creating empty whitespace.

## Elevation & Depth

This design system avoids soft atmospheric drop shadows in favor of **hardware layering, phosphor ionization fields, and conductive high-contrast borders**.

### Structural Tiers
1. **Chassis Substrate (Level 0):** Pure dark ground (`#0b0c10` / `#131318`). Underlaid with low-opacity PCB circuit bus lines, 45-degree angle trace guides, and faint grid coordinates (`rgba(255, 255, 255, 0.03)`).
2. **Standard Enclosures (Level 1):** Semi-translucent panels (`rgba(18, 18, 22, 0.85)`) backed by `backdrop-filter: blur(12px)`. Enclosed by sharp 1px hairline borders (`rgba(255, 255, 255, 0.1)`).
3. **Active Telemetry Unit (Level 2 - Chronometer Card):** Primary operational focus pod. Retains a 1px solid accent border matching the active mode (`#e50914` in Focus, `#0088ff` in Break), backed by dual-layer edge emission: `0 10px 40px rgba(0, 0, 0, 0.8), 0 0 20px var(--accent-glow)`.
4. **Command Drawers & Overlays (Level 3):** Floating task panels (`rgba(24, 24, 27, 0.95)`) and system modal alerts (`#18181b`). Outlined with high-contrast borders and localized phosphor glow fields (`0 0 24px var(--accent-glow)`).

### Dynamic Mode Glow
Every interactive container automatically switches glow properties via the dynamic mode token `--accent-glow`:
- **Focus Cycle:** Emits an intense crimson warning bloom (`rgba(229, 9, 20, 0.25)`).
- **Break Cycle:** Emits a cryogenic blue bio-radiation bloom (`rgba(0, 136, 255, 0.25)`).

## Shapes

The design system enforces an absolute, uncompromising **Zero-Radius Paradigm (`roundedness: 0`)**. No rounded corners, soft radius pills, or squircle smoothing are permitted on any interface element.

- **Orthogonal Geometry:** Every button, card, modal, badge, and input field forms an exact 90-degree rectangle.
- **Chamfered HUD Corners:** Terminal chassis, floating modules, and primary actuators may employ 45-degree corner bevels via `clip-path: polygon(8px 0%, calc(100% - 8px) 0%, 100% 8px, 100% calc(100% - 8px), calc(100% - 8px) 100%, 8px 100%, 0% calc(100% - 8px), 0% 8px)`.
- **Chronometer Ring Geometry:** Radial progress monitors maintain circular SVG stroke tracks for temporal reading, but are locked within hard, square chassis containing corner-bracket registration marks (`+`, `[`, `]`).
- **Corner Brackets:** Interactive containers feature 1px geometric corner indices to signify structural hardware interlocking.

## Components

### Actuator Buttons
- **Primary Actuator (`.btn-primary`):** Zero-radius sharp block. Filled completely with the active dynamic accent (`var(--accent-color)`). Text rendered in `Space Mono` bold uppercase (`label-lg`), colored in high-contrast `#ffffff` or dark `#0b0c10`. Hover state triggers color acceleration (`var(--accent-hover)`) and a radiant phosphor bloom (`box-shadow: 0 0 16px var(--accent-glow)`). Active state applies a `transform: translate(1px, 1px)`.
- **Secondary / Ghost Actuator (`.btn-outline`):** Transparent background, 1px solid `rgba(255, 255, 255, 0.2)`. On hover, the border snaps directly to `var(--accent-color)` with matching text tint and `background: rgba(255, 255, 255, 0.05)`.
- **Square Utility Actuators (`.nav-arrow`, `.audio-btn`):** Shifted from circular primitives to sharp 40px × 40px squares. Center-aligned technical glyphs (`‹`, `›`, `▶`, `⏸`) with 1px border.

### Chronometer HUD Pod
- **Housing:** 480px maximum width, zero-radius glassmorphic module (`rgba(18, 18, 22, 0.85)`).
- **Radial Progress Track:** SVG circular ring with `stroke-width: 8`, segmented line cap, and dynamic stroke color binding (`var(--accent-color)`). Center displays time digits in `display-timer` (`Space Mono`).
- **Telemetry Sub-Labels:** Uppercase mode indicator (`// SYSTEM_ENGAGED: FOCUS` or `// SYSTEM_STANDBY: COOLDOWN`) positioned above digits in `label-sm` with letter spacing `2px`.

### Hardware Inputs & Console Controls
- **Terminal Inputs:** Recessed obsidian boxes (`#0b0c10`) with sharp 1px border `rgba(255, 255, 255, 0.15)`. Text in `Space Mono` (`body-md`), colored `#ffffff`.
- **Focus Interaction:** Focus event shifts border to `1px solid var(--accent-color)` and applies an internal glow `box-shadow: inset 0 0 8px var(--accent-glow)`. Preceded by terminal cursor prompts (`> `).

### Telemetry Drawers & Modals
- **Task Panel Drawer:** Docked or sliding panel with sharp zero-radius geometry, 1px solid border `var(--accent-glow)`, and dark obsidian surface (`rgba(24, 24, 27, 0.95)`).
- **Task Item Strips:** 8px vertical padding, separated by 1px hairline dividers (`rgba(255, 255, 255, 0.05)`). Task removal trigger (`✕`) renders in `Space Mono` and flashes dynamically into `var(--accent-light)` on hover.

### Status Indicators & Bus Dividers
- **Status Micro-Badges:** Rectangular 6px × 6px square status LEDs with pulsing animation (1.5s interval), coupled with `label-sm` uppercase readouts.
- **Divider Traces:** 1px horizontal conduits (`rgba(255, 255, 255, 0.08)`) with occasional $45^\circ$ diagonal routing notches, grounding the operational terminal aesthetic.