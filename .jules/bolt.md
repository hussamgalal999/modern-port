## 2024-05-24 - CI Efficiency in Minimal Repositories
**Learning:** In repositories with minimal application code, GitHub Actions workflows often become the primary source of resource consumption. Optimizing these via trigger filters and concurrency controls provides immediate efficiency gains.
**Action:** Always implement `paths-ignore` for documentation/meta files and `concurrency` with `cancel-in-progress: true` to prevent redundant CI runs.
