## 2025-07-03 - [Asset Optimization and Documentation]
**Learning:** In documentation-heavy repositories (like research project pages), the primary performance bottleneck is often the payload of static assets in the README. Converting large PNGs to WebP (quality=80) yielded a ~85% size reduction without perceptible quality loss.

**Action:** Always check `assets/` size and use `loading="lazy"` for below-the-fold images in README.md to improve initial page load performance.
