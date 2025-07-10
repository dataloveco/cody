# 🧾 Cody Data Discovery

This repository supports **Cody’s dissertation research** by organizing and profiling the datasets used in her data analysis.  
The goal is to explore, structure, and prepare large education-related datasets for deeper statistical and economic insight.

## 📁 Repository Structure

```text
Cody/
├── Cody Data Discovery.ipynb               # Main analysis notebook
├── Cody Data Discovery - Annotated.ipynb   # Annotated version with comments and markdown
├── Cody Data Discovery PDF.pdf             # Exported PDF of the notebook
├── discovered_data_files.txt               # File paths of discovered datasets
├── descriptive_summaries.xlsx              # Summary statistics for each dataset
├── multi_tab_variable_names.xlsx           # Excel file with tabs listing column names per dataset
├── data_dictionary.xlsx                    # Consolidated data dictionary preview
└── README.md                               # This file
```
## 🧠 What’s Inside?

This project includes:

- 🔍 **Automated file discovery and metadata extraction**  
  Quickly identifies all CSV, Excel, and TXT files in nested folders and logs them for analysis.

- 📊 **Descriptive statistics and variable summaries**  
  Includes counts, missing data percentages, unique values, and summary stats for numeric columns.

- 🧮 **Profiling tools for column types, missing data, and value counts**  
  Easily understand categorical distributions, missing value patterns, and column data types.

- 📑 **Excel exports with structured summaries**  
  Creates ready-to-use `.xlsx` files with variable names, profiles, and summaries for each file.

- ✏️ **Optional deep dives for filtered analyses**  
  Explore subsets of the data (e.g., by state or sector) using customizable filters and visualizations.

---

## 🛠️ Requirements

Make sure you install the following libraries:

```bash
pip install pandas matplotlib openpyxl xlsxwriter
```

---

## ⚠️ Data Disclaimer

This repository was developed for **Cody’s dissertation research**.  
The datasets used are **not owned** by The Data Love Co. and are not redistributed in this repository.  
Please refer to the original data providers for licensing and reuse terms.
