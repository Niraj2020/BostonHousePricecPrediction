# BostonHousePricecPrediction

### dataset link : https://www.kaggle.com/code/shreayan98c/boston-house-price-prediction/input

#### **Data Set Characteristics:**  

    :Number of Instances: 506 

    :Number of Attributes: 13 numeric/categorical predictive. Median Value (attribute 14) is usually the target.

    :Attribute Information (in order):
        - CRIM     per capita crime rate by town
        - ZN       proportion of residential land zoned for lots over 25,000 sq.ft.
        - INDUS    proportion of non-retail business acres per town
        - CHAS     Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
        - NOX      nitric oxides concentration (parts per 10 million)
        - RM       average number of rooms per dwelling
        - AGE      proportion of owner-occupied units built prior to 1940
        - DIS      weighted distances to five Boston employment centres
        - RAD      index of accessibility to radial highways
        - TAX      full-value property-tax rate per $10,000
        - PTRATIO  pupil-teacher ratio by town
        - B        1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
        - LSTAT    % lower status of the population
        - MEDV     Median value of owner-occupied homes in $1000's
:Missing Attribute Values: None



# Introduction:
The Boston House Prices dataset is one of the most popular datasets in the field of machine learning. It's often used to teach and practice various machine learning algorithms.


# The Project:
The goal of this project was to create a machine-learning model that could accurately predict the prices of houses in Boston. The dataset was obtained from scikit-learn, a popular machine-learning library in Python. The dataset contains 506 observations and 13 features, including the per capita crime rate, the average number of rooms per dwelling, and the pupil-teacher ratio by town.


# Data Preprocessing:
Before we could start building the model, we had to preprocess the data. This involved checking for missing values, removing any unnecessary features, and normalizing the data. We used pandas and scikit-learn libraries to perform these tasks.


# Exploratory Data Analysis:
Next, we performed some exploratory data analysis to gain insights into the relationships between the different features and the target variable, i.e., house prices. We used the matplotlib and Seaborn libraries to visualize the data and understand any patterns or correlations in the dataset. We also computed some summary statistics to understand the central tendency and variability of the data.


# Model Building:
With the preprocessed data and insights from exploratory data analysis, we started building the machine learning model. We chose to use a linear regression model since it's a simple and powerful algorithm for predicting continuous values. We used scikit-learn to split the dataset into training and testing sets, fit the model to the training data, and evaluate its performance on the testing data. We also tuned the hyperparameters of the model to improve its accuracy.


# Results:
Our linear regression model was able to predict the prices of houses in Boston with an R2 score of 0.71. Although the accuracy is not perfect, it's still a good starting point for further analysis and improvement.

# Conclusion:
In this Project, we explored a project that used the Boston House Prices dataset and demonstrated some of the techniques used to preprocess, analyze, and build a machine-learning model.





# LinkedIn: https://www.linkedin.com/in/neeraj-kumar-sharma-a4734b280/