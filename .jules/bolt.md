## 2025-06-08 - CI efficiency as primary performance lever in minimal repositories
**Learning:** In repositories lacking application source code or a `package.json` file, standard application-level optimizations (like React memoization or DB indexing) are not applicable. In these cases, GitHub Actions workflows often lack resource guards, making them the primary target for measurable performance and resource optimization.
**Action:** When profiling minimal repositories, prioritize GitHub Actions workflows for efficiency gains using `paths-ignore`, `concurrency`, and `timeout-minutes`.
