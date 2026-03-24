\# ICU Patient Care Analysis



\## Project Overview



This project analyzes ICU patient data using the MIMIC-IV demo dataset to identify clinical, demographic, and care process factors associated with variation in ICU patient outcomes. The primary focus is on understanding drivers of length of stay (LOS), recovery indicators, and hospital resource utilization.



\## Research Question



What measurable patient characteristics, treatments, and care processes are most strongly associated with ICU outcomes?



\## Dataset



\* Source: MIMIC-IV Clinical Database (Demo)

\* Tables used:



&#x20; \* `patients`

&#x20; \* `icustays`

&#x20; \* `admissions`

&#x20; \* `labevents`

&#x20; \* `d\_labitems`



\## Methodology



This project follows the CRISP-DM framework:



1\. Business Understanding

2\. Data Understanding

3\. Data Preparation

4\. Modeling

5\. Evaluation



Key steps include:



\* Merging ICU and hospital datasets

\* Feature engineering (age, mortality, lab values)

\* Handling missing data and inconsistencies

\* Exploratory data analysis (EDA)

\* Regression modeling (Linear Regression, Random Forest)

\* Model evaluation using RMSE and R²



\## Project Structure



\* `notebooks/` – Jupyter notebooks containing full analysis workflow

\* `data/raw/` – Original dataset files (.csv.gz)

\* `data/processed/` – Cleaned and model-ready datasets (train/test splits)

\* `models/` – Saved trained models (.pkl files)

\* `results/` – Outputs including metrics and visualizations

\* `report/` – Final written report (PDF)



\## Key Outputs



\* ICU Length of Stay distribution

\* LOS segmentation (Short, Moderate, Prolonged stays)

\* Lab analysis (Lactate, Creatinine, White Blood Cell count)

\* Correlation analysis between clinical variables

\* Model performance metrics (RMSE, R²)

\* Diagnostic visualizations (histograms, scatter plots, boxplots)



\## Reproducibility



All preprocessing, feature engineering, modeling, and evaluation steps are documented in the notebooks.

Final datasets, trained models, and outputs are saved to ensure reproducibility and transparency.



\## How to Run



1\. Install dependencies:

&#x20;  pip install -r requirements.txt



2\. Launch Jupyter Notebook:

&#x20;  jupyter notebook



3\. Run notebooks in the `notebooks/` directory in order.



\## Notes



\* Data is de-identified in compliance with HIPAA standards.

\* This project is intended for academic and research purposes.

\* Findings may reflect dataset limitations and should not be interpreted as clinical recommendations.

