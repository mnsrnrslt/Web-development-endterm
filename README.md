# MODANOVA — E-Commerce Web Application (Endterm Project)

Group: SE-2527

Authors: Mansur Nursultanov, Daniyar Baikanov, Temkeshev Aldiyar

---

## Project Overview
MODANOVA is a responsive multi-page web application for an apparel store. In this endterm milestone, we upgraded the existing midterm website by adding interactive JavaScript and jQuery features, dynamic rendering, client-side validation, and UI enhancements.

---

## Pages (5 Pages)
1. **Home (`index.html`)** — Promo banners, featured items, and search bar.
2. **Catalogue (`catalogue.html`)** — Products rendered dynamically via JavaScript with live search and category buttons.
3. **Product Page (`productpg.html`)** — Product details, image gallery, size picker, wishlist, and cart counter.
4. **About Us (`about.html`)** — Brand history and store mission.
5. **Contact (`contact.html`)** — Inquiry form with validation, store map, and working hours timetable.

---

## Implemented Features (Endterm)

1. **Dynamic Catalogue (`js/catalogue.js`)**
   - Products are stored in an array of objects and rendered using JS.
   - Category filtering (All, Tops, Bottoms, Outerwear).
   - Real-time search by typing in the input.
   - Shows an empty-state message if no matching products are found.

2. **Form Validation (`js/validation.js`)**
   - Checks Name length (> 2 characters).
   - Validates Email format using regular expressions (Regex).
   - Checks Message length (at least 10 characters).
   - Displays clear error alerts and a success message upon sending.

3. **Cart & Wishlist Logic (`js/cart.js`)**
   - Dynamically adds a red item counter badge to the cart icon.
   - Temporary visual feedback on the "Add to basket" button.
   - Interactive wishlist toggle (♡ / ♥) using array methods.

4. **jQuery & UI Effects (`js/ui-effects.js`)**
   - Accordion effect (`slideToggle`) for the support timetable.
   - Image gallery fade transitions (`fadeOut` / `fadeIn`) when clicking thumbnails.
   - Sibling button selection for garment sizes.
   - Working dark mode toggle (🌙).

---

## Team Work Distribution

- **Mansur Nursultanov:** Catalogue data array, dynamic DOM generation, category filtering, and instant search.
- **Temkeshev Aldiyar:** Form validation logic, regular expressions, cart counter badge, and wishlist interactions.
- **Daniyar Baikanov:** jQuery animations, image gallery switcher, table accordion, and dark mode styling.

---

## Project Structure
```text
├── index.html
├── catalogue.html
├── productpg.html
├── about.html
├── contact.html
├── css/
│   ├── style.css
│   ├── main.css
│   ├── catalogue.css
│   ├── productpg.css
│   ├── about.css
│   └── contact.css
├── js/
│   ├── catalogue.js
│   ├── cart.js
│   ├── validation.js
│   └── ui-effects.js
├── photo/
└── README.md
```

---

## How to Run
1. Download or clone this repository.
2. Open `index.html` in any web browser.
3. Navigate between pages using the top navbar.
