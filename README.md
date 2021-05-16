# Assumptions and Findings

### The most accurate model created was a random forest using gridsearch for tuning:

![rf_score](Images/random_forest_model.png)

### The SVM model had a similar accuracy in its predictions:

![svm_score](Images/svm_model.png)

The main difference in these predictions was that the random forest model was able to more accuractely predict confirmed exoplanets with an 83% accuracy as opposed to 77% with the SVM model. Overall, the random forrest model had a better f1-score in all three categories of candidate, confirmed and false positives.

### Feature Importance

![feature_importance](Images/feature_importance.png)
