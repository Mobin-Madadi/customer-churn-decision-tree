# Customer Churn Prediction using Decision Tree

A machine learning project that predicts whether a customer is likely to churn using a **Decision Tree Classifier**.

The project includes data preprocessing, categorical feature encoding, model training, evaluation, visualization, feature importance analysis, and model tuning.

## Project Overview

Customer churn prediction is a classification problem where the goal is to identify customers who are likely to leave a service.

In this project, a Decision Tree model is trained to predict the `Churn` status based on customer information such as age, tenure, monthly charges, support calls, contract type, internet service, and payment method.

## Dataset

The dataset contains **500 customer records** with the following features:

| Feature           | Description                                             |
| ----------------- | ------------------------------------------------------- |
| `Age`             | Customer age                                            |
| `Tenure`          | Length of time the customer has been with the service   |
| `MonthlyCharges`  | Customer's monthly charges                              |
| `SupportCalls`    | Number of customer support calls                        |
| `ContractType`    | Type of customer contract                               |
| `InternetService` | Customer's internet service type                        |
| `PaymentMethod`   | Customer's payment method                               |
| `Churn`           | Target variable indicating whether the customer churned |

The target variable is encoded as:

* `0` → No Churn
* `1` → Churn

## Technologies & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## Project Workflow

The project follows these main steps:

1. Load the dataset
2. Data Cleaning
3. Inspect Data
4. Handle missing values
5. Encode categorical features
6. Separate features and target
7. Split the dataset into training and testing sets
8. Train a Decision Tree Classifier
9. Evaluate the model
10. Visualize the results
11. Analyze feature importance
12. Tune model parameters

## Model

The main machine learning algorithm used in this project is:

**Decision Tree Classifier**

Decision Trees are supervised learning algorithms that can be used for classification and regression tasks. The model makes predictions by creating a sequence of decision rules based on the input features.

## Model Evaluation

The model is evaluated using classification metrics such as:

* Accuracy
* Decision Tree
* Confusion Matrix

These metrics help evaluate how well the model identifies customers who are likely to churn.

## Visualizations

The project includes several visualizations, including:

* Confusion Matrix
* Decision Tree visualization

## Project Structure

```text
customer-churn-decision-tree/
│
├── data/
│   └── customer_churn.csv
│
├── notebooks/
│   └── customer_churn.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

## Installation

Clone the repository:

```bash
git clone https://github.com/Mobin-Madadi/customer-churn-decision-tree.git
```

Navigate to the project directory:

```bash
cd customer-churn-decision-tree
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

## Running the Project

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```text
notebooks/customer_churn.ipynb
```

Run the notebook cells to reproduce the preprocessing, training, evaluation, and visualization steps.

## Key Learning Outcomes

Through this project, I practiced:

* Classification with Decision Trees
* Data preprocessing
* Handling categorical variables
* Train/Test splitting
* Model evaluation
* Confusion Matrix analysis
* Feature importance
* Data visualization
* Basic hyperparameter tuning

## Author

**Mobin Madadi**

GitHub: [Mobin-Madadi](https://github.com/Mobin-Madadi)
