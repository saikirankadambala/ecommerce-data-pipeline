# 🛒 E-Commerce Data Pipeline

An end-to-end data engineering project that builds a scalable pipeline for an 
e-commerce platform using the Medallion Architecture on Databricks with PySpark.

---

## 📌 Project Overview

This project processes raw e-commerce data through three layers — Bronze, Silver, 
and Gold — to deliver clean, analytics-ready tables for business reporting and 
decision making.

---

## 🗂️ Project Structure
ecommerce-data-pipeline/
│
├── setup_catalog.ipynb                  # Catalog and database setup
│
├── 1_dim_bronze.ipynb                   # Dimension - Bronze layer
├── 2_dim_silver.ipynb                   # Dimension - Silver layer
├── 3_dim_gold.ipynb                     # Dimension - Gold layer
│
├── 1_fact_bronze.ipynb                  # Fact - Bronze layer
├── 2_fact_silver.ipynb                  # Fact - Silver layer
└── 3_fact_gold.ipynb                    # Fact - Gold layer
---

## 🏗️ Architecture

### Medallion Architecture (Bronze → Silver → Gold)

| Layer  | Description |
|--------|-------------|
| 🥉 Bronze | Raw data ingested as-is from the landing zone |
| 🥈 Silver | Cleaned, deduplicated, and standardized data |
| 🥇 Gold   | Final aggregated tables ready for analytics |

---

## 📦 Dataset

| Table | Description |
|-------|-------------|
| Customers | Customer master data |
| Products | Product catalog with pricing |
| Brands | Brand reference data |
| Category | Product category hierarchy |
| Order Items | Daily transactional order data |

---

## 🛠️ Technologies Used

- **Databricks** — Cloud data platform
- **PySpark** — Distributed data processing
- **Delta Lake** — ACID-compliant storage
- **Unity Catalog** — Data governance
- **Python** — Notebook development

---

## 👤 Author

**Saikiranakadambala**  
[GitHub Profile](https://github.com/saikirankadambala)
