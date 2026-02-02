# 🛒 Customer Behavior & Transactional Insights: End-to-End Analytics

## 📌 Project Executive Summary
This project delivers a comprehensive analysis of customer purchasing patterns and behavioral segmentation. By integrating **Python** for ETL, **SQL** for deep-dive querying, and **Power BI** for executive-level visualization, I developed a workflow to identify high-value customer segments and provide actionable recommendations to increase retention and lifetime value (LTV).

---

## 🛠️ Tech Stack & Methodology
* **Data Engineering (Python):** Architected a robust ETL pipeline to clean and transform raw datasets for production-ready analysis.
* **Database Management (SQL):** Migrated processed data to a relational database to simulate a corporate environment and performed complex aggregations.
* **Business Intelligence (Power BI):** Developed an interactive dashboard focusing on KPIs such as Average Order Value (AOV), churn risk, and seasonal trends.

---

## 🚀 Analytical Workflow

### 1. Data Processing & ETL (Python)
The initial phase focused on transforming raw, unstructured shopping data into a clean, normalized format.
* **Library Usage:** `Pandas` for manipulation, `SQLAlchemy` for database ingestion.
* **Key Tasks:** Data type normalization, handling missing values, and schema mapping for SQL migration.
* **Source File:** `Customer_Shopping_Behavior_Analysis.ipynb`

### 2. Strategic Analysis (SQL)
With the data hosted in a relational environment, I executed a series of business-critical queries to extract deeper insights.
* **Segmentation:** Identified loyalty tiers based on frequency and spend.
* **Behavioral Trends:** Analyzed the correlation between payment methods and purchase categories.
* **Source File:** `customer_behavior_sql_queries.sql`

### 3. Data Visualization (Power BI)
The final output is a dynamic dashboard designed for stakeholders to monitor performance at a glance.
* **Key Visuals:** Heatmaps for geographic distribution, trend lines for seasonal peaks, and slicers for demographic filtering.
* **Source File:** `customer_behavior_dashboard.pbix`

---

## 📈 Key Insights & Business Impact
* **High-Value Segments:** Identified the demographic profiles contributing to the top 20% of total revenue.
* **Operational Efficiency:** Automated the data pipeline from raw file to SQL database, significantly reducing manual reporting time.
* **Strategic Recommendations:** Provided data-backed suggestions for targeted marketing spend based on seasonal purchase spikes.

---

## 📂 Repository Structure
```bash
├── Data/                   # Raw and processed datasets
├── Notebooks/              # Python ETL and EDA scripts
├── SQL_Queries/            # Business logic and analytical queries
├── Dashboard/              # Power BI (.pbix) files
├── Reports/                # Final Project Report and Stakeholder Presentation
└── README.md
