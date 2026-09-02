---
name: Industrial Precision
colors:
  surface: '#fdf8f8'
  surface-dim: '#ddd9d8'
  surface-bright: '#fdf8f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3f2'
  surface-container: '#f1edec'
  surface-container-high: '#ebe7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#444748'
  inverse-surface: '#313030'
  inverse-on-surface: '#f4f0ef'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#181919'
  on-primary: '#ffffff'
  primary-container: '#2d2d2d'
  on-primary-container: '#959494'
  inverse-primary: '#c8c6c6'
  secondary: '#585f6c'
  on-secondary: '#ffffff'
  secondary-container: '#dce2f3'
  on-secondary-container: '#5e6572'
  tertiary: '#191917'
  on-tertiary: '#ffffff'
  tertiary-container: '#2e2d2b'
  on-tertiary-container: '#979491'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e4e2e1'
  primary-fixed-dim: '#c8c6c6'
  on-primary-fixed: '#1b1c1c'
  on-primary-fixed-variant: '#474747'
  secondary-fixed: '#dce2f3'
  secondary-fixed-dim: '#c0c7d6'
  on-secondary-fixed: '#151c27'
  on-secondary-fixed-variant: '#404754'
  tertiary-fixed: '#e6e2de'
  tertiary-fixed-dim: '#c9c6c3'
  on-tertiary-fixed: '#1c1b1a'
  on-tertiary-fixed-variant: '#484644'
  background: '#fdf8f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
  deep-charcoal: '#1A1A1A'
  slate-steel: '#4A5568'
  cool-grey: '#F2F4F7'
  surface-white: '#FFFFFF'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-xl:
    fontFamily: Hanken Grotesk
    fontSize: 36px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 28px
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
  label-caps:
    fontFamily: Inter
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
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  section-gap: 120px
  stack-sm: 4px
  stack-md: 12px
  stack-lg: 24px
---

## Brand & Style

The brand personality is **authoritative, engineered, and premium**. It reflects a fusion of deep-rooted heritage with cutting-edge IoT technology. This design system targets B2B decision-makers and high-end retail operators who value reliability and technical superiority.

The visual style is **Corporate / Modern** with a strong **Minimalist** lean. It employs a "form follows function" philosophy, utilizing generous whitespace to allow product engineering details to take center stage. The aesthetic is reminiscent of high-end industrial machinery: clean lines, a monochromatic palette, and a lack of superficial ornamentation. The UI should evoke a sense of quiet confidence and technical precision.

## Colors

The palette is strictly architectural, relying on a range of charcoal and slate tones to convey an industrial feel. 

- **Primary Charcoal (#2D2D2D):** Used for primary typography and brand elements, providing a softer, more sophisticated look than pure black.
- **Secondary Slate (#6B7280):** Utilized for secondary text, borders, and icon states to create subtle hierarchy.
- **Surface & Neutrals:** Crisp whites and very light "Cool Grey" are used for background containment, ensuring the "deep" tones of the hardware imagery pop.

The design defaults to **light mode** with high-contrast text to maintain a professional, document-like clarity. Dark sections should be used sparingly for hero areas or to highlight premium hardware features.

## Typography

Typography is the backbone of this industrial aesthetic. **Hanken Grotesk** is used for headlines to provide a sharp, contemporary engineering feel. **Inter** is utilized for body and UI labels to ensure maximum legibility and a systematic, utilitarian appearance.

- **Hierarchy:** Use large display sizes for product names and hero statements. 
- **Tracking:** Headlines benefit from slight negative letter-spacing for a more "locked-in" look, while labels use expanded tracking for an institutional, technical feel.
- **Scalability:** On mobile, display sizes scale down aggressively to maintain the "clean and airy" layout without causing excessive vertical scrolling.

## Layout & Spacing

This design system uses a **fixed-width grid** for desktop (max-width: 1280px) centered on the page to emphasize order and structure. 

- **Grid Model:** A 12-column grid with 24px gutters. Elements should align strictly to the grid edges.
- **Whitespace:** Emphasize "Industrial Negative Space." Section gaps are intentionally large (120px+) to isolate products and allow the user to focus on one engineering solution at a time.
- **Responsive Behavior:** 
    - **Desktop:** Wide margins (64px) to create a centered, "gallery" feel.
    - **Tablet:** Fluid 8-column grid with 32px margins.
    - **Mobile:** Single column stack with 16px margins; typography and internal component padding should remain tight to preserve screen real estate.

## Elevation & Depth

To maintain the "high-end industrial" look, the design system avoids heavy shadows and skeuomorphism. 

- **Tonal Layers:** Depth is created primarily through color blocking. Use `cool-grey` backgrounds for container elements (like cards) against `surface-white` pages.
- **Low-Contrast Outlines:** Instead of shadows, use 1px borders in `slate-steel` (at 20% opacity) to define object boundaries. 
- **Z-Index Strategy:** Only functional elements (sticky headers, modal overlays) utilize elevation. When used, shadows must be "Ambient": very large blur radii (32px+), low opacity (under 8%), and zero offset to simulate a soft, studio-lit environment.

## Shapes

The shape language is "Soft-Industrial." Elements are not sharp-edged (to avoid looking dated), but they are not playful or overly rounded. 

- **Base Radius:** 4px (Soft) for most UI elements like buttons and input fields.
- **Large Components:** Cards and image containers may use up to 8px (rounded-lg) to soften the overall presentation of heavy industrial hardware.
- **Strictness:** Roundness should never exceed 12px. Pill shapes are strictly prohibited except for status indicators (chips).

## Components

- **Buttons:** Use a solid `primary-charcoal` for primary actions. Hover states should be a subtle shift to `slate-steel` or a slight increase in tonal depth. Avoid gradients. Secondary buttons should use the "Low-Contrast Outline" style with a ghost background.
- **Chips / Status Indicators:** Used for technical specs (e.g., "IoT Enabled," "Cloud Sync"). Use small, 10px Inter font in all-caps with a light grey fill.
- **Input Fields:** Minimalist design with only a bottom border or a very faint 1px full border. Active states are indicated by a color change of the border to `primary-charcoal`.
- **Cards:** Cards should have no shadow; they are defined by a `cool-grey` background or a fine border. They should have generous internal padding (32px or more) to feel premium.
- **Product Lists:** Use a clean, horizontal layout with high-quality technical photography on one side and a structured grid of specs on the other. Use `label-caps` for spec headers.
- **Navigation:** The header should be slim and sticky, using `body-md` weights for links. The active state is a simple, thin horizontal bar above or below the text.