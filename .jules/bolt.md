## 2026-05-31 - CI Guards in Minimal Architectures
**Learning:** In repositories with minimal or no application source code, GitHub Actions workflows often lack fundamental efficiency guards (concurrency limits, path filtering), making them the primary lever for measurable performance/resource optimization.
**Action:** Always audit workflow files for `concurrency` and `paths-ignore` when working in documentation-only or configuration-heavy repositories.
