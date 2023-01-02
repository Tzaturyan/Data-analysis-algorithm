# Data-analysis-algorithm
# 1. Linear regression algorithm. Gradient descent
Tasks to be solved: Select the learning rate (alpha) and the number of iterations; Instead of setting the number of iterations, set the condition for stopping the algorithm when the error per iteration begins to change below a certain threshold — a simplified analogue of the tol parameter in linear regression in sklearn.
# 2. Scaling of features. L1- and L2-regularization. Stochastic gradient descent
Tasks to be solved: Plot the dependence of the weights of all features on lambda in L2-regularization based on the data from the lesson; Is it possible to apply both normalization and standardization to the same feature at once?; Write a function like eval_model_reg2, but for the application of L1-regularization.
# 3. Logistic regression. Log Loss
Tasks to be solved: Change the calc_logloss function so that zeros, if possible, do not fall into np.log; Select the arguments of the eval_model function for logistic regression so that log loss is minimal; Create a calc_pred_proba function that returns the predicted probability of class 1. The input is W, which has already been calculated by the eval_model function, and X, on the output is the y_pred_proba array; Create a calc_pred function that returns the predicted class. The input is W, which has already been calculated by the eval_model function, and X, the output is an array y_pred; Calculate Accuracy, error matrix, accuracy and completeness, as well as F1 score; Could the model retrain? Why?
# 4. Algorithm for building a decision tree
Tasks to be solved: In the code from the manual, implement one or more stop criteria (number of leaves, tree depth, etc.); For the classification problem, train the decision tree using the Gini and Entropy partitioning criteria. Compare the quality of the classification, draw conclusions.
