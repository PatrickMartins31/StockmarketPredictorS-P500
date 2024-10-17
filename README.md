# Stockmarket Predictor for S&P500

This project implements a stock market prediction model using historical data from the S&P 500 index. It employs a Random Forest classifier to predict whether the market will close higher the following day based on various features from historical price data.

## Inspiration

This project was inspired by a YouTube tutorial on stock market prediction using machine learning. I began with the tutorial's code as a foundational learning tool and am currently working on enhancing its functionality and prediction accuracy.

## Current Work

### Improvements in Progress

- **Data Retrieval**: Using `yfinance` to fetch historical data for the S&P 500 index, saving it as a CSV for future use.
- **Feature Engineering**: 
  - Adding a target variable to indicate whether the market closes higher the next day.
  - Introducing rolling averages and trend features to capture market behavior over various horizons (2, 5, 60, 250, 1000 days).
- **Model Optimization**: Exploring improvements to the Random Forest model's parameters to enhance prediction performance.
- **Prediction Logic**: Updating the prediction function to utilize predicted probabilities for more flexible classification thresholds.
- **Backtesting**: Developing a backtesting function to evaluate model performance across different segments of historical data.

## Results

The model’s predictions can be visualized alongside actual market movements, allowing for an analysis of its performance. The `precision_score` metric provides insight into the model's accuracy.

## Acknowledgements

- **Original Tutorial**: Predict The Stock Market With Machine Learning And Python by Dataquest for providing foundational concepts and initial code that inspired this project.
- **Dependencies**: This project relies on the following Python libraries:
  - `yfinance`
  - `pandas`
  - `scikit-learn`
