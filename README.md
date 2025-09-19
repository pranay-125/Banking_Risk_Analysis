**🏦 Banking Risk Analysis**


📌 Project Overview

This project explores banking customer data to identify patterns, correlations, and risk factors that influence financial behavior. Using Exploratory Data Analysis (EDA), statistical methods, and interactive dashboards, the study provides actionable insights into customer risk profiles, deposits, loans, and overall financial activity.

The project is intended for data analysts, risk managers, and financial institutions seeking to better understand customer behavior and assess potential risks.



**📂 Repository Structure**
├── Banking_Data.csv              # Dataset containing customer banking details

├── BankEDA (Version 1).ipynb     # Initial exploratory data analysis

├── BankEDA (Version 2).ipynb     # Refined EDA with deeper insights

├── Banking Dashboard.pbix        # Power BI dashboard for interactive risk analysis

└── README.md                     # Project documentation



**📊 Dataset Description**

The dataset contains 3,000 customer records with 25 features, including:

Demographics: Age, Gender, Nationality, Occupation

Banking Behavior: Deposits, Savings, Loans, Credit Cards, Business Lending

Financial Indicators: Estimated Income, Superannuation, Properties Owned

Risk Features: Risk Weighting, Loyalty Classification



**🔍 Exploratory Data Analysis (EDA)**

Key analyses performed in the notebooks:

Univariate Analysis → Distribution of income, age, deposits, loans

Bivariate Analysis → Relationship between income, deposits, loans, and savings

Correlation Heatmaps → Identifying strong and weak links across financial metrics

Risk Factor Evaluation → Insights on how different financial behaviors contribute to risk



**📑 Key Insights**

Deposits & Savings Behavior

Customers with high bank deposits also maintain significant balances in savings, checking, and foreign currency accounts.

Income, Age, and Financial Growth

Older and higher-income customers generally accumulate larger savings, loans, and credit card balances.

Property Ownership

Weak correlation with banking metrics → likely driven by external market factors.

Business vs. Personal Banking

Business lending is correlated with loans but behaves differently from deposits/savings, suggesting a distinct customer segment.



**📈 Power BI Dashboard**

The Banking Dashboard.pbix provides an interactive visualization of:

Customer demographics

Deposit vs. Loan distribution

Credit card and savings behavior

Risk segmentation

This enables stakeholders to explore trends and risk indicators dynamically.



**🛠️ Technologies Used**

Python → Data analysis & visualization (Pandas, Matplotlib, Seaborn)

Jupyter Notebook → EDA and documentation of insights

Power BI → Dashboard for interactive risk assessment

CSV → Structured dataset storage



**🚀 How to Run**

Clone the repository:

git clone https://github.com/your-username/banking-risk-analysis.git
cd banking-risk-analysis


Run Jupyter notebooks (EDA):

jupyter notebook "BankEDA (Version 2).ipynb"


Open Power BI Dashboard:

Install Power BI Desktop
.

Open Banking Dashboard.pbix.



**🔮 Future Enhancements**

Build a predictive model for customer risk scoring

Automate data ingestion & reporting pipelines

Integrate real-time dashboards with streaming financial data

Explore clustering & segmentation for customer profiling



✨ This repository showcases data-driven insights into customer banking behavior and risk analysis, bridging the gap between exploratory analytics and actionable financial intelligence.
