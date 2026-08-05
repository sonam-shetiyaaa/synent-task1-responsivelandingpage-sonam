# StyleHub — Responsive Shopping Landing Page

A fully responsive shopping website landing page built with **HTML + CSS only**.

## Pages

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Hero, features, categories, footer |
| Shop | `shop.html` | Product grid — tap any item to view details |
| Product | `product.html` | Single product page with Add to Cart |
| Deals | `deals.html` | Discounted items |
| Cart | `cart.html` | Shopping cart |
| Contact | `contact.html` | Contact form and info |

## How to Run

Open `index.html` in any browser (Chrome, Firefox, Edge, Safari).

Or use a local server:

```bash
npx serve .
```

## Features

- **Hero section** with Shop Now / View Deals buttons
- **4 feature cards** (Free Delivery, Best Deals, Easy Returns, Secure Checkout) — each links to a page
- **Category cards** (Women, Men, Accessories, Footwear)
- **Footer** with quick links, support, and social links
- **Mobile hamburger menu** (CSS-only, no JavaScript)
- **Touch-friendly** tap targets (min 44px) for phones and tablets
- **Responsive breakpoints** at 900px (tablet) and 640px (mobile)

## Responsive Layout

- **Desktop**: 2-column hero, 4-column feature grid, side-by-side footer
- **Tablet**: 2-column grids collapse where needed
- **Mobile**: Single column, full-width buttons, slide-in navigation
