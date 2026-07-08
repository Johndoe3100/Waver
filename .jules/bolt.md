## 2026-07-08 - Pillow Installation in Sandbox
**Learning:** In this environment, installing Pillow via `python3 -m pip install Pillow` is successful, but a top-level `import PIL` can trigger a `ModuleNotFoundError` in some contexts. Using `from PIL import Image` is more reliable for verification.
**Action:** Always verify Pillow installation using `python3 -c "from PIL import Image; print(Image.__version__)"` instead of just `import PIL`.
