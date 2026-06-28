# 📊 Retail Sales Analysis Using Microsoft Excel 

<img width="263" height="148" alt="Image" src="https://github.com/user-attachments/assets/963b12be-dcb8-4379-9f2f-1880d235f742" />

## 📌 Project Overview

This project explores a retail sales dataset using **Microsoft Excel** to identify customer purchasing behavior, spending trends, product popularity, and the relationship between product pricing and purchase quantity.

The analysis was completed using **Pivot Tables**, **Pivot Charts**, **Scatter Plots**, and **Correlation Analysis** to answer key business questions and generate actionable insights.

---

## 📂 Dataset Information

The dataset contains **1,000 retail transactions** with customer and sales information, including:

- Customer Age
- Gender
- Product Category
- Quantity Purchased
- Price per Unit
- Total Amount
- Purchase Date (Month & Year)

---

## 🎯 Project Objectives

The analysis answers the following business questions:

1. Analyze spending patterns by gender and age.
2. Track the most popular product categories over time.
3. Determine whether price affects the quantity of products purchased.
4. Analyze how age affects each product category.
5. Identify which month has the highest customer spending.

---

## 🛠️ Tools Used

- Microsoft Excel
- Pivot Tables
- Pivot Charts
- Scatter Plot
- Correlation Analysis
- Dashboard Design

---

# 📈 Analysis & Findings

## 1️⃣ Spending Pattern by Age and Gender

### Objective

Determine how customer spending differs by age and gender.

### Method

A Pivot Table was created using:

- Rows → Age
- Columns → Gender
- Values → Sum of Total Amount

A clustered column chart was then used for visualization.

### Results

| Gender | Total Spending |
|---------|---------------:|
| Female | **232,840** |
| Male | **223,160** |
| **Grand Total** | **456,000** |

### Key Findings

- Female customers spent slightly more than male customers.
- The highest overall spending occurred at:
  - Age **43** (17,970)
  - Age **34** (16,785)
  - Age **51** (16,065)
- Customers between ages **30 and 50** contributed most of the sales.

### Business Insight

The retailer's primary customers appear to be adults between **30–50 years old**, with female customers contributing slightly more revenue than male customers.

---

## 2️⃣ Most Popular Product Categories Over Time

### Objective

Identify the most frequently purchased product category throughout the year.

### Method

A Pivot Table counted the number of purchases by month for each product category.

### Results

| Product Category | Total Purchases |
|-----------------|----------------:|
| Clothing | **351** |
| Electronics | **342** |
| Beauty | **307** |

### Monthly Highlights

#### Beauty

- Highest: October (31)
- Lowest: September (20)

#### Clothing

- Highest: March (38)
- Lowest: July (19)

#### Electronics

- Highest: May (40)
- Highest: December (40)
- Lowest: March (14)

### Business Insight

- Clothing is the most popular product category.
- Electronics experience seasonal demand peaks.
- Beauty products maintain relatively stable sales throughout the year.

---

## 3️⃣ Does Price Affect the Quantity Purchased?

### Objective

Determine whether product price influences customer purchasing quantity.

### Method

A Scatter Plot and Correlation Analysis were performed between:

- Price per Unit
- Quantity Purchased

### Correlation Result

| Variables | Correlation |
|-----------|------------:|
| Price vs Quantity | **0.0175** |

### Interpretation

The correlation coefficient (**0.0175**) is extremely close to zero.

This indicates **almost no relationship** between product price and the quantity purchased.

Although the trendline has a slight positive slope, the relationship is too weak to conclude that higher prices increase purchase quantity.

### Business Insight

Customer purchasing decisions are likely influenced by factors other than price, such as product preferences, promotions, or seasonal demand.

---

## 4️⃣ How Does Age Affect Each Product Category?

### Objective

Determine whether customer age influences product category preference.

### Method

A Pivot Table was created to count purchases for each product category.

### Results

| Product Category | Number of Purchases |
|-----------------|--------------------:|
| Clothing | **351** |
| Electronics | **342** |
| Beauty | **307** |
| **Total** | **1000** |

### Interpretation

- Clothing was purchased most frequently.
- Electronics ranked second.
- Beauty had the fewest purchases.

### Business Insight

Based on the available data, no clear relationship between **customer age** and **product category preference** can be established because the Pivot Table only counts purchases by category.

A more detailed analysis using **age groups (18–25, 26–35, 36–45, etc.)** would provide better insights into age-based purchasing preferences.

---

## 5️⃣ Which Month Has the Highest Spending?

### Objective

Identify the month with the highest customer spending.

### Method

A Pivot Table calculated the **Average Total Amount** for each month.

### Results

| Month | Average Spending |
|--------|----------------:|
| January | 474.10 |
| February | **518.35** |
| March | 397.12 |
| April | 393.84 |
| May | 506.19 |
| June | 476.82 |
| July | 492.57 |
| August | 393.19 |
| September | 363.38 |
| October | 485.21 |
| November | 447.69 |
| December | 491.10 |

### Key Findings

- February recorded the highest average customer spending (**518.35**).
- September had the lowest average spending (**363.38**).
- Spending increased during May, July, October, and December, suggesting seasonal purchasing behavior.

### Business Insight

February appears to be the strongest month for customer spending. Seasonal promotions and marketing campaigns could be planned around high-performing months to maximize revenue.

> **Note:** This analysis uses the **Average of Total Amount**. If the objective is to identify the month with the highest **total revenue**, the Pivot Table should use the **Sum of Total Amount** instead of the average.

---

# 📊 Dashboard

The Excel dashboard includes the following visualizations:

- Spending Pattern by Age and Gender (Clustered Column Chart)
- Most Popular Product Categories Over Time (Line Chart)
- Price vs Quantity Purchased (Scatter Plot)
- Product Category Summary
- Monthly Spending Analysis

---

# 📌 Key Insights

- Female customers generated slightly more revenue than male customers.
- Customers aged **30–50** contributed the highest spending.
- Clothing was the most frequently purchased product category.
- Electronics showed noticeable seasonal demand.
- Product price had almost no effect on purchase quantity (Correlation = **0.0175**).
- February recorded the highest average customer spending.
- Age-based preference for product categories could not be confirmed with the available analysis.

---

# 💼 Skills Demonstrated

- Data Cleaning
- Microsoft Excel
- Pivot Tables
- Pivot Charts
- Dashboard Design
- Data Visualization
- Correlation Analysis
- Business Analytics
- Trend Analysis
- Retail Sales Analysis

---

# 📷 Dashboard Preview

> Add screenshots of your Excel dashboard here.

```
images/dashboard.png
images/spending-pattern.png
images/product-trend.png
images/price-vs-quantity.png
```

---

## 👤 Author

**Your Name**

Microsoft Excel Retail Sales Analysis Project

---
⭐ If you found this project useful, feel free to star the repository. 
