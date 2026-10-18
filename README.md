> **Status: work in progress.** The analysis notebook and synthetic-data generator will be added to this repository; the results below are from the completed analysis.

# HERA – Early Pregnancy Preeclampsia Risk Stratification

Early-pregnancy preeclampsia risk stratification using routinely collected clinical data (applied epidemiology).

HERA (Health Evidence & Risk Analytics) is an applied epidemiology project focused on early-pregnancy risk stratification for preeclampsia using routinely collected clinical and demographic data.

## Overview
The goal of this project is to demonstrate a realistic, interpretable, and decision-relevant modeling workflow suitable for population-level screening and early triage. Emphasis is placed on calibration, risk stratification, and scalability rather than purely maximizing predictive performance.

## Data
- Literature-calibrated synthetic observational dataset
- 10,000 pregnancies
- Prediction time point: end of first trimester (~13 weeks)
- Primary outcome: preeclampsia / hypertensive disorder of pregnancy

## Modeling approach
- Logistic regression with clinically interpretable predictors
- Strict respect for temporality (no post-outcome variables)
- Train/test validation
- Evaluation focused on calibration and risk-group separation

## Key results
- Test AUC ≈ 0.65 (consistent with early-pregnancy models using routine data)
- Good calibration with meaningful risk stratification
- Top decile of predicted risk showed ~15% observed preeclampsia rate versus ~4% in the lowest 70%

## Interpretation
Even with moderate discrimination, well-calibrated models using routine data can provide actionable risk stratification to support early surveillance and targeted intervention.

## Notes
- Synthetic data used to avoid privacy concerns
- Project designed as a baseline, scalable screening model
- Biomarker scenarios explored to assess incremental value

## Author
Physician–Epidemiologist | Applied Health Analytics
