This README file is designed to provide a clear, professional overview of your project for anyone reviewing your portfolio. It highlights your end-to-end data process, from raw data cleaning to the final executive insights.

***
# Mobile Sales Performance Analytics Dashboard

## 📌 Project Overview
This project provides a comprehensive analysis of mobile phone sales across major Indian markets. By transforming raw sales data into an interactive Power BI dashboard, the project identifies key revenue drivers, brand performance tiers, and customer behavior patterns to support data-driven decision-making.

## 📁 Repository Structure
*   **Raw Data (Excel):** Contains the original dataset including transaction dates, brand names, mobile models, payment methods, and customer ratings.
*   **Power BI File (.pbix):** The core application containing the data model, Power Query transformations, and interactive visualizations.
*   **Sales Dashboard Portfolio.pdf:** A static export of the final dashboard for quick viewing.
*   **Mobile_Sales_Performance_Report.pdf:** An executive summary detailing strategic insights and actionable recommendations derived from the data[cite: 2].

## 🛠️ Data Transformation (Power Query)
Before visualization, the raw data underwent a rigorous **ETL (Extract, Transform, Load)** process within Power Query to ensure accuracy:
*   **Data Cleaning:** Handled missing values and removed duplicates to maintain transaction integrity.
*   **Type Conversion:** Standardized date formats and currency types for accurate time-series analysis and financial calculations.
*   **Attribute Standardization:** Normalized Brand and Model names to prevent fragmentation in visuals (e.g., ensuring "Apple" and "apple" are categorized together).
*   **Calculated Columns:** Created custom time-based attributes (Day Name, Month, Quarter) to enable the "Total Sales by Day Name" and "MTD" (Month-To-Date) tracking[cite: 1].

## 📊 Key Dashboard Features
*   **Sales Scorecard:** Real-time tracking of Total Sales (769M), Quantity (19K), and Average Transaction Value (40K)[cite: 1, 2].
*   **Brand Competition:** A comparative table and bar chart showcasing the tight race between Apple (161.6M) and Samsung (160M)[cite: 1].
*   **Temporal Trends:** Line charts mapping sales fluctuations by month and specific growth tracking between 2021 and 2024[cite: 1].
*   **Geographic Mapping:** A bubble map visual showing sales concentration in hubs like Delhi, Bangalore, and Mumbai[cite: 1].
*   **Customer Sentiment:** A funnel analysis of customer ratings, highlighting the 1.5K segment of "Poor" or "Average" feedback for targeted improvement[cite: 1, 2].

## 💡 Strategic Insights
The analysis revealed that while growth is strong (**33.98%**), there are significant opportunities to optimize mid-week sales (Wednesdays and Thursdays) and address customer satisfaction gaps to reduce churn[cite: 2].

***

**Tools Used:** Power BI, Power Query, Excel, DAX.
