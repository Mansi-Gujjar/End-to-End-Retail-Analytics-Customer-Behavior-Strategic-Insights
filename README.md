# End-to-End-Retail-Analytics-Consumer-Behavior-Strategic-Insights
In a competitive retail landscape, understanding the "why" behind a purchase is as critical as the "what." This project serves as a comprehensive analysis of consumer behavior for a leading retail firm, bridging the gap between raw transactional data and executive-level strategy.

As an M.Sc. Mathematics student at NIT Trichy, I leveraged statistical modeling and exploratory data analysis to uncover purchasing drivers across demographics, product categories, and sales channels.

📌 Project Overview
This project represents a complete, industry-standard data analytics workflow designed to mirror the real-world responsibilities of professional analysts. It encompasses every critical stage of the data lifecycle—from raw data preparation to executive-level reporting.

The Mission
The goal of this project is to analyze transactional data from 3,900 purchases to uncover deep insights into spending patterns, customer segments, and product preferences. By moving beyond simple numbers, I identify the "why" behind consumer choices to help a retail company optimize marketing and improve long-term loyalty.

🛠️ The Three-Pillar Approach
To solve this business problem, I implemented a structured data pipeline:

1. Data Engineering (Python)

Cleaning & Integrity: Handled 3,900 records, including the statistical imputation of 37 missing review ratings to maintain data volume without biasing results.


Feature Engineering: Created custom age segments (e.g., 18-30, 31-45) to identify which generation drives the most revenue.


Database Injection: Established a secure connection to a PostgreSQL database using SQLAlchemy to transition from data preparation to exploratory querying.

2. Investigative Analysis (SQL)

Business Logic: Simulated real-world transactions to extract "Boardroom-ready" insights.


Performance Querying: Performed deep-dives into revenue by gender, high-spending discount users, and top-rated products.


Advanced Segmentation: Classified the customer base into "New," "Returning," and "Loyal" segments to guide personalized marketing efforts.

3. Visual Intelligence (Power BI)

Interactive Executive Dashboard: Transformed technical analysis into a visual story for stakeholder decision-making.


Key Metrics: Integrated real-time tracking for Total Revenue, Average Order Value ($59.76), and Average Review Rating (3.75).


Dynamic Slicers: Enabled one-click filtering by Category, Gender, Subscription Status, and Shipping Type.

📈 Strategic Business Recommendations
Data turns into dollars when it leads to action. Based on the analysis, I proposed four high-impact strategies:


Subscription Growth: Target the "Sweet Spot" by offering loyalty upgrades to customers with >5 previous purchases.


Personalized Retention: Use engineered purchase_frequency_days metrics to send "We Miss You" reminders at the exact moment a customer is likely to shop again.


Profit Margin Protection: Recalibrate base pricing for "Discount-Dependent" products that rarely sell at full price.


Strategic Inventory: Feature the Top 5 "customer-approved" products in marketing campaigns to increase trust and conversion rates.

📂 Repository Structure

Customer_Shopping_Behavior_Analysis.ipynb: Full Python ETL and EDA process.


customer_behavior_sql_queries.sql: Comprehensive SQL library for business logic.


customer_behavior_dashboard.pbix: Interactive Power BI report.


Project_Documentation.pdf: Detailed technical and business report.
