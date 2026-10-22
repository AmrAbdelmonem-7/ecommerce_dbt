# 🛒 E-Commerce dbt Analytics Project

An end-to-end data transformation and modeling project built using **dbt Core** and **Snowflake**, designed for modern e-commerce analytics.

---

## 🚀 Tech Stack & Tools
* **Data Transformation:** dbt Core (v1.13)
* **Data Warehouse:** Snowflake
* **Language:** SQL, Jinja
* **Version Control:** Git & GitHub

---

## 📁 Project Structure

```text
ecommerce_dbt/
├── analyses/         # Ad-hoc SQL queries and analysis
├── macros/           # Reusable SQL snippets (Jinja macros)
├── models/           # Transformation models (Staging & Marts)
│   ├── staging/      # Initial cleaning and renaming
│   └── marts/        # Business-ready dimensional models
├── seeds/            # CSV files loaded directly into Snowflake
├── snapshots/        # Slowly Changing Dimensions (SCD Type 2)
├── tests/            # Custom data tests and assertions
└── dbt_project.yml   # Main project configuration file
