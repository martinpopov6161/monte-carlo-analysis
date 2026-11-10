# Monte Carlo Analysis

A step-by-step project to estimate π with a Monte Carlo experiment and study how repeated estimates vary.

## Project structure

- `notebooks/monte_carlo_analysis.ipynb` — analysis notebook
- `src/simulation.py` — simulation functions
- `src/metrics.py` — summary metrics
- `src/visualization.py` — plots

## Setup

Use Python 3.10 or newer. From this folder, create and activate a virtual environment, then install the dependencies:

```bash
python -m venv .venv
```

Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
```

macOS/Linux:

```bash
source .venv/bin/activate
python -m pip install -r requirements.txt
```

## Open and run

Open the `monte-carlo-analysis` folder in VS Code. Install the Python and Jupyter extensions if prompted, choose the project environment as the notebook kernel, and open `notebooks/monte_carlo_analysis.ipynb`. Run cells from top to bottom. The notebook currently contains project notes and a placeholder; the experiment will be implemented step by step.

Alternatively, start Jupyter from the activated environment:

```bash
jupyter lab
```
