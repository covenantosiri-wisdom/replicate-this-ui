# Replicate This UI

A front-end practice project built to sharpen HTML and CSS skills by recreating the UI of a product rack / best-sellers storefront section as closely as possible to a reference design.

This was the first project completed during a SIWES (Students Industrial Work Experience Scheme) placement at **Aptiw Software Labs**.

## Preview

**Target design**

![Target UI](./Goal%20photo.png)

## About

The goal of this project was simple: given a reference screenshot of a product listing UI, rebuild it from scratch using only HTML and CSS — matching layout, spacing, typography, and interactive states as closely as possible.

The page recreated here is a "Shop Our Best-Sellers" storefront section featuring:

- A header with a logo/breadcrumb and a tabbed navigation menu (Best sellers / Featured / Care magic)
- A hero area with a heading, supporting copy, and carousel navigation controls
- A responsive grid of product cards, each with:
  - A product image
  - A save/wishlist button
  - A "Buy now" call-to-action and a details arrow button
  - Price, product name, category, and size

## Tech Stack

- **HTML5** — semantic page structure
- **CSS3** — layout, styling, and visual effects, including:
  - CSS Grid and Flexbox for layout
  - Glassmorphism effects on card overlays
  - Absolutely positioned elements for buttons and badges layered on product images
- **[Font Awesome](https://fontawesome.com/)** — icons (arrows, etc.)
- **Google Fonts** — Caveat, Inter, Libre Baskerville, Roboto Slab, Roboto

No JavaScript, frameworks, or build tools are used — this is a pure HTML/CSS implementation.

## Project Structure

```
replicate-this-ui/
├── images/            # Product and UI images
├── Goal photo.png     # Reference/target design used for the replication
├── index.html         # Page markup
└── style.css          # Styling
```

## Getting Started

No build step or dependencies are required.

1. Clone the repository:
   ```bash
   git clone https://github.com/covenantosiri-wisdom/replicate-this-ui.git
   ```
2. Open `index.html` directly in your browser, or serve it locally (e.g. with the VS Code "Live Server" extension) for the best experience.

## Deployment

View at: https://vercel.com/ctgeees-projects/replicate-this-ui/5YexGHkyaynNWd2rsm9LezjNMsYX

## Acknowledgements

Built as part of a SIWES industrial training placement at Aptiw Software Labs, as a hands-on exercise in matching an existing UI pixel-for-pixel using HTML and CSS.
