## 2025-05-15 - [Efficient Image Optimization in documentation-only repos]
**Learning:** In repositories primarily focused on documentation, asset optimization (PNG to WebP) and lazy loading are the most impactful performance wins. Pillow is the reliable tool for this in the current environment but must be installed and verified via `python3 -c "from PIL import Image..."`.
**Action:** Always check asset sizes with `du` first, use Pillow for conversion with quality=80, and update documentation using `replace_with_git_merge_diff` for precision with HTML tags.

## 2025-05-15 - [Large File Read Constraints]
**Learning:** The automated plan reviewer may flag large file modifications as unread even if standard tools are used.
**Action:** Use chunked reading with `dd` or `read_file` with offsets before proposing plans that modify files >1000 characters.
