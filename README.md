# Obesity-Prediction-Using-Logistic-Regression
This project builds a machine learning model that predicts whether a person is overweight/ obese or normal weight based on lifestyle/ health attributes. Using a publicly available dataset, the pipeline includes data preprocessing, binary target engineering, one-hot encoding, feature scaling, model training, and evaluation using logistic regression.



## Features

- Cleaned and preprocessed real-world health data
- Binary classification of obesity status: 
  - 1 = Overweight/Obese
  - 0 = Normal Weight
- One-hot encoding for categorical features
- Feature normalization using StandardScaler
- Logistic Regression model training
- Accuracy evaluation, classification report, and confusion matrix
- Custom prediction support for new user inputs

---

## Dataset

The dataset is publicly available and includes features such as:

- Age, height, weight
- Physical activity (FAF, TUE)
- Food and alcohol consumption habits (FCVC, NCP, CALC)
- Family history, transportation methods, and more

---

## Model Performance

- Achieved accuracy: **~98%** on test set
- High precision and recall for both classes
- Very low false positives/negatives

---

## How to Use

1. Clone the repository
2. Install dependencies:
   pip install pandas numpy scikit-learn matplotlib
3. Run the main script to train and evaluate the model
4. Modify the new_user dictionary to test custom predictions

