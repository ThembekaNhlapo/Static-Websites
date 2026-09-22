# FreshCart 🥦

A single-page static storefront concept for a fresh vegetable delivery service, built with HTML and Bootstrap 5.

## Overview

FreshCart is a front-end demo/landing page showcasing a simple product catalog UI — a hero banner, a responsive grid of vegetable products with "Buy" buttons, and a footer with a contact form. It's a static mockup (no backend, no working cart or form submission) intended as a starting point for a real e-commerce build or a UI/design reference.

## Features

- **Responsive navbar** with brand logo and links (Home, Vegetables, Cart, Contact)
- **Hero banner** with gradient background and call-to-action copy
- **Product grid** of 10 vegetable cards, each showing:
  - Product image with a hover zoom/rotate effect
  - "Organic" badge on select items
  - Name, unit (per kg / per head / per bunch / per piece), and price in ZAR (R)
  - A "Buy" button (currently non-functional — no cart logic wired up)
- **Footer** with company logo, a horizontal contact form (name, email, phone), and copyright notice
- Fully responsive layout (mobile, tablet, desktop) via Bootstrap's grid system

## Tech Stack

- **HTML5**
- **[Bootstrap 5.3.8](https://getbootstrap.com/)** — loaded via CDN (CSS + JS bundle)
- **Custom CSS** (inline `<style>` block) for the green/organic theme, card hover effects, and footer styling
- No JavaScript framework, build step, or backend — it's a single self-contained `index.html` file

## Getting Started

No installation or build tools required.

1. Download or clone the file.
2. Open `index.html` directly in any modern web browser.

That's it — Bootstrap is pulled from a CDN, so an internet connection is needed for styling and icons to load correctly.

## File Structure

```
.
└── index.html   # Entire page: markup, embedded styles, and script tags
```

## Known Issues

- The **Carrots** product card has a malformed price tag (`<p class="product-price mb-3">R19.99/p>`) — missing the opening `<` on the closing tag. This should be fixed to `</p>` to avoid rendering issues.
- Several product images are hotlinked from third-party sources (Google's cached thumbnail service, external retailer catalogs) rather than hosted locally — consider downloading and self-hosting these for production use and to avoid broken links.
- Buy buttons and the contact form are static placeholders with no actual functionality (no cart state, no form validation/submission handling).

## Possible Next Steps

- Wire up cart functionality (add to cart, cart count, checkout flow)
- Hook the contact form up to a backend or form service (e.g., Formspree, a serverless function)
- Self-host product images and add lazy loading
- Add a real routing/navigation structure if additional pages are introduced

## License

No license specified. Add one (e.g., MIT) if this project will be shared or open-sourced.
