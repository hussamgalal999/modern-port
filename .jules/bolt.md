## 2025-05-15 - CI Optimization in Minimal Repositories
**Learning:** In repositories lacking application source code, GitHub Actions workflows are the primary area for performance and resource optimization. Missing concurrency controls and path filtering lead to significant CI minute wastage.
**Action:** Always check workflows for `paths-ignore`, `concurrency`, and `timeout-minutes` when dealing with automation-heavy or minimal repositories.
