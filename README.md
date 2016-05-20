# Artys-Project---Data-Science
The Repository will house the working files for my General Assembly Project

Initially i thought of using a dataset from the following websi[https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients#]


However I've gone with a dataset I found on credit scoring on the Kaggle website, purely because of the greater number of observations available. The training dataset has 150k observations and the test 100k.

Link [https://www.kaggle.com/c/GiveMeSomeCredit]

Targets are unknown in the test dataset. However in order to assess my model , I will spit my training dataset into a training sample of 100000 training and 50000 test, removing the targets and assessing my model selection in this way.

The winning solution was the one that attained the highest area under the curve.
From Kaggle:
The AUC, which is part of performance metric of a logistic regression, is a commonly used evaluation metric for binary classification problems like predicting a Buy or Sell decision (binary decision). The interpretation is that given a random positive observation and negative observation, the AUC gives the proportion of the time you guess which is correct. It is less affected by sample balance than accuracy. A perfect model will score an AUC of 1, while random guessing will score an AUC of around 0.5, a meager 50% chance on each other.


Structure of this Repo:
Part1 - Context

    1.1 -> Business_Understanding
    
    1.2 -> Data Dictionary
    
Part2 - The Data

    2.1 -> cs-training.csv (Original)
    
    2.2 -> cs-test.csv     (Original)
    
    2.2 -> training.csv    (Pre-Processing - null values imputed) [Check out DataCleaning.ipynb]
    
Part3 - Working Files

    3.1 -> Model Progress
    
    3.2.1 -> 1 - LogisticRegression.ipynb
    
    3.2.2 -> 2 - LDA.ipynb
    
    3.2.3 -> 3 - CARTS.ipynb
    
    
    
[Read more words!](docs/1_Data_Understanding.ipynb)

### TODO

- [x] Linear Discriminant Analysis
- [x] Logistic Regression
- [x] Classification and Regression Trees
- [x] Random Forests
- [x] Gradient Boosting 
- [ ] Support Vector Machines
- [ ] Neural Network




