# ☕ Starbucks Sales Dashboard – Power BI Project

This project showcases an **interactive Power BI dashboard** built using real-world Starbucks sales data. It focuses on **sales insights, trends, top-performing categories**, and **visual storytelling** through clean and meaningful visualizations.

---

## 📌 Project Overview

After attending a Power BI webinar, I started building an initial version of the Starbucks Sales Dashboard.  
This project is the **enhanced and complete version**, incorporating data cleaning, transformation, visualization, and DAX-based analysis.

---

## 🔄 Workflow

### 1. Dataset Collection
- **Source:** Starbucks Raw Sales Data (CSV format)
- Contains: Order ID, Product Type, Category, Store Location, Quantity, Unit Price, Total Amount, Date, etc.

### 2. Data Cleaning
- Removed null values and duplicates
- Standardized column names and formatting
- Verified data types for each column

### 3. Data Transformation
- Performed in **Power Query Editor**
- Added new calculated columns
- Converted date fields to proper format for time-series analysis

### 4. Data Loading
- Loaded cleaned and transformed data into Power BI Data Model

### 5. DAX Measures Used
- `Total Sales = SUM(Sales[Total Amount])`
- `Average Order Value = [Total Sales] / DISTINCTCOUNT(Sales[Order ID])`
- `Total Quantity = SUM(Sales[Quantity])`
- `Top Category = CALCULATE(MAX(Sales[Category]), ...)`

---

## 📊 Dashboard Highlights

- **Total Quantity Sold:** 214K+  
- **Total Sales:** ₹58.87M  
- **Top-Selling Category:** Coffee – ₹2.27Cr+  
- **Visualizations:**
  - Card KPIs (Total Sales, AOV, Quantity)
  - Bar & Line Charts (Monthly Trends)
  - Donut Charts (Product Categories)
  - Slicers (Month, Category, Store Location)
  - Tooltips & Drill-down features

---

## 🛠️ Tools & Technologies

| Tool            | Purpose                         |
|-----------------|---------------------------------|
| Power BI        | Data visualization & dashboard  |
| Power Query     | Data transformation & shaping   |
| DAX             | Custom measures & calculations  |
| Excel / CSV     | Initial raw data format         |

---

## 💡 Key Learnings

- Hands-on experience with Power BI’s full workflow  
- Writing DAX to extract key business metrics  
- Structuring real-world datasets for reporting  
- Designing dashboards with storytelling intent  
- Improved visual design & layout practices

---

## 📽️ Demo Video

🎬 [Click here to watch the dashboard demo](#) *(Insert your video link)*

---

## 📁 Project Files

- 📊 `StarbucksDashboard.pbix` – Main Power BI report  
- 📄 `StarbucksSales.csv` – Cleaned dataset (sample)  
- 📝 `README.md` – This documentation

---

## 🙋‍♀️ About Me

I’m **Savitha L**, an aspiring Data Analyst passionate about turning raw data into actionable insights.  
Connect with me on [LinkedIn](https://www.linkedin.com/in/savitha-l-18a750282/) to learn and grow together!

---

## 📬 Feedback or Suggestions?

Feel free to raise issues or connect with me for any suggestions or improvements! 😊  
