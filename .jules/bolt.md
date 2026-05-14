## 2024-05-14 - CI Optimization in Minimal Repos
**Learning:** In repositories without application code, GitHub Actions workflows are the primary area for performance (resource efficiency) gains.
**Action:** Always check `.github/workflows` for missing concurrency, path filtering, and timeouts when standard code bottlenecks are absent.
