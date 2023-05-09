# INSAID - Fraud Detection Model with Decision Tree

This repository contains code for a fraud detection model using a decision tree algorithm. The model is trained on a dataset of transactions and uses features such as transaction amount, location, and time to predict whether a transaction is fraudulent or not.

## Installation

To use this code, you will need Python 3.x and the following packages:
* pandas
* scikit-learn

You can install these packages using pip:

```
pip install pandas scikit-learn
```

## Usage

The main file of this project is `decision_tree_fraud_detection.py`. This file contains the code to train the decision tree model on the provided dataset and make predictions on new data.

To run the code, simply execute the following command:

```
python decision_tree_fraud_detection.py
```

This will train the model and print out the accuracy score on the training set and the test set. It will also save the trained model to a file called `decision_tree_fraud_detection.pkl`.

To make predictions on new data using the trained model, you can use the `predict` function in `decision_tree_fraud_detection.py`. The function takes a pandas DataFrame as input, where each row represents a transaction and the columns are the features used in the model.

## Dataset

The dataset used in this project is included in the repository as `Fraud.csv`. This dataset contains information about transactions, including the transaction amount, location, time, and whether the transaction is fraudulent or not.

The dataset is split into a training set and a test set in a 75/25 ratio. The training set is used to train the decision tree model, while the test set is used to evaluate the performance of the model.

