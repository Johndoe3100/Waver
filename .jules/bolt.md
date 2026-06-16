## 2025-06-16 - [Documentation Optimization: sed vs. Precision Editing]
**Learning:** Using `sed` to add attributes to HTML tags in README files can be risky, especially with self-closing tags (e.g., `/>`). A naive regex can place the new attribute after the closing slash, potentially breaking the HTML.
**Action:** Prefer using `replace_with_git_merge_diff` for precise HTML tag modifications to ensure valid syntax, or use more robust regex patterns that account for trailing slashes.
