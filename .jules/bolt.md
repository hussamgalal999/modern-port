## 2025-04-04 - CI Efficiency in Minimal Repositories
**Learning:** In repositories without application code, GitHub Actions workflows are the primary area for performance gains. Implementing `paths-ignore` and `concurrency` controls prevents redundant runs and saves CI minutes.
**Action:** Always check for `paths-ignore` and `concurrency` in `.github/workflows/*.yml` to optimize resource usage.
