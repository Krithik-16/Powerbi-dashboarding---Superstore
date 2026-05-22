# Superstore Sales & Strategy: End-to-End Data Analysis
### *Interactive Power BI Business Intelligence Solution*

## Project Overview
This repository showcases a comprehensive data analytics workflow—from raw data ingestion to executive-level visualization. Using the Global Superstore dataset, I developed a dynamic Power BI solution that identifies key performance drivers, customer behavior patterns, and regional profitability trends to support data-driven decision-making.

## Key Features & Functionality
* **Dynamic Sales Tracking:** Visualizes revenue trends over time with year-over-year comparisons.
* **Customer Segmentation:** Deep-dive analysis into Consumer, Corporate, and Home Office segments to identify high-value targets.
* **Regional Performance Mapping:** Interactive geospatial analysis identifying top-performing cities and underperforming territories.
* **Profitability Analysis:** Evaluation of product categories (Technology, Office Supplies, Furniture) to pinpoint margin leakage.

## Technical Stack & Data Architecture
* **Data Modeling:** Implemented a **Star Schema** by connecting `Orders`, `People`, and `Returns` tables to ensure optimized query performance.
* **DAX (Data Analysis Expressions):** Engineered custom measures for:
    * *Profit Margin %*
    * *Total Returns Impact*
    * *Average Sales per Customer*
* **Power Query (M):** Performed ETL processes including data profiling, handling null values, and data type standardization for 9,000+ rows of transactional data.

## 📊 Dashboard Preview
### 1. Sales Performance Overview (Page 1)
*A high-level view of Sales, Profit, and Quantity across different product sub-categories.*

### 2. Market Segmentation & Trends (Page 2)
*Detailed analysis of customer acquisition trends and segment-specific revenue growth.*

## 📈 Key Insights Found
* **Technology Leadership:** The Technology category consistently delivers the highest profit margins despite lower transaction volumes.
* **Return Rates:** Identified specific sub-categories with high return rates (e.g., Furniture), suggesting a need for quality control or description updates.
* **Regional Variance:** While the West region shows high total sales, profit margins are significantly impacted by shipping costs in certain states.
