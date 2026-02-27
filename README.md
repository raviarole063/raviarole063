<div align="center">
  <img src="https://i.gifer.com/Ry6p.gif" alt="MasterHead" />
</div>

<h1 align="center">Hi 👋, Welcome to My GitHub</h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&pause=1200&color=00F7FF&center=true&vCenter=true&width=700&lines=Data+Engineer+%7C+Azure+Cloud;Build+Pipelines+%7C+Break+Problems+%7C+Ship+Data;Databricks+%7C+ADF+%7C+Delta+Lake+%7C+PySpark" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=raviarole063&label=Profile%20views&color=0e75b6&style=flat" alt="profile views" />
</p>

---

### 🌱 About Me

- 🔧 **Data Engineer** focused on building scalable cloud data pipelines on **Microsoft Azure**
- 🏗️ Built an end-to-end **NYC Green Taxi Lakehouse** using Azure Databricks, ADF, Delta Lake & Unity Catalog
- ⚡ Passionate about **Medallion Architecture**, incremental ingestion, and data quality
- 📚 Currently deepening expertise in **PySpark**, **dbt**, and **streaming pipelines**
- 💡 I believe in writing pipelines that are **idempotent, testable, and production-grade**

---

### 🚀 Featured Project — NYC Green Taxi Data Engineering Pipeline

> End-to-end Azure Lakehouse pipeline processing NYC TLC taxi data through a Medallion Architecture

| Layer | Technology | Pattern |
|-------|-----------|---------|
| **Ingestion** | Azure Data Factory | HTTP → ADLS Gen2, ForEach loop |
| **Bronze** | Databricks + Auto Loader | Incremental, Checkpoint-based |
| **Silver** | PySpark + Delta Lake | MERGE Upsert, SCD Type-2, Cleansing |
| **Gold** | Delta Lake (Managed Table) | Aggregated KPIs, daily_trip_summary |
| **Reporting** | Power BI DirectQuery | Live dashboards from Gold layer |
| **Governance** | Unity Catalog | External Locations, RBAC, 2x Access Connectors |
| **Security** | Azure Key Vault | Service Principal, Secret Scope |
| **CI/CD** | GitHub + Databricks Repos | Version controlled notebooks & modules |

📁 **[View Project Repository →](https://github.com/raviarole063/nyc-taxi-project)**

---

### 🛠️ Data Engineering Stack

**Cloud & Orchestration**

![Azure](https://img.shields.io/badge/Microsoft_Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Azure Data Factory](https://img.shields.io/badge/Azure_Data_Factory-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![Azure Key Vault](https://img.shields.io/badge/Azure_Key_Vault-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)

**Data & Storage**

![Delta Lake](https://img.shields.io/badge/Delta_Lake-00ADD8?style=for-the-badge&logo=delta&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Apache Parquet](https://img.shields.io/badge/Apache_Parquet-50ABF1?style=for-the-badge&logo=apache&logoColor=white)
![Azure Data Lake](https://img.shields.io/badge/ADLS_Gen2-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)

**Languages & Tools**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

---

### 🔑 Key Engineering Concepts I Apply

```
✅ Medallion Architecture     (Landing → Bronze → Silver → Gold)
✅ Idempotent Pipelines        (Auto Loader + Checkpoint + MERGE Upsert)
✅ SCD Type-2                  (taxi_zone_lookup with effective/end dates)
✅ Incremental Loads           (3-month lag logic, get_filtered_dataframe())
✅ Data Quality Checks         (negative fare filter, stray year removal)
✅ Unity Catalog Governance    (External vs Managed tables, RBAC)
✅ Secret Management           (Key Vault + Databricks Secret Scope)
✅ Delta Time Travel           (DESCRIBE HISTORY, VERSION AS OF)
```

---

### 🌐 Connect with Me

<p align="left">
  <a href="https://www.linkedin.com/in/ravi-arole-645691233/" target="blank">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="linkedin" height="30" width="40" />
  </a>
</p>

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=raviarole063&show_icons=true&locale=en&layout=compact&theme=tokyonight" alt="top languages" height="200"/>
  <img src="https://github-readme-stats.vercel.app/api?username=raviarole063&show_icons=true&locale=en&theme=tokyonight" alt="GitHub stats" height="200"/>
</p>
