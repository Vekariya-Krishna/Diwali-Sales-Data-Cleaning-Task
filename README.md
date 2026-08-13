# Diwali Sales Data Cleaning

## Project Overview

This project is about cleaning the Diwali Sales dataset and preparing it for further analysis. I checked the raw dataset for common data quality problems such as missing values, duplicate rows, unnecessary columns, inconsistent formatting, and data types.

## Objective

The main objective of this task was to find and fix common data quality issues and prepare a clean dataset for reliable analysis.

## Dataset

The dataset contains customer and sales-related information such as gender, age, state, occupation, product category, orders, and amount.

## Data Cleaning Steps

### 1. Removed Unnecessary Columns

* Removed `Status` and `unnamed1` as these columns were not needed for the analysis.

### 2. Handled Missing Values

* Found 12 missing values in the `Amount` column.
* Removed those records from the dataset.

### 3. Removed Duplicate Rows

* Found 8 duplicate rows.
* Removed the duplicate records.

### 4. Fixed Inconsistent Formatting

* Found an inconsistent space in `Andhra Pradesh` in the `State` column.
* Replaced the non-breaking space with a normal space.

### 5. Checked Data Types

* Checked the data type of each column.
* All columns already had suitable data types, so no changes were needed.

## Final Result

After cleaning the dataset:

* **Rows:** 11,231
* **Columns:** 13
* **Missing values:** 0
* **Duplicate rows:** 0

The cleaned dataset is now ready for further analysis.

## Tools Used

* Python
* Pandas
* Jupyter Notebook
* Microsoft Excel
* GitHub

## Files in this Repository

* `Diwali_Sales_Data_Cleaning.ipynb` - Jupyter Notebook containing the cleaning process.
* `Diwali_Sales_Cleaned.csv` - Cleaned dataset.
* `Change_log.xlsx` - Change log and summary of the cleaning work.

## Conclusion

The dataset was cleaned by removing unnecessary columns, handling missing values, removing duplicate records, and fixing inconsistent formatting. The final dataset is clean and ready for analysis.
