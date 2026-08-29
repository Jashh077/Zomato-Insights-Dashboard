# Zomato-Insights-Dashboard
An interactive Power BI dashboard that analyzes Zomato-style food delivery order data — covering orders, revenue, ratings, delivery performance, and cuisine trends — to surface actionable business insights.
Overview :-
This project visualizes food delivery order data in a single, interactive Power BI report with two pages:
1.Cover Page — branded landing page with the Zomato logo and a navigation button into the dashboard.
2.Zomato Insights Dashboard — the main analytical view with KPI cards, charts, and slicers for interactive filtering.

#Dashboard Highlights
Key Metrics (KPI Cards)	Description :-
Total Orders :	            Count of all orders placed
Average Order Value :	      Average order amount across all orders
Average Rating :	          Average customer rating given to restaurants
Average Delivery Time	:     Average delivery time (in minutes)
Discount Utilization (%) :	Share of orders where a discount was applied

#Visuals
Orders by Rating (Donut Chart) — distribution of order volume across rating buckets
Delivery Time by Customer Location (Column Chart) — total delivery time by customer area, highlighting slower delivery zones
Orders by Cuisine (Column Chart) — most popular cuisines by order count
Average Order Value by Restaurant (Column Chart) — top/bottom performing restaurants by average order value
Orders Trend Over Time (Line Chart) — monthly/yearly order volume trend

#Interactive Filters (Slicers)
Restaurant Name
Rating
Restaurant Location
Customer Location
Delivery Partner
Order Date

#Dataset
The dataset includes order-level records with fields such as:
Order_ID, Restaurant_Name, Restaurant_Location, Cuisine, Rating, Order_Amount, Order_Date, Customer_Location, Delivery_Partner, Delivery_Time_Minutes
Update this section with your actual data source (e.g., Kaggle dataset link, or note if it's synthetic/sample data).

#Tools & Skills Used
Power BI Desktop — data modeling, DAX measures, and report design
DAX — for calculated measures (e.g., Discount Utilization %, Average Order Value)
Data cleaning & transformation via Power Query

#How to Use
Clone this repository:
bash - git clone https://github.com/yourusername/zomato-insights-dashboard.git
Open zomato_insights_dashboard.pbix in Power BI Desktop.
Use the slicers on the dashboard page to filter by restaurant, location, rating, delivery partner, or date range.

#Key Insights
Certain cuisines/restaurants consistently drive higher order volumes.
Delivery times vary significantly by customer location, pointing to potential logistics bottlenecks.
A meaningful share of orders rely on discounts, suggesting price sensitivity in specific segments.

