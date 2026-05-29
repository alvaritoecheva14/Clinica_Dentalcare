---
name: Clinical Precision & Care
colors:
  surface: '#f8f9ff'
  surface-dim: '#ccdbf3'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e6eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d5e3fc'
  on-surface: '#0d1c2e'
  on-surface-variant: '#44474f'
  inverse-surface: '#233144'
  inverse-on-surface: '#eaf1ff'
  outline: '#747780'
  outline-variant: '#c4c6d0'
  surface-tint: '#425e91'
  primary: '#002452'
  on-primary: '#ffffff'
  primary-container: '#1b3a6b'
  on-primary-container: '#89a5dd'
  inverse-primary: '#acc7ff'
  secondary: '#006d37'
  on-secondary: '#ffffff'
  secondary-container: '#6bfe9c'
  on-secondary-container: '#00743a'
  tertiary: '#222627'
  on-tertiary: '#ffffff'
  tertiary-container: '#383b3d'
  on-tertiary-container: '#a2a5a7'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d7e2ff'
  primary-fixed-dim: '#acc7ff'
  on-primary-fixed: '#001a40'
  on-primary-fixed-variant: '#294678'
  secondary-fixed: '#6bfe9c'
  secondary-fixed-dim: '#4ae183'
  on-secondary-fixed: '#00210c'
  on-secondary-fixed-variant: '#005228'
  tertiary-fixed: '#e0e3e5'
  tertiary-fixed-dim: '#c4c7c9'
  on-tertiary-fixed: '#191c1e'
  on-tertiary-fixed-variant: '#444749'
  background: '#f8f9ff'
  on-background: '#0d1c2e'
  surface-variant: '#d5e3fc'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  caption:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  section-padding: 80px
---

## Brand & Style
The design system is engineered for a high-trust dental environment, balancing clinical excellence with a welcoming, patient-first atmosphere. The personality is authoritative yet approachable, emphasizing hygiene, transparency, and modern technology.

The aesthetic follows **Modern Corporate** principles with a heavy emphasis on **Minimalism**. It utilizes expansive whitespace to evoke a "sterile but comfortable" feeling, mirroring a clean clinic environment. Visual density is kept low to reduce patient anxiety, while high-contrast elements ensure clear communication and accessibility (WCAG AA compliance).

## Colors
This design system employs a palette that signals stability and health.
- **Primary (Navy Blue):** Used for headers, primary navigation, and core branding to establish authority and professional trust.
- **Secondary (Mint Green):** Reserved exclusively for positive actions, "Book Appointment" CTAs, and success states to signal growth and dental health.
- **Tertiary (Ice Blue/White):** A soft, cool neutral used for section backgrounds to break up pure white and reduce eye strain.
- **Neutral (Slate):** Used for body text and secondary information to maintain high legibility against white backgrounds.

## Typography
The system uses **Inter** across all levels for its systematic, utilitarian, and highly legible characteristics. 

Headings use tight letter-spacing and heavy weights to create a sense of importance and SEO-friendly structure. Body text utilizes a generous 1.5x line height to ensure medical information is easy to consume for patients of all ages. Mobile typography scales down significantly to ensure long service names and dental terms do not break layout boundaries.

## Layout & Spacing
The layout follows a **Fixed Grid** model on desktop (1200px max-width) and a fluid 4-column model on mobile. 

A strict 8px base grid governs all spacing. Section vertical padding is intentionally large (80px+) to maintain the "clean clinic" feel and prevent the interface from feeling cluttered. Form fields and service lists use a "stack-md" (16px) vertical rhythm to ensure touch targets are accessible for mobile users.

## Elevation & Depth
This design system avoids heavy shadows to maintain a clean, flat, "medical-grade" aesthetic. Depth is communicated via **Tonal Layers** and **Low-contrast outlines**.

- **Level 0 (Base):** White (#FFFFFF) for the primary canvas.
- **Level 1 (Cards):** Ice Blue (#F8FAFC) backgrounds with a 1px border in a slightly darker neutral (#E2E8F0).
- **Interactive:** A subtle, highly diffused ambient shadow (10% opacity Primary color) is applied only to primary CTAs and active state cards to suggest clickability without breaking the clinical flatness.

## Shapes
The design system uses **Soft** roundedness (4px/0.25rem). 

This subtle rounding removes the "aggression" of sharp corners while maintaining a disciplined, professional structure. It avoids the playfulness of pill-shapes, which can feel too casual for a healthcare environment, favoring a precise, modern aesthetic for buttons, input fields, and containers.

## Components

### Buttons
- **Primary CTA:** Mint Green (#2ECC71) background with White text. Bold weight. Used for "Book Appointment."
- **Secondary:** Transparent with Navy Blue (#1B3A6B) border and text. Used for "Learn More" or "View Services."

### Input Fields
Inputs use a 1px slate-200 border. On focus, the border shifts to Navy Blue with a 2px offset ring. Labels are always persistent above the field for accessibility.

### Cards (Service/Doctor)
Cards utilize a subtle light gray background (#F8FAFC) instead of shadows. They feature high-quality professional photography with 4px corner radii and clear "Headline-md" titles.

### Iconography
Icons should be **Line Art** style with a consistent 2px stroke width. Use Navy Blue for functional icons (Phone, Location) and Mint Green for health-related icons (Tooth, Shield, Sparkle) to reinforce the association between the color and dental wellness.

### Status Chips
Used for appointment availability. 
- **Available:** Light Green background with Dark Green text.
- **Booked:** Light Gray background with Dark Gray text.