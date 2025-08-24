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

📦 Installation & Running Locally

1.Clone the Repo bash Copy Edit git clone https://github.com/SravyaAUCSE/TIME_SERIES_STOCK_FORECASTING.git cd TIME_SERIES_STOCK_FORECASTING

2.Install Dependencies bash Copy Edit pip install -r requirements.txt

3.Add CSV Data Dataset: https://www.kaggle.com/datasets/szrlee/stock-time-series-20050101-to-20171231?utm_source=chatgpt.com

4.Run the Streamlit App bash Copy Edit streamlit run app.py 📬 Usage Notes ✅ Handles multiple stocks: loops through all CSVs in /data folder.

📌 Usage Guide

Data Handling: Upload your own stock CSVs or use provided datasets.

EDA: Explore trends, rolling averages, and detect anomalies.

Modeling: Choose between ARIMA, SARIMA, Prophet, or LSTM.

Tuning: Adjust hyperparameters manually or run automated tuning.

Forecasting: Generate predictions for future stock values.

Comparison: Evaluate models side by side using RMSE, MAE, and MAPE.

Save & Reuse: Store trained models in /models for later use.

🛠 Tools & Technologies

Languages: Python

Frameworks: Streamlit, TensorFlow/Keras, Statsmodels, FbProphet

Libraries: Pandas, NumPy, Scikit-learn, Plotly, Matplotlib, Seaborn

Deployment: Streamlit app (local or cloud hosting)

🤝 Contributing

Fork the repository

Create a feature branch

Make your changes

Add tests if applicable

Submit a pull request

👤 Author : 

V HAMSA VALLI - https://github.com/Hamsavall

👥 Contributor :

JAMI SRAVYA - https://github.com/SravyaAUCSE

📄 License

This project is licensed under the MIT License

