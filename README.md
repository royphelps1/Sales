# 🚚 Power BI Semantic Model – Sales Delivery Dashboard

This project demonstrates a semantic model and dashboard built in Power BI using curated data tables from a data lakehouse. It showcases best practices in dimensional modeling, DAX, and data visualization for supply chain and customer delivery performance analytics.

---

## 📁 Data Sources

This model is built using gold-layer tables from a curated data lakehouse or Power Platform dataflow, including:

- `fact_SalesDelivery` – measures delivery volumes and performance
- `dim_Customer` – customer metadata and groupings
- `dim_Item` – product master data
- `dim_Location` – delivery/shipping locations
- `dim_Date` – custom date table with full hierarchy support

---

## 🌟 Semantic Model Highlights

- **Star Schema** with clear fact/dimension separation
- **Friendly Naming** conventions for all fields
- **Calculated Measures** using DAX for:
  - Total Order Amount
  - Total Quantity Delivered
  - Good Delivery %
  - Average Delivery Score
- **Time-Series Visualization** powered by `dim_Date`
- **Bar Charts, Line Charts, KPI Cards, and Matrices** for business insight
- Hidden system columns and surrogate keys to simplify the data model

---

## 📊 Sample Visuals Included

- **Top 10 Items by Order Amount** (Bar Chart)
- **Order Trends Over Time** (Line Chart)
- **Customer Delivery Summary** (Matrix)
- **Good Delivery %** (KPI Card)

---

## 🛠️ Tools Used

- Power BI Desktop
- Power Query / M Language
- DAX
- Dataflows / Lakehouse Integration

---

## 💼 Business Use Case

This dashboard supports logistics, operations, and customer service teams in:
- Monitoring delivery performance
- Identifying high-volume customers and products
- Tracking trends and seasonal patterns in deliveries
- Improving fulfillment quality over time

---



