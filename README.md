# machine-learning
Machine Learning mini-projects

Linear_Regression
* visualized relationships between dependent and independent variables
* explored implementations in statsmodels and sklearn
* plotted residuals and judged performance with mean squared error
* used 4-fold cross validation

Logistic_Regression
* visualized features and target relationships
* conducted cross-validated gridsearch with custom and sklearn's implementations
    - identified and selected opitmal C regularization parameter, based on mean accuracy score
* perfromance was comparable with a slight edge to the sklearn implementation

Clustering
* Customer Segmentation 
* clustered customer purchases based on marketing sale campaigns for different wine varietys
* explored different methods for choosing k in k-Means clustering
* Using PCA, performed dimensionality reduction of customer orders
* Visualized data, clusters, PCA components, and associated metrics
* tested a variety of other cluster algorithms in scikit-learn

Naive_Bayes
* vectorize critics' reviews into a bag of words model
* train a naive bayes algorithm on the bag of words training data
* binary prediction of fresh or rotten for test data

Recommendation_system
* explored collaborative filtering algorithms
* built a system using Python classes
* predicted movie ratings from similar users 
    * based on their zip code
    * based on similarity measures of their ratings
        * cosine, pearson, and jaccard
