---
name: Conexão Viva
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#5c3f3d'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#916f6b'
  outline-variant: '#e6bdb9'
  surface-tint: '#bf0217'
  primary: '#bb0016'
  on-primary: '#ffffff'
  primary-container: '#e1272b'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb4ac'
  secondary: '#5f5e5f'
  on-secondary: '#ffffff'
  secondary-container: '#e2dfe0'
  on-secondary-container: '#636263'
  tertiary: '#545d65'
  on-tertiary: '#ffffff'
  tertiary-container: '#6d767e'
  on-tertiary-container: '#fcfcff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb4ac'
  on-primary-fixed: '#410003'
  on-primary-fixed-variant: '#93000e'
  secondary-fixed: '#e5e2e3'
  secondary-fixed-dim: '#c8c6c7'
  on-secondary-fixed: '#1b1b1c'
  on-secondary-fixed-variant: '#474647'
  tertiary-fixed: '#dbe4ed'
  tertiary-fixed-dim: '#bfc8d0'
  on-tertiary-fixed: '#141d23'
  on-tertiary-fixed-variant: '#3f484f'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.2'
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
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style

The design system is built to position the brand as a modern, high-performance telecommunications leader in the Brazilian market. The visual language balances **technological precision** with **human accessibility**, ensuring that advanced fiber-optic technology feels warm and integrated into daily life.

The aesthetic follows a **Corporate / Modern** style with a strong emphasis on **Clean Minimalism**. It prioritizes vast whitespace to reduce cognitive load and uses high-impact "Vibrant Red" accents to drive action and brand recognition. The emotional response should be one of reliability, speed, and seamless connectivity.

## Colors

This color palette is designed for high legibility and brand impact. The **Vibrant Red** (extracted from the logo) is reserved for primary actions, critical brand elements, and key highlights.

- **Primary (Vibrant Red):** Used for CTA buttons, primary icons, and active states.
- **Secondary (Deep Black):** Used exclusively for typography and primary brand headings to ensure maximum contrast.
- **Tertiary (Medium Grey):** Used for secondary information, borders, and UI decorative elements.
- **Background (Soft Grey):** A specifically cool-toned `#F8F9FA` to provide a softer, more premium alternative to pure white for page sections.

## Typography

The typography strategy utilizes two distinct sans-serif families to balance character and utility. **Plus Jakarta Sans** provides a modern, slightly rounded geometric feel for headlines, evoking a friendly yet professional "tech" vibe. **Inter** is used for all functional body text and labels to ensure world-class legibility across all digital interfaces.

Headlines should use tight letter-spacing to appear more impactful, while body text maintains standard spacing for comfortable long-form reading.

## Layout & Spacing

This design system employs a **Fluid Grid** model based on a 12-column structure for desktop and a 4-column structure for mobile. A 8px base unit (linear scale) governs all padding and margin decisions to ensure mathematical harmony.

- **Desktop:** 12 columns, 24px gutters, and 64px side margins. 
- **Tablet:** 8 columns, 20px gutters, and 32px side margins.
- **Mobile:** 4 columns, 16px gutters, and 20px side margins.

Section vertical spacing should be generous (80px to 120px) to maintain the "Clean & Accessible" brand pillar, allowing content to breathe and reducing visual noise.

## Elevation & Depth

Hierarchy is established through **Ambient Shadows** and **Tonal Layers**. Instead of harsh borders, surfaces are defined by subtle depth.

- **Level 0 (Floor):** Background color (`#F8F9FA`).
- **Level 1 (Cards/Containers):** White surfaces with a soft, diffused shadow: `0px 4px 20px rgba(0, 0, 0, 0.05)`.
- **Level 2 (Interactive/Hover):** Lifted state with a more pronounced shadow: `0px 12px 32px rgba(0, 0, 0, 0.08)`.

Avoid inner shadows or heavy bevels. The "Glassmorphism" effect may be used sparingly on top-level navigation bars (20px backdrop blur, 80% white opacity) to maintain context while scrolling.

## Shapes

The shape language is defined by a **Rounded** philosophy. Large corner radii are used to soften the "tech" aspect of the brand and make the UI feel more approachable and modern.

- **Interactive Elements (Buttons/Inputs):** 8px (0.5rem) radius.
- **Information Containers (Cards):** 24px (1.5rem) radius.
- **Decorative Elements (Images/Tags):** 16px (1rem) radius or fully pill-shaped for tags.

## Components

### Buttons
Primary buttons are solid **Vibrant Red** with White text. The hover state should involve a slight darkening of the red or a scale-up of 2%. Secondary buttons should use a Ghost style (Red outline, Red text) or subtle Grey backgrounds.

### Cards
Cards are the primary container. They must feature a 24px border-radius, white background, and the Level 1 shadow. Padding inside cards should be a minimum of 32px to maintain "whitespace" requirements.

### Input Fields
Inputs use a light grey background (`#F1F3F5`) with no border in the default state, transitioning to a 2px Vibrant Red border on focus.

### Chips & Tags
Used for "Novidade" or plan features. These should be pill-shaped with high-contrast backgrounds (e.g., bright green for "New" or primary red for "Sale").

### Iconography
Icons must be "Line" style with a 2px stroke width. They should be consistently colored in either Vibrant Red (to highlight features) or Deep Black (for navigation).

### Imagery
Use lifestyle photography with high brightness and natural saturation. Focus on people in modern, sunlit Brazilian homes, highlighting moments of connectivity (video calls, gaming, streaming).
