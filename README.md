# House-Price-Prediction
![rpOD15e](https://github.com/raisaurabh44/House-Price-Prediction/assets/139812850/043a5df2-863d-4404-93ec-6f9876d6719b)
1 | INTRODUCTION
¶
PROBLEM STATEMENT

There are a large number of factors that can affect the value of a house property (eg. location, size, condition, time), these factors can change quite substantially from one property to another
The housing market itself is quite a volatile industry, and is quite dependent on demand and supply fluctuations, not to even mention economic factors sch as interest rates & inflation, so its quite a challenge to predict the price variation over time
It's also quite challenging to predict housing prices due to the limited data that is available, most datasets contain a limited number of features related to each property, such is why feature engineering is quite important
As a result, it is generally quite difficult to accurately predict property prices that take into account all the factors that influence it
The California housing dataaset contains different house related attributes for properties located in California
STUDY AIM

The aim is to model is to predict the median_house_value which is our target variable
Overcome missing data with a basic unsupervised learning data imputation
Identification of outliers in a dataset
Understand how to turn a simple model into your own sklearn comparible class, our aim won't be to create the most perfect model
NOTEBOOK COVERS

Introduction to basic ML principles such as missing data, scaling, feature engineering, outliers,
A basic introduction to sklearn compatible classes,model exploration & model modification in an attempt to improve our model
MODEL SELECTION

We'll use an existing model; Bayesian Linear Regression in class structure that can be used with sklearn's Pipeline and cross validation options, so we can use it here.

2 | DATA PREPARATION
2.1 | Loading the dataset 
df.info(),describe(),head() are probably one of the first things we might want to inspect having a pandas dataframe; showing feature names, limits/stats and and a few first columns respectively, to get a some initial impression of the data
I have made some minor adjustment to the original dataset and pulled out some random data from all but two coordinate features, so we can do some data imputation, the dataset is located below, even though its not made public.
