# Heart-Disease-Prediction-using-Logistic-Regression
# ❤️ Heart Disease Prediction using Logistic Regression

## Project Overview

This project demonstrates how Logistic Regression can be used to predict
the presence of heart disease using medical attributes from the UCI
Heart Disease dataset.

The project includes: - Data preprocessing - Handling missing values -
Exploratory data analysis - Data visualization - Logistic Regression
model training - Model evaluation

## What is Logistic Regression?

Logistic Regression is a supervised machine learning algorithm used for
classification problems.\
It predicts the probability that a data point belongs to a particular
class.

Sigmoid Function:

P(Y=1) = 1 / (1 + e\^(-z))

Where:

z = b0 + b1x1 + b2x2 + ... + bnxn

The output ranges between 0 and 1, representing probability.

## Dataset

Source: UCI Machine Learning Repository

Features include: - age - sex - cp (chest pain type) - trestbps (resting
blood pressure) - chol (cholesterol) - fbs (fasting blood sugar) -
restecg (ECG results) - thalach (maximum heart rate) - exang (exercise
induced angina) - oldpeak - slope - ca - thal

Target variable: num → Presence of heart disease

## Visualizations

### Feature Correlation Heatmap

Shows correlations between variables and helps identify important
predictors.

### Age Distribution

Displays the distribution of patient ages. Most patients fall between 40
and 70 years old, suggesting higher risk in middle-aged and older
individuals.

### Confusion Matrix

Used to evaluate model performance by comparing predicted vs actual
classifications.

Components: - True Positive (TP) - True Negative (TN) - False Positive
(FP) - False Negative (FN)

## Project Structure

heart-disease-logistic-regression/ │ ├── LogisticRegression.ipynb ├──
README.md ├── images/ │ ├── age_distribution.png │ ├──
correlation_heatmap.png │ └── confusion_matrix.png │ └──
requirements.txt

## Installation

Clone the repository:

git clone
https://github.com/yourusername/heart-disease-logistic-regression

Install dependencies:

pip install -r requirements.txt

Required libraries: - pandas - numpy - matplotlib - seaborn -
scikit-learn - ucimlrepo

## Running the Project

Run the notebook:

jupyter notebook LogisticRegression.ipynb

Execute all cells to load the dataset, train the model, and evaluate
performance.

## Model Evaluation

The model is evaluated using:

-   Accuracy
-   Precision
-   Recall
-   F1 Score
-   Confusion Matrix

## Future Improvements

-   Hyperparameter tuning
-   Testing additional ML models
-   Feature engineering
-   Model deployment

## Author

Machine Learning Logistic Regression Project
