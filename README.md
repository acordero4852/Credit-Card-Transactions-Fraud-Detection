# Credit Card Transactions Fraud Detection

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The goal is to classify transactions as fraudulent or legitimate based on various features extracted from transaction data.

## Project Overview

The project utilizes two datasets:

- `fraudTrain.csv`: Training data for building the model.
- `fraudTest.csv`: Testing data for evaluating model performance.

## Key Steps

1. **Data Loading**: The training and testing datasets are loaded into pandas DataFrames.
2. **Data Exploration**: Initial analysis of the data to understand its structure and key features.
3. **Feature Engineering**: Creating and selecting relevant features to improve model accuracy.
4. **Model Training**: Using machine learning algorithms to train a model on the training dataset.
5. **Model Evaluation**: Testing the trained model on the test dataset and evaluating its performance.
6. **Fraud Detection**: Identifying potentially fraudulent transactions based on the trained model's predictions.

## Dependencies

The project requires the following Python libraries:

- `pandas` for data manipulation
- `scikit-learn` for machine learning

## Usage

1. Clone the repository.
2. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/kartik2112/fraud-detection/data) in that repository
3. Install the required dependencies.
4. Run the Jupyter notebook to follow the steps for detecting fraudulent transactions.
