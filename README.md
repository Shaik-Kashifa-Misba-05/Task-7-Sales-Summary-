# 🛒 Task 7: Basic Sales Summary using SQLite and Python


### ✅ Objective:
The goal of this task was to use **SQL within Python** to generate a basic sales summary from a tiny SQLite database and visualize key insights using **matplotlib**.

---

## 🧰 Tools Used:
- Python
- SQLite (via `sqlite3`)
- pandas
- matplotlib
- Jupyter Notebook

---

## 🗃️ Dataset:
A custom SQLite database named `sales_data.db` was created manually. It contains one table `sales` with the following columns:
- `sale_id` (INTEGER)
- `product` (TEXT)
- `category` (TEXT)
- `region` (TEXT)
- `quantity` (INTEGER)
- `price` (REAL)
- `sale_date` (TEXT)

The database contains 15 sample sales records across different products, categories, regions, and dates.

---

## 📊 Queries Performed:

1. **Total Revenue per Product**  
   → Used `GROUP BY` on `product` to calculate total quantity and revenue.  
   → Visualized using a bar chart.

2. **Total Quantity Sold per Region**  
   → Aggregated quantity by region to find the most active regions.  
   → Visualized using a bar chart.

3. **Total Revenue per Category**  
   → Calculated category-wise revenue using SQL aggregation.  
   → Visualized using a green bar chart.

4. **Daily Sales Summary**  
   → Analyzed `sale_date` wise total quantity and revenue.  
   → Visualized using a line chart.

---

## 📈 Visualizations:
All queries were visualized using `matplotlib` with:
- Bar charts for product, region, and category summaries.
- Line chart for daily trends.

---

## 📂 Files Included:
- `sales_data.db` – SQLite database file  
- `task7_sales_summary.ipynb` – Jupyter notebook    
- `README.md` – This file  

---

## ✅ Outcome:
- Learned to write and execute SQL inside Python.
- Created and queried a SQLite database.
- Visualized data insights with basic plots.
- Practiced end-to-end data analysis workflow.

