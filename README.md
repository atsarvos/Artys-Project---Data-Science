# Artys-Project---Data-Science
The Repository will house the working files for my General Assembly Project

Initially i thought of using a dataset from the following websi[https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients#]


However I've gone with a dataset I found on credit scoring on the Kaggle website, purely because of the greater number of observations available. The training dataset has 150k observations and the test 100k.



Link [https://www.kaggle.com/c/GiveMeSomeCredit]

Targets are unknown in the test dataset. However in order to assess my model , I will spit my training dataset into a training sample of 100000 training and 50000 test, removing the targets and assessing my model selection in this way.

The winning solution was the one that attained the highest area under the curve.
From Kaggle:
The AUC, which is part of performance metric of a logistic regression, is a commonly used evaluation metric for binary classification problems like predicting a Buy or Sell decision (binary decision). The interpretation is that given a random positive observation and negative observation, the AUC gives the proportion of the time you guess which is correct. It is less affected by sample balance than accuracy. A perfect model will score an AUC of 1, while random guessing will score an AUC of around 0.5, a meager 50% chance on each other.


