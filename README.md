
# 🚀 Designing a Scalable Cryptocurrency Data Pipeline Using Azure

> Automating cryptocurrency data extraction, transformation, and analytics for optimized portfolio management using Azure Cloud and Databricks.

---

## 📘 Project Overview

IntelloBank aims to modernize its cryptocurrency portfolio management by building a production-grade, **cloud-native data pipeline**. This pipeline ingests real-time data from the **CoinGecko API**, transforms it using **Databricks & Delta Lake**, and serves actionable insights through **Azure SQL** and **Power BI** dashboards.

This project leverages **Azure’s cloud ecosystem** to ensure:
- 🔄 End-to-end automation
- ⚡ Scalable data handling
- ✅ High data quality
- 📊 Real-time analytical capabilities

---

## 🎯 Objectives

- Extract real-time cryptocurrency data from **CoinGecko API**
- Clean, transform, and validate data using **Azure Databricks**
- Store raw, intermediate, and refined data using **Medallion Architecture**
- Automate workflows with **Azure Data Factory**
- Deliver insights through **Power BI dashboards**

---

## 🧱 Architecture Overview

The pipeline follows a **Medallion Architecture** (Bronze → Silver → Gold) within Azure:

- **Bronze Layer:**  
  Raw data ingested from CoinGecko API → stored in **Azure Data Lake Gen2**

- **Silver Layer:**  
  Cleaned, validated, and structured data → processed with **PySpark, Delta Live Tables**

- **Gold Layer:**  
  Business-ready datasets (volatility, trends, correlations) → stored in **Azure SQL Database**

- **Presentation:**  
  Connected to **Power BI** for dashboards and visual insights

---

## 🔧 Tech Stack

| Component              | Purpose                                             |
|------------------------|-----------------------------------------------------|
| 🐍 Python              | API integration, ETL scripting                     |
| ☁️ Azure Data Factory  | Workflow orchestration                             |
| 🧠 Azure Databricks    | Data processing with Delta Lake & Autoloader       |
| 📦 Azure Data Lake     | Raw & intermediate data storage                    |
| 🗃 Azure SQL Database  | Gold layer storage for business consumption        |
| 📊 Power BI            | Real-time dashboards & reporting                   |
| 🔐 Azure Key Vault     | Secure storage of credentials & API keys          |

---

## 📈 Key Features

- 🔁 **Automated ETL:** No manual intervention needed
- ⏱ **Real-Time Ingestion:** Scheduled extraction jobs from CoinGecko API
- 📊 **Business-Ready Analytics:** Correlation matrices, volatility indices, trend tracking
- 🔍 **Power BI Dashboards:** Real-time and historical insights
- 💾 **Historical Data Management:** Time travel enabled by Delta Lake
- ⚙ **Resilience & Monitoring:** Built-in retries, alerts, and execution logs

---

## 📚 Learning Outcomes

This project offered hands-on exposure to:

- Cloud-native data engineering on Azure
- API-driven data ingestion
- Modern data lake architectures (Bronze/Silver/Gold)
- Azure-native orchestration and security
- Scalable data transformation pipelines using PySpark

---

## 🔮 Future Enhancements

- Integrate **machine learning models** for price prediction
- Add **alternative data sources** (e.g., social sentiment)
- Real-time **event-driven alerting**
- Implement **streaming ingestion pipelines**

---

## 🏦 Business Impact

✅ Improved investment decision-making  
✅ Faster market response  
✅ Reliable, scalable, cost-efficient architecture  
✅ Reduced manual effort and operational risks  

---

## 📌 Authors & Credits

**Project Team:**  
Adeseye Ogunsina - Amdari Data Engineering Consultant  
Special thanks to [CoinGecko](https://coingecko.com) for open API access
