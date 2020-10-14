# shopify-swatches
My version of Swatches for Shopify themes which is compatible with any themes which breaks down variants into option dropdowns. This may be handled by the theme using the Shopify selectCallback function or not.

To use selectCallback, must include:

{{ 'option_selection.js' | shopify_asset_url | script_tag }}

Go to https://shopify.dev/tutorials/customize-theme-use-products-with-multiple-options for more info.


This swatches implementation was created atop the Shopify Pipiline theme v4.

* Uses simple transition animations
* Uses Flexbox for layout and responsiveness

To use:

1) Create new asset product_swatches.scss and copy/paste code
2) Add link to file in theme.liquid

{{ 'product_swatches.scss.css' | asset_url | stylesheet_tag }}

3) Rename product-form.liquid snippet and create snippet of the same name and copy/paste code
