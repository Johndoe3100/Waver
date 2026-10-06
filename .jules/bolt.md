## 2025-08-05 - Documentation Asset WebP Optimization
**Learning:** In documentation-focused repositories, image asset conversion (PNG to WebP quality 80) drastically reduces asset download sizes (~85.6% bandwidth reduction from ~5.02MB to ~724KB). Note that while GitHub's markdown renderer sanitizes raw HTML attributes like `loading="lazy"`, converting images to modern WebP format directly improves page load latency on all markdown viewers.
**Action:** Prioritize WebP conversion for heavy image assets in documentation repositories to achieve maximum bandwidth reduction.
