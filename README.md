# Task-5
Decision Trees and Random Forests — Heart Disease Dataset.
This project focuses on applying tree-based machine learning models for both classification and regression using the Heart Disease dataset from Kaggle. The objective was to explore the interpretability, performance, and overfitting behavior of decision trees and ensemble methods like random forests.

The task began with training a Decision Tree Classifier on the dataset, followed by visualizing the tree structure to understand how decisions are made based on feature splits. We then conducted an overfitting analysis by varying the tree depth and plotting the training and testing accuracy to determine the optimal complexity of the model. A Random Forest Classifier was then trained and evaluated to compare its performance against the single decision tree. The random forest outperformed the decision tree in terms of accuracy and generalization, with cross-validation used to validate the stability of the results.

Feature importance analysis was conducted using the feature_importances_ attribute of the random forest, helping to identify the most predictive variables in diagnosing heart disease. Bar plots were generated for better visualization and interpretation.

In the regression section of the task, the target variable thalach (maximum heart rate achieved) was predicted using both Decision Tree Regressor and Random Forest Regressor. Model evaluation was carried out using Mean Squared Error (MSE) and R² Score, and prediction results were visualized to understand the performance differences between the two regressors.

This task successfully demonstrates the end-to-end application of decision tree algorithms in both classification and regression settings. The models were evaluated with proper cross-validation, and insights from feature importance and overfitting analysis were drawn, fulfilling all objectives outlined for Task 5.


