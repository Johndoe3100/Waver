## 2025-05-13 - [Exploration Rule & `read_file` Offset]
**Learning:** In this environment, the `offset` parameter in `read_file` might not behave as expected for large files, potentially returning the same initial chunk repeatedly. This can lead to "Exploration Rule" violations during plan review.
**Action:** Use `run_in_bash_session` with `cat`, `grep -n`, or `dd` to reliably read specific parts or identify structures in large files when `read_file` chunks appear redundant.

## 2025-05-13 - [Image Optimization Workflow]
**Learning:** Converting PNGs to WebP (quality 80) in this repository reduced asset size by ~85% (from 4.9MB to 0.7MB) with no visible impact on documentation quality.
**Action:** Prioritize WebP conversion for all documentation-heavy repositories to improve load times and reduce bandwidth usage.
