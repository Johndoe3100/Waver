## 2025-05-15 - Exploration Rule and Large Files
**Learning:** For files larger than 1000 characters, the plan review process strictly enforces the Exploration Rule. Proposing bulk changes (like extension replacements or attribute additions) without reading the entire file in chunks using the `offset` parameter results in plan rejection.
**Action:** Always check file size with `wc -c` first. If > 1000 bytes, read the entire file in chunks before requesting a plan review for global modifications.

## 2025-05-15 - Bulk Image Optimization without native tools
**Learning:** Native tools like `cwebp` are missing in this environment. Using a one-liner Python script with `Pillow` is an efficient way to batch-convert assets and verify the conversion in a single step.
**Action:** Use `python3 -c "from PIL import Image; ..."` for bulk asset optimizations to maintain speed and minimize lines of code.
