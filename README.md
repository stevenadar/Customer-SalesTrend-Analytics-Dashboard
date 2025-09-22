
📌 Project Summary:

This project presents an interactive Power BI dashboard that analyzes customer shopping trends rather than just raw sales. It highlights customer behavior, preferences, and contributions across different demographics, geographies, and product categories.

Key KPIs include:

Total Sales: 512.77K

Unique Customers: 100

Average Sales per Customer: ~5.13K

Top Category: Electronics

The dashboard empowers businesses to understand their customers better, optimize marketing, improve inventory planning, and design data-driven growth strategies.


🎯 Problem Statement:

Retailers and businesses often collect large amounts of transactional sales data, but lack visibility into customer-centric insights such as:

Which customer groups contribute most to revenue?

How does average spend vary by product, region, or demographics?

Which stores/managers drive stronger customer sales?

What seasonal or yearly purchase trends exist?

Without customer-focused analytics, businesses risk missing growth opportunities, inefficient marketing, and poor resource allocation.



🛠️ Approach & Methodology:
🔹 Data Preparation

Removed duplicates and handled missing/null values.

Standardized categorical fields (region, store, categories).

Imputed/flagged missing demographics for accuracy.

🔹 Transformations

Created customer-level metrics (avg spend, frequency, recency, tenure).

Built date hierarchies for monthly, quarterly, yearly analysis.

Segmented customers into value groups for targeting.

🔹 Data Modeling (Star Schema)

Fact Table: Sales transactions (CustomerID, ProductID, StoreID, Date, SalesAmount).

Dimension Tables: Customer, Product, Store/Manager, Date.

Optimized for performance and clarity in reporting.

🔹 Tools & Techniques

SQL/Python → ETL & cleaning

Power BI → Visualization & DAX measures

Star Schema → Structured modeling for efficient reporting



📊 Key Customer Insights:

Customer Value: Avg sales per customer ~5.13K, with clear high-value segments.

Top Category: Electronics dominates customer spending across regions.

Geography: Cities like Jeffreyborough & South David contribute highest per-customer sales (~15K each).

Demographics: Gender split balanced → Female (53.29%), Male (46.71%).

Manager/Store Impact: Barbara Riggs leads with ~63K sales, showing strong influence on customer trends.

Seasonality: Monthly peaks in April & September, reflecting seasonal buying behavior.

Growth Over Time: Strong uplift from 2022 → 2023, with steady customer sales into 2024.



✅ Conclusion

The dashboard reveals actionable customer trends that can drive strategic business decisions:

Prioritize high-value customers with personalized offers.

Optimize inventory around categories with high per-customer demand.

Focus marketing efforts on high-contributing cities and customer segments.

Learn from high-performing managers/stores and replicate successful practices.

Plan promotions around peak seasonal months to maximize revenue.

By shifting analysis from sales totals → customer-centric insights, this project demonstrates how businesses can unlock deeper understanding and long-term growth opportunities.



⚙️ Tech Stack

Power BI – Dashboard creation, DAX calculations, visuals

SQL – Data extraction, cleaning, transformations

Python (Pandas/Numpy) – Preprocessing & feature engineering

Star Schema Data Modeling – Optimized structure for analytics

