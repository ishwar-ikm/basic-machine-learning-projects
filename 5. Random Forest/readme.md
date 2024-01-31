# Penguin Size and Banknote Analysis

## Overview
This project focuses on the analysis of penguin size data and banknote_authentication using a Random Forest Classifier. The dataset (`penguins_size.csv`) includes information about penguin's species, island, sex, and various physical measurements and dataset (`data_banknote_authentication.csv`) includes information about Variance_Wavelet,Skewness_Wavelet,Curtosis_Wavelet,Image_Entropy and Class. The analysis involves data cleaning, exploratory data analysis, feature engineering, and building a Random Forest model for species classification.

## Key Files
- `model/penguin_size_analysis.ipynb, model/penguin_size_analysis.ipynb`: Jupyter Notebook containing the analysis code.
- `data/penguins_size.csv, data/data_banknote_authentication.csv`: Dataset used for the analysis.

## Analysis Steps
1. **Data Loading**: Load the penguins dataset from the provided CSV file.
2. **Data Cleaning**: Check for missing values and handle them appropriately.
3. **Exploratory Data Analysis (EDA)**: Explore the dataset by examining unique species, visualizing pair plots, and investigating feature distributions.
4. **Data Visualization**: Create visualizations such as pair plots and box plots to understand relationships between variables.
5. **Feature Engineering**: Encode categorical variables and split the dataset into features (`X`) and the target variable (`y`).
6. **Data Splitting**: Split the data into training and testing sets using `train_test_split`.
7. **Decision Tree Model Building**: Build a Decision Tree Classifier model using scikit-learn.
8. **Model Evaluation**: Evaluate the model's performance using classification reports and confusion matrices.
9. **Feature Importance**: Analyze feature importance using the trained model.
10. **Visualization of Decision Tree**: Visualize the Decision Tree model.

## Additional Notes
- Ensure that Python and the required libraries are installed.
- Adjust file paths or configurations in the script as needed.
- The impact of different hyperparameters on the model's structure and performance is demonstrated.
