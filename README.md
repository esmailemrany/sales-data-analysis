📊 Retail Sales Data Analysis

An Exploratory Data Analysis Project Using Python and Power BI

An end-to-end retail sales analysis project focused on identifying sales trends, evaluating product and geographic performance, understanding customer purchasing patterns, and analyzing shipping operations.

The project transforms raw transaction data into measurable business insights using Python, data analysis techniques, and visualization.

---

📌 Table of Contents

- "Project Overview" (#-project-overview)
- "Business Problem" (#-business-problem)
- "Project Objectives" (#-project-objectives)
- "Dataset Overview" (#-dataset-overview)
- "Tools and Technologies" (#-tools-and-technologies)
- "Project Workflow" (#-project-workflow)
- "Key Performance Indicators" (#-key-performance-indicators)
- "Key Business Insights" (#-key-business-insights)
- "Business Recommendations" (#-business-recommendations)
- "Data Quality Assessment" (#-data-quality-assessment)
- "Project Screenshots" (#-project-screenshots)
- "Limitations" (#-limitations)
- "Future Improvements" (#-future-improvements)
- "Repository Structure" (#-repository-structure)
- "Author" (#-author)

---

🎯 Project Overview

This project analyzes a retail sales dataset containing 9,800 records and 21 columns, covering transactions from January 2015 to December 2018 across the United States.

The analysis examines sales performance across time, product categories, geographic regions, customers, orders, and shipping methods.

The goal is to demonstrate how data analysis can help businesses understand performance, identify patterns, and make better-informed decisions.

❓ Business Problem

Retail businesses generate large amounts of transaction data, but raw records do not immediately reveal which products perform best, where sales are concentrated, or how purchasing patterns change over time.

This project addresses the following questions:

- How did sales change between 2015 and 2018?
- Which months recorded the highest and lowest sales?
- Which product categories and subcategories generated the most sales?
- Which regions, states, and cities contributed most to total sales?
- How were sales distributed across customers and orders?
- Which shipping methods were used most frequently?
- How much time elapsed between order placement and shipment?

🎯 Project Objectives

1. Examine the dataset's structure and quality.
2. Validate records before performing analysis.
3. Calculate key sales performance indicators.
4. Analyze sales trends across years and months.
5. Compare product categories and subcategories.
6. Identify geographic differences in sales.
7. Analyze customer sales and order value distributions.
8. Compare shipping methods and shipment timing.
9. Communicate findings through visualizations and business recommendations.

📁 Dataset Overview

The dataset contains 9,800 records and 21 columns.

The main fields used in the analysis include:

Field| Description
Order ID| Unique identifier for an order
Order Date| Date the order was placed
Ship Date| Date the order was shipped
Ship Mode| Selected shipping method
Customer ID| Customer identifier
Customer Name| Customer name
Segment| Customer segment
Country| Country associated with the transaction
City| City associated with the transaction
State| State associated with the transaction
Region| Geographic sales region
Product ID| Product identifier
Category| Main product category
Sub-Category| Product subcategory
Product Name| Product name
Sales| Recorded sales amount
Year| Order year
Month| Order month number
Month Name| Order month name
Day| Day of the month

The dataset covers the period from January 3, 2015, to December 30, 2018.

The source file included in the repository is "sales.csv".

🛠️ Tools and Technologies

Tool| Purpose
Python| Data analysis and processing
Pandas| Data manipulation and aggregation
NumPy| Numerical operations
Matplotlib| Data visualization
Seaborn| Statistical visualization
Google Colab| Python analysis environment
Power BI| Dashboard visualization and reporting
GitHub| Project hosting and documentation

🔄 Project Workflow

1. Data Understanding

- Inspected dataset dimensions and column names.
- Reviewed data types and field meanings.
- Examined the date range and sales distribution.

2. Data Quality Assessment

- Checked for missing values.
- Checked for duplicate full records.
- Validated order and shipping dates.
- Checked for non-positive sales values.
- Verified consistency between date fields and derived year/month fields.
- Checked that shipping dates were not earlier than order dates.

3. Exploratory Data Analysis (EDA)

Performed analysis across the following areas:

- Annual sales performance
- Monthly sales patterns
- Product category and subcategory performance
- Regional, state, and city sales
- Customer sales performance
- Order value distribution
- Shipping method usage
- Shipping duration

4. Visualization

Used charts and aggregated tables to communicate trends, compare categories, and highlight differences in performance.

Power BI dashboard screenshots are included in the repository.

5. Business Interpretation

Converted the numerical results into business observations and recommendations while distinguishing observed patterns from unverified explanations.

📊 Key Performance Indicators

The following indicators summarize overall sales performance.

KPI| Result
Total Sales| $2,261,536.78
Total Orders| 4,922
Unique Customers| 793
Unique Products| 1,861
Average Order Value| $459.48
Average Sales per Record| $230.77

Metric definitions:

- Total Sales: Sum of all recorded sales values.
- Total Orders: Number of unique order IDs.
- Unique Customers: Number of distinct customer IDs.
- Unique Products: Number of distinct product IDs.
- Average Order Value (AOV): Total sales divided by the number of unique orders.
- Average Sales per Record: Total sales divided by the number of transaction rows.

Average Sales per Record and Average Order Value measure different things and should not be interpreted interchangeably.

💡 Key Business Insights

1. Annual Sales Performance

Year| Total Sales| Year-over-Year Growth
2015| $479,856.21| —
2016| $459,436.01| -4.26%
2017| $600,192.55| +30.64%
2018| $722,052.02| +20.30%

Finding: Sales declined by 4.26% in 2016, then increased by 30.64% in 2017 and 20.30% in 2018.

The highest annual sales occurred in 2018, reaching $722,052.02.

Business implication: Reviewing yearly changes can help businesses identify periods requiring further investigation and understand how performance evolves over time.

2. Monthly Sales Patterns

Month| Total Sales
November| $350,161.71
December| $321,480.17
September| $300,103.41
February| $59,371.12

Finding: November recorded the highest aggregated monthly sales across the four-year period, while February recorded the lowest.

Business implication: Monthly sales patterns can support further investigation into inventory planning and promotional timing.

These aggregated figures alone do not prove that the differences are caused by seasonality.

3. Product Category Performance

Category| Total Sales| Share of Total Sales
Technology| $827,455.87| 36.59%
Furniture| $728,658.58| 32.22%
Office Supplies| $705,422.33| 31.19%

Finding: Technology generated the largest share of total sales, accounting for approximately 36.59%.

Furniture and Office Supplies also contributed substantial shares of overall sales.

Business implication: Businesses can investigate product demand, inventory availability, and category-level purchasing patterns to better understand these differences.

4. Top-Performing Subcategories

Subcategory| Total Sales| Share of Total Sales
Phones| $327,782.45| 14.49%
Chairs| $322,822.73| 14.27%
Storage| $219,343.39| 9.70%
Tables| $202,810.63| 8.97%
Binders| $200,028.78| 8.84%

Finding: Phones ranked first in sales, followed by Chairs. Together, these two subcategories generated approximately 28.76% of total sales.

Business implication: These subcategories are useful candidates for further investigation into demand, pricing, inventory availability, and sales performance.

High sales do not necessarily mean high profitability.

5. Regional Sales Performance

Region| Total Sales| Share of Total Sales
West| $710,219.68| 31.40%
East| $669,518.73| 29.60%
Central| $492,646.91| 21.78%
South| $389,151.46| 17.21%

Finding: The West recorded the highest sales, while the South recorded the lowest.

The West and East together accounted for approximately 61% of total sales.

Business implication: Regional comparisons can help identify areas for deeper market analysis and guide investigation into differences in customer demand and product availability.

6. State-Level Sales Performance

State| Total Sales| Share of Total Sales
California| $446,306.46| 19.73%
New York| $306,361.15| 13.55%
Texas| $168,572.53| 7.45%
Washington| $135,206.85| 5.98%
Pennsylvania| $116,276.65| 5.14%

Finding: California ranked first among states, generating approximately 19.73% of total sales.

California and New York together generated $752,667.61, representing approximately 33.28% of total sales.

Business implication: State-level performance can help businesses identify where further market analysis may be most valuable.

7. City-Level Sales Performance

City| State| Total Sales
New York City| New York| $252,462.55
Los Angeles| California| $173,420.18
Seattle| Washington| $116,106.32
San Francisco| California| $109,041.12
Philadelphia| Pennsylvania| $108,841.75

Finding: New York City recorded the highest sales among the analyzed cities.

Business implication: City-level comparisons can provide more detailed insight into geographic sales distribution and help identify locations for further investigation.

Cities are analyzed together with their states to avoid incorrectly combining locations that share the same city name.

8. Customer Sales Analysis

The ten highest-selling customers collectively generated $143,810.16, approximately 6.36% of total sales.

The highest-selling customer in the dataset was Sean Miller, with recorded sales of $25,043.05.

Among these ten customers, Ken Lonsdale recorded the highest number of orders, with 12.

Finding: Ranking customers by sales and comparing their order counts provides two different views of customer purchasing behavior.

Business implication: Customer-level analysis can help businesses investigate purchasing patterns and identify opportunities for customer engagement.

9. Order Value Distribution

Metric| Result
Total Orders| 4,922
Average Order Value| $459.48
Median Order Value| $151.88
Minimum Order Value| $0.56
Maximum Order Value| $23,661.23

Finding: The average order value is substantially higher than the median order value.

This indicates a right-skewed distribution in which relatively high-value orders influence the average.

Business implication: Median order value and the full distribution of order totals should be examined alongside the average when assessing typical purchasing behavior.

10. Shipping Method Analysis

Shipping Method| Orders| Share of Orders| Average Days to Shipment
Standard Class| 2,945| 59.83%| 5.00
Second Class| 944| 19.18%| 3.24
First Class| 772| 15.68%| 2.19
Same Day| 261| 5.30%| 0.05

Finding: Standard Class was the most frequently used shipping method, accounting for approximately 59.83% of orders.

Same Day was the least frequently used method, accounting for approximately 5.30% of orders.

The average time from order placement to shipment varied by shipping method.

Important distinction: These durations measure the number of days between the order date and the ship date. They do not measure the time taken for a package to reach the customer.

💼 Business Recommendations

Based on the observed results, the following actions are worth investigating:

1. Investigate annual performance: Examine the factors associated with the 2016 decline and the subsequent growth in sales.
2. Review high-sales subcategories: Investigate Phones and Chairs to understand their demand patterns and inventory requirements.
3. Compare regional performance: Examine differences between the West, East, Central, and South regions.
4. Use monthly trends for planning: Investigate recurring monthly patterns before making seasonal inventory or marketing decisions.
5. Understand order values: Examine high-value orders and the distribution of order totals rather than relying only on average order value.
6. Analyze customer purchasing behavior: Compare customer sales, order counts, and order values to understand differences in purchasing patterns.
7. Review shipping operations: Compare shipment timing across shipping methods while considering their different service characteristics.

These recommendations identify areas for further investigation. The current analysis does not establish that any particular action will necessarily increase sales or profitability.

✅ Data Quality Assessment

The data quality checks produced the following results:

Check| Result
Total records| 9,800
Total columns| 21
Missing values| 0
Duplicate full records| 0
Non-positive sales values| 0
Invalid date values| 0
Shipping dates before order dates| 0
Year/month inconsistencies in the checked fields| 0

No records were removed during these checks.

The audit supports the reliability of the checked fields, although it does not guarantee that every value in the original source data is free from error.

📸 Project Screenshots

1. Python Data Analysis

The following screenshots demonstrate the Python analysis workflow and results.

<div align="center"><img src="https://raw.githubusercontent.com/esmailemrany/sales-data-analysis/main/python1.png" width="90%" alt="Python Analysis 1" /><img src="https://raw.githubusercontent.com/esmailemrany/sales-data-analysis/main/python3.png" width="90%" alt="Python Analysis 2" /><img src="https://raw.githubusercontent.com/esmailemrany/sales-data-analysis/main/python4.png" width="90%" alt="Python Analysis 3" /></div>---

2. Data Cleaning and Quality Checks

These screenshots show the data cleaning process and data quality validation.

<div align="center"><img src="https://raw.githubusercontent.com/esmailemrany/sales-data-analysis/main/Data%20cleaning%20python6.png" width="90%" alt="Data Cleaning 1" /><img src="https://raw.githubusercontent.com/esmailemrany/sales-data-analysis/main/Data%20cleaning%20python7.png" width="90%" alt="Data Cleaning 2" /><img src="https://raw.githubusercontent.com/esmailemrany/sales-data-analysis/main/Data%20cleaning%20python8.png" width="90%" alt="Data Cleaning 3" /><img src="https://raw.githubusercontent.com/esmailemrany/sales-data-analysis/main/Data%20cleaning%20python9.png" width="90%" alt="Data Cleaning 4" /><img src="https://raw.githubusercontent.com/esmailemrany/sales-data-analysis/main/Data%20cleaning%20python10.png" width="90%" alt="Data Cleaning 5" /></div>---

3. Power BI Dashboard

The following screenshots showcase the Power BI dashboard and sales analysis visualizations.

<div align="center"><img src="https://raw.githubusercontent.com/esmailemrany/sales-data-analysis/main/PowerBi.png" width="90%" alt="Power BI Dashboard 1" /><img src="https://raw.githubusercontent.com/esmailemrany/sales-data-analysis/main/PowerBi1.png" width="90%" alt="Power BI Dashboard 2" /><img src="https://raw.githubusercontent.com/esmailemrany/sales-data-analysis/main/PowerBi2.png" width="90%" alt="Power BI Dashboard 3" /><img src="https://raw.githubusercontent.com/esmailemrany/sales-data-analysis/main/Power%20Bi3.png" width="90%" alt="Power BI Dashboard 4" /><img src="https://raw.githubusercontent.com/esmailemrany/sales-data-analysis/main/Power%20Bi5.png" width="90%" alt="Power BI Dashboard 5" /></div>

⚠️ Project Limitations

- The dataset covers 2015–2018 and should not be treated as a representation of current market conditions.
- The dataset does not contain a "Profit" column. Therefore, this analysis cannot establish product profitability, profit margins, or which products are most profitable.
- Recorded sales are not equivalent to profit or cash collected.
- Observed trends do not establish causation.
- Monthly totals alone do not prove seasonality.
- Shipping duration measures the time between order placement and shipment, not final delivery time.
- The current repository contains the dataset and screenshots, but the executable analysis notebook is not yet included.

🚀 Future Improvements

Potential extensions include:

- Adding the complete, executable Python analysis notebook.
- Improving the Power BI report with additional interactive filters.
- Developing sales forecasting models.
- Performing customer segmentation.
- Conducting profitability analysis if suitable profit and cost data become available.
- Adding automated data quality checks.
- Exploring more detailed product, customer, and geographic trends.

📂 Repository Structure

The repository currently contains:

sales-data-analysis/
├── sales.csv
├── README.md
├── requirements.txt
├── .gitignore
├── MIT License
├── images/
├── python1.png
├── python3.png
├── python4.png
├── Data cleaning python6.png
├── Data cleaning python7.png
├── Data cleaning python8.png
├── Data cleaning python9.png
├── Data cleaning python10.png
├── PowerBi.png
├── PowerBi1.png
├── PowerBi2.png
├── Power Bi3.png
└── Power Bi5.png

The "images/" directory is currently empty; the screenshots are stored in the repository's root directory.

👤 Author

Esmaile Emrany

GitHub: "esmailemrany" (https://github.com/esmailemrany)

---

This project demonstrates exploratory data analysis, data quality validation, aggregation, visualization, and business-oriented interpretation using retail sales data.
