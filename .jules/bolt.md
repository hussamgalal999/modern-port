## 2025-06-13 - CI efficiency as the primary performance lever
**Learning:** In minimal repositories lacking application source code, GitHub Actions workflows often lack efficiency guards like concurrency limits or path filtering. These become the primary targets for measurable performance/resource optimization.
**Action:** Always check GitHub Actions workflows for missing `concurrency`, `paths-ignore`, and `timeout-minutes` when dealing with minimal or configuration-heavy repositories.
