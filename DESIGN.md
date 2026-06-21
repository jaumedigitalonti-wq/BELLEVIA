---
name: Bellevia
colors:
  surface: '#fff8f8'
  surface-dim: '#e2d7d9'
  surface-bright: '#fff8f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fcf1f3'
  surface-container: '#f6ebed'
  surface-container-high: '#f0e6e8'
  surface-container-highest: '#eae0e2'
  on-surface: '#1f1a1c'
  on-surface-variant: '#4f4445'
  inverse-surface: '#352f31'
  inverse-on-surface: '#f9eef0'
  outline: '#817475'
  outline-variant: '#d2c3c4'
  surface-tint: '#71585b'
  primary: '#71585b'
  on-primary: '#ffffff'
  primary-container: '#f8d7da'
  on-primary-container: '#755c5f'
  inverse-primary: '#debfc2'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#695b5c'
  on-tertiary: '#ffffff'
  tertiary-container: '#eddbdc'
  on-tertiary-container: '#6d5f60'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#fcdbde'
  primary-fixed-dim: '#debfc2'
  on-primary-fixed: '#281719'
  on-primary-fixed-variant: '#584144'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#f1dedf'
  tertiary-fixed-dim: '#d4c2c3'
  on-tertiary-fixed: '#23191a'
  on-tertiary-fixed-variant: '#504445'
  background: '#fff8f8'
  on-background: '#1f1a1c'
  surface-variant: '#eae0e2'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.05em
  caption:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.4'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  section-gap: 120px
---

## Brand & Style
The brand personality is defined by "Accessible Luxury"—a blend of high-end Madrid sophistication and warm, feminine approachability. The design system prioritizes a serene and indulgent emotional response, ensuring the user feels a sense of calm and premium care before even stepping into the salon. 

The style utilizes a **Modern-Minimalist** foundation with **Tactile/Editorial** accents. It leverages heavy whitespace to signify breathing room and exclusivity, while incorporating metallic gold highlights to ground the ethereal palette in quality and craftsmanship. The interface should feel like a high-end beauty magazine: curated, effortless, and visually harmonious.

## Colors
The palette is centered on a "Soft Rose and Gold" narrative. 
- **Primary (#F8D7DA):** A dusty rose used for soft backgrounds and primary UI accents to evoke femininity.
- **Secondary (#D4AF37):** Metallic Gold, used sparingly for critical interactive elements, icons, and decorative borders to signify premium service.
- **Tertiary (#4A3E3F):** A deep, warm charcoal-rose used for maximum legibility in text, replacing pure black to maintain the soft aesthetic.
- **Neutral (#FDF2F4/FFFFFF):** High-light neutrals used for page sections and card surfaces to maintain a clean, airy feel.

## Typography
The typography strategy creates a high-contrast hierarchy between the traditional elegance of **Playfair Display** and the modern clarity of **Montserrat**. 

- **Headlines:** Use Playfair Display for all headings. The serif terminals provide a literary, upscale feel. Large display titles should use tighter letter spacing for an editorial look.
- **Body Text:** Montserrat is used for all functional text. It should be set with generous line height (1.6) to ensure the interface feels breathable and easy to navigate.
- **Labels & CTAs:** Use uppercase Montserrat with increased letter spacing for small labels and buttons to create a "designer label" aesthetic.

## Layout & Spacing
This design system utilizes a **Fixed Grid** model for desktop and a **Fluid Fluid** model for mobile.

- **Desktop:** A 12-column grid with a maximum width of 1200px. Gutters are kept wide (24px) to prevent visual clutter. 
- **Vertical Rhythm:** A massive `section-gap` of 120px is used between major content blocks (e.g., Hero to Services) to emphasize the luxury of "space."
- **Mobile:** Transition to a 4-column fluid grid with 20px side margins. Elements should stack vertically, maintaining high padding within cards (min 24px) to keep the "soft" feel.

## Elevation & Depth
Depth is handled through **Tonal Layering** and **Ambient Shadows** rather than harsh borders.

- **Surfaces:** Use the secondary neutral (#FDF2F4) for section backgrounds, with white (#FFFFFF) for foreground cards.
- **Shadows:** Shadows are extremely diffused and low-opacity. Use a "Rose-Tinted Shadow" (a hint of the primary color mixed into the shadow hex) to avoid a "dirty" gray look on soft pink backgrounds.
- **Interactions:** On hover, cards should lift slightly (4px) with an increased shadow spread, creating a tactile "squishy" response typical of premium beauty brands.

## Shapes
The shape language is consistently **Rounded**. Sharp corners are avoided to maintain a soft, welcoming, and feminine aesthetic. 

- **Standard Elements:** Buttons, input fields, and small tags use a 0.5rem (8px) radius.
- **Large Elements:** Service cards and testimonial containers use `rounded-xl` (1.5rem / 24px) to emphasize the "soft feel" requested.
- **Decorative:** Small circular elements (like bullet points or profile images) should be fully pill-shaped or 100% rounded.

## Components
- **Call-to-Action Buttons:** The primary CTA is a solid Gold (#D4AF37) button with white uppercase text. Secondary CTAs are "Ghost" style with a 1px Gold border and a subtle pink hover state.
- **Service Cards:** White background cards with `rounded-xl` corners. They feature a top-aligned image with a subtle 4px internal gold border on the image frame itself. The service title is centered in Playfair Display.
- **Testimonial Cards:** These use a soft pink (#FDF2F4) background, no border, and a large "quotation mark" icon in Gold. Text is centered for a classic, trustworthy look.
- **Input Fields:** Bottom-border only (Editorial style) or fully rounded with a very light rose stroke. Focus state should highlight the border in Gold.
- **Chips/Tags:** Used for treatment categories (e.g., "Facial", "Massage"). These are pill-shaped with a soft rose fill and deep charcoal-rose text.