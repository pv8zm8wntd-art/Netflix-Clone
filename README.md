<div align="center">

# 🍿 Netflix UI Clone

### ⚡ A Pixel-Perfect, High-Precision Netflix Landing Page Built with Pure HTML & CSS ⚡

![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Design-success?style=for-the-badge&logo=responsive)
![No JS](https://img.shields.io/badge/JavaScript-Zero_Dependencies-red?style=for-the-badge)

</div>

---

> 🌟 **Project Showcase:** Recreating the world's most iconic streaming platform interface with 100% pixel-perfect visual precision, smooth layout balance, dynamic video overlays, and seamless responsiveness — engineered purely using core HTML & CSS without relying on any JavaScript, Bootstrap, or external frameworks!

---

## 🔥 Key HTML & CSS Features Used

### 📐 Layout & Alignment
- `display: flex`
- `flex-direction: column`
- `flex-wrap: wrap`
- `justify-content` (`space-between`, `center`)
- `align-items: center`
- `gap`
- `display: grid`
- `grid-template-columns` (`1fr 1fr 1fr 1fr` & `1fr 1fr`)

### 📍 Positioning & Layering
- `position: relative`
- `position: absolute`
- `z-index`
- `top` / `right`
- `margin: auto`

### 📏 Math, Sizing & Units
- `calc()` (e.g., `calc(100% - 100px)`)
- `vw` & `vh` (Viewport Units)
- `max-width`
- `background-size: max(1200px, 100vw)`

### 🎨 Styling, Filters & Interactivity
- `filter: invert(1)`
- `transition`
- `opacity`
- `background-position`, `background-repeat`
- `:hover` pseudo-class
- `:nth-child()` pseudo-selectors

### 📱 Responsive Engineering
- `@media` queries (`screen and (max-width: 1300px)`)
- Dynamic font scaling
- Mobile-first element stacking

### 🧱 HTML Structural Elements
- `<nav>`, `<section>`, `<footer>`
- `<video autoplay loop muted>`
- `<img>` & `<svg>` vectors
- `<input>` & `<button>`

---

## 🧠 What I Learned From This Project

Is project ko complete karne ke baad mujhe frontend UI engineering ke ye saare major concepts aur best practices practically samajh aaye:

- 🏗️ **Core UI Architecture:** Without JavaScript or CSS libraries, raw HTML & CSS alone can build production-ready, industry-level user interfaces.
- 📐 **Mastering Modern Layout Systems:** Deep practical understanding of when to use **Flexbox** vs **CSS Grid** for complex UI components.
- 🎯 **Advanced Element Stacking:** Using `position: absolute` & `z-index` to embed playing videos inside device/TV frame images smoothly.
- 📲 **Responsive Design Thinking:** Designing layouts that automatically adapt across desktops, laptops, tablets, and smartphones using `@media` query breakpoints.
- 🎨 **Pure CSS Micro-Interactions:** Creating hover feedback effects, smooth transitions, and dynamic SVG color inversion without writing JS scripts.
- 🧹 **Clean & Organized Code Structure:** Writing clean, scalable, and well-grouped CSS rules for easy maintenance.

---

## 📁 Project Structure

```text
netflix-clone/
│
├── index.html        # Clean, semantic page structure
├── style.css         # Styling, Flexbox, Grid & Media Queries
└── assets/           # Background graphics, SVGs, device frames & videos
