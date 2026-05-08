---
name: Cafe Journal Aesthetic
colors:
  surface: '#fdf9f3'
  surface-dim: '#dddad4'
  surface-bright: '#fdf9f3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3ed'
  surface-container: '#f1ede7'
  surface-container-high: '#ebe8e2'
  surface-container-highest: '#e6e2dc'
  on-surface: '#1c1c18'
  on-surface-variant: '#504446'
  inverse-surface: '#31302d'
  inverse-on-surface: '#f4f0ea'
  outline: '#827376'
  outline-variant: '#d4c2c5'
  surface-tint: '#7d525f'
  primary: '#7d525f'
  on-primary: '#ffffff'
  primary-container: '#d9a5b3'
  on-primary-container: '#603a46'
  inverse-primary: '#eeb8c7'
  secondary: '#675d4e'
  on-secondary: '#ffffff'
  secondary-container: '#efe0cd'
  on-secondary-container: '#6d6354'
  tertiary: '#6b5b54'
  on-tertiary: '#ffffff'
  tertiary-container: '#c3afa7'
  on-tertiary-container: '#51423c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9e2'
  primary-fixed-dim: '#eeb8c7'
  on-primary-fixed: '#30111c'
  on-primary-fixed-variant: '#623b47'
  secondary-fixed: '#efe0cd'
  secondary-fixed-dim: '#d2c4b2'
  on-secondary-fixed: '#221a0f'
  on-secondary-fixed-variant: '#4f4538'
  tertiary-fixed: '#f4ded5'
  tertiary-fixed-dim: '#d7c2ba'
  on-tertiary-fixed: '#251914'
  on-tertiary-fixed-variant: '#52443e'
  background: '#fdf9f3'
  on-background: '#1c1c18'
  surface-variant: '#e6e2dc'
typography:
  display:
    fontFamily: EB Garamond
    fontSize: 48px
    fontWeight: '500'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  h1:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.2'
  h2:
    fontFamily: EB Garamond
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.3'
  h3:
    fontFamily: EB Garamond
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Plus Jakarta Sans
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
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  gutter: 20px
  margin: 32px
---

## Brand & Style

This design system draws inspiration from the "slow living" culture of Seoul and Tokyo cafes. The brand personality is cozy, academic, and nostalgic—tailored for international university students who value both productivity and aesthetic comfort. 

The visual style is a **Scrapbook/Tactile** evolution of minimalism. It avoids the sterile coldness of typical SaaS products in favor of an "editorial scrapbook" feel. Key characteristics include:
- **Layered Composition:** Elements appear as if they are pinned or taped onto a surface.
- **Organic Cues:** Subtle paper textures, sticker-like badges, and hand-drawn accents.
- **Pinterest-Inspired Layout:** Masonry-style grids and varied card aspect ratios to encourage exploration.
- **Soft Modernism:** Combining Gen Z trends (high-quality curation) with classic editorial typography.

## Colors

The palette is rooted in low-saturation, warm tones that mimic the environment of a boutique coffee shop.

- **Primary (Rosewater):** A muted pastel pink used for key actions and highlights.
- **Secondary (Clotted Cream):** A soft, buttery off-white used for secondary containers and surface differentiation.
- **Tertiary (Roasted Mocha):** A soft brown used for high-contrast text and grounding elements.
- **Neutral (Rice Paper):** The primary background color, warmer and softer than pure white to reduce eye strain during late-night study sessions.
- **Success/Warning/Error:** These should be desaturated versions of green, amber, and red to maintain the "muted" aesthetic.

## Typography

The typography pairs a romantic, intellectual serif with a friendly, modern sans-serif.

- **Headings:** Use **EB Garamond**. It provides a literary, "dark academia" feel. Use italic variants for emphasis to enhance the editorial look.
- **Body & Interface:** Use **Plus Jakarta Sans**. Its slightly rounded terminals complement the soft UI shapes while maintaining high legibility for student-heavy content.
- **Formatting:** Keep line heights generous (1.6x) for body text to mimic the airy feel of a lifestyle magazine.

## Layout & Spacing

This design system employs a **Fixed-Fluid Hybrid** grid that favors whitespace over density.

- **Grid Model:** Use a 12-column grid for desktop, but prioritize a **Masonry Layout** for content feeds to mimic a Pinterest mood board.
- **Rhythm:** Spacing should be intentional and wide. Avoid crowding elements; use `xl` spacing between major sections to allow the design to "breathe."
- **Asymmetry:** Occasionally break the grid with "sticker" elements (badges or small images) that overlap margins by 8-12px to reinforce the scrapbook aesthetic.

## Elevation & Depth

Depth in this design system is achieved through **Ambient Shadows** and **Tonal Layering** rather than heavy lighting effects.

- **Shadows:** Use extremely soft, long-range shadows with a hint of the primary color (`#D9A5B3`) in the shadow tint. This makes cards look like they are floating slightly above a paper surface.
- **Layering:** Use subtle shifts in background color (e.g., a Rice Paper background with Clotted Cream cards) to create hierarchy without needing borders.
- **Z-Index:** High-priority modals should use a soft backdrop blur (10px) to maintain the "frosted glass" cafe window vibe.

## Shapes

The shape language is defined by **High Circularity**. 

- **Cards & Containers:** Use `rounded-lg` (16px) or `rounded-xl` (24px) for main content areas to evoke a friendly, non-corporate feeling.
- **Interactions:** Buttons and input fields should utilize `rounded-xl` to feel "squishy" and approachable.
- **Decorative Elements:** Use perfectly circular shapes for profile pictures and notification dots to provide a geometric counterpoint to the organic layout.

## Components

- **Buttons:** Primary buttons use the Rosewater fill with Tertiary (Dark Mocha) text. Secondary buttons should have a soft beige background with no border. Apply a slight "lift" on hover (y-axis -2px).
- **Cards:** Pinterest-style cards with varying heights. Cards should have no border, a soft tinted shadow, and a 16px internal padding. Images within cards should always have an 8px corner radius.
- **Stickers (Badges):** Small, rounded labels for categories (e.g., "Study," "Cafe," "Travel"). Use pastel fills and thin, slightly darker outlines to make them look like physical stickers.
- **Input Fields:** Soft beige backgrounds with a subtle inner shadow to feel "recessed" into the paper. Focus states should use a soft pink glow.
- **Tape/Dividers:** Instead of horizontal lines, use subtle "Washi Tape" rectangular shapes or very low-opacity textured dividers to separate sections.
- **Navigation:** A floating bottom bar or a clean, centered top nav with high transparency and a backdrop blur.