---
name: Modern Academic Synthesis
colors:
  surface: '#f8f9ff'
  surface-dim: '#ccdbf4'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e6eeff'
  surface-container-high: '#dde9ff'
  surface-container-highest: '#d5e3fd'
  on-surface: '#0d1c2f'
  on-surface-variant: '#444651'
  inverse-surface: '#233144'
  inverse-on-surface: '#ebf1ff'
  outline: '#757682'
  outline-variant: '#c5c5d3'
  surface-tint: '#4059aa'
  primary: '#00236f'
  on-primary: '#ffffff'
  primary-container: '#1e3a8a'
  on-primary-container: '#90a8ff'
  inverse-primary: '#b6c4ff'
  secondary: '#396477'
  on-secondary: '#ffffff'
  secondary-container: '#bae6fd'
  on-secondary-container: '#3d687c'
  tertiary: '#00311f'
  on-tertiary: '#ffffff'
  tertiary-container: '#004a31'
  on-tertiary-container: '#27c38a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b6c4ff'
  on-primary-fixed: '#00164e'
  on-primary-fixed-variant: '#264191'
  secondary-fixed: '#bee9ff'
  secondary-fixed-dim: '#a1cde3'
  on-secondary-fixed: '#001f2a'
  on-secondary-fixed-variant: '#1e4c5f'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#f8f9ff'
  on-background: '#0d1c2f'
  surface-variant: '#d5e3fd'
typography:
  headline-xl:
    fontFamily: Lexend
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Lexend
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Lexend
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Lexend
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 30px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
---

## Brand & Style

The design system is built on the "Modern Academic" aesthetic—a fusion of institutional credibility and contemporary digital agility. It targets students, researchers, and lifelong learners who require clarity in the face of information density. 

The style utilizes **Modernism** with a focus on high-clarity typography and generous whitespace, accented by **Glassmorphism** for interactive AI-driven layers. The interface must feel like a premium stationary set brought into a digital space: precise, tactile, and intentional. The emotional goal is "Confident Focus"—minimizing cognitive load while providing the tools for deep synthesis.

## Colors

The palette is anchored by **Sapphire Blue** (#1E3A8A), providing a foundation of academic authority and trust. This is balanced by **Sky Blue** (#BAE6FD) for highlights and secondary actions, and a **Mint Green** (#10B981) for success states and innovative AI indicators.

Backgrounds should primarily use absolute white for content areas, with **Slate-50** (#F8FAFC) used for layout scaffolding and sidebars to provide subtle structural contrast. Text utilizes **Slate-800** (#1E293B) to maintain high contrast without the harshness of pure black, ensuring long-form readability.

## Typography

This design system uses **Lexend** for all headings to leverage its research-backed readability and friendly, geometric character. It commands attention without being aggressive. 

**Inter** is used for body copy and UI labels to provide a systematic, neutral counterpoint. For educational content, `body-lg` is preferred to reduce eye strain. All body text should maintain a line-height of at least 1.6x to ensure legible reading rhythms during long sessions.

## Layout & Spacing

The design system employs a **Fixed Grid** on desktop (12 columns) and a **Fluid Grid** on mobile (4 columns). The spacing rhythm is based on an 8px base unit.

Generous margins (40px+) are used on desktop to create a "canvas" feel, centering the content and allowing the user to focus on synthesis tasks. Padding within content cards should be consistent at 24px (3 units) to ensure elements have room to breathe. On mobile, gutters shrink to 16px to maximize the available horizontal real estate for text.

## Elevation & Depth

Visual hierarchy is established using **Tonal Layers** supplemented by **Ambient Shadows**. 

1.  **Base Level:** White background for the main workspace.
2.  **Surface Level:** Light Gray (#F1F5F9) for navigation and sidebar elements.
3.  **Raised Level:** Content cards use a very soft shadow (0px 4px 12px, 5% opacity Slate) to appear slightly lifted.
4.  **Overlay Level:** AI-generated tooltips or floating action buttons use a subtle backdrop blur (8px) and a primary-tinted shadow to signify their dynamic nature.

Avoid heavy borders; use subtle 1px strokes in Slate-200 for containment when tonal shifts are insufficient.

## Shapes

The design system uses a **Rounded** (12px to 16px) language to soften the academic tone and make the platform feel accessible. 

- Standard components (inputs, buttons): 8px (`0.5rem`).
- Content cards and containers: 16px (`1rem`).
- Feature highlights or AI prompts: 24px (`1.5rem`) or fully pill-shaped.

This curvature should be consistent across all interactive elements to reinforce the "friendly student-focused" brand pillar.

## Components

### Buttons
Primary buttons use the Sapphire Blue background with white text. Hover states should transition to a slightly darker indigo with a 2px elevation increase. Secondary buttons use the Sky Blue tint with Sapphire text.

### Chips & Tags
Used for categorization and key terms in summaries. These should have a pill-shape and use low-saturation background tints (e.g., Sky Blue-100) with high-saturation text.

### Input Fields
Fields must have a clear 1px border. On focus, the border shifts to Sapphire Blue with a soft 3px outer glow (brand-primary at 10% opacity).

### Cards
Cards are the primary container for summaries and visualizations. They feature a 1px Slate-100 border and 16px corner radius. AI-generated cards may include a subtle top-border gradient using the Primary and Secondary colors.

### Visualizers
Charts and mind-map nodes should use the Secondary (Sky Blue) and Tertiary (Mint) colors to distinguish from the primary UI, maintaining a soft, rounded aesthetic even in data representation.