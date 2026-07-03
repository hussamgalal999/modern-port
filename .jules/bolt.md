## 2025-05-18 - CI Efficiency as Primary Performance Lever
**Learning:** In minimal repositories lacking application source code, GitHub Actions workflows often lack efficiency guards like concurrency limits or path filtering. This makes them the primary target for measurable performance/resource optimization.
**Action:** Always check for `concurrency`, `paths-ignore`, and `timeout-minutes` in existing workflows to optimize resource usage.
