# personal-finance-health-optimizer-and-analyzer-visualisation

# Personal Financial Health Optimizer and Analyzer

This Tableau project helps individuals analyze and optimize their financial health by visualizing and interpreting key personal finance metrics such as income, expenses, savings, debts, and investments.



## Project Description

*Personal Financial Health Optimizer and Analyzer* is an interactive Tableau dashboard and story that:
- Visualizes user-level financial data from 7 datasets
- Tracks income, expenses, savings, and debts over time
- Breaks down investment portfolios and net worth
- Provides visual insights to support better financial decisions

Built using *Tableau Public Desktop*, the workbook links multiple datasets through UserID to form a unified financial health analysis.



## Files Included

| File Name                | Description                                      |
|--------------------------|--------------------------------------------------|
| project.twbx           | Tableau Public Workbook (Packaged)               |
| users.xlsx             | User demographic and identification info         |
| income.xlsx            | Monthly income records                           |
| expenses.xlsx          | Monthly categorized expense records              |
| savings.xlsx           | Savings balance data over time                   |
| debts.xlsx             | Debt type, amount, and repayment data            |
| investments.xlsx       | Investment types and values                      |
| Financial Health.xlsx  | Aggregated metrics like net worth and ratios     |



## Data Model

All datasets are linked via a common key: UserID.


Users
 ├── Income
 ├── Expenses
 ├── Savings
 ├── Debts
 ├── Investments
 └── Financial Health




## Visualizations (Worksheets)

1. *Income vs Expenses Over Time*
2. *Savings Trend*
3. *Investment Portfolio Distribution*
4. *Debt-to-Income Ratio Analysis*
5. *Expense Category Breakdown*
6. *Net Worth Summary (KPI View)*



## Dashboard

- *Name:* Financial Health Dashboard  
- *Features:*
  - User-based filters
  - KPI indicators
  - Dynamic charts with tooltips
  - Consistent aesthetic theme (light gray background, color-coded elements)



## Story (8 Slides)

| Slide | Title                            | Description                                             |
|-------|----------------------------------|---------------------------------------------------------|
| 1     | Introduction                     | Overview of purpose and data                            |
| 2     | Income vs Expenses               | Trend analysis and cash flow                            |
| 3     | Savings Analysis                 | Visualization of savings growth                         |
| 4     | Investment Breakdown             | Types and distribution of investments                   |
| 5     | Debt-to-Income Insights          | Visual indicators of financial burden                   |
| 6     | Expense Category Distribution    | Identifying spending patterns                           |
| 7     | Net Worth Overview               | Financial summary per user                              |
| 8     | Conclusion                       | Final insights and recommendations                      |



## Design & Color Theme

| Element      | Color     | Purpose                      |
|--------------|-----------|------------------------------|
| Income       | #2C7BE5 | Positive cash flow           |
| Expenses     | #E74C3C | Spending                     |
| Savings      | #27AE60 | Healthy financial behavior   |
| Debts        | #C0392B | Liabilities                  |
| Investments  | #17A589 | Portfolio categories         |
| Net Worth    | #34495E | Overall financial position   |
| Background   | #F7F7F7 | Neutral backdrop             |



## Requirements

- Tableau Public Desktop (latest version)
- Excel-compatible file viewer (for .xlsx files)



## How to Use

1. Download or clone the repository.
2. Open project.twbx in Tableau Public Desktop.
3. Explore the dashboard or story.
4. Modify filters to interact with individual user data.



## Contact

For questions or contributions, feel free to open an issue or contact me at kv8849@gmail.com
