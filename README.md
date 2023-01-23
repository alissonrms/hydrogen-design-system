# Hydrogen Demo Store

Hydrogen is a React framework and SDK that you can use to build fast and dynamic Shopify custom storefronts.

[Check out the docs](https://shopify.dev/custom-storefronts/hydrogen)

[Run this template in JavaScript on StackBlitz](https://stackblitz.com/github/Shopify/hydrogen/tree/dist/templates/demo-store-js?file=package.json)

[Run this template in TypeScript on StackBlitz](https://stackblitz.com/github/Shopify/hydrogen/tree/dist/templates/demo-store-ts?file=package.json)

## Getting started

**Requirements:**

- Node.js version 16.14.0 or higher
- Yarn

```bash
yarn
yarn dev
```

Remember to update `hydrogen.config.js` with your shop's domain and Storefront API token!

## Building for production

```bash
yarn build
```

## Previewing a production build

To run a local preview of your Hydrogen app in an environment similar to Oxygen, build your Hydrogen app and then run `npm run preview`:

```bash
yarn build
yarn preview
```
