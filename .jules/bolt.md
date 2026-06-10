## 2025-06-10 - CI efficiency in minimal repositories
**Learning:** In repositories lacking application source code (e.g., just README and workflows), GitHub Actions workflows are the primary area for measurable resource optimization. Standard efficiency guards like concurrency limits and path filtering are often missing in these templates.
**Action:** Always check `.github/workflows` for missing `concurrency`, `paths-ignore`, and `timeout-minutes` when working in minimal repository architectures.
