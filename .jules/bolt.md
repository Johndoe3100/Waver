## 2025-06-28 - [Pillow Import Surprise]
**Learning:** In this environment, after installing Pillow via pip, `import PIL` might fail with ModuleNotFoundError even if `from PIL import Image` succeeds immediately after.
**Action:** Use `from PIL import Image` to verify installation and perform image operations instead of a top-level `import PIL`.
