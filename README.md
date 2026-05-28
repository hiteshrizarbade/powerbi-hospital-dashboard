
🏥 Hospital Analytics Dashboard
📌 Project Overview

This project is an interactive Hospital Analytics Dashboard developed using Power BI to analyze hospital operations, patient trends, treatment performance, billing insights, appointments, and bed occupancy management.

The dashboard helps healthcare organizations make data-driven decisions by visualizing key hospital KPIs and operational metrics through interactive reports and visualizations.

🚀 Objectives
Monitor hospital operational performance
Analyze patient admission trends
Track appointment wait times
Evaluate treatment and department performance
Monitor billing and insurance coverage
Analyze hospital bed occupancy
Improve healthcare decision-making using analytics

🛠️ Tools & Technologies Used
Power BI
Power Query
DAX
Excel  Dataset
Data Modeling
ETL Process
Data Visualization

📂 Dataset Information

The project consists of 6 interconnected tables:

👨‍⚕️ Doctors Table

Contains doctor-related information.

Columns Included
doctor_id
doctor_name
specialization
department
experience_years
consultation_fee

🧑‍🤝‍🧑 Patients Table

Contains patient demographic and medical information.

Columns Included
patient_id
patient_name
gender
age
city
disease
admission_date
discharge_date
emergency_case
satisfaction_score

💉 Treatments Table

Contains treatment and diagnosis-related details.

Columns Included
treatment_id
patient_id
doctor_id
treatment_type
treatment_cost
treatment_status
diagnosis

💳 Billing Table

Contains billing and payment information.

Columns Included
billing_id
patient_id
total_bill
insurance_coverage
insurance_claim
payment_status
billing_date

📅 Appointments Table

Contains appointment scheduling and wait-time information.

Columns Included
appointment_id
patient_id
doctor_id
appointment_date
department
wait_time_minutes
appointment_status

🛏️ Beds Table

Contains hospital bed allocation and occupancy details.

Columns Included
bed_id
ward_type
bed_status
patient_id
admission_type
occupancy_days
---

# 📊 Key KPIs

The dashboard includes the following KPIs:

* Total Patients
* Total Revenue
* Average Wait Time
* Average Satisfaction Score
* Insurance Claim Amount
* Emergency Case Count
* Department-wise Performance
* Patient Admission Trends

---

# 📈 Power BI Features Used

## ✔️ Data Modeling

* Relationships between multiple tables
* Star schema implementation

## ✔️ DAX Measures

Custom DAX measures were created for KPI calculations and business insights.

### Example Measures

```DAX
Avg Wait Time = 
AVERAGE(Appointments[wait_time_minutes])
```

```DAX
Avg Satisfaction Score = 
AVERAGE(Patients[satisfaction_score])
```

```DAX
Total Revenue = 
SUM(Billing[treatment_cost])
```

```DAX
Insurance Claim Amount = 
SUM(Billing[insurance_claim])
```

---

# 📌 Important Power BI Concepts Applied

* DAX
* Measures
* Calculated Columns
* Filter Context
* Row Context
* ETL
* Relationships
* Slicers
* Drillthrough
* Time Intelligence
* Conditional Formatting
* Cross-filtering
* Tooltips
* Aggregations
* Bookmarks

---

# 📷 Dashboard Screenshots

## Hospital Performance Dashboard

dashboard-1.png

## Patient Analytics & Demographic Insights

dashboard-2.png

## Hospital Revenue and Doctor Efficiency Analytics

dashboard-3.png

---

# 📊 Insights Generated

* Certain departments have significantly higher patient wait times.
* Emergency admissions increase during weekends.
* Insurance coverage impacts revenue trends.
* Patient satisfaction scores vary by department.
* High patient load affects operational efficiency.

---

# 🎯 Business Impact

This dashboard can help hospitals:

* Reduce patient wait times
* Improve resource allocation
* Increase operational efficiency
* Monitor revenue performance
* Enhance patient satisfaction

---

# 📁 Project Structure

```text
PowerBI-Hospital-Analytics/
│
├── Hospital_Analytics.pbix
├── datasets/
├── screenshots/
├── README.md
```

---

# 🔮 Future Improvements

* Real-time data integration
* Predictive analytics using Machine Learning
* AI-based patient risk prediction
* Appointment forecasting

---

# 👨‍💻 Author

Developed by HITESHRI ZARBADE

* Power BI Developer
* Data Analytics Enthusiast
* AI & ML Learner

---

# ⭐ GitHub Repository Purpose

This project is part of my Data Analytics & Power BI portfolio to demonstrate:

* Dashboard Development
* Data Visualization
* DAX Skills
* Data Modeling
* Healthcare Analytics
* Business Intelligence Concepts

---
