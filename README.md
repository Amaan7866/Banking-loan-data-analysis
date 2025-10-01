Interactive Banking Client Dashboard
This repository contains the files for an interactive banking dashboard built with Power BI. The dashboard provides a comprehensive overview of a bank's client portfolio, offering insights into client demographics, financial health, and relationships with the institution.


📝 Project Overview
The main objective of this project is to analyze client data to identify trends and patterns. The dashboard helps stakeholders, such as financial advisors and bank managers, make data-driven decisions by visualizing:

Client distribution across different demographics and regions.

The total value of deposits, loans, and other financial products.

Performance metrics for individual investment advisors.

Client segmentation based on loyalty status and income.

🛠️ Tools and Technologies
Data Visualization & Dashboarding: Microsoft Power BI

Data Exploration & Analysis: Python (in a Jupyter Notebook) with the following libraries:

Pandas

Matplotlib

Seaborn

🗂️ Data Sources
The dashboard is powered by several CSV files, which act as the database for this project:

Banking.xlsx - Clients - Banking.csv: The main fact table containing detailed information about each client, including their financial accounts, income, and assigned advisor.

Banking.xlsx - Gender.csv: A dimension table mapping gender IDs to gender names.

Banking.xlsx - Banking Relationship.csv: A dimension table describing the type of banking relationship (e.g., Retail, Private Bank).

Banking.xlsx - Investment Advisor.csv: A dimension table listing the names of the investment advisors.

✨ Key Features
The dashboard includes a variety of interactive features:

Key Performance Indicators (KPIs): At-a-glance cards for critical metrics like Total Clients, Total Bank Deposits, and Total Bank Loans.

Client Demographics: Visualizations breaking down the client base by age, gender, nationality, and occupation.

Financial Overview: Charts illustrating the distribution of client income, savings, loans, and account balances.

Interactive Filters: Slicers and filters that allow users to drill down into the data by investment advisor, loyalty classification, and fee structure.

🚀 How to Use
To explore the dashboard interactively, you will need to have Microsoft Power BI Desktop installed.

Clone the repository:

git clone <repository-url>

Open the dashboard file:
Navigate to the project directory and open Banking Dashboard.pbix with Power BI Desktop.

Data Source Configuration:
The dashboard may require you to configure the path to the CSV data sources to refresh the data successfully.

📂 Repository Structure
.
├── Banking Dashboard.pbix              # The main Power BI dashboard file
├── Banking.xlsx - Clients - Banking.csv # Main client dataset
├── Banking.xlsx - Gender.csv             # Gender dimension table
├── Banking.xlsx - Banking Relationship.csv # Banking relationship dimension table
├── Banking.xlsx - Investment Advisor.csv # Investment advisor dimension table
├── powerbi dashboard.ipynb               # Jupyter Notebook for data exploration
├── Screenshot 2025-10-01 192150.jpg      # A screenshot of the dashboard
└── README.md                             # This README file
