<div align="center">

# 👗 Fashion Retail Sales Performance & Customer Insights

Drive Link - https://drive.google.com/drive/folders/1Q6WQ4t26-kcFcy5Wm9O9TkSDA3Lq8Gw0?usp=sharing

### 📊 Excel Data Preparation | Power BI Dashboard | Retail Analytics

A data analytics project exploring **sales performance, profitability, products, stores, returns, and customer purchasing behaviour** using Microsoft Excel and Power BI.

<kbd>Excel</kbd> &nbsp;
<kbd>Power BI</kbd> &nbsp;
<kbd>Power Query</kbd> &nbsp;
<kbd>DAX</kbd> &nbsp;
<kbd>Data Cleaning</kbd> &nbsp;
<kbd>Data Visualization</kbd>

</div>

---

## 📌 Project Overview

This project analyzes **50,000 fashion retail transactions from January 2020 to December 2024**.

The raw data was cleaned and prepared in **Microsoft Excel**, while **Power BI** was used for data modelling, DAX calculations, KPI analysis, and interactive dashboard development.

The dashboard helps answer questions such as:

- How is revenue changing over time?
- Which product categories generate the most revenue?
- Which stores perform best?
- What is the overall return rate?
- Which customer groups contribute the most transactions?
- Where are negative-profit transactions occurring?

---

## 🎯 Project Objectives

The main objectives were to:

✔ Clean and prepare raw retail data  
✔ Handle missing and inconsistent values  
✔ Create calculated financial fields  
✔ Analyse revenue and estimated profitability  
✔ Compare product and store performance  
✔ Analyse customer purchasing patterns  
✔ Identify return behaviour  
✔ Build an interactive Power BI dashboard  
✔ Generate useful business recommendations  

---

## 🗂️ Dataset

The project uses four related datasets:

| Dataset | Records | Main Information |
|---|---:|---|
| Sales | 50,000 | Transactions, quantity, discount & returns |
| Products | 50,000 | Category, colour, size, supplier, cost & price |
| Customers | 25,000 | Age, gender, city & email |
| Stores | 5 | Store name, region & size |

The tables are connected using:

`Product ID` • `Customer ID` • `Store ID`

> 🔗 **Dataset Source:** [Add your dataset link here]

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| **Microsoft Excel** | Data cleaning, validation, formulas, lookups & preparation |
| **Power BI Desktop** | Data modelling, dashboard development & visualization |
| **Power Query** | Importing cleaned data and checking data types |
| **DAX** | KPI measures, Calendar table & time analysis |
| **PivotTable** | Cross-checking Excel and Power BI totals |

---

## 🧹 Data Cleaning & Preparation

The raw datasets required several preparation steps before analysis.

### Key Cleaning Steps

- Preserved separate **Raw** and **Cleaned** worksheets
- Checked duplicate records
- Standardized date and number formats
- Standardized category and supplier names
- Handled missing discounts
- Handled unknown Customer IDs
- Treated missing gender and email values
- Used **mode and median imputation** where appropriate
- Added unmatched Product and Store reference records
- Used **XLOOKUP** to retrieve product cost and price
- Created Return Status
- Created Revenue Status
- Created customer Age Groups
- Checked pricing exceptions
- Applied conditional formatting
- Validated final results

---

## 🧮 Calculated Fields

Several calculated fields were created for analysis.

### Estimated Revenue

`Quantity × Unit Price × (1 − Discount)`

Returned transactions were assigned zero estimated revenue.

### Estimated Cost

`Quantity × Unit Cost`

### Estimated Gross Profit

`Estimated Revenue − Estimated Cost`

Additional fields included:

- Return Status
- Revenue Status
- Age Group
- Price Check
- Unit Cost
- Unit Price

---

## 📊 Power BI Dashboard

The final Power BI report contains **3 interactive pages**.

### 01 — Sales Overview

Provides a high-level view of business performance.

**Main KPIs**

