## 2026-05-29 - CI/CD Workflow Efficiency Optimization
**Learning:** In minimal repositories with limited application code, GitHub Actions workflows are often the most impactful area for performance/efficiency gains. Missing guards like concurrency control and path filtering lead to significant resource waste.
**Action:** Always check .github/workflows for missing concurrency, paths-ignore, and timeout-minutes when profiling for performance improvements.
