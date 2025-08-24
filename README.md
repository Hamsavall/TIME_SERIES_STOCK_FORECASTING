# TIME_SERIES_STOCK_FORECASTING

An interactive and automated stock market forecasting dashboard built with Streamlit, integrating both classical time series models (ARIMA, SARIMA, Prophet) and deep learning (LSTM).

The project’s goal is to provide analysts and investors with a user-friendly forecasting tool that automates data preprocessing, model building, and performance evaluation for better decision-making.

🚀 Features

✅ Upload or auto-load multiple stock datasets

📊 EDA with trend visualization, rolling averages & outlier detection

🧹 Preprocessing: missing values handling, scaling, formatting

📈 Forecasting with ARIMA, SARIMA, Prophet, and LSTM

🎛️ Hyperparameter tuning (manual & automated)

📉 Model performance comparison using RMSE, MAE, and MAPE

💾 Save trained models for reuse

📊 Real-time interactive plots with Plotly

🧠 LSTM for capturing long-term dependencies

🧭 Dashboard Modules

🔍 Exploratory Data Analysis & Outlier Detection

🤖 Forecasting with Classical & Deep Learning Models

📊 Model Comparison Metrics

📊 Models Implemented
Model	Type	Framework	Key Feature
ARIMA	Traditional	statsmodels	Works on lag, trend, and moving average
SARIMA	Traditional	statsmodels	Adds seasonality
Prophet	Additive Model	fbprophet	Handles seasonality, holidays, and trends
LSTM	Deep Learning	TensorFlow/Keras	Learns sequential patterns & long-term dependencies
📊 Evaluation Metrics

RMSE – Penalizes large errors

MAE – Mean of absolute errors

MAPE – Percentage-based error measure

📁 Project Structure
<br>
TIME_SERIES_STOCK_FORECASTING/
│── app.py                # Main Streamlit application
│── data/                 # Stock CSV datasets
│── models/               # Trained models storage
│── screenshots/          # Screenshots for documentation
│── traditional_models.py # ARIMA, SARIMA, Prophet functions
│── lstm_model.py         # Deep Learning LSTM logic
│── eda_outliers.py       # EDA & outlier detection
│── comparison.py         # Model comparison and evaluation
│── utils.py              # Utility functions (scaling, metrics, etc.)
│── requirements.txt      # Required Python packages
└── README.md             # Documentation
