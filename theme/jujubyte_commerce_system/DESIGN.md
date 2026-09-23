---
name: Jujubyte Commerce System
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#464555'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#777587'
  outline-variant: '#c7c4d8'
  surface-tint: '#4d44e3'
  primary: '#3525cd'
  on-primary: '#ffffff'
  primary-container: '#4f46e5'
  on-primary-container: '#dad7ff'
  inverse-primary: '#c3c0ff'
  secondary: '#712ae2'
  on-secondary: '#ffffff'
  secondary-container: '#8a4cfc'
  on-secondary-container: '#fffbff'
  tertiary: '#00505f'
  on-tertiary: '#ffffff'
  tertiary-container: '#006a7c'
  on-tertiary-container: '#93e8ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#0f0069'
  on-primary-fixed-variant: '#3323cc'
  secondary-fixed: '#eaddff'
  secondary-fixed-dim: '#d2bbff'
  on-secondary-fixed: '#25005a'
  on-secondary-fixed-variant: '#5a00c6'
  tertiary-fixed: '#acedff'
  tertiary-fixed-dim: '#4cd7f6'
  on-tertiary-fixed: '#001f26'
  on-tertiary-fixed-variant: '#004e5c'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 3rem
    fontWeight: '800'
    lineHeight: 3.5rem
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 2rem
    fontWeight: '700'
    lineHeight: 2.5rem
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.5rem
    fontWeight: '700'
    lineHeight: 2rem
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.25rem
    fontWeight: '700'
    lineHeight: 1.75rem
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '600'
    lineHeight: 1.5rem
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.5rem
    letterSpacing: 0em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.25rem
    letterSpacing: 0em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.75rem
    fontWeight: '400'
    lineHeight: 1rem
    letterSpacing: 0.01em
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: 1.25rem
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: 1rem
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.6875rem
    fontWeight: '700'
    lineHeight: 0.875rem
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-tablet: 2rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

The brand personality merges the high-velocity, conversion-focused utility of Latin American marketplace giants with an airy, precision-engineered digital aesthetic. It feels energetic, technologically sophisticated, highly reliable, and radically clear. 

The aesthetic is Modern Functionalist Minimalism: crisp white canvases, cool slate neutrals, and a disciplined dual-accent spectrum anchored by Electric Indigo and Vivid Violet. The user interface eliminates visual noise to prioritize product discoverability, rapid cart actions, and trustworthy checkout pathways. While utility reigns, micro-interactions and promotional badges inject moments of vibrant retail excitement without degrading layout discipline.

## Colors

The palette leverages high-contrast functional color assignments to differentiate structural navigation, dynamic commerce incentives, and transactional states:

- **Primary (`#4F46E5` - Electric Indigo):** Anchors core brand presence, primary call-to-action buttons ("Comprar Agora", "Salvar Alterações"), selected navigation tabs, and system focus rings.
- **Secondary (`#7C3AED` - Vivid Violet):** Used for promotional gradients, marketplace badges ("Queima Jujubyte"), category highlights, and merchant portal performance metrics.
- **Tertiary (`#06B6D4` - Cyber Cyan):** Reserved for technical indicators, active delivery trackers, and subtle data visualization accents in the merchant dashboard.
- **Neutral (`#0F172A` - Slate 900):** Deep, legible text contrast on backgrounds spanning `#FFFFFF` (Surface Elevated) and `#F8FAFC` (Canvas Base). Slate variants (`#64748B`, `#E2E8F0`) manage secondary metadata, dividers, and ghost borders.
- **Promotional & Status Semantics:**
  - *Success / Free Shipping (`#16A34A`):* "Frete Grátis" tags, positive inventory counts, completed payouts.
  - *Discount / Urgent Deal (`#E11D48`):* "25% OFF", lightning deals, flash sale count-downs.
  - *Warning / Low Stock (`#F59E0B`):* "Últimas unidades", pending merchant KYC.

## Typography

Plus Jakarta Sans provides geometric modernity combined with open apertures, ensuring extreme legibility across dense pricing blocks, tabular merchant data, and small screen handheld viewports.

- Use **display-lg** sparingly for hero promotional campaigns and landing headers.
- **headline-md** and **headline-sm** format catalog listing titles and dashboard analytics cards.
- **label-sm** in uppercase (`letter-spacing: 0.04em`) is optimized for commerce indicators, such as installment pricing, shipping tags, and status pills.
- Numerical price displays should enforce tabular figures (`font-variant-numeric: tabular-nums`) to prevent layout shifts during live inventory updates and dashboard metric recalculations.

## Layout & Spacing

The architecture operates on an 8-point spatial grid using a hybrid fluid grid system:

- **Customer Storefront (SPA):** 12-column layout capped at a maximum width of `1360px` with fluid column widths, shifting to 4 columns on mobile viewports (< 640px) and 8 columns on tablet devices (640px - 1024px).
- **Admin Store Portal:** Fluid dashboard shell featuring a fixed `260px` navigation rail, a `100%` flexible canvas with strict `margin-desktop` boundaries, and dense table/card arrangements.
- **Rhythm & Alignments:** Product grids deploy `space-md` gaps on mobile, transitioning to `gutter-desktop` on viewports >= 1024px. Form rows and field groupings adhere strictly to increments of `space-sm` and `space-md`.

