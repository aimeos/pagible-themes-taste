# Taste Theme

A modern restaurant, food and drinks theme for [Pagible CMS](https://pagible.com). Its composition is inspired by the welcoming, image-led rhythm of the Ichiraku Ramen reference while using a contemporary mineral palette and no animation or transition effects.

This package is part of the [Pagible CMS monorepo](https://github.com/aimeos/pagible).

## Installation

```bash
composer require aimeos/pagible-themes-taste
php artisan vendor:publish --tag=cms-theme
```

## Design

- **Style**: Image-led restaurant pages with a split hero, menu cards, editorial story sections and practical visit information
- **Colors**: Warm limestone (`#F6F4EC`), ink (`#17211D`), deep green (`#1F6B5C`) and burnt coral (`#B43B22`)
- **Typography**: Rounded system sans-serif with compact labels and large, friendly display headings
- **Surfaces**: Generous rounded panels, crisp image crops and alternating light, mint and dark-green sections
- **Motion**: No CSS animations, transitions or smooth scrolling
- **CSS framework**: Pico CSS with `--pico-*` custom property overrides

## Page Types

| Type | Description |
|------|-------------|
| `page` | Restaurant landing, menu and visit pages |
| `docs` | Documentation or recipe collections |
| `blog` | News, recipes and journal articles |

## License

MIT
