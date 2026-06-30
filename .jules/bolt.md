## 2024-06-30 - Asset Optimization and Lazy Loading
**Learning:** Converting PNG to WebP with quality=80 provided a massive ~85% size reduction in this repo without noticeable quality loss. Applying lazy loading to below-the-fold assets further improves initial page load.
**Action:** Always check for large PNG assets in documentation and convert to WebP. Ensure above-the-fold assets are NOT lazy loaded to avoid LCP issues.
