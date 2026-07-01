## 2026-07-01 - CI Efficiency in Minimal Repositories
**Learning:** In repositories lacking application source code (e.g., just README and CI configs), the primary lever for measurable performance/resource optimization is the CI/CD pipeline itself.
**Action:** Always check for missing concurrency limits, path filtering, and job timeouts in GitHub Actions workflows to optimize resource usage.
