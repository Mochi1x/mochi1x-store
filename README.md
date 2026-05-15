# Mochi Templates Store

Notion template shop — dark glassmorphism aesthetic, sold via Lemon Squeezy.

## Structure
```
/
├── index.html              # Storefront
├── product/
│   └── idea-board-pro.html # Product page w/ LS embed
├── legal/
│   ├── terms.html
│   └── privacy.html
├── css/
│   └── style.css           # Shared design system
└── README.md
```

## Deploy (GitHub Pages)

1. Create repo `mochi1x-store` on GitHub (public)
2. Push this repo's contents to `main`
3. Settings → Pages → Source: `main / root` → Save
4. Site goes live at: https://mochi1x-store.github.io

## Add a product on Lemon Squeezy

1. Product → New Product → Price → Digital Good
2. Save the product, grab the **Checkout ID**
3. Drop it into the `<div id="lemon-squeezy" data-checkout-id="CHECKOUT_ID">` in the product page
4. Update name, price, description, and thumbnail there

## Design tokens (css/style.css)

```
--bg: #0a0a0f
--amber: #e8a23f
--amber-glow: rgba(232,162,63,.25)
--surface: rgba(255,255,255,.04)
--border: rgba(255,255,255,.08)
--radius: 14px
--spring: cubic-bezier(.23,1,.32,1)
```
