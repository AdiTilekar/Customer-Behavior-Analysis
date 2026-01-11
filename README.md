# Customer Shopping Behavior Analysis

## Project Overview
This project focuses on analyzing customer shopping behavior using transactional data consisting of 3,900 purchase records across multiple product categories. The main objective is to identify spending patterns, customer segments, product preferences, discount behavior, and subscription trends to support informed business decisions.

The project is implemented using Python for data analysis, PostgreSQL for SQL-based insights, and Power BI for visualization.

---

## Dataset Information
- Records: 3,900
- Columns: 18

### Key Attributes
- Customer Details: Age, Gender, Location, Subscription Status
- Purchase Information: Item Purchased, Category, Purchase Amount, Season, Size, Color
- Behavior Metrics: Discount Applied, Promo Code Used, Previous Purchases, Purchase Frequency, Review Rating, Shipping Type

---

## Data Processing and EDA
- Data loaded and explored using pandas
- Column names standardized to snake_case
- Missing values identified in the review_rating column
- Missing ratings filled using median values by product category
- Feature engineering performed:
  - age_group
  - purchase_frequency_days
- Removed redundant promo_code_used column
- Cleaned dataset loaded into PostgreSQL

---

## SQL Analysis
The following business insights were derived using SQL:
- Revenue distribution by gender
- Identification of high-spending discount users
- Top 5 highest-rated products
- Comparison of spending by shipping type
- Subscriber vs non-subscriber revenue analysis
- Discount-dependent product identification
- Customer segmentation into New, Returning, and Loyal
- Revenue contribution by age group
- Top 3 products per category
- Subscription likelihood of repeat buyers

---

## Power BI Dashboard
An interactive Power BI dashboard was created to visualize:
- Sales and revenue trends
- Customer segments
- Product performance
- Subscription insights
- Discount impact

---

## Business Recommendations
- Encourage subscriptions through exclusive benefits
- Introduce loyalty programs for repeat customers
- Optimize discount strategies to maintain profit margins
- Promote top-rated and high-selling products
- Target marketing campaigns towards high-revenue age groups

---

## Tools and Technologies
- Python (Pandas, NumPy)
- PostgreSQL
- Power BI

---

## Author
Aditya Tilekar
