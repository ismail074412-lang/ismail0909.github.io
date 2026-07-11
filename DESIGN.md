---
name: Qarawiyyin Heritage
colors:
  surface: '#f8f9ff'
  surface-dim: '#d1dbec'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eef4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dfe9fa'
  surface-container-highest: '#d9e3f4'
  on-surface: '#121c28'
  on-surface-variant: '#404944'
  inverse-surface: '#27313e'
  inverse-on-surface: '#eaf1ff'
  outline: '#707974'
  outline-variant: '#bfc9c3'
  surface-tint: '#2b6954'
  primary: '#003527'
  on-primary: '#ffffff'
  primary-container: '#064e3b'
  on-primary-container: '#80bea6'
  inverse-primary: '#95d3ba'
  secondary: '#775a19'
  on-secondary: '#ffffff'
  secondary-container: '#fed488'
  on-secondary-container: '#785a1a'
  tertiary: '#2d2e2c'
  on-tertiary: '#ffffff'
  tertiary-container: '#444442'
  on-tertiary-container: '#b2b1ae'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#b0f0d6'
  primary-fixed-dim: '#95d3ba'
  on-primary-fixed: '#002117'
  on-primary-fixed-variant: '#0b513d'
  secondary-fixed: '#ffdea5'
  secondary-fixed-dim: '#e9c176'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5d4201'
  tertiary-fixed: '#e4e2de'
  tertiary-fixed-dim: '#c8c6c3'
  on-tertiary-fixed: '#1b1c1a'
  on-tertiary-fixed-variant: '#474744'
  background: '#f8f9ff'
  on-background: '#121c28'
  surface-variant: '#d9e3f4'
typography:
  headline-xl:
    fontFamily: Libre Caslon Text
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Libre Caslon Text
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-sm:
    fontFamily: Libre Caslon Text
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Source Sans 3
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 30px
  body-md:
    fontFamily: Source Sans 3
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  label-md:
    fontFamily: Source Sans 3
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  headline-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style
This design system captures the scholarly weight and spiritual architectural beauty of the world’s oldest continuously operating university. The brand personality is **Scholarly, Timeless, and Enlightened**, aiming to evoke a sense of deep reverence for history while maintaining the clarity of a modern educational institution.

The design style is a blend of **Minimalism and Subtle Tactile Textures**. We utilize cinematic whitespace to allow historical imagery to breathe, punctuated by intricate patterns and arched motifs that reference the university's physical architecture. The UI should feel like a bridge between a classical manuscript and a high-end digital gallery.

## Colors
The palette is rooted in the physical reality of the Al-Qarawiyyin complex.
- **Deep Emerald (#064E3B):** Used for primary actions and structural headers, representing the iconic green tiled roofs of the mosque and library.
- **Antique Gold (#C5A059):** Reserved for highlights, borders, and "The Lighthouse of Knowledge" accents, symbolizing enlightenment and the value of preserved wisdom.
- **Warm Sand (#FDFBF7):** The primary background color, mimicking the sun-drenched plaster and stone of the Moroccan courtyard.
- **Neutral Carbon (#4B5563):** Used for body text to ensure maximum legibility against the warm background.

## Typography
The typography system creates a "Manuscript-to-Modern" dialogue. 
- **Libre Caslon Text** is used for all headings. Its historical weight and sharp serifs evoke the intellectual rigor of the university's archives.
- **Source Sans 3** provides a clean, functional counterpoint for body text, ensuring that dense educational content is easily digestible across all devices.
- **Visual Rhythm:** Use generous line heights (1.6x+) for body text to maintain a calm, readable pace. For labels, use all-caps with slight tracking to differentiate metadata from narrative text.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy on desktop to maintain a curated, editorial feel. 
- **Grid:** A 12-column system with wide 24px gutters.
- **Margins:** Large horizontal margins (64px+) are encouraged to simulate the "margins of a book," focusing the user's eye on the central content.
- **Vertical Rhythm:** Use an 8px base unit. Section spacing should be aggressive (96px or 128px) to create the "cinematic" atmosphere and emphasize the importance of each topic.
- **Mobile:** Transition to a 4-column fluid grid with 20px margins; reduce vertical section spacing to 64px.

## Elevation & Depth
In alignment with the stone and plaster architecture of the university, depth is conveyed through **Tonal Layers** rather than heavy shadows.
- **Surface Levels:** Use subtle shifts between Warm Sand and a slightly darker "Stone" tint to differentiate sections.
- **Inlaid Depth:** Use thin, 1px Antique Gold borders to define interactive areas.
- **Subtle Texture:** Apply a very low-opacity (2-3%) SVG overlay of a geometric *Zellij* (mosaic) pattern on the primary background to provide tactile character without distracting from the text.
- **Shadows:** If used, they should be "Ambient" — extremely soft, wide, and tinted with the primary Emerald color to feel like a natural glow or a soft cast shadow in a courtyard.

## Shapes
The shape language is inspired by the **Horseshoe Arch** and classical geometry. 
- **Corners:** Generally "Soft" (0.25rem) to reflect aged stone that has been smoothed over centuries.
- **Arched Motifs:** Primary containers (like featured image frames or hero banners) should utilize a "Top-Rounded" or "Arched" mask, where the top two corners have a significantly larger radius (e.g., 4rem or a full semicircle) to mimic Islamic architectural portals.
- **Geometric Accents:** Decorative dividers should use small diamond or octagonal shapes, echoing the Moroccan *Zellij* tiles.

## Components
- **Buttons:** Primary buttons use the Deep Emerald background with Gold text. The shape should be slightly rounded (0.25rem), but consider an "Arched" variant for featured calls-to-action where the top is a perfect arc.
- **Cards:** Cards should have no shadow but a 1px Antique Gold border. The header image of the card should use the Arched mask.
- **Inputs:** Use a "Minimalist Field" style—only a bottom border in Gold or Emerald, reminiscent of a ruled line on a manuscript.
- **Navigation:** A centered, elegant top bar using Libre Caslon Text. Active states are indicated by a small Gold diamond underneath the menu item.
- **Dividers:** Instead of simple lines, use a 1px Gold line that breaks in the center for a small geometric pattern or star icon.
- **Chips/Tags:** Used for "Subject Categories" (e.g., Astronomy, Law); these should be Deep Emerald with a low opacity background and solid Emerald text.