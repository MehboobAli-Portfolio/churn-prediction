# Churn Prediction

This repository contains a customer churn prediction project built in Python using a Jupyter Notebook. The notebook analyzes the IBM Telco Customer Churn dataset, explores customer behavior, prepares the data for modeling, and trains a model to predict whether a customer is likely to churn.

## Project Overview

Customer churn prediction is a common business problem in telecommunications. By identifying the factors that influence churn, companies can take proactive actions to retain customers and reduce revenue loss.

This project focuses on:

- loading and exploring the churn dataset
- cleaning and preprocessing customer data
- identifying churn patterns and influential features
- training a predictive model
- evaluating model performance and business impact

## Dataset

The project uses the public IBM Telco Customer Churn dataset, downloaded via KaggleHub.

Key characteristics of the dataset:

- 7,043 customer records
- 33 columns/features
- target variable for churn prediction
- mix of customer demographics, service usage, billing details, and churn indicators

## Repository Contents

- `churn_prediction.ipynb` — end-to-end notebook for data loading, preprocessing, modeling, and evaluation
- `LICENSE` — project license
- `README.md` — project overview and usage guide

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- TensorFlow / Keras
- KaggleHub
- Jupyter Notebook

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/MehboobAli-Portfolio/churn-prediction.git
cd churn-prediction
```

### 2. Create a Virtual Environment (Recommended)

```bash
python -m venv venv
source venv/bin/activate   # Linux/macOS
# venv\Scripts\activate    # Windows
```

### 3. Install Dependencies

```bash
pip install pandas numpy matplotlib keras kagglehub openpyxl jupyter
```

### 4. Open the Notebook

Launch Jupyter Notebook and open `churn_prediction.ipynb`:

```bash
jupyter notebook
```

Or open it in Google Colab if preferred.

## Notebook Workflow

The notebook includes the following steps:

1. Import required libraries
2. Download the dataset from Kaggle
3. Load the dataset into a Pandas DataFrame
4. Explore the data and inspect feature types
5. Handle missing or inconsistent values
6. Prepare features for modeling
7. Train a machine learning model
8. Evaluate model accuracy and performance
9. Interpret churn-related patterns

## Expected Outcome

The project aims to build a model that can predict customer churn with useful performance metrics and highlight the most important factors influencing customer retention.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Author

Mehboob Ali

## Acknowledgements

This project uses the IBM Telco Customer Churn dataset and was developed as a learning-focused churn prediction exercise.
