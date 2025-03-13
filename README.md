📊 Sales Forecasting using Machine Learning

📝 Project Overview
This project focuses on forecasting daily sales for various product families across different stores . The goal is to analyze historical sales data and external factors (holidays, oil prices, promotions) to build accurate time series forecasting models.

📂 Dataset
(link: https://drive.google.com/drive/folders/1yFdxmfq1qldBYQzJMmKZb88O9fb4Rvg-?usp=drive_link)
The dataset consists of multiple files:
train.csv - Historical sales data.
test.csv - Test set for prediction.
stores.csv - Store metadata.
oil.csv - Daily oil prices.
holidays_events.csv - Holidays and special events

🔍 Key Steps:
📌 1. Data Processing & Feature Engineering
Data Cleaning: Handling missing values, merging datasets, and formatting dates.
Feature Engineering: Creating time-based features, rolling statistics, and event-based indicators.
Exploratory Data Analysis (EDA): Sales trends, correlation analysis, and anomaly detection.

🤖 2. Model Training & Evaluation
Implemented various forecasting models:
Naïve Baseline
ARIMA (Traditional time series model)
Random Forest Regressor (Tree-based approach)
XGBoost / LightGBM (Gradient boosting)
LSTM Neural Networks (Deep learning)
Prophet (Bonus) for seasonality analysis
Evaluated models using RMSE, MAPE, R² Score, and visual comparisons of actual vs. predicted sales.

📊 3. Insights & Business Recommendations
Impact of external factors on sales trends
Model performance comparison
Strategic recommendations for better demand forecasting

🛠️ Tech Stack:
Python, Pandas, NumPy, Matplotlib, Seaborn
Scikit-Learn, XGBoost, Statsmodels, TensorFlow/Keras
Jupyter Notebook for documentation

🚀 How to Run:
* Download the dataset and notebook.
* Run the Jupyter Notebook to explore data and train models.
