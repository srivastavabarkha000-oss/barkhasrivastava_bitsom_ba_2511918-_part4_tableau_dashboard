# barkhasrivastava_bitsom_ba_2511918-_part4_tableau_dashboard

#### Retail Executive Dashboard using Tableau

##### Business Problem Summary

Retail leadership requires a centralized executive dashboard to monitor key business performance indicators across sales, profitability, customer segments, product categories, shipping performance, discount effectiveness, and product returns. The objective is to transform transactional retail data into meaningful business insights that support strategic decision-making, improve operational efficiency, and identify growth opportunities.

This project develops an interactive Tableau dashboard that enables executives to monitor overall business health, explore performance across multiple dimensions, and make data-driven decisions.

\---

###### Dataset Description

The dashboard is built using a retail transactional dataset containing customer orders, product information, shipping details, and financial metrics.

###### Dataset Includes

###### Date Fields

* Order Date
* Ship Date

###### Geographic Fields

* Region
* State
* City

###### Customer Information

* Customer ID
* Customer Segment

###### Product Information

* Category
* Sub-Category
* Product Name

###### Sales Metrics

* Sales
* Profit
* Quantity
* Discount

###### Shipping Information

* Ship Mode
* Delivery Days

###### Additional Fields

* Return Flag
* Campaign Channel

The dataset was inspected to ensure correct data types, remove inconsistencies, and prepare it for Tableau analysis.

\---

###### Tableau Workbook Description

The Tableau workbook contains one executive dashboard supported by multiple analytical worksheets.

###### Worksheets Included

* Sales Trend
* Regional Performance
* Category Profitability
* Customer Segment Performance
* Shipping Performance
* Discount vs. Profit Analysis
* Return Analysis

###### Executive Dashboard

The dashboard combines these worksheets into a single interactive view, enabling leadership to monitor business performance from financial, operational, and customer perspectives.

\---

###### Calculated Fields Created

The following calculated fields were created in Tableau:

|Calculated Field|Description|
|-|-|
|Profit Margin|Calculates Profit ÷ Sales to measure profitability.|
|Cost|Calculates Sales − Profit to estimate business cost.|
|Average Order Value|Calculates average revenue generated per order.|
|Return Rate|Calculates Returned Orders ÷ Total Orders.|
|Shipping Delay Bucket|Categorizes delivery days into meaningful business groups.|
|Discount Category *(Optional)*|Groups discounts into No, Low, Medium, and High categories.|
|Profit Status *(Optional)*|Identifies profitable and loss-making transactions.|

These calculated fields support profitability analysis, operational monitoring, and executive decision-making.

\---

###### Dashboard Components

The executive dashboard includes the following components:

###### KPI Cards

* Total Sales
* Total Profit
* Profit Margin
* Average Order Value
* Return Rate

###### Visualizations

* Sales Trend (Line Chart)
* Regional Performance (Bar Chart/Map)
* Category Profitability (Stacked Bar Chart)
* Customer Segment Performance (Grouped Bar Chart)
* Shipping Performance (Grouped Bar Chart)
* Discount vs. Profit (Scatter Plot)
* Return Analysis (Horizontal Bar Chart)

The dashboard presents a complete view of retail performance while maintaining a clean and business-friendly layout.

\---

###### Filters and Interactions Used

###### Interactive Filters

* Region
* Category
* Customer Segment
* Order Date
* Ship Mode
* Campaign Channel

###### Dashboard Actions

Interactive filter actions allow users to click on a region or category and automatically update all related charts, enabling deeper analysis without leaving the dashboard.

\---

##### Key Business Insights

The dashboard provides several actionable business insights:

* Sales remain stable over time with noticeable seasonal fluctuations.
* The South region generates the highest sales and profit.
* Technology is the most profitable product category.
* Home Office customers contribute the highest revenue and profitability.
* Higher discount levels significantly reduce average profit margins.
* Same Day shipping delivers the highest average profit.
* Furniture products have the highest return rate among all categories.
* Business growth opportunities exist by expanding profitable categories while reducing losses from excessive discounting and product returns.

\---

##### Dashboard Story Summary

The dashboard follows a logical business narrative that begins with executive KPIs and progressively explores the drivers behind business performance.

Leadership first gains an overview of sales and profitability through KPI cards. Sales trends then reveal changes over time, while regional analysis identifies geographic strengths and weaknesses. Category and customer segment analyses explain which products and customer groups contribute most to revenue and profit.

Operational performance is evaluated through shipping and delivery analysis, while discount analysis demonstrates the relationship between pricing strategy and profitability. Finally, return analysis highlights quality or operational issues that require management attention.

Together, these insights enable leadership to identify business opportunities, monitor risks, and make informed strategic decisions.

\---

##### Assumptions and Limitations

###### Assumptions

* Each record represents one order line.
* Order ID uniquely identifies customer orders.
* Sales and Profit values are complete and accurate.
* Delivery Days correctly measure shipping duration.
* Return Flag accurately indicates returned orders.
* Geographic information is sufficient for regional analysis.

###### Limitations

* The dashboard uses historical transactional data only.
* External market conditions, competitor information, and economic factors are not included.
* Inventory availability and customer demographic data are outside the project scope.
* Business insights depend on the accuracy and completeness of the source data.

\---

###### Screenshots Included

The project includes screenshots of:

* Executive Dashboard
* Sales Trend Analysis
* Regional Performance
* Category Profitability
* Customer Segment Performance
* Shipping Performance
* Discount vs. Profit Analysis
* Return Analysis

These screenshots demonstrate the completed Tableau workbook, dashboard layout, and interactive visualizations.

\---

###### Project Outcome

This Tableau Executive Dashboard transforms retail transaction data into an interactive business intelligence solution. By integrating sales, profitability, customer behavior, shipping performance, discounts, and return analysis into a single dashboard, it enables leadership to monitor business performance, identify operational risks, uncover growth opportunities, and support data-driven strategic decision-making.

