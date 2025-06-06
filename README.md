# DATA-ANALYST-INTERNSHIP-TASK-7-Get-Basic-Sales-Summary-from-a-Tiny-SQLite-Database-using-Python
# 🧾 Sales Analysis from CSV using Python (Task 7)

## 📌 Objective:
Analyze sales data from a CSV file to calculate total units sold and total revenue per product, region, and payment method using Python. Also, visualize the top 5 products by revenue using a bar chart.

---

## 🗂 Dataset Description:
**File Name:** `sales.csv`  
**Columns Used:**
- Transaction ID
- Dates
- Product Category
- Product Name
- Units Sold
- Unit Price
- Total Revenue
- Region
- Payment Method

---

## ⚙️ Tools & Technologies:
- Python 🐍
- pandas 🐼
- matplotlib 📊
- Jupyter Notebook or .py file

---

## 📈 Analysis Performed:

### ✅ Step-by-Step Tasks:
1. Imported the CSV file using `pandas`
2. Cleaned the column names (converted to lowercase and replaced spaces with underscores)
3. Calculated `total_revenue` if not already present
4. Grouped data to calculate:
   - Total units sold and total revenue **per product**
   - Total sales **per region**
   - Total revenue **per payment method**
5. Identified **Top 5 Products** based on revenue
6. Plotted a **bar chart** to visualize top products
7. Saved the chart as `top_5_products_revenue_chart.png`

---

## 📊 Output Charts:
- `top_5_products_revenue_chart.png`: Bar chart showing the top 5 revenue-generating products.

---

## 📦 Output Summary:
- Product-wise sales summary
- Region-wise sales summary
- Payment method revenue breakdown
- Top 5 products by total revenue

---

## 📄 How to Run:
1. Place `sales.csv` and the Python script or Jupyter notebook in the same folder.
2. Run the script or open the notebook and execute cells step by step.
3. Check the terminal output and chart image generated.

---

## ❓ Interview Questions & Answers:

| Question | Answer |
|---------|--------|
| How did you load the data? | Using `pandas.read_csv("sales.csv")` |
| How did you clean column names? | Used `df.columns.str.strip().str.lower().str.replace(" ", "_")` |
| How did you calculate revenue? | `units_sold * unit_price` |
| How did you group the data? | Using `groupby()` and `agg()` functions in pandas |
| How did you visualize the data? | Used `matplotlib.pyplot` to create a bar chart |
| What does `groupby()` do? | It groups rows based on a column and allows aggregation like sum or average |
| Why use pandas? | It simplifies data loading, cleaning, and analysis in tabular format |
| What is the benefit of this analysis? | It helps identify top-selling products, regions with high sales, and preferred payment methods |

---

## 📂 Files Included:
- `sales.csv` — Source dataset
- `sales_analysis.py` or `.ipynb` — Python code
- `top_5_products_revenue_chart.png` — Visualization output
- `README.md` — Project description and guide

---



---