- 💰 Estimated Revenue
- 📈 Estimated Gross Profit
- 📊 Estimated Gross Margin
- 🧾 Total Transactions
- 🔄 Return Rate

**Visuals**

- Monthly Revenue & Gross Profit Trend
- Revenue by Product Category
- KPI Cards
- Year, Store and Category filters

---

### 02 — Products & Stores

Focuses on product and store performance.

**Analysis includes:**

- Category Revenue
- Category Gross Margin
- Store Performance
- Supplier Revenue
- Category & Season Revenue
- Recorded Units

---

### 03 — Customer Insights

Explores customer purchasing activity.

**Analysis includes:**

- Identified Customers
- Average Units per Transaction
- Estimated Revenue per Transaction
- Returned Transactions
- Transactions by Age Group
- Transactions by Gender
- Customers by City

---

## 📈 Key Performance Indicators

| KPI | Result |
|---|---:|
| 🧾 Total Transactions | **50,000** |
| 💰 Estimated Revenue | **$11.23M** |
| 💵 Estimated Cost | **$4.80M** |
| 📈 Estimated Gross Profit | **$6.43M** |
| 📊 Estimated Gross Margin | **57.27%** |
| 📦 Recorded Units | **125,324** |
| 👥 Identified Customers | **21,275** |
| ↩️ Returned Transactions | **4,959** |
| 🔄 Return Rate | **9.92%** |
| 💳 Revenue / Transaction | **$224.69** |
| 🛍️ Average Units / Transaction | **2.51** |

---

## 🔍 Key Insights

### 💰 Revenue Performance
Revenue remained relatively stable between 2020 and 2024.

2023 recorded the highest estimated annual revenue, while revenue decreased by approximately **2.09% in 2024**.

### 👕 Product Performance
**Accessories** generated the highest estimated revenue at approximately **$2.39M**.

However, revenue was relatively balanced across all five product categories.

### 🏬 Store Performance
**Lisbon Flagship** generated the highest estimated revenue.

**Faro Outlet** generated the highest estimated gross profit.

This shows that store performance should be evaluated using both **revenue and profitability**.

### 🌐 Online Sales
Online sales generated approximately **$2.21M**, representing around **19.65% of total estimated revenue**.

### 🔄 Returns
The overall return rate was **9.92%**, representing **4,959 returned transactions**.

### ⚠️ Negative Gross Profit
Around **16.82% of transactions** produced negative estimated gross profit.

This indicates an opportunity to review:

- Product costs
- Selling prices
- Discounts
- Pricing strategy

### 👥 Customer Insights
Customers aged **30–59** represented a large share of identified customer transactions.

---

## 💡 Business Recommendations

| Area | Recommendation |
|---|---|
| 💲 Pricing | Review costs, prices and discounts for loss-making transactions |
| 👗 Products | Maintain a balanced product mix and test Accessories promotions |
| 🏬 Stores | Compare high-performing stores and identify successful practices |
| ↩️ Returns | Investigate return reasons, especially for higher-return areas |
| 🌐 Online | Improve online product information and recommendations |
| 👥 Customers | Test targeted promotions for active customer groups |
| 📊 Monitoring | Track monthly revenue, transactions and return rates |
| 🧹 Data Quality | Improve customer identification and missing-data collection |

---

## ✅ Data Validation

The main Power BI totals were cross-checked against an Excel yearly PivotTable.

The following values matched between Excel and Power BI:

- Total Transactions
- Estimated Revenue
- Estimated Gross Profit

This helped confirm consistency between the cleaned Excel data and the Power BI model.

---

> Create an `images` folder in the GitHub repository and upload screenshots of the three dashboard pages using the filenames above.

---

## 📂 Repository Structure

```text
Fashion-Retail-Sales-Analytics/
│
├── README.md
│
├── MINI PROJECT.xlsx
├── MINI PROJECT.pbix
├── MINI PROJECT.pdf
├── MINI PROJECT.docx
│
└── images/
    ├── sales-overview.png
    ├── products-stores.png
    └── customer-insights.png
