 # Target vs Actual Sales Dashboard (Power BI)

This repository contains an interactive Power BI dashboard that compares target sales vs actual sales across products, regions, and time periods. The dashboard helps businesses measure performance, track progress toward goals, and identify areas that need improvement.

# File Included

Target vs Actual Sales.pbix — Power BI dashboard file

# Project Overview

This dashboard is designed to answer key business questions such as:

How close are we to achieving our sales targets?

Which products or regions are underperforming?

Where are sales exceeding expectations?

What trends or patterns exist over time?

It provides a clear view of performance gaps to support data-driven decision-making.

# Key Features

Comparison of Actual vs Target Sales

Product-wise and region-wise performance

KPI indicators for goal achievement

Trend charts showing performance over time

Highlighting variances (positive & negative)

Interactive slicers for detailed drilldown

# Data Preparation

Data was cleaned and transformed in Power Query by:

Removing inconsistencies

Correcting data types

Creating calculated columns

Building relationships between fact and dimension tables

# DAX Measures Used (Examples)
Total Target = SUM('Sales'[Target])
Total Actual = SUM('Sales'[Actual])
Variance = [Total Actual] - [Total Target]
Achievement % = DIVIDE([Total Actual], [Total Target], 0)

# How to Use

Download Target vs Actual Sales.pbix

Open it in Power BI Desktop

Refresh or customize based on your dataset

Explore variance, performance, and KPI indicators

👤 Author

Gajendra Sawant
Data Analyst | Power BI | SQL | Python
