# Linear Regression for House Price Prediction

A machine learning lab that predicts house prices with linear models, from a single-feature baseline to regularized regression, on the California Housing dataset and a Saudi housing dataset.

## What's inside

- **Exploration:** feature correlations, target distribution (including the $500k cap) and scatter plots on 20,640 California districts
- **Simple linear regression** using median income alone
- **Multiple linear regression** with all 8 features in a scaled pipeline, plus coefficient-based feature importance
- **Polynomial regression** comparing degrees 1–3
- **Regularization:** Ridge, Lasso and ElasticNet, with alpha tuning and Lasso feature selection
- **Saudi housing case study:** 500 properties across Riyadh, Jeddah, Makkah, Madinah and Dammam, priced in thousands of SAR

## Results

| Dataset | Model | R² |
|---|---|---|
| California Housing | Simple LR (median income) | 0.459 |
| California Housing | Multiple LR (all features) | 0.576 |
| Saudi housing | Simple LR | 0.493 |
| Saudi housing | Multiple LR / Lasso | 0.865 |

Using all features roughly doubled explained variance on the Saudi dataset, with property area as the strongest predictor.

## Tech

Python · pandas · NumPy · scikit-learn · Matplotlib · Jupyter

## Run it

Open `lab4.ipynb` in Jupyter or Google Colab and run all cells.
