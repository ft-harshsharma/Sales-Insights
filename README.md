# 📉 Sales Insights: Business Decline Analysis Dashboard  

A dynamic, interactive Power BI dashboard designed to analyze revenue decline across **markets, customers, and products** by decomposing changes into **Volume, Price, and Mix Effects**. This tool helps sales and management teams identify the **root causes of decline** and prioritize corrective actions.

---

## 🎯 Short Description / Purpose
The Sales Insights - Revenue Decline Analysis Dashboard is an analytical Power BI report that provides deep insights into revenue performance. It highlights how **volume drop** is the primary driver of decline, identifies **critical products**, and pinpoints **markets and customers** most responsible for the negative trend.  

This tool is intended for business analysts, sales managers, and decision-makers who need a clear, automated, and interactive view of sales decline drivers.

---

## 🛠 Tech Stack
The dashboard was built using the following tools and technologies:

- 📊 **Power BI Desktop** – Main data visualization platform used for report creation.  
- 📂 **Power Query** – Data transformation and cleaning for preparing raw sales data.  
- 🧠 **DAX (Data Analysis Expressions)** – Custom measures for decomposition, ranking, and Pareto analysis.  
- 📝 **Data Modeling** – Relationships among products, markets, customers, and dates.  
- 📁 **File Format** – `.pbix` for development and `.csv` for data inputs.

---

## 📂 Data Source
**Source**: Internal company sales transactions dataset  

- **Fact table**: `sales transactions`  
  - transaction-level data with `amount`, `order_date`, `product_code`, `customer_code`, `market_code`  
- **Dimension tables**:  
  - `sales products` (product attributes: Term, Status, Remarks)  
  - `sales customers` (customer details)  
  - `sales date` (calendar table with Year, Quarter, Month, etc.)  

---

## ✨ Features / Highlights

### Business Problem
The company observed a sharp revenue decline but lacked visibility into:
- Which **effect (Price, Mix, Volume)** is driving the decline.  
- Which **products, customers, and markets** are most responsible.  
- How concentrated the decline is (Pareto effect).  

### Goal of the Dashboard
- Deliver an **interactive tool** that identifies decline drivers.  
- Segment products into **Critical, Strong, Moderate, Long Tail** for prioritization.  
- Provide insights at **market, customer, and product levels**.  
- Automate reporting to replace manual analysis.  

### Walkthrough of Key Visuals
- **Performance Overview**: Cards (Revenue, Profit, Sales Qty, Profit%), YOY & QoQ trends.  
- **Markets Page**: Market revenue trends, slope analysis, bottom 5 worst markets.  
- **Customers Page**: Declining customers by market, contribution %, profitability.  
- **Products Page**: Segmentation into Core, Legacy, New, Dropped; Core vs Total revenue trends.  
- **Revenue Decomposition**: Waterfall chart of Price, Mix, Volume effects; effect trends over time.  
- **Pareto Analysis**: Bar + line chart showing cumulative product decline contribution; Critial, Strong and Moderate products out of Top 36 products.  
- **Summary Page**: Deep dive into top 36 products, with critical/strong/moderate categorization and detailed tooltips.  

### Business Impact & Insights
- **Root Cause Identified**: Volume Effect is the primary driver of decline (not price or mix).  
- **Product Insight**: Out of 339 products, 155 are core product responsible for overall decline; Top 36 products out of 155 contribute 80% of the Volume Effect. 3 critical products out of 36 alone cause 23% of the negative volume effect.  
- **Market Insight**: New Delhi is the steepest declining market, far ahead of others.  
- **Customer Insight**: Electricsara Stores is the most negatively impacted customer.  
- **Pareto Effect**: 36 products (≈20%) cause ~80% of the total decline.  

---

## 📷 Dashboard Screenshots  

### 1. Overview  
![Overview](images/1.%20Overview.png)  

### 2. Market Analysis  
![Market](images/2.%20Market.png)  

### 3. Customer Analysis  
![Customer](images/3.%20Customer.png)  

### 4. Product Analysis  
![Products](images/4.%20Products.png)  

### 5. Revenue Decomposition  
![Revenue Decomposition](images/5.%20Revenue%20Decomposition.png)  

### 6. Pareto Analysis
![Pareto Analysis](images/6.%20Pareto%20Analysis.png)  

### 7. Summary View  
![Summary](images/7.%20Summary.png)






---

## 🚀 Purpose
> To unlock sales insights that were not visible before for the sales team,  
> support better decision-making, and automate reporting to reduce manual effort.

---
