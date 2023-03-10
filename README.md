# Data-analysis-algorithm
# 1. Linear regression algorithm. Gradient descent
Tasks to be solved: Select the learning rate (alpha) and the number of iterations; Instead of setting the number of iterations, set the condition for stopping the algorithm when the error per iteration begins to change below a certain threshold — a simplified analogue of the tol parameter in linear regression in sklearn.
# 2. Scaling of features. L1- and L2-regularization. Stochastic gradient descent
Tasks to be solved: Plot the dependence of the weights of all features on lambda in L2-regularization based on the data from the lesson; Is it possible to apply both normalization and standardization to the same feature at once?; Write a function like eval_model_reg2, but for the application of L1-regularization.
# 3. Logistic regression. Log Loss
Tasks to be solved: Change the calc_logloss function so that zeros, if possible, do not fall into np.log; Select the arguments of the eval_model function for logistic regression so that log loss is minimal; Create a calc_pred_proba function that returns the predicted probability of class 1. The input is W, which has already been calculated by the eval_model function, and X, on the output is the y_pred_proba array; Create a calc_pred function that returns the predicted class. The input is W, which has already been calculated by the eval_model function, and X, the output is an array y_pred; Calculate Accuracy, error matrix, accuracy and completeness, as well as F1 score; Could the model retrain? Why?
# 4. Algorithm for building a decision tree
Tasks to be solved: In the code from the manual, implement one or more stop criteria (number of leaves, tree depth, etc.); For the classification problem, train the decision tree using the Gini and Entropy partitioning criteria. Compare the quality of the classification, draw conclusions.
# 5. Random Forest
Tasks to be solved: Using sklearn.make_classification to form a dataset of 1000 objects with two attributes; Train a random forest of 1, 3, 10, 50, 100 and 200 trees (based on the implementation of the construction of this algorithm from the lesson); Visualize their dividing lines on graphs (similar to the visualization of trees from the previous lesson, it is only necessary to replace the call of the predict function with tree_vote);To draw conclusions about the resulting complexity of the hyperplane and the lack of training or retraining of a random forest, depending on the number of trees in it; In the implemented algorithm, replace the delayed sampling check with an Out-of-Bag.
# 6. Gradient boosting (AdaBoost)
Tasks to be solved: For the implemented gradient boosting model, plot graphs of the error dependence on the number of trees in the ensemble and on the maximum depth of trees. Draw conclusions about the dependence of the error on these parameters; Modify the implemented algorithm to get stochastic gradient boosting. Take the size of the subsample to be 0.5. Compare the error curves on the test sample on the same graph, depending on the number of iterations.
# 7. Classification using KNN. K-means clustering
The tasks are solved: To the kNN algorithm implemented in the lesson, implement the addition of neighbor weights according to any of the principles shown in the lesson.
# 8. Data dimensionality reduction
Tasks to be solved: Is it possible to select the most significant features using PCA?; Train any classification model on the IRIS dataset before and after the use of PCA. Compare the quality of classification by deferred sampling; Write your own implementation of the principal component method using singular value decomposition using the numpy.linalg.svd() function.
# 9. logistic-regression-binary-classification
The problem of binary classification on Kaggle
