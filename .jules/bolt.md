## 2025-05-15 - [Image Optimization and Lazy Loading]
**Learning:** Converting PNGs to WebP (quality 80) in this documentation-heavy repo resulted in a massive ~85% size reduction (4.9MB -> 720KB). Lazy loading below-the-fold images is a low-risk, high-reward optimization for README-only repositories.
**Action:** Always check `assets/` for large PNGs and `README.md` for missing `loading="lazy"` in similar projects.
