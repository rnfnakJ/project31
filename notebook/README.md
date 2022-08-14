# Data Science for All by Correlation One - Project 31
# Summer 2022 Cohort

## Objective
To analyze determinants of abortion bans in US states

## Data : Abortion Status Classification

Data Source
* The Guttmacher Institute 
* Wikipedia
* US CDC
* The Pew Research Center

Key Features

* State population
* Number of pregnancies
* Number of abortions
* Abortion ban status  
* 913 observations, 1988-2017

## Unsupervised Learning Model 

The abortion dataset had 99 features including pregnancy rate, birth rate, abortion ratio and miscarriages. The PCA and K-Means model was used to reduce overfitting and model training time by decreasing the number of
features. Both models show 4 clusters of 99 different features are optiomal. 

## Supervised Learning Model 


For Decision Tree model, cross validation methodology was used to improve accuracy in prediction. This model correctly identified the likelihood of abortion bans based on selected features with 93% accuracy. Of these features, the state of residence was a dominant factor. The second most important feature was the abortion ratio among women aged 18 to 19 years, followed by the pregancy and birth rates of women aged 30 to 34 years.
