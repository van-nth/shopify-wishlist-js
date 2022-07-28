# Shopify Wishlist using Javascript

- Compatible with Online Store

## Installation

1. In the `assets` folder, create 2 files:

- `wishlist.js`
- `wishlist.css`

2. Place these script in `theme.liquid` before the closing `</head>` tag

- `<script id="Wishlist" data-handle={{ product.handle }} src="{{ 'Wishlist.js' | asset_url }}" defer="defer"></script>`
- `{{ 'wishlist.css' | asset_url | stylesheet_tag }}`
