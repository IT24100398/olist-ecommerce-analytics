# 📊 Olist Analytics — E-Commerce Performance & Customer Intelligence

An interactive **Power BI Business Intelligence dashboard** built using the Brazilian E-Commerce Public Dataset by Olist.

This project analyzes e-commerce performance across **sales, customers, products, payments, delivery operations, and customer satisfaction**, transforming raw transactional data into actionable business insights.

---

## 📌 Project Overview

The goal of this project is to understand the performance of an e-commerce business from multiple perspectives:

- 💰 Revenue and order performance
- 👥 Customer behavior and segmentation
- 🛍️ Product category performance
- 🚚 Delivery performance
- ⭐ Customer satisfaction
- 💳 Payment method usage
- 📍 Geographic sales distribution
- 🔄 Customer purchasing behavior

The project was developed using **Microsoft Power BI**, with data modeling, calculated measures, interactive filtering, and business-focused visualizations.

---

## 🗂️ Dataset

The project uses the:

**Brazilian E-Commerce Public Dataset by Olist**

The dataset contains approximately **100,000 orders from 2016–2018** and is distributed across multiple related datasets.

### Dataset Source

🔗 [Olist Brazilian E-Commerce Dataset — Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

### Main Tables

| Dataset | Purpose |
|---|---|
| Orders | Order status and order lifecycle |
| Customers | Customer information and location |
| Order Items | Products purchased, price and freight |
| Products | Product categories and attributes |
| Sellers | Seller information and location |
| Payments | Payment methods and transaction values |
| Reviews | Customer review scores |
| Geolocation | Brazilian ZIP code coordinates |
| Category Translation | Portuguese → English category names |

The dataset is real commercial data provided by Olist and anonymized for public use.

---

# 🎯 Business Questions

This dashboard was designed to answer questions such as:

### Sales & Business Performance

- How is revenue changing over time?
- Which product categories generate the most revenue?
- Which states contribute the most revenue?
- What is the average order value?
- How many orders and customers does the business have?

### Customer Intelligence

- Which customers generate the most revenue?
- How many new vs returning customers are there?
- Which customer segments contribute the most revenue?
- What is the purchasing frequency of different customer segments?
- Which customers may require retention strategies?

### Delivery Performance

- What percentage of orders are delivered late?
- What is the average delivery time?
- Which states have longer delivery times?
- How are delivery delays distributed?
- Does delivery performance relate to customer satisfaction?

### Customer Satisfaction

- What is the distribution of customer review scores?
- How does delivery performance relate to review scores?
- Which areas may contribute to poor customer experiences?

---

# 📊 Dashboard Pages

## 1️⃣ E-Commerce Overview

The executive overview provides a high-level view of business performance.

### Key KPIs

- Total Revenue
- Total Orders
- Total Customers
- Average Order Value

### Visualizations

- Order Status Distribution
- Revenue Trend
- Payment Method Distribution
- Top Product Categories by Revenue
- Customer Segments by RFM
- Top States by Revenue

---

## 2️⃣ Customer Intelligence & Insights

This page focuses on customer behavior and segmentation.

### Analysis Includes

- Top 10 Customers by Revenue
- Revenue by Customer Segment
- Average Order Value by Customer Segment
- New vs Returning Customers
- New Customer Acquisition Trend
- Customer Recency
- Purchase Frequency
- RFM Score Distribution

### Customer Segmentation

Customers were segmented using **RFM analysis**:

- Recency
- Frequency
- Monetary Value

Segments include:

- Champions
- Loyal Customers
- Potential Loyalists
- At Risk
- Lost Customers

---

## 3️⃣ Delivery Performance & Customer Experience

This page focuses on operational performance and customer experience.

### Key KPIs

- Average Delivery Days
- Late Delivery Rate

### Visualizations

- Delivery Time Trend
- On-Time vs Late Deliveries
- Top Product Categories by Revenue
- Delivery Delay Distribution
- Customer Review Score Distribution
- Average Delivery Time by State

---

# 🛠️ Technologies Used

### Business Intelligence

- Microsoft Power BI
- Power Query
- DAX
- Data Modeling

### Data Analysis

- Data Cleaning
- Data Transformation
- Feature Engineering
- RFM Customer Segmentation
- KPI Development

### Dataset

- Brazilian E-Commerce Public Dataset by Olist
