---
name: Obsidian Desire
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#20201f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353535'
  on-surface: '#e5e2e1'
  on-surface-variant: '#c4c7c7'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#8e9192'
  outline-variant: '#444748'
  surface-tint: '#c9c6c5'
  primary: '#c9c6c5'
  on-primary: '#313030'
  primary-container: '#0a0a0a'
  on-primary-container: '#7b7979'
  inverse-primary: '#5f5e5e'
  secondary: '#ffb3b6'
  on-secondary: '#68001a'
  secondary-container: '#cc003c'
  on-secondary-container: '#ffdcdc'
  tertiary: '#f9bd22'
  on-tertiary: '#402d00'
  tertiary-container: '#100900'
  on-tertiary-container: '#9b7300'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c9c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#ffdada'
  secondary-fixed-dim: '#ffb3b6'
  on-secondary-fixed: '#40000c'
  on-secondary-fixed-variant: '#920028'
  tertiary-fixed: '#ffdf9f'
  tertiary-fixed-dim: '#f9bd22'
  on-tertiary-fixed: '#261a00'
  on-tertiary-fixed-variant: '#5c4300'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353535'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-margin: 24px
  gutter: 16px
  card-padding: 20px
---

## Brand & Style

The design system is centered on an atmosphere of high-end privacy, seduction, and exclusivity. It targets a sophisticated audience seeking a premium, "members-only" digital experience that feels both dangerous and indulgent. 

The aesthetic is a fusion of **Dark Minimalism** and **Luxury Glassmorphism**. The UI should feel like a high-end lounge at night: low light, rich textures, and sharp highlights. Every interaction is designed to evoke a sense of physical touch and high-stakes elegance. The "Black Gold Desire" narrative is reinforced through deep matte surfaces contrasted with sharp, luminous accents that guide the user's attention to key actions and intimate content.

## Colors

This design system operates exclusively in a dark, high-contrast palette to maintain its seductive and private nature.

- **Primary (Obsidian Black):** #0a0a0a. Used for the global background and deep matte surfaces. It should feel infinite and void-like.
- **Accent 1 (Flame Red):** #e11d48. Used for high-energy interactions, "desire" indicators, and primary action buttons. It represents passion and urgency.
- **Accent 2 (Sovereign Gold):** #fbbf24. Used for premium tiers, luxury indicators, and subtle highlights. It represents status and wealth.
- **Neutral (Carbon):** #1a1a1a. Used for card backgrounds and elevated surfaces to create depth against the pure black background.

## Typography

The typography strategy emphasizes contrast between power and elegance. 

- **Headlines:** Set in **Plus Jakarta Sans**, utilizing heavy weights and tight tracking for a bold, modern, and authoritative presence.
- **Body:** Set in **Manrope**, providing a refined and balanced reading experience that feels sophisticated and airy.
- **Labels & Utility:** Set in **Geist**, utilizing its technical, precise character to ground the more expressive elements of the UI.

All text on dark backgrounds should prioritize legibility, using slightly increased line height and pure white or gold-tinted silver for secondary information.

## Layout & Spacing

The layout follows a **fluid grid** model with generous internal spacing to mimic the feeling of luxury retail environments. 

- **Desktop:** 12-column grid with a max-width of 1440px.
- **Mobile:** 4-column grid with 24px side margins to ensure content feels framed and contained.
- **Rhythm:** An 8px base unit governs all dimensions. Use large padding (32px+) for section headers to create "breathing room" that feels intentional and premium.

## Elevation & Depth

Hierarchy is established through **Glassmorphism** and **Tonal Layering** rather than traditional drop shadows.

- **Background:** The base is a deep, matte #0a0a0a.
- **Surface Layer:** Cards use a semi-transparent #1a1a1a with a `20px` backdrop-blur. 
- **Edges:** Every elevated surface must have a `1px` inner border (stroke). On the top and left, use a low-opacity Gold or White; on the bottom and right, use a low-opacity Flame Red. This creates a "rim-lit" effect.
- **Glows:** Primary elements emit a subtle, localized outer glow (15-30px blur) using the Flame Red or Gold color to suggest a "pulsing desire."

## Shapes

The design system uses **Rounded (0.5rem)** corners as a baseline to maintain a sleek, organic feel that avoids the "coldness" of sharp corners while remaining more professional than fully rounded "bubble" aesthetics.

- **Standard Elements:** 8px (0.5rem) radius.
- **Cards/Containers:** 16px (1rem) radius.
- **Interactive Triggers:** Buttons can scale up to 32px (Pill-shaped) for a more inviting, tactile "squishy" feel.

## Components

### Buttons
Primary "Desire" buttons use a gradient of Flame Red to a deeper crimson. They feature a subtle `pulse` animation on hover or active state, mimicking a heartbeat. Secondary buttons are "Ghost" style with Gold borders and high-blur glass backgrounds.

### Glass Cards
Containers for profiles and content should be frosted glass. Use a `1px` stroke with 10% opacity Gold to define the boundaries without breaking the dark immersion.

### Custom Icons
Icons (flame, silk, droplets, chains) should be thin-line (1.5pt) with a slight glow effect. Use Flame Red for icons representing action/passion and Gold for status/settings.

### Input Fields
Fields are dark matte #050505 with no visible borders until focused. On focus, a Gold "underline" or border glow expands from the center outward.

### Lists & Selection
Lists utilize high-contrast separators (1px matte grey). Selection states should be indicated by a soft Flame Red side-light rather than a full background fill.