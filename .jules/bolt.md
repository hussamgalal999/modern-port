## 2025-05-25 - CI Efficiency Optimization
**Learning:** In minimal repositories where typical application code is missing, GitHub Actions workflows are the primary area for performance gains through resource management.
**Action:** Always check for `concurrency`, `paths-ignore`, and `timeout-minutes` in workflows to prevent redundant or runaway CI runs.
