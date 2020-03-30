
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

Ziilow is in dire need of a model to help predict Home prices in Ames Iowa.

### Description of data

Data was provided by kaggle with 80 features and 2500 rows of data.

https://www.kaggle.com/c/dsi-us-9-project-2-regression-challenge/data    

The goal is to train a regression model to predict housing price in Ames Iowa.

After going through the data I was able to determine that overall quality, neighborhoods, most size features, year built and year remodel were all good indicators on predicting the home prices. 

![ames_overall.png](https://git.generalassemb.ly/artcyw/project_2/blob/master/img/ames_overall.png)

![ames_yearbuilt.png](https://git.generalassemb.ly/artcyw/project_2/blob/master/img/ames_yearbuilt.png)

![ames_year_remodel.png](https://git.generalassemb.ly/artcyw/project_2/blob/master/img/ames_year_remodel.png)

![ames_neighboorhood.png](https://git.generalassemb.ly/artcyw/project_2/blob/master/img/ames_neighborhood.png)

### Model performance on training and test data

I ended up using a linear regression model after running other models including ridge and lasso. I was able to optimize the linear regression after doing many tests and some feature engineering. My model was never really overfitted and as result the lasso and ridge models were not effective.

I was able to get my model to have a R2 score of 0.92 for the training data and 0.90 for the test data.

### Primary findings conclusions recommendations

The model I ended up with performed really well with a .90 R2 score. During the process of building the model. I notice the main predictors are related to quality size year and the neighborhood. 

I would recommend advising home sellers to improve their house prior to selling. These are tangible things they would be able to do to improve home price.

### Next steps

This model won't work for all markets, but it will most likely fit most criteria of other markets. With the main indicator being size, quality and year of the home this will work well for all home markets. These are features I believe will be important to all home markets. There is a lot of you can take from this model to help get started on models for other markets.   
