## 2025-05-18 - CI Efficiency as Primary Performance Lever
**Learning:** In minimal repositories lacking application source code, GitHub Actions workflows are often the only area where measurable performance/resource optimizations can be made. Standard guards like concurrency and path filtering are frequently missing.
**Action:** Always check `.github/workflows` for missing `concurrency`, `paths-ignore`, and `timeout-minutes` in repositories with no `package.json` or visible source code.
