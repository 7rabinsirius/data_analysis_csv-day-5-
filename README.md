# csv_pandas-day-5-
# 📊 Sales Data Analysis with Pandas & Matplotlib

## Overview
This project performs exploratory data analysis on a dataset titled **"100 Sales Records"**, using Python libraries such as **pandas** and **matplotlib**. The primary goal is to derive business insights from sales records by summarizing revenue, profit, and product performance, and by visualizing key metrics.

---

## 🔧 Tools & Technologies
- **Python 3.x**
- **Pandas** for data manipulation
- **Matplotlib** for data visualization
- Jupyter Notebook or any Python IDE

---

## 🧪 Dataset Details
The dataset contains 100 entries with the following key columns:

- `Region`
- `Country`
- `Item Type`
- `Sales Channel`
- `Order Priority`
- `Order Date`
- `Order ID`
- `Ship Date`
- `Units Sold`
- `Unit Price`
- `Unit Cost`
- `Total Revenue`
- `Total Cost`
- `Total Profit`

---

## 📈 Operations Performed

1. **Data Loading & Initial Exploration**
   - Read CSV with `pandas.read_csv()`
   - Inspected data using `.head()`, `.info()`, and `.describe()`

2. **Missing Value Handling**
   - Identified and removed `NaN` values using `dropna()`

3. **Aggregated Insights**
   - **Total Revenue by Item Type**
   - **Total Revenue by Region**
   - **Top 10 Countries by Total Profit**
   - **Most Sold Item Types**

4. **Visualization**
   - Bar chart of **Total Revenue by Product Type**

---

## 📊 Key Results
- The item types generating the highest revenue were identified.
- The regions and countries with the highest sales and profit figures were highlighted.
- A plot showcasing revenue contributions by product type was generated using `matplotlib`.

---

## 📁 How to Run
1. Clone the repository or download the notebook.
2. Make sure you have `pandas` and `matplotlib` installed:
   ```bash
   pip install pandas matplotlib


- Run the script in a Jupyter Notebook or Python environment.
- Ensure 100 Sales Records.csv is in the working directory.
