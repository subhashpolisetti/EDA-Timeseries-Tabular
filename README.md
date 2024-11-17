
# **Kaggle Dataset Analysis and Modeling**

## **Overview**
This repository contains detailed analysis and predictive modeling workflows for two Kaggle datasets:
1. **Tabular Dataset**: 2017 Yellow Taxi Trip Data
2. **Time Series Dataset**: Air Quality Data

The project focuses on cleaning, preprocessing, and visualizing the datasets while building robust machine learning models using AutoML tools like AutoViML.

---

## **Datasets**
### 1. **2017 Yellow Taxi Trip Data**
- **Description**: This dataset includes detailed trip records from NYC yellow taxis, including fare amounts, trip durations, pickup and drop-off locations, and timestamps.
- **Goal**: Predict fare amounts and analyze trip patterns.
- [Dataset Source](https://www.kaggle.com/datasets/helddata/yellow-taxi-trip-data-2017)

### 2. **Air Quality Data**
- **Description**: A time series dataset capturing air quality metrics such as PM2.5, temperature, and humidity over time.
- **Goal**: Perform time series forecasting and trend analysis.
- [Dataset Source](https://www.kaggle.com/datasets/stytch16/air-quality)

---

## **Workflow**
### **1. Data Exploration and Visualization**
- Comprehensive Exploratory Data Analysis (EDA) using:
  - pandas profiling
  - Manual and Auto EDA tools (e.g., Sweetviz)
- Visualization of trends, distributions, and anomalies with:
  - matplotlib
  - seaborn
  - plotly
  - folium (for geospatial analysis)

### **2. Data Preprocessing**
- Handling missing values and outliers.
- Feature engineering:
  - Derived trip duration and time-based features for the Taxi dataset.
  - Extracted seasonal trends for Air Quality data.
- Clustering and anomaly elimination.

### **3. Model Building**
- Machine learning models built using AutoML tools like AutoViML:
  - Regression models for fare prediction (Taxi dataset).
  - Time series forecasting for air quality metrics.
- Ensemble models for enhanced prediction accuracy.


## **Technologies Used**
- Python Libraries:
  - pandas, NumPy, matplotlib, seaborn, plotly, folium
  - scikit-learn, AutoML (AutoViML)
- Tools:
  - Google Colab
  - GitHub for version control

---

## **Results**
1. **2017 Yellow Taxi Trip Data**:
   - Insights into trip patterns and fare trends.
   - Predictive models achieved an R² score of X and RMSE of Y for fare prediction.

2. **Air Quality Data**:
   - Identified seasonal trends and anomalies in air quality metrics.
   - Time series forecasting model achieved X% accuracy.




