# Online Retail Data Cleaning using Python

## Project Overview
This project focuses on cleaning a real-world Online Retail dataset using Python and Pandas in Google Colab.

## Tools Used
- Python
- Pandas
- NumPy
- Google Colab

## Dataset
Online Retail dataset from Kaggle.

Dataset source: https://www.kaggle.com/datasets/vijayuv/onlineretail

## Data Cleaning Steps
1. Inspected the dataset structure and data types.
2. Identified missing values and duplicate records.
3. Removed 5,268 duplicate rows.
4. Replaced missing product descriptions with "Unknown".
5. Preserved missing CustomerID values instead of inventing customer IDs.
6. Converted InvoiceDate to datetime and corrected other data types.
7. Standardized text values and removed unnecessary spaces.
8. Investigated negative quantities, zero prices, negative prices, and potential outliers.
9. Created TotalAmount using Quantity × UnitPrice.
10. Added a flag to identify records with negative quantities.
11. Validated and exported the cleaned dataset to CSV.

## Final Results
- Original records: 541,909
- Final records: 536,641
- Duplicate records remaining: 0
- Missing CustomerID values retained: 135,037

## Key Learning
This project improved my understanding of data-quality assessment, missing-value handling, duplicate removal, data-type conversion, text cleaning, and transaction validation.

## Output
The cleaned dataset was exported as `Online_Retail_Cleaned.csv`.

## Author
Data Analytics Portfolio Project
