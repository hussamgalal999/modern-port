## 2025-06-07 - CI Efficiency in Minimal Repositories
**Learning:** In repositories lacking application source code or complex build systems, GitHub Actions workflows are the primary source of resource consumption. Without guards like `concurrency` or `paths-ignore`, these workflows run unnecessarily, wasting runner minutes.
**Action:** Always check for missing concurrency controls, path filtering (especially for README and CI configs), and job timeouts in GitHub Actions workflows to achieve measurable efficiency gains.
