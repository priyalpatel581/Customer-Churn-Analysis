# Customer-Churn-Analysis
```markdown
# Telecom Customer Churn Analysis

End-to-end ETL and analytics project that analyzes customer churn in the telecom industry using SQL Server and Power BI.

## Overview

Customer churn is a major business risk for telecom operators. This project performs an end-to-end analysis — from raw data ingestion and ETL to interactive dashboards and KPI modeling — to help identify churn drivers and recommend retention strategies.

Key goals:
- Build a repeatable ETL pipeline to standardize and prepare data for analytics.
- Create analytical views and measures for Power BI consumption.
- Produce dashboards and insights to inform retention and product strategies.

## Tech Stack

- SQL Server — ETL pipelines, staging and production schemas, analytical views
- Power BI — Interactive dashboards and reports (PBIX files)
- DAX — Measures for churn, retention, and revenue impact
- Excel / CSV — Source datasets for ingestion

## Project Deliverables

- End-to-end ETL workflow implemented in SQL Server
  - Data ingestion from raw CSV/Excel sources
  - Data profiling, cleansing, and transformation
  - Staging and production schema design
  - Analytical SQL views for reporting
- Power BI dashboards to analyze churn across dimensions
  - Demographics (age group, gender)
  - Tenure and contract type
  - Internet and add-on services
  - Geography (state), revenue bands, and payment method
- DAX measures and KPIs
  - Churn Rate, Retention Rate
  - Revenue impact due to churn
  - Customer segmentation and lifetime value (CLV)

## Dashboard Preview

Add your dashboard image here:

<p align="center">
  <img width="1455" height="816" alt="Churn Dashboard" src="https://github.com/user-attachments/assets/060c47ff-7eb1-40ef-b8bf-f60a426a18c2" />
</p>


## Key Insights (Summary)

- Age group impact
  - Customers aged > 50 make up the largest segment (2,729 customers, 42.52% of total).
  - Customers aged < 20 are the smallest segment (117 customers).
  - Churn rate generally increases with age in this dataset.
- Tenure behavior
  - The largest difference between total customers and churn occurred in the ≥ 24 months group (2,087 more retained than churned).
  - Across tenure groups, total customers ranged from ~980 to ~2,087 while churn rate ranged between ~0.26 to ~0.28.
- Gender influence
  - Total churn count for females (1,111) is higher than for males (621).

Use these patterns to target high-risk cohorts with retention campaigns and product offers.

## Recommendations & Business Value

This analysis supports:
- Targeted retention programs by identifying high-risk customer segments.
- Pricing and contract optimization based on tenure and churn patterns.
- Cross-sell and up-sell opportunities for customers with high CLV.
- Improved service reliability efforts in states or customer cohorts with elevated churn.

## Future Enhancements

- Deploy machine learning models for churn prediction and early warning.
- Perform clustering for more granular customer segmentation.
- Automate ETL scheduling with SQL Server Agent and enable Power BI Gateway refreshes.
- Add real-time or near-real-time monitoring for churn signals.

```
