# Problem Statement:
Imagine you're working for a toy store chain with multiple stores in Mexico. You have access to data containing transactional records from January 2022 to September 2023. You also have access to the information about products and store locations.
The goal is to build a simple, interactive report that the leadership team can use to monitor key business metrics and high-level trends.

# My Approach
### 1. Data preprocessing
I had multiple csv files. I connected to them and used the Power Query Editor to check for null values and to check if the datatypes were correct. The dates were in the american format, so I needed to change that.
### 2. Create a relational model
As I had several tables, I needed to create relationships between them, so I identified the primary and foreign keys.
### 3. Building the dashboard
Before building the dashboard, I needed to create two new columns to check the revenue and the profit of every sale. 
I added KPI cards that show the total orders, total revenue, and total profit for the current month. These KPI cards also show the monthly trends for each metric. Then, I added a bar chart showing the total orders by product category and a line chart that shows the revenue by month.
