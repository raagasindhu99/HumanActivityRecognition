📋 Project Overview

This project focuses on predicting human activities (e.g., walking, sitting, standing, laying) by analyzing time-series data collected from smartphone sensors. The data, sourced from the UCI Machine Learning Repository, includes gyroscopic and accelerometric readings from 30 volunteers performing six activities. The objective is to classify activities accurately using predictive models to demonstrate the potential of sensor-based human activity recognition.

🚀 Use Case

Real-Time Activity Prediction
Human activity recognition has applications in fitness tracking, healthcare monitoring, and human-computer interaction. This project demonstrates:

Classifying activities using smartphone sensor data for better user insights.
Developing robust models to enable accurate, real-time activity predictions for various use cases.

📊 Data Description

Source: UCI Machine Learning Repository Dataset Link
Observations: 10,299 instances with 561 features each (accelerometer and gyroscope readings along XYZ axes).
Target Labels: Six activities - WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING.
Split: 70% training, 30% testing.

🛠️ Methods

Three predictive models were implemented and evaluated:

1. Gaussian Naive Bayes
Strengths: Handles high-dimensional data efficiently, providing a strong baseline.
Performance:
Accuracy: 80.18%
Macro Precision: 80.89%
Macro Recall: 79.60%
Macro F1 Score: 79.74%
2. Softmax Regression
Strengths: Effective for multi-class classification, provides probability scores for each class.
Performance:
Accuracy: 94.27%
Macro Precision: 94.25%
Macro Recall: 94.21%
Macro F1 Score: 94.22%
3. Neural Networks
Strengths: Learns complex patterns and excels in high-dimensional data with feature extraction.
Performance:
Accuracy: 95.32%
Precision: 95.30%
Recall: 95.25%
F1 Score: 95.26%
Confusion Matrix: Demonstrates high classification accuracy across all activity classes.

📈 Key Insights

Neural Networks: Outperformed other models with the highest accuracy and F1 score.
Softmax Regression: Balanced performance and cost-effectiveness, suitable for mid-complexity problems.
Gaussian Naive Bayes: Provided a quick and efficient baseline but lagged in precision and recall.

📊 Cost Analysis

Model	Total Cost	Explanation
Gaussian Naive Bayes	$29,200	Low complexity but higher cost due to reduced precision.
Softmax Regression	$8,450	Balance between cost and accuracy for multi-class problems.
Neural Networks	$7,650	Higher computational cost justified by exceptional accuracy.

🛠️ Tools Used

Python: Data cleaning, standardization, exploratory data analysis, and model building.
Pandas, NumPy, Matplotlib: Exploratory data analysis and data visualization.
Scikit-Learn: Model training and evaluation.
Dimensionality Reduction: PCA for reducing features to principal components.

📝 How to Run the Project

Data Preprocessing:
Load and clean data, ensuring no missing values.
Standardize features for consistent scaling.
Feature Engineering:
Apply PCA to reduce dimensionality and visualize patterns.
Model Training:
Train Gaussian Naive Bayes, Softmax Regression, and Neural Network models.
Evaluation:
Analyze performance metrics (accuracy, precision, recall, F1-score).
Visualize results using confusion matrices and performance plots.

📌 Future Improvements

Real-Time Predictions: Deploy models for live activity tracking.
Advanced Models: Experiment with recurrent neural networks for time-series data.
Expanded Applications: Adapt the framework for fitness, rehabilitation, or elderly care systems.

👤 Authors

Raaga Sindhu Mangalagiri
