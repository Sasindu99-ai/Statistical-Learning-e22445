# Statistical Learning (e22445)

This repository contains coursework for **ME2050 - Statistical Learning**, focused on probability modeling and related computational exercises in Jupyter notebooks.

## Repository structure

```text
Assignments/
  Assignment 1/
    fundamentals_of_probability_assignment.ipynb
    e22445_fundamentals_of_probability_assignment.ipynb
```

- **Assignments/**: assignment notebooks (original + student version).

## Requirements

- Python **3.11+**
- Jupyter-compatible environment (Jupyter Notebook or VS Code notebooks)

Core dependencies are managed in `pyproject.toml`:
- `numpy`
- `matplotlib`
- `ipykernel`

## Setup

### Option 1: Using `uv` (recommended)

```bash
uv sync
```

### Option 2: Using `pip`

```bash
python -m venv .venv
.venv\Scripts\activate
pip install numpy matplotlib ipykernel
```

## How to run

1. Activate your environment.
2. Start Jupyter:

```bash
jupyter notebook
```

3. Open notebooks from `Assignments\Assignment 1`.

## Notes

- Notebooks include links to Google Colab sources from the course materials.
