# Task 3: Cleaning Data — Messy Dataset Transformation

## Project Overview
This project demonstrates professional-level data cleaning techniques using Python (`pandas`, `numpy`). A deliberately messy cafe sales dataset was systematically analyzed, cleaned, standardized, and transformed into an analysis-ready format.

## Tech Stack
* **Language:** Python
* **Libraries:** pandas, numpy
* **Environment:** Jupyter Notebook / Google Colab

## Data Cleaning Workflow
1. **Data Quality Audit:** Identified missing values, duplicate records, incorrect data types, and formatting inconsistencies.
2. **Missing Data Strategy:** Applied median imputation for numerical features and mode/forward fill for categorical features based on business logic.
3. **Duplicate Removal:** Deduplicated identical rows and documented total removed records.
4. **Standardization:** Normalized text casing, stripped trailing whitespace, and cast date strings into proper `datetime64` types.
5. **Outlier Handling:** Applied IQR (Interquartile Range) method to detect extreme anomalies in numeric columns.
6. **Data Type Correction:** Converted IDs to strings, monetary/quantities to float/integer.

## Before vs. After Summary Table

| Metric | Before Cleaning | After Cleaning |
| :--- | :--- | :--- |
| **Total Rows** | Initial Row Count | Final Clean Row Count |
| **Duplicate Rows** | Identified Duplicates | 0 |
| **Null Values (Total)** | Total Nulls | 0 |
| **Data Types** | Inconsistent (strings/objects) | Correct (`datetime`, `float`, `int`, `str`) |

## File Structure
* `Oasis_Infobyte_Task3_DataCleaning.ipynb` — Full Python notebook with code and markdown justification.
* `dirty_cafe_sales.csv` — Original raw/messy dataset.
* `cleaned_cafe_sales.csv` — Final cleaned CSV output.
* `README.md` — Project documentation.
