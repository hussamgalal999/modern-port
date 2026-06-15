## 2026-06-15 - CI Efficiency as Primary Lever
**Learning:** In minimal repositories that lack executable application source code, GitHub Actions workflows are often the only area where measurable performance/resource optimization can be achieved. Standard efficiency guards like concurrency limits and path filtering are frequently overlooked in these projects.
**Action:** Always inspect `.github/workflows` early when dealing with minimal or documentation-heavy repositories to identify resource-saving opportunities.
