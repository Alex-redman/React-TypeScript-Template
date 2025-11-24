
---

# NICE GADGETS — Product Catalog

A responsive product catalog inspired by premium tech aesthetics.
The project includes category pages, product details, a cart, favorites, pagination, image galleries, and reusable UI components.
The main goals were practicing React, TypeScript, SCSS modules, routing, state management, and building a scalable front-end structure.

---

## Live Preview

- [DEMO LINK](https://alex-redman.github.io/React-TypeScript-Template/)

---

## Design Reference

[Figma link here](https://www.figma.com/design/T5ttF21UnT6RRmCQQaZc6L/Phone-catalog--V2--Original?node-id=0-1&p=f)

---

## Technologies Used

* React (functional components)
* TypeScript
* React Router
* SCSS modules
* BEM-inspired class naming
* Responsive design (Flexbox / Grid)
* Context API for global state (Cart / Favorites)
* Reusable UI elements (dropdowns, sliders, pagination)

---

## Project Structure

```
src/
│   App.scss
│   App.tsx
│   index.scss
│   index.tsx
│   vite-env.d.ts
│
├───components
│   ├───BackButton
│   │       BackButton.module.scss
│   │       BackButton.tsx
│   │       index.ts
│   │
│   ├───Breadcrumbs
│   │       Breadcrumbs.module.scss
│   │       Breadcrumbs.tsx
│   │       index.ts
│   │
│   ├───BurgerMenu
│   │       BurgerMenu.module.scss
│   │       BurgerMenu.tsx
│   │       index.ts
│   │
│   ├───Card
│   │       Card.module.scss
│   │       Card.tsx
│   │       index.ts
│   │
│   ├───Description
│   │       Description.module.scss
│   │       Description.tsx
│   │       index.ts
│   │
│   ├───Footer
│   │       Footer.module.scss
│   │       Footer.tsx
│   │       index.ts
│   │
│   ├───Header
│   │       Header.module.scss
│   │       Header.tsx
│   │       index.ts
│   │
│   ├───Loader
│   │       index.ts
│   │       Loader.module.scss
│   │       Loader.tsx
│   │
│   ├───Pagination
│   │       index.ts
│   │       Pagination.module.scss
│   │       Pagination.tsx
│   │
│   ├───PicturesSwiper
│   │       index.ts
│   │       PicturesSlider.module.scss
│   │       PicturesSlider.tsx
│   │
│   ├───ProductControls
│   │       index.ts
│   │       ProductControls.module.scss
│   │       ProductControls.tsx
│   │
│   ├───ProductGallery
│   │       index.ts
│   │       ProductGallery.module.scss
│   │       ProductGallery.tsx
│   │
│   ├───ProductSwiper
│   │       index.ts
│   │       ProductSwiper.module.scss
│   │       ProductSwiper.tsx
│   │
│   ├───SortDropdown
│   │       index.ts
│   │       SortDropdown.module.scss
│   │       SortDropdown.tsx
│   │
│   ├───TechSpecs
│   │       index.ts
│   │       TechSpecs.module.scss
│   │       TechSpecs.tsx
│   │
│   └───ToggleButton
│           index.ts
│           ToggleButton.module.scss
│           ToggleButton.tsx
│
├───context
│       CartContext.tsx
│
├───imgs
│   └───svg
│           arrow-bottom-icon.svg
│           arrow-left-icon.svg
│           arrow-right-icon.svg
│           arrow-up-icon.svg
│           cart-icon.svg
│           cross-icon.svg
│           favorite-icon-selected.svg
│           favorite-icon.svg
│           home-icon.svg
│           Logo.svg
│           menu-icon.svg
│
├───pages
│   ├───AccessoriesPage
│   │       AccessoriesPage.module.scss
│   │       AccessoriesPage.tsx
│   │       index.ts
│   │
│   ├───CartPage
│   │       CartPage.module.scss
│   │       CartPage.tsx
│   │       index.ts
│   │
│   ├───FavoritesPage
│   │       FavoritesPage.module.scss
│   │       FavoritesPage.tsx
│   │       index.ts
│   │
│   ├───HomePage
│   │       HomePage.module.scss
│   │       HomePage.tsx
│   │       index.ts
│   │
│   ├───NotFoundPage
│   │       index.ts
│   │       NotFoundPage.module.scss
│   │       NotFoundPage.tsx
│   │
│   ├───PhonesPage
│   │       index.ts
│   │       PhonesPage.module.scss
│   │       PhonesPage.tsx
│   │
│   ├───ProductDetailsPage
│   │       index.ts
│   │       ProductDetailsPage.module.scss
│   │       ProductDetailsPage.tsx
│   │
│   └───TabletsPage
│           index.ts
│           TabletsPage.module.scss
│           TabletsPage.tsx
│
├───styles
│       index.ts
│       mixins.scss
│       mixinsTypography.scss
│       variables.scss
│
└───types
        Accessories.ts
        colorMap.ts
        Phones.ts
        Product.ts
        Tablets.ts
        ToggleButtonProps.ts
```

---

## Getting Started

### Clone the repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### Install dependencies

```bash
npm install
```

### Run the project locally

If you have a dev server configured:

```bash
npm start
```

If not — simply open `index.tsx` in your browser.

---

## Features

* Fully responsive layout
* Burger menu and mobile navigation
* Card-based product layout
* Clean BEM class naming for maintainability

---

## Notes About the Code

* Image assets live in /src/imgs — verify paths after deployment.
  If you want to connect Formspree or backend — this must be replaced.
* SCSS modules are well-organized — maintain consistency when adding new components.
* Check favicon and icons after deployment.

---

## Deployment Tips

* GitHub Pages may require relative asset paths.
* Vite projects deploy easily on Vercel / Netlify.
* After deployment, verify:
  * routing fallback (index.html)
  * correct image paths
  * gallery and swiper functionality

---

## README Checklist

* [x] Correct project title
* [x] Clear description
* [x] Working live demo
* [x] Tech stack
* [x] Setup instructions
* [x] Clean folder structure
* [x] No unnecessary files

---

