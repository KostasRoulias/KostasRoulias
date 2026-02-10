# 👋 Hi, I'm Konstantinos Roulias

## 👨‍💻 Profile Snapshot

Data Engineer with a strong foundation in Computer Science and extensive experience in high-responsibility environments. Background includes 15+ years in leadership roles within the Hellenic Armed Forces, developing strong problem-solving, decision-making under pressure, and accountability.

Hands-on experience in designing and implementing **end-to-end data engineering systems**, including ETL and ELT pipelines, analytics-ready data models, and cloud-based data workflows on **Microsoft Azure**.

<img src="https://github-readme-stats-sigma-five.vercel.app/api?username=KostasRoulias&show_icons=true&hide_title=true" />

## 🛠 Core Skills

- **Python & SQL** – data transformations, query optimization, analytics-ready datasets  
- **Data Engineering** – ETL / ELT pipelines, data modeling, data warehousing  
- **Cloud & Infrastructure** – Microsoft Azure, Docker, CI/CD, Linux environments  
- **Workflow Orchestration** – Apache Airflow, scheduling, branching, dependency management  
- **Collaboration & Delivery** – Git-based workflows, code reviews, team collaboration 

---

## 🚀 Selected Projects

### 🔹 EU Workforce Demographics Data Platform *(Production-style)*

- Designed and implemented a **production-style data engineering platform** for EU27 demographic and economic indicators  
- Built **ETL pipelines orchestrated with Apache Airflow**, including:
  - Incremental ingestion with conditional execution
  - Separation of slow-changing and fast-changing data domains
- Integrated multiple data sources:
  - **World Bank API** (population & GNI per capita)
  - **Frankfurter API** (USD → EUR exchange rates)
- Loaded and modeled data in **PostgreSQL**, producing **analytics-ready datasets and views**
- Enabled BI consumption via **Metabase**
- Fully **Dockerized stack** using Docker Compose
- Implemented **GitLab CI/CD** for:
  - DAG validation
  - Controlled deployments on the main branch
- Deployed on a **Linux Virtual Machine (Hetzner)**
- Developed collaboratively using:
  - Feature branches
  - Merge Requests
  - Code reviews
  - CI/CD validation

**Tech stack:** Python, Apache Airflow, PostgreSQL, Docker, GitLab CI/CD, Metabase, Linux, APIs

---

### 🔹 Weather & Air Quality ETL Pipeline (Dockerized)

- Designed and implemented an **end-to-end ETL pipeline** using the **Open-Meteo API**
- Extracts **weather & air quality data** for multiple European cities
- Transformations with **Pandas** (cleaning, enrichment, weather code mapping)
- Loads data into **PostgreSQL** using **SQLAlchemy**
- Fully containerized with **Docker Compose**:
  - PostgreSQL
  - pgAdmin
  - Python ETL service
- **Automated scheduling with cron** (monthly execution)
- Clear separation between:
  - Prototyping (**Jupyter notebooks**)
  - Production **ETL script**
- Deployed on a **Linux VM**

**Tech stack:** Python, Pandas, PostgreSQL, Docker, Cron, SQLAlchemy, Linux

### 🔹 Azure Data Warehouse & ETL
- Built an end-to-end **Azure Data Warehouse**
- Designed a star schema (**6 Dimensions, 1 Fact**)
- Implemented **ADF pipelines** and **Mapping Data Flows**
- Applied **Data Warehouse modeling** and **SCD concepts**

### 🔹 Collaborative EDA Project
- Team-based EDA using Python
- Clean Git workflow (branches, pull requests, reviews)
- Focus on structure, collaboration, and reproducibility

### 🔹 CNN Web App with Explainable AI (Thesis)
- Flask web application for image classification
- CNN models with **Grad-CAM visual explanations**
- Model comparison and evaluation under data constraints

---

## 🎯 Career Focus

- Data Engineering roles
- Cloud and data-driven teams
- Clean, scalable, and maintainable systems

---

## 📫 Contact

- GitHub: https://github.com/KostasRoulias
- LinkedIn: https://www.linkedin.com/in/konstantinosroulias/
