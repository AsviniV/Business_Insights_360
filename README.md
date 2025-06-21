# Business_Insights_360

## 📌 Project Overview
AtliQ Hardware has seen rapid growth in recent years and decided to implement data analytics using **Power BI** to gain a competitive edge and make data-driven decisions. This end-to-end project answers stakeholder questions across finance, sales, marketing, and supply chain domains.

🔗 **[Live Power BI Report](https://app.powerbi.com/view?r=eyJrIjoiMzFkMmJjODAtNDc2Ni00YmNkLWFkNDQtYzc0NjQ4MTM0ZmE4IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)**

---

## 🛠️ Tech Stack
- SQL  
- Power BI Desktop  
- Excel  
- DAX Language  
- DAX Studio (for optimization)  

---

## 📂 Project Charter File
Details the objectives, scope, and deliverables of the project.

---

## 📚 Power BI Techniques Learned
- Key questions to ask before starting the project
- Creating calculated columns and measures using DAX
- Effective **data modeling** (Snowflake Schema)
- Using bookmarks and buttons for visual navigation
- Preventing division-by-zero errors using `DIVIDE()`
- Creating a date table using M language
- Dynamic titles based on filters
- Using KPI indicators
- Conditional formatting in visuals (icons, background color)
- Data validation techniques
- Publishing reports to Power BI Service
- Setting up Personal Gateway for auto-refresh
- Power BI App creation
- Collaboration and permissions in Power BI Service

---

## 💼 Business Terminologies
- Gross Price  
- Pre-Invoice Deductions  
- Post-Invoice Deductions  
- Net Invoice Sales  
- Gross Margin  
- Net Sales  
- Net Profit  
- COGS (Cost of Goods Sold)  
- YTD (Year to Date)  
- YTG (Year to Go)  
- Channels: Retailer, Direct, Distributors  
- Customer Types: Direct, Retailer, Distributors, Consumer

---

## 🏢 Company Background
AtliQ Hardware is a fast-growing global computer and accessories company selling through:
- **Retailers**
- **Direct Channels**
- **Distributors**

Due to a significant loss from opening a store in the US based on intuition and limited Excel analysis, the company has decided to strengthen its analytics capabilities to enable better decision-making.

---

## 🎯 Questions to Ask Before Building the Dashboard
- What is the **objective** of this dashboard?
- How will **success** be measured?
- What is the **deadline**?
- Do stakeholders want a **preview** before release?
- What are their **hopes** and **fears**?
- Who will **use** the dashboard and for what?
- Any **design input** from stakeholders?
- What could **go wrong**?
- What **data** and **resources** are required?

---

## 🧩 Dataset Understanding

### gdb041

#### Dimension Tables
- `dim_customer`: 75 customers, 27 markets, 2 platforms (Brick & Mortar, E-Commerce)
- `dim_market`: 27 markets, 7 sub-zones, 4 regions (APAC, EU, LATAM, nan)
- `dim_product`: 2 divisions (P&A, N&S), 14 product categories, multiple variants

#### Fact Tables
- `fact_forecast_monthly`: Forecasted customer demand, one row per customer-product-month
- `fact_sales_monthly`: Actual sold quantities, similar structure to forecast table

### gdb056

- `freight_cost`: Travel and transport cost by market and fiscal year
- `gross_price`: Product-wise gross prices
- `manufacturing_cost`: Yearly manufacturing costs by product
- `pre_invoice_deductions`: % deduction before invoice by customer-year
- `post_invoice_deductions`: Post invoice & miscellaneous deductions

---

## 🔌 Importing Data into Power BI
Data is imported from a **MySQL** database into Power BI using appropriate credentials.

---

## 🧱 Data Modeling
We adopted a **Snowflake Schema** design for robust performance and scalability. Good data modeling is crucial, as all visuals depend on this foundation.


---

## 🎨 Dashboard Design

### Home View
Includes buttons to navigate between views:
- Info  
- Finance View  
- Sales View  
- Marketing View  
- Supply Chain View  
- Executive View  
- Products  

Mockups were used to guide the design. Measures and visuals were built based on those requirements.

---

✅ This project represents a comprehensive Power BI case study, encompassing real-world business logic, technical implementation, and stakeholder alignment.
