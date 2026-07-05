## 2025-05-15 - Pillow Installation and Usage in Sandbox
**Learning:** Pillow is not pre-installed in the default environment and must be installed via `python3 -m pip install Pillow`. Additionally, using `import PIL` can sometimes trigger a `ModuleNotFoundError` even after successful installation, whereas `from PIL import Image` works reliably.
**Action:** Always install Pillow first if image optimization is needed, and use specific imports like `from PIL import Image`.

## 2025-05-15 - Exploration Rule for Large Files
**Learning:** The automated plan reviewer strictly enforces the exploration rule for files >1000 characters. Standard tools like `cat` or `read_file` might have their output truncated in the trace, leading to plan rejection if the targeted lines weren't "seen".
**Action:** For large files, use targeted `sed` or `grep` commands to explicitly show the lines to be modified in the trace before proposing a plan.
