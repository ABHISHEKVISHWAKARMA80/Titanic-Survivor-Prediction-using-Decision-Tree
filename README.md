# Titanic-Survivor-Prediction-using-Decision-Tree

Developed a model based on data collected to predict whether a given passenger will survive or not.

# Data Description

Dataset Consist of two files "Train.csv" and "Test.csv". I have trained the model on 'Train.csv' and predict the output on 'Test.csv'.

# Data Dictionary

Variable      Definition          Key
------------------------------------------------------------------
survival:         Survival           0 = No, 1 = Yes

pclass:          Ticket class   1 = 1st, 2 = 2nd, 3 = 3rd

sex:                  Sex   

Age:                 Age in years   

sibsp:        # of siblings / spouses aboard the Titanic  

parch:        # of parents / children aboard the Titanic  

ticket:        Ticket number   

fare:            Passenger fare  

cabin:         Cabin number   

embarked:    Port of Embarkation    C = Cherbourg, Q = Queenstown, S = Southampton

# Variable Notes

pclass : A proxy for socio-economic status (SES)

1st = Upper

2nd = Middle

3rd = Lower

age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

sibsp: The dataset defines family relations in this way…

Sibling = brother, sister, stepbrother, stepsister

Spouse = husband, wife (mistresses and fiancés were ignored)

parch: The dataset defines family relations in this way…

Parent = mother, father

Child = daughter, son, stepdaughter, stepson

Some children traveled only with a nanny, therefore parch=0 for them.

# What I did in "prediction.ipynb"

firstly, I have dropped the column/data which is not required for the prediction(for example name, address, etc.). then I filled the missing values, finally applied the decision tree method using sklearn.

# Decision Tree

Decision tree is a type of supervised learning algorithm that can be used in both regression and classification problems (mostly used for classification problems). It works for both categorical and continuous input and output variables.

# why decision tree for this problem

a) Decision trees can handle multidimensional data.

b) It works for both categorical and continuous input and output variables.

c) Decision tree construction does not involve any domain knowledge or parameter setting, and therefore is appropriate for exploratory knowledge discovery.

Disadvantages of decision trees: They are unstable, meaning that a small change in the data can lead to a large change in the structure of the optimal decision tree.
