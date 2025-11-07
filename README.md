# 🌦️ Weather Prediction & Visualization in R

A mini project that generates synthetic weather data, visualizes temperature trends, and predicts future weather using R.  
This project runs both **locally in RStudio** and **on Google Colab** without needing to upload any external dataset.

---

## 📋 Project Overview

This project demonstrates:
- Generating a **synthetic weather dataset** (no CSV uploads required)
- Visualizing **temperature, humidity, and rainfall** trends using `ggplot2`
- Predicting the **next 7 days’ temperature** using an ARIMA time series model

---

## 🧩 Project Structure
weather-prediction-R/
│
├── data/ # (Optional) folder for datasets if you ever save one
├── scripts/
│ └── weather_analysis.R # Main R script for visualization and prediction
├── README.md # Project documentation


---

## 🧠 Features

- Generates synthetic daily weather data (temperature, humidity, rainfall)
- Produces line plots, scatter plots, and forecasts
- Works seamlessly on Google Colab or locally in RStudio
- No manual dataset upload — data is created automatically

---

## 🧰 Libraries Used

| Package | Purpose |
|----------|----------|
| **ggplot2** | Data visualization |
| **dplyr** | Data manipulation |
| **lubridate** | Date handling |
| **forecast** | Time series forecasting |
| **readr** | CSV reading (optional) |
| **Rcpp** | Backend dependency |

Install all required packages with:
```r
install.packages(c("ggplot2", "dplyr", "lubridate", "forecast", "readr", "tseries", "Rcpp"))
