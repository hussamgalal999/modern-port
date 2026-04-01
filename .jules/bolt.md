## 2025-04-01 - [CI Optimization for GitHub Actions]
**Learning:** GitHub Actions for documentation generation can be redundant if triggered on non-code changes. Using `paths-ignore` and `concurrency` ensures efficiency.
**Action:** Always include `paths-ignore` for non-functional files and `concurrency` for branch-specific runs.
