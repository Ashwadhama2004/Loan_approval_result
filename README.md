# Loan_approval_result


# Loan Prediction Model

This repository contains a machine learning project to predict loan approval based on various attributes of the applicants. The project uses a Support Vector Classifier (SVC) for the prediction task.

## Project Overview

The objective of this project is to predict whether a loan will be approved based on the characteristics of the applicants. The dataset used includes features such as gender, marital status, dependents, education level, employment status, income, loan amount, loan term, credit history, and property area.

## Dataset

- The dataset used is `train_u6lujuX_CVtuZ9i.csv`.
- It consists of 614 rows and 13 columns.
- Target variable: `Loan_Status`

### Key Columns
- **Loan_ID**: Unique Loan ID
- **Gender**: Gender of the applicant
- **Married**: Marital status
- **Dependents**: Number of dependents
- **Education**: Education level (Graduate/Not Graduate)
- **Self_Employed**: Self-employed status
- **ApplicantIncome**: Applicant's income
- **CoapplicantIncome**: Co-applicant's income
- **LoanAmount**: Loan amount
- **Loan_Amount_Term**: Term of loan in months
- **Credit_History**: Credit history (1.0/0.0)
- **Property_Area**: Area where property is located (Urban/Semiurban/Rural)
- **Loan_Status**: Loan approval status (Y/N)

## Data Preprocessing

- Missing values were handled by dropping rows with null values.
- Categorical variables were converted into numerical values using label encoding.
- The dataset was split into training and testing sets with a ratio of 80:20.

## Model Training

- The model used for prediction is a Support Vector Classifier (SVC) with a linear kernel.
- The model was trained on the training data (`X_train`, `Y_train`).

## Model Evaluation

- **Training Accuracy**: ~80%
- **Testing Accuracy**: ~82%

## Data Visualization

The project includes visualizations to explore the relationship between various features and loan status:
- Education vs Loan Status
- Marital Status vs Loan Status
- Property Area vs Loan Status

## How to Use

1. Clone this repository.
2. Ensure you have Python 3.x and necessary libraries installed (e.g., `pandas`, `numpy`, `scikit-learn`, `seaborn`, `matplotlib`).
3. Run the Jupyter notebook to view the data processing steps, model training, and evaluation.

```bash
git clone https://github.com/Ashwadhama2004/loan-prediction.git
cd loan-prediction
pip install -r requirements.txt
jupyter notebook
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.
