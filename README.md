# Swiggy Order Data Analysis (SQL | PostgreSQL | Excel)

![SWIGGY](https://github.com/Sameer2615/Swiggy_Order_Data_Analysis/blob/main/Swiggy.png)

This project analyzes **197,000+ Swiggy food delivery records** using **PostgreSQL (PGAdmin4)** and **Excel** to uncover insights about customer behavior, restaurant performance, pricing trends, and food category patterns.

## 📌 Project Overview
The goal of this analysis is to understand key business metrics such as revenue trends, order frequency, top-selling dishes, high-performing restaurants, and rating-price relationships using both **SQL queries** and **Excel visuals**.

## 📂 Dataset
- Source file: `Swiggy_Data_Analysis.xlsx`  
- Total Rows: **197,430**  
- Columns include: State, City, Order Date, Category, Dish Name, Food Type, Price (INR), Rating, Rating Count, etc.  
- Data was cleaned and categorized (Veg/Non-Veg) before analysis.

## 🛠 Tools & Technologies
- **PostgreSQL / PGAdmin4**
- **SQL (Aggregations, Grouping, Window Functions)**
- **Microsoft Excel (Pivot Tables, Charts, Slicers, Dashboard)**
- **Data Cleaning & Transformation**

## 🔍 Key Analysis Performed

### SQL Analysis
- Total orders, total revenue, and AOV  
- Monthly & weekly order trends  
- Top restaurants by revenue & volume  
- Most ordered dishes  
- Rating distribution & % of high-rated orders  
- Price–rating relationship  
- Category-wise revenue contribution  
- Veg vs Non-Veg ordering pattern  
- Pareto (80/20) revenue analysis  

SQL queries used are available in the file:  
📄 **`Swiggy_Order_Insights.sql`**

### Excel Analysis
- Cleaned, categorized, and structured data for reporting  
- Built pivot tables for:
  - Monthly revenue  
  - AOV by food category  
  - Rating distribution  
  - Top restaurants  
- Created visual charts and slicers for dynamic exploration  
- Developed an **interactive dashboard** summarizing:
  - High-demand categories  
  - Rating–price patterns  
  - Restaurant performance  
  - Revenue trends
 
## 📷Dashboard Preview
<img width="1905" height="777" alt="Sales Dashboard (2)" src="https://github.com/Sameer2615/Swiggy_Order_Data_Analysis/blob/main/dashboard.png" />
---  

## ⭐ Key Insights
- Weekends showed the highest order spikes.  
- Top 20% of restaurants contributed to nearly **80% of total revenue**.  
- Non-Veg dishes dominated total sales volume.  
- Higher-priced dishes did **not always** correlate with higher ratings.  
- Certain categories consistently maintained better customer satisfaction.

## 🚀 How to Run

### 1. PostgreSQL
Import CSV or Excel → Run SQL queries from `Swiggy_Order_Insights.sql`.

### 2. Excel
Open the workbook → Navigate through Pivot Tables & Dashboard.

## 📁 Project Structure
```
├── Swiggy_Data_Analysis.xlsx
├── Swiggy_Order_Insights.sql
├── Dashboard/
│   └── Swiggy_Dashboard.png (optional)
└── README.md
```

## 👤 Author
**Sameer Bhatt**  
Email: sameerbhatt2058@gmail.com  
