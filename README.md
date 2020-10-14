# shopify-swatches
My version of Swatches for Shopify themes which is compatible with themes which changes the chosen variant from dropdowns

This swatches implementation was created atop the Shopify Pipiline theme v4.

* Uses simple transition animations
* Uses Flexbox for layout and responsive swatches

To use:

1) Create new asset product_swatches.scss and copy/paste code
2) Add link to file in theme.liquid

{{ 'product_swatches.scss.css' | asset_url | stylesheet_tag }}

3) Rename product-form.liquid snippet and create snippet of the same name and copy/paste code
