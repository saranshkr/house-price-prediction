
# house-price-prediction

This project was an attempt to get a taste of what the end-to-end process might look like for a real-world machine learning problem, albeit at a smaller scale. The intent, as always, was to put my self-acquired knowledge to practical use.

### Overview

The world of statistical modeling defines `regression analysis` as a statistical technique that tries to relate a dependent variable to one or more independent variables. In the context of machine learning, this boils down to trying to express the target variable (usually continuous) as a relationship between the sample features. We can then use this expression or relationship to predict target values for unseen data.

I used the [California house prices dataset](https://www.kaggle.com/datasets/camnugent/california-housing-prices) to predict house prices based on various feature attributes, including geographic location (latitude and longitude), total number of bedrooms and median neighborhood income among others. I tried tuning the hyperparameters for the regression models to obtain better, if not the best, results using GridSearchCV for the machine learning regression models, and RandomizedSearchCV for a multilayer perceptron (constrained by my device's capabilities). I then compared the performance of different regression models for this dataset.