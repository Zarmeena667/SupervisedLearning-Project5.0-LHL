# SupervisedLearning-Project5.0-LHL
# Midterm-Project-LHL

## Project Motivation and Goals

The goal of this project for me was to put the use of supervised learning techniques into practice.

## Repository folder guide/order
1. Readme
2. Supervised Learning - Project.ipynb
3. diabetes.csv (raw data)


## Process

![image](https://github.com/Zarmeena667/SupervisedLearning-Project5.0-LHL/assets/145514413/7c95a09c-c14b-4911-af20-4dad5f21ca77)




## Results/Insights

1. The variable Glucose has the highest correlation coefficient (compared to other predictor variables) and has a moderate positive correlation with "Outcome." It is a possibility that when glucose levels increase, the likelihood of a positive outcome also increases. The relationship could further be explored through regression analysis.
2. Average glucose level of people with diabetes is 142. 
3. The average age of individuals diagnosed to have diabetes within the sample dataset is 37.
4. Between the models chosen to train the data, random forest and xgb3 model had the same accuracy score. It was hard to predict a better model without a specific use case identified. Thereby, we further evaluated both models using cross-validation and it seems that random forest is the better performing model.
5. For the models of choice the following findings are notable:
- Mean Accuracy: The Random Forest model has a slightly higher mean accuracy (0.7618) compared to the XGBoost model (0.7240). This suggests that, on average, the Random Forest model performs better in terms of accuracy across different folds of the data.
- Standard Deviation: The XGBoost model also has a slightly lower standard deviation (0.0270) compared to the Random Forest model (0.035). A lower standard deviation indicates less variability in performance across different folds.


## Challenges 

With more time, I would want to train and assess other models as well as keep iterating the process of feature engineering to find a better fit model.

## Future Goals
1. Try other models for the same data.
2. Test further iterations of feature engineering process and hyper parameter tuning to find the best fit model as well as explore data through interaction of different variables.



