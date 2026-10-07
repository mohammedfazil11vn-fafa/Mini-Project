# Fashion Retail Sales Performance and Customer Insights

**Microsoft Excel | Power BI | Power Query | DAX**

## Project Overview

This project analyses **50,000 fashion sales transactions from 2020 to 2024** to understand sales performance, product contributions, store results, returns and customer purchasing activity.

Excel was used for data cleaning and processing. Power BI was used to build an interactive dashboard with three pages: **Sales Overview, Products & Stores, and Customer Insights**.

The project represents a hypothetical retail case study.

## Project Objectives

- Analyse revenue and estimated gross profit over time.
- Compare product categories, suppliers and stores.
- Understand customer purchasing activity.
- Examine returns and transactions with negative estimated gross profit.
- Present findings through an interactive dashboard.
- Recommend business actions based on the results.

## Tools Used

| Tool | Purpose |
|---|---|
| **Microsoft Excel** | Data cleaning, missing-value treatment, lookups, calculations and PivotTable validation |
| **Power Query** | Importing and preparing tables in Power BI |
| **Power BI** | Data modelling, dashboard design and interactive visualisation |
| **DAX** | Calendar table and KPI measures |

## Dataset

The project uses four related datasets:

| Dataset | Raw Records | Information |
|---|---:|---|
| Sales | 50,000 | Transactions, dates, quantities, discounts and returns |
| Products | 50,000 | Categories, colours, sizes, suppliers, costs and prices |
| Customers | 25,000 | Customer IDs, ages, genders, cities and emails |
| Stores | 5 | Store names, regions and store sizes |

Additional reference records were created for missing customer, product and store identifiers. All 50,000 sales transactions were retained.

**Source note:** The original dataset publisher and download link have not yet been verified.

## Data Cleaning and Processing

### Excel

- Checked missing values, identifiers and duplicate records. No duplicate primary keys were found.
- Standardised dates, text labels, percentages and currency formats.
- Applied mean, median or mode imputation to selected missing values.
- Filled missing discounts with 0% as a project assumption.
- Added reference records for identifiers missing from related tables.
- Used product-ID lookups to retrieve unit cost and unit price.
- Created calculated fields for return status, revenue status, estimated revenue, estimated cost, estimated gross profit and age groups.
- Flagged products where cost exceeded list price.
- Created a yearly PivotTable to validate transaction, revenue and gross-profit totals.

### Power BI

- Imported the cleaned Excel tables and checked data types.
- Created relationships between Sales, Products, Customers and Stores.
- Added a Calendar table for date-based analysis.
- Created DAX measures for financial performance, transactions, returns and customers.
- Built three dashboard pages with synchronised slicers, navigation buttons, reset controls and tooltips.

## Dashboard Pages

| Page | Main Content |
|---|---|
| **Sales Overview** | Revenue, gross profit, margin, transactions, return rate, monthly performance and category revenue |
| **Products & Stores** | Recorded units, category revenue and margin, store performance, supplier revenue and category–season comparisons |
| **Customer Insights** | Identified customers, average units per transaction, revenue per transaction, returns, age groups, gender and customer locations |

The dashboard uses a **16:9 landscape layout** with a consistent colour scheme. Year, Store and Category filters allow users to explore specific selections across all three pages.

## Key Performance Indicators

Results cover the complete 2020–2024 dataset with no filters applied.

| KPI | Result |
|---|---:|
| Total Transactions | **50,000** |
| Estimated Revenue | **$11,234,621.25** |
| Estimated Gross Profit | **$6,434,093.54** |
| Estimated Gross Margin | **57.27%** |
| Recorded Units | **125,324** |
| Identified Purchasing Customers | **21,275** |
| Returned Transactions | **4,959** |
| Return Rate | **9.92%** |
| Estimated Revenue per Transaction | **$224.69** |
| Average Units per Transaction | **2.51** |

## Key Findings

- **Revenue trend:** Estimated revenue peaked at **$2.30 million in 2023**, then declined by **2.09% in 2024**.
- **Category performance:** Accessories generated the highest revenue at **$2.39 million**, contributing **21.24%** of the total. Revenue was relatively balanced across the five categories.
- **Store performance:** Lisbon Flagship led estimated revenue at **$2.28 million**, while Faro Outlet led estimated gross profit at **$1.31 million**.
- **Online contribution:** Online sales generated **$2.21 million**, representing **19.65%** of total estimated revenue.
- **Returns:** Approximately one in ten transactions was returned. Porto Center recorded a return rate of **10.48%**, above the overall **9.92%**.
- **Pricing review:** **8,411 transactions**, representing **16.82%** of all transactions, had negative estimated gross profit.

## Business Recommendations

| Area | Recommended Action |
|---|---|
| **Pricing** | Check product costs, selling prices and discounts for transactions with negative estimated gross profit. |
| **Products** | Maintain a balanced product range and test Accessories promotions while monitoring margin and returns. |
| **Stores** | Compare product mix, discounts and returns across stores to understand performance differences. |
| **Returns** | Collect return reasons and investigate affected products before deciding on improvements. |
| **Online Sales** | Test improvements to product descriptions and the online shopping experience. |
| **Performance Monitoring** | Review monthly revenue, transactions and returns to investigate changes in performance. |

These recommendations have not been implemented or tested as part of the project.

## How to Explore the Project

1. Download the cleaned Excel workbook and Power BI `.pbix` file.
2. Open the workbook to review the cleaned tables, calculations and yearly summary.
3. Open the `.pbix` file in Power BI Desktop.
4. Before refreshing, update the Excel source path to the workbook’s location on your computer.
5. Explore the dashboard using the Year, Store and Category slicers.

## Assumptions and Limitations

- Financial values are estimates based on product catalogue prices and costs.
- The dollar symbol is a presentation assumption.
- Gross profit excludes operating expenses and does not represent net profit.
- Missing-value imputation may affect the results.
- Returned transactions contribute zero estimated revenue, cost and gross profit, but remain included in transaction and recorded-unit counts.
- Product season is a catalogue classification and does not establish purchasing seasonality.
- In the reviewed version, the `C_UNKNOWN` customer’s demographic values still require correction before final age and gender comparisons.
- The project focuses on historical analysis and does not include forecasting or machine learning.

## Skills Demonstrated

**Data cleaning · Missing-value treatment · Excel formulas · Lookups · PivotTables · Data modelling · DAX · Interactive dashboards · Business analysis**

## Author

**Mohammed Fazil**
