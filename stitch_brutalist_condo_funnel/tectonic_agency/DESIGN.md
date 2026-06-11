---
name: Tectonic Agency
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#4c4546'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#7e7576'
  outline-variant: '#cfc4c5'
  surface-tint: '#5e5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1b1b1b'
  on-primary-container: '#848484'
  inverse-primary: '#c6c6c6'
  secondary: '#aa3000'
  on-secondary: '#ffffff'
  secondary-container: '#d43f00'
  on-secondary-container: '#fffbff'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1a1c1c'
  on-tertiary-container: '#838484'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2e2e2'
  primary-fixed-dim: '#c6c6c6'
  on-primary-fixed: '#1b1b1b'
  on-primary-fixed-variant: '#474747'
  secondary-fixed: '#ffdbd0'
  secondary-fixed-dim: '#ffb59e'
  on-secondary-fixed: '#3a0b00'
  on-secondary-fixed-variant: '#852400'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-lg:
    fontFamily: Anton
    fontSize: 120px
    fontWeight: '400'
    lineHeight: 110px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Anton
    fontSize: 64px
    fontWeight: '400'
    lineHeight: 60px
  headline-xl:
    fontFamily: Anton
    fontSize: 64px
    fontWeight: '400'
    lineHeight: 72px
  headline-lg:
    fontFamily: Anton
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 52px
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '800'
    lineHeight: 32px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.1em
  data-mono:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
spacing:
  unit: 4px
  border-thick: 4px
  border-thin: 2px
  gutter: 24px
  margin-edge: 40px
  section-gap: 120px
---

## Brand & Style
This design system employs a **Modern Brutalist** aesthetic tailored for the high-end real estate market. It rejects the soft, apologetic curves of traditional luxury in favor of architectural strength, raw material honesty, and uncompromising structural clarity. The target audience consists of bold investors and urbanites who view property as both a functional asset and a design statement.

The emotional response is one of stability, authority, and "unfiltered" transparency. We achieve this through:
- **Raw Materials:** Use of subtle concrete grain and stone textures in background layers.
- **Architectural Rigor:** Heavy use of grids and structural lines that mimic floor plans and blueprints.
- **Aggressive Hierarchy:** Dramatic scale shifts between oversized headlines and dense data points.
- **Luxury Contrast:** Combining the "low-fi" brutalist structure with "high-fidelity" professional architectural photography.

## Colors
The palette is rooted in a high-contrast, industrial foundation with a singular, high-energy focal point.

- **Primary (Ink):** Used for all structural borders, primary text, and solid backgrounds. It represents the "lead" of a pencil or the steel of a frame.
- **Secondary (International Orange):** A sharp, high-visibility accent used exclusively for calls to action, status indicators (e.g., "Available Now"), and interactive highlights.
- **Neutral/Surface (Concrete & Chalk):** The background is a very light grey (#F2F2F2) rather than pure white to reduce eye strain and provide a surface for subtle texture overlays. 
- **Functional Blacks:** Various shades of deep grey/black are used to create depth without relying on shadows.

## Typography
Typography is the primary visual driver of this design system. We use a three-tier font strategy:
1. **The Statement (Anton):** A heavy, condensed sans-serif used for massive property titles and hero sections. It should feel industrial and loud.
2. **The Narrative (Hanken Grotesk):** A clean, contemporary sans-serif for body descriptions and sub-headlines, providing high legibility against the aggressive display type.
3. **The Specification (JetBrains Mono):** A monospaced font used for technical data (sq ft, price, coordinates). This reinforces the "blueprint" and "raw data" feel of the agency.

## Layout & Spacing
The layout follows a strict **Fixed Grid** philosophy inspired by architectural drafting. 

- **The Grid:** A 12-column grid on desktop with 0px gutters between structural containers to allow borders to merge, but 24px internal padding within those containers.
- **Thick Borders:** Every major component is wrapped in a 4px black border. Nested elements use 2px borders.
- **Padding:** Use generous internal padding (min 32px) to ensure that despite the heavy borders, the content has "breathing room" to appear premium.
- **Mobile Adaption:** On mobile, the 12-column grid collapses to a 2-column grid. The 4px border remains constant to maintain the "heavy" brand feel even on smaller screens.

## Elevation & Depth
This design system explicitly avoids soft shadows or blurs. Depth is communicated through **Structural Layering** and **Hard Offsets**:
- **Hard Shadows:** Instead of blurs, use "Block Shadows"—solid black offsets (e.g., 8px down, 8px right) to lift cards or buttons off the page.
- **Z-Axis Stacking:** Elements do not float; they sit on top of one another like sheets of plywood or slabs of concrete.
- **Inverted Surfaces:** Use high-contrast color flips (Black background with White text) to denote a change in depth or a "drilled-down" state.

## Shapes
The shape language is **completely sharp (0px radius)**. Curves are non-existent in the UI framework, reflecting the hard angles of modern skyscraper architecture. 
- **Intersections:** Borders should meet at perfect 90-degree angles.
- **Image Treatment:** Photography must also maintain sharp corners. For a "raw" effect, images can be framed with a secondary 1px internal border to look like technical documents.

## Components
- **Buttons:** Rectangular with 4px black borders. Primary state is Black with White text. Hover state shifts to the Accent color (#FF4D00) with a 4px hard block shadow.
- **Cards:** Large containers for property listings. Features a 4px border. The price is always displayed in the top-right corner using `data-mono` inside a solid black "badge" box.
- **Inputs:** Simple boxes with 2px borders. On focus, the border weight increases to 4px. No glows or soft highlights.
- **Chips/Tags:** Small rectangular boxes using `label-caps`. Used for property status (e.g., "SOLD", "OFF-PLAN").
- **Property Grids:** Technical specs (beds, baths, area) should be separated by vertical 1px lines, resembling a ledger or data sheet.
- **Navigation:** A heavy top-bar where links are separated by physical "|" pipe characters, maintaining the brutalist, typewriter-adjacent feel.