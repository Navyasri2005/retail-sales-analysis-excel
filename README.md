# Retail Sales Analysis and Interactive Dashboard using Excel

## Project Overview

This project analyzes retail sales data using Microsoft Excel to evaluate sales performance, profitability, regional trends, and product category performance. An interactive dashboard was developed using Excel formulas, PivotTables, PivotCharts, and slicers to transform raw transactional data into actionable business insights.

## Business Objectives

- Analyze total sales, profit, quantity sold, and order volume.
- Compare sales and profitability across different regions.
- Identify high-performing and loss-making product sub-categories.
- Analyze monthly sales trends from 2014 to 2017.
- Build an interactive dashboard for monitoring business performance.
- Generate data-driven recommendations to improve profitability.

## Dataset

- **Dataset:** Sample Superstore Retail Sales Dataset
- **Records:** 9,994 rows
- **Time Period:** 2014–2017
- **Source:** [Sample Superstore Dataset on Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

### Key Columns

| Column | Description |
|---|---|
| Order ID | Order identifier |
| Order Date | Date the order was placed |
| Ship Date | Date the order was shipped |
| Ship Mode | Shipping method |
| Customer ID | Customer identifier |
| Segment | Customer segment |
| Region | Sales region |
| Category | Product category |
| Sub-Category | Product sub-category |
| Sales | Revenue generated |
| Quantity | Number of units sold |
| Discount | Discount applied |
| Profit | Profit or loss generated |

## Tools and Technologies

- Microsoft Excel
- Excel Tables and Structured References
- Excel Formulas and Functions
- PivotTables and PivotCharts
- Interactive Slicers
- KPI Cards
- Data Visualization
- Business Analysis

## Project Workflow

### 1. Data Preparation

- Reviewed the original dataset and retained a separate raw-data worksheet.
- Used a dedicated worksheet for analysis.
- Checked for missing values and duplicate records.
- Added calculated columns to support trend and profitability analysis.

### 2. Feature Engineering

Created additional columns using Excel formulas:

- **Order Year:** Extracted the year from Order Date.
- **Order Month:** Extracted the month name from Order Date.
- **Month Number:** Extracted the numeric month for chronological sorting.
- **Shipping Days:** Calculated the time between Order Date and Ship Date.
- **Profit Status:** Classified records as Profit, Loss, or Break-even.
- **Row Profit Margin:** Calculated profit as a percentage of sales for each record.

### 3. Exploratory Data Analysis

Created PivotTables to analyze:

- Sales and profit by region.
- Sales and profit by category and sub-category.
- Monthly sales trends from 2014 to 2017.
- Profitability across product sub-categories.

### 4. Dashboard Development

Developed an interactive Excel dashboard featuring:

- Total Sales KPI
- Total Profit KPI
- Unique Orders KPI
- Overall Profit Margin KPI
- Monthly Sales Trend chart
- Regional Sales and Profit Comparison chart
- Profit by Sub-Category chart
- Region, Category, and Segment slicers

## Key Performance Indicators

| Metric | Result |
|---|---:|
| Total Sales | $2,297,200.86 |
| Total Profit | $286,397.02 |
| Total Quantity Sold | 37,873 |
| Unique Orders | 5,009 |
| Overall Profit Margin | 12.47% |

## Key Business Insights

### 1. Regional Performance

The West region generated the highest sales of **$725,457.82** and the highest profit of **$108,418.45**.

**Recommendation:** Investigate successful sales practices in the West region and identify opportunities to improve performance in other regions.

### 2. Category Performance

Technology generated the highest category sales of **$836,154.03** and profit of **$145,454.95**.

Furniture generated **$741,999.80** in sales but only **$18,451.27** in profit.

**Recommendation:** Review Furniture discounting, product costs, and product mix to identify opportunities to improve profitability.

### 3. Loss-Making Sub-Categories

The analysis identified the following loss-making sub-categories:

| Sub-Category | Total Profit |
|---|---:|
| Tables | -$17,725.48 |
| Bookcases | -$3,472.56 |
| Supplies | -$1,189.10 |

Copiers generated the highest sub-category profit of **$55,617.82**.

**Recommendation:** Investigate pricing, discount levels, shipping costs, and product costs for loss-making sub-categories before changing their sales strategy.

### 4. Monthly Sales Trends

Monthly sales fluctuated throughout the 2014–2017 period, with noticeable peaks in certain months.

**Recommendation:** Use monthly sales patterns to support inventory planning and promotional scheduling. Validate recurring seasonal patterns across multiple years before using them for forecasting.

## Dashboard Features

- Interactive filtering by Region, Category, and Segment.
- KPI cards for quick performance monitoring.
- Regional sales and profit comparison.
- Monthly sales trend analysis.
- Identification of profitable and loss-making sub-categories.
- Business recommendations based on the analysis.

## Project Structure

```text
retail-sales-analysis-excel/
│
├── Retail_Sales_Analysis.xlsx
├── README.md
└── screenshots/
    └── retail_sales_dashboard.png
```

## How to Use

1. Clone or download this repository.
2. Open `Retail_Sales_Analysis.xlsx` in desktop Microsoft Excel.
3. Navigate to the Dashboard worksheet.
4. Use the Region, Category, and Segment slicers to explore the data.
5. Review the PivotTables and Insights worksheets for detailed findings.

**Note:** Interactive slicers and PivotCharts work best in desktop Microsoft Excel.

## Conclusion

This project demonstrates how Microsoft Excel can be used to transform retail transaction data into meaningful business insights. It combines data preparation, formula-based analysis, PivotTables, PivotCharts, and interactive slicers to evaluate sales performance, profitability, and product trends.

The findings highlight regional and category performance differences and identify loss-making sub-categories that warrant further investigation.

## Author

**Navya Sri Gude**
