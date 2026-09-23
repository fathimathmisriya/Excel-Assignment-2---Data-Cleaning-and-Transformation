# Excel Data Cleaning and Formatting Assignment

## 📌 Project Overview

This project demonstrates the process of cleaning, transforming, and formatting a dataset using Microsoft Excel. The main objective is to improve the accuracy, consistency, readability, and usability of the dataset by applying different data-cleaning and formatting techniques.

## 🎯 Objectives

- Identify and handle missing values.
- Identify and correct inconsistent text formats.
- Find and correct typos in categorical data.
- Remove duplicate records.
- Split Product ID into separate fields.
- Merge Brand Name and Product Name into a new column.
- Format Price values as currency.
- Format Manufacturing Date consistently.
- Apply conditional formatting to numerical and categorical data.

## 🧹 Data Cleaning and Transformation

The following data-cleaning tasks were performed:

### 1. Handling Missing Price Values
Missing values in the **Price** column were identified and handled using an appropriate value-imputation method.

### 2. Standardizing Product Names
Inconsistent capitalization in the **Product Name** column was identified and standardized.

Examples:

- `laptop` → `Laptop`
- `smartphone` → `Smartphone`
- `headphones` → `Headphones`

### 3. Correcting Category Typos
Typographical errors in the **Category** column were identified and corrected.

Example:

- `Electroni` → `Electronics`

### 4. Removing Duplicate Records
Duplicate records were identified using Excel's **Remove Duplicates** feature and unnecessary duplicate records were removed.

### 5. Splitting Product ID
The **Product ID** column was separated into:

- Manufacturing Date
- Country Code

For example:

`28-JAN-US`

was separated into:

- Manufacturing Date: `28-JAN`
- Country Code: `US`

### 6. Creating Product Brand
The **Brand Name** and **Product Name** columns were merged into a new column named **Product Brand**.

Example:

`Dell` + `Laptop` → `Dell Laptop`

### 7. Formatting Price
The **Price** column was formatted using the currency format to improve readability and clearly represent monetary values.

### 8. Formatting Manufacturing Date
The **Manufacturing Date** column was formatted using the `DD-MM-YYYY` date format.

Example:

`28-JAN-2026` → `28-01-2026`

### 9. Conditional Formatting – Price
Data Bars were applied to the **Price** column to visually compare low and high price values.

### 10. Conditional Formatting – Category
A custom conditional formatting rule was created to highlight cells where the category is **Electronics**.


## 📁 Project Files

- `Dataset.xlsx` – Cleaned and formatted Excel dataset
- `README.md` – Project documentation

## ✅ Conclusion

This assignment demonstrates the practical use of Microsoft Excel for data cleaning and preparation. The cleaned dataset is more consistent, organized, and suitable for further analysis and reporting.

---

**Tools:** Microsoft Excel | GitHub
