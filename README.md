# Supply Chain Delivery Performance Analytics

Predicting late deliveries using machine learning on the DataCo Supply Chain dataset (~180k orders).

## Key findings
- Overall On-Time Delivery rate: 59.7%
- Standard Class shipping has a 3× higher delay rate than Same Day
- XGBoost model achieved 0.87 AUC-ROC on held-out test set
- SHAP analysis identified Shipping Mode as the #1 driver of delay risk

## Tech stack
Python · Pandas · Scikit-learn · XGBoost · SHAP · Plotly · Seaborn

## Project structure
- notebooks/ — Full analysis from EDA to ML modeling
- reports/   — Final project report PDF

## Dataset
DataCo Smart Supply Chain — Constante et al., Mendeley Data V5
https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis

## How to run
Open the notebook directly on Kaggle: [link to your public notebook]