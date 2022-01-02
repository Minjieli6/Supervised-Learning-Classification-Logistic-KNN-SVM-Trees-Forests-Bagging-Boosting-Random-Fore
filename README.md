# Goal
Build and evaluate tree-based models for classification 

# Data
https://www.kaggle.com/fedesoriano/company-bankruptcy-prediction

# Steps:
1. Split the training set into an 80% training and 20% validation set and conduct
2. Build SVM, logistic regression, Naïve Bayes models 
3. Build Random Forest Classifier, Gradient Boosted Trees, Extra Trees
4. Conduct hyperparameter tuning of n_estimators (number of trees), max_features (maximum features considered for splitting a node), max_depth (maximum number of levels in each tree), splitting criteria (entropy or gini)
5. Evaluate goodness of fit metrics including TPR, FPR, precision, recall, and accuracy on the training and validation sets. Build ROC and Precision / Recall graphs. 
6. Evaluate your models' performance on the validation set using the F1-score.  Python scikit-learn should be your primary environment for conducting this research.

# Code:
- [Jupyter](https://github.com/Minjieli6/Supervised-Learning-Classification-logistic-KNN-SVM-Trees-Forests-Bagging-Boosting-Random-Fore/blob/main/Supervised_Learning_Classification_Company_Bankruptcy.ipynb)
- [HTML](https://htmlpreview.github.io/?https://github.com/Minjieli6/Supervised-Learning-Classification-logistic-KNN-SVM-Trees-Forests-Bagging-Boosting-Random-Fore/blob/main/Supervised_Learning_Classification_Company_Bankruptcy.html)

# Source:
- James, Gareth, Daniela Witten, Trevor Hastie, and Robert Tibshirani. (2013). An Introduction to Statistical Learning. New York: Springer.
- Geron, Aurelien. (2019). Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems. 2nd ed. Sebastopol, CA: O'Reilly.
