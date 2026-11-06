# ⚡ Electricity Load Forecasting Using Machine Learning

## 📌 Project Overview

This project investigates the application of statistical and machine learning techniques to predict electricity demand. Accurate electricity load forecasting is essential for maintaining power grid stability, optimising energy distribution, and reducing operational costs.

The research compares five forecasting models using historical electricity consumption and temperature data to identify the most effective approach for predicting electricity demand.

**Academic Dissertation | September 2024**

## 🎯 Objectives

- Analyse historical electricity consumption and temperature patterns.
- Perform exploratory data analysis and data preprocessing.
- Develop and evaluate five forecasting models.
- Compare predictive performance using Root Mean Squared Error (RMSE).
- Identify the most effective approach for electricity demand forecasting.

## 🛠️ Technologies Used

**Programming Language:** Python

**Libraries:** Pandas, NumPy, Scikit-learn, TensorFlow, Statsmodels

**Development Environment:** Google Colab

**Techniques:** Data Preprocessing, Exploratory Data Analysis, Time Series Forecasting, Regression, Ensemble Learning, Neural Networks

## 🤖 Machine Learning Models

Five models were investigated:

1. **ARIMA:** Statistical time series forecasting.
2. **Linear Regression:** Baseline regression model.
3. **Support Vector Machine (SVM):** Support vector regression for electricity demand prediction.
4. **Random Forest:** Ensemble learning using multiple decision trees.
5. **Artificial Neural Network (ANN):** Neural network with two hidden layers containing 64 neurons each.

## 📂 Dataset

The research uses historical electricity consumption and temperature data from the Global Energy Forecasting Competition dataset.

The dataset includes:

- `Load_history.csv` — Historical hourly electricity demand.
- `temperature_history.csv` — Historical temperature observations.
- `Benchmark.csv` — Benchmark forecasting data.
- `weights.csv` — Zone-specific weighting information.

**Dataset Source:** [Kaggle](https://www.kaggle.com/competitions/global-energy-forecasting-competition-2012-load-forecasting)

## 🔍 Methodology

### 1. Data Preprocessing
- Cleaned and converted numerical data.
- Handled missing values using linear interpolation.
- Prepared historical load and temperature datasets for analysis.

### 2. Exploratory Data Analysis
- Examined electricity consumption distributions.
- Investigated relationships between temperature and electricity load.
- Visualised hourly consumption patterns and temporal trends.

### 3. Model Development
- Implemented five forecasting approaches.
- Applied model-specific preprocessing and parameter tuning.
- Generated predictions for comparison with actual electricity demand.

### 4. Model Evaluation
- Evaluated model performance using RMSE.
- Compared actual and predicted electricity consumption.
- Analysed the strengths and limitations of each forecasting technique.

## 📊 Key Results

| Model | Findings |
|---|---|
| Random Forest | Best overall forecasting performance |
| Artificial Neural Network | Competitive accuracy, close to Random Forest |
| Support Vector Machine | Captured complex relationships |
| ARIMA | Limited ability to capture short-term fluctuations |
| Linear Regression | Highest RMSE among the evaluated models |

### Key Finding

**Random Forest achieved the strongest overall forecasting performance**, demonstrating the effectiveness of ensemble learning in capturing complex relationships between electricity demand and influencing variables.

Artificial Neural Networks also demonstrated promising performance, while traditional statistical methods struggled with more complex consumption patterns.

## 🌍 Practical Applications

- Electricity demand forecasting
- Smart grid optimisation
- Energy resource planning
- Power distribution management
- Operational cost reduction

## 🚀 Future Improvements

- Explore LSTM and hybrid forecasting models.
- Investigate additional weather and seasonal features.
- Improve hyperparameter optimisation.
- Develop an interactive electricity demand forecasting dashboard.

## 👨‍💻 Author

**Piyush Rane**

Aspiring Data Scientist | Python | Machine Learning

[GitHub Profile](https://github.com/ranepiyush123)

---

*Academic research completed in September 2024.*
