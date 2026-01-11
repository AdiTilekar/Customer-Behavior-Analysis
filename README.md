# 🛒 Customer Shopping Behavior Analysis

## 📌 Project Overview
This project analyzes customer shopping behavior using transactional data from **3,900 purchases** across multiple product categories.  
The objective is to uncover insights into **spending patterns, customer segments, product preferences, discount usage, and subscription behavior** to support data-driven business decisions.

Technologies used include **Python**, **PostgreSQL**, and **Power BI**.

---

## 📊 Dataset Information
- 📄 **Records:** 3,900  
- 📑 **Columns:** 18  

### 🔑 Key Attributes
- 👤 **Customer Details:** Age, Gender, Location, Subscription Status  
- 🛍️ **Purchase Information:** Item Purchased, Category, Purchase Amount, Season, Size, Color  
- 📈 **Behavior Metrics:** Discount Applied, Promo Code Used, Previous Purchases, Purchase Frequency, Review Rating, Shipping Type  

---

## 🧹 Data Processing & EDA (Python)
- 📥 Loaded data using **pandas**
- 🔍 Performed initial exploration using `df.info()` and `df.describe()`
- 🧾 Standardized column names to **snake_case**
- ⚠️ Identified missing values in the `review_rating` column
- 🛠️ Filled missing ratings using **median values per product category**
- 🧪 Feature engineering:
  - `age_group`
  - `purchase_frequency_days`
- 🗑️ Removed redundant column `promo_code_used`
- 🗄️ Loaded cleaned dataset into **PostgreSQL**

---

## 🗄️ SQL Analysis (PostgreSQL)
Business questions answered using SQL queries:

- 💰 Revenue distribution by gender  
- 🎯 High-spending customers who used discounts  
- ⭐ Top 5 highest-rated products  
- 🚚 Spending comparison by shipping type  
- 👥 Subscriber vs non-subscriber revenue analysis  
- 🏷️ Discount-dependent product identification  
- 🔄 Customer segmentation (New, Returning, Loyal)  
- 📊 Revenue contribution by age group  
- 🥇 Top 3 products per category  
- 🔁 Subscription likelihood of repeat buyers  

---

## 📈 Power BI Dashboard
An interactive **Power BI dashboard** was built to visualize:
- 📉 Sales and revenue trends  
- 👥 Customer segmentation  
- 🛍️ Product performance  
- 🔐 Subscription insights  
- 💸 Discount impact  

---

## 💡 Business Recommendations
- 🚀 Promote subscriptions through exclusive benefits  
- ❤️ Introduce loyalty programs for repeat customers  
- ⚖️ Optimize discount strategies to protect profit margins  
- 🌟 Highlight top-rated and best-selling products  
- 🎯 Target marketing efforts toward high-revenue age groups  

---

## 🛠️ Tools & Technologies
- 🐍 **Python** (Pandas, NumPy)  
- 🗄️ **PostgreSQL**  
- 📊 **Power BI**

---

## 👤 Author
**Aditya Tilekar**
