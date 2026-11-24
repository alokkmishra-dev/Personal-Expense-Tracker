# Personal Expense Tracker (ExpenseFlow)

**Course:** CSD0111 – Project Studio-I (July–December 2026 B)  
**Institution:** ITM University, Gwalior (M.P.)  
**Submitted By:** Alok Kumar Mishra (Roll No: \[BETN1CS26111] | B.Tech CSE Core – Section B)  
**Submitted To:** Dr. Neeraj Goyal  
**GitHub Repository:** https://github.com/alokkmishra-dev/Personal-Expense-Tracker

\---

## Project Description

**Personal Expense Tracker (ExpenseFlow)** is an integrated mini-project combining MS Office tools (Word, Excel, PowerPoint) and core web technologies (HTML5, CSS3, JavaScript). It helps students and individuals log daily income and expenses, track monthly budget limits, filter transaction history, and analyze monthly savings offline without backend dependencies.

## Key Features

1. **Strict Client-Side Form Validation:** Blocks empty descriptions, zero/negative amounts, unselected categories, and missing dates with inline error messages.
2. **Real-Time Financial Dashboard:** Automatically computes Net Balance (Savings), Total Income, Total Expenses, entry counts, and Savings Rate (%).
3. **Monthly Budget Tracker \& Alerts:** Customizable monthly budget limit with a dynamic progress bar (Green < 75%, Amber 75–100%, Red > 100%).
4. **Live Search \& Multi-Criteria Filtering:** Filters records instantly by keyword, transaction type (Income/Expense), and category.
5. **Browser `localStorage` Persistence:** Retains all transactions and budget limits across browser refreshes.
6. **1-Click CSV Export \& Sample Data Loader:** Exports saved transactions to `Personal\_Expense\_Report.csv` for spreadsheet use.
7. **MS Excel Analytics (`Project\_Data.xlsx`):** 25 structured records (`₹9,100` Income, `₹5,711` Expenses, `₹3,389` Net Savings, `37.2%` Savings Rate), 8 live formulas (`SUMIF`, `SUMIFS`, `AVERAGEIF`, `COUNTIF`, `COUNTIFS`, `IF`), conditional formatting, and 2 visual charts.

## Folder Structure

```text
CSD0111\_Mini\_Project/
├── 01\_Word\_Documentation/
│   ├── Project\_Report.docx
│   └── Project\_Report.pdf
├── 02\_Excel\_Workbook/
│   └── Project\_Data.xlsx
├── 03\_PowerPoint/
│   └── Project\_Presentation.pptx
├── 04\_Website/
│   ├── index.html
│   ├── style.css
│   ├── script.js
│   └── images/
│       └── logo.svg
├── 05\_Screenshots/
│   └── Project\_Screenshots/
│       ├── 01\_Dashboard\_Overview.png
│       ├── 02\_Form\_Validation\_Errors.png
│       ├── 03\_Filtered\_Transactions.png
│       ├── 04\_Mobile\_Responsive\_View.png
│       └── 05\_Excel\_Summary\_and\_Charts.png
└── README.md
```

## How to Run the Website

1. Clone or download this repository from `https://github.com/alokkmishra-dev/Personal-Expense-Tracker`.
2. Open the `04\_Website/` folder.
3. Double-click `index.html` to launch the app in any modern browser (Chrome, Brave, Edge, or Firefox).
4. Sample transactions auto-load on first visit; use the form to add/delete records, adjust the monthly budget, filter history, or click **Export CSV**.

