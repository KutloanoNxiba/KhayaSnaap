# KhayaSnaps Photography — Static Website


This repository contains a simple, responsive, image-first photography website for **KhayaSnaps Photography**. It's ready to be hosted on GitHub Pages or Netlify. The site uses plain HTML, CSS and JavaScript and includes a Netlify Forms-ready booking form.


### Files
- `index.html` — main site markup
- `styles.css` — site styles
- `scripts.js` — interactivity (lightbox, smooth scroll, mobile menu)
- `logo.svg` — simple logo SVG
- `netlify.toml` — Netlify configuration
- `/images/` — folder for your photos (NOT included). Add your images here.


### How to add your images
1. Create a folder named `images` at the root of the repo.
2. Replace placeholder image names in `index.html` with your files, for example:
- `images/portfolio1.jpg`, `images/portfolio2.jpg`, etc.
3. Recommended: add optimized JPG/WEBP files, keep size under ~1–2MB each for faster load.
4. Update hero video or hero image in `index.html` if you prefer a video hero.


### Deploying to Netlify
1. Push this repository to GitHub.
2. Go to Netlify -> New site -> Import from Git -> choose your repo.
3. Set **Build command**: leave empty (static site), **Publish directory**: `/` (root) or `.`
4. Netlify Forms will pick up the form automatically if `index.html` contains `data-netlify="true"`.


### Replace contact info
Open `index.html` and update the email and social links to: `ayabongazixunge@gmail.com`, Facebook: `khayasnap` and `Kickoffkings`, TikTok: `Khayasnap12` and `Khayasnap`.
