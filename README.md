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

![Image](https://github.com/user-attachments/assets/f7e9ba14-430a-4202-9184-3482080b5021)


                            



