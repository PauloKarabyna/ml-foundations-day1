# ML Foundations — Day 1 Starter

This repository scaffolds **Month 1 / Day 1** of your Core ML & Data Foundations plan.

## What you’ll do today
- Set up a clean Python environment (virtualenv)
- Practice linear algebra with NumPy: vectors, dot product, norm, angle, projection
- Practice matrix ops: identity, inverse, determinant, matrix–vector, matrix–matrix
- Plot 2D vectors and a simple linear transformation with Matplotlib
- Save figures to `figures/`
- Write a short reflection in the notebook
- Commit your work with Git

## How to run
1. Open a terminal (or PowerShell on Windows) and navigate to this folder.
2. Create & activate a virtual environment, then install dependencies:
   - macOS/Linux:
     ```bash
     python3 -m venv .venv
     source .venv/bin/activate
     pip install --upgrade pip
     pip install -r requirements.txt
     ```
   - Windows (PowerShell):
     ```powershell
     py -3 -m venv .venv
     . .venv\Scripts\Activate.ps1
     python -m pip install --upgrade pip
     pip install -r requirements.txt
     ```

3. Start Jupyter and open the Day 1 notebook:
   ```bash
   jupyter notebook notebooks/01_linear_algebra_basics.ipynb
   ```

Figures you create will be saved into `figures/`.
