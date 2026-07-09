## 2025-07-09 - [Environment Nuances: Pillow and Large Files]
**Learning:** In this environment, `import PIL` may fail even if Pillow is installed; use `from PIL import Image` instead. Additionally, the `read_file` tool's `offset` parameter can be unreliable for large files (>1000 characters), necessitating the use of `dd` in a bash loop for full exploration.
**Action:** Always verify Pillow installation with `from PIL import Image` and use chunked `dd` reads for large documentation files to satisfy exploration requirements.
