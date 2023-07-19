# Mental Fitness Prediction Project

## Purpose of the Project
The purpose of this project is to develop a machine learning model that can predict the mental fitness of individuals based on various mental and substance use disorders data. By accurately predicting mental fitness, this model aims to provide valuable insights into mental health patterns, identify potential risk factors, and support efforts to improve mental well-being.

## Problem Statement
The problem addressed in this project is to predict an individual's mental fitness based on data related to mental and substance use disorders. The objective is to build a regression model that can accurately estimate mental fitness scores, enabling better understanding and management of mental health.

## Technologies Used
The project utilizes the following technologies and libraries:
- Python: The primary programming language used for data processing, analysis, and model development.
- Numpy and Pandas: For data manipulation and handling.
- Seaborn and Matplotlib: For data visualization and exploratory data analysis (EDA).
- Plotly Express: To create interactive visualizations for deeper insights.
- Scikit-learn: For implementing machine learning algorithms, data preprocessing, and evaluation.
- TensorFlow and Keras: For building and training neural network models.
- Tabulate: To create tables for comparing model performance metrics.

## Exploratory Data Analysis
During the EDA phase, various visualizations are used to gain insights into the dataset. The visualizations include box plots, heatmaps, scatter plots, histograms, and time series plots. These visualizations provide a clear understanding of the data distribution, correlations, and trends related to mental fitness across different countries and years.

## Model Training and Evaluation
Multiple regression models are trained and evaluated to predict mental fitness:
- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- Support Vector Regressor (SVR)
- Neural Network Regressor

Each model is evaluated using mean squared error (MSE), root mean squared error (RMSE), and R-squared (R2) score to assess its performance on both the training and testing datasets. The models are trained on a portion of the dataset and tested on unseen data to measure their ability to generalize.

## Model Performance
The performance metrics of each model are compared in a table that includes MSE, RMSE, and R2 score for easy comparison. The feature importance plot from the Random Forest Regressor provides insights into the most significant features affecting mental fitness predictions.

The performance metrics of each model on the testing dataset are as follows:

| Model                      | MSE                | RMSE               | R2 Score           |
|----------------------------|--------------------|--------------------|--------------------|
| Linear Regression          | 1.13575           | 1.06572           | 0.763897          |
| Random Forest Regressor    | 0.029257          | 0.171047          | 0.993918          |
| Gradient Boosting Regressor| 0.245318          | 0.495296          | 0.949003          |
| Support Vector Regressor   | 0.240255          | 0.490158          | 0.950055          |
| Neural Network Regressor   | 0.0746332         | 0.273191          | 0.984485          |

The table above presents the Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2) score for each model's predictions. These metrics provide valuable insights into the accuracy and performance of the models in estimating mental fitness. The Random Forest Regressor shows promising results with the lowest MSE and RMSE and the highest R2 score, indicating its effectiveness in predicting mental fitness based on the given features.
## Conclusion
In conclusion, the project successfully develops regression models to predict mental fitness based on mental and substance use disorders data. The models' performance is evaluated and compared, with the Random Forest Regressor showing promising results. The project highlights the importance of mental health data analysis and predictive modeling in promoting better mental well-being and offers a foundation for further research and improvement in mental health prediction.