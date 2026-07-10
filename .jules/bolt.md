## 2025-05-14 - Asset format optimization for Documentation
**Learning:** In documentation-heavy repositories (like research models), binary assets (PNGs) often dominate the repository size. Converting to WebP (quality 80) achieved an ~85% size reduction (4.9MB -> 720KB) with no perceptible loss in quality for diagrams and results.
**Action:** Always check the 'assets/' directory in documentation-centric repos for unoptimized formats like PNG/JPG and migrate to WebP + lazy loading.
