# retina
Agentic Extraction Pipeline

## Environment and package management

This project uses `uv` with `pyproject.toml`.

### 1) Create and sync the project environment

```bash
uv sync
```

This creates `.venv` and installs both runtime and dev dependencies.

### 2) Run scripts

```bash
uv run python test.py
uv run python test2.py
```

### 3) Add dependencies

```bash
uv add <package>
uv add --dev <package>
```

### 4) Update lockfile after edits

```bash
uv lock
uv sync
```

Commit `uv.lock` so installs stay reproducible across machines.
