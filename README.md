<div align="center">

<!-- Visitor Counter -->
![Profile Views](https://komarev.com/ghpvc/?username=donthula9908&color=0078d4&style=for-the-badge&label=PROFILE+VIEWS)

<!-- Wave -->
![Wave](https://raw.githubusercontent.com/ABSphreak/ABSphreak/master/gifs/Hi.gif)

<!-- Typing SVG -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=0078D4&center=true&vCenter=true&width=700&lines=Hi%2C+I'm+Naveen+Donthula+%F0%9F%91%8B;Senior+Data+Engineer;Azure+%7C+Databricks+%7C+Microsoft+Fabric;Building+Scalable+Data+Platforms)](https://git.io/typing-svg)

</div>

---

## 🙋 About Me

I'm a Senior Data Engineer with 6+ years of experience building end-to-end data platforms — from writing PySpark jobs and optimizing SQL pipelines to designing cloud infrastructure and owning production incidents.

I work across the full data engineering stack: ingestion → transformation → validation → reporting → monitoring — with deep hands-on experience in Azure, Databricks, Snowflake, and Microsoft Fabric.

- ⚡ Delivered ~9x pipeline throughput improvement by optimizing a PySpark/SQL query pattern
- 🏗️  Built and maintain 80+ ADF pipelines — ForEach chunking, triggers, copy activities, ARM templates
- 🔬 Developed row-level data validation frameworks using PySpark exceptAll diffs + schema comparison
- 📓 Migrated Databricks notebooks to Synapse Spark with config-driven dynamic endpoints
- 🔐 Authored SOX control narratives and built IcM automation for daily reconciliation
- 📊 67+ pull requests across financial reporting repos
- 🌍 H1B | C2C / W2 | Open to Relocation | Available Immediately

---

## 🔧 What I Actually Build

```python
# PySpark — data validation framework I built for Databricks → Synapse migration
df_diff = df_databricks.exceptAll(df_synapse)
schema_match = df_databricks.schema == df_synapse.schema
row_counts = {"databricks": df_databricks.count(), "synapse": df_synapse.count()}
```

```sql
-- SQL optimization that delivered ~9x throughput on financial data pipeline
SELECT * FROM PricedTokens
ORDER BY partitionKey   -- single change, ~9x improvement on cache load
```

```json
// ADF pipeline chunked ForEach pattern — parallel processing at scale
{
  "type": "ForEach",
  "batchCount": 10,
  "isSequential": false,
  "activities": [...]
}
```

---

## 🛠️ Tech Stack & Skills

### ☁️ Cloud & Data Platforms
![Microsoft Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Microsoft Fabric](https://img.shields.io/badge/Microsoft_Fabric-FFB900?style=for-the-badge&logo=microsoft&logoColor=black)
![Azure Databricks](https://img.shields.io/badge/Azure_Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![Azure Synapse](https://img.shields.io/badge/Azure_Synapse-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)

### ⚙️ Data Engineering & Pipelines
![Azure Data Factory](https://img.shields.io/badge/Azure_Data_Factory-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-003366?style=for-the-badge&logo=databricks&logoColor=white)
![Azure Logic Apps](https://img.shields.io/badge/Azure_Logic_Apps-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

### 💻 Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![KQL](https://img.shields.io/badge/KQL-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white)
![Scala](https://img.shields.io/badge/Scala-DC322F?style=for-the-badge&logo=scala&logoColor=white)

### 📊 Visualization & Reporting
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

### 🔐 Security, DevOps & CI/CD
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D4?style=for-the-badge&logo=azuredevops&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### 🗄️ Databases & Storage
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)

---

## 📋 Core Engineering Skills

| Skill | What I Build |
|---|---|
| PySpark / Spark SQL | ETL pipelines, Delta Lake read/write, schema validation, exceptAll row diffs, dynamic config-driven notebooks |
| Azure Data Factory | 80+ pipelines — ForEach chunking, copy activities, triggers, ARM templates, UAMI auth, Logic App alerts |
| Azure Databricks | Python notebooks, migration from Databricks → Synapse Spark, performance optimization, JDBC connections |
| SQL / T-SQL | Complex recon queries, stored procs, DACPAC, view files, query optimization (9x throughput) |
| Microsoft Fabric | Fabric Pipelines, OneLake integration, Dataflows Gen2, Lakehouse architecture |
| Snowflake | Data warehouse design, ELT pipelines, cloud data loading |
| Python | Data processing scripts, automation, validation frameworks, API integrations |
| Power BI | .pbix reports, DAX, Direct Lake, dataset connections to Synapse |
| Azure Synapse | Spark pools, DWU tuning, JDBC, VNet migration, release pipelines |
| KQL | Azure Monitor queries — StorageBlobLogs, AzureDiagnostics, security investigations |
| C# / .NET | Auth policies, API security fixes, ASP.NET Core middleware |
| CI/CD | OneBranch YAML, Azure DevOps release pipelines, EV2 RolloutSpec |

---

## 🚀 Featured Projects

| Project | Stack | Description |
|---------|-------|-------------|
| 🏗️ [Azure End-to-End Data Engineering](https://github.com/donthula9908/azure-data-engineering-projects) | ADF · ADLS Gen2 · Databricks · Synapse | Medallion architecture — Bronze/Silver/Gold, SCD Type 2, DQ framework, 50M+ records/day |
| 🔥 [Databricks Lakehouse Platform](https://github.com/donthula9908/databricks-lakehouse-projects) | PySpark · Delta Lake · DLT · Unity Catalog | Enterprise lakehouse — Kafka streaming, Delta Live Tables, ABAC governance |
| 🧵 [Microsoft Fabric Analytics](https://github.com/donthula9908/microsoft-fabric-analytics) | Fabric · Lakehouses · Dataflow Gen2 · T-SQL | Full Fabric workspace — OneLake, Fabric Warehouse, Power BI DirectLake |
| 🎬 [Netflix Data Engineering Pipeline](https://github.com/donthula9908/netflix-data-engineering-pipeline) | Azure · Databricks · Airflow · Delta Lake | Streaming analytics — viewer sessions, content KPIs, churn signals, < 10 min latency |
| 🌩️ [AWS Data Engineering Pipeline](https://github.com/donthula9908/aws-data-engineering) | Glue · Lambda · Kinesis · S3 · Redshift | Serverless event-driven pipeline with incremental Glue bookmarks and SSM locking |
| ❄️ [Snowflake & dbt Analytics](https://github.com/donthula9908/snowflake-dbt-project) | Snowflake · dbt · Streams & Tasks | ELT platform — SCD2 macro, dbt incremental models, Dynamic Tables CDC |
| 🌀 [Apache Airflow Data Pipelines](https://github.com/donthula9908/apache-airflow-data-pipelines) | Airflow · dbt · Databricks · Docker | Production DAGs — incremental ingestion, dbt orchestration, Databricks job triggers |
| 🤖 [Azure AI for Data Engineering](https://github.com/donthula9908/azure-ai-data-engineering) | Azure OpenAI · LangChain · RAG · Unity Catalog | RAG over data catalog, Text-to-SQL agent, AI-powered metadata enrichment |
| ⚙️ [Azure DevOps CI/CD](https://github.com/donthula9908/azure-devops-cicd-data-engineering) | ADF · Databricks Asset Bundles · dbt | Dev→staging→prod pipelines for ADF, DABs, and dbt slim CI |
| 🐍 [PySpark Interview Prep](https://github.com/donthula9908/pyspark-interview-prep) | PySpark · Delta Lake · Databricks | Real scenarios — exceptAll diff, 9x optimisation, window functions, skew handling |

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=donthula9908&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=donthula9908&layout=compact&theme=tokyonight&hide_border=true" height="165" />

</div>

<div align="center">

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=donthula9908&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

</div>

---

## 🏆 GitHub Trophies

<div align="center">

[![trophy](https://github-profile-trophy.vercel.app/?username=donthula9908&theme=darkhub&no-frame=true&margin-w=10&row=1)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## 🤝 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Naveen_Donthula-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/donthula9989/)
[![Email](https://img.shields.io/badge/Email-ndonthula3%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ndonthula3@gmail.com)

</div>

---

<div align="center">

Senior Data Engineer | Azure · Databricks · Microsoft Fabric · Snowflake · PySpark · SQL

Open to new opportunities — feel free to reach out!

</div>
