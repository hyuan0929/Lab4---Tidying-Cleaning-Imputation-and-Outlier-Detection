# Lab 4 – Data Tidying, Data Cleaning, Missing Values & Outlier Detection


## Overview

1. **Data Tidying**
   - Reshaping datasets from wide → long format using **`pandas.melt()`**
2. **Data Cleaning / Missing Values**
   - Exploring missingness and applying different strategies:
     - Dropping columns with missing values (and discussing trade-offs)
     - Simple imputation examples (e.g., fill with 0 vs mean-based imputation)
     - Using **`sklearn.impute.SimpleImputer`** for numeric columns
3. **Outlier Detection**
   - Visualizing and detecting outliers using:
     - **Boxplot**
     - **Scatter plot**
     - **Z-score method**
     - **IQR (Inter-Quartile Range) method**
   - Demonstrating outlier filtering on a selected feature (e.g., **Glucose**)

The notebook was also tested in a **clean virtual environment** to ensure replicability.

---

## Notebook
- Main notebook: `Lab4 - Tidying, Cleaning, Imputation, and Outlier Detection` 

---

## Datasets Used
The notebook loads CSV files from a `CSVs/` folder (relative to the notebook directory):

- `../CSVs/pew-raw.csv`  (PEW Research – income ranges by religion)
- `../CSVs/billboard.csv` (Billboard weekly ranking dataset)
- `../CSVs/cars.csv` (Cars dataset, delimiter `;`)
- `../CSVs/diabetes.csv` (Diabetes dataset for outlier detection)

> ✅ Make sure your local folder structure matches the paths above, otherwise `pd.read_csv()` will fail.

---

## Install dependencies

pip install -r requirements.txt



