# Customer Shopping Behaviour Analysis

End-to-end Data Analytics project analyzing **3,900 customer purchase records** to uncover spending patterns, customer segments, product preferences, and subscription behavior.

The goal of this project is to generate actionable business insights that can support marketing, product, and subscription strategy decisions.

**Tools Used:**  
Python (Pandas, NumPy) | MySQL | Power BI

---

## 📌 Project Overview

This project explores customer shopping behavior using transactional data.  
Key focus areas include:

- Customer segmentation (New / Returning / Loyal)
- Subscription vs Non-subscription performance
- Product and category performance
- Age-group and gender-based revenue analysis
- Discount and shipping behavior

---

## 📂 Dataset

- **Rows:** 3,900
- **Columns:** 18
- **Key Features:**
  - Customer demographics (Age, Gender, Location, Subscription Status)
  - Purchase details (Item, Category, Purchase Amount, Season, Size, Color)
  - Shopping behavior (Discount, Promo Code, Previous Purchases, Frequency, Review Rating, Shipping Type)

---

## 🔍 What I Did

### 1. Data Cleaning & Feature Engineering (Python)
- Handled missing values (Review Rating imputed with category-wise median)
- Standardized column names
- Created new features: `age_group` and `purchase_frequency_days`
- Performed consistency checks and loaded cleaned data into MySQL

### 2. Business Analysis (SQL)
Performed 10 business-focused SQL analyses including:

- Revenue by Gender
- Subscribers vs Non-subscribers performance
- Customer Segmentation (New / Returning / Loyal)
- Top products by average rating
- Top 3 products per category
- Discount-dependent products
- Shipping type comparison
- Revenue contribution by Age Group
- High-spending discount users
- Repeat buyers & subscription relationship

### 3. Interactive Dashboard (Power BI)
Built an interactive dashboard showing:

- Key KPIs (Total Customers, Average Purchase Amount, Average Review Rating)
- Subscription Status distribution
- Revenue & Sales by Category
- Revenue & Sales by Age Group
- Filters for Gender, Category, Shipping Type, and Subscription Status

---

## 📊 Key Insights

- Non-subscribers generated **~73% of total revenue**, while average spend was nearly identical to subscribers
- Clothing is the top revenue-generating category
- Young Adults contribute the highest revenue among age groups
- Only ~27% of customers are subscribers
- Majority of customers fall into the “Loyal” segment

---

## 💡 Business Recommendations

- Focus on converting high-spending non-subscribers into subscribers
- Launch loyalty programs to move customers into the Loyal segment
- Review discount strategy to protect margins
- Highlight top-rated and best-selling products in marketing campaigns
- Target high-revenue age groups and Express shipping users

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `Customer_Shopping_Behavior_Analysis.ipynb` | Python cleaning + EDA notebook |
| `customer_behavior_sql_queries.sql` | SQL business analysis queries |
| `customer_behaviour_dashboard.pbix` | Interactive Power BI dashboard |
| `customer_shopping_behavior.csv` | Dataset |
| `Customer_Shopping_Behavior_Analysis.pdf` | Project report |
| `Customer-Shopping-Behavior-Analysis.pptx` | Presentation |

---

## 🛠️ Skills Demonstrated

- Data Cleaning & Feature Engineering
- Exploratory Data Analysis (EDA)
- Advanced SQL (Aggregations, Segmentation, Window Functions)
- Business Problem Solving
- Power BI Dashboard Development
- Data Storytelling & Recommendations

---

**Author:** Manish Kumar  
**Role:** Aspiring Data Analyst  
**GitHub:** [manishpandiyaar16](https://github.com/manishpandiyaar16)
