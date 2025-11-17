**📊 Financial Performance Dashboard – Power BI Project**

This project is an interactive Power BI dashboard designed to analyze a company’s financial performance across 12 months.
It showcases **Revenue**, **Expenses**, **Profit**, and **Target Achievement**, making it an ideal portfolio project for **Business Analyst**, **Data Analyst**, and **Power BI roles**.

**🚀 Project Overview:**

The purpose of this dashboard is to:

Visualize month-wise revenue performance

Compare Operating vs Marketing expenses

Analyze profit trends

Measure target achievement percentage

Gain insights into cost distribution

Present clean and professional KPIs

This project demonstrates:

Financial analysis

Data modeling

KPI creation

DAX calculations

Dashboard design principles

**📁 Project Structure:**
Financial-Performance-Dashboard/
│

├── Data/

│   └── financial_data.csv
│

├── PowerBI/
│   └── Financial_Performance_Dashboard.pbix

│
├── Documentation/

│   └── Dashboard_Screenshots/
│       ├── full_dashboard.png
│       ├── kpi_cards.png
│       ├── revenue_trend.png
│       ├── expense_comparison.png
│       └── pie_chart.png

│
└── README.md

**🧩 Dataset Details:**

The dataset contains 12 months of simplified financial data.

Column	Description
Month	January–December
Revenue	Total monthly revenue
Operating_Expense	Operational costs
Marketing_Expense	Marketing-related expenses
Target_Revenue	Monthly business target

**📐 DAX Measures Used:**

1️⃣ Net Profit
Net Profit =
SUM(financial_data[Revenue]) - (SUM(financial_data[Operating_Expense]) + SUM(financial_data[Marketing_Expense]))

2️⃣ Total Expense
Total Expense = SUM(financial_data[Operating_Expense]) + SUM(financial_data[Marketing_Expense])

3️⃣ Profit %
Profit % = DIVIDE([Net Profit], SUM(financial_data[Revenue]), 0)

4️⃣ Target Achievement
Target Achievement = DIVIDE(SUM(financial_data[Revenue]), SUM(financial_data[Target_Revenue]), 0)

****📊 Dashboard Features
⭐ KPIs (Top Section)

Total Revenue

Total Expense

Net Profit

Target Achievement %

**📈 Revenue vs Net Profit Trend (Line Chart):**

Shows growth and seasonal trends.

**📊 Operating vs Marketing Expense (Column Chart):**

Compares two expense categories month-wise.

🥧 **Expense Distribution (Pie Chart):**

Shows which expense category is heavier.

**📋 Summary Table**

Month-wise:

Revenue

Net Profit

Target Achievement

**🛠 Tools Used:**

Power BI Desktop

DAX

CSV Dataset (Custom)

Excel (for basic preprocessing)

**🎯 Purpose of This Project**

This project is built to strengthen portfolio skills in:

Business Analytics

Financial Dashboarding

Power BI Modelling

KPI Reporting

Data Visualization

It is suitable for roles like:

Business Analyst

Power BI Developer

Data Analyst

Reporting Analyst

**📸 Screenshots:**

![Full Dashboard](Documentation/Dashboard_Screenshots/full_dashboard.png)
![KPIs](Documentation/Dashboard_Screenshots/kpi_cards.png)
![Trend](Documentation/Dashboard_Screenshots/revenue_trend.png)
![Expenses](Documentation/Dashboard_Screensshots/expense_comparison.png)
![Distribution](Documentation/Dashboard_Screenshots/pie_chart.png)

**👤 Author**

Bainaboina Lokesh
Business Analyst | Data Analytics | Power BI
🔗 LinkedIn: https://linkedin.com/in/lokesh-bainaboina

🔗 GitHub: https://github.com/Lokesh63046

**📝 How to Run This Project**

Download repository

Open financial_data.csv in Power BI

Add DAX measures

Build visuals described above

Save .pbix file

🎉 Thank You for Viewing This Project!

If you liked this project, feel free to ⭐ star the repository!
