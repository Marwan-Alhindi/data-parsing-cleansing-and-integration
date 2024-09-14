# Job Advertisement Data Parsing, Cleansing, and Integration

## Overview

This project is focused on parsing, cleansing, and integrating job advertisement data from multiple sources. The data is provided in both XML and CSV formats, and the tasks involve addressing various data quality issues and integrating the datasets to form a unified dataset.

### Tasks Breakdown:
1. **Task 1 & 2 (Data Parsing and Cleansing)**:
   - Parse job advertisement data stored in an XML file into a Pandas DataFrame.
   - Clean the data, handle missing values, correct errors, and ensure data consistency.

2. **Task 3 (Data Integration)**:
   - Integrate the cleaned dataset from Task 2 with a second dataset in CSV format.
   - Resolve schema conflicts, remove duplicates, and ensure consistency across both datasets.

## Files Included

- **s3969393_dataset1.xml**: XML file containing job advertisement data for parsing and cleansing.
- **s3969393_dataset2.csv**: CSV file with additional job advertisement data for integration.
- **s3969393_dataset1_solution.csv**: The output of the cleaned dataset from Task 2.
- **s3969393_dataset_integrated.csv**: The final integrated dataset combining both XML and CSV data sources.
- **s3969393_errorlist.csv**: A list of errors identified and corrected during the data cleansing process, including details about each error and how it was resolved.
- **s3969393_task1_2.ipynb**: Jupyter notebook containing Python code for Task 1 and Task 2 (parsing and cleansing).
- **s3969393_task3.ipynb**: Jupyter notebook containing Python code for Task 3 (integration).

## Tasks Summary

### Task 1: Data Parsing
- **Goal**: Parse the XML data into a Pandas DataFrame.
- **Output**: A DataFrame with columns like `Id`, `Title`, `Location`, `Company`, `ContractType`, `ContractTime`, `Category`, `Salary`, `OpenDate`, `CloseDate`, and `SourceName`.

### Task 2: Data Cleansing
- **Goal**: Clean the parsed dataset, fix errors, handle missing values, and format the data appropriately.
- **Errors Addressed**: Spelling mistakes, missing values, irregularities, outliers, and duplicates.
- **Output**: A cleaned dataset, saved as `s3969393_dataset1_solution.csv`.

### Task 3: Data Integration
- **Goal**: Integrate the cleaned dataset from Task 2 with the second CSV dataset.
- **Steps**:
  - Resolve schema conflicts.
  - Remove duplicate entries.
  - Ensure consistency across both datasets.
- **Output**: The final integrated dataset, saved as `s3969393_dataset_integrated.csv`.

## How to Run

1. **Environment Setup**:
   - Ensure you have Python 3.x installed.
   - Install the necessary dependencies using:
     ```bash
     pip install pandas numpy matplotlib
     ```

2. **Running Tasks 1 & 2** (Parsing and Cleansing):
   - Open the `s3969393_task1_2.ipynb` Jupyter notebook.
   - Execute the code cells to parse and clean the XML dataset.
   - The cleaned dataset will be saved as `s3969393_dataset1_solution.csv`.

3. **Running Task 3** (Integration):
   - Open the `s3969393_task3.ipynb` Jupyter notebook.
   - Execute the code cells to integrate the cleaned dataset with the CSV dataset.
   - The integrated dataset will be saved as `s3969393_dataset_integrated.csv`.

## Outputs

- **Cleaned Dataset**: `s3969393_dataset1_solution.csv`
- **Integrated Dataset**: `s3969393_dataset_integrated.csv`
- **Error List**: `s3969393_errorlist.csv`
