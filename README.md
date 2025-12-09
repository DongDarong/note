# Clothing Store Display Website

A small, static website that showcases clothing products and store information.

**Purpose:** A simple demo site for displaying product pages, contact info, and an about page. This repository contains only static HTML (and optionally CSS/JS assets) so it works by opening files in a browser or serving them from a lightweight HTTP server.

**Files:**
- `index.html`: Home / landing page.
- `product.html`: Product listing or detail page.
- `about.html`: About the store / company information.
- `contact.html`: Contact form or contact details.
- `README.md`: This file.

**Run locally:**
- Open `index.html` directly in your browser (double-click the file).
- Or serve the folder with a simple HTTP server (recommended for proper relative-path handling):

```powershell
# Python 3 (Windows PowerShell)
python -m http.server 8000
# then open: http://localhost:8000/
```

**Notes & Next Steps:**
- Add a site stylesheet at `styles.css` and link it from each HTML file for consistent styling.
- Add `scripts.js` for basic interactivity (mobile menu, product gallery lightbox).
- Store product images in an `assets/` or `images/` folder and reference them from the HTML.

If you'd like, I can add a responsive `styles.css`, a small `scripts.js`, and expand the content of `about.html` or `product.html` next.