## Elevation & Depth

Visual hierarchy uses clean tonal surfaces combined with soft, indigo-tinted ambient shadows, ensuring elements pop cleanly from `#F8FAFC` backgrounds without feeling heavy:

- **Level 0 (Flat / Baseline):** Background canvases (`#F8FAFC`) and static merchant table rows. Separation is achieved via subtle 1px border rules (`#E2E8F0`).
- **Level 1 (Card / Rest):** Default product cards, admin metric cards, and filter panels (`#FFFFFF`). Outlined with a 1px border (`#F1F5F9`) and an ambient shadow: `0 1px 3px 0 rgba(15, 23, 42, 0.04), 0 1px 2px -1px rgba(15, 23, 42, 0.04)`.
- **Level 2 (Hover / Active Overlay):** Interactive product cards on cursor hover, floating search suggestions, and dropdown menus: `0 10px 15px -3px rgba(79, 70, 229, 0.08), 0 4px 6px -4px rgba(15, 23, 42, 0.05)`, with a border color shift to `#E0E7FF`.
- **Level 3 (Modal / Cart Drawer):** Checkout side-drawers, critical operational modals, and quick-buy popovers: `0 20px 25px -5px rgba(15, 23, 42, 0.12), 0 8px 10px -6px rgba(15, 23, 42, 0.06)`, framed with a transparent dark scrim (`rgba(15, 23, 42, 0.4)` with 4px backdrop blur).

## Shapes

The system uses a balanced Level 2 (Rounded) corner geometry (`0.5rem` / `8px` baseline):

- **Inputs, Buttons, and Data Cells:** Standard radius of `8px` (`rounded-md`), establishing an approachable yet functional silhouette.
- **Product & Analytic Cards:** `12px` to `16px` (`rounded-lg` to `rounded-xl`) to soften dense content containers.
- **Status Pills, Discount Chips, and Avatar Tokens:** Pill-shaped (`rounded-full` / `9999px`) to create an immediate visual contrast against geometric card structures and data grids.

## Components

### Buttons
- **Primary CTA ("Comprar Agora", "Confirmar Pedido"):** Background `#4F46E5`, text `#FFFFFF`, font `label-lg`, radius `8px`. Hover: `#4338CA`. Active state: subtle scale transformation (`scale(0.98)`).
- **Secondary CTA ("Adicionar ao Carrinho"):** Solid `#EEF2FF` surface with `#4F46E5` text and high-contrast hover state (`#E0E7FF`).
- **Destructive / Admin Action:** `#FEE2E2` surface with `#DC2626` text, shifting to solid `#DC2626` fill upon intent confirmation.

### Badges & Chips
- **Promotion & Discount Pill:** Background `#FFF1F2`, text `#E11D48`, font `label-sm`, uppercase bold styling (`e.g., 25% OFF`).
- **Shipping Pill ("Frete Grátis"):** Background `#DCFCE7`, text `#15803D`, font `label-sm`, prepended with lightning or truck glyphs.
- **Flash Deals ("Queima Air Fryer"):** Radial gradient background `from-[#4F46E5] to-[#7C3AED]`, text `#FFFFFF`, drop shadow, uppercase `label-sm`.

### Product Cards (Customer SPA)
- Set on `#FFFFFF` with `1px solid #F1F5F9`. Features an image container with an `aspect-square` ratio on an ultra-subtle grey backdrop (`#F8FAFC`).
- Vertical stack contains: Promotional pill row, title (`body-md`, clamp 2 lines), standard price strikethrough (`body-sm`, `#94A3B8`), prominent dynamic sale price (`headline-md`, `#0F172A`), installment terms (`body-sm`, `#16A34A`), and shipping pill.
- Desktop hover triggers Elevation Level 2 and reveals a quick-add overlay button.

### Form Inputs & Search Fields
- **Marketplace Global Search:** High-efficiency pill or `8px` rectangle with a `#FFFFFF` fill, `#CBD5E1` border, dynamic active state with a `2px` focus ring in `#4F46E5`, accompanied by hotkey badge hints (`/` to search).
- **Admin Input Fields:** Standard height of `40px`, padding `space-sm space-md`, floating or top-aligned labels in `label-sm` (`#64748B`), with inline validation icons and micro-copy messages.

### Admin Data Tables & Metric Cards
- **Metric Cards:** `#FFFFFF` background, `8px` border radius, containing an upper row with label and secondary accent icon, followed by primary counter (`headline-lg`) and week-over-week performance delta badges.
- **Data Tables:** Crisp horizontal borders (`#F1F5F9`), striped alternative hover rows (`#F8FAFC`), sticky header bar with `label-md` uppercase typography, and integrated pagination controls at the base.