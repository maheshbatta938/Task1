# Bootstrap Remix — Project

## Project Overview 
## LIVE https://maheshbatta938.github.io/Task1/

**Goal:** Remix Bootstrap 5 components to produce clean, responsive pages (Home / About / Contact) demonstrating navbars, hero/carousel, cards, forms, and modals.

This repository contains:
- `index.html` — Home (Navbar, Hero carousel, Features, Cards, Modal, Footer)
- `about.html` — About / Services
- `contact.html` — Contact with working form (Formspree placeholder)
- `css/style.css` — Minimal custom styles and spacing tweaks

## How I built it (step-by-step)
1. Bootstrapped the project structure (HTML files + `css/` folder).
2. Added Bootstrap 5 and Bootstrap Icons via CDN for fast prototyping.
3. Designed a hero carousel on the homepage combining a text column + image column.
4. Selected card patterns from Bootstrap examples for the Features and Gallery sections.
5. Implemented a modal for quick previews and a CTA section.
6. Created the About page with card services and a sticky sidebar.
7. Built the Contact page with a form using Formspree for demo submissions and added client-side validation via HTML5 & JavaScript fetch.
8. Added small custom CSS for consistent radius/spacing and responsive tweaks.
9. Tested layout at multiple widths (mobile, tablet, desktop) and adjusted spacing with utility classes.

## Transparency (AI / resources)
- Main resources used:
  - Bootstrap 5 official documentation & Examples (components, utilities, layout).
  - Unsplash images for placeholder hero/gallery images.
- Tools used:
  - I used ChatGPT (for small snippets and validation suggestions).
  - Bootstrap docs for component reference.
  - No full-copying of example pages — components were extracted and recomposed into original pages.

## Challenges & solutions
- **Responsive image cropping:** solved by using `object-fit: cover` and fixed heights on hero/gallery images.
- **Form handling without backend:** used Formspree as a simple forms endpoint and added client-side fetch handling to show success/failure.
- **Keeping design consistent:** created a small `:root` palette and reused Bootstrap utility classes for spacing and alignment.

## Deployment (GitHub Pages)
1. Initialize git and push:
   ```bash
   git init
   git add .
   git commit -m "Initial commit - Bootstrap Remix"
   git branch -M main
   git remote add origin git@github.com:yourusername/bootstrap-remix.git
   git push -u origin main
