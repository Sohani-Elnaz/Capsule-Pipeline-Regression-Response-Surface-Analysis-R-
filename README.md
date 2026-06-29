# Capsule-Pipeline-Regression-Response-Surface-Analysis-R-
A clean, reproducible R project for quadratic regression modelling, response‑surface visualization, and performance evaluation of capsule‑pipeline hydrodynamics.

# Capsule Pipeline Regression & Response Surface Analysis (R)

This repository contains an R implementation of a quadratic regression model
for predicting pressure loss (PL) in hydraulic capsule pipelines based on
three geometric factors:

- Lc — Capsule Length  
- S  — Capsule Spacing  
- Dc — Capsule Diameter  

The project includes:
- Quadratic regression model with interaction terms  
- Model performance metrics (R², RMSE, MAE)  
- Response surface plots for pairwise factor interactions  
- Residual analysis  
- Predicted vs experimental comparison  

---

## 📂 Files

### `analysis.R`
Main R script performing:
- Data loading  
- Model fitting  
- Prediction  
- Performance evaluation  
- Response surface visualization  

### `data/dataset.csv`
Raw dataset used for modelling.

---

## 📊 Model Summary

The regression model used:



\[
PL \sim (Lc + S + Dc)^2 + Lc^2 + S^2 + Dc^2
\]



This includes:
- Linear terms  
- Pairwise interactions  
- Quadratic terms  

---

## ▶️ Running the Script

Open R or RStudio and run:

```r
source("analysis.R")

This will generate:

Model summary

Performance metrics

Three response‑surface plots

Residual plot

Predicted vs experimental scatter plot
