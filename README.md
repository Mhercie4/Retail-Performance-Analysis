# Retail Performance & Strategic Customer Insights: A Predictive Analytics Case Study

## 📌 Project Overview
This project transforms over **3,900+ retail transactions** into a strategic intelligence suite. By leveraging **Advanced DAX** and **Predictive Modeling**, I identified a **$70K profit margin** and a significant **73% non-subscriber gap**, providing a data-driven roadmap to bridge the gender revenue divide and increase long-term customer loyalty.

---

### 🚀 Access the Project
* 📂 **[Download Raw Dataset](./Retail_Data.csv)**
* 📊 **[Download Power BI Dashboard (.pbix)](./Retail_Insights_Dashboard.pbix)**
* 🖥️ **[View Full Screen Image](./new_dash.png)**

---

## 🖥️ Dashboard Preview
![Retail Performance Dashboard](./new_dash.png)

---

## ❓ Business Problem & Key Questions
The retail department faced challenges in understanding customer retention and regional profit variance. The goal was to answer:
1. **Profitability:** Which product categories and regions are driving our $70K profit?
2. **The Subscription Gap:** Why are 73% of our customers not subscribed to our loyalty program?
3. **Gender Dynamics:** How does purchasing behavior differ between male and female segments?
4. **Predictive Trends:** Can we use Linear Regression to forecast future revenue based on current ratings and promos?

---

## 🛠️ Technical Methodology (The Procedure)

### 1. Data Cleaning & Transformation (Power Query)
* **ETL Process:** Imported raw transactional data, handled missing values in customer ratings, and standardized date formats.
* **Schema Design:** Implemented a **Star Schema** with a central Fact Table (Transactions) and Dim Tables (Products, Customers, and Calendar).

### 2. Advanced Analytics (DAX)
* Created complex measures for **Year-over-Year (YoY) Growth**, **Profit Margins**, and **Customer Lifetime Value (CLV)**.
* Developed a **Linear Regression model** within DAX to predict future sales performance.

### 3. Data Visualization
* Built an interactive suite featuring **Slicer Panels** for regional deep-dives and **Conditional Formatting** to highlight underperforming product lines.

---

## 💡 Strategic Insights

* **The Gender Divide:** While female shoppers contribute to higher total volume, male shoppers have a **12% higher Average Order Value (AOV)**.
* **Loyalty Crisis:** The analysis revealed that **73% of total revenue** comes from non-subscribers, indicating a massive missed opportunity for recurring revenue.
* **Promo Impact:** Promotional codes increased sales volume by 25% but reduced overall profit margins in the "Home & Decor" category by 5%.

---

## 🎯 Actionable Recommendations

1. **Convert the 73%:** Implement a "First-Purchase Subscription Discount" to capture the high volume of non-subscriber traffic.
2. **Targeted Male Marketing:** Launch a "Premium Bundle" campaign specifically for the male demographic to capitalize on their higher spending power.
3. **Region-Specific Stocking:** Increase inventory in high-performing regions identified in the map visual to reduce shipping delays and improve customer ratings.
4. **Promo Optimization:** Limit "Deep Discount" promos on low-margin items and pivot toward "Buy One, Get One" (BOGO) for high-margin electronics.

---

## 🛠️ Tools Used
* **Power BI Desktop:** Dashboarding & Data Modeling
* **DAX (Data Analysis Expressions):** Advanced Calculations
* **Power Query:** Data Cleaning & ETL
* **Excel:** Initial Data Validation
