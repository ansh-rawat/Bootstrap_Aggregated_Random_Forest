# Applying Bootstrap Aggregated Random Forest

Bootstrap Aggregation or Bagging is one of the Ensemble techniques in which overall variance of a model is reduced by combining several weak learners (often with low bias and high variance).  
Random Forest is one of the popular algorithm which operates on the concept of bagging. A number of decision trees are trained on sub-sample datasets which are then combined together to get the best predictions.   

To learn more about Bagging and other Ensembles go through the following links:  
https://www.ibm.com/cloud/learn/bagging  
https://towardsdatascience.com/ensemble-methods-bagging-boosting-and-stacking-c9214a10a205

In the .ipynb I've implemented Bootstrap Aggregated Random Forest using custom functions without using sklearn's RandomForestRegressor and calculated the Mean Square Error and Out of Bag score. OOB Score: https://towardsdatascience.com/what-is-out-of-bag-oob-score-in-random-forest-a7fa23d710  
The notebook is self explanatory and well documented with examples.  

I've used Boston dataset for this implementation. The dataset has Boston housing prices. This dataset is already available in scikit-learn library.  
Link: https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_boston.html  
