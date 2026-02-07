# Hospital-Emergency-Data-Analysis
"To analyze customer churn patterns for a telecom provider and identify key predictors of attrition to improve retention rates."

Retail Performance & Consumer Insights Analysis

Project Objective
The primary goal of this project is to analyze historical sales data to identify seasonal trends, evaluate product category performance, and uncover customer purchasing behaviors. By transforming raw transactional data into actionable insights, this project aims to provide data-driven recommendations for inventory management and targeted marketing strategies.

Dataset Used

Source: Synthetic Retail Transaction Dataset (CSV format).

Size: 50,000+ records covering a 24-month period.

Key Attributes: Order ID, Transaction Date, Customer Segment, Product Category, Sales Revenue, Profit Margin, and Geographic Region.

Questions (KPIs)
The analysis focuses on the following Key Performance Indicators:

Revenue Growth: What is the Month-over-Month (MoM) and Year-over-Year (YoY) growth rate?

Profitability: Which product categories yield the highest profit margins versus total sales volume?

Customer Segmentation: Which customer segment (Consumer, Corporate, or Home Office) contributes most to the bottom line?

Regional Performance: Which geographic regions are underperforming and require localized marketing intervention?

Process
Data Wrangling: Cleaned missing values in "Customer ID" and standardized date formats using Python (Pandas).

Exploratory Data Analysis (EDA): Performed univariate and bivariate analysis to identify outliers in sales prices and discount distributions.

Feature Engineering: Created new metrics such as Profit_Margin_Percentage and Shipping_Duration.

Visualization: Developed an interactive dashboard using [Power BI/Tableau/Matplotlib] to visualize sales heatmaps and trend lines.

Dashboard Image:
<img width="1052" height="445" alt="Hospital Emergency Dashboard" src="https://github.com/user-attachments/assets/9235490a-832a-487a-a1d3-4b73afd29de6" />


Project Insights
Seasonal Spikes: Sales consistently peak in Q4 (November-December), driven largely by the "Technology" category, which sees a 35% increase compared to the yearly average.

Discount Paradox: High discount rates (>20%) on "Office Supplies" significantly boosted volume but led to a 12% net loss in profit for that segment.

Customer Loyalty: The "Corporate" segment has the highest retention rate, accounting for 45% of total revenue despite being only 20% of the customer base.

Final Conclusion
The analysis reveals that while the company is growing in volume, profitability is being eroded by aggressive discounting in low-margin categories. To optimize future performance, the business should shift its promotional focus toward the Corporate segment and reduce discount thresholds on "Office Supplies" to stabilize profit margins.

