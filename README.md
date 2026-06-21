# 🚆 Railway Ticketing and Journey Analytics Data Warehouse

A full BI pipeline — from raw transactional data to interactive dashboards — built to analyze UK railway ticket sales and journey performance.

![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white)
![SSIS](https://img.shields.io/badge/SSIS-ETL-blue?style=flat)
![SSRS](https://img.shields.io/badge/SSRS-Reporting-blue?style=flat)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)

## 📌 Overview
This project builds an end-to-end data warehouse for a railway ticketing system, designed to support analytical reporting on passenger behaviour, ticket sales, and operational performance (delays, cancellations, refunds). It mirrors a typical enterprise BI workflow: raw data → ETL → warehouse → reporting layer → dashboard.

## 📊 Dataset
- **Source:** [Maven Analytics Data Playground](https://mavenanalytics.io/data-playground)
- **Size:** 65,535 ticket transactions, 17 attributes
- **Key fields:** Transaction ID, Purchase Type, Payment Method, Railcard, Ticket Class/Type, Price, Departure/Arrival Station, Journey Date & Times, Journey Status, Refund Request

## 🛠️ Tools & Technologies
- **SQL Server (SSMS)** — data warehouse design and storage
- **SSIS** — ETL pipeline to extract, clean, and load transactional data
- **SSRS** — paginated operational reports
- **Tableau** — interactive analytics dashboard
- **Azure** — cloud hosting component

## 🔍 Approach
1. Profiled and cleaned the raw transaction dataset
2. Designed a dimensional model (fact table for transactions, dimensions for stations, ticket types, time)
3. Built an SSIS package to automate the ETL load into SQL Server
4. Created SSRS reports for operational metrics (refunds, journey status breakdown)
5. Built a Tableau dashboard to visualize sales trends, ticket type popularity, and journey punctuality

## 📈 Key Insights
- Ticket sales patterns across payment methods, railcard usage, and ticket class
- Journey status breakdown (on time / delayed / cancelled) and its link to refund requests
- Revenue trends by station pair and ticket type

## 📁 Repository Contents
| File | Description |
|---|---|
| `railway data.xls` | Raw dataset (65,535 rows) |
| `datasetlink.txt` | Original dataset source |
| `_Harsanbruno_Maria_Joseph_Esuraj_20065575.pdf` | Full project report |

## 👤 Author
**Harsanbruno Maria Joseph Esuraj** — MSc Data Analytics, Dublin Business School
[LinkedIn](https://linkedin.com/in/harsanbruno) · [GitHub](https://github.com/harsanbruno2003-glitch)
