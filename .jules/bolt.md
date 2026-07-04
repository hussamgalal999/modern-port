## 2025-05-18 - CI Efficiency in Minimal Repositories
**Learning:** In repositories lacking application source code, GitHub Actions workflows are the primary area for measurable performance optimization. Common omissions include concurrency limits and path filtering.
**Action:** Always check `.github/workflows` for missing `concurrency` and `paths-ignore` guards when profiling minimal repositories.
