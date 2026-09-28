# Commercial Fleet Electrification: Financial Modeling & Investment Appraisal

An end-to-end corporate financial model and capital budgeting analysis built in Microsoft Excel. This project evaluates the commercial viability, debt service capacity, and investment returns for a fleet electrification initiative (Apex Delivery Ltd.).

---

## 📌 Project Overview
The model addresses two critical analytical objectives:
1. **Capital Budgeting & DCF Valuation:** Assessing a BDT 1,200,000 electric vehicle fleet investment using Discounted Cash Flow modeling against an 11% cost of capital hurdle rate.
2. **Financial Health Diagnostics:** Mapping transactional general ledger records into dynamic 3-statement financials (P&L, Balance Sheet, Cash Flow) and evaluating operational solvency, liquidity, and leverage ratios.

---

## 📊 Key Financial Metrics & Findings

| Metric | Output Value | Benchmark / Interpretation |
| :--- | :--- | :--- |
| **Net Present Value (NPV)** | **BDT 125,764** | Positive (Financially Viable) |
| **Internal Rate of Return (IRR)** | **15.92%** | Exceeds 11.0% Hurdle Rate |
| **Payback Period** | **2.67 Years** | Initial capital recovered in ~32 months |
| **Liquidity (Current Ratio)** | **2.70x – 3.49x** | 🟢 Robust short-term working capital |
| **Debt-to-Equity Ratio** | **0.51x – 0.71x** | 🟢 Conservative financial leverage |

---

## 🛠️ Model Architecture & Methodology

### 1. Loan Amortization Schedule
* Structured a **48-month loan schedule** for a **BDT 1,200,000** facility at **10.5% annual interest**.
* Programmed dynamic monthly debt service functions (`PMT`, `PPMT`, `IPMT`) to track monthly principal paydowns and declining interest liabilities.

### 2. Discounted Cash Flow (DCF) Model
* Modeled annual post-maintenance cash inflows over the 4-year lifecycle:
  * **Year 1:** BDT 400,000
  * **Year 2:** BDT 500,000
  * **Year 3:** BDT 450,000
  * **Year 4:** BDT 350,000
* Discounted at **11.0%** to derive net cumulative value, project IRR, and capital recovery timelines.

### 3. Integrated Financial Health Dashboard
* Formulated automated multi-period ratio diagnostics with conditional alert logic:
  * **Current Ratio:** Liquidity coverage consistently above 2.7x.
  * **Profitability:** Net Margin tracking and Return on Assets (ROA).
  * **Capital Structure:** Debt-to-Equity ratio maintaining safe leverage below 0.71x across all periods.

---

## 📂 Repository Contents
* `Financial Analysis Assignment2.xlsx`: Complete working model containing financial statements, amortization schedules, and DCF calculations.

---

## 👤 Author
* **Md. Farhan**
* [LinkedIn Profile](https://www.linkedin.com/in/md-farhan-pol/)
