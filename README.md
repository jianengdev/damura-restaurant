# 🍜 Damura Ramen — Restaurant Website

A responsive, single-page digital menu and ordering interface for **Damura Ramen**, a Japanese ramen restaurant. Built with pure HTML and Tailwind CSS — no framework, no build step.

## ✨ Features

- **Full digital menu** — 70+ items across 11 categories: starters, baos, gyoza, mains, desserts, drinks, beer, wine, sake, and tea & coffee
- **Category filtering** — sticky horizontal nav bar to browse by section
- **Cart system** — add/remove items with quantity controls, persisted via `localStorage`
- **Floating cart bar** — live total and item count, links directly to checkout
- **Dark / light theme** — toggle with preference saved to `localStorage` and synced via URL param (supports link-sharing with a specific theme)
- **Responsive grid** — 1 to 5 columns depending on viewport size
- **Product images** pulled dynamically from the restaurant's own POS system

## 🛠 Tech Stack

| Tool | Usage |
|---|---|
| HTML5 | Structure & markup |
| [Tailwind CSS](https://tailwindcss.com) (CDN) | Utility-first styling |
| [Google Fonts](https://fonts.google.com) | Epilogue · Krona One · Space Grotesk · Be Vietnam Pro |
| [Material Symbols](https://fonts.google.com/icons) | Icons (cart, add, remove…) |
| `localStorage` | Cart & theme persistence |

No npm, no bundler, no dependencies to install.

## 📁 File Structure
