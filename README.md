# F1 prediction
- This is an application used for predicting result of F1 Racings through which round, driver and start position of that driver

We use the Random Forest Classifier to solve this exercise


## Random Forest Classifier
- A random forest classifier.
- A random forest is a meta estimator that fits a number of decision tree classifiers on various sub-samples of the dataset and uses averaging to improve the predictive accuracy and control over-fitting. Trees in the forest use the best split strategy, i.e. equivalent to passing splitter="best" to the underlying DecisionTreeRegressor. The sub-sample size is controlled with the max_samples parameter if bootstrap=True (default), otherwise the whole dataset is used to build each tree.
- For a comparison between tree-based ensemble models see the example Comparing Random Forests and Histogram Gradient Boosting models.
- We use this model to train the data after preprocessing and cleaning data
- Learn more about this model: [https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)


## Data Crawling
We crawl data from:
- Ergast API: [https://ergast.com/mrd/](https://ergast.com/mrd/)
- Wikipedia: [https://www.wikipedia.org/](https://www.wikipedia.org/)
