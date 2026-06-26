## 2025-06-26 - [Image Asset Optimization]
**Learning:** Converting PNG assets to WebP with 80% quality using Pillow resulted in a significant ~85% size reduction (from 4.9MB to 720KB) with negligible visual impact for documentation.
**Action:** Always prefer WebP for repository image assets to improve README load times and reduce clone size.

## 2025-06-26 - [Grep Regex Compatibility]
**Learning:** The `grep` version in this environment may return "Invalid regular expression" for some standard ERE patterns like `grep -nE '<img|!\['`.
**Action:** Use multiple simple `grep` calls or carefully escape special characters when searching for multiple patterns.
