# Amazon-Product-Review-Analysis
This project dissects a scraped Amazon dataset with the aim to uncover how price, discount, ratings, and review interact across product category. It is a Microsoft Excel- focused analysis, where I used my skills to distil raw e-commerce data, cleaning and refining it into actionable insights for marketing teams. 
## Objectives
- Quantify pricing and discount patterns by product category.
- Identify products and categories with the strongest review engagement.
- Assess relationships between discount levels and customer ratings.
- To generate insight on the product flow and revenue sustainance.
- Deliver a concise, interactive Excel dashboard for non-technical stakeholders.
## Data Overview
- 1,465 rows containing one row per product.
- 16 columns (product name, category, discounted price, discount %, average rating, reviews and more).
- I removed long text columns that were not needed.
- I made sure numbers are stored as numbers and percentages as percentages.
## Steps I Followed
#### Data Cleaning and Preparation
1. Removed irrelevant text fields
2. Standardized Column Names (`Discount %`)
3. Converted Data types - Prices to Numeric, Discount to Percentages
4. Split Nested Categories - Ranked and Kept highest-level segment
5. Created Calculated Columns (`Revenue`, `Price Range Bucket`)
#### Create Pivot Tables
To analyse business questions and compare values (`average discount by category`)
#### Build the dashboard
Bar charts for category comparisons. Pie and Bar charts for business insights into highest discount % by regions.
## Key Findings
Electronics give the biggest discounts but also gained the highest revenue.
Very high discounts (over 50%) often come with lower ratings.
Only a few products have more than 1000 reviews, yet these products (Electronics) create most of the revenue.
## Recommendations
- Prioritize sales of Electronics as it shows high revenue and strong customer engagement.
- Limits Discounts over 50% to reduce lower average ratings.
- Focus on Mid-Priced products (200-500).
- Promote products with both high ratings and many reviews to perform best overall.
## Files in the Repository
[`Amazon Product Review Analysis`](Amazon_Product_Review_Analysis.xlsx)
[`README.md`](README.md)
[`images/](

