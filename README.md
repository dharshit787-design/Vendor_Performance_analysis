# Vendor Performance Analysis

## Project Overview
This project analyzes vendor-level purchase and sales data to evaluate performance, identify cost concentration, and understand inventory behavior. The goal is to provide practical insights that support better procurement and inventory decisions.

---

## Project Workflow
The analysis is structured into three logical stages, each handled in a separate notebook.

### 1. Data Preparation (`da.ipynb`)
- Raw datasets are loaded and checked for inconsistencies  
- Missing values and data quality issues are addressed  
- Required calculated fields are created for analysis  

This step ensures the data is reliable before moving forward.

---

### 2. Exploratory Data Analysis (`Exploratory Data Analysis.ipynb`)
- Summary statistics are generated  
- Purchase and sales trends are examined  
- Key distributions and relationships are visualized  

This stage helps in understanding patterns and anomalies in the data.

---

### 3. Vendor Performance Analysis (`vendor_preformance_analysis.ipynb`)
- Vendors are ranked based on purchase contribution  
- High and low-performing vendors are compared  
- Inventory efficiency and capital lock-in are analyzed  

The results highlight areas for optimization and cost control.

---

## Tools & Technologies
- Python  
- Pandas and NumPy  
- Matplotlib and Seaborn  
- Jupyter Notebook  

---

## Execution Order
For best results, run the notebooks in the following sequence:

da.ipynb
↓
Exploratory Data Analysis.ipynb
↓
vendor_preformance_analysis.ipynb
