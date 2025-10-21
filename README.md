# 🛍️ Customer Shopping Behavior Analysis

_Uncovering insights from transactional data to guide strategic business decisions._

---

## 📘 Project Overview

This project analyzes **3,900 customer purchases** across multiple product categories to understand consumer behavior and drive **data-informed business strategies**.

### 🎯 Objectives
- **Analyze** transactional and demographic data.  
- **Uncover** key spending patterns, customer segments, and product preferences.  
- **Guide** marketing and operational strategies using insights from SQL and Python analysis.

---

## 🧾 Dataset Summary

| Attribute Type | Description |
|----------------|--------------|
| **Dataset Size** | 3,900 rows × 18 columns |
| **Demographics** | Age, Gender, Location, Subscription |
| **Purchase Details** | Item, Category, Amount, Season, Size, Color |
| **Shopping Behavior** | Discount, Promo, Frequency, Rating, Shipping |
| **Missing Data** | 37 missing values in `review_rating` column |

---

## 🐍 Exploratory Data Analysis (Python)

### Data Preparation & Feature Engineering
- **Loaded dataset** using `pandas` and examined structure & summary statistics.  
- **Handled missing data** by imputing missing review ratings using the **median rating per category**.  
- **Standardized columns** (snake_case naming) and dropped redundant fields (`promo_code_used`).  
- **Feature Engineering:** Created  
  - `age_group`  
  - `purchase_frequency_days` (mapped frequency to days: weekly, monthly, quarterly, etc.)

---

## 🧮 SQL Analysis

### 💰 Revenue & Spending Patterns
- **Revenue by Gender:**  
  Male customers generated **significantly higher revenue**.  
- **Shipping Type vs. Average Spend:**

| Shipping Type | Avg. Spend (USD) |
|----------------|------------------|
| Standard | 58.46 |
| Express | 60.48 |

---

### 🏷️ Product & Discount Insights
- **Top 5 Rated Products:**  
  Gloves (3.86), Sandals (3.84), Boots (3.82), Hat (3.80), Skirt (3.78)  
- **Discount-Dependent Products:**  
  Hat (50.00%), Sneakers (49.66%), Coat (49.07%)  
- **High-Spending Discount Users:**  
  Identified **839 customers** who used discounts but still spent above the average purchase amount.

---

### 👥 Customer Segmentation
- **Customer Categories:**  
  - Loyal — 3,116 customers  
  - Returning — 701 customers  
  - New — 83 customers  
- **Subscription Analysis:**  
  - Non-Subscribers: 2,847 customers / $170,436 revenue  
  - Subscribers: 1,053 customers / $62,645 revenue  
  - Among repeat buyers (>5 purchases), **958 are subscribers.**

---

### 👗 Product Category Insights

| Category | Top Item | Total Orders |
|-----------|-----------|---------------|
| Accessories | Jewelry | 171 |
| Clothing | Blouse | 171 |
| Footwear | Sandals | 160 |
| Outerwear | Jacket | 163 |

---

### 🧓 Age Group Revenue Contribution
- **Young Adults** generated the **highest revenue**, followed closely by **Middle-Aged customers**.

---

## 💡 Business Recommendations

| Focus Area | Recommendation |
|-------------|----------------|
| **Subscriptions** | Promote exclusive benefits to increase subscriber base. |
| **Customer Loyalty** | Implement reward programs for repeat buyers. |
| **Discount Policy** | Review discount dependency to maintain profit margins. |
| **Product Strategy** | Feature top-rated and best-selling items in marketing. |
| **Target Marketing** | Focus efforts on high-revenue age groups and express-shipping users. |

---

## 🧰 Tools & Technologies
- **Python:** pandas, numpy, matplotlib, seaborn  
- **SQL:** Data querying, aggregation, and segmentation  
- **PowerPoint / Power BI:** Visualization and presentation of key insights  

---

## 📈 Key Takeaways
- Male and express-shipping users drive more revenue.  
- Young adults are the most valuable customer group.  
- Subscription programs need optimization for higher engagement.  
- Balanced discount strategies can maintain both **sales volume** and **profit margin**.

---

## 👨‍💻 Author
**Ramesh Sonta**  
📍 BTech Graduate, IARE College  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/sonta-ramesh/)
