# EMSSE-AOS-Energy-Consumption-ML
Machine learning project for household appliance energy consumption prediction using Linear Regression and Decision Tree Regression.
EMSSE AOS Energy Consumption Prediction Using Machine Learning

Project Overview

This project applies machine learning regression techniques to predict household appliance energy consumption using the UCI Appliances Energy Prediction dataset.

Objectives

- Explore and analyze energy-consumption data.
- Train a Linear Regression model.
- Train a Decision Tree Regression model.
- Evaluate and compare model performance.

Models Evaluated

1. Linear Regression
2. Decision Tree Regression

Evaluation Metrics

The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- Coefficient of Determination (R²)

Results

Linear Regression

- MAE: 52.015 Wh per 10 minutes
- RMSE: 86.730 Wh per 10 minutes
- R²: 0.092

Decision Tree Regression

- MAE: 155.845 Wh per 10 minutes
- RMSE: 211.575 Wh per 10 minutes
- R²: -4.401

Linear Regression performed better than the Decision Tree model on the test set. However, the results indicate that predictive performance could be improved.

Project Files

- The Google Colab notebook containing the code and analysis.
- "linear_regression_evaluation.csv"
- "decision_tree_evaluation.csv"
- "final_model_comparison.csv"

Future Improvements

Future work could investigate feature engineering, hyperparameter tuning, and additional regression algorithms to improve predictive accuracy.

Conclusion

This project demonstrates the application of machine learning to household energy-consumption prediction and provides a foundation for further research into data-driven energy management.
Project Limitations

1. Limited predictive performance: The Linear Regression model achieved an R² of 0.092, indicating that it explains only a small proportion of the variation in the target values on the test set.
2. Poor Decision Tree performance: The Decision Tree model achieved a negative R² of -4.401, meaning it performed worse than a baseline that predicts the mean of the test targets.
3. Limited model selection: Only two regression algorithms were evaluated.
4. Potential for improvement: Feature engineering, hyperparameter tuning, and testing other regression models may improve predictive accuracy.
5. Generalization: The models should be tested further before being relied on for real-world energy-management decisions.

Recommendations for Future Research

1. Evaluate additional algorithms: Test Random Forest Regression, Gradient Boosting, and other suitable regression models.
2. Improve feature selection: Investigate which input variables contribute most to energy-consumption predictions.
3. Tune model parameters: Use appropriate hyperparameter optimization methods to improve model performance.
4. Use robust validation: Apply time-aware validation methods where appropriate to assess performance on future observations.
5. Improve predictive accuracy: Investigate why the current models have low or negative R² scores and compare improvements using MAE, RMSE, and R².
6. Explore practical applications: Once validated, investigate how accurate predictions could support household energy monitoring and energy-management decisions.

