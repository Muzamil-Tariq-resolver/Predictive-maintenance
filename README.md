# Predictive-Maintenance

**Industrial Predictive Maintenance using Physics-Based Analytics, Sensor Data, and Machine Learning**

**Tags:** Physics · Vibration Analysis · Machine Learning · Industrial Analytics  

**Author:** Muzamil Tariq  

---

## Project Overview

Unplanned machine failures are costly in industries like Manufacturing, Automotive, and Aerospace. This project demonstrates how predictive maintenance can prevent downtime by combining **sensor data**, **physics-based insights**, and **machine learning**.

**Key goals:**  
- Predict machine failures before they occur  
- Understand physical mechanisms behind different failure modes  
- Provide actionable insights for industrial decision-making  

**Highlights:**  
- Physics-driven feature analysis (temperature, torque, rotational speed, tool wear)  
- Statistical modeling to uncover relationships between operational parameters and failures  
- Machine learning models for anomaly detection and predictive failure classification  
- Professional reporting and visualization for stakeholders  

---

##  Dataset Description

- **Source:** Kaggle – Industrial Machine Failure Dataset  
- **Observations:** 10,000  
- **Features:** 14 sensor and operational parameters  

**Key Features:**  
- Air temperature [K]  
- Process temperature [K]  
- Rotational speed [rpm]  
- Torque [Nm]  
- Tool wear [min]  

**Target Variables:**  
- **Machine failure** (binary: 0/1)  
- **Failure types (multi-class):**  
  - TWF – Tool Wear Failure  
  - HDF – Heat Dissipation Failure  
  - PWF – Power Failure  
  - OSF – Overstrain Failure  
  - RNF – Random Failure  

This dataset supports both **binary failure prediction** and **multi-class classification**, providing a rich testbed for predictive maintenance solutions.  

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
- Predictive modeling: Logistic Regression, Random Forest, Gradient Boosting  
- Feature engineering and feature importance evaluation  

### Visualization & Reporting
- Industrial-style charts and plots  
- Structured report in MS Word  
- Executive summary and actionable insights in PowerPoint  

---

## Project Outcome

- High-performing Random Forest model for failure prediction  
- Feature insights show **tool wear, thermal stress, torque, and speed** as primary drivers of failure  
- Model tested with unseen data, robust to missing or irrelevant columns  
- Provides actionable insights for maintenance scheduling and risk reduction  

