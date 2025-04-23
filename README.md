
# Delinquency Analysis Dashboard

This project consists of a Power BI report designed to analyze and monitor delinquency among tenants in a large retail network. The analysis was based on structured data extracted and transformed via SQL, ensuring accurate information on due amounts, payments, renegotiations, and duplications. Key KPIs include overdue balances, collection efficiency, and aging buckets. The dashboard provides a clear and dynamic view of the financial status of each tenant, supporting strategic decision-making for credit control and recovery actions. This solution helped bring transparency to the delinquency process and aligned the financial team with up-to-date and reliable insights.

## Dashboard Link: https://app.powerbi.com/reportEmbed?reportId=a8e65e68-84b0-4f97-8619-23f7fa4f7bb9&autoAuth=true&ctid=7dc647e5-6288-496e-9c52-70467492ebf3

![Image](https://infoxnet.com.br/storage/posts/imagem.blog_-1.png)

## Problem to be Solved

The company was facing challenges in accurately identifying and tracking tenant delinquency across its network of shopping malls. The existing data was fragmented, inconsistent, and often outdated, leading to unreliable reports and poor visibility of overdue amounts. As a result, the financial team struggled to prioritize recovery efforts, evaluate the real impact of delinquency, and make informed decisions. There was also a lack of standardized KPIs and tools to support cross-department communication regarding outstanding debts and renegotiation statuses. A solution was needed to centralize, clean, and structure the data, as well as to provide a comprehensive and intuitive dashboard to monitor delinquency and improve credit control efficiency.

## Dataset Information

The dataset used in this project was primarily extracted from the company’s SQL Server database, containing detailed records of tenant contracts, due amounts, payments, and renegotiations. To enrich the analysis, additional data was automatically retrieved from SAP through scheduled Python scripts, which exported relevant Excel files containing updated financial transactions and account statuses. These Excel files were then processed and integrated into the main dataset to ensure completeness and accuracy. This combination of structured database queries and automated SAP data extraction allowed for a comprehensive view of the delinquency scenario across all shopping malls.

## Steps followed 

### [1]  Data Extraction and Integration

* Extracted structured data from the company's SQL Server database, including information on tenant contracts, payment history, due dates, and renegotiations.
* Developed a Python script to automatically retrieve Excel files from SAP, containing up-to-date financial transactions.
* Merged all sources into a unified dataset for analysis.

### [2]  Data Cleaning and Preparation
* Removed duplicates and corrected inconsistencies across datasets.
* Standardized column formats (dates, currency, IDs) to ensure compatibility.
* Validated data integrity by cross-checking SAP and SQL values to ensure accuracy.
### [3]  KPI Definition and Calculation
* Defined key performance indicators such as total overdue balance, percentage of delinquent tenants, aging buckets, and recovery rate.
* Created new calculated fields to reflect renegotiated amounts, payment status, and historical comparisons.
### [4]  Exploratory Data Analysis (EDA)
* Analyzed the distribution of overdue amounts across different malls, time periods, and tenant types.
* Identified patterns in payment delays and frequent renegotiation behaviors.
* Highlighted key risk areas through trend analysis and segment filtering.
### [5]  Dashboard Design in Power BI
* Designed a dynamic Power BI report with interactive filters for mall, period, contract status, and delinquency stage.
* Created clear visualizations to monitor KPIs, highlight critical values, and support decision-making.
* Ensured usability by collaborating with stakeholders for iterative feedback and improvements.
### [6]  Business Insights and Impact
* Delivered actionable insights to the finance and credit recovery teams, enabling targeted interventions.
* Improved visibility over the entire delinquency process, aligning internal teams and enhancing control.
* Supported strategic decisions that contributed to a more efficient and proactive credit recovery process.

## Insights

* Improved Delinquency Control: Through better data integration, cleaning, and visibility, the company reduced overall tenant delinquency from 6% to less than 1% throughout 2024, significantly improving financial health.

* Revenue Recovery Impact: The reduction in delinquency directly contributed to over R$ 20 million in recovered revenue in 2024, representing a major win for the credit recovery team and overall business performance.

* Enhanced Data Accuracy: By combining SQL data with automated SAP exports via Python, the analysis ensured more accurate and timely information, eliminating discrepancies and outdated figures previously used in manual reports.

* Strategic Credit Management: The dashboard allowed stakeholders to identify tenants with recurring delays, prioritize renegotiation efforts, and implement proactive actions, optimizing resource allocation.

* Custom KPI Monitoring: Tailored indicators such as overdue balance by aging bucket, collection rate, and renegotiated debt performance empowered the finance team to track progress and adjust strategies in real-time.

* Cross-Department Alignment: The Power BI report became a shared tool between finance, commercial, and operations teams, promoting alignment and faster decision-making based on a single source of truth.

## Conclusion

This project successfully addressed the lack of visibility and reliability in tenant delinquency data by creating a robust and insightful Power BI dashboard. Through the integration of SQL data and automated SAP exports via Python, the report provided a centralized and accurate view of overdue payments, renegotiations, and financial performance across the company’s shopping mall network.

The clear structure of KPIs and interactive visualizations empowered stakeholders to take informed, strategic actions that led to a drastic reduction in delinquency — from 6% to less than 1% — and generated over R$ 20 million in recovered revenue in 2024.

Beyond its financial impact, the solution fostered greater alignment between departments and established a scalable, data-driven foundation for ongoing credit management. This project highlights how thoughtful data preparation, automation, and visualization can drive measurable business outcomes.

As a data professional, I’m proud to contribute to solutions that not only solve technical challenges but also generate real business value. This project reflects my focus on combining analytics, automation, and storytelling to support smarter decisions.
