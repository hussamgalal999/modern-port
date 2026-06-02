## 2025-06-02 - CI efficiency in minimal repositories
**Learning:** In repositories with no application code, GitHub Action workflows are the primary targets for optimization. Without guards like concurrency and path filtering, CI resources are wasted on redundant or irrelevant runs.
**Action:** Always implement concurrency control and path filtering for workflows that don't need to run on every single change (e.g., documentation generators).
