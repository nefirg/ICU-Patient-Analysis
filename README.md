# ICU Patient Care Analysis

## Project Overview
This project analyzes ICU patient data to identify clinical, demographic, and care process factors associated with variation in ICU outcomes, with a focus on length of stay, recovery indicators, and resource utilization.

## Research Question
What measurable patient characteristics, treatments, and care processes are most strongly associated with ICU outcomes?

## Dataset
- MIMIC-IV Demo Dataset
- Tables used:
  - patients
  - icustays
  - labevents
  - d_labitems

## Project Structure
- notebooks/ – Jupyter notebooks used for analysis
- data/raw/ – Original dataset files
- data/processed/ – Cleaned/merged datasets
- outputs/ – Figures and tables used in the final report
- report/ – Final written report (PDF)

## How to Run
1. Install dependencies:
   pip install -r requirements.txt

2. Open Jupyter Notebook:
   jupyter notebook

3. Run notebooks in the notebooks/ folder in order.

## Key Outputs
- ICU Length of Stay distribution
- Lab value histograms (Lactate, Creatinine, WBC)
- LOS segmentation analysis
- Data quality assessment tables
