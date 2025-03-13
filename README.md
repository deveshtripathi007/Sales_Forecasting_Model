📊 Sales Forecasting using Machine Learning

📝 Project Overview : <br>
This project focuses on forecasting daily sales for various product families across different stores . The goal is to analyze historical sales data and external factors (holidays, oil prices, promotions) to build accurate time series forecasting models.

📂 Dataset : <br>
(link: https://drive.google.com/drive/folders/1yFdxmfq1qldBYQzJMmKZb88O9fb4Rvg-?usp=drive_link) <br>
The dataset consists of multiple files: <br>
train.csv - Historical sales data <br>
test.csv - Test set for prediction <br>
stores.csv - Store metadata <br>
oil.csv - Daily oil prices <br>
holidays_events.csv - Holidays and special events

🔍 Key Steps: <br>
* 1. Data Processing & Feature Engineering
Data Cleaning: Handling missing values, merging datasets, and formatting dates.
Feature Engineering: Creating time-based features, rolling statistics, and event-based indicators.
Exploratory Data Analysis (EDA): Sales trends, correlation analysis, and anomaly detection.

* 2. Model Training & Evaluation
Implemented various forecasting models: <br>
Naïve Baseline <br>
ARIMA (Traditional time series model) <br>
Random Forest Regressor (Tree-based approach) <br>
XGBoost / LightGBM (Gradient boosting) <br>
LSTM Neural Networks (Deep learning) <br>
Prophet (Bonus) for seasonality analysis <br>
Evaluated models using RMSE, MAPE, R² Score, and visual comparisons of actual vs. predicted sales. <br>

* 3. Insights & Business Recommendations <br>
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
