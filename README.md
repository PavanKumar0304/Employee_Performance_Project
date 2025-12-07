# Employee_Performance_Project
A data-driven Employee Performance &amp; Productivity Analysis using Python. Includes data cleaning, EDA, ML models (Logistic Regression &amp; Decision Tree), and insights on key factors influencing employee performance. Visualizations highlight workload, salary, experience, and satisfaction impacts.

Project Overview
This project analyzes employee performance and productivity using Python.
The objective is to:
Identify key factors that drive high vs low performance
Build machine learning models to classify employee performance levels
Understand workforce productivity trends
Provide actionable HR insights for real-world decision making
The dataset includes 100,000 employee records with 20 HR and productivity-related attributes.

📚 Libraries Used & Their Purpose
1. pandas:
Data loading, cleaning, transformation Handling missing values and preparing dataset for modeling
2. numpy:
Numerical operationsSupporting ML computations
3. seaborn & matplotlib: Used to create powerful HR analytics visualizations: Performance distribution Salary variations Workload patterns Productivity correlations
4. scikit-learn:
Used for: Train-test split Data preprocessing pipelines OneHotEncoding categorical variables caling numerical features Logistic Regression & Decision Tree modeling Accuracy, F1-score, and classification report Confusion matrix & ROC Curve

🎯 Project Steps
Loaded and explored the dataset Created a target variable → High vs Low Performance Applied preprocessing pipelines (imputing, scaling, encoding) Trained 2 models: Logistic Regression Decision Tree Classifier Evaluated the models
Built HR-focused visualizations Generated insights HR teams can use

📊 Visualizations Explained
1. High vs Low Performance Distribution
Count plot showing how many employees fall into each performance group
Helps estimate workforce productivity levels
2. Monthly Salary by Department
Box plot comparing department-wise salary ranges
Helps identify compensation gaps across teams
3. Work Hours vs Performance (Colored by Overtime Hours)
Scatter plot visualizing how work hours relate to productivity
Helps understand overwork, burnout, and productivity efficiency
4. Confusion Matrix (For Model Evaluation)
Shows correct vs incorrect predictions
Helps assess classification model performance
5. Distribution of Predictions
A visual summary of how many employees were predicted as high/low performers
Useful for HR planning
6. Actual vs Predicted Comparison
Two-class comparison plot
Helps identify misclassification patterns

🧠 Key Insights From the Project
Employees with higher work hours are not always high performers
Training hours significantly influence performance
Satisfaction score strongly correlates with high performance
Overtime hours can increase performance up to a point, then reduce it
Experience (Years_At_Company) impacts productivity trends
