# SmartHelioDS
# 🌞 SmartHelio Data Science Challenge - Shadow Modeling & PV Anomaly Detection

This repository contains two completed assignments for SmartHelio’s Data Science Challenge. Each problem addresses a unique domain challenge in solar energy and demonstrates analytical thinking, physics-based modeling, and machine learning.

---

## 🔧 Problem 1: Chimney Shadow Area on Tilted Roof

### 📝 Problem Statement

Given a traditional bungalow roof in Chaukori, Uttarakhand (Lat: 29.8375, Long: 80.0316) sloped at 30° and facing Southeast, compute the **shadow area** cast by a 1m tall chimney on the tilted roof at **any given time** of the year.

### ✅ Key Objectives:
- Calculate shadow area using solar position geometry.
- Use libraries like `pysolar` and `pvlib` to obtain sun vectors.
- Project chimney corners onto the roof plane.
- Visualize 2D shadow polygon and 3D projection.
- Identify **date and time** of **minimum shadow** in 2022.

### 📂 Files:
- `chimney_shadow_calcproblem1.ipynb`: Main solution notebook.
- `chimney_shadow_calc.pdf`: Report with methodology, plots, and results.
- `Data Science {Challenge Statements (2 Problems)}.pdf`: Original assignment.

### 📈 Features:
- Vector math to calculate projections.
- Convex hull algorithm to estimate shadow area.
- 2D & 3D visualizations of shadow footprint.
- Year-long simulation to find minimum shadow time.

---

## ⚙️ Problem 2: PV System Anomaly Detection

### 📝 Problem Statement

Use one month of 1-minute interval PV power data to detect **anomalies** in system performance using unsupervised ML models, based on deviations from expected power output.

### ✅ Key Objectives:
- Engineer features from time-series data (`Delta_P`, rolling stats, etc.).
- Apply 3 anomaly detection models:
  - Isolation Forest
  - Local Outlier Factor (LOF)
  - One-Class SVM
- Visualize anomalies and compare model outputs.

### 📂 Files:
- `pv_anomaly_detectionproblem2.ipynb`: Final solution notebook.
- `SampleData.csv`: Input dataset (provided externally).
- `pv_anomaly_detection.pdf`: Report with findings and visualizations.

### 📊 Features:
- Rich visualizations of PV behavior and anomaly points.
- Venn diagram showing model overlap.
- Comparison table summarizing anomaly counts and agreement.

---


