# Bolt's Performance Journal

## 2025-05-15 - [CI Optimization for Minimal Repositories]
**Learning:** In repositories containing only documentation or configuration files, GitHub Actions often lack efficiency guards like concurrency limits or path filtering.
**Action:** Always check `.github/workflows` for opportunities to add `concurrency` and `paths-ignore` when application source code is missing.
