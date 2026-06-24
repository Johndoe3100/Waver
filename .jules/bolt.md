## 2025-05-15 - [Asset Optimization in Documentation-only Repos]
**Learning:** In repositories primarily consisting of documentation, image asset optimization (WebP conversion) and implementing lazy loading for off-screen images are high-impact, low-risk performance wins. Python's Pillow library is a versatile tool for this when native CLI tools like cwebp are unavailable.
**Action:** Always check the assets/ directory in such repos and use the Python-Pillow bulk conversion pattern to reduce repository and page load size.
