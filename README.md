# Time-Series-Analysis-on-Hourly-Electricity-Consumption

This project focuses on analyzing hourly electricity consumption data using time series analysis techniques. The goal is to make accurate predictions and evaluate forecast performance.

## Preprocessing
1. **Dataset Splitting:** The dataset is divided into training and testing subsets to facilitate model training and evaluation.
2. **Formatting for Prophet:** Data preprocessing involves formatting the dataset into the required input format for Facebook's Prophet forecasting model.

## Model Training and Prediction
- The training data is fitted onto the Prophet model to capture underlying patterns and seasonality.
- Predictions are made on the test data using the trained model.

## Evaluation
- **Comparison with Actuals:** The forecasted values are compared with the actual consumption data to assess the accuracy of the predictions.
- **Error Calculation:** Mean Squared Error (MSE) and Mean Absolute Error (MAE) are calculated to quantify the discrepancy between predicted and actual values.

## Incorporating Holidays
- A similar process is repeated, taking into account the effects of holidays on electricity consumption patterns.
- The model is trained and evaluated with holiday data to improve forecast accuracy.

### Repository Structure
- **`dataset/`:** Contains the raw dataset.
- **`notebooks/`:** Jupyter notebooks documenting the data analysis, model training, and evaluation processes.
- **`README.md`:** Overview of the project.

## Usage
1. Clone the repository: `git clone https://github.com/prnvpwr2612/Time-Series-Analysis-on-Hourly-Electricity-Consumption`
2. Navigate to the project directory.
3. Run the provided scripts or notebooks to preprocess the data, train the model, make predictions, and evaluate forecast performance.

## Dependencies
- Python 3.x
- Jupyter Notebook
- Pandas
- Numpy
- Prophet
- Seaborn
- Matplotlib
- Scikit-learn

## Contributors
- [Pranav Pawar](https://github.com/prnvpwr2612)

---
