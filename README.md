# LUXE — Premium E-Commerce Website

A fully static e-commerce landing page built with **pure HTML & CSS only** — no JavaScript, no backend, no build tools.

## ✨ Features

All of the following are implemented with plain HTML and CSS (using the checkbox hack, `:target`, and `:has()`):

- 🌗 Dark / Light theme toggle
- 📱 Responsive mobile menu
- 🔍 Search bar toggle
- 🛒 Shopping cart drawer (open/close UI)
- 🖼️ Product detail modals
- 🔐 Login modal
- 🏷️ Category filter (Fashion, Shoes, Accessories, Watches, Bags)
- 💵 Price range filter (Under $25, $25–$50, $50+)
- ⬆️⬇️ Sort by price or rating

## 📁 Project Structure

```
ecommerce-wibsite/
├── index.html          # all markup, sections, modals
├── css/
│   └── style.css       # styling + pure-CSS interactivity
├── images/
│   ├── products/        # product photos
│   └── categories/      # category thumbnails
└── README.md
```

## 🚀 Run locally

No build step needed — just open `index.html` in any browser, or serve the folder with any static server:

```bash
# Python
python3 -m http.server 8000

# Node
npx serve .
```

Then visit `http://localhost:8000`.

## 🌐 Deploy

This project is a static site, so it works out of the box on:

- **Vercel** — import the repo, no build command needed, `index.html` must be at the repo root.
- **Netlify** — drag & drop the folder or connect the repo.
- **GitHub Pages** — enable Pages on the repo, pointing to the root/`main` branch.

## ⚠️ Known limitations (no JavaScript)

Since there's no JavaScript or backend, a few things are intentionally simplified compared to a fully dynamic store:

- The cart drawer opens/closes but doesn't actually add/remove items or persist between visits.
- The countdown timer shows a static time and doesn't tick down live.
- The search box opens/closes but doesn't filter results as you type.
- The newsletter/login forms use native HTML5 validation only (no custom success/error messages).

## 🛠️ Tech

- HTML5
- CSS3 (custom properties, `:has()`, `:target`, checkbox/radio hacks)
- [Font Awesome](https://fontawesome.com/) (icons, via CDN)
- [Google Fonts](https://fonts.google.com/) — Plus Jakarta Sans

## 📄 License

Free to use for personal or commercial projects.
