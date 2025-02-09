# Tax Rate Data Analysis

This Jupyter notebook contains an analysis of tax rate data for various countries, with a focus on Indonesia (country code 'ID'). Do note that this is a sample dataset.

## Contents

1. Data Import and Overview
2. Data Analysis for Indonesia
3. Data Quality Issues
4. Observations and Findings

## Key Features

- Imports tax rate data from an Excel file
- Filters data for Indonesia
- Analyzes tax types, rates, and effective dates
- Identifies data quality issues and inconsistencies

## Data Quality Issues Identified

1. Duplicated entries
2. Incomplete tax types for Indonesia
3. Issues with tax_rate column:
   - Negative and overly high values
   - Presence of null values
   - Fluctuating tax rates for certain categories
4. Problems with effective_month column:
   - Incomplete data
   - Mixed data from different years
   - Inconsistent date formats

## Usage

To use this notebook:

1. Ensure you have Pandas installed (`pip install pandas`)
2. Place the 'tax_rate_data.xlsx' file in the same directory as the notebook
3. Run the cells in order to reproduce the analysis

## Notes

- The original file was in strict open XML spreadsheet format. It was converted to a valid Excel workbook for use with Pandas.
- This analysis was part of an interview task focusing on data for the country code 'ID' (Indonesia).
- If you found any other anomalies with the data that was addressed, feel free to reach out! I would love to know as well ^.^
