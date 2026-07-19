# Bolt Journal

## 2025-07-19 - [Document Asset Delivery Optimization]
**Learning:** Raw heavy PNG images in documentation repos can significantly slow down page load and consume unnecessary user bandwidth. Converting these assets to high-efficiency WebP format at quality 80 maintains visual clarity while achieving up to ~85% reduction in asset size. Additionally, applying `loading="lazy"` to images below the fold prevents blocking the initial page rendering paths, while avoiding it on the logo ensures optimal Largest Contentful Paint (LCP) above the fold.
**Action:** When handling documentation-heavy repositories, audit all visual assets (.png, .jpg) and convert them to modern formats like WebP, update documentation references, and introduce lazy loading tags systematically to optimize load speed and bandwidth usage.
