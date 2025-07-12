# Retail_sales_-analysis-with-product-type
📝 Retail Sales Analysis Project
📌 Project Overview
This project involves the design and creation of a Retail Sales Database System using MySQL to store, manage, and analyse sales data effectively. It simulates a small retail store’s transactions to derive meaningful business insights.

💻 Key Components
Retail Sales Table (retail_data)

Columns: transaction_id, sale_date, sale_time, customer_id, age, gender, category, quantity, price_per_unit, cogs, total_sale

Stores individual sales transactions with customer demographics and product purchase details.

Product Table (product)

Columns: category, price_per_unit, product_type

Contains product information categorised by type and pricing.

🔍 Project Objectives
✅ Design relational tables with appropriate data types and keys
✅ Populate tables with realistic sample data
✅ Perform SQL queries to:

Retrieve unique categories

Analyse sales by product type

Join tables to extract combined insights (e.g. sale details with product type)

✅ Export data files (SQL/CSV) for integration into external analytics tools or GitHub repositories

📊 Key Learnings
Database schema design for retail systems

Writing efficient JOIN, GROUP BY, and DISTINCT queries

Managing data imports and exports between MySQL and GitHub

Enhancing datasets with reference tables to enable deeper business analysis

🚀 Future Enhancements
Add customer_details table with city, state, membership status for regional and demographic insights

Create store_details table for multi-store sales tracking

Integrate with Python (Pandas) or Power BI for advanced visual analytics

📂 Files Included
retail_data.sql / retail_data.csv – Sales transactions data

product.sql / product.csv – Product details data

README.md – Project overview and usage instructions
