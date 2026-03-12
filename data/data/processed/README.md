# Processed Data

This folder contains datasets generated during the data cleaning and transformation process.  
These datasets are produced by scripts in the `scripts/` folder.

## Datasets

### state_tax_brackets_clean.csv
Cleaned version of the state tax bracket dataset formatted for analysis.

This dataset standardizes tax bracket ranges and tax rates across states to make them suitable for merging with income data.

---

### tax_income_merged.csv
Dataset created by merging state tax bracket information with state income data.

This dataset is used to estimate **average annual net income after state income tax**.

---

### remaining_income_by_state.csv
Final dataset used for analysis and visualization.

This dataset contains the key variables used to evaluate affordability across U.S. states, including:

- average annual net income
- annual rental cost
- annual grocery cost
- remaining income after basic living expenses
