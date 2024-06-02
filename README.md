# Heart Disease Classification Project

## Introduction
This project focuses on building a machine learning model to classify the presence of heart disease in patients. The dataset contains various medical attributes used to predict the likelihood of heart disease.

## Data Loading and Preprocessing
- **Data Source**: The data is loaded from a CSV file using Pandas.
- **Data Cleaning**: Initial inspection for missing values and data types.
- **Feature Engineering**: Numerical features are scaled using StandardScaler from scikit-learn.
  

## Model Building
- **Data Splitting**: The data is split into training and test sets.
- **Model Selection**: Random Forest Classifier.
- **Hyperparameter Tuning**: GridSearchCV is used to find the best hyperparameters for the models.

## Model Training and Evaluation
- **Training**: Models are trained on the training set with the tuned hyperparameters.
- **Evaluation**: Performance is evaluated using metrics like accuracy, precision, recall, F1 score, and confusion matrix on the test set.

## Results

The performance metrics of the decision tree classifier are as follows:

| Metrics    | Score     |
|------------|-----------|
| Accuracy   | 0.883333  |
| Precision  | 0.882961  |
| Recall     | 0.883333  |
| F1 Score   | 0.882891  |
