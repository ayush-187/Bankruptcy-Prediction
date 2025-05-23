# Bankruptcy-Prediction
Bankruptcy Prediction – Trend Trackers

This project focuses on predicting bankruptcy using a rich set of financial attributes through various machine learning models in SAS Enterprise Miner. The goal was to build an accurate and interpretable model for early identification of bankruptcy risk.

Key Steps:
	•	Data Exploration: Used StatExplore to analyze distributions and confirm no missing values.
	•	Data Transformation: Handled skewed variables through transformation based on skewness thresholds.
	•	Modeling Techniques:
	•	Decision Tree: Provided interpretable rules and a strong baseline.
	•	Gradient Boosting: Addressed residual errors through sequential learning.
	•	Polynomial Logistic Regression: Captured nonlinear trends for binary outcomes.
	•	Neural Networks (Standard & HP): Modeled complex interactions, scaled for performance.
	•	HP GLM: Tackled skewed/over-dispersed continuous variables with advanced distributions.
	•	LARS (Adaptive LASSO): Enabled variable selection to reduce overfitting.
	•	Ensemble: Combined all models for superior accuracy.

Results:
	•	Final Model AUC (ROC): 0.936
	•	Leaderboard Accuracy: 94.7%

This ensemble-based hybrid approach effectively balances accuracy, interpretability, and computational efficiency, making it suitable for real-world financial risk management.
