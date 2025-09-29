# Sales Performance Dashboard – 2023  

This project demonstrates an end-to-end data pipeline and dashboard using **PySpark** for data cleaning and **Power BI** for visualization.  

---

## Steps  

### 1. Data Cleaning with PySpark  
- Standardized column names  
- Converted data types (int, double, date)  
- Removed nulls and duplicates  
- Exported cleaned dataset  

### 2. Data Visualization with Power BI  
- **Key KPIs**: Total Sales, Total Profit, Average Order Value, Profit Margin  
- **Trend Analysis**: Sales & Sales Growth % by Month  
- **Category & Region breakdowns**  
- **Matrix with sparklines** for detailed category-region performance  

---

## Tech Stack  
- **PySpark** - Data cleaning & transformation  
- **Power BI** - Data visualization & dashboard design  
- **GitHub** - Project version control & portfolio showcase  

---

## Data  

This project uses sales data that was cleaned and transformed using PySpark.  
For privacy and size reasons, the full dataset is not included in this repository.  

Instead, a sample dataset is provided in the `data/` folder:  

- `sample_sales_data.csv` – A small demo dataset (50 rows) with the same structure as the real data.  
- `data_dictionary.md` – Explains each column and its meaning.  

### Data Dictionary  
- `orderid` - Unique order identifier (integer)  
- `orderdate` - Date of the order (date)  
- `category` - Product category (Furniture, Office Supplies, Technology)  
- `subcategory` - Product subcategory (e.g., Chairs, Binders, Phones)  
- `region` - Sales region (East, West, North, South)  
- `quantity` - Number of units sold (integer)  
- `sales` - Total sales amount (currency, USD in this demo)  
- `profit` - Profit for the order (currency, USD in this demo)  

**Note:** This is a sample dataset only for demonstrating the PySpark cleaning pipeline and Power BI dashboard.  
The actual dataset used in the analysis contained more rows and business context.  

---

## Final Dashboard  

![Dashboard Screenshot](dashboard/dashboard_screenshot.png)  
<!-- Or, if screenshot is in the repo root:  
![Dashboard Screenshot](dashboard_screenshot.png) -->  

[Download Dashboard (PBIX file)](dashboard/sales_dashboard.pbix)  

---

## How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/panwarnalini-hub/sales-performance-dashboard.git
   Open the dataset in your environment (Jupyter, Databricks, or PySpark).
2. The PySpark scripts handle data cleaning (standardizing columns, converting data types, removing nulls and duplicates).
3. Export the cleaned dataset as instructed in the notebook/script.
4. Open the Power BI file:
5. Download the .pbix file from this repo.
6. Open it in Power BI Desktop.
7. Connect it to the cleaned dataset (CSV/Parquet).
8. Explore the dashboard:  
   Review KPIs, Sales Growth %, Regional and Category Trends.  
   Drill through to explore insights.
