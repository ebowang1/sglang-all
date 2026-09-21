# Origin / Provenance

This repo is a consolidation of two repositories into a single one.

| Part | Original source | Original commit | Date |
|---|---|---|---|
| SGLang framework (repo root) | https://github.com/Huangxy-Minel/sglang | 1519acf37c23f2189adb93f57ca9cd2db1bebf18 | 2026-04-05 |
| sglang-run/ (launch scripts) | https://github.com/ebowang1/sglang-run | see note below | - |

Notes:
- History was intentionally reset (fresh history). Upstream merge is NOT possible
  via `git merge`; upstream fixes must be applied manually or via cherry-pick.
- Build artifacts, compiled .so files and caches are excluded via .gitignore.
