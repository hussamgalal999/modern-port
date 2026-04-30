## 2025-05-22 - CI Efficiency in Minimal Repositories
**Learning:** In repositories consisting primarily of configuration and documentation (like this one), GitHub Actions workflows are the primary source of resource consumption. Standard optimizations like `concurrency` and `paths-ignore` significantly reduce CI/CD overhead and prevent redundant processing of non-code changes.
**Action:** Always check `.github/workflows` for missing efficiency guards (concurrency, path filtering, timeouts) when working in minimal or configuration-heavy repositories.
