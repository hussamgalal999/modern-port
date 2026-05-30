## 2025-05-30 - GitHub Action Efficiency
**Learning:** In minimal repositories with little to no application code, GitHub Actions are often unoptimized. Missing `paths-ignore`, `concurrency`, and `timeout-minutes` leads to unnecessary resource consumption and potential hung jobs.
**Action:** Always audit CI workflows for these basic efficiency guards in minimal repos.
