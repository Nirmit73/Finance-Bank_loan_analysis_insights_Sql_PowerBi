# **Bank Loan Portfolio Analysis Project**

This project delivers an in-depth analysis of a bank’s loan portfolio, leveraging the power of SQL for data querying and transformation, coupled with visualizations in **Power BI**. The goal is to extract key insights into loan performance, borrower demographics, and repayment behaviors. This analysis explores various dimensions such as temporal trends (monthly, quarterly), geographic distribution (state-level insights), and categorical aspects (loan purpose, home ownership).

---

## **Project Objectives**

- **Evaluate Loan Portfolio Performance**: Conduct a thorough analysis of the loan portfolio to identify strengths, weaknesses, and areas for improvement.
- **Identify Loan Trends**: Uncover trends in loan applications, approvals, and repayment behaviors to enhance lending strategies.
- **Financial Health Insights**: Analyze key financial indicators, such as total funded amounts, average interest rates, and loan statuses, to assess portfolio stability and profitability.
- **Strategic Decision-Making**: Provide data-driven insights to support optimization of credit and loan offerings, ensuring alignment with market trends and customer needs.

---

## **Data Source**

This analysis is built upon a comprehensive dataset containing detailed loan information such as loan amounts, issue dates, interest rates, DTI ratios, and loan statuses, stored in a SQL database. You can find the data used for this project in the following [link](https://github.com/Nirmit73/Finance-Bank_loan_analysis_insights_Sql_PowerBi/blob/main/Data/financial_loan.csv).

---

## **Methodology**

The project follows a structured, multi-step process for thorough analysis and visualization:

### **1. Data Ingestion and Database Setup:**
- **Objective**: Establish a strong foundation for data storage and retrieval.
- **Approach**: Data is ingested and organized in a **SQL Server** database to ensure data integrity, consistency, and accessibility.

### **2. Data Analysis with SQL Queries:**
- **Objective**: Extract key insights and performance indicators (KPIs).
- **Approach**: Custom SQL queries were designed to capture important KPIs, such as loan application counts, funded amounts, and interest rate averages. This stage was crucial for identifying trends and performance metrics.

### **3. Data Processing in Excel:**
- **Objective**: Clean and validate data before deeper analysis.
- **Approach**: Initial data cleaning and processing were carried out in **Excel**, ensuring accuracy and consistency. Preliminary insights were generated to guide the next phase of analysis.

### **4. Loan Categorization:**
- **Objective**: Segment loans based on repayment performance.
- **Approach**: Loans were categorized into 'Good' or 'Bad' loans based on repayment status, giving insight into the risk profile of the portfolio.

### **5. Multi-Dimensional Analysis:**
- **Objective**: Analyze data across different dimensions such as time, geography, and loan purpose.
- **Approach**: The dataset was analyzed across factors like issue month, state, loan term, employment length, and home ownership to extract deeper insights into loan performance and borrower behavior.

### **6. Data Visualization:**
- **Objective**: Present data visually for easier consumption and insight discovery.
- **Approach**: **Power BI** was used to create rich, interactive dashboards that made the results accessible and actionable for stakeholders.

---

## **Key Insights and Findings**

- **Total Loan Applications**: Monthly and cumulative loan applications were analyzed, highlighting trends in application growth and seasonality.
- **Funded Amounts vs. Received Amounts**: A comparison of the total funded amounts versus the actual amounts received revealed potential liquidity issues.
- **Interest Rates and Debt-to-Income (DTI) Ratios**: Analysis of these metrics showed borrower financial health and risk, aiding in future lending decisions.
- **Loan Categorization**: Loans were segmented into high- and low-risk categories, providing a clear view of the portfolio’s risk exposure.
- **Detailed Breakdowns by Factors**: The dataset was analyzed across loan status, purpose, state, and term, uncovering underlying patterns and informing future lending strategies.

---

## **Tools and Technologies Used**

- **SQL Management Server**: Used for managing, querying, and analyzing data from the bank’s loan dataset.
- **Power BI**: Used for building interactive dashboards that visualize loan trends and portfolio performance.


---

## **Future Enhancements**

- **Predictive Modeling**: Incorporate machine learning models to predict loan defaults and borrower risk profiles.
- **Demographic Analysis**: Perform deeper demographic studies to refine customer segmentation and tailor loan offerings.
- **Loan Term Impact**: Further analysis on loan repayment rates based on different loan terms to optimize product offerings and reduce default risk.

---

## **Principal Visualizations**

### **Summary Panel**
![summary](https://github.com/Nirmit73/Finance-Bank_loan_analysis_insights_Sql_PowerBi/blob/main/Images/summary.png)

### **Overview Display**
![overview](https://github.com/Nirmit73/Finance-Bank_loan_analysis_insights_Sql_PowerBi/blob/main/Images/overview.png)

### **Detailed Insights Interface**
![details](https://github.com/Nirmit73/Finance-Bank_loan_analysis_insights_Sql_PowerBi/blob/main/Images/details.png)

---


## **Data Field Definitions**

| **Field**             | **Description**                                                                                             | **Purpose for Bank**                                                                                                                   |
|-----------------------|-------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| **Loan ID**           | A unique identifier assigned to each loan.                                                                  | Manage and track loans throughout their lifecycle, ensuring quick access to loan data.                                                   |
| **Address State**     | The state where the borrower resides.                                                                       | Analyze regional trends and adjust marketing strategies accordingly.                                                                    |
| **Employee Length**   | The duration of the borrower’s employment.                                                                  | Gauge borrower stability; long employment often correlates with lower default risk.                                                      |
| **Employee Title**    | Borrower’s job title or occupation.                                                                         | Understand borrower income sources and tailor loan offerings to specific job sectors.                                                    |
| **Grade**             | A risk classification for loans, based on creditworthiness.                                                 | Classify loans for risk management, with higher grades indicating lower risk.                                                            |
| **Sub Grade**         | A more granular breakdown of the loan grade.                                                                | Provide finer differentiation of loan risk, useful for pricing and risk assessment.                                                      |
| **Home Ownership**    | The borrower’s home ownership status.                                                                       | Assess the borrower's stability and collateral, as homeowners may present lower risk.                                                    |
| **Issue Date**        | Date when the loan was issued.                                                                              | Track loan aging, manage portfolio timing, and forecast revenue.                                                                         |
| **Loan Status**       | Current state of the loan (e.g., Current, Fully Paid, Default).                                              | Monitor loan health and identify potential risks in the portfolio.                                                                       |
| **Purpose**           | The purpose for which the loan was taken (e.g., debt consolidation, education).                             | Categorize loans to better understand borrower needs and manage risk.                                                                    |
| **Term**              | Loan duration in months.                                                                                    | Tailor loan offers based on borrower needs and manage repayment
