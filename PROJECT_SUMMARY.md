Project Summary: Energy Consumption Prediction Using Machine Learning

Project area: Artificial Intelligence, Machine Learning, and Data Science

Dataset: UCI Appliances Energy Prediction dataset

Objective: To develop and compare regression models for predicting household appliance energy consumption.

Models used:

- Linear Regression
- Decision Tree Regression

Evaluation results:

Metric| Linear Regression| Decision Tree
MAE| 52.015| 155.845
RMSE| 86.730| 211.575
R²| 0.092| -4.401

Key finding: Linear Regression performed better than the Decision Tree model on the test set. However, the low R² score indicates that further model improvement is necessary.

Future work: Investigate feature engineering, hyperparameter tuning, and alternative regression algorithms to improve predictive performance.

Project outcome: A documented machine-learning notebook, model evaluation files, model comparison results, and project documentation.

Limitations and Future Improvements

The current models have limited predictive performance. Linear Regression achieved an R² of 0.092, while Decision Tree Regression achieved an R² of -4.401 on the test set.

Future work should evaluate additional regression algorithms, improve feature selection, tune model parameters, and use appropriate time-aware validation methods. Further testing is necessary before applying the models to real-world energy-management decisions.

