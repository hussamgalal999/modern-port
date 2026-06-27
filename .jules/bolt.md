## 2025-05-18 - CI Efficiency as Primary Lever
**Learning:** In minimal repositories with no application source code, GitHub Actions workflows are the primary area for measurable performance and resource optimization. Standard guards like `paths-ignore`, `concurrency`, and `timeout-minutes` significantly reduce redundant CI usage.
**Action:** Always check `.github/workflows` for missing efficiency guards when working in minimal repository architectures.
