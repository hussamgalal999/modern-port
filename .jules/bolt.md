## 2026-05-09 - CI Workflow Efficiency Guard
**Learning:** In minimal repositories with no executable code, GitHub Actions workflows are the primary source of resource consumption. Implementing concurrency control, path filtering, and timeouts provides measurable efficiency gains.
**Action:** Always check for missing 'concurrency', 'paths-ignore', and 'timeout-minutes' in existing workflows.
