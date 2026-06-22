## 2026-06-22 - [Asset Optimization]
**Learning:** Converting high-resolution PNGs to WebP (quality=80) in documentation-heavy repositories can yield ~85% size reduction with negligible visual impact. Adding `loading="lazy"` to below-the-fold images further improves page performance, but it must be avoided for the hero/logo to prevent LCP regressions.
**Action:** Always check for large PNGs in READMEs and apply both WebP conversion and selective lazy loading as a standard performance baseline.
