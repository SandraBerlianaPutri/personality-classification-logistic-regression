# Personality Prediction Using Logistic Regression

## About
This project uses Logistic Regression with Gradient Descent to classify individuals as introverts or extroverts based on their social behavior and lifestyle characteristics.

## Data
- **Source:** [Kaggle](https://www.kaggle.com/)
- **Observations:** 2,900
- **Predictor Variables:** 7
- **Target Variable:** Personality type (Introvert or Extrovert)
- **Data Type:** Secondary data
- **Variables:**

| Variable | Description | Type |
|---|---|---|
| X1 | Time spent alone | Numerical |
| X2 | Stage fear | Categorical |
| X3 | Social event attendance | Numerical |
| X4 | Frequency of going outside | Numerical |
| X5 | Feeling drained after socializing | Categorical |
| X6 | Friends circle size | Numerical |
| X7 | Social media posting frequency | Numerical |
| Y | Personality type | Categorical |

## Methods
1. **Data Exploration** — Examine data structure, missing values, descriptive statistics, outliers, and target distribution.
2. **Statistical Analysis** — Assess categorical predictors using Chi-square tests and numerical predictors using Welch’s t-test and eta-squared.
3. **Data Preprocessing** — Remove missing observations and encode categorical predictors using one-hot encoding.
4. **Multicollinearity Assessment** — Calculate Generalized Variance Inflation Factors (GVIF).
5. **Data Splitting** — Divide the data into training and testing sets using an 80:20 ratio with stratified sampling.
6. **Model Development** — Implement Logistic Regression from scratch using Gradient Descent.
7. **Hyperparameter Tuning** — Compare learning rates and iteration counts to select the best configuration based on accuracy.
8. **Model Evaluation** — Evaluate performance using accuracy, precision, recall, F1-score, ROC-AUC, confusion matrices, and ROC curves.

## Author
**Sandra Berliana Putri** - Statistics and Data Science graduate from IPB University, interested in data analysis and machine learning.
