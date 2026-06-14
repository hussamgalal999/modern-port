## 2025-06-14 - CI efficiency as primary performance lever
**Learning:** In minimal repositories consisting primarily of configuration and documentation (like this one), GitHub Actions workflows often lack efficiency guards like concurrency limits or path filtering. This makes them the primary target for measurable performance/resource optimization when no application source code is present.
**Action:** Always check `.github/workflows` for missing `concurrency`, `paths-ignore`, and `timeout-minutes` when working on minimal or configuration-heavy repositories.
