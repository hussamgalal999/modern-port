## 2026-07-06 - CI Efficiency as Primary Performance Lever
**Learning:** In minimal repositories lacking application source code, GitHub Actions workflows often lack efficiency guards like concurrency limits or path filtering. This makes them the primary target for measurable performance/resource optimization.
**Action:** Always check `.github/workflows` for missing `paths-ignore`, `concurrency`, and `timeout-minutes` when working in a skeleton or configuration-only repository.
