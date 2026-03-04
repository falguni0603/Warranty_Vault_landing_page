# WarrantyVault – AI Powered Digital Warranty Tracker

## Current State
New project. No existing frontend or backend code. Starting from a blank Caffeine template.

## Requested Changes (Diff)

### Add
- Full landing page React app with the following sections:
  1. **Navigation** – Logo "WarrantyVault" on left, nav links (Home, Features, How It Works, Pricing, Contact), Login + Sign Up buttons on right. Sticky on scroll.
  2. **Hero Section** – Full-width hero with headline "Secure, Smart, AI Warranty Tracking", subheading "Automatically track, store and claim product warranties", primary CTA "Get Started", secondary CTA "View Demo". 3D-style illustration (generated image) of warranty cards/invoices/mobile device. Soft cool-tone gradient background.
  3. **Features Section** – 3-column card grid with icons: "Automatic Invoice Detection", "AI Warranty Assistant", "Smart Reminders" each with description text.
  4. **How It Works Section** – 3-step horizontal timeline: Step 1 Upload/Detect Invoice, Step 2 Track & Remind, Step 3 Claim with AI Assistance.
  5. **Footer** – Simple footer with brand name and links.
- Framer Motion animations: fade-in on scroll for sections, hover effects on cards, hero entrance animation.
- Fully responsive layout (mobile-first, hero stacks on small screens).
- Cool-tone color palette (blues, purples) using OKLCH design tokens.
- Outfit or Plus Jakarta Sans font for modern sans-serif typography.

### Modify
- `index.css` – Define OKLCH design tokens for blues/purples palette, dark-mode ready.
- `tailwind.config.js` – Register custom font, color tokens, and border-radius extensions.

### Remove
- Nothing (new project).

## Implementation Plan
1. Write `spec.md` (this file) and rename project to "WarrantyVault".
2. Generate 3D hero illustration image (warranty cards, invoices, mobile device in cool-tone 3D style).
3. Set up design tokens in `index.css` and `tailwind.config.js` with OKLCH cool-tone palette.
4. Build `App.tsx` with components: `Navbar`, `HeroSection`, `FeaturesSection`, `HowItWorksSection`, `Footer`.
5. Wire Framer Motion animations for entrance + scroll-triggered reveals.
6. Ensure full responsiveness at mobile, tablet, desktop breakpoints.
7. Validate with typecheck, lint, and build.
8. Deploy draft.
