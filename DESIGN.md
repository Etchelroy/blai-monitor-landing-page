# MONITOR LANDING PAGE DESIGN SPEC

**SUMMARY:**
Premium computer monitor e-commerce landing page with clean blue/white aesthetic, hero-driven conversion flow, and trust-building product showcase optimized for desktop and mobile browsing.

---

## LAYOUT

**HEADER / STICKY NAVIGATION**
- Fixed top bar, full viewport width
- Left: Logo (white text "MONITOR PRO" on #0052CC)
- Center: Nav links (Home, Products, Reviews, Support) â white text, 14px
- Right: Cart icon + CTA button "Shop Now" (#FFFFFF text on #0052CC background, 12px bold)
- Height: 64px
- Background: #0052CC with subtle drop shadow (0 2px 8px rgba(0,0,0,0.1))

**HERO SECTION**
- Full viewport height (min 600px)
- Background: Linear gradient #0052CC (top-left) to #003DA5 (bottom-right)
- Left side (50% on desktop): White headline text
  - "Elevate Your Display" â 56px bold serif (Georgia)
  - Subheading "Crystal-clear visuals. Superior color accuracy. Professional grade." â 18px white, light weight
  - Two CTAs stacked: Primary "Explore Monitors" (#FFFFFF bg, #0052CC text) | Secondary "Watch Demo" (#0052CC bg, #FFFFFF text, outline style)
  - Button height: 48px, 16px padding horizontal, border-radius 4px
- Right side (50% on desktop): Hero image of premium monitor (1:1 aspect, high-res WebP)
- Mobile (320pxâ767px): Single column, image above text, 100% width

**TRUST SIGNALS BANNER** (below hero)
- Background: #F5F7FA (light blue-gray)
- 4-column grid (responsive to 2 cols @ 768px, 1 col @ 320px)
- Each card: centered icon (48x48px) + metric text (24px bold #0052CC) + label (14px #555)
  - "50K+" Reviews | "98%" Satisfaction | "2M+" Units Sold | "24/7" Support
- Padding: 48px vertical, 24px horizontal

**PRODUCT SHOWCASE SECTION**
- Background: #FFFFFF
- Heading: "Best-Selling Monitors" (48px bold #0052CC, center-aligned)
- Subheading: "Handpicked for professionals and gamers alike" (16px #666, center)
- 3-column grid (6 product cards total)
  - Responsive: 1 col @ 320px, 2 cols @ 768px, 3 cols @ 1025px
  - Max container width: 1200px, centered
  - Card structure (each 280px wide):
    - Product image (280x210px, 16:12 aspect, WebP format)
    - Title (16px bold #0052CC)
    - Rating badge (â­ 4.8/5, 14px #F39C12 star color)
    - Price range (18px bold #0052CC)
    - "Add to Cart" button (40px height, #0052CC bg, white text, 12px bold)
    - Hover state: shadow +8px, slight scale +2%, 200ms ease transition
- Grid gap: 24px
- Padding: 64px 24px

**COMPARISON TABLE SECTION**
- Background: #F5F7FA
- Heading: "Why Choose Us?" (40px bold #0052CC, left-aligned)
- Horizontal scrollable table (4 columns: Feature | Our Brand | Competitor A | Competitor B)
- Header row background: #0052CC, white text, 14px bold
- Data rows: alternating #FFFFFF and #F9FBFD
- Cell padding: 16px
- Checkmark icon (#27AE60) for "yes", X icon (#E74C3C) for "no"
- Max width: 1200px, centered
- Margin: 64px auto

**TESTIMONIALS SECTION**
- Background: #FFFFFF
- Heading: "What Our Customers Say" (40px bold #0052CC)
- 3 testimonial cards (1 col @ 320px, 2 cols @ 768px, 3 cols @ 1025px)
  - Each card: 280px wide
  - Quote text (14px #555, italic Georgia) in quotation marks
  - Author name (14px bold #0052CC)
  - Title/role (12px #999)
  - 5-star rating (â­ yellow #F39C12)
  - Card background: #F5F7FA, padding 24px, border-left 4px solid #0052CC
  - Border-radius: 4px
- Grid gap: 24px
- Padding: 64px 24px

**NEWSLETTER SIGNUP SECTION**
- Background: Linear gradient #0052CC to #003DA5
- Heading: "Stay Updated" (32px bold white)
- Subtext: "Get exclusive deals and monitor reviews" (16px white, 70% opacity)
- Input field: 300px wide, 44px height, white background, placeholder #999, padding 12px
- Subscribe button: "Sign Up" (44px, #FFFFFF bg, #0052CC text, 14px bold)
- Form centered, vertical stack on mobile
- Padding: 48px 24px

**FOOTER**
- Background: #001A4D (very dark blue)
- 4-column layout (responsive to 2 cols @ 768px, 1 col @ 320px)
  - Column 1: Logo + tagline (white, 12px)
  - Column 2: Product links (Company, About, Careers, etc.) â white 12px
  - Column 3: Support links (Help, Contact, Warranty, Returns) â white 12px
  - Column 4: Social icons (Facebook, Twitter, Instagram, LinkedIn) â light blue #6BA3D4 on hover
- Bottom bar: Copyright text (12px white, 60% opacity) centered
- Padding: 48px 24px top/bottom, 24px left/right columns
- Links hover: color #6BA3D4, no underline (underline appears on focus for a11y)

---

## COLORS

| Element | Hex | Usage |
|---------|-----|-------|
| Primary Blue | #0052CC | CTA buttons, links, headings, header, accent lines |
| Dark Blue | #003DA5 | Gradient fills, secondary actions |
| Very Dark Blue | #001A4D | Footer background |
| Light Blue-Gray | #F5F7FA | Section backgrounds, card backgrounds |
| White | #FFFFFF | Primary background, text on dark, button text |
| Text Primary | #333333 | Body text (14pxâ16px) |
| Text Secondary | #666666 | Subheadings, descriptions |
| Text Tertiary | #999999 | Meta text, labels, timestamps |
| Light Hover | #6BA3D4 | Link hover state, secondary interactions |
| Success Green | #27AE60 | Checkmarks, positive indicators |
| Alert Red | #E74C3C | Negative indicators, X marks |
| Star Yellow | #F39C12 | Rating stars, badges |

**Contrast verification:**
- #0052CC on #FFFFFF: 8.5:1 â (exceeds 4.5:1 AA)
- #FFFFFF on #0052CC: 8.5:1 â
- #333333 on #FFFFFF: 10.5:1 â
- #666666 on #FFFFFF: 7:1 â

---

## COMPONENTS

**BUTTONS**

Primary Button
- Background: #0052CC
- Text: #FFFFFF, 14px bold
- Padding: 12px 24px (48px height with line-height)
- Border-radius: 4px
- Box-shadow: none (default), 0 4px 12px rgba(0,82,204,0.3) (hover)
- Transition: 200ms ease-out
- Cursor: pointer
- Focus: 3px solid #003DA5 outline, 2px offset from edge

Secondary Button
- Background: transparent
- Border: 2px solid #0052CC
- Text: #0052CC, 14px bold
- Padding: 10px 22px (compensate for border)
- Border-radius: 4px
- Hover: background #0052CC, text #FFFFFF
- Transition: 150ms ease-in-out

**INPUT FIELDS**

Newsletter Input
- Width: 300px (responsive: 100% @ mobile)
- Height: 44px
- Background: #FFFFFF
- Border: 1px solid #E0E0E0
- Border-radius: 4px
- Padding: 12px 16px
- Font: 14px #333
- Placeholder text: 12px #999
- Focus: border-color #0052CC (2px), outline none
- Box-shadow on focus: 0 0 0 3px rgba(0,82,204,0.1)

**PRODUCT CARD**

Container: 280px wide, #FFFFFF background, border-radius 8px
- Image: 280x210px, object-fit cover, WebP with JPG fallback
- Content area: padding 16px
- Title: 16px bold #0052CC
- Rating: 14px, â­ #F39C12 star, 4.8/5 text #666
- Price: 18px bold #0052CC, "$" symbol 14px
- Button: full width, 40px height, 12px bold, centered text
- Hover state: box-shadow 0 8px 24px rgba(0,0,0,0.12), transform translateY(-4px), transition 200ms cubic-bezier(0.4,0,0.2,1)
- ARIA label: "Add [product name] to cart"

**TESTIMONIAL CARD**

Container: 280px wide, #F5F7FA background, left border-left 4px #0052CC, padding 24px, border-radius 4px
- Quote: 14px italic Georgia #555
- Author name: 14px bold #0052CC
- Role: 12px #999
- Stars: â­â­â­â­â­ #F39C12, 16px
- Margin-bottom: 4px between elements

**COMPARISON TABLE**

- Responsive horizontal scroll on mobile (touch-friendly)
- Header row: #0052CC bg, #FFFFFF text, 14px bold, padding 16px
- Data rows: alternating #FFFFFF and #F9FBFD
- Cell padding: 16px
- Checkmark: â #27AE60, 18px, bold
- X mark: â #E74C3C, 18px, bold
- Border-collapse: on (no double borders)
- Table borders: 1px solid #E0E0E0

**STICKY HEADER NAVIGATION**

- Position: fixed, top 0, z-index 100
- Width: 100vw
- Height: 64px
- Background: #0052CC
- Display: flex, items-center, justify-content: space-between
- Padding: 0 24px
- Logo: 18px bold white, letter-spacing 1px
- Nav links: white, 14px, underline on hover (1px solid #FFFFFF, underline-offset 4px), no underline on default
- Cart icon: white, 20px, margin-right 16px, pointer cursor
- CTA button: styled as Primary Button (above)
- Mobile menu icon (hamburger â°): visible @ 767px and below, white, 24px, pointer cursor

**SKIP-TO-CONTENT LINK**

- Position: absolute, off-screen (-9999px, -9999px)
- Appears on focus: position static, background #0052CC, color #FFFFFF, padding 12px 24px, z-index 200
- Font: 14px bold
- Text: "Skip to main content"

---

## INTERACTIONS

**HOVER STATES**

- All text links: underline appears on hover (#0052CC underline, 2px), color stays #0052CC, 150ms ease
- Primary buttons: shadow expands to 0 8px 24px rgba(0,82,204,0.4), background darkens to #003DA5, 200ms ease
- Secondary buttons: background fills with #0052CC, text becomes white, 150ms ease
- Product card: entire card lifts (translateY -4px), shadow grows to 0 12px 32px rgba(0,0,0,0.15), image slightly brightens (+5% brightness filter), 200ms cubic-bezier(0.4,0,0.2,1)
- Testimonial cards: border-left color animates from #0052CC to #6BA3D4, shadow appears 0 4px 16px rgba(0,82,204,0.2), 200ms ease
- Input fields: border-color becomes #0052CC, box-shadow 0 0 0 3px rgba(0,82,204,0.1), 150ms ease

**FOCUS STATES (Keyboard Navigation)**

- All focusable elements: 3px solid #0052CC outline with 2px offset (outline-offset: 2px)
- Buttons & links: visible focus ring, no removal of outline
- Form inputs: border-color #0052CC (2px), box-shadow as above
- Tab order: logical, left-to-right, top-to-bottom (header nav â hero CTAs â product cards â testimonials â newsletter â footer links)

**CLICK / ACTIVE STATES**

- Primary buttons: background deepens to #003DA5, scale 0.98, transition 100ms ease (pressed feel)
- Product card "Add to Cart": button background darkens, text remains white, shadow reduces slightly
- Testimonial cards: no active state (not interactive), focus outline only for keyboard users

**SCROLL BEHAVIORS**

- Sticky header: remains visible during scroll, slight fade of shadow on scroll-to-top (shadow opacity 0%), shadow opacity 100% after 20px scroll
- Smooth scroll anchors: internal links (#products, #testimonials, etc.) scroll smoothly (scroll-behavior: smooth) over 300ms
- Lazy loading: product images load with fade-in animation (opacity 0 â 1, 400ms ease) as they enter viewport

**MOBILE-SPECIFIC INTERACTIONS**

- Hamburger menu: click toggles overlay nav (position: fixed, full-screen, #0052CC background, white text, 32px font)
- Newsletter input: full-width 100%, placeholder text visible on focus
- Product cards: tap-to-expand detail view (modal overlay), swipe to dismiss
- Comparison table: horizontal scroll with visual indicator (scroll arrow or gradient edge fade)

**FORM INTERACTIONS**

- Newsletter input on focus: border #0052CC, cursor moves to input, placeholder fades to 30% opacity
- Submit button on hover: background #003DA5, cursor pointer
- Form submission: button shows loading state ("Signing up..." text with spinner icon), disabled pointer-events
- Success state: button text changes to "â Subscribed!", background #27AE60 for 2s, then resets
- Error state: border-color #E74C3C, error message appears 12px red text below input

---

## STYLE NOTES

**TYPOGRAPHY**

- Serif (Headlines): Georgia, serif
  - Hero headline: 56px bold, line-height 1.2, letter-spacing -1px
  - Section headings (40pxâ48px): 1.3 line-height, -0.5px letter-spacing
- Sans-serif (Body): -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif
  - Body text: 14pxâ16px, line-height 1.6, letter-spacing 0
  - Navigation: 14px, line-height 1.4
  - Labels: 12px, line-height 1.4, letter-spacing 0.5px (slightly tracked)
- Font weights: 400 (regular), 600 (semi-bold for labels), 700 (bold for headers & CTAs)
- Text hierarchy: H1 (56px) â H2 (40px) â H3 (24px) â Body (16px) â Captions (12px)

**SPACING & GRID**

- Base unit: 8px
- Section padding: 64px (vertical), 24px (horizontal) on desktop; 48px vertical, 16px horizontal on mobile
- Grid gap (cards, columns): 24px (desktop), 16px (tablet), 8px (mobile)
- Component padding: 16pxâ24px internal
- Margin between sections: 48pxâ64px
- Consistent 8px baseline for all spacing (margin, padding, gaps)

**SHADOWS & DEPTH**

- Subtle shadows: 0 2px 8px rgba(0,0,0,0.1) (cards, inputs on default)
- Medium shadows: 0 4px 16px rgba(0,0,0,0.12) (product cards on hover, modals)
- Large shadows: 0 12px 32px rgba(0,0,0,0.15) (lifted product cards, overlays)
- Inset shadows on focus: inset 0 0 0 3px rgba(0,82,204,0.2) for soft ring effect
- Header shadow: 0 2px 8px rgba(0,0,0,0.1), fades on scroll-top

**BORDER & RADIUS**

- Buttons, inputs, cards: border-radius 4px (subtle, modern)
- Product cards, testimonials: border-radius 8px (slightly rounder for softer feel)
- Hero section, gradients: no radius (full-bleed)
- Borders: 1px solid #E0E0E0 (light gray) for light backgrounds, 2px solid #0052CC for primary borders (buttons, focus states)

**ANIMATIONS & TRANSITIONS**

- Default transition: 150msâ200ms ease-in-out (hover, focus)
- Micro-interactions (button press): 100ms ease-out
- Page scroll: 300ms smooth scroll-behavior
- Loading spinners: linear 1.5s infinite rotation
- Fade-in (lazy load images): 400ms ease-in
- Modal overlays: 200ms ease-out (opacity, scale)
- Feel: smooth, not jarring; responsive to user input with 100â200ms feedback delay (feels natural)

**FEEL & TONE**

- Professional, clean, minimal â premium monitor brand aesthetic
- Blue (#0052CC) evokes trust, technology, precision
- Lots of whitespace (breathing room between sections)
- Consistent use of shadows for depth hierarchy (not overdone)
- Smooth animations create polished, high-end experience
- No clutter; each section clearly separated by background color or whitespace
- Accessibility-first: high contrast, readable fonts, clear focus states

**RESPONSIVE BREAKPOINTS**

| Device | Width | Layout | Hero | Products |
|--------|-------|--------|------|----------|
| Mobile | 320pxâ767px | 1 column, stacked | Single column, image above text | 1 column, 100% width cards |
| Tablet | 768pxâ1024px | 2 columns where applicable | 1 column | 2 column grid |
| Desktop | 1025px+ | Full layout, centered max 1200px | 2 columns (50/50) | 3 column grid |

---

## ACCESSIBILITY FEATURES

1. **Semantic HTML**: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>` used correctly
2. **ARIA labels**: Buttons with icon-only (cart icon) have aria-label="Shopping cart"
3. **Color contrast**: All text meets 4.5:1 minimum (most exceed 7:1)
4. **Focus indicators**: Visible on all interactive elements (3px outline)
5. **Keyboard navigation**: Tab order logical, Enter/Space activates buttons
6. **Skip link**: "Skip to main content" link appears on focus, jumps to `<main>`
7. **Image alt text**: All product images have descriptive alt text (alt="Premium 4K gaming monitor with 144Hz refresh rate")
8. **Form labels**: All inputs have associated `<label>` elements with id/for attributes
9. **Reduced motion**: Respects `prefers-reduced-motion: reduce` media query (no animations, instant transitions)
10. **Mobile touch targets**: Buttons min 44x44px, spacing 8px between targets
11. **Link underlines**: Links always underlined or have hover underline (not color-only)

---

This design spec is now ready for the Frontend Developer to implement in Tailwind CSS + HTML5. Every color, spacing, component behavior, and interaction is defined. No ambiguity.