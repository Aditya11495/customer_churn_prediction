Customer Churn Prediction using AN
 **Project Overview**

This project predicts whether a customer will leave (churn) or stay in a bank using an Artificial Neural Network (ANN).

The model is built using TensorFlow (Keras) and Scikit-learn, and includes full preprocessing, feature scaling, training, evaluation, and performance visualization.

**Problem Statement**

Customer churn prediction helps businesses identify customers who are likely to leave, allowing them to take proactive actions to retain them.

This is a binary classification problem:

0 → Customer stays

1 → Customer exits

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Scikit-learn

TensorFlow / Keras

 **Project Workflow**

Data Loading

Data Cleaning

Categorical Encoding

Train-Test Split

Feature Scaling

ANN Model Building

Model Training

Performance Evaluation

Accuracy & Loss Visualization

**Model Architecture**

Input Layer (11 features)

Dense Layer (16 neurons, ReLU)

Dense Layer (8 neurons, ReLU)

Output Layer (1 neuron, Sigmoid)

Loss Function: Binary Crossentropy
Optimizer: Adam
Metric: Accuracy

**Model Performance**

Achieved approximately 82%–86% accuracy

Proper train vs validation monitoring

Confusion matrix and classification report included

**Visualizations

The project includes:

Training vs Validation Accuracy Curve

Training vs Validation Loss Curve

Dataset used: Churn_Modelling.csv

Features include:

Credit Score

Geography

Gender

Age

Balance

Tenure

Estimated Salary
