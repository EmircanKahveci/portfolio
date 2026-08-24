---
name: Executive Slate
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#464555'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#777587'
  outline-variant: '#c7c4d8'
  surface-tint: '#4d44e3'
  primary: '#3525cd'
  on-primary: '#ffffff'
  primary-container: '#4f46e5'
  on-primary-container: '#dad7ff'
  inverse-primary: '#c3c0ff'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
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
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#ffdbcc'
  tertiary-fixed-dim: '#ffb695'
  on-tertiary-fixed: '#351000'
  on-tertiary-fixed-variant: '#7b2f00'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  display-sm:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.02em
  h1:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  h2:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  h3:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  h1-mobile:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 32px
  sidebar-width: 260px
---

## Brand & Style

The brand personality is authoritative yet accessible, designed for high-productivity environments where clarity and focus are paramount. The target audience includes data analysts, project managers, and administrators who require a tool that feels reliable and "out of the way."

The design system adopts a **Modern Corporate Minimalism** style. It prioritizes information density without sacrificing legibility. The aesthetic is defined by:
- **Functional Clarity:** Removing unnecessary ornamentation to focus on data.
- **Card-Based Architecture:** Using distinct surfaces to group related information, creating a structured mental model.
- **Subtle Precision:** High-quality execution of borders, shadows, and alignment to evoke a sense of professional polish.
- **Intentional Whitespace:** Generous breathing room between functional groups to reduce cognitive load during complex tasks.

## Colors

The palette is anchored in a sophisticated "Slate" and "Zinc" foundation to provide a neutral backdrop for complex data visualizations.

- **Primary Action (Indigo):** Used exclusively for primary call-to-actions, active navigation states, and critical interaction points. This creates a clear visual path for the user.
- **Surface (Slate/Zinc):** Darker slate shades are reserved for text and sidebar backgrounds to provide high contrast and grounding.
- **Neutral Grays:** A range of cool grays (Slate 50 to 400) is used for backgrounds, borders, and secondary text to establish a hierarchy of information.
- **Functional Colors:** Standardized success (Emerald), warning (Amber), and error (Rose) tones are used sparingly for status indicators and feedback.

## Typography

The typography system utilizes **Inter** for its exceptional legibility in UI contexts, particularly in data-heavy tables and dashboards.

- **Scale:** A tight scale is used to maintain high information density while ensuring clear headers.
- **Weight:** Medium (500) and Semi-Bold (600) weights are used for labels and buttons to differentiate them from body copy.
- **Labels:** Small labels use an uppercase transform with slight letter-spacing to act as "meta" indicators for categories or table headers.
- **Vertical Rhythm:** Line heights are strictly optimized for the 4px baseline grid to ensure alignment across multiple columns of text.

## Layout & Spacing

This design system employs a **12-column fluid grid** for the main content area, paired with a fixed-width sidebar for navigation.

- **Grid System:** On desktop, the layout utilizes a 24px gutter. Elements typically span in multiples of 3 or 4 columns to create balanced dashboards.
- **Sidebar:** A 260px fixed sidebar on the left houses the primary navigation. It collapses to an icon-only view (64px) on smaller desktop screens.
- **Responsive Behavior:** 
    - **Desktop (>1024px):** Full sidebar, 32px page margins.
    - **Tablet (768px - 1023px):** Collapsed sidebar, 24px page margins, cards stack to 2 columns.
    - **Mobile (<767px):** Hidden sidebar (hamburger menu), 16px page margins, cards stack to a single column.
- **Spacing Rhythm:** All margins and padding must be multiples of 4px, ideally using 8px (sm), 16px (md), or 24px (lg) for most component spacing.

## Elevation & Depth

Hierarchy is established through **Tonal Layering** and **Ambient Shadows**.

- **Level 0 (Background):** The application background uses a subtle Slate-50 ($F8FAFC) to differentiate from white cards.
- **Level 1 (Cards/Surface):** Primary content containers use a white background with a 1px border in Slate-200.
- **Shadows:** A soft, diffused "Ambient Shadow" is applied to cards to lift them from the background: `0px 1px 3px 0px rgba(0, 0, 0, 0.1), 0px 1px 2px -1px rgba(0, 0, 0, 0.1)`.
- **Level 2 (Dropdowns/Modals):** Overlays use a more pronounced shadow to indicate significant elevation: `0px 10px 15px -3px rgba(0, 0, 0, 0.1), 0px 4px 6px -4px rgba(0, 0, 0, 0.1)`.

## Shapes

The shape language is consistent and "Medium-Rounded" to maintain a modern, friendly, yet professional appearance.

- **Standard Radius:** 8px (0.5rem) is the default for buttons, input fields, and small components.
- **Large Radius:** 12px (0.75rem) is used for main content cards and dashboard widgets.
- **Extra Large Radius:** 16px (1rem) is reserved for modals and large flyout panels.
- **Interactive States:** Buttons maintain their radius but may use a subtle scale-down effect (0.98) on click to feel tactile.

## Components

### Buttons
- **Primary:** Solid Indigo-600 background, white text. High contrast.
- **Secondary:** White background with Slate-200 border. Slate-700 text.
- **Ghost:** No background or border. Used for tertiary actions in tables.

### Input Fields
- White background, 1px Slate-300 border.
- On focus: 1px Indigo-500 border with a 3px Indigo-100 outer glow (ring).
- Placeholder text: Slate-400.

### Data Tables
- **Header:** Slate-50 background, uppercase Label-sm text, Slate-200 bottom border.
- **Rows:** White background, subtle hover state (Slate-50), 1px Slate-100 divider between rows.
- **Cell Padding:** 12px vertical, 16px horizontal.

### Sidebar Navigation
- **Inactive:** Slate-400 icons and text.
- **Active:** Indigo-600 icons and text with a vertical 3px Indigo-600 "pill" indicator on the far left edge.
- **Hover:** Subtle Slate-800 background change for the menu item container.

### Status Chips
- Rounded-full (pill) shape. 
- Low-saturation background with high-saturation text (e.g., Success: Emerald-50 background with Emerald-700 text).

### Cards
- White background, Slate-200 border, Level 1 shadow.
- Header section with a 1px Slate-100 bottom divider when containing titles.