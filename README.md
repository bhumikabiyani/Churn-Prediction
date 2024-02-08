# Churn-Prediction
# Logistic Regression

This is a simple implementation of Logistic Regression using Python and the scikit-learn library. Logistic Regression is a classification algorithm commonly used for binary classification problems.

## Overview

The provided code demonstrates the use of Logistic Regression on a dataset named "Social_Network_Ads.csv". The dataset contains information about users, including their age, estimated salary, and whether they purchased a product (target variable).

## Requirements

Make sure you have the following libraries installed before running the code:

```bash
pip install numpy matplotlib pandas scikit-learn
```

## Code Structure

1. **Importing Libraries:** Import necessary libraries - NumPy for numerical operations, Matplotlib for plotting, and Pandas for handling datasets.

2. **Importing Dataset:** Load the dataset using Pandas, where `X` contains features (age and estimated salary), and `y` contains the target variable (purchase status).

3. **Splitting the Dataset:** Split the dataset into training and testing sets using the `train_test_split` function from scikit-learn.

4. **Feature Scaling:** Standardize the features using `StandardScaler` to ensure that all features contribute equally to the model.

5. **Training the Model:** Create and train the Logistic Regression model using the training set.

6. **Making Predictions:** Use the trained model to make predictions, and print the result for a new input (e.g., age=30, salary=87000).

7. **Confusion Matrix:** Evaluate the model performance using a confusion matrix and calculate the accuracy.

8. **Visualizing Results:** Plot decision boundaries and visualize the results on both the training and test sets.

## How to Use

1. Ensure the dataset file ("Social_Network_Ads.csv") is in the same directory as the notebook or script.
2. Run the code cell by cell in a Python environment (e.g., Jupyter Notebook, Google Colab).

## Note

- The provided code assumes that the dataset has a specific structure, with the last column representing the target variable.
- Customize the code according to your dataset and requirements.

Feel free to explore and modify the code to suit your needs.
