---
name: Kinetic Noir
colors:
  surface: '#0c1320'
  surface-dim: '#0c1320'
  surface-bright: '#323948'
  surface-container-lowest: '#070e1b'
  surface-container-low: '#151c29'
  surface-container: '#19202d'
  surface-container-high: '#232a38'
  surface-container-highest: '#2e3543'
  on-surface: '#dce2f5'
  on-surface-variant: '#e4beba'
  inverse-surface: '#dce2f5'
  inverse-on-surface: '#2a303f'
  outline: '#ab8986'
  outline-variant: '#5b403e'
  surface-tint: '#ffb3ae'
  primary: '#ffb3ae'
  on-primary: '#68000b'
  primary-container: '#ff5352'
  on-primary-container: '#5c0008'
  inverse-primary: '#ba1724'
  secondary: '#bcc7de'
  on-secondary: '#263143'
  secondary-container: '#3e495d'
  on-secondary-container: '#aeb9d0'
  tertiary: '#ffb3b1'
  on-tertiary: '#640a15'
  tertiary-container: '#e46b6c'
  on-tertiary-container: '#5b020f'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad7'
  primary-fixed-dim: '#ffb3ae'
  on-primary-fixed: '#410004'
  on-primary-fixed-variant: '#930014'
  secondary-fixed: '#d8e3fb'
  secondary-fixed-dim: '#bcc7de'
  on-secondary-fixed: '#111c2d'
  on-secondary-fixed-variant: '#3c475a'
  tertiary-fixed: '#ffdad8'
  tertiary-fixed-dim: '#ffb3b1'
  on-tertiary-fixed: '#410007'
  on-tertiary-fixed-variant: '#842328'
  background: '#0c1320'
  on-background: '#dce2f5'
  surface-variant: '#2e3543'
typography:
  headline-lg:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
  container-max: 1280px
---

## Brand & Style

The design system is built on a foundation of **Professional Vibrancy**, tailored for high-performance environments that require both urgency and precision. By pairing a deep, institutional dark navy with a high-chroma, energetic red, the UI evokes a sense of "active intelligence." 

The style sits at the intersection of **Corporate Modern** and **High-Contrast Bold**. It utilizes heavy whitespace—even in dark mode—to ensure that the vibrant red accents act as precise navigational beacons rather than overwhelming the user. The aesthetic is engineered to feel responsive, technical, and authoritative, making it ideal for data-heavy SaaS or fintech applications where critical actions must be unmistakable.

## Colors

The palette is dominated by **Carbon Navy (#0B121F)**, providing a sophisticated, low-fatigue backdrop. The primary brand color is **Vibrant Kinetic Red (#FF4D4D)**, a high-visibility hue specifically tuned to maintain a 4.5:1 contrast ratio against the dark navy background for accessibility.

- **Primary (Kinetic Red):** Reserved for primary calls to action, active navigation states, and critical alerts.
- **Secondary (Slate Blue):** Used for muted backgrounds and secondary UI containers to provide depth without competing with the red accents.
- **Surface:** A slightly lighter navy used to define cards and elevated panels.
- **Accent Tints:** Lightened versions of the red are used sparingly for hover states and subtle glows to indicate interactivity.

## Typography

This design system utilizes **Inter** exclusively to leverage its systematic, utilitarian character. The type scale is tight and functional, favoring legibility in dense information environments.

Headlines use bold weights and tighter letter-spacing to create a "locked-in," professional feel. Body text maintains generous line heights to ensure readability against the dark background. Labels are often set in uppercase with slight tracking increases to differentiate them from interactive body elements.

## Layout & Spacing

The layout follows a **Fluid Grid** model based on an 8px base unit. 

- **Desktop:** A 12-column grid with 24px gutters. Content is contained within a 1280px max-width wrapper for optimal scanning.
- **Tablet:** 8-column grid with 20px gutters.
- **Mobile:** 4-column grid with 16px margins. 

Spacing is used to create clear groupings; related elements use a 1-unit (8px) or 2-unit (16px) gap, while major sections are separated by 6-unit (48px) or 8-unit (64px) blocks.

## Elevation & Depth

In this dark-themed system, hierarchy is communicated through **Tonal Layering** and **Subtle Luminous Shadows**.

- **Base Level:** The deep Carbon Navy (#0B121F) background.
- **Level 1 (Cards/Panels):** Surface Navy (#161F30) with a 1px low-contrast border (#2D3748).
- **Level 2 (Dropdowns/Modals):** A lighter Slate (#1E293B) with a soft, 15% opacity black shadow and a subtle red top-border for primary modals.

Interactivity is signaled by "Kinetic Glows"—a very soft, low-spread outer shadow using the primary red color, applied only to active or focused components.

## Shapes

The design system employs a **Soft** shape language. Corners are rounded just enough to feel modern and approachable without losing the professional, "engineered" edge.

- **Standard Elements (Buttons, Inputs):** 0.25rem (4px) radius.
- **Container Elements (Cards, Modals):** 0.5rem (8px) radius.
- **Feedback Elements (Chips, Badges):** 1rem (16px) or fully pill-shaped to differentiate them from structural components.

## Components

### Buttons
- **Primary:** Solid Vibrant Red background with White text. Hover state shifts to a slightly darker red with a subtle red glow.
- **Secondary:** Outlined in Kinetic Red with Red text. On hover, the background fills with a 10% opacity red tint.
- **Ghost:** No border, Red text. Used for low-emphasis actions.

### Input Fields
- Dark background (#0B121F) with a thin slate border. On focus, the border transitions to Kinetic Red with a 2px outer glow (ring). Labels sit 4px above the input in `label-sm`.

### Cards
- Utilizes the "Surface" color with a subtle 1px border. Interactive cards lift slightly on hover (Y-offset -2px) and gain a more pronounced border.

### Chips & Badges
- Used for status indicators. Primary chips use a subtle red background (15% opacity) with bright red text to ensure they stand out against the navy background without being as heavy as a primary button.

### Focus Indicators
- All focus states must use a 2px Kinetic Red ring with a 2px offset to ensure high visibility for keyboard navigation.