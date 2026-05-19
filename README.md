# Predictive-Maintenance

**Industrial Predictive Maintenance using Physics-Based Analytics, Sensor Data, and Machine Learning**

**Tags:** Physics · Vibration Analysis · Machine Learning · Industrial Analytics  

**Author:** Muzamil Tariq  

---

## Project Overview

Modern industries such as Manufacturing, Automotive, and Aerospace heavily rely on machines operating continuously under varying operational conditions. Unexpected equipment failures can cause:

- Production downtime
- Financial losses
- Reduced operational efficiency
- Increased maintenance costs
- Safety risks

This project develops an **Industrial Predictive Maintenance System** using:

- Physics-based engineering insights
- Sensor-driven analytics
- Machine learning algorithms
- Statistical modeling
- Cloud data warehousing with Google BigQuery

The system predicts machine failures before breakdowns occur and helps industries move from **reactive maintenance** to **predictive maintenance strategies**.

---

# Problem Statement

Traditional maintenance approaches are inefficient because they either:

### Reactive Maintenance
Machines are repaired only after failure occurs.

### Scheduled Maintenance
Components are replaced at fixed intervals regardless of actual machine condition.

These approaches increase operational costs and waste resources.

The challenge is to build an intelligent system capable of:

- Detecting hidden failure patterns
- Predicting failures before breakdowns
- Understanding physical failure mechanisms
- Reducing downtime and maintenance costs
- Scaling analytics pipelines for industrial environments

---

# Project Goals

The primary objectives of this project are:

- Predict machine failures before they occur
- Analyze physical relationships between operational variables
- Identify key drivers of machine failure
- Build robust machine learning models
- Integrate ML workflows with Google BigQuery
- Create scalable cloud-based analytics pipelines
- Generate actionable maintenance insights

---

# BigQuery Integration & Cloud Pipeline

This project demonstrates modern cloud-based industrial analytics workflows using **Google BigQuery**.


##  Dataset Description

- Industrial Machine Failure Dataset  
- **Observations:** 10,000  
- **Features:** 6 sensor and operational parameters  

**Key Features:**  
- Air temperature [K]  
- Process temperature [K]  
- Rotational speed [rpm]  
- Torque [Nm]  
- Tool wear [min]
- The Type column has values: These are machine sizes or classes:

L → Small/Light machine

M → Medium machine

H → Heavy/Large machine

**Target Variables:**  
- **Machine failure** (binary: 0/1)  
- **Failure types (multi-class):**  
  - TWF – Tool Wear Failure  
  - HDF – Heat Dissipation Failure  
  - PWF – Power Failure  
  - OSF – Overstrain Failure  
  - RNF – Random Failure   

---

## Skills & Techniques Demonstrated

### Physics & Engineering Insights
- Thermal analysis (air vs. process temperature)  
- Mechanical stress interpretation (torque and rotational speed)  
- Tool wear progression and failure mechanism modeling  

### Data Science & Machine Learning
- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA) using Seaborn & Matplotlib  
- Statistical modeling with Statsmodels  
- Anomaly detection (Isolation Forest, PCA)  
- Predictive modeling: Logistic Regression, Random Forest  
- Feature engineering and feature importance evaluation  

### Visualization & Reporting
- Industrial-style charts and plots  
- Structured report in MS Word  
- Executive summary and actionable insights in PowerPoint  

---

## Outcomes

- High-performing Random Forest model for failure prediction  
- Feature insights show **tool wear, thermal stress, torque, and speed** as primary drivers of failure  
- Model tested with unseen data, robust to missing or irrelevant columns  
- Provides actionable insights for maintenance scheduling and risk reduction  

