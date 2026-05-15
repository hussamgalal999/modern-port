## 2025-05-15 - CI Optimization in Minimal Repositories
**Learning:** In repositories that lack application source code (e.g., just README and workflows), performance optimizations should target CI/CD resource usage. Using `paths-ignore`, `concurrency`, and `timeout-minutes` provides measurable efficiency gains by reducing redundant runs and preventing resource leakage.
**Action:** Always check `.github/workflows` for missing efficiency guards when no application code is present for traditional optimization.
