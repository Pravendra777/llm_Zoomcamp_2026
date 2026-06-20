# llm_Zoomcamp_2026

A concise repository for the LLM Zoomcamp 2026 homework and exercises.

This repo contains a short project and a Jupyter notebook used for the Week 1 Zoomcamp exercises. It includes example code and a small runnable entrypoint.

**Contents**
- `homework_week1.ipynb` — Jupyter notebook with exercises, notes, and results.
- `main.py` — Small script / entrypoint used in demonstrations.
- `pyproject.toml` — Project metadata and build config.

**Quickstart**

Requirements: Python 3.10+ (or the version declared in `pyproject.toml`). Recommended: use a virtual environment.

1. Create and activate a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate
```

2. Install the project (uses `pyproject.toml`):

```bash
pip install -e .
```

If the project has additional dependencies listed elsewhere, install them via `pip install -r requirements.txt` if present.

**Run the example script**

```bash
python main.py
```

This runs the small demo or entrypoint included in the repository. Check `main.py` for options or configuration.

**Open the notebook**

To view and run the notebook interactively:

```bash
jupyter lab homework_week1.ipynb
# or
jupyter notebook homework_week1.ipynb
```

**Project structure**

- [homework_week1.ipynb](homework_week1.ipynb) — Notebook with the Week 1 exercises.
- [main.py](main.py) — Example script to run the project's demo.
- [pyproject.toml](pyproject.toml) — Project config.

**Development**

- Use the virtual environment for iterative development.
- Run the notebook cells to reproduce experiments and visualizations.
- If you add dependencies, update `pyproject.toml` (or `requirements.txt`) and document them here.

**Contributing**

Contributions are welcome. For small edits, open a PR against `main`. Describe changes briefly in the PR description and include a short test or reproduction where applicable.

**License & Contact**

Specify license information here if you want to open-source this repo (e.g., MIT). For questions, open an issue or contact the repository owner.

---

If you'd like, I can also:
- add a `requirements.txt` generated from the environment,
- add a short CLI usage section for `main.py`, or
- expand the notebook README with exercise answers and expected outputs.

Tell me which you'd prefer and I'll implement it.
