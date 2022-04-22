# Data Description
   The data has been split into two groups:

    training set (train.csv)
    test set (test.csv)

The training set used to build machine learning model. For the training set, we provide the outcome (also known as the “ground truth”) for each passenger. the model will be based on “features” like passengers’ gender and class. we also use feature engineering to create new features.

The test set used to see how well the model performs on unseen data. For the test set, we do not provide the ground truth for each passenger. It is your job to predict these outcomes. For each passenger in the test set, use the model you trained to predict whether or not they survived the sinking of the Titanic.

We also include gender_submission.csv, a set of predictions that assume all and only female passengers survive, as an example of what a submission file should look like.
