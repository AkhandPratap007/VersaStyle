# Sales Data Analysis and Forecasting in Power BI

## 📌 Project Overview
This project focuses on analyzing sales data using Power BI.  
The workflow includes:
1. Data Cleaning – ensuring consistency and accuracy in the raw dataset.  
2. Data Transformation – preparing and shaping the dataset for meaningful analysis.  
3. Exploratory Analysis – building interactive visuals to understand sales trends and patterns.  
4. Forecasting – leveraging Power BI’s Analytics → Forecasting option to predict sales for the next 30 days using a line chart.

---

## 🛠️ Steps Performed

### 1. Data Cleaning
- Removed duplicate rows.  
- Handled missing values by replacing them with appropriate measures (mean, mode, or interpolation).  
- Standardized column names (e.g., `Order Date`, `Sales`, `Region`).  
- Corrected inconsistent entries in categorical fields like product categories and regions.

### 2. Data Transformation
- Converted date columns into proper `Date` format.  
- Created new calculated columns:
  - Month-Year (for time-based analysis).  
  - Profit Margin % = `(Profit / Sales) * 100`.  
- Aggregated sales by region, category, and time period.  
- Applied DAX measures for KPIs:
  - `Total Sales`
  - `Total Profit`
  - `Average Order Value`

### 3. Visualization
Key visuals included:
- Bar Charts → Sales by region and category.  
- Pie Charts → Contribution of product categories to total sales.  
- KPIs Cards → Showing revenue, profit, and growth %.  
- Trend Line Graphs → Monthly sales performance.

### 4. Forecasting (30 Days)
- Used the Line Chart visualization with the `Analytics` pane.  
- Enabled the Forecasting option → set horizon to 30 days.  
- Power BI applied time-series forecasting (exponential smoothing) to predict upcoming sales.  
- The forecast line was shown along with confidence intervals for reliability.

---

## 📊 Insights & Outcomes
- Identified top-performing regions and categories.  
- Observed seasonal trends in sales (monthly and quarterly spikes).  
- Predicted a **30-day upward/downward trend** in sales to support decision-making.  

---

## 🚀 Tools & Technologies
- Power BI Desktop 
- DAX (Data Analysis Expressions) 
- Data Modeling & Relationships  
- Forecasting (in-built analytics)  
<img width="1262" height="710" alt="project5" src="https://github.com/user-attachments/assets/37777261-452c-457b-b48f-4edcac6bd3b1" />



<img width="1252" height="704" alt="Screenshot 2025-08-18 025000" src="https://github.com/user-attachments/assets/d5402dd1-838b-459f-af05-7fc878b08c90" />



