## 2025-06-02 - Large PNG Assets Optimization
**Learning:** Found several large PNG images in the `assets/` directory totaling ~4.9MB. These high-resolution images are used in the README and can significantly slow down the initial repository load and page rendering on GitHub/web. Converting them to WebP can provide substantial size reduction without noticeable quality loss.
**Action:** Convert all PNG assets to WebP format and update the README references to improve page load speed and reduce repository size.

**Performance Impact:**
- Total original size (PNG): 5,019,022 bytes (~4.8 MB)
- Total optimized size (WebP): 702,410 bytes (~0.67 MB)
- Overall size reduction: ~86%
- Page load improvement: Significant reduction in data transfer (saves ~4.1 MB) for README rendering.
