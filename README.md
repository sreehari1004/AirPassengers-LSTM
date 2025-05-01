#  Air Passengers Time Series Forecasting using LSTM

This project implements a time series forecasting model using Long Short-Term Memory (LSTM) neural networks. The goal is to predict monthly totals of international airline passengers from 1949 to 1960.

##  Dataset
- File: `AirPassengers.csv`
- Contains monthly airline passenger totals from 1949 to 1960.

##  Tech Stack
- Python
- TensorFlow / Keras
- NumPy, Pandas, Matplotlib
- Scikit-learn

##  How It Works
1. Load and normalize the dataset
2. Create time-series sequences using a sliding window
3. Train an LSTM model on the sequences
4. Predict future passenger counts
5. Visualize the results

##  Result
The model learns seasonal patterns in the data and predicts passenger trends with reasonable accuracy. See plot output for actual vs predicted performance.

##  Run it yourself
```bash
pip install numpy pandas matplotlib scikit-learn tensorflow
python lstm_air_passengers.py
