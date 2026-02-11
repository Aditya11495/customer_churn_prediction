Customer Churn Prediction using ANN

 Overview

Built an Artificial Neural Network (ANN) to predict customer churn using the Bank Churn dataset. The project covers complete preprocessing, model training, evaluation, and performance visualization.

 Objective

Predict whether a customer will:

0 → Stay

1 → Exit

Tech Stack

Python • Pandas • NumPy • Scikit-learn • TensorFlow (Keras) • Matplotlib

 Model Architecture

Input Layer (11 features)

Dense (16, ReLU)

Dense (8, ReLU)

Output (1, Sigmoid)

Loss: Binary Crossentropy
Optimizer: Adam
Metric: Accuracy

Performance

 Test Accuracy: 84.25% (replace with your exact value)

Includes Confusion Matrix & Classification Report

Train vs Validation Accuracy/Loss visualization

 Workflow

Data Cleaning → Encoding → Scaling → ANN Training → Evaluation → Visualization

Dataset

Churn_Modelling.csv
Key features: Credit Score, Geography, Gender, Age, Balance, Tenure, Estimated Salary

