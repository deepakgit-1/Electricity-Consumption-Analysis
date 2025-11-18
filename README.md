# ⚡ Electricity Consumption Analysis – AIML Project
This repository contains **one Colab notebook** that includes all tasks:

- Task 1: Exploratory Data Analysis (EDA)
- Task 2: Time-Series Forecasting (LSTM + RandomForest)
- Task 3: Unsupervised Learning (KMeans Clustering + PCA + Anomaly Detection)
- Task 4: Rule-Based AI System

✔ All tasks are implemented in order  
✔ All output images are included  
✔ No separate notebooks needed  

---

## 📁 Files in This Repository
1. Electricity_Consumption_Analysis.ipynb ← SINGLE main notebook
2. lstm_power_model.h5 ← Trained LSTM model
3. README.md ← Project explanation
4. Images/ ← All output images

   
---

## 📘 Dataset Used
Household Electric Power Consumption Dataset (UCI Repository)

- Rows: ~2 million  
- Columns: 9  
- Years: 2006–2010  
- One-minute interval readings  

---

# 🧩 Task 1 — Exploratory Data Analysis

### ✔ Done in the notebook:
- Loaded dataset  
- Cleaned missing values  
- Converted numeric types  
- Created timestamp  
- Visualized:
  - Full time-series  
  - Hourly usage  
  - Daily usage  
- Identified patterns and spikes  

### 📷 Output Images:
- **task1_timeseries.png**  
- **task1_hourly.png**  
- **task1_daily.png**

---

# 🔮 Task 2 — Time Series Forecasting

### ✔ Models Used:
- **LSTM Neural Network**
- **RandomForest Regressor**

### ✔ Tasks Completed:
- Prepared hourly data  
- Created windowed dataset  
- Trained and evaluated models  
- Predicted future consumption  
- Visualized prediction performance  

### 📷 Output Image:
- **task2_predictions.png**

---

# 🧠 Task 3 — Unsupervised Learning

### ✔ Performed:
- Daily feature engineering (mean, max, min, std)
- Standardization  
- KMeans clustering (3 clusters: Low, Medium, High usage)
- PCA visualization  
- Isolation Forest anomaly detection  

### 📷 Output Images:
- **task3_clusters.png**  
- **task3_anomalies.png**

---

# 🤖 Task 4 — Rule-Based AI System

A simple rule-based logic was implemented:

- if power < 2 kW → Low Usage
- elif 2 ≤ power < 4 kW → Medium Usage
- else → High Usage


Outputs:
- Usage classification  
- Energy-saving suggestions  

---

# 🚀 How to Use
1. Open **Electricity_Consumption_Analysis.ipynb**
2. Run all cells **in order**
3. Upload the dataset inside Colab when prompted
4. Train the lstm model (Note: after training save and download the model for upcoming use just upload the model and update the path)
5. Outputs will be displayed automatically  
6. All generated plots will be saved in `/images/` folder

---

# 🛠 Tools and Libraries
- Python  
- Google Colab  
- Pandas, NumPy  
- Matplotlib  
- Scikit-Learn  
- TensorFlow / Keras  
- PCA, KMeans, IsolationForest  

---

# 👨‍💻 Author
DEEPAKKUMAR G  
CSBS, KPRIET  





