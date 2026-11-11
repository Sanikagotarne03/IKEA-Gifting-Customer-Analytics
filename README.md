# IKEA Gifting – Customer Analytics & RFM Segmentation

An end-to-end data analytics project using **SQL Server, Python, and Power BI** to analyze customer purchasing behaviour, identify valuable customer segments, and understand customer retention and churn patterns.

## Project Overview

IKEA Gifting is a fictional UK-based online gifting and home décor business. This project focuses on analyzing historical retail transaction data to understand customer behaviour, evaluate revenue contribution, identify high-value customers, and highlight customers at risk of churn.

The project follows an end-to-end analytics workflow, starting with data extraction and cleaning in SQL Server, followed by exploratory data analysis and RFM-based customer segmentation using Python, and finally presenting actionable business insights through an interactive Power BI dashboard.

## Business Problem

The business lacks a structured understanding of customer purchasing patterns, customer value, and retention behaviour.

The objective is to transform raw transactional data into meaningful insights that help the business:

- Identify high-value and loyal customers.
- Understand customer purchasing behaviour.
- Identify customers at risk of churn.
- Analyze revenue contribution across customer segments.
- Monitor customer retention and business performance.
- Support data-driven customer retention strategies.

## Business Questions

1. Who are the most valuable customers?
2. Which customer segments contribute the highest revenue?
3. Which customers are at risk of churning?
4. How does customer purchasing behaviour vary across segments?
5. How do revenue and customer trends change over time?
6. Which customer segments require greater retention efforts?

## Dataset

**Source:** Online Retail II Dataset – UCI Machine Learning Repository.

- Total Records: 1,067,371 transactions
- Time Period: December 2009 – December 2011
- Data Type: Historical retail transactional data
- Key Attributes: Invoice, Stock Code, Description, Quantity, Invoice Date, Price, Customer ID, and Country.

The dataset contains real-world data quality challenges, making it suitable for practicing data cleaning, preprocessing, and business analytics.

## Technology Stack

| Technology | Purpose |
|---|---|
| SQL Server / SSMS | Data extraction, cleaning and querying |
| Python | Data preprocessing, EDA and RFM analysis |
| Pandas & NumPy | Data manipulation and analysis |
| Matplotlib & Seaborn | Data visualization |
| Jupyter Notebook | Python development and analysis |
| Power BI | Interactive dashboard development |
| DAX | Measures and business KPIs |
| Power Query | Data transformation |
| Git & GitHub | Project version control |

## Project Workflow

### Step 1 – Business Requirements Analysis
- Defined the business problem and project objectives.
- Identified key business questions and analytical requirements.
- Prepared a Business Requirements Document (BRD).
- Defined customer segmentation and churn criteria.

### Step 2 – SQL Server: Data Cleaning & Exploration
- Imported and combined retail transaction data.
- Handled missing values and data quality issues.
- Standardized data types and date formats.
- Identified and removed duplicate transactions.
- Performed data validation and exploratory SQL queries.
- Prepared an analysis-ready dataset.

### Step 3 – Python: Exploratory Data Analysis & Customer Segmentation
- Loaded and processed cleaned transactional data using Pandas.
- Performed exploratory data analysis (EDA).
- Analyzed customer purchasing patterns and revenue distribution.
- Calculated Recency, Frequency, and Monetary (RFM) values.
- Applied RFM scoring to evaluate customer value.
- Classified customers into six segments:
  - Champions
  - Loyal
  - At Risk
  - New
  - Needs Attention
  - Lost
- Applied a 90-day inactivity threshold to identify churned customers.

### Step 4 – Power BI: Interactive Dashboard

Developed a three-page interactive Power BI dashboard to communicate business performance and customer insights.

**Page 1 – Home**
- Project introduction and branding.
- Dashboard navigation.
- Key analytical definitions and glossary.

**Page 2 – Business Overview**
- Total Customers
- Total Revenue
- Average Customer Value
- Churn Percentage
- Customer and revenue analysis.
- Customer segment distribution.
- Time-based revenue and customer trends.
- Interactive slicers and bookmark-based metric navigation.

**Page 3 – RFM Analysis**
- Customer segment performance.
- Segment-wise customer distribution.
- Revenue contribution by customer segment.
- Average RFM scores.
- Customer value comparison.
- Churn trend analysis.

## Key Analytical Concepts

- **Exploratory Data Analysis (EDA):** Understanding customer behaviour, transaction patterns, and revenue distribution.
- **RFM Analysis:** Evaluating customer value through Recency, Frequency, and Monetary metrics.
- **Customer Segmentation:** Grouping customers into six meaningful categories based on purchasing behaviour.
- **Churn Analysis:** Identifying inactive customers using a fixed 90-day threshold.
- **Data Cleaning:** Handling missing values, duplicates, inconsistent formats, and invalid records.
- **Business Intelligence:** Converting analytical results into interactive dashboards and business KPIs.

## Future Enhancements

The project establishes a foundation for extending traditional customer analytics with predictive techniques.

Potential enhancements include:
- ML-based customer churn prediction.
- Predictive customer value analysis.
- Customer retention risk classification.
- AI-assisted customer segmentation insights.

*These are proposed enhancements and are not part of the currently implemented analytical workflow.*

## Project Deliverables

- Business Requirements Document (BRD).
- Cleaned and processed retail dataset.
- SQL data cleaning and exploration.
- Python EDA and RFM analysis.
- Six-segment customer classification.
- 90-day churn analysis.
- Interactive three-page Power BI dashboard.

## Disclaimer

IKEA Gifting is a fictional business created for educational and portfolio purposes. This project is not affiliated with, endorsed by, or representative of the actual IKEA corporation. All analysis is based on the publicly available Online Retail II dataset.

---

**Project Focus:** Data Analytics | Customer Analytics | RFM Segmentation | Business Intelligence | SQL | Python | Power BI
