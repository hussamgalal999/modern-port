## 2026-03-24 - [GitHub Actions CI Optimization]
**Learning:** In projects with minimal code or specialized workflows (like auto-documentation), CI resources are often wasted on non-code changes. Path filters and concurrency groups are highly effective for these "cold" repos.
**Action:** Always check for `paths-ignore` and `concurrency` in GitHub Actions workflows, especially those that perform external API calls or expensive processing.
