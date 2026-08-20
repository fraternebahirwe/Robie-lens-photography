# 📸 Robbie Lens Photographie

> A multi-page responsive photography portfolio website showcasing landscape photography, portraiture, studio services, and an interactive contact form.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

## 📄 Site Architecture

The project consists of three main pages connected via a top navigation bar:

1. **`index.html` (Accueil / Home Page):**
   - Hero banner with introduction and call-to-action button.
   - Featured projects grid showcasing recent photography work.
   - Interactive project inquiry contact form (`#contact`).

2. **`a-propos.html` (À propos / About Page):**
   - Overview of professional photography services (Portraits, Fashion Shoots, Custom Retouching).
   - Structured pricing table detailing studio resources and lighting assistant services.

3. **`portfolio.html` (Portfolio Page):**
   - Visual galleries categorized by **Paysages** (Landscapes) and **Portraits**.
   - Accessible image grids optimized for asynchronous/lazy loading.

---

## ✨ Features & Best Practices

- **Semantic HTML5:** Built using semantic tags (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`, `<figure>`).
- **Performance Optimized:** Images use native `loading="lazy"` and `decoding="async"` attributes for fast initial page renders.
- **Accessibility (a11y):** Form fields mapped with explicit `<label>` tags, and full `aria-label` coverage on links and imagery.
- **Typography:** Custom typography powered by Google Fonts (*Manrope*, *Montserrat*, and *Playfair Display*).
- **Responsive Navigation:** Consistent navbar and footer links across all pages.

---

## 📂 Repository Structure

```text
.
├── index.html          # Main landing page & contact form
├── a-propos.html       # Biography, services & pricing table
├── portfolio.html      # Categorized image galleries (Landscapes & Portraits)
├── design.css          # Primary stylesheet
├── style.css           # Additional layout styles
├── img/                # Logos and social icons
├── accueil/            # Home page gallery assets
└── portfolio/          # Landscape and portrait gallery assets
