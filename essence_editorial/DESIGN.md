---
name: Essence Editorial
colors:
  surface: '#faf9f6'
  surface-dim: '#dbdad7'
  surface-bright: '#faf9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f1'
  surface-container: '#efeeeb'
  surface-container-high: '#e9e8e5'
  surface-container-highest: '#e3e2e0'
  on-surface: '#1a1c1a'
  on-surface-variant: '#43474e'
  inverse-surface: '#2f312f'
  inverse-on-surface: '#f2f1ee'
  outline: '#74777e'
  outline-variant: '#c4c6ce'
  surface-tint: '#486081'
  primary: '#00040c'
  on-primary: '#ffffff'
  primary-container: '#001e3c'
  on-primary-container: '#6f87aa'
  inverse-primary: '#afc8ee'
  secondary: '#70585b'
  on-secondary: '#ffffff'
  secondary-container: '#f8d8db'
  on-secondary-container: '#755d5f'
  tertiary: '#0f0004'
  on-tertiary: '#ffffff'
  tertiary-container: '#42001f'
  on-tertiary-container: '#e7498a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d3e3ff'
  primary-fixed-dim: '#afc8ee'
  on-primary-fixed: '#001c39'
  on-primary-fixed-variant: '#2f4868'
  secondary-fixed: '#fbdbde'
  secondary-fixed-dim: '#debfc2'
  on-secondary-fixed: '#281719'
  on-secondary-fixed-variant: '#574144'
  tertiary-fixed: '#ffd9e2'
  tertiary-fixed-dim: '#ffb1c8'
  on-tertiary-fixed: '#3e001d'
  on-tertiary-fixed-variant: '#8e004a'
  background: '#faf9f6'
  on-background: '#1a1c1a'
  surface-variant: '#e3e2e0'
typography:
  display-xl:
    fontFamily: Noto Serif
    fontSize: 84px
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  section-gap: 160px
  container-max: 1280px
  gutter: 24px
  stack-sm: 8px
  stack-md: 24px
  stack-lg: 48px
---

## Brand & Style

This design system is built on the philosophy of "Elevated Serenity." It merges the high-fashion editorial feel of a luxury magazine with the soft, welcoming atmosphere of a high-end wellness retreat. The visual narrative targets a discerning clientele looking for professional expertise wrapped in a modern, feminine aesthetic.

The design style is a sophisticated blend of **Minimalism** and **Glassmorphism**. It utilizes expansive whitespace to create a sense of calm and breathing room, while employing translucent, frosted layers for UI elements to suggest depth and tactility. The overall vibe is premium and intentional, moving away from cluttered layouts toward a curated, scrollytelling experience where every image and headline has room to resonate.

## Colors

The palette is anchored by a **Deep Navy** (the primary color), used for high-contrast sections, footers, and authoritative typography. This is balanced by a **Soft Petal Pink** (secondary) and **Pastel Cream** (neutral) to maintain a feminine and welcoming warmth.

A **Vibrant Rose** (tertiary) is used sparingly as an accent for call-to-action elements and interactive states to draw the eye without overwhelming the senses. The "Light" mode is the default state to ensure a clean, airy feel, though "Deep Navy" sections should be used strategically to create dramatic, premium breaks in the user journey.

## Typography

The typography strategy relies on a classic editorial pairing. **Noto Serif** provides a timeless, authoritative voice for headlines, echoing the elegance of luxury beauty branding. Large "Display" sizes should be used in scrollytelling sections with generous tracking adjustments to emphasize the premium nature of the content.

**Manrope** serves as the functional workhorse for body text and labels. Its modern, geometric construction ensures high legibility across digital interfaces while remaining soft enough to align with the feminine aesthetic. Use "Label-Caps" for overlines and small navigation elements to create a rhythmic, structured hierarchy.

## Layout & Spacing

The layout follows a **Fixed Grid** model (12 columns) but prioritizes "Airy Whitespace" to facilitate a scrollytelling experience. Sections are separated by significant vertical gaps (`section-gap`) to allow the user to focus on one concept at a time. 

Content should be centered or offset with asymmetrical balance to mimic high-end magazine layouts. Elements should frequently break the grid with subtle overlaps (e.g., a floating image slightly covering a headline) to create visual interest and a sense of movement as the user scrolls.

## Elevation & Depth

Hierarchy is established through **Glassmorphism** and **Ambient Shadows**. Instead of heavy dropshadows, this design system uses "Soft Lume"—highly diffused, low-opacity shadows (e.g., 5% opacity Navy or Rose) to lift cards and modals gently off the surface.

Glassmorphic overlays should be used for navigation bars and product info cards sitting atop imagery. These elements use a `backdrop-filter: blur(12px)` and a subtle 1px border in a semi-transparent white or soft pink to simulate polished glass, reinforcing the "premium" vibe.

## Shapes

The shape language is organic and soft, avoiding sharp corners to maintain the welcoming and feminine tone. Containers, buttons, and input fields use a **Rounded** (0.5rem) base. For high-interaction elements like primary buttons and tags, a "Pill" shape (rounded-full) is preferred to evoke a sense of smoothness and comfort. Imagery should occasionally use soft-masked edges or circular frames to contrast against the structured grid.

## Components

### Buttons
- **Primary:** Pill-shaped, Solid Navy background with White or Pink text. Use a subtle scale-up animation on hover.
- **Secondary:** Pill-shaped, Transparent with a thin Navy or Rose border (Ghost style). 

### Cards
- **Product Cards:** Minimalist frames with a slight "Soft Lume" shadow. Text is center-aligned below the image using `body-md` for the title and `label-caps` for the category.
- **Service Cards:** Use a background color of `secondary_color_hex` at 10% opacity with a glassmorphic blur.

### Inputs
- **Fields:** Bottom-border only for a "clean" look, or fully rounded borders with a very light neutral fill. Labels should use the `label-caps` style for a professional, organized appearance.

### Scrollytelling Elements
- **Reveal Animations:** As headings enter the viewport, they should transition from `opacity: 0` and `translateY: 20px` to their natural state with a slow, elegant cubic-bezier easing.
- **Parallax Imagery:** Large hero images should have a subtle parallax effect (moving at 0.9x scroll speed) to add depth to the storytelling.