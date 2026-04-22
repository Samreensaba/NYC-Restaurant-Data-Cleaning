# NYC Restaurant Inspections: Data Cleaning Case Study

### Project Overview
This project involves a comprehensive cleaning of 81,000+ records of NYC restaurant data. I transformed a "dirty" dataset into an analysis-ready format by handling null values, optimizing data types, and standardizing categories.

### Key Transformations
* **Memory Optimization:** Converted object types to `category` for 40% faster processing.
* **Date Standardization:** Fixed inconsistent string formats into `datetime` objects.
* **Geographical Imputation:** Handled ~8,000 missing coordinates by marking them as `0.0` to preserve record integrity.

### Results
<img width="1583" height="572" alt="image" src="https://github.com/user-attachments/assets/3797895e-a5e8-412e-98e1-33a6ca4facc2" />

*The chart above demonstrates how imputed values were handled without losing 10% of the dataset.*
