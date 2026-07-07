---
name: Obsidian Desire
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#e8bcb7'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#ae8783'
  outline-variant: '#5e3f3b'
  surface-tint: '#ffb4ab'
  primary: '#ffb4ab'
  on-primary: '#690005'
  primary-container: '#ff544a'
  on-primary-container: '#5c0004'
  inverse-primary: '#c00013'
  secondary: '#c8c6c5'
  on-secondary: '#313030'
  secondary-container: '#474746'
  on-secondary-container: '#b7b5b4'
  tertiary: '#c6c6c7'
  on-tertiary: '#2f3131'
  tertiary-container: '#909191'
  on-tertiary-container: '#282a2a'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb4ab'
  on-primary-fixed: '#410002'
  on-primary-fixed-variant: '#93000b'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
  meta-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  container-padding-mobile: 16px
  container-padding-desktop: 40px
  gutter: 16px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style
The design system embodies a premium, high-octane entertainment atmosphere tailored for an elite audience. The personality is mysterious yet energetic, utilizing a "Dark Cinematic" aesthetic. The target audience expects exclusivity and tactile responsiveness.

The style is a hybrid of **Glassmorphism** and **Minimalism**. It features deep, obsidian-like surfaces, translucent frosted layers that imply depth without clutter, and sharp, high-energy "Flame Red" accents to draw focus to critical actions and notifications. The emotional response is one of immersion, prestige, and urgency.

## Colors
The palette is dominated by **Obsidian Black** (#0A0A0A) as the base canvas to ensure maximum OLED contrast. 

- **Primary (Flame Red):** Used exclusively for call-to-actions, unread message indicators, and critical system alerts. It should vibrate against the dark background.
- **Secondary (Onyx):** Used for elevated surface containers (#1A1A1A).
- **Glass Layers:** A semi-transparent white (Alpha 5-10%) used for frosted glass overlays.
- **Accents:** High-purity white is reserved for primary text to ensure legibility against dark backgrounds.

## Typography
The typography uses **Plus Jakarta Sans** for its modern, approachable yet premium feel, providing excellent readability in dark mode. Headlines are set with heavy weights and tight tracking to feel impactful.

**Space Grotesk** is used for labels and technical metadata (timestamps, message categories) to inject a subtle futuristic/tech edge that aligns with high-end entertainment platforms. All secondary text should utilize reduced opacity (60%) rather than grey hex codes to maintain the "glass" aesthetic.

## Layout & Spacing
The layout follows a **Fluid Grid** model with generous internal padding to create an airy, premium feel. 

- **Mobile:** Single column list view. Content is pinned to 16px side margins. 
- **Desktop:** Two-column split-view. Left column (320px fixed) for the message list; Right column (fluid) for the active conversation or announcement detail.
- **Rhythm:** All spacing must be multiples of 4px. Use `stack-lg` (32px) to separate different message categories (e.g., Announcements vs. Private Messages).

## Elevation & Depth
This design system eschews traditional shadows in favor of **Tonal Layering** and **Glassmorphism**.

1.  **Level 0 (Base):** Obsidian Black (#0A0A0A).
2.  **Level 1 (Card/List Item):** Onyx (#1A1A1A) with a 1px subtle stroke (White at 10% opacity).
3.  **Level 2 (Modals/Overlays):** Frosted Glass effect. Background blur at 20px, Fill color at White 5% opacity.
4.  **Glow:** Primary Flame Red elements (like unread pips) should have a soft 8px outer glow of the same color (Opacity 30%) to simulate a light-emitting diode.

## Shapes
Shapes are modern and refined. The standard corner radius is 0.5rem (8px), which provides a balanced look that is neither too sharp nor too playful. Large containers like the message detail view should use `rounded-xl` (24px) to create a distinct frame-within-a-frame effect. Interactive elements like "New Message" buttons should use pill-shaping to stand out from the rectangular message cards.

## Components
- **Message Cards:** Use a Level 1 surface. Unread states are indicated by a 2px vertical Flame Red line on the left edge and a glowing red dot next to the timestamp.
- **Buttons (Primary):** Solid Flame Red fill, white text, pill-shaped. On hover, increase the outer glow intensity.
- **Buttons (Secondary):** Glass background with a 1px white border (20% opacity).
- **Tabs/Filters:** Use `label-caps` typography. The active state is indicated by a Flame Red underline that glows.
- **Input Fields:** Darker than the surface (#050505), 1px border. The border turns Flame Red when focused.
- **System Notifications:** Distinct from private messages; use a subtle gradient border (Flame Red to Transparent) to signify official status.
- **Avatars:** Circular, with a 2px offset border in Onyx to separate the image from the background layers.