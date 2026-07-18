---
name: Urban Kinetic
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1b1b1c'
  surface-container: '#202020'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353535'
  on-surface: '#e5e2e1'
  on-surface-variant: '#e9bcb6'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#303030'
  outline: '#b08782'
  outline-variant: '#5f3f3a'
  surface-tint: '#ffb4aa'
  primary: '#ffb4aa'
  on-primary: '#690003'
  primary-container: '#ff5446'
  on-primary-container: '#5c0002'
  inverse-primary: '#c0000c'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#c8c6c5'
  on-tertiary: '#313030'
  tertiary-container: '#929090'
  on-tertiary-container: '#2a2a29'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad5'
  primary-fixed-dim: '#ffb4aa'
  on-primary-fixed: '#410001'
  on-primary-fixed-variant: '#930006'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474646'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353535'
typography:
  display-xl:
    fontFamily: Anton
    fontSize: 120px
    fontWeight: '400'
    lineHeight: 110px
    letterSpacing: -0.04em
  display-lg:
    fontFamily: Anton
    fontSize: 80px
    fontWeight: '400'
    lineHeight: 76px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Anton
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 52px
    letterSpacing: 0.02em
  headline-lg-mobile:
    fontFamily: Anton
    fontSize: 36px
    fontWeight: '400'
    lineHeight: 40px
  body-lg:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
  mono-quote:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
spacing:
  base: 8px
  section-gap: 120px
  container-padding: 24px
  gutter: 16px
  margin-mobile: 20px
  margin-desktop: 64px
---

## Brand & Style
The design system embodies a "Hyper-Street" aesthetic: a fusion of raw urban grit and high-end digital precision. It is designed for a Gen-Z audience that values authenticity, irony, and high-impact visuals. 

The style is **Experimental Glassmorphism mixed with Brutalist structuralism**. Expect heavy, textured typography that feels physical, contrasted against ethereal, translucent glass panels that float in a 3D space. The mood is unapologetic, energetic, and "always-on," utilizing high-contrast backgrounds to make content feel like a street-style editorial.

## Colors
The palette is rooted in a high-tension "Signal Red" and "Obsidian" foundation. 

- **Primary (Signal Red):** Used exclusively for high-priority actions, critical micro-copy, and kinetic accents.
- **Secondary (Pure White):** Used for maximum legibility in body text and primary headers.
- **Tertiary/Neutral (Obsidian & Charcoal):** Layered blacks create a sense of infinite depth.
- **Glass Tint:** Semi-transparent white (#FFFFFF at 5-10% opacity) with a 20px-32px backdrop blur is the signature treatment for containers.

## Typography
Typography is the primary visual driver. **Anton** is used for massive, impactful headlines that feel like poster art. It should frequently be used in all-caps. 

**Geist** provides a clinical, technical balance for body copy, ensuring the UI remains functional despite its edgy aesthetic. **Space Grotesk** is reserved for metadata, labels, and "tech-style" annotations, reinforcing the modern, slightly futuristic street vibe. Use "Display XL" for hero sections, often overlapping photography or 3D elements.

## Layout & Spacing
The layout follows a **Fluid Grid with Asymmetrical Overlays**. 

- **Desktop:** 12-column grid. Components often "break" the grid slightly to feel less rigid. Use wide margins (64px) to create a premium, editorial feel.
- **Mobile:** 4-column grid with tight margins. Stacked hierarchy with high vertical density.
- **Rhythm:** Use an 8px base unit. Section gaps should be aggressive (120px+) to allow the 3D assets and large typography to breathe.

## Elevation & Depth
Depth is achieved through **Dynamic Glassmorphism and Z-axis layering**.

1.  **Level 0 (Background):** Deep charcoal/black with subtle noise texture or grainy gradients.
2.  **Level 1 (The "Glass" Layer):** High-blur (32px), low-opacity panels. Borders are 1px solid white at 15% opacity to define edges without adding visual weight.
3.  **Level 2 (Active Elements):** Cards and buttons that use subtle "Outer Glows" in the primary red instead of traditional shadows.
4.  **Floating Elements:** Interactive annotations and "call-outs" use 1px leader lines (inspired by the reference image) to connect floating text to specific visual points.

## Shapes
This design system utilizes **Sharp Geometry**. 

All primary UI elements (buttons, inputs, cards) use a 0px border radius to maintain a raw, brutalist edge. The only exception is for circular avatars or icon-buttons. Use "Angled Cuts" or 45-degree chamfers for decorative elements to reinforce the edgy, street-style architecture.

## Components

- **Buttons:** Hard-edged rectangles. Default state is 1px white border. Hover state is solid primary red with black text and a "glitch" or rapid-shift transition.
- **Glass Cards:** Blurred backgrounds with a "frosted" texture. Use thin leader lines to anchor these cards to content, similar to technical HUDs.
- **Input Fields:** Bottom-border only (2px thick). Focus state turns the border primary red.
- **Chips/Tags:** Monospaced text inside small, high-contrast black boxes with white text.
- **Call-outs:** Floating text blocks using `label-sm` or `mono-quote`. Use a small dot marker and a thin horizontal line (the "leader") to point toward the subject.
- **Interactive Layers:** Use 3D transforms on hover for cards, creating a "tilt" effect that emphasizes the depth of the glass layers.