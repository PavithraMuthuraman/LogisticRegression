# LogisticRegression
*Logistic Regression for Insurance Claim Prediction*

**Description:** This project focuses on predicting whether an individual will make an insurance claim based on their personal characteristics and medical history using the Logistic Regression algorithm. The dataset utilized contains information on various factors such as age, sex, BMI, number of children, smoking status, region, and insurance charges.

## Project Overview:
- **Objective:** Predict the likelihood of an individual making an insurance claim using logistic regression.
- **Model:** Logistic Regression is employed to classify data into insurance claim or no insurance claim categories.
- **Dataset:** The dataset includes features such as age, sex, BMI, number of children, smoking status, region, and charges, along with the target variable indicating whether an insurance claim was made.

## Files Included:
- `insurance_classification.csv`: The dataset used for training and testing the Logistic Regression model.
- `LogisticRegression.ipynb`: The Python script that performs data preprocessing, model training, prediction, and evaluation.

## Code Execution:
1. **Setup Environment:** Install the required libraries (`numpy`, `pandas`, `scikit-learn`).
2. **Data Loading:** Place `insurance_classification.csv` in the appropriate directory, then load and inspect the dataset.
3. **Preprocessing:** Divide the dataset into dependent and independent variables, and split into training and testing sets.
4. **Model Training:** Train the Logistic Regression model on the training data.
5. **Prediction:** Predict insurance claim outcomes for the test data.
6. **Evaluation:** Assess the model’s performance using confusion matrix and accuracy score.

