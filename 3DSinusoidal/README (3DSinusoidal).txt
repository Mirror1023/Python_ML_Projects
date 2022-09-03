
# Exploring Tree-Based Regression Methods for 3D Sinusoidal Data

The main purpose of this project is to showcase tree-based methods to solve simple regression problems.

I will fit a Gradient-Boosted Regression Tree, a Random Forest, and a Decision Tree to a noisy 3D sinusoidal data set. Since these models can be trained very quickly on the supplied data, I will first manually adjust hyperparameter values and observe their influence on the model's predictions. I  manually sweep the hyperparameter space and try to hone in on the optimal hyperparameter values, again, manually.

However, merely attempting to identify the optimal hyperparameter values is not enough. I will be sure to really get a visceral understanding of how altering a hyperparameter in turn alters the model predictions (i.e. the prediction curve). This is how machine learning intuition is built!

I will also perform several grid searches, to be able to compare my "optimal" hyperparameter values with those computed from the grid search.

I will visualize model predictions for the optimal Gradient-Boosted Regression Tree, a Random Forest, and Decision Tree models that were determined by the grid searches. And finally, I will compute the generalization error on the test set for the three models.