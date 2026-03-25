SUMMARY: A high-conversion landing page for a computer monitor e-commerce site using blue and white color scheme with product showcase, trust signals, and clear CTAs.

APPROACH: Static site architecture with semantic HTML5, CSS Grid/Flexbox for responsive layout, minimal JavaScript for interactions. Use a modern CSS framework (Tailwind or Pico CSS) for rapid consistent styling. Host on Vercel or Netlify for zero-config deployment. No backend required initially; integrate e-commerce platform (Shopify embed or direct product links) later.

REQUIREMENTS:

Hero Section
â Full-width hero with monitor product image, headline "Premium Displays for Every Workspace," subheading about performance/quality
â Contrasting white background with blue accent text and button
â Two CTAs: "Shop Now" (blue, primary) and "Learn More" (white outline, secondary)
â Above-the-fold viewport optimization

Product Showcase Grid
â 3-column responsive grid (1 column mobile, 2 tablet, 3 desktop) displaying 6 monitor categories
â Each card: product image, monitor name, price range ($200â$3000), brief spec (resolution, refresh rate, panel type)
â Hover state: subtle lift animation, blue border highlight, "View Details" button appears
â 8px baseline grid for card spacing and internal padding

Trust & Social Proof
â Customer ratings section with 5-star aggregate display
â 3â4 testimonial cards with customer photos, names, quotes (max 50 words each)
â Badge section: "ISO Certified," "10-Year Warranty," "Free 30-Day Returns"
â Color: white cards on light blue background (#F0F4F8)

Technical Specifications Section
â Comparison table showing key specs (resolution, panel type, refresh rate, color accuracy)
â Accessible table markup with proper thead/tbody/th
â Sticky header on scroll (desktop only)
â Blue text for highlighted values

Navigation & Footer
â Sticky header with logo, nav links (Shop, About, Support, Contact), search icon, cart icon
â Navigation background: white with subtle blue shadow on scroll
â Footer: 4-column layout (Product Categories, Company Info, Support Links, Newsletter Signup)
â Newsletter input with "Subscribe" button (blue background, white text)
â Copyright and social media icons (LinkedIn, Twitter, YouTube)

Responsive Breakpoints
â Mobile: 320pxâ767px (single column, touch-friendly buttons 48px minimum)
â Tablet: 768pxâ1024px (2 columns, adjusted spacing)
â Desktop: 1025px+ (full 3-column grid, max-width container 1200px)

Performance & Accessibility
â Lazy loading for product images (native loading="lazy")
â WebP image format with JPG fallback
â WCAG AA color contrast: blue (#0052CC) on white (ratio 8.5:1), white on blue (ratio 8.5:1)
â Alt text for all images (descriptive, not "image of monitor")
â Semantic HTML: nav, section, article, figure tags
â Form labels properly associated with inputs (for/id attributes)
â Skip-to-content link for keyboard navigation
â Meta tags: viewport, Open Graph, Twitter Card for social sharing

CONSTRAINTS:

â Max bundle size: 100KB gzipped (CSS + JS combined)
â Image optimization: compress to under 150KB per image, use srcset for retina displays
â Must load in under 2 seconds on 4G (Lighthouse performance >80)
â No third-party analytics tracking until GDPR consent implemented
â Browser support: Chrome/Firefox/Safari/Edge (last 2 versions), IE11 not required
â Dependency on Shopify API or similar if product data comes from external source (plan for API latency)

NOTES:

â Color psychology: Blue conveys trust, professionalism, and tech expertiseâideal for hardware
â Hero image: use a high-quality lifestyle shot (monitor in workspace) rather than flat product shot; invest in professional photography or high-res stock
â Avoid monitor oversaturation in heroâshow the monitor in context (desk setup, gamer, office) to make it relatable
â CTA button text should be action-oriented ("Shop Now" not "Click Here")
â Sticky header may hide content on mobileâuse hamburger menu toggle with smooth slide animation
â Testimonials: include specific monitor model names to build credibility (not generic praise)
â Test hover states and animations on touch devicesâdisable on mobile to prevent jank
â Consider A/B testing two hero headlines (performance vs. aesthetics) before launch
â Add FAQ section below fold for SEO and user confidence (common questions: warranty, return policy, shipping time)
â Product images need consistent lighting and angle for visual coherenceâestablish a style guide