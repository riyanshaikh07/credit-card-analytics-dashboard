# 💳 Credit Card Analytics Dashboard

An interactive **Power BI** dashboard that analyzes credit card transactions and customer behavior — revenue trends, card categories, spending types, and customer demographics.

---

## 📌 Project Overview

This project has **two report pages**:

1. **Credit Card Transaction Report** – how much revenue is generated, when, through which card, and on what kind of spending.
2. **Credit Card Customer Report** – who the customers are (age, gender, income, job, education, state) and how much revenue each segment brings.

---

## 📊 Key Metrics (KPIs)

| Metric | Value |
|---|---|
| Total Revenue | 55.32M |
| Total Transaction Amount | 45M |
| Total Transaction Count | 656K |
| Interest Earned | 7.84M |
| Avg. Customer Satisfaction | 3.19 |
| Total Customer Income | 576M |

---

## 🔍 Key Insights

- **Blue card dominates** – ~46M of the 55.32M revenue comes from Blue cards; Silver (6M), Gold (2M) and Platinum (1M) are far behind.
- **Revenue is stable across quarters** – Q1 14.0M, Q2 13.8M, Q3 14.2M, Q4 13.3M. Q4 is the lowest.
- **Bills are the top expense type** (14M), followed by Entertainment (10M) and Fuel (9M). Travel is the lowest (6M).
- **Swipe is the most used method** (35M), then Chip (17M) and Online (3M).
- **Male customers contribute more revenue** (30.22M) than female customers (25.09M).
- **Businessmen are the top customer group** by job (17M); **Graduates** lead by education (22M).
- **40–50 age group** brings the highest revenue.
- **Top states by revenue:** TX, NY, CA, FL, NJ.

---

## 🛠️ Tools & Skills Used

- **SQL (PostgreSQL)** – created tables and imported raw CSV data (transactions + customer details)
- **Power BI Desktop** – connected to SQL database, dashboard design & interactivity
- **DAX** – calculated columns and measures (AgeGroup, IncomeGroup, Revenue, Week-over-Week Revenue)
- **Data Modeling** – relationships between transaction and customer tables
- **Data Cleaning / Transformation** – Power Query

---

## 🎛️ Interactive Features

- Slicers: **Quarter, Card Category, Gender, Income Status, Use Chip, Week Start Date**
- Cross-filtering between all visuals
- Combo chart (revenue + transaction count by quarter)
- Drill-down on the revenue trend (Year → Quarter → Month → Day)

---

## 🖼️ Screenshots

**Transaction Report**
![Transaction Report](images/transaction_report.jpg)

**Customer Report**
![Customer Report](images/customer_report.jpg)

---

## 📁 Repository Structure

```
credit-card-dashboard/
│── Credit_Card_Dashboard.pbix
│── README.md
│── images/
│    ├── transaction_report.jpg
│    └── customer_report.jpg
```

---

## 🗄️ Data Pipeline

1. Raw data prepared as CSV files (transaction details + customer details)
2. Tables created in **SQL (PostgreSQL)** and CSVs imported into the database
3. Power BI connected directly to the SQL database
4. DAX measures & calculated columns added (AgeGroup, IncomeGroup, Revenue, WoW Revenue)
5. Dashboard built with slicers, KPI cards, and visuals

---

## 🚀 How to Use

1. Download / clone this repository.
2. Import the CSVs into your SQL database using the provided SQL scripts.
3. Open the `.pbix` file in **Power BI Desktop** and update the SQL connection.
4. Use the slicers to explore the data.

---

## 👤 Author

**Riyan**
T.Y. B.Sc. Computer Science | Aspiring Data Analyst
GitHub: [riyanshaikh07](https://github.com/riyanshaikh07)

⭐ If you like this project, give it a star!
