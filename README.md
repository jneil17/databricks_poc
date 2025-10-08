# Databricks "Data Pioneer" Onboarding Workshop

Welcome to the Databricks Data Intelligence Platform! This repository is designed to guide new users through the core components of Databricks in a simple, hands-on manner.

The goal is **not** to be an exhaustive training, but to showcase the **simplicity and power** of Databricks for the most common data and AI tasks.

---

## 🚀 How to Get Started (2 Simple Steps)

1. **Run the Setup Notebook:** Open the `1. Getting Started.ipynb` notebook and "Run All" cells. This will install several pre-built `dbdemos`, populating your workspace with sample data, ETL pipelines, and dashboards. This entire process takes about 10-15 minutes.

2. **Follow the Guided Tour:** Proceed through the notebooks in order, from `2. Data Ingestion.ipynb` to `5. AgentBricks.ipynb`. Each notebook will act as a guided tour of the assets you just created, explaining key concepts and linking you to the relevant resources.

---

## 🏗️ What the Setup Notebook Installs

The `1. Getting Started.ipynb` notebook installs 7 essential demos to create a rich environment for you to explore:

* **`delta-lake`**: The foundational storage layer of the Lakehouse.
* **`auto-loader`** (and **`data-ingestion`**): For powerful, incremental data ingestion from cloud storage.
* **`pipeline-bike`**: A complete, declarative ETL pipeline using Delta Live Tables.
* **`sql-warehouse`**: Showcasing enterprise data warehousing capabilities.
* **`aibi-portfolio-assistant`**: An AI-powered BI dashboard for advanced analytics.
* **`uc-03-data-lineage`**: Demonstrating automatic data lineage and governance with Unity Catalog.
* **`delta-sharing-airlines`**: For secure, cross-organizational data sharing.

---

## 📚 Notebook Structure

* **`1. Getting Started.ipynb`**: **Installer.** Run this first and only once. It sets up your environment.
* **`2. Data Ingestion.ipynb`**: **Getting Data In.** Covers the easiest ways to ingest data, from simple UI-based connectors to powerful, automated tools like Auto Loader.
* **`3. Querying and ETL.ipynb`**: **Transforming Data.** Learn how to query your data and orchestrate transformations using both scheduled jobs and modern, declarative pipelines.
* **`4. Dashboarding and AI.ipynb`**: **Visualizing Data.** Discover how to build interactive dashboards using Databricks' built-in AI tools and how to connect to popular external BI tools like Tableau and Power BI.
* **`5. AgentBricks.ipynb`**: **Leveraging GenAI.** Get a high-level introduction to building GenAI applications and AI agents on Databricks.

---

## ✅ Prerequisites

* A Databricks account on AWS, Azure, or GCP.
* Permissions to create clusters, run notebooks, and install libraries.

---

## 📖 Additional Resources

* [Databricks Documentation](https://docs.databricks.com/)
* [Databricks Academy for free training](https://academy.databricks.com/)
* [Databricks Community Forums](https://community.databricks.com/)
* [Full DBDEMOS Library](https://github.com/databricks-demos/dbdemos)