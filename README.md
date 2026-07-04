#  Predictive Maintenance System using LightGBM

An AI-powered **Predictive Maintenance System** that predicts machine failure risk using sensor data.  
Built using **LightGBM, Python, and Scikit-learn**, with advanced data visualizations and real-time prediction capability.

---

##  Project Overview

Industrial machines often fail without warning, causing downtime and financial loss.  
This project uses Machine Learning to predict **failure risk in advance** using sensor readings.

The model classifies whether a machine is:
- Normal (No Failure Risk)
-  High Risk (Possible Failure)

---

##  Dataset Features

- Machine_ID
- Temperature (°C)
- Vibration (mm/s)
- Pressure (bar)
- Runtime Hours
- Humidity (%)
- Power Consumption (kW)
- Maintenance History
- Failure Risk (Target)

---

##  Machine Learning Model

- Algorithm: **LightGBM Classifier**
- Task: Binary Classification
- Output: Failure Risk Prediction (0 / 1)

---

##  Visualizations

The project includes advanced visual analytics:

- Confusion Matrix
- Feature Importance Plot
- ROC Curve
- Probability Distribution of Failure Risk

---

## Tech Stack

- Python 
- LightGBM 
- Pandas & NumPy
- Scikit-learn
- Matplotlib

---

##  Installation

```bash
pip install lightgbm scikit-learn pandas numpy matplotlib openpyxl
