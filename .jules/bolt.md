## 2026-07-06 - CI efficiency as primary performance lever in minimal repositories

**Learning:** In repositories that lack application source code or a `package.json`, standard application performance optimizations (like memoization or database indexing) are not applicable. GitHub Actions workflows become the primary target for measurable efficiency improvements.

**Action:** When encountering minimal repositories, profile the CI/CD pipelines first. Look for missing concurrency controls, lack of path filtering, and missing timeouts to optimize resource usage.
