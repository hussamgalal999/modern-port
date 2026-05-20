# Bolt's Performance Journal

## 2025-05-20 - CI Efficiency Optimization
**Learning:** In repositories with minimal or no application code, GitHub Actions workflows are the primary area for performance/efficiency gains. Standard optimizations like `paths-ignore`, `concurrency` (with `cancel-in-progress: true`), and `timeout-minutes` significantly reduce wasted CI resources and speed up the feedback loop.
**Action:** Always check workflows for missing concurrency controls and path filters when profiling minimal repositories.
