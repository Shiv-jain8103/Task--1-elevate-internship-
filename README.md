# Task--1-elevate-internship-
# 🧹 Data Cleaning and Preprocessing (Excel + CSV)

## 📌 Objective

Clean and prepare a raw CSV dataset by handling missing values, removing duplicates, standardizing formats, and ensuring data consistency using Microsoft Excel.

## 🛠️ Tools Used

- Microsoft Excel
- CSV to Markdown conversion tools (e.g., `csvtomd`, `csv2md`)

## 📂 Files

- `raw_dataset.csv` – Original unprocessed data.
- `cleaned_dataset.csv` – Final cleaned dataset.
- `README.md` – Documentation of the data cleaning process.

## 🔧 Steps Performed

1. **Handled Missing Values**:
   - Identified missing values using Excel filters.
   - Filled missing numeric values with the column average.
   - Filled missing categorical values with the most frequent category.
   - Removed rows with critical missing data.

2. **Removed Duplicates**:
   - Used Excel's "Remove Duplicates" feature to eliminate duplicate rows based on key columns.

3. **Standardized Text Formats**:
   - Trimmed extra spaces using the `TRIM` function.
   - Standardized text case using `UPPER`, `LOWER`, and `PROPER` functions.
   - Replaced inconsistent entries using "Find and Replace".

4. **Converted Date Formats**:
   - Ensured all dates follow the `DD-MM-YYYY` format using Excel's "Format Cells" feature.

5. **Renamed Column Headers**:
   - Renamed columns to lowercase with underscores for consistency.

6. **Checked and Fixed Data Types**:
   - Converted numeric text to numbers using the `VALUE` function.
   - Ensured date fields are correctly recognized using the `DATEVALUE` function.

## 📊 Sample of Cleaned Data

Below is a preview of the cleaned dataset:

```csv
Name,Gender,Age,Country,Date_of_Birth
Alice,Female,29,India,15-06-1996
Bob,Male,34,USA,22-09-1991
Charlie,Male,28,UK,03-12-1996
