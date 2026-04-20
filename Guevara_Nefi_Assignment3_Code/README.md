# ICU Patient Care Analysis

## Project Overview
This project analyzes ICU patient data using the MIMIC-IV dataset to identify key factors influencing patient outcomes, particularly ICU length of stay (LOS). The goal is to support improved patient care and more efficient hospital resource utilization.

## Research Objective
What patient characteristics, clinical indicators, and care factors are most strongly associated with ICU length of stay and outcomes?

---

## Dataset
- Source: MIMIC-IV Clinical Database (Demo)
- Tables used:
  - icustays
  - patients
  - admissions
  - labevents
  - d_labitems

---

## Methodology
This project follows the CRISP-DM framework:

1. Data Integration (multi-table joins)
2. Data Cleaning (missing values, inconsistencies)
3. Feature Engineering:
   - Age
   - Mortality
   - Lab values (lactate, creatinine, WBC)
   - LOS segmentation
4. Exploratory Data Analysis (EDA)
5. Modeling:
   - Linear Regression
   - Random Forest Regression
6. Model Evaluation (RMSE, R²)

---

## Key Findings

- Clinical indicators (lab values) are stronger predictors of ICU LOS than demographics
- Lactate, creatinine, and WBC are key drivers of outcomes
- A small subset of patients accounts for the majority of ICU resource utilization
- LOS segmentation reveals meaningful differences in mortality and care complexity

---

## Results & Outputs

All outputs are saved in the `/results` folder:

- LOS distribution
- LOS segmentation analysis
- Mortality by LOS segment
- Lab analysis plots
- Feature importance chart
- Model performance metrics

---

## Project Structure

assignment2/
│
├── ICU_Patient_Care_Analysis.ipynb
├── README.md
├── requirements.txt
├── ICU Patient Care Analysis Case Study_3rd_Part.pdf
│
├── data/
│   ├── raw/
│   └── processed/
│
├── models/
│   └── model.pkl
│
├── results/

## How to Reproduce

1. Install dependencies:
pip install -r requirements.txt

2. Launch Jupyter:
jupyter notebook

3. Run:
ICU_Patient_Care_Analysis3.ipynb

4. Outputs will be saved in `/results`