# Financial Loan Analysis – Power BI Dashboard

This repository contains an interactive **Power BI Dashboard** designed to analyze financial loan performance, customer behavior, and portfolio risk.  
The `.pbix` file delivers insights across loan applications, customer demographics, repayment status, and geographic risk distribution.

---

## 📊 Dashboard Overview

The report consists of **5 interactive pages**, each focusing on a different aspect of loan analytics:

### **1. Loan Overview**
- Total Loan Applications: **39K**
- Total Amount Received: **$473.1M**
- Total Funded Amount: **$435.8M**
- Average Interest Rate: **12.05%**
- Average DTI: **13.33%**
- Loan Status by Grade (A–G)
- Average Interest Rate by Grade
- Detailed loan-level table (ID, Grade, Status, DTI, Interest Rate, Amount)

---

### **2. Customer Insights**
- Total Customers: **39K**
- Average Annual Income: **$69.645K**
- Active Customers: **32K**
- Home Ownership Breakdown (Rent, Mortgage, Own)
- Income Distribution Histogram
- Employment Length vs Average Loan Amount
- Geographic Loan Amount by State (Map Visualization)

---

### **3. Risk Analysis**
- Total Charged-Off Loans: **5K**
- Average DTI (Risk Category): **13.3%**
- Average Interest Rate by Grade
- Charged-Off Rate: **13.8%**
- High-Risk Grade Count: **4K**
- Default Rate by Loan Grade
- Overall Loan Risk Composition (Current, Fully Paid, Charged-Off)
- Top 10 Riskiest States (by Charged-Off Rate)

---

### **4. Tool Tip Pages**
- Two customized tooltip pages that enhance user experience  
by showing context-sensitive insights when hovering on visuals.

---

## 🧠 Key Insights from the Dashboard

- **Grade B & C loans** dominate portfolio volume but show increased risk compared to A-grade loans.  
- States like **AK, NV, ND, and WY** show **higher charged-off rates**, marking them as risk-heavy regions.  
- Customers with **10+ years employment** tend to receive **higher loan amounts**.  
- Majority of customers have **annual income below $100K**, shaping the portfolio’s risk/ability to repay.  
- **Homeownership (Rent vs Mortgage)** influences the average loan value and default likelihood.

---

## 🛠️ Features & Techniques Used

- Interactive **slicers** (Grade, Loan Purpose, Employment Length)
- **Drill-through** and **tooltip navigation**
- **Custom DAX Measures** for KPI calculations:
  - Total Loan Applications  
  - Average Interest Rate  
  - Charged-Off Rate  
  - High-Risk Grade Count  
  - Average DTI  
- **Geographic mapping** for high-risk state detection  
- Visual storytelling with consistent theme & layout

---

## 📁 Repository Structure

PowerBI-Project/
├── Final PBI Project.pbix
├── README.md
└── images/
├── loan_overview.png

yaml
Copy code

*(Upload your screenshots into `/images` to activate the preview section below.)*

---

## 🖼️ Screenshots

### **Loan Overview**
![Loan Overview](images/loan_overview.png)


---

## ▶ How to Use This Dashboard

1. Install **Power BI Desktop**  
   https://powerbi.microsoft.com/desktop  
2. Download `Final PBI Project.pbix`  
3. Open the file in Power BI Desktop  
4. Explore filters, slicers, drill-through pages  
5. Hover over visuals to view advanced tooltip insights  

---

## 📌 Use Cases

- Financial risk assessment  
- Customer loan behavior modeling  
- Credit policy presentation  
- Portfolio performance tracking  
- Capstone/College project  
- Resume & portfolio showcase  

---

## 📜 License
This project is available for educational and portfolio use.

---

## ✨ Author
**Anaya**  
GitHub: https://github.com/Anaya3104-pk  
Power BI | SQL | Data Analytics  

---

## ⭐ If you found this useful, give the repository a star!
