---
name: Unity & Bloom
colors:
  surface: '#fff7fb'
  surface-dim: '#e1d7e0'
  surface-bright: '#fff7fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fcf0f9'
  surface-container: '#f6ebf4'
  surface-container-high: '#f0e5ee'
  surface-container-highest: '#eadfe8'
  on-surface: '#1f1a20'
  on-surface-variant: '#4d4350'
  inverse-surface: '#342e35'
  inverse-on-surface: '#f9edf7'
  outline: '#7f7381'
  outline-variant: '#d0c2d1'
  surface-tint: '#8441a1'
  primary: '#8441a1'
  on-primary: '#ffffff'
  primary-container: '#bb75d8'
  on-primary-container: '#480065'
  inverse-primary: '#ebb2ff'
  secondary: '#3e665f'
  on-secondary: '#ffffff'
  secondary-container: '#bde8e0'
  on-secondary-container: '#426a64'
  tertiary: '#715950'
  on-tertiary: '#ffffff'
  tertiary-container: '#a78b80'
  on-tertiary-container: '#38261e'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#f8d8ff'
  primary-fixed-dim: '#ebb2ff'
  on-primary-fixed: '#320047'
  on-primary-fixed-variant: '#692787'
  secondary-fixed: '#c0ebe3'
  secondary-fixed-dim: '#a4cfc7'
  on-secondary-fixed: '#00201c'
  on-secondary-fixed-variant: '#254d48'
  tertiary-fixed: '#fcdccf'
  tertiary-fixed-dim: '#dfc0b4'
  on-tertiary-fixed: '#281810'
  on-tertiary-fixed-variant: '#584239'
  background: '#fff7fb'
  on-background: '#1f1a20'
  surface-variant: '#eadfe8'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
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
  margin-desktop: auto
  max-width: 1200px
---

## Brand & Style

The design system is centered on fostering a sense of warmth, inclusivity, and proactive community engagement. Aimed at university students and local partners, the aesthetic balances the energy of campus life with the reliability of a service-oriented organization.

The visual style is **Soft-Modern**. It leverages a "Modern Corporate" foundation—prioritizing clarity and accessibility—but softens it with organic shapes, a pastel-dominant palette, and gentle depth. The goal is to evoke an emotional response of optimism and belonging, ensuring the platform feels like a welcoming invitation rather than a bureaucratic requirement.

## Colors

The palette is derived from a soft, multi-tonal spring spectrum. **Purple (#BB75D8)** serves as the primary action color, providing enough contrast for readability and buttons. **Mint (#B8E3DB)** and **Peach (#E3C4B8)** are used for secondary UI elements like tags, category indicators, and background sections to differentiate content types.

**Lavender (#CBB8E4)** and **Pale Yellow (#E3E2B8)** are reserved for soft decorative backgrounds and "quiet" call-outs. Text should primarily utilize a deep charcoal (off-black) to maintain high legibility against the light, airy background colors.

## Typography

This design system uses **Plus Jakarta Sans** across all levels to maintain a friendly, contemporary, and open feel. Its geometric yet soft letterforms reflect the community-focused narrative of the group.

- **Headlines:** Use Bold or SemiBold weights with tighter letter-spacing for a confident, grounded look.
- **Body Text:** Use Regular weight for maximum legibility in long-form descriptions of volunteer opportunities.
- **Labels:** Use SemiBold with a slight uppercase treatment for navigation and small UI indicators to ensure they stand out without adding visual bulk.

## Layout & Spacing

The layout follows a **fluid-to-fixed grid** model. On mobile devices, content spans the width of the screen with 16px side margins. On desktop, content is contained within a 1200px centered container to ensure readability.

We utilize an 8px base grid to maintain a consistent rhythm. Generous whitespace (using 'lg' and 'xl' tokens) is encouraged between major sections to prevent the site from feeling cluttered, reinforcing the "calm and welcoming" brand pillar. Elements should generally align to a 12-column grid on desktop, shifting to a single-column stack on mobile.

## Elevation & Depth

To maintain a "welcoming" feel, this design system avoids harsh borders. Instead, hierarchy is created through **Tonal Layering** and **Ambient Shadows**.

- **Surface Levels:** The main background is a very light grey (#FAFAFA). Interaction cards and containers use pure white (#FFFFFF).
- **Shadows:** Use a single, soft shadow style for elevated elements like cards and buttons. Shadows should be highly diffused (20px - 30px blur), low-opacity (8-10%), and slightly tinted with the Primary Purple color to keep the palette cohesive.
- **Depth:** Avoid more than two levels of elevation. Elements are either flat on the surface or "floating" slightly to indicate interactivity.

## Shapes

The shape language is consistently **Rounded**. Sharp corners are avoided to ensure the UI feels approachable and safe. 

- **Standard Elements:** Buttons, input fields, and small tags use a 0.5rem (8px) radius.
- **Large Containers:** Content cards and donation call-outs use a 1rem (16px) radius.
- **Special Elements:** Image frames or featured buttons may use a 1.5rem (24px) radius to create a more organic, playful feel.

## Components

### Buttons
- **Primary:** Solid Primary Purple (#BB75D8) with white text. High-rounded corners (0.5rem).
- **Secondary:** Mint (#B8E3DB) background with dark text for less urgent actions.
- **Ghost:** Transparent background with Primary Purple border and text.

### Social Media Links
- Use a dedicated "Social Bar" component. Icons (Instagram, TikTok) should be housed in circular Lavender (#CBB8E4) backgrounds that scale slightly on hover.

### Donation Call-outs
- These should be styled as "High-Impact Cards." Use the Peach (#E3C4B8) background to distinguish them from volunteer listings. Include a clear Primary Button inside the card for the "Donate" action.

### Cards (Volunteer Opportunities)
- White background with a soft ambient shadow. 
- Use the Mint or Lavender colors as small "category chips" at the top of the card (e.g., "Education," "Environment").
- Bold Headline-md for the title.

### Input Fields
- Subtle 1px border in Lavender or Light Grey. 
- Focus state should use a Primary Purple glow and 2px border.