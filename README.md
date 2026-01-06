# 🏥 Hospital Emergency Room Dashboard | Power BI

## 📊 Project Overview
This project is an **interactive Hospital Emergency Room (ER) Dashboard** developed using **Microsoft Power BI**.  
It provides both **monthly** and **consolidated** insights into ER operations, helping hospital administrators and decision-makers monitor patient flow, wait times, admissions, and overall service performance.
---
<img width="1148" height="806" alt="Screenshot (211)" src="https://github.com/user-attachments/assets/c41d8f9c-40b1-4c31-a0cb-3fc4a6c792d5" />

<img width="1138" height="781" alt="Screenshot (212)" src="https://github.com/user-attachments/assets/b557e166-8392-4da4-b3a4-90d71aff0978" />

<img width="1170" height="805" alt="Screenshot (213)" src="https://github.com/user-attachments/assets/7b185276-f04c-4b4e-aa0a-1233f97c3d59" />


The dashboard focuses on improving **operational efficiency**, **patient experience**, and **resource planning**.

---

## 🎯 Objectives
- Analyze **patient inflow trends** over time
- Monitor **average waiting time** and service efficiency
- Track **patient satisfaction scores**
- Understand **admission vs non-admission** patterns
- Identify peak hours and high-demand departments
- Perform demographic analysis by **age, gender, and race**

---

## 🛠 Tools & Technologies Used
- **Microsoft Power BI**
- **DAX (Data Analysis Expressions)**
- **Power Query**
- **Data Modeling**
- **Interactive Visual Analytics**

---

## 📌 Dashboard Structure

### 🗓️ 1. Monthly View
Provides insights for a **selected month and year**.

#### Key KPIs
- **Number of Patients**
- **Average Wait Time (Minutes)**
- **Patient Satisfaction Score**
- **Number of Persons Referred**

#### Visuals Included
- Admission Status (Admitted vs Not Admitted)
- % of Patients Seen Within 30 Minutes
- Patients by Age Group
- Patients by Gender
- Patients by Department Referral
- Patients by Race
- Patients by Day and Hour (Heatmap)

---

### 📈 2. Consolidated View
Provides a **long-term performance overview** across a selected date range.

#### Key KPIs
- Total Patients
- Average Wait Time
- Average Patient Satisfaction Score
- Total Patients Referred

#### Visuals Included
- Admission Status Distribution
- Wait Time SLA Performance
- Demographic Analysis (Age, Gender, Race)
- Department Referral Analysis
- Hourly and Daily Patient Distribution

---

### 📄 3. Patient Details View
Displays **record-level patient data** for detailed analysis.

#### Fields Included
- Patient ID
- Patient Name
- Age
- Race
- Admission Date
- Department Referral
- Admission Status

This view is useful for:
- Data validation
- Case-level review
- Operational audits

---

## 🎛 Filters & Slicers
The dashboard supports interactive filtering using:
- **Year**
- **Month**
- **Department Referral**
- **Patient Race**
- **Age Group**
- **Date Range**

All visuals dynamically update based on selected filters.

---

## 🧠 DAX Concepts Used
- Calculated Columns (Age Group, Hour Intervals)
- Time-based analysis
- KPI calculations
- Conditional logic using `SWITCH(TRUE())`
- Performance filtering and segmentation

Example concepts:
- Average Wait Time
- SLA compliance (Seen within 30 minutes)
- Patient count metrics
- Satisfaction score aggregation

---

## 📈 Key Insights
- Peak patient inflow occurs during specific **day–hour combinations**
- A significant percentage of patients exceed the **30-minute wait target**
- Certain departments receive disproportionately high referrals
- Demographic analysis highlights patient distribution by age and race
- Admission rates vary significantly month-to-month

---


