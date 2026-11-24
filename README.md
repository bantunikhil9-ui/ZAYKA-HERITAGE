# TEAM-DOOM
# Zayka Heritage — Fine Dining Restaurant Website

A modern, responsive single-page restaurant web application crafted with an editorial culinary aesthetic. Built as a college web development project, it showcases contemporary Indian fine dining with interactive menu filtering, live order cart calculations, promo code redemption, dynamic customer reviews, and instant table reservations.

---

## Live Preview & Features

* **Editorial UI/UX & Typography**: Pairs **Cormorant Garamond** for high-contrast display headings with **Plus Jakarta Sans** for clean body copy and interactive controls, layered over a warm cream (`#FAF6F0`), deep charcoal (`#181310`), and saffron gold (`#D97706`) palette.
* **Hero Section**: Full-bleed culinary showcase with quick call-to-action buttons for exploring the menu and booking a table, plus key restaurant highlights.
* **Interactive Food Menu & Dietary Filters**:
  * Filter dishes across four categories (*Starters*, *Main Course*, *Breads & Rice*, and *Desserts & Beverages*).
  * Toggle between **All**, **Pure Veg**, and **Non-Veg** options in real time.
  * Indian Rupee (`₹`) pricing with dish descriptions and chef tags.
* **Slide-Over Order Bag & Billing**:
  * Add or adjust dish quantities directly from the menu.
  * Automatic subtotal, **5% GST** calculation, and live discount application using promo codes.
* **Special Offers & One-Click Promo Codes**: Interactive offer cards with one-click clipboard copy functionality (`FEAST20`, `THALI299`, `SIPROYAL`) and visual toast confirmations.
* **Dynamic Customer Reviews**: Displays verified diner testimonials with star ratings, alongside a **Write a Review** modal that appends new user reviews directly to the page.
* **Table Reservation & Location Info**: Interactive booking modal with date, time, guest count, and seating preference validation, paired with opening hours, contact details, and an interactive location map section.

---

## Tech Stack

* **HTML5**: Semantic structure (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`) and accessible form controls.
* **CSS3 / Tailwind CSS**: Responsive grid and flexbox layouts, custom colour tokens, smooth scroll behaviour, and hover micro-interactions.
* **Vanilla JavaScript (ES6+)**: DOM manipulation, real-time category/dietary filtering, cart state management, clipboard API integration, and modal handling.
* **Google Fonts & Lucide/FontAwesome Icons**: Typography and crisp vector iconography.

---

## Project Structure

```text
zayka-heritage-restaurant/
│
├── index.html          # Complete single-page application (HTML, CSS & JS)
└── README.md           # Project documentation
