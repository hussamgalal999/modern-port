## 2024-06-09 - CI efficiency as primary optimization
**Learning:** In minimal repositories with no application source code, GitHub Actions workflows often lack efficiency guards (concurrency, path filtering, timeouts), making them the primary target for measurable performance/resource optimization.
**Action:** Always check `.github/workflows` for missing `concurrency` and `paths-ignore` when profiling minimal repos.
