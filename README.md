# Qozary Official Website - GitHub Pages Static Site

This is a lightweight static brand website for Qozary.

## What this site is for

- Official brand presence
- Product catalog
- Amazon / Walmart traffic routing
- Customer support entry point
- Warranty / replacement information
- User manuals and size guides

## What this site is not

This first version does not include a shopping cart, payment system, account login, inventory system, or order management.

## Files

- `index.html` - homepage
- `products.html` - product listing page
- `product.html` - dynamic product detail page powered by URL parameter
- `support.html` - customer support page
- `about.html` - brand page
- `manuals.html` - manuals and size guides
- `warranty.html` - warranty and replacement support
- `privacy.html` - placeholder privacy policy
- `terms.html` - placeholder terms of service
- `assets/css/style.css` - design
- `assets/js/products.js` - product data
- `assets/js/main.js` - page interactions

## Important edits before publishing

1. Replace product dimensions with final confirmed dimensions.
2. Replace Amazon and Walmart URLs in `assets/js/products.js`.
3. Replace `support@qozary.com` in `assets/js/main.js` with your real support email.
4. Replace placeholder Privacy Policy and Terms pages.
5. Add real product images.
6. Add downloadable PDF manuals if needed.

## How to publish on GitHub Pages

1. Create a GitHub repository, for example `qozary-official`.
2. Upload all files in this folder.
3. Go to repository `Settings`.
4. Open `Pages`.
5. Choose `Deploy from a branch`.
6. Select branch `main` and folder `/root`.
7. Save.
8. GitHub will generate a public URL.

## Custom domain

If you want to use a custom domain, configure it in GitHub Pages settings and update DNS records at your domain provider.

Do not add a `CNAME` file until you are ready to bind the official domain.
