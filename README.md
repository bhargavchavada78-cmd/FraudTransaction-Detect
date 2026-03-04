💳 Credit Card Fraud Detection – Machine Learning Project

📌 Project Overview

This project focuses on detecting fraudulent transactions using Machine Learning techniques.
The model is trained and evaluated using separate training and testing datasets:

fraudTrain.csv

fraudTest.csv

Multiple classification algorithms are implemented and compared to determine the best-performing model for fraud detection.

🎯 Objectives

Perform feature scaling

Train multiple machine learning models

Evaluate and compare model performance

Identify the most accurate fraud detection model


🗂️ Project Structure

├── task-2-code.ipynb      # Main Jupyter Notebook
├── fraudTrain.csv         # Training dataset
├── fraudTest.csv          # Testing dataset
├── README.md              # Project documentation

🛠️ Technologies & Libraries Used

Python 3.x

Jupyter Notebook

NumPy

Pandas

Scikit-learn

Machine Learning Models Implemented:

Logistic Regression

K-Nearest Neighbors (KNN)

Decision Tree Classifier

Random Forest Classifier

Linear Regression (for comparison)

Evaluation Metrics:

Accuracy Score

Confusion Matrix

Classification Report


⚙️ Workflow

1️⃣ Data Loading

Training and testing datasets loaded using Pandas.

2️⃣ Data Preprocessing

Feature scaling using StandardScaler

Train-test separation

3️⃣ Model Training

The following models were trained:

Logistic Regression

KNN

Decision Tree

Random Forest

4️⃣ Model Evaluation

Models were evaluated using:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

📊 Results

Multiple classification models were compared.

Ensemble methods like Random Forest typically provide better performance in fraud detection tasks.

Model comparison helps identify the most reliable algorithm for detecting fraudulent transactions.

