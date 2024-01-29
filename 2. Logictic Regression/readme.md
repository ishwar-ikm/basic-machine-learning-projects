### In this section on Logistic Regression, we have three distinct projects, each featuring its own logistic regression model.

<br>

# Project 1: Hearing Test Analysis

## Overview
This project analyzes a dataset related to hearing tests. It explores the relationship between various features such as age, physical score, and the test results. The analysis includes data visualization, statistical summaries, and logistic regression modeling.

## Key Files
- `hearing_test.ipynb`: Jupyter Notebook containing the analysis code.
- `DATA/hearing_test.csv`: Dataset used for the analysis.

<br>

# Project 2: Heart Disease Prediction

## Overview
This project focuses on predicting heart disease based on a dataset containing various health-related features. It involves data exploration, visualization, feature scaling, logistic regression modeling, and performance evaluation.

## Key Files
- `heart_disease.ipynb`: Jupyter Notebook containing the analysis code.
- `Data/heart.csv`: Dataset used for the analysis.

<br>

# Project 3: Iris Species Classification

## Overview
This project involves the classification of iris species based on features like petal length and width. It includes data exploration, visualization, feature scaling, logistic regression modeling with hyperparameter tuning, and performance evaluation.

## Key Files
- `iris_classification.ipynb`: Jupyter Notebook containing the analysis code.
- `Data/iris.csv`: Dataset used for the analysis.

<hr>

# Dependencies
- `numpy`
- `pandas`
- `seaborn`
- `matplotlib`
- `scikit-learn`

# Analysis Steps
1. **Data Loading**: Load the iris dataset from the provided CSV file.
2. **Data Exploration**: Examine the dataset's structure, unique species, and descriptive statistics.
3. **Data Visualization**: Visualize data using scatterplots, pairplots, and a heatmap of correlations.
4. **Data Preprocessing**: Split the data into features and target, scale features, and split into training and testing sets.
5. **Logistic Regression Modeling with Grid Search**: Build a logistic regression model with hyperparameter tuning using scikit-learn's GridSearchCV.
6. **Model Evaluation**: Evaluate the model's performance using a confusion matrix and classification report, and analyze the best hyperparameters.

## Additional Notes

- Make sure you have Python and the required libraries installed.
- Adjust the file paths or configurations in the script as needed.

Feel free to explore the individual Jupyter Notebooks for detailed analysis and code implementation for each project.