# README: Sales Prediction Model using Python

## Submitted By: Jay Chopra

## Intern as: Data Science

## August Batch

## Aim

The main aim of this project is to predict sales based on the expenditure on advertisements through different medias using the given dataset. The dataset contains information about advertising spending on different platforms (TV, Radio, and Newspaper) and their effect on sales.

## Libraries in use

The following important libraries were used for this project:

- numpy
- pandas
- matplotlib.pyplot
- seaborn
- sklearn.model_selection.train_test_split
- sklearn.linear_model.LinearRegression

## Dataset

The dataset was loaded using pandas as a DataFrame from the file "advertising.csv" which is provided by Kaggle.

## Data Exploration and Preprocessing

1. The shape and descriptive statistics for the dataset were displayed using `df.shape` and `df.describe()`.
2. Separate pair plots were used to visualize the relationship between sales and advertisment expenditure on TV, Radio, Newspaper using `seaborn.pairplot`.
3.Also, Histograms were plotted to observe the distribution of advertising expenditure on TV, Radio, and Newspaper using `matplotlib.pyplot.hist`.

## Correlation between sales and medium of advertisement

1. A correlation matrix heatmap was plotted to observe the correlation between advertising expenditure on TV, Radio, Newspaper, and sales using `seaborn.heatmap`.

## Model Training

1. The data was split into training and testing sets using `train_test_split`, with 70:30 ratio for training and testing respectively.
2. Linear regression model was trained on the training data using `sklearn.linear_model.LinearRegression`.

## Prediction Model

1. The model was used to predict sales based on advertising expenditure on TV for the test set using `model.predict(X_test)` and the corresponding advertising expenditure on TV in the test set.
2. The model coefficients and intercept were obtained using `model.coef_` and `model.intercept_`.
3. The predictions and actual sales values were plotted using `matplotlib.pyplot.plot` and `matplotlib.pyplot.scatter`.

## Observations and Outcome 
1. The above model is a conclusion to the requirement as this would be a reliable model for prediction of sales.\
2. The above model is working mainly on the major effecting method i.e. TV advertisement.
