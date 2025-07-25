SQL Data Warehouse Project
A modern end-to-end data warehouse solution using SQL Server, featuring ETL pipelines, data modeling, and analytics.
==================================================================================================================================

Project Overview
This project demonstrates how to build a modern data warehouse using the Medallion Architecture (Bronze, Silver, Gold) to support scalable and efficient analytics.
==================================================================================================================================
Key Components:
Data Architecture: Design of the Medallion architecture (Bronze, Silver, Gold layers).

ETL Pipelines: Extract, transform, and load data from source systems into SQL Server.

Data Modeling: Star schema design with fact and dimension tables optimized for analytics.

Analytics & Reporting: SQL-based dashboards and reports to derive actionable insights.

This is my first end-to-end project as an aspiring Data Analyst. It is a semi-guided project, allowing me to learn by following structured steps while also applying independent problem-solving and critical thinking throughout the ETL, modeling, and reporting phases.

===================================
Datasets: ERP and CRM CSV files.
===================================
SQL Server Express: Lightweight database server.

SQL Server Management Studio (SSMS): GUI for managing databases.

Git & GitHub: Version control and collaboration.

Draw.io: Visualizing architecture, data flow, and schema designs.

Notion: Task management and project tracking (template included).

Project Requirements
Phase 1: Data Engineering — Build the Data Warehouse
Objective
Consolidate sales data into a centralized SQL Server warehouse to enable deep analytical reporting.

Specifications

Data Sources: Import CSV data from two systems — ERP and CRM.

Data Cleaning: Address inconsistencies and ensure data quality.

Integration: Merge both sources into a unified, analytical data model.

Scope: Focus on the latest available dataset (no historization needed).

Documentation: Provide a clear data model to support analysts and stakeholders.

Phase 2: Data Analytics — Deliver Business Insights
Objective
Use SQL to extract insights that support strategic decision-making.

Focus Areas

Customer behavior patterns

Product performance metrics

Sales trends over time

Repository Structure
graphql
Copy
Edit
data-warehouse-project/
│
├── datasets/                   # Raw data files (ERP & CRM CSVs)
│
├── docs/                       # Documentation and architecture diagrams
│   ├── etl.drawio              # Visual ETL process design
│   ├── data_architecture.drawio
│   ├── data_catalog.md         # Field descriptions and metadata
│   ├── data_flow.drawio
│   ├── data_models.drawio      # Star schema models
│   ├── naming-conventions.md
│
├── scripts/                    # SQL scripts by data layer
│   ├── bronze/                 # Raw data ingestion scripts
│   ├── silver/                 # Cleaning and transformation scripts
│   ├── gold/                   # Analytical model creation scripts
│
├── tests/                      # Data quality tests and checks
│
├── README.md                   # Project overview and setup guide
├── LICENSE                     # License info
├── .gitignore                  # Git ignore rules
└── requirements.txt            # Project dependencies (if any)
Documentation
For detailed instructions and technical specifications, see:

docs/data_catalog.md

docs/naming-conventions.md

docs/data_models.drawio

docs/etl.drawio

Additional Resources
Notion Project Template: Plan and track all project tasks in Notion

Draw.io Diagrams: Ready-to-use architectural, ETL, and schema diagram
