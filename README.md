Project Overview
This project focuses on exploring and analyzing a real-world sales dataset using Microsoft Excel.
The objective was to clean the data, validate its quality, perform descriptive analysis, and extract business-relevant insights using Excel formulas, Pivot Tables, and charts.

The emphasis of this work is on analyst thinking: understanding data structure, validating assumptions, and explaining results clearly.

Dataset Description

- 25036 rows
- 21 columns
- Each row represents a single customer transaction

Key fields include:

- Order Date

- Sales

- Profit

- Discount

- Category

- Region
- 
Dataset source: Kaggle (public sales dataset)


Data Cleaning & Validation

Before analysis, I reviewed and cleaned the dataset with the following steps:

- Preserved the original raw dataset and worked on a cleaned copy

- Checked for missing values using:

* Filters

* COUNTBLANK

- Pivot Table counts vs sums

- Identified and removed one fully blank row (entire record was empty)

- Verified numeric columns (Sales, Profit, Discount) for inconsistencies and extreme values

- Corrected date issues where dates were stored as text

- Created derived columns:

* Order Year

* Order Month

- Standardized text fields using Excel text functions to ensure consistency for analysis

I made all cleaning decisions cautiously and would be documented in a real business setting.


Analysis Performed

Summary statistics:

- Total, minimum, maximum, and average sales and profit

Pivot Table analysis:

- Sales and profit by year

- Sales by month (seasonality)

- Sales by category

- Profit by region

- Time-based trend analysis using Year and Month

- Visual exploration using Excel charts

I also used Pivot Tables as data quality check, revealing issues I did't find through formulas alone.


Key Insights

- The trends showed that sales and profits consistently rose over the years, with the peak recorded in the most recent year.

- One category consistently generated the most sales and the most profit over the years

- Losses were recorded on discounts greater than 0, which indicated that profits were only recorded when there was no discount.
  
- Sales consistently peaked in December, indicating seasonal patterns
   

Recommendations

- Review discounting strategies, especially for low-margin products

- Focus growth efforts on consistently best perfrming categories and regions

- Use seasonal trends to plan promotions more strategically rather than applying uniform discounts
- 

Tools Used

- Microsoft Excel

- Formulas & functions

- Pivot Tables

- Charts & basic dashboarding


Next Steps

- Advanced Excel

-Build more structured Excel dashboards
