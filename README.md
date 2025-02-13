# Python Data Cleaning

# Project Overview
This project is designed to efficiently clean datasets by handling duplicates, missing values, and providing cleaned output within seconds. This is user-friendly, highly performance, and has been tested on various datasets, ensuring smooth execution and accuracy.

This code can handle datasets with thousands of rows and quickly clean them without errors. It keeps a backup of duplicate records, replaces missing numeric values with column means, and drops rows with missing non-numeric values. This makes it an excellent tool for data pre-processing in data analysis workflows.
# Objective
The key objectives of this project are:
1. Load and clean datasets in various formats (CSV and Excel).
2. Identify and remove duplicate records, while keeping a backup of these duplicates.
   
Handle missing values:
1. For numeric columns: replace missing values with the column's mean.
2. For non-numeric columns: remove rows containing missing values.
3. Save the cleaned dataset and provide access to both the cleaned data and duplicate records.

# Project Requirements
Python 3.x
Pandas
Numpy
Openpyxl
Xlrd
OS library
Jupyter Notebook (for testing)
