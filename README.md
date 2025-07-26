# StockPrice-prediction-LSTM
## **Project Overview**
This project uses Long Short-Term Memory (LSTM) networks to forecast stock prices for multiple tickers. The model is built using historical price data combined with technical indicators such as Simple Moving Average (SMA), Exponential Moving Average (EMA), Relative Strength Index (RSI), and Moving Average Convergence Divergence (MACD). The model's performance is evaluated using metrics like Mean Absolute Error (MAE) and R-squared (R²), and the predictions are visualized for easy comparison with actual values.

## **Objective**
The goal of this project is to predict future stock prices for multiple tickers, leveraging advanced machine learning techniques and time series forecasting methods. The LSTM model aims to capture the patterns in stock price data over time and provide actionable insights for financial decision-making.

## **Key Features**
- **Stock Price Prediction**: Predicts stock prices for multiple tickers using LSTM.
- **Technical Indicators**: Incorporates technical indicators like SMA, EMA, RSI, and MACD to enhance the prediction model.
- **Data Preprocessing**: Includes cleaning, feature engineering, and normalization of data.
- **Model Training**: LSTM network is trained on historical stock price data to make predictions.
- **Visualization**: The predicted vs. actual stock prices are visualized with plots, allowing for easy performance comparison.
- **Evaluation Metrics**: Utilizes MAE and R² to evaluate model accuracy and performance.

## **Technologies Used**
- **Python**  
- **TensorFlow/Keras** for deep learning model implementation.
- **pandas**, **numpy** for data manipulation and preprocessing.
- **yfinance** for fetching historical stock data.
- **scikit-learn** for data scaling and model evaluation.
- **matplotlib** and **seaborn** for data visualization.

## **Model Workflow**
1. **Data Collection**: Historical stock data is fetched from Yahoo Finance using the `yfinance` library.
2. **Feature Engineering**: Technical indicators such as SMA, EMA, RSI, and MACD are calculated and added as features to the dataset.
3. **Data Preprocessing**: The data is scaled using MinMaxScaler, and sequences are created for LSTM input.
4. **Model Architecture**: The LSTM model is built and trained using historical stock price data.
5. **Evaluation**: The model's predictions are evaluated using MAE and R², and its performance is compared to actual stock prices through visualization.
6. **Visualization**: The predictions and actual values are plotted to assess the model's performance.

## **Easy Customization**
This project is designed with flexibility in mind. 

- **Changing Tickers**: Modify the `TICKERS` list in the code to include the stock symbols you want to analyze. Simply replace the existing tickers with your desired ones.<img width="857" height="120" alt="image" src="https://github.com/user-attachments/assets/92e818a5-d453-416d-9a0d-cffc142e8bc2" />

  
- **Adjusting Forecast Length**: You can change the number of days the model predicts by adjusting the `FORECAST` variable. <img width="715" height="117" alt="image" src="https://github.com/user-attachments/assets/77a56d3c-f7bd-4d6b-9d5b-c3bfe2ceb870" />


- **Model Hyperparameters**: Adjust the learning rate, number of layers, and units in the LSTM model by changing the relevant parameters in the code. This allows for tuning the model for better performance. <img width="833" height="80" alt="image" src="https://github.com/user-attachments/assets/56e323a8-d1bd-49a3-b1ce-8ee7311d1740" />




## **Output Example**

The model outputs the following:

- **Performance Metrics**: MAE and R² for each stock ticker.
  - Example for **AAPL**:
    - Mean Absolute Error (MAE): $6.22
    - R-squared (R²): 0.72
    - <img width="521" height="110" alt="image" src="https://github.com/user-attachments/assets/3c58bb0e-ba70-4bd7-9209-d70ae0719d7d" />


- **Predicted vs Actual Graphs**: Visual comparison between predicted stock prices and actual stock prices for each ticker.

<img width="1242" height="633" alt="image" src="https://github.com/user-attachments/assets/5a7efa97-3b26-42a7-8889-c709e69960c4" />
<img width="1242" height="633" alt="image" src="https://github.com/user-attachments/assets/0728ddbb-37f3-42b5-a0ec-f3dd36a8dd5d" />



## **Contributing**

Feel free to fork this repository, open issues, or submit pull requests if you'd like to contribute to this project.

### **How to Contribute:**
1. Fork the repository to your own GitHub account.
2. Clone the repository to your local machine.
3. Make your changes or improvements.
4. Submit a pull request with a description of your changes.

