# Medical Insurance Charges — Exploratory Data Analysis

## Project Overview
This project explores a medical insurance dataset to investigate how age, BMI, number of children, smoking status, sex, and region relate to insurance charges.

## Objectives
- Inspect dataset structure and summary statistics.
- Explore numerical distributions, categorical counts, and potential outliers.
- Check missing values and duplicate rows.
- Encode categorical variables and create BMI categories.
- Explore relationships with insurance charges using correlations and chi-square tests.
- Prepare a selected feature table for further analysis.

## Technologies
Python, Pandas, NumPy, Matplotlib, Seaborn, SciPy, scikit-learn, and Jupyter Notebook.

## Files
- `Medical_Insurance_Charges_EDA.ipynb` — organized notebook containing data inspection, EDA, preprocessing, feature engineering, and statistical association analysis.
- `insurance.csv` — input dataset. Include it only if you have permission to redistribute it.

## How to Run
1. Download or clone this repository.
2. Put `insurance.csv` in the same folder as the notebook.
3. Install dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn scipy scikit-learn jupyter
   ```

4. Open the notebook in Jupyter Notebook or JupyterLab.
5. Run cells from top to bottom.

## Notes and Limitations
- BMI categories are for descriptive analysis, not medical diagnosis.
- Pearson correlation describes linear association; it does not prove causation.
- Chi-square tests on binned charges examine association between categorical variables and charge groups.
- The selected columns are a starting point for analysis, not a validated prediction model.
- For predictive modeling, use a train/test split and fit preprocessing steps on training data only to avoid data leakage.

## Author
Created by [robinbuildsai](https://github.com/robinbuildsai)
