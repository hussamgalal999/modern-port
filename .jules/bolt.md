## 2025-05-18 - CI Efficiency as the Primary Performance Lever
**Learning:** In minimal repositories lacking application source code, GitHub Actions workflows are often the primary (and sometimes only) area for measurable performance optimization. These workflows frequently lack standard efficiency guards like concurrency limits or path filtering.
**Action:** Always inspect `.github/workflows` early in such repositories and implement `concurrency` groups and `paths-ignore` to save CI resources and reduce feedback loops.
