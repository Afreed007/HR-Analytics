HR Analytics: Predicting Employee Churn
This project focuses on analyzing and predicting employee churn using the provided HR dataset. The goal is to identify the factors that contribute to employees leaving the company and build a model to predict which employees are likely to churn.

Project Steps:
Data Loading and Exploration:

Loaded the training and testing datasets.
Explored the data types and identified missing values.
Analyzed the correlation between numerical features and the target variable.
Visualized the distribution of categorical features with respect to the target variable to understand their relationship with churn.
Data Preprocessing and Treatment:

Handled categorical features by converting them to a suitable format using Label Encoding.
Addressed the imbalance in the target variable using the SMOTE (Synthetic Minority Over-sampling Technique) algorithm to create a more balanced dataset for model training.
Machine Learning Modeling:

Implemented and evaluated several classification models (Logistic Regression, K-Nearest Neighbors, Decision Tree) on the SMOTE-augmented training data.
Used confusion matrices and accuracy scores to assess the performance of each model.
Feature Importance:

Analyzed the importance of different features in predicting churn using the Decision Tree model to identify the most influential factors.
Key Findings:
The dataset exhibits a significant class imbalance, with a much larger number of employees who did not churn compared to those who did. SMOTE was used to address this.
(Include specific insights from your data exploration and feature importance analysis here. For example, mention which features were most correlated with the target or which features the Decision Tree model found most important.)
(Summarize the performance of the models you trained and mention which model performed best, if applicable.)
