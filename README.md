# 🌿 Eden Gardens Vagamon

A premium, single-page marketing website for **Eden Gardens Vagamon** — a private two-bedroom villa homestay nestled inside a working tea estate in Pullikkanam, Vagamon, Kerala.

> **Live at:** [edengardens.vercel.app](https://edengardens.vercel.app)

---

## ✨ Features

| Feature | Description |
|---|---|
| **Hero Slideshow** | Cinematic image carousel with smooth crossfade transitions |
| **Bento Grid Layout** | Asymmetric card grid showcasing the estate, rooms, and amenities |
| **Masonry Gallery** | Filterable photo gallery (Exterior, Interiors, Outdoors) with lightbox viewer |
| **Booking Form** | Interactive inquiry form with live price calculation based on dates and guest count |
| **Guest Reviews** | Verified Booking.com testimonials with rating badges |
| **Plan Your Visit** | Travel distances, seasonal info, and temperature guide |
| **Responsive Design** | Fully mobile-friendly with hamburger navigation and adaptive layouts |
| **WhatsApp Integration** | Direct WhatsApp contact links for instant booking inquiries |

## 🎨 Design

- **Typography:** Cormorant Garamond (serif headings) + Outfit (sans body text)
- **Color Palette:** Sage greens, warm cream, charcoal — inspired by the tea estate setting
- **Animations:** Scroll reveal with blur-in, hero word mask reveal, parallax tilt, magnetic button physics, cursor glow aura
- **Visual Style:** Double-bezel card architecture, glassmorphism navigation, film grain overlay, custom scrollbar
- **Framework:** Tailwind CSS (CDN) + custom vanilla CSS design system

## 📁 Project Structure

```
edengardens/
├── index.html          # Single-page site (all sections + inline JS)
├── index.css           # Custom design system, animations, and overrides
├── booking.com/        # Property photo assets (20 JPGs)
│   ├── 509215170.jpg
│   ├── 590548265.jpg
│   └── ...
└── README.md
```

## 🚀 Getting Started

No build step required — this is a static site.

```bash
# Clone the repo
git clone https://github.com/Ben2221/edengardens.git
cd edengardens

# Serve locally with any static server
python3 -m http.server 3001
# or
npx serve .
```

Then open [http://localhost:3001](http://localhost:3001) in your browser.

## 📍 Property Details

| Detail | Info |
|---|---|
| **Location** | Pullikkanam, Vagamon, Idukki, Kerala 685503 |
| **Bedrooms** | 2 (queen-sized beds) |
| **Bathrooms** | 3 |
| **Capacity** | Up to 7 guests (base rate for 4) |
| **Amenities** | Kitchen, dining, patio swings, balcony, parking, campfire |
| **Contact** | +91 85476 80185 (WhatsApp / Call) |
| **Email** | bensavio2221@gmail.com |
| **Booking.com** | [Eden Gardens Vagamon](https://www.booking.com/hotel/in/eden-gardens-vagamon.html) |
| **Instagram** | [@eden_gardens_vagamon](https://www.instagram.com/eden_gardens_vagamon/) |

## 🛠 Tech Stack

- **HTML5** — semantic markup with Schema.org JSON-LD structured data
- **Tailwind CSS** — utility-first styling via CDN
- **Vanilla CSS** — custom design tokens, spring-physics animations, masonry layout
- **Vanilla JavaScript** — slideshow, gallery filters, lightbox, price calculator, scroll reveals
- **Google Fonts** — Cormorant Garamond + Outfit

## 📄 License

All rights reserved. Property images and content are owned by Eden Gardens Vagamon.
