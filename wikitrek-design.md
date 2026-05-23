---
name: Wikitrek
colors:
  primary: "#996633"
  secondary: "#CFAA82"
  tertiary: "#FFD700"
  neutral: "#FFF5DC"
  table-header: "#EAECF0"
  table-body: "#F8F9FA"
  command-gold: "#FFD700"
  science-silver: "#c0c0c0"
  operations-copper: "#CB6d51"
  website-blue: "#3366cc"
  lcars-slate: '#2F3749'
  lcars-2: "#52596E"
  lcars-3: "#6D748C"
  lcars-4: "#9EA5BA"
  lcars-alert: '#E7442A'
  lcars-6: "#FF6753"
  lcars-7: "#FF977B"
  lcars-blue: '#1C3C55'
  lcars-elbow: "#2A7193"
  lcars-10: "#37A6D1"
  htng-link: "#CC6600"
  htng-visited: "#993300"
  htng-active: "#FF6600"
  htng-hover: "#FF6633"
  grey-gradient-1: "#fefefe"
  grey-gradient-2: "#e0e0e0"
  grey-gradient-3: "#dadada"
  grey-gradient-4: "#b3b3b3"
  grey-gradient-5: "#9e9e9e"
  grey-gradient-6: "#9e9e9e"
  grey-gradient-7: "#727272"
typography:
  display:
    fontFamily: Fjalla One
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Fjalla One
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  headline-md:
    fontFamily: Fjalla One
    fontSize: 24px
    fontWeight: '400'
    lineHeight: 32px
  headline-sm:
    fontFamily: Fjalla One
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 28px
  body-lg:
    fontFamily: Open Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Open Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Open Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-caps:
    fontFamily: Open Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.05em
  code:
    fontFamily: monospace
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  headline-lg-mobile:
    fontFamily: Fjalla One
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 34px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 24px
  margin-page: 32px
  margin-mobile: 16px
  section-gap: 48px
---

## Brand & Style

The design system establishes a professional, authoritative, and encyclopedic aesthetic that bridges the functional utility of a modern wiki with the immersive visual language of the Star Trek universe. It is a dual-purpose system: it must serve as a high-readability research tool while evoking the high-tech, futuristic atmosphere of Starfleet LCARS (Library Computer Access and Retrieval System) interfaces.

The design style is **Corporate / Modern** mixed with **LCARS-inspired Futurism**. It utilizes clean information density, sharp geometric accents, and a distinctive color palette that signals different Starfleet divisions. The brand personality is scholarly yet adventurous, reliable yet innovative. Key visual cues include metallic gradients, pill-shaped UI "elbows," and a strong contrast between technical slate-blues and command-gold accents.

## Colors

The color system is organized into functional hierarchies based on Starfleet divisions and LCARS interface logic. 

- **Primary & Command:** The core brand uses #996633 (Dark Brown) and #FFD700 (Command Gold). These should be used for site-wide navigation and top-level branding.
- **Surface & Backgrounds:** The main content areas utilize #FFF5DC (Cream) and light neutrals to ensure high text legibility, maintaining the "encyclopedia" feel.
- **LCARS Accents:** Use the slate-blues and teals for technical UI components like headers, sidebar widgets, and search bars. 
- **Thematic Divisions:** Apply division colors (Silver for Science, Copper for Operations) contextually for specific series-related content or data tables.
- **Interactive States:** Links use a warm "HyperTrek" orange palette (#CC6600) to distinguish them from brand golds and navigational slates.

## Typography

The typography system balances the high-impact, condensed feel of **Fjalla One** for headings with the high-utility legibility of **Open Sans** for body content.

- **Headlines:** Use Fjalla One in all-caps for major page titles and section headers to evoke the LCARS display feel.
- **Body Content:** Open Sans is the workhorse for all article text, ensuring a comfortable reading experience for long-form data.
- **Stylistic Accents:** For decorative labels, credits, or Klingon-language contexts, use stylistic accents inspired by 'DIn pIqaD' sparingly.
- **Technical Data:** Use the Monospace role for star-dates, ship registry numbers, and raw technical output.

## Layout & Spacing

The design system uses a **Fixed Grid** approach for article content to maintain focus, while the UI "shell" (headers and sidebars) can behave fluidly to accommodate various screen sizes.

- **Grid Model:** 12-column grid for desktop with 24px gutters. Content should be centered with a maximum width of 1280px for optimal readability.
- **LCARS Paneling:** Use asymmetrical layouts where technical data is housed in a "sidebar" panel (3 or 4 columns) and primary article text in the main "viewscreen" area (8 or 9 columns).
- **Responsive Behavior:** 
    - **Desktop:** Sidebar is persistent on the left.
    - **Tablet:** Sidebar collapses into a top-level menu icon; margins reduce to 24px.
    - **Mobile:** Single column layout; margins at 16px. Typography scales down to mobile-specific variables.

## Elevation & Depth

This system utilizes **Tonal Layers** and **Low-contrast Outlines** rather than heavy shadows to create depth, mimicking a glass screen interface.

- **Tiers:** Use background colors to define elevation. The base page is neutral, while "Containers" (like Infoboxes) use `#FFF5DC` or `#F8F9FA` with a subtle 1px border of `#CFAA82`.
- **LCARS Elements:** Technical panels use dark, solid fills (`#2F3749`) with no shadows, creating a "flat panel" aesthetic that looks like part of a console.
- **Interactive Elevation:** Buttons and cards should not float; instead, use 1px borders and slight color shifts on hover to indicate interactability.
- **Metallic Accents:** Apply subtle linear gradients (e.g., `#996633` to `#FFD700`) only on the logo or primary brand headers to simulate a metallic division badge.

## Shapes

The shape language is primarily **Soft** with targeted use of **Pill-shaped** elements for specific LCARS metaphors.

- **Standard Containers:** Use 0.25rem (4px) rounded corners for article boxes, images, and input fields.
- **LCARS Elbows:** Navigation headers and terminal-style buttons should use "pill" roundedness (1rem+) on one side (e.g., top-left and bottom-left) to create the iconic Star Trek interface curve.
- **Dividers:** Use horizontal rules with a 2px thickness, often using a "capped" look where the line ends in a small vertical block or pill.

## Components

- **Buttons:** Primary buttons use the LCARS "elbow" shape with a background of `#2A7193` and white text. Secondary buttons are outlined in `#CFAA82`.
- **Infoboxes (Wiki Cards):** Use a light cream background (`#FFF5DC`) with a thick 4px top-border in the relevant division color (Gold/Silver/Copper).
- **Chips/Labels:** Small pill-shaped tags used for series categorization (e.g., "TOS", "DIS", "PIC"). Text is all-caps Fjalla One at 10px.
- **Inputs:** Clean, rectangular fields with 1px slate borders. Focus state should use a sharp Command Gold glow.
- **Data Tables:** Alternate row colors using `#F8F9FA` and `#EAECF0`. Headers must be bold with a dark background (`#1C3C55`) and light text.
- **Alerts:** Use the `#E7442A` (Red Alert) for errors or critical warnings, formatted as a full-width bar at the top of the content area.
