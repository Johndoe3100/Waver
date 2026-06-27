## 2025-05-14 - [LCP Protection in Documentation]
**Learning:** Applying `loading="lazy"` to the hero image (top-most asset) can negatively impact Largest Contentful Paint (LCP) as the browser waits to discover it.
**Action:** Always exclude the first/main logo from lazy loading in README optimizations.

## 2025-05-14 - [Pillow for Image Optimization]
**Learning:** Native image optimization tools like `cwebp` or `convert` are unavailable in this environment.
**Action:** Use `python3 -m pip install Pillow` and a Python script for bulk image conversion (PNG -> WebP) to achieve significant asset size reduction.
