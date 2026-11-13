# Nexvia Technologies – Data Analytics Internship Projects

This repository contains two end-to-end data analytics projects completed as part of the **Nexvia Technologies Data Analytics Internship**.

The projects demonstrate practical experience in enterprise business intelligence, data warehousing, ETL development, financial analytics, credit-risk analysis, data visualization, and reporting.

---

## Projects Overview

### 1. DA-01 – Enterprise Business Intelligence Suite

**Objective:** Develop an enterprise business intelligence solution for a multi-region company to analyse business performance across multiple departments.

**Technologies:** SQL Server, T-SQL, Power BI, DAX, Power Query, PowerShell

**Key Features:**

- Designed a data warehouse using staging, dimension, and fact table architecture.
- Implemented ETL procedures to load and transform source data.
- Created data validation checks and ETL execution logging.
- Developed analytical dashboards for Executive, Sales, Finance, HR, and Supply Chain departments.
- Created DAX measures for business performance analysis, including sales, financial metrics, and time-based comparisons.
- Automated warehouse refresh execution using PowerShell and Windows Task Scheduler.
- Configured Power BI Row-Level Security (RLS) to support regional data access restrictions.

**Architecture:**

AdventureWorks2022 Source Database → Staging Layer → Dimension and Fact Tables → Power BI Semantic Model → Business Intelligence Dashboards

**Main Deliverables:**

- SQL database implementation scripts.
- ETL stored procedures and PowerShell automation.
- Power BI dashboard (`.pbix`).
- Data dictionary and architecture documentation.
- Validation results, screenshots, and project presentation.

**Project Documentation:** [DA-01 README](DA-01_Enterprise-Business-Intelligence/README.md)

---

### 2. DA-04 – Finance Analytics & Credit Risk

**Objective:** Develop a finance analytics and credit-risk analysis solution using financial ledger data and loan-level datasets.

**Technologies:** Python, Pandas, NumPy, MySQL, Excel, Power BI, Matplotlib, Seaborn, Scikit-learn

**Key Features:**

- Prepared and analysed financial ledger data.
- Generated monthly Profit and Loss reports.
- Performed Balance Sheet validation and financial variance analysis.
- Used Python and Pandas for loan data cleaning and preparation.
- Conducted credit-risk analysis using Weight of Evidence (WoE) and Information Value (IV).
- Developed a credit-risk scorecard and analytical outputs.
- Evaluated model performance using metrics such as AUC, Gini, and KS.
- Created financial and credit-risk dashboards in Power BI.

**Architecture:**

Financial and Loan Datasets → Data Preparation (Python / SQL) → Financial Reporting and Credit-Risk Analysis → Analytical Outputs → Power BI Dashboards

**Main Deliverables:**

- Python scripts for data preparation and credit-risk analysis.
- MySQL database scripts and financial queries.
- Excel financial analysis workbook.
- Power BI dashboard (`.pbix`).
- Project report, screenshots, and demonstration video.

**Project Documentation:** [DA-04 README](DA-04_Finance-Analytics-Credit-Risk/README.md)

**Dataset Sources:** [DA-04 SOURCES](DA-04_Finance-Analytics-Credit-Risk/SOURCES.md)

---

## Repository Structure

```text
Nexvia-Internship-Projects/
│
├── DA-01_Enterprise-Business-Intelligence/
│   ├── README.md
│   ├── LICENSE
│   ├── Documentation/
│   ├── Evidence/
│   ├── Logs/
│   ├── PowerBI/
│   ├── PowerShell/
│   ├── Presentation/
│   └── SQL/
│
├── DA-04_Finance-Analytics-Credit-Risk/
│   ├── README.md
│   ├── SOURCES.md
│   ├── Code/
│   ├── Dashboards/
│   ├── Datasets/
│   │   ├── Processed/
│   │   └── Synthetic_Finance/
│   ├── Demonstration Video/
│   ├── Reports/
│   └── Screenshots/
│
├── .gitignore
└── README.md
```

*Note: Refer to the individual project directories for their complete file structures.*

---

## Tools and Technologies

| Category | Tools |
|---|---|
| Programming | Python, SQL, T-SQL, PowerShell |
| Data Analysis | Pandas, NumPy |
| Databases | MySQL, Microsoft SQL Server |
| Visualization | Power BI, Excel, Matplotlib, Seaborn |
| Business Intelligence | DAX, Power Query |
| Risk Analysis | Scikit-learn, WoE, IV |
| Version Control | Git, GitHub |

---

## Installation and Execution

### DA-01 – Enterprise Business Intelligence

**Prerequisites:**

- Microsoft SQL Server.
- SQL Server Management Studio (SSMS).
- Power BI Desktop.
- PowerShell.

**Execution overview:**

1. Install and configure SQL Server.
2. Restore or make available the AdventureWorks2022 source database.
3. Review the SQL implementation scripts in the DA-01 project folder.
4. Execute the database and ETL implementation scripts in the documented order.
5. Configure the PowerShell ETL automation using the project instructions.
6. Open the Power BI `.pbix` file using Power BI Desktop.
7. Configure the required data source connection and refresh the dashboard.

### DA-04 – Finance Analytics & Credit Risk

**Prerequisites:**

- Python 3.
- MySQL Server and MySQL Workbench.
- Microsoft Excel.
- Power BI Desktop.

**Execution overview:**

1. Set up the Python environment.
2. Install the required Python libraries listed in the project documentation.
3. Obtain the required source datasets and place them in the documented data directories.
4. Configure the MySQL database and execute the SQL scripts.
5. Run the Python scripts for data preparation, WoE/IV analysis, and credit-risk scorecard generation.
6. Open the Excel workbook and Power BI dashboard to inspect the analytical outputs.

**Important:** Refer to the individual project README files and documentation for exact script execution order, configuration details, and dataset requirements.

---

## Validation and Project Evidence

Both projects include supporting evidence to demonstrate their implementation and outputs.

**DA-01:**

- Database and table validation.
- ETL execution logs.
- Power BI dashboard screenshots.
- Project architecture and data dictionary.
- Project presentation.

**DA-04:**

- Financial reporting outputs.
- Balance Sheet validation.
- Credit-risk analysis and model evaluation metrics.
- Power BI dashboard screenshots.
- Final project report and demonstration video.

---

## Dataset Information

The projects use publicly available sample and financial datasets for analysis and demonstration.

The processed credit-risk dataset `credit_risk_clean.csv` is retained locally but excluded from GitHub because it exceeds GitHub's individual file-size limit.

For DA-04, the Lending Club dataset source is available through:

https://www.kaggle.com/datasets/wordsforthewise/lending-club

Refer to the individual project documentation and `SOURCES.md` for dataset details and preparation instructions.

---

## Requirements

- Power BI Desktop is required to open the `.pbix` dashboard files.
- SQL Server and MySQL are required for their respective database components.
- Python is required to execute the DA-04 analytical scripts.
- Dataset availability and database configuration are required before executing the corresponding workflows.

---

## Author

**Miryala Shashi Varma**

GitHub: https://github.com/shashivarma-miryala

LinkedIn: https://www.linkedin.com/in/miryala-shashi-varma-9452003b6

---

*Completed as part of the Nexvia Technologies Data Analytics Internship.*
