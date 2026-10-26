📊 Sales Data Analysis

An end-to-end exploratory sales data analysis project using Python, Pandas, NumPy, data visualization, and Power BI. This project examines sales performance across time, products, customers, and geographic regions to identify business patterns and support data-driven decision-making.

📌 Project Overview

This project analyzes a retail sales dataset containing 9,800 records and 21 columns, covering transactions from 2015 to 2018 across the United States.

The analysis focuses on understanding sales trends, identifying high-performing product categories and locations, examining customer purchasing patterns, and evaluating shipping behavior.

🎯 Business Problem

Sales data can reveal valuable business patterns, but raw transaction records are difficult to interpret without structured analysis.

This project transforms raw sales data into actionable insights by answering questions such as:

- How have sales changed over time?
- Which product categories and subcategories generate the most sales?
- Which regions, states, and cities contribute most to total sales?
- How are sales distributed across customers and orders?
- Which shipping methods are most frequently used?
- How long does each shipping method take from order placement to shipment?

🛠️ Tools & Technologies

- Python — Data analysis and processing
- Pandas — Data manipulation and aggregation
- NumPy — Numerical operations
- Matplotlib & Seaborn — Data visualization
- Power BI — Interactive business reporting
- Jupyter / Google Colab — Analysis environment
- Git & GitHub — Version control and project documentation

🔍 Project Workflow

1. Data Understanding and Quality Checks

- Inspected dataset dimensions, columns, and data types.
- Checked for missing values and duplicate full records.
- Validated order and shipping dates.
- Checked sales values for missing or non-positive entries.
- Verified date consistency, including year and month fields.
- Confirmed that shipping dates were not earlier than order dates.

Data quality results: The audit found no missing values, duplicate full rows, invalid dates, or non-positive sales values.

No records needed to be removed during these checks.

2. Exploratory Data Analysis (EDA)

The analysis covered:

- Annual and monthly sales trends
- Sales by category and subcategory
- Regional, state, and city performance
- Customer-level sales analysis
- Order value distribution
- Shipping method usage
- Shipping duration by shipping method

3. Data Visualization and Reporting

Charts and aggregated tables were used to compare performance, identify patterns, and communicate findings.

Power BI was used to present sales performance through dashboard visualizations.

📈 Key Performance Indicators (KPIs)

Metric| Result
Total Sales| $2,261,536.78
Total Orders| 4,922
Unique Customers| 793
Unique Products| 1,861
Average Order Value| $459.48
Average Sales per Record| $230.77

Note: Average Order Value is calculated by summing sales for each unique order and then averaging the order totals. Average Sales per Record is calculated at the individual transaction-row level.

💡 Key Business Insights

1. Annual Sales Performance

Year| Total Sales| Year-over-Year Growth
2015| $479,856.21| —
2016| $459,436.01| -4.26%
2017| $600,192.55| +30.64%
2018| $722,052.02| +20.30%

Insight: Sales declined by 4.26% in 2016 before increasing by 30.64% in 2017 and 20.30% in 2018. The highest annual sales occurred in 2018.

Business implication: Comparing yearly performance can help businesses identify periods of growth or decline and investigate the factors behind those changes.

2. Product Category Performance

Category| Total Sales| Share of Total Sales
Technology| $827,455.87| 36.59%
Furniture| $728,658.58| 32.22%
Office Supplies| $705,422.33| 31.19%

Insight: Technology generated the largest share of sales, accounting for approximately 36.59% of total revenue.

Business implication: Businesses can investigate the products and customer needs contributing to Technology sales before making inventory or marketing decisions.

3. Top-Performing Subcategories

Subcategory| Total Sales| Share of Total Sales
Phones| $327,782.45| 14.49%
Chairs| $322,822.73| 14.27%
Storage| $219,343.39| 9.70%
Tables| $202,810.63| 8.97%
Binders| $200,028.78| 8.84%

Insight: Phones ranked first in total sales, followed closely by Chairs. Together, these two subcategories contributed approximately 28.76% of total sales.

Business implication: These subcategories are useful candidates for further investigation into demand, stock availability, pricing, and sales trends.

4. Regional Sales Performance

Region| Total Sales| Share of Total Sales
West| $710,219.68| 31.40%
East| $669,518.73| 29.60%
Central| $492,646.91| 21.78%
South| $389,151.46| 17.21%

Insight: The West region recorded the highest sales, while the South recorded the lowest. Together, the West and East accounted for approximately 61% of total sales.

