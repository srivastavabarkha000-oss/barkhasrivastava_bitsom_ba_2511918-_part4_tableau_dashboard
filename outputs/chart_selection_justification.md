#### Chart Selection Justification

##### 1\. Category Profitability (Treemap)

###### Business Question

* Which product categories and sub-categories contribute the most profit?
* Which categories should leadership prioritize for growth?

###### Why this Chart Type?

A treemap efficiently displays hierarchical data while allowing executives to compare the relative contribution of categories and sub-categories in a compact space.

###### Visual Encoding

* **Size:** Profit
* **Color:** Profit intensity (darker color indicates higher profit)
* **Label:** Category, Sub-category, Profit Value
* **Filter:** Category

###### Design Principle Applied

* Uses pre-attentive visual attributes (size and color) to quickly highlight the most profitable areas.
* Maximizes information density without overcrowding the dashboard.

###### Mistake Avoided

* Avoided using multiple bar charts for numerous sub-categories, which would consume more dashboard space and reduce readability.

\---

##### 2\. Profit vs Sales by Region (Side-by-Side Bar Chart)

###### Business Question

* Which region generates the highest sales?
* Are high-sales regions also the most profitable?

###### Why this Chart Type?

Grouped bars enable easy comparison of two business metrics (Sales and Profit) across regions.

###### Visual Encoding

* **X-axis:** Region
* **Y-axis:** Value
* **Color:** Measure (Sales vs Profit)
* **Label:** Sales and Profit Values

###### Design Principle Applied

* Supports direct comparison between two related KPIs.
* Uses consistent color coding for better interpretation.

###### Mistake Avoided

* Avoided stacked bars because they make it difficult to compare individual measures accurately.

\---

##### 3\. Sales by Region (Bar Chart)

###### Business Question

* Which region contributes the highest sales revenue?
* Which regions require additional sales efforts?

###### Why this Chart Type?

Bar charts provide the clearest comparison of sales across discrete regions.

###### Visual Encoding

* **X-axis:** Region
* **Y-axis:** Sales
* **Color:** Region
* **Filter:** Dashboard filters

###### Design Principle Applied

* Simple comparison using aligned bars.
* Easy for executives to identify the highest and lowest performing regions.

###### Mistake Avoided

* Avoided pie charts because regional sales comparisons are more accurate with bar lengths than angles.

\---

##### 4\. Discount vs Profit (Scatter Plot)

###### Business Question

* Does offering larger discounts reduce profitability?
* Are there any outliers with unusually high profit or discount?

###### Why this Chart Type?

Scatter plots are ideal for identifying relationships, trends, and outliers between two continuous variables.

###### Visual Encoding

* **X-axis:** Profit
* **Y-axis:** Discount
* **Color:** Category
* **Label:** Profit Value
* **Filter:** Category

###### Design Principle Applied

* Makes correlation patterns immediately visible.
* Highlights unusual observations that may require business investigation.

###### Mistake Avoided

* Avoided line charts because discount and profit do not have a sequential relationship.

\---

##### 5\. Return Analysis (Highlight Table)

###### Business Question

* Which customer segments experience the highest return rates across regions?
* Where should return reduction strategies be focused?

###### Why this Chart Type?

A highlight table combines numerical values with color intensity, making high-return areas immediately noticeable.

###### Visual Encoding

* **Rows:** Customer Segment
* **Columns:** Region
* **Color:** Return Rate
* **Label:** Return Percentage

###### Design Principle Applied

* Uses color intensity to emphasize problem areas.
* Allows quick comparison across multiple dimensions simultaneously.

###### Mistake Avoided

* Avoided standard tables that require users to read every value individually.

\---

##### 6\. Sales Trend (Line Chart)

###### Business Question

* How have monthly sales changed throughout the year?
* Are there seasonal peaks or declines?

###### Why this Chart Type?

A line chart is the most effective visualization for displaying trends over time.

###### Visual Encoding

* **X-axis:** Month
* **Y-axis:** Sales
* **Labels:** Monthly Sales Values
* **Filter:** Dashboard filters

###### Design Principle Applied

* Clearly illustrates continuous changes over time.
* Uses data labels to improve readability without clutter.

###### Mistake Avoided

* Avoided bar charts because they make long-term trend identification more difficult.

\---

##### 7\. Customer Segment Performance (Treemap)

###### Business Question

* Which customer segment contributes the most profit?
* Which segment should receive greater business focus?

###### Why this Chart Type?

A treemap effectively compares proportional contributions while using minimal dashboard space.

###### Visual Encoding

* **Size:** Profit
* **Color:** Customer Segment
* **Label:** Segment Name and Profit

###### Design Principle Applied

* Supports rapid identification of the highest contributing customer segment.
* Efficient use of dashboard real estate.

###### Mistake Avoided

* Avoided multiple pie charts, which make comparison of segment contributions less accurate.

\---

##### 8\. Shipping Performance (Highlight Table)

###### Business Question

* Which shipping modes experience longer delivery times?
* Which shipping methods perform best across delay buckets?

###### Why this Chart Type?

A highlight table efficiently compares shipping performance across multiple shipping modes and delay categories.

###### Visual Encoding

* **Rows:** Shipping Delay Bucket
* **Columns:** Ship Mode
* **Color:** Performance Value
* **Label:** Numeric Value

###### Design Principle Applied

* Uses heat-map coloring to quickly identify shipping bottlenecks.
* Allows comparison across two categorical dimensions simultaneously.

###### Mistake Avoided

* Avoided clustered bar charts, which would require significantly more dashboard space and reduce readability.

\---

##### Overall Dashboard Design Principles

The Executive Dashboard was designed to support leadership decision-making by presenting key business metrics in a logical flow:

1. **Profitability** – Identify profitable product categories.
2. **Regional Performance** – Compare sales and profit across regions.
3. **Sales Monitoring** – Track monthly sales trends.
4. **Customer Insights** – Evaluate customer segment contribution.
5. **Discount Analysis** – Understand the impact of discounts on profit.
6. **Operational Performance** – Monitor returns and shipping efficiency.

###### Design Principles Applied

* Consistent color palette across all charts.
* Appropriate chart selection based on data type.
* Minimal visual clutter with clear titles and labels.
* Balanced dashboard layout for executive readability.
* Interactive filters to support detailed exploration.

###### Common Visualization Mistakes Avoided

* No unnecessary 3D charts.
* No overloaded pie charts.
* No excessive use of colors.
* No duplicated information across charts.
* Limited labels to essential values to maintain clarity.
* Appropriate chart types selected for categorical, geographical, and time-series data.

