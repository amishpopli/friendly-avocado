# Friendly Avocado Project

This is submission for the take home project

---

## Prerequisites

- Python 3.13 or higher
- uv installed  
  You can install `uv` with:

```bash
brew install uv
```

## Setup

1. Clone the repository:

```bash
git clone <repo-url>
cd friendly-avocado
```

2. Sync dependencies and create the virtual environment:
```bash
uv sync
```


This will:

Create a virtual environment in .venv and Install all dependencies listed in pyproject.toml


3. To launch Jupyter Lab inside the uv environment:
```bash
uv run --with jupyter jupyter lab
```
This ensures Jupyter uses the environment with all dependencies installed.

<b>Open the notebook Full analysis.ipynb from Jupyter Lab to start exploring the project. </b>

Files Overview

- Full analysis.ipynb – Main Jupyter notebook with analysis

- Bot-hunter project report.pdf – Project report

- bot-hunter-dataset.tsv – Dataset used in the analysis

- pyproject.toml – Dependency configuration

- uv.lock – Locked versions of dependencies

- requirements.txt – Optional fallback for pip users