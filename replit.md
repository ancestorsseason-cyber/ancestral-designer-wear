# A.D.W — Ancestral Designer Wear

## Project overview
Static pre-built site for the A.D.W fashion brand. Contains compiled HTML/CSS/JS — no editable source code beyond `index.html`.

## How to run
Served via Python's built-in HTTP server (workflow: **Start application**, port 5000):
```
python3 serve.py
```

## Key files
- `index.html` — full single-page site (hero, collections, gallery, about, contact, footer)
- `assets/adw-logo-nobg.png` — background-removed version of the new ADW logo (used everywhere)
- `assets/new_adw_logo.png` — original logo with background
- `serve.py` — Python static file server with CORS headers

## Collections section
- **128 products** across 8 categories: Clothes, Shoes, Watches, Bags, Accessories, Jewelry, Perfume, Headwear
- **8 Men's + 8 Women's items** per category
- **Gender filter**: All / Men / Women toggle
- **Category tabs**: all 8 categories
- Each product card shows the animated ADW logo (CSS float animation), up to 8 colour swatches, size chips, and a WhatsApp enquiry link
- All JS-rendered from a `PRODUCTS` data array in `index.html` — no backend

## GitHub remote
- Repository: `https://github.com/ancestorsseason-cyber/ancestral-designer-wear`
- Branch: `main`
- GitHub Pages should be configured to serve from `main` root

## User preferences
