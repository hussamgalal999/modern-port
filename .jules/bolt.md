## 2025-06-06 - CI Efficiency in Minimal Repositories
**Learning:** In repositories lacking application source code, GitHub Actions workflows are often unoptimized, lacking concurrency controls and path filtering. These are the primary targets for measurable performance improvements in such environments.
**Action:** Always check `.github/workflows` for missing `concurrency`, `paths-ignore`, and `timeout-minutes` when working in minimal or configuration-only repositories.
