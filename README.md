# Monte Carlo Analysis

## Overview

This project explores how to estimate π using random sampling. Imagine a square with sides of length 1 and a quarter circle of radius 1 inside it. For each randomly generated point \((x, y)\), we check whether it falls inside the quarter circle using \(x^2 + y^2 \leq 1\).

The quarter circle covers \(π/4\) of the square’s area. So if \(K\) out of \(N\) points fall inside it, we can estimate π with:

\[
\hat{π} = 4\frac{K}{N}
\]

The main question is how the estimate changes as we use more points. We’ll run the simulation several times at different point counts, compare each estimate with π, and look at how much the results vary between runs. Because the points are random, a larger sample may improve the estimate overall, but it does not guarantee that every run will be closer to π.

## Project structure

- `notebooks/monte_carlo_analysis.ipynb` — project explanation, code, experiments, and results
- `README.md` — project overview and setup instructions
- `requirements.txt` — Python packages used in the project

## Setup

I’m using Python 3.10 or newer for this project. Open a terminal in the project folder and create a virtual environment:

```bash
python -m venv .venv
```

Activate the environment, then install the packages from `requirements.txt`.

**Windows PowerShell**

```powershell
.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
```

**macOS/Linux**

```bash
source .venv/bin/activate
python -m pip install -r requirements.txt
```

## Running the notebook

In VS Code, open the project folder and open `notebooks/monte_carlo_analysis.ipynb`. Select the `.venv` environment as the notebook kernel, then run the cells from top to bottom.

If you prefer JupyterLab, activate the environment and run:

```bash
jupyter lab
```
