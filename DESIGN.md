---
name: Organic Botanical
colors:
  surface: '#fbf9f5'
  surface-dim: '#dbdad6'
  surface-bright: '#fbf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ef'
  surface-container: '#efeeea'
  surface-container-high: '#eae8e4'
  surface-container-highest: '#e4e2de'
  on-surface: '#1b1c1a'
  on-surface-variant: '#55423d'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f0ed'
  outline: '#89726c'
  outline-variant: '#dcc1b9'
  surface-tint: '#9b4428'
  primary: '#6f240a'
  on-primary: '#ffffff'
  primary-container: '#8e3a1f'
  on-primary-container: '#ffb8a3'
  inverse-primary: '#ffb59f'
  secondary: '#904d00'
  on-secondary: '#ffffff'
  secondary-container: '#fe932c'
  on-secondary-container: '#663500'
  tertiary: '#2e4220'
  on-tertiary: '#ffffff'
  tertiary-container: '#445a35'
  on-tertiary-container: '#b7d0a2'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbd0'
  primary-fixed-dim: '#ffb59f'
  on-primary-fixed: '#3a0a00'
  on-primary-fixed-variant: '#7c2d13'
  secondary-fixed: '#ffdcc3'
  secondary-fixed-dim: '#ffb77d'
  on-secondary-fixed: '#2f1500'
  on-secondary-fixed-variant: '#6e3900'
  tertiary-fixed: '#d1ebba'
  tertiary-fixed-dim: '#b5cea0'
  on-tertiary-fixed: '#0d2003'
  on-tertiary-fixed-variant: '#384d29'
  background: '#fbf9f5'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2de'
typography:
  display-lg:
    fontFamily: Libre Caslon Text
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 36px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Libre Caslon Text
    fontSize: 24px
    fontWeight: '400'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Work Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
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
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style
The design system for Zizah Spices is rooted in the concept of "The Modern Apothecary." It evokes a sense of artisanal quality, purity, and the healing power of nature. The target audience includes health-conscious culinary enthusiasts and wellness practitioners who value transparency and premium sourcing.

The design style is **Minimalist-Organic**. It utilizes generous whitespace to allow rich product photography and earthy colors to breathe. We blend clean, systematic layouts with subtle organic textures—such as grain or soft paper finishes—to ensure the interface feels tactile rather than cold. The emotional response is one of calm, reliability, and warmth.

## Colors
This design system uses a palette inspired by raw, unprocessed botanicals.
- **Primary (Cinnamon):** A deep, grounded red used for primary calls to action and key branding moments.
- **Secondary (Turmeric):** An energetic orange used for highlights, badges, and seasonal alerts.
- **Tertiary (Moringa):** A deep leaf green representing health and vitality, used for navigation and iconography.
- **Neutral (Paper):** A warm, off-white base that avoids the harshness of pure white, providing a "parchment" feel.
- **Text (Ink):** A very dark brown, rather than black, to maintain a soft, natural contrast.

## Typography
The typography strategy pairings high-editorial elegance with functional clarity. 
- **Headings:** Use **Libre Caslon Text**. This serif brings historical authority and a "premium culinary" feel. It should be used for all storytelling and product titles.
- **Body & Labels:** Use **Work Sans**. Its clean, professional, and slightly wider proportions ensure legibility even in dense ingredient lists or health benefit descriptions.
- **Styling:** Use `label-caps` for category headers and overlines to add a structured, apothecary-label aesthetic.

## Layout & Spacing
The layout follows a **Fluid Grid** model with generous margins to evoke a premium, "un-crowded" feel.
- **Desktop:** 12-column grid with 64px outside margins and 24px gutters. Use asymmetrical layouts (e.g., text spanning 5 columns, image spanning 7) to mimic high-end lifestyle magazines.
- **Mobile:** 4-column grid with 16px margins. 
- **Spacing Rhythm:** Use a strict 8px base unit. Vertical rhythm should favor "airy" spacing (LG and XL units) between sections to highlight the organic nature of the brand.

## Elevation & Depth
This design system avoids heavy drop shadows, opting instead for **Tonal Layers** and **Low-Contrast Outlines**.
- **Surface Depth:** Use subtle shifts in background color (e.g., a slightly darker cream or a very pale Moringa green) to define containers.
- **Borders:** Use thin (1px) solid borders in `accent_cardamom` or `text_ink` at 10% opacity to define cards and input fields.
- **Floating Elements:** If a shadow is necessary for a modal or primary button, use a "Botanical Shadow": a very soft, diffused blur with a slight tint of the `primary_color` (Cinnamon) at 5% opacity to maintain warmth.

## Shapes
The shape language is **Soft**. 
- Standard elements like buttons and cards use a 4px (0.25rem) corner radius. This provides enough structure to feel professional and "packaged," but enough softness to feel approachable.
- Iconic elements, such as product category "spots" or "add to cart" circular buttons, may use full pill-rounding to create a friendly contrast against the structured grid.

## Components
- **Buttons:** Primary buttons are solid `primary_color_hex` (Cinnamon) with white `Work Sans` text. Secondary buttons use a `primary_color_hex` border with no fill.
- **Input Fields:** Use a "bottom-border only" style for a more elegant, apothecary-logbook look, or a full soft-rounded border at 10% opacity.
- **Cards:** Product cards should have a background of `neutral_color_hex` slightly differentiated from the page background, with no shadow and a thin `accent_cardamom` border.
- **Chips/Badges:** Use for "Organic," "Fair Trade," or "Anti-inflammatory" tags. These should have a light `accent_cardamom` background with dark `accent_moringa` text.
- **Lists:** Ingredient lists should use custom bullets—small green leaves or simple geometric dots in the `accent_moringa` color.
- **Specialty Component (The Seal):** A circular badge element containing a "Z" or an icon of a spice flower, used as a watermark or a quality guarantee seal on product images.