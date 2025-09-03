**Healthcare Operations**

Project Overview

This project simulates a healthcare dataset to analyze patient outcomes, revenue trends, and operational efficiency. The goal is to uncover insights that can help healthcare administrators make data-driven decisions.


**ASK**

**Problem Statement**

What patterens in patient attendance, appointment types, and revenue can be uncovered to help reduce no-sho ratesand improve overall healthcare operaions efficiency?

3 Guided Questions:

1. What trends exist in patient attendance across appointment types, times, and days, and how do these patterns affect no-show rates?
2. How do appointment types (consultations, follow-ups, specialty visits) correlate with revenue and patient retention?
3. Which operational factors (check-in times, appointment volumes, peak days) most strongly impact efficiency and overall patient flow?

**Prepare**

Data Source: Created Mock healthcare dataset simulating patient visits 
Tools Used: SQL, Tableau, Excel

**Key Variables:**

patient_id – unique patient identifier

visit_date / check_in_time / check_out_time

appointment_type – e.g., consultation, follow-up

no_show – patient attendance status

revenue – payment received


**Process**


Created a structured dataset including patient ID, visit date, department, scheduled vs attended appointments, revenue, and insurance type

Data Cleaning & Preparation

Removed duplicate and incomplete records

Converted timestamps into day, month, and visit duration

Standardized appointment types and patient categories

Aggregated revenue and no-show metrics for analysis



**Analyze & Share**


Analysis & Insights

Key Questions Answered:

1. What are peak patient volumes by day/week/month?
2. Which appointment types have the highest no-show rates?
3. What factors correlate with patient attendance?


Insights:

No-shows are higher for certain appointment types and days

Peak patient load occurs on mid-week mornings

Revenue trends align closely with patient volume

Operational bottlenecks can be identified for process improvement


Tableau Dashboard:
📈 View Dashboard [ https://public.tableau.com/views/HealthcareDashboardAppointmentTrendsRevenueandNo-ShowKPIs/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link ]


**Deliverables**

Cleaned SQL tables for patient and revenue analysis

Tableau dashboards visualizing trends and operational metrics

Insights report highlighting recommendations for administrators


**Act**


**Recommendations**

Implement reminder notifications for high-risk no-show appointments

Optimize staffing schedules during peak hours

Focus on appointment types with higher revenue potential

Use data-driven scheduling to reduce patient wait times



**What I Would Do Differently**

Include patient demographics to better understand patterns

Integrate insurance type and payment data for revenue analysis

Predict no-shows using machine learning models

Conduct longitudinal studies for patient retention



⚠️ Disclaimer

This dataset is fictional and created for educational and portfolio purposes only. It does not contain any real patient information.
