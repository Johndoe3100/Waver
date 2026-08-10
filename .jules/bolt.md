# Bolt Journal

## 2025-08-10 - WebP Asset Optimization and Image Lazy Loading
**Learning:** Legacy heavy PNG images in documentation can significantly bloat repository size and increase first-load network payload, harming user experience and performance. Converting PNG images to WebP (quality=80) achieves a massive (~85.6%) reduction in asset size without noticeable loss of visual fidelity. Excluding above-the-fold visual elements (e.g. logos) from lazy-loading avoids degrading Largest Contentful Paint (LCP) performance, while below-the-fold images should always have `loading="lazy"`.
**Action:** Always identify heavy PNG images in `assets/` and convert them to `.webp` format at quality=80. Always append the `loading="lazy"` attribute to image elements below the fold.
