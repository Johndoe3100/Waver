## 2025-06-03 - Optimized image assets for README
**Learning:** High-resolution PNG images in the assets directory significantly increased the initial load size of the README (approx 4.9MB). Converting these to WebP format with quality=80 provides a massive reduction in file size (approx 85%) with minimal visual quality loss.
**Action:** Always prefer WebP for documentation assets to ensure fast README load times, especially for repositories with many screenshots or diagrams.
