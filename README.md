# Data Description
   The data has been split into two groups:

    training set (train.csv)
    test set (test.csv)

The training set used to build machine learning model. For the training set, we provide the outcome (also known as the “ground truth”) for each passenger. the model will be based on “features” like passengers’ gender and class. we also use feature engineering to create new features.

The test set used to see how well the model performs on unseen data. For the test set, we do not provide the ground truth for each passenger. It is the job to predict these outcomes. For each passenger in the test set, use the model we trained to predict whether or not they survived the sinking of the Titanic.

We also include gender_submission.csv, a set of predictions that assume all and only female passengers survive, as an example of what a submission file should look like.

# Variable Notes

pclass: A proxy for socio-economic status (SES)
1st = Upper
2nd = Middle
3rd = Lower

age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

sibsp: The dataset defines family relations in this way...

Sibling = brother, sister, stepbrother, stepsister

Spouse = husband, wife (mistresses and fiancés were ignored)

parch: The dataset defines family relations in this way...

Parent = mother, father

Child = daughter, son, stepdaughter, stepson

Some children travelled only with a nanny, therefore parch=0 for them.

# Goal

predict if a passenger survived the sinking of the Titanic or not.

For each in the test set, we must predict a 0 or 1 value for the variable.
