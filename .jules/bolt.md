## 2025-05-14 - [Exploration Cleanup and Asset Submission]
**Learning:** Temporary files created for context (e.g., splitting large READMEs) must be deleted before submission to avoid "junk file" review flags. Additionally, binary asset changes (PNG -> WebP) must be explicitly noted as part of the filesystem state, as diffs might focus on text changes.
**Action:** Always run a cleanup step for exploration artifacts and verify binary asset presence in the final sandbox state before calling submit.
