# Sales Management Dashboard - Sano y Fresco

![Power BI](https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=Power%20BI&logoColor=white)

A Power BI dashboard to monitor, analyze, and optimize annual sales performance for **Sano y Fresco**, providing insights into revenue, customer behavior, and product category performance.

---

## 📌 Overview

### Objective
Develop an interactive Power BI dashboard to track key sales metrics, visualize trends, and identify top-performing/underperforming products and categories for informed decision-making.

### Scope
The dashboard includes:
- Monthly sales and customer data visualization.
- Sales trend analysis.
- Product/category performance highlights.
- Interactive filters for granular insights.

---

## 🚀 Features

### 📊 Key Metrics (KPIs)
- **Total Sales**: Annual revenue.
- **Total Customers**: Unique customers per year.
- **Average Order Value**: Avg. spending per order.
- **Average Customer Spending**: Avg. spending per customer.

### 📈 Sales Trends
- **Monthly Sales Bar Chart**: Track monthly revenue in millions of euros.

### 🛒 Product Analysis
- **Unique Products per Order**: Avg. distinct products per order.
- **Average Quantity per Item**: Avg. units per product type.

### 🏆 Top Performers
- **Product Sales Table**: Top-selling products by revenue.
- **Units Sold Treemap**: Visualize units sold per product category.

### 🔍 Interactive Filters
- **Month Filter**: Drill down into monthly data.
- **Product Category Filter**: Segment by category (beverages, creams, fruits, herbs, etc.).

---

## 📂 Data Sources
1. **Tickets Table**: Sales and customer data from the company's commercial database.
2. **secciones.xlsx**: Product category metadata (Excel file).

---

## 🛠️ Setup & Usage

### Prerequisites
- Power BI Desktop installed.
- Access to the `Tickets` table and `secciones.xlsx` file.

### Steps
1. **Import Data**:
   - Connect Power BI to the `Tickets` table (database) > download https://drive.google.com/file/d/1FPRBiIH5mPd0aOy1T3ve5_jv3rJvpMWn/view
   - Load `secciones.xlsx` for product category metadata.
2. **Data Modeling**:
   - Establish relationships between tables.
3. **Build Visualizations**:
   - Use the provided [DAX queries](#) (link to script if available) for KPIs.
   - Design charts and tables as outlined in [Features](#-features).
4. **Apply Filters**:
   - Add slicers for `Month` and `Product Category`.

---

## 🔧 Validation & Testing
- **Data Review**: Ensure completeness of sales/customer data.
- **Visualization Testing**: Confirm all charts meet requirements.
- **Performance Testing**: Optimize dashboard responsiveness.

---

## 💡 Technologies Used
- **Power BI**: Dashboard development and visualization.
- **Excel**: Metadata management.
- **DAX**: Data analysis expressions for metrics.

