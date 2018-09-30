# ML

ML scripts in Python Jupyter notebook
## (1) Boston_housing: ##
- The project uses supervised learning algorithms to train models with Boston Housing dataset in order to make prediction of prices for clients who intend to purchase houses.
Dataset: Boston Housing Prices and Features (e.g. numbers of rooms, student-to-teacher ratios, etc.) from Kaggle
Project steps brief summary: 
1) Load Dataset
2) Training and testing data splitting
3) Train model using DecisionTreeRegressor
4) Evaluate the model with GridSearchCV cross validation
5) Make prediction
6) Justify if more features should be included.


## (2) Find_donors: ##
- Project steps:
1) Evaluate three classifiers (e.g. SVC, Statistical Gradient Descent classifier, essemble methods-adaboost, logistic regression, etc.) by training the models with training data and computing accuracy_score and f0.5_score for model performance on training data and testing data. 
2) The best model is selected based on computing time, and model performance (accuracy_score, f0.5_score). 
3) After best model selected, GridSearchCV is used for hyperparameter tuning and model optimization. 

## (3) Create customer segments
-Unsupervised learning problem (e.g. hierarchical clustering, Gaussian Mixture Models, complete- and average-link clustering, etc.)
- Project steps:
1) Data Preprocessing: log transform, outlier detection (points falling out of 1.5 IQR and reasonably remove a few)
2) PCA: dimensionality reduction.
3) Clustering: K-Means v.s. GaussianMixture Model; use of Silhouette score as evaluation metrics.
4) Visualizaton, Prediction: pca.inverse_transform for centers of clusters, predict selected samples and compare with raw data.
