# **Economic Forecasting Using ADL and AR Models**

## **Overview**  
This repository contains the **NUS_DSESC_DATABUSTERS_14.ipynb** notebook, which explores **GDP forecasting** using **Autoregressive (AR) and Autoregressive Distributed Lag (ADL) models**.  
The project applies **recursive cross-validation** to assess model performance and evaluates different macroeconomic indicators for improving predictions.  

## **Key Features**  
✔ **ADL Model Implementation** – Uses lagged economic indicators to forecast GDP.  
✔ **AR Model Implementation** – Captures long-term GDP trends using autoregression.  
✔ **Recursive Cross-Validation** – Evaluates model accuracy under real-time forecasting conditions.  
✔ **RMSE Analysis** – Measures prediction error for performance comparison.  
✔ **Macroeconomic Indicators Selection** – Features are optimized for improved forecasting accuracy.  

## **Usage**  
✔ Modify the lag structure in the ADL model to fine-tune predictions.  
✔ Evaluate the recursive cross-validation output for RMSE trends.  
✔ Use PCA or feature selection to refine the input variables.  
✔ Extend the forecast to analyze policy impacts on GDP trends.  

## **Results & Findings**  

📈 **Forecasted US GDP Growth for 2025 based on ADL Model (relative to the preceding quarter):**  
- **Q1 2025:** 0.22%  
- **Q2 2025:** 0.28%  
- **Q4 2025:** 0.36%  

📊 **RMSE Comparison:** ADL model outperforms AR in stable conditions but struggles during high-volatility periods.  
📉 **Limitations:** The model exhibits lagging behavior in economic shocks (e.g., COVID-19).  
🔍 **Future Work:** Incorporating machine learning techniques and alternative feature selection methods can improve accuracy.  
