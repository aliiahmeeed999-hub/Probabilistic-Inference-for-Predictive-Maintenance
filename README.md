# Predictive Maintenance via Probabilistic Inference

Inferential statistics project focused on predictive maintenance for industrial machinery, with a practical Sub-Saharan African deployment context.

## Project Overview

This project models hidden machine health states using a Hidden Markov Model (HMM) and performs both exact and approximate inference from multivariate sensor data (temperature, vibration, pressure).

The notebook implements a full end-to-end pipeline:

- Problem formulation and probabilistic model design
- Synthetic data generation process (DGP)
- Exact inference (Forward-Backward and Viterbi baseline)
- Approximate inference (vectorized block Gibbs MCMC)
- Evaluation, diagnostics, and parameter learning (Baum-Welch / EM)
- Final synthesis and communication outputs

## Repository Contents

- `full_project.ipynb` - Main project notebook (Milestones I-V)
- `predictive_maintenance.csv` - Source dataset used in the project
- `final_report-1.pdf` - Final written report

## Methods and Tools

- Python
- NumPy
- SciPy
- Matplotlib

## How to Run

1. Create and activate a Python environment (recommended).
2. Install dependencies:

   ```bash
   pip install numpy scipy matplotlib jupyter
   ```

3. Launch Jupyter and open the notebook:

   ```bash
   jupyter notebook
   ```

4. Open `full_project.ipynb` and run all cells in order.

## Academic Context

Course: **CSC5341 - Inferential Statistics**

This repository is organized to make review and reproducibility straightforward: code, data, and report are all included in one place.
