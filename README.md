# BLINKIT-SALES-PERFORMANCE-ANALYSIS-USING SQL


## 📘 Project Overview
This project provides an in-depth **sales performance analysis** of Blinkit using **SQL**. 
The objective was to identify **key business insights** regarding product performance, customer preferences, and outlet-level efficiency.

---

## 🎯 Objectives
The main goals of the project were to:
- Analyze **total and average sales** across multiple categories.  
- Measure the **impact of product features** such as fat content and item type on sales.  
- Evaluate **outlet performance** based on establishment year, size, and location.  
- Assess **customer satisfaction** using product ratings.  

---

## 🧩 Dataset Description
The dataset used for analysis (`blinkit_data`) contains detailed transactional and categorical data from Blinkit’s retail operations.  
It includes the following key columns:

| Column | Description |
|--------|--------------|
| `Item_Fat_Content` | Indicates whether the product is *Low Fat* or *Regular* |
| `Item_Type` | Product category (e.g., dairy, snacks, frozen foods) |
| `Outlet_Establishment_Year` | Year when the outlet was opened |
| `Outlet_Size` | Size of the outlet (*Small*, *Medium*, *Large*) |
| `Outlet_Location_Type` | Type of outlet location (*Urban*, *Semi-Urban*, *Rural*) |
| `Outlet_Type` | Type of business outlet (*Supermarket Type 1*, *Grocery Store*, etc.) |
| `Total_Sales` | Total revenue generated from the item |
| `Rating` | Customer rating for the product |
| `Item_Visibility` | Visibility score of the item in the outlet |

---

## 🧹 Data Cleaning & Preparation
Data preprocessing was done using **SQL** to ensure data quality and consistency:
- Standardized inconsistent category names (e.g., “LF”, “low fat” → “Low Fat”).  
- Removed duplicates and missing records.  
- Verified data distribution for numeric fields like `Total_Sales` and `Rating`.  
- Ensured all categorical variables were uniform for accurate grouping and aggregation.

---

## 📊 Key KPIs Analyzed
1. **Total Sales** – Overall revenue generated across all products.  
2. **Average Sales** – Average revenue per transaction.  
3. **Number of Items Sold** – Count of unique items sold.  
4. **Average Rating** – Mean customer satisfaction score.  

Additional breakdowns were created to analyze:
- Total Sales by **Fat Content**  
- Total Sales by **Item Type**  
- Total Sales by **Outlet Establishment Year**  
- Sales percentage by **Outlet Size**  
- Sales by **Outlet Location Type**  
- Combined KPI view by **Outlet Type**

---

## 📈 Process Summary
1. **Data Extraction:** Imported the Blinkit dataset into SQL for analysis.  
2. **Data Cleaning:** Standardized categorical values and validated data quality.  
3. **KPI Calculation:** Computed key performance metrics using aggregate SQL queries.  
4. **Data Analysis:** Explored relationships between product and outlet characteristics.  

---

## 💡 Key Insights
- **Regular items** generated slightly higher sales than **Low Fat** items.  
- **Large outlets** contributed the highest percentage to overall revenue.  
- **Urban outlets** showed dominant sales performance compared to semi-urban and rural ones.  
- **Recently established outlets** demonstrated stronger sales trends, indicating successful expansions.  
- **Supermarket outlets** outperformed grocery stores across all key metrics.  
- **Customer ratings** were generally positive, correlating with higher sales volume.  

---

## 🏁 Conclusion
This project provided valuable insights into **Blinkit’s product and outlet performance**, enabling data-driven decision-making in:
- **Inventory management**  
- **Outlet expansion strategies**  
- **Product assortment optimization**  
- **Customer satisfaction improvement**


---

## 🧮 Tools & Technologies Used
- **Microsoft SQL Server** – Data processing and KPI computation  
- **Excel / CSV** – Raw data management  

---


---
