# Stock-Return-Prediction-Model-using-Machine-Learning
## Inspiration
Interest in finance and a basic understanding in Machine Learning concepts which we looked to further.

## What it does
It generates a model of high accuracy after having been tested and ran several times using the LightGBM Model

## How we built it
We investigated various methods to optimise accuracy in stock prediction. Initially, we began with exploring the dataset provided. Following this, we began to consider the variables algorithms used in tackling classification problems using Machine Learning. This included looking at logistic regression, decision trees, random forests and gradient boosted models. Our main improvement came from feature engineering using an 80/20 split to cross-validate our predictions.

## Challenges we ran into
We began feature engineering on our RandomForest Model however with such a large dataset this was very slow (approx 30 mins each time we ran it). Therefore, we aimed to use LightGBM which runs quicker however this was initially difficult to implement. Although eventually, despite the vast array of modelling parameters, we got this working. 

## Accomplishments that we're proud of
Being able to improve on the benchmark accuracy of 51.31% by 0.38% to get to a 51.69% accuracy, which we would predict to be profitable if it were to be used to trade real stocks. We were also proud of getting the LGBM model to work and being able to combine the LGBM and RandomForestClassifier.

## What we learned
We have learned how to use new packages to implement Machine Learning models - random forest and lightgbm. We also practised finding good signals in the data despite the noise. We did this through observing changes in accuracy and making changes accordingly, given the split to cross-validate.

## What's next for LightGBM Stock Return Prediction Model
The model can be further improved and developed by testing more factors to find better signals and add a logistic regression model as well.
