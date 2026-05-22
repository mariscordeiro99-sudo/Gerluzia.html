---
name: Atelier Couture
colors:
  surface: '#faf9f7'
  surface-dim: '#dadad8'
  surface-bright: '#faf9f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f1'
  surface-container: '#efeeec'
  surface-container-high: '#e9e8e6'
  surface-container-highest: '#e3e2e0'
  on-surface: '#1a1c1b'
  on-surface-variant: '#554240'
  inverse-surface: '#2f3130'
  inverse-on-surface: '#f1f1ef'
  outline: '#88726f'
  outline-variant: '#dbc1bd'
  surface-tint: '#98453c'
  primary: '#410403'
  on-primary: '#ffffff'
  primary-container: '#5e1914'
  on-primary-container: '#e17e72'
  inverse-primary: '#ffb4aa'
  secondary: '#9b4338'
  on-secondary: '#ffffff'
  secondary-container: '#fd8f81'
  on-secondary-container: '#75271f'
  tertiary: '#3f0703'
  on-tertiary: '#ffffff'
  tertiary-container: '#5c1c13'
  on-tertiary-container: '#dd8071'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad5'
  primary-fixed-dim: '#ffb4aa'
  on-primary-fixed: '#3f0303'
  on-primary-fixed-variant: '#7a2e27'
  secondary-fixed: '#ffdad5'
  secondary-fixed-dim: '#ffb4a9'
  on-secondary-fixed: '#400101'
  on-secondary-fixed-variant: '#7c2c23'
  tertiary-fixed: '#ffdad4'
  tertiary-fixed-dim: '#ffb4a7'
  on-tertiary-fixed: '#3d0602'
  on-tertiary-fixed-variant: '#773026'
  background: '#faf9f7'
  on-background: '#1a1c1b'
  surface-variant: '#e3e2e0'
typography:
  h1:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  h2:
    fontFamily: Noto Serif
    fontSize: 36px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  h3:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: '0'
  body-lg:
    fontFamily: Work Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  body-md:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  label-caps:
    fontFamily: Work Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
  section-padding: 80px
---

## Brand & Style
The brand personality is rooted in the intersection of artisanal mastery and educational clarity. It targets a discerning clientele who values precision, slow-fashion ethics, and the heritage of professional tailoring. The UI evokes a sense of "approachable luxury"—it is sophisticated yet transparent and pedagogical, mirroring the process of a master seamstress explaining her craft.

The design style follows a **Modern Corporate** approach with **Minimalist** leanings. It prioritizes clarity and whitespace to reflect the precision of a needle's stitch. Visuals are structured and intentional, avoiding unnecessary ornamentation to allow the texture of fabrics and the quality of typography to take center stage.

## Colors
The palette is built on a foundation of sophisticated reds that represent the passion and depth of the textile arts. 
- **Primary (Wine):** Used for core branding, primary buttons, and deep structural elements.
- **Secondary (Burgundy/Terracotta):** Used for interactive states and emphasizing pedagogical callouts.
- **Tertiary (Dusty Rose/Terracotta):** Reserved for subtle highlights and decorative accents.
- **Neutrals:** An off-white (#F9F8F6) serves as the primary canvas to prevent the "starkness" of pure white, while light grays provide soft structural containment.
- **Contrast:** High-contrast dark charcoal is used for body text to ensure maximum readability and accessibility.

## Typography
This design system utilizes a classic Serif/Sans-Serif pairing to balance tradition with modernity. 
- **Headings:** Noto Serif conveys authority and the "literary" nature of professional patterns and instructions.
- **Body:** Work Sans provides a grounded, neutral, and highly legible experience for long-form content and service descriptions.
- **Labels:** Uppercase Work Sans with increased tracking is used for categories, metadata, and small UI hints to maintain a professional, organized aesthetic.

## Layout & Spacing
The layout employs a **Fixed Grid** system for desktop (12 columns) and a fluid 4-column system for mobile. The spacing rhythm is based on an 8px baseline to ensure consistent alignment of typographic elements.

Generous section padding (80px+) is used to create a "gallery" feel, allowing images of garments and sewing details to breathe. On mobile, margins are tightened to 16px to maximize the utility of the screen while maintaining a clear vertical flow. Elements should prioritize vertical stacking to facilitate the pedagogical nature of the content.

## Elevation & Depth
The system uses **Tonal Layers** rather than heavy shadows to signify depth. Backgrounds are primarily the off-white neutral, with "Surface" elements using subtle shifts in color or extremely thin 1px borders in light gray.

When depth is required for interactive elements like modals or floating action buttons, use **Ambient Shadows**: soft, highly diffused shadows with a slight warm tint (Wine color at 5% opacity) to prevent them from feeling "muddy." This maintains the clean, professional look while providing clear visual cues for hierarchy.

## Shapes
The shape language is **Soft** (roundedness 1). This choice balances the sharpness of a needle with the organic curves of fabric. 
- **Buttons and Inputs:** Use a 0.25rem corner radius for a precise, modern look.
- **Cards and Containers:** Use 0.5rem (rounded-lg) to provide a gentle container for photography.
- **Iconography:** Icons should feature consistent stroke weights and slight rounding on terminals to match the Work Sans typeface.

## Components
- **Buttons:** Primary buttons are solid Wine with white text. Secondary buttons use a Wine border with a transparent background. Text is centered and bold.
- **Input Fields:** Use "Ghost" style inputs with a 1px Light Gray bottom border that transforms into a Wine border upon focus. Labels remain visible at all times for pedagogical clarity.
- **Chips/Tags:** Small, pill-shaped tags used for "Service Type" (e.g., *Alterations*, *Bespoke*) using light Terracotta backgrounds with dark text.
- **Lists:** Bulleted lists should use a custom "stitch" icon or a simple 4px square in Wine color instead of standard dots.
- **Cards:** Use a minimal card design with a 1px border. Photography should be top-aligned with content following below, separated by ample whitespace.
- **Special Component - The "Step Indicator":** A custom vertical or horizontal progress bar for explaining the 4-step sewing process (Consultation, Measurement, Fitting, Delivery), using the Wine and Terracotta palette.