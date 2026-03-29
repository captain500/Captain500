# Hi, I'm Sergio Amorrosta 👋
### Data Engineer

I am a **Data Engineer** with 6+ years of experience designing and implementing scalable data solutions. Currently at **BBVA Technology**, I coordinate data-driven initiatives for the Spanish region, orchestrating large-scale pipelines using **Python, Scala, Spark, and AWS** in collaboration with cross-functional teams.

---

### 🛠️ Professional Tech Stack

* **Languages & Core:** ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/-SQL-4479A1?logo=postgresql&logoColor=white) ![Scala](https://img.shields.io/badge/-Scala-DE3423?logo=scala&logoColor=white)
* **Data Engineering:** ![Spark](https://img.shields.io/badge/-Apache%20Spark-E25A1C?logo=apache-spark&logoColor=white) ![Databricks](https://img.shields.io/badge/-Databricks-FF3621?logo=databricks&logoColor=white) ![Polars](https://img.shields.io/badge/-Polars-CD792C) ![dbt](https://img.shields.io/badge/-dbt-FF694B?logo=dbt&logoColor=white) ![Prefect](https://img.shields.io/badge/-Prefect-070E10?logo=prefect&logoColor=white)
* **Cloud & Infrastructure:** ![AWS](https://img.shields.io/badge/-AWS-232F3E?logo=amazon-aws&logoColor=white) ![Azure](https://img.shields.io/badge/-Azure-0089D6?logo=microsoft-azure&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?logo=github-actions&logoColor=white)
* **Databases & BI:** ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![Clickhouse](https://img.shields.io/badge/-Clickhouse-FFCC01?logo=clickhouse&logoColor=black) ![Power BI](https://img.shields.io/badge/-Power%20BI-F2C811?logo=power-bi&logoColor=black)
* **Storage:** MongoDB, Neo4j.

---

### 🚀 Featured Project: Canada Rental Market Intelligence
*An end-to-end data platform to analyze the Canadian rental market.*

This project implements a **Medallion Architecture** (Bronze → Silver → Gold) with hash-based change detection and SCD2 history tracking.

* **Ingestion:** Custom scrapers built with **requests** + **BeautifulSoup4**, following the Template Method pattern for extensibility.
* **Storage:** **MinIO** (S3-compatible) for the immutable Bronze layer, **PostgreSQL** for Silver and Gold.
* **Processing:** **Polars** for high-performance cleaning, normalisation, deduplication, and range validation.
* **Transformation:** **dbt** implementing a **Kimball Star Schema** with **SCD2 snapshots** (row-hash change detection) for rental price history tracking.
* **Quality:** Pydantic models for schema validation, centralised column registry with numeric range rules, and **194 unit tests** with pytest.
* **Orchestration:** **Prefect** managing multi-partition flows with per-partition isolation and idempotent upserts.
* **DevOps:** **Poetry** + **Ruff** + **pre-commit** for code quality, **GitHub Actions** CI pipeline, and **Makefile** for local workflow automation.
* **Visualization:** Interactive **Power BI** dashboards.

---

### 📖 Content Creation & Community
I run [**elmundodelosdatos.com**](https://elmundodelosdatos.com), where I simplify complex data concepts for the Spanish-speaking community.

---

### 💼 Professional Journey
* **Data Engineer @ BBVA Technology** (*2024 - Present*)
  Coordinating regional data tasks and building Spark/Scala pipelines on **AWS** (S3, Athena, SageMaker).
* **Data Engineer @ AscendMakers & Dentsu** (*2022 - 2024*)
  Designed Azure-based ETLs (**Databricks/Delta Lake**) and AI-driven marketing tools using **Python, ClickHouse, and Prefect**.
* **Data Scientist @ TomTom** (*2021 - 2022*)
  Automated global map quality metrics using **Azure Data Factory**, **Databricks**, and **PySpark**.
* **ML Software Engineer @ DWX** (*2019 - 2021*)
  Built an NLP-powered SEO platform (Python/Java/Neo4j) that increased organic traffic for major clients by 10%.
* **MSc in Big Data Analytics** @ UC3M | **BSc in Computer Engineering** @ UPV/EHU.

---

### 📫 Let's Connect
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sergio-a-75603313a)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sgotxi500@gmail.com)
[![Website](https://img.shields.io/badge/Blog-121011?style=for-the-badge&logo=ghost&logoColor=white)](https://elmundodelosdatos.com)
