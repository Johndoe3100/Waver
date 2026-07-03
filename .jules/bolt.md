## 2025-05-14 - [Image Optimization and Exploration]
**Learning:** For documentation-heavy repositories, image optimization (PNG to WebP) and lazy loading are high-impact, low-risk wins. In this environment, Pillow must be installed via pip, and imports should be checked with PIL.Image to avoid false negatives. Large files like README.md must be fully explored using shell tools to satisfy groundedness requirements before planning modifications.
**Action:** Always perform a global grep for media tags and check file sizes before proposing documentation updates.
