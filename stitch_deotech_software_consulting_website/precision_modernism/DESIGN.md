---
name: Precision Modernism
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#44474e'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#74777f'
  outline-variant: '#c4c6cf'
  surface-tint: '#485f84'
  primary: '#031f41'
  on-primary: '#ffffff'
  primary-container: '#1d3557'
  on-primary-container: '#879ec6'
  inverse-primary: '#b0c7f1'
  secondary: '#bb0014'
  on-secondary: '#ffffff'
  secondary-container: '#e41f25'
  on-secondary-container: '#fffbff'
  tertiary: '#002234'
  on-tertiary: '#ffffff'
  tertiary-container: '#003953'
  on-tertiary-container: '#6fa4c7'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d5e3ff'
  primary-fixed-dim: '#b0c7f1'
  on-primary-fixed: '#001b3c'
  on-primary-fixed-variant: '#30476a'
  secondary-fixed: '#ffdad6'
  secondary-fixed-dim: '#ffb4ab'
  on-secondary-fixed: '#410002'
  on-secondary-fixed-variant: '#93000d'
  tertiary-fixed: '#c7e7ff'
  tertiary-fixed-dim: '#98cdf2'
  on-tertiary-fixed: '#001e2e'
  on-tertiary-fixed-variant: '#064c6b'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-xl:
    fontFamily: Inter
    fontSize: 60px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-xl-mobile:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.01em
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
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  section-padding: 120px
---

## Brand & Style

The design system is rooted in **Corporate Modernism**, blending the authoritative presence of a consultancy with the agility of a software powerhouse. It evokes a sense of **Expertise, Trust, and Technological Foresight**.

The visual language is defined by high-density whitespace, crisp typography, and a "precision-first" aesthetic. It avoids decorative clutter in favor of functional clarity, using vibrant accents to highlight innovation and key user actions. The emotional response is one of reliability—a partner that is both established and cutting-edge.

## Colors

The palette is anchored by **Deep Navy (#1D3557)**, representing institutional trust and depth. **Vibrant Red (#E31E24)** is used strategically as a high-energy catalyst for calls-to-action and critical data points.

*   **Primary (Navy):** Used for headers, primary buttons, and foundational UI elements.
*   **Secondary (Red):** Used for highlights, active states, and primary CTAs to drive conversion.
*   **Tertiary (Slate Blue):** A supporting bridge color for secondary information or decorative icons.
*   **Surface Colors:** The UI utilizes a "Pure White" base (#FFFFFF) with "Ghost Gray" (#F8FAFC) for sectional backgrounds to create subtle visual separation without heavy borders.

## Typography

This design system utilizes **Inter** exclusively to maintain a systematic, highly legible, and neutral tone. The typographic hierarchy relies on significant weight contrast and tight letter-spacing in headlines to achieve a "tech-editorial" feel.

Large display sizes should use negative letter-spacing to feel more cohesive. For body text, standard tracking ensures maximum readability during long-form consultancy reports or service descriptions. Labels use a slight tracking increase and medium weight to stand out at small scales.

## Layout & Spacing

The layout follows a **12-column fluid grid** with a maximum container width of 1280px to ensure readability on ultra-wide monitors. 

**Spacing Principles:**
*   **Generous Margins:** Vertical section padding is set to 120px to allow the "Innovation" value to breathe, preventing the corporate content from feeling dense.
*   **Grid Logic:** Gutters are fixed at 24px. Elements should snap to the grid, but use internal padding (stack-lg) to maintain the clean aesthetic.
*   **Responsive Reflow:** On tablet, the grid shifts to 8 columns. On mobile, it collapses to 4 columns with margins reduced to 20px.

## Elevation & Depth

Depth is achieved through **Ambient Shadows** and **Tonal Layering** rather than heavy outlines. 

*   **Soft Elevation:** Used for cards and dropdowns. The shadow is highly diffused (blur: 24px) with low opacity (10%) using a Navy-tinted neutral color to avoid a "dirty" gray look.
*   **Interactive Lift:** On hover, cards should transition to a slightly deeper shadow and a subtle 2px vertical lift to provide tactile feedback.
*   **Surface Layers:** Use #F8FAFC for background containers to sit "behind" white primary cards, creating a natural hierarchy without requiring shadows on every element.

## Shapes

The shape language balances approachability with professional structure. 

*   **Base Radius:** Standard UI elements like inputs and small buttons use a 0.5rem (8px) radius.
*   **Container Radius:** Feature cards and larger containers (e.g., "Expertise Cards") utilize a **1rem (16px)** radius, as specified to create a modern, friendly software aesthetic.
*   **Strictness:** Never use fully sharp corners or full pills (except for tags/chips), as the 16px radius strikes the optimal balance for a consultancy brand.

## Components

### Buttons
*   **Primary:** Navy background, white text. Bold and authoritative. 16px internal horizontal padding.
*   **Accent (CTA):** Vibrant Red background. Used sparingly for "Get Started" or "Contact Us."
*   **Ghost:** Transparent background with a Navy or Red border (2px). Used for secondary navigation.

### Cards (Expertise & Services)
Cards feature a white background, 16px corner radius, and the "Soft Elevation" shadow. They should include a subtle 1px border (#E2E8F0) to ensure definition on white backgrounds.

### Input Fields
Inputs are minimal: white background, 8px radius, and a 1px border. On focus, the border transitions to Navy with a subtle 4px outer glow in the primary color at 10% opacity.

### Chips & Tags
Used for service categories (e.g., "AI Strategy", "Cloud Ops"). These use a light tint of the Tertiary color (#457B9D at 10% opacity) with Navy text to keep the interface professional yet categorized.

### Progress Indicators
Thin, 4px height bars using the Vibrant Red color to represent "Technology" and "Innovation" metrics or loading states.