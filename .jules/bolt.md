## 2025-06-08 - Optimized README assets
**Learning:** High-resolution PNG images in the documentation can significantly slow down the initial load time of the project's repository page. Converting these to WebP with a quality setting of 80 provides a massive reduction in file size (~86% in this case) with no perceptible loss in quality for documentation purposes.
**Action:** Always check the `assets/` directory for large PNG/JPEG files and suggest conversion to WebP as a low-risk, high-impact performance win for documentation-heavy repositories.
