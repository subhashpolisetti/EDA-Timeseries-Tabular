
# ML Workflow for Taxi Fare Prediction

This project demonstrates a comprehensive machine learning workflow to predict taxi fares using historical trip data. The workflow includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, hyperparameter tuning, and deployment of a final predictive model. It leverages **PyCaret** for rapid prototyping and streamlined machine learning pipeline development.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Technologies Used](#technologies-used)
3. [Workflow Steps](#workflow-steps)
4. [Role of PyCaret](#role-of-pycaret)
5. [How to Run](#how-to-run)
6. [Results](#results)

---

## Project Overview

The primary goal is to predict taxi fares based on input features such as trip distance, passenger count, payment type, and pickup details. This project follows an end-to-end machine learning lifecycle, ensuring robust results and model interpretability.

---

## Technologies Used
- **Python**: Core programming language for the project.
- **Jupyter Notebook/Colab**: Environment for running the pipeline.
- **Pandas, NumPy**: For data preprocessing and manipulation.
- **Matplotlib, Seaborn**: For data visualization.
- **PyCaret**: For model development, hyperparameter tuning, and AutoML functionality.
- **Scikit-learn**: Additional machine learning utilities.
- **LightGBM**: Model training.

---

## Workflow Steps
### 1. Data Collection and Loading
- Historical taxi trip data is loaded and inspected for completeness.

### 2. Exploratory Data Analysis (EDA)
- Advanced visualizations to uncover patterns and anomalies.
- Analyzing feature distributions and relationships.

### 3. Data Preprocessing
- Handling missing values.
- Encoding categorical variables.
- Scaling and normalizing data.

### 4. Feature Engineering
- Creating new features like trip duration.
- Temporal feature extraction from timestamps.

### 5. Model Training
- Using PyCaret for rapid model training and evaluation.
- Algorithms include LightGBM, Gradient Boosting, and Linear Regression.

### 6. Hyperparameter Tuning
- PyCaret's built-in optimization ensures optimal model parameters.

### 7. Model Ensemble
- Creating an ensemble model using PyCaret's blending techniques for improved accuracy.

### 8. Deployment Preparation
- Saving the pipeline and model for future use.
- Demonstrating sample predictions on test data.

---

## Role of PyCaret

**PyCaret** significantly simplifies the ML workflow by providing:

- **Model Comparison**: Quickly evaluates and compares multiple models.
- **Hyperparameter Tuning**: Automates grid search for optimal configurations.
- **Model Stacking and Blending**: Creates advanced ensembles with minimal code.
- **Pipeline Creation**: Integrates preprocessing steps directly into the ML pipeline.
- **User-Friendly API**: Reduces verbose code, speeding up development.

For more details, visit the [PyCaret documentation](https://pycaret.org/docs).

---

## How to Run
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/subhashpolisetti/EDA-Timeseries-Tabular.git
   ```
2. **Run the Notebook**:
   Open `ML_Workflow_for_Taxi_Fare_Prediction.ipynb` in Jupyter or Colab and execute the cells.

3. **Predict with New Data**:
   Modify the prediction section in the notebook to input new data for predictions.

---

## Results

### Key Metrics:
- **Mean Absolute Error (MAE)**: 1.79
- **Root Mean Square Error (RMSE)**: 2.99
- **R-squared**: 0.87
- **Best Model**: Ensemble (Gradient Boosting, LightGBM, and Linear Regression)

### Sample Prediction:
**Input Features**:
```json
{'trip_distance': 3.34, 'pickup_hour': 8, ...}
```
**Predicted Fare**: `$14.76`





