## 2025-07-15 - Asset Optimization with WebP
**Learning:** Converting unoptimized PNG assets to WebP (quality 80) in this repository resulted in an ~85% size reduction (4.9MB to 724KB). Additionally, adding `loading="lazy"` to images below the fold is a low-effort, high-impact win for documentation-heavy projects.
**Action:** Always check `assets/` for unoptimized formats and consider `loading="lazy"` for any HTML-based image tags in documentation.

## 2025-07-15 - Shell Verification Gotcha
**Learning:** Using `grep -c` in an `&&` chain to verify the absence of a string (expecting 0) will cause the chain to fail because `grep` returns exit code 1 when no matches are found.
**Action:** Use separate commands or `;` instead of `&&` when verifying zero occurrences with `grep -c`.
