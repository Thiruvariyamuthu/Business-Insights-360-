# 📊 Business Insights 360 – Power BI Project for AtliQ Hardwares

A business intelligence project that empowers AtliQ Hardwares to make strategic decisions using data from Finance, Sales, Supply Chain, and Marketing departments. Built with Power BI, SQL, and Excel.

---

### 🟡 Situation
AtliQ Hardwares, a consumer electronics company, is expanding rapidly but lacks a centralized system for data analysis. 
Business decisions were being made based on assumptions, resulting in inefficiencies in various departments, especially in new markets like Latin America and APAC.

### 🟠 Task
As a data analyst, I was tasked with building an end-to-end BI solution that would:
- Integrate data from multiple departments and sources
- Highlight performance issues and growth opportunities
- Present actionable insights to stakeholders through a clear and interactive dashboard

### 🔵 Action
- Collected data from MySQL and Excel files (Sales, Manufacturing, Forecast, Expenses, Market Share, etc.)
- Cleaned and transformed data using Power Query and SQL views
- Designed a star schema data model with proper relationships
- Created DAX measures for KPIs like Net Sales, Profit Margin, Forecast Accuracy, etc.
- Built five dashboards: Finance, Sales, Supply Chain, Marketing, Executive Overview
- Added bookmarks, slicers, and navigation for user-friendly interaction

### 🟢 Result
- Delivered a comprehensive Power BI dashboard enabling business leaders to:
  - Monitor key metrics like Gross Margin %, Forecast Error, and Market Share
  - Identify underperforming divisions and cost centers
  - Improve supply chain operations in LATAM and APAC
  - Make better budgeting and expansion decisions

---

## 📁 Data Sources

| Source | Table | Description |
|--------|-------|-------------|
| MySQL  | Fact_Sales_Monthly | Actual monthly sales |
| MySQL  | Fact_Manufacturing_Cost | Cost to manufacture |
| MySQL  | Fact_Forecast_Monthly | Forecast data |
| MySQL  | Fact_Freight_Cost | Logistics cost |
| Excel  | Market_Share | Regional share by competitors |
| Excel  | Target | Department sales targets |

###Data Model Diagram

The data model integrates multiple fact and dimension tables to support comprehensive business analysis.
![Data Modeling](https://raw.githubusercontent.com/Thiruvariyamuthu/Business-Insights-360-/main/DataModeling.png)


---

## 📈 Key Dashboards

1. **Finance** – Profit & Loss, Net Profit %, Margin Analysis  
2. **Sales** – Top customers/products, performance vs targets  
3. **Marketing** – Operational expense impact, ROI by division  
4. **Supply Chain** – Forecast accuracy, regional logistics  
5. **Executive Summary** – High-level overview for CXOs  

---

## 💡 Top Insights

- 📉 Profit shrinking despite sales growth → Cost issues identified  
- 🌍 LATAM has poor forecast accuracy and high freight costs  
- 📢 Gaming division underperforming in APAC despite high expenses  
- 📦 Supply chain bottlenecks leading to delivery delays  
- 📈 Market share increasing but not reflected in profit  

---

## 🧰 Tools & Skills Used

- **Power BI** – Data modeling, DAX, visuals, navigation
- **SQL** – Views, joins, aggregations
- **Excel** – Targets, operational costs, market share
- **ETL** – Power Query for cleaning and transformation
- **Data Storytelling** – Insight-driven dashboards for business users

---

## 📎 Links

- 🔗 [Power BI Dashboard (PDF/Image)](#) *(Insert link)*
- 🎬 [Walkthrough Video](#) *(Insert link if available)*
- 💼 [LinkedIn Project Post](#) *(Optional)*

---

## 🙌 Acknowledgments

Special thanks to **CodeBasics Bootcamp** for guidance, and the AtliQ Hardware case study for practical learning.

---

📌 *If you found this project helpful, consider starring the repo and following for more insights!*
