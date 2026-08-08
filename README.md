# Odyssey — Responsive Travel Landing Page

A fully responsive travel website landing page built with **HTML + CSS only**.

## Pages

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Hero, search bar, destinations, features, auth, footer |
| Destinations | `destinations.html` | Travel package cards with details |
| Package | `package.html` | Single destination package page |
| Deals | `deals.html` | Travel offers and seasonal discounts |
| Trip Plan | `trip-plan.html` | Saved travel plan + saved-for-later list |
| Dashboard | `dashboard.html` | Logged-in user's bookings and account overview |
| Contact | `contact.html` | Working contact form and support info |

## How to Run

Open `index.html` in any browser (Chrome, Firefox, Edge, Safari).

Or use the bundled local server (recommended — supports query strings such as the sign-in flow):

```bash
node server.js
# Server running at http://localhost:8000/
```

## Features

- **Hero section** with travel search and destination discovery
- **Trending destinations** grid with package details
- **Travel deal page** for limited-time offers
- **Working contact form** with validation and confirmation
- **Sign in / Sign up** stored in the browser (localStorage)
- **Instant booking** — sign in and book directly from the destination card (no redirect); a toast confirms the booking
- **Booked counter** in the top-right navbar that opens a dropdown listing every booked destination with a remove option
- **Trip plan & dashboard** pages list all booked destinations with saved-for-later support
- **Mobile-friendly navigation** for smooth browsing on phones and tablets
- **Responsive breakpoints** for desktop, tablet, and mobile views

## Responsive Layout

- **Desktop**: immersive hero, grid-based destination cards, rich footer
- **Tablet**: stacked content and simplified navigation
- **Mobile**: single-column layout, large buttons, easy tap targets
