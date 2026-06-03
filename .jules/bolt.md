## 2025-05-22 - CI Guard Optimization in Minimal Repositories
**Learning:** In repositories with minimal code (e.g., only documentation or configuration), the primary performance bottlenecks are often in the CI/CD pipelines. Missing guards like `paths-ignore`, `concurrency`, and `timeout-minutes` lead to significant waste of CI resources.
**Action:** Always check GitHub Actions for missing efficiency guards when application source code is absent or minimal.
