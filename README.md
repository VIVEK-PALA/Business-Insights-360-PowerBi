# Business-Insights-360-PowerBi
# 📊 Business Insights 360 – Power BI Project

## 🔍 Project Overview
AtliQ Hardware is expanding rapidly, and to stay ahead of its competitors, it is implementing data analytics for the first time using **Power BI**. The goal of this project is to create a 360° Business Intelligence dashboard covering **Sales**, **Finance**, **Marketing**, and **Supply Chain**, enabling stakeholders to make informed, data-driven decisions.

---

## 🧰 Tech Stack

- SQL (MySQL)
- Power BI Desktop
- Excel
- DAX Language
- DAX Studio (for performance tuning)
- Power BI Services

---

## 🚀 Key Power BI Skills Applied

- Asking the right business questions before starting
- Creating **calculated columns** and **measures using DAX**
- Efficient **data modeling** using **snowflake schema**
- Building **dynamic titles** and **KPI indicators**
- Using **bookmarks**, **buttons**, and **page navigation**
- Preventing division errors using `DIVIDE` function
- Creating custom **date tables with M language**
- Using **conditional formatting** with icons and colors
- Validating and cleaning data
- Publishing reports to Power BI Service
- Creating **Power BI Apps**, setting up **personal gateways**, and managing **access permissions**

---

## 📦 Business Terms Covered

- Gross Price
- Net Sales & Net Profit
- COGS (Cost of Goods Sold)
- Pre- & Post-Invoice Deductions
- Gross Margin
- YTD (Year to Date) / YTG (Year to Go)
- Channels: Retailers, Distributors, Direct
- Markets: 27 Global Markets (India, USA, Spain, etc.)

---

## 🗂️ Dataset & Tables

**Data Sources:** Imported directly from **MySQL** database  
**Data Model Type:** Snowflake schema (optimized for analytics)

### 🟦 Dimension Tables
- `dim_customer`: Customer details across 27 markets
- `dim_market`: Region, sub-zone, market info
- `dim_product`: Product hierarchy (Division → Category → Variant)

### 🟨 Fact Tables
- `fact_forecast_monthly`: Monthly customer forecasts
- `fact_sales_monthly`: Actual monthly sales
- `freight_cost`: Travel and shipping cost by region and year
- `gross_price`, `manufacturing_cost`: Cost metrics by product
- `pre_invoice_deductions`, `post_invoice_deductions`: Discount details

---

## 🧠 Data Modeling Insights

Effective data modeling is the **foundation** of reliable dashboards. We followed best practices for:
- Snowflake schema design
- Fact & dimension segregation
- Relationship setup and cardinality check
- Performance tuning using **DAX Studio**

---

## 🖥️ Dashboard Views

The interactive dashboard includes the following views, accessible via a homepage:

- 🧾 **Home View**

     ![Home view](https://github.com/VIVEK-PALA/Business-Insights-360-PowerBi/raw/b9db42d497c4665d064e4b6978aec28193f35c10/bi%20360%20new_page-0001.jpg)

- 🧾 **Finance View**
 ![Finance View](https://github.com/VIVEK-PALA/Business-Insights-360-PowerBi/blob/f138337654a5085a11688fe7af10166f73f468f6/bi%20360%20new_page-0002.jpg)

- 🎯 **Marketing View**
  ![Marketing View](https://github.com/VIVEK-PALA/Business-Insights-360-PowerBi/blob/f138337654a5085a11688fe7af10166f73f468f6/bi%20360%20new_page-0003.jpg)
- 🛠️ **Supply Chain View**
  
- 👑 **Executive Summary**  
- 📦 **Product View**  
- 🆘 **Support Page**

Each view includes dynamic visuals, KPIs, filters, and narrative insights.

---

## 🎯 Project Outcome

✅ With this dashboard, AtliQ’s management can:
- Track KPIs across departments
- Make data-backed strategic decisions
- Understand “why” metrics changed
- Reduce storage cost with better forecasting
- Improve cross-team collaboration using Power BI Services

---

## 📸 Dashboard Preview

![Dashboard Preview](screenshots/dashboard_preview.png)

> *(Add a screenshot or GIF of your dashboard here to make it visually engaging)*

---

## 📩 Contact

Made with 💡 by **Your Name**  
📧 your.email@example.com  
🔗 [LinkedIn](https://linkedin.com/in/your-link)

---

