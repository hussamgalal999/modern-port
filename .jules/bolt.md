## 2025-03-28 - [CI Optimization for Minimal Repository]
**Learning:** In repositories without application code or `package.json`, performance wins are found in CI/CD pipeline efficiency (GitHub Actions) by reducing redundant runs and resource usage.
**Action:** Use `paths-ignore`, `concurrency`, and `timeout-minutes` to optimize GitHub Actions workflows when no source code is available for application-level performance tuning.
