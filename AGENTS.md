# AGENTS.md

- Greenfield repo: only `README.md` placeholder, MIT `LICENSE`, stock Python `.gitignore`. No source, manifests, lockfiles, tests, lint/typecheck config, CI, or `opencode.json`.
- 所有的回應都使用繁體中文。
- 專案語言為 Python，使用 conda 管理套件，環境名稱為 `iem_python`（例如：`conda run -n iem_python python ...`）。
- No verified build / test / lint commands. Do not assume `pytest`, `tox`, `uv`, or `pip` — check what gets committed first.
- `.gitignore` covers standard Python artifacts (`__pycache__/`, `.venv/`, `dist/`, `.pytest_cache/`, etc.).
- When a stack is introduced, record its exact commands and entrypoints here. Trust executable config over prose.
