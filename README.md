# 📊 Super Store Business Explorer – Power BI Dashboard

## 📌 Project Overview

**Super Store Business Explorer** is an interactive Power BI dashboard developed to analyze sales, profit, orders, products, customers, geographical performance, shipping patterns, and discount scenarios.

The dashboard converts transactional Super Store data into meaningful business insights using **DAX measures, interactive filters, KPI cards, charts, maps, treemaps, and Sankey diagrams**.

---

## 🎯 Objectives

The dashboard is designed to help users:

- Monitor overall sales and profitability
- Analyze sales and profit trends over time
- Compare product category performance
- Identify geographical sales and profit patterns
- Understand regional shipping behavior
- Analyze customer and order characteristics
- Evaluate the potential impact of different discount scenarios
- Support data-driven business decisions

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Power Query** – Data cleaning and transformation
- **DAX** – Calculated measures and scenario analysis
- **Bing Maps / Power BI Maps** – Geographical analysis
- **Sankey Diagram** – Regional shipping-flow analysis
- **GitHub** – Project documentation

---

## 📂 Dataset

The dataset contains transactional information related to:

### Orders & Customers
- Order ID
- Row ID
- Order Date
- Order Priority
- Order Quantity
- Customer Name
- Customer Segment

### Products
- Product Name
- Product Category
- Product Sub-Category
- Product Container
- Product Base Margin

### Financial Data
- Sales
- Profit
- Discount
- Unit Price
- Shipping Cost

### Geography & Shipping
- City
- State
- Region
- Zip Code
- Ship Date
- Ship Mode

---

## 🧮 DAX Measures

A dedicated **Measures Table** was created to organize the dashboard calculations.

### Core Measures
- `Total Sales`
- `Total Profit`
- `Total Orders`
- `Total Quantity`
- `Profit Margin`
- `Average Order Value`
- `Gross Sales`
- `Current Cost`

### Scenario Measures
- `Scenario Sales`
- `Scenario Profit`
- `Scenario Profit Margin`
- `Scenario Average Order Value`

These measures provide reusable calculations for the dashboard KPIs and interactive scenario analysis.

---

## 📊 Key Dashboard Features

### KPI Cards

The dashboard provides a high-level summary of business performance:

| KPI | Value |
|---|---:|
| Total Sales | 14.92M |
| Total Profit | 1.52M |
| Total Orders | 5K |
| Profit Margin | 0.10 |
| Average Order Value | 2.71K |

---

### 🎛️ Interactive Filters

Users can dynamically filter the dashboard by:

- Ship Mode
- State
- Region
- Product Category
- Year
- Order Priority
- Customer Segment

All major visuals respond to the selected filters, allowing users to explore specific business segments.

---

### 📈 Sales & Profit by Year

A combination chart compares **Sales and Profit by Year**, helping identify changes in financial performance and trends over time.

---

### 🗺️ Geographical Sales & Profit Map

The map visualizes sales and profit across different geographical locations in the United States.

It helps identify areas with higher business activity and supports regional performance analysis.

---

### 🗂️ Product Treemap

The treemap compares the major product categories:

- Technology
- Furniture
- Office Supplies

It provides a quick visual understanding of category-level business contribution.

---

### 🔀 Sankey – Order Flow

The Sankey diagram shows the flow between:

**Region → Ship Mode**

It helps analyze how shipping methods are distributed across:

- South
- East
- West
- Central

and shipping modes such as:

- Delivery Truck
- Express Air
- Regular Air

---

## 🎚️ Discount Scenario Analysis

A **Discount Scenario** parameter allows users to evaluate alternative discount assumptions.

The dashboard dynamically displays:

- Scenario Sales
- Scenario Profit
- Scenario Profit Margin
- Scenario Average Order Value

This provides a simple **what-if analysis** for understanding how discount changes may affect business performance.

---

## 📄 Dashboard Pages

The Power BI project includes several analytical pages:

1. **Exploratory Dashboard** – Interactive overview of business performance
2. **Sales vs Profit Margin** – Financial relationship analysis
3. **Line Chart** – Trend analysis
4. **Annotated Geographic Map** – Location-based analysis
5. **Explanatory Dashboard** – Focused presentation of key insights

---

## 💡 Business Insights

The dashboard enables users to identify:

- Overall sales and profit performance
- Yearly changes in sales and profitability
- Strong and weak geographical areas
- Product category contribution
- Regional shipping patterns
- Potential effects of different discount levels

The insights dynamically change based on the selected filters and scenarios.

---

## 🧠 Skills Demonstrated

- Business Intelligence
- Power BI Dashboard Development
- DAX
- Power Query
- Data Visualization
- KPI Development
- Interactive Dashboard Design
- Geographical Analysis
- What-If / Scenario Analysis
- Business Data Analysis

---

## 📁 Project Structure

```text
Super-Store-Business-Explorer/
│
├── README.md
├── PowerBI/
│   └── Super_Store_Business_Explorer.pbix
├── Dataset/
│   └── SuperStore.csv
└── Screenshots/
    └── dashboard screenshots
