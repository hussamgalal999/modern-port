## 2025-05-18 - CI Efficiency as Primary Performance Lever
**Learning:** In minimal repositories lacking application source code, GitHub Actions workflows are the primary source of measurable performance/resource optimization. These often lack concurrency limits or path filtering.
**Action:** Prioritize adding `concurrency`, `paths-ignore`, and `timeout-minutes` to CI workflows to optimize feedback speed and resource usage.
