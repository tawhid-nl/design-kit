# Design Kit

A white-labelled design system extracted from a production website. Use these tokens, styles, and component markup to reproduce the site's look and feel for any brand.

## Contents

- `tokens.css` - CSS custom properties (colors, typography, radius)
- `tokens.json` - the same tokens as JSON for tooling
- `components.css` - the full stylesheet (all components)
- `index.html` - a live preview / demo page
- `markup/` - HTML markup for each component (header, hero, verse, splash, footer)

## Usage

1. Link `tokens.css` and `components.css` in your page head.
2. Drop the component markup from `markup/` into your pages.
3. Override the `--ds-*` variables in `:root` to re-brand.

All brand-specific references have been removed. Replace the `BRAND` placeholder and `--ds-*` token values with your own.
