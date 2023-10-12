# German Credit Risk

This project focuses on assessing credit risk using machine learning. The primary objective is to predict whether a credit applicant poses a high risk of defaulting. It involves data analysis, preprocessing, feature engineering, modeling, and evaluation. Below are the main steps and findings:

## Required Libraries and Data

- Python libraries such as Pandas, NumPy, Seaborn, Matplotlib, and Plotly are used.
- The dataset is loaded from "german_credit_data.csv".

## Data Analysis

### Gender Analysis
- The dataset comprises 69% male and 31% female applicants.
- Analysis shows differences in the age at which individuals apply for loans, with females tending to apply earlier.
- Common loan purposes include cars and radio/TV.

### Risk Analysis
- Credit amount and duration significantly influence credit risk.
- Those with high credit amounts and longer durations are more likely to be high-risk applicants.
- People with rich housing types are less likely to default.
- Young (20-30) and old (60+) applicants have a slightly higher chance of defaulting.

## Data Preprocessing and Feature Engineering

- Handling missing values in "Saving accounts" and "Checking account" by filling them with "none."
- Mapping "Job" values to descriptive labels.
- Creating "Age group" based on age ranges.

## Outlier Detection

- Identifying outliers in numeric features such as "Age," "Credit amount," and "Duration."

## Feature Encoding

- Using one-hot encoding for categorical features.

## Standardization

- Applying robust scaling to numeric features.

## Modeling

- Several machine learning models are tested for credit risk prediction, including Logistic Regression, Decision Trees, Naive Bayes, K-Nearest Neighbors, Random Forest, Support Vector Machines, and XGBoost.
- Cross-validation and recall scoring are used to evaluate models.
- Best-performing models are Naive Bayes, Decision Trees, and XGBoost.

## Hyperparameter Tuning

- Models (Naive Bayes, Decision Trees, and XGBoost) are fine-tuned to optimize their performance.
- Metrics, such as precision, recall, and ROC curves, are evaluated for the tuned models.

For more details, refer to the project code and Jupyter Notebook.
