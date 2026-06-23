## 2024-06-20 - CI efficiency as a primary performance lever in minimal repositories

**Learning:** In repositories that consist primarily of configuration and documentation (lacking application source code), GitHub Actions workflows are the most impactful area for performance and resource optimization. Standard guards like `concurrency`, `paths-ignore`, and `timeout-minutes` significantly reduce wasted compute time.

**Action:** Always check `.github/workflows` for missing efficiency guards when working in minimal or infrastructure-heavy repositories.
