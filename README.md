# Banking-Customer-Analytics-Risk-Profiling-Dashboard

🎯 Short Description / Purpose

The Banking Portfolio Insights Dashboard is a BI solution designed to help senior management, credit teams, and product strategists monitor loan–deposit balance, customer demographics, and portfolio concentration. It provides a consolidated executive view of liquidity, credit risk, deposit mix, and cross-sell potential to support faster and more informed decision-making.

🛠 Tech Stack

📊 Power BI Desktop – Interactive dashboards and reports
📂 Power Query – ETL for cleaning & transforming customer, loan, and deposit datasets
🧮 DAX (Data Analysis Expressions) – KPIs such as LDR, Gender Mix %, Concentration %
📝 SQL (MySQL / PostgreSQL) – Data extraction, joins, aggregations for customer, loans, and deposits prior to BI modeling
📝 Data Modeling – Star-schema linking Loans, Deposits, Customers, Branches, and Products
📁 Formats – .pbix for development, .png exports for sharing with stakeholders

📑 Data Source

Source: Core banking dataset of ~3K customers

Size: ~4.38B loans & 3.77B deposits across multiple product categories

Key Fields: Customer demographics, loan type, deposit type, branch, income band, product usage

🌟 Features / Highlights
• Business Problem

Bank leadership needed a unified view to answer:

Are loans and deposits balanced enough to avoid liquidity risks?

Which branches and customer groups dominate exposure?

How engaged are customers with high-margin products like credit cards?

• Goals of the Dashboard

Track loan–deposit balance (LDR ratio, liquidity position)

Identify branch, product, and demographic concentrations

Highlight cross-sell opportunities (credit cards, bundled accounts)

Provide gender-balanced portfolio insights for inclusive banking

• Walkthrough of Key Visuals

📍 Executive Snapshot (Home Dashboard)

💰 Total Loans: 4.38B

🏦 Total Deposits: 3.77B

👥 Total Customers: 2,913

📊 Loan-to-Deposit Ratio: 1.16 (16% above benchmark → moderate liquidity risk)

📍 Loan Mix Dashboard

Bank Loans: 40.4%

Business Loans: 59.4%

Credit Card Exposure: 9.53M (only 0.22% of loans → massive growth potential)

Income Bands (Commercial + Male): 62% Medium, 21% High, 17% Low → mid-income dominance

📍 Deposit Mix Dashboard

Bank Deposits: 53.4%

Checking/Warehouse: 25.6%

Savings: 18.6%

Forex: 2.4%

Retail + Female Deposits: 20.12M (balanced spread, but concentrated in one branch + nationality)

📍 Gender Balance Dashboard

Customers: 51.1% Women

Loans: 50.0% Women

Deposits: 49.6% Women
👉 Gender equity achieved across products

📊 Business Impact & Insights

💡 Liquidity & Growth: LDR = 1.16 signals a need to grow stable deposits (savings, salary accounts).

💡 Cross-Sell Potential: Credit cards = just 0.22% of loans → untapped revenue driver.

💡 Portfolio Concentration: Branch and nationality-level dominance creates systemic risk → require diversification limits.

💡 Income Band Strategy: Middle-income segment is the backbone → target with bundled offers (salary + SME loans + credit cards).

💡 Data Hygiene: Engagement Account (4.49B) > Deposits (3.77B) → needs definition alignment before board reporting.
