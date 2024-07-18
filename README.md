# Nashville Housing Data Cleaning Project

This project involves cleaning and preparing the Nashville Housing dataset to ensure data consistency, completeness, and accuracy for further analysis. The data cleaning steps performed 
include:

- **Converting Date Format**: Standardized the `SaleDate` field to a consistent date format.
- **Populating Property Address Data**: Filled in missing `PropertyAddress` values using other records with the same `ParcelID`.
- **Breaking Out Address into Individual Columns**: Split `PropertyAddress` and `OwnerAddress` into separate columns for `Address`, `City`, and `State`.
- **Standardizing "Sold As Vacant" Field**: Converted `Y` and `N` values in the `SoldAsVacant` field to `Yes` and `No`.
- **Removing Duplicates**: Identified and removed duplicate records based on key fields.
- **Deleting Unused Columns**: Dropped columns that are no longer needed after data cleaning.

## Project Overview

The goal of this project is to make the Nashville Housing dataset ready for analysis by performing comprehensive data cleaning tasks. This includes transforming date formats, 
addressing missing data, standardizing categorical values, eliminating duplicate records, and refining the dataset structure.
