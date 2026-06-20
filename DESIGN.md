---
name: Agri-Tech Precision
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#44483c'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#74796b'
  outline-variant: '#c4c8b8'
  surface-tint: '#486725'
  primary: '#284404'
  on-primary: '#ffffff'
  primary-container: '#3e5c1b'
  on-primary-container: '#afd384'
  inverse-primary: '#aed283'
  secondary: '#166395'
  on-secondary: '#ffffff'
  secondary-container: '#89c7ff'
  on-secondary-container: '#005381'
  tertiary: '#2c4400'
  on-tertiary: '#ffffff'
  tertiary-container: '#3e5d00'
  on-tertiary-container: '#a1da43'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c9ef9c'
  primary-fixed-dim: '#aed283'
  on-primary-fixed: '#0f2000'
  on-primary-fixed-variant: '#324f0e'
  secondary-fixed: '#cde5ff'
  secondary-fixed-dim: '#95ccff'
  on-secondary-fixed: '#001d32'
  on-secondary-fixed-variant: '#004a75'
  tertiary-fixed: '#baf55b'
  tertiary-fixed-dim: '#9fd840'
  on-tertiary-fixed: '#121f00'
  on-tertiary-fixed-variant: '#344e00'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  headline-display:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Work Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
  caption:
    fontFamily: Work Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
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
  margin-desktop: 64px
  margin-mobile: 20px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  stack-xl: 64px
---

## Brand & Style

The brand personality is authoritative yet forward-thinking, bridging the gap between traditional agricultural wisdom and cutting-edge IoT technology. This design system targets the academic community, government stakeholders, and industry partners who value precision, sustainability, and transparency.

The visual style is **Corporate / Modern** with a lean toward **Minimalism**. It prioritizes information density and legibility, using generous whitespace to allow complex research data to breathe. To reflect the project's technological core, subtle "circuitry-meets-organic" motifs are used—line-based patterns that mimic both leaf veins and PCB traces. This creates a professional atmosphere that feels established and scientifically rigorous.

## Colors

The palette is derived from the intersection of nature and technology. 

- **Primary (Olive Green):** A deep, scholarly green representing the earth, longevity, and the olive groves at the center of the research.
- **Secondary (Tech Blue):** A precise, trustworthy blue that denotes the IoT, data science, and engineering components of the project.
- **Tertiary (Sprout Green):** A vibrant, high-energy green used sparingly for calls-to-action and highlighting key data points.
- **Neutral (Cloud & Slate):** A foundation of clean grays and off-whites ensures a light, airy feel that doesn't overwhelm the reader with heavy blocks of color.

Backgrounds should primarily be white or very light gray (`#F8F9FA`) to maintain a clean academic standard.

## Typography

This system utilizes a trio of typefaces to delineate different information types:

1. **Hanken Grotesk (Headlines):** A sharp, contemporary sans-serif that provides a clean and professional structure for page titles and section headers.
2. **Work Sans (Body):** Optimized for screen readability at various sizes, used for the main research text, abstracts, and reports. Its neutral character ensures that the focus remains on the content.
3. **JetBrains Mono (Technical Labels):** Used for metadata, sensor readings, and small technical labels. This monospaced font reinforces the IoT/Technology narrative.

For mobile, headlines are scaled down slightly to maintain hierarchy without causing excessive line wrapping.

## Layout & Spacing

The layout follows a **Fixed Grid** system for desktop to maintain a professional, "published" feel, centering the content with a maximum width of 1200px. 

- **Desktop:** A 12-column grid. Research papers and dense text should occupy a central 8-column span for optimal line length, while sidebars or data visualizations can occupy the remaining 4 columns.
- **Tablet:** 8-column grid with reduced margins (32px).
- **Mobile:** 4-column fluid grid.

Spacing follows a consistent vertical rhythm based on multiples of 8px. Large sections of content are separated by `stack-xl` to emphasize the clean, airy aesthetic.

## Elevation & Depth

Visual hierarchy is established through **Low-contrast outlines** and **Tonal layers** rather than heavy shadows.

- **Surface Tiers:** The primary background is white. Secondary information containers (like sensor data cards) use a very light gray or a pale tint of the tech blue.
- **Borders:** Instead of shadows, use 1px solid borders in a soft neutral (e.g., `#E9ECEF`) to define card boundaries.
- **Subtle Depth:** A single, extremely soft ambient shadow (0px 4px 20px, 5% opacity) may be used on the primary "Call to Action" or the main navigation bar to provide a slight lift from the page.

## Shapes

The shape language is **Soft** and restrained.

- **Corners:** A base radius of `0.25rem` (4px) is applied to buttons, input fields, and small UI elements. This provides a modern touch without appearing overly "bubbly" or informal.
- **Large Components:** Cards and images utilize `0.5rem` (8px) for a more pronounced but still professional framing.
- **Icons:** Use linear, 2px stroke-width icons that follow the same corner radius logic. Avoid filled icons unless used for active states.

## Components

### Buttons
- **Primary:** Solid Olive Green (`primary_color_hex`) with white text. High contrast for key actions like "View Report."
- **Secondary:** Outlined Blue (`secondary_color_hex`) with a 1px border. Used for navigation and less critical actions.

### Data Cards
Cards should be white with a 1px neutral border. Headers within cards should use the `label-caps` (JetBrains Mono) style to indicate technical data points.

### Lists & Tables
Research data should be presented in clean, striped tables using the neutral color for alternating rows. Avoid vertical borders; use horizontal dividers only to maintain a clean, modern look.

### Input Fields
Strictly rectangular with a `0.25rem` corner radius. Use the `secondary_color_hex` for the focus state to signify "active tech."

### Interactive Motifs
Incorporate subtle SVG patterns in the background of hero sections or footer areas. These patterns should be light gray or very pale green, featuring intersecting lines and nodes that suggest a network of trees or sensors.