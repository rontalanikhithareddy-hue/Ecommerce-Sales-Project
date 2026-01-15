# Ecommerce-Sales-Project
Exploratory data analysis and sales insights from an e-commerce dataset using Python.
This project focuses on analyzing an e-commerce dataset to understand customer behavior, pricing patterns, product performance, and ratings using Python and data analysis techniques. The goal is to derive actionable business insights rather than just performing calculations.

Tools & Libraries Used :
Python , Pandas ,NumPy, Matplotlib

The dataset contains information about:
Product categories and brands
Prices and quantities
Total order amount
Customer ratings and reviews
Platforms and cities
Each row represents a single completed order.

Data Cleaning & Feature Engineering
Checked for duplicate records (no duplicates found)

Created new categorical tiers:
Price_tier (Inexpensive / Moderate / Expensive)
Rating_tier (Low / Good / Excellent)
Reviews_tier (Positive / Neutral / Negative / Unknown)

Descriptive Analysis:
Analyzed value counts for newly created tiers
Observed that:
Most products fall under the Expensive price tier
Positive reviews dominate, but Excellent ratings are fewer compared to Good and Low ratings

Category & Brand Analysis
Calculated average price by Brand
Calculated average price by Category
Found that categories like Fashion and Electronics tend to have higher average prices

Sales & Revenue Insights:
Aggregated TotalAmount by product category
Analyzed average TotalAmount by Rating_tier
Found that Good-rated products have the highest average order value, indicating higher spending even when ratings are not perfect

Visualization & Distribution Analysis:
Created:
Bar charts for category-wise analysis
Histogram for TotalAmount distribution
Observed that:
Most orders are concentrated in lower-to-mid order values
Distribution shows skewness, indicating fewer high-value purchases

Pivot Table Analysis:
Used pivot tables to analyze relationships between:
Category and Ratings
Platform and Sales (where applicable)
Helped identify category-wise customer satisfaction patterns

Insights gained after completion of poject:

Higher ratings do not always lead to higher spending

Expensive products dominate the dataset, which may impact sales volume

Customer satisfaction varies across product categories

Pricing strategy and customer perception are closely linked
