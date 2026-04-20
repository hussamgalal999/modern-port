## 2025-05-14 - Optimize CI workflow efficiency
**Learning:** In repositories with minimal executable code, CI workflows often represent the largest source of resource consumption. Optimizing these via concurrency control and path-based triggers significantly reduces redundant execution and saves compute minutes.
**Action:** Always implement `concurrency` with `cancel-in-progress: true` and `paths-ignore` for non-code files (README, workflows, metadata) in GitHub Actions to ensure maximum efficiency.
