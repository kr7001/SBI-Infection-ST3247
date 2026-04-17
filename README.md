# Simulation-Based Inference for an Adaptive-Network Epidemic Model

Parameter inference for a stochastic SIR model on an adaptive network using simulation-based inference methods.

ST3247 Simulation, AY25/26 Semester 2, National University of Singapore.

## Team (Group 1)

- Zachary Gabriel Tan
- Goh Yu Siang Ranier
- Lee Kai Rong

## Structure

- data/ — Observed data (40 replicates)
- simulator.py — Adaptive-network SIR simulator
- rejection_abc.ipynb — Basic rejection ABC pipeline
- requirements.txt — Python dependencies

## Setup
```
pip install -r requirements.txt
```

Place the observed data CSVs in the data/ folder, then run the notebooks in order.

## Acknowledgements

Assignment, simulator, and observed data provided by Alexandre Thiery:
https://github.com/alexxthiery/SBI_infection