# 🍔 QuickBite Express — Business Performance & Crisis Recovery Analytics



## 📌 Project Overview

QuickBite Express is a fictional Bengaluru-based food-tech startup used for a Business Intelligence and Data Analytics case study.

This project analyzes business performance from **January to September 2025**, focusing on a major business downturn in June 2025.

The objective is to identify trends, understand operational challenges, analyze customer behavior, and provide data-driven recommendations to improve business performance.

## 🎯 Business Objectives

- Analyze monthly order and revenue performance.
- Understand customer acquisition and purchasing behavior.
- Evaluate restaurant and menu category performance.
- Monitor delivery efficiency and SLA breaches.
- Analyze customer ratings and sentiment.
- Identify potential areas for business recovery.

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data exploration and preprocessing |
| Pandas | Data cleaning and manipulation |
| Power BI | Interactive dashboard development |
| Power Query | Data transformation |
| DAX | KPI calculations and measures |
| Version control | Git,Github  |

## 📂 Dataset Description

The project uses eight cleaned tables:

| Table | Description |
|---|---|
| fact_orders_clean | Order transactions and revenue |
| fact_order_items_clean | Order item details |
| fact_ratings_clean | Customer ratings and sentiment |
| fact_delivery_performance_clean | Delivery time and distance |
| dim_customer_clean | Customer information and acquisition channel |
| dim_restaurant_clean | Restaurant and cuisine information |
| dim_delivery_partner_clean | Delivery partner information |
| dim_menu_item_clean | Menu item and category information |

**Data preparation:** Initial profiling, missing-value analysis, duplicate checks, and cleaning were performed using Python and Pandas.

*Dataset source: Add the original dataset source or explain that it is synthetic if applicable. Do not claim an unverified source.*

## 🧩 Data Modeling

A relational model was developed in Power BI using fact and dimension tables.

Key modeling components:
- One-to-many relationships.
- Single-direction filtering.
- Dedicated date dimension (`Dim_Date`).
- Relationships supporting customer, restaurant, delivery, rating, and menu analysis.
- DAX measures for business KPIs.

## 📊 Dashboard Pages

The report contains four interactive pages.

### 1. Executive Overview

- Total Orders
- Completed Orders
- Total Revenue
- Average Order Value
- Cancellation Rate
- Completed SLA Breach Rate
- Average Rating
- Average Sentiment

### 2. Customer & Revenue Analytics

- Revenue by Acquisition Channel
- Orders by Acquisition Channel
- Customer Order Trend
- Customer Rating Trend

### 3. Restaurant & Product Analytics

- Revenue by Cuisine
- Orders by Partner Type
- Top 10 Restaurants by Revenue
- Menu Item Revenue by Category

### 4. Delivery & Customer Experience

- Average Delivery Time
- Delivery Delay
- Completed SLA Breach Rate
- Actual vs Expected Delivery Time
- Monthly SLA Breach Rate
- Customer Rating Trend
- Customer Sentiment Trend

## 📈 Key Business Insights

| Finding | Result |
|---|---:|
| Order decline (May–June) | 58.86% |
| Revenue decline (May–June) | 61.22% |
| Average rating (May) | 4.49 |
| Average rating (June) | 2.58 |
| Completed-order SLA breach rate | 63.46% |
| Overall revenue | ₹48.56M |
| Overall orders | 149,166 |

### Major Observations

- Orders and revenue declined sharply in June 2025.
- Customer ratings and sentiment deteriorated during the same period.
- Cancellation rates nearly doubled from May to June.
- Delivery SLA breaches increased significantly from June onward.
- Organic acquisition was the leading revenue channel.

These observations indicate areas requiring investigation. The analysis does not independently prove that the fictional crisis caused the changes.

## 💡 Business Recommendations

- Improve delivery partner allocation and route efficiency.
- Investigate customer complaints and negative reviews.
- Strengthen restaurant food-safety practices.
- Prioritize customer retention and trust-building campaigns.
- Monitor SLA performance and delivery delays.
- Establish monthly business recovery targets.

## 🔮 Future Scope

- Customer retention and repeat purchase analysis.
- Customer Lifetime Value (CLV) analysis.
- Machine Learning-based delivery delay prediction.
- Restaurant and delivery partner performance scoring.
- Automated data refresh and real-time monitoring.

## 📁 Project Structure

QuickBite-Express-Analytics/
│
├── datas/
│   ├── dim_customer_clean.csv
│   ├── dim_delivery_partner_clean.csv
│   ├── dim_menu_item_clean.csv
│   ├── dim_restaurant_clean.csv
│   ├── fact_delivery_performance_clean.csv
│   ├── fact_order_items_clean.csv
│   ├── fact_orders_clean.csv
│   └── fact_ratings_clean.csv
│
├── screenshots/
│
├── README.md
├── business_findings.md
└── mohanakrishnan_m_DS_may_26.pbix
```

## 👨‍💻 Skills Demonstrated

- Data Cleaning and Preprocessing
- Exploratory Data Analysis
- Data Modeling
- DAX Measures
- KPI Development
- Data Visualization
- Business Intelligence
- Analytical Thinking
- Business Recommendations

## 📝 Project Note

QuickBite Express is a fictional business case study developed for educational and portfolio purposes. Business findings are based on the dataset and analysis performed in this project.

---

**Thank you for visiting this project!** ⭐

If you find this project interesting, feel free to explore the dashboard and its business findings.
