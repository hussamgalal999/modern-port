## 2025-05-15 - CI Efficiency as Performance
**Learning:** In minimal repositories lacking executable source code, GitHub Actions workflows are the primary area for measurable efficiency gains. Implementing concurrency control and path filtering significantly reduces CI resource wastage.
**Action:** Always check `.github/workflows` for missing `concurrency` and `paths-ignore` when working on minimal projects.
