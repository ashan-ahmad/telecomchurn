# Telco Churn Prediction Project

This project focuses on predicting customer churn for a telecommunications company using machine learning techniques. The dataset used is a historical customer dataset where each row represents one customer, providing various demographic and service usage information.

## Project Overview

The goal of this project is to predict whether a customer will churn (leave the company) based on their historical data. By identifying customers likely to churn, the company can take proactive measures to retain them, which is typically more cost-effective than acquiring new customers.

### Key Features of the Dataset:

- **Demographic Information**: Includes details like age, address, and income.
- **Service Usage**: Tracks the customer's tenure, equipment usage, and other service-related metrics.
- **Target Variable**: The `churn` column indicates whether the customer has churned (1) or not (0).

## Steps in the Project

1. **Data Loading**: The dataset is loaded from a remote URL.
2. **Data Preprocessing**:
   - Selecting relevant features.
   - Converting the target variable to an integer type.
3. **Feature Scaling**: Standardizing the input features using `StandardScaler`.
4. **Splitting the Dataset**: Dividing the data into training and testing sets.
5. **Modeling**:
   - Logistic Regression is used as the classifier.
   - Predictions and probabilities are generated for the test set.
6. **Feature Importance**: Visualizing the coefficients of the logistic regression model to understand the impact of each feature.
7. **Performance Evaluation**:
   - Calculating log loss to evaluate the model's performance.

## Libraries Used

- `pandas` and `numpy` for data manipulation.
- `scikit-learn` for machine learning tasks.
- `matplotlib` for data visualization.

## How to Run the Project

1. Clone the repository to your local machine.
2. Install the required Python libraries using `pip install -r requirements.txt`.
3. Open the Jupyter Notebook file (`Telco Churn data.ipynb`) and run the cells sequentially.

## Results

The project demonstrates how logistic regression can be used to predict customer churn and provides insights into the importance of various features in the prediction process.

## Future Work

- Experiment with other machine learning algorithms like decision trees, random forests, or gradient boosting.
- Perform hyperparameter tuning to improve model performance.
- Explore additional feature engineering techniques to enhance the dataset.

## Acknowledgments

The dataset used in this project is sourced from IBM Developer Skills Network.

---
