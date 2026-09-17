# Web Development Project Proposal Submission

# Apex Logic Systems Website - Part 2

## Student Information
* **Name:** [Kgothatso]
* **Surname:** [Mokhine]
* **Student Number:** [ST10477871]
* **Course / Module:** Web Development / HTML5
* **Date:** 18 September 2026
---

## 1. Executive Summary & Overview
Apex Logic Systems is a technology enterprise based in Pretoria, Gauteng, specializing in custom banking software, business process automation, and enterprise cloud integration. 

Part 2 introduces an external CSS framework (`css/style.css`), converting the initial plain HTML layout into an interactive, modern, and fully responsive website across desktop, tablet, and mobile displays.

---

## 2. Part 1 Feedback & Revision Changelog

### Feedback Addressed
- **Website Structure & Planning:** Re-architected page markup using semantic HTML5 tags (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, and `<footer>`).
- **Technical Requirements & Styling:** Connected external stylesheet (`css/style.css`), resolved navigation file pathing, and implemented CSS variables (`:root`) alongside a CSS Reset.
- **Academic Rigor:** Standardized all source citations in strict Harvard referencing format.

### Revision Changelog
- **v1.0 (Part 1):** Authored baseline HTML structure across core pages (`index.html`, `about.html`, `service.html`, `gallery.html`, and `contact.html`).
- **v1.1:** Linked external stylesheet `css/style.css` in all document `<head>` sections.
- **v1.2:** Established global color scheme, baseline typography, flexbox navigation bar, and sticky header layout.
- **v1.3:** Applied hero banner background image with gradient overlay (`linear-gradient`) and full-width viewport scaling (`100vw`).
- **v1.4:** Integrated responsive media queries for tablet (`max-width: 1024px`) and mobile (`max-width: 768px`) viewports.
- **v1.5:** Enhanced form controls, interactive button hover states (`:hover`, `:focus`), and image responsiveness (`max-width: 100%`).

---

## 3. Responsive Design Architecture & Breakpoints

### Viewport Breakpoints
- **Desktop (Default > 1024px):** Full-width hero cover image, side-by-side header layout, horizontal navigation bar, multi-column feature cards.
- **Tablet (`max-width: 1024px`):** Scaled root font sizing (`93.75%` / `15px`), condensed container margins, fluid grid adaptation.
- **Mobile (`max-width: 768px`):** Single-column stacked layout, full-width interactive buttons (`width: 100%`), vertical full-width navigation menu.

### Sizing Units & Fluidity
- **Typography & Spacing:** Styled using relative `rem` and `em` units for fluid browser zoom and text scaling.
- **Container Elements:** Built using fluid percentages (`%`) constrained by `max-width` rules.
- **Media Assets:** Enforced `max-width: 100%; height: auto;` to eliminate horizontal scrollbars and layout clipping across screens.

---

## 4. Screenshot Evidence

*(Include local screenshots of your pages across different viewport sizes)*
- **Desktop View:** `images/desktop-preview.png`
- **Tablet View:** `images/tablet-preview.png`
- **Mobile View:** `images/mobile-preview.png`

---

## 5. References (Harvard Style)
1. Duckett, J., 2011. *HTML and CSS: Design and Build Websites*. Indianapolis: John Wiley & Sons.
2. MDN Web Docs, 2026. *CSS: Cascading Style Sheets*. Available at: <https://developer.mozilla.org/en-US/docs/Web/CSS> [Accessed 15 September 2026].
3. W3C, 2026. *Responsive Web Design Basics*. Available at: <https://www.w3.org/WAI/WCAG21/Understanding/> [Accessed 15 September 2026].