# 🛒 End-to-End Retail Analytics: Consumer Behavior & Strategic Insights

In a competitive retail landscape, understanding **why** a customer makes a purchase is just as important as **what** they purchase.  
This project delivers a **full-stack retail analytics solution**, transforming raw transactional data into **actionable, executive-level insights**.

Built as an industry-aligned analytics workflow, the project bridges **data engineering, business analysis, and strategic decision-making**.
<p align="center">
  <img src="images/work flow.png" width="850">
</p>

---

## 🎓 Author Background
**M.Sc. Mathematics | NIT Trichy**  
Strong foundation in statistical modeling, exploratory data analysis, and data-driven business strategy.

---

## 📌 Project Objective

The goal of this project is to analyze **3,900 retail transactions** to uncover:

- Spending patterns across demographics  
- High-value customer segments  
- Product performance drivers  
- The behavioral “why” behind purchasing decisions  

These insights are designed to help a retail firm **optimize marketing, pricing, and customer retention strategies**.

---

## 🛠️ Analytics Workflow: The Three-Pillar Approach
<p align="center">
  <img src="images/customer shopping.png" width="850">
</p>


This project follows a **real-world, end-to-end data analytics pipeline**.

---

### 1️⃣ Data Engineering & Preparation (Python)

**Tools:** Pandas, NumPy, SQLAlchemy  

- **Data Cleaning & Integrity**
  - Processed 3,900 transactional records
  - Statistically imputed **37 missing review ratings** to preserve dataset integrity

- **Feature Engineering**
  - Created custom **age segments** (18–30, 31–45, etc.)
  - Engineered behavioral metrics such as purchase frequency

- **Database Integration**
  - Established secure PostgreSQL connection using SQLAlchemy
  - Prepared structured data for analytical querying

---

### 2️⃣ Investigative Business Analysis (SQL)

**Tools:** PostgreSQL  

- **Revenue Analysis**
  - Revenue by gender, category, and subscription status
  - Identification of high-spending discount users

- **Customer Segmentation**
  - Classified users into:
    - **New Customers**
    - **Returning Customers**
    - **Loyal Customers**

- **Product Intelligence**
  - Top-rated and most-trusted products
  - Identification of discount-dependent items

> All queries are written to simulate **real boardroom-level business questions**.

---

### 3️⃣ Visual Intelligence & Storytelling (Power BI)

**Tools:** Power BI  

- **Executive Dashboard**
  - Converts technical findings into clear business narratives

- **Key KPIs**
  - **Total Revenue**
  - **Average Order Value:** $59.76
  - **Average Review Rating:** 3.75

- **Interactive Slicers**
  - Category
  - Gender
  - Subscription Status
  - Shipping Type

Designed for **non-technical stakeholders and leadership teams**.

---

## 📈 Strategic Business Recommendations

Based on the analysis, the following **high-impact strategies** were proposed:

1. **Subscription Growth**
   - Target customers with **>5 previous purchases** for loyalty upgrades

2. **Personalized Retention**
   - Use purchase frequency metrics to trigger  
     _“We Miss You”_ campaigns at the optimal time

3. **Profit Margin Protection**
   - Reprice products that sell **only under discounts**

4. **Strategic Inventory Promotion**
   - Highlight **Top 5 customer-approved products** in marketing campaigns  
     to increase trust and conversion rates

---

## 📂 Repository Structure

📁 End-to-End-Retail-Analytics
│
├── 📘 Customer_Shopping_Behavior_Analysis.ipynb
│ └─ Python ETL, cleaning, feature engineering & EDA
│
├── 🗄️ customer_behavior_sql_queries.sql
│ └─ Business-driven SQL queries & segmentation logic
│
├── 📊 customer_behavior_dashboard.pbix
│ └─ Interactive Power BI executive dashboard
│
└── 📄 Project_Documentation.pdf
└─ Detailed technical and business insights report

