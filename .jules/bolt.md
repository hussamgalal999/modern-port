## 2024-06-25 - [CI Efficiency as Primary Lever]
**Learning:** In minimal repositories with no application code, GitHub Actions workflows are the primary target for measurable performance optimization. Common missing guards include path filtering, concurrency limits, and job timeouts.
**Action:** Always check `.github/workflows` for missing `paths-ignore`, `concurrency`, and `timeout-minutes` when working in infrastructure-heavy or minimal repos.
