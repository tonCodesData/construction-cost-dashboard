# Construction Cost & Performance Dashboard (BoQ + EVM + S-Curve)

## Project Overview
This project simulates a real-world construction project to demonstrate cost control, project performance tracking, and decision-making using Excel and Power BI.

The dashboard replicates how Quantity Surveyors (QS) and Project Controls professionals monitor budget, cost, and progress on a live construction project.

---

## Objective
To build an end-to-end construction analytics project that demonstrates:

- Budget vs actual cost tracking  
- Bill of Quantities (BoQ) structure  
- Planned vs actual progress comparison  
- Earned Value Management (EVM)  
- S-curve analysis  
- Data-driven commercial decision-making  

---

## Why This Project
I am transitioning into construction, project controls, and quantity surveying (QS) roles by applying my background in data analysis, Excel, and Power BI.

This project bridges my existing experience with construction-style commercial reporting and demonstrates my ability to work with project performance data in a structured and practical way.

---

## Project Workflow
This project follows a structured workflow similar to real-world project controls:

1. Design a realistic construction dataset (BoQ, costs, progress)  
2. Build Excel data model and calculations  
3. Implement Earned Value Management (EVM) metrics  
4. Create S-curve analysis (planned vs actual progress)  
5. Develop Power BI dashboard  
6. Generate insights for decision-making  
7. Publish project with documentation on GitHub  

---

## Dataset Description

### 1. Bill of Quantities (BoQ)
- Defines project cost structure by category (e.g. Groundworks, Structure, MEP, Finishes)  
- Contains total budget allocation per category  

### 2. Monthly Costs (Actual Spend)
- Tracks actual project spending over time  
- Enables comparison against planned budget  

### 3. Planned vs Actual Progress
- Tracks percentage completion over time  
- Forms the basis of S-curve analysis  

### 4. Project Summary
- Overall project value and duration  

---

## Key Concepts Implemented

### Budget vs Actual Tracking
Compare planned budget against actual cost to identify overspending or underspending.

### Earned Value Management (EVM)
Used to evaluate project performance:

- Planned Value (PV)  
- Earned Value (EV)  
- Actual Cost (AC)  

Performance metrics:

- Cost Variance (CV = EV - AC)  
- Schedule Variance (SV = EV - PV)  
- Cost Performance Index (CPI = EV / AC)  
- Schedule Performance Index (SPI = EV / PV)  

---

## S-Curve Analysis
- Visual comparison of planned vs actual progress over time  
- Used to identify delays and performance gaps  

---

## Expected Insights
This dashboard is designed to support commercial and project control decisions by answering:

- Is the project currently over or under budget?  
- Is the project ahead or behind schedule?  
- Which cost categories are driving overspend?  
- How does actual progress compare to planned progress?  
- Is project performance improving or deteriorating over time?  
- What early warning signals indicate potential project risk?  

These insights reflect real-world decision-making in construction project controls and quantity surveying.

---

## Tools Used
- Excel (data modelling and calculations)  
- Power BI (dashboard and visualisation)  
- VS Code (project environment)  
- Git and GitHub (version control and portfolio)  

---

## Project Structure

construction-cost-dashboard/
│
├── data/  
├── docs/  
│   └── progress_log.md  
├── screenshots/  
├── README.md  
└── .gitignore  

---

## Status
Project setup complete. Base Excel dataset and EVM calculation model created, including PV, EV, AC, CV, SV, CPI, and SPI.