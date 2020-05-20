# Credit-card-fault-detection

## Problem Statement:
The Credit Card Fraud Detection Problem includes modeling past credit card transactions with the knowledge of the Apache Spark for the ones that turned out to be fraud. This model is then used to identify whether a new transaction is fraudulent or not. Our aim here is to detect most of the fraudulent transactions while minimizing the incorrect fraud classifications.
Credit card fraud stands as a major problem for world wide financial institutions. 
Annual losses due to it scales to billions of dollars.

Effective credit risk management has gained an increased focus in recent years, largely due to the fact that inadequate credit risk policies are still the main source of serious problems within the banking industry. 
The chief goal of an effective credit risk management policy must be to maximize a bank's risk-adjusted rate of return by maintaining credit exposure within acceptable limits. 
Moreover, banks need to manage credit risk in the entire portfolio as well as the risk in individual credits or transactions. 
This executive summary seeks to investigate how much progress banks are making in the development and deployment of successful credit risk management strategies.

## Approach Taken:
Three algorithms were used:
- Decision tree
- Randomforest 
- Naive Bayes
 #### Decision Tree
Decision Tree algorithm belongs to the family of supervised learning algorithms. Unlike other supervised learning algorithms, the decision tree algorithm can be used for solving regression and classification problems too.

The goal of using a Decision Tree is to create a training model that can use to predict the class or value of the target variable by learning simple decision rules inferred from prior data(training data).

In Decision Trees, for predicting a class label for a record we start from the root of the tree. We compare the values of the root attribute with the record’s attribute. On the basis of comparison, we follow the branch corresponding to that value and jump to the next node.
![Decision Tree](https://github.com/TinaChandwani/Credit-card-fault-detection/blob/master/decision_tree.JPG)

#### Random Forest
Random forest is a supervised learning algorithm which is used for both classification as well as regression. But however, it is mainly used for classification problems. As we know that a forest is made up of trees and more trees means more robust forest. Similarly, random forest algorithm creates decision trees on data samples and then gets the prediction from each of them and finally selects the best solution by means of voting. It is an ensemble method which is better than a single decision tree because it reduces the over-fitting by averaging the result.
![Random Forest](https://github.com/TinaChandwani/Credit-card-fault-detection/blob/master/random_forest.JPG)

#### Naive Bayes
The Naive Bayes algorithm is a supervised machine learning algorithm for classification. It learns the probability of an object with certain features belonging to a particular group. In short, it is a probabilistic classifier. 

The Naive Bayes algorithm is called “naive” because it makes the assumption that the occurrence of a certain feature is independent of the occurrence of other features.
![Naive Bayes](https://github.com/TinaChandwani/Credit-card-fault-detection/blob/master/naive_bayes.JPG)
