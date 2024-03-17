
In this practical part, I will use a dataset describing penguins, applying several machine learning algorithms. Here's a summary of the steps and algorithms used:

## Part I: Nearest Neighbors Method for Classification

- Algorithm Used: k-Nearest Neighbors (kNN)
  - Description: The kNN algorithm classifies penguins based on their characteristics by assigning them to the majority class of their k nearest neighbors in the feature space.
  - Optimization: Hyperparameters such as the number of neighbors (k) were optimized using cross-validation with GridSearchCV.

## Part II: Nearest Neighbors Regression

- Algorithm Used: k-Nearest Neighbors (kNN) Regression
  - Description: The kNN regression algorithm predicts certain features of penguins based on the values of other features by averaging the target values of its k nearest neighbors.
  - Optimization: Hyperparameters such as the number of neighbors (k) were optimized using cross-validation with GridSearchCV.

## Part III: Logistic Regression

- Algorithm Used: Logistic Regression
  - Description: Logistic regression models the probability of a penguin belonging to a certain class (species) based on its features using a logistic function.
  - Evaluation: The data was split into k-folds for model evaluation and performance assessment.

## Part IV: Support Vector Machine (SVM)

- Algorithm Used:
  1. Linear SVM (Support Vector Machine)
    - Description: Linear SVM separates penguins into different species using a linear decision boundary in the feature space.
  2. Non-Linear SVM (Radial Basis Function RBF)
    - Description: Non-linear SVM uses a radial basis function kernel to transform the feature space into a higher-dimensional space, allowing for non-linear decision boundaries.
  - Optimization: The SVM algorithms were applied with different kernels and their hyperparameters were tuned for optimal performance.

These steps ,ressults and the corresponding codes are provided in the notebook.

