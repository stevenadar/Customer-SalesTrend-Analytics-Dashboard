
# 📌 Project Summary:

This project presents an interactive Power BI dashboard that analyzes customer shopping trends rather than just raw sales. It highlights customer behavior, preferences, and contributions across different demographics, geographies, and product categories.

Key KPIs include:

Total Sales: 512.77K

Unique Customers: 100

Average Sales per Customer: ~5.13K

Top Category: Electronics

The dashboard empowers businesses to understand their customers better, optimize marketing, improve inventory planning, and design data-driven growth strategies.


# 🎯 Problem Statement:

Retailers and businesses often collect large amounts of transactional sales data, but lack visibility into customer-centric insights such as:

1)Which customer groups contribute most to revenue?

2)How does average spend vary by product, region, or demographics?

3)Which stores/managers drive stronger customer sales?

4)What seasonal or yearly purchase trends exist?

Without customer-focused analytics, businesses risk missing growth opportunities, inefficient marketing, and poor resource allocation.



# 🛠️ Approach & Methodology:
##  🔹 Data Preparation

1)Removed duplicates and handled missing/null values.

2)Standardized categorical fields (region, store, categories).


##🔹 Transformations

1)Created customer-level metrics (avg spend, frequency, recency, tenure).

2)Built date hierarchies for monthly, quarterly, yearly analysis.

3)Segmented customers into value groups for targeting.

##🔹 Data Modeling (Star Schema)

1)Fact Table: Sales transactions (CustomerID, ProductID, StoreID, Date, SalesAmount).

2)Dimension Tables: Customer, Product, Store/Manager, Date.

3)Optimized for performance and clarity in reporting.

##🔹 Tools & Techniques

1)SQL/Python → ETL & cleaning

2)Power BI → Visualization & DAX measures

3)Star Schema → Structured modeling for efficient reporting



# 📊 Key Customer Insights:

1)Customer Value: Avg sales per customer ~5.13K, with clear high-value segments.

2)Top Category: Electronics dominates customer spending across regions.

3)Geography: Cities like Jeffreyborough & South David contribute highest per-customer sales (~15K each).

4)Demographics: Gender split balanced → Female (53.29%), Male (46.71%).

5)Manager/Store Impact: Barbara Riggs leads with ~63K sales, showing strong influence on customer trends.

6)Seasonality: Monthly peaks in April & September, reflecting seasonal buying behavior.

7)Growth Over Time: Strong uplift from 2022 → 2023, with steady customer sales into 2024.



# ✅ Conclusion

The dashboard reveals actionable customer trends that can drive strategic business decisions:

1)Prioritize high-value customers with personalized offers.

2)Optimize inventory around categories with high per-customer demand.

3)Focus marketing efforts on high-contributing cities and customer segments.

4)Learn from high-performing managers/stores and replicate successful practices.

5)Plan promotions around peak seasonal months to maximize revenue.

By shifting analysis from sales totals → customer-centric insights, this project demonstrates how businesses can unlock deeper understanding and long-term growth opportunities.



# ⚙️ Tech Stack

1)Power BI – Dashboard creation, DAX calculations, visuals

2)SQL – Data extraction, cleaning, transformations

3)Python (Pandas/Numpy) – Preprocessing & feature engineering

4)Star Schema Data Modeling – Optimized structure for analytics

