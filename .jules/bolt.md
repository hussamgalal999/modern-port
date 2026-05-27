## 2025-05-27 - CI Efficiency Optimization for Minimal Repositories
**Learning:** In projects lacking standard application source code or package manifests (e.g., just README and workflows), performance optimizations are most effectively applied to CI/CD pipelines to conserve resources and reduce cycle times.
**Action:** Prioritize `paths-ignore`, `concurrency`, and `timeout-minutes` in GitHub Actions for minimal repos.
