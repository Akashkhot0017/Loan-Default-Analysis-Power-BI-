# Loan-Default-Analysis-Power-BI-
Power BI Loan Default Analysis – Interactive dashboards &amp; DAX measures to track loan distribution, borrower profiles, and default risk. Includes YOY/YTD trends, decomposition tree, and demographics insights.
# 📊 Loan Default Analysis (Power BI)

## 🚀 Project Overview  
An end-to-end Power BI project that analyses loan applicant data to monitor loan distribution, detect risk patterns, and track default trends.  
The report uses Power Query + DAX measures (organized in measure tables) to drive interactive dashboards for business users.

---

## 🔎 Problem Statement  
Financial institutions need clear, visual insights to:
- Identify borrower groups with elevated default risk.  
- Understand how loans are distributed by purpose, age, credit score and employment.  
- Track default and loan book trends over time to inform policy or monitoring.  

---

## 🗂 Dataset  
- Applicant demographics: age group, education, marital status, dependents.  
- Financial attributes: income, loan amount, credit score bins, mortgage flag.  
- Loan attributes: purpose, term, default flag, year.  
- Source files connected via Power BI (Excel / SQL / Dataflow as shown in the UI).  

---

## 🧰 Tools & Techniques  
- Power BI Desktop & Power BI Service (Dataflow, publishing options visible)  
- Power Query for cleaning & transformations  
- DAX measures organized into Measure Table 1 / 2 / 3  
- Visual types: Donut, Line, Area, Decomposition Tree, Clustered Column, KPI cards, Bar charts  

---

## 📐 Measures  

Measure Table 1  
- Average income by Employment type  
- Average Loan by Age Group  
- Default Rate by Employment type  
- Default Rate by Year  
- Loan Amount by Purpose  

Measure Table 2  
- Average Loan Amt (High Credit)  
- Loans by Education type  
- Median by Credit Score bins  
- Total Loan (Credit bins)  
- Total Loan (Middle Age Adults)  

Measure Table 3  
- YOY Default Loans change  
- YOY Loan Amount Change  
- YTD Loan Amount  

(Also present: a Loan_default table used in visuals/filters.)  

---

## 📑 Dashboard Pages & Key Visuals  

### 1) Loan Default & Overview  
- Loan Amount by Purpose (step/line visual)  
- Average Loan by Age Group (area/line)  
- Average Income by Employment Type (small multiples)  
- Default Rate (%) by Year (area/line)  
- Default Rate (%) by Employment Type (column/line)  

### 2) Applicant Demographics & Financial Profile  
- Median Loan Amount by Credit Score category (line)  
- Total Loan (Adults) by Credit Score Bins (area / stacked)  
- Donut chart: Loan share by Age Groups & Marital Status  
- Loans by Education type & Number of loans by Education (line / area)  
- Mortgage vs Non-mortgage loan bars  

### 3) Financial Risk Metrics  
- YOY Default Loans change (line)  
- YOY Loan Amount Change (line)  
- YTD Loan Amount (summary tile / KPI)  
- Decomposition Tree showing loan amount split by Income bracket, Employment type, Credit bins  

---

## 🧹 Data Preparation & Validation  
1. Dataflow / import into Power BI Desktop.  
2. Column definitions, data types & profiling (Data pane & Query Editor used).  
3. Create and group DAX measures into Measure Table 1/2/3.  
4. Visual validation: cross-check measures using cards, charts and drill-throughs.  
5. Publish to Power BI Service and configure Scheduled / Incremental refresh.  

---

## 🔍 Insights  
- Default rate trends are shown by year and by employment type.  
- Loan distribution and median loan amount segmented by credit score bins and age groups.  
- The decomposition tree and YTD / YOY visuals provide drill-down for where loan value (and risk) is concentrated.  

---

## 🛠 How to Run  
1. Open Loan_Report.pbix in Power BI Desktop.  
2. Verify data sources in Transform Data (Power Query).  
3. Confirm measure tables exist (Measure Table 1 / 2 / 3) and refresh the model.  
4. Use slicers and drill-downs to explore data.  
5. Publish to Power BI Service and enable Scheduled / Incremental refresh.  

---

<img width="1291" height="722" alt="Screenshort 2" src="https://github.com/user-attachments/assets/69d80715-1efe-4742-9043-aec42e48baa6" />


