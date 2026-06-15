## 2025-05-13 - Documentation Asset Optimization
**Learning:** In documentation-heavy repositories without a build system or standard test suite, performance optimizations should focus on asset size and browser rendering. Converting PNG to WebP with a quality of 80 provides a significant (~85%) reduction in size with no visible quality loss. Adding `loading="lazy"` to images below the fold is a critical complement to reduce initial page load.

**Action:** Always check the `assets/` directory for large images and the `README.md` for missing lazy-loading attributes. Use Pillow for image conversion as it's the most reliable tool available in this environment.
