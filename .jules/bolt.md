## 2026-04-10 - CI Efficiency Optimization
**Learning:** In a repository with minimal source code, optimizing GitHub Actions is the most impactful performance win. Using `paths-ignore` prevents unnecessary documentation generation runs, while `concurrency` ensures that only the latest commit is processed, saving CI minutes and developer time.
**Action:** Always check for `paths-ignore` and `concurrency` in workflows, especially for documentation or linting tasks that don't need to run on every file change.
