---
name: Lumina Tech Persona
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#c7c4d7'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#908fa0'
  outline-variant: '#464554'
  surface-tint: '#c0c1ff'
  primary: '#c0c1ff'
  on-primary: '#1000a9'
  primary-container: '#8083ff'
  on-primary-container: '#0d0096'
  inverse-primary: '#494bd6'
  secondary: '#ddb7ff'
  on-secondary: '#490080'
  secondary-container: '#6f00be'
  on-secondary-container: '#d6a9ff'
  tertiary: '#ffb0cd'
  on-tertiary: '#640039'
  tertiary-container: '#f751a1'
  on-tertiary-container: '#570032'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e1e0ff'
  primary-fixed-dim: '#c0c1ff'
  on-primary-fixed: '#07006c'
  on-primary-fixed-variant: '#2f2ebe'
  secondary-fixed: '#f0dbff'
  secondary-fixed-dim: '#ddb7ff'
  on-secondary-fixed: '#2c0051'
  on-secondary-fixed-variant: '#6900b3'
  tertiary-fixed: '#ffd9e4'
  tertiary-fixed-dim: '#ffb0cd'
  on-tertiary-fixed: '#3e0022'
  on-tertiary-fixed-variant: '#8c0053'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  display:
    fontFamily: Plus Jakarta Sans
    fontSize: 64px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Plus Jakarta Sans
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
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  label-caps:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1.0'
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
  section-gap: 120px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

The design system is engineered for the high-achieving Computer Science student, balancing academic rigor with creative technical flair. The brand personality is **Visionary, Precise, and Energetic**. It aims to evoke a sense of "digital craftsmanship"—where clean code meets high-end aesthetics.

The style is a hybrid of **Modern Corporate** and **Glassmorphism**. It utilizes a "Deep Tech" aesthetic characterized by layered transparency, vibrant accent glows, and rigorous grid alignment. This ensures the portfolio feels like a premium software product rather than just a static resume.

- **Primary Audience:** Technical recruiters, engineering managers, and open-source collaborators.
- **Emotional Response:** Trust in technical competence, excitement about innovation, and appreciation for attention to detail.

## Colors

This design system uses a **Spectrum Gradient** approach to represent the versatility of full-stack engineering. 

### Palette Logic
- **Primary (Indigo):** Represents stability and logic. Used for primary actions and key brand elements.
- **Secondary (Purple):** Represents creativity and integration. Used for accents and secondary highlights.
- **Tertiary (Pink):** Represents energy and innovation. Used sparingly for high-impact status or hover states.
- **Neutral:** A deep navy-black (`#020617`) provides the high-contrast foundation needed for "glow" effects.

### Color Modes
- **Dark Mode (Default):** Uses deep navy backgrounds with 5% opacity white overlays for card surfaces. Gradients act as "light sources" behind translucent glass layers.
- **Light Mode:** Shifts to an off-white/slate-50 background. Gradients are softened and used as subtle border strokes or very light background washes (2% opacity) to maintain professionalism.

## Typography

The typography strategy emphasizes **readability and technical identity**.

1.  **Headlines (Plus Jakarta Sans):** Chosen for its modern, slightly geometric curves that feel welcoming yet professional. Use `display` for hero sections with gradient text clipping.
2.  **Body (Inter):** The industry standard for UI. Highly legible at small sizes, ensuring that project descriptions and technical resumes are easy to scan.
3.  **Labels & Snippets (JetBrains Mono):** Used for "Metadata" (dates, tech stack tags, or small code snippets). This reinforces the "Developer" persona.

**Weight Usage:** 
Use `Bold` (700+) exclusively for titles. Use `Regular` (400) for all long-form text to prevent visual fatigue on dark backgrounds.

## Layout & Spacing

The layout follows a **structured fluid grid** with a maximum content width of 1200px to ensure readability on ultra-wide monitors.

### Grid System
- **Desktop:** 12-column grid. Projects typically span 4 or 6 columns.
- **Tablet:** 8-column grid.
- **Mobile:** 4-column grid with 16px side margins.

### Spacing Philosophy
The system uses a large "Section Gap" (120px) to give content room to breathe, emphasizing the "Premium" nature of the design. Vertical rhythm is maintained using an 8px base unit. Components should use `stack-md` (16px) for internal padding to maintain a clean, airy feel.

## Elevation & Depth

Depth is achieved through **Luminous Layering** rather than traditional heavy shadows.

- **Level 0 (Background):** Deepest color (`#020617`).
- **Level 1 (Cards):** Semi-transparent surfaces (White at 5% opacity in dark mode) with a `16px` backdrop-blur. 
- **Level 2 (Active/Hover):** Increase surface opacity to 8% and add a very thin (`1px`) border using a linear gradient (Primary to Secondary) at 30% opacity.
- **Glow Accents:** Use large, blurred radial gradients (200px - 400px radius) positioned *behind* the Level 1 cards to create a "sub-surface" lighting effect. This mimics the glow of a high-end backlit keyboard.

## Shapes

The shape language is **Soft-Geometric**.

- **Cards & Sections:** Use `rounded-lg` (1rem / 16px) to maintain a modern, friendly appearance.
- **Buttons:** Use `pill-shaped` (full radius) for primary CTAs to distinguish them from content cards.
- **Inputs:** Use `rounded-md` (0.5rem / 8px) for a more structured, tool-like feel.
- **Borders:** Keep borders ultra-thin (1px). In dark mode, borders should be slightly lighter than the surface; in light mode, they should be a soft gray-blue.

## Components

### Buttons
- **Primary:** Gradient background (Indigo to Purple). White text. No shadow, but a subtle outer glow on hover.
- **Secondary:** Transparent background with a gradient border. Text uses the primary color.
- **Tertiary/Ghost:** No background or border. Used for navigation links.

### Cards (Project/Experience)
- **Structure:** 1px gradient border, backdrop blur of 12px, and 16px internal padding.
- **Interaction:** On hover, the card should lift slightly (-4px Y-axis) and the border opacity should increase.

### Chips (Tech Stack)
- Small, `label-code` typography. 
- Background: Primary color at 10% opacity. 
- Border: Primary color at 20% opacity.

### Input Fields
- Dark, recessed background.
- On focus, the border transitions to a vibrant gradient and a subtle 4px glow is applied to the perimeter.

### Navigation Bar
- Fixed to top.
- Floating "Island" style or full-width with a high backdrop-blur and a bottom-border gradient separator.