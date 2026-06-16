## 2024-06-16 - CI Efficiency Optimization in Minimal Repositories
**Learning:** In minimal repositories lacking application source code, GitHub Actions workflows often lack efficiency guards like concurrency limits or path filtering. These become the primary target for measurable performance/resource optimization.
**Action:** Always check for `concurrency`, `paths-ignore`, and `timeout-minutes` in GitHub Actions workflows to optimize CI resource usage.
