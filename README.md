# 💳 Advanced expon Banking CRM with Anomaly & Fraud Detection

A Data Warehousing and Business Intelligence project focused on building a scalable Banking CRM analytics system integrated with fraud and anomaly detection mechanisms.

🎓 Data Warehousing & Business Intelligence Project  
FAST NUCES – 2025  

---

## 🚨 Repository Access Notice

> ⚠️ The complete technical implementation (ETL scripts, SQL schema, indexing strategies, and detailed reports) is maintained in a **private repository**.

If you are a recruiter, academic reviewer, or collaborator and would like access:

📧 [mahnoornaveed2405@gmail.com](mailto:mahnoornaveed2405@gmail.com)

Access is granted upon request.

---

# 🏦 Project Overview

This project simulates an enterprise-grade Banking CRM system using a Star Schema Data Warehouse architecture and Business Intelligence dashboards.

It integrates:

- Customer behavior analytics  
- Fraud detection logic  
- Anomaly detection rules  
- KPI-driven BI dashboards  

The system supports decision-making for:

- Customer relationship management teams  
- Risk and fraud management departments  

---

# 🗄️ Data Warehouse Architecture

## ⭐ Star Schema Design

### Fact Table
**fact_transactions**
- transactionotron transaction_id (PK)  
- date_key (FK)  
- customer_key (FK)  
- card_key (FK)  
- merchant_key (FK)  
- mcc_key (FK)  
- amount  
- fraud_label  
- anomaly_flag  

### Dimension Tables
- dim_customer  
- dim_card  
- dim_merchant  
- dim_mcc  
- dim_date  

📄 The complete Star Schema diagram is available inside this repository under the documentation section.

---

# 🔄 ETL & Data Engineering Workflow

### Extract
- Imported multi-million record transaction CSV dataset  
- Loaded reference datasets (customers, merchants, cards, MCC codes)  

### Transform
- Data cleansing and null handling  
- Surrogate key generation  
- Derived anomaly flags such as velocity checks and high-value spikes  
- Customer profile enrichment  

### Load
- Populated dimension tables  
- Inserted structured transactions into the fact table  
- Applied fraud and anomaly indicators  

**ETL Orchestration:** Apache Airflow  
**Data Processing:** Python & SQL  

---

# 📈 Business Intelligence & CRM Analytics

## CRM Insights
- Customer segmentation by spending patterns  
- Average spend and frequency analysis  
- High-value customer identification  
- Card utilization metrics  

## Fraud & Anomaly Analytics
- Fraud rate trends over time  
- High-risk merchants and MCC categories  
- Velocity anomaly detection  
- Geographical transaction anomalies  

---

# 📊 Power BI Dashboards

The repository includes dashboard screenshots demonstrating:

- Fraud percentage trends  
- Top risky merchants  
- Average spend vs fraud likelihood  
- Monthly anomaly alerts  
- Customer segmentation insights  

All dashboard previews are available within the repository folders.

---

# 🧠 Key Performance Indicators

- Fraud Percentage Trend  
- Merchant Risk Score  
- Customer Risk Profile  
- Transaction Velocity Alerts  
- CRM Behavioral Segmentation Metrics  

---

# ⚙️ Technology Stack

| Layer | Technology |
|-------|------------|
| Data Warehouse | Star Schema |
| Data Processing | Python, SQL |
| BI Layer | Power BI |
| Database | PostgresSQL |

---

# 🎯 Project Outcome

Delivered a scalable Banking CRM analytics system capable of:

- Handling large-scale transactional data  
- Supporting fraud detection rules  
- Enabling OLAP-style business analysis  
- Generating executive-level BI dashboards  

This project demonstrates applied knowledge in:

- Data Warehouse Design  
- ETL Pipeline Development  
- OLAP & Query Optimization  
- Indexing & Partitioning Strategies  
- BI Dashboard Engineering  

---

# 📩 Contact

**Mahnoor Naveed**

📧 Email: [mahnoornaveed2405@gmail.com](mailto:mahnoornaveed2405@gmail.com)  
🔗 LinkedIn: [View Profile](https://www.linkedin.com/in/your-linkedin-url)
