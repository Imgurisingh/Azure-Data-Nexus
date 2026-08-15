# ☁️ Azure Data Fundamentals Project

*A hands-on cloud and data analytics project demonstrating Microsoft Azure fundamentals, relational and non-relational databases, data ingestion, Microsoft Fabric analytics, and SQL-based business intelligence solutions.* 

---

## 📖 Overview

This project was completed as part of the **Microsoft Azure Data Fundamentals** learning pathway and Data Technician programme. It demonstrates foundational knowledge of cloud computing concepts and practical experience working with key Azure data services, including Azure SQL Database, Azure Storage Account, Azure Cosmos DB, Microsoft Fabric Lakehouse, Eventstreams, and Power BI. 

The project combines theoretical understanding with hands-on labs to explore how organisations store, process, analyse, and visualise data using Microsoft Azure technologies.

---

## 🏗️ Solution Architecture

Data Sources
     ↓
Azure Storage / Azure SQL Database / Azure Cosmos DB
     ↓
Data Ingestion (Eventstreams & Pipelines)
     ↓
Microsoft Fabric Lakehouse
     ↓
SQL Analysis & Data Transformation
     ↓
Power BI Dashboards & Reports

---

## Core Technologies (Visual Overview)

<img width="100" height="100" alt="image" src="https://github.com/user-attachments/assets/f5f25f1f-468f-425b-83c8-fc7d395fc144" /> <img width="100" height="100" alt="image" src="https://github.com/user-attachments/assets/f84fdd2a-6202-4c2b-a873-47d155ff01e8" /> <img width="100" height="100" alt="image" src="https://github.com/user-attachments/assets/e72214fd-b82d-43c4-a048-d8f413768def" /> <img width="100" height="100" alt="image" src="https://github.com/user-attachments/assets/239a5787-620c-4ba9-a43e-975b93de227b" />

---

# 🚀 Skills Demonstrated

## ☁️ Cloud Computing Fundamentals

- Understanding cloud computing concepts and benefits
- Identifying business use cases for cloud adoption
- Comparing cloud and on-premises infrastructure
- Understanding IaaS, PaaS, and SaaS service models
- Exploring Public, Private, Hybrid, and Community Cloud deployments
- Understanding scalability, availability, reliability, and cost optimisation in cloud environments

---

## 🔷 Microsoft Azure Fundamentals

Developed practical understanding of:

- Azure Regions and Availability Zones
- Azure Resource Groups
- Azure Pricing and Cost Management
- Azure Governance and Security Concepts
- Cloud-based Storage and Database Services
- Data Analytics and Reporting Solutions 

---

# 🗄️ Relational Data with Azure SQL Database

Explored relational database concepts using **Azure SQL Database**.

### Key Concepts

- Tables, Rows, and Columns
- Primary Keys and Foreign Keys
- Data Relationships
- Structured Data Management
- Relational Data Modelling
- SQL Querying and Data Analysis 

### SQL Skills Demonstrated

#### Retrieving Data

```sql
SELECT *
FROM Sales;
```

#### Filtering Data

```sql
SELECT *
FROM Sales
WHERE SalesAmount > 1000;
```

#### Sorting Results

```sql
SELECT ProductName, SalesAmount
FROM Sales
ORDER BY SalesAmount DESC;
```

#### Aggregating Data

```sql
SELECT Category,
       SUM(SalesAmount) AS TotalSales
FROM Sales
GROUP BY Category;
```

#### Joining Multiple Tables

```sql
SELECT c.CustomerName,
       o.OrderID,
       o.OrderTotal
FROM Customers c
INNER JOIN Orders o
ON c.CustomerID = o.CustomerID;
```

### Business Insights Generated

Using SQL queries, sales and retail datasets were analysed to:

- Identify top-performing products
- Analyse customer purchasing behaviour
- Calculate sales by category
- Track revenue trends
- Support data-driven decision making

---

# 💾 Non-Relational Data with Azure Storage Account

Explored Azure Storage services for managing large volumes of structured, semi-structured, and unstructured data.

### Azure Storage Services

- Blob Storage
- File Storage
- Queue Storage
- Table Storage

### Skills Developed

- Managing cloud storage resources
- Uploading and organising datasets
- Understanding storage tiers
- Working with structured and unstructured files
- Supporting data ingestion and analytics workloads 

---

# 🌐 Non-Relational Data with Azure Cosmos DB

Worked with **Azure Cosmos DB** to understand NoSQL database technologies.

### Concepts Covered

- Document-based databases
- JSON data structures
- Flexible schema design
- Horizontal scaling
- High availability
- Global distribution

### Example JSON Document

```json
{
  "customerId": "1001",
  "customerName": "John Smith",
  "city": "London",
  "orders": 12
}
```

### Benefits of Cosmos DB

- Fast performance
- Global scalability
- Flexible data models
- High availability for modern applications

---

