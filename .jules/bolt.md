## 2025-06-24 - [Image Optimization and Lazy Loading]
**Learning:** Converting PNG assets to WebP (quality 80) in documentation-heavy repositories provides a massive (~85%) reduction in total asset size with negligible quality loss. Adding `loading="lazy"` to below-the-fold images further improves initial page load performance.
**Action:** Always check `assets/` for large PNGs in documentation-centric repos and propose WebP conversion as a high-impact, low-risk optimization. Ensure the top-most visual asset (hero/logo) is NOT lazy-loaded to protect LCP.
