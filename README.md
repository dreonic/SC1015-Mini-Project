# Diamond Price Prediction Repository
## Description
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which uses a [diamond dataset](https://www.kaggle.com/datasets/hrokrin/the-largest-diamond-dataset-currely-on-kaggle) from Kaggle. 


## Contributors
> School of Computer Science and Engineering
> Nanyang Technological University
> Lab: A136
> Group: 8

| Name|GitHub Acount|Main Contributions|
|:---:|:---:|:---:|
|Juan Frederick|[@dreonic](https://github.com/dreonic)|Data Resampling, Machine Learning, Hyperparameter Tuning|
|Hilarius Jeremy|[@HilariusJeremy](https://github.com/HilariusJeremy)|Data Visualisation, Problem Definition, Data Driven Insight|
|Poh Jing Ting, Felicia|[@feliciapjt](https://github.com/feliciapjt)|Exploratory Data Analysis, Machine Learning, Problem Definition|

## Problem Statement
> - Building an accurate model for estimation and prediction diamond price
> - Determine related factors to diamond price to suggest further action from buyers and sellers.


## Workflow
1. Identifying Data and Data Cleaning
2. Exploratory Data Analysis
3. Machine Learning
4. Hyperparametric Tuning and Optimization
5. Data Driven Insights

## Models Used
> - Linear Regression
    > A simple model to predict the dependent variable based on the independent variable by fitting a line
> - Random Forest
    > A classification algorithm that involves many decision trees, using bagging and feature randomness to build each tree
> - XGBoost
    > An implmentation of gradient-boosting decision trees. It uses a gradient descent algorithm to minimize the loss function and it includes regularization techniques to avoid overfitting.

## Conclusion
- Price of diamonds can reliably be predicted using their attributes
- XGBoost is the best model we found to predict price
- Main variables that affect price: carat weight, cut, lab certificate
- Color, culet size, and cut quality is irrelevant to predict diamond price

## What We Have Learnt From this Project
- How to handle missing values using imputation
- Types of visualizations to better understand relationship between variables
- Encoding numerical variables to get better results
- Handling random forest and XGBoost models along with their parameters
- Hyperparametric tuning and how to choose the parameters
- How to use GitHub and markdown syntax

## References

1. 123dartist. (n.d.). Luxury Shinning Diamond Balanced on Rippled Water Surface with Reflected Sky Background, Diamond Wallpaper, [Image]. Adobe Stock. https://stock.adobe.com/sg/images/luxury-shinning-diamond-balanced-on-rippled-water-surface-with-reflected-sky-background-diamond-wallpaper/452760672?prev_url=detail
2. How to Deal with Missing Data. (n.d.). Master’s in Data Science. https://www.mastersindatascience.org/learning/how-to-deal-with-missing-data/
3. Upgrade Your Diamond. (n.d.). Long Jewelers. https://www.longjewelers.net/Upgrade-Your-Diamond/3001108/EN
4. HROKR. (2023). The largest diamond dataset currently on Kaggle. Kaggle. https://www.kaggle.com/code/hrokrin/kaggle-s-largest-dataset-of-diamonds-eda
5. Kulkarni, M. (n.d.).  *Machine Learning Notebook*.  GitHub. https://github.com/maykulkarni/Machine-Learning-Notebooks/tree/master/02.%20Regression 
6. Yiu, T. (2019). *Understanding Random Forest*. Towards Data Science. https://towardsdatascience.com/understanding-random-forest-58381e0602d2
7. *What is linear regression?* (n.d.). IBM. 
https://www.ibm.com/topics/linear-regression#:~:text=Resources-,What%20is%20linear%20regression%3F,is%20called%20the%20independent%20variable.
9. Brownlee, J. (2016). *A Gentle Introduction to XGBoost for Applied Machine Learning*. Machine Learning Mastery.
https://machinelearningmastery.com/gentle-introduction-xgboost-applied-machine-learning/
