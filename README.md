# 📊 Sales Dashboard Project (Python + Power BI)

## 🚀 Project Overview
This project demonstrates an **end-to-end Data Science and Business Intelligence workflow**.  
I started with a raw Kaggle dataset (Amazon sales), performed **data cleaning in Python**, and built an **interactive dashboard in Power BI**.  
The dashboard highlights sales performance, product insights, and geographical trends.

## 📂 Project Workflow

### 1. Data Collection
- Source: [Kaggle – Amazon Sales Dataset](https://www.kaggle.com/)  
- Records: ~120K orders, 22 columns (order details, shipping, sales channels, etc.) for the year 2022

### 2. Data Cleaning (Python – Jupyter Notebook)
- Removed null values & dropped unnecessary columns  
- Standardized column names  
- Converted datatypes (date → datetime, qty → int, amount → float)  
- Created `total_sales = qty * amount`  
- Added time-based features: `year`, `month`, `day`
- 
### 3. Dashboard Development (Power BI)
- Imported cleaned dataset (`cleaned_sales_data.csv`)  
- Created DAX measures:  
  - `Total Sales`  
  - `Total Quantity`  
  - `Order Count`  
  - `Average Order Value`  
- Built a dashboard:  
  - **Sales Overview** – KPIs, sales trend, sales by category, channel split   
  - **Product Insights** – Top SKUs, category vs style analysis 

## 📊 Dashboard Preview
"Amazon Sales Dashboard.pbix"

## 🛠️ Tools & Technologies
- **Python (Pandas)** – Data Cleaning & EDA  
- **Power BI (DAX, Visualizations)** – Dashboard
