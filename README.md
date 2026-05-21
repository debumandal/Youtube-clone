# YouTube Homepage Clone

A responsive, pixel-perfect frontend clone of the YouTube homepage built from scratch. This project was developed as a deep-dive training exercise to master modern CSS layouts, semantic HTML5 design patterns, and responsive web accessibility standard practices.

## 🚀 Live Demo
[View Live Project](https://debu-youtube-clone.netlify.app/) | [View Code Repository](https://github.com/debumandal/Youtube-clone.git)

---

## 🛠️ Key Architectural Focus Areas

When I initiated this project, my goal wasn't just to make a page that looks like YouTube visually; I wanted to build it with production-grade engineering practices.

### 1. Semantic Architecture & Accessibility (a11y)
Instead of relying on generic "div-soup," the markup layout is intentionally separated into standard structural components:
*   `<header>` and `<form role="search">` containers defining the top layout.
*   `<nav>` wrapped with clean nested unordered lists (`<ul>`, `<li>`) mapping the sidebar menu.
*   `<main>` enclosing a highly optimized grid layout of independent `<article>` components representing video records.
*   Strict accessibility rules implemented via descriptive image `alt` text and empty mappings (`alt=""`) on purely decorative media links to optimize usability for screen readers.

### 2. Complex Layout Patterns & CSS Mastery
*   **Flexbox Alignment:** Deployed extensive alignment properties (`align-items: center`, `justify-content: space-between`) to handle multi-zone alignments within the header sections.
*   **CSS Grid Dynamics:** Constructed a fully responsive, clean video display dashboard layout that accommodates shifting fluid grid screens effortlessly.
*   **Hover Overlays & Tooltips:** Built pure CSS custom hover tooltips and rich popover profiles (like the channel hover view cards) using absolute and relative coordinate structures entirely without relying on JavaScript libraries.

---

## ⚙️ Built With

*   **HTML5** — Structured semantic elements for performance, clean indexing, and optimized document accessibility.
*   **CSS3** — Custom layout configurations, fluid sizing models, structural animations, responsive flexboxes, grids, and typography rendering.
*   **Google Fonts** — Styled using the official Roboto web typography scales.

---

## 🎓 Acknowledgments & Credits

* **Design & Project Concept:** This project layout and asset collection are based on the excellent **HTML & CSS Full Course** by [SuperSimpleDev](https://www.youtube.com/@SuperSimpleDev). 
* **My Contribution:** While following the visual framework of the course, I independently refactored the structural codebase into modern semantic HTML5, audited the document for web accessibility standard compliance (a11y), and optimized asset attributes for screen readers.

---
## 📈 Engineering Evolution & Refactoring Lesson

This project represents a crucial milestone in my growth as a front-end engineer:
1. **The Layout Phase:** Initially, my core focus was purely resolving structural CSS calculations—handling fluid layout grids, flex limits, positioning absolute dynamic timestamps, and creating robust tooltip states.
2. **The Clean Code Refactor:** Once the visual layouts were production-accurate, I went back and meticulously refactored my entire document tree from meaningless layouts into descriptive semantic HTML5 components.

This exercise deeply reinforced how to balance complex interface requirements alongside semantic data integrity, accessibility considerations, and sustainable selector styling logic.

---

Developed with 💻 by [Debu Mandal](www.linkedin.com/in/debumandal-dev)
