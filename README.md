# Power-bi
This Power BI project provides a comprehensive dashboard for analyzing sales and operational data for "blinkit," India's last-minute app. The dashboard is designed to offer quick insights into key performance indicators (KPIs), sales trends, product performance, outlet characteristics, and customer feedback. It leverages various interactive visualizations and a filter panel to enable granular analysis.

**Overall Dashboard Layout and Key Metrics:**

The dashboard is structured with a clear top-level summary, followed by more detailed breakdowns. The top section immediately presents four crucial KPIs:
* **Total Sales:** $1.20M, indicating the overall revenue generated.
* **Avg Sales:** $141, representing the average sales per transaction or item.
* **No. of Items:** 8523, showing the total number of items sold.
* **Avg Rating:** 3.9, reflecting customer satisfaction.

These high-level metrics provide an immediate snapshot of the business's performance.

**Filter Panel for Granular Analysis:**

On the left-hand side, a "FILTER PANEL" allows users to drill down into specific segments of the data. This panel includes dropdown filters for:
* **Outlet Location Type:** Enables analysis based on the type of location where outlets are situated.
* **Outlet Size:** Allows filtering by the size of the outlets (e.g., small, medium, large).
* **Item Type:** Provides the ability to focus on specific categories of products.
* **Item:** Offers filtering by individual items, allowing for very specific product performance analysis.

This interactive filter panel is crucial for slicing and dicing the data to answer specific business questions.

**Sales and Item Performance Breakdown:**

The central part of the dashboard delves into sales and item-level performance. This section is organized with tabs for "Total Sales," "Avg Sales," "No. of Items," and "Avg Rating," allowing users to toggle between different perspectives of the same data.

* **FAT CONTENTS - Total Sales:** A donut chart visually represents the proportion of total sales contributed by "Low Fat" ($425.36K) and "Regular" ($776.32K) items. This immediately highlights that "Regular" items account for a significantly larger share of sales.

* **ITEM TYPE - Sales:** A horizontal bar chart displays sales figures for various item types, with "Fruits and Vegetables" leading at $0.18M, followed by "Snack Foods" at $0.18M, and so on. This visualization helps identify top-selling product categories and areas for potential focus. The long tail of less profitable items is also evident, indicating a diverse product offering.

* **FAT BY OUTLET - Sales:** A stacked bar chart breaks down sales by "Low Fat" and "Regular" items across different "Tier" outlets (Tier 3, Tier 2, Tier 1). Tier 3 has the highest sales for both Low Fat ($0.30M) and Regular ($0.17M) items, suggesting its importance in overall revenue generation. Tier 2 and Tier 1 follow, providing insights into the performance of different outlet tiers based on fat content.

**Outlet and Establishment Insights:**

The right side of the dashboard focuses on outlet-related metrics and trends.

* **OUTLET ESTABLISHMENT:** A line chart tracks the establishment of outlets over time, showing a fluctuating trend. There's a notable peak in outlet establishment around 2018 ($205K) and 2019 ($199K), followed by a decline in subsequent years. This trend could indicate periods of aggressive expansion or market saturation. The Y-axis represents the establishment cost or investment, suggesting that 2018-2019 saw the highest investment in new outlets.

* **OUTLET SIZE:** A donut chart shows the distribution of sales based on "Outlet Size" – "Medium" ($507.90K), "Small" ($444.79K), and "High" (likely a smaller share, although the exact value isn't clearly visible from the image, it's represented by the remaining portion of the circle). This indicates that medium and small outlets contribute significantly to total sales.

* **OUTLET LOCATION:** A horizontal bar chart visualizes sales across different "Outlet Location" tiers (Tier 3, Tier 2, Tier 1). Tier 3 leads with $472.13K in sales, followed by Tier 2 ($393.15K) and Tier 1 ($336.40K). This suggests that Tier 3 locations are the most lucrative, potentially due to higher population density or better market positioning.

* **OUTLET TYPE - Detailed Table:** A table provides a detailed breakdown of performance by "Outlet Type." It includes "Total sales," "No. of Items," "Avg Sales," "Avg Rating," and "Item Visibility" for "Supermarket Type3," "Supermarket Type2," "Supermarket Type1," and "Grocery Store."
    * "Grocery Store" has the highest "Total sales" ($151.94K) and "No. of Items" (1083), but a lower "Avg Sales" ($140) compared to "Supermarket Type2" and "Supermarket Type3." It also has the highest "Item Visibility" (0.10).
    * "Supermarket Type1" has significantly higher "Total sales" ($787.55K), suggesting it might represent a different aggregation or a very large category of outlets, contributing the most to overall revenue. However, its individual rows are not directly comparable to other supermarket types. This might be a summary row or a parent category.
    * Comparing "Supermarket Type2" ($131.48K total sales, 928 items, $142 avg sales) and "Supermarket Type3" ($130.71K total sales, 935 items, $140 avg sales), they show similar performance in terms of total sales and items sold, with comparable average sales and ratings.

**Potential Insights and Business Value:**

This Power BI dashboard offers numerous opportunities for actionable insights:
* **Sales Strategy:** The breakdown by fat content and item type can inform product development and marketing strategies. For instance, understanding why "Regular" items sell more or identifying top-performing item types can lead to targeted promotions.
* **Outlet Optimization:** The analysis of outlet size, location, and establishment trends can guide future expansion plans and resource allocation. Identifying the most profitable outlet tiers and types can help prioritize investments.
* **Inventory Management:** Insights into item sales and visibility can aid in optimizing inventory levels and ensuring popular items are always in stock.
* **Customer Satisfaction:** The "Avg Rating" KPI and its potential breakdown (if further explored through filters) can highlight areas for improving customer experience.
* **Performance Monitoring:** The dashboard serves as a real-time monitoring tool for key business metrics, allowing stakeholders to quickly assess overall performance and identify any deviations.

In conclusion, this Power BI project provides a robust and interactive platform for analyzing Blinkit's operational and sales data. Its intuitive design and comprehensive visualizations empower users to gain valuable insights, make data-driven decisions, and ultimately drive business growth.
