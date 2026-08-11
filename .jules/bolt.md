## 2025-08-11 - Image Optimization & Lazy Loading
**Learning:** Top-level images (like logo.webp) are critical for LCP (Largest Contentful Paint) and should not be lazy-loaded to avoid performance degradation. In contrast, below-the-fold images should be lazy-loaded to defer network overhead.
**Action:** Always omit loading="lazy" for above-the-fold/critical visual assets while applying it strictly below the fold.
