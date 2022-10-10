# Kaggle Titanic Problem

The Problem: https://www.kaggle.com/competitions/titanic/overview

## Checklist

- [x] Identify the problem
      The problem here is to be able to predict whether a person has survived or not depending on some information about him/her.
- [x] The data
      The data is from teh kaggle competition and can be found [here](https://www.kaggle.com/competitions/titanic/data)
- [ ] Data exploration
      Explore the data to understand how the data is and how features relate to each other. This also helps in model selection and knowing which type of model is best for the problem.
- [ ] Data preparation
      Encoding and scaling the data. Preparing the data and putting it in the right form for the models to work with.
- [ ] Model time
      Train different models and compare their performances. Crosscheck the performances against the problem specifications. Shortlist the best models.
- [ ] Model Improvement
      Fine tune best models and combine them into a better one. Ensemble?
- [ ] Present Solutions
      Test the model on the test set and submit solutions to kaggle for scoring
- [ ] Done!

## Notes on Data Exploration

- 891 Training examples
- We could fill the missing ages with the median value.
- Convert the sex into integer values (encoding)
- Sex is a key feature
- Pclass is an important feature
- Age is not very important
- Most people embarked from port S. So we use that to replace NaN
- SibSp is important
- Parch
