# Customer-Churn-Prediction-using-Deep-Learning
This project focuses on Customer Churn Prediction using Deep Learning (Neural Networks). It aims to identify customers who are likely to stop using a service based on various factors like tenure, charges, and internet service type.
________________________________________
Project Overview
•	Dataset: The dataset contains customer demographics, service details, and payment methods.
•	Goal: Build neural network models to predict whether a customer will churn (leave) or stay.
________________________________________
Key Steps
1. Data Preprocessing
•	Handled Missing Values: TotalCharges was converted to numeric format, and missing values were replaced with 0.
•	Feature Selection: Key features like tenure, MonthlyCharges, and TotalCharges were selected.
•	Label Encoding: The target column Churn was encoded into binary values.
2. Data Visualization
•	Churn Distribution: A pie chart was plotted to show the percentage of customers who churned vs. those who stayed.
•	Internet Service Distribution: A count plot visualized different types of internet services used.
3. Model Building
Three different deep learning models were trained:
1.	Model 1: A basic neural network using only tenure as input.
2.	Model 2: Similar to Model 1 but with Dropout layers to prevent overfitting.
3.	Model 3: A multi-feature model trained on tenure, MonthlyCharges, and TotalCharges.
________________________________________
Results & Evaluation
•	Confusion Matrices: Used to analyze the classification performance.
•	Accuracy Trends: Accuracy vs. epochs plots were generated for each model to compare training progress.
________________________________________
Future Improvements
•	Include categorical features (e.g., Contract Type, Payment Method) using one-hot encoding.
•	Experiment with more complex architectures like LSTMs or Transformer-based models.
•	Use hyperparameter tuning to optimize learning rates and neuron configurations.

