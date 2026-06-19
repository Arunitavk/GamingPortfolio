---
name: Obsidian Nebula
colors:
  surface: '#131315'
  surface-dim: '#131315'
  surface-bright: '#39393b'
  surface-container-lowest: '#0e0e10'
  surface-container-low: '#1c1b1d'
  surface-container: '#201f22'
  surface-container-high: '#2a2a2c'
  surface-container-highest: '#353437'
  on-surface: '#e5e1e4'
  on-surface-variant: '#cfc2d6'
  inverse-surface: '#e5e1e4'
  inverse-on-surface: '#313032'
  outline: '#988d9f'
  outline-variant: '#4d4354'
  surface-tint: '#ddb7ff'
  primary: '#ddb7ff'
  on-primary: '#490080'
  primary-container: '#b76dff'
  on-primary-container: '#400071'
  inverse-primary: '#842bd2'
  secondary: '#adc6ff'
  on-secondary: '#002e6a'
  secondary-container: '#0566d9'
  on-secondary-container: '#e6ecff'
  tertiary: '#4edea3'
  on-tertiary: '#003824'
  tertiary-container: '#00a572'
  on-tertiary-container: '#00311f'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#f0dbff'
  primary-fixed-dim: '#ddb7ff'
  on-primary-fixed: '#2c0051'
  on-primary-fixed-variant: '#6900b3'
  secondary-fixed: '#d8e2ff'
  secondary-fixed-dim: '#adc6ff'
  on-secondary-fixed: '#001a42'
  on-secondary-fixed-variant: '#004395'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#131315'
  on-background: '#e5e1e4'
  surface-variant: '#353437'
typography:
  display-lg:
    fontFamily: Space Grotesk
    fontSize: 72px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: 0.05em
  code-sm:
    fontFamily: Geist
    fontSize: 13px
    fontWeight: '400'
    lineHeight: '1.5'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1280px
  section-gap: 160px
  section-gap-mobile: 80px
  gutter: 32px
  margin-mobile: 20px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 24px
---

## Brand & Style

The design system is engineered for a high-end, "AAA Studio" aesthetic, balancing the technical rigor of Artificial Intelligence with the immersive atmosphere of premium game development. It targets a professional audience of recruiters and collaborators, aiming to evoke a sense of sophisticated innovation rather than adolescent high-energy gaming.

The style is a refined hybrid of **Minimalism** and **Glassmorphism**. It utilizes a "Dark Mode First" philosophy, where depth is communicated through subtle luminosity and layered translucency rather than heavy shadows. The interface should feel like a high-end developer console—precise, expansive, and atmospheric—utilizing generous whitespace to let technical projects breathe.

## Colors

The palette is anchored in **Midnight Charcoal (#09090B)** for the primary background, providing a deep, non-distracting canvas.

- **Primary (Neon Purple):** Used for critical actions, active states, and focus highlights. It represents the "creative" spark of game development.
- **Secondary (Electric Blue):** Used for technical data, links, and secondary interactive elements, representing the "logic" of AI.
- **Accents:** High-frequency interactions use subtle gradients blending the primary and secondary colors. 
- **Surface Tints:** Instead of pure greys, the system uses very low-opacity overlays of the primary and secondary colors (2-4%) on containers to create a sense of atmospheric depth.

## Typography

The typography strategy pairs technical precision with modern readability. 

1.  **Headlines:** **Space Grotesk** provides a geometric, slightly futuristic feel that echoes high-tech HUDs without sacrificing legibility.
2.  **Body:** **Inter** is the workhorse for long-form content, ensuring research papers and project descriptions remain highly readable.
3.  **Technical Labels:** **Geist** is used for metadata, tags, and small labels to provide a monospaced, developer-centric aesthetic for AI parameters and engine specs.

Large display type should use tighter letter-spacing to appear more "designed" and cinematic. Mobile sizes aggressively scale down to maintain a clean vertical rhythm.

## Layout & Spacing

This design system utilizes a **12-column fixed-max grid** (1280px) for desktop to ensure a cinematic framing of content. 

- **Section Spacing:** To achieve the "AAA" feel, we use exaggerated vertical spacing (160px) between major portfolio sections. This forces focus on one project at a time.
- **Vertical Flow:** The layout is strictly linear and vertically scrollable. Avoid complex sidebars or multi-column dashboard layouts.
- **Micro-spacing:** Built on an 8px base unit. Component internal padding should favor larger horizontal values to create a "wide-screen" feel within cards and buttons.

## Elevation & Depth

Depth is achieved through **Glassmorphism** and light-based hierarchy rather than traditional shadows.

- **Surface Tiers:**
    - **Level 0 (Background):** Deep Charcoal (#09090B).
    - **Level 1 (Cards):** Translucent fill (White @ 3%) with a 20px backdrop blur and a 1px border (White @ 10%).
    - **Level 2 (Modals/Popovers):** Translucent fill (White @ 6%) with a 40px backdrop blur and a thin primary-color-tinted border.
- **Glow Effects:** Use "Ambient Glows"—large, low-opacity (5-10%) radial gradients of Purple and Blue positioned behind key content blocks to create a sense of localized light sources.
- **Interactive States:** On hover, cards should increase their border opacity and the intensity of their background blur.

## Shapes

The design system uses a **Soft (0.25rem)** roundedness approach. This maintains a sharp, technical edge associated with engineering while removing the "aggressive" sharpness of pure brutalism.

- **Standard Elements:** 4px radius (Buttons, Inputs).
- **Large Containers:** 8px or 12px radius (Project Cards, Hero Sections).
- **Visual Accents:** Use 45-degree clipped corners sparingly for "high-tech" accents on decorative elements or image frames.

## Components

### Buttons
- **Primary:** Solid-to-gradient fill (Blue to Purple) with white text. High-contrast and impactful.
- **Ghost:** Transparent background with a 1px border. On hover, the border glows with the primary color.
- **Technical:** Small, all-caps Geist font for secondary actions, often accompanied by a small '+' or '>' icon.

### Project Cards
Cards should be "wide-format" where possible. They feature a 1px subtle border and a light glass effect. Content inside should be strictly aligned to a sub-grid, using labels for "Tech Stack" and "Role."

### Input Fields
Minimalist design with only a bottom border that animates into a full-width gradient when focused. Backgrounds are slightly darker than the main surface to provide a "recessed" feel.

### Chips & Tags
Used for AI libraries and Game Engines. These should be low-profile: a subtle border and a colored dot indicating the category (e.g., Green for "Stable", Purple for "Experimental").

### Progress Bars / Data Viz
Used for skill sets or AI metrics. Use thin, 4px lines with a neon glow effect on the "filled" portion to mimic a loading screen or HUD.