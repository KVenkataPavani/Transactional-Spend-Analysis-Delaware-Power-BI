# Transactional-Spend-Analysis-Delaware

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Skills and Tools Used](#skills-and-tools-used)
- [Project Scope](#project-scope)
- [Results/Findings](#resultsfindings)

## Project Overview
This project involves creating a comprehensive Power BI dashboard to analyze transactional spending data for a fictitious organization. The objective was to provide insights into departmental expenditures, track merchant-specific transactions, and highlight key spending patterns over time. By leveraging data from multiple departments and categories, the dashboard aims to facilitate data-driven decision-making and offer executives and stakeholders a clear visualization of financial performance.

## Data Sources
The primary dataset used for this analysis is the [Delaware_dataset](https://www.kaggle.com/datasets/mahmudulhaqueshawon/delaware-anomaly/data?select=delaware_anomaly.csv) file, containing detailed information about each sale made by the company.

## Skills and Tools Used
- Power Query | Power BI (Data Transformation, Data Cleaning and Preparation)
- Power BI (DAX Formulas, Visualization Design)
- KPI Development and Financial Analysis
- Power BI (Interactive Dashboard Design and User-Centric Layout)

## Project Scope

### Data Collection, Cleaning and Preparation
* Imported raw transaction data, including fields like fiscal year, department name, merchant name, transaction date, and amount.
* Cleaned and formatted data within Power BI, converting transaction dates into a standard date type, removing duplicates, and handling negative values for refund transactions.

### Data Transformation and Metrics Calculation
* Created custom DAX measures for key metrics, including Total Spend, Average Transaction Value, and Transaction Count.
* Developed KPIs to monitor monthly spend changes, department-level expenditures, and high-spend merchant insights.
* Designed additional metrics, like the success rate and percentage contribution by the top 3 departments, to provide granular insights.

### Visualization and Dashboard Design
* Built interactive visualizations, such as line charts for monthly trends, bar charts for department-level spend, pie charts for category breakdowns, and matrix heatmaps for high-spend analysis.
* Added slicers for dynamic filtering by fiscal year, department, and merchant to allow for custom analysis.
* Applied a color-coded theme to distinguish between positive spends and refunds, ensuring clarity in data representation.

### KPI and Interactive Features
* Highlighted KPIs for Total Spend, Average Transaction Value, and Top Department to provide a quick snapshot of key financial metrics.
* Enabled drill-through and filtering options for deeper insights into specific departments and merchants.

## Results/Findings
The completed dashboard provides an at-a-glance summary of transactional patterns, helping identify major cost centers, spending trends, and opportunities for cost management.
