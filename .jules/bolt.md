## 2026-04-29 - CI Workflow Resource Optimization
**Learning:** In minimal repositories lacking application code, GitHub Actions workflows are often the primary source of resource consumption. Implementing concurrency controls, path filtering, and timeouts can significantly reduce unnecessary compute usage.
**Action:** Always check for missing `concurrency`, `paths-ignore`, and `timeout-minutes` in GitHub Actions workflows as a high-impact, low-risk performance win for small repos.
