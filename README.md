# Logistics-Import-Export-Analytics-Dashboard
Database extraction, data cleaning, modeling, DAX measures, and KPI dashboards for a Colombian import-export logistics company.

# Logistics Import–Export Analytics Dashboard

## 📌 Project Overview
This project showcases an **end-to-end data analytics and business intelligence solution** built with **Power BI**, focused on a **large logistics and transportation company operating in Colombia**.

The objective was to transform raw operational data into **actionable insights** through robust data modeling, advanced DAX measures, and interactive dashboards that support **executive, financial, and operational decision-making**.

> ⚠️ **Data Disclaimer**  
> The dataset is based on real operational data; however, all sensitive and private information has been **anonymized and modified** to ensure confidentiality and data protection.

---

## 🎯 Target Roles
- Data Analyst  
- BI Analyst  
- Power BI Developer  
- Analytics Engineer  

---

## 🏢 Business Context
- **Industry**: Logistics & Transportation (Import & Export)
- **Company Size**: Large enterprise
- **Region**: Colombia (nationwide operations)
- **Time Span**: 7 years of historical data (2021–2025)
- **Operational Scale**:
  - +120,000 shipment records (manifiestos)
  - Import, export, national, and interurban transport
  - Multi-region and multi-route operations

---

## 🧰 Technology Stack
- **Power BI Desktop** – Data modeling, dashboards, KPIs
- **SQL** – Original data source
- **Power Query (M)** – Data extraction, cleaning, transformation
- **DAX** – Advanced measures and time intelligence
- **Excel** – Data validation and exploratory analysis
- **Python** – Data preprocessing and analysis
- **Angular** – Supporting analytical dashboards

---

## 🗄️ Data Architecture
- **Source**: SQL Database → CSV
- **Rows**: 120,000+
- **Columns**: 200+
- **Tables**: 14+
- **Model Type**: ⭐ Star Schema
<img width="1431" height="572" alt="image" src="https://github.com/user-attachments/assets/25b08434-7b0d-4021-ae71-4315c6fa36d2" />

### Fact Tables
- Shipments / Manifiestos  
- Financial Transactions  
- Operational Costs  

### Dimension Tables
- Clients  
- Vehicles  
- Origin–Destination  
- Regions  
- Calendar (Date Table)  

### Relationships
- One-to-many and many-to-one relationships
- Dedicated **Calendar table** for time intelligence

---

## 🔄 Data Cleaning & Transformation
All data preparation was performed **entirely in Power BI**, using **Power Query and DAX**, with more than **60 hours of data processing and modeling**.

Key steps included:
- Removal of duplicates
- Handling null and missing values
- Currency standardization
- Date normalization
- Creation of calculated columns
- Data consistency validation
- Star schema optimization for performance

---

## 📐 Data Modeling & DAX
The data model was designed for **performance, scalability, and analytical flexibility**.

### DAX Skill Levels Used
- **Basic**: `SUM`, `COUNT`, `AVERAGE`
- **Intermediate**: `CALCULATE`, `FILTER`, `DIVIDE`
- **Advanced**:
  - Time Intelligence (MoM, YoY, YTD)
  - Ranking (Top N clients, routes)
  - Percentage contribution analysis

---

## 📊 Key KPIs & Metrics

### Financial KPIs
- **Total Revenue (Valor Facturado)**: $358.32B
- **Total Costs (Valor Gastos)**: $277.59B
- **Profit Margin**: **22.92%**
- **Cost per Shipment**
- **Total Profit (Valor Utilidad)**
<img width="1281" height="726" alt="image" src="https://github.com/user-attachments/assets/9f24e1bb-18b7-4dff-a1c8-5737e6cd664a" />

### Operational KPIs
- **Total Shipments (Manifiestos)**: 110,000+
- **Average Revenue per Trip**
- **Average Transit Time**
- **On-Time Delivery %**
- **Own Fleet vs Third-Party Vehicles**
<img width="1288" height="729" alt="image" src="https://github.com/user-attachments/assets/91724c01-f2fb-42e1-b6af-7b76556ee8dc" />

### Commercial KPIs
- **Total Imports**
- **Total Exports**
- **Shipments by Country and Region**
- **Top Clients by Revenue**
- **Month-over-Month Growth**
<img width="1279" height="724" alt="image" src="https://github.com/user-attachments/assets/220f8502-6bda-49be-8cfb-2fb235f93489" />

---

## 📈 Dashboard Pages & Insights

### 1️⃣ Executive Overview
- Global KPIs: revenue, costs, margin, total shipments
- Quarterly and yearly trends (2021–2025)
- Import vs export performance comparison

### 2️⃣ Financial Performance
- Revenue, costs, and profit evolution
- Margin analysis over time
- High-profit period identification

### 3️⃣ Routes & Geographic Analysis
- Origin–destination performance
- Revenue and margin by city and region
- Interactive maps for logistics flows
- Identification of the most profitable routes

### 4️⃣ Client Analysis
- Top clients by revenue and shipment volume
- Revenue concentration analysis
- Client contribution percentages
<img width="1288" height="741" alt="image" src="https://github.com/user-attachments/assets/c385d5ef-783d-4085-8df1-79ce5d64933f" />

### 5️⃣ Operational Analysis
- Shipment volume by transport type
- Own fleet vs outsourced fleet usage
- Trip distribution and operational load

### 6️⃣ Time Intelligence & Comparisons
- Month-over-Month and Year-over-Year growth
- Revenue comparison vs targets
- Seasonality and trend detection

---

## ❓ Business Questions Answered
This dashboard helps answer key business questions such as:
- Which routes are the most profitable?
- Which clients generate the highest revenue?
- How do imports vs exports evolve over time?
- Which regions contribute the most to profitability?
- How does margin behave across transport types?
<img width="1281" height="726" alt="image" src="https://github.com/user-attachments/assets/cc20c703-395c-4c52-8771-fc1e93fa1c04" />

---

## 🚀 Business Impact
- Centralized 7 years of logistics data into a single BI solution
- Improved visibility into financial and operational performance
- Enabled data-driven decision-making for executives
- Reduced manual reporting and analysis time
- Scalable model ready for future growth

---


## 📬 Contact
If you are interested in this project or would like to discuss **Data Analytics, Power BI development, or BI opportunities**, feel free to connect.



