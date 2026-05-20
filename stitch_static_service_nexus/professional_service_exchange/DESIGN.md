---
name: Professional Service Exchange
colors:
  surface: '#fcf8ff'
  surface-dim: '#dcd8e5'
  surface-bright: '#fcf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f2ff'
  surface-container: '#f0ecf9'
  surface-container-high: '#eae6f4'
  surface-container-highest: '#e4e1ee'
  on-surface: '#1b1b24'
  on-surface-variant: '#464555'
  inverse-surface: '#302f39'
  inverse-on-surface: '#f3effc'
  outline: '#777587'
  outline-variant: '#c7c4d8'
  surface-tint: '#4d44e3'
  primary: '#3525cd'
  on-primary: '#ffffff'
  primary-container: '#4f46e5'
  on-primary-container: '#dad7ff'
  inverse-primary: '#c3c0ff'
  secondary: '#006c49'
  on-secondary: '#ffffff'
  secondary-container: '#6cf8bb'
  on-secondary-container: '#00714d'
  tertiary: '#7e3000'
  on-tertiary: '#ffffff'
  tertiary-container: '#a44100'
  on-tertiary-container: '#ffd2be'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#0f0069'
  on-primary-fixed-variant: '#3323cc'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#ffdbcc'
  tertiary-fixed-dim: '#ffb695'
  on-tertiary-fixed: '#351000'
  on-tertiary-fixed-variant: '#7b2f00'
  background: '#fcf8ff'
  on-background: '#1b1b24'
  surface-variant: '#e4e1ee'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-h1:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-h1-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-h2:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-h3:
    fontFamily: Inter
    fontSize: 24px
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
  label-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
  label-xs:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
---

## Brand & Style

The design system is engineered to facilitate trust, efficiency, and clarity in a high-stakes service marketplace. The brand personality is **Professional, Reliable, and Empowering**, aiming to evoke a sense of security for both service providers and consumers. 

The visual style follows a **Corporate/Modern** aesthetic with a focus on high-utility components. It prioritizes information density and legible hierarchies over decorative flair. The interface utilizes generous whitespace and a rigorous grid to ensure that users can navigate complex service listings, booking flows, and messaging interfaces with minimal cognitive load. The emotional response should be one of "effortless competence"—the platform disappears, leaving only the value of the service exchange.

## Colors

The color palette is anchored in high-contrast pairings to ensure WCAG 2.1 accessibility compliance. 

- **Primary (Indigo):** Used for primary actions, navigational cues, and active interactive states. It represents the "engine" of the platform.
- **Secondary (Emerald):** Reserved for success states, verified badges, and secondary highlights that signify positive growth or completed transactions.
- **Accent (Amber):** Strategically applied to ratings, "Featured" tags, and urgency markers to draw the eye without overwhelming the primary hierarchy.
- **Neutral:** A range of grays from the deep `Neutral Dark` (typography and icons) to the soft `Neutral Light` (background fills and stroke colors) provides a grounded, stable environment for the vibrant brand colors.

## Typography

This design system uses **Inter** as a singular, systematic typeface to ensure maximum legibility across all viewport sizes and device types. 

Headings use a Bold (700) or Semi-Bold (600) weight with slight negative letter-spacing to create a strong, authoritative presence. Body copy is set at 16px for standard reading, with a generous 1.5 line height to accommodate long-form service descriptions. Small labels and "all-caps" utility text use a heavier weight to maintain readability at reduced scales.

## Layout & Spacing

The layout is built on a **12-column fluid grid** for desktop and tablet, transitioning to a single-column stack on mobile devices. 

- **Desktop (1024px+):** 12 columns, 24px gutters, max-width 1280px.
- **Tablet (768px-1023px):** 8 columns, 16px gutters.
- **Mobile (Up to 767px):** 4 columns (or single stack), 16px gutters and margins.

Spacing follows a strict 4px-base-8px increment scale. Use `md` (16px) for standard internal padding within cards and `lg` (24px) for vertical separation between distinct sections.

## Elevation & Depth

Visual hierarchy in this design system is established through a combination of **Tonal Layers** and **Ambient Shadows**.

1.  **Level 0 (Background):** The `#FFFFFF` base.
2.  **Level 1 (Subtle Inset):** Used for input fields and search bars, utilizing a 1px border in `#E5E7EB`.
3.  **Level 2 (Raised Cards):** The standard surface for service listings. It uses a very soft, diffused shadow: `0px 4px 6px -1px rgba(0, 0, 0, 0.05), 0px 2px 4px -1px rgba(0, 0, 0, 0.03)`.
4.  **Level 3 (Overlay/Modal):** Used for dropdowns and pop-overs, featuring a more pronounced shadow to clearly separate the element from the content below.

Avoid heavy dark shadows; the goal is to create "lift" through soft lighting rather than harsh contrast.

## Shapes

The shape language is characterized by **softened geometry**. 

- **Standard Components:** Buttons and input fields use a `0.5rem` (8px) radius.
- **Primary Containers:** Following the design requirement, all service cards and prominent containers must use a **12px (0.75rem)** border radius to create a distinctive, approachable silhouette.
- **Tags/Badges:** Use a fully rounded "pill" shape (999px) to distinguish them from interactive buttons.

## Components

### Buttons
- **Primary:** Solid Indigo (#4F46E5) with white text. High-emphasis for "Book Now" or "Post Job."
- **Secondary:** Outlined Indigo or Solid Emerald (#10B981) for success-oriented secondary actions like "Message Provider."
- **Ghost:** No background, Indigo text. Used for "Cancel" or "View More" actions to reduce visual noise.

### Cards
Cards are the primary vehicle for content. They must include a 12px border radius, the Level 2 ambient shadow, and a 1px border (#F3F4F6) to ensure definition against white backgrounds.

### Inputs
Search bars and form fields use a 16px internal horizontal padding, 8px vertical padding, and a 1px border (#D1D5DB). On focus, the border color shifts to Indigo with a subtle outer glow.

### Chips & Badges
- **Verified Badge:** Emerald background (10% opacity) with Emerald text.
- **Rating Tag:** Amber text with a small leading star icon.
- **Category Chip:** Neutral Light background with Neutral Dark text.

### Lists
Service lists should maintain a consistent 16px vertical gap. Items use a subtle divider line (#F3F4F6) only if not contained within individual cards.