# 📊 Bank Loan Report | Power BI Dashboard

An interactive Power BI dashboard designed to analyze and monitor bank loan performance, risk metrics, and financial summaries. 

---

## 🚀 Dashboard Overview

This report provides executive leadership and financial analysts with deep visibility into loan portfolios, helping distinguish between healthy assets and potential risks. 

## 📊 Dashboard Preview

![Bank Loan Report Dashboard](https://github.com/Adityakaushik-mrt/Power-BI-Dashboard/blob/main/Bank%20Loan%20Analysis/Dashboard.PNG?raw=true)

### 🌟 Key Performance Indicators (KPIs)
* **Total Loan Applications:** 38.6K (4.31K MTD | 6.91% MoM)
* **Total Funded Amount:** ₹435.8M (₹53.98M MTD | 13.04% MoM)
* **Total Amount Received:** ₹473.1M (₹58.07M MTD | 15.84% MoM)
* **Average Interest Rate:** 12.05% (12.36% MTD | 3.47% MoM)
* **Average DTI (Debt-to-Income) Ratio:** 13.33% (13.67% MTD | 2.73% MoM)

---

## 📈 Key Dashboard Sections

### 1. Good Loan vs. Bad Loan Analysis
* **Good Loan Issued:** Accounts for **86.18%** of the portfolio.
  * *Good Loan Applications:* 33.2K
  * *Good Loan Funded Amount:* ₹370.2M
  * *Good Loan Amount Received:* ₹435.8M
* **Bad Loan Issued:** Accounts for **13.82%** of the portfolio (Charged Off / At-Risk).
  * *Bad Loan Applications:* 5.3K
  * *Bad Loan Funded Amount:* ₹65.5M
  * *Bad Loan Amount Received:* ₹37.3M

### 2. Loan Status Grid Matrix
A comprehensive grid breaking down performance metrics by loan status (**Charged Off**, **Current**, **Fully Paid**):
* Tracks individual application volumes, received vs. funded amounts, MTD metrics, average interest rates, and average DTI ratios per category.

### 3. Interactive Filters & Slicers
Users can seamlessly slice and dice data using the sidebar filters:
* **Good vs Bad Loan Filter:** (All / Good / Bad)
* **Grade Filter:** (A, B, C, D, E, F, G)
* **State Filter:** Geographic breakdown of portfolio health.
* **Navigation Panes:** Switch instantly between **Summary**, **Overview**, and **Grid** views.

---

## 🛠️ Tools & Technologies Used
* **Power BI Desktop:** Data modeling, DAX measures, and interactive UI design.
* **Data Source:** Financial loan dataset (CSV/SQL backend).
* **Version Control:** Git & GitHub.

---

## ⚙️ How to Use / Run Locally
1. Ensure you have **Power BI Desktop** installed.
2. Clone this repository or download the `.pbix` file.
3. Open the file in Power BI Desktop to interact with the slicers, filters, and underlying data model.
