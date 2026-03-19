# Shopify Dawn Theme — Custom Development

A customised version of Shopify's default **Dawn theme**, modified for learning and development purposes.

## Customisations

- **Product Metafields Display** — Added `Made In` metafield display on product pages via `sections/main-product.liquid`
- **Custom Sections & Blocks** — Explored and modified theme sections, blocks and settings
- **Schema Configuration** — Custom block and section settings via JSON schema
- **Locales** — Explored translation files (`locales/en.json`, `locales/fr.json`)

## Tech Stack

- Shopify Liquid
- JSON (section/block schemas)
- CSS / JavaScript
- Shopify CLI

## Setup

1. Install Shopify CLI
```bash
npm install -g @shopify/cli
```

2. Clone this repo
```bash
git clone <your-repo-url>
cd your-theme
```

3. Push to your Shopify store
```bash
shopify theme push
```

4. Or preview locally
```bash
shopify theme dev
```

## Project Structure

```
├── assets/          → CSS, JS, images
├── config/          → Theme settings (settings_schema.json, settings_data.json)
├── layout/          → theme.liquid (main layout file)
├── locales/         → Translation files
├── sections/        → Reusable page sections
├── snippets/        → Reusable Liquid components
└── templates/       → Page templates (JSON)
```

## Learning Outcomes

- Shopify theme architecture (sections, blocks, snippets)
- Liquid templating language
- Metafields integration and display
- Theme settings and schema configuration
- Shopify CLI workflow (pull, push, dev)

## Resources

- [Shopify Dawn Theme](https://github.com/Shopify/dawn)
- [Shopify Liquid Documentation](https://shopify.dev/docs/api/liquid)
- [Shopify CLI](https://shopify.dev/docs/api/shopify-cli)