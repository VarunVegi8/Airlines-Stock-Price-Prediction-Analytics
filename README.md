# Airlines Stock Price Prediction Analytics

This project delivers a comprehensive predictive analytics dashboard for airline stock performance using a combination of financial, operational, and market data.

---

## Introduction

**Airlines Stock Price Prediction Analytics** aims to enhance decision-making in the airline industry by integrating real-time and historical datasets. By employing advanced machine learning algorithms and data processing pipelines, the project forecasts airline stock performance and operational trends. It is designed for investors, airline executives, and financial analysts to gain insightful, actionable data.

---

## Architecture

The project leverages a multi-layered architecture for data ingestion, feature engineering, and forecasting:

### Data Ingestion
- Automated collection of airline operational data from the **Bureau of Transportation Statistics (BTS)** and financial data from **Yahoo Finance**.
- Scheduled via **AWS Lambda** and **EventBridge** for regular updates.

### Feature Engineering & Modeling
- Integration and processing of datasets to create enriched features.
- Predictive models trained include **Ridge**, **Lasso**, **XGBoost**, and **LSTM**, applied on both historical and high-frequency trading data.

### Dashboard & Analytics
- An interactive dashboard visualizes key performance metrics, forecasted trends, and trading signals.
- Designed to support strategic decision-making in real-time.

---

## Technology Used

- **Programming Language:**  
  Python

- **Data Processing & Analytics:**  
  `pandas`, `numpy`

- **Cloud & Automation:**  
  `AWS Lambda`, `AWS EventBridge`, `AWS S3`

---

## Dataset Used

The project utilizes comprehensive datasets including:

- **Operational Data**  
  Collected from **BTS**, detailing flight performance, delays, and capacity metrics.

- **Financial Data**  
  Stock market data from **Yahoo Finance**, covering daily **OHLCV** metrics and other financial indicators.

---

## Data Pipeline Execution

1. **Data Collection:**  
   Automated scripts pull data from BTS and Yahoo Finance into raw and processed formats.

2. **Feature Engineering:**  
   Cleaned data is integrated and transformed to extract key metrics influencing airline stock performance.

3. **Forecasting Models:**  
   Multiple models are trained to capture both long-term trends and short-term fluctuations.

4. **Interactive Dashboard:**  
   The final web dashboard visualizes forecasts and key KPIs, offering real-time insights to users.

---

## Challenges Faced

- Integrating diverse datasets with varying update frequencies and formats.
- Balancing model complexity with interpretability for different forecasting horizons.
- Managing real-time data ingestion and ensuring robust pipeline automation.

---

## GitHub Repositories

### Backend (this repo)
**[Airlines Stock Price Prediction Analytics – Backend](https://github.com/VarunVegi8/Airlines-Stock-Price-Prediction-Analytics)**  
This repository contains the complete backend pipeline including data ingestion, modeling, and forecasting.

### Frontend
**[Flight Forecast Dashboard – Frontend](https://github.com/nitheshbethur39/flight-forecast-dashboard)**  
A separate interactive web dashboard built using **React**, **Vite**, and **TailwindCSS** that visualizes model outputs, forecast trends, KPIs, and day trading signals for each airline.

---

## Contributions

Contributions, feedback, and suggestions are highly welcome. For more details, please refer to the documentation provided in each module within the repositories.