# 🔄 Data Ingestion & Eventstreams

Explored multiple methods of ingesting data into Azure and Microsoft Fabric environments.

### Data Ingestion Techniques

- File Uploads (CSV, JSON, Parquet)
- Azure Storage Integration
- Data Pipelines
- Batch Processing
- Streaming Data
- Eventstreams

### Eventstreams

Used **Microsoft Fabric Eventstreams** to process incoming data in real time.

Capabilities included:

- Continuous event collection
- Real-time monitoring
- Streaming analytics
- Live data processing workflows

This demonstrated how organisations can capture, process, and analyse operational data as it is generated.

---

# 🏗️ Microsoft Fabric Lakehouse

Explored analytical workloads using **Microsoft Fabric Lakehouse**.

### Areas Covered

- Data Lakes
- Data Warehousing
- Lakehouse Architecture
- Data Engineering
- Analytics Workloads
- Data Transformation

### Benefits of Lakehouse Architecture

- Unified platform for structured and unstructured data
- Centralised analytics environment
- Scalable data storage
- Simplified data processing and reporting

The Lakehouse environment enabled efficient querying and analysis across different data sources.

---

# ⚡ Real-Time Analytics

Worked with Microsoft Fabric Real-Time Analytics capabilities.

### Activities Included

- Streaming Data Analysis
- Event Monitoring
- Real-Time Reporting
- Operational Intelligence

This provided practical experience in analysing data as it arrives and supporting faster business decision-making.

---

# 📊 Data Visualisation with Power BI

Explored how Power BI integrates with Microsoft Fabric and Azure data services.

### Dashboard Use Cases

- Sales Performance Analysis
- KPI Monitoring
- Trend Analysis
- Customer Insights
- Business Reporting

Power BI was used to transform raw data into meaningful visual insights for stakeholders.

---

# 🧪 Hands-On Labs Completed

### Lab 1 – Explore Azure SQL Database

- Relational database concepts
- Data querying with SQL
- Structured data analysis

### Lab 2 – Explore Azure Storage

- Storage Accounts
- Blob Storage
- Cloud-based file storage

### Lab 3 – Explore Azure Cosmos DB

- NoSQL concepts
- JSON document storage
- Distributed databases

### Lab 4 – Explore Data Analytics in Microsoft Fabric

- Fabric Workspaces
- Lakehouse analytics
- Data exploration

### Lab 5 – Explore Real-Time Analytics in Microsoft Fabric

- Eventstreams
- Streaming data
- Real-time processing

### Lab 6 – Explore Fundamentals of Data Visualisation with Power BI

- Data visualisation
- Interactive reports
- Dashboard development 

---

# 📋 Scenario-Based Cloud Solution Design

As part of the project, a cloud-based solution was designed for a growing retail business.

### Data Protection & Compliance

Considered:

- GDPR Compliance
- Data Protection Act 2018
- Secure Storage of Customer Data
- Access Control and Data Privacy 

### Recommended Azure Services

| Business Requirement | Azure Service |
|---------------------|--------------|
| Transactional Data | Azure SQL Database |
| Customer Information | Azure SQL Database |
| File Storage | Azure Blob Storage |
| Real-Time Data | Eventstreams |
| Analytics | Microsoft Fabric Lakehouse |
| Reporting | Power BI |
| Data Integration | Azure Data Factory |

### Data Formats Explored

- CSV
- JSON
- Parquet

### Security Measures

- Encryption at Rest
- Encryption in Transit
- Role-Based Access Control (RBAC)
- Backup and Disaster Recovery Planning

---

# 🎯 Key Learning Outcomes

Through this project, I developed the ability to:

- Explain core cloud computing concepts and service models
- Understand Azure architecture and cloud services
- Work with relational and non-relational databases
- Query and analyse datasets using SQL
- Implement filtering, sorting, aggregation, and joins
- Understand modern data storage solutions
- Ingest and process data using Eventstreams and cloud storage services
- Build analytical workloads in Microsoft Fabric
- Generate insights from business datasets
- Create reports and dashboards using Power BI
- Apply data protection and compliance principles
- Design cloud-based data solutions using Azure technologies

---

# 🛠️ Technologies Used

- Microsoft Azure
- Azure SQL Database
- Azure Storage Account
- Azure Cosmos DB
- Microsoft Fabric
- Microsoft Fabric Lakehouse
- Microsoft Fabric Eventstreams
- Power BI
- SQL
- Azure Data Factory
- Azure Pricing Calculator

---

# ✅ Project Summary

This project demonstrates practical knowledge of cloud computing and Microsoft Azure data services through hands-on experience with relational databases, NoSQL databases, data ingestion, real-time analytics, Microsoft Fabric, and SQL-based data analysis. It showcases an understanding of how modern organisations use Azure technologies to store, process, analyse, and visualise data while supporting scalable, secure, and data-driven decision-making. 
---
