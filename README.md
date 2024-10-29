# PREDICTING HEART DISEASE RISK WITH MACHINE LEARNING

This Jupyter Notebook performs a machine learning analysis of a heart disease dataset to predict the presence or absence of heart disease in patients. It explores the data, performs data preprocessing, trains various machine learning models, evaluates their performance, and visualizes the results.

## Key functionalities of the code:

# Data exploration:
- Reads the heart disease dataset from a CSV file.
- Provides descriptive statistics and visualizations of the data (histograms, boxplots, violin plots) to understand the distribution of features for both numerical and categorical variables.
# Data preprocessing:
- Handles missing values (checks if there are any).
- Performs one-hot encoding for categorical features.
- Splits the data into training and testing sets for model evaluation.
# Machine learning models:
- Trains and evaluates three ensemble learning models: Decision Tree Classifier, Random Forest Classifier, and Gradient Boosting Classifier.
- Hyperparameters tuning using GridSearchCV for the Decision Tree Classifier.
- Analyzes the performance of each model using accuracy score and classification report.
# Visualization:
- Generates learning curves to visualize the relationship between training set size and model performance (training and cross-validation scores).
- Creates bar charts to show the relative importance of features for each trained model.
# Instructions:
- Ensure you have the required libraries installed (pandas, numpy, matplotlib, seaborn, scikit-learn).
- Download the heart disease dataset ( Cleveland Dataset) and save it as "heart.csv" in the same directory as this notebook.
- Run the notebook cells sequentially to execute the code and generate the visualizations.
# Note:

- This script assumes the "heart.csv" file is located in the same directory as the notebook.
- The code utilizes various functions from external libraries for data manipulation, visualization, and machine learning. Refer to the documentation of these libraries for a deeper understanding of their functionalities.
