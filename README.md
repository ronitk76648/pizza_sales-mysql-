Pizza Sales Data Analysis (MySQL)
 Project Overview
This project involves a comprehensive analysis of a year's worth of sales data for a pizza shop. Using MySQL, I extracted, cleaned, and analyzed data across multiple relational tables to uncover insights regarding customer preferences, peak ordering times, and revenue drivers.

The goal was to provide data-backed recommendations to improve operational efficiency and marketing strategies.

 Key Business Insights
Total Revenue: Generated $817,860.05 over the analyzed period.

Order Volume: A total of 21,350 orders were successfully processed.

Peak Demand: The busiest hour for orders is 12:00 PM, indicating a heavy lunch-time rush.

Top Performer: The Thai Chicken Pizza is the highest revenue contributor ($43,434.25), while the Classic Deluxe leads in total quantity sold.

Customer Preference: Large (L) size pizzas are the most frequently ordered across all categories.

Tech Stack & Skills
Database: MySQL

SQL Techniques used:

Joins: Connecting orders, order_details, pizzas, and pizza_types.

Aggregations: SUM, COUNT, AVG, and ROUND for financial metrics.

Window Functions: Utilized RANK() and OVER(PARTITION BY...) to find top-selling pizzas per category.

Common Table Expressions (CTEs): To manage complex multi-step calculations like cumulative revenue.

 Database Schema
The project utilizes four primary tables:

Orders: Date and time of every order placed.

Order_Details: Specific pizzas and quantities within each order.

Pizzas: Size and price information for each pizza variant.

Pizza_Types: Categorization (Classic, Veggie, Chicken, Supreme) and ingredient details.

 Analysis Workflow
Phase 1: Foundational Analysis
Identified total orders and revenue.

Determined the highest-priced pizza and most common size.

Ranked top 5 most ordered pizza types.

Phase 2: Intermediate Analysis
Analyzed the distribution of orders by hour to identify peak staffing needs.

Calculated category-wise sales distribution.

Grouped sales by date to find the average number of pizzas sold per day.

Phase 3: Advanced Analysis
Calculated percentage contribution of each pizza type to total revenue.

Analyzed cumulative revenue over time to track business growth.

Identified the top 3 pizzas by revenue for each category using advanced ranking.
