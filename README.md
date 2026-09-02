### Hi there 👋, I'm Santiago Venegas

**Sr. Data Engineer** | 

Senior Data Engineer with **6+ years** of experience across Python, SQL, Java, and Go — frameworks like PySpark, FastAPI/Flask, and Spring Boot/Gin, on cloud platforms including DynamoDB, S3, Step Functions, Lambda, EC2, Fargate, and Redshift. Specialized in fintech, food delivery, and mining (geophysical data extraction), at companies including iFood, Bancolombia, and Mastercard: daily multi-step Impala pipelines, ownership of a Postgres engagement process DB, migrating Impala logic to PostgreSQL, checkpointed extracts with mid-run resume, and production PySpark ETL in banking.
**AWS Solutions Architect – Associate** · **Databricks Data Engineer Associate**

## 🚀 About Me
- 🔭 I'm currently working at **iFood** as a Data Engineer
- 🌱 Currently building a 5-repo portfolio of production-pattern data pipelines (fintech, food delivery, mining) — real tests against emulated AWS infra, CI that lints/type-checks/security-scans, ADRs naming the trade-offs
- 👯 Looking to collaborate on interesting data engineering / AI projects
- 💬 Ask me about Python, PySpark, SQL, AWS, agentic/RAG pipelines
- 📫 How to reach me: **santiago.venegas@yandex.com**
- 📍 Located in: **Bogotá, Colombia**

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/-Python-007ACC?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-007ACC?style=flat-square&logo=postgresql&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007ACC?style=flat-square&logo=openjdk&logoColor=white)
![Go](https://img.shields.io/badge/-Go-007ACC?style=flat-square&logo=go&logoColor=white)
![Shell](https://img.shields.io/badge/-Shell-007ACC?style=flat-square&logo=gnubash&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)

![PySpark](https://img.shields.io/badge/-PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/-Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Gin](https://img.shields.io/badge/-Gin-00ADD8?style=flat-square&logo=go&logoColor=white)

![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![DynamoDB](https://img.shields.io/badge/-DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)
![S3](https://img.shields.io/badge/-S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![Lambda](https://img.shields.io/badge/-Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)
![Step Functions](https://img.shields.io/badge/-Step%20Functions-FF4F8B?style=flat-square&logo=amazonaws&logoColor=white)
![Redshift](https://img.shields.io/badge/-Redshift-8C4FFF?style=flat-square&logo=amazonredshift&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

## 📊 GitHub Stats

![GitHub Stats](https://helio-github-stats.vercel.app/api?username=Codemonster808&show_icons=true&theme=radical&hide_border=true&count_private=true)

![GitHub Streak](https://streak-stats.demolab.com/?user=Codemonster808&theme=radical&hide_border=true)

![Top Languages](https://helio-github-stats.vercel.app/api/top-langs/?username=Codemonster808&layout=compact&theme=radical&hide_border=true)

---

## Work experience

### EPAM — Client: Mastercard
**Data Engineer** | March 2024 – Present
- Built daily multi-step Impala SQL pipelines for card engagement: segmentation, consent/eligibility rules, journey state, and campaign-ready communication exports
- Designed Python orchestration with checkpoints, retries, and logging so long warehouse extracts/loads can resume without full restarts
- Migrated engagement business logic from Impala to PostgreSQL (PL/pgSQL), preserving history and exit rules
- Partnered with marketing/agency stakeholders on count reconciliations and edge cases (duplicates, consent semantics), documenting production fixes

### Finaipro — Client: Bancolombia
**Data Engineer** | May 2023 – February 2024
- Built ETL pipelines with Spark, Python, and Apache Sqoop to automate ingestion at scale on the Hadoop stack
- Managed large-scale file processing on Hadoop HDFS for reliable batch delivery
- Deployed and scheduled ETL packages for on-time daily execution

### iFood
**Data Analyst** | August 2022 – November 2022
- Designed and executed PySpark ETL processes, curating large-scale datasets for analysis
- Built Tableau dashboards that turned operational data into clear, actionable views
- Led A/B testing experiments that informed data-driven product and performance decisions

### Foodology
**Demand Data Analyst** | February 2022 – July 2022
- Improved predictive model accuracy in Jupyter using Pandas cleansing and key variable selection
- Applied statistical techniques and Power BI reporting to strengthen model monitoring and performance

### SunRun
**Back Office – Data Analyst** | April 2020 – November 2021
- Built dashboards that highlighted operational failure points for faster remediation
- Implemented Salesforce CRM data quality and cleansing procedures, streamlining data used for decisions

### Tapclicks
**Marketing Research Expert** | March 2019 – August 2019
- Generated qualified leads via web scraping and SQL querying
- Preprocessed data with SQL and automated email generation to reduce manual outreach effort

---

## 💼 Portfolio

Five LocalStack-based projects proving production-grade Python/SQL/PySpark data engineering plus two RAG/agentic builds — each with real tests against emulated AWS infra (not mocks), CI that lints/type-checks/security-scans on every push, and an ADR per repo naming the alternatives rejected, not just the choice made. Full index, build order, and rationale: **[portfolio-overview](https://github.com/Codemonster808/portfolio-overview)**.

| # | Repo | Sector | Core skill it proves |
|---|---|---|---|
| 1 | [fintech-txn-integrity-pipeline](https://github.com/Codemonster808/fintech-txn-integrity-pipeline) | Fintech | Exactly-once ingestion, schema evolution, Parquet compaction |
| 2 | [banking-engagement-warehouse](https://github.com/Codemonster808/banking-engagement-warehouse) | Fintech | Dimensional modeling, SCD Type 2, quality gates that block bad loads |
| 3 | [agentic-claims-copilot](https://github.com/Codemonster808/agentic-claims-copilot) | Fintech / AI | Agentic retrieval loop (plan → retrieve → observe → retry) with a hard token budget |
| 4 | [delivery-eta-mesh](https://github.com/Codemonster808/delivery-eta-mesh) | Food delivery | Event-time handling, Spark skew mitigation, Java/Fargate worker |
| 5 | [geo-doc-extraction-agent](https://github.com/Codemonster808/geo-doc-extraction-agent) | Mining / AI | Confidence-gated extraction, domain schema validation |

---

## Education

- **University Foundation CAFAM** — BHBA (Bachelor in Hospitality Business Administration) | 2013 – 2017
- **Acamica / Digital House** — Data Scientist | March 2021 – December 2021
- **Coursera** — NoSQL, Big Data, and Spark Foundations | November 2022  
  [Certificate](https://www.coursera.org/account/accomplishments/specialization/QJ92HH9XVDF6)
- **Udemy** — Complete SQL and Databases Bootcamp: Zero to Mastery | March 2023  
  [Certificate](https://www.udemy.com/certificate/UC-9bab812a-6a8f-48b5-935c-fca5a030a286/)
- **Undefined Academy** — Full-Stack JavaScript Bootcamp (Guillermo Rodas) | February 2023 – June 2023  
  [Program](https://undefined.academy/)

---

## Certifications

- **AWS Certified Solutions Architect – Associate** (2025)  
  [Credly](https://www.credly.com/badges/95f7582e-d7d2-4051-921c-388343044bf4/linked_in_profile)
- **Databricks Certified Data Engineer Associate** (2024)  
  [Credential](https://credentials.databricks.com/15c5b139-4693-4016-9bf9-087c0a6439a5)
- Databricks Academy Accreditation — Lakehouse Fundamentals (2024)
- Claude Certified Architect (2026)
  [Credential](https://www.credly.com/badges/ec650bb8-91ff-4904-875e-82be6e24dbbc/linked_in?t=tiaevp)

---

## Skills / tools

| Area | Tools |
|------|--------|
| **Languages** | Python, SQL, Java, Go |
| **SQL / databases** | Apache Impala, Hive-compatible SQL, PostgreSQL (PL/pgSQL), MySQL, DynamoDB, window functions, CTEs |
| **Python** | pandas, PySpark, NumPy, pyodbc, psycopg2, SQLAlchemy |
| **Frameworks** | FastAPI, Flask, Spring Boot, Gin |
| **Big data** | Hadoop, Spark, Apache Sqoop, Databricks |
| **Cloud (AWS)** | S3, DynamoDB, Step Functions, Lambda, EC2, Fargate, Redshift — AWS SAA certified |
| **Data engineering** | ETL/ELT, batch integration, checkpoint/resume loads, data quality, schema migration, scheduling |
| **BI / analytics** | Tableau, Power BI, Excel |
| **ML (background)** | scikit-learn, Jupyter |

## 📫 Connect with me

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/santiago-venegas1)
[![Email](https://img.shields.io/badge/-Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:santiago.venegas@yandex.com)
[![Portfolio](https://img.shields.io/badge/-Portfolio-000000?style=flat-square&logo=googlechrome&logoColor=white)](https://github.com/Codemonster808/portfolio-overview)

---
⭐️ From [Codemonster808](https://github.com/Codemonster808)
