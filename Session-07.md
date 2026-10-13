# Session 7: Data Cleaning and Handling Missing Values

## Topics Covered
- Introduction to data cleaning.
- Handling missing values.
- Removing duplicate records.
- Identifying inconsistent data.

## Key Learnings

- **Data Cleaning:** The process of identifying and correcting errors in a dataset.
- **Missing Values:** Empty or unavailable values that can be handled by removing or filling them.
- **Duplicate Records:** Repeated entries that may affect data analysis and should be checked.
- **Inconsistent Data:** Incorrect formats or values that need correction.
- **Outlier Detection:** Identifying unusually high or low values that may require investigation.

## Common Pandas Operations
- `isnull().sum()` – Counts missing values.
- `dropna()` – Removes rows or columns containing missing values.
- `fillna()` – Replaces missing values with specified values.
- `duplicated()` – Identifies duplicate records.
- `drop_duplicates()` – Removes duplicate records.

## Key Takeaways
- Clean data improves the reliability of Machine Learning models.
- Missing values can be handled using suitable methods, such as mean or median imputation.
- Duplicate and inconsistent records should be checked before training.
- Data cleaning methods should be selected according to the dataset.

## Summary
Learned the importance of data cleaning and explored techniques for handling missing values, removing duplicates, and identifying inconsistencies using Pandas.
