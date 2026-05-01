## 2026-05-01 - [CI Efficiency Optimization]
**Learning:** In repositories consisting primarily of configuration and documentation, GitHub Actions workflows often lack efficiency guards like concurrency limits or path filtering, making them the primary target for measurable resource optimization.
**Action:** Always check for missing 'concurrency', 'paths-ignore', and 'timeout-minutes' in GitHub Actions workflows to prevent wasting CI resources.
