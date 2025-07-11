# 💼 Banco Wild West – Cloud-Native Data Platform Architecture

🎓 **UT Dallas | MS in Business Analytics – Final Semester Project (Spring 2025)**  
📚 Course: BUAN 6335 – Data Architecture & Management  
👥 Team: Ananya Avula, Sahil, Sri Krishna, Bhumika, Saurabh, Utkarsh, Ambuj  

---

## 🏦 Project Overview

Banco Wild West, a leading regional bank, faced critical challenges due to legacy infrastructure—outdated middleware, siloed databases, and a lack of real-time insights. To modernize operations and remain competitive in the digital banking era, the bank's new CIDO, Ms. Data First, initiated a strategic transformation to Azure Cloud.

Our team designed a **modular, scalable, and secure data platform** that supports both **OLTP (transactional)** and **OLAP (analytical)** workloads, meeting the needs of regulatory compliance, AI readiness, and real-time banking services.

---

## 🚀 Key Objectives

- Replace outdated N-tier architecture with a cloud-native solution
- Enable real-time fraud detection, predictive analytics, and personalized customer experiences
- Build a unified data lakehouse architecture (Bronze, Silver, Gold layers)
- Ensure end-to-end compliance, data lineage, and secure governance

---

## 🧱 Technology Stack

| Component               | Purpose                                             |
|------------------------|-----------------------------------------------------|
| **Azure Data Lake Gen2** | Scalable, cost-effective storage for all data types |
| **Delta Lake**         | ACID-compliant, versioned, and query-optimized layers |
| **Azure Data Factory** | Batch data ingestion (Oracle, SQL Server, Salesforce) |
| **Azure Event Hubs**   | Real-time event ingestion from ATMs, mobile apps     |
| **Azure Databricks**   | ETL, ML pipelines, and streaming data processing     |
| **Azure Synapse**      | BI dashboards, ad-hoc analytics, compliance reports  |
| **Azure ML & MLflow**  | Fraud detection, CLV prediction, document automation |
| **Microsoft Purview**  | Data cataloging, lineage, and auditability           |
| **Unity Catalog**      | Fine-grained access control and PII masking          |
| **Power BI**           | Business dashboards and reporting                    |
| **Azure Functions**    | Real-time API delivery and ML integration            |

---

## 🧠 ML Use Cases Implemented

- ⚠️ **Real-time Fraud Detection**
- 📈 **Customer Lifetime Value (CLV) Prediction**
- 🧾 **Document Verification via OCR & NLP**
- 🤖 **Agent Assist via Salesforce + Azure ML**
- 🛠️ **ATM Predictive Maintenance**
- 📝 **Smart Document Processing**

---

## 🔐 Governance & Compliance

- ✅ 90+ global certifications (PCI-DSS, ISO 27001, NIST CSF, BSA/AML, IRS)
- 🔐 Encryption: TLS 1.2 (in transit), AES-256 (at rest)
- 👥 Identity & Access: Azure AD (Entra ID), RBAC, Unity Catalog
- 🧾 Data Lineage: Microsoft Purview with full audit trails

---

## 💡 Architecture Highlights

- **Medallion Architecture (Bronze, Silver, Gold)** for traceable and version-controlled pipelines
- **Hybrid Ingestion** (Batch + Streaming) across enterprise and real-time sources
- **Tiered Storage Strategy** (Hot, Cool, Archive) for cost efficiency
- **Self-service BI & API-ready data delivery** for cross-functional access

---

## 🗂️ Project Files

| File | Description |
|------|-------------|
| `docs/ProjectReport-BancoWildWest.pdf` | 📄 Full 25-page technical report with architecture, decisions, and roadmap |
| `docs/FinalPresentation-Slides.pdf`    | 🎥 15-slide executive summary deck presented in class |
| `docs/ProjectPrompt-UTD.pdf`           | 📝 Original problem statement and guidelines from the instructor |

---

## 🛣️ Roadmap (Phases)

1. **Infrastructure & Governance Setup**
2. **Bronze Layer Ingestion (Batch & Streaming)**
3. **Silver Layer – Cleansing & Transformation**
4. **Gold Layer – BI/ML Integration**
5. **Optimization & Monitoring (MLOps, Delta Sharing)**

---

## 🎯 Outcomes

- ✅ Achieved scalable, secure cloud-native architecture
- 📊 Enabled real-time analytics and predictive models
- 💰 Reduced storage and compute costs with intelligent tiering
- 🔄 Built reusable, governed data pipelines for multiple use cases

