# Explainable-AI
# XAI on Tabular Biomedical Data

**SHAP · LIME · Counterfactual Explanations (DiCE)**

## Overview
This project explores **Explainable AI (XAI)** techniques on **tabular biomedical data**, using the **Breast Cancer dataset** as a case study.  
The notebook demonstrates how to train baseline classifiers and interpret their predictions using **global**, **local**, and **counterfactual** explanations.

## Objectives
By completing this notebook, you will learn how to:

- Train and evaluate classical ML models on tabular medical data
- Apply **SHAP** for global and local feature attribution
- Use **LIME** for local, instance-level explanations
- Generate counterfactual explanations with **DiCE-ML**
- Analyze explanation **faithfulness, stability, and plausibility** in a clinical context

## Methods

### Models
- **Logistic Regression** (interpretable linear baseline)
- **Random Forest** (non-linear ensemble model)

### Explainability Techniques

#### SHAP
- Global feature importance
- Local explanations (e.g. waterfall plots)

#### LIME
- Local surrogate explanations for individual predictions

#### DiCE-ML
- Counterfactual examples to minimally flip model predictions
