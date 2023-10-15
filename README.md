# DecisionTrees_EnsembleLearning_FX

In this notebook we will compare out of sample accuracy score for predicting positive returns to EURUSD at the daily level. We will use Decision Tree Ensemble Classifiers for our Supervised Learning Task.

* Decision Trees: Sequential decisions, splitting values, to get a result. Checks for feature importance (Gini, AUC, Entropy) to rank trees.
* Bagging (Bootstrap Aggregating): Trains multiple models in parallel on different subsets of the data, using random subsets (with replacement) for each model. Majority voting.
* Random Forrest: bagging based, with random feature selection.
* Boosting: models are built sequentially minimizing the errors from previous models increasing (boosting) high-performing models.
* Gradient Boosting: gradient descendent algorithm to minimize errors in sequential models.
* XGBoost (Extreme Gradient Boosting): optimized stochastic gradient boosting with tree-pruning and regularization.

![EURUSD](https://github.com/manuzrpEd/DecisionTrees_EnsembleLearning_FX/blob/main/EURUSD.png)

# References:

[https://github.com/anujjohri/Decision-Tree-with-bagging-boosting-and-Ensemble-models/blob/master/Decision_tree%20with%20bagging%2C%20boosting%2C%20ensemble%20models.ipynb](https://github.com/anujjohri/Decision-Tree-with-bagging-boosting-and-Ensemble-models/blob/master/Decision_tree%20with%20bagging%2C%20boosting%2C%20ensemble%20models.ipynb)
