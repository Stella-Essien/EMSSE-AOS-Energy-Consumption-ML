Household Energy Consumption Prediction Using Machine Learning

Project Overview

This project applies machine learning regression techniques to predict household appliance energy consumption using the UCI Appliances Energy Prediction dataset.

Objectives

- Explore and analyze energy-consumption data.
- Train a Linear Regression model.
- Train a Decision Tree Regression model.
- Evaluate and compare model performance.

Dataset

The project uses the UCI Appliances Energy Prediction dataset. The data was explored and prepared before training and evaluating the models.

Methodology

The workflow included data exploration, feature and target separation, a chronological train-test split, model training, prediction, evaluation, and visualization.

The models evaluated were:

1. Linear Regression
2. Decision Tree Regression

Evaluation Metrics

- Mean Absolute Error (MAE): Measures the average absolute difference between actual and predicted values.
- Root Mean Squared Error (RMSE): Measures prediction error while penalizing larger errors more heavily.
- R²: Measures model performance relative to a mean-based baseline.

Results

Metric| Linear Regression| Decision Tree
MAE| 52.015| 155.845
RMSE| 86.730| 211.575
R²| 0.092| -4.401

The Linear Regression model performed better than the Decision Tree model on the test set. However, its low R² indicates limited predictive performance.

Project Limitations

The Linear Regression model explains only a small proportion of the variation in the test targets. The Decision Tree model performed worse than a baseline that predicts the mean of the test targets. Only two regression algorithms were evaluated.

Recommendations for Future Research

- Evaluate additional algorithms, such as Random Forest and Gradient Boosting.
- Investigate feature selection and feature engineering.
- Tune model hyperparameters.
- Use appropriate time-aware validation methods.
- Investigate ways to improve predictive accuracy before real-world deployment.

Project Files

- "EMSSE_AOS_Energy_Consumption_ML.ipynb" — project notebook.
- "linear_regression_evaluation.csv" — Linear Regression metrics.
- "decision_tree_evaluation.csv" — Decision Tree metrics.
- "final_model_comparison.csv" — model comparison results.

Conclusion

This project demonstrates the application of machine learning to household energy-consumption prediction. Linear Regression performed better than Decision Tree Regression in this experiment, but further work is needed to improve predictive accuracy.
