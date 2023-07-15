# Mental Fitness Prediction

This project focuses on predicting mental fitness based on various mental and substance use disorder factors. The goal is to explore the relationship between different disorders and mental fitness and develop regression models to make predictions.

## Technologies Used

The following technologies were used in this project:

- Python
- NumPy
- Pandas
- Seaborn
- Matplotlib
- Plotly
- Scikit-learn

## Dataset

The dataset used in this project consists of two CSV files:

- prevalence-by-mental-and-substance-use-disorder-AI.csv: Contains information about the prevalence of mental and substance use disorders.
- mental-and-substance-use-as-share-of-disease-AI.csv: Provides data on the share of mental and substance use disorders in total disease burden.

Both datasets were combined into a single DataFrame for analysis and modeling.

## Data Exploration and Preprocessing

- Data cleaning: The datasets were checked for missing values, and the "Code" column was dropped as it was not necessary for the analysis.
- Exploratory Data Analysis: Various visualizations such as heatmaps, joint plots, pair plots, and pie charts were created to understand the relationships between different variables and mental fitness.

## Model Training and Evaluation

Two regression models were trained on the dataset:

1. Linear Regression:
   - The dataset was split into training and testing sets.
   - The features were scaled using the StandardScaler.
   - Linear Regression model was trained and evaluated using Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2) score.

2. Random Forest Regressor:
   - The dataset was split into training and testing sets.
   - The Random Forest Regressor model was trained and evaluated using MSE, RMSE, and R2 score.
   - Hyperparameter tuning was performed using GridSearchCV to find the best parameters for the model.
   - The model was retrained using the best parameters and evaluated on the training and testing sets.

## Model Performance

Linear Regression:
- MSE on the training set: 1.389
- RMSE on the training set: 1.178
- R2 score on the training set: 0.741
- MSE on the testing set: 1.135
- RMSE on the testing set: 1.065
- R2 score on the testing set: 0.763

Random Forest Regressor:
- Best parameters found: 'max_depth': None, 'n_estimators': 200
- Best score found: 0.992
- MSE on the training set: 0.0052
- RMSE on the training set: 0.0726
- R2 score on the training set: 0.9990
- MSE on the testing set: 0.1807
- RMSE on the testing set: 0.4251
- R2 score on the testing set: 0.9624

This project provides insights into the relationship between mental disorders and mental fitness, as well as predictive models to estimate mental fitness based on the given factors.