# 📘  Banking Dashboard (Power BI)

## 🎯 Objective

The main goal of this project is to build a dynamic, easy-to-use Power BI dashboard that gives banking professionals a bird’s-eye view of their operations, customer behavior, and loan performance.
The dashboard allows users to:
- Monitor overall banking performance.
- Track loan status and default rates.
- Analyze customer distribution by region, age, and income.
- Evaluate trends over time for business growth.

![Image](https://github.com/user-attachments/assets/5b100cc2-5196-478d-9594-252490cfb2be)
![Image](https://github.com/user-attachments/assets/5b100cc2-5196-478d-9594-252490cfb2be)


---
## 📌 Key Features
- Clear KPIs like Total Customers, Total Loans, Default Rate.
- Loan status breakdown (Approved, Pending, Rejected).
- Regional and demographic segmentation.
- Monthly trends in loan disbursement and repayment.
---
## 🧮 Metrics Calculated

- **Total Customers**
- **Active Loans**
- **Loan Default Rate**
- **Average Loan Amount**
- **Customer Segmentation by Age/Income/Region**
- **Loan Performance by Month**

---

## 📊 Visualizations Used

- Bar & Column Charts
- KPI Cards
- Pie Charts
- Slicers for Filtering
- Line Graphs for Time-Series Analysis
- Maps for Region-wise Breakdown (if applied)

---

## 🧰 Tools Used
- **Power BI** – for interactive data visualizations.
- **Python** - for EDA and to under the data in deeper
- **Excel** – as the primary data source (if applicable).
- **DAX** – for calculated metrics and measures.

---

## 🧪 DAX Highlights

Sample DAX measure:
```DAX
Default Rate = DIVIDE(SUM(Loans[Defaults]), SUM(Loans[TotalLoans]))
```
## ✅ Outcome
This dashboard helps banking stakeholders to:
- Understand customer profiles.
- Reduce risk with real-time monitoring.
- Improve decision-making based on data insights.
