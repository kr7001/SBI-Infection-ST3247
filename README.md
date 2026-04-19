# Simulation-Based Inference for an Adaptive-Network Epidemic Model

Parameter inference for a stochastic SIR model on an adaptive network using simulation-based inference methods.

ST3247 Simulation, AY25/26 Semester 2, National University of Singapore.

## Team (Group 1)

- Lee Kai Rong
- Zachary Gabriel Tan
- Goh Yu Siang Ranier

## Structure

- data/ — Observed data (40 replicates)
- simulator.py — Adaptive-network SIR simulator
- rejection_abc.ipynb — Basic rejection ABC pipeline
- rejection_abc_smc.ipynb — Sequential Monte Carlo ABC pipeline including basic rejection ABC (as some functions were reused)
- model_comparison.ipynb — Results and analysis for basic rejection ABC and SMC-ABC
- rejection_abc.npz — Rejection ABC results (saved for rejection_abc_smc.ipynb and model_comparison.ipynb)
- smc_abc_results.npz — SMC-ABC results (saved for model_comparison.ipynb)
- requirements.txt — Python dependencies

## Setup
```
pip install -r requirements.txt
```

Place the observed data CSVs in the data/ folder, then run the notebooks in order.

## Acknowledgements

Assignment, simulator, and observed data provided by Prof. Alexandre Thiery:
https://github.com/alexxthiery/SBI_infection