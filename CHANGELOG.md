# Changelog

## 1.1.0 — 2026-11-11

### Changed
- Gallery links get a real `href` to the full image instead of `data-src` (crawlable anchors, works before JS binds).
- Images are wrapped with `wrap()` instead of re-rendering via `outerHTML`: the original `<img>` node keeps `loading="lazy"`/`decoding`.
- Full image: largest `srcset` candidate, then `data-src`, then `src`.

### Fixed
- Images already inside a link were wrapped a second time (`parent() !== 'a'` was always true); now an existing link keeps its `href` and becomes a gallery item only if it points to an image.
