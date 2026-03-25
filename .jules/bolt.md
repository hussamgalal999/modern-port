## 2026-03-24 - [GitHub Actions CI Optimization]
**Learning:** In repositories with minimal code or automated tasks, CI resources are frequently wasted on non-essential changes. Implementing `paths-ignore` and `concurrency` groups is a highly effective way to reduce CI overhead and prevent redundant processing.
**Action:** Always verify if a GitHub Action workflow needs to run on every push. Use `paths-ignore` for documentation and configuration files that don't affect the workflow's output, and use `concurrency` to cancel in-progress runs on new pushes.
