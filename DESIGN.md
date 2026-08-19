---
name: Kinetic Precision
colors:
  surface: '#f9f9fb'
  surface-dim: '#d9dadc'
  surface-bright: '#f9f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f5'
  surface-container: '#eeeef0'
  surface-container-high: '#e8e8ea'
  surface-container-highest: '#e2e2e4'
  on-surface: '#1a1c1d'
  on-surface-variant: '#4c4546'
  inverse-surface: '#2f3132'
  inverse-on-surface: '#f0f0f2'
  outline: '#7e7576'
  outline-variant: '#cfc4c5'
  surface-tint: '#5e5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1b1b1b'
  on-primary-container: '#848484'
  inverse-primary: '#c6c6c6'
  secondary: '#5e5e63'
  on-secondary: '#ffffff'
  secondary-container: '#e0dfe4'
  on-secondary-container: '#626267'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#001b3e'
  on-tertiary-container: '#3a83ea'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2e2e2'
  primary-fixed-dim: '#c6c6c6'
  on-primary-fixed: '#1b1b1b'
  on-primary-fixed-variant: '#474747'
  secondary-fixed: '#e3e2e7'
  secondary-fixed-dim: '#c7c6cb'
  on-secondary-fixed: '#1a1b1f'
  on-secondary-fixed-variant: '#46464b'
  tertiary-fixed: '#d7e3ff'
  tertiary-fixed-dim: '#aac7ff'
  on-tertiary-fixed: '#001b3e'
  on-tertiary-fixed-variant: '#00458e'
  background: '#f9f9fb'
  on-background: '#1a1c1d'
  surface-variant: '#e2e2e4'
  metallic-silver: '#D2D2D7'
  success-green: '#28CD41'
  warning-amber: '#FF9F0A'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 60px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.2'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.05em
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
  margin-desktop: 80px
  margin-mobile: 20px
  max-width: 1440px
---

## Brand & Style
The design system is built for a high-end smartphone retail experience where the product is the hero. The brand personality is "Quiet Authority"—it is confident, precise, and sophisticated. It avoids the clutter of traditional e-commerce in favor of a **Minimalist** and **Corporate Modern** aesthetic.

The target audience consists of tech enthusiasts and professionals who value transparency (e.g., battery health) and premium craftsmanship. The emotional response should be one of "Digital Calm"—a frictionless, high-trust environment where white space facilitates focus and metallic accents signify quality.

## Colors
The palette is rooted in a "Studio White" environment to make product photography pop. 
- **Primary:** Deep Black (`#000000`) for high-contrast typography and primary actions.
- **Secondary:** A sophisticated Apple-inspired gray (`#86868B`) for secondary text and icons.
- **Tertiary:** A refined "Tech Blue" (`#0066CC`) used sparingly for interactive links or status indicators.
- **Neutral:** A very light gray (`#F5F5F7`) for section backgrounds to create subtle "containment" without harsh lines.

Use **Metallic Silver** for borders and dividers to evoke the physical materials of the smartphones.

## Typography
This design system utilizes **Inter** for its neutral, highly legible, and premium "San Francisco-esque" feel. To emphasize the technical specifications of the devices (Battery Health, Storage), **JetBrains Mono** is introduced as a secondary label font to provide a "spec-sheet" technical aesthetic.

Headlines should use tight tracking (letter-spacing) to feel modern and impactful. Body text remains open and airy to ensure readability during long browsing sessions.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy on desktop to maintain a "Gallery" feel, centering the content within a 1440px container. 

- **Desktop:** 12-column grid with 24px gutters. Wide margins (80px) create an expensive, editorial feel.
- **Mobile:** 4-column grid with 16px gutters and 20px margins.
- **Rhythm:** All spacing must be multiples of 8px. Use generous vertical padding between sections (80px–120px) to prevent the interface from feeling "salesy" or cluttered.

## Elevation & Depth
Depth is conveyed through **Tonal Layers** and **Low-Contrast Outlines** rather than heavy shadows.
- **Surface 1:** Pure White (`#FFFFFF`) - The main background.
- **Surface 2:** Light Neutral (`#F5F5F7`) - Used for card containers or background shifts to denote different functional areas.
- **Borders:** Use 1px solid `metallic-silver` for cards and inputs. 

Avoid drop shadows except for "Floating" elements like high-end modals or sticky navigation bars, where a very large, 2% opacity black blur should be used to imply a soft ambient lift.

## Shapes
The shape language is **Soft (0.25rem)**. This mimics the precise, tight corner radii of modern hardware components. While a "Pill" shape may be used exclusively for "Add to Cart" buttons to make them tactile and inviting, all structural elements (Cards, Input fields, Product images) should maintain the soft, professional corner radius to look structured and engineered.

## Components
### Product Cards
Cards are the core of this design system. They feature a `Surface 1` background with a subtle `metallic-silver` border. 
- **Tech Badges:** Battery health (e.g., "98% BH") and Storage (e.g., "256GB") should be displayed in `label-mono` inside small, light-gray pill containers at the top of the card.
- **Color Swatches:** Small, circular tokens representing the available phone colors should appear below the product name.

### Buttons
- **Primary:** Solid Black background with White `body-md` text. No border. High-impact.
- **Secondary:** Transparent background with a `metallic-silver` border.
- **Interaction:** On hover, primary buttons should shift to a dark charcoal; secondary buttons should fill with a subtle `neutral-color` tint.

### Input Fields
Minimalist line-based inputs or very light-gray troughs. Labels should always be visible (never just placeholder text) using `label-mono` for a technical feel.

### Status Indicators
Battery health percentages above 90% use `success-green`. Below 85% use `warning-amber`. This transparency builds immediate trust with the high-end consumer.