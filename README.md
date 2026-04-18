# 📊 SQL Customer Analytics Mini-Project

## 🎯 Project Overview
This project focuses on extracting actionable business intelligence from an e-commerce database. Using advanced SQL techniques like Correlated Subqueries, Joins, and Set Operators, we transformed raw transactional data into meaningful insights regarding customer behavior and inventory health.

## 🛠️ The Database
The analysis is built on a relational schema consisting of four core tables:

- Customers: Identity and contact details.
- Products: Catalog information including categories and pricing.
- Orders: Transactional headers with total amounts and dates.
- Order Items: The "bridge" table that lists specific products, quantities, and prices for every order.
- Reviews: Customer feedback and product ratings.

## 🧩 Challenges Solved
We addressed several real-world business questions, including:

- Data Silos: Bridging the gap between sales data and customer feedback.
- Complex Filtering: Identifying personal "spending peaks" by comparing individual rows against aggregate personal histories.
- Inventory Gaps: Detecting products that exist in the catalog but have never generated revenue.

## 💡 Key Findings

- Brand Ambassadors: Successfully isolated a high-value segment of customers who are both active shoppers and active reviewers, perfect for loyalty rewards.
- High-Value Transaction Mapping: Identified the "Maximum Order per Customer," allowing marketing teams to see the peak purchasing capacity of every user.
- Market Inertia: Discovered "Dead Stock" items (products with zero orders) and "Inactive Users" (sign-ups with no orders), providing clear targets for clearance sales and re-engagement campaigns.

🚀 How to Use
- Schema: Run the schema.sql.docx file to set up the table structures.
- Data: Populate the tables using the retail_data.sql script.
- Analysis: Execute the queries in sql-retail-sales-analysis.sql to generate the business reports.

