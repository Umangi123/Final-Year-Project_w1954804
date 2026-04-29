# Final-Year-Project_w1954804
# Rice Supply Analysis & Forecasting Dashboard – Sri Lanka

## 📌 Project Overview
This repository contains the datasets and forecasting models used for analysing Sri Lanka’s rice production, consumption, and trade. The project integrates multiple data sources and applies time series forecasting techniques to support decision-making through an interactive Power BI dashboard.

---

## 📂 Repository Structure


---

## 📊 Data Description

### 🔹 Production Data
- District-level rice production data  
- Covers both **Maha** and **Yala** seasons  
- Files are separated by year and season (e.g., `2004_2005_Maha.xlsx`, `2005_Yala.xlsx`)  
- Used for calculating annual production and yield  

### 🔹 National-Level Data
- **Consumption Data.xlsx** → national rice consumption  
- **Population_Data.xlsx** → population data  
- **Import_Export.xlsx** → trade data (imports & exports)  
- **Price_Data.xlsx** → price indicators  
- **exchange_rate_usd_lkr.xlsx** → currency conversion  

### 🔹 Forecast Data
- **Forecast Model.csv** → dataset used for model development  
- **forecast_output.xlsx** → final forecast results used in the dashboard  

---

## 🧠 Forecasting Models

### 1. Model Comparison
- Models tested:
  - Holt’s Exponential Smoothing  
  - ARIMA  
  - Prophet  
- Approach:
  - Train-test split (last 3 years used for testing)  
  - Performance evaluated using Mean Absolute Error (MAE)  

### 2. Final Forecasting Model
- ARIMA used for **yield forecasting**  
- Prophet used for **consumption forecasting**  
- Models trained on the full dataset  
- Forecast period: **2024–2029**  

---

## 🛠️ Technologies Used
- Python (Google Colab)
  - pandas  
  - statsmodels  
  - prophet  
- Power BI
  - Power Query (data preprocessing)  
  - DAX (calculated measures)   

---

## ▶️ How to Run

### Forecasting Models
1. Open notebooks in Google Colab:
   - `Forecast_Model_Comparison.ipynb`
   - `Final_Forecasting_Model.ipynb`

---

## 🔁 Reproducibility
All datasets and model code are included in this repository.  
Forecasting results can be reproduced by running the provided notebooks.

---

## 📌 Notes
- Production data is stored separately due to district-level granularity  
- Forecasting is based on historical trends and model assumptions  
- Scenario analysis is implemented within Power BI  

---

## 👤 Author
Umangi Jayakody  
BSc (Hons) Business Data Analytics  

---

## 📎 License
This project is submitted for academic purposes.
