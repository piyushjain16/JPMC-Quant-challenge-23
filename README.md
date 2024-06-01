# Stock Price Prediction Using Random Walk Theory

## Project Overview

This project aims to predict stock prices by leveraging the Random Walk Theory and employing ensemble machine learning techniques. By focusing on predicting price changes rather than absolute prices, we address issues like non-stationarity in financial data and validate the Random Walk Theory. Our approach combines Linear Regression and Random Forest models to enhance prediction accuracy and interpretability.

## Key Features

1. **Explainable ML Model:**
   - Developed an ensemble model combining Linear Regression and Random Forest techniques.
   - Achieved a significant RMSE improvement from a baseline of 39.8 to 2.1.

2. **Model Explainability:**
   - Utilized financial metrics to create a transparent, white-box model.
   - Enhanced the interpretability of predictions by exploiting financial instruments.

3. **Innovative Forecasting Approach:**
   - Predicted price changes instead of absolute prices, effectively handling non-stationarity.
   - Validated the Random Walk Theory through this novel method.

## Tech Stack

- **Programming Languages:** Python
- **Libraries and Frameworks:**
  - Scikit-learn
  - Pandas
  - NumPy

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/piyushjain16/JPMC-Quant-challenge-23.git
   cd stock-price-prediction
   ```

2. Create and activate a virtual environment:
   ```bash
   python3 -m venv env
   source env/bin/activate   # On Windows use `env\Scripts\activate`
   ```

## Usage

1. **Data Preparation:**
   - Ensure you have the necessary historical stock market data in the appropriate format.
   - Preprocess the data using the provided scripts in the `data_preprocessing` directory.

2. **Model Training:**
   - Run the training script to build the ensemble model:
     ```bash
     python code_final_round.py
     ```

3. **Prediction:**
   - Prediction available in './Submission.csv'

## Results

- The ensemble model significantly reduced the RMSE from a baseline of 39.8 to 2.1.
- The model's predictions are explainable, leveraging financial metrics for better interpretability.

## Contributing

We welcome contributions to improve this project. Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
