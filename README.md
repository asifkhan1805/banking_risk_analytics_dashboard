# 🏦 Banking Risk Analytics Dashboard

Welcome to the **Banking Risk Analytics Dashboard** project! 
This project demonstrates how modern risk analytics and interactive business intelligence dashboards can help financial institutions minimize lending risks, make informed decisions, and visualize key banking metrics.

---

## 📊 Project Overview

Banks and financial institutions face significant risks when granting loans. 
Leveraging data analytics and visualization can transform raw data into actionable insights—helping lenders reduce defaults and optimize their strategies. 

In this project:
- **EDA (Exploratory Data Analysis)** was performed using Python to uncover hidden patterns in client financial behavior.
- **Interactive dashboards** were built with Power BI, providing an at-a-glance view of crucial metrics and client segmentation.

---

## 🗂️ Data Model

![Data_Model](https://github.com/user-attachments/assets/9527ffa8-9cf4-4404-a776-cf0ceea89f71)


- Shows relationships between fact and dimension tables for integrity and flexibility.

**Key tables include:**  
- `Clients-Banking`(Facts_Table)
- `Banking Relationship`(Dimension_Table)
- `Investment Advisor`(Dimension_Table)
- `Gender`(Dimension_Table)
- `Period`(Dimension_Table)

---

## 🧹 Data Preparation & Feature Engineering

- **Calculated engagement timeframe and engagement days** per client.
- **Created income bands** to segment clients as Low, Mid, High.
- **Processing fees** estimated based on fee structure.
- **Binned and calculated KPIs** for streamlined analysis.

---

## ⚡ EDA Insights (Python)

- **Strong positive correlations** among `Bank Deposits`, `Checking Accounts`, `Savings`, and `Foreign Currency Accounts` — Customers with high balances in one account often hold more in others.
- **Savings and Deposits** are closely linked, reflecting similar behavior.
- **Income & Age** positively relate to higher account balances, savings, and loans.
- **Property ownership** less correlated—may depend on external factors.
- **Business lending** forms a distinct banking segment, only moderately connected to personal borrowing.

---

## 📈 Power BI Dashboards

### 1. Home Dashboard
![Home](https://github.com/user-attachments/assets/ea3708ef-ab23-48f1-b8ae-7e7301ead038)
Key KPIs at a glance:
- Total Clients
- Total Loan
- Total Deposit
- Total Fees
- Total Credit Card (CC) Amount
- Saving Account Amount  
With gender and time filters for deep dives.

### 2. Loan Analysis Dashboard
![Loan_Analysis](https://github.com/user-attachments/assets/cf19ec90-3935-4fda-a63c-aeb86ba529cb)
- Visualizes loan distribution, outstanding balances, and client loan segmentation.
- Drill-down by gender, period, and other factors.

### 3. Deposit Analysis Dashboard
![Deposit_Analysis](https://github.com/user-attachments/assets/8c0739f0-7f5c-4c35-8f96-d5ee6bf7ff86)
- Analyzes client deposit patterns across account types.
- Helps understand deposit behavior by demographics.

### 4. Summary Dashboard
![Summary](https://github.com/user-attachments/assets/1f3c143b-086a-4bbe-8d1d-a60f7ca5afdf)
- Aggregated insights from both loan and deposit analysis.
- Aids executive-level understanding and quick decision-making.

---

## 🌟 Key Metrics (KPIs)

| KPI                 | Description                                       |
|---------------------|---------------------------------------------------|
| Total Clients       | Number of unique customers                        |
| Total Loan          | Sum of all loan and credit balances               |
| Total Deposit       | Combined balances from all deposit accounts       |
| Total Fees          | Total fees charged (setup, maintenance, etc.)     |
| Total CC Amount     | Aggregate credit card usage                       |
| Saving Account Amt  | Total value in savings accounts                   |
| Engagement Duration | Days since client joined the bank                 |

---

## 🚀 Why This Project?

- **Modernizes risk assessment:** Empowers banks with data to make smarter, faster lending decisions.
- **Interactive and transparent:** Dashboards let users slice, filter, and drill into client profiles.
- **Ready for extension:** Add your own calculations, visuals, or integrate with other systems.

---

## 📁 Directory Structure

| File/Directory                        | Description                                                    |
|---------------------------------------|----------------------------------------------------------------|
| `README.md`                           | Project documentation and instructions (this file)             |
|                                       |                                                                |
| `Datasets/`                           | Contains all dataset CSV files                                 |
| ├── `banking-clients.csv`             | Main client data                                               |
| ├── `banking-relationships.csv`       | Relationships between clients and banks                        |
| ├── `gender.csv`                      | Gender reference data                                          |
| └── `investment-advisors.csv`         | Investment advisor reference data                              |
|                                       |                                                                |
| `Dashboard/`                          | Power BI dashboard files                                       |
| └── `Banking_Analysis_Dashboard.pbix` | Interactive Power BI dashboard                                 |
|                                       |                                                                |
| `python_eda_scripts/`                 | Python notebooks for EDA and analysis                          |
| ├── `Banking_Analysis_Part1.ipynb`    | Part 1 - EDA and initial insights                              |
| └── `Banking_Analysis_Part2.ipynb`    | Part 2 - Further EDA and correlation analysis                  |
|                                       |                                                                |
| `Assets/`                             | Project visuals and supporting images                          |
|     ├── `Data_Model.png`              | Screenshot of the Power BI data model                          |
|     ├── `Deposit_Analysis.png`        | Deposit Analysis dashboard screenshot                          |
|     ├── `Home.png`                    | Home dashboard screenshot                                      |
|     ├── `Loan_Analysis.png`           | Loan Analysis dashboard screenshot                             |
|     └── `Summary.png`                 | Summary dashboard screenshot                                   |

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 👨‍💻 Author

Asif Khan Mohammed.

linkedIN: [Link Text](https://www.linkedin.com/in/asif-khan-mohammed-aksi/).
email: [Link Text](asif.md1805@gmail.com).
github: [Link Text](https://github.com/asifkhan1805).

---
