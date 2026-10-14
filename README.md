# ATP Healthy Baking: interactive recipe book

One self-contained file (`index.html`, ~1 MB). All photos are embedded, and there's no build step or backend.

## Hosting
- Upload `index.html` anywhere static, e.g. atpfit.co.za/recipes (Next.js: put it in /public/recipes/index.html).
- Fonts load from Google Fonts. Everything else is inline.
- Favourites, ticked ingredients, shopping ticks and timers save to the visitor's own browser (localStorage).

## To edit
- Product links: the `PRODUCT_URLS` block at the top of the <script>. They currently point to /products; swap in the exact isolate/collagen pages.
- Recipes: the `R` array (ingredients, steps, nutrition, timers). Shopping list: the `SHOP` object.

## Nice to add on the live site
- A web app manifest + 192/512 px icons, so "Add to Home Screen" opens it full-screen like an app.
