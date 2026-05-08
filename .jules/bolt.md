## 2025-05-23 - CI Efficiency in Minimal Repositories
**Learning:** In repositories lacking application source code (e.g., just README and workflows), performance optimizations shift from code execution to CI/CD resource management. Implementing `paths-ignore`, `concurrency`, and `timeout-minutes` provides measurable efficiency gains.
**Action:** Always check `.github/workflows` for missing resource guards in minimal projects.

## 2025-05-23 - Environment Tool Limitations
**Learning:** The current execution environment lacks `yamllint` and the Python `yaml` module, making automated YAML validation difficult.
**Action:** Rely on manual inspection and `read_file` for YAML verification in this environment.
