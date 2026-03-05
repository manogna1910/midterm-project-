# ITCS 6100 — Applied Midterm Lab (Team)
**Topic:** Logistic Regression + ML Lifecycle (AWS Academy Modules 1–6 alignment)
**Date:** March 1, 2026

## Team Information
- **Team Name:** project group 5 BIGDATA
- **Student Names:**
  - Manogna Devarapu
  - Banvitha Balaji
  - Sai praneeth reddy kaithi
  - Ruchika Baireddy

## Project Overview
This project presents the completed Midterm Lab for ITCS 6100. It demonstrates a complete Machine Learning lifecycle applying Logistic Regression to predict customer churn. The project aligns with concepts from AWS Academy Modules 1-6.

## Dataset
The project utilizes a synthetic, realistic "messy" customer churn dataset (`synthetic_churn.csv`) with the following characteristics:
- **Size:** 6000 records, 21 varying features (demographics, behavior, billing, product details).
- **Target Variable:** `churn` (1 = churned, 0 = stayed).
- **Data Quality Issues Addressed:** Includes many dimensions (numeric & categorical), missing values (both random and structured), outliers, heavy-tailed distributions, redundant features, and mild class imbalance.

## ML Lifecycle Roadmap & Components
The analysis is structured according to a standard ML lifecycle, organized directly within the Jupyter Notebook (`.ipynb`):
1. **INGEST:** Data loading and initial inspection (identifying shape, missing values, and data types).
2. **CLEAN:** Handling data quality issues like missing values and outliers.
3. **PREPARE:** Data splitting, encoding categorical variables, scaling numerical features, and building preprocessing pipelines.
4. **MODEL:** Training the Logistic Regression model, including configuring considerations for regularization and class weights.
5. **ANALYZE:** Complete model evaluation detailing the confusion matrix, performance metrics, threshold tuning, and reasoning interpreted from the results.

## Deliverables
- Fully executed Jupyter Notebook (`.ipynb`) containing all code, generated outputs, and analytical discussions.
- Individual submission verifications on the Github class repo.

## Usage
To review the project:
1. Open the `.ipynb` file using Jupyter Lab, Jupyter Notebook, Google Colab, or any compatible environment.
2. The notebook generates the `synthetic_churn.csv` dataset in its first executable block. Subsequent cells should be reviewed sequentially to follow the ML implementation lifecycle.

---
