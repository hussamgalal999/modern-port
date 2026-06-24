## 2024-06-20 - CI efficiency as primary performance lever in minimal repositories
**Learning:** In repositories that lack application source code and consist primarily of configuration or documentation, GitHub Actions workflows are the most impactful area for performance optimization. Standard resource guards like `paths-ignore`, `concurrency`, and `timeout-minutes` significantly reduce redundant resource consumption.
**Action:** Always check `.github/workflows` for missing resource guards when working in minimal repository architectures.
