## dbt Fundamentals

### Who is an Analytical Engineer
```
Analyst know what to build
Data Engineers know how to build it

- ETL process has typically been handled by data engineers
- Traditional ETL requires additional tools, languages, skills to orchestrate
- Enter cloud-based data warehouses
- Data warehouses combine a database and super computer for transforming data
- Data can be transformed directly in the database - no nedd to extract and load repeatedly

- ELT shifts focus to:
  - Get the data in the warehouse
  - Transform the data from there

- Cloud-based data warehouse offer:
  - Scalable compute
  - Scalable storage
  - Reduction of tranfer time

Analytics Engineer:
- Owns the transformation of raw data up to the BI layer
- Charge the T in ELT

Data Engineer:
- Can focus on the extracting/loading of raw data and the larger data infrastructure

Data Analyst:
- Can work to deliver dashboards and reporting to stakeholders

Modern Data Team:
- Data Engineer
- Analytics Engineer
- Data Analyst
```

| Data Engineers | Analytics Engineers | Data Analysts
| --- | --- | --- |
| Build custom data ingestion integrations | Provide clean, transformed data ready for analysis | Deep insights work (ex. Why did churn spike last month? <br> What are the best acquisition channels?) |
| Manage overall pipeline orchestration | Apply software engineering practices to analytics code (ex. version control, testing, continuous integration) | Work with business users to understand data |
| Develop and deploy machine learning endpoints | Maintain data documentation & definitions | Build critical dashboards |
| Build and maintain the data platform | Train business users on how to use a data platform, data visualization tools | Forecasting | 
| Data warehouse performance optimization | | |

### dbt workflow
```
Raw data -> Develop -> Test & document -> Deploy -> Dataseets -> BI Tools/ML Models/Operational Analytics
