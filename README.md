# Computing Intelligence — Lab 1

This repository contains the completed exploratory analysis for the IBM Telco Customer Churn dataset.

## Contents

- `Telco_Customer_Churn_Lab1.ipynb` — the assignment notebook.
- `data/` — place `Telco-Customer-Churn.csv` here if internet access is unavailable when running the notebook.

## Run it

1. Create a Python environment with `pandas`, `numpy`, `matplotlib`, `seaborn`, and `jupyter`.
2. Open `Telco_Customer_Churn_Lab1.ipynb`.
3. Run all cells from top to bottom.

The first cell uses the official public IBM raw-data URL and saves a local copy under `data/`. The source corresponds to the dataset specified in the brief: https://www.kaggle.com/datasets/blastchar/telco-customer-churn

## Covered requirements

- Introduction, loading, head, and tail
- Churn encoding (`Yes`/`No` to `1`/`0`)
- Data type inspection/conversion and missing-value removal
- Demographic analysis: gender, senior citizen, partner, dependents
- Service analysis: phone service
- Payments/account analysis: contract, paperless billing, payment method
- A written interpretation after every chart output
