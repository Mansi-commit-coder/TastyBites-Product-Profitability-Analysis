<img width="1390" height="740" alt="Screenshot (141)" src="https://github.com/user-attachments/assets/9f11f5f3-a732-47b1-adc5-9de9cc0ec74f" />
# 🍔 TastyBites – Product Profitability & Pricing Strategy Analysis

## 📌 Project Overview

This project focuses on analyzing sales performance, product profitability, discount effectiveness, 
and pricing strategies for **TastyBites**, a food delivery business.

The objective is to identify high-performing products, understand the impact of discounts on profit margins, 
evaluate product and category performance, and provide actionable business recommendations to improve 
profitability and revenue.

The analysis uses business data to transform raw sales records into meaningful insights that support data-driven decision-making.

## 🎯 Business Objectives

- Identify products and categories generating the highest revenue and profit.
- Analyze how discounts affect profitability and profit margins.
- Identify high-volume products with opportunities for profit improvement.
- Evaluate pricing strategies and potential price adjustments.
- Recommend promotional offers and product bundles to increase revenue.

## 🛠️ Tools & Technologies

- **Power BI** – Data visualization, dashboard development, and business reporting.
- **Microsoft Excel / CSV** – Dataset inspection and data preparation.
- **Data Analytics** – Exploratory data analysis, KPI calculations, and business insights.

## 📂 Dataset Description

The dataset contains 1,000 order records with the following columns:

| Column | Description |
|---|---|
| OrderID | Unique order identifier |
| OrderDate | Date of the order |
| ProductID | Unique product identifier |
| ProductName | Name of the product |
| Category | Product category |
| Quantity | Number of units sold |
| UnitPrice | Selling price per unit |
| CostPerUnit | Cost of each unit |
| Discount | Discount applied per unit |
| CustomerType | Type of customer |
| PaymentMode | Payment method used |

## 📊 Key Performance Indicators (KPIs)

| KPI | Formula |
|---|---|
| Gross Revenue | Quantity × Unit Price |
| Discount Amount | Quantity × Discount |
| Net Revenue | Gross Revenue − Discount Amount |
| Total Cost | Quantity × Cost Per Unit |
| Total Profit | Net Revenue − Total Cost |
| Profit Margin | (Total Profit / Net Revenue) × 100 |
| Average Order Value | Net Revenue / Total Orders |
| Total Orders | Distinct Count of OrderID |
| Units Sold | Sum of Quantity |

## 🔍 Key Business Insights

### 1. Product Performance
- Combo Meal generates the highest net revenue and absolute profit.
- French Fries has the highest sales volume, with 401 units sold.
- Lemonade has the highest profit margin at approximately 57.28%, despite generating the lowest absolute profit among the products.

### 2. Category Performance
- Meals generate the highest category revenue and profit.
- Beverages have the highest category profit margin at approximately 55.69%.
- Combos have the lowest category profit margin at approximately 42.10%.

### 3. Discount Analysis
- Transactions with positive discounts show a lower profit margin than transactions with explicitly zero discounts.
- Discounted transactions have an average profit margin of approximately 44.36%, compared with 49.22% for zero-discount transactions.
- This indicates an association between discount status and lower margins, although it does not establish that discounts alone caused the reduction.

### 4. Overall Business Performance

| Metric | Result |
|---|---:|
| Total Orders | 1,000 |
| Units Sold | 2,979 |
| Gross Revenue | ₹530,730 |
| Total Discounts | ₹27,495 |
| Net Revenue | ₹503,235 |
| Total Cost | ₹270,085 |
| Total Profit | ₹233,150 |
| Overall Profit Margin | 46.33% |
| Average Order Value | ₹503.24 |

## 💡 Business Recommendations

1. **Optimize Product Pricing:** Conduct controlled 3–5% price-increase experiments on selected high-volume products and monitor customer response.

2. **Improve Discount Strategy:** Use targeted discounts instead of applying broad promotional offers across all products.

3. **Promote High-Margin Products:** Increase the visibility of beverages such as Lemonade and Cold Coffee.

4. **Introduce Product Bundles:** Test meal-and-beverage combinations and French Fries add-ons to increase average order value.

5. **Monitor Profit Margins:** Establish minimum profit-margin targets before launching promotional campaigns.

## 📈 Dashboard & Analysis

The Power BI dashboard can be used to explore:

- Overall sales and profitability KPIs.
- Product-wise revenue and profit.
- Category-wise sales and profit margins.
- Discount impact on profitability.
- Product sales volume and performance.
- Business performance across different dimensions.

## ⚠️ Assumptions & Limitations

- Missing discount values are treated as zero for headline financial calculations, while missing values
  are kept separate for discount comparisons.
- Discount is assumed to represent a currency amount per unit.
- Delivery and operational expenses are excluded because they are not available in the dataset.
- Historical sales data alone cannot establish price elasticity or prove the causal impact of discounts.
- Pricing recommendations should be validated through controlled experiments.

## 🏁 Conclusion

The analysis highlights that revenue generation and profitability are not always driven by the same products. 
While Combo Meal contributes the highest absolute profit, beverages generate stronger profit margins.

By improving discount strategies, testing pricing adjustments, and promoting high-margin products through targeted bundles, 
TastyBites can work toward sustainable revenue growth and improved profitability.

---

**Project Type:** Business Analytics | Product Profitability | Pricing Strategy

**Created using:** Power BI, Excel/CSV, and Data Analytics

**Author:** Mansi Sinha
