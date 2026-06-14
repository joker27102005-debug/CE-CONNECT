---
name: Academic Insight
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
  on-surface-variant: '#45464d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#006a61'
  on-secondary: '#ffffff'
  secondary-container: '#86f2e4'
  on-secondary-container: '#006f66'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#271901'
  on-tertiary-container: '#98805d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#89f5e7'
  secondary-fixed-dim: '#6bd8cb'
  on-secondary-fixed: '#00201d'
  on-secondary-fixed-variant: '#005049'
  tertiary-fixed: '#fcdeb5'
  tertiary-fixed-dim: '#dec29a'
  on-tertiary-fixed: '#271901'
  on-tertiary-fixed-variant: '#574425'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Newsreader
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Newsreader
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Newsreader
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Newsreader
    fontSize: 24px
    fontWeight: '500'
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
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
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
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
  section-gap: 80px
---

## Brand & Style

The design system is engineered to project **authority, clarity, and intellectual rigor**. It serves as a bridge between traditional academic excellence and modern digital consumption, tailoring its experience to faculty, students, and institutional partners.

The visual style is **Corporate / Modern** with a strong **Editorial** influence. It prioritizes content hierarchy and readability, using significant whitespace to prevent cognitive overload. The aesthetic is "Newspaper 2.0"—clean, structured, and intentional. Every element is designed to feel like a curated piece of a larger institutional narrative, avoiding the cluttered noise of typical social feeds in favor of a calm, focused reading environment.

## Colors

The palette is anchored by **Deep Navy (#0F172A)**, which provides the "weight" and authority expected of an academic institution. This is contrasted against **Vibrant Teal (#0D9488)** for primary actions and interactive elements, signaling progress and innovation. **Burnt Orange (#EA580C)** is used sparingly as an accent for urgent notifications, deadlines, or high-priority calls to action.

The background ecosystem relies on a range of cool grays and crisp whites to maintain a high-contrast, accessible reading experience. Secondary backgrounds utilize soft tints of the primary blue to create subtle sections without breaking the flow of the layout.

## Typography

This design system utilizes a **dual-typeface strategy** to balance tradition with utility. 

**Newsreader** is employed for headlines and display text. Its serif characteristics evoke the feeling of a printed journal or university press, establishing immediate credibility. 

**Inter** is the workhorse for all body copy, navigation, and UI labels. Its high x-height and neutral design ensure maximum legibility across all device sizes. For long-form newsletter content, `body-lg` is the preferred choice to reduce eye strain. Labels and metadata (like "5 min read" or "Department Name") should use the uppercase `label-md` style to provide clear structural markers.

## Layout & Spacing

The layout follows a **Fixed-Grid** model on desktop, centering content within a 1280px container to ensure optimal line lengths for reading. On mobile, it transitions to a fluid single-column layout.

- **The Grid:** A 12-column system is used for the "Magazine" dashboard. Featured stories span 8 columns, while secondary sidebars or "trending" lists span 4.
- **Rhythm:** An 8px base unit governs all padding and margins. 
- **White Space:** To maintain the "Modern News" feel, vertical spacing between sections (`section-gap`) is generous. Cards should have substantial internal padding (32px) to let imagery and text breathe.

## Elevation & Depth

Hierarchy is established through **Tonal Layering** and **Low-Contrast Outlines** rather than heavy shadows. 

1.  **Base Layer:** The main page background is white (#FFFFFF) or ultra-light gray (#F8FAFC).
2.  **Card Layer:** Cards use a subtle 1px border (#E2E8F0). On hover, they gain a very soft, diffused ambient shadow (0px 4px 20px rgba(15, 23, 42, 0.05)) to indicate interactivity.
3.  **Overlay Layer:** Modals or navigation dropdowns use a crisp border and a more defined shadow to separate them from the content beneath.

Avoid using physical textures or skeuomorphic effects. The "depth" comes from the logical stacking of information.

## Shapes

The design system uses **Soft (0.25rem)** roundedness. This subtle rounding softens the clinical edge of the "Deep Navy" palette while maintaining a professional, structured appearance. 

- **Buttons & Inputs:** Use the standard 0.25rem (4px) radius.
- **Content Cards:** May scale up to `rounded-lg` (8px) to create a clear container for imagery.
- **Category Chips:** Use a full pill shape to distinguish them from interactive buttons or cards.

## Components

### Buttons
Primary buttons use the Teal background with white text. Secondary buttons are "Ghost" style (transparent background, 1px navy border). All buttons use `label-md` typography for a disciplined, formal look.

### Newsletter Cards
Cards are the primary molecule of the design system. They must include:
- A high-quality cover image with a consistent aspect ratio (16:9).
- A category label in the Teal secondary color.
- A serif headline (`headline-md`).
- Metadata (Author, Date, Read time) in `caption` style.

### Inputs
Search bars and subscription fields use a white background, a 1px gray border, and 16px horizontal padding. On focus, the border shifts to the primary Navy color with a 2px outer "halo" of light teal.

### Chips & Tags
Used for academic departments (e.g., "Engineering," "Arts"). These are small, pill-shaped elements with light background tints of the primary color to keep them subordinate to the main headlines.

### Lists
"Quick Read" lists use a simple vertical layout with a thin separator line and no icons, relying on pure typography and spacing to denote hierarchy.