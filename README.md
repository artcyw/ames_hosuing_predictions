
# Predicting Home Prices in Ames Iowa
## Albert Wong

## Contents

1. [Problem statement](#Problem-statement)
2. [Description of data](#Description-of-data)
3. [Model performance on training/ test data](#Model-performance-on-training-and-test-data)
4. [Primary findings/conclusions/recommendations](#Primary-findings-conclusions-recommendations)
5. [Next steps](#Next-steps)
6. [Presentation](#Presentation-Prompt)


### Problem statement

Predicting Home prices in Ames, Iowa was my very first modeling project. There are 4 main parts to this project, Cleaning the data, Exploratory Data Analysis, Preprocessing/Feature Engineering, and Modeling.

There 4 main parts are usually the same for most Data Science projects and are repeatable. Doing this everytime create chaotic code and consume a lot of time.

The solution! My own module dstools will help speed things up and keep everything clean.

### Description of data

Data was provided by kaggle with 80 features and 2500 rows of data.

https://www.kaggle.com/c/dsi-us-9-project-2-regression-challenge/data    

The goal is to train a regression model to predict housing price in Ames, Iowa with dstools.

### Cleaning the Data

I standardize most of the data to make it easier to process. Main attributes of the module here standardize the string to lowercase and replace string with underscore upon initializing.

Method included to organize null values with a dataframe summarizing them base on each column.

### Exploring the Data

Main attributes include splitting the data into nominal and numerical features. Graphing with subplots for both numerical and nominal data. Heatmap to check data for correlation. 

### Preprocessing/Feature Engineer

Easily create dummies and createPolynominal features.

### Modeling

Set your pipeline steps and you are ready to test your model. With cross validation included, one easy steps to run your model multiple time and all score will be summarize.


### Next steps

dstools right now is built around linear regression. Need to add more attributes that will work for classification as well. More graphs can be include to exploring data.
