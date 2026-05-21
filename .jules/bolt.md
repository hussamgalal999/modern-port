## 2025-05-21 - CI Efficiency in Minimal Repos
**Learning:** In repositories with no application source code (only config/docs), GitHub Actions workflows are the primary area for performance/efficiency gains.
**Action:** Always check for `concurrency`, `timeout-minutes`, and `paths-ignore` in workflows when profiling minimal projects.
