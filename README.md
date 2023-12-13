# Telecom Churn Prediction

## Overview

This project focuses on predicting customer churn in the telecom industry. Customer churn, or attrition, is a critical concern for telecom companies, and predicting which customers are likely to churn can help businesses take proactive measures to retain customers.

![](telecom_churn.png)

In this repository, we have developed and implemented machine learning models to predict customer churn based on historical data and customer behavior patterns.

## Table of Contents

- [Data](#data)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Feature Engineering](#feature-engineering)
- [Model Development](#model-development)
- [Model Evaluation](#model-evaluation)
- [Deployment](#deployment)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Data

We have used a telecom industry dataset containing historical customer information, including features such as customer demographics, usage patterns, and contract details. The dataset is available [here](data/telecom_churn_dataset.csv).

## Data Preprocessing

Before building and training machine learning models, we performed data preprocessing tasks such as handling missing values, encoding categorical variables, and scaling features. Details can be found in the [data_preprocessing.ipynb](notebooks/data_preprocessing.ipynb) notebook.

## Exploratory Data Analysis (EDA)

We conducted an in-depth exploratory data analysis to gain insights into customer behavior and identify potential churn indicators. Visualizations and findings are documented in the [eda.ipynb](notebooks/eda.ipynb) notebook.

## Feature Engineering

Feature engineering is a crucial step in improving model performance. We created new features and transformed existing ones to enhance predictive power. Details can be found in the [feature_engineering.ipynb](notebooks/feature_engineering.ipynb) notebook.

## Model Development

We experimented with various machine learning algorithms, including:
- Logistic Regression
- Random Forest
- XGBoost
- Support Vector Machine (SVM)

The model development process is documented in the [model_development.ipynb](notebooks/model_development.ipynb) notebook.

## Model Evaluation

We evaluated model performance using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC. Model evaluation results are summarized in the [model_evaluation.ipynb](notebooks/model_evaluation.ipynb) notebook.

## Deployment

We deployed the best-performing model as a RESTful API using Flask. The deployment code and instructions can be found in the [deployment](deployment/) directory.

## Usage

To use this project:
1. Clone the repository: `git clone https://github.com/hargurjeet/telecom-churn-prediction.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Follow the notebooks in the [notebooks](notebooks/) directory for data preprocessing, EDA, feature engineering, and model development.
4. For model deployment, follow the instructions in the [deployment](deployment/) directory.

## Contributing

Contributions to this project are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
