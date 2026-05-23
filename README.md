# 📊 Amazon India Sales Power BI Dashboard

An interactive Power BI dashboard that delivers a comprehensive analysis of Amazon's sales performance — tracking revenue trends, product rankings, customer engagement, and category contributions through dynamic visuals and time-intelligence measures.

---

## 📸 Dashboard Preview

<img width="1167" height="656" alt="Screenshot " src="https://github.com/user-attachments/assets/98382ec6-1840-4874-8c71-b1a137e26c11" />


---

## 🎯 Objective

Analyze Amazon's sales data to uncover performance patterns, identify high-revenue products, and understand seasonal sales behavior — demonstrating end-to-end BI skills from data preparation to visual storytelling.

**Skills demonstrated:**
- Data cleaning and transformation using Power Query
- Data modeling with DAX and table relationships
- Time-intelligence calculations (YTD, QTD)
- Interactive dashboard design with slicers and filters
- Deriving actionable business insights

---

## 🧩 Dataset

The dataset consists of **6 columns** capturing product and order-level sales information:

| Column | Description |
|---|---|
| `Product Category` | Category of the product (e.g., Camera, Toys, Clothes) |
| `Product Description` | Name or description of the product |
| `Price` | Selling price of the product |
| `Number of Reviews` | Total customer reviews received |
| `Shipment` | Number of shipments made |
| `Order Date` | Date the order was placed |


### Relationship
A **one-to-many** relationship was established between:

```
Date Table[Date]  →  Amazon_Data[Order Date]
```

---

## 📊 Dashboard Features

### KPI Cards

| Metric | Value |
|---|---|
| YTD Sales | $2.18M |
| QTD Sales | $811.09K |
| YTD Products Sold | 27.75K |
| YTD Reviews | 19.42M |

### Visuals

| Visual Type | Purpose |
|---|---|
| Line Chart | Monthly sales trends |
| Column Chart | Weekly sales distribution |
| Bar Chart | Top 5 products by YTD Sales |
| Bar Chart | Top 5 products by YTD Reviews |
| Table | Category-wise sales with % of YTD Sales |
| Slicers | Filter by Product Category and Quarter |

---

## 💡 Key Insights

- **Men's Shoes** is the top-grossing category, contributing **43.18%** of total YTD sales.
- **Cameras** and **Men's Clothes** are consistent secondary performers with steady growth.
- Sales peaked in **September** and **December**, indicating strong seasonal demand patterns.
- **SanDisk** products led in customer engagement, recording the highest review counts.
- Month-over-month growth trends suggest effective product placement and sustained demand.

---

## 🎨 Design Decisions

| Element | Choice | Reason |
|---|---|---|
| Background | Dark navy blue | Professional contrast, reduces eye strain |
| Accent colors | Orange & cyan | High visibility against dark background |
| Layout | KPIs top, charts below | Follows natural reading hierarchy |
| Borders | Minimal | Keeps focus on data, reduces visual noise |
| Filters | Top-level slicers | Easy access for category and quarter drilldown |

---

## 🚀 Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Power BI Desktop | Dashboard development |
| Power Query | Data transformation and cleaning |
| DAX | Calculated columns, measures, time intelligence |
| GitHub | Version control and project showcase |

---

## 🗣️ Project Summary

> Built this Power BI dashboard to analyze Amazon's sales performance across products, categories, and time periods. A custom Date Table enabled time-intelligence measures like YTD and QTD Sales. Key findings: Men's Shoes dominated revenue at 43% of total sales, while seasonal spikes in September and December highlighted strong demand windows — insights that could directly inform inventory and marketing strategies.
