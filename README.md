# NYC Taxi Data Pipeline using Microsoft Fabric 🚖

This project showcases a complete data pipeline using Microsoft Fabric tools with 2024 NYC Yellow Taxi trip data.

## 🔧 Tools Used
- **Microsoft Fabric**
  - Data Lakehouse
  - Data Factory
  - Dataflow Gen2
  - Data Warehouse
  - Power BI

## 📁 Data Source
- **Trip Data (Parquet)**: Monthly yellow taxi trip records (Jan–May 2024)
- **Taxi Zone Lookup (CSV)**: Location info for pickup/drop-off zones

## 🛠️ What This Project Does
1. **Store Data** in a Fabric Lakehouse
2. **Copy Data** to a staging table using Data Factory pipelines
3. **Clean & Transform** using Dataflow Gen2 and stored procedures
4. **Load to Presentation Table** for analysis
5. **Log Metadata** (row counts, dates processed)
6. **Visualize in Power BI** with filters and key metrics

## 📊 Power BI Dashboard
Includes:
- Total revenue
- Trip counts
- Passenger count
- Filters: Date,Payment type

## 🧠 Key Insights
- Revenue increases from Jan to Mar 2024
- Most rides paid by credit card

## 📂 Files in This Repo
- Fabric pipeline JSON files
- Dataflow Gen2 definition
- Power BI report (.pbix)
