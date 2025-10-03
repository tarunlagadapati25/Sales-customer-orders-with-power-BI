# Sales-customer-orders-with-power-BI

# Sales Performance Analysis Dashboard

This repository contains the analysis and visualization of sales data for a retail company. The project utilizes a comprehensive **Power BI dashboard** to track key performance indicators (KPIs) and uncover insights across various business dimensions, including product performance, regional sales, customer behavior, and temporal trends.

---

## 📈 Dashboard Overview
The interactive dashboard provides a multi-faceted view of the company's sales performance. Stakeholders can drill down into specifics, from high-level yearly trends to individual product profitability.


---

## 🔑 Key Insights & Findings

### Profitability by Product Category
- **Furniture** is the most profitable category, contributing **28.02%** of total profit.
- Followed by **Electronics (25.91%)** and **Food & Beverages (23.67%)**.
- Total sales are evenly distributed across categories, but profit contributions vary, highlighting differences in margins.

### Regional Performance
- Profit distribution across regions is balanced:
  - East: **28.4%**
  - North: **24.79%**
  - South: **24.16%**
  - West: **22.65%**
- No single region drastically underperforms.

### Sales Trends Over Time
- Daily sales show high volatility, typical for retail.
- Significant sales peak around **January 2024**, possibly due to a seasonal spike or marketing campaign.

### Customer Analysis
- **Top customers by sales volume**: Customer **C1430** leads.
- High-spending customers are not always the most profitable, as shown by variability in profit per customer.

### Pricing Anomaly
- A sharp decrease in **UnitPrice** from 2023 to 2024 is observed.
- Requires investigation: potential data issues, product mix changes, or new pricing strategies.

---

## 📊 Dashboard Visualizations
The dashboard includes multiple pages and visual types:

- **Time Series Line Chart:** Tracks daily Sum of TotalSales to observe trends and outliers.
- **Donut & Bar Charts:** Compare Sum of Profit across ProductCategory and Region.
- **100% Stacked Bar Chart:** Shows profit contribution by category within each region.
- **Treemap:** Hierarchical view of TotalSales and Profit across products.
- **Geospatial Map:** Displays states with sales activity across the U.S.
- **Scatter Plot:** Explores relationship between Profit and TotalSales.
- **Detailed Table:** Provides granular data per ProductName.

---

## 🛠️ Data Model & Metrics

### Measures (KPIs)
- **Sum of TotalSales:** Total revenue.
- **Sum of Profit:** Total profit earned.
- **Count of OrderID:** Number of unique orders.
- **Average of Profit:** Average profit per order.
- **Sum of UnitPrice:** Total unit prices of items sold.

### Dimensions
- **Product:** ProductCategory, ProductName
- **Geography:** Region, State
- **Time:** Year, Quarter, Month, Day
- **Customer:** CustomerID

---

## 💻 Technology Stack
- **Business Intelligence Tool:** Microsoft Power BI

---

## 🚀 How to Use
1. Clone this repository:
    ```bash
    git clone <repository_url>
    ```
2. Open the `.pbix` file using **Power BI Desktop**.
3. Configure your data source connections.
4. Refresh the dataset to view the latest data.
5. Interact with the slicers and visuals to explore insights.

---

*Created with ❤️ for insightful sales analytics.*
