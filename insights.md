# Retail-Sales-Analysis
End-to-end SQL analysis and business reporting for Duka Smart Electronics.
## Overview
This project contains an end-to-end SQL analysis for *Duka Smart Electronics*, a retail business. The goal is to set up a relational database schema, execute data verification, analyze retail performance using SQL queries and deliver actionable business insights.

## Project Structure
- schema.sql: Database table creation scripts, primary keys, foreign keys, and constraints.
- queries.sql: Solution queries covering questions Q01 through Q46.
- insights.md: Summary of business insights, metric evidence and recommendations.
- screenshots/: Visual evidence of query results and data verification outputs.

## Setup Instructions
1. OpenPostgreSQL
2. Execute schema.sql to build the database tables.
3. Import the dataset into the created tables.

## How to Run Queries
Open queries.sql in postgres and execute queries.

# Business Insights & Recommendations - Duka Smart Electronics
### Regional Revenue Concentration in Nairobi
- Nairobi generated 12,189,217.40 in total sales revenue leading all cities by a large margin (followed by Mombasa at 3,941,057.95).
- This demonstrates strong market dominance and high purchasing power in Nairobi making it the highest revenue city for Duka Smart Electronics.
- Cities like Machakos (1,033,066.80), Nyeri (1,307,413.80), and Thika (1,492,750.00) currently contribute the lowest total revenue.
- My Recommendation is to prioritize fast-track delivery services and local inventory stocking in Nairobi to maintain market share while organizing marketing campaigns in regions like Mombasa and Nakuru by introducing  promotional discounts.

### Product Category Revenue Performance
- Mobile Phones (8.98M) and Computing (8.31M) generate the highest sales followed by Electronics (7.25M), Home Appliances (4.72M) and Accessories (1.54M).
- Accessories revenue (1,542,348.90) lags Mobile Phones (8,982,283.25) by a ratio of roughly 1:6, despite accessories carrying significantly higher gross profit margins.
- My Recommendation is that since customers are buying core devices at Duka Smart Electronics but are sourcing their complementary items (chargers, cases, cables, adapters) from competitor retail outlets,strategies such as offering a 15% discount on phone cases or laptop bags when purchased alongside a primary device would boost sales.

### Customer Intent vs. Fulfillment Friction
-  The overall order cancellation rate is 11%.Cancellation rate signals potential delay in the checkout process, stockout issues after purchase or long delivery timelines causing buyer's remorse.
- This indicates a disconnect between customer expectations at checkout (such as shipping costs or delivery estimates) and the actual terms presented post-order.
- My Recommendation is to display accurate shipping fees and delivery times clearly prior to payment checkout to manage expectations and reduce cancellations also,audit the checkout and fulfillment pipeline to identify why customers cancel and introduce an automated confirmation or follow-up messaging system to secure order commitment.

### Insight: Peak Performance in July
-  Monthly revenue peaked significantly in July 2025 at 1,525,868.45 (up from 957,489.35 in June).
-  This demonstrates a major surge in mid-year customer spending, indicating seasonal buying behavior or successful promotional campaigns during that period.
- I recommend analyzing the marketing campaigns, product promotions or inventory stocked during July 2025 and replicate those strategies to capture similar demand spikes in future quarters.

### Insight: Pareto Distribution in Customer Spending Tiers
-  The top quartile of customers (Tier 4 via NTILE) accounts for approximately 40% to 50% of total cumulative spending revenue this indicates a heavy reliance on a smaller group of high-spending VIP customers rather than an even distribution across the entire customer base.
- My recommendation is to create a dedicated VIP loyalty or rewards program tailored to the top spending quartile to ensure high retention rates and protect core revenue streams.

### Insight: Repeat Purchase Frequency Deficit
-  Only a small fraction of total registered customers (less than 15%) have placed more than 5 orders, that is a total of 46/150 customers with more than five orders only. This indicates that while customer acquisition brings in new buyers, long-term retention remains low, forcing the business to rely continuously on costly new-customer marketing. 
- My recommendation is to launch an automated post-purchase email campaign offering refill reminders, accessory recommendations, or a multi-order loyalty reward to convert one-time buyers into repeat orderers.
