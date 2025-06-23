# Bank-Customer-Churn-Analysis-
# 🤖 Artificial Neural Network for Customer Churn Prediction

This project uses an Artificial Neural Network (ANN) built with TensorFlow/Keras to predict whether a customer will leave a bank (churn) based on structured input data. The model is trained on a real-world dataset and includes preprocessing, model training, evaluation, and prediction for new customer inputs.

---

##  Dataset Overview

The model uses the **Churn_Modelling.csv** dataset, which includes features like:

- Customer Credit Score, Age, Gender, Tenure, Balance, etc.
- Categorical columns like Geography and Gender are encoded.
- The target variable is whether the customer exited (1) or stayed (0).

---

##  Tech Stack

- **Python 3**
- **TensorFlow / Keras**
- **NumPy / Pandas**
- **Scikit-learn** (for preprocessing and evaluation)

---

##  Workflow Summary

1. **Data Preprocessing**
   - Label encoding for `Gender`
   - One-hot encoding for `Geography`
   - Feature scaling using `StandardScaler`
   - Train-test split (80/20)

2. **Model Architecture**
   - Input layer and two hidden layers with ReLU activation
   - Output layer with sigmoid activation (binary classification)
   - Optimizer: Adam
   - Loss Function: Binary Crossentropy
   - Trained over 100 epochs with batch size 32

3. **Evaluation**
   - Accuracy score and confusion matrix on test set
   - Single prediction using custom input

---

