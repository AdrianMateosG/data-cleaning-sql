# Nashville Housing Data Cleaning & Preparation

## Author

Adrian Mateos Garza
Email: mateos.garza.adrian@gmail.com

## Overview

This notebook outlines the process of cleaning and preparing Nashville housing data for analysis. The data is sourced from an Excel file (nashville_housing_data.xlsx) and is then loaded into an SQLite database for further manipulation.

## Steps Involved

1. **Setup**:

   - Import necessary libraries (`pandas` and `sqlite3`).
   - Load the SQL magic extension for executing SQL commands within the notebook.
2. **Data Loading**:

   - Load the Nashville housing data from an Excel file into a pandas DataFrame.
   - Convert the DataFrame into an SQLite database table.
3. **Data Cleaning**:

   - Standardized date formats for relevant columns.
   - Addressed missing values by utilizing appropriate joins and transformations.
   - Split multi-field columns into separate, more specific fields.
   - Encoded categorical columns into numerical representations.
   - Removed duplicate entries.
   - Eliminated irrelevant or unnecessary columns from the dataset.
4. **Final Output**:

   - The cleaned dataset is now ready for analysis, with all necessary transformations applied.

## Usage

To run this notebook, ensure you have the required libraries installed and the input Excel file (`nashville_housing_data.xlsx`) available in the working directory.

## License

This project is licensed under the MIT License.
