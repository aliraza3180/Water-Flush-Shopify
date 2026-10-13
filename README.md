# Water Flush: Shopify theme

A Shopify storefront for a dietary supplement, built on Shopify's Horizon 4.2.0 theme with a set of custom sections.

## Custom work

All custom sections appear in the theme editor as "WF | ...".

| Section | File |
|---|---|
| Hero | `sections/wf-hero.liquid` |
| Trust bar | `sections/wf-trust-bar.liquid` |
| Image with text | `sections/wf-image-text.liquid` |
| Feature grid | `sections/wf-feature-grid.liquid` |
| Ingredients | `sections/wf-ingredients.liquid` |
| Size selector with quantity and Add to cart | `sections/wf-size-selector.liquid` |
| Bundle row | `sections/wf-bundle-row.liquid` |
| FAQ (numbered, two columns, structured data) | `sections/wf-faq.liquid` |
| Diagram | `sections/wf-diagram.liquid` |
| Call to action | `sections/wf-cta.liquid` |
| Disclaimer | `sections/wf-disclaimer.liquid` |

Shared snippets are in `snippets/wf-*.liquid` and the styles are in `assets/wf-sections.css`.
The size selector adds to cart through Horizon's own product form component, so the cart drawer and cart count update as they do on the product page.

## Notes

- Company, brand names and contact details in the content are placeholders.
- Images are referenced from the store's Shopify Files and are not part of this repository.
- Horizon is a theme by Shopify.

## Local development

```
shopify theme dev --store your-store.myshopify.com
```
