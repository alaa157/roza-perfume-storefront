# ROZA · روزا — Arabic Perfume Storefront

A single-file, frontend-only demo boutique for Arabic perfumes — dark, luxe, RTL experience built with pure HTML + CSS + JS (no build step, no dependencies).

> Source file: `index.html` (originally from `~/Downloads/index.html`)

## ✨ What's inside

- **Hero** — روزا branding (AR + ROZA latin), animated arch spotlight that follows the mouse, SVG-rendered perfume bottle
- **Collection** — 6 fragrances (عود الليل، مخمل، أثر، وردة داكنة، عنبر ملكي، سكون) with family/collection filters + live search
- **Mood finder** — pick a vibe (دافئ، زهري، خشبي، منعش) and get curated picks
- **Product modal** — notes pyramid (top/heart/base), size, price (EGP), favorites
- **Cart drawer** — add/remove quantities, totals, Arabic-Indic numerals, toasts
- **Story + footer** — brand narrative and navigation
- Fully **responsive** (desktop / tablet / mobile) + `prefers-reduced-motion` support, keyboard accessible

## 🚀 Run it

Just open it — no server needed:

```bash
xdg-open index.html
# or
python3 -m http.server 8000
# then visit http://localhost:8000
```

## 🖼️ Screenshots

| Desktop hero (1440px) | Full page | Mobile (390px) |
|---|---|---|
| ![Desktop hero](screenshots/desktop-hero.png) | ![Full page](screenshots/desktop-full.png) | ![Mobile](screenshots/mobile.png) |

Screenshots were captured headlessly with Chrome from the exact `index.html` in this repo.

## 🛠️ Tech

- Single `index.html` (~95 KB, 1574 lines): embedded CSS + JS
- Fonts via Google Fonts: Aref Ruqaa / Amiri / IBM Plex Sans Arabic
- Bottles drawn as inline SVG (no image assets)
- State in vanilla JS (`PRODUCTS`, `MOODS`, cart Map, favorites Set)

## 📄 Note

Demo storefront with sample content — no backend, checkout is illustrative only.
