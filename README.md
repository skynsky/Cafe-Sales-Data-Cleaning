# Cafe Sales Data Cleaning and Analysis

## Overview

This project focuses on cleaning and analyzing a cafe sales dataset using Python. The dataset contains missing values, inconsistent data types, and potential outliers that must be handled before analysis.

## Objectives

* Clean missing and invalid data
* Convert columns into appropriate data types
* Handle outliers
* Prepare data for business analysis and visualization

## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

## Data Cleaning Process

1. Checked missing values.
2. Converted numerical columns into numeric format.
3. Replaced missing values using median and mode.
4. Removed unnecessary columns.
5. Identified potential outliers using the IQR method.

## Dataset Features

* Item
* Quantity
* Price Per Unit
* Total Spent
* Transaction Date
* Payment Method

## Key Findings

* Several numerical columns contained invalid values and missing data.
* Missing values were successfully handled using statistical imputation.
* Outliers were identified in transaction spending data.
* The cleaned dataset is ready for dashboard development and further business analysis.

## Project Files

* `cafe_sales_.ipynb` : Data cleaning and analysis notebook
* `dirty_cafe_sales.csv` : Raw dataset
* `screenshots/` : Visualization outputs

## Future Improvements

* Build an interactive Power BI dashboard.
* Create sales trend analysis.
* Analyze customer purchasing behavior.
* Generate business insights for decision making.
