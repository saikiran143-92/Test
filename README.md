**Amazon Sales Dashboard**


**##Problem Statement:**
This dashboard is designed to analyze Amazon’s sales data, highlighting the key factors that impact sales performance. By uncovering trends and patterns, it provides valuable insights to refine sales strategies, boost profitability, and enhance customer engagement across different product categories and regions.

**##Dataset Explanation:**

•	Order Details:
o	Order ID: Unique identifier for each customer order.
o	Order Date: Date when the order was placed.
o	Ship Date: Date when the order was shipped.
o	Ship Mode: Method of shipping used for the order.
•	Customer Information:
o	Customer ID: Unique identifier for each customer.
o	Customer Name: Name of the customer.
o	Segment: Customer segment (e.g., Consumer, Corporate).
•	Shipping & Location:
o	Country: Destination country of the order.
o	City: Destination city of the order.
o	State: State or province where the order was delivered.
o	Region: Geographic region of order delivery.
•	Product Information:
o	Product ID: Unique identifier for each product.
o	Product Name: Name of the product.
o	Category: Product category (e.g., Electronics, Home Appliances).
o	Sub-Category: Specific sub-category of the product.
•	Sales & Performance Metrics:
o	Sales: Total revenue generated from the order.
o	Quantity: Number of units ordered.
o	Discount %: Discount percentage applied to the order.
o	Profit: Profit earned from the order (Revenue - Cost).
o	Shipment Cost: Cost incurred for shipping the order.



**##Steps Followed in Building the Amazon Sales Dashboard**

**1. Data Preparation**

•	Data Loading: Import the Amazon sales dataset into Power BI Desktop. Navigate to the Home tab, click Get Data, and select the appropriate file format.

•	Data Quality Check: Open Power Query Editor to inspect data quality, checking for anomalies, missing values, and errors by selecting Transform Data.

•	Error & Missing Values Handling: Identify and correct errors, filter for empty values, and remove irrelevant data if necessary.

•	Data Profiling: Utilize Data Profiling tools in Power Query to understand column statistics, distributions, and potential data cleaning needs.

•	Data Cleaning: Replace or remove null values and handle any errors using Remove Errors or Replace Errors functions in Power Query.

**2. Building Key Metrics & Visualizations**
•	Total Metrics Cards: Display key metrics such as Total Sales, Total Quantity, Total Profit, and Total Shipment Cost using Card Visuals.


**•	Sales Trend Analysis:**

o	Line Chart: Visualize sales trends over time, using Order Date on the axis and Sales on the values to track monthly and yearly sales performance.

•	Sales by Product & Category:

o	Column Chart: Show total sales per product category by placing Category on the axis and Sales on values.

o	Treemap: Highlight revenue and profit distribution across different Categories and Sub-Categories.

•	Regional Sales & Profit Analysis:

o	Bar Chart by Region: Compare Sales and Profit variations across different regions.

o	Map Visualization: Represent the geographic distribution of customers, ranking states by profit.

•	Customer Segmentation Analysis:

o	Scatter Chart: Compare sales and profit across customer segments by product categories, using Category on the axis, Segment as the legend, and Sales and Profit as values.

**
##Key Insights from the Amazon Sales Dashboard**

1. Overall Sales & Profit Performance
•	The total sales revenue is $2.30M, with a profit of $0.29M, resulting in a profit margin of 12.6%.
•	There is potential to improve profit margins through cost reduction strategies or optimized pricing models.

2. Sales Growth Over Time
•	Sales have shown a steady upward trend from 2014 to 2017, with 2017 recording the highest sales.
•	This growth pattern indicates a positive business trajectory, suggesting strong market demand and potential for further expansion.

3. Performance by Category
•	Technology leads in total sales, followed by Furniture and Office Supplies.
•	This highlights that Technology products drive revenue, while Furniture and Office Supplies remain significant contributors to sales.

4. Regional Sales & Profitability
•	The West region outperforms all other regions in both sales and profit, indicating a strong market presence.
•	The South region has the lowest sales and profit, suggesting a need for market expansion efforts or strategic adjustments to improve performance.

5. Sales & Profit by Category and Customer Segment
•	The Consumer segment in Furniture contributes significantly to total sales, followed closely by Office Supplies.
•	Targeting high-value consumer segments within these categories could lead to increased profitability.

6. Profitability by State
•	Profitability varies across states, with some performing significantly better than others.
•	A state-wise strategy could be implemented to maximize profits in high-performing states while identifying opportunities for growth in lower-performing areas.

7. Sales Distribution by Sub-Category
•	Machines and phones are the top-selling items in the Technology category.
•	Chairs and tables contribute significantly to Furniture sales.
•	This insight can help businesses optimize inventory management and focus marketing efforts on high-performing sub-categories.

**##Strategic Recommendations for Amazon Sales Improvement:**

1. Enhance Profit Margins
•	Analyze cost structures and pricing strategies to improve profitability.
•	Focus on high-profit categories like Technology while controlling costs in Furniture and Office Supplies.
•	Consider negotiating better supplier deals or optimizing shipping costs to reduce expenses.

2. Targeted Marketing Efforts
•	Leverage the strong sales performance in the West region by increasing marketing efforts and offering region-specific promotions.
•	Develop localized marketing strategies to boost sales in the South region, such as special discounts or strategic partnerships with local businesses.

3. Focus on High-Value Customer Segments
•	Prioritize marketing and sales efforts on consumer segments in Furniture and Office Supplies, as they contribute significantly to revenue.
•	Introduce loyalty programs, targeted discounts, or bundle offers to increase repeat purchases.

4. Optimize State-Level Strategies
•	Identify high-profit states and increase investments to maximize revenue from top-performing areas.
•	Conduct a deep analysis of lower-profit states to identify and mitigate factors causing underperformance.
•	Tailor promotional campaigns based on regional buying behaviors.

5. Improve Inventory Management
•	Optimize stock levels for high-demand sub-categories like machines, phones, chairs, and tables to avoid stockouts.
•	Use demand forecasting tools to ensure efficient inventory replenishment and reduce overstock.

6. Expand into New Markets
•	Utilize geographic and customer purchase data to identify new potential markets for expansion.
•	Strengthen online presence in underperforming regions through targeted digital marketing campaigns.

7. Optimize Shipping and Delivery Processes
•	Reduce shipping costs by improving logistics and supplier management.
•	Offer faster delivery options to enhance customer satisfaction and increase repeat purchases.

By implementing these strategies, Amazon can increase profitability, strengthen market presence, and enhance customer experience through better cost management, targeted marketing, and optimized operations.

Screenshot Of AMAZON Sales Dashboard-(POWER BI)
![Image](https://github.com/user-attachments/assets/69364d12-820b-4ff8-b036-23244939f6cd)
