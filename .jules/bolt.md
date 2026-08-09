## 2025-08-09 - WebP and Lazy Loading Optimization
**Learning:** Converting legacy PNG assets to WebP using Pillow (quality 80) reduces asset sizes by ~85.6% without visible loss in quality, saving valuable bandwidth and repo bloat. Additionally, placing loading="lazy" attributes below the fold protects the Largest Contentful Paint (LCP) score for the main logo image while improving overall loading speed.
**Action:** Always identify below-the-fold visual elements and apply lazy-loading appropriately, and convert any static PNG/JPEG illustrations to modern WebP format for optimal size.
