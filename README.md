# Interactive Machine Learning Workflow Dashboard

This repository contains an **Interactive Machine Learning Workflow Dashboard** built using **Streamlit**, **Prophet**, **Seaborn**, and other Python libraries. This tool is designed to streamline and simplify the machine learning process, enabling practitioners to visualize, analyze, and interpret key stages of the machine learning workflow interactively.

---

## Introduction

The Interactive Machine Learning Workflow Dashboard is a user-friendly and feature-rich tool tailored for machine learning practitioners, data scientists, and analysts. It provides a comprehensive framework for exploring data, preprocessing it, evaluating models, and interpreting results. With its intuitive design, users can easily upload their datasets and visualize complex processes without requiring in-depth coding knowledge.

### Key Objectives:
- Enhance interpretability and trust in machine learning models.
- Provide insights into data patterns and potential preprocessing strategies.
- Evaluate model performance and diagnostics interactively.
- Facilitate the machine learning lifecycle from data exploration to model explainability.

---

## Features

### 1. **Exploratory Data Analysis (EDA)**
- **Missing Data Heatmap**: Visualize patterns of missing values in your dataset.
- **Correlation Matrix**: Identify relationships between numerical features.
- **Distribution Plots**: Analyze the original and transformed distributions of categorical variables.

### 2. **Data Preprocessing**
- **Categorical Variable Encoding**: Visualize encoding effects dynamically.
- **Scaling and Transformation**: Apply log transformation and standardization with visual feedback.
- **High-Cardinality Handling**: Automatically display the top 20 categories for better clarity.

### 3. **Time Series Forecasting**
- **Prophet Forecasting**: Perform time series predictions and visualize trends, seasonality, and uncertainty.
- **Dynamic Column Selection**: Choose time series and target columns directly from the dataset.
- **Interactive Plots**: See detailed and clean visualizations of forecasted values.

### 4. **Model Evaluation**
#### Classification Metrics:
- **Confusion Matrix**: View model classification performance.
- **ROC and Precision-Recall Curves**: Evaluate model discrimination capabilities and performance metrics.

#### Regression Diagnostics:
- **Residual Analysis**: Examine residuals to detect patterns and biases.
- **Q-Q Plot**: Assess normality of residuals.
- **Prediction vs. Actual Plot**: Visualize prediction accuracy.

### 5. **Model Interpretability**
- **SHAP and LIME Integration**: Interpret and explain model predictions (placeholders included for integration).
- **Partial Dependence Plots**: Explore feature interactions.

---

## Technologies Used

- **Python 3.8+**
- **Streamlit**: For creating the interactive dashboard.
- **Prophet**: For time series forecasting and trend analysis.
- **Seaborn & Matplotlib**: For data visualization and aesthetic plots.
- **Pandas & NumPy**: For efficient data manipulation and analysis.
- **Scikit-learn**: For machine learning model building and evaluation.
- **SHAP**: For global interpretability of models.
- **LIME**: For local interpretability of individual predictions.
- **Pyngrok**: For public deployment of the dashboard.

---

## How to Run

### Prerequisites
1. Ensure Python 3.8 or above is installed.
2. Install the required libraries from `requirements.txt`.

```bash
pip install -r requirements.txt
