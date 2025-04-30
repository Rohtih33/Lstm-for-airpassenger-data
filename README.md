# LSTM Time Series Forecasting on Air Passengers Dataset

This project implements a Long Short-Term Memory (LSTM) neural network to forecast international airline passenger numbers using the classic Air Passengers dataset (1949–1960).

## 📊 Dataset

- **Source**: Monthly totals of international airline passengers from 1949 to 1960.
- **Columns**:
  - `Month`: Time period (YYYY-MM)
  - `#Passengers`: Number of passengers

Make sure the file `AirPassengers.csv` is in the same directory as the script.

## 🧠 Model

The model uses a univariate LSTM neural network to predict future values based on sequences of 12 months of historical data.

## 🛠️ Requirements

Install required packages using:

```bash
pip install pandas matplotlib scikit-learn tensorflow
```

## 🚀 Usage

1. Place `AirPassengers.csv` in the working directory.
2. Run the Python script (e.g., `python lstm_forecast.py` or in a Jupyter notebook).
3. The model will train and display a plot comparing actual vs predicted passenger numbers.

## 📈 Output

The script will:
- Normalize and sequence the data
- Train an LSTM model
- Plot actual vs predicted values for the test set

## 📁 File Structure

```
.
├── AirPassengers.csv
├── lstm_forecast.py  # Your Python script
└── README.md
```

## 🔮 Future Work

- Extend the model for multi-step forecasting
- Tune hyperparameters and experiment with deeper architectures
- Add seasonal decomposition for hybrid models

## 📘 References

- [Air Passengers dataset on Kaggle](https://www.kaggle.com/datasets)
- TensorFlow and Keras documentation
