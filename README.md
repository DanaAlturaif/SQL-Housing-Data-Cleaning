# Nashville Housing Data Cleaning (SQL)

This project focuses on cleaning and preparing a housing dataset using SQL to improve data quality and usability for analysis.

The dataset was cleaned by standardizing formats, handling missing values, splitting columns, correcting inconsistent values, and removing unnecessary fields.

## Tool Used
- SQL (Microsoft SQL Server)

## Cleaning Steps Performed
- Standardized date format by converting SaleDate to a proper Date column
- Populated missing PropertyAddress values using self-joins
- Split PropertyAddress into separate Address and City columns
- Split OwnerAddress into Address, City, and State columns
- Converted SoldAsVacant values from Y/N to Yes/No
- Identified and removed duplicate records using ROW_NUMBER()
- Dropped unused columns
