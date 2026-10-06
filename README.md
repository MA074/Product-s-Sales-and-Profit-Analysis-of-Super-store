# 📊 Product's Sales and Profit Analysis of Superstore

An interactive **Power BI dashboard** designed to analyze retail sales and profitability performance across products, categories, years, and U.S. states using the Superstore dataset.

The dashboard provides a consolidated view of **sales, profit, discount, product performance, and geographical profitability**, helping identify areas of strong performance as well as products and regions contributing disproportionately to low profits.

---

## 📊 Dashboard Preview

![Superstore Sales and Profit Analysis Dashboard](superstore.png)

---

## 📌 Project Overview

### 🎯 Objective

The primary objective of this project is to analyze **2017–2020 retail sales and profit performance** and uncover the factors influencing profitability.

The dashboard focuses on:

- Tracking sales and profit trends over time
- Comparing sales performance across product categories
- Identifying products associated with high sales but low or negative profit
- Examining the relationship between sales, profit, and discount
- Identifying geographical variations in profitability across U.S. states
- Highlighting areas, categories, and products requiring further investigation

The project demonstrates how interactive business intelligence dashboards can transform transactional data into actionable business insights.

---

## 🗂️ Data Source

**Dataset:** Superstore Dataset

The Superstore dataset contains retail transaction-level information covering products, categories, sales, profit, discounts, customers, and geographical information.

The dashboard primarily utilizes fields related to:

- Sales
- Profit
- Discount
- Product Category
- Product Name
- Year
- State

---

## ✨ Key Features & Visualizations

### 1. 🏷️ Sales by Category

A horizontal bar chart compares total sales across the three major product categories:

- **Technology**
- **Furniture**
- **Office Supplies**

Technology generates the highest sales, followed by Furniture and Office Supplies.

This visualization provides a quick comparison of category-level revenue contribution.

---

### 2. 📈 Sales and Profit by Year

A dual-axis line chart compares yearly sales and profit from **2017 to 2020**.

It allows users to observe:

- Overall sales growth
- Year-to-year changes in profitability
- The relationship between revenue growth and profit generation

The visualization provides an overview of whether increasing sales are accompanied by corresponding improvements in profit.

---

### 3. 🫧 Profit and Discount over Sales

The bubble chart examines the relationship between:

**Sales ↔ Profit ↔ Discount**

Products are visually separated based on profitability:

- 🔵 **Positive Profit**
- 🟢 **Negative Profit**

The chart makes it easier to identify products that generate substantial sales but produce little or negative profit.

This is particularly useful for investigating whether discounting or other product-level factors may be contributing to poor profitability.

---

### 4. 🗺️ Profit by State

A U.S. map visualizes profitability geographically using transition-based colors.

The map helps identify:

- States generating stronger profits
- States with relatively poor profitability
- Geographic concentration of profitable and underperforming markets

Users can also interact with the **State** filter to investigate individual states.

---

### 5. 🎛️ Interactive Filters

The dashboard includes interactive filters that allow users to dynamically explore the data.

Available filters include:

- **Year**
- **Quarter**
- **Month**
- **Day**
- **Profit Category**
- **State**

These filters allow users to move from a high-level overview to more specific analyses without leaving the dashboard.

---

## 💡 Key Business Insights

### 📈 1. Sales show a strong overall upward trend

Sales increase substantially over the four-year period.

The dashboard shows sales of approximately:

| Year | Sales |
|------|------:|
| 2017 | $0.48M |
| 2018 | $0.47M |
| 2019 | $0.61M |
| 2020 | $0.73M |

Although sales experienced a slight decline in 2018, the overall trend from 2017 to 2020 is strongly positive.

---

### 💰 2. Profit improves steadily after 2017

Profit follows a different pattern from sales.

The dashboard indicates approximately:

| Year | Profit |
|------|-------:|
| 2017 | $50K |
| 2018 | $62K |
| 2019 | $82K |
| 2020 | $93K |

Unlike sales, profit does not decline in 2018. Instead, it shows a steady upward trend throughout the period.

This suggests that the business was able to improve profitability even while sales experienced a temporary slowdown in 2018.

---

### ⚠️ 3. High sales do not necessarily translate into high profit

The **Profit and Discount over Sales** visualization highlights an important business problem: some products generate significant sales while producing relatively low or negative profit.

This demonstrates why evaluating sales alone can be misleading.

A product may appear successful based on revenue but may require further investigation when profitability, discounting, and associated costs are considered.

The supplementary product-level visualization helps pinpoint these potentially underperforming products.

---

### 🏆 4. Technology is the leading sales category

Technology records the highest sales among the three major product categories at approximately **$0.84M**, followed by:

- Furniture — approximately **$0.74M**
- Office Supplies — approximately **$0.72M**

This indicates that Technology is the strongest category in terms of overall sales contribution.

---

### 🌎 5. Profitability varies significantly by geography

The state-level map demonstrates that profitability is not evenly distributed across the United States.

Some states contribute strongly to overall profit, while others show weaker or negative performance.

This geographic variation can help businesses investigate regional pricing, discounting, product mix, and market-specific factors.

---

## 🔎 Business Questions Addressed

This dashboard can be used to answer questions such as:

- Which product category generates the highest sales?
- How have sales and profit changed from 2017 to 2020?
- Are increasing sales accompanied by increasing profits?
- Which products generate high sales but low or negative profit?
- How does discounting relate to profitability?
- Which U.S. states generate the highest profits?
- Which geographical regions require further investigation?
- Where are sales strong but profitability comparatively weak?

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Microsoft Power BI** | Dashboard development and visualization |
| **Power Query** | Data preparation and transformation |
| **DAX** | Calculations and analytical measures |
| **Superstore Dataset** | Source data |
| **GitHub** | Project version control and portfolio hosting |

