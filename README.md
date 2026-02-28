# Data Analytics Portfolio – Power BI & SQL Projects

This repository contains multiple end-to-end Business Intelligence and Data Analysis projects built using SQL, Power BI, DAX, and structured data modeling techniques.
Each project demonstrates practical data analyst skills including data extraction, cleaning, transformation, modeling, KPI development, and business insight generation.

## Projects Included
* Customer and Profit Analysis
* Performance and Profitability Marketing Analysis
* Customer Profitability Analysis
* Growth and Time-Based Sales Analysis
* Executive Dashboard

## Customer and Profit Analysis
### Objective
To analyze customer behavior, revenue contribution, and profitability trends in order to identify high-value customers and margin drivers.
### Key Features

* Revenue by Customer
* Profit and Profit Margin %
* Top Customers Ranking using RANKX
* Contribution % to Total Revenue
* Regional Customer Distribution
* DAX Concepts Used
* CALCULATE
* ALL
* RANKX
* Profit Margin Calculation
* Revenue Contribution %

## Dashboard Preview
![Customer Profit Analysis](Customer-&-Profit-Analysis/customer_and_profit_analysis.png)

## Performance and Profitability Analysis
### Objective
To evaluate overall sales performance across product categories and marketing segments while analyzing the impact of discounts and profitability on business performance.

### Key Features
* Revenue by Category and Sub-Category
* Profit and Profit Margin % by Segment
* Discount Impact on Profitability
* Regional Performance Comparison
* Top Performing Products by Revenue
* Sales Contribution by Category
* Variance Analysis across Segments
* DAX Concepts Used
* CALCULATE
* ALL / ALLEXCEPT
* RANKX
* Profit Margin Calculation
* Revenue Contribution %
* Context Transition and Filter Modification

## Dashboard Preview
![Performance Profitability Analysis](images/performance-profitability.png)

## Customer Profitability Analysis
###Objective
To identify profitable and loss-generating customers and measure long-term value contribution.

### Key Features
* Customer Ranking by Revenue
* Customer Ranking by Profit
* High vs Low Margin Customers
* Contribution % by Customer Segment
* Geographic Sales Distribution
* Business Insights Generated
* Top customers contribute a significant portion of total revenue
* Certain customer segments generate lower margin
* Profitability varies across regions

## Dashboard Preview
![Customer Profitability](images/customer-profitability.png)


### Marketing Analysis
## Objective
To analyze the effectiveness of marketing efforts by evaluating sales performance across regions, customer segments, and product categories, while identifying the impact of discounts and promotional strategies on revenue and profitability.

### Key Features

* Sales Performance by Marketing Segment
* Revenue by Region and Customer Segment
* Discount Impact on Sales and Profit
* Category-wise Campaign Performance
* Top Products Influenced by Promotions
* Contribution % by Segment
* Geographic Sales Distribution
* DAX Concepts Used
* CALCULATE
* ALL / ALLEXCEPT
* RANKX
* Profit Margin Calculation
* Revenue Contribution %
* Variance Analysis

## Dashboard Preview
[!Marketing analysis]()


## Growth and Time-Based Sales Analysis

### Objective
To analyze sales trends over time and measure growth performance.

### Key Features
* Monthly and Yearly Sales Trend
* Sales Growth %
* Budget vs Actual Comparison
* Seasonal Performance Analysis
* Time Intelligence Metrics
* DAX Concepts Used
* Time-based calculations
* Growth percentage computation
* Variance from budget
* Context transition using CALCULATE

## Dashboard Preview
![Growth Time Analysis](images/growth-time-analysis.png)

## Executive Dashboard

###Objective
To provide high-level KPI monitoring for decision-makers and stakeholders.

## Key Metrics
* Total Revenue
* Total Profit
* Profit Margin %
* Revenue Contribution by Category
* Sales vs Budget
* Top Performing Region
* Top Customers Snapshot
* Dashboard Features
* KPI Cards
* Category Distribution
* Regional Performance Comparison
* Budget Tracking
* Interactive Filters and Slicers

## Dashboard Preview
![Executive Dashboard](images/executive-dashboard.png)

## Data Modeling Approach
Across projects, a star schema model was implemented:
* Fact Table: Sales
* Dimension Tables: Product, Customer, Date, Geography
* Relationships were defined using one-to-many cardinality to ensure accurate filter context behavior and optimized analytical performance.

## Tech Stack
* MySQL
* Power BI
* DAX
* Power Query
* Excel

## Skills Demonstrated
* SQL Data Extraction and Joins
* Data Cleaning and Transformation
* Star Schema Data Modeling
* DAX (CALCULATE, ALL, RANKX)
* KPI Development
* Profitability and Contribution Analysis
* Dashboard Design and Business Storytelling
