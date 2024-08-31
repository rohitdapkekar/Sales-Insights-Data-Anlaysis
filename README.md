 

### Sales Insights Data Analysis - AltiQ

This repository contains the Sales Insights Data Analysis project for AltiQ, an electronics hardware company. The goal of this project was to unlock hidden sales insights, automate data processes, and support the sales team in making data-driven decisions through an automated dashboard.

#### Project Overview

- **Objective**: To create an automated Power BI dashboard that provides real-time sales insights, enhancing decision-making capabilities for the Sales Director, Marketing Team, Customer Service Team, and other stakeholders.
- **Stakeholders**: Sales Director, Marketing Team, Customer Service Team, Data & Analytics Team, IT.
- **Success Metrics**:
  - Uncovered key sales order insights using the latest data.
  - Enabled the sales team to achieve 10% cost savings on total spend.
  - Saved 20% of the sales analyst's time by automating data gathering, allowing them to focus on value-added tasks.

#### Technical Details

- **Data Sources**: Extracted sales data from MySQL (OLTP) database named "sales," consisting of five tables: customers, date, market, products, and transactions.
- **ETL Process**:
  - **Extraction**: Pulled data from MySQL.
  - **Transformation**: Used Apache NiFi, Talend, and Python (Pandas) to clean and transform data.
  - **Loading**: Loaded data into data warehouses like Teradata and Snowflake for optimized data management.
- **Dashboard**: Built an interactive Power BI dashboard providing sales insights.

#### Tools & Technologies

- **Project Management**: AIMS Grid
- **Database & Warehousing**: MySQL, Teradata, Snowflake
- **ETL Tools**: Apache NiFi, Talend, Python (Pandas)
- **Visualization**: Power BI

#### Impact

The automated dashboard has significantly enhanced the sales team's ability to make informed decisions, resulting in measurable cost savings and improved operational efficiency.

Author: Rohit Rajesh Dapkekar 
rohitdapkekar04@gmail.com
