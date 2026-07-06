## 2025-05-15 - Image Optimization for Documentation-Centric Repos
**Learning:** In repositories that are primarily documentation (like this one), image optimization (WebP conversion) and lazy loading are the most impactful performance wins. WebP reduced the asset size by ~85% (4.9MB to 724KB).
**Action:** Always check `assets/` for unoptimized PNG/JPG files and apply `loading="lazy"` to below-the-fold images in README.md.
