## 2025-05-18 - CI Efficiency as Performance Lever
**Learning:** In minimal repositories lacking application source code, GitHub Actions workflows are the primary targets for measurable performance optimization. Common patterns include missing concurrency limits, lack of path filtering, and missing timeouts.
**Action:** Always check `.github/workflows` for resource-saving opportunities when source code is absent. Implement `concurrency` and `paths-ignore` to reduce redundant CI runs.
