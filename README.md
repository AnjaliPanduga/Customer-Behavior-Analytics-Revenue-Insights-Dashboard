# 🛍️ Customer Behavior Analytics & Revenue Insights Dashboard

## 📌 Project Overview

This project focuses on understanding how customers behave while shopping and how their actions impact business revenue. Instead of just looking at raw data, the goal was to answer meaningful business questions like:

Who spends more — male or female customers?
Do discounts actually increase revenue?
Are loyal customers more valuable than new ones?
Which products are performing the best?

By combining SQL, Python, and Power BI, I transformed raw customer data into actionable insights that can help businesses make better decisions.

---

## ❗ Problem Statement

Businesses collect a huge amount of customer data, but most of it remains unused or underutilized.

The main problem I wanted to solve was:

"How can we use customer purchase data to understand behavior patterns and improve business decisions?"

Without proper analysis, companies miss opportunities like:

- Identifying high-value customers
- Understanding the impact of discounts
- Improving product strategies
- Increasing customer retention

---

## 🛠️ Approach & Solution

I broke the project into three main stages:

1️⃣ Data Exploration & Cleaning
- Loaded customer shopping dataset
- Checked for inconsistencies and cleaned the data
- Prepared it for analysis

----

2️⃣ SQL-Based Analysis

I used SQL to answer real business questions such as:

- Revenue comparison by gender
- Identifying high-spending customers using discounts
- Top-rated and most purchased products
- Customer segmentation (New, Returning, Loyal)
- Subscription vs non-subscription revenue behavior

Example:

SELECT gender, SUM(purchase_amount) as revenue
FROM customer
GROUP BY gender;

More queries available in the project 👉

---

3️⃣ Dashboard Creation (Power BI)
- Built an interactive dashboard to visualize insights
- Added filters for better exploration
- Designed charts for:
  - Revenue trends
  - Customer segments
  - Product performance
  - Discount impact

This makes it easy for even non-technical users to understand the data.

---

## 📊 Key Insights

Some interesting findings from the analysis:

- Certain customer segments contribute more to overall revenue
- Discounts do not always guarantee higher spending
- Loyal customers play a major role in business growth
- Subscription-based users show different spending patterns

---

## 🧰 Tech Stack
- SQL → Data analysis and querying
- Python → Data handling and preprocessing
- Power BI → Dashboard and visualization

---

## 🎯 What I Learned

This project helped me understand:

- How to translate business problems into data questions
- Writing efficient SQL queries for real-world scenarios
- Building dashboards that tell a story, not just show numbers
- The importance of customer segmentation in analytics

---






