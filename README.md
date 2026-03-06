# IBM-HR-Attrition-Burnout-Dashboard
Power BI dashboard analyzing employee attrition and burnout risk using IBM HR Analytics dataset (1,470 employees, 35 variables)
## Project Overview
An interactive 3-page Power BI dashboard built for IT service and consulting
firms to monitor employee attrition patterns, identify burnout risk early,
and analyze compensation-driven retention factors.
## Problem Statement
IT consulting firms lose 20–25% of their workforce every year — one of the highest attrition rates across all industries. Each departure costs an estimated ₹8–15 lakhs in recruitment, onboarding, and lost productivity.
Yet most HR teams only react after an employee resigns.
This dashboard was built to change that — by identifying burnout signals and attrition risk before employees leave, giving HR teams and department managers data to act on proactively.

## 📊 Dashboard Pages
Page 1 — Executive Summary
High-level attrition overview for leadership and HR heads.
VisualInsight DeliveredOverall Attrition Rate (KPI Card)16.1% — 237 of 1,470 employees leftAttrition by Department (Bar)Which business unit bleeds the most talentAttrition by Job Role (Bar)Sales Reps at ~40% — highest exit rateAttrition by Age Group (Column)26–35 age group is highest riskAttrition by Gender (Donut)Gender-based attrition distribution

Page 2 — Burnout Risk Analysis ⭐
The most unique page — built around a custom engineered burnout score.
VisualInsight DeliveredBurnout Category Distribution (Donut)Low / Medium / High / Critical breakdownOvertime Impact on Attrition (Bar)Overtime employees leave at 3× the rateBurnout Risk by Department (Stacked Bar)Which dept has the most critical-risk employeesWork-Life Balance vs Attrition (Column)Score 1 (Bad) drives nearly 2× attrition

Page 3 — Compensation & Retention Intelligence
What makes employees stay — or leave.
VisualInsight DeliveredIncome Gap: Active vs Exited (Bar)Exited employees earned significantly lessStock Option Level vs Attrition (Column)Level 0 employees exit at the highest rateTenure vs Attrition Rate (Line)Attrition peaks at Year 1 & Year 2Training Frequency vs Attrition (Column)0 trainings/year = highest attrition
## Custom DAX Engineering
The most technically challenging part of this project was building the Burnout Risk Score — there is no single column in the dataset that measures burnout. It required combining 6 separate HR variables into one composite metric.
- Burnout Risk Score (composite of 6 variables)
- Burnout Category segmentation (Low / Medium / High / Critical)
- Dynamic Attrition Rate measure with slicer cross-filtering

## 🔍 Key Findings
- Overall attrition rate: **16.1%** (237 of 1,470 employees)
- Overtime employees leave at **3× the rate** of non-overtime staff (30.5% vs 10.4%)
- Sales Representatives have the highest attrition rate: **~40%**
- Employees with **0 stock options** show highest exit rates
- Attrition peaks at **Year 1–2** of tenure — early attrition is the biggest risk
- Employees with **0 trainings/year** have significantly higher attrition
- Frequent travelers exit at ~25% vs ~8%
- WLB Score 1 (Bad) nearly doubles attrition rate
  
## 🛠️ Tools & Technologies
- Power BI Desktop
-  DAX (Data Analysis Expressions)
-  Power Query (M)
-  IBM HR Analytics Dataset
  
## 📸 Dashboard Screenshots
Page 1 — Executive Summary
<img width="1170" height="663" alt="Page1_Executive_Summary png" src="https://github.com/user-attachments/assets/0b8a5cb8-1f43-404c-ad45-7320054ec771" />
Page 2 — Burnout Risk Analysis
<img width="1189" height="669" alt="Page2_Burnout_Risk png" src="https://github.com/user-attachments/assets/50cad9d8-a513-4487-8c8a-b0e8e5d368e7" />
Page 3 — Compensation & Retention
<img width="1168" height="659" alt="Page3_Compensation_Retention png" src="https://github.com/user-attachments/assets/9571193d-d7ba-4c4e-9720-22bf77408301" />

## 🚀 How to Run This Project
- Download the dataset from Kaggle:
👉https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset
- Download Power BI Desktop
- Open the .pbix file from the Dashboard folder
-  Update data source path:
   Home → Transform Data → Data Source Settings → change path to your CSV location
-   Refresh — all visuals will populate automatically



  
