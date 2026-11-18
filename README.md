# Engap Bakery website

A one-page showcase site for Engap Bakery: menu with prices, about, location and
WhatsApp contact. Built with [Astro](https://astro.build). No online ordering yet.

## Update the menu or contact details

- Menu items and prices: `src/data/menu.json`
- Address, hours, WhatsApp numbers, Instagram: `src/data/site.json`
- Photos: `public/images/` (credits in `CREDITS.md`)

## Run it on your computer

```sh
npm install
npm run dev      # opens a local preview at http://localhost:4321
npm run build    # makes the finished site in dist/
```

## Put it online

The site is static, so any free host works. On Vercel or Netlify: import this
GitHub repository, keep the detected Astro settings, and deploy. Every change
pushed to `main` then updates the live site.
