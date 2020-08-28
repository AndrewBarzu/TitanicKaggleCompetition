# TitanicKaggleCompetition
Notebook with my code for the titanic competition on kaggle

The notebook contains a handwritten model, using an Adam optimizer (also handwritten) using only numpy.

The model is very versatile, and it permits changes to all of the hyperparameters. 

It also uses L2 regularization, if that's needed. More details are found in the notebook's comments!

## Algorithms and concepts practiced:

* L2 regularization
* Feature scaling (mean normalization and standardization)
* Adam optimization
* Feature engineering (created new features from existing features, such as the different titles from the names, or the family size, and removed not needed features, that were either not relevant enough for the problem or had large amounts of missing data)
* Correlation checking, using the seaborne library for a heatmap.
* Data visualization (using graphics to see which of the features have a higher impact on survivability)
