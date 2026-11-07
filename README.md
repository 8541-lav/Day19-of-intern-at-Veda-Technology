# Day 19 – Inventory Turnover Analysis

## Internship: Veda Technology

### 1. Project Overview
The objective of this project is to analyze inventory data and evaluate how efficiently inventory is being managed. The analysis focuses on calculating inventory turnover ratios, comparing product categories, and identifying potentially slow-moving inventory records.

### 2. Dataset Information
- **Dataset:** Inventory Supply Chain Dataset
- **Total Records:** 1,200
- **Total Columns:** 15
- **Date Range:** 2020–2024

Important columns used:
- Category
- Units Sold
- Inventory Level
- Cost of Goods Sold (COGS)
- Average Inventory
- Date

### 3. Tools and Technologies
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

### 4. Project Tasks
1. Imported the inventory dataset using Pandas.
2. Explored dataset structure and statistical information.
3. Checked missing values and duplicate records.
4. Converted the Date column into datetime format.
5. Calculated Inventory Turnover Ratio.
6. Performed category-wise inventory turnover analysis.
7. Identified slow-moving and fast-moving inventory records.
8. Created visualizations for inventory performance.
9. Exported analysis results into CSV files.

### 5. Inventory Turnover Formula

**Inventory Turnover Ratio = COGS / Average Inventory**

This ratio measures how efficiently inventory is being sold and replenished.

### 6. Key Results

| Metric | Result |
|---|---:|
| Total Records | 1,200 |
| Average Turnover | 31.10 |
| Highest Turnover | 417.1262 |
| Lowest Turnover | 0.4963 |
| Slow-Moving Records | 8 |
| Missing Values | 0 |
| Duplicate Records | 0 |

### 7. Category-wise Analysis

| Category | Average Turnover |
|---|---:|
| Electronics | 32.52 |
| Furniture | 31.70 |
| Accessories | 31.31 |
| Clothing | 28.88 |

**Observation:** Electronics recorded the highest average inventory turnover, while Clothing recorded the lowest.

### 8. Key Learnings
- Understanding inventory management analytics.
- Working with real-world supply chain data.
- Calculating inventory turnover ratios using Python.
- Performing category-wise comparisons.
- Identifying potentially slow-moving inventory.
- Creating data visualizations.
- Exporting analytical results.

### 9. Conclusion
Successfully completed the Inventory Turnover Analysis project using Python. The analysis helped evaluate inventory performance, compare product categories, and identify records that may require further inventory management attention.

### 10. Project Files
- `Day19_Inventory_Analysis.ipynb`
- `Inventory_SupplyChain_Dataset.csv`
- `Day19_Inventory_Analysis_Result.csv`
- `Day19_Category_Turnover.csv`
- `README.md`

---

**Internship Organization:** Veda Technology

**Project:** Day 19 – Inventory Turnover Analysis
