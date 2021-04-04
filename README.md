# GridSearchKNN_CaseStudy:
Grid Search Hyperparameter optimization of K-nearest neighbors and Random Forests. 
There are four main steps of Hyperparameter optimization, using a Grid Search: 
# 1 param_grid = {'n_neighbors':np.arange(1,50)} - Choose the correct "param_grid" (Random forest parameters are more extensive),
# 2 knn = KNeighborsClassifier() -- Instantiate the K-Nearest Neighbors Classifier,
# 3 knn_cv= GridSearchCV(knn,param_grid,cv=5) -- Perform a Grid Search, either Random and Exhaustive; Choose the number of folds for Cross Validation,
# 4 knn_cv.fit(X,y) -- Fit the data: X is the data, y is the target.
