# Data Science & Relational Database Analytics Sandbox

This repository contains a comprehensive suite of data engineering, exploratory data analysis (EDA), and database management tasks. It demonstrates practical skills in schema design, automated data pipeline engineering, relational database querying, and data analysis using Python and Jupyter Notebooks.

---

## 📁 Repository Structure & Technical Breakdown

### 1. Relational Database & Business Intelligence (`PostgreSQL / SQLite`)
This core architecture demonstrates the ability to design, populate, and query scalable relational databases.
*   **`create_db.sql`** — Database Schema Architecture. Defines the complete relational model, tables, data types, constraints, and relational integrity (`PRIMARY KEY`, `FOREIGN KEY`).
*   **`seed.py`** — Automated ETL Pipeline. A Python automation script that programmatically connects to the database and utilizes `Faker` to generate and insert thousands of structured test records.
*   **`main.py`** — Database Orchestration Script. Handles active database sessions, connection pooling, and error-free execution of programmatic SQL operations.
*   **`select.sql`** — Business Intelligence Query Suite. Contains complex analytical SQL production queries executing multi-table **`JOIN`** operations, aggregations (**`SUM`**, **`AVG`**, **`COUNT`**), and metric filtering using **`GROUP BY`** and **`HAVING`**.

### 2. Exploratory Data Analysis & Manipulation (`Jupyter Notebooks`)
These notebooks contain end-to-end data pipelines focused on loading, cleaning, transforming, and visualizing datasets.
*   **Data Analysis with Pandas:** Deep utilization of the **Pandas** library for structured data processing, handling missing values, filtering dataframes, and performing custom transformations using analytical functions.
*   **Relational Operations & Joining:** Advanced data merging techniques, mapping relationships across multiple datasets, and structured schema alignment.
*   **Exploratory Data Analysis (EDA) & Visualization:** Statistical analysis of variables, identifying trends, patterns, and anomalies in data using plotting libraries (**Matplotlib / Seaborn**) to generate insightful charts.

---

## 🚀 Key Implemented Concepts

*   **Data Engineering:** Designing normalized tables, implementing indexing concepts, and handling relational database integrity.
*   **Data Manipulation & Transformation:** Feature engineering, text data cleaning, type casting, and filtering using high-performance Pandas workflows.
*   **Analytical Querying:** Authoring optimized SQL queries to answer critical data-driven business questions.
*   **Data Storytelling:** Translating raw database records and unstructured components into visual charts that highlight business trends.

---

## 🛠️ Tech Stack & Analytical Tools

- **Programming Language:** Python
- **Data Analysis & Manipulation:** Pandas, NumPy
- **Database Engineering:** SQL, PostgreSQL, SQLite
- **Data Visualization:** Matplotlib, Seaborn
- **Development Environment:** Jupyter Notebook, VS Code, Git, GitHub
- **Automation Libraries:** Faker
