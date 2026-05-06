Neural Network Analysis - Customer Churn

Overview

This project builds a neural network model to predict customer churn using a structured dataset.

Dataset

The dataset contains customer information such as usage, plan type, and payment method.  
The target variable is 'churn', indicating whether a customer leaves the service.

Steps Performed

1. Data exploration and understanding
2. Data preprocessing (encoding, scaling, splitting)
3. Neural network model building
4. Model training and evaluation
5. Hyperparameter experiments
6. Handling class imbalance using class weights

Model Performance

The initial model achieved high accuracy but failed to detect churn cases due to class imbalance.  
After applying class weights, the model improved its ability to identify churn customers.

Key Learnings

- Accuracy is not reliable for imbalanced datasets
- Confusion matrix provides better insight
- Neural networks require proper preprocessing
- Handling imbalance improves real-world performance

Technologies Used

- Python
- Pandas
- Scikit-learn
- TensorFlow / Keras
