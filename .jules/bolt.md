## 2026-05-24 - CI Workflow Efficiency Anti-pattern
**Learning:** GitHub Actions workflows without path filtering, concurrency limits, or timeouts lead to significant resource waste. In this repository, the documentation workflow was triggering on every push to main, even for changes to the README or the workflow itself, which is redundant for an AI documentation generator.
**Action:** Always implement `paths-ignore` for non-source files, `concurrency` with `cancel-in-progress: true`, and explicit `timeout-minutes` for all workflows to maximize CI efficiency.
