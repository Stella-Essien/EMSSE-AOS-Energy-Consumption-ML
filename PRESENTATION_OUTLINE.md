Household Energy Consumption Prediction Using Machine Learning

1. Introduction

Household energy consumption is an important area of energy management. Predicting energy consumption can help us understand usage patterns and support better energy-planning decisions. Machine learning provides techniques for identifying relationships in data and generating predictions.

2. Project Aim

The aim of this project is to develop and compare machine learning regression models for predicting household appliance energy consumption using the UCI Appliances Energy Prediction dataset.

3. Dataset

The project uses the UCI Appliances Energy Prediction dataset. The data was explored and prepared before model development.

The preparation workflow included:

- Exploring the dataset.
- Separating input features from the target variable.
- Splitting the data into training and testing sets in chronological order.

4. Methodology

Two regression models were trained and evaluated:

1. Linear Regression: A regression algorithm that models a linear relationship between input features and a target variable.
2. Decision Tree Regression: A model that learns decision rules from data to generate predictions.

The models were trained using the training data, and their predictions were evaluated on the test data.

5. Evaluation Metrics

The models were evaluated using three metrics:

- Mean Absolute Error (MAE): Measures the average absolute difference between actual and predicted values. Lower values are better.
- Root Mean Squared Error (RMSE): Measures prediction error while penalizing larger errors more heavily. Lower values are better.
- Coefficient of Determination (R²): Measures performance relative to a mean-based baseline. Higher values are generally better; a negative value indicates performance worse than that baseline.

6. Results

Metric| Linear Regression| Decision Tree
MAE| 52.015| 155.845
RMSE| 86.730| 211.575
R²| 0.092| -4.401

The error metrics are reported in Wh per 10 minutes for MAE and RMSE.

7. Discussion

Linear Regression performed better than Decision Tree Regression on the test set because it achieved lower MAE and RMSE values and a higher R² score.

However, the Linear Regression model's R² of 0.092 indicates limited predictive performance. The Decision Tree model's negative R² indicates that it performed worse than a baseline that predicts the mean of the test targets.

These findings show that additional model development and evaluation are needed.

8. Limitations and Future Work

The project evaluated only two regression algorithms, and neither achieved strong predictive performance.

Future work could include:

- Testing additional algorithms, such as Random Forest Regression and Gradient Boosting.
- Improving feature selection and feature engineering.
- Tuning model hyperparameters.
- Using appropriate time-aware validation methods.
- Investigating prediction errors and testing improvements on unseen data.

9. Conclusion

This project demonstrates a practical application of machine learning to household energy-consumption prediction. Linear Regression performed better than Decision Tree Regression in this experiment, but its predictive performance remains limited. Further research is needed to improve accuracy before relying on the models for real-world energy-management decisions.
