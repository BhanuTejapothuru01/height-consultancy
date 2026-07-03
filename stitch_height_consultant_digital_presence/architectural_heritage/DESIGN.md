---
name: Architectural Heritage
colors:
  surface: '#fcf9f3'
  surface-dim: '#dcdad4'
  surface-bright: '#fcf9f3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ed'
  surface-container: '#f0eee8'
  surface-container-high: '#ebe8e2'
  surface-container-highest: '#e5e2dc'
  on-surface: '#1c1c18'
  on-surface-variant: '#4f453b'
  inverse-surface: '#31312d'
  inverse-on-surface: '#f3f0ea'
  outline: '#817569'
  outline-variant: '#d3c4b6'
  surface-tint: '#7a582d'
  primary: '#7a582d'
  on-primary: '#ffffff'
  primary-container: '#b58d5d'
  on-primary-container: '#422701'
  inverse-primary: '#ebbf8b'
  secondary: '#645d58'
  on-secondary: '#ffffff'
  secondary-container: '#e8ded7'
  on-secondary-container: '#68615c'
  tertiary: '#43617d'
  on-tertiary: '#ffffff'
  tertiary-container: '#7997b5'
  on-tertiary-container: '#0c2f48'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffddb8'
  primary-fixed-dim: '#ebbf8b'
  on-primary-fixed: '#2a1700'
  on-primary-fixed-variant: '#5f4118'
  secondary-fixed: '#ebe1da'
  secondary-fixed-dim: '#cec5be'
  on-secondary-fixed: '#1f1b17'
  on-secondary-fixed-variant: '#4c4641'
  tertiary-fixed: '#cee5ff'
  tertiary-fixed-dim: '#abcaea'
  on-tertiary-fixed: '#001d32'
  on-tertiary-fixed-variant: '#2b4964'
  background: '#fcf9f3'
  on-background: '#1c1c18'
  surface-variant: '#e5e2dc'
typography:
  display-lg:
    fontFamily: EB Garamond
    fontSize: 64px
    fontWeight: '400'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: EB Garamond
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 48px
  headline-lg-mobile:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  headline-md:
    fontFamily: EB Garamond
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
spacing:
  unit: 8px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  max-width: 1440px
---

## Brand & Style

This design system embodies the intersection of classical architectural principles and modern digital luxury. The aesthetic is defined by "Warm Minimalism"—a shift away from sterile, cold whites toward a grounded, tactile palette inspired by natural stone, limestone, and aged parchment.

The target audience is discerning and values intentionality, permanence, and quiet luxury. The UI should evoke a sense of calm, intellectual rigor, and premium heritage.

**Design Style: Editorial Minimalism**
*   **Tactile Textures:** Use subtle noise grains and soft gradients to mimic the feel of physical materials.
*   **Structured Breathing Room:** Generous whitespace (or rather, "sand-space") that prioritizes content as if it were a high-end monograph.
*   **Architectural Precision:** A focus on alignment, proportion, and weight rather than decorative flourishes.

## Colors

The palette is anchored in a sophisticated "Sand" foundation, removing all instances of pure white to create a more immersive, cinematic atmosphere.

*   **Primary (#B58D5D):** Heritage Brown. Used for key calls to action, brand identifiers, and active states. It suggests aged brass or refined leather.
*   **Surface (#F2EFE9):** The primary canvas. A muted, architectural light parchment that reduces eye strain and adds warmth.
*   **Surface Variant (#E8E3D9):** Used for depth. These areas are slightly darker and more saturated than the base surface, creating a "carved" or layered effect rather than an "elevated" one.
*   **Secondary (#4A443F):** Deep Umber. Used for primary text and high-contrast iconography.
*   **Border (#D6CFC1):** A structural color for subtle dividers that maintains a low-contrast, harmonious feel.

## Typography

The typographic system pairs the intellectual, classical elegance of **EB Garamond** with the technical precision of **Hanken Grotesk**.

*   **Serif (EB Garamond):** Used for all storytelling elements, headlines, and pull quotes. It should feel editorial and expansive.
*   **Sans-Serif (Hanken Grotesk):** Used for utility, navigation, and long-form body text. Its clean, sharp metrics provide a modern counterpoint to the serif's tradition.
*   **Styling Note:** Labels and small metadata should always use uppercase with generous letter spacing (0.05em) to maintain a premium, architectural feel.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop to preserve intentional composition and "architectural" proportions.

*   **Desktop:** 12-column grid with 64px outer margins and 24px gutters. Elements should often span 6 or 8 columns to create centered, monograph-style reading experiences.
*   **Mobile:** 4-column fluid grid with 20px margins.
*   **Rhythm:** Vertical rhythm is strictly enforced in 8px increments. Use large padding blocks (80px, 120px) to separate sections, reinforcing the "Cinema" aspect of the brand through deliberate pacing.

## Elevation & Depth

This design system avoids traditional drop shadows in favor of **Tonal Layering** and **Structural Outlines**.

*   **The "Carved" Method:** Depth is achieved by placing elements on a slightly darker surface (`#E8E3D9`) rather than a lighter one. This mimics the appearance of elements being inset or carved into stone.
*   **Low-Contrast Outlines:** Use 1px borders in `#D6CFC1` to define boundaries. 
*   **Glassmorphism:** Reserved exclusively for navigation overlays. Use a backdrop blur of 20px with a 60% opacity fill of the surface color (`#F2EFE9`).

## Shapes

The shape language is strictly **Sharp (0px)**. 

Sharp corners convey the precision of architectural blueprints and the crisp edges of cut stone. This lack of rounding differentiates the system from consumer-grade software and aligns it with luxury publishing. Circular elements are used only for profile imagery or specific icon backdrops to provide a singular point of organic contrast.

## Components

*   **Buttons:** Primary buttons use the Heritage Brown (`#B58D5D`) with white text and sharp corners. Secondary buttons use a "Ghost" style: 1px border of the Secondary color with no fill.
*   **Cards:** Do not use shadows. Define cards using a subtle background shift to `#E8E3D9` or a thin `#D6CFC1` border.
*   **Inputs:** Bottom-border only (1px). When focused, the border transitions to Heritage Brown.
*   **Chips:** Small, all-caps Hanken Grotesk labels inside a box with a 1px border. No background fill.
*   **Lists:** Separated by thin, full-width horizontal rules in `#D6CFC1`. Use generous vertical padding (24px+) between list items.
*   **Media:** All imagery should have a slight sepia or desaturated filter to harmonize with the architectural sand palette.