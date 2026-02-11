# Reinforcement Learning Programming — Assignment 1

**Name:** Albright Maduka

**Student ID:** 9053136

## Overview

This repository contains the Jupyter Notebook solution for Assignment 1 (CSCN 8020). It implements and compares dynamic-programming and Monte Carlo methods on a small 5×5 gridworld, including:

- Value Iteration (synchronous and in-place)
- Policy Evaluation / Improvement example for a 2×2 grid
- Off-policy Monte Carlo control with Weighted Importance Sampling

## Repository structure

- Albright_9053136_Assignment1_CSCN_8020_Reinforcement_Learning_Programming.ipynb — Main notebook containing all problems, code, results, and discussion.
- logs/ — Directory where run logs are written (e.g., `logs/problem3.log`, `logs/problem4.log`).

## Requirements
- numpy

Install the dependency with:

```bash
python -m pip install --upgrade pip
pip install numpy
```

## Running the notebook

1. Open the notebook interactively with Jupyter Notebook or JupyterLab:

```bash
jupyter notebook Albright_9053136_Assignment1_CSCN_8020_Reinforcement_Learning_Programming.ipynb
```

2. To run the notebook end-to-end non-interactively (executes all cells and updates the notebook):

```bash
jupyter nbconvert --execute --inplace --to notebook Albright_9053136_Assignment1_CSCN_8020_Reinforcement_Learning_Programming.ipynb
```

3. Logs will be written to the `logs/` directory. Check `logs/problem3.log` and `logs/problem4.log` for detailed run information.

## Notes

- The notebook is self-contained and includes implementations and brief discussions of results.
- If you want automated environment setup, I can add a `requirements.txt` .