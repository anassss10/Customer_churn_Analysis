# Customer_churn_Analysis
Data Analysis Project Showcasing Customer Churn Analysis Using Python and Power Bi


**Project Overview**

This project delivers an end‑to‑end, production‑ready customer churn analysis using Python, Machine Learning, and Power BI, designed specifically to demonstrate real‑world business thinking and job‑ready analytical skills.

The goal is not just to analyze churn, but to identify high‑risk customer segments, explain why churn happens, predict churn, and recommend actionable retention strategies.


**Business Problem**

Customer churn directly impacts revenue, customer lifetime value, and acquisition costs in the telecom industry.


Objective:

Identify churn‑prone customers early and provide data‑driven insights to reduce churn and improve retention.


**Dataset**

Source: Telecom Customer Churn Dataset

Records: 7,043 customers

Target Variable: Churn (Yes / No)


**Key Features**

tenure

Contract

MonthlyCharges

TotalCharges

SeniorCitizen

Churn

**Tools & Technologies**

**Programming & Analysis**

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit‑learn


**Visualization & BI**

Power BI

DAX Measures

Interactive Dashboards


**Data Cleaning & Feature Engineering**

**Data Preparation**

Converted TotalCharges to numeric

Removed invalid and missing records

Encoded churn as a binary variable (ChurnFlag)


**Advanced Feature Engineering**

Tenure Bands (0–3, 3–6, 6–12 months, etc.)

Monthly Charge Buckets (Low, Medium, High, Very High)

Contract Risk Levels (High / Medium / Low Risk)

These features significantly improved segmentation, insight quality, and model performance.


**Exploratory Data Analysis (EDA)**

**Visual Insights (11+ Visuals)**

Churn distribution

Churn by contract type

Churn rate by tenure band

Monthly charges vs churn

Correlation heatmap

Tenure vs pricing scatter analysis

Churn heatmap by tenure and contract


**Key Insight**

38% of churned customers were on month‑to‑month contracts with less than 3 months tenure.


**Machine Learning – Churn Prediction**

**Models Built**

Logistic Regression (baseline, interpretable)

Random Forest Classifier (non‑linear, higher accuracy)

**Performance**

Model,	                  Accuracy,	 ROC‑AUC

Logistic Regression	    ~81%	     ~0.84

Random Forest	          ~83%	     ~0.86

**Key Predictors Identified**

Contract type (Month‑to‑month)

Short tenure

High monthly charges

**Power BI Dashboard**

Pages Included

Executive Overview – KPIs & churn summary

Churn Drivers Analysis – Visual deep‑dive


**Dashboard Features**

KPI cards

Heatmaps

Scatter plots

Interactive slicers

Business‑ready storytelling


**Business Recommendations**

High‑Risk Segment

New customers (< 3 months)

Month‑to‑month contracts

High monthly charges


**Recommended Actions**

Early onboarding offers (first 90 days)

Incentives for 1‑year contract upgrades

Proactive customer support outreach


**Expected Impact**

Reducing early churn can improve revenue retention by 15–20%.


**Project Impact**

Business‑driven analysis

Advanced feature engineering 

Predictive modeling 


**Repository Structure**

├── notebooks/

│ └── churn_analysis.ipynb

├── powerbi/

│ └── churn_dashboard.pbix

├── data/

│ └── telecom_churn_final.csv

├── README.md
