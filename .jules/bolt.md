## 2025-05-17 - CI Efficiency as Primary Optimization Target
**Learning:** In minimal repositories lacking application source code, GitHub Actions workflows are the primary area for performance and resource optimization. Standard guards like `paths-ignore`, `concurrency`, and `timeout-minutes` provide measurable efficiency gains by reducing redundant CI execution and preventing resource leakage.
**Action:** Always check `.github/workflows` for missing efficiency guards when no application code is present for traditional optimization.
