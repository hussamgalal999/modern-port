## 2025-05-18 - CI Efficiency as Primary Lever in Minimal Repositories
**Learning:** In repositories like this one, which lack application source code and standard performance targets (frontend/backend), GitHub Actions workflows are the primary area for measurable performance and resource optimization. Missing efficiency guards like concurrency limits and path filtering lead to significant resource waste.
**Action:** Always audit GitHub Actions for missing `paths-ignore`, `concurrency`, and `timeout-minutes` when working in minimal or configuration-heavy repositories.
