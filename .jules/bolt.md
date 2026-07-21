# Bolt Journal ⚡

## 2025-02-14 - Media asset format and lazy loading optimization
**Learning:** High-resolution PNG images in a project's README are a significant bottleneck for repository size and initial load speeds (LCP/FCP). Converting these assets to WebP at quality 80 results in an ~85% reduction in total asset size (down from ~4.9MB to ~720KB). In addition, using `loading="lazy"` on all below-the-fold media assets blocks off-screen image requests on initial render, further optimizing critical path rendering performance.
**Action:** Always identify static image assets in documentation or public pages, convert them to WebP format, clean up the original unoptimized formats, and apply `loading="lazy"` to any below-the-fold elements while leaving the above-the-fold logo un-lazyloaded.
