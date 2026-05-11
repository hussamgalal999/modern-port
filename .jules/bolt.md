## 2026-05-11 - CI Workflow Optimization in Minimal Repo
**Learning:** In repositories lacking application source code, GitHub Actions workflows are the primary target for performance gains. Standard guards like `paths-ignore`, `concurrency`, and `timeout-minutes` provide measurable efficiency boosts by reducing redundant CI minutes.
**Action:** Always check `.github/workflows` for missing resource management configurations in minimal or documentation-heavy repositories.
