## 2025-04-21 - CI Efficiency in Minimal Repositories
**Learning:** In repositories consisting primarily of configuration and documentation, GitHub Actions workflows often lack standard efficiency guards like concurrency limits or path filtering, leading to wasted CI minutes.
**Action:** Always check `.github/workflows` for missing `concurrency` and `paths-ignore` when working in minimal or documentation-heavy repositories.
