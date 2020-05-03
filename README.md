# bank_decision_tree_R

Objectives: Can we predict whether client subscribed a term deposit using these features?

Model I use: Decision tree ("C50" package)

Data preprocessing:
  1. detect missing values and find no missing value
  2. figure out label (y) is imbalanced and use "ROSE" package to resample data

Hyper-parameter Tuning:
  How many trials we need to fill in?

After we run decision tree and fit test set into model, accuracy is 0.859 and AUC is about 0.767 and therefore the model performance is not bad.

--------------------------------------------------------------------------------------------------------------------------------------
Business Insight:
1. If there is a new customer, we can predict whether this customer will subscribe product based on this model
2. We can understand which variables are most important to classify whether customers will subscribe products and therefore we can find more customers who have good performance on those important variables and company can target customers efficiently.
