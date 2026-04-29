# Healthcare Analytics Dashboard – Excel | Power Query | Power Pivot

This project is an end‑to‑end **Healthcare Analytics Dashboard** built using Excel, Power Query, and Power Pivot.  
It analyzes patient encounters, procedures, insurance coverage, and operational trends for a hospital system.

Data Source/Credit: 
https://mavenanalytics.io/data-playground/hospital-patient-records
https://synthea.mitre.org/downloads

---

## 📊 Project Overview
The goal of this project was to transform raw healthcare datasets into a fully interactive dashboard that supports:
- Encounter trend analysis  
- Procedure utilization  
- Insurance coverage insights  
- Patient admission vs readmission patterns  
- Encounter duration and cost metrics  

The final dashboard provides a clear, executive‑level view of hospital performance.

---

## 🧩 Data Model
The relational model includes the following tables:
- **Patients**
- **Encounters**
- **Procedures**
- **Payers**
- **Organizations**
- **Stay_Duration**
- **Reasons_Append**

Power Pivot relationships were created using keys such as:
- `PATIENT_ID`
- `ENCOUNTER_ID`
- `PAYER_ID`
- `ORGANIZATION_ID`

---

## 🔧 Tools & Techniques
- **Excel** (Dashboarding, PivotTables, Slicers)
- **Power Query** (Data cleaning, merging, transformations)
- **Power Pivot** (Data modeling, relationships, DAX measures)
- **DAX** (KPIs: Avg Cost per Visit, Avg Stay Duration, Encounter Counts)
- **Data Visualization** (Bar charts, line charts, pie charts, KPI cards)

---

## 📈 Key Insights
- **27,891** total encounters analyzed  
- **47,701** procedures performed  
- **95.9%** of encounters lasted under 24 hours  
- Medicare and BCBS were the top insurance providers  
- Chronic congestive heart failure was the most common encounter reason  
- Admissions and readmissions show clear multi‑year trends  

---

## 📬 Contact
If you have questions or want to discuss this project, feel free to reach out:
- [LinkedIn](https://www.linkedin.com/in/nikhilkattaguri)  
- [Email](mailto:nikhilkattaguri27@gmail.com)
