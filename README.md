# Hydrogen template: Skeleton

Hydrogen is Shopify’s stack for headless commerce. Hydrogen is designed to dovetail with [Remix](https://remix.run/), Shopify’s full stack web framework. This template contains a **minimal setup** of components, queries and tooling to get started with Hydrogen.

[Check out Hydrogen docs](https://shopify.dev/custom-storefronts/hydrogen)
[Get familiar with Remix](https://remix.run/docs/en/v1)

## What's included

- Remix
- Hydrogen
- Oxygen
- Vite
- Shopify CLI
- ESLint
- Prettier
- GraphQL generator
- TypeScript and JavaScript flavors
- Minimal setup of components and routes

## Getting started

**Requirements:**

- Node.js version 18.0.0 or higher

```bash
npm create @shopify/hydrogen@latest
```

## Building for production

```bash
npm run build
```

## Local development

```bash
npm run dev
```

## Setup for using Customer Account API (`/account` section)

Follow step 1 and 2 of <https://shopify.dev/docs/custom-storefronts/building-with-the-customer-account-api/hydrogen#step-1-set-up-a-public-domain-for-local-development>


│  Storefront setup complete!                                                                                                                                               │
│                                                                                                                                                                           │
│    Shopify:   Mock.shop                                                                                                                                                   │
│    Language:  TypeScript                                                                                                                                                  │
│    Styling:   Tailwind (v4 beta)                                                                                                                                          │
│    Markets:   Subfolders                                                                                                                                                  │
│    Routes:                                                                                                                                                                │
│      • Home (/ & /:catchAll)                                                                                                                                              │
│      • Page (/pages/:handle)                                                                                                                                              │
│      • Cart (/cart/* & /discount/*)                                                                                                                                       │
│      • Products (/products/:handle)                                                                                                                                       │
│      • Collections (/collections/*)                                                                                                                                       │
│      • Policies (/policies & /policies/:handle)                                                                                                                           │
│      • Blogs (/blogs/*)                                                                                                                                                   │
│      • Account (/account/*)                                                                                                                                               │
│      • Search (/search)                                                                                                                                                   │
│      • Robots (/robots.txt)                                                                                                                                               │
│      • Sitemap (/sitemap.xml & /sitemap/:type/:page.xml)                                                                                                                  │
│                                                                                                                                                                           │
│  Next steps                                                                                                                                                               │
│                                                                                                                                                                           │
│    • Run `cd OSC && npm run dev`        



##
Deploy on Netlify has 404 and deploy on vercel fails build :)

Dont have much experience deploying Hydrogen, does everything but not sure am missing 
something as is just: npm create @shopify/hydrogen@latest

I have been ill with cold

Havent implemented unit tests as i will be honest dont have experience with remix at this time, more nextjs/react/angular

I am subitting this but think is maybe cheeky :D