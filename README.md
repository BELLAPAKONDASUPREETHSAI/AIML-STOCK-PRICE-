# AIML-STOCK-PRICE-
STOCK PRICE USING LSTM

STOCK PRICE TREND PREDICTION WITH List

INTRODUCTION:

Stock price prediction is a critical task in fnancial analysis, leveraging historical data to forecast future price movements. This project aims to predict stock price trends using Long Short-Term Memory (LSTM) networks,
 a type of recurrent neural network well-suited for time-series data. By integrating technical indicators such as Moving Average (MA) and Relative Strength Index (RSI), themodel
enhances its ability to capture marketpatterns. The project employs Python-based tools 
and culminates in a deployable dashboard for visualizing predictions, offering insightsfor 
investors and analysts. The deliverables include a Jupyter notebook, trained model
weights, visualizations, and an optional Streamlit Dashboard

ABSTRACT: 

This project develops a predictive model for stock price trends using LSTM networks. Historical stock data is fetched via the Yahoo Finance API, preprocessed, and enriched with technical indicators (Moving Average and RSI). The LSTM model is built and trained using Keras, with data normalized to ensure robust performance. The model is validated against actual stock prices, and results are visualized using Matplotlib. An optional Streamlit dashboard enables interactive exploration of predictions. The project demonstrates the potential of deep learning in fnancial 
forecasting, achieving reliable predictions while highlighting challenges such as market volatility.

TOOLS :

1.Python: Core programming language for data processing and model development.     

2.yfnance: API to fetch historical stock price data from Yahoo Finance.

3.Pandas: Data manipulation and preprocessing, including handling time-series data.

4.Keras: Framework for building and training the LSTM model.

5.Matplotlib: Visualization of actual vs. predicted stock prices and technical indicators.

6.NumPy: Numerical operations for data normalization and array handling.

7.Scikit-learn: Data preprocessing, including scaling and splitting datasets.

8.Streamlit: Optional tool for deploying an interactive dashboard.

9.Jupyter Notebook: Environment for code development, testing, and documentation.

STEPS INVOLVED IN BUILDING THE PROJECT:

1.Data Acquisition:
Use the yfnance library to fetch historical stock price data (e.g., daily closing prices) for a chosen 
stock ticker.

2.Data processing:
Store data in a Pandas DataFrame for further processing.

3.Compute technical indicators: Simple Moving Average (SMA) and Relative Strength Index (RSI).
(i)Normalize price data and indicators using Min-Max scaling to ensure consistent input ranges for 
the LSTM model.
(ii)Create sequences of historical data (e.g., 60-day windows) as input features for time-series 
prediction.
(iii)Split data into training (e.g., 80%) and testing (e.g., 20%) sets.

4.Model Development:
(i)Build an LSTM model using Keras with multiple layers to capture temporal dependencies.
(ii)Confgure the model with appropriate input shapes based on sequence length and features (e.g., 
closing price, SMA, RSI).
(iii)Use Mean Squared Error (MSE) as the loss function and Adam optimizer for training.

5.Model Training and Validation:
(i)Train the LSTM model on the training dataset for a specifed number of epochs.

(ii)Validate performance on the test set, evaluating metrics such as Root Mean Squared Error 
(RMSE).

(iii)Save model weights for future use.

6.Prediction and Visualization:

(i)Generate predictions on the test set and inverse-transform normalized data to obtain actual price 
values.

(ii)Plot actual vs. predicted prices using Matplotlib, including technical indicators for context.

7.Optional Dashboard Deployment:

(i)Develop a Streamlit dashboard to allow users to select stock tickers, view predictions, and 
explore historical trends interactively.

(ii)Deploy the dashboard via Streamlit Cloud or a similar platform, providing a shareable link.

8.Deliverables Preparation:

(i)Document the workfow in a Jupyter notebook, including code, comments, and visualizations.

(ii)Export model weights and generate graphs for predictions and indicators.

(iii)Provide a link to the Streamlit dashboard (if implemented).

CONCLUSION:

This project successfully demonstrates the application of LSTM networks for stock price trend prediction, enhanced by technical indicators like Moving Average and RSI. The model, built with Keras and supported by robust data preprocessing, achieves reasonable accuracy in forecasting 
short-term price movements. Visualizations provide clear insights into model performance, while the optional Streamlit dashboard offers an interactive user experience. Despite challenges such as market unpredictability and data noise, the project highlights the potential of deep learning in fnancial analysis. Future improvements could include incorporating additional features (e.g., 
volume, sentiment data) or exploring advanced models like Transformer networks.