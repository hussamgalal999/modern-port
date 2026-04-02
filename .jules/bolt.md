## 2025-04-02 - Optimizing CI for Minimal Repositories
**Learning:** In repositories with very little code (like this one), the most significant performance gains are often in CI/CD pipelines by preventing redundant runs and setting resource limits.
**Action:** Always check GitHub Actions for `paths-ignore`, `concurrency`, and `timeout-minutes` when an application codebase is minimal or missing.
