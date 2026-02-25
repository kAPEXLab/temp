# Temporary Directory (`tmp/`)

This folder is used for transient files generated during development, CI pipelines,
or local testing. **Do not commit any generated data here** – it should be ignored
by Git.

Typical contents:
- `tmp/cache/` – cache files created by scripts.
- `tmp/logs/` – short‑lived log files.
- `tmp/artifacts/` – intermediate build artefacts.

The folder is kept in the repository so that its path is always available.