Business implication: Regional comparisons can help prioritize further investigation into customer demand, product availability, and opportunities in lower-performing regions.

5. Geographic Concentration

- California generated $446,306.46, approximately 19.73% of total sales.
- New York generated $306,361.15, approximately 13.55% of total sales.
- New York City recorded $252,462.55, approximately 11.16% of total sales.

Insight: California was the highest-performing state, while New York City was the highest-performing city by sales.

Business implication: Geographic sales patterns can guide more detailed market analysis and help businesses evaluate where additional sales opportunities may exist.

6. Customer and Order Value Analysis

- Total unique customers: 793
- Average order value: $459.48
- Median order value: $151.88
- Highest order value: $23,661.23

Insight: The average order value was substantially higher than the median, indicating a right-skewed order value distribution. A relatively small number of high-value orders may influence the average.

Business implication: Median order value and the distribution of order totals should be considered alongside the average when evaluating typical customer purchases.

7. Monthly Sales Patterns

- November recorded the highest aggregated monthly sales at $350,161.71.
- February recorded the lowest aggregated monthly sales at $59,371.12.

Insight: Sales varied considerably across calendar months, with November showing the highest total across the four-year dataset.

Business implication: Monthly patterns can help inform further investigation into inventory planning and promotional timing. These aggregated results alone do not establish the cause of the differences or prove a recurring seasonal effect.

8. Shipping Method Analysis

Shipping Method| Total Orders| Share of Orders| Average Days to Shipment
Standard Class| 2,945| 59.83%| 5.00
Second Class| 944| 19.18%| 3.24
First Class| 772| 15.68%| 2.19
Same Day| 261| 5.30%| 0.05

Insight: Standard Class was the most frequently used shipping method, accounting for approximately 59.83% of orders. Same Day was the least frequently used.

The average time from order placement to shipment varied across shipping methods.

Important distinction: Shipping duration is calculated as the difference between the order date and ship date. It does not measure the time taken for the package to reach the customer.

💼 Business Recommendations

Based on the observed results, the following actions are worth investigating:

1. Investigate sales growth: Examine what changed between 2016 and 2018 before attributing growth to a specific cause.
2. Review product demand: Study Phones, Chairs, and other high-sales subcategories to inform inventory and merchandising decisions.
3. Compare regional performance: Investigate differences between the West, East, Central, and South regions.
4. Improve monthly planning: Use monthly sales patterns as a starting point for more detailed demand analysis.
5. Evaluate order values: Examine high-value orders and the distribution of order totals rather than relying on the average alone.
6. Review shipping operations: Compare shipping methods and shipment timing while considering the service characteristics of each method.

These are data-informed recommendations for further investigation, not proof that a particular business action will increase revenue.

🖼️ Project Screenshots

Python Data Analysis

"Python Analysis" (python1.png)

"Python Data Cleaning" (Data%20cleaning%20python6.png)

Power BI Dashboard

"Power BI Dashboard" (PowerBi.png)

"Power BI Dashboard View" (PowerBi1.png)

"Power BI Dashboard View" (Power%20Bi3.png)

⚠️ Data Limitations

- The dataset covers transactions from 2015 through 2018 and should not be treated as a representation of current market conditions.
- The dataset does not contain a "Profit" column. Therefore, this project does not establish product profitability, profit margins, or the most profitable categories.
- Sales figures describe recorded sales, not profit or cash collected.
- Observed relationships and trends do not, by themselves, establish causation.
- Shipping duration measures the time between order placement and shipment, not final delivery time.

🚀 Future Improvements

Potential extensions include:

- Sales forecasting using time-series methods
- Customer segmentation
- Profitability analysis if suitable cost and profit data become available
- More detailed product and geographic analysis
- Enhanced Power BI reporting and interactive filtering
- Automated data quality checks

📁 Repository Contents

The repository includes the sales dataset, project screenshots, dependency information, and documentation.

- "sales.csv" — Sales dataset
- "images/" — Project images and visual assets
- "requirements.txt" — Python dependencies
- ".gitignore" — Git exclusion rules
- "README.md" — Project documentation
- "LICENSE" — Project license

👤 Author

Esmaile Emrany

GitHub: "@esmailemrany" (https://github.com/esmailemrany)

---

This project demonstrates data cleaning validation, exploratory data analysis, aggregation, visualization, and business-oriented interpretation using retail sales data.
