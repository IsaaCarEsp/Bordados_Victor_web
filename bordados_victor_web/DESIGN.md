---
name: Artisanal Elegance
colors:
  surface: '#faf9fd'
  surface-dim: '#dad9dd'
  surface-bright: '#faf9fd'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f7'
  surface-container: '#efedf1'
  surface-container-high: '#e9e7eb'
  surface-container-highest: '#e3e2e6'
  on-surface: '#1a1b1e'
  on-surface-variant: '#44474e'
  inverse-surface: '#2f3033'
  inverse-on-surface: '#f1f0f4'
  outline: '#74777f'
  outline-variant: '#c4c6cf'
  surface-tint: '#465f88'
  primary: '#000a1e'
  on-primary: '#ffffff'
  primary-container: '#002147'
  on-primary-container: '#708ab5'
  inverse-primary: '#aec7f6'
  secondary: '#4e6077'
  on-secondary: '#ffffff'
  secondary-container: '#cfe1fd'
  on-secondary-container: '#52647b'
  tertiary: '#180500'
  on-tertiary: '#ffffff'
  tertiary-container: '#3d1500'
  on-tertiary-container: '#b97958'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#aec7f6'
  on-primary-fixed: '#001b3d'
  on-primary-fixed-variant: '#2d476f'
  secondary-fixed: '#d2e4ff'
  secondary-fixed-dim: '#b6c8e3'
  on-secondary-fixed: '#091c31'
  on-secondary-fixed-variant: '#37485e'
  tertiary-fixed: '#ffdbcb'
  tertiary-fixed-dim: '#ffb691'
  on-tertiary-fixed: '#341100'
  on-tertiary-fixed-variant: '#6c391d'
  background: '#faf9fd'
  on-background: '#1a1b1e'
  surface-variant: '#e3e2e6'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: DM Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: DM Sans
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1200px
  gutter: 24px
  section-padding-desktop: 100px
  section-padding-mobile: 60px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

The design system is built upon the intersection of traditional craftsmanship and modern professional excellence. It evokes a sense of bespoke quality, reliability, and meticulous attention to detail, targeting a clientele that values premium service over mass production.

The visual style is **Sophisticated Minimalism with High-Contrast Accents**. It utilizes a structured layout, generous whitespace, and delicate golden linework to mirror the precision of embroidery threads. The interface feels established and authoritative, yet accessible through familiar patterns and clear calls to action. Every interaction should feel intentional, reflecting the "crafted" nature of the product.

## Colors

The palette is anchored by **Navy Blue**, providing a foundation of trust and professionalism. **Gold** is used sparingly as a highlight to represent the premium "Craft" aspect of the business—applied to borders, icons, and subtle grid patterns.

**Functional Color Assignments:**
- **Primary (Navy):** Used for navigation backgrounds, primary headings, and structural elements.
- **Secondary (Dark Navy):** Reserved for footers and high-impact CTA sections to create visual depth.
- **Accent (Gold):** Used for decorative linework, bullet points, and small UI flourishes.
- **WhatsApp Green:** Strictly reserved for the floating WhatsApp contact button and specific "Chat with us" triggers.
- **Quote Red:** High-contrast color for the primary "Get a Quote" lead generation buttons.
- **Neutrals:** White backgrounds for readability with Light Gray used for section dividers and subtle surface transitions.

## Typography

This design system employs a classic Serif/Sans-Serif pairing. **Playfair Display** provides an editorial, high-end feel for all headings, suggesting a legacy of quality. **DM Sans** ensures high legibility for body copy and UI labels, maintaining a clean and modern professional edge.

For large display text, use a slight negative letter-spacing to maintain a tight, sophisticated look. Label styles should be set in uppercase with increased letter spacing to serve as clear section identifiers or button text.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy. Content is centered within a 1200px container on desktop to maintain focus and prevent the sophisticated typography from stretching excessively.

- **Grid:** A 12-column system for desktop, 4-column for mobile.
- **Sectioning:** Large vertical padding (100px) between sections creates the "breathable" luxury feel.
- **The "Stitch" Grid:** Implement a subtle background pattern using 1px Gold lines in a 40px x 40px grid, set at 5% opacity, to reinforce the embroidery theme without distracting from content.

## Elevation & Depth

Hierarchy is established through **Ambient Shadows** and **Tonal Layering**. 

1.  **Level 0 (Base):** White or Light Gray flat surfaces.
2.  **Level 1 (Cards):** Floating white cards with a soft, expansive shadow (`box-shadow: 0 10px 30px rgba(0, 33, 71, 0.08)`). These should appear to lift slightly off the background.
3.  **Level 2 (Active Elements):** Navigation bar and primary CTAs. The navigation bar should feature a glassmorphism effect (backdrop blur) when scrolling to maintain context of the background grid while ensuring legibility.

## Shapes

The shape language is **Soft and Architectural**. 

- **Corners:** Use 0.25rem (4px) radius for most UI elements. This keeps the look sharp and professional rather than playful.
- **Buttons:** Maintain the 4px radius for the "Quote" button. The WhatsApp button may use a full pill-shape (round) to align with global brand recognition.
- **Dividers:** Use thin 1px lines in Gold (#D4AF37) for a delicate, thread-like aesthetic.

## Components

### Buttons
- **Primary CTA (Get a Quote):** Red background, white text, uppercase label. High contrast against Navy backgrounds.
- **Secondary CTA:** Gold outline with Primary Navy text.
- **WhatsApp Button:** Floating action button in the bottom right, green background with the white WA icon.

### Cards
- White background, 4px corner radius, soft ambient shadow. 
- Top-border accent: A 2px Gold line across the top of the card to tie into the brand style.

### Navigation
- **Fixed Navbar:** Transitions from transparent to a semi-opaque Navy (with backdrop blur) on scroll.
- **Links:** DM Sans, uppercase, with a Gold underline transition on hover.

### Input Fields
- Underlined style (minimalist) or light gray stroke with 4px radius. 
- Focus state: Border changes to Gold with a soft outer glow.

### Lists
- Use a small Gold "stitch" (a vertical dash or custom icon) instead of standard bullets to reinforce the embroidery theme.