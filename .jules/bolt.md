# Bolt Journal

## 2025-07-21 - WebP Asset Optimization
**Learning:** Converting unoptimized high-resolution PNG assets in a codebase's documentation to WebP with a reasonable quality factor (e.g., 80) drastically reduces page load latency and repository size without sacrificing visual fidelity. Adding `loading="lazy"` to images below the fold further accelerates the first contentful paint (FCP) and largest contentful paint (LCP).
**Action:** Identify static PNG images, convert them using a Python script with Pillow, update documentation references, and delete legacy binary PNGs to prevent repo bloat.
