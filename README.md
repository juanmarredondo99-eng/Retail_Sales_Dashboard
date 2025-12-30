# 🛒 Retail Sales Dashboard – Excel BI & Data Analytics

This project presents an interactive dashboard built in **Microsoft Excel** to analyze sales performance, revenue behavior, top-selling products, payment methods, and channel distribution for a retail business operating in Colombia.  
The dataset powering this dashboard was **synthetically generated using Python** to simulate +1,200 real-world sales transactions across multiple regions, cities, customer interactions, and product categories.

---

## 📌 Business Context

A retail company selling sportswear, clothing, footwear, and accessories manages operations using both online and physical store channels.  
Although orders occur constantly and revenues look promising, leadership lacks clarity on:

- Which months drive the highest sales
- Which products and categories truly generate profits
- Which cities and regions offer the highest opportunity
- Whether online or in-store channels perform better
- How payment preferences affect conversion and cash flow

A dashboard was needed to **turn scattered spreadsheet data into actionable business insights**.

---

## 🎯 Project Objective

Build a clear and accessible visualization that enables users to identify:

- 📊 Total sales volume and average ticket
- 📅 Seasonal demand and critical sales months
- 🧍‍♂️ Sales reps performance
- 🗺️ Customer geography – cities & regions
- 🛍️ Most profitable products and categories
- 🧾 Payment method distribution
- 📦 Channel behavior – Online vs Store

---

## 🧩 Dataset

The dataset was generated using Python (Pandas, datetime, random) and includes:

| Variable | Description |
|---------|-------------|
| Order_ID | Unique transaction ID |
| Order_Date | Date of purchase |
| Region / City | Geographic information |
| Sales_Channel | Online or physical store |
| Product_Category | Clothing / Footwear / Accessories |
| Product_Name | Specific item sold |
| Quantity | Units per order |
| Unit_Price | Price per item |
| Total_Sales | Quantity × price |
| Sales_Rep | Assigned salesperson |
| Payment_Method | Credit card, cash, debit, transfer |

📌 Files included in this repo:

```bash
├── dashboard_sales.xlsx            # Final interactive dashboard
├── sales_data.xlsx                 # Dataset generated in Python
├── data_script.ipynb               # Jupyter Notebook used to create dataset
├── assets/
│   └── dashboard_preview.jpg       # Dashboard screenshot for preview
├── docs/
│   └── Retail_Sales_Context_Problem.pdf   # Business context & problem statement
└── README.md

```
---

## 🧠 Key Insights (Summary)
🚀 February–July 2024 sales show fluctuation, with March ($30K) and July ($28K) performing best.

🛍 Top-selling products include: Pants ($21K), Hoodies ($20K), Backpacks ($18K).

💳 Most used payment method: Credit Card – $42K (27%).

🔄 Channel distribution: Online (50.87%) vs Store (49.13%) — both nearly equal.

🗺 Medellín, Bogotá and Cali outperform other cities.

---

## 🚀 How to Use the Dashboard
1️⃣ Download dashboard_sales.xlsx
2️⃣ Open it with Excel 2019 or later
3️⃣ Enable editing and content if prompted
4️⃣ Interact using slicers (Month, Region, City, Product, Channel)
5️⃣ Explore KPIs, top products, and trends for decision-making

---
## 🛠️ Tech Stack
| Tool             | Use                                 |
| ---------------- | ----------------------------------- |
| Python (Pandas)  | Synthetic dataset generation        |
| Jupyter Notebook | Data creation script                |
| Microsoft Excel  | Dashboard design & BI visualization |

---
## 👤 Author

Juan Manuel Arredondo Londoño
Industrial Engineering Student – Analytics & Development
📍 Medellín, Colombia
---