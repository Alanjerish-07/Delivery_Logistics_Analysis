# 🚚 Delivery Logistics Data Analytics

### Analyzing Delivery Performance, Logistics Costs & Operational Trends

![Project](https://img.shields.io/badge/Project-Data%20Analytics-blue)
![Dataset](https://img.shields.io/badge/Dataset-9%2C999%20Records-orange)
![Power BI](https://img.shields.io/badge/Visualization-Power%20BI-yellow)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview

The **Delivery Logistics Data Analytics** project focuses on analyzing delivery operations to identify meaningful patterns, understand cost variations, and evaluate delivery performance.

The project uses Exploratory Data Analysis (EDA), data cleaning, statistical analysis, and interactive dashboard visualizations to transform raw delivery data into useful business insights.

## 🎯 Project Objectives

- Analyze delivery volume across different delivery partners.
- Understand delivery costs and distance patterns.
- Compare delivery modes, vehicle types, and package categories.
- Identify regional delivery cost variations.
- Explore the relationship between delivery distance and delivery cost.
- Develop an interactive Power BI dashboard.
- Provide data-driven business recommendations.

## 📂 Dataset Information

| Description | Details |
|---|---|
| Dataset Name | Delivery Logistics Analysis |
| Total Records | 9,999 |
| Total Columns | 13 |
| Missing Values | 0 |
| Exact Duplicate Rows | 0 |
| Domain | Logistics & Supply Chain |

### Dataset Columns

1. `delivery_id`
2. `delivery_partner`
3. `package_type`
4. `vehicle_type`
5. `delivery_mode`
6. `region`
7. `weather_condition`
8. `distance_km`
9. `package_weight_kg`
10. `delivery_status`
11. `delivery_rating`
12. `delivery_cost`
13. `cost_per_km`

## 🛠️ Tools & Technologies

- **Microsoft Excel:** Data inspection, cleaning, and preparation.
- **Python:** Data analysis and exploratory data analysis.
- **Pandas:** Data manipulation and processing.
- **Matplotlib:** Data visualization.
- **Power BI:** Interactive dashboard development.
- **GitHub:** Project documentation and version control.

## 🔄 Project Workflow

1. **Data Collection:** Obtained the delivery logistics dataset.
2. **Data Understanding:** Examined dataset structure, rows, columns, and data types.
3. **Data Cleaning:** Checked missing values, duplicate records, and inconsistent categories.
4. **Exploratory Data Analysis:** Analyzed numerical and categorical variables.
5. **Data Visualization:** Created charts to identify patterns and trends.
6. **Power BI Dashboard:** Designed an interactive logistics dashboard.
7. **Insights & Recommendations:** Interpreted results and suggested improvements.

## 📊 Key Performance Indicators (KPIs)

| KPI | Result |
|---|---:|
| Total Deliveries | 9,999 |
| Average Delivery Cost | 809.32 |
| Average Distance | 141.32 km |
| Average Package Weight | 25.07 kg |
| Average Customer Rating | 4.74 / 5 |

*Cost values are shown in the dataset's numeric units; the currency was not specified.*

## 📈 Key Visualizations

The project includes the following visual analyses:

1. Delivery Volume by Partner
2. Delivery Cost by Region
3. Delivery Mode Distribution
4. Delivery Cost by Weather Condition
5. Delivery Cost by Package Type
6. Delivery Distance vs Delivery Cost
7. Delivery Status Distribution
8. Vehicle Type Analysis
9. Customer Rating Analysis
10. Average Cost per Kilometre

## 💡 Key Insights

- Blue Dart has the highest delivery record count in the dataset.
- Standard delivery is the most frequently recorded delivery mode.
- Central region has the highest number of delivery records.
- Hot weather has the highest average delivery cost among the recorded weather categories.
- Delivery distance and delivery cost have a very strong positive correlation (approximately 0.990).
- Same-day delivery has a higher average cost per kilometre than standard and two-day delivery in this dataset.
- Some cost-per-kilometre values require further investigation.

## 💼 Business Recommendations

- Monitor delivery costs across different partners and regions.
- Review unusually high cost-per-kilometre records.
- Compare delivery partners using similar distance and package-weight groups.
- Improve delivery cost monitoring and reporting.
- Collect complete delivery status and timestamp information.
- Track customer feedback across the full rating scale.

## ⚠️ Dataset Limitations

- All 9,999 records have a delivered status.
- Customer ratings are limited to 4 and 5.
- Delay and failure rates cannot be reliably calculated from this dataset.
- Currency information is not provided.
- Statistical outliers require business validation before removal.

These limitations should be considered when interpreting the results.

## 📁 Project Structure

```text
Delivery-Logistics-Data-Analytics/
│
├── Dataset/
│   └── Delivery_Logistics_Analysis.csv
│
├── Dashboard/
│   └── Delivery_Logistics_Dashboard.pbix
│
├── Visualizations/
│   ├── delivery_partner.png
│   ├── delivery_mode.png
│   ├── region_cost.png
│   └── distance_cost.png
│
├── Report/
│   └── Delivery_Logistics_Analytics_Report.pdf
│
└── README.md
```

*Update the folder and file names to match the actual files in your GitHub repository.*

## 🏁 Conclusion

This project demonstrates how data analytics can help understand logistics operations through data cleaning, exploratory analysis, visualization, and business intelligence.

By analyzing 9,999 delivery records, the project identifies important patterns in delivery volume, cost, distance, delivery modes, and regional performance.

The Power BI dashboard provides a clear view of logistics data and supports better data-driven decision-making.

## 👨‍💻 Author

**Alanjerish A**

Aspiring Data Analyst | BCA Graduate

Interested in Data Analytics, Business Intelligence, Python, SQL, Excel, and Power BI.


