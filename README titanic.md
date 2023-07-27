# Titanic Survival Prediction

Based on the sinking of the RMS Titanic, that ended up killing 1502 out of 2224 passengers and crew. One of the reasons for such loss was that there were not enough lifeboats for the passengers and crew. Some groups of people were more likely to survive than others. In this challenge you are requested to **analyse** data applying *machine learning* and **predict** which passenger survived the tragedy.

## Models Implemented

Right now we have implemented 9 *Machine Learning* models.

1)Logistic Regression

2)SVM

3)KNN

4)Naive Bayes

5)Decision Tree

## Data Insights

Here are some insights we had analysing the Data.
- Pclass, Sex, Cabin and Embarked are **Categorical _features_**.
- Comparing *Genders*, Females are way more likely to survive.
- The fares didn't contribute much to the model
- We decided to unite Age and Pclass due to the correlation with results
- Names are unique in the dataset, so they are useless without preprocessing
- Dividing age *feature* by groups is important to improve Machine Learning performance. 
