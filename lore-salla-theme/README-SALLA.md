# LORE Salla Theme Notes

This repo now includes a Salla-compatible theme base in:

- `twilight.json`
- `src/views`
- `src/assets`
- `src/locales`

The old Next.js prototype is still present for visual reference, but the Salla-ready implementation is the `src/` theme structure.

## What was adapted

- Homepage rebuilt in Twig: `src/views/pages/index.twig`
- Product listing rebuilt for Salla: `src/views/pages/product/index.twig`
- Single product rebuilt for Salla: `src/views/pages/product/single.twig`
- Shared theme layout: `src/views/layouts/master.twig`
- Shared styling: `src/assets/styles/lore.css`

## Before importing to Salla

1. Push this repository to GitHub.
2. In Salla Partners / theme workflow, connect or import the GitHub repository.
3. Confirm the final required page filenames with your Salla theme preview.
4. Replace placeholder links such as `/page/about` if your store uses different page slugs.
5. Test add-to-cart, wishlist, search, and customer/account pages inside the Salla preview environment.

## Important

This theme base is now structured for Salla, but it still needs theme-preview QA inside Salla because store routes, enabled features, and available objects can vary by store configuration.
