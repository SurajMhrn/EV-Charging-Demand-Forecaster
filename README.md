# Electric Vehicle Charging Demand Forecasting ⚡🚗

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Tableau](https://img.shields.io/badge/Visualization-Tableau-e97627)
![Time Series](https://img.shields.io/badge/Model-ARIMA%2FProphet-green)

## 📖 Overview
This project focuses on predicting the energy demand at Electric Vehicle (EV) charging stations. By analyzing historical usage data alongside external factors like weather conditions, time of day, and traffic density, we aim to optimize charging station operations and grid load management.

## 🎯 Objectives
* **Data Integration:** Merge EV usage logs with weather and traffic datasets to create a robust feature set.
* **Forecasting:** Develop time-series models (ARIMA/Prophet) to predict future demand.
* **Visualization:** Create interactive Tableau dashboards to monitor demand curves and peak hours.
* **Optimization:** Propose strategies for efficient energy distribution based on predicted patterns.

## 🛠️ Tools & Technologies
* **Python:** For data processing and modeling.
* **Pandas & NumPy:** Data manipulation and merging.
* **Statsmodels / Prophet:** For building time-series forecasting models.
* **Tableau:** For creating interactive heatmaps and demand dashboards.
* **Excel:** Initial data storage and reporting.

## 📂 Project Structure
```text
├── data/                   # Weather, Traffic, and EV usage datasets
├── notebooks/              # Jupyter notebooks for ARIMA/Prophet modeling
├── dashboards/             # Tableau workbook files (.twb)
├── README.md               # Project documentation
└── requirements.txt        # Python dependencies
