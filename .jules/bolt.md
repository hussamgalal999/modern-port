## 2024-06-12 - CI Efficiency as Performance Lever
**Learning:** In minimal repositories that lack application source code (e.g., just README and workflows), GitHub Actions workflows are the primary area where performance/resource optimizations can be achieved. Standard guards like concurrency and path filtering are often overlooked.
**Action:** Always check `.github/workflows` for missing efficiency guards when no other obvious bottlenecks exist.
