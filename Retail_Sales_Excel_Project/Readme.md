# Retail Sales Analysis and Interactive Dashboard using Excel

## Project Overview

This project analyzes retail sales data using Microsoft Excel to evaluate sales performance, profitability, regional trends, and product category performance. An interactive dashboard was developed using PivotTables, PivotCharts, Excel formulas, and slicers to transform raw transactional data into actionable business insights.

The project demonstrates how Excel can be used for data analysis, business reporting, KPI tracking, and data-driven decision-making.

## Business Objectives

- Analyze overall sales, profit, quantity sold, and order volume.
- Compare sales and profitability across different regions.
- Identify high-performing and loss-making product sub-categories.
- Analyze monthly sales trends from 2014 to 2017.
- Build an interactive dashboard for exploring sales performance.
- Provide business recommendations to improve profitability.

## Dataset

- **Dataset:** Sample Superstore Retail Sales Dataset
- **Records:** 9,994 rows
- **Time Period:** 2014–2017
- **Data Format:** Excel workbook
- **Source:** [Sample Superstore Dataset — Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

### Key Columns

| Column | Description |
|---|---|
| Order ID | Unique identifier for an order |
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

- **Microsoft Excel**
- Excel Tables and Structured References
- Excel Formulas and Functions
- PivotTables
- PivotCharts
- Interactive Slicers
- KPI Cards
- Data Visualization
- Business Analysis

## Project Workflow

### 1. Data Preparation

- Reviewed the original dataset and retained a separate source-data worksheet.
- Used a cleaned-data worksheet for analysis.
- Checked for missing values and duplicate records.
- Added calculated columns to support trend and profitability analysis.

### 2. Feature Engineering

Created additional columns using Excel formulas:

- **Order Year:** Extracted the year from Order Date.
- **Order Month:** Extracted the month name from Order Date.
- **Month Number:** Extracted the numeric month for chronological sorting.
- **Shipping Days:** Calculated the difference between Ship Date and Order Date.
- **Profit Status:** Classified records as Profit, Loss, or Break-even.
- **Row Profit Margin:** Calculated profit as a percentage of sales for each record.

### 3. Exploratory Data Analysis

Created PivotTables to investigate:

- Sales and profit by region.
- Sales and profit by category and sub-category.
- Monthly sales trends from 2014 to 2017.
- Profitability across product sub-categories.

### 4. Dashboard Development

Built an interactive dashboard containing:

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
| Overall Profit Margin | Approximately 12.47% |

## Key Business Insights

### 1. Regional Performance

The West region generated the highest sales of **$725,457.82** and the highest profit of **$108,418.45**.

**Business recommendation:** Investigate the sales strategies and product mix in the West region to identify practices that could improve performance in other regions.

### 2. Category Performance

Technology generated the highest category sales of **$836,154.03** and the highest category profit of **$145,454.95**.

Furniture generated **$741,999.80** in sales but only **$18,451.27** in profit.

**Business recommendation:** Review Furniture discounting, product costs, and product mix to identify opportunities to improve margins.

### 3. Loss-Making Sub-Categories

The analysis identified the following loss-making sub-categories:

| Sub-Category | Total Profit |
|---|---:|
| Tables | -$17,725.48 |
| Bookcases | -$3,472.56 |
| Supplies | -$1,189.10 |

Copiers generated the highest sub-category profit of **$55,617.82**.

**Business recommendation:** Investigate discount levels, pricing, shipping costs, and product costs for loss-making sub-categories before making changes to their sales strategy.

### 4. Monthly Sales Trends

Monthly sales fluctuated throughout the 2014–2017 period, with noticeable peaks in certain months.

**Business recommendation:** Use monthly sales patterns to support inventory planning and promotional scheduling. Validate recurring seasonal patterns across multiple years before using them for forecasting.

## Dashboard Features

- Interactive filtering by Region, Category, and Segment.
- KPI cards for quick performance monitoring.
- Visual comparison of regional sales and profit.
- Monthly sales trend analysis.
- Identification of profitable and loss-making sub-categories.

## Project Structure

```text
Retail-Sales-Excel-Analysis/
│
├── Retail_Sales_Analysis.xlsx
├── README.md
└── Dashboard Screenshot.png
```

## How to Use This Project

1. Clone or download this repository.
2. Open `Retail_Sales_Analysis.xlsx` in Microsoft Excel.
3. Navigate to the Dashboard worksheet.
4. Use the Region, Category, and Segment slicers to explore the data.
5. Review the PivotTables and Insights worksheets for detailed analysis.

**Note:** Interactive slicers and PivotCharts work best in desktop Microsoft Excel.

## Conclusion

This project demonstrates the use of Microsoft Excel to analyze retail transactions, calculate business KPIs, explore profitability, and build an interactive dashboard. It highlights regional and category performance differences and identifies loss-making product sub-categories that warrant further investigation.

The project demonstrates practical skills in data preparation, Excel formulas, PivotTables, data visualization, and business insight generation.

## Author

**Navya Sri Gude**

Aspiring Data Analyst | Excel | SQL | Power BI | Python


