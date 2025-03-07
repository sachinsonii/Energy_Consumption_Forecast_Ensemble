# Energy Consumption Prediction using XGBoost and LSTM

This project implements a hybrid model using XGBoost and LSTM to predict energy consumption based on household power consumption data.

## Features

- **Data Preprocessing**: Handles missing values and scales input features.
- **Parallel Modeling**: Uses XGBoost for feature extraction and LSTM for sequence learning.
- **Hybrid Model**: Combines the strengths of gradient boosting and recurrent neural networks.
- **Performance Metrics**: Evaluates RMSE, MAE, and MAPE.
- **Visualization**: Plots actual vs predicted energy consumption.

## Dataset

The dataset contains time-series power consumption data with the following features:

- `global_active_power`
- `global_reactive_power`
- `voltage`
- `global_intensity`
- `sub_metering_1`
- `sub_metering_2`
- `sub_metering_3`

## Installation

### Prerequisites

Ensure you have the required dependencies installed:

```sh
pip install numpy pandas scikit-learn xgboost keras tensorflow matplotlib
```

### Clone the Repository

```sh
git clone https://github.com/sachinsonii/Energy_Consumption_Forecast_Ensemble.git
cd Energy_Consumption_Forecast_Ensemble
```

## Running the Notebook

Since this project is implemented in a Jupyter Notebook, follow these steps:

1. Install Jupyter Notebook if not already installed:
   ```sh
   pip install notebook
   ```
2. Open the notebook:
   ```sh
   jupyter notebook energy_prediction.ipynb
   ```
3. Run all the cells in order to train the model and make predictions.

## Model Architecture

1. **XGBoost**: Learns feature representations from input data.
2. **LSTM**: Processes sequential energy data.
3. **Output**: Predicts energy consumption values.

## Performance Metrics

- **Root Mean Squared Error (RMSE)**
- **Mean Absolute Error (MAE)**
- **Mean Absolute Percentage Error (MAPE)**

## Visualization

The model generates plots comparing actual vs predicted energy consumption over time.

## Future Improvements

- Optimize hyperparameters using GridSearchCV.
- Implement real-time prediction capabilities.
- Extend model to predict future timestamps.

## License

This project is licensed under the MIT License.

