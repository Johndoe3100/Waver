## 2025-07-01 - Image Optimization Impact
**Learning:** Converting high-resolution PNG assets to WebP with a quality factor of 80 resulted in a massive ~85% reduction in asset size (4.9MB to 724KB) with negligible visual impact for documentation purposes. Implementing `loading="lazy"` for below-the-fold images further improves initial page load performance.
**Action:** Always check for unoptimized PNG/JPEG assets in documentation-heavy repositories and prefer WebP for significant bandwidth savings.
