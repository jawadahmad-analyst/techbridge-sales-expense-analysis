# TechBridge Distributors — Monthly Sales & Expense Analysis (Excel)

A small, beginner-friendly Excel accounting project built to practice core finance and spreadsheet skills: recording sales/purchases/expenses, calculating receivables & payables, and summarizing monthly profitability — all with native Excel formulas (no VBA, no macros, no Power Query).

> 📌 **Note:** TechBridge Distributors is a **fictional company**. All transaction data (invoices, customers, suppliers, amounts) is **AI-generated sample data** created for learning purposes — it does not represent any real business. The accounting logic, formulas, summary calculations, and charts were built manually by me.

---

## 📊 Project Overview

| | |
|---|---|
| **Company (fictional)** | TechBridge Distributors — consumer electronics distributor |
| **Period** | September 2026 |
| **Currency** | PKR |
| **Products** | Keyboard, Mouse, Headphones, Webcam, USB Drive, Power Bank |
| **Transactions** | 50 rows across Sales, Purchases, and Expenses |
| **Tools used** | Microsoft Excel (formulas, charts) |

---

## 🗂️ Workbook Structure

The workbook has exactly 4 sheets:

### 1. Sales (28 transactions)
`Date | Invoice No. | Customer | Product | Quantity | Unit Price | Total Sales | Payment Type | Amount Received | Outstanding`
- `Total Sales = Quantity × Unit Price`
- `Outstanding = Total Sales − Amount Received`
- Includes cash sales, credit sales, and partially paid invoices

### 2. Purchases (11 transactions)
`Date | Purchase No. | Supplier | Product | Quantity | Unit Cost | Total Purchase | Payment Type | Amount Paid | Outstanding`
- `Total Purchase = Quantity × Unit Cost`
- `Outstanding = Total Purchase − Amount Paid`
- Includes cash and credit purchases

### 3. Expenses (11 transactions)
`Date | Expense Category | Description | Payment Method | Amount`
- Categories: Rent, Electricity, Internet, Transportation, Office Supplies, Telephone, Delivery, Bank Charges

### 4. Summary
A one-page management dashboard built with `SUM`, `SUMIF`, `COUNTIF`, and `IF`:
- Total Sales, Total Purchases, Total Expenses
- Total Amount Received / Paid
- Accounts Receivable & Accounts Payable
- Estimated Gross Profit and Net Profit
- Cash vs. Credit invoice counts
- Two charts: **Sales by Product** and **Expenses by Category**

---

## 🧮 Key Results (September 2026)

| Metric | Amount (PKR) |
|---|---:|
| Total Sales | 493,350 |
| Total Purchases | 424,350 |
| Total Expenses | 64,800 |
| Accounts Receivable | 172,800 |
| Accounts Payable | 140,350 |
| Estimated Gross Profit | 69,000 |
| **Net Profit** | **4,200** |

*Gross Profit is estimated as Total Sales − Total Purchases, since this beginner-level model doesn't track opening/closing inventory (no COGS calculation).*

---

## 🧠 Skills Demonstrated

- Formula-driven spreadsheet design (no hardcoded results)
- `SUM`, `SUMIF`, `COUNTIF`, `IF` for summarization and logic
- Accounts receivable / accounts payable tracking
- Basic profitability analysis (gross profit, net profit)
- Data visualization with native Excel charts
- Structuring a multi-sheet workbook for a small business use case

---

## 📁 Repository Structure

```
techbridge-sales-expense-analysis/
├── README.md
├── TechBridge_Sales_Expense_Analysis.xlsx
└── screenshots/
    ├── summary-dashboard.png
    ├── sales-sheet.png
    ├── purchases-sheet.png
    └── expenses-sheet.png
```

---

## 🖼️ Screenshots

**Summary Dashboard** — KPIs, receivables/payables, profitability, and charts
![Summary Dashboard](screenshots/summary-dashboard.png)

**Sales Sheet**
![Sales Sheet](screenshots/sales-sheet.png)

**Purchases Sheet**
![Purchases Sheet](screenshots/purchases-sheet.png)

**Expenses Sheet**
![Expenses Sheet](screenshots/expenses-sheet.png)

---

## 👤 Author

**Jawad Ahmad**
BBA Finance | Aspiring Financial/Data Analyst
📧 jawadah312@gmail.com
