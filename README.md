# Predicting house prices in Ames, IA

Here, I took a Kaggle dataset describing house features and their sale price in Ames, Iowa.

The goal was to be able to, based on 80 features of a house, predict the sale price of that house.
For that, I built a number of predictive models and evaluated their performance.
It turned out that the best performing model was Ridge Regression with a test percent error of just 0.602%.

In the python notebook saved here, I go over nearly all the steps in the modelling process in detail. Some of things I did include:
- Dealing with missing/nan values.
- EDA plotting some variables.
- Dealing with outliers.
- Transformation of data.
- Dealing with multicollinearity and using feature selection.
- Training a number of predictive models on the dataset and assessing model performance.
