## 2025-05-15 - Asset Optimization: PNG to WebP
**Learning:** In this documentation-centric repository, large PNG assets (up to 1.3MB each) were significantly bloating the repository and README load times. Converting to WebP with quality=80 resulted in an ~85% reduction in size.
**Action:** Always check the `assets/` directory in documentation-heavy repos for large images. WebP is a safe and highly effective optimization for these environments.
**Impact:** Total asset size reduced from 4.9MB to 0.7MB (~85% reduction).
