# Supermarket-Sales-Analysis

# Project Background
In a competitive retail environment, supermarkets handle thousands of daily transactions across various product categories, locations, and customer segments. Understanding sales performance, customer buying patterns, and product profitability is essential for optimizing operations, inventory management, and marketing strategies.

This project was undertaken to address the common challenge faced by supermarkets: turning vast amounts of transactional data into actionable business intelligence. 

Key Insights and Recommendations Focused on:

- **Sales Trends Over Time:** An analysis of monthly, weekly and hourly sales patterns to uncover seasonal peaks, weekday performance trends, and optimal sales hours for operational and marketing optimization.

- **Store Location Performance:** Evaluation of revenue distribution across major cities to identify top performing regions, regional sales imbalances, potential areas for localized improvement.

- **Customer Frequency and Behavior:** Assessment of customer purchase frequency (one-time, occasional, regular) to measure loyalty levels, understand spending behavior, and highlight retention opportunities.

- **Product and Category Sales Analysis:** Identifying best-selling products and high-performing categories to guide inventory planning, marchendising stretegy, and promotional focus.


An interactive Power BI dashboard used to report and explore sales trends can be found [here](https://app.powerbi.com/links/HZlRLLXAl5?ctid=16d83ee6-254a-469d-a6cc-54e2ca2313e7&pbi_source=linkSh)

The SQL queries used to inspect and clean the data for this analysis can be found [here](https://github.com/Numb3rNinja/Quality-Assessment.git)

Targeted SQL queries answering specific business questions can be found [here](https://github.com/Numb3rNinja/Business-Questions.git
)



## Data Structure & Initial Checks
The company's main database for this project consisted of one table, with 2001 rows.

Table columns included: TransactionID, TransactionDate, TransactionTime, CustomerName, StoreLocation, Category, Product, Quantity, UnitPrice, TotalPrice, Discount, FinalPrice, PaymentMethod, Cashier, Returned

**Key early checks included:**

- Validating data types (date, text, numeric fields).

- Checking for missing or null values (minimal, non-impactful).

- Ensuring consistent formatting across locations and product names.


# Executive Summary

## Overview of Findings
Sales trends revealed clear seasonal peaks, with September 2024 and March 2025 standing out as the highest-performing months, and Fridays consistently generated the most sales each week. Store performance analysis showed that while sales were evenly distributed across locations, Houston slightly outperformed other cities, indicating strong regional engagement. Customer behavior isnsights highlighted a heavy reliance on one-time shoppers, with minimal contributions from regular customers, underscroring a significant opportunity for loyalty initiatives. Product and category analysis demonstrated that a small set of items, particularly in Personal Care and Bakery, drove a large proportion of revenue, suggesting that strategic inventory and promotional focus on top categories could further boost overall sales.

![Image](https://github.com/user-attachments/assets/d827453e-8898-49eb-a742-f557df3524d7)

## Insights Deep Dive

### Sales Trends Over Time
Sales analysis over the 12-month period revealed distinct seasonal patterns. **September 2024** was the highest-grossing month, with sales reaching **$21K**, cinciding with back-to-school and early fall seasonal shopping. Sales also surged in **November 2024** and **March 2025**, aligning with holiday and spring break periods. Conversly, **July 2024** experienced the lowest sales volume (**7.6K**), potentially due to summer vacations and reduced in-store activity.
Weekly trends indicated that **Fridays** consistently generated the highest daily sales (**$38K** cumulative), suggesting that customers prefer stocking up before weekends.
Hourly patterns showed that the bulk of transactions occured between **10:00 AM and 8:00 PM**, confirming this as the optimal window for promotional activities an dstore staffing. 
Overall, The time-based analysis emphasized key periods where marketing and operational efforts should be intensified.

**Monthly Sales** ![Image](https://github.com/user-attachments/assets/f7e9ba14-430a-4202-9184-3482080b5021)
**Daily Sales** ![Image](https://github.com/user-attachments/assets/28ed79bb-e1a5-41c3-86eb-e63a0b61aacb)
**Hourly Sales** ![Image](https://github.com/user-attachments/assets/36d9de26-a9ab-43ad-a5c8-44a9cc55fa62)


### Store Location Performance
Sales were relatively evenly distributed across the five key store locations, each contributing between 18.86% and 21.26% of total sales revenue. Houston emerged as the top-performing location with $48.72K (21.26% of total sales), likely benefiting from higher customer traffic or localized promotions. New York and Phoenix followed closely, each contributing around 20%. Los Angeles, while still performing strongly, showed a slight lag with $43.23K (18.86%), suggesting a potential opportunity for deeper market engagement strategies.
The overall balanced distribution indicates a well-managed regional strategy but also higlights specific cities where targeted iitiatives could drive additional growth.

![Image](https://github.com/user-attachments/assets/5c823dc5-1376-4858-a771-260d56f8df9f)



### Customer Frequency and Behavior
The customer behavior analysis revealed a heavy reliance on one-time customers, who accounted for 94.28% of all sales ($216.07K).
Regular customers represented just 3.56% ($8.15K) of sales, and occasional customers contributed only 2.16% ($4.95K).
This extremely low repeat customer rate suggests a significant opportunity for customer retention initiatives such as loyalty programs or personalized marketing.
Interestingly, occasional customers displayed slightly higher average transaction values compared to regulars, hinting that infrequent but targeted buyers might be a profitable segment if properly nurtured.
Across customer types, there was no significant variation in payment method preference, meaning loyalty programs could focus more on experiential benefits rather than payment incentives.

![Image](https://github.com/user-attachments/assets/2eb397e0-d232-47f1-bb5e-5ad55e9abbd4)


### Product and Category Sales Analysis

Sales were highly concentrated among a small group of products and categories. Apples led individual product sales with $17.2K, followed by Bread ($10.7K) and Detergent ($7.5K), indicating strong customer preference for essential grocery and household items.
At the category level, Personal Care products generated $14.6K in sales, closely followed by Bakery at $13.9K.Beverages ($9.7K) and Dairy ($8.3K) also performed well, while categories like Meat ($3.8K) and Produce ($6.6K) lagged behind.This concentration highlights opportunities to boost underperforming categories through promotions or remerchandising while capitalizing on the strength of the top categories with expanded inventory or bundled offers.Focusing marketing efforts on top-selling products could yield quick wins, while strategic initiatives could revitalize slower-moving inventory categories.

![Image](https://github.com/user-attachments/assets/45cb10df-578c-4f5c-9925-51bf074b9ffb)   ![Image](https://github.com/user-attachments/assets/5d3067f2-bbfa-4160-b142-bd88a1022fc5)

## Recommendations
Based on the findings from the sales, customer, product, and location analysis, the following recommendations are proposed to drive revenue growth, improve customer retention, and enhance operational efficiency:

1. **Introduce a Targeted Loyalty Program:**
The overwhelming dominance of one-time customers (94.28%) suggests a critical need for initiatives that encourage repeat visits. A tiered loyalty program offering points, discounts, or exclusive deals for frequent purchases can increase customer lifetime value. This program should include personalized promotions based on shopping habits and could be integrated with SMS/email marketing to improve engagement. Regular shoppers showed slightly higher transaction values — a sign that fostering loyalty can have a direct financial impact.

2. **Leverage Weekly and Hourly Sales Patterns for Promotions:**
With Fridays driving the highest daily sales and peak activity occurring between 10:00 AM and 8:00 PM, marketing campaigns and in-store promotions should be timed around these windows. Consider running flash sales or "Weekend Kickoff" deals that start Friday mornings to capture traffic. Additionally, staffing schedules should be aligned with these hours to ensure adequate customer support and maximize conversion during high-traffic periods.

3. **Expand Top-Performing Categories and Bundle Best-Sellers:**
The concentration of revenue in categories like Personal Care and Bakery offers an opportunity to expand shelf space and product variety in these segments. Additionally, high-selling individual items like Apples and Bread can be bundled with complementary products (e.g., milk, spreads, snacks) to increase basket size. Cross-merchandising strategies can help boost both top and mid-tier product sales.

4. **Optimize Performance at Lower-Growth Locations:**
While overall store performance is well balanced, locations like Los Angeles underperformed slightly compared to others. Conducting store-specific audits — including foot traffic analysis, local competition, and marketing reach — could uncover factors impacting performance. Tailored in-store events, community engagement, or hyperlocal promotions may help improve visibility and revenue in these markets.

5. **Revitalize Underperforming Product Categories:**
Categories like Meat and Produce lagged behind in sales, indicating a need to evaluate freshness, pricing, display strategy, and promotional frequency. Consider launching rotating weekly discounts or in-store sampling to boost interest. These categories could also be paired with more popular items (e.g., a fresh produce + dairy combo) to increase uptake.

6. **Standardize Payment Options While Improving Checkout Experience:**
The balanced usage of payment methods (cash, card, mobile, voucher) shows that customers appreciate having flexible options. While no single method dominates, the checkout process can be improved with faster payment terminals, clearer signage, and staff training on multiple payment workflows — contributing to an overall smoother in-store experience and potentially higher customer satisfaction.



