# WP Fancybox

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/tikhomirov/wp-fancybox-plugin/releases)
[![WordPress](https://img.shields.io/badge/WordPress-4.6%2B-blue.svg)](https://wordpress.org/)
[![PHP](https://img.shields.io/badge/PHP-8.0%2B-purple.svg)](https://php.net/)

Lightweight Fancybox integration for WordPress themes. Enables lightbox for linked images in post content when the theme declares support.

## Requirements

| Component | Minimum |
|-----------|---------|
| **WordPress** | 4.6 |
| **PHP** | 8.0 |

## Features

- Fancybox JS/CSS enqueued when theme supports `fancybox`
- Automatic binding to content images
- Composer package `rwsite/wp-fancybox-plugin`

## Installation

### Composer

```bash
composer require rwsite/wp-fancybox-plugin
```

### Manual

1. Download the [latest release](https://github.com/tikhomirov/wp-fancybox-plugin/releases).
2. Upload to `wp-content/plugins/wp-fancybox-plugin/`.
3. Activate **Fancybox js** in WordPress admin.

## Usage

In your theme `functions.php`:

```php
add_theme_support('fancybox');
```

## License

GPL-2.0-or-later

## Author

Aleksey Tikhomirov — [rwsite.ru](https://rwsite.ru)

---

## Русский

Плагин подключает Fancybox к изображениям в контенте. Включение: `add_theme_support('fancybox');` в теме.
