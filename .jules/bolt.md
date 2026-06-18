## 2024-06-18 - CI Efficiency in Minimal Repositories
**Learning:** In repositories without application source code, GitHub Actions workflows are the primary source of resource consumption. Without guards like `paths-ignore` and `concurrency`, these workflows can run redundantly on every metadata change.
**Action:** Always implement path filtering and concurrency controls in CI workflows for minimal or documentation-only repositories to maximize resource efficiency.
